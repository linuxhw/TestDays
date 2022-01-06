EndeavourOS - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | Notebook    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | Notebook    | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [608af1b572](https://linux-hardware.org/?probe=608af1b572) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [56db8627d8](https://linux-hardware.org/?probe=56db8627d8) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| Timi          | A35S                        | Notebook    | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| LattePanda    | Alpha                       | Desktop     | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda    | Alpha                       | Desktop     | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [a4a8130a06](https://linux-hardware.org/?probe=a4a8130a06) | Dec 24, 2021 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [f51d57d3bc](https://linux-hardware.org/?probe=f51d57d3bc) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Unknown       | Intel X79                   | Desktop     | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | Notebook    | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [bc313ce031](https://linux-hardware.org/?probe=bc313ce031) | Dec 15, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [6d5612f136](https://linux-hardware.org/?probe=6d5612f136) | Dec 13, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [fd75c6dc41](https://linux-hardware.org/?probe=fd75c6dc41) | Dec 13, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | Notebook    | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | Notebook    | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | Notebook    | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [8382b9a420](https://linux-hardware.org/?probe=8382b9a420) | Nov 13, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f57c7bbe97](https://linux-hardware.org/?probe=f57c7bbe97) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [ca3c48f689](https://linux-hardware.org/?probe=ca3c48f689) | Oct 30, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [36b667da98](https://linux-hardware.org/?probe=36b667da98) | Oct 29, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | Notebook    | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [8d5149212b](https://linux-hardware.org/?probe=8d5149212b) | Oct 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e37860a101](https://linux-hardware.org/?probe=e37860a101) | Oct 15, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | Notebook    | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | Notebook    | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7f47afdf06](https://linux-hardware.org/?probe=7f47afdf06) | Oct 10, 2021 |
| UMAX          | J42 Nano                    | Desktop     | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | Notebook    | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | Notebook    | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| MSI           | G41M-P33 Combo              | Desktop     | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | Notebook    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | Notebook    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | Notebook    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [c11a70be9e](https://linux-hardware.org/?probe=c11a70be9e) | Sep 24, 2021 |
| Dell          | Precision 3560              | Notebook    | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | Notebook    | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | Notebook    | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Dell          | 0JYH5J A00                  | All in one  | [f05e2951a1](https://linux-hardware.org/?probe=f05e2951a1) | Sep 11, 2021 |
| HP            | 8430 1000                   | All in one  | [56c6d48f6e](https://linux-hardware.org/?probe=56c6d48f6e) | Sep 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| AMI           | Intel                       | Notebook    | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | Notebook    | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | Notebook    | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | Notebook    | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Intel         | DH55HC AAE70933-504         | Desktop     | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [bcd0cff6bb](https://linux-hardware.org/?probe=bcd0cff6bb) | Aug 29, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [292b3048d8](https://linux-hardware.org/?probe=292b3048d8) | Aug 26, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [6b88068dc4](https://linux-hardware.org/?probe=6b88068dc4) | Aug 26, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | Notebook    | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [504260a3f8](https://linux-hardware.org/?probe=504260a3f8) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | Notebook    | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | Desktop     | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| Dell          | Latitude E7440              | Notebook    | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [4c8282bb42](https://linux-hardware.org/?probe=4c8282bb42) | Aug 16, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Gigabyte      | P35-DS3R                    | Desktop     | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [fe3d61f4d6](https://linux-hardware.org/?probe=fe3d61f4d6) | Aug 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell          | 0K240Y A01                  | Desktop     | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| Notebook      | W65_67SZ                    | Notebook    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [1af0342def](https://linux-hardware.org/?probe=1af0342def) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Acer          | Aspire C27-962              | All in one  | [75e1d7295c](https://linux-hardware.org/?probe=75e1d7295c) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [8d7689bceb](https://linux-hardware.org/?probe=8d7689bceb) | Jul 14, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | Notebook    | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | Notebook    | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [81ccc0c89d](https://linux-hardware.org/?probe=81ccc0c89d) | Jun 29, 2021 |
| Dell          | G7 7588                     | Notebook    | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [d3e7a93219](https://linux-hardware.org/?probe=d3e7a93219) | Jun 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [44a7645f10](https://linux-hardware.org/?probe=44a7645f10) | Jun 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [9e238ebb4f](https://linux-hardware.org/?probe=9e238ebb4f) | Jun 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | Notebook    | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | Notebook    | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Dell          | Inspiron 7386               | Convertible | [42442e4d61](https://linux-hardware.org/?probe=42442e4d61) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| Notebook      | NS50MU                      | Notebook    | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | Notebook    | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| HP            | 2B36                        | Desktop     | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| MSI           | GE72 6QD                    | Notebook    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| Dell          | Inspiron 7386               | Convertible | [c6f4d6de84](https://linux-hardware.org/?probe=c6f4d6de84) | May 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | Notebook    | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | Notebook    | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | Notebook    | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| Acer          | Extensa 2510                | Notebook    | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [010a6ef208](https://linux-hardware.org/?probe=010a6ef208) | Apr 14, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [650e9efbab](https://linux-hardware.org/?probe=650e9efbab) | Apr 13, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Toshiba       | Satellite P750              | Notebook    | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | Notebook    | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Dell          | 0080PM A00                  | Desktop     | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo        | 36EB NOK                    | Desktop     | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Dell          | G7 7588                     | Notebook    | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | Notebook    | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [2290f44e04](https://linux-hardware.org/?probe=2290f44e04) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | Notebook    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0debcb68ae](https://linux-hardware.org/?probe=0debcb68ae) | Mar 18, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | Notebook    | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [c7fbd818e8](https://linux-hardware.org/?probe=c7fbd818e8) | Mar 16, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [4983586fe5](https://linux-hardware.org/?probe=4983586fe5) | Mar 12, 2021 |
| Dell          | G5 5505                     | Notebook    | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [04c16e80ba](https://linux-hardware.org/?probe=04c16e80ba) | Mar 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [4b204c80ad](https://linux-hardware.org/?probe=4b204c80ad) | Mar 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [ccd6f06e61](https://linux-hardware.org/?probe=ccd6f06e61) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | Notebook    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | Notebook    | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [4b469e2e7e](https://linux-hardware.org/?probe=4b469e2e7e) | Jan 23, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [7e927a72ec](https://linux-hardware.org/?probe=7e927a72ec) | Jan 21, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [dac6f95caa](https://linux-hardware.org/?probe=dac6f95caa) | Jan 21, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [43b3323a07](https://linux-hardware.org/?probe=43b3323a07) | Jan 18, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [5df2e0f87d](https://linux-hardware.org/?probe=5df2e0f87d) | Jan 06, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | 1905                        | Desktop     | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | EliteBook Revolve 810       | Notebook    | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [8a8d0b8b26](https://linux-hardware.org/?probe=8a8d0b8b26) | Dec 13, 2020 |
| Alienware     | 14                          | Notebook    | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | Notebook    | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | Notebook    | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | Notebook    | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Dell          | Precision M6600             | Notebook    | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | Notebook    | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | 0D4VY1 A00                  | All in one  | [071c584451](https://linux-hardware.org/?probe=071c584451) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [650cf712bb](https://linux-hardware.org/?probe=650cf712bb) | Nov 08, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP            | 8455                        | Desktop     | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HP            | 8455                        | Desktop     | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | Notebook    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Dell          | 0G214D A00                  | Desktop     | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Microsoft     | Surface Laptop              | Tablet      | [26578393cc](https://linux-hardware.org/?probe=26578393cc) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [eab288b1e2](https://linux-hardware.org/?probe=eab288b1e2) | Oct 13, 2020 |
| ASUSTek       | GL702ZC                     | Notebook    | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | Notebook    | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| MSI           | MS-7366                     | Desktop     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| Dell          | G3 3579                     | Notebook    | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [9499adb6fc](https://linux-hardware.org/?probe=9499adb6fc) | Sep 26, 2020 |
| MSI           | MS-7366                     | Desktop     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP            | 1497                        | Desktop     | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| Acer          | TravelMate P633-M           | Notebook    | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [8802aa3282](https://linux-hardware.org/?probe=8802aa3282) | Sep 04, 2020 |
| Dell          | Latitude E6440              | Notebook    | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [8b75181a08](https://linux-hardware.org/?probe=8b75181a08) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | Notebook    | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8790b1b459](https://linux-hardware.org/?probe=8790b1b459) | Aug 12, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [e94f81e5f1](https://linux-hardware.org/?probe=e94f81e5f1) | Aug 12, 2020 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Dell          | Inspiron 5485 2n1           | Convertible | [b6c573f5aa](https://linux-hardware.org/?probe=b6c573f5aa) | Aug 05, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | Notebook    | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | Notebook    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7994cb0fae](https://linux-hardware.org/?probe=7994cb0fae) | Jul 13, 2020 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI           | B450-A PRO MAX              | Desktop     | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1708b21dab](https://linux-hardware.org/?probe=1708b21dab) | Jun 28, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [d0d3d517ef](https://linux-hardware.org/?probe=d0d3d517ef) | Jun 16, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| HP            | EliteBook 8770w             | Notebook    | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | Notebook    | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Notebook      | W65KJ1_KK1                  | Notebook    | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [eb3f07de2a](https://linux-hardware.org/?probe=eb3f07de2a) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d95c487c0a](https://linux-hardware.org/?probe=d95c487c0a) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c75091b3fd](https://linux-hardware.org/?probe=c75091b3fd) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [53dcfb848c](https://linux-hardware.org/?probe=53dcfb848c) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [612f3a46e8](https://linux-hardware.org/?probe=612f3a46e8) | Nov 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [da3b984be5](https://linux-hardware.org/?probe=da3b984be5) | Nov 07, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |
| HP            | Spectre x360 Convertible... | Convertible | [90c646de9c](https://linux-hardware.org/?probe=90c646de9c) | Sep 13, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.15.12-arch1-1    | 16        | 4.18%   |
| 5.15.10-arch1-1    | 9         | 2.35%   |
| 5.15.7-arch1-1     | 8         | 2.09%   |
| 5.14.9-arch2-1     | 8         | 2.09%   |
| 5.13.13-arch1-1    | 8         | 2.09%   |
| 5.11.11-arch1-1    | 8         | 2.09%   |
| 5.9.14-arch1-1     | 7         | 1.83%   |
| 5.9.1-arch1-1      | 6         | 1.57%   |
| 5.7.7-arch1-1      | 6         | 1.57%   |
| 5.15.4-arch1-1     | 6         | 1.57%   |
| 5.7.8-arch1-1      | 5         | 1.31%   |
| 5.15.2-arch1-1     | 5         | 1.31%   |
| 5.14.2-arch1-2     | 5         | 1.31%   |
| 5.14.14-arch1-1    | 5         | 1.31%   |
| 5.12.14-arch1-1    | 5         | 1.31%   |
| 5.9.10-arch1-1     | 4         | 1.04%   |
| 5.7.12-arch1-1     | 4         | 1.04%   |
| 5.15.12-zen1-1-zen | 4         | 1.04%   |
| 5.15.11-arch2-1    | 4         | 1.04%   |
| 5.14.8-arch1-1     | 4         | 1.04%   |
| 5.14.6-arch1-1     | 4         | 1.04%   |
| 5.14.16-arch1-1    | 4         | 1.04%   |
| 5.12.13-arch1-2    | 4         | 1.04%   |
| 5.11.16-zen1-1-zen | 4         | 1.04%   |
| 5.11.16-arch1-1    | 4         | 1.04%   |
| 5.10.88-2-lts      | 4         | 1.04%   |
| 5.10.15-arch1-1    | 4         | 1.04%   |
| 5.9.8-arch1-1      | 3         | 0.78%   |
| 5.9.2-arch1-1      | 3         | 0.78%   |
| 5.8.5-arch1-1      | 3         | 0.78%   |
| 5.8.10-arch1-1     | 3         | 0.78%   |
| 5.7.6-arch1-1      | 3         | 0.78%   |
| 5.15.8-arch1-1     | 3         | 0.78%   |
| 5.15.6-zen2-1-zen  | 3         | 0.78%   |
| 5.14.7-arch1-1     | 3         | 0.78%   |
| 5.13.9-arch1-1     | 3         | 0.78%   |
| 5.13.12-arch1-1    | 3         | 0.78%   |
| 5.13.10-arch1-1    | 3         | 0.78%   |
| 5.12.5-zen1-1-zen  | 3         | 0.78%   |
| 5.12.5-arch1-1     | 3         | 0.78%   |
| 5.12.15-arch1-1    | 3         | 0.78%   |
| 5.11.8-arch1-1     | 3         | 0.78%   |
| 5.11.6-arch1-1     | 3         | 0.78%   |
| 5.10.16-arch1-1    | 3         | 0.78%   |
| 5.10.11-arch1-1    | 3         | 0.78%   |
| 5.9.9-arch1-1      | 2         | 0.52%   |
| 5.9.13-arch1-1     | 2         | 0.52%   |
| 5.9.12-arch1-1     | 2         | 0.52%   |
| 5.8.8-arch1-1      | 2         | 0.52%   |
| 5.8.5-zen1-1-zen   | 2         | 0.52%   |
| 5.8.14-arch1-1     | 2         | 0.52%   |
| 5.8.12-arch1-1     | 2         | 0.52%   |
| 5.8.11-arch1-1     | 2         | 0.52%   |
| 5.7.10-arch1-1     | 2         | 0.52%   |
| 5.4.2-arch1-1      | 2         | 0.52%   |
| 5.15.6-arch2-1     | 2         | 0.52%   |
| 5.15.4-zen1-1-zen  | 2         | 0.52%   |
| 5.15.2-zen1-1-zen  | 2         | 0.52%   |
| 5.14.9-lqx4-1-lqx  | 2         | 0.52%   |
| 5.14.8-zen1-1-zen  | 2         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.12 | 23        | 6.01%   |
| 5.13.13 | 12        | 3.13%   |
| 5.14.9  | 10        | 2.61%   |
| 5.15.7  | 9         | 2.35%   |
| 5.15.4  | 9         | 2.35%   |
| 5.15.10 | 9         | 2.35%   |
| 5.11.11 | 9         | 2.35%   |
| 5.9.1   | 8         | 2.09%   |
| 5.15.2  | 8         | 2.09%   |
| 5.12.13 | 8         | 2.09%   |
| 5.11.16 | 8         | 2.09%   |
| 5.9.14  | 7         | 1.83%   |
| 5.8.5   | 7         | 1.83%   |
| 5.7.7   | 6         | 1.57%   |
| 5.15.6  | 6         | 1.57%   |
| 5.14.8  | 6         | 1.57%   |
| 5.14.2  | 6         | 1.57%   |
| 5.14.14 | 6         | 1.57%   |
| 5.12.5  | 6         | 1.57%   |
| 5.12.14 | 6         | 1.57%   |
| 5.9.8   | 5         | 1.31%   |
| 5.7.8   | 5         | 1.31%   |
| 5.7.12  | 5         | 1.31%   |
| 5.15.11 | 5         | 1.31%   |
| 5.14.6  | 5         | 1.31%   |
| 5.13.4  | 5         | 1.31%   |
| 5.10.88 | 5         | 1.31%   |
| 5.9.10  | 4         | 1.04%   |
| 5.8.10  | 4         | 1.04%   |
| 5.14.16 | 4         | 1.04%   |
| 5.13.9  | 4         | 1.04%   |
| 5.13.12 | 4         | 1.04%   |
| 5.13.10 | 4         | 1.04%   |
| 5.12.15 | 4         | 1.04%   |
| 5.10.15 | 4         | 1.04%   |
| 5.9.2   | 3         | 0.78%   |
| 5.8.14  | 3         | 0.78%   |
| 5.8.12  | 3         | 0.78%   |
| 5.7.6   | 3         | 0.78%   |
| 5.15.8  | 3         | 0.78%   |
| 5.15.0  | 3         | 0.78%   |
| 5.14.7  | 3         | 0.78%   |
| 5.14.15 | 3         | 0.78%   |
| 5.14.11 | 3         | 0.78%   |
| 5.13.7  | 3         | 0.78%   |
| 5.12.4  | 3         | 0.78%   |
| 5.12.1  | 3         | 0.78%   |
| 5.11.8  | 3         | 0.78%   |
| 5.11.6  | 3         | 0.78%   |
| 5.11.15 | 3         | 0.78%   |
| 5.11.14 | 3         | 0.78%   |
| 5.10.16 | 3         | 0.78%   |
| 5.10.11 | 3         | 0.78%   |
| 5.9.9   | 2         | 0.52%   |
| 5.9.13  | 2         | 0.52%   |
| 5.9.12  | 2         | 0.52%   |
| 5.9.0   | 2         | 0.52%   |
| 5.8.8   | 2         | 0.52%   |
| 5.8.11  | 2         | 0.52%   |
| 5.7.10  | 2         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 74        | 20%     |
| 5.14    | 51        | 13.78%  |
| 5.12    | 38        | 10.27%  |
| 5.10    | 37        | 10%     |
| 5.9     | 36        | 9.73%   |
| 5.11    | 36        | 9.73%   |
| 5.13    | 35        | 9.46%   |
| 5.8     | 24        | 6.49%   |
| 5.7     | 21        | 5.68%   |
| 5.4     | 7         | 1.89%   |
| 5.6     | 5         | 1.35%   |
| 5.5     | 2         | 0.54%   |
| 4.19    | 2         | 0.54%   |
| 5.2     | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 342       | 99.71%  |
| aarch64 | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 99        | 27.73%  |
| GNOME           | 86        | 24.09%  |
| XFCE            | 75        | 21.01%  |
| KDE             | 22        | 6.16%   |
| X-Cinnamon      | 18        | 5.04%   |
| i3              | 10        | 2.8%    |
| Unknown         | 10        | 2.8%    |
| Cinnamon        | 9         | 2.52%   |
| Budgie          | 8         | 2.24%   |
| sway            | 4         | 1.12%   |
| MATE            | 4         | 1.12%   |
| LXQt            | 4         | 1.12%   |
| Deepin          | 3         | 0.84%   |
| awesome         | 3         | 0.84%   |
| herbstluftwm    | 1         | 0.28%   |
| GNOME Flashback | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 280       | 79.55%  |
| Wayland | 56        | 15.91%  |
| Unknown | 8         | 2.27%   |
| Tty     | 7         | 1.99%   |
| Web     | 1         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 90        | 25.57%  |
| Unknown | 80        | 22.73%  |
| LightDM | 79        | 22.44%  |
| GDM     | 55        | 15.63%  |
| TDM     | 48        | 13.64%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 168       | 48.98%  |
| en_GB   | 30        | 8.75%   |
| de_DE   | 22        | 6.41%   |
| en_CA   | 14        | 4.08%   |
| it_IT   | 13        | 3.79%   |
| fr_FR   | 10        | 2.92%   |
| en_IN   | 8         | 2.33%   |
| Unknown | 8         | 2.33%   |
| pl_PL   | 6         | 1.75%   |
| ru_RU   | 5         | 1.46%   |
| pt_BR   | 5         | 1.46%   |
| en_AU   | 5         | 1.46%   |
| nl_NL   | 4         | 1.17%   |
| es_ES   | 4         | 1.17%   |
| es_AR   | 4         | 1.17%   |
| en_NZ   | 4         | 1.17%   |
| tr_TR   | 3         | 0.87%   |
| sv_SE   | 3         | 0.87%   |
| es_MX   | 3         | 0.87%   |
| en_DK   | 3         | 0.87%   |
| pt_PT   | 2         | 0.58%   |
| en_PH   | 2         | 0.58%   |
| de_AT   | 2         | 0.58%   |
| cs_CZ   | 2         | 0.58%   |
| sl_SI   | 1         | 0.29%   |
| sk_SK   | 1         | 0.29%   |
| ru_UA   | 1         | 0.29%   |
| nl_BE   | 1         | 0.29%   |
| hr_HR   | 1         | 0.29%   |
| fi_FI   | 1         | 0.29%   |
| es_GT   | 1         | 0.29%   |
| es_CR   | 1         | 0.29%   |
| en_ZA   | 1         | 0.29%   |
| en_SG   | 1         | 0.29%   |
| en_MY   | 1         | 0.29%   |
| en_FI   | 1         | 0.29%   |
| an_ES   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 240       | 68.77%  |
| BIOS | 109       | 31.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 250       | 72.67%  |
| Btrfs   | 84        | 24.42%  |
| Overlay | 4         | 1.16%   |
| Xfs     | 3         | 0.87%   |
| Unknown | 2         | 0.58%   |
| F2fs    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 241       | 69.25%  |
| Unknown | 82        | 23.56%  |
| MBR     | 25        | 7.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 298       | 86.63%  |
| Yes       | 46        | 13.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 234       | 67.24%  |
| Yes       | 114       | 32.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 77        | 22.45%  |
| ASUSTek Computer    | 60        | 17.49%  |
| Dell                | 38        | 11.08%  |
| Hewlett-Packard     | 35        | 10.2%   |
| Gigabyte Technology | 33        | 9.62%   |
| MSI                 | 26        | 7.58%   |
| Acer                | 14        | 4.08%   |
| Apple               | 11        | 3.21%   |
| ASRock              | 9         | 2.62%   |
| Unknown             | 4         | 1.17%   |
| Microsoft           | 3         | 0.87%   |
| HUAWEI              | 3         | 0.87%   |
| Toshiba             | 2         | 0.58%   |
| Timi                | 2         | 0.58%   |
| Schenker            | 2         | 0.58%   |
| Samsung Electronics | 2         | 0.58%   |
| Notebook            | 2         | 0.58%   |
| Intel               | 2         | 0.58%   |
| Fujitsu             | 2         | 0.58%   |
| Biostar             | 2         | 0.58%   |
| AMI                 | 2         | 0.58%   |
| ZOTAC               | 1         | 0.29%   |
| UMAX                | 1         | 0.29%   |
| TUXEDO              | 1         | 0.29%   |
| TrekStor            | 1         | 0.29%   |
| Razer               | 1         | 0.29%   |
| Positivo            | 1         | 0.29%   |
| Pine Microsystems   | 1         | 0.29%   |
| LG Electronics      | 1         | 0.29%   |
| LattePanda          | 1         | 0.29%   |
| Framework           | 1         | 0.29%   |
| Dynabook            | 1         | 0.29%   |
| Alienware           | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 5         | 1.46%   |
| MSI MS-7C02                                           | 4         | 1.17%   |
| ASUS ROG STRIX X570-E GAMING                          | 4         | 1.17%   |
| Apple MacBookAir7,2                                   | 4         | 1.17%   |
| Unknown                                               | 4         | 1.17%   |
| Lenovo ThinkPad X140e 20BL000BUS                      | 3         | 0.87%   |
| MSI MS-7C84                                           | 2         | 0.58%   |
| MSI MS-7B86                                           | 2         | 0.58%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB                  | 2         | 0.58%   |
| Lenovo IdeaPad FLEX-14API 81SS                        | 2         | 0.58%   |
| HP Pavilion Gaming Laptop 15-cx0xxx                   | 2         | 0.58%   |
| HP ENVY Laptop 13-ba0xxx                              | 2         | 0.58%   |
| HP 255 G7 Notebook PC                                 | 2         | 0.58%   |
| Gigabyte H110M-S2                                     | 2         | 0.58%   |
| Gigabyte B550M AORUS PRO                              | 2         | 0.58%   |
| Gigabyte B550 AORUS ELITE V2                          | 2         | 0.58%   |
| Dell G7 7588                                          | 2         | 0.58%   |
| Biostar G31-M7 TE                                     | 2         | 0.58%   |
| ASUS TUF GAMING X570-PLUS                             | 2         | 0.58%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR                 | 2         | 0.58%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV                 | 2         | 0.58%   |
| ASUS ROG CROSSHAIR VIII DARK HERO                     | 2         | 0.58%   |
| ASUS K30AD_M31AD_M51AD                                | 2         | 0.58%   |
| ZOTAC ZBOXNANO-CI520NANO/CI540NANO                    | 1         | 0.29%   |
| UMAX J42 Nano                                         | 1         | 0.29%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.29%   |
| TrekStor Primebook P14                                | 1         | 0.29%   |
| Toshiba Satellite P750                                | 1         | 0.29%   |
| Toshiba Satellite L50D-B                              | 1         | 0.29%   |
| Timi TM1607                                           | 1         | 0.29%   |
| Timi A35S                                             | 1         | 0.29%   |
| Schenker XMG NEO 15(E20, RTX 20xx)                    | 1         | 0.29%   |
| Schenker XMG FUSION 15 (XFU15L19)                     | 1         | 0.29%   |
| Samsung 500T8A/500S8A/500T9A/500S9A                   | 1         | 0.29%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.29%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.29%   |
| Positivo POS-PIH81DI                                  | 1         | 0.29%   |
| Pine Microsystems Pine64 Pinebook Pro                 | 1         | 0.29%   |
| Notebook W65_67SZ                                     | 1         | 0.29%   |
| Notebook W65KJ1_KK1                                   | 1         | 0.29%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.29%   |
| MSI MS-7C91                                           | 1         | 0.29%   |
| MSI MS-7C75                                           | 1         | 0.29%   |
| MSI MS-7C37                                           | 1         | 0.29%   |
| MSI MS-7A38                                           | 1         | 0.29%   |
| MSI MS-7A34                                           | 1         | 0.29%   |
| MSI MS-7A32                                           | 1         | 0.29%   |
| MSI MS-7850                                           | 1         | 0.29%   |
| MSI MS-7821                                           | 1         | 0.29%   |
| MSI MS-7592                                           | 1         | 0.29%   |
| MSI MS-7366                                           | 1         | 0.29%   |
| MSI Modern 14 B5M                                     | 1         | 0.29%   |
| MSI GT80S 6QE                                         | 1         | 0.29%   |
| MSI GS63VR 6RF                                        | 1         | 0.29%   |
| MSI GP66 Leopard 10UH                                 | 1         | 0.29%   |
| MSI GL75 Leopard 10SDK                                | 1         | 0.29%   |
| MSI GE72 6QD                                          | 1         | 0.29%   |
| MSI Bravo 15 B5DD                                     | 1         | 0.29%   |
| Microsoft Surface Pro 6                               | 1         | 0.29%   |
| Microsoft Surface Laptop                              | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 37        | 10.79%  |
| ASUS ROG                 | 22        | 6.41%   |
| Lenovo IdeaPad           | 16        | 4.66%   |
| Dell Inspiron            | 12        | 3.5%    |
| Dell Latitude            | 9         | 2.62%   |
| Acer Aspire              | 9         | 2.62%   |
| HP ENVY                  | 7         | 2.04%   |
| HP EliteBook             | 7         | 2.04%   |
| Lenovo Yoga              | 6         | 1.75%   |
| HP Laptop                | 5         | 1.46%   |
| Dell Precision           | 5         | 1.46%   |
| ASUS TUF                 | 5         | 1.46%   |
| ASUS All                 | 5         | 1.46%   |
| MSI MS-7C02              | 4         | 1.17%   |
| HP Pavilion              | 4         | 1.17%   |
| Gigabyte X570            | 4         | 1.17%   |
| ASUS PRIME               | 4         | 1.17%   |
| Apple MacBookAir7        | 4         | 1.17%   |
| Unknown                  | 4         | 1.17%   |
| Microsoft Surface        | 3         | 0.87%   |
| Lenovo ThinkCentre       | 3         | 0.87%   |
| Lenovo IdeaCentre        | 3         | 0.87%   |
| HP 255                   | 3         | 0.87%   |
| Gigabyte B550            | 3         | 0.87%   |
| Dell XPS                 | 3         | 0.87%   |
| Dell OptiPlex            | 3         | 0.87%   |
| Toshiba Satellite        | 2         | 0.58%   |
| Schenker XMG             | 2         | 0.58%   |
| MSI MS-7C84              | 2         | 0.58%   |
| MSI MS-7B86              | 2         | 0.58%   |
| Lenovo ThinkBook         | 2         | 0.58%   |
| Lenovo Legion            | 2         | 0.58%   |
| Gigabyte Z97X-Gaming     | 2         | 0.58%   |
| Gigabyte H110M-S2        | 2         | 0.58%   |
| Gigabyte B550M           | 2         | 0.58%   |
| Gigabyte B450M           | 2         | 0.58%   |
| Gigabyte B450            | 2         | 0.58%   |
| Fujitsu CELSIUS          | 2         | 0.58%   |
| Dell G7                  | 2         | 0.58%   |
| Dell G3                  | 2         | 0.58%   |
| Biostar G31-M7           | 2         | 0.58%   |
| ASUS K30AD               | 2         | 0.58%   |
| ASUS ASUS                | 2         | 0.58%   |
| ASRock B550M             | 2         | 0.58%   |
| ASRock B450              | 2         | 0.58%   |
| ZOTAC ZBOXNANO-CI520NANO | 1         | 0.29%   |
| UMAX J42                 | 1         | 0.29%   |
| TUXEDO Pulse             | 1         | 0.29%   |
| TrekStor Primebook       | 1         | 0.29%   |
| Timi TM1607              | 1         | 0.29%   |
| Timi A35S                | 1         | 0.29%   |
| Samsung 500T8A           | 1         | 0.29%   |
| Samsung 340XAA           | 1         | 0.29%   |
| Razer Blade              | 1         | 0.29%   |
| Positivo POS-PIH81DI     | 1         | 0.29%   |
| Pine Microsystems Pine64 | 1         | 0.29%   |
| Notebook W65KJ1          | 1         | 0.29%   |
| Notebook W65             | 1         | 0.29%   |
| MSI Prestige             | 1         | 0.29%   |
| MSI MS-7C91              | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 81        | 23.62%  |
| 2020    | 70        | 20.41%  |
| 2019    | 55        | 16.03%  |
| 2018    | 30        | 8.75%   |
| 2015    | 21        | 6.12%   |
| 2014    | 21        | 6.12%   |
| 2017    | 19        | 5.54%   |
| 2013    | 13        | 3.79%   |
| 2016    | 9         | 2.62%   |
| 2011    | 8         | 2.33%   |
| 2012    | 6         | 1.75%   |
| 2010    | 6         | 1.75%   |
| 2009    | 2         | 0.58%   |
| 2007    | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 195       | 56.85%  |
| Desktop     | 120       | 34.99%  |
| Convertible | 12        | 3.5%    |
| All in one  | 8         | 2.33%   |
| Tablet      | 4         | 1.17%   |
| Mini pc     | 4         | 1.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 342       | 99.71%  |
| Enabled  | 1         | 0.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 343       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 91        | 26.38%  |
| 4.01-8.0    | 81        | 23.48%  |
| 8.01-16.0   | 74        | 21.45%  |
| 32.01-64.0  | 47        | 13.62%  |
| 3.01-4.0    | 32        | 9.28%   |
| 24.01-32.0  | 12        | 3.48%   |
| 64.01-256.0 | 7         | 2.03%   |
| 1.01-2.0    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 102       | 27.57%  |
| 1.01-2.0   | 95        | 25.68%  |
| 4.01-8.0   | 74        | 20%     |
| 3.01-4.0   | 59        | 15.95%  |
| 8.01-16.0  | 18        | 4.86%   |
| 0.51-1.0   | 16        | 4.32%   |
| 16.01-24.0 | 3         | 0.81%   |
| 0.01-0.5   | 2         | 0.54%   |
| 24.01-32.0 | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 179       | 51.14%  |
| 2      | 99        | 28.29%  |
| 3      | 27        | 7.71%   |
| 4      | 24        | 6.86%   |
| 5      | 13        | 3.71%   |
| 0      | 3         | 0.86%   |
| 7      | 2         | 0.57%   |
| 6      | 2         | 0.57%   |
| 9      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 273       | 79.13%  |
| Yes       | 72        | 20.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 289       | 84.26%  |
| No        | 54        | 15.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 81.45%  |
| No        | 64        | 18.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 267       | 77.39%  |
| No        | 78        | 22.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 80        | 23.26%  |
| Germany      | 37        | 10.76%  |
| France       | 18        | 5.23%   |
| Italy        | 17        | 4.94%   |
| Canada       | 15        | 4.36%   |
| UK           | 14        | 4.07%   |
| India        | 12        | 3.49%   |
| Poland       | 11        | 3.2%    |
| Netherlands  | 11        | 3.2%    |
| Brazil       | 11        | 3.2%    |
| Turkey       | 6         | 1.74%   |
| Russia       | 6         | 1.74%   |
| Mexico       | 6         | 1.74%   |
| Australia    | 6         | 1.74%   |
| Sweden       | 5         | 1.45%   |
| Spain        | 5         | 1.45%   |
| Finland      | 5         | 1.45%   |
| Austria      | 5         | 1.45%   |
| Portugal     | 4         | 1.16%   |
| New Zealand  | 4         | 1.16%   |
| Indonesia    | 4         | 1.16%   |
| Greece       | 4         | 1.16%   |
| Belgium      | 4         | 1.16%   |
| Argentina    | 4         | 1.16%   |
| Vietnam      | 3         | 0.87%   |
| Slovenia     | 3         | 0.87%   |
| Denmark      | 3         | 0.87%   |
| Czechia      | 3         | 0.87%   |
| Bahrain      | 3         | 0.87%   |
| Ukraine      | 2         | 0.58%   |
| Switzerland  | 2         | 0.58%   |
| South Korea  | 2         | 0.58%   |
| Romania      | 2         | 0.58%   |
| Philippines  | 2         | 0.58%   |
| Norway       | 2         | 0.58%   |
| Hong Kong    | 2         | 0.58%   |
| Georgia      | 2         | 0.58%   |
| Croatia      | 2         | 0.58%   |
| Thailand     | 1         | 0.29%   |
| Taiwan       | 1         | 0.29%   |
| South Africa | 1         | 0.29%   |
| Slovakia     | 1         | 0.29%   |
| Singapore    | 1         | 0.29%   |
| Saudi Arabia | 1         | 0.29%   |
| Puerto Rico  | 1         | 0.29%   |
| Pakistan     | 1         | 0.29%   |
| Morocco      | 1         | 0.29%   |
| Malaysia     | 1         | 0.29%   |
| Hungary      | 1         | 0.29%   |
| Guatemala    | 1         | 0.29%   |
| Egypt        | 1         | 0.29%   |
| Costa Rica   | 1         | 0.29%   |
| Colombia     | 1         | 0.29%   |
| Bulgaria     | 1         | 0.29%   |
| Bangladesh   | 1         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Montreal                       | 7         | 1.97%   |
| Berlin                         | 7         | 1.97%   |
| Hamburg                        | 4         | 1.12%   |
| Barberton                      | 4         | 1.12%   |
| Warsaw                         | 3         | 0.84%   |
| Turin                          | 3         | 0.84%   |
| Toms River                     | 3         | 0.84%   |
| Sydney                         | 3         | 0.84%   |
| Paris                          | 3         | 0.84%   |
| Moscow                         | 3         | 0.84%   |
| Mesa                           | 3         | 0.84%   |
| Manama                         | 3         | 0.84%   |
| Jacksonville                   | 3         | 0.84%   |
| Frankfurt am Main              | 3         | 0.84%   |
| Amsterdam                      | 3         | 0.84%   |
| Zapopan                        | 2         | 0.56%   |
| Yuma                           | 2         | 0.56%   |
| Villa Ballester                | 2         | 0.56%   |
| Victoria                       | 2         | 0.56%   |
| Toronto                        | 2         | 0.56%   |
| Tbilisi                        | 2         | 0.56%   |
| St Petersburg                  | 2         | 0.56%   |
| Seattle                        | 2         | 0.56%   |
| S??o Paulo                     | 2         | 0.56%   |
| Portland                       | 2         | 0.56%   |
| Ottawa                         | 2         | 0.56%   |
| Orlando                        | 2         | 0.56%   |
| Oldenburg                      | 2         | 0.56%   |
| Milan                          | 2         | 0.56%   |
| Madrid                         | 2         | 0.56%   |
| Llanelli                       | 2         | 0.56%   |
| Leipzig                        | 2         | 0.56%   |
| Ho Chi Minh City               | 2         | 0.56%   |
| Hampstead                      | 2         | 0.56%   |
| Gothenburg                     | 2         | 0.56%   |
| Florence                       | 2         | 0.56%   |
| Essen                          | 2         | 0.56%   |
| Chicago                        | 2         | 0.56%   |
| Central                        | 2         | 0.56%   |
| Brussels                       | 2         | 0.56%   |
| Bengaluru                      | 2         | 0.56%   |
| Bandung                        | 2         | 0.56%   |
| Auckland                       | 2         | 0.56%   |
| Annecy                         | 2         | 0.56%   |
| Ankara                         | 2         | 0.56%   |
| Ålesund                       | 1         | 0.28%   |
| Zurich                         | 1         | 0.28%   |
| Wroclaw                        | 1         | 0.28%   |
| Winnipeg                       | 1         | 0.28%   |
| Windham Center                 | 1         | 0.28%   |
| Wilmington                     | 1         | 0.28%   |
| Wiesbaden                      | 1         | 0.28%   |
| Whittier                       | 1         | 0.28%   |
| Whiteville                     | 1         | 0.28%   |
| West Haddon                    | 1         | 0.28%   |
| Wellington                     | 1         | 0.28%   |
| Washington                     | 1         | 0.28%   |
| Vrbovec                        | 1         | 0.28%   |
| Volketswil / Volketswil (Dorf) | 1         | 0.28%   |
| Vienna                         | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 113       | 171    | 20.25%  |
| WDC                            | 76        | 120    | 13.62%  |
| Seagate                        | 76        | 103    | 13.62%  |
| Toshiba                        | 29        | 35     | 5.2%    |
| Kingston                       | 29        | 46     | 5.2%    |
| Crucial                        | 26        | 39     | 4.66%   |
| SanDisk                        | 21        | 24     | 3.76%   |
| SK Hynix                       | 18        | 19     | 3.23%   |
| Intel                          | 15        | 19     | 2.69%   |
| HGST                           | 15        | 16     | 2.69%   |
| Unknown                        | 11        | 15     | 1.97%   |
| A-DATA Technology              | 10        | 16     | 1.79%   |
| Phison                         | 9         | 10     | 1.61%   |
| Micron Technology              | 8         | 8      | 1.43%   |
| Apple                          | 8         | 9      | 1.43%   |
| KIOXIA                         | 7         | 7      | 1.25%   |
| Hitachi                        | 6         | 6      | 1.08%   |
| Corsair                        | 4         | 4      | 0.72%   |
| Transcend                      | 3         | 3      | 0.54%   |
| SPCC                           | 3         | 3      | 0.54%   |
| PNY                            | 3         | 3      | 0.54%   |
| OCZ                            | 3         | 3      | 0.54%   |
| Maxone                         | 3         | 3      | 0.54%   |
| LITEONIT                       | 3         | 4      | 0.54%   |
| JMicron                        | 3         | 3      | 0.54%   |
| Intenso                        | 3         | 3      | 0.54%   |
| China                          | 3         | 3      | 0.54%   |
| XPG                            | 2         | 2      | 0.36%   |
| WDC WDS                        | 2         | 2      | 0.36%   |
| Solid State Storage Technology | 2         | 2      | 0.36%   |
| Mushkin                        | 2         | 2      | 0.36%   |
| KingSpec                       | 2         | 2      | 0.36%   |
| HFS256G3                       | 2         | 2      | 0.36%   |
| Gigabyte Technology            | 2         | 3      | 0.36%   |
| V-GeN                          | 1         | 1      | 0.18%   |
| USB3.1                         | 1         | 1      | 0.18%   |
| USB3.0                         | 1         | 1      | 0.18%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.18%   |
| UMAX                           | 1         | 1      | 0.18%   |
| Teclast                        | 1         | 1      | 0.18%   |
| Team                           | 1         | 2      | 0.18%   |
| StoreJet                       | 1         | 1      | 0.18%   |
| RSH-319                        | 1         | 1      | 0.18%   |
| Realtek                        | 1         | 1      | 0.18%   |
| Pioneer                        | 1         | 3      | 0.18%   |
| PI-041                         | 1         | 1      | 0.18%   |
| Patriot                        | 1         | 2      | 0.18%   |
| Netac                          | 1         | 1      | 0.18%   |
| Micron/Crucial Technology      | 1         | 1      | 0.18%   |
| MAXTOR                         | 1         | 1      | 0.18%   |
| LITEON                         | 1         | 1      | 0.18%   |
| Lite-On                        | 1         | 1      | 0.18%   |
| Leven                          | 1         | 1      | 0.18%   |
| Lenovo                         | 1         | 1      | 0.18%   |
| LDLC                           | 1         | 1      | 0.18%   |
| KingFast                       | 1         | 1      | 0.18%   |
| KingDian                       | 1         | 1      | 0.18%   |
| imation                        | 1         | 1      | 0.18%   |
| HUAWEI                         | 1         | 1      | 0.18%   |
| HPE                            | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB           | 11        | 1.74%   |
| Seagate ST1000LM035-1RK172 1TB    | 10        | 1.58%   |
| Samsung SSD 860 EVO 500GB         | 7         | 1.11%   |
| Samsung SSD 860 EVO 250GB         | 7         | 1.11%   |
| Samsung SSD 850 EVO 250GB         | 7         | 1.11%   |
| HGST HTS721010A9E630 1TB          | 7         | 1.11%   |
| Seagate ST500LT012-1DG142 500GB   | 6         | 0.95%   |
| Samsung SSD 970 EVO 500GB         | 6         | 0.95%   |
| Samsung SSD 850 EVO 500GB         | 6         | 0.95%   |
| Crucial CT500MX500SSD1 500GB      | 6         | 0.95%   |
| WDC WD10EZEX-00BN5A0 1TB          | 5         | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB    | 5         | 0.79%   |
| Samsung SSD 970 EVO 1TB           | 5         | 0.79%   |
| Kingston SA400S37120G 120GB SSD   | 5         | 0.79%   |
| Crucial CT1000MX500SSD1 1TB       | 5         | 0.79%   |
| WDC WDS100T3X0C-00SJG0 1TB        | 4         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4         | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB    | 4         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB    | 4         | 0.63%   |
| Seagate Expansion Desk 8TB        | 4         | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB    | 4         | 0.63%   |
| Samsung SSD 870 EVO 250GB         | 4         | 0.63%   |
| Kingston SA400S37240G 240GB SSD   | 4         | 0.63%   |
| Apple SSD SM0128G 121GB           | 4         | 0.63%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3         | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 3         | 0.48%   |
| WDC WD10EZEX-00RKKA0 1TB          | 3         | 0.48%   |
| Unknown SD/MMC/MS PRO 4GB         | 3         | 0.48%   |
| Toshiba HDWD110 1TB               | 3         | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB    | 3         | 0.48%   |
| Seagate ST2000DM006-2DM164 2TB    | 3         | 0.48%   |
| Seagate ST1000LM049-2GH172 1TB    | 3         | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB    | 3         | 0.48%   |
| Samsung SSD 980 PRO 500GB         | 3         | 0.48%   |
| Samsung SSD 960 EVO 500GB         | 3         | 0.48%   |
| Samsung SSD 840 EVO 250GB         | 3         | 0.48%   |
| Samsung NVMe SSD Drive 512GB      | 3         | 0.48%   |
| Samsung NVMe SSD Drive 1TB        | 3         | 0.48%   |
| Samsung MZVLB1T0HBLR-00000 1TB    | 3         | 0.48%   |
| Maxone USB 3.0 160GB              | 3         | 0.48%   |
| KIOXIA KBG40ZNV512G 512GB         | 3         | 0.48%   |
| Hitachi HTS545050A7E380 500GB     | 3         | 0.48%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 2         | 0.32%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 2         | 0.32%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 2         | 0.32%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD | 2         | 0.32%   |
| WDC WD40EZRZ-00GXCB0 4TB          | 2         | 0.32%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2         | 0.32%   |
| WDC WD10SPZX-24Z10 1TB            | 2         | 0.32%   |
| WDC WD10JPVX-22JC3T0 1TB          | 2         | 0.32%   |
| WDC WD10EZRX-00A8LB0 1TB          | 2         | 0.32%   |
| WDC WD10EZEX-60WN4A1 1TB          | 2         | 0.32%   |
| WDC WD10EZEX-22MFCA0 1TB          | 2         | 0.32%   |
| Unknown MMC Card  64GB            | 2         | 0.32%   |
| Unknown MMC Card  128GB           | 2         | 0.32%   |
| Transcend TS240GMTS420S 240GB SSD | 2         | 0.32%   |
| Toshiba THNSNJ256GCSU 256GB SSD   | 2         | 0.32%   |
| Toshiba MQ01ABD100 1TB            | 2         | 0.32%   |
| Toshiba KBG40ZNT512G MEMORY 512GB | 2         | 0.32%   |
| Toshiba DT01ACA100 1TB            | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 97     | 40.11%  |
| WDC                 | 49        | 76     | 27.68%  |
| Toshiba             | 17        | 18     | 9.6%    |
| HGST                | 15        | 16     | 8.47%   |
| Hitachi             | 6         | 6      | 3.39%   |
| Unknown             | 3         | 3      | 1.69%   |
| Samsung Electronics | 3         | 4      | 1.69%   |
| Maxone              | 3         | 3      | 1.69%   |
| USB3.0              | 1         | 1      | 0.56%   |
| StoreJet            | 1         | 1      | 0.56%   |
| RSH-319             | 1         | 1      | 0.56%   |
| PI-041              | 1         | 1      | 0.56%   |
| MAXTOR              | 1         | 1      | 0.56%   |
| JMicron             | 1         | 1      | 0.56%   |
| HPE                 | 1         | 1      | 0.56%   |
| Generic-            | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |
| ASMT                | 1         | 2      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 77        | 110    | 34.68%  |
| Kingston            | 21        | 37     | 9.46%   |
| Crucial             | 21        | 27     | 9.46%   |
| SanDisk             | 14        | 15     | 6.31%   |
| WDC                 | 12        | 18     | 5.41%   |
| Apple               | 7         | 8      | 3.15%   |
| Toshiba             | 5         | 6      | 2.25%   |
| SK Hynix            | 4         | 4      | 1.8%    |
| Micron Technology   | 4         | 4      | 1.8%    |
| Intel               | 4         | 5      | 1.8%    |
| A-DATA Technology   | 4         | 5      | 1.8%    |
| Transcend           | 3         | 3      | 1.35%   |
| OCZ                 | 3         | 3      | 1.35%   |
| LITEONIT            | 3         | 4      | 1.35%   |
| Intenso             | 3         | 3      | 1.35%   |
| China               | 3         | 3      | 1.35%   |
| WDC WDS             | 2         | 2      | 0.9%    |
| SPCC                | 2         | 2      | 0.9%    |
| Seagate             | 2         | 2      | 0.9%    |
| Mushkin             | 2         | 2      | 0.9%    |
| KingSpec            | 2         | 2      | 0.9%    |
| Corsair             | 2         | 2      | 0.9%    |
| V-GeN               | 1         | 1      | 0.45%   |
| Unknown             | 1         | 2      | 0.45%   |
| UMAX                | 1         | 1      | 0.45%   |
| Teclast             | 1         | 1      | 0.45%   |
| Team                | 1         | 2      | 0.45%   |
| PNY                 | 1         | 1      | 0.45%   |
| Pioneer             | 1         | 3      | 0.45%   |
| PHISON              | 1         | 1      | 0.45%   |
| Patriot             | 1         | 2      | 0.45%   |
| LITEON              | 1         | 1      | 0.45%   |
| Leven               | 1         | 1      | 0.45%   |
| LDLC                | 1         | 1      | 0.45%   |
| KingFast            | 1         | 1      | 0.45%   |
| KingDian            | 1         | 1      | 0.45%   |
| JMicron             | 1         | 1      | 0.45%   |
| imation             | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| GOODRAM             | 1         | 1      | 0.45%   |
| Gigabyte Technology | 1         | 1      | 0.45%   |
| FORESEE             | 1         | 1      | 0.45%   |
| DREVO               | 1         | 1      | 0.45%   |
| Apacer              | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 181       | 294    | 36.2%   |
| NVMe    | 155       | 204    | 31%     |
| HDD     | 148       | 234    | 29.6%   |
| MMC     | 8         | 11     | 1.6%    |
| Unknown | 8         | 8      | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 247       | 496    | 55.76%  |
| NVMe | 155       | 203    | 34.99%  |
| SAS  | 33        | 41     | 7.45%   |
| MMC  | 8         | 11     | 1.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 178       | 292    | 50.28%  |
| 0.51-1.0   | 118       | 158    | 33.33%  |
| 1.01-2.0   | 29        | 41     | 8.19%   |
| 3.01-4.0   | 12        | 17     | 3.39%   |
| 4.01-10.0  | 8         | 10     | 2.26%   |
| 2.01-3.0   | 7         | 8      | 1.98%   |
| 10.01-20.0 | 2         | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 20.06%  |
| 251-500        | 66        | 18.64%  |
| 501-1000       | 57        | 16.1%   |
| 1001-2000      | 56        | 15.82%  |
| More than 3000 | 29        | 8.19%   |
| Unknown        | 27        | 7.63%   |
| 2001-3000      | 19        | 5.37%   |
| 51-100         | 14        | 3.95%   |
| 21-50          | 8         | 2.26%   |
| 1-20           | 7         | 1.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 69        | 18.85%  |
| 101-250        | 59        | 16.12%  |
| 21-50          | 52        | 14.21%  |
| 51-100         | 46        | 12.57%  |
| 251-500        | 41        | 11.2%   |
| 1001-2000      | 29        | 7.92%   |
| 501-1000       | 27        | 7.38%   |
| Unknown        | 27        | 7.38%   |
| More than 3000 | 11        | 3.01%   |
| 2001-3000      | 5         | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                    | 3         | 3      | 10.71%  |
| HGST HTS721010A9E630 1TB                         | 3         | 3      | 10.71%  |
| WDC WD5000AZRX-00A8LB0 500GB                     | 1         | 1      | 3.57%   |
| WDC WD40EFRX-68WT0N0 4TB                         | 1         | 2      | 3.57%   |
| Toshiba MK5055GSXF 500GB                         | 1         | 1      | 3.57%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 3.57%   |
| SK Hynix SC308 SATA 128GB SSD                    | 1         | 1      | 3.57%   |
| Seagate ST9320325AS 320GB                        | 1         | 5      | 3.57%   |
| Seagate ST6000VX0023-2EF110 6TB                  | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST3320620AS 320GB                        | 1         | 1      | 3.57%   |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 1      | 3.57%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 3.57%   |
| SanDisk SDSSDA240G 240GB                         | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 960 EVO 500GB            | 1         | 1      | 3.57%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.57%   |
| Samsung Electronics HD103SI 752GB                | 1         | 1      | 3.57%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 3.57%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 3.57%   |
| Fujitsu MHZ2320BH G2 320GB                       | 1         | 1      | 3.57%   |
| DREVO X1 SSD 120GB                               | 1         | 1      | 3.57%   |
| ASMT ASM1156-PM 2TB                              | 1         | 2      | 3.57%   |
| Apple SSD SM256C 256GB                           | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 9      | 17.86%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| HGST                | 4         | 4      | 14.29%  |
| Hitachi             | 3         | 3      | 10.71%  |
| WDC                 | 2         | 3      | 7.14%   |
| Toshiba             | 2         | 2      | 7.14%   |
| SanDisk             | 2         | 2      | 7.14%   |
| SK Hynix            | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| DREVO               | 1         | 1      | 3.57%   |
| ASMT                | 1         | 2      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 9      | 26.32%  |
| HGST                | 4         | 4      | 21.05%  |
| Hitachi             | 3         | 3      | 15.79%  |
| WDC                 | 2         | 3      | 10.53%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |
| ASMT                | 1         | 2      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 25     | 70.37%  |
| SSD  | 6         | 7      | 22.22%  |
| NVMe | 2         | 2      | 7.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 250       | 495    | 64.77%  |
| Detected | 109       | 221    | 28.24%  |
| Malfunc  | 26        | 34     | 6.74%   |
| Failed   | 1         | 1      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 193       | 41.24%  |
| AMD                            | 90        | 19.23%  |
| Samsung Electronics            | 54        | 11.54%  |
| Sandisk                        | 29        | 6.2%    |
| SK Hynix                       | 13        | 2.78%   |
| Phison Electronics             | 13        | 2.78%   |
| KIOXIA                         | 9         | 1.92%   |
| Toshiba America Info Systems   | 8         | 1.71%   |
| Kingston Technology Company    | 8         | 1.71%   |
| ASMedia Technology             | 8         | 1.71%   |
| Marvell Technology Group       | 6         | 1.28%   |
| Micron/Crucial Technology      | 5         | 1.07%   |
| Micron Technology              | 5         | 1.07%   |
| ADATA Technology               | 5         | 1.07%   |
| Realtek Semiconductor          | 4         | 0.85%   |
| JMicron Technology             | 4         | 0.85%   |
| Seagate Technology             | 3         | 0.64%   |
| Nvidia                         | 3         | 0.64%   |
| Solid State Storage Technology | 2         | 0.43%   |
| Union Memory (Shenzhen)        | 1         | 0.21%   |
| Silicon Motion                 | 1         | 0.21%   |
| LSI Logic / Symbios Logic      | 1         | 0.21%   |
| Lite-On Technology             | 1         | 0.21%   |
| Lenovo                         | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 68        | 13.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 34        | 6.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 27        | 5.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 19        | 3.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 18        | 3.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 3.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 2.16%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.96%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 10        | 1.96%   |
| KIOXIA Non-Volatile memory controller                                          | 9         | 1.77%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 8         | 1.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 1.57%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8         | 1.57%   |
| Intel SSD 660P Series                                                          | 7         | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.38%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6         | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.18%   |
| SK Hynix Gold P31 SSD                                                          | 5         | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 0.98%   |
| Samsung Electronics SATA controller                                            | 5         | 0.98%   |
| Micron Non-Volatile memory controller                                          | 5         | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.98%   |
| SK Hynix Non-Volatile memory controller                                        | 4         | 0.79%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                | 4         | 0.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 0.79%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 0.59%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3         | 0.59%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 3         | 0.59%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 0.59%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.59%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3         | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.59%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.59%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 0.39%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 2         | 0.39%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 0.39%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.39%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 0.39%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 254       | 56.44%  |
| NVMe | 155       | 34.44%  |
| RAID | 25        | 5.56%   |
| IDE  | 15        | 3.33%   |
| SAS  | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 225       | 65.6%   |
| AMD    | 117       | 34.11%  |
| ARM    | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 2.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 2.04%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 2.04%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 1.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.46%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 1.46%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 5         | 1.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.17%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 4         | 1.17%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.17%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 1.17%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.87%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 0.87%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 3         | 0.87%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 3         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.87%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 3         | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3         | 0.87%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 3         | 0.87%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.58%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.58%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.58%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.58%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.58%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.58%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 2         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.58%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 2         | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.58%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.58%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.58%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.58%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 0.58%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.58%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 0.58%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.58%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.58%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 2         | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.58%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 0.58%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 93        | 27.11%  |
| Intel Core i7           | 79        | 23.03%  |
| AMD Ryzen 5             | 37        | 10.79%  |
| AMD Ryzen 7             | 31        | 9.04%   |
| AMD Ryzen 9             | 16        | 4.66%   |
| Intel Core i3           | 15        | 4.37%   |
| Other                   | 12        | 3.5%    |
| Intel Celeron           | 8         | 2.33%   |
| Intel Xeon              | 7         | 2.04%   |
| AMD Ryzen 7 PRO         | 6         | 1.75%   |
| AMD A4                  | 6         | 1.75%   |
| AMD Ryzen 3             | 5         | 1.46%   |
| Intel Core 2 Duo        | 4         | 1.17%   |
| Intel Core 2 Quad       | 3         | 0.87%   |
| AMD FX                  | 3         | 0.87%   |
| AMD A8                  | 3         | 0.87%   |
| Intel Core m3           | 2         | 0.58%   |
| AMD E1                  | 2         | 0.58%   |
| Intel Pentium Gold      | 1         | 0.29%   |
| Intel Pentium Dual-Core | 1         | 0.29%   |
| Intel Pentium Dual      | 1         | 0.29%   |
| Intel Pentium           | 1         | 0.29%   |
| Intel Core 2 Extreme    | 1         | 0.29%   |
| AMD Ryzen Threadripper  | 1         | 0.29%   |
| AMD Ryzen 5 PRO         | 1         | 0.29%   |
| AMD Phenom II X4        | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD Athlon II X4        | 1         | 0.29%   |
| AMD Athlon              | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 135       | 39.24%  |
| 2      | 96        | 27.91%  |
| 6      | 52        | 15.12%  |
| 8      | 45        | 13.08%  |
| 12     | 11        | 3.2%    |
| 16     | 2         | 0.58%   |
| 3      | 2         | 0.58%   |
| 10     | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 341       | 99.13%  |
| 2      | 3         | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 275       | 80.17%  |
| 1      | 68        | 19.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 340       | 99.13%  |
| Unknown        | 2         | 0.58%   |
| 64-bit         | 1         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 25.5%   |
| 0x306c3    | 17        | 4.87%   |
| 0x08701021 | 16        | 4.58%   |
| 0x906ea    | 14        | 4.01%   |
| 0x806ea    | 13        | 3.72%   |
| 0x406e3    | 13        | 3.72%   |
| 0x306a9    | 13        | 3.72%   |
| 0x506e3    | 12        | 3.44%   |
| 0x40651    | 9         | 2.58%   |
| 0x806ec    | 8         | 2.29%   |
| 0x0a50000c | 8         | 2.29%   |
| 0x0a201009 | 8         | 2.29%   |
| 0x806e9    | 7         | 2.01%   |
| 0x08701013 | 7         | 2.01%   |
| 0x08108109 | 7         | 2.01%   |
| 0x08600104 | 6         | 1.72%   |
| 0x906e9    | 5         | 1.43%   |
| 0x706e5    | 5         | 1.43%   |
| 0x306d4    | 5         | 1.43%   |
| 0x206a7    | 5         | 1.43%   |
| 0x08600106 | 5         | 1.43%   |
| 0x08108102 | 5         | 1.43%   |
| 0xa0652    | 4         | 1.15%   |
| 0x08608103 | 4         | 1.15%   |
| 0x0800820d | 4         | 1.15%   |
| 0x806d1    | 3         | 0.86%   |
| 0x706a1    | 3         | 0.86%   |
| 0x20655    | 3         | 0.86%   |
| 0x106a5    | 3         | 0.86%   |
| 0x0a201016 | 3         | 0.86%   |
| 0x08600102 | 3         | 0.86%   |
| 0x08001137 | 3         | 0.86%   |
| 0xa0655    | 2         | 0.57%   |
| 0x806eb    | 2         | 0.57%   |
| 0x806c1    | 2         | 0.57%   |
| 0x706a8    | 2         | 0.57%   |
| 0x6fd      | 2         | 0.57%   |
| 0x20652    | 2         | 0.57%   |
| 0x1067a    | 2         | 0.57%   |
| 0x07000110 | 2         | 0.57%   |
| 0x06006705 | 2         | 0.57%   |
| 0x906ed    | 1         | 0.29%   |
| 0x906eb    | 1         | 0.29%   |
| 0x6fb      | 1         | 0.29%   |
| 0x506c9    | 1         | 0.29%   |
| 0x40671    | 1         | 0.29%   |
| 0x306f2    | 1         | 0.29%   |
| 0x30678    | 1         | 0.29%   |
| 0x206c2    | 1         | 0.29%   |
| 0x106e5    | 1         | 0.29%   |
| 0x0a50000b | 1         | 0.29%   |
| 0x08608102 | 1         | 0.29%   |
| 0x08600103 | 1         | 0.29%   |
| 0x08101016 | 1         | 0.29%   |
| 0x08001138 | 1         | 0.29%   |
| 0x07030105 | 1         | 0.29%   |
| 0x07030104 | 1         | 0.29%   |
| 0x0700010f | 1         | 0.29%   |
| 0x06006704 | 1         | 0.29%   |
| 0x06001119 | 1         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 67        | 19.53%  |
| Zen 2         | 44        | 12.83%  |
| Haswell       | 38        | 11.08%  |
| Skylake       | 33        | 9.62%   |
| Zen 3         | 23        | 6.71%   |
| Zen+          | 18        | 5.25%   |
| IvyBridge     | 17        | 4.96%   |
| Icelake       | 10        | 2.92%   |
| CometLake     | 9         | 2.62%   |
| Broadwell     | 9         | 2.62%   |
| Zen           | 8         | 2.33%   |
| SandyBridge   | 8         | 2.33%   |
| Unknown       | 7         | 2.04%   |
| Westmere      | 6         | 1.75%   |
| Core          | 6         | 1.75%   |
| TigerLake     | 5         | 1.46%   |
| Jaguar        | 5         | 1.46%   |
| Goldmont plus | 5         | 1.46%   |
| Piledriver    | 4         | 1.17%   |
| Penryn        | 4         | 1.17%   |
| Nehalem       | 4         | 1.17%   |
| Excavator     | 4         | 1.17%   |
| Silvermont    | 2         | 0.58%   |
| Puma          | 2         | 0.58%   |
| K10 Llano     | 1         | 0.29%   |
| K10           | 1         | 0.29%   |
| Goldmont      | 1         | 0.29%   |
| Bulldozer     | 1         | 0.29%   |
| Bobcat        | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 172       | 40.47%  |
| Nvidia | 141       | 33.18%  |
| AMD    | 112       | 26.35%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                            | 18        | 4.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 17        | 3.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 16        | 3.71%   |
| Intel UHD Graphics 620                                                                | 15        | 3.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 14        | 3.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 3.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 2.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 10        | 2.32%   |
| AMD Cezanne                                                                           | 10        | 2.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 8         | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 8         | 1.86%   |
| Intel HD Graphics 530                                                                 | 8         | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 6         | 1.39%   |
| Intel HD Graphics 620                                                                 | 6         | 1.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 6         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 5         | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 5         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 1.16%   |
| AMD Lucienne                                                                          | 5         | 1.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 0.93%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                | 4         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 4         | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 0.93%   |
| Intel HD Graphics 630                                                                 | 4         | 0.93%   |
| Intel HD Graphics 6000                                                                | 4         | 0.93%   |
| Intel HD Graphics 5500                                                                | 4         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 4         | 0.93%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                        | 4         | 0.93%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                        | 4         | 0.93%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 4         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 0.7%    |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 3         | 0.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 3         | 0.7%    |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 3         | 0.7%    |
| Nvidia GM108M [GeForce 940M]                                                          | 3         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 3         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.7%    |
| AMD Kabini [Radeon HD 8330]                                                           | 3         | 0.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                        | 3         | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 2         | 0.46%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 2         | 0.46%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 2         | 0.46%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 0.46%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.46%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 2         | 0.46%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                    | 2         | 0.46%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 2         | 0.46%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 2         | 0.46%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 2         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 100       | 29.07%  |
| 1 x AMD        | 88        | 25.58%  |
| 1 x Nvidia     | 71        | 20.64%  |
| Intel + Nvidia | 59        | 17.15%  |
| AMD + Nvidia   | 11        | 3.2%    |
| Intel + AMD    | 9         | 2.62%   |
| 2 x AMD        | 5         | 1.45%   |
| Other          | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 234       | 68.02%  |
| Proprietary | 109       | 31.69%  |
| Unknown     | 1         | 0.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 176       | 50.29%  |
| 1.01-2.0   | 39        | 11.14%  |
| 0.01-0.5   | 36        | 10.29%  |
| 7.01-8.0   | 32        | 9.14%   |
| 3.01-4.0   | 25        | 7.14%   |
| 5.01-6.0   | 14        | 4%      |
| 0.51-1.0   | 14        | 4%      |
| 8.01-16.0  | 9         | 2.57%   |
| 2.01-3.0   | 4         | 1.14%   |
| 16.01-24.0 | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 12.26%  |
| Samsung Electronics     | 47        | 11.3%   |
| LG Display              | 40        | 9.62%   |
| Chimei Innolux          | 33        | 7.93%   |
| BOE                     | 31        | 7.45%   |
| Goldstar                | 22        | 5.29%   |
| Dell                    | 21        | 5.05%   |
| BenQ                    | 15        | 3.61%   |
| Ancor Communications    | 13        | 3.13%   |
| Acer                    | 13        | 3.13%   |
| Apple                   | 11        | 2.64%   |
| AOC                     | 10        | 2.4%    |
| ViewSonic               | 9         | 2.16%   |
| Hewlett-Packard         | 9         | 2.16%   |
| PANDA                   | 8         | 1.92%   |
| Lenovo                  | 8         | 1.92%   |
| InfoVision              | 7         | 1.68%   |
| Sharp                   | 6         | 1.44%   |
| Vizio                   | 5         | 1.2%    |
| Iiyama                  | 5         | 1.2%    |
| Sony                    | 4         | 0.96%   |
| Philips                 | 4         | 0.96%   |
| ASUSTek Computer        | 4         | 0.96%   |
| LG Electronics          | 3         | 0.72%   |
| Fujitsu Siemens         | 3         | 0.72%   |
| Unknown                 | 2         | 0.48%   |
| Sceptre Tech            | 2         | 0.48%   |
| Pixio                   | 2         | 0.48%   |
| Lenovo Group Limited    | 2         | 0.48%   |
| Gigabyte Technology     | 2         | 0.48%   |
| CSO                     | 2         | 0.48%   |
| Chi Mei Optoelectronics | 2         | 0.48%   |
| Valve                   | 1         | 0.24%   |
| Unknown (XXX)           | 1         | 0.24%   |
| Sun                     | 1         | 0.24%   |
| SAC                     | 1         | 0.24%   |
| RTK                     | 1         | 0.24%   |
| RS                      | 1         | 0.24%   |
| Planar                  | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| NEC Computers           | 1         | 0.24%   |
| MSI                     | 1         | 0.24%   |
| Insignia                | 1         | 0.24%   |
| InnoLux Display         | 1         | 0.24%   |
| HVR                     | 1         | 0.24%   |
| HPN                     | 1         | 0.24%   |
| Grundig                 | 1         | 0.24%   |
| Gateway                 | 1         | 0.24%   |
| Eizo                    | 1         | 0.24%   |
| DENON                   | 1         | 0.24%   |
| Belinea                 | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 1.17%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.94%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 3         | 0.7%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch         | 3         | 0.7%    |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                   | 2         | 0.47%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 2         | 0.47%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2         | 0.47%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch     | 2         | 0.47%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch      | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.47%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 2         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.47%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 2         | 0.47%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.47%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 2         | 0.47%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.47%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 2         | 0.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.47%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 2         | 0.47%   |
| InfoVision LCD Monitor IVO8544 1920x1080 294x165mm 13.3-inch          | 2         | 0.47%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.47%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 2         | 0.47%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 2         | 0.47%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 2         | 0.47%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 2         | 0.47%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                 | 2         | 0.47%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                 | 2         | 0.47%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.47%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 2         | 0.47%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                     | 2         | 0.47%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                    | 2         | 0.47%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 340x190mm 15.3-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 0.47%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch          | 2         | 0.47%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 2         | 0.47%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 2         | 0.47%   |
| Vizio V505-G9 VIZ1033 3840x2160 1096x616mm 49.5-inch                  | 1         | 0.23%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                    | 1         | 0.23%   |
| Vizio 320AR VIZ0089 1360x768 477x268mm 21.5-inch                      | 1         | 0.23%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.23%   |
| ViewSonic VX2457 VSCB931 1920x1080 520x290mm 23.4-inch                | 1         | 0.23%   |
| ViewSonic VX2456 SERIES VSC4F2F 1920x1080 521x293mm 23.5-inch         | 1         | 0.23%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1         | 0.23%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch         | 1         | 0.23%   |
| ViewSonic LCD Monitor VX2250 SERIES                                   | 1         | 0.23%   |
| Valve Index HMD VLV91A8                                               | 1         | 0.23%   |
| Unknown LCD Monitor Sharp LQ156M1JW03 3840x1080                       | 1         | 0.23%   |
| Unknown LCD Monitor MARANTZ JAPAN, INC. marantz-AVR 3840x2160         | 1         | 0.23%   |
| Unknown LCD Monitor Dell SE2717H/HX                                   | 1         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 200       | 50.13%  |
| 1366x768 (WXGA)    | 54        | 13.53%  |
| 3840x2160 (4K)     | 30        | 7.52%   |
| 2560x1440 (QHD)    | 28        | 7.02%   |
| 1920x1200 (WUXGA)  | 11        | 2.76%   |
| 1440x900 (WXGA+)   | 11        | 2.76%   |
| 1280x1024 (SXGA)   | 7         | 1.75%   |
| Unknown            | 7         | 1.75%   |
| 2560x1600          | 6         | 1.5%    |
| 2560x1080          | 6         | 1.5%    |
| 1680x1050 (WSXGA+) | 5         | 1.25%   |
| 1600x900 (HD+)     | 5         | 1.25%   |
| 1280x800 (WXGA)    | 4         | 1%      |
| 3840x1080          | 3         | 0.75%   |
| 3440x1440          | 3         | 0.75%   |
| 2160x1440          | 2         | 0.5%    |
| 1360x768           | 2         | 0.5%    |
| 9840x3840          | 1         | 0.25%   |
| 4480x1440          | 1         | 0.25%   |
| 3840x2400          | 1         | 0.25%   |
| 3840x1600          | 1         | 0.25%   |
| 3840x1440          | 1         | 0.25%   |
| 3520x1080          | 1         | 0.25%   |
| 3456x2160          | 1         | 0.25%   |
| 3240x2160          | 1         | 0.25%   |
| 3200x1800 (QHD+)   | 1         | 0.25%   |
| 2880x1920          | 1         | 0.25%   |
| 2880x1800          | 1         | 0.25%   |
| 2880x1700          | 1         | 0.25%   |
| 2736x1824          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 1600x1200          | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 95        | 22.84%  |
| 13      | 56        | 13.46%  |
| 27      | 41        | 9.86%   |
| 24      | 40        | 9.62%   |
| 14      | 28        | 6.73%   |
| 23      | 24        | 5.77%   |
| 21      | 22        | 5.29%   |
| 17      | 16        | 3.85%   |
| Unknown | 15        | 3.61%   |
| 34      | 10        | 2.4%    |
| 31      | 9         | 2.16%   |
| 18      | 7         | 1.68%   |
| 22      | 6         | 1.44%   |
| 19      | 6         | 1.44%   |
| 12      | 5         | 1.2%    |
| 11      | 5         | 1.2%    |
| 54      | 4         | 0.96%   |
| 49      | 3         | 0.72%   |
| 20      | 3         | 0.72%   |
| 16      | 3         | 0.72%   |
| 72      | 2         | 0.48%   |
| 42      | 2         | 0.48%   |
| 32      | 2         | 0.48%   |
| 69      | 1         | 0.24%   |
| 65      | 1         | 0.24%   |
| 60      | 1         | 0.24%   |
| 57      | 1         | 0.24%   |
| 48      | 1         | 0.24%   |
| 47      | 1         | 0.24%   |
| 37      | 1         | 0.24%   |
| 29      | 1         | 0.24%   |
| 28      | 1         | 0.24%   |
| 25      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |
| 8       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 153       | 37.78%  |
| 501-600     | 91        | 22.47%  |
| 201-300     | 40        | 9.88%   |
| 401-500     | 38        | 9.38%   |
| 351-400     | 20        | 4.94%   |
| 601-700     | 17        | 4.2%    |
| Unknown     | 15        | 3.7%    |
| 701-800     | 12        | 2.96%   |
| 1001-1500   | 12        | 2.96%   |
| 1501-2000   | 3         | 0.74%   |
| 901-1000    | 2         | 0.49%   |
| 801-900     | 1         | 0.25%   |
| 101-200     | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 281       | 77.41%  |
| 16/10   | 42        | 11.57%  |
| Unknown | 14        | 3.86%   |
| 21/9    | 9         | 2.48%   |
| 5/4     | 5         | 1.38%   |
| 3/2     | 5         | 1.38%   |
| 4/3     | 2         | 0.55%   |
| 32/9    | 2         | 0.55%   |
| 6/5     | 1         | 0.28%   |
| 2.65    | 1         | 0.28%   |
| 0.62    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 94        | 22.87%  |
| 201-250        | 68        | 16.55%  |
| 81-90          | 60        | 14.6%   |
| 301-350        | 41        | 9.98%   |
| 71-80          | 26        | 6.33%   |
| 351-500        | 21        | 5.11%   |
| 251-300        | 20        | 4.87%   |
| Unknown        | 15        | 3.65%   |
| More than 1000 | 12        | 2.92%   |
| 121-130        | 12        | 2.92%   |
| 151-200        | 11        | 2.68%   |
| 141-150        | 8         | 1.95%   |
| 501-1000       | 7         | 1.7%    |
| 51-60          | 5         | 1.22%   |
| 111-120        | 4         | 0.97%   |
| 61-70          | 3         | 0.73%   |
| 131-140        | 2         | 0.49%   |
| 41-50          | 1         | 0.24%   |
| 1-40           | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 129       | 32.91%  |
| 51-100        | 111       | 28.32%  |
| 101-120       | 82        | 20.92%  |
| 161-240       | 30        | 7.65%   |
| Unknown       | 15        | 3.83%   |
| More than 240 | 13        | 3.32%   |
| 1-50          | 12        | 3.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 270       | 77.59%  |
| 2     | 68        | 19.54%  |
| 3     | 8         | 2.3%    |
| 4     | 2         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 205       | 38.75%  |
| Intel                    | 194       | 36.67%  |
| Qualcomm Atheros         | 40        | 7.56%   |
| Broadcom                 | 19        | 3.59%   |
| MediaTek                 | 10        | 1.89%   |
| Broadcom Limited         | 7         | 1.32%   |
| TP-Link                  | 6         | 1.13%   |
| D-Link                   | 6         | 1.13%   |
| ASIX Electronics         | 5         | 0.95%   |
| Sierra Wireless          | 3         | 0.57%   |
| Ralink Technology        | 3         | 0.57%   |
| Ralink                   | 3         | 0.57%   |
| Microsoft                | 3         | 0.57%   |
| Marvell Technology Group | 3         | 0.57%   |
| Hewlett-Packard          | 3         | 0.57%   |
| Nvidia                   | 2         | 0.38%   |
| NetGear                  | 2         | 0.38%   |
| Linksys                  | 2         | 0.38%   |
| Lenovo                   | 2         | 0.38%   |
| Huawei Technologies      | 2         | 0.38%   |
| Cypress Semiconductor    | 2         | 0.38%   |
| Xiaomi                   | 1         | 0.19%   |
| InterBiometrics          | 1         | 0.19%   |
| Exar                     | 1         | 0.19%   |
| Edimax Technology        | 1         | 0.19%   |
| DisplayLink              | 1         | 0.19%   |
| Aquantia                 | 1         | 0.19%   |
| Apple                    | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 140       | 21.94%  |
| Intel Wi-Fi 6 AX200                                               | 42        | 6.58%   |
| Intel I211 Gigabit Network Connection                             | 19        | 2.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 2.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.88%   |
| Intel Wireless 7260                                               | 12        | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.72%   |
| Intel Wireless 8260                                               | 11        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 1.1%    |
| MEDIATEK Network controller                                       | 7         | 1.1%    |
| Intel Wireless 7265                                               | 7         | 1.1%    |
| Intel Wireless 3165                                               | 7         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.94%   |
| D-Link 802.11ac NIC                                               | 6         | 0.94%   |
| TP-Link 802.11ac NIC                                              | 5         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.78%   |
| Realtek 802.11ac NIC                                              | 5         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.78%   |
| Intel Wireless-AC 9260                                            | 5         | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.63%   |
| Intel Wireless 3160                                               | 4         | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.47%   |
| Microsoft Wireless XBox Controller Dongle                         | 3         | 0.47%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 3         | 0.47%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.47%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.47%   |
| HP un2430 Mobile Broadband Module                                 | 3         | 0.47%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 167       | 54.75%  |
| Realtek Semiconductor    | 46        | 15.08%  |
| Qualcomm Atheros         | 29        | 9.51%   |
| Broadcom                 | 17        | 5.57%   |
| MEDIATEK                 | 10        | 3.28%   |
| TP-Link                  | 6         | 1.97%   |
| D-Link                   | 6         | 1.97%   |
| Broadcom Limited         | 6         | 1.97%   |
| Ralink Technology        | 3         | 0.98%   |
| Ralink                   | 3         | 0.98%   |
| Microsoft                | 3         | 0.98%   |
| Marvell Technology Group | 3         | 0.98%   |
| Sierra Wireless          | 2         | 0.66%   |
| Linksys                  | 2         | 0.66%   |
| NetGear                  | 1         | 0.33%   |
| Edimax Technology        | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 42        | 13.64%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 13        | 4.22%   |
| Intel Wireless 7260                                                 | 12        | 3.9%    |
| Intel Wireless 8265 / 8275                                          | 11        | 3.57%   |
| Intel Wireless 8260                                                 | 11        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 10        | 3.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 9         | 2.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 9         | 2.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 7         | 2.27%   |
| MEDIATEK Network controller                                         | 7         | 2.27%   |
| Intel Wireless 7265                                                 | 7         | 2.27%   |
| Intel Wireless 3165                                                 | 7         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 7         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 6         | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 6         | 1.95%   |
| D-Link 802.11ac NIC                                                 | 6         | 1.95%   |
| TP-Link 802.11ac NIC                                                | 5         | 1.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 5         | 1.62%   |
| Realtek 802.11ac NIC                                                | 5         | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 5         | 1.62%   |
| Intel Wireless-AC 9260                                              | 5         | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 5         | 1.62%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter          | 5         | 1.62%   |
| Intel Wireless 3160                                                 | 4         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                      | 4         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                       | 4         | 1.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 3         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 3         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 3         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 3         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 0.97%   |
| Microsoft Wireless XBox Controller Dongle                           | 3         | 0.97%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                   | 3         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                 | 3         | 0.97%   |
| Intel Centrino Advanced-N 6235                                      | 3         | 0.97%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3         | 0.97%   |
| Sierra Wireless EM7455                                              | 2         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 2         | 0.65%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 0.65%   |
| MediaTek WiFi                                                       | 2         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2         | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.65%   |
| Intel Centrino Advanced-N 6200                                      | 2         | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2         | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.65%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1         | 0.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1         | 0.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.32%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                              | 1         | 0.32%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1         | 0.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1         | 0.32%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1         | 0.32%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 0.32%   |
| Ralink RT5572 Wireless Adapter                                      | 1         | 0.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 0.32%   |
| Ralink RT2870 Wireless Adapter                                      | 1         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 183       | 57.91%  |
| Intel                 | 92        | 29.11%  |
| Qualcomm Atheros      | 17        | 5.38%   |
| Broadcom              | 6         | 1.9%    |
| ASIX Electronics      | 5         | 1.58%   |
| Nvidia                | 2         | 0.63%   |
| Lenovo                | 2         | 0.63%   |
| Cypress Semiconductor | 2         | 0.63%   |
| Xiaomi                | 1         | 0.32%   |
| Sierra Wireless       | 1         | 0.32%   |
| NetGear               | 1         | 0.32%   |
| DisplayLink           | 1         | 0.32%   |
| Broadcom Limited      | 1         | 0.32%   |
| Aquantia              | 1         | 0.32%   |
| Apple                 | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 140       | 43.34%  |
| Intel I211 Gigabit Network Connection                             | 19        | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 4.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 4.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.86%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.55%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.55%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.55%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 1.24%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.24%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.62%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.62%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.62%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.62%   |
| Cypress K38231_03                                                 | 2         | 0.62%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.31%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.31%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.31%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.31%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.31%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.31%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.31%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.31%   |
| NetGear LB1120-100NAS                                             | 1         | 0.31%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.31%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.31%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.31%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.31%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.31%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.31%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.31%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.31%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.31%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.31%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.31%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.31%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.31%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 0.31%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.31%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.31%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 1         | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.31%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 1         | 0.31%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 288       | 50%     |
| WiFi     | 281       | 48.78%  |
| Modem    | 7         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 230       | 56.65%  |
| Ethernet | 175       | 43.1%   |
| Modem    | 1         | 0.25%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 191       | 55.52%  |
| 1     | 132       | 38.37%  |
| 3     | 16        | 4.65%   |
| 0     | 3         | 0.87%   |
| 4     | 2         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 278       | 80.12%  |
| Yes  | 69        | 19.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 55.84%  |
| Realtek Semiconductor           | 34        | 12.41%  |
| Qualcomm Atheros Communications | 17        | 6.2%    |
| Broadcom                        | 14        | 5.11%   |
| Cambridge Silicon Radio         | 12        | 4.38%   |
| Apple                           | 10        | 3.65%   |
| IMC Networks                    | 8         | 2.92%   |
| Lite-On Technology              | 6         | 2.19%   |
| Foxconn / Hon Hai               | 5         | 1.82%   |
| ASUSTek Computer                | 4         | 1.46%   |
| Realtek                         | 3         | 1.09%   |
| Toshiba                         | 2         | 0.73%   |
| Marvell Semiconductor           | 2         | 0.73%   |
| MediaTek                        | 1         | 0.36%   |
| HTC (High Tech Computer)        | 1         | 0.36%   |
| Foxconn International           | 1         | 0.36%   |
| Dell                            | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 60        | 21.9%   |
| Intel Bluetooth Device                                               | 41        | 14.96%  |
| Intel AX200 Bluetooth                                                | 40        | 14.6%   |
| Realtek Bluetooth Radio                                              | 21        | 7.66%   |
| Qualcomm Atheros  Bluetooth Device                                   | 12        | 4.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 12        | 4.38%   |
| Apple Bluetooth USB Host Controller                                  | 8         | 2.92%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 7         | 2.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6         | 2.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 4         | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4         | 1.46%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4         | 1.46%   |
| IMC Networks Wireless_Device                                         | 4         | 1.46%   |
| IMC Networks Bluetooth Radio                                         | 4         | 1.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 3         | 1.09%   |
| Realtek Bluetooth Radio                                              | 3         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3         | 1.09%   |
| Realtek 802.11ac WLAN Adapter                                        | 2         | 0.73%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 2         | 0.73%   |
| Lite-On Bluetooth Device                                             | 2         | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 2         | 0.73%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 0.73%   |
| Toshiba BCM43142A0                                                   | 1         | 0.36%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1         | 0.36%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1         | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1         | 0.36%   |
| MediaTek Wireless_Device                                             | 1         | 0.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.36%   |
| Lite-On Atheros Bluetooth                                            | 1         | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.36%   |
| Foxconn International BCM43142A0 Bluetooth module                    | 1         | 0.36%   |
| Foxconn / Hon Hai BT                                                 | 1         | 0.36%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 0.36%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                      | 1         | 0.36%   |
| Dell Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.36%   |
| Broadcom HP Portable Valentine                                       | 1         | 0.36%   |
| Broadcom HP Portable SoftSailing                                     | 1         | 0.36%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.36%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                 | 1         | 0.36%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 1         | 0.36%   |
| Broadcom BCM2045A0                                                   | 1         | 0.36%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.36%   |
| ASUS Bluetooth Device                                                | 1         | 0.36%   |
| ASUS Bluetooth Adapter                                               | 1         | 0.36%   |
| ASUS BCM20702A0                                                      | 1         | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1         | 0.36%   |
| Apple Bluetooth Host Controller                                      | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 220       | 39.93%  |
| AMD                                             | 129       | 23.41%  |
| Nvidia                                          | 108       | 19.6%   |
| C-Media Electronics                             | 11        | 2%      |
| Texas Instruments                               | 9         | 1.63%   |
| Logitech                                        | 9         | 1.63%   |
| SteelSeries ApS                                 | 7         | 1.27%   |
| KORG                                            | 4         | 0.73%   |
| Creative Labs                                   | 4         | 0.73%   |
| AKAI                                            | 4         | 0.73%   |
| Kingston Technology                             | 3         | 0.54%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.36%   |
| Sony                                            | 2         | 0.36%   |
| Sennheiser Communications                       | 2         | 0.36%   |
| Samson Technologies                             | 2         | 0.36%   |
| RODE Microphones                                | 2         | 0.36%   |
| Realtek Semiconductor                           | 2         | 0.36%   |
| Razer USA                                       | 2         | 0.36%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.36%   |
| Lenovo                                          | 2         | 0.36%   |
| JMTek                                           | 2         | 0.36%   |
| Generalplus Technology                          | 2         | 0.36%   |
| Corsair                                         | 2         | 0.36%   |
| AKAI Professional M.I.                          | 2         | 0.36%   |
| Xilinx                                          | 1         | 0.18%   |
| VIA Technologies                                | 1         | 0.18%   |
| Valve Software                                  | 1         | 0.18%   |
| Tdlasunnic                                      | 1         | 0.18%   |
| No brand                                        | 1         | 0.18%   |
| Native Instruments                              | 1         | 0.18%   |
| Micro Star International                        | 1         | 0.18%   |
| M-Audio                                         | 1         | 0.18%   |
| iConnectivity                                   | 1         | 0.18%   |
| Hewlett-Packard                                 | 1         | 0.18%   |
| GYROCOM C&C                                     | 1         | 0.18%   |
| GN Netcom                                       | 1         | 0.18%   |
| Focusrite-Novation                              | 1         | 0.18%   |
| Creative Technology                             | 1         | 0.18%   |
| Blue Microphones                                | 1         | 0.18%   |
| BEHRINGER International                         | 1         | 0.18%   |
| Apple                                           | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 48        | 7.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 41        | 6.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 34        | 5.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 4.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 3.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 2.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16        | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 2.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 1.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.63%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 1.63%   |
| AMD FCH Azalia Controller                                                  | 10        | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.49%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.34%   |
| AMD Navi 10 HDMI Audio                                                     | 9         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.04%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.04%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.89%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 6         | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6         | 0.89%   |
| Texas Instruments PCM2902 Audio Codec                                      | 5         | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 5         | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.74%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.59%   |
| Nvidia Audio device                                                        | 4         | 0.59%   |
| KORG nanoKONTROL2 MIDI Controller                                          | 4         | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.59%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4         | 0.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.59%   |
| AMD High Definition Audio Controller                                       | 4         | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.59%   |
| AKAI MPKmini2                                                              | 4         | 0.59%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 3         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.45%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 0.45%   |
| Intel Audio device                                                         | 3         | 0.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.45%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3         | 0.45%   |
| C-Media Electronics CM106 Like Sound Device                                | 3         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 25%     |
| SK Hynix            | 55        | 17.86%  |
| Corsair             | 29        | 9.42%   |
| Micron Technology   | 26        | 8.44%   |
| G.Skill             | 26        | 8.44%   |
| Unknown             | 18        | 5.84%   |
| Crucial             | 18        | 5.84%   |
| Kingston            | 16        | 5.19%   |
| A-DATA Technology   | 10        | 3.25%   |
| Ramaxel Technology  | 5         | 1.62%   |
| Patriot             | 5         | 1.62%   |
| Unknown (ABCD)      | 4         | 1.3%    |
| Team                | 4         | 1.3%    |
| Elpida              | 3         | 0.97%   |
| Shenzhen Mic        | 2         | 0.65%   |
| V-GeN               | 1         | 0.32%   |
| Strontium           | 1         | 0.32%   |
| SMART Brazil        | 1         | 0.32%   |
| Smart               | 1         | 0.32%   |
| Sesame              | 1         | 0.32%   |
| PNY                 | 1         | 0.32%   |
| Nanya Technology    | 1         | 0.32%   |
| Kllisre             | 1         | 0.32%   |
| Klevv               | 1         | 0.32%   |
| Golden Empire       | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 2.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 1.75%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 5         | 1.46%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 5         | 1.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 5         | 1.46%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 1.17%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 4         | 1.17%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 4         | 1.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 1.17%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 4         | 1.17%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 4         | 1.17%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.88%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.88%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 3         | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s                | 3         | 0.88%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s               | 3         | 0.88%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 2         | 0.58%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 0.58%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s         | 2         | 0.58%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.58%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s            | 2         | 0.58%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 2         | 0.58%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s                 | 2         | 0.58%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s                 | 2         | 0.58%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8192MB SODIMM DDR4 2400MT/s         | 2         | 0.58%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s              | 2         | 0.58%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s            | 2         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.58%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 0.58%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s               | 2         | 0.58%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s              | 2         | 0.58%   |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s                | 2         | 0.58%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s             | 2         | 0.58%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s              | 2         | 0.58%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s            | 2         | 0.58%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                         | 2         | 0.58%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                         | 2         | 0.58%   |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM 400MT/s                                 | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                            | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 1         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 166       | 61.71%  |
| DDR3    | 77        | 28.62%  |
| LPDDR3  | 8         | 2.97%   |
| LPDDR4  | 7         | 2.6%    |
| Unknown | 4         | 1.49%   |
| SDRAM   | 3         | 1.12%   |
| DDR2    | 3         | 1.12%   |
| DDR     | 1         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 58.89%  |
| DIMM         | 90        | 33.33%  |
| Row Of Chips | 16        | 5.93%   |
| Chip         | 4         | 1.48%   |
| RIMM         | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 135       | 46.71%  |
| 4096  | 83        | 28.72%  |
| 16384 | 45        | 15.57%  |
| 2048  | 19        | 6.57%   |
| 32768 | 6         | 2.08%   |
| 1024  | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 71        | 23.83%  |
| 1600    | 58        | 19.46%  |
| 2667    | 47        | 15.77%  |
| 2400    | 24        | 8.05%   |
| 3600    | 15        | 5.03%   |
| 1333    | 14        | 4.7%    |
| 2133    | 13        | 4.36%   |
| 1867    | 10        | 3.36%   |
| 3266    | 8         | 2.68%   |
| 1334    | 5         | 1.68%   |
| 800     | 4         | 1.34%   |
| 3533    | 3         | 1.01%   |
| 3466    | 3         | 1.01%   |
| 3000    | 3         | 1.01%   |
| 3333    | 2         | 0.67%   |
| 2733    | 2         | 0.67%   |
| 1800    | 2         | 0.67%   |
| 4333    | 1         | 0.34%   |
| 4267    | 1         | 0.34%   |
| 3800    | 1         | 0.34%   |
| 3733    | 1         | 0.34%   |
| 3500    | 1         | 0.34%   |
| 3400    | 1         | 0.34%   |
| 2933    | 1         | 0.34%   |
| 2800    | 1         | 0.34%   |
| 2666    | 1         | 0.34%   |
| 2048    | 1         | 0.34%   |
| 1067    | 1         | 0.34%   |
| 1066    | 1         | 0.34%   |
| 400     | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 2         | 28.57%  |
| Hewlett-Packard     | 2         | 28.57%  |
| Brother Industries  | 2         | 28.57%  |
| Seiko Epson         | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 28.57%  |
| Seiko Epson WF-2010 Series    | 1         | 14.29%  |
| HP ENVY 5540 series           | 1         | 14.29%  |
| HP DeskJet 2130 series        | 1         | 14.29%  |
| Brother Printer               | 1         | 14.29%  |
| Brother HL-2130 series        | 1         | 14.29%  |

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
| Chicony Electronics                    | 46        | 20.72%  |
| IMC Networks                           | 26        | 11.71%  |
| Logitech                               | 23        | 10.36%  |
| Acer                                   | 16        | 7.21%   |
| Microdia                               | 15        | 6.76%   |
| Realtek Semiconductor                  | 13        | 5.86%   |
| Syntek                                 | 10        | 4.5%    |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.5%    |
| Apple                                  | 9         | 4.05%   |
| Lite-On Technology                     | 8         | 3.6%    |
| Sunplus Innovation Technology          | 7         | 3.15%   |
| Quanta                                 | 7         | 3.15%   |
| Microsoft                              | 4         | 1.8%    |
| Suyin                                  | 3         | 1.35%   |
| Sonix Technology                       | 2         | 0.9%    |
| Primax Electronics                     | 2         | 0.9%    |
| Intel                                  | 2         | 0.9%    |
| Hewlett-Packard                        | 2         | 0.9%    |
| Alcor Micro                            | 2         | 0.9%    |
| Y Media                                | 1         | 0.45%   |
| Xiaomi                                 | 1         | 0.45%   |
| Valve Software                         | 1         | 0.45%   |
| Tobii Technology AB                    | 1         | 0.45%   |
| Sunplus IT                             | 1         | 0.45%   |
| Silicon Motion                         | 1         | 0.45%   |
| Ricoh                                  | 1         | 0.45%   |
| Razer USA                              | 1         | 0.45%   |
| MACROSILICON                           | 1         | 0.45%   |
| Lenovo                                 | 1         | 0.45%   |
| Leap Motion                            | 1         | 0.45%   |
| Huawei Technologies                    | 1         | 0.45%   |
| HTC (High Tech Computer)               | 1         | 0.45%   |
| 8SSC21B70095V1SR17900E1                | 1         | 0.45%   |
| Unknown                                | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                          | 15        | 6.76%   |
| Chicony Integrated Camera                               | 15        | 6.76%   |
| Chicony HD Webcam                                       | 8         | 3.6%    |
| Acer Integrated Camera                                  | 8         | 3.6%    |
| Microdia Integrated_Webcam_HD                           | 7         | 3.15%   |
| Logitech HD Pro Webcam C920                             | 6         | 2.7%    |
| Syntek Integrated Camera                                | 5         | 2.25%   |
| Realtek Integrated_Webcam_HD                            | 5         | 2.25%   |
| Logitech Webcam C270                                    | 5         | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 2.25%   |
| Syntek Lenovo EasyCamera                                | 3         | 1.35%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.35%   |
| Lite-On Integrated Camera                               | 3         | 1.35%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 1.35%   |
| Chicony EasyCamera                                      | 3         | 1.35%   |
| Apple iPhone 5/5C/5S/6/SE                               | 3         | 1.35%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.35%   |
| Acer HD Webcam                                          | 3         | 1.35%   |
| Acer EasyCamera                                         | 3         | 1.35%   |
| Syntek EasyCamera                                       | 2         | 0.9%    |
| Sunplus HD WebCam                                       | 2         | 0.9%    |
| Sonix USB2.0 HD UVC WebCam                              | 2         | 0.9%    |
| Quanta HP TrueVision HD Camera                          | 2         | 0.9%    |
| Quanta HP HD Camera                                     | 2         | 0.9%    |
| Microsoft LifeCam HD-3000                               | 2         | 0.9%    |
| Microdia USB 2.0 Camera                                 | 2         | 0.9%    |
| Microdia Integrated Webcam                              | 2         | 0.9%    |
| Logitech Webcam C310                                    | 2         | 0.9%    |
| Logitech C922 Pro Stream Webcam                         | 2         | 0.9%    |
| Lite-On HP Wide Vision HD Camera                        | 2         | 0.9%    |
| Lite-On HP Webcam                                       | 2         | 0.9%    |
| Intel RealSense 3D Camera (Front F200)                  | 2         | 0.9%    |
| HP Webcam HD 2300                                       | 2         | 0.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 0.9%    |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.9%    |
| Chicony HP Webcam                                       | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 0.9%    |
| Y Media USB Camera                                      | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                      | 1         | 0.45%   |
| Valve Software 3D Camera                                | 1         | 0.45%   |
| Tobii AB EyeChip                                        | 1         | 0.45%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.45%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.45%   |
| Suyin HP TrueVision HD                                  | 1         | 0.45%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                      | 1         | 0.45%   |
| Sunplus FHD Camera Microphone                           | 1         | 0.45%   |
| Sunplus Asus Webcam                                     | 1         | 0.45%   |
| Silicon Motion Web Camera                               | 1         | 0.45%   |
| Ricoh HD Webcam                                         | 1         | 0.45%   |
| Realtek Webcam                                          | 1         | 0.45%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.45%   |
| Realtek USB HD Webcam                                   | 1         | 0.45%   |
| Realtek MTD Camera                                      | 1         | 0.45%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 0.45%   |
| Realtek Integrated Webcam_HD                            | 1         | 0.45%   |
| Realtek Integrated Webcam                               | 1         | 0.45%   |
| Realtek EasyCamera                                      | 1         | 0.45%   |
| Razer USA Gaming Webcam [Kiyo]                          | 1         | 0.45%   |
| Quanta VGA WebCam                                       | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 45.83%  |
| Validity Sensors           | 14        | 29.17%  |
| Shenzhen Goodix Technology | 9         | 18.75%  |
| LighTuning Technology      | 2         | 4.17%   |
| Upek                       | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 9         | 18.75%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 10.42%  |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 10.42%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 8.33%   |
| Synaptics  WBDI                                                            | 4         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 8.33%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.08%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.08%   |
| Validity Sensors VFS491                                                    | 1         | 2.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 55.56%  |
| Alcor Micro | 6         | 33.33%  |
| Lenovo      | 1         | 5.56%   |
| HID Global  | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 31.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 26.32%  |
| Broadcom 58200                                                               | 3         | 15.79%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10.53%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.26%   |
| HID Global USB Reader V3                                                     | 1         | 5.26%   |
| Broadcom 5880                                                                | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 227       | 63.94%  |
| 1     | 104       | 29.3%   |
| 2     | 24        | 6.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 33.57%  |
| Net/ethernet             | 26        | 18.18%  |
| Chipcard                 | 16        | 11.19%  |
| Multimedia controller    | 13        | 9.09%   |
| Graphics card            | 13        | 9.09%   |
| Net/wireless             | 9         | 6.29%   |
| Bluetooth                | 6         | 4.2%    |
| Network                  | 5         | 3.5%    |
| Camera                   | 2         | 1.4%    |
| Unassigned class         | 1         | 0.7%    |
| Storage                  | 1         | 0.7%    |
| Modem                    | 1         | 0.7%    |
| Dvb card                 | 1         | 0.7%    |
| Communication controller | 1         | 0.7%    |


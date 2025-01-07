Linux in Estonia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Estonia/Desktop/README.md) and [notebooks](/Location/Estonia/Notebook/README.md).

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

Total: 575

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8470p             | Notebook    | [7a5df9412c](https://linux-hardware.org/?probe=7a5df9412c) | Dec 31, 2024 |
| Dell          | Latitude 7640               | Notebook    | [931523acc9](https://linux-hardware.org/?probe=931523acc9) | Dec 28, 2024 |
| Intel         | HM570                       | Desktop     | [74847a808d](https://linux-hardware.org/?probe=74847a808d) | Dec 21, 2024 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34567a9026](https://linux-hardware.org/?probe=34567a9026) | Dec 20, 2024 |
| Dell          | System XPS 15Z              | Notebook    | [9e7fc2d36e](https://linux-hardware.org/?probe=9e7fc2d36e) | Dec 20, 2024 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [c511952a11](https://linux-hardware.org/?probe=c511952a11) | Dec 19, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [9c3c2fb92b](https://linux-hardware.org/?probe=9c3c2fb92b) | Dec 13, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [b3ea15c92e](https://linux-hardware.org/?probe=b3ea15c92e) | Dec 12, 2024 |
| Supermicro    | H13SAE-MF                   | Server      | [cab997495e](https://linux-hardware.org/?probe=cab997495e) | Dec 11, 2024 |
| MACHINIST     | E5-RS9 V1.1                 | Desktop     | [9f5f41fa91](https://linux-hardware.org/?probe=9f5f41fa91) | Dec 07, 2024 |
| Lenovo        | ThinkPad T460s 20F9003RM... | Notebook    | [5092bec86b](https://linux-hardware.org/?probe=5092bec86b) | Dec 07, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e51903f612](https://linux-hardware.org/?probe=e51903f612) | Dec 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4e0782715d](https://linux-hardware.org/?probe=4e0782715d) | Dec 02, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [469069638e](https://linux-hardware.org/?probe=469069638e) | Dec 01, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [458a67a9e4](https://linux-hardware.org/?probe=458a67a9e4) | Nov 30, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [f03062334f](https://linux-hardware.org/?probe=f03062334f) | Nov 29, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [5a464dff99](https://linux-hardware.org/?probe=5a464dff99) | Nov 27, 2024 |
| Toshiba       | Satellite L870-120          | Notebook    | [44263921b6](https://linux-hardware.org/?probe=44263921b6) | Nov 26, 2024 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [8af2b2f494](https://linux-hardware.org/?probe=8af2b2f494) | Nov 24, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [ac01b2a1d7](https://linux-hardware.org/?probe=ac01b2a1d7) | Nov 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | Notebook    | [2d30a85677](https://linux-hardware.org/?probe=2d30a85677) | Nov 18, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ccf9df80ca](https://linux-hardware.org/?probe=ccf9df80ca) | Nov 11, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [7b749bf585](https://linux-hardware.org/?probe=7b749bf585) | Nov 11, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6dda519942](https://linux-hardware.org/?probe=6dda519942) | Nov 07, 2024 |
| Dell          | Latitude 7640               | Notebook    | [f092c8cc9f](https://linux-hardware.org/?probe=f092c8cc9f) | Oct 27, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [25a5b7315a](https://linux-hardware.org/?probe=25a5b7315a) | Oct 21, 2024 |
| HP            | Compaq 6910p                | Notebook    | [2d33276514](https://linux-hardware.org/?probe=2d33276514) | Oct 17, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [676dd2d194](https://linux-hardware.org/?probe=676dd2d194) | Oct 14, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [ec688a0cae](https://linux-hardware.org/?probe=ec688a0cae) | Oct 13, 2024 |
| Dell          | XPS L322X                   | Notebook    | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [d55aedf9d2](https://linux-hardware.org/?probe=d55aedf9d2) | Oct 06, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [e93a1db49f](https://linux-hardware.org/?probe=e93a1db49f) | Oct 06, 2024 |
| Intel         | JSL MRD                     | Desktop     | [8ccee12f0f](https://linux-hardware.org/?probe=8ccee12f0f) | Oct 02, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [29d2b26873](https://linux-hardware.org/?probe=29d2b26873) | Sep 30, 2024 |
| Intel         | DH61CR AAG14064-208         | Desktop     | [10e7fcebd5](https://linux-hardware.org/?probe=10e7fcebd5) | Sep 28, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [76e2b2a322](https://linux-hardware.org/?probe=76e2b2a322) | Sep 22, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a8bb2af7ad](https://linux-hardware.org/?probe=a8bb2af7ad) | Sep 20, 2024 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6f566682d4](https://linux-hardware.org/?probe=6f566682d4) | Sep 19, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [7b97957b7a](https://linux-hardware.org/?probe=7b97957b7a) | Sep 10, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [c107b751c7](https://linux-hardware.org/?probe=c107b751c7) | Sep 03, 2024 |
| MSI           | B75MA-P45                   | Desktop     | [177c4ba401](https://linux-hardware.org/?probe=177c4ba401) | Sep 01, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [d05b98ac9f](https://linux-hardware.org/?probe=d05b98ac9f) | Sep 01, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [14e3740dda](https://linux-hardware.org/?probe=14e3740dda) | Aug 22, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [04fbf91f84](https://linux-hardware.org/?probe=04fbf91f84) | Aug 22, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0bfe4993d8](https://linux-hardware.org/?probe=0bfe4993d8) | Aug 22, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [83343a4a26](https://linux-hardware.org/?probe=83343a4a26) | Aug 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [b3dd1179a9](https://linux-hardware.org/?probe=b3dd1179a9) | Aug 05, 2024 |
| Dell          | Latitude 3340               | Notebook    | [533fe2ea9d](https://linux-hardware.org/?probe=533fe2ea9d) | Aug 04, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c3feea4b6d](https://linux-hardware.org/?probe=c3feea4b6d) | Aug 03, 2024 |
| Dell          | XPS L322X                   | Notebook    | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | Notebook    | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Dell          | Latitude E7450              | Notebook    | [ba9d36e59d](https://linux-hardware.org/?probe=ba9d36e59d) | Jul 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [c83514f0ef](https://linux-hardware.org/?probe=c83514f0ef) | Jul 13, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0050e9851f](https://linux-hardware.org/?probe=0050e9851f) | Jul 08, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [9d85820d8a](https://linux-hardware.org/?probe=9d85820d8a) | Jul 06, 2024 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [b5dfce71c0](https://linux-hardware.org/?probe=b5dfce71c0) | Jul 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8046341f97](https://linux-hardware.org/?probe=8046341f97) | Jul 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a4411a1a03](https://linux-hardware.org/?probe=a4411a1a03) | Jul 03, 2024 |
| Notebook      | PE60RNE_RND_RNC             | Notebook    | [82b61a10fa](https://linux-hardware.org/?probe=82b61a10fa) | Jul 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [64bd09dae7](https://linux-hardware.org/?probe=64bd09dae7) | Jul 02, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | Notebook    | [a311daa558](https://linux-hardware.org/?probe=a311daa558) | Jul 01, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | Notebook    | [8df67624a1](https://linux-hardware.org/?probe=8df67624a1) | Jul 01, 2024 |
| ASRock        | B460 Steel Legend           | Desktop     | [937d1eb881](https://linux-hardware.org/?probe=937d1eb881) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [7cb4543c27](https://linux-hardware.org/?probe=7cb4543c27) | Jun 30, 2024 |
| Dell          | Latitude 5431               | Notebook    | [b945bd0e46](https://linux-hardware.org/?probe=b945bd0e46) | Jun 21, 2024 |
| Dell          | XPS L322X                   | Notebook    | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | Notebook    | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Dell          | Latitude 5431               | Notebook    | [7469c5f44a](https://linux-hardware.org/?probe=7469c5f44a) | Jun 17, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [161e412652](https://linux-hardware.org/?probe=161e412652) | Jun 09, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [f265233665](https://linux-hardware.org/?probe=f265233665) | Jun 05, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [8534f873cf](https://linux-hardware.org/?probe=8534f873cf) | May 24, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [548c48e57a](https://linux-hardware.org/?probe=548c48e57a) | May 21, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fbc31b1a58](https://linux-hardware.org/?probe=fbc31b1a58) | May 19, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [8818119aed](https://linux-hardware.org/?probe=8818119aed) | May 16, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [536f8ed319](https://linux-hardware.org/?probe=536f8ed319) | May 09, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [2dee9df53a](https://linux-hardware.org/?probe=2dee9df53a) | May 02, 2024 |
| Dell          | Latitude 3300               | Notebook    | [639fb8097f](https://linux-hardware.org/?probe=639fb8097f) | May 02, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| Acer          | Extensa 5620                | Notebook    | [4150199b68](https://linux-hardware.org/?probe=4150199b68) | Apr 29, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [01d705d92b](https://linux-hardware.org/?probe=01d705d92b) | Apr 25, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Gigabyte      | H81M-S                      | Desktop     | [d18c354852](https://linux-hardware.org/?probe=d18c354852) | Mar 31, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | Notebook    | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d13f0a354c](https://linux-hardware.org/?probe=d13f0a354c) | Mar 21, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| HP            | 650                         | Notebook    | [d58bfc527e](https://linux-hardware.org/?probe=d58bfc527e) | Mar 17, 2024 |
| ASRock        | H310M-HDV                   | Desktop     | [4e2f714f49](https://linux-hardware.org/?probe=4e2f714f49) | Mar 16, 2024 |
| ASRock        | H310M-HDV                   | Desktop     | [8d62cae785](https://linux-hardware.org/?probe=8d62cae785) | Mar 15, 2024 |
| MSI           | B85M-G43                    | Desktop     | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [8c9bcaf098](https://linux-hardware.org/?probe=8c9bcaf098) | Mar 14, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [16dee4c095](https://linux-hardware.org/?probe=16dee4c095) | Mar 13, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | Notebook    | [d3de9797e5](https://linux-hardware.org/?probe=d3de9797e5) | Mar 07, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | Notebook    | [48c9ed444c](https://linux-hardware.org/?probe=48c9ed444c) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | Notebook    | [a8c23be08a](https://linux-hardware.org/?probe=a8c23be08a) | Mar 05, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66295fb0e8](https://linux-hardware.org/?probe=66295fb0e8) | Mar 04, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [9dbfe4a6eb](https://linux-hardware.org/?probe=9dbfe4a6eb) | Mar 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7c8e1659f2](https://linux-hardware.org/?probe=7c8e1659f2) | Feb 24, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b1c2e786ed](https://linux-hardware.org/?probe=b1c2e786ed) | Feb 17, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0ea90e3ee0](https://linux-hardware.org/?probe=0ea90e3ee0) | Feb 17, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [50746a2234](https://linux-hardware.org/?probe=50746a2234) | Feb 09, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [779b399243](https://linux-hardware.org/?probe=779b399243) | Feb 09, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [07deb1efe3](https://linux-hardware.org/?probe=07deb1efe3) | Feb 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| MSI           | Pulse GL66 11UDK            | Notebook    | [fdb748bed5](https://linux-hardware.org/?probe=fdb748bed5) | Jan 13, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [7536a68c05](https://linux-hardware.org/?probe=7536a68c05) | Jan 06, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [8991ffeadc](https://linux-hardware.org/?probe=8991ffeadc) | Jan 04, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [0863d91cdc](https://linux-hardware.org/?probe=0863d91cdc) | Dec 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c1069bda0b](https://linux-hardware.org/?probe=c1069bda0b) | Dec 23, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e222a97c0b](https://linux-hardware.org/?probe=e222a97c0b) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9c4f708056](https://linux-hardware.org/?probe=9c4f708056) | Dec 10, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [62734db5de](https://linux-hardware.org/?probe=62734db5de) | Dec 10, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [be768fb273](https://linux-hardware.org/?probe=be768fb273) | Dec 06, 2023 |
| HP            | 8619                        | Desktop     | [a33e273f33](https://linux-hardware.org/?probe=a33e273f33) | Dec 04, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [bb0ded92ef](https://linux-hardware.org/?probe=bb0ded92ef) | Dec 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [a1ab0858a6](https://linux-hardware.org/?probe=a1ab0858a6) | Dec 01, 2023 |
| HP            | ProBook 4530s               | Notebook    | [5743a3e441](https://linux-hardware.org/?probe=5743a3e441) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Dell          | Precision M4600             | Notebook    | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Dell          | Precision M4600             | Notebook    | [af124219eb](https://linux-hardware.org/?probe=af124219eb) | Nov 18, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [84650e7d6f](https://linux-hardware.org/?probe=84650e7d6f) | Nov 15, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [be33944c69](https://linux-hardware.org/?probe=be33944c69) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| ECS           | H61H2-M12                   | Desktop     | [885cbf522c](https://linux-hardware.org/?probe=885cbf522c) | Oct 28, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [235eadfef8](https://linux-hardware.org/?probe=235eadfef8) | Oct 18, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [42b86ea4ec](https://linux-hardware.org/?probe=42b86ea4ec) | Oct 18, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [506accae39](https://linux-hardware.org/?probe=506accae39) | Oct 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | Notebook    | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [9044f3b345](https://linux-hardware.org/?probe=9044f3b345) | Sep 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | Notebook    | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | Notebook    | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | Notebook    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | Notebook    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d78e4ab87d](https://linux-hardware.org/?probe=d78e4ab87d) | Aug 08, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Intel         | powered classmate PC        | Notebook    | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | Desktop     | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | Notebook    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | Notebook    | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| HP            | 304Ah                       | Desktop     | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6694c9279d](https://linux-hardware.org/?probe=6694c9279d) | Mar 31, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | Notebook    | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [396ad2d6aa](https://linux-hardware.org/?probe=396ad2d6aa) | Mar 04, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [07d496ada9](https://linux-hardware.org/?probe=07d496ada9) | Feb 04, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70436ae3c3](https://linux-hardware.org/?probe=70436ae3c3) | Dec 15, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4c5bac90eb](https://linux-hardware.org/?probe=4c5bac90eb) | Dec 15, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [2ace77f72c](https://linux-hardware.org/?probe=2ace77f72c) | Dec 14, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [0b91c8c70f](https://linux-hardware.org/?probe=0b91c8c70f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | Notebook    | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASRock        | B460 Steel Legend           | Desktop     | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Unknown       | Seagate Personal Cloud (... | Desktop     | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [5dae076f42](https://linux-hardware.org/?probe=5dae076f42) | Jul 27, 2022 |
| ECS           | G41T-M7                     | Desktop     | [a531a754a8](https://linux-hardware.org/?probe=a531a754a8) | Jul 23, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | 3646h                       | Desktop     | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [cdb4149eba](https://linux-hardware.org/?probe=cdb4149eba) | Jun 27, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a068a18649](https://linux-hardware.org/?probe=a068a18649) | Jun 08, 2022 |
| Dell          | 088DT1 A00                  | Desktop     | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| HP            | Presario CQ57               | Notebook    | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | Desktop     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | Notebook    | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | Notebook    | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | Notebook    | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| HP            | 18E9                        | Desktop     | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d34e3c79a0](https://linux-hardware.org/?probe=d34e3c79a0) | Mar 01, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| HP            | 304Ah                       | Desktop     | [078b605c39](https://linux-hardware.org/?probe=078b605c39) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [c9b246d9a8](https://linux-hardware.org/?probe=c9b246d9a8) | Jan 12, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [49234f883d](https://linux-hardware.org/?probe=49234f883d) | Jan 12, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Dell          | 0KH290                      | Desktop     | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [201bc8d044](https://linux-hardware.org/?probe=201bc8d044) | Oct 17, 2021 |
| Getac         | B300G4                      | Notebook    | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | Notebook    | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | Notebook    | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [95d389bfe5](https://linux-hardware.org/?probe=95d389bfe5) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [326b3f5892](https://linux-hardware.org/?probe=326b3f5892) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [c2c6287186](https://linux-hardware.org/?probe=c2c6287186) | Oct 07, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d339553d59](https://linux-hardware.org/?probe=d339553d59) | Sep 19, 2021 |
| Prestigio     | PNT10131DEDB                | Convertible | [39dc1df1df](https://linux-hardware.org/?probe=39dc1df1df) | Sep 18, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [47fb03fde8](https://linux-hardware.org/?probe=47fb03fde8) | Sep 17, 2021 |
| MSI           | MS-B901                     | All in one  | [282992f343](https://linux-hardware.org/?probe=282992f343) | Sep 14, 2021 |
| MSI           | MS-B901                     | All in one  | [3a288bcc81](https://linux-hardware.org/?probe=3a288bcc81) | Sep 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | Notebook    | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bf81c78371](https://linux-hardware.org/?probe=bf81c78371) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | Notebook    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [559742f4d7](https://linux-hardware.org/?probe=559742f4d7) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d28cc83aed](https://linux-hardware.org/?probe=d28cc83aed) | Aug 17, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [be5db43316](https://linux-hardware.org/?probe=be5db43316) | Aug 17, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [286d06cd5e](https://linux-hardware.org/?probe=286d06cd5e) | Aug 15, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| MSI           | GP62M 7RDX                  | Notebook    | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | M3N78                       | Desktop     | [810e386d8b](https://linux-hardware.org/?probe=810e386d8b) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | Notebook    | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | Notebook    | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | Notebook    | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | Notebook    | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| MSI           | B250M PRO-VD                | Desktop     | [20ff770033](https://linux-hardware.org/?probe=20ff770033) | Apr 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | Notebook    | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [72b40a39d4](https://linux-hardware.org/?probe=72b40a39d4) | Mar 25, 2021 |
| Samsung       | R410                        | Notebook    | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f555918663](https://linux-hardware.org/?probe=f555918663) | Mar 24, 2021 |
| Samsung       | R410                        | Notebook    | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| OEM           | Intel H81                   | Desktop     | [385b6ee448](https://linux-hardware.org/?probe=385b6ee448) | Mar 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [013a785195](https://linux-hardware.org/?probe=013a785195) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b991380f9](https://linux-hardware.org/?probe=9b991380f9) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [273fba9fd2](https://linux-hardware.org/?probe=273fba9fd2) | Mar 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [75a661f9f8](https://linux-hardware.org/?probe=75a661f9f8) | Mar 14, 2021 |
| Notebook      | W35xSS_370SS                | Notebook    | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ff698cacf3](https://linux-hardware.org/?probe=ff698cacf3) | Feb 27, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [116202ee88](https://linux-hardware.org/?probe=116202ee88) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 766112G        | Notebook    | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | Notebook    | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [b987c1ad14](https://linux-hardware.org/?probe=b987c1ad14) | Feb 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e1dc5a8ea7](https://linux-hardware.org/?probe=e1dc5a8ea7) | Feb 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d3004980ee](https://linux-hardware.org/?probe=d3004980ee) | Feb 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| MSI           | Z77A-G41                    | Desktop     | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| Timi          | RedmiBook 16                | Notebook    | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | Notebook    | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| MSI           | H81I                        | Desktop     | [772ce7ff24](https://linux-hardware.org/?probe=772ce7ff24) | Dec 03, 2020 |
| MSI           | Boston                      | Desktop     | [9843e15faa](https://linux-hardware.org/?probe=9843e15faa) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [1280ebbedf](https://linux-hardware.org/?probe=1280ebbedf) | Nov 17, 2020 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [e1f6c727d9](https://linux-hardware.org/?probe=e1f6c727d9) | Oct 14, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f61cacc391](https://linux-hardware.org/?probe=f61cacc391) | Oct 05, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | Notebook    | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [6b818c1352](https://linux-hardware.org/?probe=6b818c1352) | Sep 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3255a17583](https://linux-hardware.org/?probe=3255a17583) | Sep 28, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf22d328e](https://linux-hardware.org/?probe=bcf22d328e) | Sep 28, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| Intel         | DX79TO AAG28805-400         | Desktop     | [d4cdc0726f](https://linux-hardware.org/?probe=d4cdc0726f) | Sep 26, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [118729faeb](https://linux-hardware.org/?probe=118729faeb) | Sep 23, 2020 |
| TUXEDO        | Book BA1510                 | Notebook    | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | Notebook    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | Notebook    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0dd7682249](https://linux-hardware.org/?probe=0dd7682249) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | Notebook    | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | Notebook    | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | Notebook    | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| ASRock        | P45DE3                      | Desktop     | [3fce267079](https://linux-hardware.org/?probe=3fce267079) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [5b48876c88](https://linux-hardware.org/?probe=5b48876c88) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [420e531d0c](https://linux-hardware.org/?probe=420e531d0c) | Aug 11, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [fd8d68081e](https://linux-hardware.org/?probe=fd8d68081e) | Aug 08, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [30d102a39e](https://linux-hardware.org/?probe=30d102a39e) | Aug 07, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | Notebook    | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | Notebook    | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | Notebook    | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| ASRock        | B250M Pro4                  | Desktop     | [3ad9bafdc1](https://linux-hardware.org/?probe=3ad9bafdc1) | Jul 19, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [43684f5ded](https://linux-hardware.org/?probe=43684f5ded) | Jul 15, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [caa5d2a038](https://linux-hardware.org/?probe=caa5d2a038) | Jul 13, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [751ba49889](https://linux-hardware.org/?probe=751ba49889) | Jul 09, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [3149f0037a](https://linux-hardware.org/?probe=3149f0037a) | Jul 03, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9bd5a64d0d](https://linux-hardware.org/?probe=9bd5a64d0d) | Jun 25, 2020 |
| HP            | Presario CQ56               | Notebook    | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | Boston                      | Desktop     | [48a3bf1932](https://linux-hardware.org/?probe=48a3bf1932) | Jun 02, 2020 |
| Samsung       | 535U3C                      | Notebook    | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [869444acf6](https://linux-hardware.org/?probe=869444acf6) | May 26, 2020 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [d4e3d725fa](https://linux-hardware.org/?probe=d4e3d725fa) | May 19, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | Notebook    | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| MSI           | B360-A PRO                  | Desktop     | [c42cb75770](https://linux-hardware.org/?probe=c42cb75770) | Apr 24, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | Notebook    | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [76af4a7e0b](https://linux-hardware.org/?probe=76af4a7e0b) | Mar 21, 2020 |
| ASRock        | P45DE3                      | Desktop     | [fffef664cd](https://linux-hardware.org/?probe=fffef664cd) | Mar 18, 2020 |
| MSI           | B75A-G43                    | Desktop     | [9683ec9bd4](https://linux-hardware.org/?probe=9683ec9bd4) | Mar 16, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | Notebook    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [63e19ed1f4](https://linux-hardware.org/?probe=63e19ed1f4) | Feb 28, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [adc15c7147](https://linux-hardware.org/?probe=adc15c7147) | Feb 24, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b17f2abd3e](https://linux-hardware.org/?probe=b17f2abd3e) | Feb 20, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Gigabyte      | H81M-S1                     | Desktop     | [754bdf88c1](https://linux-hardware.org/?probe=754bdf88c1) | Jan 26, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [1eb5f177d1](https://linux-hardware.org/?probe=1eb5f177d1) | Jan 13, 2020 |
| Dell          | 0D28YY A01                  | Desktop     | [be51211fe3](https://linux-hardware.org/?probe=be51211fe3) | Dec 09, 2019 |
| Dell          | Latitude 5289               | Convertible | [dfdc8c484f](https://linux-hardware.org/?probe=dfdc8c484f) | Dec 04, 2019 |
| Gigabyte      | H81M-S1                     | Desktop     | [57524ab581](https://linux-hardware.org/?probe=57524ab581) | Dec 03, 2019 |
| Dell          | Precision 5510              | Notebook    | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| ASUSTek       | VM60                        | Desktop     | [4842363a0b](https://linux-hardware.org/?probe=4842363a0b) | Nov 14, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [8beb57338d](https://linux-hardware.org/?probe=8beb57338d) | Oct 02, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [abc398724a](https://linux-hardware.org/?probe=abc398724a) | Sep 16, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [f6acac9fc8](https://linux-hardware.org/?probe=f6acac9fc8) | Sep 15, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d2b5c32d2f](https://linux-hardware.org/?probe=d2b5c32d2f) | Sep 15, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | Notebook    | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | Notebook    | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | Notebook    | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| HP            | 1495                        | Desktop     | [3d9e77ae8a](https://linux-hardware.org/?probe=3d9e77ae8a) | Jul 23, 2019 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [46e1a9fc55](https://linux-hardware.org/?probe=46e1a9fc55) | Jul 04, 2019 |
| Dell          | Inspiron 5558               | Notebook    | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | Notebook    | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [3a8d19c8fc](https://linux-hardware.org/?probe=3a8d19c8fc) | Jun 22, 2019 |
| Gigabyte      | 970-GAMING                  | Desktop     | [aa1385d100](https://linux-hardware.org/?probe=aa1385d100) | Jun 03, 2019 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | Notebook    | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [7f57ad053d](https://linux-hardware.org/?probe=7f57ad053d) | May 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Dell          | Latitude 5289               | Convertible | [e28d069f05](https://linux-hardware.org/?probe=e28d069f05) | May 07, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Dell          | 0KP561                      | Desktop     | [bba0fe2672](https://linux-hardware.org/?probe=bba0fe2672) | Apr 05, 2019 |
| Dell          | 0KP561                      | Desktop     | [f3085d1ae9](https://linux-hardware.org/?probe=f3085d1ae9) | Apr 04, 2019 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ba39531b87](https://linux-hardware.org/?probe=ba39531b87) | Mar 31, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | Notebook    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | 18E7                        | Desktop     | [19df4fb560](https://linux-hardware.org/?probe=19df4fb560) | Feb 22, 2019 |
| HP            | ProBook 470 G1              | Notebook    | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| ABIT          | KN9 Series                  | Desktop     | [10015b723b](https://linux-hardware.org/?probe=10015b723b) | Feb 04, 2019 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [f1a9b27e5c](https://linux-hardware.org/?probe=f1a9b27e5c) | Feb 04, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [b702949950](https://linux-hardware.org/?probe=b702949950) | Dec 19, 2018 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [158fb83dcc](https://linux-hardware.org/?probe=158fb83dcc) | Nov 13, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [a00ad66604](https://linux-hardware.org/?probe=a00ad66604) | Oct 24, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [9c47ffacd5](https://linux-hardware.org/?probe=9c47ffacd5) | Oct 24, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | Notebook    | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | Notebook    | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| ECS           | H55H-3.8L                   | Desktop     | [7e782321c8](https://linux-hardware.org/?probe=7e782321c8) | Mar 31, 2018 |
| Dell          | Inspiron N5110              | Notebook    | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [78791d4918](https://linux-hardware.org/?probe=78791d4918) | Sep 13, 2017 |
| Acer          | Aspire 6530G                | Notebook    | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| ASUSTek       | P8H67                       | Desktop     | [e36d00c6f9](https://linux-hardware.org/?probe=e36d00c6f9) | Jul 21, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | Notebook    | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | Notebook    | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| ECS           | nVidia-nForce               | Desktop     | [db8fd734f9](https://linux-hardware.org/?probe=db8fd734f9) | May 16, 2017 |
| HP            | Pavilion dv5                | Notebook    | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | Notebook    | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | Notebook    | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | Notebook    | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | Notebook    | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | Notebook    | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Estonia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 7.37%   |
| Ubuntu 22.04                 | 31        | 7.14%   |
| Ubuntu 18.04                 | 22        | 5.07%   |
| Arch Rolling                 | 22        | 5.07%   |
| ArcoLinux Rolling            | 11        | 2.53%   |
| ROSA R11                     | 10        | 2.3%    |
| Debian 12                    | 10        | 2.3%    |
| Arch                         | 10        | 2.3%    |
| OpenMandriva 4.3             | 9         | 2.07%   |
| Fedora 34                    | 8         | 1.84%   |
| Ubuntu 19.04                 | 7         | 1.61%   |
| ROSA R8.1                    | 7         | 1.61%   |
| Manjaro                      | 7         | 1.61%   |
| Kubuntu 20.04                | 7         | 1.61%   |
| Ubuntu MATE 22.04            | 6         | 1.38%   |
| Ubuntu 24.04                 | 6         | 1.38%   |
| Pop!_OS 22.04                | 6         | 1.38%   |
| Linux Mint 20.1              | 6         | 1.38%   |
| Debian 11                    | 6         | 1.38%   |
| ROSA 12.2                    | 5         | 1.15%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.15%   |
| OpenMandriva 4.2             | 5         | 1.15%   |
| Fedora 36                    | 5         | 1.15%   |
| Fedora 35                    | 5         | 1.15%   |
| EndeavourOS Rolling          | 5         | 1.15%   |
| ROSA R9                      | 4         | 0.92%   |
| Kubuntu 22.04                | 4         | 0.92%   |
| KDE neon 20.04               | 4         | 0.92%   |
| Zorin 17                     | 3         | 0.69%   |
| Zorin 16                     | 3         | 0.69%   |
| Ubuntu 21.10                 | 3         | 0.69%   |
| Ubuntu 19.10                 | 3         | 0.69%   |
| ROSA R10                     | 3         | 0.69%   |
| Pop!_OS 20.04                | 3         | 0.69%   |
| Nobara 37                    | 3         | 0.69%   |
| Linux Mint 21.3              | 3         | 0.69%   |
| Linux Mint 21.2              | 3         | 0.69%   |
| Linux Mint 20.3              | 3         | 0.69%   |
| KDE neon 22.04               | 3         | 0.69%   |
| Gentoo 2.6                   | 3         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 110       | 26.07%  |
| ROSA         | 35        | 8.29%   |
| Fedora       | 33        | 7.82%   |
| Arch         | 32        | 7.58%   |
| Linux Mint   | 24        | 5.69%   |
| Debian       | 22        | 5.21%   |
| OpenMandriva | 20        | 4.74%   |
| Manjaro      | 17        | 4.03%   |
| Pop!_OS      | 13        | 3.08%   |
| Kubuntu      | 12        | 2.84%   |
| ArcoLinux    | 11        | 2.61%   |
| Xubuntu      | 8         | 1.9%    |
| Ubuntu MATE  | 8         | 1.9%    |
| Zorin        | 7         | 1.66%   |
| KDE neon     | 7         | 1.66%   |
| openSUSE     | 6         | 1.42%   |
| Nobara       | 5         | 1.18%   |
| EndeavourOS  | 5         | 1.18%   |
| Elementary   | 5         | 1.18%   |
| Gentoo       | 4         | 0.95%   |
| Endless      | 4         | 0.95%   |
| SteamOS      | 3         | 0.71%   |
| Reborn OS    | 3         | 0.71%   |
| Methaneos    | 3         | 0.71%   |
| Lubuntu      | 3         | 0.71%   |
| Kali         | 3         | 0.71%   |
| Clear Linux  | 3         | 0.71%   |
| MX           | 2         | 0.47%   |
| LMDE         | 2         | 0.47%   |
| ChimeraOS    | 2         | 0.47%   |
| CachyOS      | 2         | 0.47%   |
| Xero         | 1         | 0.24%   |
| Ubuntu Unity | 1         | 0.24%   |
| TUXEDO OS    | 1         | 0.24%   |
| Parrot       | 1         | 0.24%   |
| NixOS        | 1         | 0.24%   |
| Devuan       | 1         | 0.24%   |
| Bazzite      | 1         | 0.24%   |
| ALT Linux    | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003             | 9         | 1.93%   |
| 5.4.0-42-generic                    | 8         | 1.72%   |
| 6.1.0-13-amd64                      | 5         | 1.07%   |
| 5.15.0-52-generic                   | 5         | 1.07%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.07%   |
| 6.8.0-49-generic                    | 4         | 0.86%   |
| 6.2.0-26-generic                    | 4         | 0.86%   |
| 5.15.0-53-generic                   | 4         | 0.86%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 0.86%   |
| 6.8.0-41-generic                    | 3         | 0.64%   |
| 5.4.0-65-generic                    | 3         | 0.64%   |
| 5.4.0-47-generic                    | 3         | 0.64%   |
| 5.4.0-28-generic                    | 3         | 0.64%   |
| 5.15.0-56-generic                   | 3         | 0.64%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 3         | 0.64%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3         | 0.64%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 0.64%   |
| 6.9.6-methane-jn27                  | 2         | 0.43%   |
| 6.9.3-76060903-generic              | 2         | 0.43%   |
| 6.8.0-45-generic                    | 2         | 0.43%   |
| 6.8.0-31-generic                    | 2         | 0.43%   |
| 6.5.0-9-generic                     | 2         | 0.43%   |
| 6.5.0-45-generic                    | 2         | 0.43%   |
| 6.5.0-35-generic                    | 2         | 0.43%   |
| 6.5.0-14-generic                    | 2         | 0.43%   |
| 6.2.6-desktop-1omv2390              | 2         | 0.43%   |
| 6.2.0-39-generic                    | 2         | 0.43%   |
| 6.10.10-zen1-1-zen                  | 2         | 0.43%   |
| 6.1.1-desktop-1omv2290              | 2         | 0.43%   |
| 6.1.0-kali7-amd64                   | 2         | 0.43%   |
| 6.1.0-18-amd64                      | 2         | 0.43%   |
| 5.8.0-63-generic                    | 2         | 0.43%   |
| 5.8.0-53-generic                    | 2         | 0.43%   |
| 5.5.2-1-MANJARO                     | 2         | 0.43%   |
| 5.4.0-88-generic                    | 2         | 0.43%   |
| 5.4.0-58-generic                    | 2         | 0.43%   |
| 5.4.0-53-generic                    | 2         | 0.43%   |
| 5.4.0-45-generic                    | 2         | 0.43%   |
| 5.4.0-33-generic                    | 2         | 0.43%   |
| 5.4.0-29-generic                    | 2         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 48        | 10.62%  |
| 5.15.0   | 32        | 7.08%   |
| 4.15.0   | 27        | 5.97%   |
| 6.5.0    | 16        | 3.54%   |
| 5.11.0   | 15        | 3.32%   |
| 6.8.0    | 13        | 2.88%   |
| 5.13.0   | 12        | 2.65%   |
| 6.1.0    | 11        | 2.43%   |
| 5.8.0    | 11        | 2.43%   |
| 6.2.0    | 10        | 2.21%   |
| 5.0.0    | 10        | 2.21%   |
| 5.16.7   | 9         | 1.99%   |
| 5.10.0   | 8         | 1.77%   |
| 5.3.0    | 6         | 1.33%   |
| 4.18.0   | 6         | 1.33%   |
| 6.2.6    | 5         | 1.11%   |
| 5.19.0   | 5         | 1.11%   |
| 5.10.14  | 5         | 1.11%   |
| 4.9.20   | 5         | 1.11%   |
| 6.9.3    | 4         | 0.88%   |
| 5.15.2   | 3         | 0.66%   |
| 5.13.12  | 3         | 0.66%   |
| 5.10.74  | 3         | 0.66%   |
| 5.10.118 | 3         | 0.66%   |
| 4.9.9    | 3         | 0.66%   |
| 6.9.6    | 2         | 0.44%   |
| 6.6.10   | 2         | 0.44%   |
| 6.5.6    | 2         | 0.44%   |
| 6.12.6   | 2         | 0.44%   |
| 6.11.9   | 2         | 0.44%   |
| 6.10.10  | 2         | 0.44%   |
| 6.10.0   | 2         | 0.44%   |
| 6.1.1    | 2         | 0.44%   |
| 6.0.9    | 2         | 0.44%   |
| 6.0.11   | 2         | 0.44%   |
| 5.8.10   | 2         | 0.44%   |
| 5.5.2    | 2         | 0.44%   |
| 5.17.1   | 2         | 0.44%   |
| 5.15.5   | 2         | 0.44%   |
| 5.13.19  | 2         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 54        | 12%     |
| 5.15    | 40        | 8.89%   |
| 6.1     | 27        | 6%      |
| 4.15    | 27        | 6%      |
| 5.10    | 26        | 5.78%   |
| 5.13    | 25        | 5.56%   |
| 5.11    | 20        | 4.44%   |
| 6.5     | 19        | 4.22%   |
| 6.8     | 16        | 3.56%   |
| 6.2     | 16        | 3.56%   |
| 5.8     | 14        | 3.11%   |
| 5.16    | 14        | 3.11%   |
| 4.9     | 14        | 3.11%   |
| 6.6     | 13        | 2.89%   |
| 6.11    | 11        | 2.44%   |
| 5.0     | 11        | 2.44%   |
| 6.10    | 9         | 2%      |
| 6.0     | 9         | 2%      |
| 6.9     | 8         | 1.78%   |
| 5.3     | 8         | 1.78%   |
| 5.14    | 8         | 1.78%   |
| 5.19    | 7         | 1.56%   |
| 5.17    | 6         | 1.33%   |
| 4.18    | 6         | 1.33%   |
| 6.7     | 5         | 1.11%   |
| 5.9     | 4         | 0.89%   |
| 5.5     | 4         | 0.89%   |
| 5.12    | 4         | 0.89%   |
| 4.19    | 4         | 0.89%   |
| 6.4     | 3         | 0.67%   |
| 6.12    | 3         | 0.67%   |
| 5.6     | 3         | 0.67%   |
| 5.18    | 3         | 0.67%   |
| 6.3     | 2         | 0.44%   |
| 4.1     | 2         | 0.44%   |
| 5.7     | 1         | 0.22%   |
| 5.1     | 1         | 0.22%   |
| 4.4     | 1         | 0.22%   |
| 4.10    | 1         | 0.22%   |
| 3.16    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 396       | 96.82%  |
| i686   | 12        | 2.93%   |
| armv7l | 1         | 0.24%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 155       | 36.3%   |
| KDE5       | 75        | 17.56%  |
| Unknown    | 48        | 11.24%  |
| XFCE       | 28        | 6.56%   |
| X-Cinnamon | 24        | 5.62%   |
| KDE4       | 20        | 4.68%   |
| KDE6       | 19        | 4.45%   |
| MATE       | 18        | 4.22%   |
| KDE        | 8         | 1.87%   |
| LXQt       | 7         | 1.64%   |
| Pantheon   | 5         | 1.17%   |
| i3         | 5         | 1.17%   |
| Budgie     | 3         | 0.7%    |
| Unity      | 2         | 0.47%   |
| sway       | 2         | 0.47%   |
| LXDE       | 2         | 0.47%   |
| awesome    | 2         | 0.47%   |
| Yoyo       | 1         | 0.23%   |
| openbox    | 1         | 0.23%   |
| Hyprland   | 1         | 0.23%   |
| Cinnamon   | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 292       | 69.86%  |
| Wayland | 104       | 24.88%  |
| Unknown | 16        | 3.83%   |
| Tty     | 5         | 1.2%    |
| Web     | 1         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 171       | 40.62%  |
| SDDM    | 87        | 20.67%  |
| GDM3    | 48        | 11.4%   |
| GDM     | 45        | 10.69%  |
| LightDM | 38        | 9.03%   |
| KDM     | 20        | 4.75%   |
| TDM     | 12        | 2.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 209       | 50.24%  |
| et_EE           | 61        | 14.66%  |
| Unknown         | 60        | 14.42%  |
| ru_RU           | 38        | 9.13%   |
| en_GB           | 19        | 4.57%   |
| C               | 8         | 1.92%   |
| de_DE           | 4         | 0.96%   |
| pl_PL           | 2         | 0.48%   |
| fr_FR           | 2         | 0.48%   |
| en_IE           | 2         | 0.48%   |
| en_DK           | 2         | 0.48%   |
| uk_UA           | 1         | 0.24%   |
| ru_UA           | 1         | 0.24%   |
| it_IT           | 1         | 0.24%   |
| es_MX           | 1         | 0.24%   |
| en_US.utf-8     | 1         | 0.24%   |
| en_US.iso885915 | 1         | 0.24%   |
| en_DE           | 1         | 0.24%   |
| en_BW           | 1         | 0.24%   |
| en_AU           | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 218       | 51.9%   |
| EFI  | 202       | 48.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 275       | 65.63%  |
| Btrfs   | 65        | 15.51%  |
| Overlay | 25        | 5.97%   |
| Tmpfs   | 20        | 4.77%   |
| Unknown | 20        | 4.77%   |
| Zfs     | 7         | 1.67%   |
| Xfs     | 4         | 0.95%   |
| Ext3    | 3         | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 193       | 46.28%  |
| Unknown | 172       | 41.25%  |
| MBR     | 52        | 12.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 348       | 83.65%  |
| Yes       | 68        | 16.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 288       | 69.06%  |
| Yes       | 129       | 30.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 92        | 22.49%  |
| ASUSTek Computer    | 60        | 14.67%  |
| Hewlett-Packard     | 53        | 12.96%  |
| Dell                | 45        | 11%     |
| MSI                 | 38        | 9.29%   |
| Gigabyte Technology | 30        | 7.33%   |
| Intel               | 12        | 2.93%   |
| ASRock              | 11        | 2.69%   |
| Acer                | 10        | 2.44%   |
| Samsung Electronics | 8         | 1.96%   |
| Apple               | 7         | 1.71%   |
| Valve               | 4         | 0.98%   |
| Fujitsu             | 4         | 0.98%   |
| ECS                 | 4         | 0.98%   |
| Notebook            | 3         | 0.73%   |
| TUXEDO              | 2         | 0.49%   |
| Toshiba             | 2         | 0.49%   |
| Timi                | 2         | 0.49%   |
| Supermicro          | 2         | 0.49%   |
| Quanta              | 2         | 0.49%   |
| Alienware           | 2         | 0.49%   |
| ZOTAC               | 1         | 0.24%   |
| Prestigio           | 1         | 0.24%   |
| Packard Bell        | 1         | 0.24%   |
| OEM                 | 1         | 0.24%   |
| mPTech              | 1         | 0.24%   |
| Microsoft           | 1         | 0.24%   |
| MACHINIST           | 1         | 0.24%   |
| HUAWEI              | 1         | 0.24%   |
| Huanan              | 1         | 0.24%   |
| GPD                 | 1         | 0.24%   |
| Getac               | 1         | 0.24%   |
| Fujitsu Siemens     | 1         | 0.24%   |
| Framework           | 1         | 0.24%   |
| Chuwi               | 1         | 0.24%   |
| ABIT                | 1         | 0.24%   |
| Unknown             | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Valve Jupiter                       | 4         | 0.98%   |
| ASUS All Series                     | 4         | 0.98%   |
| MSI MS-7C91                         | 3         | 0.73%   |
| HP EliteBook 8470p                  | 3         | 0.73%   |
| Quanta TWH                          | 2         | 0.49%   |
| MSI MS-7C37                         | 2         | 0.49%   |
| MSI MS-7C02                         | 2         | 0.49%   |
| MSI MS-7758                         | 2         | 0.49%   |
| Lenovo Y50-70 20378                 | 2         | 0.49%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 2         | 0.49%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 2         | 0.49%   |
| HP Pavilion dv7                     | 2         | 0.49%   |
| HP ENVY Laptop 13-ah0xxx            | 2         | 0.49%   |
| HP EliteBook 8460p                  | 2         | 0.49%   |
| HP EliteBook 840 G5                 | 2         | 0.49%   |
| HP EliteBook 840 G2                 | 2         | 0.49%   |
| HP Compaq 8100 Elite SFF PC         | 2         | 0.49%   |
| Gigabyte X570 AORUS PRO             | 2         | 0.49%   |
| Gigabyte Q87M-D2H                   | 2         | 0.49%   |
| Dell Latitude 7490                  | 2         | 0.49%   |
| Dell Inspiron N5110                 | 2         | 0.49%   |
| Dell Inspiron 5558                  | 2         | 0.49%   |
| ASUS ZenBook UX325EA_UX325EA        | 2         | 0.49%   |
| ASUS ROG STRIX B650E-E GAMING WIFI  | 2         | 0.49%   |
| ASUS ROG STRIX B550-F GAMING        | 2         | 0.49%   |
| ASUS PRIME X570-PRO                 | 2         | 0.49%   |
| ASUS PRIME B550M-K                  | 2         | 0.49%   |
| Apple MacBookPro9,2                 | 2         | 0.49%   |
| Alienware 17                        | 2         | 0.49%   |
| Unknown                             | 2         | 0.49%   |
| ZOTAC B410                          | 1         | 0.24%   |
| TUXEDO Polaris AMD Gen5             | 1         | 0.24%   |
| TUXEDO Book BA1510                  | 1         | 0.24%   |
| Toshiba Satellite L870-120          | 1         | 0.24%   |
| Toshiba Satellite L855              | 1         | 0.24%   |
| Timi RedmiBook 16                   | 1         | 0.24%   |
| Timi RedmiBook 14 II                | 1         | 0.24%   |
| Supermicro X10SLH-F/X10SLM+-F       | 1         | 0.24%   |
| Supermicro Super Server             | 1         | 0.24%   |
| Samsung R410                        | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 58        | 14.18%  |
| HP EliteBook       | 17        | 4.16%   |
| Dell Latitude      | 14        | 3.42%   |
| Dell Inspiron      | 9         | 2.2%    |
| ASUS PRIME         | 9         | 2.2%    |
| Lenovo IdeaPad     | 8         | 1.96%   |
| HP Pavilion        | 8         | 1.96%   |
| HP Compaq          | 7         | 1.71%   |
| Dell XPS           | 7         | 1.71%   |
| ASUS ROG           | 6         | 1.47%   |
| Acer Aspire        | 6         | 1.47%   |
| Dell Precision     | 5         | 1.22%   |
| Dell OptiPlex      | 5         | 1.22%   |
| Valve Jupiter      | 4         | 0.98%   |
| Lenovo ThinkCentre | 4         | 0.98%   |
| Lenovo Legion      | 4         | 0.98%   |
| HP ProBook         | 4         | 0.98%   |
| Gigabyte X570      | 4         | 0.98%   |
| ASUS ZenBook       | 4         | 0.98%   |
| ASUS VivoBook      | 4         | 0.98%   |
| ASUS TUF           | 4         | 0.98%   |
| ASUS All           | 4         | 0.98%   |
| MSI MS-7C91        | 3         | 0.73%   |
| Lenovo Yoga        | 3         | 0.73%   |
| Lenovo IdeaPadFlex | 3         | 0.73%   |
| HP Laptop          | 3         | 0.73%   |
| HP ENVY            | 3         | 0.73%   |
| Fujitsu LIFEBOOK   | 3         | 0.73%   |
| ASUS ASUS          | 3         | 0.73%   |
| Toshiba Satellite  | 2         | 0.49%   |
| Timi RedmiBook     | 2         | 0.49%   |
| Samsung 900X3C     | 2         | 0.49%   |
| Quanta TWH         | 2         | 0.49%   |
| MSI MS-7C37        | 2         | 0.49%   |
| MSI MS-7C02        | 2         | 0.49%   |
| MSI MS-7758        | 2         | 0.49%   |
| Lenovo Y50-70      | 2         | 0.49%   |
| HP ProDesk         | 2         | 0.49%   |
| HP Presario        | 2         | 0.49%   |
| HP OMEN            | 2         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 48        | 11.74%  |
| 2018    | 39        | 9.54%   |
| 2013    | 38        | 9.29%   |
| 2019    | 35        | 8.56%   |
| 2012    | 30        | 7.33%   |
| 2011    | 27        | 6.6%    |
| 2014    | 24        | 5.87%   |
| 2021    | 23        | 5.62%   |
| 2022    | 21        | 5.13%   |
| 2017    | 20        | 4.89%   |
| 2015    | 19        | 4.65%   |
| 2016    | 17        | 4.16%   |
| 2010    | 15        | 3.67%   |
| 2009    | 11        | 2.69%   |
| 2008    | 10        | 2.44%   |
| 2007    | 10        | 2.44%   |
| 2023    | 9         | 2.2%    |
| 2006    | 5         | 1.22%   |
| 2024    | 4         | 0.98%   |
| 2005    | 2         | 0.49%   |
| 2004    | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 245       | 59.9%   |
| Desktop     | 144       | 35.21%  |
| Convertible | 12        | 2.93%   |
| Mini pc     | 4         | 0.98%   |
| Server      | 2         | 0.49%   |
| Tablet      | 1         | 0.24%   |
| All in one  | 1         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 388       | 93.95%  |
| Enabled  | 25        | 6.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 409       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 93        | 22.52%  |
| 4.01-8.0    | 83        | 20.1%   |
| 8.01-16.0   | 77        | 18.64%  |
| 3.01-4.0    | 55        | 13.32%  |
| 32.01-64.0  | 53        | 12.83%  |
| 24.01-32.0  | 14        | 3.39%   |
| 64.01-256.0 | 13        | 3.15%   |
| 2.01-3.0    | 12        | 2.91%   |
| 1.01-2.0    | 10        | 2.42%   |
| 0.51-1.0    | 2         | 0.48%   |
| 0.01-0.5    | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 114       | 25.79%  |
| 4.01-8.0   | 99        | 22.4%   |
| 2.01-3.0   | 98        | 22.17%  |
| 3.01-4.0   | 55        | 12.44%  |
| 0.51-1.0   | 32        | 7.24%   |
| 8.01-16.0  | 30        | 6.79%   |
| 16.01-24.0 | 6         | 1.36%   |
| 0.01-0.5   | 4         | 0.9%    |
| 24.01-32.0 | 3         | 0.68%   |
| 32.01-64.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 253       | 59.95%  |
| 2      | 97        | 22.99%  |
| 3      | 36        | 8.53%   |
| 4      | 16        | 3.79%   |
| 6      | 9         | 2.13%   |
| 5      | 7         | 1.66%   |
| 0      | 3         | 0.71%   |
| 7      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 270       | 65.38%  |
| Yes       | 143       | 34.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 359       | 87.35%  |
| No        | 52        | 12.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 75.06%  |
| No        | 102       | 24.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 63.2%   |
| No        | 152       | 36.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 409       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 261       | 61.7%   |
| Tartu             | 51        | 12.06%  |
| Pärnu            | 14        | 3.31%   |
| Rapla             | 8         | 1.89%   |
| Rakvere           | 8         | 1.89%   |
| Narva             | 8         | 1.89%   |
| Tabasalu          | 6         | 1.42%   |
| Haapsalu          | 6         | 1.42%   |
| Viljandi          | 3         | 0.71%   |
| Valga             | 3         | 0.71%   |
| Tapa              | 3         | 0.71%   |
| Saku              | 3         | 0.71%   |
| Maardu            | 3         | 0.71%   |
| Vinni             | 2         | 0.47%   |
| Viimsi            | 2         | 0.47%   |
| Põlva            | 2         | 0.47%   |
| Paldiski          | 2         | 0.47%   |
| Otepaeae          | 2         | 0.47%   |
| Laagri            | 2         | 0.47%   |
| Kose              | 2         | 0.47%   |
| Kohtla-Järve     | 2         | 0.47%   |
| Keila             | 2         | 0.47%   |
| Jõhvi            | 2         | 0.47%   |
| Võru             | 1         | 0.24%   |
| Vatla             | 1         | 0.24%   |
| Vaidasoo          | 1         | 0.24%   |
| Türi             | 1         | 0.24%   |
| Sindi             | 1         | 0.24%   |
| Sillamäe         | 1         | 0.24%   |
| Sauga             | 1         | 0.24%   |
| Reiu              | 1         | 0.24%   |
| Rae Parish        | 1         | 0.24%   |
| Pohja-Sakala vald | 1         | 0.24%   |
| Palamuse          | 1         | 0.24%   |
| Paide             | 1         | 0.24%   |
| Muraste           | 1         | 0.24%   |
| Lohkva            | 1         | 0.24%   |
| Kuressaare        | 1         | 0.24%   |
| Kupu              | 1         | 0.24%   |
| Kiviõli          | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 137       | 193    | 22.5%   |
| Seagate                     | 69        | 90     | 11.33%  |
| WDC                         | 60        | 87     | 9.85%   |
| Kingston                    | 49        | 67     | 8.05%   |
| Toshiba                     | 41        | 44     | 6.73%   |
| Sandisk                     | 28        | 31     | 4.6%    |
| Crucial                     | 23        | 34     | 3.78%   |
| SK hynix                    | 22        | 26     | 3.61%   |
| Unknown                     | 16        | 18     | 2.63%   |
| Hitachi                     | 16        | 20     | 2.63%   |
| Intel                       | 15        | 18     | 2.46%   |
| HGST                        | 14        | 18     | 2.3%    |
| Patriot                     | 9         | 10     | 1.48%   |
| A-DATA Technology           | 9         | 15     | 1.48%   |
| Micron Technology           | 7         | 7      | 1.15%   |
| China                       | 7         | 7      | 1.15%   |
| Kingston Technology Company | 6         | 8      | 0.99%   |
| Apacer                      | 6         | 7      | 0.99%   |
| KIOXIA                      | 5         | 6      | 0.82%   |
| ADATA Technology            | 5         | 5      | 0.82%   |
| SPCC                        | 4         | 6      | 0.66%   |
| Phison Electronics          | 4         | 5      | 0.66%   |
| KingSpec                    | 4         | 6      | 0.66%   |
| Gigabyte Technology         | 4         | 5      | 0.66%   |
| XPG                         | 3         | 3      | 0.49%   |
| Transcend                   | 3         | 6      | 0.49%   |
| Lenovo                      | 3         | 3      | 0.49%   |
| Apple                       | 3         | 3      | 0.49%   |
| Unknown                     | 3         | 3      | 0.49%   |
| Team                        | 2         | 3      | 0.33%   |
| Silicon Motion              | 2         | 4      | 0.33%   |
| Netac                       | 2         | 2      | 0.33%   |
| Micron/Crucial Technology   | 2         | 3      | 0.33%   |
| Maxtor                      | 2         | 2      | 0.33%   |
| LITEONIT                    | 2         | 2      | 0.33%   |
| Intenso                     | 2         | 2      | 0.33%   |
| Fujitsu                     | 2         | 2      | 0.33%   |
| Corsair                     | 2         | 2      | 0.33%   |
| ZADAK                       | 1         | 1      | 0.16%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 13        | 1.93%   |
| Samsung SSD 850 EVO 250GB                                         | 8         | 1.19%   |
| Kingston SA400S37240G 240GB SSD                                   | 8         | 1.19%   |
| Samsung SSD 860 EVO 250GB                                         | 7         | 1.04%   |
| Samsung SSD 850 EVO 500GB                                         | 7         | 1.04%   |
| Samsung NVMe SSD Drive 1TB                                        | 6         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 6         | 0.89%   |
| Kingston SA400S37120G 120GB SSD                                   | 6         | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 5         | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5         | 0.74%   |
| Kingston SA400S37480G 480GB SSD                                   | 5         | 0.74%   |
| Toshiba DT01ACA100 1TB                                            | 4         | 0.59%   |
| Seagate ST500LT012-9WS142 500GB                                   | 4         | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB                                    | 4         | 0.59%   |
| Samsung SSD 870 QVO 1TB                                           | 4         | 0.59%   |
| Samsung NVMe SSD Drive 512GB                                      | 4         | 0.59%   |
| Samsung HD103SJ 1TB                                               | 4         | 0.59%   |
| HGST HTS721010A9E630 1TB                                          | 4         | 0.59%   |
| HGST HTS541010A9E680 1TB                                          | 4         | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 4         | 0.59%   |
| Toshiba HDWD130 3TB                                               | 3         | 0.45%   |
| SK hynix NVMe SSD Drive 256GB                                     | 3         | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB                                   | 3         | 0.45%   |
| Seagate ST500DM002-1BD142 500GB                                   | 3         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                                      | 3         | 0.45%   |
| Samsung SSD 960 PRO 512GB                                         | 3         | 0.45%   |
| Samsung SSD 860 EVO 500GB                                         | 3         | 0.45%   |
| Samsung SSD 840 EVO 120GB                                         | 3         | 0.45%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD                              | 3         | 0.45%   |
| Samsung HD080HJ/ 80GB                                             | 3         | 0.45%   |
| Patriot Burst 480GB SSD                                           | 3         | 0.45%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB                           | 3         | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                                  | 3         | 0.45%   |
| Kingston SUV400S37240G 240GB SSD                                  | 3         | 0.45%   |
| Kingston SA400S37960G 960GB SSD                                   | 3         | 0.45%   |
| Crucial CT500MX500SSD1 500GB                                      | 3         | 0.45%   |
| Apacer AS350 512GB SSD                                            | 3         | 0.45%   |
| A-DATA SX8200PNP 512GB                                            | 3         | 0.45%   |
| Unknown                                                           | 3         | 0.45%   |
| WDC WD10EZRZ-00HTKB0 1TB                                          | 2         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 86     | 34.21%  |
| WDC                 | 46        | 65     | 24.21%  |
| Toshiba             | 23        | 25     | 12.11%  |
| Samsung Electronics | 17        | 23     | 8.95%   |
| Hitachi             | 16        | 20     | 8.42%   |
| HGST                | 14        | 18     | 7.37%   |
| Maxtor              | 2         | 2      | 1.05%   |
| Fujitsu             | 2         | 2      | 1.05%   |
| Unknown             | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| External            | 1         | 1      | 0.53%   |
| ASMT                | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 74        | 94     | 32.03%  |
| Kingston            | 39        | 53     | 16.88%  |
| Crucial             | 22        | 33     | 9.52%   |
| SanDisk             | 13        | 15     | 5.63%   |
| WDC                 | 8         | 12     | 3.46%   |
| Patriot             | 8         | 9      | 3.46%   |
| China               | 7         | 7      | 3.03%   |
| A-DATA Technology   | 7         | 12     | 3.03%   |
| Apacer              | 6         | 7      | 2.6%    |
| Intel               | 5         | 6      | 2.16%   |
| SK hynix            | 4         | 4      | 1.73%   |
| Micron Technology   | 4         | 4      | 1.73%   |
| KingSpec            | 4         | 6      | 1.73%   |
| Transcend           | 3         | 6      | 1.3%    |
| Toshiba             | 3         | 4      | 1.3%    |
| SPCC                | 3         | 5      | 1.3%    |
| Team                | 2         | 3      | 0.87%   |
| Netac               | 2         | 2      | 0.87%   |
| LITEONIT            | 2         | 2      | 0.87%   |
| Intenso             | 2         | 2      | 0.87%   |
| Gigabyte Technology | 2         | 3      | 0.87%   |
| Corsair             | 2         | 2      | 0.87%   |
| Apple               | 2         | 2      | 0.87%   |
| ZADAK               | 1         | 1      | 0.43%   |
| XPG                 | 1         | 1      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| Lexar               | 1         | 1      | 0.43%   |
| Integral            | 1         | 1      | 0.43%   |
| i-FlashDisk         | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 191       | 300    | 35.9%   |
| NVMe    | 162       | 219    | 30.45%  |
| HDD     | 157       | 246    | 29.51%  |
| MMC     | 14        | 16     | 2.63%   |
| Unknown | 8         | 9      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 283       | 536    | 58.96%  |
| NVMe | 162       | 217    | 33.75%  |
| SAS  | 21        | 21     | 4.38%   |
| MMC  | 14        | 16     | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 227       | 352    | 60.86%  |
| 0.51-1.0   | 100       | 132    | 26.81%  |
| 1.01-2.0   | 22        | 29     | 5.9%    |
| 4.01-10.0  | 8         | 9      | 2.14%   |
| 3.01-4.0   | 7         | 7      | 1.88%   |
| 2.01-3.0   | 7         | 15     | 1.88%   |
| 10.01-20.0 | 2         | 2      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 115       | 26.87%  |
| 251-500        | 80        | 18.69%  |
| 501-1000       | 57        | 13.32%  |
| 1-20           | 42        | 9.81%   |
| 1001-2000      | 36        | 8.41%   |
| More than 3000 | 30        | 7.01%   |
| 51-100         | 28        | 6.54%   |
| Unknown        | 18        | 4.21%   |
| 2001-3000      | 12        | 2.8%    |
| 21-50          | 10        | 2.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 158       | 35.99%  |
| 21-50          | 68        | 15.49%  |
| 101-250        | 58        | 13.21%  |
| 51-100         | 46        | 10.48%  |
| 251-500        | 31        | 7.06%   |
| 501-1000       | 26        | 5.92%   |
| 1001-2000      | 18        | 4.1%    |
| Unknown        | 18        | 4.1%    |
| More than 3000 | 12        | 2.73%   |
| 2001-3000      | 3         | 0.68%   |
| 0              | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                        | 2         | 3      | 4.08%   |
| WDC WD60EFRX-68MYMN1 6TB                            | 1         | 1      | 2.04%   |
| WDC WD5002AALX-00J37A0 500GB                        | 1         | 1      | 2.04%   |
| WDC WD5000BPVT-00HXZT1 500GB                        | 1         | 1      | 2.04%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1      | 2.04%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 1      | 2.04%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 2.04%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 2      | 2.04%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.04%   |
| WDC WD10PURX-64E5EY0 1TB                            | 1         | 1      | 2.04%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 1      | 2.04%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 2      | 2.04%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 2      | 2.04%   |
| Toshiba MK6475GSX 640GB                             | 1         | 1      | 2.04%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 2.04%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 2.04%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.04%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.04%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.04%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 2.04%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.04%   |
| Seagate ST340016A 40GB                              | 1         | 2      | 2.04%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.04%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.04%   |
| Seagate ST3000DM008-2DM166 3TB                      | 1         | 1      | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.04%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 840 PRO Series 128GB        | 1         | 1      | 2.04%   |
| Samsung Electronics SP0802N 80GB                    | 1         | 1      | 2.04%   |
| Samsung Electronics HD642JJ 640GB                   | 1         | 2      | 2.04%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.04%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.04%   |
| Samsung Electronics HD080HJ/ 80GB                   | 1         | 1      | 2.04%   |
| Patriot P210 256GB SSD                              | 1         | 1      | 2.04%   |
| Patriot Burst 480GB SSD                             | 1         | 1      | 2.04%   |
| Netac SSD 720GB                                     | 1         | 1      | 2.04%   |
| Micron Technology MTFDDAK256TDL-1AW15ABHA 256GB SSD | 1         | 1      | 2.04%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.04%   |
| Maxtor STM3250310AS 250GB                           | 1         | 1      | 2.04%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 25.53%  |
| WDC                 | 10        | 13     | 21.28%  |
| Samsung Electronics | 5         | 7      | 10.64%  |
| Crucial             | 4         | 5      | 8.51%   |
| Toshiba             | 3         | 4      | 6.38%   |
| Hitachi             | 3         | 3      | 6.38%   |
| Patriot             | 2         | 2      | 4.26%   |
| Micron Technology   | 2         | 2      | 4.26%   |
| Kingston            | 2         | 2      | 4.26%   |
| Netac               | 1         | 1      | 2.13%   |
| Maxtor              | 1         | 1      | 2.13%   |
| HGST                | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 35.29%  |
| WDC                 | 10        | 13     | 29.41%  |
| Samsung Electronics | 4         | 6      | 11.76%  |
| Hitachi             | 3         | 3      | 8.82%   |
| Toshiba             | 2         | 2      | 5.88%   |
| Maxtor              | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 40     | 72.73%  |
| SSD  | 12        | 15     | 27.27%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 209       | 409    | 47.18%  |
| Works    | 190       | 325    | 42.89%  |
| Malfunc  | 43        | 55     | 9.71%   |
| Failed   | 1         | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 251       | 47.09%  |
| AMD                          | 81        | 15.2%   |
| Samsung Electronics          | 61        | 11.44%  |
| SanDisk                      | 23        | 4.32%   |
| SK hynix                     | 18        | 3.38%   |
| Kingston Technology Company  | 16        | 3%      |
| Toshiba America Info Systems | 13        | 2.44%   |
| Marvell Technology Group     | 10        | 1.88%   |
| ADATA Technology             | 9         | 1.69%   |
| Phison Electronics           | 7         | 1.31%   |
| Nvidia                       | 7         | 1.31%   |
| KIOXIA                       | 7         | 1.31%   |
| ASMedia Technology           | 7         | 1.31%   |
| VIA Technologies             | 3         | 0.56%   |
| Silicon Motion               | 3         | 0.56%   |
| Micron/Crucial Technology    | 3         | 0.56%   |
| Micron Technology            | 3         | 0.56%   |
| Lenovo                       | 3         | 0.56%   |
| JMicron Technology           | 2         | 0.38%   |
| Union Memory (Shenzhen)      | 1         | 0.19%   |
| Silicon Image                | 1         | 0.19%   |
| Seagate Technology           | 1         | 0.19%   |
| Realtek Semiconductor        | 1         | 0.19%   |
| Hosin Global Electronics     | 1         | 0.19%   |
| Adaptec                      | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 50        | 8.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 35        | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 32        | 5.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 2.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.85%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.51%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.18%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7         | 1.18%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 7         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 0.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 0.84%   |
| Intel SSD 660P Series                                                          | 5         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 0.67%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 4         | 0.67%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 4         | 0.67%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 302       | 57.09%  |
| NVMe | 164       | 31%     |
| IDE  | 44        | 8.32%   |
| RAID | 18        | 3.4%    |
| SCSI | 1         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 294       | 71.88%  |
| AMD                   | 114       | 27.87%  |
| Marvell Semiconductor | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 1.96%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 6         | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 5         | 1.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.98%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 4         | 0.98%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 4         | 0.98%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4         | 0.98%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 4         | 0.98%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor       | 4         | 0.98%   |
| AMD Custom APU 0405                     | 4         | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 0.73%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 0.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 0.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 0.73%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz      | 3         | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 0.73%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 3         | 0.73%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 3         | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3         | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 3         | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 3         | 0.73%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 0.73%   |
| AMD FX-8350 Eight-Core Processor        | 3         | 0.73%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz     | 2         | 0.49%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 2         | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.49%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.49%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.49%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.49%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 2         | 0.49%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.49%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 99        | 24.21%  |
| Intel Core i7                  | 78        | 19.07%  |
| Other                          | 32        | 7.82%   |
| AMD Ryzen 7                    | 31        | 7.58%   |
| AMD Ryzen 5                    | 27        | 6.6%    |
| Intel Core i3                  | 23        | 5.62%   |
| Intel Celeron                  | 16        | 3.91%   |
| Intel Core 2 Duo               | 15        | 3.67%   |
| AMD Ryzen 9                    | 9         | 2.2%    |
| Intel Xeon                     | 7         | 1.71%   |
| Intel Pentium                  | 7         | 1.71%   |
| AMD Ryzen 7 PRO                | 7         | 1.71%   |
| Intel Atom                     | 5         | 1.22%   |
| AMD FX                         | 5         | 1.22%   |
| AMD Phenom II X4               | 4         | 0.98%   |
| AMD Athlon 64 X2               | 4         | 0.98%   |
| Intel Core i9                  | 3         | 0.73%   |
| AMD Ryzen 5 PRO                | 3         | 0.73%   |
| AMD Ryzen 3 PRO                | 3         | 0.73%   |
| AMD Ryzen 3                    | 3         | 0.73%   |
| Intel Pentium Silver           | 2         | 0.49%   |
| Intel Pentium M                | 2         | 0.49%   |
| Intel Core 2                   | 2         | 0.49%   |
| Intel Celeron Dual-Core        | 2         | 0.49%   |
| AMD A4                         | 2         | 0.49%   |
| AMD A10                        | 2         | 0.49%   |
| Intel Pentium Gold             | 1         | 0.24%   |
| Intel Pentium Dual-Core        | 1         | 0.24%   |
| Intel Pentium Dual             | 1         | 0.24%   |
| Intel Pentium D                | 1         | 0.24%   |
| Intel Pentium 4                | 1         | 0.24%   |
| Intel Genuine                  | 1         | 0.24%   |
| Intel Celeron M                | 1         | 0.24%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.24%   |
| AMD Phenom II X6               | 1         | 0.24%   |
| AMD E2                         | 1         | 0.24%   |
| AMD E                          | 1         | 0.24%   |
| AMD C-60                       | 1         | 0.24%   |
| AMD Athlon XP                  | 1         | 0.24%   |
| AMD Athlon II Dual-Core        | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 149       | 36.43%  |
| 4       | 130       | 31.78%  |
| 6       | 49        | 11.98%  |
| 8       | 43        | 10.51%  |
| 1       | 12        | 2.93%   |
| 12      | 11        | 2.69%   |
| 14      | 5         | 1.22%   |
| 16      | 3         | 0.73%   |
| 10      | 3         | 0.73%   |
| Unknown | 3         | 0.73%   |
| 3       | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 408       | 99.76%  |
| 2      | 1         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 293       | 71.46%  |
| 1       | 114       | 27.8%   |
| Unknown | 3         | 0.73%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 403       | 98.29%  |
| Unknown        | 4         | 0.98%   |
| 32-bit         | 3         | 0.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 38.12%  |
| 0x306c3    | 24        | 5.65%   |
| 0x306a9    | 22        | 5.18%   |
| 0x206a7    | 19        | 4.47%   |
| 0x806ea    | 10        | 2.35%   |
| 0x906e9    | 9         | 2.12%   |
| 0x1067a    | 9         | 2.12%   |
| 0x08600106 | 9         | 2.12%   |
| 0x40651    | 8         | 1.88%   |
| 0x906ea    | 7         | 1.65%   |
| 0x20655    | 7         | 1.65%   |
| 0x08701021 | 7         | 1.65%   |
| 0x806ec    | 6         | 1.41%   |
| 0x806e9    | 6         | 1.41%   |
| 0x806c1    | 6         | 1.41%   |
| 0x506e3    | 6         | 1.41%   |
| 0x306d4    | 6         | 1.41%   |
| 0x6fb      | 5         | 1.18%   |
| 0x08701013 | 5         | 1.18%   |
| 0xa0652    | 4         | 0.94%   |
| 0x6fd      | 4         | 0.94%   |
| 0x08108102 | 4         | 0.94%   |
| 0xa0655    | 3         | 0.71%   |
| 0x90672    | 3         | 0.71%   |
| 0x406e3    | 3         | 0.71%   |
| 0x06000852 | 3         | 0.71%   |
| 0x05000119 | 3         | 0.71%   |
| 0xa0671    | 2         | 0.47%   |
| 0x906ed    | 2         | 0.47%   |
| 0x706a1    | 2         | 0.47%   |
| 0x6d8      | 2         | 0.47%   |
| 0x406c4    | 2         | 0.47%   |
| 0x30678    | 2         | 0.47%   |
| 0x106ca    | 2         | 0.47%   |
| 0x10676    | 2         | 0.47%   |
| 0x0a601206 | 2         | 0.47%   |
| 0x0a50000d | 2         | 0.47%   |
| 0x0a50000c | 2         | 0.47%   |
| 0x08600104 | 2         | 0.47%   |
| 0x08600103 | 2         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 64        | 15.65%  |
| Haswell          | 46        | 11.25%  |
| Zen 2            | 36        | 8.8%    |
| IvyBridge        | 32        | 7.82%   |
| SandyBridge      | 30        | 7.33%   |
| Unknown          | 28        | 6.85%   |
| Zen 3            | 19        | 4.65%   |
| Skylake          | 16        | 3.91%   |
| Westmere         | 13        | 3.18%   |
| Core             | 13        | 3.18%   |
| Broadwell        | 12        | 2.93%   |
| Penryn           | 11        | 2.69%   |
| TigerLake        | 10        | 2.44%   |
| Zen+             | 9         | 2.2%    |
| CometLake        | 9         | 2.2%    |
| Alderlake Hybrid | 7         | 1.71%   |
| Zen              | 6         | 1.47%   |
| Piledriver       | 6         | 1.47%   |
| K10              | 6         | 1.47%   |
| Silvermont       | 5         | 1.22%   |
| K8 Hammer        | 4         | 0.98%   |
| IceLake          | 4         | 0.98%   |
| Goldmont plus    | 4         | 0.98%   |
| Steamroller      | 3         | 0.73%   |
| Bonnell          | 3         | 0.73%   |
| Bobcat           | 3         | 0.73%   |
| P6               | 2         | 0.49%   |
| NetBurst         | 2         | 0.49%   |
| Excavator        | 2         | 0.49%   |
| Tremont          | 1         | 0.24%   |
| K8 & K10 hybrid  | 1         | 0.24%   |
| K6               | 1         | 0.24%   |
| Goldmont         | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 236       | 45.74%  |
| Nvidia            | 165       | 31.98%  |
| AMD               | 112       | 21.71%  |
| ASPEED Technology | 2         | 0.39%   |
| VIA Technologies  | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 21        | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 21        | 3.95%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 18        | 3.38%   |
| Intel UHD Graphics 620                                                      | 15        | 2.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 14        | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12        | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                         | 11        | 2.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 10        | 1.88%   |
| Intel HD Graphics 620                                                       | 10        | 1.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 10        | 1.88%   |
| Intel HD Graphics 5500                                                      | 9         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 8         | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8         | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 7         | 1.32%   |
| Intel HD Graphics 630                                                       | 7         | 1.32%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 6         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 6         | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6         | 1.13%   |
| Nvidia GP108M [GeForce MX150]                                               | 5         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 5         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 0.94%   |
| Intel HD Graphics 530                                                       | 5         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 4         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 4         | 0.75%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4         | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 0.75%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 4         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 0.75%   |
| AMD VanGogh [AMD Custom GPU 0405]                                           | 4         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4         | 0.75%   |
| AMD Raphael                                                                 | 4         | 0.75%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4         | 0.75%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3         | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 146       | 35.52%  |
| 1 x AMD        | 83        | 20.19%  |
| 1 x Nvidia     | 74        | 18%     |
| Intel + Nvidia | 74        | 18%     |
| AMD + Nvidia   | 13        | 3.16%   |
| Intel + AMD    | 9         | 2.19%   |
| 2 x AMD        | 4         | 0.97%   |
| 2 x Nvidia     | 2         | 0.49%   |
| 2 x Intel      | 2         | 0.49%   |
| AMD + ASPEED   | 2         | 0.49%   |
| Other          | 1         | 0.24%   |
| 1 x VIA        | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 300       | 71.77%  |
| Proprietary | 101       | 24.16%  |
| Unknown     | 17        | 4.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 51.44%  |
| 1.01-2.0   | 55        | 13.16%  |
| 0.01-0.5   | 43        | 10.29%  |
| 3.01-4.0   | 30        | 7.18%   |
| 0.51-1.0   | 26        | 6.22%   |
| 7.01-8.0   | 22        | 5.26%   |
| 8.01-16.0  | 12        | 2.87%   |
| 5.01-6.0   | 9         | 2.15%   |
| 16.01-24.0 | 3         | 0.72%   |
| 2.01-3.0   | 2         | 0.48%   |
| 4.01-5.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 59        | 12.39%  |
| Dell                    | 56        | 11.76%  |
| AU Optronics            | 54        | 11.34%  |
| Chimei Innolux          | 47        | 9.87%   |
| LG Display              | 36        | 7.56%   |
| BOE                     | 33        | 6.93%   |
| Goldstar                | 27        | 5.67%   |
| Hewlett-Packard         | 17        | 3.57%   |
| AOC                     | 13        | 2.73%   |
| Sharp                   | 12        | 2.52%   |
| Philips                 | 12        | 2.52%   |
| Chi Mei Optoelectronics | 11        | 2.31%   |
| ViewSonic               | 10        | 2.1%    |
| Lenovo                  | 10        | 2.1%    |
| BenQ                    | 7         | 1.47%   |
| Apple                   | 7         | 1.47%   |
| PANDA                   | 6         | 1.26%   |
| Ancor Communications    | 5         | 1.05%   |
| LG Philips              | 4         | 0.84%   |
| Hitachi                 | 4         | 0.84%   |
| Sony                    | 3         | 0.63%   |
| CSO                     | 3         | 0.63%   |
| ASUSTek Computer        | 3         | 0.63%   |
| Valve                   | 2         | 0.42%   |
| Unknown                 | 2         | 0.42%   |
| RoverScan               | 2         | 0.42%   |
| Panasonic               | 2         | 0.42%   |
| LG Electronics          | 2         | 0.42%   |
| Lenovo Group Limited    | 2         | 0.42%   |
| Fujitsu Siemens         | 2         | 0.42%   |
| CPT                     | 2         | 0.42%   |
| Acer                    | 2         | 0.42%   |
| Vestel Elektronik       | 1         | 0.21%   |
| Toshiba                 | 1         | 0.21%   |
| Tech Concepts           | 1         | 0.21%   |
| Sun                     | 1         | 0.21%   |
| Seiko/Epson             | 1         | 0.21%   |
| Plain Tree Systems      | 1         | 0.21%   |
| MSI                     | 1         | 0.21%   |
| MiTAC                   | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 5         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 5         | 1.01%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch             | 4         | 0.8%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 4         | 0.8%    |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch              | 3         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 3         | 0.6%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 3         | 0.6%    |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch        | 2         | 0.4%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.4%    |
| Sony TV SNYDB01 1920x1080                                            | 2         | 0.4%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.4%    |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch              | 2         | 0.4%    |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch    | 2         | 0.4%    |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch    | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 2         | 0.4%    |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 2         | 0.4%    |
| LG Philips LCD Monitor LPL0133 1280x800 304x190mm 14.1-inch          | 2         | 0.4%    |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch         | 2         | 0.4%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch              | 2         | 0.4%    |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch          | 2         | 0.4%    |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch           | 2         | 0.4%    |
| Goldstar ULTRAWIDE GSM7768 3440x1440 800x334mm 34.1-inch             | 2         | 0.4%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2         | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2         | 0.4%    |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                    | 2         | 0.4%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 2         | 0.4%    |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                   | 2         | 0.4%    |
| Dell P3421W DELA1A8 3440x1440 800x335mm 34.1-inch                    | 2         | 0.4%    |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                    | 2         | 0.4%    |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                    | 2         | 0.4%    |
| Dell 2407WFP DELA017 1920x1200 519x324mm 24.1-inch                   | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch     | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 2         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 192       | 42.29%  |
| 1366x768 (WXGA)    | 54        | 11.89%  |
| 3840x2160 (4K)     | 39        | 8.59%   |
| 1920x1200 (WUXGA)  | 32        | 7.05%   |
| 2560x1440 (QHD)    | 29        | 6.39%   |
| 1600x900 (HD+)     | 21        | 4.63%   |
| 1280x1024 (SXGA)   | 21        | 4.63%   |
| 1280x800 (WXGA)    | 13        | 2.86%   |
| 3440x1440          | 11        | 2.42%   |
| 2560x1600          | 10        | 2.2%    |
| 1680x1050 (WSXGA+) | 9         | 1.98%   |
| 1440x900 (WXGA+)   | 7         | 1.54%   |
| 800x1280           | 3         | 0.66%   |
| 3840x1600          | 2         | 0.44%   |
| 2560x1080          | 2         | 0.44%   |
| 1600x1200          | 2         | 0.44%   |
| 3840x2400          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 2880x1800          | 1         | 0.22%   |
| 2256x1504          | 1         | 0.22%   |
| 1920x540           | 1         | 0.22%   |
| 1360x768           | 1         | 0.22%   |
| 1024x768 (XGA)     | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 105       | 21.69%  |
| 14      | 50        | 10.33%  |
| 13      | 49        | 10.12%  |
| 24      | 47        | 9.71%   |
| 27      | 34        | 7.02%   |
| 17      | 31        | 6.4%    |
| 23      | 25        | 5.17%   |
| 21      | 19        | 3.93%   |
| Unknown | 19        | 3.93%   |
| 31      | 14        | 2.89%   |
| 34      | 10        | 2.07%   |
| 19      | 9         | 1.86%   |
| 12      | 9         | 1.86%   |
| 84      | 7         | 1.45%   |
| 16      | 7         | 1.45%   |
| 20      | 6         | 1.24%   |
| 40      | 5         | 1.03%   |
| 32      | 4         | 0.83%   |
| 18      | 4         | 0.83%   |
| 72      | 3         | 0.62%   |
| 25      | 3         | 0.62%   |
| 22      | 3         | 0.62%   |
| 65      | 2         | 0.41%   |
| 54      | 2         | 0.41%   |
| 43      | 2         | 0.41%   |
| 37      | 2         | 0.41%   |
| 33      | 2         | 0.41%   |
| 7       | 2         | 0.41%   |
| 86      | 1         | 0.21%   |
| 52      | 1         | 0.21%   |
| 38      | 1         | 0.21%   |
| 29      | 1         | 0.21%   |
| 28      | 1         | 0.21%   |
| 11      | 1         | 0.21%   |
| 10      | 1         | 0.21%   |
| 9       | 1         | 0.21%   |
| 3       | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 191       | 40.3%   |
| 501-600     | 96        | 20.25%  |
| 201-300     | 42        | 8.86%   |
| 401-500     | 34        | 7.17%   |
| 351-400     | 25        | 5.27%   |
| 601-700     | 22        | 4.64%   |
| Unknown     | 19        | 4.01%   |
| 701-800     | 16        | 3.38%   |
| 1501-2000   | 10        | 2.11%   |
| 801-900     | 8         | 1.69%   |
| 1001-1500   | 6         | 1.27%   |
| 1-100       | 3         | 0.63%   |
| 901-1000    | 2         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 297       | 68.75%  |
| 16/10   | 74        | 17.13%  |
| 5/4     | 18        | 4.17%   |
| Unknown | 17        | 3.94%   |
| 21/9    | 12        | 2.78%   |
| 4/3     | 4         | 0.93%   |
| 6/5     | 3         | 0.69%   |
| 3/2     | 3         | 0.69%   |
| 0.67    | 2         | 0.46%   |
| 32/9    | 1         | 0.23%   |
| 0.56    | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 21.16%  |
| 81-90          | 71        | 14.73%  |
| 201-250        | 55        | 11.41%  |
| 251-300        | 35        | 7.26%   |
| 301-350        | 34        | 7.05%   |
| 351-500        | 32        | 6.64%   |
| 71-80          | 25        | 5.19%   |
| 151-200        | 21        | 4.36%   |
| Unknown        | 19        | 3.94%   |
| 141-150        | 17        | 3.53%   |
| More than 1000 | 16        | 3.32%   |
| 121-130        | 16        | 3.32%   |
| 111-120        | 10        | 2.07%   |
| 501-1000       | 10        | 2.07%   |
| 61-70          | 9         | 1.87%   |
| 1-40           | 3         | 0.62%   |
| 91-100         | 3         | 0.62%   |
| 41-50          | 2         | 0.41%   |
| 51-60          | 1         | 0.21%   |
| 131-140        | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 147       | 31.75%  |
| 121-160       | 135       | 29.16%  |
| 101-120       | 103       | 22.25%  |
| 161-240       | 38        | 8.21%   |
| Unknown       | 19        | 4.1%    |
| More than 240 | 11        | 2.38%   |
| 1-50          | 10        | 2.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 310       | 73.99%  |
| 2     | 86        | 20.53%  |
| 0     | 12        | 2.86%   |
| 3     | 10        | 2.39%   |
| 4     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 209       | 34.15%  |
| Realtek Semiconductor             | 201       | 32.84%  |
| Qualcomm Atheros                  | 57        | 9.31%   |
| Broadcom                          | 26        | 4.25%   |
| MediaTek                          | 21        | 3.43%   |
| TP-Link                           | 11        | 1.8%    |
| ASIX Electronics                  | 9         | 1.47%   |
| Ralink                            | 8         | 1.31%   |
| Nvidia                            | 7         | 1.14%   |
| Broadcom Limited                  | 7         | 1.14%   |
| Ralink Technology                 | 5         | 0.82%   |
| Ericsson Business Mobile Networks | 5         | 0.82%   |
| Sierra Wireless                   | 4         | 0.65%   |
| Marvell Technology Group          | 4         | 0.65%   |
| Lenovo                            | 4         | 0.65%   |
| Fibocom                           | 4         | 0.65%   |
| Samsung Electronics               | 3         | 0.49%   |
| Microsoft                         | 3         | 0.49%   |
| Hewlett-Packard                   | 3         | 0.49%   |
| Qualcomm Atheros Communications   | 2         | 0.33%   |
| JMicron Technology                | 2         | 0.33%   |
| Huawei Technologies               | 2         | 0.33%   |
| D-Link System                     | 2         | 0.33%   |
| VIA Technologies                  | 1         | 0.16%   |
| Van Ooijen Technische Informatica | 1         | 0.16%   |
| Qualcomm Technologies             | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| QinHeng Electronics               | 1         | 0.16%   |
| OPPO Electronics                  | 1         | 0.16%   |
| Mellanox Technologies             | 1         | 0.16%   |
| Insyde Software                   | 1         | 0.16%   |
| DisplayLink                       | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |
| Aquantia                          | 1         | 0.16%   |
| Apple                             | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 132       | 17.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 2.99%   |
| Intel Wireless 8265 / 8275                                             | 18        | 2.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 17        | 2.31%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 1.63%   |
| Intel Wireless 7260                                                    | 11        | 1.5%    |
| Intel Wireless 7265                                                    | 10        | 1.36%   |
| Intel I211 Gigabit Network Connection                                  | 9         | 1.22%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 8         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.95%   |
| Intel Wireless 8260                                                    | 7         | 0.95%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.82%   |
| Intel Wireless 3165                                                    | 6         | 0.82%   |
| Intel Ethernet Controller I225-V                                       | 6         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 0.68%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 5         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.68%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.68%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.54%   |
| Intel Wireless 3160                                                    | 4         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 155       | 47.84%  |
| Realtek Semiconductor           | 46        | 14.2%   |
| Qualcomm Atheros                | 41        | 12.65%  |
| Broadcom                        | 21        | 6.48%   |
| MediaTek                        | 15        | 4.63%   |
| TP-Link                         | 10        | 3.09%   |
| Ralink                          | 8         | 2.47%   |
| Ralink Technology               | 5         | 1.54%   |
| Sierra Wireless                 | 4         | 1.23%   |
| Fibocom                         | 4         | 1.23%   |
| Broadcom Limited                | 4         | 1.23%   |
| Microsoft                       | 3         | 0.93%   |
| Qualcomm Atheros Communications | 2         | 0.62%   |
| Qualcomm Technologies           | 1         | 0.31%   |
| Qualcomm                        | 1         | 0.31%   |
| Marvell Technology Group        | 1         | 0.31%   |
| Hewlett-Packard                 | 1         | 0.31%   |
| D-Link System                   | 1         | 0.31%   |
| D-Link                          | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 18        | 5.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 17        | 5.21%   |
| Intel Wi-Fi 6 AX200                                            | 15        | 4.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 3.68%   |
| Intel Wireless 7260                                            | 11        | 3.37%   |
| Intel Wireless 7265                                            | 10        | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 8         | 2.45%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.15%   |
| Intel Wireless 8260                                            | 7         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 2.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.84%   |
| Intel Wireless 3165                                            | 6         | 1.84%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.53%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 5         | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.23%   |
| Intel Wireless 3160                                            | 4         | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 4         | 1.23%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 4         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 0.92%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 180       | 46.88%  |
| Intel                    | 127       | 33.07%  |
| Qualcomm Atheros         | 23        | 5.99%   |
| Broadcom                 | 10        | 2.6%    |
| ASIX Electronics         | 9         | 2.34%   |
| Nvidia                   | 7         | 1.82%   |
| MediaTek                 | 6         | 1.56%   |
| Marvell Technology Group | 3         | 0.78%   |
| Lenovo                   | 3         | 0.78%   |
| Broadcom Limited         | 3         | 0.78%   |
| JMicron Technology       | 2         | 0.52%   |
| VIA Technologies         | 1         | 0.26%   |
| TP-Link                  | 1         | 0.26%   |
| OPPO Electronics         | 1         | 0.26%   |
| Mellanox Technologies    | 1         | 0.26%   |
| Insyde Software          | 1         | 0.26%   |
| Hewlett-Packard          | 1         | 0.26%   |
| DisplayLink              | 1         | 0.26%   |
| D-Link System            | 1         | 0.26%   |
| ASUSTek Computer         | 1         | 0.26%   |
| Aquantia                 | 1         | 0.26%   |
| Apple                    | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 132       | 33.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 5.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 3.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 3.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 3.05%   |
| Intel I211 Gigabit Network Connection                                  | 9         | 2.29%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 2.29%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.78%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.53%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.27%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 1.27%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.02%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.76%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.51%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.51%   |
| Nvidia CK804 Ethernet Controller                                       | 2         | 0.51%   |
| MediaTek Infinix SMART 5                                               | 2         | 0.51%   |
| Lenovo ThinkPad TBT3 LAN                                               | 2         | 0.51%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.51%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.51%   |
| Intel 82578DM Gigabit Network Connection                               | 2         | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 358       | 52.65%  |
| WiFi     | 307       | 45.15%  |
| Modem    | 15        | 2.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 232       | 55.24%  |
| Ethernet | 188       | 44.76%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 227       | 55.37%  |
| 1     | 170       | 41.46%  |
| 0     | 6         | 1.46%   |
| 3     | 5         | 1.22%   |
| 6     | 1         | 0.24%   |
| 4     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 339       | 81.1%   |
| Yes  | 79        | 18.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 45.08%  |
| Realtek Semiconductor           | 24        | 9.09%   |
| Cambridge Silicon Radio         | 21        | 7.95%   |
| Qualcomm Atheros Communications | 19        | 7.2%    |
| Broadcom                        | 16        | 6.06%   |
| IMC Networks                    | 15        | 5.68%   |
| Foxconn / Hon Hai               | 13        | 4.92%   |
| Apple                           | 7         | 2.65%   |
| TP-Link                         | 5         | 1.89%   |
| Hewlett-Packard                 | 5         | 1.89%   |
| Realtek                         | 4         | 1.52%   |
| ASUSTek Computer                | 3         | 1.14%   |
| Toshiba                         | 2         | 0.76%   |
| MediaTek                        | 2         | 0.76%   |
| Lite-On Technology              | 2         | 0.76%   |
| Edimax Technology               | 2         | 0.76%   |
| Dell                            | 2         | 0.76%   |
| Ralink                          | 1         | 0.38%   |
| Integrated System Solution      | 1         | 0.38%   |
| Askey Computer                  | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 52        | 19.7%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 7.95%   |
| Intel AX201 Bluetooth                               | 19        | 7.2%    |
| Realtek Bluetooth Radio                             | 12        | 4.55%   |
| Intel AX200 Bluetooth                               | 12        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 3.03%   |
| Intel AX211 Bluetooth                               | 8         | 3.03%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.27%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 2.27%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 5         | 1.89%   |
| Intel AX210 Bluetooth                               | 5         | 1.89%   |
| IMC Networks Bluetooth Device                       | 5         | 1.89%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.52%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 1.52%   |
| Realtek Bluetooth Radio                             | 4         | 1.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.52%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 1.52%   |
| Apple Bluetooth Host Controller                     | 4         | 1.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.14%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.14%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.76%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.76%   |
| MediaTek Wireless_Device                            | 2         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.76%   |
| IMC Networks Wireless_Device                        | 2         | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.76%   |
| Edimax Bluetooth Adapter                            | 2         | 0.76%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.76%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.76%   |
| ASUS ASUS USB-BT500                                 | 2         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 286       | 47.91%  |
| AMD                      | 131       | 21.94%  |
| Nvidia                   | 112       | 18.76%  |
| C-Media Electronics      | 9         | 1.51%   |
| Logitech                 | 6         | 1.01%   |
| Kingston Technology      | 6         | 1.01%   |
| Lenovo                   | 5         | 0.84%   |
| Razer USA                | 4         | 0.67%   |
| ASUSTek Computer         | 4         | 0.67%   |
| JMTek                    | 3         | 0.5%    |
| Creative Labs            | 3         | 0.5%    |
| TerraTec Electronic      | 2         | 0.34%   |
| SteelSeries ApS          | 2         | 0.34%   |
| Realtek Semiconductor    | 2         | 0.34%   |
| Generalplus Technology   | 2         | 0.34%   |
| Focusrite-Novation       | 2         | 0.34%   |
| DSEA A/S                 | 2         | 0.34%   |
| VIA Technologies         | 1         | 0.17%   |
| Texas Instruments        | 1         | 0.17%   |
| Syntek                   | 1         | 0.17%   |
| Sony                     | 1         | 0.17%   |
| Samson Technologies      | 1         | 0.17%   |
| Roland                   | 1         | 0.17%   |
| Micronas                 | 1         | 0.17%   |
| Micro Star International | 1         | 0.17%   |
| Mark of the Unicorn      | 1         | 0.17%   |
| M-Audio                  | 1         | 0.17%   |
| KTMicro                  | 1         | 0.17%   |
| GYROCOM C&C              | 1         | 0.17%   |
| GN Netcom                | 1         | 0.17%   |
| Elite Silicon            | 1         | 0.17%   |
| Creative Technology      | 1         | 0.17%   |
| BEHRINGER International  | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 50        | 7.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33        | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32        | 4.53%   |
| Intel Sunrise Point-LP HD Audio                                            | 30        | 4.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29        | 4.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 25        | 3.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 3.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14        | 1.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13        | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 11        | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.56%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.41%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8         | 1.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.85%   |
| AMD FCH Azalia Controller                                                  | 6         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.71%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5         | 0.71%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 5         | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 72        | 24.41%  |
| SK hynix            | 50        | 16.95%  |
| Kingston            | 40        | 13.56%  |
| Micron Technology   | 28        | 9.49%   |
| Unknown             | 25        | 8.47%   |
| G.Skill             | 23        | 7.8%    |
| Crucial             | 16        | 5.42%   |
| Corsair             | 8         | 2.71%   |
| Ramaxel Technology  | 4         | 1.36%   |
| A-DATA Technology   | 4         | 1.36%   |
| Nanya Technology    | 3         | 1.02%   |
| Elpida              | 3         | 1.02%   |
| Unknown (ABCD)      | 2         | 0.68%   |
| Patriot             | 2         | 0.68%   |
| ASint Technology    | 2         | 0.68%   |
| Apacer              | 2         | 0.68%   |
| Wilk                | 1         | 0.34%   |
| Unifosa             | 1         | 0.34%   |
| Team                | 1         | 0.34%   |
| Silicon Power       | 1         | 0.34%   |
| Qimonda             | 1         | 0.34%   |
| Lexar               | 1         | 0.34%   |
| Kllisre             | 1         | 0.34%   |
| GOODRAM             | 1         | 0.34%   |
| AMD                 | 1         | 0.34%   |
| Aeneon              | 1         | 0.34%   |
| Unknown             | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.25%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.93%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 3         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.93%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.93%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 0.62%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.62%   |
| SK hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s             | 2         | 0.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.62%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s           | 2         | 0.62%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.62%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.62%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.62%   |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1632MT/s             | 2         | 0.62%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.62%   |
| Crucial RAM BLS8G4D240FSB.16FBR2 8GB DIMM DDR4 2400MT/s          | 2         | 0.62%   |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s              | 1         | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.31%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.31%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 117       | 46.99%  |
| DDR3    | 81        | 32.53%  |
| DDR2    | 12        | 4.82%   |
| DDR5    | 9         | 3.61%   |
| LPDDR4  | 8         | 3.21%   |
| SDRAM   | 7         | 2.81%   |
| LPDDR5  | 5         | 2.01%   |
| Unknown | 5         | 2.01%   |
| LPDDR3  | 3         | 1.2%    |
| DDR     | 2         | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 58.2%   |
| DIMM         | 90        | 36.89%  |
| Row Of Chips | 12        | 4.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 100       | 36.63%  |
| 4096  | 65        | 23.81%  |
| 16384 | 48        | 17.58%  |
| 2048  | 32        | 11.72%  |
| 32768 | 11        | 4.03%   |
| 1024  | 11        | 4.03%   |
| 512   | 5         | 1.83%   |
| 256   | 1         | 0.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 18.35%  |
| 3200    | 41        | 14.75%  |
| 2667    | 39        | 14.03%  |
| 1333    | 21        | 7.55%   |
| 2400    | 15        | 5.4%    |
| 1334    | 11        | 3.96%   |
| 2133    | 10        | 3.6%    |
| Unknown | 8         | 2.88%   |
| 3600    | 7         | 2.52%   |
| 667     | 7         | 2.52%   |
| 1067    | 6         | 2.16%   |
| 4267    | 5         | 1.8%    |
| 5600    | 4         | 1.44%   |
| 4800    | 4         | 1.44%   |
| 3266    | 4         | 1.44%   |
| 800     | 4         | 1.44%   |
| 6400    | 3         | 1.08%   |
| 3666    | 3         | 1.08%   |
| 1867    | 3         | 1.08%   |
| 4266    | 2         | 0.72%   |
| 4199    | 2         | 0.72%   |
| 3800    | 2         | 0.72%   |
| 3733    | 2         | 0.72%   |
| 3000    | 2         | 0.72%   |
| 2666    | 2         | 0.72%   |
| 1866    | 2         | 0.72%   |
| 1632    | 2         | 0.72%   |
| 533     | 2         | 0.72%   |
| 8400    | 1         | 0.36%   |
| 7500    | 1         | 0.36%   |
| 6000    | 1         | 0.36%   |
| 4133    | 1         | 0.36%   |
| 3534    | 1         | 0.36%   |
| 3466    | 1         | 0.36%   |
| 3334    | 1         | 0.36%   |
| 2933    | 1         | 0.36%   |
| 2733    | 1         | 0.36%   |
| 2134    | 1         | 0.36%   |
| 1800    | 1         | 0.36%   |
| 1066    | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother Industries              | 3         | 30%     |
| Samsung Electronics             | 2         | 20%     |
| Seiko Epson                     | 1         | 10%     |
| QinHeng Electronics             | 1         | 10%     |
| Konica Minolta                  | 1         | 10%     |
| Hewlett-Packard                 | 1         | 10%     |
| cab Produkttechnik GmbH & Co KG | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 10%     |
| Samsung SCX-3400 Series                      | 1         | 10%     |
| Samsung ML-1670 Series                       | 1         | 10%     |
| QinHeng CH340S                               | 1         | 10%     |
| Konica Minolta Printer                       | 1         | 10%     |
| HP Smart Tank 750 series                     | 1         | 10%     |
| cab Produkttechnik GmbH & Co KG EOS2/300     | 1         | 10%     |
| Brother HL-4140CN series                     | 1         | 10%     |
| Brother DCP-L2510D series                    | 1         | 10%     |
| Brother DCP-J152W                            | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson Perfection 660                          | 1         | 50%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 54        | 22.22%  |
| IMC Networks                           | 23        | 9.47%   |
| Microdia                               | 22        | 9.05%   |
| Bison Electronics                      | 18        | 7.41%   |
| Sunplus Innovation Technology          | 17        | 7%      |
| Realtek Semiconductor                  | 17        | 7%      |
| Logitech                               | 12        | 4.94%   |
| Lite-On Technology                     | 9         | 3.7%    |
| Luxvisions Innotech Limited            | 8         | 3.29%   |
| Apple                                  | 8         | 3.29%   |
| Syntek                                 | 7         | 2.88%   |
| Acer                                   | 7         | 2.88%   |
| Suyin                                  | 6         | 2.47%   |
| Silicon Motion                         | 6         | 2.47%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.47%   |
| Quanta                                 | 4         | 1.65%   |
| Sonix Technology                       | 2         | 0.82%   |
| Samsung Electronics                    | 2         | 0.82%   |
| Lenovo                                 | 2         | 0.82%   |
| Arkmicro Technologies                  | 2         | 0.82%   |
| Alcor Micro                            | 2         | 0.82%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Xiaomi                                 | 1         | 0.41%   |
| Tripath Technology                     | 1         | 0.41%   |
| Shinetech                              | 1         | 0.41%   |
| Microsoft                              | 1         | 0.41%   |
| LG Electronics                         | 1         | 0.41%   |
| Importek                               | 1         | 0.41%   |
| Huddly                                 | 1         | 0.41%   |
| Creative Technology                    | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 15        | 6.1%    |
| Microdia Integrated_Webcam_HD                           | 10        | 4.07%   |
| Bison Integrated Camera                                 | 9         | 3.66%   |
| IMC Networks Integrated Camera                          | 8         | 3.25%   |
| Lite-On Integrated Camera                               | 7         | 2.85%   |
| Syntek Integrated Camera                                | 5         | 2.03%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 1.63%   |
| Realtek USB Camera                                      | 4         | 1.63%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.63%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.22%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 3         | 1.22%   |
| Logitech Webcam C930e                                   | 3         | 1.22%   |
| Logitech HD Webcam C525                                 | 3         | 1.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.22%   |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.22%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.22%   |
| Chicony Integrated HP HD Webcam                         | 3         | 1.22%   |
| Chicony HP HD Webcam                                    | 3         | 1.22%   |
| Chicony FJ Camera                                       | 3         | 1.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 3         | 1.22%   |
| Apple FaceTime HD Camera                                | 3         | 1.22%   |
| Sunplus Asus Webcam                                     | 2         | 0.81%   |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 0.81%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 2         | 0.81%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.81%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.81%   |
| Realtek Integrated Webcam HD                            | 2         | 0.81%   |
| Quanta HP HD Camera                                     | 2         | 0.81%   |
| Microdia Webcam Vitade AF                               | 2         | 0.81%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.81%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.81%   |
| Logitech Webcam C270                                    | 2         | 0.81%   |
| Logitech HD Pro Webcam C920                             | 2         | 0.81%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.81%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.81%   |
| Chicony HP HD Camera                                    | 2         | 0.81%   |
| Chicony HD Webcam                                       | 2         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 28        | 41.18%  |
| Synaptics                          | 21        | 30.88%  |
| STMicroelectronics                 | 5         | 7.35%   |
| Shenzhen Goodix Technology         | 5         | 7.35%   |
| Upek                               | 4         | 5.88%   |
| AuthenTec                          | 2         | 2.94%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.47%   |
| LighTuning Technology              | 1         | 1.47%   |
| Elan Microelectronics              | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 9         | 13.24%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 8.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 6         | 8.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 7.35%   |
| STMicroelectronics Fingerprint Reader                           | 5         | 7.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 4         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.41%   |
| Synaptics WBDI                                                  | 3         | 4.41%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 4.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 2.94%   |
| Validity Sensors VFS491                                         | 2         | 2.94%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 2.94%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.47%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 1.47%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.47%   |
| Synaptics UWP WBDI                                              | 1         | 1.47%   |
| Synaptics Prometheus Fingerprint Reader                         | 1         | 1.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.47%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.47%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.47%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.47%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 38        | 45.78%  |
| OmniKey               | 21        | 25.3%   |
| Broadcom              | 9         | 10.84%  |
| Gemalto (was Gemplus) | 7         | 8.43%   |
| Lenovo                | 4         | 4.82%   |
| SCM Microsystems      | 1         | 1.2%    |
| O2 Micro              | 1         | 1.2%    |
| Clay Logic            | 1         | 1.2%    |
| Chicony Electronics   | 1         | 1.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 39.76%  |
| OmniKey CardMan 1021                                                         | 18        | 21.69%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 7.23%   |
| Broadcom 58200                                                               | 5         | 6.02%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 6.02%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.82%   |
| OmniKey CardMan 4321                                                         | 3         | 3.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.41%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.2%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.2%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.2%    |
| Clay Logic Nitrokey Start                                                    | 1         | 1.2%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.2%    |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 1.2%    |
| Broadcom 5880                                                                | 1         | 1.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 259       | 61.67%  |
| 1     | 125       | 29.76%  |
| 2     | 32        | 7.62%   |
| 3     | 3         | 0.71%   |
| 4     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 68        | 34.52%  |
| Graphics card            | 51        | 25.89%  |
| Chipcard                 | 45        | 22.84%  |
| Multimedia controller    | 8         | 4.06%   |
| Net/wireless             | 6         | 3.05%   |
| Camera                   | 6         | 3.05%   |
| Net/ethernet             | 3         | 1.52%   |
| Communication controller | 3         | 1.52%   |
| Card reader              | 3         | 1.52%   |
| Storage                  | 1         | 0.51%   |
| Sound                    | 1         | 0.51%   |
| Modem                    | 1         | 0.51%   |
| Bluetooth                | 1         | 0.51%   |


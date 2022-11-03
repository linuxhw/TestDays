Ubuntu Studio - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Studio/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Studio/Notebook/README.md).

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

Total: 152

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 09F8h                       | Desktop     | [f1107e91f2](https://linux-hardware.org/?probe=f1107e91f2) | Nov 01, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | Desktop     | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [55771f0c33](https://linux-hardware.org/?probe=55771f0c33) | Oct 18, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [7e0028c2fa](https://linux-hardware.org/?probe=7e0028c2fa) | Oct 18, 2022 |
| Gigabyte      | X79S-UP5                    | Desktop     | [62f59af32c](https://linux-hardware.org/?probe=62f59af32c) | Oct 15, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2dc3febd4d](https://linux-hardware.org/?probe=2dc3febd4d) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [5b39dcf114](https://linux-hardware.org/?probe=5b39dcf114) | Sep 19, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [b1d97f239e](https://linux-hardware.org/?probe=b1d97f239e) | Sep 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de37b9cf96](https://linux-hardware.org/?probe=de37b9cf96) | Sep 13, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [d6d8f577e0](https://linux-hardware.org/?probe=d6d8f577e0) | Sep 12, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [07428c96e1](https://linux-hardware.org/?probe=07428c96e1) | Sep 11, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a23b4a8cd4](https://linux-hardware.org/?probe=a23b4a8cd4) | Aug 27, 2022 |
| HP            | 18E7                        | Desktop     | [698520133f](https://linux-hardware.org/?probe=698520133f) | Aug 22, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [45491460bc](https://linux-hardware.org/?probe=45491460bc) | Aug 12, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| HP            | G62                         | Notebook    | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| AZW           | SER V01                     | Mini pc     | [0bf81855b6](https://linux-hardware.org/?probe=0bf81855b6) | Jul 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e45e0b0c90](https://linux-hardware.org/?probe=e45e0b0c90) | Jun 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6023bfb4cc](https://linux-hardware.org/?probe=6023bfb4cc) | Jun 09, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [a4aa661ab1](https://linux-hardware.org/?probe=a4aa661ab1) | Jun 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bcd22d5d0e](https://linux-hardware.org/?probe=bcd22d5d0e) | May 20, 2022 |
| Getac         | S400G3                      | Notebook    | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b2bddaf1b1](https://linux-hardware.org/?probe=b2bddaf1b1) | Apr 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [02b0c35fed](https://linux-hardware.org/?probe=02b0c35fed) | Apr 27, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [cebf5b3135](https://linux-hardware.org/?probe=cebf5b3135) | Apr 17, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [aff1557d72](https://linux-hardware.org/?probe=aff1557d72) | Apr 11, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [a87f9de14e](https://linux-hardware.org/?probe=a87f9de14e) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | Notebook    | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | Notebook    | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [82f706b315](https://linux-hardware.org/?probe=82f706b315) | Feb 11, 2022 |
| Google        | Nami                        | Notebook    | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | Notebook    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [7f94c66f93](https://linux-hardware.org/?probe=7f94c66f93) | Jan 09, 2022 |
| AZW           | GK35                        | Desktop     | [ed1be3dbf7](https://linux-hardware.org/?probe=ed1be3dbf7) | Jan 07, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| Toshiba       | Satellite C855              | Notebook    | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | Notebook    | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Acer          | Aspire U5-710               | All in one  | [c2ff1a33ee](https://linux-hardware.org/?probe=c2ff1a33ee) | Jun 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| HP            | 1495                        | Desktop     | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| Intel Clie... | LAPBC510                    | Notebook    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| HP            | 158A                        | Desktop     | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ef264215af](https://linux-hardware.org/?probe=ef264215af) | Apr 24, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | Notebook    | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [43cb3af3a5](https://linux-hardware.org/?probe=43cb3af3a5) | Apr 12, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | Desktop     | [4cd56bcfa1](https://linux-hardware.org/?probe=4cd56bcfa1) | Apr 02, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [5ff7a11404](https://linux-hardware.org/?probe=5ff7a11404) | Mar 28, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7b7a266de6](https://linux-hardware.org/?probe=7b7a266de6) | Mar 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [d9f29b65da](https://linux-hardware.org/?probe=d9f29b65da) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| Sony          | VGN-NS31M_W                 | Notebook    | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [387cfadf45](https://linux-hardware.org/?probe=387cfadf45) | Feb 06, 2021 |
| IBM           | 8188PPV                     | Desktop     | [6d4f098a65](https://linux-hardware.org/?probe=6d4f098a65) | Jan 31, 2021 |
| Dell          | 02YRK5 A01                  | Desktop     | [6a2d5cd538](https://linux-hardware.org/?probe=6a2d5cd538) | Jan 30, 2021 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [e74dbb590d](https://linux-hardware.org/?probe=e74dbb590d) | Jan 21, 2021 |
| Intel         | DQ965GF AAD41676-402        | Desktop     | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [13edd89415](https://linux-hardware.org/?probe=13edd89415) | Jan 11, 2021 |
| ASUSTek       | U56E                        | Notebook    | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [a8ebb648f7](https://linux-hardware.org/?probe=a8ebb648f7) | Jan 03, 2021 |
| Acer          | Aspire X3400                | Desktop     | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| Packard Be... | WMCP78M                     | Desktop     | [6a6c4577d4](https://linux-hardware.org/?probe=6a6c4577d4) | Dec 31, 2020 |
| HP            | 1850                        | Desktop     | [b86e749745](https://linux-hardware.org/?probe=b86e749745) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4332bc902d](https://linux-hardware.org/?probe=4332bc902d) | Dec 21, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [2291f0c106](https://linux-hardware.org/?probe=2291f0c106) | Dec 08, 2020 |
| Dell          | 04YP6J A02                  | Desktop     | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505443aeb1](https://linux-hardware.org/?probe=505443aeb1) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [73e35c07b8](https://linux-hardware.org/?probe=73e35c07b8) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [3b24badd98](https://linux-hardware.org/?probe=3b24badd98) | Dec 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | Latitude E6530              | Notebook    | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| ASUSTek       | CS-B                        | Desktop     | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Dell          | Latitude E7250              | Notebook    | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | Notebook    | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| HP            | 3047h                       | Desktop     | [a23efe0e20](https://linux-hardware.org/?probe=a23efe0e20) | Oct 26, 2020 |
| ASRock        | H55M/USB3                   | Desktop     | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| Dell          | 0F8098                      | Desktop     | [a2217fa6a7](https://linux-hardware.org/?probe=a2217fa6a7) | Sep 25, 2020 |
| Dell          | 0F8098                      | Desktop     | [2c747bcc47](https://linux-hardware.org/?probe=2c747bcc47) | Sep 25, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | Notebook    | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | Notebook    | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| HP            | Compaq 8510p                | Notebook    | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [d2851c54e9](https://linux-hardware.org/?probe=d2851c54e9) | Aug 18, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [96ba8dc0e8](https://linux-hardware.org/?probe=96ba8dc0e8) | Jul 31, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [d21c458a4f](https://linux-hardware.org/?probe=d21c458a4f) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [957ec007de](https://linux-hardware.org/?probe=957ec007de) | Jun 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cb240b6e7e](https://linux-hardware.org/?probe=cb240b6e7e) | Jun 05, 2020 |
| HP            | Notebook                    | Notebook    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [8271aeba33](https://linux-hardware.org/?probe=8271aeba33) | Mar 19, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | Notebook    | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | Notebook    | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 78        | 60.47%  |
| Ubuntu Studio 22.04 | 20        | 15.5%   |
| Ubuntu Studio 20.10 | 13        | 10.08%  |
| Ubuntu Studio 21.10 | 7         | 5.43%   |
| Ubuntu Studio 21.04 | 5         | 3.88%   |
| Ubuntu Studio 18.04 | 3         | 2.33%   |
| Ubuntu Studio 19.10 | 2         | 1.55%   |
| Ubuntu Studio 16.04 | 1         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 129       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-46-lowlatency    | 5         | 3.85%   |
| 5.13.0-28-lowlatency    | 5         | 3.85%   |
| 5.4.0-52-lowlatency     | 4         | 3.08%   |
| 5.4.0-42-lowlatency     | 4         | 3.08%   |
| 5.8.0-55-lowlatency     | 3         | 2.31%   |
| 5.8.0-50-lowlatency     | 3         | 2.31%   |
| 5.8.0-44-lowlatency     | 3         | 2.31%   |
| 5.8.0-25-lowlatency     | 3         | 2.31%   |
| 5.4.0-65-lowlatency     | 3         | 2.31%   |
| 5.4.0-26-lowlatency     | 3         | 2.31%   |
| 5.15.0-47-lowlatency    | 3         | 2.31%   |
| 5.11.0-44-lowlatency    | 3         | 2.31%   |
| 5.11.0-34-lowlatency    | 3         | 2.31%   |
| 5.8.0-48-lowlatency     | 2         | 1.54%   |
| 5.8.0-29-lowlatency     | 2         | 1.54%   |
| 5.4.0-94-lowlatency     | 2         | 1.54%   |
| 5.4.0-58-lowlatency     | 2         | 1.54%   |
| 5.4.0-56-lowlatency     | 2         | 1.54%   |
| 5.4.0-45-lowlatency     | 2         | 1.54%   |
| 5.15.0-52-lowlatency    | 2         | 1.54%   |
| 5.15.0-50-lowlatency    | 2         | 1.54%   |
| 5.15.0-48-lowlatency    | 2         | 1.54%   |
| 5.15.0-40-lowlatency    | 2         | 1.54%   |
| 5.15.0-30-lowlatency    | 2         | 1.54%   |
| 5.13.0-30-lowlatency    | 2         | 1.54%   |
| 5.11.0-27-lowlatency    | 2         | 1.54%   |
| 5.8.0-59-lowlatency     | 1         | 0.77%   |
| 5.8.0-45-lowlatency     | 1         | 0.77%   |
| 5.8.0-43-lowlatency     | 1         | 0.77%   |
| 5.8.0-36-lowlatency     | 1         | 0.77%   |
| 5.8.0-34-lowlatency     | 1         | 0.77%   |
| 5.8.0-34-generic        | 1         | 0.77%   |
| 5.8.0-33-lowlatency     | 1         | 0.77%   |
| 5.7.6-050706-lowlatency | 1         | 0.77%   |
| 5.7.6-050706-generic    | 1         | 0.77%   |
| 5.4.0-99-lowlatency     | 1         | 0.77%   |
| 5.4.0-96-lowlatency     | 1         | 0.77%   |
| 5.4.0-88-lowlatency     | 1         | 0.77%   |
| 5.4.0-72-lowlatency     | 1         | 0.77%   |
| 5.4.0-71-lowlatency     | 1         | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 38.76%  |
| 5.8.0   | 23        | 17.83%  |
| 5.15.0  | 22        | 17.05%  |
| 5.11.0  | 15        | 11.63%  |
| 5.13.0  | 10        | 7.75%   |
| 4.15.0  | 3         | 2.33%   |
| 5.3.0   | 2         | 1.55%   |
| 5.7.6   | 1         | 0.78%   |
| 5.17.1  | 1         | 0.78%   |
| 5.15.6  | 1         | 0.78%   |
| 4.4.0   | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 38.76%  |
| 5.8     | 23        | 17.83%  |
| 5.15    | 23        | 17.83%  |
| 5.11    | 15        | 11.63%  |
| 5.13    | 10        | 7.75%   |
| 4.15    | 3         | 2.33%   |
| 5.3     | 2         | 1.55%   |
| 5.7     | 1         | 0.78%   |
| 5.17    | 1         | 0.78%   |
| 4.4     | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 127       | 98.45%  |
| i686    | 1         | 0.78%   |
| aarch64 | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 73        | 56.59%  |
| KDE5            | 39        | 30.23%  |
| GNOME           | 10        | 7.75%   |
| MATE            | 2         | 1.55%   |
| LXQt            | 2         | 1.55%   |
| KDE             | 1         | 0.78%   |
| GNOME Flashback | 1         | 0.78%   |
| Cinnamon        | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 122       | 94.57%  |
| Wayland | 5         | 3.88%   |
| Tty     | 2         | 1.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 49        | 37.98%  |
| SDDM    | 35        | 27.13%  |
| LightDM | 33        | 25.58%  |
| GDM     | 11        | 8.53%   |
| LXDM    | 1         | 0.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 54        | 41.86%  |
| fr_FR      | 17        | 13.18%  |
| de_DE      | 9         | 6.98%   |
| pt_BR      | 6         | 4.65%   |
| it_IT      | 6         | 4.65%   |
| C          | 5         | 3.88%   |
| en_GB      | 4         | 3.1%    |
| en_CA      | 4         | 3.1%    |
| en_AU      | 2         | 1.55%   |
| en_AG      | 2         | 1.55%   |
| Unknown    | 2         | 1.55%   |
| sk_SK      | 1         | 0.78%   |
| ru_RU      | 1         | 0.78%   |
| nl_NL      | 1         | 0.78%   |
| nl_BE      | 1         | 0.78%   |
| nb_NO      | 1         | 0.78%   |
| hu_HU      | 1         | 0.78%   |
| fr_FR.UTF8 | 1         | 0.78%   |
| fr_CH      | 1         | 0.78%   |
| es_NI      | 1         | 0.78%   |
| es_GT      | 1         | 0.78%   |
| es_ES      | 1         | 0.78%   |
| es_CR      | 1         | 0.78%   |
| es_AR      | 1         | 0.78%   |
| en_NG      | 1         | 0.78%   |
| en_IE      | 1         | 0.78%   |
| en_DE      | 1         | 0.78%   |
| ca_ES      | 1         | 0.78%   |
| ca_AD      | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 72        | 55.81%  |
| BIOS | 57        | 44.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 123       | 95.35%  |
| Overlay | 4         | 3.1%    |
| Xfs     | 1         | 0.78%   |
| Ext2    | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 78        | 60.47%  |
| MBR  | 51        | 39.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 79.84%  |
| Yes       | 26        | 20.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 52.71%  |
| Yes       | 61        | 47.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 25        | 19.38%  |
| Dell                    | 22        | 17.05%  |
| Lenovo                  | 17        | 13.18%  |
| Hewlett-Packard         | 17        | 13.18%  |
| Gigabyte Technology     | 9         | 6.98%   |
| Acer                    | 5         | 3.88%   |
| Apple                   | 4         | 3.1%    |
| Fujitsu                 | 3         | 2.33%   |
| Toshiba                 | 2         | 1.55%   |
| MSI                     | 2         | 1.55%   |
| Intel                   | 2         | 1.55%   |
| HUAWEI                  | 2         | 1.55%   |
| AZW                     | 2         | 1.55%   |
| ASRock                  | 2         | 1.55%   |
| Sony                    | 1         | 0.78%   |
| Samsung Electronics     | 1         | 0.78%   |
| Razer                   | 1         | 0.78%   |
| Raspberry Pi Foundation | 1         | 0.78%   |
| Pegatron                | 1         | 0.78%   |
| Packard Bell            | 1         | 0.78%   |
| Medion                  | 1         | 0.78%   |
| Intel Client Systems    | 1         | 0.78%   |
| IBM                     | 1         | 0.78%   |
| Google                  | 1         | 0.78%   |
| Getac                   | 1         | 0.78%   |
| Foxconn                 | 1         | 0.78%   |
| Clevo                   | 1         | 0.78%   |
| Avell High Performance  | 1         | 0.78%   |
| Acidanthera             | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 3.1%    |
| Lenovo G50-45 80E3                         | 2         | 1.55%   |
| HP Pavilion dv6                            | 2         | 1.55%   |
| Dell OptiPlex 790                          | 2         | 1.55%   |
| Toshiba Satellite L755D                    | 1         | 0.78%   |
| Toshiba Satellite C855                     | 1         | 0.78%   |
| Sony VGN-NS31M_W                           | 1         | 0.78%   |
| Samsung 305V4A/305V5A                      | 1         | 0.78%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.78%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.78%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.78%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.78%   |
| MSI MS-7A57                                | 1         | 0.78%   |
| MSI MS-7752                                | 1         | 0.78%   |
| Medion MD34207/C746                        | 1         | 0.78%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.78%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.78%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.78%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.78%   |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.78%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1         | 0.78%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.78%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4       | 1         | 0.78%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 1         | 0.78%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 1         | 0.78%   |
| Lenovo IdeaPad 3 15ABA7 82RN               | 1         | 0.78%   |
| Lenovo IdeaPad 3 14ARE05 81W3              | 1         | 0.78%   |
| Lenovo IdeaCentre AIO 520-27ICB F0DE00EJRI | 1         | 0.78%   |
| Intel NUC8i5BEH                            | 1         | 0.78%   |
| Intel DQ965GF HD/FP Audio                  | 1         | 0.78%   |
| Intel Client Systems LAPBC510              | 1         | 0.78%   |
| IBM 8188PPV                                | 1         | 0.78%   |
| HUAWEI KLVL-WXXW                           | 1         | 0.78%   |
| HUAWEI HLYL-WXX9                           | 1         | 0.78%   |
| HP ZBook 15 G3                             | 1         | 0.78%   |
| HP Z620 Workstation                        | 1         | 0.78%   |
| HP Stream Laptop 14-cb0XX                  | 1         | 0.78%   |
| HP Sona                                    | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Dell OptiPlex                 | 8         | 6.2%    |
| Dell Inspiron                 | 8         | 6.2%    |
| Lenovo ThinkPad               | 7         | 5.43%   |
| HP Compaq                     | 6         | 4.65%   |
| Lenovo IdeaPad                | 5         | 3.88%   |
| ASUS ROG                      | 4         | 3.1%    |
| ASUS All                      | 4         | 3.1%    |
| Acer Aspire                   | 4         | 3.1%    |
| Fujitsu ESPRIMO               | 3         | 2.33%   |
| Dell Latitude                 | 3         | 2.33%   |
| Toshiba Satellite             | 2         | 1.55%   |
| Lenovo G50-45                 | 2         | 1.55%   |
| HP Pavilion                   | 2         | 1.55%   |
| Dell Precision                | 2         | 1.55%   |
| ASUS TUF                      | 2         | 1.55%   |
| ASUS P8P67                    | 2         | 1.55%   |
| Sony VGN-NS31M                | 1         | 0.78%   |
| Samsung 305V4A                | 1         | 0.78%   |
| Razer Blade                   | 1         | 0.78%   |
| RPi Raspberry                 | 1         | 0.78%   |
| Pegatron FL368AA-UUZ          | 1         | 0.78%   |
| Packard Bell IMEDIA           | 1         | 0.78%   |
| MSI MS-7A57                   | 1         | 0.78%   |
| MSI MS-7752                   | 1         | 0.78%   |
| Medion MD34207                | 1         | 0.78%   |
| Lenovo ThinkCentre            | 1         | 0.78%   |
| Lenovo Legion                 | 1         | 0.78%   |
| Lenovo IdeaCentre             | 1         | 0.78%   |
| Intel NUC8i5BEH               | 1         | 0.78%   |
| Intel DQ965GF                 | 1         | 0.78%   |
| Intel Client Systems LAPBC510 | 1         | 0.78%   |
| IBM 8188PPV                   | 1         | 0.78%   |
| HUAWEI KLVL-WXXW              | 1         | 0.78%   |
| HUAWEI HLYL-WXX9              | 1         | 0.78%   |
| HP ZBook                      | 1         | 0.78%   |
| HP Z620                       | 1         | 0.78%   |
| HP Stream                     | 1         | 0.78%   |
| HP Sona                       | 1         | 0.78%   |
| HP ProDesk                    | 1         | 0.78%   |
| HP OMEN                       | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 14        | 10.85%  |
| 2014 | 13        | 10.08%  |
| 2012 | 13        | 10.08%  |
| 2019 | 11        | 8.53%   |
| 2018 | 10        | 7.75%   |
| 2011 | 10        | 7.75%   |
| 2013 | 9         | 6.98%   |
| 2017 | 8         | 6.2%    |
| 2021 | 7         | 5.43%   |
| 2010 | 7         | 5.43%   |
| 2016 | 6         | 4.65%   |
| 2008 | 6         | 4.65%   |
| 2015 | 4         | 3.1%    |
| 2007 | 4         | 3.1%    |
| 2009 | 3         | 2.33%   |
| 2005 | 3         | 2.33%   |
| 2022 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 61        | 47.29%  |
| Notebook       | 58        | 44.96%  |
| All in one     | 5         | 3.88%   |
| Mini pc        | 3         | 2.33%   |
| System on chip | 1         | 0.78%   |
| Convertible    | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 121       | 93.8%   |
| Enabled  | 8         | 6.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 127       | 98.45%  |
| Yes  | 2         | 1.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 38        | 29.46%  |
| 16.01-24.0  | 31        | 24.03%  |
| 8.01-16.0   | 22        | 17.05%  |
| 3.01-4.0    | 13        | 10.08%  |
| 32.01-64.0  | 10        | 7.75%   |
| 64.01-256.0 | 5         | 3.88%   |
| 1.01-2.0    | 4         | 3.1%    |
| 24.01-32.0  | 3         | 2.33%   |
| 2.01-3.0    | 3         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 48        | 36.92%  |
| 2.01-3.0   | 30        | 23.08%  |
| 4.01-8.0   | 22        | 16.92%  |
| 3.01-4.0   | 16        | 12.31%  |
| 8.01-16.0  | 9         | 6.92%   |
| 0.51-1.0   | 4         | 3.08%   |
| 24.01-32.0 | 1         | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 53.49%  |
| 2      | 44        | 34.11%  |
| 3      | 6         | 4.65%   |
| 4      | 3         | 2.33%   |
| 7      | 2         | 1.55%   |
| 0      | 2         | 1.55%   |
| 11     | 1         | 0.78%   |
| 10     | 1         | 0.78%   |
| 5      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 52.71%  |
| Yes       | 61        | 47.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 89.15%  |
| No        | 14        | 10.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 72.87%  |
| No        | 35        | 27.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 55.04%  |
| No        | 58        | 44.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 28        | 21.71%  |
| France                 | 19        | 14.73%  |
| Germany                | 15        | 11.63%  |
| Italy                  | 9         | 6.98%   |
| Brazil                 | 7         | 5.43%   |
| Canada                 | 5         | 3.88%   |
| UK                     | 4         | 3.1%    |
| Spain                  | 3         | 2.33%   |
| Russia                 | 3         | 2.33%   |
| Austria                | 3         | 2.33%   |
| Australia              | 3         | 2.33%   |
| Taiwan                 | 2         | 1.55%   |
| Romania                | 2         | 1.55%   |
| Norway                 | 2         | 1.55%   |
| Mexico                 | 2         | 1.55%   |
| Costa Rica             | 2         | 1.55%   |
| Belgium                | 2         | 1.55%   |
| Yemen                  | 1         | 0.78%   |
| Turkey                 | 1         | 0.78%   |
| Switzerland            | 1         | 0.78%   |
| Sweden                 | 1         | 0.78%   |
| Slovakia               | 1         | 0.78%   |
| Poland                 | 1         | 0.78%   |
| Nigeria                | 1         | 0.78%   |
| Nicaragua              | 1         | 0.78%   |
| Netherlands            | 1         | 0.78%   |
| Kenya                  | 1         | 0.78%   |
| Ivory Coast            | 1         | 0.78%   |
| Indonesia              | 1         | 0.78%   |
| Hungary                | 1         | 0.78%   |
| Guatemala              | 1         | 0.78%   |
| Finland                | 1         | 0.78%   |
| Bulgaria               | 1         | 0.78%   |
| Bosnia and Herzegovina | 1         | 0.78%   |
| Argentina              | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Paris                   | 3         | 2.33%   |
| Turin                   | 2         | 1.55%   |
| Stuttgart               | 2         | 1.55%   |
| Montreal                | 2         | 1.55%   |
| Mississauga             | 2         | 1.55%   |
| Houston                 | 2         | 1.55%   |
| Denver                  | 2         | 1.55%   |
| Bucharest               | 2         | 1.55%   |
| Béziers                | 2         | 1.55%   |
| Zanesville              | 1         | 0.78%   |
| Yekaterinburg           | 1         | 0.78%   |
| Wroclaw                 | 1         | 0.78%   |
| Woonsocket              | 1         | 0.78%   |
| Woodland Park           | 1         | 0.78%   |
| Villefontaine           | 1         | 0.78%   |
| Vienna                  | 1         | 0.78%   |
| Velleron                | 1         | 0.78%   |
| Tilburg                 | 1         | 0.78%   |
| Taylor                  | 1         | 0.78%   |
| Taipei                  | 1         | 0.78%   |
| Taichung                | 1         | 0.78%   |
| Sunderland              | 1         | 0.78%   |
| Stockholm               | 1         | 0.78%   |
| Stabekk                 | 1         | 0.78%   |
| Sofia                   | 1         | 0.78%   |
| Sleman                  | 1         | 0.78%   |
| Sherman Oaks            | 1         | 0.78%   |
| Seropedica              | 1         | 0.78%   |
| Sarajevo                | 1         | 0.78%   |
| Sao Paulo               | 1         | 0.78%   |
| Santa Barbara d'Oeste   | 1         | 0.78%   |
| Sanaa                   | 1         | 0.78%   |
| San Secondo di Pinerolo | 1         | 0.78%   |
| San Juan                | 1         | 0.78%   |
| Samara                  | 1         | 0.78%   |
| Saint-Ouen-l'Aumone     | 1         | 0.78%   |
| Rio Grande da Serra     | 1         | 0.78%   |
| Rio de Janeiro          | 1         | 0.78%   |
| Rennes                  | 1         | 0.78%   |
| Ragusa                  | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 42     | 17.35%  |
| WDC                 | 32        | 39     | 16.33%  |
| Seagate             | 23        | 31     | 11.73%  |
| SanDisk             | 14        | 15     | 7.14%   |
| Toshiba             | 13        | 14     | 6.63%   |
| Kingston            | 8         | 8      | 4.08%   |
| Intel               | 8         | 10     | 4.08%   |
| Unknown             | 7         | 7      | 3.57%   |
| Crucial             | 6         | 6      | 3.06%   |
| Hitachi             | 5         | 5      | 2.55%   |
| HGST                | 4         | 4      | 2.04%   |
| SK hynix            | 3         | 4      | 1.53%   |
| Micron Technology   | 3         | 3      | 1.53%   |
| ASMT                | 3         | 3      | 1.53%   |
| JMicron Technology  | 2         | 2      | 1.02%   |
| Intenso             | 2         | 2      | 1.02%   |
| Fujitsu             | 2         | 2      | 1.02%   |
| Corsair             | 2         | 3      | 1.02%   |
| China               | 2         | 2      | 1.02%   |
| BHT                 | 2         | 2      | 1.02%   |
| A-DATA Technology   | 2         | 2      | 1.02%   |
| USB 3.0             | 1         | 2      | 0.51%   |
| Union Memory        | 1         | 1      | 0.51%   |
| UMIS                | 1         | 1      | 0.51%   |
| TO Exter            | 1         | 1      | 0.51%   |
| Team                | 1         | 1      | 0.51%   |
| SPCC                | 1         | 1      | 0.51%   |
| Phison Electronics  | 1         | 1      | 0.51%   |
| Phison              | 1         | 1      | 0.51%   |
| Patriot             | 1         | 1      | 0.51%   |
| OCZ                 | 1         | 1      | 0.51%   |
| NGFF                | 1         | 1      | 0.51%   |
| Maxtor              | 1         | 1      | 0.51%   |
| Leven               | 1         | 1      | 0.51%   |
| KIOXIA              | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 1      | 0.51%   |
| Integral            | 1         | 1      | 0.51%   |
| Inateck             | 1         | 1      | 0.51%   |
| EAGET               | 1         | 1      | 0.51%   |
| Apple               | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.83%   |
| Toshiba MQ01ABD100 1TB                    | 3         | 1.38%   |
| Seagate ST2000DM001-1ER164 2TB            | 3         | 1.38%   |
| Samsung SSD 870 EVO 1TB                   | 3         | 1.38%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 1.38%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 1.38%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.92%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.92%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.92%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.92%   |
| Seagate ST2000DM008-2FR102 2TB            | 2         | 0.92%   |
| Seagate Expansion 2TB                     | 2         | 0.92%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.92%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.92%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.92%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.92%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.92%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.92%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.92%   |
| JMicron Generic 500GB                     | 2         | 0.92%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 0.92%   |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.46%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 1         | 0.46%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.46%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1         | 0.46%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.46%   |
| WDC WD5000BPKT-60PK4T0 500GB              | 1         | 0.46%   |
| WDC WD5000AAKS-75V0A0 500GB               | 1         | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB                  | 1         | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB                  | 1         | 0.46%   |
| WDC WD40EFAX-68JH4N1 4TB                  | 1         | 0.46%   |
| WDC WD40EFAX-68JH4N0 4TB                  | 1         | 0.46%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.46%   |
| WDC WD3200BPVT-75JJ5T0 320GB              | 1         | 0.46%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.46%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.46%   |
| WDC WD3200AAKS-00VYA0 320GB               | 1         | 0.46%   |
| WDC WD30EZRZ-00Z5HB0 3TB                  | 1         | 0.46%   |
| WDC WD30EZRX-00SPEB0 3TB                  | 1         | 0.46%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 32.1%   |
| Seagate             | 23        | 30     | 28.4%   |
| Toshiba             | 12        | 13     | 14.81%  |
| Hitachi             | 5         | 5      | 6.17%   |
| Samsung Electronics | 4         | 4      | 4.94%   |
| HGST                | 4         | 4      | 4.94%   |
| Fujitsu             | 2         | 2      | 2.47%   |
| USB 3.0             | 1         | 2      | 1.23%   |
| Unknown             | 1         | 1      | 1.23%   |
| Maxtor              | 1         | 1      | 1.23%   |
| Inateck             | 1         | 1      | 1.23%   |
| ASMT                | 1         | 1      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 25     | 30.99%  |
| SanDisk             | 12        | 13     | 16.9%   |
| Kingston            | 7         | 7      | 9.86%   |
| Crucial             | 6         | 6      | 8.45%   |
| Micron Technology   | 2         | 2      | 2.82%   |
| Intenso             | 2         | 2      | 2.82%   |
| China               | 2         | 2      | 2.82%   |
| BHT                 | 2         | 2      | 2.82%   |
| ASMT                | 2         | 2      | 2.82%   |
| A-DATA Technology   | 2         | 2      | 2.82%   |
| WDC                 | 1         | 1      | 1.41%   |
| Toshiba             | 1         | 1      | 1.41%   |
| TO Exter            | 1         | 1      | 1.41%   |
| SPCC                | 1         | 1      | 1.41%   |
| Patriot             | 1         | 1      | 1.41%   |
| OCZ                 | 1         | 1      | 1.41%   |
| NGFF                | 1         | 1      | 1.41%   |
| Leven               | 1         | 1      | 1.41%   |
| KingSpec            | 1         | 1      | 1.41%   |
| Intel               | 1         | 1      | 1.41%   |
| Integral            | 1         | 1      | 1.41%   |
| Corsair             | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 65        | 97     | 38.92%  |
| SSD     | 59        | 75     | 35.33%  |
| NVMe    | 34        | 44     | 20.36%  |
| MMC     | 7         | 8      | 4.19%   |
| Unknown | 2         | 2      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 157    | 64.9%   |
| NVMe | 33        | 42     | 21.85%  |
| SAS  | 13        | 19     | 8.61%   |
| MMC  | 7         | 8      | 4.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 92     | 53.24%  |
| 0.51-1.0   | 40        | 48     | 28.78%  |
| 1.01-2.0   | 11        | 13     | 7.91%   |
| 3.01-4.0   | 8         | 10     | 5.76%   |
| 4.01-10.0  | 4         | 6      | 2.88%   |
| 2.01-3.0   | 2         | 3      | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 31.01%  |
| 251-500        | 21        | 16.28%  |
| 501-1000       | 20        | 15.5%   |
| 1001-2000      | 15        | 11.63%  |
| 51-100         | 10        | 7.75%   |
| More than 3000 | 9         | 6.98%   |
| 21-50          | 8         | 6.2%    |
| 1-20           | 5         | 3.88%   |
| 2001-3000      | 1         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 34.62%  |
| 21-50          | 25        | 19.23%  |
| 101-250        | 18        | 13.85%  |
| 51-100         | 12        | 9.23%   |
| 251-500        | 10        | 7.69%   |
| 501-1000       | 8         | 6.15%   |
| More than 3000 | 5         | 3.85%   |
| 1001-2000      | 5         | 3.85%   |
| 2001-3000      | 2         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 10%     |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 3.33%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 3.33%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 3.33%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 3.33%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 3.33%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 3.33%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 3.33%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 3.33%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.33%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 3.33%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 3.33%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 3.33%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.33%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 3.33%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 3.33%   |
| Samsung Electronics HD753LJ 752GB                   | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.33%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 3.33%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 3.33%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.33%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 3.33%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 3.33%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 3.33%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 30%     |
| WDC                 | 6         | 6      | 20%     |
| Samsung Electronics | 5         | 5      | 16.67%  |
| Toshiba             | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| A-DATA Technology   | 2         | 2      | 6.67%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| KingSpec            | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 39.13%  |
| WDC                 | 6         | 6      | 26.09%  |
| Samsung Electronics | 3         | 3      | 13.04%  |
| Toshiba             | 2         | 2      | 8.7%    |
| Hitachi             | 2         | 2      | 8.7%    |
| HGST                | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 75.86%  |
| SSD  | 6         | 6      | 20.69%  |
| NVMe | 1         | 1      | 3.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 103       | 169    | 68.21%  |
| Malfunc  | 29        | 30     | 19.21%  |
| Detected | 18        | 26     | 11.92%  |
| Failed   | 1         | 1      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 92        | 55.76%  |
| AMD                         | 26        | 15.76%  |
| Samsung Electronics         | 10        | 6.06%   |
| SanDisk                     | 6         | 3.64%   |
| Marvell Technology Group    | 5         | 3.03%   |
| ASMedia Technology          | 5         | 3.03%   |
| Phison Electronics          | 4         | 2.42%   |
| SK hynix                    | 3         | 1.82%   |
| Nvidia                      | 3         | 1.82%   |
| Union Memory (Shenzhen)     | 2         | 1.21%   |
| JMicron Technology          | 2         | 1.21%   |
| VIA Technologies            | 1         | 0.61%   |
| Silicon Image               | 1         | 0.61%   |
| Micron Technology           | 1         | 0.61%   |
| KIOXIA                      | 1         | 0.61%   |
| Kingston Technology Company | 1         | 0.61%   |
| Apple                       | 1         | 0.61%   |
| Adaptec                     | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 10.05%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 6.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 4.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 3.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.51%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 2.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.51%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.51%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 1.01%   |
| SK hynix BC511                                                                 | 2         | 1.01%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.01%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 1.01%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 1.01%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.01%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2         | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.01%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.01%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.5%    |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 58.08%  |
| NVMe | 34        | 20.36%  |
| IDE  | 22        | 13.17%  |
| RAID | 11        | 6.59%   |
| SAS  | 2         | 1.2%    |
| SCSI | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 97        | 75.19%  |
| AMD    | 31        | 24.03%  |
| ARM    | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 2.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 2.33%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 2.33%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 2.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.55%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.55%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.78%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.78%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.78%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.78%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.78%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.78%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.78%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.78%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.78%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.78%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.78%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.78%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.78%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.78%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.78%   |
| Intel Core i7-6700T CPU @ 2.80GHz       | 1         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.78%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.78%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz      | 1         | 0.78%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.78%   |
| Intel Core i7-3940XM CPU @ 3.00GHz      | 1         | 0.78%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 1         | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 0.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 0.78%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 34        | 26.36%  |
| Intel Core i7          | 29        | 22.48%  |
| Intel Core i3          | 8         | 6.2%    |
| Other                  | 6         | 4.65%   |
| Intel Celeron          | 5         | 3.88%   |
| AMD Ryzen 7            | 5         | 3.88%   |
| AMD Ryzen 5            | 5         | 3.88%   |
| Intel Core 2 Duo       | 4         | 3.1%    |
| Intel Xeon             | 3         | 2.33%   |
| Intel Pentium 4        | 2         | 1.55%   |
| Intel Core i9          | 2         | 1.55%   |
| AMD Ryzen 9            | 2         | 1.55%   |
| AMD Ryzen 3            | 2         | 1.55%   |
| AMD Phenom II X4       | 2         | 1.55%   |
| AMD E                  | 2         | 1.55%   |
| AMD Athlon II X2       | 2         | 1.55%   |
| AMD A4                 | 2         | 1.55%   |
| Intel Pentium Dual     | 1         | 0.78%   |
| Intel Pentium D        | 1         | 0.78%   |
| Intel Pentium          | 1         | 0.78%   |
| Intel Genuine          | 1         | 0.78%   |
| Intel Core 2           | 1         | 0.78%   |
| AMD Ryzen Threadripper | 1         | 0.78%   |
| AMD FX                 | 1         | 0.78%   |
| AMD E2                 | 1         | 0.78%   |
| AMD E1                 | 1         | 0.78%   |
| AMD Athlon X4          | 1         | 0.78%   |
| AMD Athlon Dual Core   | 1         | 0.78%   |
| AMD Athlon 64 X2       | 1         | 0.78%   |
| AMD A6                 | 1         | 0.78%   |
| AMD A10                | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 55        | 42.64%  |
| 2      | 46        | 35.66%  |
| 6      | 13        | 10.08%  |
| 8      | 7         | 5.43%   |
| 1      | 3         | 2.33%   |
| 10     | 2         | 1.55%   |
| 32     | 1         | 0.78%   |
| 16     | 1         | 0.78%   |
| 12     | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 128       | 99.22%  |
| 2      | 1         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 78        | 60.47%  |
| 1      | 51        | 39.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 128       | 99.22%  |
| 32-bit         | 1         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 13        | 10.08%  |
| Unknown    | 13        | 10.08%  |
| 0x306a9    | 11        | 8.53%   |
| 0x206a7    | 11        | 8.53%   |
| 0x906ea    | 7         | 5.43%   |
| 0x806ea    | 4         | 3.1%    |
| 0x806c1    | 4         | 3.1%    |
| 0x506e3    | 4         | 3.1%    |
| 0x08600104 | 4         | 3.1%    |
| 0x306d4    | 3         | 2.33%   |
| 0x010000c8 | 3         | 2.33%   |
| 0xf41      | 2         | 1.55%   |
| 0x906e9    | 2         | 1.55%   |
| 0x706e5    | 2         | 1.55%   |
| 0x6fd      | 2         | 1.55%   |
| 0x406e3    | 2         | 1.55%   |
| 0x206d7    | 2         | 1.55%   |
| 0x106e5    | 2         | 1.55%   |
| 0x10676    | 2         | 1.55%   |
| 0x08701021 | 2         | 1.55%   |
| 0x08600106 | 2         | 1.55%   |
| 0x07030105 | 2         | 1.55%   |
| 0xf65      | 1         | 0.78%   |
| 0xa0655    | 1         | 0.78%   |
| 0xa0652    | 1         | 0.78%   |
| 0x906ed    | 1         | 0.78%   |
| 0x706a1    | 1         | 0.78%   |
| 0x6fb      | 1         | 0.78%   |
| 0x6f6      | 1         | 0.78%   |
| 0x506ca    | 1         | 0.78%   |
| 0x506c9    | 1         | 0.78%   |
| 0x50654    | 1         | 0.78%   |
| 0x406c4    | 1         | 0.78%   |
| 0x40661    | 1         | 0.78%   |
| 0x40651    | 1         | 0.78%   |
| 0x20655    | 1         | 0.78%   |
| 0x106a5    | 1         | 0.78%   |
| 0x1067a    | 1         | 0.78%   |
| 0x0a50000c | 1         | 0.78%   |
| 0x0a201009 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 12.4%   |
| Haswell       | 15        | 11.63%  |
| SandyBridge   | 13        | 10.08%  |
| Zen 2         | 11        | 8.53%   |
| IvyBridge     | 11        | 8.53%   |
| Skylake       | 10        | 7.75%   |
| TigerLake     | 4         | 3.1%    |
| Penryn        | 4         | 3.1%    |
| K10           | 4         | 3.1%    |
| Core          | 4         | 3.1%    |
| Broadwell     | 4         | 3.1%    |
| Puma          | 3         | 2.33%   |
| NetBurst      | 3         | 2.33%   |
| Nehalem       | 3         | 2.33%   |
| Zen 3         | 2         | 1.55%   |
| Westmere      | 2         | 1.55%   |
| Piledriver    | 2         | 1.55%   |
| K8 Hammer     | 2         | 1.55%   |
| IceLake       | 2         | 1.55%   |
| Goldmont      | 2         | 1.55%   |
| CometLake     | 2         | 1.55%   |
| Unknown       | 2         | 1.55%   |
| Zen+          | 1         | 0.78%   |
| Zen           | 1         | 0.78%   |
| Steamroller   | 1         | 0.78%   |
| Silvermont    | 1         | 0.78%   |
| K10 Llano     | 1         | 0.78%   |
| Goldmont plus | 1         | 0.78%   |
| Excavator     | 1         | 0.78%   |
| Bobcat        | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 68        | 45.33%  |
| Nvidia | 49        | 32.67%  |
| AMD    | 33        | 22%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 7         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 3.9%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 3.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.9%    |
| Intel HD Graphics 530                                                       | 5         | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.6%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.95%   |
| Intel UHD Graphics 620                                                      | 3         | 1.95%   |
| Intel HD Graphics 5500                                                      | 3         | 1.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.95%   |
| Nvidia TU117M                                                               | 2         | 1.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.3%    |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.3%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 1.3%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 1.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.3%    |
| Intel HD Graphics 630                                                       | 2         | 1.3%    |
| Intel HD Graphics 500                                                       | 2         | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.3%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.65%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1         | 0.65%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 1         | 0.65%   |
| Nvidia GT216 [GeForce 315]                                                  | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.65%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 37.98%  |
| 1 x Nvidia     | 30        | 23.26%  |
| 1 x AMD        | 26        | 20.16%  |
| Intel + Nvidia | 14        | 10.85%  |
| AMD + Nvidia   | 4         | 3.1%    |
| Intel + AMD    | 2         | 1.55%   |
| Other          | 1         | 0.78%   |
| 2 x Nvidia     | 1         | 0.78%   |
| 2 x Intel      | 1         | 0.78%   |
| 2 x AMD        | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 79.07%  |
| Proprietary | 25        | 19.38%  |
| Unknown     | 2         | 1.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 45.74%  |
| 1.01-2.0   | 17        | 13.18%  |
| 0.01-0.5   | 16        | 12.4%   |
| 0.51-1.0   | 15        | 11.63%  |
| 3.01-4.0   | 10        | 7.75%   |
| 5.01-6.0   | 4         | 3.1%    |
| 8.01-16.0  | 4         | 3.1%    |
| 7.01-8.0   | 2         | 1.55%   |
| 2.01-3.0   | 1         | 0.78%   |
| 16.01-24.0 | 1         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 12.84%  |
| AU Optronics            | 15        | 10.14%  |
| LG Display              | 13        | 8.78%   |
| Goldstar                | 10        | 6.76%   |
| Hewlett-Packard         | 9         | 6.08%   |
| Dell                    | 9         | 6.08%   |
| BOE                     | 9         | 6.08%   |
| Philips                 | 8         | 5.41%   |
| Acer                    | 8         | 5.41%   |
| Ancor Communications    | 7         | 4.73%   |
| Chimei Innolux          | 6         | 4.05%   |
| Lenovo                  | 3         | 2.03%   |
| Sharp                   | 2         | 1.35%   |
| Iiyama                  | 2         | 1.35%   |
| Hannspree               | 2         | 1.35%   |
| Eizo                    | 2         | 1.35%   |
| BenQ                    | 2         | 1.35%   |
| Apple                   | 2         | 1.35%   |
| AOC                     | 2         | 1.35%   |
| VIE                     | 1         | 0.68%   |
| Unknown                 | 1         | 0.68%   |
| UGD                     | 1         | 0.68%   |
| TVT                     | 1         | 0.68%   |
| Targa Visionary         | 1         | 0.68%   |
| Sony                    | 1         | 0.68%   |
| Seiki                   | 1         | 0.68%   |
| Onkyo                   | 1         | 0.68%   |
| NEC Computers           | 1         | 0.68%   |
| Medion                  | 1         | 0.68%   |
| LG Philips              | 1         | 0.68%   |
| KTC                     | 1         | 0.68%   |
| Fujitsu Siemens         | 1         | 0.68%   |
| DENON                   | 1         | 0.68%   |
| CPT                     | 1         | 0.68%   |
| Chi Mei Optoelectronics | 1         | 0.68%   |
| ASUSTek Computer        | 1         | 0.68%   |
| Arnos Instruments       | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 2         | 1.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 1.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.28%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                   | 2         | 1.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 1.28%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.28%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                  | 1         | 0.64%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                  | 1         | 0.64%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch                | 1         | 0.64%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                         | 1         | 0.64%   |
| Targa Visionary LCD Monitor TARA240 1920x1080 520x300mm 23.6-inch      | 1         | 0.64%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                    | 1         | 0.64%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.64%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.64%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                    | 1         | 0.64%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch      | 1         | 0.64%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch    | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch   | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch   | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch   | 1         | 0.64%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch   | 1         | 0.64%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch    | 1         | 0.64%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch    | 1         | 0.64%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch     | 1         | 0.64%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 0.64%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1         | 0.64%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch              | 1         | 0.64%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                    | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 45.32%  |
| 1366x768 (WXGA)    | 22        | 15.83%  |
| 3840x2160 (4K)     | 13        | 9.35%   |
| 1280x1024 (SXGA)   | 10        | 7.19%   |
| 1680x1050 (WSXGA+) | 6         | 4.32%   |
| 1600x900 (HD+)     | 6         | 4.32%   |
| 2560x1440 (QHD)    | 4         | 2.88%   |
| 1440x900 (WXGA+)   | 4         | 2.88%   |
| 1920x1200 (WUXGA)  | 2         | 1.44%   |
| 1280x800 (WXGA)    | 2         | 1.44%   |
| 5760x2160          | 1         | 0.72%   |
| 2880x1800          | 1         | 0.72%   |
| 2160x1440          | 1         | 0.72%   |
| 1600x1200          | 1         | 0.72%   |
| 1400x1050          | 1         | 0.72%   |
| 1360x768           | 1         | 0.72%   |
| Unknown            | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 37        | 25.17%  |
| 21      | 16        | 10.88%  |
| 24      | 12        | 8.16%   |
| 23      | 12        | 8.16%   |
| 27      | 10        | 6.8%    |
| 19      | 8         | 5.44%   |
| 13      | 8         | 5.44%   |
| 17      | 6         | 4.08%   |
| 14      | 6         | 4.08%   |
| 22      | 5         | 3.4%    |
| 18      | 5         | 3.4%    |
| 20      | 4         | 2.72%   |
| 12      | 4         | 2.72%   |
| 84      | 2         | 1.36%   |
| 31      | 2         | 1.36%   |
| 65      | 1         | 0.68%   |
| 54      | 1         | 0.68%   |
| 52      | 1         | 0.68%   |
| 50      | 1         | 0.68%   |
| 43      | 1         | 0.68%   |
| 32      | 1         | 0.68%   |
| 26      | 1         | 0.68%   |
| 16      | 1         | 0.68%   |
| 11      | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 37.06%  |
| 501-600     | 32        | 22.38%  |
| 401-500     | 32        | 22.38%  |
| 201-300     | 9         | 6.29%   |
| 351-400     | 5         | 3.5%    |
| 1001-1500   | 4         | 2.8%    |
| 601-700     | 3         | 2.1%    |
| 1501-2000   | 2         | 1.4%    |
| 701-800     | 1         | 0.7%    |
| 901-1000    | 1         | 0.7%    |
| Unknown     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 75.76%  |
| 16/10   | 18        | 13.64%  |
| 5/4     | 9         | 6.82%   |
| 4/3     | 2         | 1.52%   |
| 3/2     | 2         | 1.52%   |
| Unknown | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 25.52%  |
| 201-250        | 36        | 24.83%  |
| 151-200        | 15        | 10.34%  |
| 81-90          | 11        | 7.59%   |
| 301-350        | 11        | 7.59%   |
| 141-150        | 11        | 7.59%   |
| More than 1000 | 6         | 4.14%   |
| 61-70          | 4         | 2.76%   |
| 251-300        | 4         | 2.76%   |
| 71-80          | 3         | 2.07%   |
| 351-500        | 3         | 2.07%   |
| 51-60          | 1         | 0.69%   |
| 111-120        | 1         | 0.69%   |
| 501-1000       | 1         | 0.69%   |
| Unknown        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 58        | 42.03%  |
| 101-120       | 37        | 26.81%  |
| 121-160       | 31        | 22.46%  |
| 161-240       | 8         | 5.8%    |
| More than 240 | 2         | 1.45%   |
| 1-50          | 1         | 0.72%   |
| Unknown       | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 96        | 73.85%  |
| 2     | 32        | 24.62%  |
| 3     | 1         | 0.77%   |
| 0     | 1         | 0.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 70        | 35.18%  |
| Intel                             | 68        | 34.17%  |
| Qualcomm Atheros                  | 22        | 11.06%  |
| Broadcom                          | 11        | 5.53%   |
| TP-Link                           | 3         | 1.51%   |
| Nvidia                            | 3         | 1.51%   |
| Broadcom Limited                  | 3         | 1.51%   |
| ASIX Electronics                  | 3         | 1.51%   |
| Ralink                            | 2         | 1.01%   |
| MediaTek                          | 2         | 1.01%   |
| Aquantia                          | 2         | 1.01%   |
| ZyDAS                             | 1         | 0.5%    |
| Wacom                             | 1         | 0.5%    |
| Ralink Technology                 | 1         | 0.5%    |
| Qualcomm Atheros Communications   | 1         | 0.5%    |
| NetGear                           | 1         | 0.5%    |
| Microsoft                         | 1         | 0.5%    |
| Marvell Technology Group          | 1         | 0.5%    |
| Huawei Technologies               | 1         | 0.5%    |
| Ericsson Business Mobile Networks | 1         | 0.5%    |
| DisplayLink                       | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 20.8%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 5.75%   |
| Intel Wireless 7265                                               | 7         | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.77%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.77%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.33%   |
| Intel Wireless-AC 9260                                            | 3         | 1.33%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.33%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.88%   |
| Realtek 802.11ac NIC                                              | 2         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.88%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.88%   |
| Intel Wireless 8260                                               | 2         | 0.88%   |
| Intel Wireless 7260                                               | 2         | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.88%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.88%   |
| ZyDAS ZD1211B 802.11g                                             | 1         | 0.44%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1         | 0.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.44%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.44%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.44%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 46.88%  |
| Realtek Semiconductor           | 16        | 16.67%  |
| Qualcomm Atheros                | 16        | 16.67%  |
| Broadcom                        | 6         | 6.25%   |
| TP-Link                         | 3         | 3.13%   |
| Ralink                          | 2         | 2.08%   |
| ZyDAS                           | 1         | 1.04%   |
| Wacom                           | 1         | 1.04%   |
| Ralink Technology               | 1         | 1.04%   |
| Qualcomm Atheros Communications | 1         | 1.04%   |
| NetGear                         | 1         | 1.04%   |
| Microsoft                       | 1         | 1.04%   |
| MediaTek                        | 1         | 1.04%   |
| Broadcom Limited                | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 7         | 7.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5         | 5.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 4.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 4         | 4.12%   |
| Intel Wi-Fi 6 AX201                                              | 4         | 4.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 4         | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 3         | 3.09%   |
| Intel Wireless-AC 9260                                           | 3         | 3.09%   |
| Intel Wireless 8265 / 8275                                       | 3         | 3.09%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 3.09%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 3.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.06%   |
| Realtek 802.11ac NIC                                             | 2         | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 2         | 2.06%   |
| Intel Wireless 8260                                              | 2         | 2.06%   |
| Intel Wireless 7260                                              | 2         | 2.06%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.06%   |
| ZyDAS ZD1211B 802.11g                                            | 1         | 1.03%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                         | 1         | 1.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 1         | 1.03%   |
| TP-Link 802.11ac WLAN Adapter                                    | 1         | 1.03%   |
| TP-Link 802.11ac NIC                                             | 1         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.03%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter          | 1         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1         | 1.03%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller        | 1         | 1.03%   |
| Realtek Realtek Network controller                               | 1         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 1.03%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.03%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                  | 1         | 1.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                 | 1         | 1.03%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                 | 1         | 1.03%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter       | 1         | 1.03%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]      | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 57        | 45.24%  |
| Intel                    | 43        | 34.13%  |
| Qualcomm Atheros         | 7         | 5.56%   |
| Broadcom                 | 6         | 4.76%   |
| Nvidia                   | 3         | 2.38%   |
| ASIX Electronics         | 3         | 2.38%   |
| Broadcom Limited         | 2         | 1.59%   |
| Aquantia                 | 2         | 1.59%   |
| MediaTek                 | 1         | 0.79%   |
| Marvell Technology Group | 1         | 0.79%   |
| DisplayLink              | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 37.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 10.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.94%   |
| Intel I211 Gigabit Network Connection                             | 4         | 3.15%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.36%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.57%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.57%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.79%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.79%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.79%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.79%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 115       | 54.5%   |
| WiFi     | 94        | 44.55%  |
| Modem    | 2         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 50.36%  |
| WiFi     | 68        | 49.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 55.04%  |
| 1     | 55        | 42.64%  |
| 3     | 2         | 1.55%   |
| 0     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 82.17%  |
| Yes  | 23        | 17.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 47.22%  |
| Qualcomm Atheros Communications | 8         | 11.11%  |
| Realtek Semiconductor           | 6         | 8.33%   |
| Cambridge Silicon Radio         | 6         | 8.33%   |
| Broadcom                        | 4         | 5.56%   |
| ASUSTek Computer                | 3         | 4.17%   |
| Apple                           | 3         | 4.17%   |
| Realtek                         | 2         | 2.78%   |
| Ralink Technology               | 2         | 2.78%   |
| MediaTek                        | 1         | 1.39%   |
| Lite-On Technology              | 1         | 1.39%   |
| Hewlett-Packard                 | 1         | 1.39%   |
| Foxconn International           | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 19.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 8.33%   |
| Intel AX201 Bluetooth                               | 6         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 8.33%   |
| Realtek Bluetooth Radio                             | 4         | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 4.17%   |
| Intel AX200 Bluetooth                               | 3         | 4.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 4.17%   |
| Realtek Bluetooth Radio                             | 2         | 2.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 2.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 2.78%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.39%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.39%   |
| Ralink CSR BS8510                                   | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.39%   |
| MediaTek Wireless_Device                            | 1         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.39%   |
| Intel AX210 Bluetooth                               | 1         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.39%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.39%   |
| ASUS BCM20702A0                                     | 1         | 1.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.39%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.39%   |
| Apple Bluetooth Host Controller                     | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 93        | 44.29%  |
| Nvidia                               | 39        | 18.57%  |
| AMD                                  | 35        | 16.67%  |
| Texas Instruments                    | 5         | 2.38%   |
| C-Media Electronics                  | 5         | 2.38%   |
| Yamaha                               | 3         | 1.43%   |
| Logitech                             | 3         | 1.43%   |
| QinHeng Electronics                  | 2         | 0.95%   |
| Mackie Designs                       | 2         | 0.95%   |
| ZOOM                                 | 1         | 0.48%   |
| Yealink Network Technology           | 1         | 0.48%   |
| Xilinx                               | 1         | 0.48%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.48%   |
| Textech International                | 1         | 0.48%   |
| Studiologic                          | 1         | 0.48%   |
| SteelSeries ApS                      | 1         | 0.48%   |
| Samson Technologies                  | 1         | 0.48%   |
| PreSonus Audio Electronics           | 1         | 0.48%   |
| Plantronics                          | 1         | 0.48%   |
| Medeli Electronics                   | 1         | 0.48%   |
| Mark of the Unicorn                  | 1         | 0.48%   |
| M-Audio                              | 1         | 0.48%   |
| KTMicro                              | 1         | 0.48%   |
| JMTek                                | 1         | 0.48%   |
| Jieli Technology                     | 1         | 0.48%   |
| Focusrite-Novation                   | 1         | 0.48%   |
| Ensoniq                              | 1         | 0.48%   |
| Behringer.......                     | 1         | 0.48%   |
| BEHRINGER International              | 1         | 0.48%   |
| ASUSTek Computer                     | 1         | 0.48%   |
| Apple                                | 1         | 0.48%   |
| Alesis                               | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 5.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.1%    |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 3.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.87%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.87%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.64%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.64%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.64%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.23%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 2         | 0.82%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2         | 0.82%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.82%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 35        | 22.44%  |
| Samsung Electronics | 35        | 22.44%  |
| Kingston            | 19        | 12.18%  |
| Micron Technology   | 14        | 8.97%   |
| Unknown             | 12        | 7.69%   |
| Crucial             | 10        | 6.41%   |
| Corsair             | 9         | 5.77%   |
| G.Skill             | 5         | 3.21%   |
| Ramaxel Technology  | 3         | 1.92%   |
| Patriot             | 3         | 1.92%   |
| Nanya Technology    | 3         | 1.92%   |
| Transcend           | 1         | 0.64%   |
| Smart               | 1         | 0.64%   |
| S                   | 1         | 0.64%   |
| PNY                 | 1         | 0.64%   |
| M                   | 1         | 0.64%   |
| HBS                 | 1         | 0.64%   |
| Aeneon              | 1         | 0.64%   |
| 0194808980CE        | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 3         | 1.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.71%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s        | 3         | 1.71%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2         | 1.14%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 2         | 1.14%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 1.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 1.14%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 2         | 1.14%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2         | 1.14%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s          | 2         | 1.14%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2         | 1.14%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s    | 2         | 1.14%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 0.57%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1         | 0.57%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1         | 0.57%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s            | 1         | 0.57%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s               | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1         | 0.57%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1         | 0.57%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s          | 1         | 0.57%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1         | 0.57%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1         | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 1         | 0.57%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s             | 1         | 0.57%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1067MT/s             | 1         | 0.57%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1         | 0.57%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1067MT/s             | 1         | 0.57%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1         | 0.57%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s       | 1         | 0.57%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1         | 0.57%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1         | 0.57%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 62        | 46.97%  |
| DDR4    | 45        | 34.09%  |
| DDR2    | 9         | 6.82%   |
| SDRAM   | 4         | 3.03%   |
| Unknown | 4         | 3.03%   |
| LPDDR4  | 3         | 2.27%   |
| DDR     | 3         | 2.27%   |
| LPDDR3  | 2         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 48.09%  |
| DIMM         | 56        | 42.75%  |
| Row Of Chips | 9         | 6.87%   |
| FB-DIMM      | 1         | 0.76%   |
| Chip         | 1         | 0.76%   |
| Unknown      | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 49        | 33.11%  |
| 8192  | 44        | 29.73%  |
| 2048  | 22        | 14.86%  |
| 16384 | 16        | 10.81%  |
| 1024  | 9         | 6.08%   |
| 32768 | 5         | 3.38%   |
| 512   | 2         | 1.35%   |
| 256   | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 44        | 31.21%  |
| 3200    | 15        | 10.64%  |
| 2667    | 12        | 8.51%   |
| 1333    | 10        | 7.09%   |
| 2133    | 8         | 5.67%   |
| 1334    | 7         | 4.96%   |
| 667     | 6         | 4.26%   |
| 2400    | 5         | 3.55%   |
| 4267    | 3         | 2.13%   |
| 1866    | 3         | 2.13%   |
| 1066    | 3         | 2.13%   |
| 800     | 3         | 2.13%   |
| Unknown | 3         | 2.13%   |
| 4199    | 2         | 1.42%   |
| 3600    | 2         | 1.42%   |
| 1867    | 2         | 1.42%   |
| 1800    | 2         | 1.42%   |
| 533     | 2         | 1.42%   |
| 3500    | 1         | 0.71%   |
| 3466    | 1         | 0.71%   |
| 3266    | 1         | 0.71%   |
| 2933    | 1         | 0.71%   |
| 2800    | 1         | 0.71%   |
| 2666    | 1         | 0.71%   |
| 2472    | 1         | 0.71%   |
| 1639    | 1         | 0.71%   |
| 1067    | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 75%     |
| Canon           | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP OfficeJet Pro 6960 | 1         | 25%     |
| HP OfficeJet 6950     | 1         | 25%     |
| HP LaserJet 1022      | 1         | 25%     |
| Canon LiDE 400        | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Canon CanoScan FB630U | 1         | 50%     |
| Canon CanoScan 4200F  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 19.72%  |
| IMC Networks                           | 7         | 9.86%   |
| Microdia                               | 6         | 8.45%   |
| Sunplus Innovation Technology          | 5         | 7.04%   |
| Realtek Semiconductor                  | 5         | 7.04%   |
| Logitech                               | 5         | 7.04%   |
| Syntek                                 | 4         | 5.63%   |
| Suyin                                  | 3         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.23%   |
| Samsung Electronics                    | 2         | 2.82%   |
| Quanta                                 | 2         | 2.82%   |
| Philips (or NXP)                       | 2         | 2.82%   |
| Microsoft                              | 2         | 2.82%   |
| Acer                                   | 2         | 2.82%   |
| Xiongmai                               | 1         | 1.41%   |
| ViewSonic                              | 1         | 1.41%   |
| ViewQuest Technologies                 | 1         | 1.41%   |
| Sweex                                  | 1         | 1.41%   |
| Silicon Motion                         | 1         | 1.41%   |
| Ricoh                                  | 1         | 1.41%   |
| Intel                                  | 1         | 1.41%   |
| Importek                               | 1         | 1.41%   |
| Apple                                  | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Syntek Integrated Camera                   | 4         | 5.56%   |
| Chicony Integrated Camera                  | 4         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 4.17%   |
| IMC Networks Integrated Camera             | 3         | 4.17%   |
| Sunplus Integrated_Webcam_HD               | 2         | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)    | 2         | 2.78%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]       | 2         | 2.78%   |
| Xiongmai web camera                        | 1         | 1.39%   |
| ViewSonic PC Camera                        | 1         | 1.39%   |
| ViewQuest Ability GABB Webcam              | 1         | 1.39%   |
| Sweex WC060 Series HD Webcam               | 1         | 1.39%   |
| Suyin HP Webcam                            | 1         | 1.39%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.39%   |
| Suyin Asus Integrated Webcam               | 1         | 1.39%   |
| Sunplus HD WebCam                          | 1         | 1.39%   |
| Sunplus HD 720P webcam                     | 1         | 1.39%   |
| Sunplus Dell HD Webcam                     | 1         | 1.39%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.39%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.39%   |
| Realtek VGA WebCam                         | 1         | 1.39%   |
| Realtek MTD camera                         | 1         | 1.39%   |
| Realtek Lenovo EasyCamera                  | 1         | 1.39%   |
| Realtek Integrated_Webcam_HD               | 1         | 1.39%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.39%   |
| Quanta ov9734_techfront_camera             | 1         | 1.39%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.39%   |
| Philips (or NXP) Webcam SPC530NC           | 1         | 1.39%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.39%   |
| Microsoft LifeCam VX-5000                  | 1         | 1.39%   |
| Microsoft LifeCam Cinema                   | 1         | 1.39%   |
| Microdia USB 2.0 Camera                    | 1         | 1.39%   |
| Microdia MSI Starcam Racer                 | 1         | 1.39%   |
| Microdia Integrated_Webcam_FHD             | 1         | 1.39%   |
| Microdia Integrated Webcam HD              | 1         | 1.39%   |
| Logitech Webcam C270                       | 1         | 1.39%   |
| Logitech QuickCam Communicate MP/S5500     | 1         | 1.39%   |
| Logitech Portable Webcam C905              | 1         | 1.39%   |
| Logitech HD Webcam C910                    | 1         | 1.39%   |
| Logitech HD Pro Webcam C920                | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 33.33%  |
| Synaptics                  | 1         | 11.11%  |
| LighTuning Technology      | 1         | 11.11%  |
| AuthenTec                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device              | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner             | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader               | 1         | 11.11%  |
| LighTuning EgisTec_ES603                         | 1         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor             | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Upek        | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 72.87%  |
| 1     | 32        | 24.81%  |
| 2     | 2         | 1.55%   |
| 3     | 1         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 25.71%  |
| Fingerprint reader       | 9         | 25.71%  |
| Chipcard                 | 6         | 17.14%  |
| Net/wireless             | 5         | 14.29%  |
| Sound                    | 2         | 5.71%   |
| Multimedia controller    | 2         | 5.71%   |
| Communication controller | 1         | 2.86%   |
| Camera                   | 1         | 2.86%   |


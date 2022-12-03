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

Total: 158

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| System76      | Thelio thelio-r1            | Desktop     | [a888eb38b3](https://linux-hardware.org/?probe=a888eb38b3) | Dec 01, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [78defd6c12](https://linux-hardware.org/?probe=78defd6c12) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [b76898d624](https://linux-hardware.org/?probe=b76898d624) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [5147db88ea](https://linux-hardware.org/?probe=5147db88ea) | Nov 14, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
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
| Ubuntu Studio 20.04 | 79        | 59.85%  |
| Ubuntu Studio 22.04 | 21        | 15.91%  |
| Ubuntu Studio 20.10 | 13        | 9.85%   |
| Ubuntu Studio 21.10 | 7         | 5.3%    |
| Ubuntu Studio 21.04 | 5         | 3.79%   |
| Ubuntu Studio 18.04 | 3         | 2.27%   |
| Ubuntu Studio 19.10 | 2         | 1.52%   |
| Ubuntu Studio 22.10 | 1         | 0.76%   |
| Ubuntu Studio 16.04 | 1         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 132       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-46-lowlatency    | 5         | 3.73%   |
| 5.13.0-28-lowlatency    | 5         | 3.73%   |
| 5.4.0-52-lowlatency     | 4         | 2.99%   |
| 5.4.0-42-lowlatency     | 4         | 2.99%   |
| 5.8.0-55-lowlatency     | 3         | 2.24%   |
| 5.8.0-50-lowlatency     | 3         | 2.24%   |
| 5.8.0-44-lowlatency     | 3         | 2.24%   |
| 5.8.0-25-lowlatency     | 3         | 2.24%   |
| 5.4.0-65-lowlatency     | 3         | 2.24%   |
| 5.4.0-26-lowlatency     | 3         | 2.24%   |
| 5.15.0-52-lowlatency    | 3         | 2.24%   |
| 5.15.0-47-lowlatency    | 3         | 2.24%   |
| 5.11.0-44-lowlatency    | 3         | 2.24%   |
| 5.11.0-34-lowlatency    | 3         | 2.24%   |
| 5.8.0-48-lowlatency     | 2         | 1.49%   |
| 5.8.0-29-lowlatency     | 2         | 1.49%   |
| 5.4.0-94-lowlatency     | 2         | 1.49%   |
| 5.4.0-58-lowlatency     | 2         | 1.49%   |
| 5.4.0-56-lowlatency     | 2         | 1.49%   |
| 5.4.0-45-lowlatency     | 2         | 1.49%   |
| 5.15.0-50-lowlatency    | 2         | 1.49%   |
| 5.15.0-48-lowlatency    | 2         | 1.49%   |
| 5.15.0-40-lowlatency    | 2         | 1.49%   |
| 5.15.0-30-lowlatency    | 2         | 1.49%   |
| 5.13.0-30-lowlatency    | 2         | 1.49%   |
| 5.11.0-27-lowlatency    | 2         | 1.49%   |
| 5.8.0-59-lowlatency     | 1         | 0.75%   |
| 5.8.0-45-lowlatency     | 1         | 0.75%   |
| 5.8.0-43-lowlatency     | 1         | 0.75%   |
| 5.8.0-36-lowlatency     | 1         | 0.75%   |
| 5.8.0-34-lowlatency     | 1         | 0.75%   |
| 5.8.0-34-generic        | 1         | 0.75%   |
| 5.8.0-33-lowlatency     | 1         | 0.75%   |
| 5.7.6-050706-lowlatency | 1         | 0.75%   |
| 5.7.6-050706-generic    | 1         | 0.75%   |
| 5.4.0-99-lowlatency     | 1         | 0.75%   |
| 5.4.0-96-lowlatency     | 1         | 0.75%   |
| 5.4.0-88-lowlatency     | 1         | 0.75%   |
| 5.4.0-72-lowlatency     | 1         | 0.75%   |
| 5.4.0-71-lowlatency     | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 38.64%  |
| 5.8.0   | 23        | 17.42%  |
| 5.15.0  | 23        | 17.42%  |
| 5.11.0  | 15        | 11.36%  |
| 5.13.0  | 10        | 7.58%   |
| 4.15.0  | 3         | 2.27%   |
| 5.3.0   | 2         | 1.52%   |
| 5.7.6   | 1         | 0.76%   |
| 5.19.0  | 1         | 0.76%   |
| 5.17.1  | 1         | 0.76%   |
| 5.15.6  | 1         | 0.76%   |
| 4.4.0   | 1         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 38.64%  |
| 5.15    | 24        | 18.18%  |
| 5.8     | 23        | 17.42%  |
| 5.11    | 15        | 11.36%  |
| 5.13    | 10        | 7.58%   |
| 4.15    | 3         | 2.27%   |
| 5.3     | 2         | 1.52%   |
| 5.7     | 1         | 0.76%   |
| 5.19    | 1         | 0.76%   |
| 5.17    | 1         | 0.76%   |
| 4.4     | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 130       | 98.48%  |
| i686    | 1         | 0.76%   |
| aarch64 | 1         | 0.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 74        | 56.06%  |
| KDE5            | 41        | 31.06%  |
| GNOME           | 10        | 7.58%   |
| MATE            | 2         | 1.52%   |
| LXQt            | 2         | 1.52%   |
| KDE             | 1         | 0.76%   |
| GNOME Flashback | 1         | 0.76%   |
| Cinnamon        | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 125       | 94.7%   |
| Wayland | 5         | 3.79%   |
| Tty     | 2         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 49        | 37.12%  |
| SDDM    | 37        | 28.03%  |
| LightDM | 34        | 25.76%  |
| GDM     | 11        | 8.33%   |
| LXDM    | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 55        | 41.67%  |
| fr_FR      | 18        | 13.64%  |
| de_DE      | 9         | 6.82%   |
| pt_BR      | 6         | 4.55%   |
| it_IT      | 6         | 4.55%   |
| C          | 6         | 4.55%   |
| en_GB      | 4         | 3.03%   |
| en_CA      | 4         | 3.03%   |
| en_AU      | 2         | 1.52%   |
| en_AG      | 2         | 1.52%   |
| Unknown    | 2         | 1.52%   |
| sk_SK      | 1         | 0.76%   |
| ru_RU      | 1         | 0.76%   |
| nl_NL      | 1         | 0.76%   |
| nl_BE      | 1         | 0.76%   |
| nb_NO      | 1         | 0.76%   |
| hu_HU      | 1         | 0.76%   |
| fr_FR.UTF8 | 1         | 0.76%   |
| fr_CH      | 1         | 0.76%   |
| es_NI      | 1         | 0.76%   |
| es_GT      | 1         | 0.76%   |
| es_ES      | 1         | 0.76%   |
| es_CR      | 1         | 0.76%   |
| es_AR      | 1         | 0.76%   |
| en_NG      | 1         | 0.76%   |
| en_IE      | 1         | 0.76%   |
| en_DE      | 1         | 0.76%   |
| ca_ES      | 1         | 0.76%   |
| ca_AD      | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 74        | 56.06%  |
| BIOS | 58        | 43.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 95.45%  |
| Overlay | 4         | 3.03%   |
| Xfs     | 1         | 0.76%   |
| Ext2    | 1         | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 81        | 61.36%  |
| MBR  | 51        | 38.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 78.79%  |
| Yes       | 28        | 21.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 53.79%  |
| Yes       | 61        | 46.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 26        | 19.7%   |
| Dell                    | 22        | 16.67%  |
| Lenovo                  | 18        | 13.64%  |
| Hewlett-Packard         | 17        | 12.88%  |
| Gigabyte Technology     | 9         | 6.82%   |
| Acer                    | 5         | 3.79%   |
| Apple                   | 4         | 3.03%   |
| Fujitsu                 | 3         | 2.27%   |
| Toshiba                 | 2         | 1.52%   |
| MSI                     | 2         | 1.52%   |
| Intel                   | 2         | 1.52%   |
| HUAWEI                  | 2         | 1.52%   |
| AZW                     | 2         | 1.52%   |
| ASRock                  | 2         | 1.52%   |
| System76                | 1         | 0.76%   |
| Sony                    | 1         | 0.76%   |
| Samsung Electronics     | 1         | 0.76%   |
| Razer                   | 1         | 0.76%   |
| Raspberry Pi Foundation | 1         | 0.76%   |
| Pegatron                | 1         | 0.76%   |
| Packard Bell            | 1         | 0.76%   |
| Medion                  | 1         | 0.76%   |
| Intel Client Systems    | 1         | 0.76%   |
| IBM                     | 1         | 0.76%   |
| Google                  | 1         | 0.76%   |
| Getac                   | 1         | 0.76%   |
| Foxconn                 | 1         | 0.76%   |
| Clevo                   | 1         | 0.76%   |
| Avell High Performance  | 1         | 0.76%   |
| Acidanthera             | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 3.03%   |
| Lenovo G50-45 80E3                         | 2         | 1.52%   |
| HP Pavilion dv6                            | 2         | 1.52%   |
| Dell OptiPlex 790                          | 2         | 1.52%   |
| ASUS PRIME X570-PRO                        | 2         | 1.52%   |
| Toshiba Satellite L755D                    | 1         | 0.76%   |
| Toshiba Satellite C855                     | 1         | 0.76%   |
| System76 Thelio                            | 1         | 0.76%   |
| Sony VGN-NS31M_W                           | 1         | 0.76%   |
| Samsung 305V4A/305V5A                      | 1         | 0.76%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.76%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.76%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.76%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.76%   |
| MSI MS-7A57                                | 1         | 0.76%   |
| MSI MS-7752                                | 1         | 0.76%   |
| Medion MD34207/C746                        | 1         | 0.76%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.76%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.76%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.76%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.76%   |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.76%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1         | 0.76%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.76%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4       | 1         | 0.76%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 1         | 0.76%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 1         | 0.76%   |
| Lenovo IdeaPad 3 15ABA7 82RN               | 1         | 0.76%   |
| Lenovo IdeaPad 3 14ARE05 81W3              | 1         | 0.76%   |
| Lenovo IdeaCentre AIO 520-27ICB F0DE00EJRI | 1         | 0.76%   |
| Lenovo G70-80 80FF                         | 1         | 0.76%   |
| Intel NUC8i5BEH                            | 1         | 0.76%   |
| Intel DQ965GF HD/FP Audio                  | 1         | 0.76%   |
| Intel Client Systems LAPBC510              | 1         | 0.76%   |
| IBM 8188PPV                                | 1         | 0.76%   |
| HUAWEI KLVL-WXXW                           | 1         | 0.76%   |
| HUAWEI HLYL-WXX9                           | 1         | 0.76%   |
| HP ZBook 15 G3                             | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Dell OptiPlex                 | 8         | 6.06%   |
| Dell Inspiron                 | 8         | 6.06%   |
| Lenovo ThinkPad               | 7         | 5.3%    |
| HP Compaq                     | 6         | 4.55%   |
| Lenovo IdeaPad                | 5         | 3.79%   |
| ASUS ROG                      | 4         | 3.03%   |
| ASUS All                      | 4         | 3.03%   |
| Acer Aspire                   | 4         | 3.03%   |
| Fujitsu ESPRIMO               | 3         | 2.27%   |
| Dell Latitude                 | 3         | 2.27%   |
| Toshiba Satellite             | 2         | 1.52%   |
| Lenovo G50-45                 | 2         | 1.52%   |
| HP Pavilion                   | 2         | 1.52%   |
| Dell Precision                | 2         | 1.52%   |
| ASUS TUF                      | 2         | 1.52%   |
| ASUS PRIME                    | 2         | 1.52%   |
| ASUS P8P67                    | 2         | 1.52%   |
| System76 Thelio               | 1         | 0.76%   |
| Sony VGN-NS31M                | 1         | 0.76%   |
| Samsung 305V4A                | 1         | 0.76%   |
| Razer Blade                   | 1         | 0.76%   |
| RPi Raspberry                 | 1         | 0.76%   |
| Pegatron FL368AA-UUZ          | 1         | 0.76%   |
| Packard Bell IMEDIA           | 1         | 0.76%   |
| MSI MS-7A57                   | 1         | 0.76%   |
| MSI MS-7752                   | 1         | 0.76%   |
| Medion MD34207                | 1         | 0.76%   |
| Lenovo ThinkCentre            | 1         | 0.76%   |
| Lenovo Legion                 | 1         | 0.76%   |
| Lenovo IdeaCentre             | 1         | 0.76%   |
| Lenovo G70-80                 | 1         | 0.76%   |
| Intel NUC8i5BEH               | 1         | 0.76%   |
| Intel DQ965GF                 | 1         | 0.76%   |
| Intel Client Systems LAPBC510 | 1         | 0.76%   |
| IBM 8188PPV                   | 1         | 0.76%   |
| HUAWEI KLVL-WXXW              | 1         | 0.76%   |
| HUAWEI HLYL-WXX9              | 1         | 0.76%   |
| HP ZBook                      | 1         | 0.76%   |
| HP Z620                       | 1         | 0.76%   |
| HP Stream                     | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 14        | 10.61%  |
| 2014 | 13        | 9.85%   |
| 2012 | 13        | 9.85%   |
| 2019 | 12        | 9.09%   |
| 2018 | 10        | 7.58%   |
| 2011 | 10        | 7.58%   |
| 2013 | 9         | 6.82%   |
| 2021 | 8         | 6.06%   |
| 2017 | 8         | 6.06%   |
| 2010 | 7         | 5.3%    |
| 2016 | 6         | 4.55%   |
| 2008 | 6         | 4.55%   |
| 2015 | 5         | 3.79%   |
| 2007 | 4         | 3.03%   |
| 2009 | 3         | 2.27%   |
| 2005 | 3         | 2.27%   |
| 2022 | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 63        | 47.73%  |
| Notebook       | 59        | 44.7%   |
| All in one     | 5         | 3.79%   |
| Mini pc        | 3         | 2.27%   |
| System on chip | 1         | 0.76%   |
| Convertible    | 1         | 0.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 124       | 93.94%  |
| Enabled  | 8         | 6.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 130       | 98.48%  |
| Yes  | 2         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 38        | 28.79%  |
| 16.01-24.0  | 32        | 24.24%  |
| 8.01-16.0   | 22        | 16.67%  |
| 3.01-4.0    | 13        | 9.85%   |
| 32.01-64.0  | 11        | 8.33%   |
| 64.01-256.0 | 6         | 4.55%   |
| 1.01-2.0    | 4         | 3.03%   |
| 24.01-32.0  | 3         | 2.27%   |
| 2.01-3.0    | 3         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 49        | 36.57%  |
| 2.01-3.0   | 30        | 22.39%  |
| 4.01-8.0   | 22        | 16.42%  |
| 3.01-4.0   | 17        | 12.69%  |
| 8.01-16.0  | 11        | 8.21%   |
| 0.51-1.0   | 4         | 2.99%   |
| 24.01-32.0 | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 53.03%  |
| 2      | 44        | 33.33%  |
| 3      | 6         | 4.55%   |
| 4      | 3         | 2.27%   |
| 7      | 2         | 1.52%   |
| 5      | 2         | 1.52%   |
| 0      | 2         | 1.52%   |
| 16     | 1         | 0.76%   |
| 11     | 1         | 0.76%   |
| 10     | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 53.03%  |
| Yes       | 62        | 46.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 89.39%  |
| No        | 14        | 10.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 72.73%  |
| No        | 36        | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 55.3%   |
| No        | 59        | 44.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 30        | 22.73%  |
| France                 | 20        | 15.15%  |
| Germany                | 15        | 11.36%  |
| Italy                  | 9         | 6.82%   |
| Brazil                 | 7         | 5.3%    |
| Canada                 | 5         | 3.79%   |
| UK                     | 4         | 3.03%   |
| Spain                  | 3         | 2.27%   |
| Russia                 | 3         | 2.27%   |
| Austria                | 3         | 2.27%   |
| Australia              | 3         | 2.27%   |
| Taiwan                 | 2         | 1.52%   |
| Romania                | 2         | 1.52%   |
| Norway                 | 2         | 1.52%   |
| Mexico                 | 2         | 1.52%   |
| Costa Rica             | 2         | 1.52%   |
| Belgium                | 2         | 1.52%   |
| Yemen                  | 1         | 0.76%   |
| Turkey                 | 1         | 0.76%   |
| Switzerland            | 1         | 0.76%   |
| Sweden                 | 1         | 0.76%   |
| Slovakia               | 1         | 0.76%   |
| Poland                 | 1         | 0.76%   |
| Nigeria                | 1         | 0.76%   |
| Nicaragua              | 1         | 0.76%   |
| Netherlands            | 1         | 0.76%   |
| Kenya                  | 1         | 0.76%   |
| Ivory Coast            | 1         | 0.76%   |
| Indonesia              | 1         | 0.76%   |
| Hungary                | 1         | 0.76%   |
| Guatemala              | 1         | 0.76%   |
| Finland                | 1         | 0.76%   |
| Bulgaria               | 1         | 0.76%   |
| Bosnia and Herzegovina | 1         | 0.76%   |
| Argentina              | 1         | 0.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Paris                   | 3         | 2.26%   |
| Turin                   | 2         | 1.5%    |
| Stuttgart               | 2         | 1.5%    |
| Montreal                | 2         | 1.5%    |
| Mississauga             | 2         | 1.5%    |
| Houston                 | 2         | 1.5%    |
| Denver                  | 2         | 1.5%    |
| Bucharest               | 2         | 1.5%    |
| Béziers                | 2         | 1.5%    |
| Zanesville              | 1         | 0.75%   |
| Yekaterinburg           | 1         | 0.75%   |
| Wroclaw                 | 1         | 0.75%   |
| Woonsocket              | 1         | 0.75%   |
| Woodland Park           | 1         | 0.75%   |
| Villefontaine           | 1         | 0.75%   |
| Vienna                  | 1         | 0.75%   |
| Velleron                | 1         | 0.75%   |
| Tilburg                 | 1         | 0.75%   |
| Taylor                  | 1         | 0.75%   |
| Taipei                  | 1         | 0.75%   |
| Taichung                | 1         | 0.75%   |
| Sunderland              | 1         | 0.75%   |
| Stockholm               | 1         | 0.75%   |
| Stabekk                 | 1         | 0.75%   |
| Sofia                   | 1         | 0.75%   |
| Sleman                  | 1         | 0.75%   |
| Sherman Oaks            | 1         | 0.75%   |
| Seropedica              | 1         | 0.75%   |
| Sarajevo                | 1         | 0.75%   |
| Sao Paulo               | 1         | 0.75%   |
| Santa Barbara d'Oeste   | 1         | 0.75%   |
| Sanaa                   | 1         | 0.75%   |
| San Secondo di Pinerolo | 1         | 0.75%   |
| San Juan                | 1         | 0.75%   |
| Samara                  | 1         | 0.75%   |
| Saint-Ouen-l'Aumone     | 1         | 0.75%   |
| Rio Grande da Serra     | 1         | 0.75%   |
| Rio de Janeiro          | 1         | 0.75%   |
| Rennes                  | 1         | 0.75%   |
| Ragusa                  | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 45     | 17.56%  |
| WDC                 | 32        | 39     | 15.61%  |
| Seagate             | 26        | 46     | 12.68%  |
| SanDisk             | 15        | 16     | 7.32%   |
| Toshiba             | 13        | 14     | 6.34%   |
| Kingston            | 8         | 8      | 3.9%    |
| Intel               | 8         | 11     | 3.9%    |
| Unknown             | 7         | 7      | 3.41%   |
| Crucial             | 7         | 7      | 3.41%   |
| Hitachi             | 5         | 5      | 2.44%   |
| HGST                | 5         | 6      | 2.44%   |
| SK hynix            | 3         | 4      | 1.46%   |
| Micron Technology   | 3         | 3      | 1.46%   |
| ASMT                | 3         | 3      | 1.46%   |
| Phison              | 2         | 2      | 0.98%   |
| JMicron Technology  | 2         | 2      | 0.98%   |
| Intenso             | 2         | 2      | 0.98%   |
| Fujitsu             | 2         | 2      | 0.98%   |
| Corsair             | 2         | 3      | 0.98%   |
| China               | 2         | 2      | 0.98%   |
| BHT                 | 2         | 2      | 0.98%   |
| A-DATA Technology   | 2         | 2      | 0.98%   |
| USB 3.0             | 1         | 2      | 0.49%   |
| Union Memory        | 1         | 1      | 0.49%   |
| UMIS                | 1         | 1      | 0.49%   |
| TO Exter            | 1         | 1      | 0.49%   |
| Team                | 1         | 1      | 0.49%   |
| SPCC                | 1         | 1      | 0.49%   |
| Phison Electronics  | 1         | 1      | 0.49%   |
| Patriot             | 1         | 1      | 0.49%   |
| OCZ                 | 1         | 1      | 0.49%   |
| NGFF                | 1         | 1      | 0.49%   |
| Maxtor              | 1         | 1      | 0.49%   |
| Leven               | 1         | 1      | 0.49%   |
| KIOXIA              | 1         | 1      | 0.49%   |
| KingSpec            | 1         | 1      | 0.49%   |
| Integral            | 1         | 1      | 0.49%   |
| Inateck             | 1         | 1      | 0.49%   |
| EAGET               | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.74%   |
| Toshiba MQ01ABD100 1TB                    | 3         | 1.3%    |
| Seagate ST2000DM001-1ER164 2TB            | 3         | 1.3%    |
| Samsung SSD 870 EVO 1TB                   | 3         | 1.3%    |
| Samsung SSD 860 EVO 500GB                 | 3         | 1.3%    |
| Kingston SA400S37240G 240GB SSD           | 3         | 1.3%    |
| Crucial CT500MX500SSD1 500GB              | 3         | 1.3%    |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.87%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.87%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.87%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.87%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB            | 2         | 0.87%   |
| Seagate Expansion 1TB                     | 2         | 0.87%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.87%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.87%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.87%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.87%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.87%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.87%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.87%   |
| JMicron Generic 1TB                       | 2         | 0.87%   |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.43%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 1         | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.43%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.43%   |
| WDC WD5000BPKT-60PK4T0 500GB              | 1         | 0.43%   |
| WDC WD5000AAKS-75V0A0 500GB               | 1         | 0.43%   |
| WDC WD40EZRZ-00GXCB0 4TB                  | 1         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB                  | 1         | 0.43%   |
| WDC WD40EFAX-68JH4N1 4TB                  | 1         | 0.43%   |
| WDC WD40EFAX-68JH4N0 4TB                  | 1         | 0.43%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.43%   |
| WDC WD3200BPVT-75JJ5T0 320GB              | 1         | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.43%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.43%   |
| WDC WD3200AAKS-00VYA0 320GB               | 1         | 0.43%   |
| WDC WD30EZRZ-00Z5HB0 3TB                  | 1         | 0.43%   |
| WDC WD30EZRX-00SPEB0 3TB                  | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 30.59%  |
| Seagate             | 25        | 44     | 29.41%  |
| Toshiba             | 12        | 13     | 14.12%  |
| Hitachi             | 5         | 5      | 5.88%   |
| HGST                | 5         | 6      | 5.88%   |
| Samsung Electronics | 4         | 4      | 4.71%   |
| Fujitsu             | 2         | 2      | 2.35%   |
| ASMT                | 2         | 2      | 2.35%   |
| USB 3.0             | 1         | 2      | 1.18%   |
| Unknown             | 1         | 1      | 1.18%   |
| Maxtor              | 1         | 1      | 1.18%   |
| Inateck             | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 26     | 30.67%  |
| SanDisk             | 13        | 14     | 17.33%  |
| Kingston            | 7         | 7      | 9.33%   |
| Crucial             | 7         | 7      | 9.33%   |
| Micron Technology   | 2         | 2      | 2.67%   |
| JMicron Technology  | 2         | 2      | 2.67%   |
| Intenso             | 2         | 2      | 2.67%   |
| China               | 2         | 2      | 2.67%   |
| BHT                 | 2         | 2      | 2.67%   |
| A-DATA Technology   | 2         | 2      | 2.67%   |
| WDC                 | 1         | 1      | 1.33%   |
| Toshiba             | 1         | 1      | 1.33%   |
| TO Exter            | 1         | 1      | 1.33%   |
| SPCC                | 1         | 1      | 1.33%   |
| Patriot             | 1         | 1      | 1.33%   |
| OCZ                 | 1         | 1      | 1.33%   |
| NGFF                | 1         | 1      | 1.33%   |
| Leven               | 1         | 1      | 1.33%   |
| KingSpec            | 1         | 1      | 1.33%   |
| Intel               | 1         | 1      | 1.33%   |
| Integral            | 1         | 1      | 1.33%   |
| Corsair             | 1         | 1      | 1.33%   |
| ASMT                | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 68        | 114    | 39.08%  |
| SSD     | 62        | 79     | 35.63%  |
| NVMe    | 35        | 47     | 20.11%  |
| MMC     | 7         | 8      | 4.02%   |
| Unknown | 2         | 2      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 176    | 64.74%  |
| NVMe | 35        | 47     | 22.44%  |
| SAS  | 13        | 19     | 8.33%   |
| MMC  | 7         | 8      | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 97     | 54.61%  |
| 0.51-1.0   | 40        | 50     | 28.37%  |
| 1.01-2.0   | 9         | 11     | 6.38%   |
| 4.01-10.0  | 7         | 24     | 4.96%   |
| 3.01-4.0   | 6         | 8      | 4.26%   |
| 2.01-3.0   | 2         | 3      | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 30.08%  |
| 251-500        | 22        | 16.54%  |
| 501-1000       | 20        | 15.04%  |
| 1001-2000      | 16        | 12.03%  |
| More than 3000 | 11        | 8.27%   |
| 51-100         | 10        | 7.52%   |
| 21-50          | 8         | 6.02%   |
| 1-20           | 5         | 3.76%   |
| 2001-3000      | 1         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 33.58%  |
| 21-50          | 25        | 18.66%  |
| 101-250        | 18        | 13.43%  |
| 251-500        | 12        | 8.96%   |
| 51-100         | 12        | 8.96%   |
| 501-1000       | 8         | 5.97%   |
| More than 3000 | 6         | 4.48%   |
| 1001-2000      | 5         | 3.73%   |
| 2001-3000      | 3         | 2.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 9.68%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 3.23%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 3.23%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 3.23%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 3.23%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 3.23%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 3.23%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 3.23%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 3.23%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 3.23%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 3.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.23%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 3.23%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 3.23%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 3.23%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.23%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 3.23%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 3.23%   |
| Samsung Electronics HD753LJ 752GB                   | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.23%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 3.23%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 3.23%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.23%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 3.23%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 3.23%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 3.23%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 32.26%  |
| WDC                 | 6         | 6      | 19.35%  |
| Samsung Electronics | 5         | 5      | 16.13%  |
| Toshiba             | 2         | 2      | 6.45%   |
| Hitachi             | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 41.67%  |
| WDC                 | 6         | 6      | 25%     |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 2      | 8.33%   |
| Hitachi             | 2         | 2      | 8.33%   |
| HGST                | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 29     | 76.67%  |
| SSD  | 6         | 6      | 20%     |
| NVMe | 1         | 1      | 3.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 50%     |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 106       | 186    | 67.95%  |
| Malfunc  | 30        | 36     | 19.23%  |
| Detected | 18        | 26     | 11.54%  |
| Failed   | 2         | 2      | 1.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 93        | 53.76%  |
| AMD                         | 28        | 16.18%  |
| Samsung Electronics         | 12        | 6.94%   |
| SanDisk                     | 6         | 3.47%   |
| Phison Electronics          | 5         | 2.89%   |
| Marvell Technology Group    | 5         | 2.89%   |
| ASMedia Technology          | 5         | 2.89%   |
| SK hynix                    | 3         | 1.73%   |
| Nvidia                      | 3         | 1.73%   |
| Union Memory (Shenzhen)     | 2         | 1.16%   |
| JMicron Technology          | 2         | 1.16%   |
| VIA Technologies            | 1         | 0.58%   |
| Silicon Image               | 1         | 0.58%   |
| Seagate Technology          | 1         | 0.58%   |
| Micron Technology           | 1         | 0.58%   |
| LSI Logic / Symbios Logic   | 1         | 0.58%   |
| KIOXIA                      | 1         | 0.58%   |
| Kingston Technology Company | 1         | 0.58%   |
| Apple                       | 1         | 0.58%   |
| Adaptec                     | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 10.14%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 5.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 2.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.42%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.45%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.45%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.97%   |
| SK hynix BC511                                                                 | 2         | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.97%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.97%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 0.97%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 0.97%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.97%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 0.97%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.97%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2         | 0.97%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 0.97%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 100       | 57.8%   |
| NVMe | 36        | 20.81%  |
| IDE  | 22        | 12.72%  |
| RAID | 11        | 6.36%   |
| SAS  | 3         | 1.73%   |
| SCSI | 1         | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 98        | 74.24%  |
| AMD    | 33        | 25%     |
| ARM    | 1         | 0.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 2.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 2.27%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 2.27%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 2.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.52%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.52%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 1.52%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.52%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.76%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.76%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.76%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.76%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.76%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.76%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.76%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.76%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.76%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.76%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.76%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.76%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.76%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.76%   |
| Intel Core i7-6700T CPU @ 2.80GHz       | 1         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.76%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.76%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.76%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz      | 1         | 0.76%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 0.76%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 0.76%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.76%   |
| Intel Core i7-3940XM CPU @ 3.00GHz      | 1         | 0.76%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 1         | 0.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 34        | 25.76%  |
| Intel Core i7          | 29        | 21.97%  |
| Intel Core i3          | 9         | 6.82%   |
| Other                  | 6         | 4.55%   |
| Intel Celeron          | 5         | 3.79%   |
| AMD Ryzen 7            | 5         | 3.79%   |
| AMD Ryzen 5            | 5         | 3.79%   |
| Intel Core 2 Duo       | 4         | 3.03%   |
| AMD Ryzen 9            | 4         | 3.03%   |
| Intel Xeon             | 3         | 2.27%   |
| Intel Pentium 4        | 2         | 1.52%   |
| Intel Core i9          | 2         | 1.52%   |
| AMD Ryzen 3            | 2         | 1.52%   |
| AMD Phenom II X4       | 2         | 1.52%   |
| AMD E                  | 2         | 1.52%   |
| AMD Athlon II X2       | 2         | 1.52%   |
| AMD A4                 | 2         | 1.52%   |
| Intel Pentium Dual     | 1         | 0.76%   |
| Intel Pentium D        | 1         | 0.76%   |
| Intel Pentium          | 1         | 0.76%   |
| Intel Genuine          | 1         | 0.76%   |
| Intel Core 2           | 1         | 0.76%   |
| AMD Ryzen Threadripper | 1         | 0.76%   |
| AMD FX                 | 1         | 0.76%   |
| AMD E2                 | 1         | 0.76%   |
| AMD E1                 | 1         | 0.76%   |
| AMD Athlon X4          | 1         | 0.76%   |
| AMD Athlon Dual Core   | 1         | 0.76%   |
| AMD Athlon 64 X2       | 1         | 0.76%   |
| AMD A6                 | 1         | 0.76%   |
| AMD A10                | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 55        | 41.67%  |
| 2      | 47        | 35.61%  |
| 6      | 13        | 9.85%   |
| 8      | 7         | 5.3%    |
| 1      | 3         | 2.27%   |
| 16     | 2         | 1.52%   |
| 12     | 2         | 1.52%   |
| 10     | 2         | 1.52%   |
| 32     | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 131       | 99.24%  |
| 2      | 1         | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 81        | 61.36%  |
| 1      | 51        | 38.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 131       | 99.24%  |
| 32-bit         | 1         | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 10.53%  |
| 0x306c3    | 13        | 9.77%   |
| 0x306a9    | 11        | 8.27%   |
| 0x206a7    | 11        | 8.27%   |
| 0x906ea    | 7         | 5.26%   |
| 0x806ea    | 4         | 3.01%   |
| 0x806c1    | 4         | 3.01%   |
| 0x506e3    | 4         | 3.01%   |
| 0x306d4    | 4         | 3.01%   |
| 0x08701021 | 4         | 3.01%   |
| 0x08600104 | 4         | 3.01%   |
| 0x010000c8 | 3         | 2.26%   |
| 0xf41      | 2         | 1.5%    |
| 0x906e9    | 2         | 1.5%    |
| 0x706e5    | 2         | 1.5%    |
| 0x6fd      | 2         | 1.5%    |
| 0x406e3    | 2         | 1.5%    |
| 0x206d7    | 2         | 1.5%    |
| 0x106e5    | 2         | 1.5%    |
| 0x10676    | 2         | 1.5%    |
| 0x08600106 | 2         | 1.5%    |
| 0x07030105 | 2         | 1.5%    |
| 0xf65      | 1         | 0.75%   |
| 0xa0655    | 1         | 0.75%   |
| 0xa0652    | 1         | 0.75%   |
| 0x906ed    | 1         | 0.75%   |
| 0x706a1    | 1         | 0.75%   |
| 0x6fb      | 1         | 0.75%   |
| 0x6f6      | 1         | 0.75%   |
| 0x506ca    | 1         | 0.75%   |
| 0x506c9    | 1         | 0.75%   |
| 0x50654    | 1         | 0.75%   |
| 0x406c4    | 1         | 0.75%   |
| 0x40661    | 1         | 0.75%   |
| 0x40651    | 1         | 0.75%   |
| 0x20655    | 1         | 0.75%   |
| 0x106a5    | 1         | 0.75%   |
| 0x1067a    | 1         | 0.75%   |
| 0x0a50000c | 1         | 0.75%   |
| 0x0a201009 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 12.12%  |
| Haswell       | 15        | 11.36%  |
| Zen 2         | 13        | 9.85%   |
| SandyBridge   | 13        | 9.85%   |
| IvyBridge     | 11        | 8.33%   |
| Skylake       | 10        | 7.58%   |
| Broadwell     | 5         | 3.79%   |
| TigerLake     | 4         | 3.03%   |
| Penryn        | 4         | 3.03%   |
| K10           | 4         | 3.03%   |
| Core          | 4         | 3.03%   |
| Puma          | 3         | 2.27%   |
| NetBurst      | 3         | 2.27%   |
| Nehalem       | 3         | 2.27%   |
| Zen 3         | 2         | 1.52%   |
| Westmere      | 2         | 1.52%   |
| Piledriver    | 2         | 1.52%   |
| K8 Hammer     | 2         | 1.52%   |
| IceLake       | 2         | 1.52%   |
| Goldmont      | 2         | 1.52%   |
| CometLake     | 2         | 1.52%   |
| Unknown       | 2         | 1.52%   |
| Zen+          | 1         | 0.76%   |
| Zen           | 1         | 0.76%   |
| Steamroller   | 1         | 0.76%   |
| Silvermont    | 1         | 0.76%   |
| K10 Llano     | 1         | 0.76%   |
| Goldmont plus | 1         | 0.76%   |
| Excavator     | 1         | 0.76%   |
| Bobcat        | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 69        | 44.81%  |
| Nvidia | 51        | 33.12%  |
| AMD    | 34        | 22.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 7         | 4.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 3.8%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.8%    |
| Intel HD Graphics 530                                                       | 5         | 3.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.53%   |
| Intel HD Graphics 5500                                                      | 4         | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.53%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.9%    |
| Intel UHD Graphics 620                                                      | 3         | 1.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.9%    |
| Nvidia TU117M                                                               | 2         | 1.27%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.27%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 1.27%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.27%   |
| Intel HD Graphics 630                                                       | 2         | 1.27%   |
| Intel HD Graphics 500                                                       | 2         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.27%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.63%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1         | 0.63%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 1         | 0.63%   |
| Nvidia GT216 [GeForce 315]                                                  | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.63%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 37.12%  |
| 1 x Nvidia     | 31        | 23.48%  |
| 1 x AMD        | 27        | 20.45%  |
| Intel + Nvidia | 15        | 11.36%  |
| AMD + Nvidia   | 4         | 3.03%   |
| Intel + AMD    | 2         | 1.52%   |
| Other          | 1         | 0.76%   |
| 2 x Nvidia     | 1         | 0.76%   |
| 2 x Intel      | 1         | 0.76%   |
| 2 x AMD        | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 104       | 78.79%  |
| Proprietary | 26        | 19.7%   |
| Unknown     | 2         | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 44.7%   |
| 1.01-2.0   | 19        | 14.39%  |
| 0.01-0.5   | 16        | 12.12%  |
| 0.51-1.0   | 15        | 11.36%  |
| 3.01-4.0   | 10        | 7.58%   |
| 5.01-6.0   | 4         | 3.03%   |
| 8.01-16.0  | 4         | 3.03%   |
| 7.01-8.0   | 3         | 2.27%   |
| 2.01-3.0   | 1         | 0.76%   |
| 16.01-24.0 | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 13.25%  |
| AU Optronics            | 15        | 9.93%   |
| LG Display              | 13        | 8.61%   |
| Hewlett-Packard         | 10        | 6.62%   |
| Goldstar                | 10        | 6.62%   |
| Dell                    | 9         | 5.96%   |
| BOE                     | 9         | 5.96%   |
| Philips                 | 8         | 5.3%    |
| Acer                    | 8         | 5.3%    |
| Chimei Innolux          | 7         | 4.64%   |
| Ancor Communications    | 7         | 4.64%   |
| Lenovo                  | 3         | 1.99%   |
| Sharp                   | 2         | 1.32%   |
| Iiyama                  | 2         | 1.32%   |
| Hannspree               | 2         | 1.32%   |
| Eizo                    | 2         | 1.32%   |
| BenQ                    | 2         | 1.32%   |
| Apple                   | 2         | 1.32%   |
| AOC                     | 2         | 1.32%   |
| VIE                     | 1         | 0.66%   |
| Unknown                 | 1         | 0.66%   |
| UGD                     | 1         | 0.66%   |
| TVT                     | 1         | 0.66%   |
| Targa Visionary         | 1         | 0.66%   |
| Sony                    | 1         | 0.66%   |
| Seiki                   | 1         | 0.66%   |
| Onkyo                   | 1         | 0.66%   |
| NEC Computers           | 1         | 0.66%   |
| Medion                  | 1         | 0.66%   |
| LG Philips              | 1         | 0.66%   |
| KTC                     | 1         | 0.66%   |
| Fujitsu Siemens         | 1         | 0.66%   |
| DENON                   | 1         | 0.66%   |
| CPT                     | 1         | 0.66%   |
| Chi Mei Optoelectronics | 1         | 0.66%   |
| ASUSTek Computer        | 1         | 0.66%   |
| Arnos Instruments       | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch            | 2         | 1.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 1.26%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                    | 2         | 1.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 1.26%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.26%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1         | 0.63%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1         | 0.63%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch                 | 1         | 0.63%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1         | 0.63%   |
| Targa Visionary LCD Monitor TARA240 1920x1080 520x300mm 23.6-inch       | 1         | 0.63%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                     | 1         | 0.63%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                 | 1         | 0.63%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 0.63%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1         | 0.63%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch       | 1         | 0.63%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch     | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1         | 0.63%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1         | 0.63%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch     | 1         | 0.63%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch     | 1         | 0.63%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1         | 0.63%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.63%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch   | 1         | 0.63%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 1         | 0.63%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch               | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 64        | 45.39%  |
| 1366x768 (WXGA)    | 22        | 15.6%   |
| 3840x2160 (4K)     | 13        | 9.22%   |
| 1280x1024 (SXGA)   | 10        | 7.09%   |
| 1600x900 (HD+)     | 7         | 4.96%   |
| 1680x1050 (WSXGA+) | 6         | 4.26%   |
| 2560x1440 (QHD)    | 4         | 2.84%   |
| 1440x900 (WXGA+)   | 4         | 2.84%   |
| 1920x1200 (WUXGA)  | 2         | 1.42%   |
| 1280x800 (WXGA)    | 2         | 1.42%   |
| 5760x2160          | 1         | 0.71%   |
| 2880x1800          | 1         | 0.71%   |
| 2160x1440          | 1         | 0.71%   |
| 1600x1200          | 1         | 0.71%   |
| 1400x1050          | 1         | 0.71%   |
| 1360x768           | 1         | 0.71%   |
| Unknown            | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 37        | 24.67%  |
| 21      | 16        | 10.67%  |
| 24      | 13        | 8.67%   |
| 23      | 12        | 8%      |
| 27      | 11        | 7.33%   |
| 19      | 8         | 5.33%   |
| 13      | 8         | 5.33%   |
| 17      | 7         | 4.67%   |
| 14      | 6         | 4%      |
| 22      | 5         | 3.33%   |
| 18      | 5         | 3.33%   |
| 20      | 4         | 2.67%   |
| 12      | 4         | 2.67%   |
| 84      | 2         | 1.33%   |
| 31      | 2         | 1.33%   |
| 65      | 1         | 0.67%   |
| 54      | 1         | 0.67%   |
| 52      | 1         | 0.67%   |
| 50      | 1         | 0.67%   |
| 43      | 1         | 0.67%   |
| 32      | 1         | 0.67%   |
| 26      | 1         | 0.67%   |
| 16      | 1         | 0.67%   |
| 11      | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 36.3%   |
| 501-600     | 33        | 22.6%   |
| 401-500     | 32        | 21.92%  |
| 201-300     | 9         | 6.16%   |
| 351-400     | 6         | 4.11%   |
| 601-700     | 4         | 2.74%   |
| 1001-1500   | 4         | 2.74%   |
| 1501-2000   | 2         | 1.37%   |
| 701-800     | 1         | 0.68%   |
| 901-1000    | 1         | 0.68%   |
| Unknown     | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 75.56%  |
| 16/10   | 19        | 14.07%  |
| 5/4     | 9         | 6.67%   |
| 4/3     | 2         | 1.48%   |
| 3/2     | 2         | 1.48%   |
| Unknown | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 25%     |
| 201-250        | 36        | 24.32%  |
| 151-200        | 15        | 10.14%  |
| 301-350        | 12        | 8.11%   |
| 81-90          | 11        | 7.43%   |
| 141-150        | 11        | 7.43%   |
| More than 1000 | 6         | 4.05%   |
| 251-300        | 5         | 3.38%   |
| 61-70          | 4         | 2.7%    |
| 71-80          | 3         | 2.03%   |
| 351-500        | 3         | 2.03%   |
| 51-60          | 1         | 0.68%   |
| 121-130        | 1         | 0.68%   |
| 111-120        | 1         | 0.68%   |
| 501-1000       | 1         | 0.68%   |
| Unknown        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 60        | 42.55%  |
| 101-120       | 38        | 26.95%  |
| 121-160       | 31        | 21.99%  |
| 161-240       | 8         | 5.67%   |
| More than 240 | 2         | 1.42%   |
| 1-50          | 1         | 0.71%   |
| Unknown       | 1         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 99        | 73.88%  |
| 2     | 33        | 24.63%  |
| 3     | 1         | 0.75%   |
| 0     | 1         | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 71        | 34.8%   |
| Intel                             | 71        | 34.8%   |
| Qualcomm Atheros                  | 22        | 10.78%  |
| Broadcom                          | 11        | 5.39%   |
| TP-Link                           | 3         | 1.47%   |
| Nvidia                            | 3         | 1.47%   |
| Broadcom Limited                  | 3         | 1.47%   |
| ASIX Electronics                  | 3         | 1.47%   |
| Ralink                            | 2         | 0.98%   |
| MediaTek                          | 2         | 0.98%   |
| Aquantia                          | 2         | 0.98%   |
| ZyDAS                             | 1         | 0.49%   |
| Wacom                             | 1         | 0.49%   |
| Ralink Technology                 | 1         | 0.49%   |
| Qualcomm Atheros Communications   | 1         | 0.49%   |
| NetGear                           | 1         | 0.49%   |
| Microsoft                         | 1         | 0.49%   |
| Marvell Technology Group          | 1         | 0.49%   |
| InterBiometrics                   | 1         | 0.49%   |
| Huawei Technologies               | 1         | 0.49%   |
| Ericsson Business Mobile Networks | 1         | 0.49%   |
| DisplayLink                       | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 20.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 5.6%    |
| Intel Wireless 7265                                               | 7         | 3.02%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.72%   |
| Intel Wireless-AC 9260                                            | 4         | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.29%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.29%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.29%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.29%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.29%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.86%   |
| Realtek 802.11ac NIC                                              | 2         | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.86%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.86%   |
| Intel Wireless 8260                                               | 2         | 0.86%   |
| Intel Wireless 7260                                               | 2         | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.86%   |
| ZyDAS ZD1211B 802.11g                                             | 1         | 0.43%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1         | 0.43%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.43%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 1         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 47.96%  |
| Realtek Semiconductor           | 16        | 16.33%  |
| Qualcomm Atheros                | 16        | 16.33%  |
| Broadcom                        | 6         | 6.12%   |
| TP-Link                         | 3         | 3.06%   |
| Ralink                          | 2         | 2.04%   |
| ZyDAS                           | 1         | 1.02%   |
| Wacom                           | 1         | 1.02%   |
| Ralink Technology               | 1         | 1.02%   |
| Qualcomm Atheros Communications | 1         | 1.02%   |
| NetGear                         | 1         | 1.02%   |
| Microsoft                       | 1         | 1.02%   |
| MediaTek                        | 1         | 1.02%   |
| Broadcom Limited                | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 7         | 7.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5         | 5.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 4.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 4         | 4.04%   |
| Intel Wireless-AC 9260                                           | 4         | 4.04%   |
| Intel Wi-Fi 6 AX201                                              | 4         | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 4         | 4.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 3         | 3.03%   |
| Intel Wireless 8265 / 8275                                       | 3         | 3.03%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 3.03%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 3.03%   |
| TP-Link 802.11ac WLAN Adapter                                    | 2         | 2.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.02%   |
| Realtek 802.11ac NIC                                             | 2         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 2         | 2.02%   |
| Intel Wireless 8260                                              | 2         | 2.02%   |
| Intel Wireless 7260                                              | 2         | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.02%   |
| ZyDAS ZD1211B 802.11g                                            | 1         | 1.01%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                         | 1         | 1.01%   |
| TP-Link 802.11ac NIC                                             | 1         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.01%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter          | 1         | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1         | 1.01%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller        | 1         | 1.01%   |
| Realtek Realtek Network controller                               | 1         | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 1.01%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.01%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                  | 1         | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                 | 1         | 1.01%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                 | 1         | 1.01%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter       | 1         | 1.01%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]      | 1         | 1.01%   |
| Microsoft Xbox 360 Wireless Adapter                              | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 44.96%  |
| Intel                    | 45        | 34.88%  |
| Qualcomm Atheros         | 7         | 5.43%   |
| Broadcom                 | 6         | 4.65%   |
| Nvidia                   | 3         | 2.33%   |
| ASIX Electronics         | 3         | 2.33%   |
| Broadcom Limited         | 2         | 1.55%   |
| Aquantia                 | 2         | 1.55%   |
| MediaTek                 | 1         | 0.78%   |
| Marvell Technology Group | 1         | 0.78%   |
| DisplayLink              | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 36.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 10%     |
| Intel I211 Gigabit Network Connection                             | 6         | 4.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.85%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.31%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.54%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.77%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.77%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.77%   |
| MediaTek N152DL                                                   | 1         | 0.77%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.77%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.77%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.77%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.77%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.77%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1         | 0.77%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 54.38%  |
| WiFi     | 96        | 44.24%  |
| Modem    | 3         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 50.35%  |
| WiFi     | 70        | 49.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 73        | 55.3%   |
| 1     | 56        | 42.42%  |
| 3     | 2         | 1.52%   |
| 0     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 81.06%  |
| Yes  | 25        | 18.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 48.65%  |
| Qualcomm Atheros Communications | 8         | 10.81%  |
| Realtek Semiconductor           | 6         | 8.11%   |
| Cambridge Silicon Radio         | 6         | 8.11%   |
| Broadcom                        | 4         | 5.41%   |
| ASUSTek Computer                | 3         | 4.05%   |
| Apple                           | 3         | 4.05%   |
| Realtek                         | 2         | 2.7%    |
| Ralink Technology               | 2         | 2.7%    |
| MediaTek                        | 1         | 1.35%   |
| Lite-On Technology              | 1         | 1.35%   |
| Hewlett-Packard                 | 1         | 1.35%   |
| Foxconn International           | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 20.27%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 8.11%   |
| Intel AX201 Bluetooth                               | 6         | 8.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 8.11%   |
| Realtek Bluetooth Radio                             | 4         | 5.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 5.41%   |
| Intel AX200 Bluetooth                               | 3         | 4.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 4.05%   |
| Realtek Bluetooth Radio                             | 2         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 2.7%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.35%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.35%   |
| Ralink CSR BS8510                                   | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.35%   |
| MediaTek Wireless_Device                            | 1         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.35%   |
| Intel AX210 Bluetooth                               | 1         | 1.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.35%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.35%   |
| ASUS BCM20702A0                                     | 1         | 1.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.35%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.35%   |
| Apple Bluetooth Host Controller                     | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 94        | 43.52%  |
| Nvidia                               | 41        | 18.98%  |
| AMD                                  | 37        | 17.13%  |
| Texas Instruments                    | 5         | 2.31%   |
| C-Media Electronics                  | 5         | 2.31%   |
| Yamaha                               | 3         | 1.39%   |
| Logitech                             | 3         | 1.39%   |
| QinHeng Electronics                  | 2         | 0.93%   |
| Mackie Designs                       | 2         | 0.93%   |
| ZOOM                                 | 1         | 0.46%   |
| Yealink Network Technology           | 1         | 0.46%   |
| Xilinx                               | 1         | 0.46%   |
| WL80                                 | 1         | 0.46%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.46%   |
| Textech International                | 1         | 0.46%   |
| Studiologic                          | 1         | 0.46%   |
| SteelSeries ApS                      | 1         | 0.46%   |
| Samson Technologies                  | 1         | 0.46%   |
| PreSonus Audio Electronics           | 1         | 0.46%   |
| Plantronics                          | 1         | 0.46%   |
| Medeli Electronics                   | 1         | 0.46%   |
| Mark of the Unicorn                  | 1         | 0.46%   |
| M-Audio                              | 1         | 0.46%   |
| KTMicro                              | 1         | 0.46%   |
| JMTek                                | 1         | 0.46%   |
| Generalplus Technology               | 1         | 0.46%   |
| Focusrite-Novation                   | 1         | 0.46%   |
| Ensoniq                              | 1         | 0.46%   |
| Behringer.......                     | 1         | 0.46%   |
| BEHRINGER International              | 1         | 0.46%   |
| ASUSTek Computer                     | 1         | 0.46%   |
| Apple                                | 1         | 0.46%   |
| Alesis                               | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 3.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.78%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.78%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 1.98%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.59%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.19%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.19%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 2         | 0.79%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2         | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.79%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 35        | 21.74%  |
| Samsung Electronics | 35        | 21.74%  |
| Kingston            | 19        | 11.8%   |
| Micron Technology   | 14        | 8.7%    |
| Unknown             | 12        | 7.45%   |
| Crucial             | 11        | 6.83%   |
| Corsair             | 11        | 6.83%   |
| G.Skill             | 5         | 3.11%   |
| Ramaxel Technology  | 3         | 1.86%   |
| Patriot             | 3         | 1.86%   |
| Nanya Technology    | 3         | 1.86%   |
| Transcend           | 1         | 0.62%   |
| Timetec             | 1         | 0.62%   |
| Smart               | 1         | 0.62%   |
| S                   | 1         | 0.62%   |
| PNY                 | 1         | 0.62%   |
| M                   | 1         | 0.62%   |
| HBS                 | 1         | 0.62%   |
| Elpida              | 1         | 0.62%   |
| Aeneon              | 1         | 0.62%   |
| 0194808980CE        | 1         | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s           | 3         | 1.67%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 3         | 1.67%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s        | 3         | 1.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2         | 1.11%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 2         | 1.11%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 1.11%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 1.11%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s      | 2         | 1.11%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2         | 1.11%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s         | 2         | 1.11%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2         | 1.11%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2         | 1.11%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s      | 2         | 1.11%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s            | 1         | 0.56%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s               | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1         | 0.56%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1         | 0.56%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s          | 1         | 0.56%   |
| Timetec RAM SD3-1600 8192MB SODIMM DDR3                     | 1         | 0.56%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1         | 0.56%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s             | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1067MT/s             | 1         | 0.56%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1         | 0.56%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1067MT/s             | 1         | 0.56%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1         | 0.56%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s       | 1         | 0.56%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1         | 0.56%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1         | 0.56%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 64        | 47.06%  |
| DDR4    | 47        | 34.56%  |
| DDR2    | 9         | 6.62%   |
| SDRAM   | 4         | 2.94%   |
| Unknown | 4         | 2.94%   |
| LPDDR4  | 3         | 2.21%   |
| DDR     | 3         | 2.21%   |
| LPDDR3  | 2         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 47.41%  |
| DIMM         | 59        | 43.7%   |
| Row Of Chips | 9         | 6.67%   |
| FB-DIMM      | 1         | 0.74%   |
| Chip         | 1         | 0.74%   |
| Unknown      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 50        | 32.68%  |
| 8192  | 45        | 29.41%  |
| 2048  | 22        | 14.38%  |
| 16384 | 17        | 11.11%  |
| 1024  | 10        | 6.54%   |
| 32768 | 6         | 3.92%   |
| 512   | 2         | 1.31%   |
| 256   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 31.51%  |
| 3200    | 16        | 10.96%  |
| 2667    | 12        | 8.22%   |
| 1333    | 10        | 6.85%   |
| 2133    | 8         | 5.48%   |
| 1334    | 7         | 4.79%   |
| 667     | 6         | 4.11%   |
| 2400    | 5         | 3.42%   |
| 1066    | 4         | 2.74%   |
| 4267    | 3         | 2.05%   |
| 1866    | 3         | 2.05%   |
| 800     | 3         | 2.05%   |
| Unknown | 3         | 2.05%   |
| 4199    | 2         | 1.37%   |
| 3600    | 2         | 1.37%   |
| 1867    | 2         | 1.37%   |
| 1800    | 2         | 1.37%   |
| 533     | 2         | 1.37%   |
| 3500    | 1         | 0.68%   |
| 3466    | 1         | 0.68%   |
| 3266    | 1         | 0.68%   |
| 3000    | 1         | 0.68%   |
| 2933    | 1         | 0.68%   |
| 2800    | 1         | 0.68%   |
| 2666    | 1         | 0.68%   |
| 2472    | 1         | 0.68%   |
| 1639    | 1         | 0.68%   |
| 1067    | 1         | 0.68%   |

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
| Chicony Electronics                    | 14        | 19.18%  |
| IMC Networks                           | 7         | 9.59%   |
| Realtek Semiconductor                  | 6         | 8.22%   |
| Microdia                               | 6         | 8.22%   |
| Logitech                               | 6         | 8.22%   |
| Sunplus Innovation Technology          | 5         | 6.85%   |
| Syntek                                 | 4         | 5.48%   |
| Suyin                                  | 3         | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.11%   |
| Samsung Electronics                    | 2         | 2.74%   |
| Quanta                                 | 2         | 2.74%   |
| Philips (or NXP)                       | 2         | 2.74%   |
| Microsoft                              | 2         | 2.74%   |
| Acer                                   | 2         | 2.74%   |
| Xiongmai                               | 1         | 1.37%   |
| ViewSonic                              | 1         | 1.37%   |
| ViewQuest Technologies                 | 1         | 1.37%   |
| Sweex                                  | 1         | 1.37%   |
| Silicon Motion                         | 1         | 1.37%   |
| Ricoh                                  | 1         | 1.37%   |
| Intel                                  | 1         | 1.37%   |
| Importek                               | 1         | 1.37%   |
| Apple                                  | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Syntek Integrated Camera                   | 4         | 5.41%   |
| Chicony Integrated Camera                  | 4         | 5.41%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 4.05%   |
| IMC Networks Integrated Camera             | 3         | 4.05%   |
| Sunplus Integrated_Webcam_HD               | 2         | 2.7%    |
| Samsung Galaxy series, misc. (MTP mode)    | 2         | 2.7%    |
| Realtek Lenovo EasyCamera                  | 2         | 2.7%    |
| Microdia Integrated_Webcam_HD              | 2         | 2.7%    |
| Logitech Webcam C270                       | 2         | 2.7%    |
| Chicony Integrated Camera [ThinkPad]       | 2         | 2.7%    |
| Xiongmai web camera                        | 1         | 1.35%   |
| ViewSonic PC Camera                        | 1         | 1.35%   |
| ViewQuest Ability GABB Webcam              | 1         | 1.35%   |
| Sweex WC060 Series HD Webcam               | 1         | 1.35%   |
| Suyin HP Webcam                            | 1         | 1.35%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.35%   |
| Suyin Asus Integrated Webcam               | 1         | 1.35%   |
| Sunplus HD WebCam                          | 1         | 1.35%   |
| Sunplus HD 720P webcam                     | 1         | 1.35%   |
| Sunplus Dell HD Webcam                     | 1         | 1.35%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.35%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.35%   |
| Realtek VGA WebCam                         | 1         | 1.35%   |
| Realtek USB Camera                         | 1         | 1.35%   |
| Realtek Integrated_Webcam_HD               | 1         | 1.35%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.35%   |
| Quanta ov9734_techfront_camera             | 1         | 1.35%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.35%   |
| Philips (or NXP) Webcam SPC530NC           | 1         | 1.35%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.35%   |
| Microsoft LifeCam VX-5000                  | 1         | 1.35%   |
| Microsoft LifeCam Cinema                   | 1         | 1.35%   |
| Microdia USB 2.0 Camera                    | 1         | 1.35%   |
| Microdia MSI Starcam Racer                 | 1         | 1.35%   |
| Microdia Integrated_Webcam_FHD             | 1         | 1.35%   |
| Microdia Integrated Webcam HD              | 1         | 1.35%   |
| Logitech QuickCam Communicate MP/S5500     | 1         | 1.35%   |
| Logitech Portable Webcam C905              | 1         | 1.35%   |
| Logitech HD Webcam C910                    | 1         | 1.35%   |
| Logitech HD Pro Webcam C920                | 1         | 1.35%   |

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
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 11.11%  |
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
| 0     | 96        | 72.73%  |
| 1     | 33        | 25%     |
| 2     | 2         | 1.52%   |
| 3     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 25%     |
| Fingerprint reader       | 9         | 25%     |
| Chipcard                 | 6         | 16.67%  |
| Net/wireless             | 5         | 13.89%  |
| Sound                    | 2         | 5.56%   |
| Multimedia controller    | 2         | 5.56%   |
| Modem                    | 1         | 2.78%   |
| Communication controller | 1         | 2.78%   |
| Camera                   | 1         | 2.78%   |


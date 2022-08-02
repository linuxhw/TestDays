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

Total: 132

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu Studio 20.04 | 73        | 65.18%  |
| Ubuntu Studio 20.10 | 13        | 11.61%  |
| Ubuntu Studio 22.04 | 8         | 7.14%   |
| Ubuntu Studio 21.10 | 7         | 6.25%   |
| Ubuntu Studio 21.04 | 5         | 4.46%   |
| Ubuntu Studio 18.04 | 3         | 2.68%   |
| Ubuntu Studio 19.10 | 2         | 1.79%   |
| Ubuntu Studio 16.04 | 1         | 0.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 112       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.13.0-28-lowlatency     | 5         | 4.42%   |
| 5.4.0-52-lowlatency      | 4         | 3.54%   |
| 5.4.0-42-lowlatency      | 4         | 3.54%   |
| 5.8.0-55-lowlatency      | 3         | 2.65%   |
| 5.8.0-50-lowlatency      | 3         | 2.65%   |
| 5.8.0-44-lowlatency      | 3         | 2.65%   |
| 5.8.0-25-lowlatency      | 3         | 2.65%   |
| 5.4.0-65-lowlatency      | 3         | 2.65%   |
| 5.4.0-26-lowlatency      | 3         | 2.65%   |
| 5.11.0-44-lowlatency     | 3         | 2.65%   |
| 5.11.0-34-lowlatency     | 3         | 2.65%   |
| 5.8.0-48-lowlatency      | 2         | 1.77%   |
| 5.8.0-29-lowlatency      | 2         | 1.77%   |
| 5.4.0-94-lowlatency      | 2         | 1.77%   |
| 5.4.0-58-lowlatency      | 2         | 1.77%   |
| 5.4.0-56-lowlatency      | 2         | 1.77%   |
| 5.4.0-45-lowlatency      | 2         | 1.77%   |
| 5.15.0-40-lowlatency     | 2         | 1.77%   |
| 5.15.0-30-lowlatency     | 2         | 1.77%   |
| 5.13.0-30-lowlatency     | 2         | 1.77%   |
| 5.11.0-27-lowlatency     | 2         | 1.77%   |
| 5.8.0-59-lowlatency      | 1         | 0.88%   |
| 5.8.0-45-lowlatency      | 1         | 0.88%   |
| 5.8.0-43-lowlatency      | 1         | 0.88%   |
| 5.8.0-36-lowlatency      | 1         | 0.88%   |
| 5.8.0-34-lowlatency      | 1         | 0.88%   |
| 5.8.0-34-generic         | 1         | 0.88%   |
| 5.8.0-33-lowlatency      | 1         | 0.88%   |
| 5.7.6-050706-lowlatency  | 1         | 0.88%   |
| 5.7.6-050706-generic     | 1         | 0.88%   |
| 5.4.0-99-lowlatency      | 1         | 0.88%   |
| 5.4.0-96-lowlatency      | 1         | 0.88%   |
| 5.4.0-88-lowlatency      | 1         | 0.88%   |
| 5.4.0-72-lowlatency      | 1         | 0.88%   |
| 5.4.0-71-lowlatency      | 1         | 0.88%   |
| 5.4.0-70-lowlatency      | 1         | 0.88%   |
| 5.4.0-65-generic         | 1         | 0.88%   |
| 5.4.0-64-lowlatency      | 1         | 0.88%   |
| 5.4.0-62-lowlatency      | 1         | 0.88%   |
| 5.4.0-60-lowlatency      | 1         | 0.88%   |
| 5.4.0-53-lowlatency      | 1         | 0.88%   |
| 5.4.0-52-generic         | 1         | 0.88%   |
| 5.4.0-51-lowlatency      | 1         | 0.88%   |
| 5.4.0-48-lowlatency      | 1         | 0.88%   |
| 5.4.0-47-lowlatency      | 1         | 0.88%   |
| 5.4.0-45-generic         | 1         | 0.88%   |
| 5.4.0-39-lowlatency      | 1         | 0.88%   |
| 5.4.0-34-lowlatency      | 1         | 0.88%   |
| 5.4.0-33-lowlatency      | 1         | 0.88%   |
| 5.4.0-122-generic        | 1         | 0.88%   |
| 5.4.0-110-lowlatency     | 1         | 0.88%   |
| 5.4.0-109-lowlatency     | 1         | 0.88%   |
| 5.4.0-107-lowlatency     | 1         | 0.88%   |
| 5.4.0-1025-raspi         | 1         | 0.88%   |
| 5.4.0-100-lowlatency     | 1         | 0.88%   |
| 5.3.0-42-lowlatency      | 1         | 0.88%   |
| 5.3.0-19-lowlatency      | 1         | 0.88%   |
| 5.17.1-051701-generic    | 1         | 0.88%   |
| 5.15.6-051506-lowlatency | 1         | 0.88%   |
| 5.15.0-41-lowlatency     | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 47        | 41.96%  |
| 5.8.0   | 23        | 20.54%  |
| 5.11.0  | 15        | 13.39%  |
| 5.13.0  | 10        | 8.93%   |
| 5.15.0  | 8         | 7.14%   |
| 4.15.0  | 3         | 2.68%   |
| 5.3.0   | 2         | 1.79%   |
| 5.7.6   | 1         | 0.89%   |
| 5.17.1  | 1         | 0.89%   |
| 5.15.6  | 1         | 0.89%   |
| 4.4.0   | 1         | 0.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 41.96%  |
| 5.8     | 23        | 20.54%  |
| 5.11    | 15        | 13.39%  |
| 5.13    | 10        | 8.93%   |
| 5.15    | 9         | 8.04%   |
| 4.15    | 3         | 2.68%   |
| 5.3     | 2         | 1.79%   |
| 5.7     | 1         | 0.89%   |
| 5.17    | 1         | 0.89%   |
| 4.4     | 1         | 0.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 110       | 98.21%  |
| i686    | 1         | 0.89%   |
| aarch64 | 1         | 0.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 67        | 59.82%  |
| KDE5            | 28        | 25%     |
| GNOME           | 10        | 8.93%   |
| MATE            | 2         | 1.79%   |
| LXQt            | 2         | 1.79%   |
| KDE             | 1         | 0.89%   |
| GNOME Flashback | 1         | 0.89%   |
| Cinnamon        | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 105       | 93.75%  |
| Wayland | 5         | 4.46%   |
| Tty     | 2         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 49        | 43.75%  |
| LightDM | 27        | 24.11%  |
| SDDM    | 24        | 21.43%  |
| GDM     | 11        | 9.82%   |
| LXDM    | 1         | 0.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 46        | 41.07%  |
| fr_FR      | 16        | 14.29%  |
| de_DE      | 8         | 7.14%   |
| pt_BR      | 6         | 5.36%   |
| C          | 5         | 4.46%   |
| it_IT      | 4         | 3.57%   |
| en_CA      | 4         | 3.57%   |
| en_GB      | 3         | 2.68%   |
| en_AU      | 2         | 1.79%   |
| Unknown    | 2         | 1.79%   |
| sk_SK      | 1         | 0.89%   |
| ru_RU      | 1         | 0.89%   |
| nl_NL      | 1         | 0.89%   |
| nl_BE      | 1         | 0.89%   |
| nb_NO      | 1         | 0.89%   |
| hu_HU      | 1         | 0.89%   |
| fr_FR.UTF8 | 1         | 0.89%   |
| fr_CH      | 1         | 0.89%   |
| es_NI      | 1         | 0.89%   |
| es_ES      | 1         | 0.89%   |
| es_CR      | 1         | 0.89%   |
| es_AR      | 1         | 0.89%   |
| en_NG      | 1         | 0.89%   |
| en_IE      | 1         | 0.89%   |
| en_DE      | 1         | 0.89%   |
| ca_ES      | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 61        | 54.46%  |
| BIOS | 51        | 45.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 94.64%  |
| Overlay | 4         | 3.57%   |
| Xfs     | 1         | 0.89%   |
| Ext2    | 1         | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 66        | 58.93%  |
| MBR  | 46        | 41.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 81.25%  |
| Yes       | 21        | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 54.46%  |
| Yes       | 51        | 45.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 21        | 18.75%  |
| ASUSTek Computer        | 20        | 17.86%  |
| Hewlett-Packard         | 14        | 12.5%   |
| Lenovo                  | 13        | 11.61%  |
| Gigabyte Technology     | 7         | 6.25%   |
| Acer                    | 5         | 4.46%   |
| Apple                   | 4         | 3.57%   |
| Fujitsu                 | 3         | 2.68%   |
| Toshiba                 | 2         | 1.79%   |
| Intel                   | 2         | 1.79%   |
| AZW                     | 2         | 1.79%   |
| ASRock                  | 2         | 1.79%   |
| Sony                    | 1         | 0.89%   |
| Samsung Electronics     | 1         | 0.89%   |
| Razer                   | 1         | 0.89%   |
| Raspberry Pi Foundation | 1         | 0.89%   |
| Pegatron                | 1         | 0.89%   |
| Packard Bell            | 1         | 0.89%   |
| MSI                     | 1         | 0.89%   |
| Medion                  | 1         | 0.89%   |
| Intel Client Systems    | 1         | 0.89%   |
| IBM                     | 1         | 0.89%   |
| HUAWEI                  | 1         | 0.89%   |
| Google                  | 1         | 0.89%   |
| Getac                   | 1         | 0.89%   |
| Foxconn                 | 1         | 0.89%   |
| Clevo                   | 1         | 0.89%   |
| Avell High Performance  | 1         | 0.89%   |
| Acidanthera             | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 3.57%   |
| Lenovo G50-45 80E3                       | 2         | 1.79%   |
| HP Pavilion dv6                          | 2         | 1.79%   |
| Dell OptiPlex 790                        | 2         | 1.79%   |
| Toshiba Satellite L755D                  | 1         | 0.89%   |
| Toshiba Satellite C855                   | 1         | 0.89%   |
| Sony VGN-NS31M_W                         | 1         | 0.89%   |
| Samsung 305V4A/305V5A                    | 1         | 0.89%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 0.89%   |
| RPi Raspberry Pi 4 Model B Rev 1.4       | 1         | 0.89%   |
| Pegatron FL368AA-UUZ SR5612CH            | 1         | 0.89%   |
| Packard Bell IMEDIA S3220                | 1         | 0.89%   |
| MSI MS-7A57                              | 1         | 0.89%   |
| Medion MD34207/C746                      | 1         | 0.89%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 0.89%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 0.89%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 0.89%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 0.89%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 0.89%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 0.89%   |
| Lenovo ThinkCentre M93p 10A8S45S00       | 1         | 0.89%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 0.89%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 0.89%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.89%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 0.89%   |
| Intel NUC8i5BEH                          | 1         | 0.89%   |
| Intel DQ965GF HD/FP Audio                | 1         | 0.89%   |
| Intel Client Systems LAPBC510            | 1         | 0.89%   |
| IBM 8188PPV                              | 1         | 0.89%   |
| HUAWEI HLYL-WXX9                         | 1         | 0.89%   |
| HP Z620 Workstation                      | 1         | 0.89%   |
| HP Stream Laptop 14-cb0XX                | 1         | 0.89%   |
| HP Sona                                  | 1         | 0.89%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 0.89%   |
| HP Notebook                              | 1         | 0.89%   |
| HP Laptop 15s-fq1xxx                     | 1         | 0.89%   |
| HP EliteBook 840 G3                      | 1         | 0.89%   |
| HP Compaq Pro 6305 SFF                   | 1         | 0.89%   |
| HP Compaq Elite 8300 CMT                 | 1         | 0.89%   |
| HP Compaq 8510p                          | 1         | 0.89%   |
| HP Compaq 8200 Elite SFF PC              | 1         | 0.89%   |
| HP Compaq 6005 Pro MT PC                 | 1         | 0.89%   |
| Google Nami                              | 1         | 0.89%   |
| Gigabyte X570 AORUS ELITE WIFI           | 1         | 0.89%   |
| Gigabyte H170-HD3-CF                     | 1         | 0.89%   |
| Gigabyte GA-MA770-DS3                    | 1         | 0.89%   |
| Gigabyte F2A78M-HD2                      | 1         | 0.89%   |
| Gigabyte B450M S2H                       | 1         | 0.89%   |
| Gigabyte B450 I AORUS PRO WIFI           | 1         | 0.89%   |
| Gigabyte A320M-S2H                       | 1         | 0.89%   |
| Getac S400G3                             | 1         | 0.89%   |
| Fujitsu ESPRIMO P420                     | 1         | 0.89%   |
| Fujitsu ESPRIMO G558                     | 1         | 0.89%   |
| Fujitsu ESPRIMO E720                     | 1         | 0.89%   |
| Foxconn Pro3500 Series                   | 1         | 0.89%   |
| Dell XPS 15 9570                         | 1         | 0.89%   |
| Dell Precision WorkStation T5400         | 1         | 0.89%   |
| Dell Precision M4500                     | 1         | 0.89%   |
| Dell OptiPlex GX620                      | 1         | 0.89%   |
| Dell OptiPlex 7050                       | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Dell Inspiron                 | 8         | 7.14%   |
| Dell OptiPlex                 | 7         | 6.25%   |
| Lenovo ThinkPad               | 6         | 5.36%   |
| HP Compaq                     | 5         | 4.46%   |
| ASUS All                      | 4         | 3.57%   |
| Acer Aspire                   | 4         | 3.57%   |
| Lenovo IdeaPad                | 3         | 2.68%   |
| Fujitsu ESPRIMO               | 3         | 2.68%   |
| Dell Latitude                 | 3         | 2.68%   |
| ASUS ROG                      | 3         | 2.68%   |
| Toshiba Satellite             | 2         | 1.79%   |
| Lenovo G50-45                 | 2         | 1.79%   |
| HP Pavilion                   | 2         | 1.79%   |
| Dell Precision                | 2         | 1.79%   |
| ASUS TUF                      | 2         | 1.79%   |
| Sony VGN-NS31M                | 1         | 0.89%   |
| Samsung 305V4A                | 1         | 0.89%   |
| Razer Blade                   | 1         | 0.89%   |
| RPi Raspberry                 | 1         | 0.89%   |
| Pegatron FL368AA-UUZ          | 1         | 0.89%   |
| Packard Bell IMEDIA           | 1         | 0.89%   |
| MSI MS-7A57                   | 1         | 0.89%   |
| Medion MD34207                | 1         | 0.89%   |
| Lenovo ThinkCentre            | 1         | 0.89%   |
| Lenovo Legion                 | 1         | 0.89%   |
| Intel NUC8i5BEH               | 1         | 0.89%   |
| Intel DQ965GF                 | 1         | 0.89%   |
| Intel Client Systems LAPBC510 | 1         | 0.89%   |
| IBM 8188PPV                   | 1         | 0.89%   |
| HUAWEI HLYL-WXX9              | 1         | 0.89%   |
| HP Z620                       | 1         | 0.89%   |
| HP Stream                     | 1         | 0.89%   |
| HP Sona                       | 1         | 0.89%   |
| HP OMEN                       | 1         | 0.89%   |
| HP Notebook                   | 1         | 0.89%   |
| HP Laptop                     | 1         | 0.89%   |
| HP EliteBook                  | 1         | 0.89%   |
| Google Nami                   | 1         | 0.89%   |
| Gigabyte X570                 | 1         | 0.89%   |
| Gigabyte H170-HD3-CF          | 1         | 0.89%   |
| Gigabyte GA-MA770-DS3         | 1         | 0.89%   |
| Gigabyte F2A78M-HD2           | 1         | 0.89%   |
| Gigabyte B450M                | 1         | 0.89%   |
| Gigabyte B450                 | 1         | 0.89%   |
| Gigabyte A320M-S2H            | 1         | 0.89%   |
| Getac S400G3                  | 1         | 0.89%   |
| Foxconn Pro3500               | 1         | 0.89%   |
| Dell XPS                      | 1         | 0.89%   |
| Clevo W35                     | 1         | 0.89%   |
| AZW SER                       | 1         | 0.89%   |
| AZW GK35                      | 1         | 0.89%   |
| Avell High Performance Avell  | 1         | 0.89%   |
| ASUS X541NA                   | 1         | 0.89%   |
| ASUS VivoBook                 | 1         | 0.89%   |
| ASUS UX305FA                  | 1         | 0.89%   |
| ASUS U56E                     | 1         | 0.89%   |
| ASUS P8P67                    | 1         | 0.89%   |
| ASUS P6T                      | 1         | 0.89%   |
| ASUS P5QC                     | 1         | 0.89%   |
| ASUS M5A78L-M                 | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2014 | 13        | 11.61%  |
| 2020 | 12        | 10.71%  |
| 2012 | 11        | 9.82%   |
| 2018 | 10        | 8.93%   |
| 2019 | 9         | 8.04%   |
| 2011 | 9         | 8.04%   |
| 2010 | 7         | 6.25%   |
| 2017 | 6         | 5.36%   |
| 2008 | 6         | 5.36%   |
| 2021 | 5         | 4.46%   |
| 2016 | 5         | 4.46%   |
| 2013 | 5         | 4.46%   |
| 2015 | 4         | 3.57%   |
| 2007 | 4         | 3.57%   |
| 2009 | 3         | 2.68%   |
| 2005 | 2         | 1.79%   |
| 2022 | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 53        | 47.32%  |
| Notebook       | 50        | 44.64%  |
| All in one     | 4         | 3.57%   |
| Mini pc        | 3         | 2.68%   |
| System on chip | 1         | 0.89%   |
| Convertible    | 1         | 0.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 106       | 94.64%  |
| Enabled  | 6         | 5.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 110       | 98.21%  |
| Yes  | 2         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 34        | 30.36%  |
| 16.01-24.0  | 27        | 24.11%  |
| 8.01-16.0   | 17        | 15.18%  |
| 3.01-4.0    | 12        | 10.71%  |
| 32.01-64.0  | 9         | 8.04%   |
| 64.01-256.0 | 4         | 3.57%   |
| 1.01-2.0    | 4         | 3.57%   |
| 2.01-3.0    | 3         | 2.68%   |
| 24.01-32.0  | 2         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 45        | 39.82%  |
| 2.01-3.0   | 24        | 21.24%  |
| 4.01-8.0   | 17        | 15.04%  |
| 3.01-4.0   | 14        | 12.39%  |
| 8.01-16.0  | 9         | 7.96%   |
| 0.51-1.0   | 3         | 2.65%   |
| 24.01-32.0 | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 55.36%  |
| 2      | 37        | 33.04%  |
| 3      | 5         | 4.46%   |
| 4      | 3         | 2.68%   |
| 0      | 2         | 1.79%   |
| 11     | 1         | 0.89%   |
| 10     | 1         | 0.89%   |
| 7      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 52.68%  |
| Yes       | 53        | 47.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 89.29%  |
| No        | 12        | 10.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 72.32%  |
| No        | 31        | 27.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 51.79%  |
| No        | 54        | 48.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 23        | 20.54%  |
| France                 | 19        | 16.96%  |
| Germany                | 12        | 10.71%  |
| Italy                  | 7         | 6.25%   |
| Brazil                 | 7         | 6.25%   |
| Canada                 | 5         | 4.46%   |
| UK                     | 3         | 2.68%   |
| Russia                 | 3         | 2.68%   |
| Austria                | 3         | 2.68%   |
| Australia              | 3         | 2.68%   |
| Taiwan                 | 2         | 1.79%   |
| Spain                  | 2         | 1.79%   |
| Norway                 | 2         | 1.79%   |
| Mexico                 | 2         | 1.79%   |
| Costa Rica             | 2         | 1.79%   |
| Belgium                | 2         | 1.79%   |
| Turkey                 | 1         | 0.89%   |
| Switzerland            | 1         | 0.89%   |
| Sweden                 | 1         | 0.89%   |
| Slovakia               | 1         | 0.89%   |
| Romania                | 1         | 0.89%   |
| Poland                 | 1         | 0.89%   |
| Nigeria                | 1         | 0.89%   |
| Nicaragua              | 1         | 0.89%   |
| Netherlands            | 1         | 0.89%   |
| Kenya                  | 1         | 0.89%   |
| Hungary                | 1         | 0.89%   |
| Finland                | 1         | 0.89%   |
| Bulgaria               | 1         | 0.89%   |
| Bosnia and Herzegovina | 1         | 0.89%   |
| Argentina              | 1         | 0.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Paris                   | 3         | 2.68%   |
| Turin                   | 2         | 1.79%   |
| Stuttgart               | 2         | 1.79%   |
| Montreal                | 2         | 1.79%   |
| Mississauga             | 2         | 1.79%   |
| Houston                 | 2         | 1.79%   |
| Béziers                | 2         | 1.79%   |
| Zanesville              | 1         | 0.89%   |
| Yekaterinburg           | 1         | 0.89%   |
| Wroclaw                 | 1         | 0.89%   |
| Woonsocket              | 1         | 0.89%   |
| Woodland Park           | 1         | 0.89%   |
| Villefontaine           | 1         | 0.89%   |
| Vienna                  | 1         | 0.89%   |
| Velleron                | 1         | 0.89%   |
| Tilburg                 | 1         | 0.89%   |
| Taylor                  | 1         | 0.89%   |
| Taipei                  | 1         | 0.89%   |
| Taichung                | 1         | 0.89%   |
| Sunderland              | 1         | 0.89%   |
| Stockholm               | 1         | 0.89%   |
| Stabekk                 | 1         | 0.89%   |
| Sofia                   | 1         | 0.89%   |
| Sherman Oaks            | 1         | 0.89%   |
| Seropedica              | 1         | 0.89%   |
| Sarajevo                | 1         | 0.89%   |
| Sao Paulo               | 1         | 0.89%   |
| Santa Barbara d'Oeste   | 1         | 0.89%   |
| San Secondo di Pinerolo | 1         | 0.89%   |
| San Juan                | 1         | 0.89%   |
| Samara                  | 1         | 0.89%   |
| Saint-Ouen-l'Aumone     | 1         | 0.89%   |
| Rio Grande da Serra     | 1         | 0.89%   |
| Rio de Janeiro          | 1         | 0.89%   |
| Rennes                  | 1         | 0.89%   |
| Ragusa                  | 1         | 0.89%   |
| Portland                | 1         | 0.89%   |
| Port Harcourt           | 1         | 0.89%   |
| Phoenix                 | 1         | 0.89%   |
| Pezinok                 | 1         | 0.89%   |
| Perth                   | 1         | 0.89%   |
| Palermo                 | 1         | 0.89%   |
| Oslo                    | 1         | 0.89%   |
| Olympia                 | 1         | 0.89%   |
| Oldenburg               | 1         | 0.89%   |
| Naumburg                | 1         | 0.89%   |
| Nairobi                 | 1         | 0.89%   |
| Moscow                  | 1         | 0.89%   |
| Modesto                 | 1         | 0.89%   |
| Mexico City             | 1         | 0.89%   |
| Mérida                 | 1         | 0.89%   |
| Merced                  | 1         | 0.89%   |
| Melbourne               | 1         | 0.89%   |
| Managua                 | 1         | 0.89%   |
| Maidenhead              | 1         | 0.89%   |
| Madrid                  | 1         | 0.89%   |
| Lyon                    | 1         | 0.89%   |
| Lomas de Zamora         | 1         | 0.89%   |
| Linz                    | 1         | 0.89%   |
| Lindsay                 | 1         | 0.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 39     | 18.79%  |
| WDC                 | 24        | 29     | 14.55%  |
| Seagate             | 19        | 27     | 11.52%  |
| Toshiba             | 13        | 14     | 7.88%   |
| SanDisk             | 11        | 11     | 6.67%   |
| Kingston            | 8         | 8      | 4.85%   |
| Unknown             | 6         | 6      | 3.64%   |
| Intel               | 6         | 7      | 3.64%   |
| Hitachi             | 5         | 5      | 3.03%   |
| Crucial             | 5         | 5      | 3.03%   |
| HGST                | 4         | 4      | 2.42%   |
| SK hynix            | 2         | 3      | 1.21%   |
| Micron Technology   | 2         | 2      | 1.21%   |
| Fujitsu             | 2         | 2      | 1.21%   |
| BHT                 | 2         | 2      | 1.21%   |
| A-DATA Technology   | 2         | 2      | 1.21%   |
| USB 3.0             | 1         | 2      | 0.61%   |
| Union Memory        | 1         | 1      | 0.61%   |
| UMIS                | 1         | 1      | 0.61%   |
| TO Exter            | 1         | 1      | 0.61%   |
| Team                | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| Phison Electronics  | 1         | 1      | 0.61%   |
| Patriot             | 1         | 1      | 0.61%   |
| OCZ                 | 1         | 1      | 0.61%   |
| NGFF                | 1         | 1      | 0.61%   |
| Maxtor              | 1         | 1      | 0.61%   |
| Leven               | 1         | 1      | 0.61%   |
| KIOXIA              | 1         | 1      | 0.61%   |
| KingSpec            | 1         | 1      | 0.61%   |
| JMicron Technology  | 1         | 1      | 0.61%   |
| Intenso             | 1         | 1      | 0.61%   |
| Integral            | 1         | 1      | 0.61%   |
| Inateck             | 1         | 1      | 0.61%   |
| EAGET               | 1         | 1      | 0.61%   |
| Corsair             | 1         | 1      | 0.61%   |
| China               | 1         | 1      | 0.61%   |
| ASMT                | 1         | 1      | 0.61%   |
| Apple               | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 3         | 1.62%   |
| Seagate ST500DM002-1BD142 500GB         | 3         | 1.62%   |
| Seagate ST2000DM001-1ER164 2TB          | 3         | 1.62%   |
| Samsung SSD 870 EVO 1TB                 | 3         | 1.62%   |
| Samsung SSD 860 EVO 500GB               | 3         | 1.62%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 1.62%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.08%   |
| Seagate Expansion 1TB                   | 2         | 1.08%   |
| SanDisk SSD PLUS 240GB                  | 2         | 1.08%   |
| SanDisk SDSSDA240G 240GB                | 2         | 1.08%   |
| Samsung SSD 970 EVO Plus 500GB          | 2         | 1.08%   |
| Samsung SSD 960 PRO 512GB               | 2         | 1.08%   |
| Samsung SSD 850 EVO 500GB               | 2         | 1.08%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD    | 2         | 1.08%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 1.08%   |
| WDC WDS200T2B0A-00SM50 2TB SSD          | 1         | 0.54%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.54%   |
| WDC WD6400AAKS-22A7B2 640GB             | 1         | 0.54%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 1         | 0.54%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1         | 0.54%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1         | 0.54%   |
| WDC WD3200BPVT-80ZEST0 320GB            | 1         | 0.54%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 0.54%   |
| WDC WD3200BEKT-75PVMT1 320GB            | 1         | 0.54%   |
| WDC WD3200AAKS-00VYA0 320GB             | 1         | 0.54%   |
| WDC WD30EZRZ-00Z5HB0 3TB                | 1         | 0.54%   |
| WDC WD30EZRX-00SPEB0 3TB                | 1         | 0.54%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.54%   |
| WDC WD2500AAKX-001CA0 250GB             | 1         | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.54%   |
| WDC WD20EZAZ-00GGJB0 2TB                | 1         | 0.54%   |
| WDC WD1600AAJS-60Z0A0 160GB             | 1         | 0.54%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1         | 0.54%   |
| WDC WD10JPVT-75A1YT0 1TB                | 1         | 0.54%   |
| WDC WD10EZEX-22RKKA0 1TB                | 1         | 0.54%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1         | 0.54%   |
| WDC WD10EZEX-22BN5A0 1TB                | 1         | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 0.54%   |
| WDC WD10EAVS-00D7B1 1TB                 | 1         | 0.54%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.54%   |
| WDC WD10EADS-00L5B1 1TB                 | 1         | 0.54%   |
| WDC WD1003FBYZ-010FB0 1TB               | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB    | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB    | 1         | 0.54%   |
| USB 3.0 Disk 640GB                      | 1         | 0.54%   |
| Unknown SN128  128GB                    | 1         | 0.54%   |
| Unknown SD/MMC/MS PRO 64GB              | 1         | 0.54%   |
| Unknown MMC Card  4GB                   | 1         | 0.54%   |
| Unknown MMC Card  16GB                  | 1         | 0.54%   |
| Unknown DA4128  128GB                   | 1         | 0.54%   |
| Unknown 032G34  32GB                    | 1         | 0.54%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB | 1         | 0.54%   |
| UMIS RPJTJ256MEE1OWX 256GB              | 1         | 0.54%   |
| Toshiba TR150 240GB SSD                 | 1         | 0.54%   |
| Toshiba MQ01ABB200 2TB                  | 1         | 0.54%   |
| Toshiba MK1637GSX 160GB                 | 1         | 0.54%   |
| Toshiba HDWE150 5TB                     | 1         | 0.54%   |
| Toshiba HDWE140 4TB                     | 1         | 0.54%   |
| Toshiba HDWD130 3TB                     | 1         | 0.54%   |
| Toshiba DT01ACA200 2TB                  | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 25     | 28.99%  |
| Seagate             | 19        | 26     | 27.54%  |
| Toshiba             | 12        | 13     | 17.39%  |
| Hitachi             | 5         | 5      | 7.25%   |
| Samsung Electronics | 4         | 4      | 5.8%    |
| HGST                | 4         | 4      | 5.8%    |
| Fujitsu             | 2         | 2      | 2.9%    |
| USB 3.0             | 1         | 2      | 1.45%   |
| Unknown             | 1         | 1      | 1.45%   |
| Maxtor              | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 30.65%  |
| SanDisk             | 9         | 9      | 14.52%  |
| Kingston            | 7         | 7      | 11.29%  |
| Crucial             | 5         | 5      | 8.06%   |
| Micron Technology   | 2         | 2      | 3.23%   |
| BHT                 | 2         | 2      | 3.23%   |
| A-DATA Technology   | 2         | 2      | 3.23%   |
| WDC                 | 1         | 1      | 1.61%   |
| Toshiba             | 1         | 1      | 1.61%   |
| TO Exter            | 1         | 1      | 1.61%   |
| SPCC                | 1         | 1      | 1.61%   |
| Patriot             | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 1      | 1.61%   |
| NGFF                | 1         | 1      | 1.61%   |
| Leven               | 1         | 1      | 1.61%   |
| KingSpec            | 1         | 1      | 1.61%   |
| Intenso             | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Integral            | 1         | 1      | 1.61%   |
| Inateck             | 1         | 1      | 1.61%   |
| Corsair             | 1         | 1      | 1.61%   |
| China               | 1         | 1      | 1.61%   |
| ASMT                | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 56        | 83     | 38.89%  |
| SSD     | 54        | 65     | 37.5%   |
| NVMe    | 26        | 33     | 18.06%  |
| MMC     | 6         | 7      | 4.17%   |
| Unknown | 2         | 2      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 136    | 67.44%  |
| NVMe | 25        | 32     | 19.38%  |
| SAS  | 11        | 15     | 8.53%   |
| MMC  | 6         | 7      | 4.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 84     | 57.5%   |
| 0.51-1.0   | 33        | 40     | 27.5%   |
| 1.01-2.0   | 8         | 10     | 6.67%   |
| 3.01-4.0   | 5         | 5      | 4.17%   |
| 4.01-10.0  | 3         | 6      | 2.5%    |
| 2.01-3.0   | 2         | 3      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 33.93%  |
| 501-1000       | 17        | 15.18%  |
| 251-500        | 16        | 14.29%  |
| 1001-2000      | 12        | 10.71%  |
| 51-100         | 9         | 8.04%   |
| 21-50          | 8         | 7.14%   |
| More than 3000 | 7         | 6.25%   |
| 1-20           | 5         | 4.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 44        | 38.94%  |
| 21-50          | 20        | 17.7%   |
| 101-250        | 16        | 14.16%  |
| 51-100         | 11        | 9.73%   |
| 251-500        | 7         | 6.19%   |
| 501-1000       | 7         | 6.19%   |
| More than 3000 | 4         | 3.54%   |
| 1001-2000      | 3         | 2.65%   |
| 2001-3000      | 1         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 2         | 2      | 7.14%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 3.57%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 3.57%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 3.57%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 3.57%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 3.57%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 3.57%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 3.57%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 3.57%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 3.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 3.57%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 3.57%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.57%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 3.57%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 3.57%   |
| Samsung Electronics HD753LJ 752GB                   | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.57%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 3.57%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 3.57%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.57%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 3.57%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 3.57%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 3.57%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 25%     |
| WDC                 | 6         | 6      | 21.43%  |
| Samsung Electronics | 5         | 5      | 17.86%  |
| Toshiba             | 2         | 2      | 7.14%   |
| Hitachi             | 2         | 2      | 7.14%   |
| A-DATA Technology   | 2         | 2      | 7.14%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 33.33%  |
| WDC                 | 6         | 6      | 28.57%  |
| Samsung Electronics | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| HGST                | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 21     | 74.07%  |
| SSD  | 6         | 6      | 22.22%  |
| NVMe | 1         | 1      | 3.7%    |

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
| Works    | 87        | 140    | 66.92%  |
| Malfunc  | 27        | 28     | 20.77%  |
| Detected | 15        | 21     | 11.54%  |
| Failed   | 1         | 1      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 78        | 56.12%  |
| AMD                         | 23        | 16.55%  |
| Samsung Electronics         | 10        | 7.19%   |
| ASMedia Technology          | 5         | 3.6%    |
| SanDisk                     | 3         | 2.16%   |
| Nvidia                      | 3         | 2.16%   |
| Marvell Technology Group    | 3         | 2.16%   |
| Union Memory (Shenzhen)     | 2         | 1.44%   |
| SK hynix                    | 2         | 1.44%   |
| Phison Electronics          | 2         | 1.44%   |
| JMicron Technology          | 2         | 1.44%   |
| VIA Technologies            | 1         | 0.72%   |
| Silicon Image               | 1         | 0.72%   |
| KIOXIA                      | 1         | 0.72%   |
| Kingston Technology Company | 1         | 0.72%   |
| Apple                       | 1         | 0.72%   |
| Adaptec                     | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 10.06%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 6.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 4.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.55%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.78%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.18%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 1.18%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.18%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.18%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2         | 1.18%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.18%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.59%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.59%   |
| SK hynix BC511                                                                 | 1         | 0.59%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.59%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.59%   |
| Nvidia MCP61 IDE                                                               | 1         | 0.59%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.59%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1         | 0.59%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1         | 0.59%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.59%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.59%   |
| JMicron JMB362 SATA Controller                                                 | 1         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.59%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.59%   |
| Intel SSD 660P Series                                                          | 1         | 0.59%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.59%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.59%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 0.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.59%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 0.59%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 60%     |
| NVMe | 25        | 17.86%  |
| IDE  | 20        | 14.29%  |
| RAID | 9         | 6.43%   |
| SAS  | 1         | 0.71%   |
| SCSI | 1         | 0.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 84        | 75%     |
| AMD    | 27        | 24.11%  |
| ARM    | 1         | 0.89%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 2.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 2.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 2.68%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 2.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.79%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.79%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.89%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.89%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.89%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.89%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.89%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.89%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.89%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.89%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.89%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.89%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.89%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 0.89%   |
| Intel Core i7-6700T CPU @ 2.80GHz       | 1         | 0.89%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz      | 1         | 0.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 0.89%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 0.89%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.89%   |
| Intel Core i7-3940XM CPU @ 3.00GHz      | 1         | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 0.89%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 0.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 0.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 0.89%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 1         | 0.89%   |
| Intel Core i7 CPU 930 @ 2.80GHz         | 1         | 0.89%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 0.89%   |
| Intel Core i5-9400T CPU @ 1.80GHz       | 1         | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1         | 0.89%   |
| Intel Core i5-8259U CPU @ 2.30GHz       | 1         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 0.89%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 0.89%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 0.89%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 0.89%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 0.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 0.89%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1         | 0.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 0.89%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 0.89%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 1         | 0.89%   |
| Intel Core i3-8130U CPU @ 2.20GHz       | 1         | 0.89%   |
| Intel Core i3-6100T CPU @ 3.20GHz       | 1         | 0.89%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 30        | 26.79%  |
| Intel Core i7          | 23        | 20.54%  |
| Intel Core i3          | 7         | 6.25%   |
| Other                  | 5         | 4.46%   |
| Intel Celeron          | 5         | 4.46%   |
| Intel Core 2 Duo       | 4         | 3.57%   |
| AMD Ryzen 7            | 4         | 3.57%   |
| AMD Ryzen 5            | 4         | 3.57%   |
| Intel Xeon             | 3         | 2.68%   |
| Intel Pentium 4        | 2         | 1.79%   |
| Intel Core i9          | 2         | 1.79%   |
| AMD Phenom II X4       | 2         | 1.79%   |
| AMD E                  | 2         | 1.79%   |
| AMD Athlon II X2       | 2         | 1.79%   |
| AMD A4                 | 2         | 1.79%   |
| Intel Pentium Dual     | 1         | 0.89%   |
| Intel Pentium          | 1         | 0.89%   |
| Intel Genuine          | 1         | 0.89%   |
| Intel Core 2           | 1         | 0.89%   |
| AMD Ryzen Threadripper | 1         | 0.89%   |
| AMD Ryzen 9            | 1         | 0.89%   |
| AMD Ryzen 3            | 1         | 0.89%   |
| AMD FX                 | 1         | 0.89%   |
| AMD E2                 | 1         | 0.89%   |
| AMD E1                 | 1         | 0.89%   |
| AMD Athlon X4          | 1         | 0.89%   |
| AMD Athlon Dual Core   | 1         | 0.89%   |
| AMD Athlon 64 X2       | 1         | 0.89%   |
| AMD A6                 | 1         | 0.89%   |
| AMD A10                | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 48        | 42.86%  |
| 2      | 43        | 38.39%  |
| 6      | 8         | 7.14%   |
| 8      | 6         | 5.36%   |
| 1      | 3         | 2.68%   |
| 10     | 2         | 1.79%   |
| 32     | 1         | 0.89%   |
| 16     | 1         | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 111       | 99.11%  |
| 2      | 1         | 0.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 58.93%  |
| 1      | 46        | 41.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 111       | 99.11%  |
| 32-bit         | 1         | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 11.61%  |
| 0x306c3    | 12        | 10.71%  |
| 0x206a7    | 10        | 8.93%   |
| 0x306a9    | 8         | 7.14%   |
| 0x906ea    | 4         | 3.57%   |
| 0x806ea    | 4         | 3.57%   |
| 0x08600104 | 4         | 3.57%   |
| 0x806c1    | 3         | 2.68%   |
| 0x506e3    | 3         | 2.68%   |
| 0x306d4    | 3         | 2.68%   |
| 0x010000c8 | 3         | 2.68%   |
| 0xf41      | 2         | 1.79%   |
| 0x706e5    | 2         | 1.79%   |
| 0x6fd      | 2         | 1.79%   |
| 0x406e3    | 2         | 1.79%   |
| 0x106e5    | 2         | 1.79%   |
| 0x10676    | 2         | 1.79%   |
| 0x07030105 | 2         | 1.79%   |
| 0xa0655    | 1         | 0.89%   |
| 0xa0652    | 1         | 0.89%   |
| 0x906ed    | 1         | 0.89%   |
| 0x906e9    | 1         | 0.89%   |
| 0x706a1    | 1         | 0.89%   |
| 0x6fb      | 1         | 0.89%   |
| 0x6f6      | 1         | 0.89%   |
| 0x506ca    | 1         | 0.89%   |
| 0x506c9    | 1         | 0.89%   |
| 0x50654    | 1         | 0.89%   |
| 0x406c4    | 1         | 0.89%   |
| 0x40661    | 1         | 0.89%   |
| 0x40651    | 1         | 0.89%   |
| 0x206d7    | 1         | 0.89%   |
| 0x20655    | 1         | 0.89%   |
| 0x106a5    | 1         | 0.89%   |
| 0x1067a    | 1         | 0.89%   |
| 0x0a201009 | 1         | 0.89%   |
| 0x08701021 | 1         | 0.89%   |
| 0x08600106 | 1         | 0.89%   |
| 0x08600103 | 1         | 0.89%   |
| 0x08301039 | 1         | 0.89%   |
| 0x08108109 | 1         | 0.89%   |
| 0x08101016 | 1         | 0.89%   |
| 0x07030104 | 1         | 0.89%   |
| 0x06003106 | 1         | 0.89%   |
| 0x06001119 | 1         | 0.89%   |
| 0x06000852 | 1         | 0.89%   |
| 0x05000029 | 1         | 0.89%   |
| 0x03000027 | 1         | 0.89%   |
| 0x010000c7 | 1         | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 14        | 12.5%   |
| KabyLake      | 12        | 10.71%  |
| SandyBridge   | 11        | 9.82%   |
| Zen 2         | 9         | 8.04%   |
| Skylake       | 9         | 8.04%   |
| IvyBridge     | 8         | 7.14%   |
| Penryn        | 4         | 3.57%   |
| K10           | 4         | 3.57%   |
| Core          | 4         | 3.57%   |
| Broadwell     | 4         | 3.57%   |
| TigerLake     | 3         | 2.68%   |
| Puma          | 3         | 2.68%   |
| Nehalem       | 3         | 2.68%   |
| Westmere      | 2         | 1.79%   |
| Piledriver    | 2         | 1.79%   |
| NetBurst      | 2         | 1.79%   |
| K8 Hammer     | 2         | 1.79%   |
| IceLake       | 2         | 1.79%   |
| Goldmont      | 2         | 1.79%   |
| CometLake     | 2         | 1.79%   |
| Zen+          | 1         | 0.89%   |
| Zen 3         | 1         | 0.89%   |
| Zen           | 1         | 0.89%   |
| Steamroller   | 1         | 0.89%   |
| Silvermont    | 1         | 0.89%   |
| K10 Llano     | 1         | 0.89%   |
| Goldmont plus | 1         | 0.89%   |
| Excavator     | 1         | 0.89%   |
| Bobcat        | 1         | 0.89%   |
| Unknown       | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 44.96%  |
| Nvidia | 41        | 31.78%  |
| AMD    | 30        | 23.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 4.51%   |
| AMD Renoir                                                                  | 6         | 4.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 3.76%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.76%   |
| Intel HD Graphics 530                                                       | 4         | 3.01%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 2.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 2.26%   |
| Intel UHD Graphics 620                                                      | 3         | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 2.26%   |
| Intel HD Graphics 5500                                                      | 3         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 2.26%   |
| Nvidia TU117M                                                               | 2         | 1.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.5%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.5%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.5%    |
| Intel HD Graphics 500                                                       | 2         | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.75%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1         | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.75%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 1         | 0.75%   |
| Nvidia GT216 [GeForce 315]                                                  | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.75%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.75%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.75%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1         | 0.75%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1         | 0.75%   |
| Nvidia GK107M [GeForce GTX 660M]                                            | 1         | 0.75%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 1         | 0.75%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 0.75%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 0.75%   |
| Nvidia GF108M [GeForce GT 525M]                                             | 1         | 0.75%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 0.75%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1         | 0.75%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1         | 0.75%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1         | 0.75%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1         | 0.75%   |
| Nvidia C77 [GeForce 8200]                                                   | 1         | 0.75%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1         | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 0.75%   |
| Intel Iris Plus Graphics G7                                                 | 1         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 0.75%   |
| Intel HD Graphics 630                                                       | 1         | 0.75%   |
| Intel HD Graphics 5300                                                      | 1         | 0.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 0.75%   |
| Intel DG1 [Iris Xe MAX Graphics]                                            | 1         | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 38.39%  |
| 1 x Nvidia     | 26        | 23.21%  |
| 1 x AMD        | 23        | 20.54%  |
| Intel + Nvidia | 10        | 8.93%   |
| AMD + Nvidia   | 4         | 3.57%   |
| Intel + AMD    | 2         | 1.79%   |
| Other          | 1         | 0.89%   |
| 2 x Nvidia     | 1         | 0.89%   |
| 2 x Intel      | 1         | 0.89%   |
| 2 x AMD        | 1         | 0.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 91        | 81.25%  |
| Proprietary | 19        | 16.96%  |
| Unknown     | 2         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 45.54%  |
| 1.01-2.0   | 15        | 13.39%  |
| 0.01-0.5   | 15        | 13.39%  |
| 0.51-1.0   | 14        | 12.5%   |
| 3.01-4.0   | 8         | 7.14%   |
| 5.01-6.0   | 3         | 2.68%   |
| 7.01-8.0   | 2         | 1.79%   |
| 8.01-16.0  | 2         | 1.79%   |
| 2.01-3.0   | 1         | 0.89%   |
| 16.01-24.0 | 1         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 13.28%  |
| AU Optronics            | 14        | 10.94%  |
| LG Display              | 9         | 7.03%   |
| Goldstar                | 9         | 7.03%   |
| Dell                    | 8         | 6.25%   |
| Acer                    | 8         | 6.25%   |
| Philips                 | 7         | 5.47%   |
| Chimei Innolux          | 6         | 4.69%   |
| BOE                     | 6         | 4.69%   |
| Ancor Communications    | 6         | 4.69%   |
| Hewlett-Packard         | 5         | 3.91%   |
| Sharp                   | 2         | 1.56%   |
| Lenovo                  | 2         | 1.56%   |
| Iiyama                  | 2         | 1.56%   |
| Hannspree               | 2         | 1.56%   |
| Eizo                    | 2         | 1.56%   |
| Apple                   | 2         | 1.56%   |
| AOC                     | 2         | 1.56%   |
| VIE                     | 1         | 0.78%   |
| Unknown                 | 1         | 0.78%   |
| UGD                     | 1         | 0.78%   |
| TVT                     | 1         | 0.78%   |
| Targa Visionary         | 1         | 0.78%   |
| Sony                    | 1         | 0.78%   |
| Seiki                   | 1         | 0.78%   |
| Onkyo                   | 1         | 0.78%   |
| NEC Computers           | 1         | 0.78%   |
| Medion                  | 1         | 0.78%   |
| LG Philips              | 1         | 0.78%   |
| KTC                     | 1         | 0.78%   |
| Fujitsu Siemens         | 1         | 0.78%   |
| DENON                   | 1         | 0.78%   |
| CPT                     | 1         | 0.78%   |
| Chi Mei Optoelectronics | 1         | 0.78%   |
| BenQ                    | 1         | 0.78%   |
| ASUSTek Computer        | 1         | 0.78%   |
| Arnos Instruments       | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.49%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 1.49%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                    | 2         | 1.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 1.49%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.49%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1         | 0.75%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1         | 0.75%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch                 | 1         | 0.75%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1         | 0.75%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1         | 0.75%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                      | 1         | 0.75%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                 | 1         | 0.75%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1         | 0.75%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.75%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch     | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1         | 0.75%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1         | 0.75%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1         | 0.75%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.75%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch   | 1         | 0.75%   |
| Philips PHL 244E5 PHLC0C0 1920x1080 527x296mm 23.8-inch                 | 1         | 0.75%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                   | 1         | 0.75%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 0.75%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                       | 1         | 0.75%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                      | 1         | 0.75%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1         | 0.75%   |
| Philips 170B PHL082C 1280x1024 338x270mm 17.0-inch                      | 1         | 0.75%   |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                    | 1         | 0.75%   |
| NEC Computers LCD2180UX NEC662C 1600x1200 430x320mm 21.1-inch           | 1         | 0.75%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                  | 1         | 0.75%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch            | 1         | 0.75%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                | 1         | 0.75%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                 | 1         | 0.75%   |
| KTC H-W2206S-D KTC2203 1680x1050 433x270mm 20.1-inch                    | 1         | 0.75%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 1         | 0.75%   |
| Iiyama PL2435M IVM6112 1920x1080 521x293mm 23.5-inch                    | 1         | 0.75%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch             | 1         | 0.75%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch           | 1         | 0.75%   |
| Hewlett-Packard L1902 HWP261E 1280x1024 340x270mm 17.1-inch             | 1         | 0.75%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch               | 1         | 0.75%   |
| Hewlett-Packard 22xi HWP302E 1920x1080 480x270mm 21.7-inch              | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 42.86%  |
| 1366x768 (WXGA)    | 20        | 16.81%  |
| 3840x2160 (4K)     | 10        | 8.4%    |
| 1280x1024 (SXGA)   | 9         | 7.56%   |
| 1680x1050 (WSXGA+) | 6         | 5.04%   |
| 1600x900 (HD+)     | 6         | 5.04%   |
| 1440x900 (WXGA+)   | 4         | 3.36%   |
| 2560x1440 (QHD)    | 3         | 2.52%   |
| 1920x1200 (WUXGA)  | 2         | 1.68%   |
| 1280x800 (WXGA)    | 2         | 1.68%   |
| 5760x2160          | 1         | 0.84%   |
| 2880x1800          | 1         | 0.84%   |
| 1600x1200          | 1         | 0.84%   |
| 1400x1050          | 1         | 0.84%   |
| 1360x768           | 1         | 0.84%   |
| Unknown            | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 25.4%   |
| 21      | 14        | 11.11%  |
| 23      | 10        | 7.94%   |
| 27      | 9         | 7.14%   |
| 24      | 9         | 7.14%   |
| 19      | 8         | 6.35%   |
| 13      | 8         | 6.35%   |
| 22      | 5         | 3.97%   |
| 17      | 5         | 3.97%   |
| 20      | 4         | 3.17%   |
| 18      | 4         | 3.17%   |
| 14      | 4         | 3.17%   |
| 12      | 3         | 2.38%   |
| 84      | 2         | 1.59%   |
| 65      | 1         | 0.79%   |
| 52      | 1         | 0.79%   |
| 50      | 1         | 0.79%   |
| 32      | 1         | 0.79%   |
| 31      | 1         | 0.79%   |
| 26      | 1         | 0.79%   |
| 16      | 1         | 0.79%   |
| 11      | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 37.7%   |
| 401-500     | 29        | 23.77%  |
| 501-600     | 26        | 21.31%  |
| 201-300     | 7         | 5.74%   |
| 351-400     | 5         | 4.1%    |
| 1001-1500   | 3         | 2.46%   |
| 601-700     | 2         | 1.64%   |
| 1501-2000   | 2         | 1.64%   |
| 701-800     | 1         | 0.82%   |
| Unknown     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 73.68%  |
| 16/10   | 18        | 15.79%  |
| 5/4     | 8         | 7.02%   |
| 4/3     | 2         | 1.75%   |
| 3/2     | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 32        | 25.6%   |
| 101-110        | 32        | 25.6%   |
| 151-200        | 14        | 11.2%   |
| 301-350        | 10        | 8%      |
| 81-90          | 9         | 7.2%    |
| 141-150        | 9         | 7.2%    |
| More than 1000 | 5         | 4%      |
| 71-80          | 3         | 2.4%    |
| 61-70          | 3         | 2.4%    |
| 251-300        | 3         | 2.4%    |
| 351-500        | 2         | 1.6%    |
| 51-60          | 1         | 0.8%    |
| 111-120        | 1         | 0.8%    |
| Unknown        | 1         | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 52        | 44.07%  |
| 101-120       | 33        | 27.97%  |
| 121-160       | 23        | 19.49%  |
| 161-240       | 7         | 5.93%   |
| More than 240 | 2         | 1.69%   |
| Unknown       | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 85        | 75.22%  |
| 2     | 26        | 23.01%  |
| 3     | 1         | 0.88%   |
| 0     | 1         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 59        | 34.3%   |
| Intel                             | 59        | 34.3%   |
| Qualcomm Atheros                  | 19        | 11.05%  |
| Broadcom                          | 11        | 6.4%    |
| Nvidia                            | 3         | 1.74%   |
| TP-Link                           | 2         | 1.16%   |
| Ralink                            | 2         | 1.16%   |
| MediaTek                          | 2         | 1.16%   |
| Broadcom Limited                  | 2         | 1.16%   |
| ASIX Electronics                  | 2         | 1.16%   |
| Aquantia                          | 2         | 1.16%   |
| ZyDAS                             | 1         | 0.58%   |
| Wacom                             | 1         | 0.58%   |
| Qualcomm Atheros Communications   | 1         | 0.58%   |
| NetGear                           | 1         | 0.58%   |
| Microsoft                         | 1         | 0.58%   |
| Marvell Technology Group          | 1         | 0.58%   |
| Huawei Technologies               | 1         | 0.58%   |
| Ericsson Business Mobile Networks | 1         | 0.58%   |
| DisplayLink                       | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 21.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5.64%   |
| Intel Wireless 7265                                               | 7         | 3.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.54%   |
| Intel Wireless-AC 9260                                            | 3         | 1.54%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.54%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.03%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.03%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.03%   |
| Intel Wireless 7260                                               | 2         | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.03%   |
| ZyDAS ZD1211B 802.11g                                             | 1         | 0.51%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1         | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.51%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.51%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1         | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.51%   |
| Realtek 802.11ac NIC                                              | 1         | 0.51%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]  | 1         | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.51%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.51%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1         | 0.51%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.51%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 0.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.51%   |
| MediaTek moto e(6) plus                                           | 1         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.51%   |
| Intel Wireless 8260                                               | 1         | 0.51%   |
| Intel WiFi Link 5100                                              | 1         | 0.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 48.15%  |
| Qualcomm Atheros                | 14        | 17.28%  |
| Realtek Semiconductor           | 11        | 13.58%  |
| Broadcom                        | 6         | 7.41%   |
| TP-Link                         | 2         | 2.47%   |
| Ralink                          | 2         | 2.47%   |
| ZyDAS                           | 1         | 1.23%   |
| Wacom                           | 1         | 1.23%   |
| Qualcomm Atheros Communications | 1         | 1.23%   |
| NetGear                         | 1         | 1.23%   |
| Microsoft                       | 1         | 1.23%   |
| MediaTek                        | 1         | 1.23%   |
| Broadcom Limited                | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 7         | 8.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 4         | 4.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 4         | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 3         | 3.66%   |
| Intel Wireless-AC 9260                                           | 3         | 3.66%   |
| Intel Wi-Fi 6 AX201                                              | 3         | 3.66%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 3.66%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 3         | 3.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 2         | 2.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 2         | 2.44%   |
| Intel Wireless 8265 / 8275                                       | 2         | 2.44%   |
| Intel Wireless 7260                                              | 2         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.44%   |
| ZyDAS ZD1211B 802.11g                                            | 1         | 1.22%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                         | 1         | 1.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 1         | 1.22%   |
| TP-Link 802.11ac NIC                                             | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1         | 1.22%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller        | 1         | 1.22%   |
| Realtek 802.11ac NIC                                             | 1         | 1.22%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 1         | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                  | 1         | 1.22%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                 | 1         | 1.22%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter       | 1         | 1.22%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]      | 1         | 1.22%   |
| Microsoft Xbox 360 Wireless Adapter                              | 1         | 1.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 1         | 1.22%   |
| Intel Wireless 8260                                              | 1         | 1.22%   |
| Intel WiFi Link 5100                                             | 1         | 1.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.22%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.22%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.22%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 1         | 1.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.22%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter               | 1         | 1.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.22%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter               | 1         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 51        | 46.36%  |
| Intel                    | 36        | 32.73%  |
| Qualcomm Atheros         | 6         | 5.45%   |
| Broadcom                 | 6         | 5.45%   |
| Nvidia                   | 3         | 2.73%   |
| ASIX Electronics         | 2         | 1.82%   |
| Aquantia                 | 2         | 1.82%   |
| MediaTek                 | 1         | 0.91%   |
| Marvell Technology Group | 1         | 0.91%   |
| DisplayLink              | 1         | 0.91%   |
| Broadcom Limited         | 1         | 0.91%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 36.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 9.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.7%    |
| Intel I211 Gigabit Network Connection                             | 3         | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.7%    |
| Nvidia MCP77 Ethernet                                             | 2         | 1.8%    |
| Intel Ethernet Connection I217-V                                  | 2         | 1.8%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.8%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.9%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.9%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.9%    |
| MediaTek moto e(6) plus                                           | 1         | 0.9%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.9%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.9%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.9%    |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.9%    |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1         | 0.9%    |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 0.9%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.9%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.9%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.9%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.9%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.9%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.9%    |
| ASIX AX88772B                                                     | 1         | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 54.64%  |
| WiFi     | 81        | 44.26%  |
| Modem    | 2         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 50.83%  |
| WiFi     | 59        | 49.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 56.25%  |
| 1     | 47        | 41.96%  |
| 3     | 1         | 0.89%   |
| 0     | 1         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 92        | 82.14%  |
| Yes  | 20        | 17.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 50%     |
| Qualcomm Atheros Communications | 7         | 12.07%  |
| Realtek Semiconductor           | 4         | 6.9%    |
| Broadcom                        | 4         | 6.9%    |
| Cambridge Silicon Radio         | 3         | 5.17%   |
| Apple                           | 3         | 5.17%   |
| Ralink Technology               | 2         | 3.45%   |
| Realtek                         | 1         | 1.72%   |
| MediaTek                        | 1         | 1.72%   |
| Lite-On Technology              | 1         | 1.72%   |
| Hewlett-Packard                 | 1         | 1.72%   |
| Foxconn International           | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 20.69%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 8.62%   |
| Intel AX201 Bluetooth                               | 5         | 8.62%   |
| Intel Bluetooth Device                              | 4         | 6.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 5.17%   |
| Intel AX200 Bluetooth                               | 3         | 5.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 5.17%   |
| Realtek Bluetooth Radio                             | 2         | 3.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 3.45%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.72%   |
| Realtek Bluetooth Radio                             | 1         | 1.72%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.72%   |
| Ralink CSR BS8510                                   | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.72%   |
| MediaTek Wireless_Device                            | 1         | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.72%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.72%   |
| ASUS BCM20702A0                                     | 1         | 1.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.72%   |
| Apple Bluetooth Host Controller                     | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 82        | 44.57%  |
| Nvidia                               | 32        | 17.39%  |
| AMD                                  | 31        | 16.85%  |
| Texas Instruments                    | 5         | 2.72%   |
| C-Media Electronics                  | 5         | 2.72%   |
| Yamaha                               | 3         | 1.63%   |
| Logitech                             | 3         | 1.63%   |
| QinHeng Electronics                  | 2         | 1.09%   |
| Mackie Designs                       | 2         | 1.09%   |
| ZOOM                                 | 1         | 0.54%   |
| Yealink Network Technology           | 1         | 0.54%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.54%   |
| Textech International                | 1         | 0.54%   |
| Studiologic                          | 1         | 0.54%   |
| SteelSeries ApS                      | 1         | 0.54%   |
| Plantronics                          | 1         | 0.54%   |
| Medeli Electronics                   | 1         | 0.54%   |
| Mark of the Unicorn                  | 1         | 0.54%   |
| M-Audio                              | 1         | 0.54%   |
| KTMicro                              | 1         | 0.54%   |
| JMTek                                | 1         | 0.54%   |
| Jieli Technology                     | 1         | 0.54%   |
| Focusrite-Novation                   | 1         | 0.54%   |
| Ensoniq                              | 1         | 0.54%   |
| Behringer.......                     | 1         | 0.54%   |
| BEHRINGER International              | 1         | 0.54%   |
| ASUSTek Computer                     | 1         | 0.54%   |
| Apple                                | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13        | 6.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 4.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8         | 3.72%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8         | 3.72%   |
| AMD FCH Azalia Controller                                                         | 7         | 3.26%   |
| Intel Cannon Lake PCH cAVS                                                        | 6         | 2.79%   |
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4         | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 1.86%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 1.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4         | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 1.86%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 1.4%    |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 1.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3         | 1.4%    |
| Intel 200 Series PCH HD Audio                                                     | 3         | 1.4%    |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                          | 3         | 1.4%    |
| QinHeng Electronics CH345 MIDI adapter                                            | 2         | 0.93%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2         | 0.93%   |
| Nvidia GT216 HDMI Audio Controller                                                | 2         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 0.93%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                         | 2         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 0.93%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2         | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2         | 0.93%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.93%   |
| ZOOM U-22                                                                         | 1         | 0.47%   |
| Yealink Network Technology VoIP Phone                                             | 1         | 0.47%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1         | 0.47%   |
| Yamaha MG-XU                                                                      | 1         | 0.47%   |
| Yamaha AG06/AG03                                                                  | 1         | 0.47%   |
| Thesycon Systemsoftware & Consulting USB HiRes Audio                              | 1         | 0.47%   |
| Textech International MIDI Interface cable                                        | 1         | 0.47%   |
| Texas Instruments PCM2900B Audio CODEC                                            | 1         | 0.47%   |
| Texas Instruments PCM2900 Audio Codec                                             | 1         | 0.47%   |
| Studiologic SL STUDIO                                                             | 1         | 0.47%   |
| SteelSeries ApS Arctis Pro Wireless                                               | 1         | 0.47%   |
| Plantronics DA40                                                                  | 1         | 0.47%   |
| Nvidia MCP61 High Definition Audio                                                | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                           | 1         | 0.47%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 0.47%   |
| Nvidia GK110 High Definition Audio Controller                                     | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.47%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 22.96%  |
| SK hynix            | 29        | 21.48%  |
| Kingston            | 15        | 11.11%  |
| Unknown             | 12        | 8.89%   |
| Micron Technology   | 12        | 8.89%   |
| Crucial             | 9         | 6.67%   |
| Corsair             | 8         | 5.93%   |
| G.Skill             | 4         | 2.96%   |
| Patriot             | 3         | 2.22%   |
| Nanya Technology    | 3         | 2.22%   |
| Ramaxel Technology  | 2         | 1.48%   |
| Transcend           | 1         | 0.74%   |
| Smart               | 1         | 0.74%   |
| S                   | 1         | 0.74%   |
| M                   | 1         | 0.74%   |
| HBS                 | 1         | 0.74%   |
| Aeneon              | 1         | 0.74%   |
| 0194808980CE        | 1         | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.96%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 3         | 1.96%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 2         | 1.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 1.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.31%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s          | 2         | 1.31%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 2         | 1.31%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s           | 2         | 1.31%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s       | 2         | 1.31%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 2         | 1.31%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 0.65%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 512MB DIMM DDR                            | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 0.65%   |
| Unknown RAM Module 256MB DIMM DDR                            | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR                           | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                       | 1         | 0.65%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                  | 1         | 0.65%   |
| Transcend RAM TS1GSK64W6H 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s           | 1         | 0.65%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s    | 1         | 0.65%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 0.65%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1067MT/s              | 1         | 0.65%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s                | 1         | 0.65%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1067MT/s              | 1         | 0.65%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s         | 1         | 0.65%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s        | 1         | 0.65%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s  | 1         | 0.65%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s  | 1         | 0.65%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s         | 1         | 0.65%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT351U7CFR8C-PB 4096MB DIMM DDR3 1600MT/s      | 1         | 0.65%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 1         | 0.65%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s         | 1         | 0.65%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 0.65%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1         | 0.65%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 0.65%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.65%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 0.65%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 56        | 48.7%   |
| DDR4    | 35        | 30.43%  |
| DDR2    | 8         | 6.96%   |
| SDRAM   | 4         | 3.48%   |
| Unknown | 4         | 3.48%   |
| LPDDR4  | 3         | 2.61%   |
| DDR     | 3         | 2.61%   |
| LPDDR3  | 2         | 1.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 49.11%  |
| DIMM         | 48        | 42.86%  |
| Row Of Chips | 6         | 5.36%   |
| FB-DIMM      | 1         | 0.89%   |
| Chip         | 1         | 0.89%   |
| Unknown      | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 42        | 32.81%  |
| 8192  | 39        | 30.47%  |
| 2048  | 20        | 15.63%  |
| 16384 | 11        | 8.59%   |
| 1024  | 8         | 6.25%   |
| 32768 | 5         | 3.91%   |
| 512   | 2         | 1.56%   |
| 256   | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 42        | 34.15%  |
| 3200    | 11        | 8.94%   |
| 2667    | 9         | 7.32%   |
| 1333    | 8         | 6.5%    |
| 1334    | 7         | 5.69%   |
| 2133    | 6         | 4.88%   |
| 2400    | 5         | 4.07%   |
| 667     | 5         | 4.07%   |
| 4267    | 3         | 2.44%   |
| 1866    | 3         | 2.44%   |
| 1066    | 3         | 2.44%   |
| 800     | 3         | 2.44%   |
| Unknown | 3         | 2.44%   |
| 4199    | 2         | 1.63%   |
| 1867    | 2         | 1.63%   |
| 3600    | 1         | 0.81%   |
| 3500    | 1         | 0.81%   |
| 3466    | 1         | 0.81%   |
| 3266    | 1         | 0.81%   |
| 2933    | 1         | 0.81%   |
| 2800    | 1         | 0.81%   |
| 2666    | 1         | 0.81%   |
| 1800    | 1         | 0.81%   |
| 1639    | 1         | 0.81%   |
| 1067    | 1         | 0.81%   |
| 533     | 1         | 0.81%   |

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
| Chicony Electronics                    | 13        | 21.67%  |
| Realtek Semiconductor                  | 5         | 8.33%   |
| Logitech                               | 5         | 8.33%   |
| IMC Networks                           | 5         | 8.33%   |
| Sunplus Innovation Technology          | 4         | 6.67%   |
| Microdia                               | 4         | 6.67%   |
| Suyin                                  | 3         | 5%      |
| Samsung Electronics                    | 2         | 3.33%   |
| Quanta                                 | 2         | 3.33%   |
| Philips (or NXP)                       | 2         | 3.33%   |
| Microsoft                              | 2         | 3.33%   |
| Acer                                   | 2         | 3.33%   |
| Xiongmai                               | 1         | 1.67%   |
| ViewSonic                              | 1         | 1.67%   |
| ViewQuest Technologies                 | 1         | 1.67%   |
| Syntek                                 | 1         | 1.67%   |
| Sweex                                  | 1         | 1.67%   |
| Silicon Motion                         | 1         | 1.67%   |
| Ricoh                                  | 1         | 1.67%   |
| Intel                                  | 1         | 1.67%   |
| Importek                               | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.67%   |
| Apple                                  | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                   | 3         | 4.92%   |
| Chicony Integrated Camera                        | 3         | 4.92%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 3.28%   |
| Samsung Galaxy A5 (MTP)                          | 2         | 3.28%   |
| Microdia Integrated_Webcam_HD                    | 2         | 3.28%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 3.28%   |
| Xiongmai web camera                              | 1         | 1.64%   |
| ViewSonic PC Camera                              | 1         | 1.64%   |
| ViewQuest Ability GABB Webcam                    | 1         | 1.64%   |
| Syntek Integrated Camera                         | 1         | 1.64%   |
| Sweex WC060 Series HD Webcam                     | 1         | 1.64%   |
| Suyin HP Webcam                                  | 1         | 1.64%   |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 1.64%   |
| Suyin Asus Integrated Webcam                     | 1         | 1.64%   |
| Sunplus HD 720P webcam                           | 1         | 1.64%   |
| Sunplus Dell HD Webcam                           | 1         | 1.64%   |
| Silicon Motion WebCam SCB-1100N                  | 1         | 1.64%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 1.64%   |
| Realtek VGA WebCam                               | 1         | 1.64%   |
| Realtek MTD camera                               | 1         | 1.64%   |
| Realtek Lenovo EasyCamera                        | 1         | 1.64%   |
| Realtek Integrated_Webcam_HD                     | 1         | 1.64%   |
| Realtek HP Wide Vision HD Camera                 | 1         | 1.64%   |
| Quanta ov9734_techfront_camera                   | 1         | 1.64%   |
| Quanta HP TrueVision HD Camera                   | 1         | 1.64%   |
| Philips (or NXP) Webcam SPC530NC                 | 1         | 1.64%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]       | 1         | 1.64%   |
| Microsoft LifeCam VX-5000                        | 1         | 1.64%   |
| Microsoft LifeCam Cinema                         | 1         | 1.64%   |
| Microdia Integrated_Webcam_FHD                   | 1         | 1.64%   |
| Microdia Integrated Webcam HD                    | 1         | 1.64%   |
| Logitech Webcam C270                             | 1         | 1.64%   |
| Logitech QuickCam Communicate MP/S5500           | 1         | 1.64%   |
| Logitech Portable Webcam C905                    | 1         | 1.64%   |
| Logitech HD Webcam C910                          | 1         | 1.64%   |
| Logitech HD Pro Webcam C920                      | 1         | 1.64%   |
| Intel RealSense 3D Camera (Front F200)           | 1         | 1.64%   |
| Importek TOSHIBA Web Camera - HD                 | 1         | 1.64%   |
| IMC Networks UVC VGA Webcam                      | 1         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                | 1         | 1.64%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 1         | 1.64%   |
| Chicony Integrated IR Camera                     | 1         | 1.64%   |
| Chicony HP Wide Vision HD Camera                 | 1         | 1.64%   |
| Chicony HP TrueVision HD                         | 1         | 1.64%   |
| Chicony HP HD Camera                             | 1         | 1.64%   |
| Chicony HD Webcam                                | 1         | 1.64%   |
| Chicony HD User Facing                           | 1         | 1.64%   |
| Chicony CNF9055 Toshiba Webcam                   | 1         | 1.64%   |
| Chicony 4-Port Hub                               | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 1.64%   |
| Apple Built-in iSight                            | 1         | 1.64%   |
| Acer Lenovo EasyCamera                           | 1         | 1.64%   |
| Acer BisonCam, NB Pro                            | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| LighTuning Technology      | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner             | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device              | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader               | 1         | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor             | 1         | 12.5%   |

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
| 0     | 83        | 74.11%  |
| 1     | 26        | 23.21%  |
| 2     | 2         | 1.79%   |
| 3     | 1         | 0.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 8         | 27.59%  |
| Fingerprint reader       | 8         | 27.59%  |
| Chipcard                 | 6         | 20.69%  |
| Sound                    | 2         | 6.9%    |
| Net/wireless             | 2         | 6.9%    |
| Multimedia controller    | 2         | 6.9%    |
| Communication controller | 1         | 3.45%   |


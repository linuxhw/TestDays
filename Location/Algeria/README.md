Linux in Algeria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Algeria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Algeria/Desktop/README.md) and [notebooks](/Location/Algeria/Notebook/README.md).

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

Total: 442

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 2B34                        | Desktop     | [52737869e2](https://linux-hardware.org/?probe=52737869e2) | Nov 06, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [ad0e3ec9ea](https://linux-hardware.org/?probe=ad0e3ec9ea) | Nov 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d2d21dcf50](https://linux-hardware.org/?probe=d2d21dcf50) | Nov 01, 2023 |
| AMI           | Intel                       | Desktop     | [c4587092bf](https://linux-hardware.org/?probe=c4587092bf) | Nov 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [fcee866d9a](https://linux-hardware.org/?probe=fcee866d9a) | Oct 31, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| HP            | Compaq 15                   | Notebook    | [83fab35dec](https://linux-hardware.org/?probe=83fab35dec) | Oct 26, 2023 |
| HP            | Compaq 15                   | Notebook    | [41ada9e77d](https://linux-hardware.org/?probe=41ada9e77d) | Oct 26, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [eb2ef3f8d5](https://linux-hardware.org/?probe=eb2ef3f8d5) | Oct 24, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [7991ecc4ee](https://linux-hardware.org/?probe=7991ecc4ee) | Oct 22, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [67e51cbac1](https://linux-hardware.org/?probe=67e51cbac1) | Oct 19, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [7a11989cb0](https://linux-hardware.org/?probe=7a11989cb0) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1ce86e7416](https://linux-hardware.org/?probe=1ce86e7416) | Oct 08, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [fc4a10d945](https://linux-hardware.org/?probe=fc4a10d945) | Oct 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b54af646b7](https://linux-hardware.org/?probe=b54af646b7) | Oct 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [96c6a8d31e](https://linux-hardware.org/?probe=96c6a8d31e) | Oct 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [3672418d7a](https://linux-hardware.org/?probe=3672418d7a) | Oct 02, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [1d3c36ccf4](https://linux-hardware.org/?probe=1d3c36ccf4) | Sep 25, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [e98b118b85](https://linux-hardware.org/?probe=e98b118b85) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [6903c7fc50](https://linux-hardware.org/?probe=6903c7fc50) | Sep 18, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [b5b49fefb3](https://linux-hardware.org/?probe=b5b49fefb3) | Sep 09, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [eaf6dbaf3e](https://linux-hardware.org/?probe=eaf6dbaf3e) | Sep 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [a404e86063](https://linux-hardware.org/?probe=a404e86063) | Sep 08, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [daa7101bf4](https://linux-hardware.org/?probe=daa7101bf4) | Sep 07, 2023 |
| Unknown       | TBYF-1014WIN32              | Notebook    | [11ef48e0c0](https://linux-hardware.org/?probe=11ef48e0c0) | Sep 06, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| HP            | 18E9                        | Desktop     | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| MSI           | CR610M                      | Notebook    | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Dell          | Latitude 7430               | Notebook    | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| Intel         | H61                         | Desktop     | [4d6bf88f48](https://linux-hardware.org/?probe=4d6bf88f48) | Aug 21, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [439b66555d](https://linux-hardware.org/?probe=439b66555d) | Aug 17, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [e11ae0d2b7](https://linux-hardware.org/?probe=e11ae0d2b7) | Aug 17, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [e51e841817](https://linux-hardware.org/?probe=e51e841817) | Jul 31, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a79ddb19](https://linux-hardware.org/?probe=a0a79ddb19) | Jul 27, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [99dadfd3f5](https://linux-hardware.org/?probe=99dadfd3f5) | Jul 21, 2023 |
| MSI           | 2A9C                        | Desktop     | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e6c5dadeef](https://linux-hardware.org/?probe=e6c5dadeef) | Jul 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b72c043646](https://linux-hardware.org/?probe=b72c043646) | Jul 13, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c816d8f1b](https://linux-hardware.org/?probe=8c816d8f1b) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [355ccda3d5](https://linux-hardware.org/?probe=355ccda3d5) | Jul 05, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [354dd05c7f](https://linux-hardware.org/?probe=354dd05c7f) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [b465607eea](https://linux-hardware.org/?probe=b465607eea) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [0668932749](https://linux-hardware.org/?probe=0668932749) | Jun 30, 2023 |
| Lenovo        | ThinkPad W520 428425G       | Notebook    | [48d9a1b9fc](https://linux-hardware.org/?probe=48d9a1b9fc) | Jun 26, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [46ed210eb0](https://linux-hardware.org/?probe=46ed210eb0) | Jun 26, 2023 |
| Lenovo        | ThinkPad W520 428425G       | Notebook    | [813d5adfd5](https://linux-hardware.org/?probe=813d5adfd5) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| HP            | 2B34                        | Desktop     | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | Notebook    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [d1d1ef644d](https://linux-hardware.org/?probe=d1d1ef644d) | May 15, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2d5e375a3d](https://linux-hardware.org/?probe=2d5e375a3d) | May 09, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e68f2bc46e](https://linux-hardware.org/?probe=e68f2bc46e) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [98ffa037d9](https://linux-hardware.org/?probe=98ffa037d9) | Apr 24, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [0d45b24479](https://linux-hardware.org/?probe=0d45b24479) | Apr 23, 2023 |
| Toshiba       | Satellite Pro A100          | Notebook    | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [48b2d021fa](https://linux-hardware.org/?probe=48b2d021fa) | Apr 17, 2023 |
| MSI           | G41M-P26                    | Desktop     | [80c102169c](https://linux-hardware.org/?probe=80c102169c) | Apr 16, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [065b7d4c01](https://linux-hardware.org/?probe=065b7d4c01) | Apr 13, 2023 |
| MSI           | G41M-P26                    | Desktop     | [5b6831f7fc](https://linux-hardware.org/?probe=5b6831f7fc) | Apr 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a6e4c91ee0](https://linux-hardware.org/?probe=a6e4c91ee0) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [e27fc333c6](https://linux-hardware.org/?probe=e27fc333c6) | Apr 05, 2023 |
| ASUSTek       | M5401WUA                    | All in one  | [f6285d1100](https://linux-hardware.org/?probe=f6285d1100) | Apr 03, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [f4b76d1e01](https://linux-hardware.org/?probe=f4b76d1e01) | Apr 03, 2023 |
| Toshiba       | Satellite C55-B             | Notebook    | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ee66bc49a5](https://linux-hardware.org/?probe=ee66bc49a5) | Apr 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [267dad60ba](https://linux-hardware.org/?probe=267dad60ba) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f6b6b24623](https://linux-hardware.org/?probe=f6b6b24623) | Feb 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6b5f9db086](https://linux-hardware.org/?probe=6b5f9db086) | Feb 21, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [fd2b985f41](https://linux-hardware.org/?probe=fd2b985f41) | Feb 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| HP            | Notebook                    | Notebook    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [515525584c](https://linux-hardware.org/?probe=515525584c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [46981444b1](https://linux-hardware.org/?probe=46981444b1) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| ASRock        | H81M-GL                     | Desktop     | [059a818847](https://linux-hardware.org/?probe=059a818847) | Feb 09, 2023 |
| Dell          | Latitude E7470              | Notebook    | [5c8d26c4ff](https://linux-hardware.org/?probe=5c8d26c4ff) | Feb 05, 2023 |
| Dell          | Latitude E7470              | Notebook    | [d68227808b](https://linux-hardware.org/?probe=d68227808b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [1f55ca148f](https://linux-hardware.org/?probe=1f55ca148f) | Jan 30, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4042b92ee1](https://linux-hardware.org/?probe=4042b92ee1) | Jan 29, 2023 |
| HP            | 18E7                        | Desktop     | [01cbafc241](https://linux-hardware.org/?probe=01cbafc241) | Jan 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f1f0543123](https://linux-hardware.org/?probe=f1f0543123) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5169fb5013](https://linux-hardware.org/?probe=5169fb5013) | Jan 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [f0ed3b4989](https://linux-hardware.org/?probe=f0ed3b4989) | Jan 14, 2023 |
| MSI           | H270-A PRO                  | Desktop     | [f150327257](https://linux-hardware.org/?probe=f150327257) | Jan 14, 2023 |
| Acer          | Calpella                    | Notebook    | [108843a25a](https://linux-hardware.org/?probe=108843a25a) | Jan 14, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9cc37ff271](https://linux-hardware.org/?probe=9cc37ff271) | Jan 09, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Sony          | VGN-NS10J_S                 | Notebook    | [3789038010](https://linux-hardware.org/?probe=3789038010) | Jan 04, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [c2d592a9e5](https://linux-hardware.org/?probe=c2d592a9e5) | Dec 30, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [de5dc0c3ea](https://linux-hardware.org/?probe=de5dc0c3ea) | Dec 17, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [3b340e6b29](https://linux-hardware.org/?probe=3b340e6b29) | Dec 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [ca043cff45](https://linux-hardware.org/?probe=ca043cff45) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [08d7f00868](https://linux-hardware.org/?probe=08d7f00868) | Nov 24, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [da02cb82bf](https://linux-hardware.org/?probe=da02cb82bf) | Nov 23, 2022 |
| ASUSTek       | S300CA                      | Notebook    | [3efc297b44](https://linux-hardware.org/?probe=3efc297b44) | Nov 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [cae1dbbb12](https://linux-hardware.org/?probe=cae1dbbb12) | Nov 12, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [64c65685da](https://linux-hardware.org/?probe=64c65685da) | Nov 03, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5dbeb8f7dd](https://linux-hardware.org/?probe=5dbeb8f7dd) | Nov 03, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6c979bdf58](https://linux-hardware.org/?probe=6c979bdf58) | Oct 27, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4727244665](https://linux-hardware.org/?probe=4727244665) | Oct 18, 2022 |
| ECS           | G41T-M7                     | Desktop     | [3abe70653e](https://linux-hardware.org/?probe=3abe70653e) | Oct 16, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Dell          | Precision M4800             | Notebook    | [be05dcbe15](https://linux-hardware.org/?probe=be05dcbe15) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [7d65aefb93](https://linux-hardware.org/?probe=7d65aefb93) | Oct 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [719ac47bc6](https://linux-hardware.org/?probe=719ac47bc6) | Oct 06, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cd06f54882](https://linux-hardware.org/?probe=cd06f54882) | Sep 30, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [21d9eb0a71](https://linux-hardware.org/?probe=21d9eb0a71) | Sep 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | Notebook    | [b484febc13](https://linux-hardware.org/?probe=b484febc13) | Sep 17, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e61fe6932b](https://linux-hardware.org/?probe=e61fe6932b) | Sep 13, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [3b1c07d561](https://linux-hardware.org/?probe=3b1c07d561) | Sep 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [26c9be116e](https://linux-hardware.org/?probe=26c9be116e) | Aug 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1f4f742288](https://linux-hardware.org/?probe=1f4f742288) | Aug 23, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [708f9572ad](https://linux-hardware.org/?probe=708f9572ad) | Jul 26, 2022 |
| ECS           | G41T-M16                    | Desktop     | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [4eadb7ee17](https://linux-hardware.org/?probe=4eadb7ee17) | Jun 19, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [fd9f1b2ef6](https://linux-hardware.org/?probe=fd9f1b2ef6) | Jun 17, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [149eb0bab7](https://linux-hardware.org/?probe=149eb0bab7) | Jun 14, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9ff02a8c0c](https://linux-hardware.org/?probe=9ff02a8c0c) | Jun 12, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9273aa4844](https://linux-hardware.org/?probe=9273aa4844) | Jun 12, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [15532b1663](https://linux-hardware.org/?probe=15532b1663) | Jun 07, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [0dd5791ff8](https://linux-hardware.org/?probe=0dd5791ff8) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1b7a237b9b](https://linux-hardware.org/?probe=1b7a237b9b) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| HP            | ProBook 4720s               | Notebook    | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| HP            | ProBook 4720s               | Notebook    | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [95d53f5fc0](https://linux-hardware.org/?probe=95d53f5fc0) | Mar 31, 2022 |
| Dell          | 07N90W A02                  | Desktop     | [4fd59735d6](https://linux-hardware.org/?probe=4fd59735d6) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [698654a73f](https://linux-hardware.org/?probe=698654a73f) | Mar 26, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [00e72ee0ce](https://linux-hardware.org/?probe=00e72ee0ce) | Mar 04, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [eb4abb6e15](https://linux-hardware.org/?probe=eb4abb6e15) | Mar 02, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4110664747](https://linux-hardware.org/?probe=4110664747) | Mar 02, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [9d0a21adb1](https://linux-hardware.org/?probe=9d0a21adb1) | Mar 02, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [7bdf3a8998](https://linux-hardware.org/?probe=7bdf3a8998) | Feb 27, 2022 |
| HP            | 630                         | Notebook    | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [214381cf00](https://linux-hardware.org/?probe=214381cf00) | Feb 16, 2022 |
| Lenovo        | 0B98417 PRO                 | Desktop     | [6e5fa50531](https://linux-hardware.org/?probe=6e5fa50531) | Feb 13, 2022 |
| Intel         | H55                         | Desktop     | [1b1b5c3ed8](https://linux-hardware.org/?probe=1b1b5c3ed8) | Feb 12, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f5b85f478](https://linux-hardware.org/?probe=3f5b85f478) | Feb 07, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03d4a4af15](https://linux-hardware.org/?probe=03d4a4af15) | Feb 05, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| MSI           | H61M-S20                    | Desktop     | [7d0384b2d2](https://linux-hardware.org/?probe=7d0384b2d2) | Jan 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [0d6dacc5dc](https://linux-hardware.org/?probe=0d6dacc5dc) | Jan 20, 2022 |
| ECS           | H61H2-M4                    | Desktop     | [2995a79728](https://linux-hardware.org/?probe=2995a79728) | Jan 07, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Unknown       | X79                         | Desktop     | [ec1620ee82](https://linux-hardware.org/?probe=ec1620ee82) | Jan 01, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [33df9edd07](https://linux-hardware.org/?probe=33df9edd07) | Dec 25, 2021 |
| LDLC          | Mercure MH                  | Notebook    | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Sony          | VGN-AW21M_H                 | Notebook    | [b4cf74ec7d](https://linux-hardware.org/?probe=b4cf74ec7d) | Dec 23, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | X555LAB                     | Notebook    | [c07bccb6c7](https://linux-hardware.org/?probe=c07bccb6c7) | Dec 07, 2021 |
| Sony          | SVF1531GSFB                 | Notebook    | [fb251b93e9](https://linux-hardware.org/?probe=fb251b93e9) | Dec 04, 2021 |
| MSI           | H61M-S20                    | Desktop     | [5e73200702](https://linux-hardware.org/?probe=5e73200702) | Dec 02, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Foxconn       | 17A0                        | Desktop     | [0fc17817a1](https://linux-hardware.org/?probe=0fc17817a1) | Nov 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e26d674874](https://linux-hardware.org/?probe=e26d674874) | Nov 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [233d576651](https://linux-hardware.org/?probe=233d576651) | Nov 12, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [0862dc626b](https://linux-hardware.org/?probe=0862dc626b) | Oct 29, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [545b983e7c](https://linux-hardware.org/?probe=545b983e7c) | Oct 22, 2021 |
| Unknown       | G41 Series V10              | Desktop     | [ce791f779f](https://linux-hardware.org/?probe=ce791f779f) | Oct 21, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [ebd6264587](https://linux-hardware.org/?probe=ebd6264587) | Oct 19, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [9855c138d4](https://linux-hardware.org/?probe=9855c138d4) | Oct 11, 2021 |
| MSI           | H61M-S20                    | Desktop     | [9669908158](https://linux-hardware.org/?probe=9669908158) | Sep 29, 2021 |
| MSI           | H61M-S20                    | Desktop     | [481ecaa854](https://linux-hardware.org/?probe=481ecaa854) | Sep 28, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [d986a2e532](https://linux-hardware.org/?probe=d986a2e532) | Sep 26, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3b43d9b42f](https://linux-hardware.org/?probe=3b43d9b42f) | Sep 22, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [a31437072c](https://linux-hardware.org/?probe=a31437072c) | Sep 20, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [1c77028990](https://linux-hardware.org/?probe=1c77028990) | Sep 18, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [b740654686](https://linux-hardware.org/?probe=b740654686) | Sep 17, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [e817658118](https://linux-hardware.org/?probe=e817658118) | Sep 10, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [b8661880d2](https://linux-hardware.org/?probe=b8661880d2) | Sep 07, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [95d654f778](https://linux-hardware.org/?probe=95d654f778) | Sep 04, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [78886ef280](https://linux-hardware.org/?probe=78886ef280) | Aug 31, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [82aceb2458](https://linux-hardware.org/?probe=82aceb2458) | Aug 30, 2021 |
| HP            | 15                          | Notebook    | [5520042e14](https://linux-hardware.org/?probe=5520042e14) | Aug 28, 2021 |
| HP            | 15                          | Notebook    | [cc4e936b38](https://linux-hardware.org/?probe=cc4e936b38) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8a71545b54](https://linux-hardware.org/?probe=8a71545b54) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [297e2e187c](https://linux-hardware.org/?probe=297e2e187c) | Aug 25, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [b1490652d3](https://linux-hardware.org/?probe=b1490652d3) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [47ed88595b](https://linux-hardware.org/?probe=47ed88595b) | Aug 20, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [cf362e966f](https://linux-hardware.org/?probe=cf362e966f) | Aug 19, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [795edc5779](https://linux-hardware.org/?probe=795edc5779) | Aug 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [eb029acad6](https://linux-hardware.org/?probe=eb029acad6) | Aug 12, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [84199b59aa](https://linux-hardware.org/?probe=84199b59aa) | Aug 10, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [a4be1b3322](https://linux-hardware.org/?probe=a4be1b3322) | Aug 10, 2021 |
| MSI           | CR610M                      | Notebook    | [68759b0315](https://linux-hardware.org/?probe=68759b0315) | Aug 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [007cd499bf](https://linux-hardware.org/?probe=007cd499bf) | Aug 06, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [405dddebf5](https://linux-hardware.org/?probe=405dddebf5) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| Dell          | Latitude 7380               | Notebook    | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| Dell          | 0WG864                      | Desktop     | [2e28996126](https://linux-hardware.org/?probe=2e28996126) | Jul 28, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [185f27f184](https://linux-hardware.org/?probe=185f27f184) | Jul 22, 2021 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [cf7ebc455f](https://linux-hardware.org/?probe=cf7ebc455f) | Jul 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [d8fd7fe06d](https://linux-hardware.org/?probe=d8fd7fe06d) | Jul 20, 2021 |
| Intel         | H55                         | Desktop     | [47c7c454ac](https://linux-hardware.org/?probe=47c7c454ac) | Jul 09, 2021 |
| Intel         | H55                         | Desktop     | [9e4504d3a3](https://linux-hardware.org/?probe=9e4504d3a3) | Jul 09, 2021 |
| Dell          | Latitude 7480               | Notebook    | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| HP            | 2B34                        | Desktop     | [d2c91c450b](https://linux-hardware.org/?probe=d2c91c450b) | May 31, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| Toshiba       | Satellite C50-A539          | Notebook    | [c6c8ae87d9](https://linux-hardware.org/?probe=c6c8ae87d9) | May 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f54143a81d](https://linux-hardware.org/?probe=f54143a81d) | May 24, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [36b88b7391](https://linux-hardware.org/?probe=36b88b7391) | May 23, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [be3e7aa080](https://linux-hardware.org/?probe=be3e7aa080) | May 09, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0252beb838](https://linux-hardware.org/?probe=0252beb838) | May 04, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bd06d6bb56](https://linux-hardware.org/?probe=bd06d6bb56) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [861a11fe04](https://linux-hardware.org/?probe=861a11fe04) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [66faef6161](https://linux-hardware.org/?probe=66faef6161) | May 02, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [62fc21894d](https://linux-hardware.org/?probe=62fc21894d) | Apr 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [7a97f404a4](https://linux-hardware.org/?probe=7a97f404a4) | Apr 24, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [ba300d050b](https://linux-hardware.org/?probe=ba300d050b) | Apr 24, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [7a72fc45b4](https://linux-hardware.org/?probe=7a72fc45b4) | Apr 22, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [b46bb85400](https://linux-hardware.org/?probe=b46bb85400) | Apr 21, 2021 |
| Dell          | Latitude E7440              | Notebook    | [4acb0ea358](https://linux-hardware.org/?probe=4acb0ea358) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [a48b0c422f](https://linux-hardware.org/?probe=a48b0c422f) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [6fd83225c1](https://linux-hardware.org/?probe=6fd83225c1) | Apr 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [2953bef8d1](https://linux-hardware.org/?probe=2953bef8d1) | Apr 18, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [f3b2236c7a](https://linux-hardware.org/?probe=f3b2236c7a) | Apr 15, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [8e5a3a6e19](https://linux-hardware.org/?probe=8e5a3a6e19) | Apr 05, 2021 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [843dae0f43](https://linux-hardware.org/?probe=843dae0f43) | Apr 04, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [2df99824aa](https://linux-hardware.org/?probe=2df99824aa) | Apr 03, 2021 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [765ae993b9](https://linux-hardware.org/?probe=765ae993b9) | Mar 16, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [6408cdb8b2](https://linux-hardware.org/?probe=6408cdb8b2) | Mar 14, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [210d440087](https://linux-hardware.org/?probe=210d440087) | Mar 13, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [a9068d7ec4](https://linux-hardware.org/?probe=a9068d7ec4) | Mar 12, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [387b714e2f](https://linux-hardware.org/?probe=387b714e2f) | Mar 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [5f41497264](https://linux-hardware.org/?probe=5f41497264) | Mar 02, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5cf7ce91a7](https://linux-hardware.org/?probe=5cf7ce91a7) | Mar 01, 2021 |
| Acer          | Extensa 2508                | Notebook    | [7fb16dc91b](https://linux-hardware.org/?probe=7fb16dc91b) | Feb 28, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [0eb94c0487](https://linux-hardware.org/?probe=0eb94c0487) | Feb 26, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [5582abd577](https://linux-hardware.org/?probe=5582abd577) | Feb 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [7ec7f64225](https://linux-hardware.org/?probe=7ec7f64225) | Feb 20, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [35ca18e322](https://linux-hardware.org/?probe=35ca18e322) | Feb 18, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [67702a7546](https://linux-hardware.org/?probe=67702a7546) | Feb 17, 2021 |
| HP            | ProBook 4540s               | Notebook    | [f6618c225b](https://linux-hardware.org/?probe=f6618c225b) | Feb 16, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [c107fc9c40](https://linux-hardware.org/?probe=c107fc9c40) | Feb 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [74fb8b5b1d](https://linux-hardware.org/?probe=74fb8b5b1d) | Feb 14, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [da10465006](https://linux-hardware.org/?probe=da10465006) | Feb 08, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b050103b48](https://linux-hardware.org/?probe=b050103b48) | Feb 04, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [8c36c3c601](https://linux-hardware.org/?probe=8c36c3c601) | Feb 03, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [807a0ea003](https://linux-hardware.org/?probe=807a0ea003) | Jan 31, 2021 |
| Dell          | Precision M6600             | Notebook    | [3731eb952c](https://linux-hardware.org/?probe=3731eb952c) | Jan 29, 2021 |
| Acer          | Aspire V5-571               | Notebook    | [74f0d86e1e](https://linux-hardware.org/?probe=74f0d86e1e) | Jan 28, 2021 |
| Dell          | Precision M6600             | Notebook    | [105a9a66c3](https://linux-hardware.org/?probe=105a9a66c3) | Jan 23, 2021 |
| Dell          | Precision M6600             | Notebook    | [84d3a754fb](https://linux-hardware.org/?probe=84d3a754fb) | Jan 23, 2021 |
| Sony          | VPCEH2H1E                   | Notebook    | [891e9364e0](https://linux-hardware.org/?probe=891e9364e0) | Jan 14, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [9286a611a0](https://linux-hardware.org/?probe=9286a611a0) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [aae61a1ca3](https://linux-hardware.org/?probe=aae61a1ca3) | Dec 22, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ce37e65007](https://linux-hardware.org/?probe=ce37e65007) | Dec 21, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [cf12b04ead](https://linux-hardware.org/?probe=cf12b04ead) | Dec 21, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Unknown       | Unknown                     | Desktop     | [83507a1ac0](https://linux-hardware.org/?probe=83507a1ac0) | Dec 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [688a7e3a73](https://linux-hardware.org/?probe=688a7e3a73) | Dec 11, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [3bab146c4c](https://linux-hardware.org/?probe=3bab146c4c) | Dec 10, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [997a066f37](https://linux-hardware.org/?probe=997a066f37) | Dec 08, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [356e5f32f8](https://linux-hardware.org/?probe=356e5f32f8) | Dec 08, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8dec91d656](https://linux-hardware.org/?probe=8dec91d656) | Dec 01, 2020 |
| Dell          | Vostro 3500                 | Notebook    | [a76707659b](https://linux-hardware.org/?probe=a76707659b) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Gigabyte      | P61A-D3                     | Desktop     | [c547f76923](https://linux-hardware.org/?probe=c547f76923) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [cfbfec849d](https://linux-hardware.org/?probe=cfbfec849d) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [97d5763d6b](https://linux-hardware.org/?probe=97d5763d6b) | Nov 21, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [4ead657ec9](https://linux-hardware.org/?probe=4ead657ec9) | Nov 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a9f4ce29b9](https://linux-hardware.org/?probe=a9f4ce29b9) | Nov 15, 2020 |
| MSI           | G41M-P33 Combo              | Desktop     | [36ffd6debb](https://linux-hardware.org/?probe=36ffd6debb) | Nov 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [51b974180e](https://linux-hardware.org/?probe=51b974180e) | Nov 11, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [39251e283c](https://linux-hardware.org/?probe=39251e283c) | Oct 29, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [85e77f85c7](https://linux-hardware.org/?probe=85e77f85c7) | Oct 26, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [230a4dff71](https://linux-hardware.org/?probe=230a4dff71) | Oct 26, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e2bb03b7da](https://linux-hardware.org/?probe=e2bb03b7da) | Oct 23, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1425d1ebde](https://linux-hardware.org/?probe=1425d1ebde) | Oct 20, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [f1040f264c](https://linux-hardware.org/?probe=f1040f264c) | Oct 19, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [6a54c56b7a](https://linux-hardware.org/?probe=6a54c56b7a) | Oct 19, 2020 |
| HP            | ProBook 4540s               | Notebook    | [b369817417](https://linux-hardware.org/?probe=b369817417) | Oct 15, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [07077a7194](https://linux-hardware.org/?probe=07077a7194) | Oct 02, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [c35dfa149d](https://linux-hardware.org/?probe=c35dfa149d) | Sep 24, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1efd90cecb](https://linux-hardware.org/?probe=1efd90cecb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ebaa6b30e4](https://linux-hardware.org/?probe=ebaa6b30e4) | Sep 20, 2020 |
| HP            | 3397                        | Desktop     | [5232568c4a](https://linux-hardware.org/?probe=5232568c4a) | Sep 06, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [ec99eca757](https://linux-hardware.org/?probe=ec99eca757) | Sep 03, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [9ab161c8d7](https://linux-hardware.org/?probe=9ab161c8d7) | Sep 03, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [c4e5d02631](https://linux-hardware.org/?probe=c4e5d02631) | Sep 02, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Packard Be... | EasyNote LJ71               | Notebook    | [8848f3250d](https://linux-hardware.org/?probe=8848f3250d) | Aug 26, 2020 |
| HP            | 250 G4                      | Notebook    | [84bd70a658](https://linux-hardware.org/?probe=84bd70a658) | Jul 24, 2020 |
| HP            | 250 G4                      | Notebook    | [bb773c0ade](https://linux-hardware.org/?probe=bb773c0ade) | Jul 24, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [33e5e60503](https://linux-hardware.org/?probe=33e5e60503) | Jul 05, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [2273ab39c8](https://linux-hardware.org/?probe=2273ab39c8) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [734c3a7d86](https://linux-hardware.org/?probe=734c3a7d86) | Jun 22, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [9451ca4468](https://linux-hardware.org/?probe=9451ca4468) | Jun 22, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [cb406c43ec](https://linux-hardware.org/?probe=cb406c43ec) | Jun 21, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [46894e19cd](https://linux-hardware.org/?probe=46894e19cd) | Jun 21, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [81cf9fa7cf](https://linux-hardware.org/?probe=81cf9fa7cf) | Jun 11, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [b4ef87de2d](https://linux-hardware.org/?probe=b4ef87de2d) | Jun 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [c349a84934](https://linux-hardware.org/?probe=c349a84934) | Jun 02, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [0bc2465c23](https://linux-hardware.org/?probe=0bc2465c23) | May 25, 2020 |
| ASUSTek       | X541UV                      | Notebook    | [25108243d2](https://linux-hardware.org/?probe=25108243d2) | May 23, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [148b457da1](https://linux-hardware.org/?probe=148b457da1) | May 21, 2020 |
| Acer          | Extensa 2510                | Notebook    | [3c56d54986](https://linux-hardware.org/?probe=3c56d54986) | May 16, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [800fe450a7](https://linux-hardware.org/?probe=800fe450a7) | May 16, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [ad602ee170](https://linux-hardware.org/?probe=ad602ee170) | May 15, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [e1f352ee7e](https://linux-hardware.org/?probe=e1f352ee7e) | May 15, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [165c5e3446](https://linux-hardware.org/?probe=165c5e3446) | May 11, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9deb8b9d38](https://linux-hardware.org/?probe=9deb8b9d38) | May 01, 2020 |
| HP            | 15                          | Notebook    | [bc0640c653](https://linux-hardware.org/?probe=bc0640c653) | May 01, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [30806c27ea](https://linux-hardware.org/?probe=30806c27ea) | May 01, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [bc3989f5fd](https://linux-hardware.org/?probe=bc3989f5fd) | Apr 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [eb26a0a6dd](https://linux-hardware.org/?probe=eb26a0a6dd) | Apr 26, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [27139478ff](https://linux-hardware.org/?probe=27139478ff) | Apr 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1e23113365](https://linux-hardware.org/?probe=1e23113365) | Apr 19, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [a06745a31b](https://linux-hardware.org/?probe=a06745a31b) | Apr 19, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [300ccfbb68](https://linux-hardware.org/?probe=300ccfbb68) | Apr 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [32919aba44](https://linux-hardware.org/?probe=32919aba44) | Apr 08, 2020 |
| Sony          | SVE1713A6EW                 | Notebook    | [998290195d](https://linux-hardware.org/?probe=998290195d) | Mar 26, 2020 |
| Dell          | Precision M4600             | Notebook    | [995809b82f](https://linux-hardware.org/?probe=995809b82f) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [394723d5ec](https://linux-hardware.org/?probe=394723d5ec) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [9a4b04d5c6](https://linux-hardware.org/?probe=9a4b04d5c6) | Mar 10, 2020 |
| Dell          | Latitude 7490               | Notebook    | [3b7100f499](https://linux-hardware.org/?probe=3b7100f499) | Mar 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [b0b0e640c9](https://linux-hardware.org/?probe=b0b0e640c9) | Mar 01, 2020 |
| ECS           | G41T-M7                     | Desktop     | [39f9889169](https://linux-hardware.org/?probe=39f9889169) | Feb 26, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [46a39dcec8](https://linux-hardware.org/?probe=46a39dcec8) | Feb 10, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [52020faf85](https://linux-hardware.org/?probe=52020faf85) | Feb 05, 2020 |
| Dell          | 0F0TGN A00                  | Desktop     | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [ed6be60ed5](https://linux-hardware.org/?probe=ed6be60ed5) | Jan 07, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [b8f52696c7](https://linux-hardware.org/?probe=b8f52696c7) | Jan 07, 2020 |
| MSI           | H55M-E21                    | Desktop     | [a586112d3f](https://linux-hardware.org/?probe=a586112d3f) | Jan 01, 2020 |
| MSI           | H55M-E21                    | Desktop     | [71183fc4d2](https://linux-hardware.org/?probe=71183fc4d2) | Jan 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [170967f63e](https://linux-hardware.org/?probe=170967f63e) | Dec 31, 2019 |
| HP            | Pavilion 15                 | Notebook    | [e190391a64](https://linux-hardware.org/?probe=e190391a64) | Dec 10, 2019 |
| Lenovo        | ThinkPad T440 20B6S00200    | Notebook    | [8491772fe8](https://linux-hardware.org/?probe=8491772fe8) | Nov 19, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [3aed06c634](https://linux-hardware.org/?probe=3aed06c634) | Nov 05, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [80803b7502](https://linux-hardware.org/?probe=80803b7502) | Nov 05, 2019 |
| Sony          | VPCEJ2S1E                   | Notebook    | [909ce7c754](https://linux-hardware.org/?probe=909ce7c754) | Oct 25, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [742402d677](https://linux-hardware.org/?probe=742402d677) | Oct 01, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [bf938959f0](https://linux-hardware.org/?probe=bf938959f0) | Sep 30, 2019 |
| MSI           | Z77A-G45                    | Desktop     | [169e8e49d9](https://linux-hardware.org/?probe=169e8e49d9) | Sep 27, 2019 |
| HP            | 3397                        | Desktop     | [4367666d7a](https://linux-hardware.org/?probe=4367666d7a) | Sep 18, 2019 |
| HP            | 3397                        | Desktop     | [148b5948f9](https://linux-hardware.org/?probe=148b5948f9) | Sep 18, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Intel         | H55                         | Desktop     | [4529486397](https://linux-hardware.org/?probe=4529486397) | Jul 17, 2019 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [a9f20406b7](https://linux-hardware.org/?probe=a9f20406b7) | Jul 17, 2019 |
| Packard Be... | EasyNote TJ75               | Notebook    | [84742985cb](https://linux-hardware.org/?probe=84742985cb) | Apr 30, 2019 |
| Dell          | Latitude E5430 vPro         | Notebook    | [d88e664ef7](https://linux-hardware.org/?probe=d88e664ef7) | Apr 29, 2019 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [ec6b1b90c3](https://linux-hardware.org/?probe=ec6b1b90c3) | Apr 22, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5aeb26c21c](https://linux-hardware.org/?probe=5aeb26c21c) | Apr 10, 2019 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [92ce529502](https://linux-hardware.org/?probe=92ce529502) | Apr 10, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [53ac040baf](https://linux-hardware.org/?probe=53ac040baf) | Mar 28, 2019 |
| HP            | Notebook                    | Notebook    | [a94921a2ad](https://linux-hardware.org/?probe=a94921a2ad) | Dec 29, 2018 |
| WeiBu         | SIMM INT G-41D3 G1.0L       | Desktop     | [d8be685baa](https://linux-hardware.org/?probe=d8be685baa) | Dec 01, 2018 |
| Dell          | 0TP406                      | Desktop     | [620c3d413f](https://linux-hardware.org/?probe=620c3d413f) | Nov 28, 2018 |
| Dell          | 0TP406                      | Desktop     | [e33d9fb70d](https://linux-hardware.org/?probe=e33d9fb70d) | Nov 28, 2018 |
| Unknown       | Unknown                     | Desktop     | [1ee83f48b0](https://linux-hardware.org/?probe=1ee83f48b0) | Oct 14, 2018 |
| MSI           | H55-GD65                    | Desktop     | [6cbd59f0a9](https://linux-hardware.org/?probe=6cbd59f0a9) | Feb 27, 2018 |
| HP            | Pavilion Notebook           | Notebook    | [283bc29327](https://linux-hardware.org/?probe=283bc29327) | Dec 24, 2017 |
| HP            | Pavilion Notebook           | Notebook    | [af28f98e0a](https://linux-hardware.org/?probe=af28f98e0a) | Dec 07, 2017 |
| MSI           | 970A-G46                    | Desktop     | [693800273f](https://linux-hardware.org/?probe=693800273f) | Apr 01, 2017 |
| ASUSTek       | X540SA                      | Notebook    | [f76ee802c9](https://linux-hardware.org/?probe=f76ee802c9) | Mar 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 51        | 16.56%  |
| Ubuntu 18.04       | 20        | 6.49%   |
| Ubuntu 22.04       | 17        | 5.52%   |
| OpenMandriva 4.3   | 15        | 4.87%   |
| OpenMandriva 4.2   | 15        | 4.87%   |
| Zorin 16           | 8         | 2.6%    |
| OpenMandriva 23.03 | 7         | 2.27%   |
| Linux Mint 20.1    | 7         | 2.27%   |
| KDE neon 20.04     | 6         | 1.95%   |
| Pop!_OS 20.04      | 5         | 1.62%   |
| Arch               | 5         | 1.62%   |
| Ubuntu 21.04       | 4         | 1.3%    |
| Ubuntu 19.10       | 4         | 1.3%    |
| OpenMandriva 23.09 | 4         | 1.3%    |
| OpenMandriva 23.08 | 4         | 1.3%    |
| Manjaro            | 4         | 1.3%    |
| KDE neon 22.04     | 4         | 1.3%    |
| Fedora 37          | 4         | 1.3%    |
| Fedora 35          | 4         | 1.3%    |
| Debian 11          | 4         | 1.3%    |
| ArcoLinux Rolling  | 4         | 1.3%    |
| Xubuntu 20.04      | 3         | 0.97%   |
| Ubuntu 20.10       | 3         | 0.97%   |
| ROSA R11           | 3         | 0.97%   |
| ROSA R10           | 3         | 0.97%   |
| Pop!_OS 22.04      | 3         | 0.97%   |
| OpenMandriva 23.01 | 3         | 0.97%   |
| Linux Mint 20.2    | 3         | 0.97%   |
| Fedora 38          | 3         | 0.97%   |
| BlackPanther 18.1  | 3         | 0.97%   |
| Xubuntu 22.04      | 2         | 0.65%   |
| Ubuntu 21.10       | 2         | 0.65%   |
| Ubuntu 19.04       | 2         | 0.65%   |
| ROSA R8.1          | 2         | 0.65%   |
| Parrot 5.0         | 2         | 0.65%   |
| MX 23              | 2         | 0.65%   |
| Manjaro 20.1       | 2         | 0.65%   |
| Linux Mint 21      | 2         | 0.65%   |
| Kubuntu 20.04      | 2         | 0.65%   |
| Kali 2021.2        | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 102       | 34.46%  |
| OpenMandriva  | 46        | 15.54%  |
| Linux Mint    | 19        | 6.42%   |
| Fedora        | 16        | 5.41%   |
| Pop!_OS       | 11        | 3.72%   |
| KDE neon      | 10        | 3.38%   |
| Zorin         | 9         | 3.04%   |
| Debian        | 9         | 3.04%   |
| ROSA          | 8         | 2.7%    |
| Manjaro       | 8         | 2.7%    |
| Kali          | 7         | 2.36%   |
| Xubuntu       | 6         | 2.03%   |
| Arch          | 6         | 2.03%   |
| Parrot        | 5         | 1.69%   |
| ArcoLinux     | 4         | 1.35%   |
| MX            | 3         | 1.01%   |
| Kubuntu       | 3         | 1.01%   |
| BlackPanther  | 3         | 1.01%   |
| Ubuntu MATE   | 2         | 0.68%   |
| Peppermint    | 2         | 0.68%   |
| Xero          | 1         | 0.34%   |
| UbuntuDDE     | 1         | 0.34%   |
| Ubuntu Unity  | 1         | 0.34%   |
| Ubuntu Budgie | 1         | 0.34%   |
| Skygate       | 1         | 0.34%   |
| Pear OS       | 1         | 0.34%   |
| openSUSE      | 1         | 0.34%   |
| Gentoo        | 1         | 0.34%   |
| Garuda Linux  | 1         | 0.34%   |
| Endless       | 1         | 0.34%   |
| EndeavourOS   | 1         | 0.34%   |
| Deepin        | 1         | 0.34%   |
| Clear Linux   | 1         | 0.34%   |
| CentOS        | 1         | 0.34%   |
| Athena        | 1         | 0.34%   |
| Artix         | 1         | 0.34%   |
| ArchLabs      | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 15        | 4.59%   |
| 5.10.14-desktop-1omv4002 | 15        | 4.59%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.83%   |
| 5.4.0-42-generic         | 5         | 1.53%   |
| 5.15.0-47-generic        | 5         | 1.53%   |
| 5.8.0-50-generic         | 4         | 1.22%   |
| 5.4.0-72-generic         | 4         | 1.22%   |
| 5.4.0-54-generic         | 4         | 1.22%   |
| 5.4.0-29-generic         | 4         | 1.22%   |
| 5.0.0-37-generic         | 4         | 1.22%   |
| 6.2.0-33-generic         | 3         | 0.92%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.92%   |
| 6.1.0-13-amd64           | 3         | 0.92%   |
| 5.4.0-65-generic         | 3         | 0.92%   |
| 5.4.0-56-generic         | 3         | 0.92%   |
| 5.4.0-52-generic         | 3         | 0.92%   |
| 5.3.0-46-generic         | 3         | 0.92%   |
| 5.15.0-86-generic        | 3         | 0.92%   |
| 5.15.0-58-generic        | 3         | 0.92%   |
| 5.15.0-56-generic        | 3         | 0.92%   |
| 5.13.0-30-generic        | 3         | 0.92%   |
| 5.11.0-38-generic        | 3         | 0.92%   |
| 5.11.0-27-generic        | 3         | 0.92%   |
| 6.5.5-desktop-1omv2390   | 2         | 0.61%   |
| 6.5.0-desktop-1omv2390   | 2         | 0.61%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.61%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.61%   |
| 6.0.7-301.fc37.x86_64    | 2         | 0.61%   |
| 5.8.0-44-generic         | 2         | 0.61%   |
| 5.4.0-88-generic         | 2         | 0.61%   |
| 5.4.0-81-generic         | 2         | 0.61%   |
| 5.4.0-80-generic         | 2         | 0.61%   |
| 5.4.0-7625-generic       | 2         | 0.61%   |
| 5.4.0-48-generic         | 2         | 0.61%   |
| 5.4.0-33-generic         | 2         | 0.61%   |
| 5.3.0-40-generic         | 2         | 0.61%   |
| 5.19.0-40-generic        | 2         | 0.61%   |
| 5.15.0-83-generic        | 2         | 0.61%   |
| 5.15.0-60-generic        | 2         | 0.61%   |
| 5.15.0-48-generic        | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 16.08%  |
| 5.15.0  | 29        | 9.32%   |
| 5.11.0  | 16        | 5.14%   |
| 5.16.7  | 15        | 4.82%   |
| 5.10.14 | 15        | 4.82%   |
| 5.8.0   | 14        | 4.5%    |
| 4.15.0  | 13        | 4.18%   |
| 5.3.0   | 10        | 3.22%   |
| 5.0.0   | 10        | 3.22%   |
| 5.13.0  | 9         | 2.89%   |
| 5.10.0  | 8         | 2.57%   |
| 6.2.6   | 7         | 2.25%   |
| 6.1.0   | 6         | 1.93%   |
| 6.2.0   | 5         | 1.61%   |
| 5.19.0  | 5         | 1.61%   |
| 6.1.1   | 3         | 0.96%   |
| 4.18.16 | 3         | 0.96%   |
| 6.5.5   | 2         | 0.64%   |
| 6.5.0   | 2         | 0.64%   |
| 6.4.8   | 2         | 0.64%   |
| 6.4.11  | 2         | 0.64%   |
| 6.2.8   | 2         | 0.64%   |
| 6.1.12  | 2         | 0.64%   |
| 6.0.7   | 2         | 0.64%   |
| 5.18.12 | 2         | 0.64%   |
| 5.15.7  | 2         | 0.64%   |
| 5.14.0  | 2         | 0.64%   |
| 4.9.60  | 2         | 0.64%   |
| 4.4.0   | 2         | 0.64%   |
| 4.19.0  | 2         | 0.64%   |
| 6.5.6   | 1         | 0.32%   |
| 6.5.3   | 1         | 0.32%   |
| 6.4.9   | 1         | 0.32%   |
| 6.4.6   | 1         | 0.32%   |
| 6.4.4   | 1         | 0.32%   |
| 6.4.14  | 1         | 0.32%   |
| 6.3.4   | 1         | 0.32%   |
| 6.3.0   | 1         | 0.32%   |
| 6.2.9   | 1         | 0.32%   |
| 6.2.14  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 17.1%   |
| 5.15    | 39        | 12.58%  |
| 5.10    | 28        | 9.03%   |
| 5.11    | 18        | 5.81%   |
| 6.2     | 17        | 5.48%   |
| 5.16    | 17        | 5.48%   |
| 6.1     | 15        | 4.84%   |
| 5.8     | 15        | 4.84%   |
| 4.15    | 13        | 4.19%   |
| 5.3     | 10        | 3.23%   |
| 5.19    | 10        | 3.23%   |
| 5.13    | 10        | 3.23%   |
| 5.0     | 10        | 3.23%   |
| 6.4     | 8         | 2.58%   |
| 6.5     | 6         | 1.94%   |
| 6.0     | 5         | 1.61%   |
| 5.14    | 4         | 1.29%   |
| 4.9     | 4         | 1.29%   |
| 4.19    | 4         | 1.29%   |
| 4.18    | 4         | 1.29%   |
| 5.18    | 3         | 0.97%   |
| 5.17    | 3         | 0.97%   |
| 5.12    | 3         | 0.97%   |
| 6.3     | 2         | 0.65%   |
| 5.7     | 2         | 0.65%   |
| 5.6     | 2         | 0.65%   |
| 4.4     | 2         | 0.65%   |
| 5.9     | 1         | 0.32%   |
| 4.1     | 1         | 0.32%   |
| 3.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 265       | 96.72%  |
| i686   | 8         | 2.92%   |
| armv7l | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 129       | 44.48%  |
| KDE5             | 70        | 24.14%  |
| Unknown          | 24        | 8.28%   |
| XFCE             | 20        | 6.9%    |
| X-Cinnamon       | 11        | 3.79%   |
| MATE             | 9         | 3.1%    |
| KDE4             | 5         | 1.72%   |
| KDE              | 5         | 1.72%   |
| Cinnamon         | 4         | 1.38%   |
| LXQt             | 2         | 0.69%   |
| i3               | 2         | 0.69%   |
| Unity            | 1         | 0.34%   |
| Peppermint       | 1         | 0.34%   |
| LXDE             | 1         | 0.34%   |
| lightdm-xsession | 1         | 0.34%   |
| GNOME Flashback  | 1         | 0.34%   |
| fvwm             | 1         | 0.34%   |
| Deepin           | 1         | 0.34%   |
| DDE              | 1         | 0.34%   |
| Budgie           | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 216       | 76.87%  |
| Wayland | 51        | 18.15%  |
| Unknown | 12        | 4.27%   |
| Tty     | 2         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 44.64%  |
| SDDM    | 60        | 20.76%  |
| LightDM | 30        | 10.38%  |
| GDM3    | 29        | 10.03%  |
| GDM     | 28        | 9.69%   |
| TDM     | 7         | 2.42%   |
| KDM     | 5         | 1.73%   |
| SLiM    | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 121       | 42.31%  |
| fr_FR       | 108       | 37.76%  |
| Unknown     | 26        | 9.09%   |
| en_GB       | 12        | 4.2%    |
| C           | 6         | 2.1%    |
| ar_DZ       | 6         | 2.1%    |
| fr_DZ       | 2         | 0.7%    |
| fr_BE       | 2         | 0.7%    |
| ar_EG       | 2         | 0.7%    |
| en-US-UTF-8 | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 187       | 66.79%  |
| EFI  | 93        | 33.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 207       | 72.13%  |
| Overlay | 40        | 13.94%  |
| Btrfs   | 23        | 8.01%   |
| Unknown | 9         | 3.14%   |
| Tmpfs   | 3         | 1.05%   |
| Ext2    | 3         | 1.05%   |
| Xfs     | 1         | 0.35%   |
| Ext3    | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 145       | 51.42%  |
| GPT     | 77        | 27.3%   |
| MBR     | 60        | 21.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 223       | 78.52%  |
| Yes       | 61        | 21.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 52.5%   |
| Yes       | 133       | 47.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 47        | 17.15%  |
| Hewlett-Packard     | 40        | 14.6%   |
| ASUSTek Computer    | 31        | 11.31%  |
| Lenovo              | 29        | 10.58%  |
| MSI                 | 19        | 6.93%   |
| Gigabyte Technology | 16        | 5.84%   |
| Acer                | 13        | 4.74%   |
| Toshiba             | 11        | 4.01%   |
| Unknown             | 10        | 3.65%   |
| Foxconn             | 8         | 2.92%   |
| ECS                 | 8         | 2.92%   |
| Sony                | 7         | 2.55%   |
| Apple               | 5         | 1.82%   |
| Intel               | 4         | 1.46%   |
| Samsung Electronics | 3         | 1.09%   |
| Packard Bell        | 3         | 1.09%   |
| Biostar             | 3         | 1.09%   |
| ASRock              | 3         | 1.09%   |
| Fujitsu             | 2         | 0.73%   |
| Wistron             | 1         | 0.36%   |
| WeiBu               | 1         | 0.36%   |
| UNOWHY              | 1         | 0.36%   |
| sunxi               | 1         | 0.36%   |
| Pegatron            | 1         | 0.36%   |
| Notebook            | 1         | 0.36%   |
| Microsoft           | 1         | 0.36%   |
| LORD ELECTRONICS    | 1         | 0.36%   |
| LDLC                | 1         | 0.36%   |
| HUAWEI              | 1         | 0.36%   |
| eMachines           | 1         | 0.36%   |
| AMI                 | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 10        | 3.65%   |
| ASUS UL80VT                   | 6         | 2.19%   |
| Toshiba Satellite C55-B       | 4         | 1.46%   |
| Dell Inspiron 15-3567         | 4         | 1.46%   |
| Intel H55                     | 3         | 1.09%   |
| HP Pavilion 15                | 3         | 1.09%   |
| HP Notebook                   | 3         | 1.09%   |
| HP 280 G1 MT                  | 3         | 1.09%   |
| Gigabyte H61M-S2PV            | 3         | 1.09%   |
| Foxconn H61MXL/H61MXL-K       | 3         | 1.09%   |
| ECS G41T-M7                   | 3         | 1.09%   |
| Dell Inspiron N5110           | 3         | 1.09%   |
| Dell Inspiron 3542            | 3         | 1.09%   |
| MSI MS-7758                   | 2         | 0.73%   |
| MSI MS-7636                   | 2         | 0.73%   |
| MSI MS-7592                   | 2         | 0.73%   |
| Lenovo IdeaPad 300-15ISK 80Q7 | 2         | 0.73%   |
| Lenovo G560 20042             | 2         | 0.73%   |
| Lenovo G50-30 80G0            | 2         | 0.73%   |
| Lenovo B50-70 20384           | 2         | 0.73%   |
| HP ProBook 4540s              | 2         | 0.73%   |
| HP 15                         | 2         | 0.73%   |
| Gigabyte B85M-DS3H-A          | 2         | 0.73%   |
| ECS H61H2-MV                  | 2         | 0.73%   |
| Dell Latitude E7440           | 2         | 0.73%   |
| Dell Latitude E5430 vPro      | 2         | 0.73%   |
| Dell Latitude 7480            | 2         | 0.73%   |
| Dell Latitude 5480            | 2         | 0.73%   |
| Biostar P4M89-M7B             | 2         | 0.73%   |
| ASUS H61M-K                   | 2         | 0.73%   |
| ASUS All Series               | 2         | 0.73%   |
| Acer Aspire 5738              | 2         | 0.73%   |
| Wistron ProLiant ML110 G5     | 1         | 0.36%   |
| WeiBu SIMM INT G-41D3 G1.0L   | 1         | 0.36%   |
| UNOWHY Y13G012S4EI            | 1         | 0.36%   |
| Toshiba Satellite Pro A100    | 1         | 0.36%   |
| Toshiba Satellite C850-A979   | 1         | 0.36%   |
| Toshiba Satellite C50-A560    | 1         | 0.36%   |
| Toshiba Satellite C50-A545    | 1         | 0.36%   |
| Toshiba Satellite C50-A539    | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 17        | 6.2%    |
| Dell Inspiron         | 17        | 6.2%    |
| Acer Aspire           | 10        | 3.65%   |
| Unknown               | 10        | 3.65%   |
| Toshiba Satellite     | 9         | 3.28%   |
| Lenovo ThinkPad       | 9         | 3.28%   |
| HP ProBook            | 9         | 3.28%   |
| HP Pavilion           | 6         | 2.19%   |
| ASUS UL80VT           | 6         | 2.19%   |
| Lenovo IdeaPad        | 5         | 1.82%   |
| HP EliteBook          | 5         | 1.82%   |
| Dell Vostro           | 4         | 1.46%   |
| Intel H55             | 3         | 1.09%   |
| HP Notebook           | 3         | 1.09%   |
| HP 280                | 3         | 1.09%   |
| Gigabyte H61M-S2PV    | 3         | 1.09%   |
| Foxconn H61MXL        | 3         | 1.09%   |
| ECS G41T-M7           | 3         | 1.09%   |
| Dell Precision        | 3         | 1.09%   |
| Dell OptiPlex         | 3         | 1.09%   |
| Toshiba PORTEGE       | 2         | 0.73%   |
| Packard Bell EasyNote | 2         | 0.73%   |
| MSI MS-7758           | 2         | 0.73%   |
| MSI MS-7636           | 2         | 0.73%   |
| MSI MS-7592           | 2         | 0.73%   |
| Lenovo G580           | 2         | 0.73%   |
| Lenovo G560           | 2         | 0.73%   |
| Lenovo G50-30         | 2         | 0.73%   |
| Lenovo B50-70         | 2         | 0.73%   |
| HP ProDesk            | 2         | 0.73%   |
| HP Laptop             | 2         | 0.73%   |
| HP Compaq             | 2         | 0.73%   |
| HP 15                 | 2         | 0.73%   |
| Gigabyte B85M-DS3H-A  | 2         | 0.73%   |
| Fujitsu LIFEBOOK      | 2         | 0.73%   |
| ECS H61H2-MV          | 2         | 0.73%   |
| Biostar P4M89-M7B     | 2         | 0.73%   |
| ASUS TUF              | 2         | 0.73%   |
| ASUS PRIME            | 2         | 0.73%   |
| ASUS H61M-K           | 2         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 44        | 16.06%  |
| 2014    | 34        | 12.41%  |
| 2013    | 32        | 11.68%  |
| 2011    | 26        | 9.49%   |
| 2015    | 20        | 7.3%    |
| 2016    | 19        | 6.93%   |
| 2009    | 19        | 6.93%   |
| 2017    | 17        | 6.2%    |
| 2010    | 16        | 5.84%   |
| 2018    | 14        | 5.11%   |
| 2019    | 7         | 2.55%   |
| 2021    | 5         | 1.82%   |
| 2020    | 5         | 1.82%   |
| 2008    | 5         | 1.82%   |
| 2007    | 5         | 1.82%   |
| 2022    | 2         | 0.73%   |
| 2006    | 2         | 0.73%   |
| 2023    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 166       | 60.58%  |
| Desktop        | 101       | 36.86%  |
| All in one     | 3         | 1.09%   |
| Tablet         | 2         | 0.73%   |
| System on chip | 1         | 0.36%   |
| Convertible    | 1         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 268       | 97.45%  |
| Enabled  | 7         | 2.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 274       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 95        | 33.93%  |
| 4.01-8.0    | 71        | 25.36%  |
| 8.01-16.0   | 54        | 19.29%  |
| 1.01-2.0    | 22        | 7.86%   |
| 16.01-24.0  | 18        | 6.43%   |
| 2.01-3.0    | 8         | 2.86%   |
| 32.01-64.0  | 6         | 2.14%   |
| 0.51-1.0    | 4         | 1.43%   |
| 64.01-256.0 | 2         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 135       | 44.7%   |
| 2.01-3.0   | 82        | 27.15%  |
| 3.01-4.0   | 38        | 12.58%  |
| 0.51-1.0   | 20        | 6.62%   |
| 4.01-8.0   | 18        | 5.96%   |
| 8.01-16.0  | 5         | 1.66%   |
| 0.01-0.5   | 3         | 0.99%   |
| 32.01-64.0 | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 183       | 65.36%  |
| 2      | 75        | 26.79%  |
| 3      | 13        | 4.64%   |
| 4      | 4         | 1.43%   |
| 0      | 3         | 1.07%   |
| 7      | 1         | 0.36%   |
| 5      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 57.19%  |
| No        | 119       | 42.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 252       | 91.97%  |
| No        | 22        | 8.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 78.06%  |
| No        | 61        | 21.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 54.12%  |
| Yes       | 128       | 45.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 274       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Algiers            | 46        | 14.6%   |
| Belcourt           | 18        | 5.71%   |
| Oran               | 15        | 4.76%   |
| Annaba             | 12        | 3.81%   |
| Tlemcen            | 11        | 3.49%   |
| Constantine        | 10        | 3.17%   |
| Sétif             | 8         | 2.54%   |
| Skikda             | 7         | 2.22%   |
| Béjaïa           | 7         | 2.22%   |
| Relizane           | 6         | 1.9%    |
| Ouargla            | 6         | 1.9%    |
| Jijelli            | 6         | 1.9%    |
| Blida              | 6         | 1.9%    |
| Tizi Ouzou         | 5         | 1.59%   |
| Tipasa             | 5         | 1.59%   |
| Cheraga            | 5         | 1.59%   |
| Biskra             | 5         | 1.59%   |
| Batna City         | 5         | 1.59%   |
| Mostaganem         | 4         | 1.27%   |
| Laghouat           | 4         | 1.27%   |
| Birkhadem          | 4         | 1.27%   |
| Bab Ezzouar        | 4         | 1.27%   |
| Tolga              | 3         | 0.95%   |
| Sidi Bel Abbes     | 3         | 0.95%   |
| Sidi Akkacha       | 3         | 0.95%   |
| Saoula             | 3         | 0.95%   |
| Kouba              | 3         | 0.95%   |
| Bordj Bou Arreridj | 3         | 0.95%   |
| Ben ’Aknoûn     | 3         | 0.95%   |
| ash-Shalif         | 3         | 0.95%   |
| Saida              | 2         | 0.63%   |
| Ouenza             | 2         | 0.63%   |
| Khenchela          | 2         | 0.63%   |
| El Aouinet         | 2         | 0.63%   |
| Draria             | 2         | 0.63%   |
| Djelfa             | 2         | 0.63%   |
| Boumerdes          | 2         | 0.63%   |
| Boudouaou          | 2         | 0.63%   |
| Bordj el Kiffan    | 2         | 0.63%   |
| Bir el Djir        | 2         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 66        | 84     | 18.08%  |
| WDC                       | 58        | 82     | 15.89%  |
| Toshiba                   | 41        | 53     | 11.23%  |
| Hitachi                   | 33        | 43     | 9.04%   |
| Samsung Electronics       | 26        | 30     | 7.12%   |
| A-DATA Technology         | 19        | 24     | 5.21%   |
| HGST                      | 17        | 22     | 4.66%   |
| Unknown                   | 10        | 14     | 2.74%   |
| SanDisk                   | 9         | 10     | 2.47%   |
| Team                      | 7         | 8      | 1.92%   |
| Lexar                     | 7         | 10     | 1.92%   |
| Maxtor                    | 6         | 8      | 1.64%   |
| LITEON                    | 5         | 8      | 1.37%   |
| SK hynix                  | 4         | 6      | 1.1%    |
| China                     | 4         | 4      | 1.1%    |
| Realtek Semiconductor     | 3         | 3      | 0.82%   |
| Kingston                  | 3         | 3      | 0.82%   |
| Intel                     | 3         | 4      | 0.82%   |
| Fujitsu                   | 3         | 4      | 0.82%   |
| ZTE                       | 2         | 2      | 0.55%   |
| XrayDisk                  | 2         | 2      | 0.55%   |
| XPG                       | 2         | 2      | 0.55%   |
| Silicon Motion            | 2         | 2      | 0.55%   |
| Micron Technology         | 2         | 3      | 0.55%   |
| KingSpec                  | 2         | 2      | 0.55%   |
| KESU                      | 2         | 2      | 0.55%   |
| Apple                     | 2         | 2      | 0.55%   |
| WD MediaMax               | 1         | 1      | 0.27%   |
| TwinMOS                   | 1         | 1      | 0.27%   |
| tecmiyo                   | 1         | 1      | 0.27%   |
| T-FORCE                   | 1         | 1      | 0.27%   |
| Smart                     | 1         | 1      | 0.27%   |
| PNY                       | 1         | 1      | 0.27%   |
| Micron/Crucial Technology | 1         | 1      | 0.27%   |
| MDT                       | 1         | 1      | 0.27%   |
| MAX                       | 1         | 1      | 0.27%   |
| Magnetic Data             | 1         | 1      | 0.27%   |
| Londisk                   | 1         | 1      | 0.27%   |
| LITEONIT                  | 1         | 1      | 0.27%   |
| Lenovo                    | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB           | 9         | 2.34%   |
| Seagate ST9500325AS 500GB          | 9         | 2.34%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 1.56%   |
| Toshiba MQ01ABD100 1TB             | 5         | 1.3%    |
| Toshiba DT01ACA100 1TB             | 5         | 1.3%    |
| Toshiba DT01ACA050 500GB           | 5         | 1.3%    |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 1.04%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.04%   |
| Seagate Expansion 1TB              | 4         | 1.04%   |
| HGST HTS545050A7E680 500GB         | 4         | 1.04%   |
| HGST HTS545050A7E380 500GB         | 4         | 1.04%   |
| A-DATA SU630 240GB SSD             | 4         | 1.04%   |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.78%   |
| WDC WD10EZEX-00WN4A0 1TB           | 3         | 0.78%   |
| Unknown MMC Card  64GB             | 3         | 0.78%   |
| Lexar 512GB SSD                    | 3         | 0.78%   |
| Lexar 128GB SSD                    | 3         | 0.78%   |
| Hitachi HTS545050B9A300 500GB      | 3         | 0.78%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 0.78%   |
| Hitachi HDS721616PLA380 164GB      | 3         | 0.78%   |
| HGST HTS725050A7E630 500GB         | 3         | 0.78%   |
| A-DATA LEGEND 710 512GB            | 3         | 0.78%   |
| ZTE MMC Storage 942MB              | 2         | 0.52%   |
| XPG SX950U 240GB                   | 2         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.52%   |
| WDC WD5000AVVS-63M8B0 500GB        | 2         | 0.52%   |
| WDC WD1600AVJS-63WNA0 160GB        | 2         | 0.52%   |
| Unknown SD/MMC 2GB                 | 2         | 0.52%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 2         | 0.52%   |
| Team T253512GB SSD                 | 2         | 0.52%   |
| Team T253256GB SSD                 | 2         | 0.52%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.52%   |
| Seagate ST3500413AS 500GB          | 2         | 0.52%   |
| Seagate ST3500312CS 500GB          | 2         | 0.52%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 84     | 27.85%  |
| WDC                 | 55        | 75     | 23.21%  |
| Toshiba             | 40        | 50     | 16.88%  |
| Hitachi             | 33        | 43     | 13.92%  |
| HGST                | 17        | 22     | 7.17%   |
| Samsung Electronics | 11        | 12     | 4.64%   |
| Maxtor              | 6         | 8      | 2.53%   |
| Fujitsu             | 3         | 4      | 1.27%   |
| WD MediaMax         | 1         | 1      | 0.42%   |
| Magnetic Data       | 1         | 1      | 0.42%   |
| KESU                | 1         | 1      | 0.42%   |
| Initio              | 1         | 1      | 0.42%   |
| Hewlett-Packard     | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 13        | 16     | 17.11%  |
| Team                | 6         | 7      | 7.89%   |
| SanDisk             | 6         | 6      | 7.89%   |
| Lexar               | 6         | 9      | 7.89%   |
| Samsung Electronics | 5         | 5      | 6.58%   |
| LITEON              | 5         | 8      | 6.58%   |
| WDC                 | 4         | 6      | 5.26%   |
| China               | 4         | 4      | 5.26%   |
| SK hynix            | 3         | 5      | 3.95%   |
| Intel               | 3         | 4      | 3.95%   |
| XrayDisk            | 2         | 2      | 2.63%   |
| XPG                 | 2         | 2      | 2.63%   |
| Kingston            | 2         | 2      | 2.63%   |
| KingSpec            | 2         | 2      | 2.63%   |
| TwinMOS             | 1         | 1      | 1.32%   |
| tecmiyo             | 1         | 1      | 1.32%   |
| T-FORCE             | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| MAX                 | 1         | 1      | 1.32%   |
| Londisk             | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Lenovo              | 1         | 1      | 1.32%   |
| HS-SSD-C100         | 1         | 1      | 1.32%   |
| Crucial             | 1         | 1      | 1.32%   |
| Corsair             | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 211       | 304    | 64.33%  |
| SSD     | 70        | 91     | 21.34%  |
| NVMe    | 27        | 43     | 8.23%   |
| MMC     | 10        | 12     | 3.05%   |
| Unknown | 10        | 13     | 3.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 246       | 390    | 82.83%  |
| NVMe | 26        | 42     | 8.75%   |
| SAS  | 15        | 19     | 5.05%   |
| MMC  | 10        | 12     | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 201       | 295    | 71.79%  |
| 0.51-1.0   | 72        | 91     | 25.71%  |
| 1.01-2.0   | 7         | 9      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 72        | 24.32%  |
| 101-250    | 57        | 19.26%  |
| 51-100     | 48        | 16.22%  |
| 1-20       | 36        | 12.16%  |
| 501-1000   | 33        | 11.15%  |
| 21-50      | 29        | 9.8%    |
| 1001-2000  | 15        | 5.07%   |
| 2001-3000  | 3         | 1.01%   |
| Unknown    | 3         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 147       | 48.68%  |
| 21-50     | 58        | 19.21%  |
| 101-250   | 36        | 11.92%  |
| 51-100    | 26        | 8.61%   |
| 251-500   | 19        | 6.29%   |
| 501-1000  | 9         | 2.98%   |
| 1001-2000 | 4         | 1.32%   |
| Unknown   | 3         | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                   | 7         | 7      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB             | 3         | 3      | 4.76%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 2      | 3.17%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 2      | 3.17%   |
| Samsung Electronics HD502HI 500GB           | 2         | 2      | 3.17%   |
| HGST HTS725050A7E630 500GB                  | 2         | 4      | 3.17%   |
| WDC WD5000LUCT-62C26Y0 500GB                | 1         | 1      | 1.59%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 1.59%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 1.59%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 1.59%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 1.59%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 1.59%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 1.59%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 1.59%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 1.59%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 1.59%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 1.59%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 1.59%   |
| Toshiba DT01ACA050 500GB                    | 1         | 1      | 1.59%   |
| tecmiyo SATA SSD 128GB                      | 1         | 1      | 1.59%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.59%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 1.59%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.59%   |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 1.59%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 2      | 1.59%   |
| Seagate ST3500413AS 500GB                   | 1         | 1      | 1.59%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.59%   |
| Seagate ST1000LM048-2E7172 1TB              | 1         | 1      | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 1.59%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 1.59%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 1.59%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 1.59%   |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 1.59%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 1.59%   |
| Maxtor STM3320613AS 320GB                   | 1         | 1      | 1.59%   |
| Maxtor STM3160215AS 160GB                   | 1         | 1      | 1.59%   |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 1.59%   |
| Maxtor 32049H2 20GB                         | 1         | 1      | 1.59%   |
| Magnetic Data MD07500-ALDW-RO 752GB         | 1         | 1      | 1.59%   |
| LITEONIT L8T-256L6G-HP 256GB SSD            | 1         | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 33.87%  |
| WDC                 | 9         | 10     | 14.52%  |
| Samsung Electronics | 7         | 7      | 11.29%  |
| Hitachi             | 7         | 8      | 11.29%  |
| Toshiba             | 4         | 4      | 6.45%   |
| Maxtor              | 4         | 4      | 6.45%   |
| HGST                | 3         | 5      | 4.84%   |
| A-DATA Technology   | 2         | 2      | 3.23%   |
| WD MediaMax         | 1         | 1      | 1.61%   |
| tecmiyo             | 1         | 1      | 1.61%   |
| Magnetic Data       | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| KingSpec            | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 37.5%   |
| WDC                 | 9         | 10     | 16.07%  |
| Hitachi             | 7         | 8      | 12.5%   |
| Samsung Electronics | 6         | 6      | 10.71%  |
| Toshiba             | 4         | 4      | 7.14%   |
| Maxtor              | 4         | 4      | 7.14%   |
| HGST                | 3         | 5      | 5.36%   |
| WD MediaMax         | 1         | 1      | 1.79%   |
| Magnetic Data       | 1         | 1      | 1.79%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 61     | 89.83%  |
| SSD  | 5         | 5      | 8.47%   |
| NVMe | 1         | 1      | 1.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 165       | 285    | 54.82%  |
| Works    | 77        | 109    | 25.58%  |
| Malfunc  | 57        | 67     | 18.94%  |
| Failed   | 2         | 2      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 237       | 79.53%  |
| AMD                          | 16        | 5.37%   |
| Samsung Electronics          | 10        | 3.36%   |
| Realtek Semiconductor        | 5         | 1.68%   |
| VIA Technologies             | 4         | 1.34%   |
| Nvidia                       | 4         | 1.34%   |
| ASMedia Technology           | 4         | 1.34%   |
| Silicon Motion               | 3         | 1.01%   |
| ADATA Technology             | 3         | 1.01%   |
| Micron Technology            | 2         | 0.67%   |
| Kingston Technology Company  | 2         | 0.67%   |
| JMicron Technology           | 2         | 0.67%   |
| Toshiba America Info Systems | 1         | 0.34%   |
| SanDisk                      | 1         | 0.34%   |
| Micron/Crucial Technology    | 1         | 0.34%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.34%   |
| Marvell Technology Group     | 1         | 0.34%   |
| KIOXIA                       | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 27        | 7.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 23        | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21        | 5.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16        | 4.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 4.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 14        | 3.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 3.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 3.34%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10        | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 2.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 1.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.39%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 4         | 1.11%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.11%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3         | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 0.84%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.84%   |
| ADATA ADATA XPG GAMMIXS1 1L Media (256 GB SSD)                                          | 3         | 0.84%   |
| VIA Serial ATA Controller                                                               | 2         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.56%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.56%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 2         | 0.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 187       | 62.96%  |
| IDE  | 62        | 20.88%  |
| NVMe | 26        | 8.75%   |
| RAID | 21        | 7.07%   |
| SAS  | 1         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 253       | 92.34%  |
| AMD    | 20        | 7.3%    |
| ARM    | 1         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6         | 2.17%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 6         | 2.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 2.17%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 2.17%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 5         | 1.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 5         | 1.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 1.81%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4         | 1.45%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 4         | 1.45%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 1.45%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3         | 1.09%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 3         | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.09%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 1.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.09%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.09%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.09%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.09%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 1.09%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 1.09%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.09%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.09%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 1.09%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3         | 1.09%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2         | 0.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 0.72%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2         | 0.72%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.72%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 2         | 0.72%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 23.55%  |
| Intel Core i3           | 65        | 23.55%  |
| Intel Core i7           | 34        | 12.32%  |
| Intel Pentium           | 22        | 7.97%   |
| Intel Core 2 Duo        | 15        | 5.43%   |
| Intel Pentium Dual-Core | 14        | 5.07%   |
| Intel Celeron           | 12        | 4.35%   |
| Intel Genuine           | 8         | 2.9%    |
| Intel Atom              | 6         | 2.17%   |
| AMD Ryzen 5             | 5         | 1.81%   |
| Intel Xeon              | 4         | 1.45%   |
| Intel Pentium Dual      | 4         | 1.45%   |
| AMD Ryzen 7             | 4         | 1.45%   |
| Other                   | 3         | 1.09%   |
| AMD A4                  | 2         | 0.72%   |
| Intel Pentium D         | 1         | 0.36%   |
| Intel Pentium 4         | 1         | 0.36%   |
| Intel Core 2 Quad       | 1         | 0.36%   |
| ARM Allwinner           | 1         | 0.36%   |
| AMD Ryzen 9             | 1         | 0.36%   |
| AMD Ryzen 5 PRO         | 1         | 0.36%   |
| AMD Ryzen 3             | 1         | 0.36%   |
| AMD FX                  | 1         | 0.36%   |
| AMD E2                  | 1         | 0.36%   |
| AMD E1                  | 1         | 0.36%   |
| AMD Athlon Neo X2       | 1         | 0.36%   |
| AMD Athlon II Dual-Core | 1         | 0.36%   |
| AMD Athlon 64           | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 196       | 71.27%  |
| 4      | 58        | 21.09%  |
| 6      | 8         | 2.91%   |
| 1      | 5         | 1.82%   |
| 8      | 4         | 1.45%   |
| 16     | 2         | 0.73%   |
| 12     | 1         | 0.36%   |
| 3      | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 274       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 168       | 61.09%  |
| 1      | 106       | 38.55%  |
| 4      | 1         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 269       | 97.82%  |
| Unknown        | 4         | 1.45%   |
| 32-bit         | 2         | 0.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 26.99%  |
| 0x306a9    | 33        | 11.42%  |
| 0x206a7    | 23        | 7.96%   |
| 0x1067a    | 21        | 7.27%   |
| 0x20655    | 17        | 5.88%   |
| 0x40651    | 12        | 4.15%   |
| 0x406e3    | 11        | 3.81%   |
| 0x306c3    | 10        | 3.46%   |
| 0x806e9    | 8         | 2.77%   |
| 0x306d4    | 8         | 2.77%   |
| 0x30678    | 8         | 2.77%   |
| 0x906e9    | 5         | 1.73%   |
| 0x806ea    | 5         | 1.73%   |
| 0x6fd      | 5         | 1.73%   |
| 0x20652    | 3         | 1.04%   |
| 0x806ec    | 2         | 0.69%   |
| 0x706a8    | 2         | 0.69%   |
| 0x6fb      | 2         | 0.69%   |
| 0x506e3    | 2         | 0.69%   |
| 0x306e4    | 2         | 0.69%   |
| 0x30661    | 2         | 0.69%   |
| 0x10676    | 2         | 0.69%   |
| 0x0a50000d | 2         | 0.69%   |
| 0x08600106 | 2         | 0.69%   |
| 0x0800820d | 2         | 0.69%   |
| 0xf65      | 1         | 0.35%   |
| 0xa0652    | 1         | 0.35%   |
| 0x906eb    | 1         | 0.35%   |
| 0x806c1    | 1         | 0.35%   |
| 0x706a1    | 1         | 0.35%   |
| 0x6ec      | 1         | 0.35%   |
| 0x6e8      | 1         | 0.35%   |
| 0x506c9    | 1         | 0.35%   |
| 0x406c4    | 1         | 0.35%   |
| 0x406c3    | 1         | 0.35%   |
| 0x206d7    | 1         | 0.35%   |
| 0x0a201016 | 1         | 0.35%   |
| 0x0a201005 | 1         | 0.35%   |
| 0x08701021 | 1         | 0.35%   |
| 0x08608103 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 45        | 16.3%   |
| SandyBridge   | 36        | 13.04%  |
| Haswell       | 33        | 11.96%  |
| Penryn        | 32        | 11.59%  |
| KabyLake      | 25        | 9.06%   |
| Westmere      | 20        | 7.25%   |
| Skylake       | 17        | 6.16%   |
| Silvermont    | 14        | 5.07%   |
| Core          | 9         | 3.26%   |
| Broadwell     | 9         | 3.26%   |
| Zen 3         | 4         | 1.45%   |
| Goldmont plus | 4         | 1.45%   |
| Unknown       | 4         | 1.45%   |
| Zen+          | 3         | 1.09%   |
| Zen 2         | 3         | 1.09%   |
| P6            | 2         | 0.72%   |
| NetBurst      | 2         | 0.72%   |
| K8 Hammer     | 2         | 0.72%   |
| Jaguar        | 2         | 0.72%   |
| Bonnell       | 2         | 0.72%   |
| Zen           | 1         | 0.36%   |
| TigerLake     | 1         | 0.36%   |
| K10           | 1         | 0.36%   |
| Goldmont      | 1         | 0.36%   |
| Excavator     | 1         | 0.36%   |
| CometLake     | 1         | 0.36%   |
| Bulldozer     | 1         | 0.36%   |
| Bobcat        | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 205       | 62.5%   |
| Nvidia                     | 61        | 18.6%   |
| AMD                        | 59        | 17.99%  |
| VIA Technologies           | 2         | 0.61%   |
| Matrox Electronics Systems | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 7.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 6.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 4.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 3.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 3.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 3.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 3.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 3.03%   |
| Intel HD Graphics 620                                                                    | 9         | 2.73%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 9         | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 2.42%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.12%   |
| Nvidia GT218M [GeForce G210M]                                                            | 6         | 1.82%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.52%   |
| Intel HD Graphics 630                                                                    | 5         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.21%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.91%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.91%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.61%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.61%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.61%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.61%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 2         | 0.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.61%   |
| Intel HD Graphics 530                                                                    | 2         | 0.61%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.61%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 2         | 0.61%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.61%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.61%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 153       | 55.43%  |
| 1 x AMD        | 36        | 13.04%  |
| 1 x Nvidia     | 31        | 11.23%  |
| Intel + Nvidia | 29        | 10.51%  |
| Intel + AMD    | 22        | 7.97%   |
| 1 x VIA        | 2         | 0.72%   |
| Other          | 1         | 0.36%   |
| 1 x Matrox     | 1         | 0.36%   |
| AMD + Nvidia   | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 247       | 88.21%  |
| Proprietary | 23        | 8.21%   |
| Unknown     | 10        | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 62.5%   |
| 1.01-2.0   | 51        | 18.21%  |
| 0.01-0.5   | 24        | 8.57%   |
| 0.51-1.0   | 16        | 5.71%   |
| 3.01-4.0   | 9         | 3.21%   |
| 7.01-8.0   | 3         | 1.07%   |
| 5.01-6.0   | 1         | 0.36%   |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 52        | 18.91%  |
| LG Display              | 38        | 13.82%  |
| AU Optronics            | 34        | 12.36%  |
| BOE                     | 23        | 8.36%   |
| Chimei Innolux          | 18        | 6.55%   |
| Hewlett-Packard         | 16        | 5.82%   |
| AOC                     | 14        | 5.09%   |
| Acer                    | 12        | 4.36%   |
| Chi Mei Optoelectronics | 11        | 4%      |
| Goldstar                | 6         | 2.18%   |
| KTC                     | 5         | 1.82%   |
| Apple                   | 5         | 1.82%   |
| BenQ                    | 4         | 1.45%   |
| Ancor Communications    | 4         | 1.45%   |
| Unknown                 | 4         | 1.45%   |
| Sharp                   | 3         | 1.09%   |
| Lenovo                  | 3         | 1.09%   |
| Dell                    | 3         | 1.09%   |
| Unknown (XXX)           | 2         | 0.73%   |
| Unknown                 | 2         | 0.73%   |
| ___                     | 1         | 0.36%   |
| Westinghouse            | 1         | 0.36%   |
| TSN                     | 1         | 0.36%   |
| TGC                     | 1         | 0.36%   |
| SKY                     | 1         | 0.36%   |
| PTW                     | 1         | 0.36%   |
| PiLot                   | 1         | 0.36%   |
| PANDA                   | 1         | 0.36%   |
| MStar                   | 1         | 0.36%   |
| LGD                     | 1         | 0.36%   |
| ITE                     | 1         | 0.36%   |
| InnoLux Display         | 1         | 0.36%   |
| InfoVision              | 1         | 0.36%   |
| Hitachi                 | 1         | 0.36%   |
| EMP                     | 1         | 0.36%   |
| AGO                     | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213C 1366x768 309x174mm 14.0-inch            | 6         | 2.15%   |
| Acer V193HQ ACR00F9 1366x768 410x230mm 18.5-inch                         | 6         | 2.15%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 4         | 1.43%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 4         | 1.43%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 4         | 1.43%   |
| Unknown                                                                  | 4         | 1.43%   |
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.08%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.08%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.08%   |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                          | 3         | 1.08%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 2         | 0.72%   |
| Sharp HDMI SHP10DB 1920x1080 1330x750mm 60.1-inch                        | 2         | 0.72%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch        | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.72%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.72%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.72%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 2         | 0.72%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 0.72%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.72%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.36%   |
| Westinghouse LED-TV WET3663 1680x1050 640x384mm 29.4-inch                | 1         | 0.36%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.36%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 124       | 47.88%  |
| 1920x1080 (FHD)    | 71        | 27.41%  |
| 1600x900 (HD+)     | 16        | 6.18%   |
| 1440x900 (WXGA+)   | 11        | 4.25%   |
| 2560x1440 (QHD)    | 5         | 1.93%   |
| 1680x1050 (WSXGA+) | 5         | 1.93%   |
| 1360x768           | 5         | 1.93%   |
| 1280x800 (WXGA)    | 4         | 1.54%   |
| 1280x1024 (SXGA)   | 4         | 1.54%   |
| 3840x2160 (4K)     | 3         | 1.16%   |
| 1920x540           | 2         | 0.77%   |
| 1920x1200 (WUXGA)  | 2         | 0.77%   |
| 2160x1440          | 1         | 0.39%   |
| 1680x945           | 1         | 0.39%   |
| 1600x1200          | 1         | 0.39%   |
| 1280x720 (HD)      | 1         | 0.39%   |
| 1152x864           | 1         | 0.39%   |
| 1024x768 (XGA)     | 1         | 0.39%   |
| 1024x600           | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 105       | 38.04%  |
| 18      | 27        | 9.78%   |
| 14      | 21        | 7.61%   |
| 13      | 16        | 5.8%    |
| 21      | 15        | 5.43%   |
| 19      | 12        | 4.35%   |
| 23      | 10        | 3.62%   |
| 17      | 10        | 3.62%   |
| 20      | 9         | 3.26%   |
| 27      | 8         | 2.9%    |
| Unknown | 8         | 2.9%    |
| 12      | 7         | 2.54%   |
| 24      | 5         | 1.81%   |
| 52      | 4         | 1.45%   |
| 22      | 4         | 1.45%   |
| 60      | 2         | 0.72%   |
| 11      | 2         | 0.72%   |
| 10      | 2         | 0.72%   |
| 72      | 1         | 0.36%   |
| 48      | 1         | 0.36%   |
| 46      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 37      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 31      | 1         | 0.36%   |
| 29      | 1         | 0.36%   |
| 16      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 134       | 48.91%  |
| 401-500     | 62        | 22.63%  |
| 501-600     | 23        | 8.39%   |
| 351-400     | 17        | 6.2%    |
| 201-300     | 16        | 5.84%   |
| 1001-1500   | 8         | 2.92%   |
| Unknown     | 8         | 2.92%   |
| 801-900     | 2         | 0.73%   |
| 601-700     | 2         | 0.73%   |
| 701-800     | 1         | 0.36%   |
| 1501-2000   | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 215       | 84.31%  |
| 16/10   | 21        | 8.24%   |
| Unknown | 6         | 2.35%   |
| 5/4     | 4         | 1.57%   |
| 4/3     | 4         | 1.57%   |
| 32/9    | 2         | 0.78%   |
| 3/2     | 2         | 0.78%   |
| 6/5     | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 103       | 37.59%  |
| 81-90          | 33        | 12.04%  |
| 141-150        | 28        | 10.22%  |
| 151-200        | 27        | 9.85%   |
| 201-250        | 26        | 9.49%   |
| More than 1000 | 8         | 2.92%   |
| 301-350        | 8         | 2.92%   |
| Unknown        | 8         | 2.92%   |
| 61-70          | 6         | 2.19%   |
| 121-130        | 6         | 2.19%   |
| 71-80          | 5         | 1.82%   |
| 351-500        | 3         | 1.09%   |
| 111-120        | 3         | 1.09%   |
| 501-1000       | 3         | 1.09%   |
| 51-60          | 2         | 0.73%   |
| 41-50          | 2         | 0.73%   |
| 131-140        | 2         | 0.73%   |
| 251-300        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 112       | 41.18%  |
| 51-100        | 95        | 34.93%  |
| 121-160       | 40        | 14.71%  |
| 1-50          | 10        | 3.68%   |
| Unknown       | 8         | 2.94%   |
| 161-240       | 6         | 2.21%   |
| More than 240 | 1         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 237       | 85.25%  |
| 2     | 29        | 10.43%  |
| 0     | 10        | 3.6%    |
| 3     | 2         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 167       | 38.04%  |
| Qualcomm Atheros                | 76        | 17.31%  |
| Intel                           | 71        | 16.17%  |
| Broadcom                        | 38        | 8.66%   |
| Ralink Technology               | 27        | 6.15%   |
| Ralink                          | 11        | 2.51%   |
| Qualcomm Atheros Communications | 7         | 1.59%   |
| MediaTek                        | 5         | 1.14%   |
| Broadcom Limited                | 5         | 1.14%   |
| Xiaomi                          | 4         | 0.91%   |
| Samsung Electronics             | 4         | 0.91%   |
| Marvell Technology Group        | 4         | 0.91%   |
| VIA Technologies                | 3         | 0.68%   |
| Nvidia                          | 3         | 0.68%   |
| D-Link System                   | 3         | 0.68%   |
| TP-Link                         | 2         | 0.46%   |
| Huawei Technologies             | 2         | 0.46%   |
| D-Link                          | 2         | 0.46%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.23%   |
| Sierra Wireless                 | 1         | 0.23%   |
| LG Electronics                  | 1         | 0.23%   |
| Hewlett-Packard                 | 1         | 0.23%   |
| AMD                             | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 19.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57        | 11.33%  |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 2.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.58%   |
| Ralink MT7601U Wireless Adapter                                   | 12        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.79%   |
| Ralink RT5370 Wireless Adapter                                    | 7         | 1.39%   |
| Qualcomm Atheros AR9271 802.11n                                   | 7         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 6         | 1.19%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.99%   |
| Intel Wireless 8260                                               | 5         | 0.99%   |
| Intel Wireless 7265                                               | 5         | 0.99%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.6%    |
| MediaTek Wiko U316AT                                              | 3         | 0.6%    |
| Intel Wireless 7260                                               | 3         | 0.6%    |
| Intel Wireless 3160                                               | 3         | 0.6%    |
| Intel WiFi Link 5100                                              | 3         | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.6%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 25.42%  |
| Qualcomm Atheros                | 57        | 24.15%  |
| Realtek Semiconductor           | 31        | 13.14%  |
| Broadcom                        | 29        | 12.29%  |
| Ralink Technology               | 27        | 11.44%  |
| Ralink                          | 11        | 4.66%   |
| Qualcomm Atheros Communications | 7         | 2.97%   |
| D-Link System                   | 3         | 1.27%   |
| TP-Link                         | 2         | 0.85%   |
| MediaTek                        | 2         | 0.85%   |
| D-Link                          | 2         | 0.85%   |
| Broadcom Limited                | 2         | 0.85%   |
| Sierra Wireless                 | 1         | 0.42%   |
| Marvell Technology Group        | 1         | 0.42%   |
| Hewlett-Packard                 | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 15        | 6.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 14        | 5.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 13        | 5.51%   |
| Ralink MT7601U Wireless Adapter                                      | 12        | 5.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 4.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 9         | 3.81%   |
| Intel Wireless 8265 / 8275                                           | 9         | 3.81%   |
| Ralink RT5370 Wireless Adapter                                       | 7         | 2.97%   |
| Qualcomm Atheros AR9271 802.11n                                      | 7         | 2.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 2.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 6         | 2.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 2.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 5         | 2.12%   |
| Intel Wireless 8260                                                  | 5         | 2.12%   |
| Intel Wireless 7265                                                  | 5         | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 5         | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.27%   |
| Intel Wireless 7260                                                  | 3         | 1.27%   |
| Intel Wireless 3160                                                  | 3         | 1.27%   |
| Intel WiFi Link 5100                                                 | 3         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 0.85%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 0.85%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 0.85%   |
| Intel Centrino Wireless-N 135                                        | 2         | 0.85%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 0.85%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 0.85%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 0.85%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 154       | 58.11%  |
| Intel                      | 46        | 17.36%  |
| Qualcomm Atheros           | 25        | 9.43%   |
| Broadcom                   | 13        | 4.91%   |
| Xiaomi                     | 4         | 1.51%   |
| Samsung Electronics        | 4         | 1.51%   |
| VIA Technologies           | 3         | 1.13%   |
| Nvidia                     | 3         | 1.13%   |
| MediaTek                   | 3         | 1.13%   |
| Marvell Technology Group   | 3         | 1.13%   |
| Broadcom Limited           | 3         | 1.13%   |
| ZTE WCDMA Technologies MSM | 1         | 0.38%   |
| LG Electronics             | 1         | 0.38%   |
| Huawei Technologies        | 1         | 0.38%   |
| AMD                        | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 36.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57        | 21.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 2.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.26%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 1.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.13%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.13%   |
| MediaTek Wiko U316AT                                              | 3         | 1.13%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.13%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.75%   |
| Intel PRO/100 VE Network Connection                               | 2         | 0.75%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.75%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.75%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.75%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1         | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.38%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.38%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.38%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.38%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.38%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 251       | 53.52%  |
| WiFi     | 217       | 46.27%  |
| Modem    | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 63.14%  |
| Ethernet | 101       | 36.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 167       | 59.86%  |
| 1     | 105       | 37.63%  |
| 0     | 6         | 2.15%   |
| 3     | 1         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 274       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 28.13%  |
| Qualcomm Atheros Communications | 18        | 14.06%  |
| Broadcom                        | 13        | 10.16%  |
| Realtek Semiconductor           | 10        | 7.81%   |
| IMC Networks                    | 6         | 4.69%   |
| Foxconn / Hon Hai               | 6         | 4.69%   |
| Ralink                          | 5         | 3.91%   |
| Lite-On Technology              | 5         | 3.91%   |
| Cambridge Silicon Radio         | 5         | 3.91%   |
| Apple                           | 5         | 3.91%   |
| Dell                            | 4         | 3.13%   |
| Toshiba                         | 3         | 2.34%   |
| Foxconn International           | 3         | 2.34%   |
| Integrated System Solution      | 2         | 1.56%   |
| Ralink Technology               | 1         | 0.78%   |
| Marvell Semiconductor           | 1         | 0.78%   |
| ISSC                            | 1         | 0.78%   |
| Hewlett-Packard                 | 1         | 0.78%   |
| Chicony Electronics             | 1         | 0.78%   |
| ASUSTek Computer                | 1         | 0.78%   |
| Alps Electric                   | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 23        | 17.97%  |
| Qualcomm Atheros  Bluetooth Device                    | 7         | 5.47%   |
| Realtek Bluetooth Radio                               | 5         | 3.91%   |
| Ralink RT3290 Bluetooth                               | 5         | 3.91%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 3.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5         | 3.91%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 3.13%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3         | 2.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3         | 2.34%   |
| IMC Networks Bluetooth Device                         | 3         | 2.34%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 2.34%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 2.34%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3         | 2.34%   |
| Apple Bluetooth Host Controller                       | 3         | 2.34%   |
| Toshiba Bluetooth Device                              | 2         | 1.56%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2         | 1.56%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 2         | 1.56%   |
| Dell Wireless 365 Bluetooth                           | 2         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.56%   |
| Toshiba BCM43142A0                                    | 1         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.78%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.78%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.78%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 0.78%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.78%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.78%   |
| Lite-On Wireless_Device                               | 1         | 0.78%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 0.78%   |
| Lite-On BCM43142A0                                    | 1         | 0.78%   |
| ISSC Bluetooth Device                                 | 1         | 0.78%   |
| Intel Bluetooth Device                                | 1         | 0.78%   |
| Intel AX210 Bluetooth                                 | 1         | 0.78%   |
| Intel AX200 Bluetooth                                 | 1         | 0.78%   |
| IMC Networks Wireless_Device                          | 1         | 0.78%   |
| IMC Networks Bluetooth Radio                          | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 241       | 69.86%  |
| AMD                    | 45        | 13.04%  |
| Nvidia                 | 43        | 12.46%  |
| JMTek                  | 4         | 1.16%   |
| VIA Technologies       | 3         | 0.87%   |
| Texas Instruments      | 1         | 0.29%   |
| Medeli Electronics     | 1         | 0.29%   |
| Logitech               | 1         | 0.29%   |
| Logic3 / SpectraVideo  | 1         | 0.29%   |
| Guillemot              | 1         | 0.29%   |
| Goldvish               | 1         | 0.29%   |
| GN Netcom              | 1         | 0.29%   |
| Generalplus Technology | 1         | 0.29%   |
| ASUSTek Computer       | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 42        | 10.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 37        | 9.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 7.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 5.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 19        | 4.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 4.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 4.05%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 4.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 11        | 2.78%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 2.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.28%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 1.77%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.52%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.27%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 1.01%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.01%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.76%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.51%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.51%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 43        | 23.12%  |
| SK hynix            | 34        | 18.28%  |
| Samsung Electronics | 34        | 18.28%  |
| Micron Technology   | 23        | 12.37%  |
| Kingston            | 12        | 6.45%   |
| A-DATA Technology   | 11        | 5.91%   |
| Crucial             | 5         | 2.69%   |
| Nanya Technology    | 4         | 2.15%   |
| TwinMOS             | 3         | 1.61%   |
| Unknown (ABCD)      | 2         | 1.08%   |
| Ramaxel Technology  | 2         | 1.08%   |
| Unknown             | 2         | 1.08%   |
| Thermaltake         | 1         | 0.54%   |
| Team                | 1         | 0.54%   |
| SemsoTai            | 1         | 0.54%   |
| Patriot             | 1         | 0.54%   |
| GeIL                | 1         | 0.54%   |
| G.Skill             | 1         | 0.54%   |
| Elpida              | 1         | 0.54%   |
| Dynet               | 1         | 0.54%   |
| CSX                 | 1         | 0.54%   |
| Corsair             | 1         | 0.54%   |
| ASint Technology    | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                    | 6         | 2.91%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 6         | 2.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 6         | 2.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.94%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 3         | 1.46%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 0.97%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 0.97%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 0.97%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.97%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 2         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 2         | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.97%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.97%   |
| Nanya RAM Module 8GB SODIMM DDR4 2667MT/s                 | 2         | 0.97%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 2         | 0.97%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2         | 0.97%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s     | 2         | 0.97%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1334MT/s  | 2         | 0.97%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s               | 2         | 0.97%   |
| Unknown                                                   | 2         | 0.97%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.49%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR2                        | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR2                     | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s             | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM SDRAM                      | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s               | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s               | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 80        | 53.69%  |
| DDR4    | 33        | 22.15%  |
| Unknown | 11        | 7.38%   |
| SDRAM   | 10        | 6.71%   |
| DDR2    | 9         | 6.04%   |
| LPDDR4  | 3         | 2.01%   |
| LPDDR3  | 1         | 0.67%   |
| DDR5    | 1         | 0.67%   |
| DDR     | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 60.69%  |
| DIMM         | 55        | 37.93%  |
| Row Of Chips | 2         | 1.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 75        | 45.18%  |
| 2048  | 39        | 23.49%  |
| 8192  | 33        | 19.88%  |
| 1024  | 8         | 4.82%   |
| 16384 | 5         | 3.01%   |
| 32768 | 4         | 2.41%   |
| 512   | 2         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 45        | 26.95%  |
| 1333    | 27        | 16.17%  |
| 2667    | 14        | 8.38%   |
| 3200    | 7         | 4.19%   |
| 2400    | 7         | 4.19%   |
| 2133    | 7         | 4.19%   |
| 1334    | 7         | 4.19%   |
| 1066    | 7         | 4.19%   |
| 800     | 7         | 4.19%   |
| Unknown | 7         | 4.19%   |
| 1067    | 5         | 2.99%   |
| 667     | 4         | 2.4%    |
| 4199    | 3         | 1.8%    |
| 3600    | 2         | 1.2%    |
| 3266    | 2         | 1.2%    |
| 533     | 2         | 1.2%    |
| 6400    | 1         | 0.6%    |
| 3800    | 1         | 0.6%    |
| 3066    | 1         | 0.6%    |
| 3000    | 1         | 0.6%    |
| 2666    | 1         | 0.6%    |
| 2200    | 1         | 0.6%    |
| 1867    | 1         | 0.6%    |
| 1800    | 1         | 0.6%    |
| 1648    | 1         | 0.6%    |
| 1639    | 1         | 0.6%    |
| 1400    | 1         | 0.6%    |
| 333     | 1         | 0.6%    |
| 266     | 1         | 0.6%    |
| 200     | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 10        | 58.82%  |
| Seiko Epson        | 4         | 23.53%  |
| Hewlett-Packard    | 2         | 11.76%  |
| Brother Industries | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Canon LBP6020                                                         | 2         | 11.76%  |
| Canon LBP6000                                                         | 2         | 11.76%  |
| Seiko Epson XP-240 Series                                             | 1         | 5.88%   |
| Seiko Epson XP-200 Series                                             | 1         | 5.88%   |
| Seiko Epson Printer                                                   | 1         | 5.88%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 5.88%   |
| HP Ink Tank 310 series                                                | 1         | 5.88%   |
| HP DeskJet 5810 series                                                | 1         | 5.88%   |
| Canon MG5700 series                                                   | 1         | 5.88%   |
| Canon MF3010                                                          | 1         | 5.88%   |
| Canon LBP6030w/6018w                                                  | 1         | 5.88%   |
| Canon LBP3010/LBP3018/LBP3050                                         | 1         | 5.88%   |
| Canon LBP3000                                                         | 1         | 5.88%   |
| Canon LBP2900                                                         | 1         | 5.88%   |
| Brother MFC-J480DW                                                    | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 42        | 26.42%  |
| Microdia                               | 24        | 15.09%  |
| Realtek Semiconductor                  | 16        | 10.06%  |
| Cheng Uei Precision Industry (Foxlink) | 12        | 7.55%   |
| Sunplus Innovation Technology          | 9         | 5.66%   |
| Bison Electronics                      | 8         | 5.03%   |
| IMC Networks                           | 7         | 4.4%    |
| Suyin                                  | 6         | 3.77%   |
| Apple                                  | 5         | 3.14%   |
| Syntek                                 | 4         | 2.52%   |
| Silicon Motion                         | 3         | 1.89%   |
| Quanta                                 | 3         | 1.89%   |
| Acer                                   | 3         | 1.89%   |
| Samsung Electronics                    | 2         | 1.26%   |
| Lite-On Technology                     | 2         | 1.26%   |
| Alcor Micro                            | 2         | 1.26%   |
| Sonix Technology                       | 1         | 0.63%   |
| Ricoh                                  | 1         | 0.63%   |
| Primax Electronics                     | 1         | 0.63%   |
| Pixart Imaging                         | 1         | 0.63%   |
| Microsoft                              | 1         | 0.63%   |
| Logitech                               | 1         | 0.63%   |
| GEMBIRD                                | 1         | 0.63%   |
| Cubeternet                             | 1         | 0.63%   |
| Aveo Technology                        | 1         | 0.63%   |
| Arkmicro Technologies                  | 1         | 0.63%   |
| ALi                                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 7         | 4.38%   |
| Chicony TOSHIBA Web Camera - HD                                          | 6         | 3.75%   |
| Chicony Asus Integrated 0.3M UVC Webcam                                  | 6         | 3.75%   |
| Chicony Integrated Camera                                                | 5         | 3.13%   |
| Bison Lenovo EasyCamera                                                  | 5         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 2.5%    |
| Sunplus Integrated_Webcam_HD                                             | 3         | 1.88%   |
| Realtek Integrated_Webcam_HD                                             | 3         | 1.88%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 1.88%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 1.88%   |
| Microdia Integrated Webcam                                               | 3         | 1.88%   |
| Chicony HP Truevision HD                                                 | 3         | 1.88%   |
| Chicony HD WebCam                                                        | 3         | 1.88%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 1.25%   |
| Suyin HP Truevision HD                                                   | 2         | 1.25%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.25%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 2         | 1.25%   |
| Realtek HP Truevision HD                                                 | 2         | 1.25%   |
| IMC Networks Lenovo EasyCamera                                           | 2         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.25%   |
| Chicony HP HD Webcam [Fixed]                                             | 2         | 1.25%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 2         | 1.25%   |
| Apple Built-in iSight                                                    | 2         | 1.25%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.63%   |
| Syntek EasyCamera                                                        | 1         | 0.63%   |
| Suyin WebCam                                                             | 1         | 0.63%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                      | 1         | 0.63%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.63%   |
| Sunplus Laptop Integrated Webcam HD                                      | 1         | 0.63%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.63%   |
| Sunplus Dell HD Webcam                                                   | 1         | 0.63%   |
| Sunplus Asus Webcam                                                      | 1         | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                                               | 1         | 0.63%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 0.63%   |
| Silicon Motion WebCam SC-10HDD12636N                                     | 1         | 0.63%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 12        | 66.67%  |
| Synaptics             | 3         | 16.67%  |
| AuthenTec             | 2         | 11.11%  |
| Elan Microelectronics | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 5         | 27.78%  |
| Validity Sensors VFS491                           | 3         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.56%   |
| Synaptics WBDI Device                             | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5.56%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5.56%   |
| Elan ELAN:Fingerprint                             | 1         | 5.56%   |
| AuthenTec AES2810                                 | 1         | 5.56%   |
| AuthenTec AES1600                                 | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 12        | 92.31%  |
| OmniKey  | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 6         | 46.15%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 30.77%  |
| OmniKey CardMan 4321                                                         | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 201       | 71.79%  |
| 1     | 69        | 24.64%  |
| 2     | 8         | 2.86%   |
| 3     | 2         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 18        | 20%     |
| Fingerprint reader       | 18        | 20%     |
| Net/wireless             | 14        | 15.56%  |
| Chipcard                 | 13        | 14.44%  |
| Communication controller | 6         | 6.67%   |
| Bluetooth                | 6         | 6.67%   |
| Multimedia controller    | 5         | 5.56%   |
| Storage                  | 3         | 3.33%   |
| Camera                   | 3         | 3.33%   |
| Net/ethernet             | 2         | 2.22%   |
| Sound                    | 1         | 1.11%   |
| Card reader              | 1         | 1.11%   |


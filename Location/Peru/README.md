Linux in Peru - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Peru/Desktop/README.md) and [notebooks](/Location/Peru/Notebook/README.md).

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

Total: 435

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | A520M H                     | Desktop     | [acf2f9d381](https://linux-hardware.org/?probe=acf2f9d381) | Sep 25, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [21407ce4a8](https://linux-hardware.org/?probe=21407ce4a8) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Intel         | D945GCNL AAD97184-106       | Desktop     | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| AZW           | GK mini                     | Mini pc     | [b2d573f8e2](https://linux-hardware.org/?probe=b2d573f8e2) | Sep 10, 2022 |
| AZW           | GK mini                     | Mini pc     | [58c74cb934](https://linux-hardware.org/?probe=58c74cb934) | Sep 09, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [e6a9f975ae](https://linux-hardware.org/?probe=e6a9f975ae) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [c1e007def0](https://linux-hardware.org/?probe=c1e007def0) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd78986d01](https://linux-hardware.org/?probe=fd78986d01) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | 1493                        | Desktop     | [2ac16ddc1f](https://linux-hardware.org/?probe=2ac16ddc1f) | Aug 03, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [e5b05f8e39](https://linux-hardware.org/?probe=e5b05f8e39) | Aug 02, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [1c92a49cd4](https://linux-hardware.org/?probe=1c92a49cd4) | Aug 01, 2022 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f0952d8c25](https://linux-hardware.org/?probe=f0952d8c25) | Jul 13, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI           | GL65 Leopard 10SEK          | Notebook    | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell          | Latitude E7450              | Notebook    | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c1db97e482](https://linux-hardware.org/?probe=c1db97e482) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c274a43a82](https://linux-hardware.org/?probe=c274a43a82) | May 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek       | X555UQ                      | Notebook    | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2ce35a0cba](https://linux-hardware.org/?probe=2ce35a0cba) | May 30, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Intel         | DP67BA AAG10219-300         | Desktop     | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Acer          | TravelMate 5320             | Notebook    | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| HP            | 8056                        | Desktop     | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [03581837bc](https://linux-hardware.org/?probe=03581837bc) | May 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e436a62479](https://linux-hardware.org/?probe=e436a62479) | May 13, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [358cadc7df](https://linux-hardware.org/?probe=358cadc7df) | May 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [9b0f684d99](https://linux-hardware.org/?probe=9b0f684d99) | May 09, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo        | ThinkPad T530 24296G9       | Notebook    | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [f68946f3d4](https://linux-hardware.org/?probe=f68946f3d4) | May 06, 2022 |
| Compal        | QAQXX                       | Notebook    | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cbe76ee3d3](https://linux-hardware.org/?probe=cbe76ee3d3) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP            | ENVY dv6                    | Notebook    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U3S... | Notebook    | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek       | X556UR                      | Notebook    | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | Desktop     | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| Foxconn       | H61MXE                      | Desktop     | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [ed62d97841](https://linux-hardware.org/?probe=ed62d97841) | Apr 18, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| ASUSTek       | A68HM-E                     | Desktop     | [af6b7df94c](https://linux-hardware.org/?probe=af6b7df94c) | Apr 06, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [1ab5b833d9](https://linux-hardware.org/?probe=1ab5b833d9) | Mar 12, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 340 G2                      | Notebook    | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [91e577540a](https://linux-hardware.org/?probe=91e577540a) | Feb 11, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [15dd0e4767](https://linux-hardware.org/?probe=15dd0e4767) | Feb 08, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | Notebook    | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50fae55964](https://linux-hardware.org/?probe=50fae55964) | Jan 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f679efaa1](https://linux-hardware.org/?probe=5f679efaa1) | Jan 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony          | VGN-FW56M                   | Notebook    | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba       | Satellite E205              | Notebook    | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo        | G400 20235                  | Notebook    | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3c85ddcb3](https://linux-hardware.org/?probe=a3c85ddcb3) | Dec 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [9dccdb1f45](https://linux-hardware.org/?probe=9dccdb1f45) | Nov 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [180b98585e](https://linux-hardware.org/?probe=180b98585e) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [83ce5b471d](https://linux-hardware.org/?probe=83ce5b471d) | Nov 10, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [140cf1defc](https://linux-hardware.org/?probe=140cf1defc) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| ASRock        | B460M-HDV                   | Desktop     | [f343673932](https://linux-hardware.org/?probe=f343673932) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [9343a7aac0](https://linux-hardware.org/?probe=9343a7aac0) | Oct 13, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [2a068afc0c](https://linux-hardware.org/?probe=2a068afc0c) | Oct 11, 2021 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [57fb928b65](https://linux-hardware.org/?probe=57fb928b65) | Oct 03, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP            | Notebook                    | Notebook    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [72114a075d](https://linux-hardware.org/?probe=72114a075d) | Sep 24, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [5b63f0fc0a](https://linux-hardware.org/?probe=5b63f0fc0a) | Sep 16, 2021 |
| Advance       | AN-5431                     | Notebook    | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [72a24d0b34](https://linux-hardware.org/?probe=72a24d0b34) | Sep 01, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [92fb750c2f](https://linux-hardware.org/?probe=92fb750c2f) | Sep 01, 2021 |
| Lenovo        | ThinkPad T440 20B7A08500    | Notebook    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP            | 450                         | Notebook    | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Intel         | DG33BU AAD79951-413         | Desktop     | [9824fedcc4](https://linux-hardware.org/?probe=9824fedcc4) | Aug 16, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [46cd16e708](https://linux-hardware.org/?probe=46cd16e708) | Aug 13, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| Advance       | AN-5431                     | Notebook    | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS0XD00    | Notebook    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [5b80d3040f](https://linux-hardware.org/?probe=5b80d3040f) | Jul 25, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [771ef872d9](https://linux-hardware.org/?probe=771ef872d9) | Jul 25, 2021 |
| Dell          | Latitude E5540              | Notebook    | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo        | ThinkPad L460 20FVA0G400    | Notebook    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [95fcf3868f](https://linux-hardware.org/?probe=95fcf3868f) | Jun 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cebf94c181](https://linux-hardware.org/?probe=cebf94c181) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | 8054                        | Desktop     | [b0662fd84b](https://linux-hardware.org/?probe=b0662fd84b) | May 30, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| HP            | 8054                        | Desktop     | [37f65c4171](https://linux-hardware.org/?probe=37f65c4171) | May 27, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP            | 2B2F MVB,A                  | All in one  | [093f49b44c](https://linux-hardware.org/?probe=093f49b44c) | May 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a1959c22e0](https://linux-hardware.org/?probe=a1959c22e0) | May 20, 2021 |
| HP            | 240 G7                      | Notebook    | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [930993fd14](https://linux-hardware.org/?probe=930993fd14) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [f7a3ab5c2f](https://linux-hardware.org/?probe=f7a3ab5c2f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [6eb605ae36](https://linux-hardware.org/?probe=6eb605ae36) | Apr 21, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [642a8e122e](https://linux-hardware.org/?probe=642a8e122e) | Apr 18, 2021 |
| Toshiba       | Satellite L35               | Notebook    | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [4bd5425a6b](https://linux-hardware.org/?probe=4bd5425a6b) | Apr 11, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| HP            | 14                          | Notebook    | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [b02d3fa1c0](https://linux-hardware.org/?probe=b02d3fa1c0) | Apr 04, 2021 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [91ae7f221c](https://linux-hardware.org/?probe=91ae7f221c) | Apr 01, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell          | Latitude E5470              | Notebook    | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [860e86fde0](https://linux-hardware.org/?probe=860e86fde0) | Mar 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [4d1099b04c](https://linux-hardware.org/?probe=4d1099b04c) | Mar 18, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba       | Satellite A665              | Notebook    | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [96dd155871](https://linux-hardware.org/?probe=96dd155871) | Mar 07, 2021 |
| Intel         | H61                         | Desktop     | [77b62ac54a](https://linux-hardware.org/?probe=77b62ac54a) | Mar 05, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [ccb97bb311](https://linux-hardware.org/?probe=ccb97bb311) | Feb 23, 2021 |
| HP            | ProBook 5330m               | Notebook    | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer         | Blade                       | Notebook    | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| PCChips       | P49G                        | Desktop     | [a2f19ae622](https://linux-hardware.org/?probe=a2f19ae622) | Feb 17, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [05d5a888d4](https://linux-hardware.org/?probe=05d5a888d4) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c4f6a52387](https://linux-hardware.org/?probe=c4f6a52387) | Feb 13, 2021 |
| Intel         | D945GTP AAC97834-305        | Desktop     | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [c577103201](https://linux-hardware.org/?probe=c577103201) | Jan 02, 2021 |
| Dell          | G5 5505                     | Notebook    | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell          | Latitude E5470              | Notebook    | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [35757b1c8c](https://linux-hardware.org/?probe=35757b1c8c) | Dec 06, 2020 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [228dc321d9](https://linux-hardware.org/?probe=228dc321d9) | Dec 05, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [f0c3c358a0](https://linux-hardware.org/?probe=f0c3c358a0) | Dec 03, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5837b78f0c](https://linux-hardware.org/?probe=5837b78f0c) | Nov 26, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP            | 14                          | Notebook    | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell          | Latitude 3440               | Notebook    | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [751f746aaf](https://linux-hardware.org/?probe=751f746aaf) | Nov 09, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [9a0e5bd73b](https://linux-hardware.org/?probe=9a0e5bd73b) | Oct 31, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [8d1e7af345](https://linux-hardware.org/?probe=8d1e7af345) | Oct 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [80aa8797b0](https://linux-hardware.org/?probe=80aa8797b0) | Oct 29, 2020 |
| MSI           | B360M PRO-VH                | Desktop     | [d8eb2de621](https://linux-hardware.org/?probe=d8eb2de621) | Oct 21, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [943240cc2a](https://linux-hardware.org/?probe=943240cc2a) | Oct 09, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [8987176239](https://linux-hardware.org/?probe=8987176239) | Sep 28, 2020 |
| HP            | 240 G7                      | Notebook    | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Lenovo        | ThinkPad T470 20HES0JQ00    | Notebook    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| MSI           | H81M-E33                    | Desktop     | [313883253c](https://linux-hardware.org/?probe=313883253c) | Sep 07, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [47c7bf1c93](https://linux-hardware.org/?probe=47c7bf1c93) | Aug 30, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ac15dbee9](https://linux-hardware.org/?probe=3ac15dbee9) | Aug 28, 2020 |
| Lenovo        | G475 20080                  | Notebook    | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba       | Satellite C845              | Notebook    | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [31a8ca3766](https://linux-hardware.org/?probe=31a8ca3766) | Aug 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2098b09526](https://linux-hardware.org/?probe=2098b09526) | Aug 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [39ccf30487](https://linux-hardware.org/?probe=39ccf30487) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [2adefb78ad](https://linux-hardware.org/?probe=2adefb78ad) | Aug 13, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba       | Satellite L45-B             | Notebook    | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [02c231ca67](https://linux-hardware.org/?probe=02c231ca67) | Jul 27, 2020 |
| HP            | 245 G3                      | Notebook    | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fda411a3d7](https://linux-hardware.org/?probe=fda411a3d7) | Jul 24, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4e0fee8549](https://linux-hardware.org/?probe=4e0fee8549) | Jul 20, 2020 |
| Intel         | DG31PR AAD97573-305         | Desktop     | [e3bd0984ee](https://linux-hardware.org/?probe=e3bd0984ee) | Jul 17, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [2e847ac1d0](https://linux-hardware.org/?probe=2e847ac1d0) | Jul 16, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b0f11672bb](https://linux-hardware.org/?probe=b0f11672bb) | Jul 05, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4716a84af9](https://linux-hardware.org/?probe=4716a84af9) | Jul 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP            | 09E8h                       | Desktop     | [d9b1f1bf60](https://linux-hardware.org/?probe=d9b1f1bf60) | Jun 28, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [f073723231](https://linux-hardware.org/?probe=f073723231) | Jun 27, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [7f8abda42c](https://linux-hardware.org/?probe=7f8abda42c) | Jun 27, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [aef4861ab1](https://linux-hardware.org/?probe=aef4861ab1) | Jun 25, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP            | 3397                        | Desktop     | [3421ad000d](https://linux-hardware.org/?probe=3421ad000d) | Jun 21, 2020 |
| HP            | 09E8h                       | Desktop     | [14e6514858](https://linux-hardware.org/?probe=14e6514858) | Jun 20, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [3b021c1b62](https://linux-hardware.org/?probe=3b021c1b62) | Jun 17, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [821a7a7b85](https://linux-hardware.org/?probe=821a7a7b85) | Jun 17, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Dell          | 0DR845                      | Desktop     | [cb4b80e381](https://linux-hardware.org/?probe=cb4b80e381) | Jun 14, 2020 |
| Dell          | 0DR845                      | Desktop     | [107ec57e94](https://linux-hardware.org/?probe=107ec57e94) | Jun 13, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [615d9bbafb](https://linux-hardware.org/?probe=615d9bbafb) | Jun 07, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [db6aa4b6fa](https://linux-hardware.org/?probe=db6aa4b6fa) | Jun 07, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b803424e29](https://linux-hardware.org/?probe=b803424e29) | May 31, 2020 |
| HP            | ENVY 15                     | Notebook    | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [ea48f46d27](https://linux-hardware.org/?probe=ea48f46d27) | May 27, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [3d5fc4df20](https://linux-hardware.org/?probe=3d5fc4df20) | May 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4c93d3634b](https://linux-hardware.org/?probe=4c93d3634b) | May 24, 2020 |
| HP            | ENVY 15                     | Notebook    | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Gigabyte      | G41MT-S2                    | Desktop     | [f8702707c6](https://linux-hardware.org/?probe=f8702707c6) | May 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Intel         | D945GCNL AAD97184-102       | Desktop     | [72691e43eb](https://linux-hardware.org/?probe=72691e43eb) | May 14, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [404ef9032e](https://linux-hardware.org/?probe=404ef9032e) | May 12, 2020 |
| Dell          | Precision M4600             | Notebook    | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP            | 0A58h                       | Desktop     | [a3a4679ef9](https://linux-hardware.org/?probe=a3a4679ef9) | May 05, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [08c0779e95](https://linux-hardware.org/?probe=08c0779e95) | May 02, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [d5880c1076](https://linux-hardware.org/?probe=d5880c1076) | May 02, 2020 |
| HP            | 450                         | Notebook    | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP            | 450                         | Notebook    | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [eb77b46e2f](https://linux-hardware.org/?probe=eb77b46e2f) | Apr 30, 2020 |
| Dell          | System XPS L502X            | Notebook    | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [e2ab73d9cf](https://linux-hardware.org/?probe=e2ab73d9cf) | Apr 26, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [32546cbd9d](https://linux-hardware.org/?probe=32546cbd9d) | Apr 26, 2020 |
| Dell          | System XPS L502X            | Notebook    | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [d88e072663](https://linux-hardware.org/?probe=d88e072663) | Apr 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [71673b2f86](https://linux-hardware.org/?probe=71673b2f86) | Apr 09, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [6277a6ec0b](https://linux-hardware.org/?probe=6277a6ec0b) | Apr 08, 2020 |
| HP            | 0A60h                       | Desktop     | [e929430fd0](https://linux-hardware.org/?probe=e929430fd0) | Apr 08, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba       | NB505                       | Notebook    | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| PCChips       | P49G                        | Desktop     | [57f11f5c76](https://linux-hardware.org/?probe=57f11f5c76) | Apr 04, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony          | SVF15A17CLB                 | Notebook    | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| HP            | 3397                        | Desktop     | [71764f18dd](https://linux-hardware.org/?probe=71764f18dd) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [57904c47e1](https://linux-hardware.org/?probe=57904c47e1) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [4c44586ba9](https://linux-hardware.org/?probe=4c44586ba9) | Mar 21, 2020 |
| PCChips       | P49G                        | Desktop     | [1cedc0a4f7](https://linux-hardware.org/?probe=1cedc0a4f7) | Mar 17, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [145e6998fc](https://linux-hardware.org/?probe=145e6998fc) | Mar 06, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [baaf155c68](https://linux-hardware.org/?probe=baaf155c68) | Mar 04, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [6a5c6cf0dc](https://linux-hardware.org/?probe=6a5c6cf0dc) | Feb 23, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [8a4a2a6066](https://linux-hardware.org/?probe=8a4a2a6066) | Feb 21, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [4ba8cd9ca2](https://linux-hardware.org/?probe=4ba8cd9ca2) | Feb 16, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [19086b2ac2](https://linux-hardware.org/?probe=19086b2ac2) | Feb 16, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [7ae91dcf15](https://linux-hardware.org/?probe=7ae91dcf15) | Jan 21, 2020 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [12b760b696](https://linux-hardware.org/?probe=12b760b696) | Jan 20, 2020 |
| ASUSTek       | M5A97                       | Desktop     | [a381f0be23](https://linux-hardware.org/?probe=a381f0be23) | Jan 17, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5b67f6ed83](https://linux-hardware.org/?probe=5b67f6ed83) | Dec 26, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [c05b5b48de](https://linux-hardware.org/?probe=c05b5b48de) | Dec 05, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [3862b040a2](https://linux-hardware.org/?probe=3862b040a2) | Dec 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [50ef5c54ef](https://linux-hardware.org/?probe=50ef5c54ef) | Nov 29, 2019 |
| HP            | Pavilion g4                 | Notebook    | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell          | Latitude 5580               | Notebook    | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell          | Latitude 5580               | Notebook    | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Foxconn       | A76GMV                      | Desktop     | [ddfa1ad143](https://linux-hardware.org/?probe=ddfa1ad143) | Oct 22, 2019 |
| Dell          | Inspiron 3443               | Notebook    | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP            | ProBook 440 G4              | Notebook    | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [048c1a4f90](https://linux-hardware.org/?probe=048c1a4f90) | Jun 25, 2019 |
| Gigabyte      | A55M-DS2                    | Desktop     | [9e2c603e49](https://linux-hardware.org/?probe=9e2c603e49) | Jun 23, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [07dd5b8424](https://linux-hardware.org/?probe=07dd5b8424) | Jun 14, 2019 |
| Toshiba       | Satellite P755              | Notebook    | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5ca60ce3ac](https://linux-hardware.org/?probe=5ca60ce3ac) | Apr 06, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [c7dd2b6e26](https://linux-hardware.org/?probe=c7dd2b6e26) | Mar 26, 2019 |
| Lenovo        | B50-80 80EW                 | Notebook    | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo        | B50-80 80EW                 | Notebook    | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| AMI           | Cherry Trail CR             | Desktop     | [e248592999](https://linux-hardware.org/?probe=e248592999) | Nov 03, 2018 |
| HP            | 1000                        | Notebook    | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [765c79328e](https://linux-hardware.org/?probe=765c79328e) | Jun 26, 2018 |
| ECS           | MCP61M-M3                   | Desktop     | [a51a8c96df](https://linux-hardware.org/?probe=a51a8c96df) | Apr 08, 2018 |
| HP            | Stream x360 Convertible ... | Convertible | [be4128010b](https://linux-hardware.org/?probe=be4128010b) | Feb 12, 2018 |
| HP            | 1000                        | Notebook    | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony          | VGN-FW170J                  | Notebook    | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP            | 1000                        | Notebook    | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony          | VGN-FW170J                  | Notebook    | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer          | Aspire S3                   | Notebook    | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer          | Aspire S3                   | Notebook    | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |
| HP            | Stream x360 Convertible ... | Convertible | [e721d571fe](https://linux-hardware.org/?probe=e721d571fe) | May 15, 2017 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4d498130d3](https://linux-hardware.org/?probe=4d498130d3) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [58bc94c592](https://linux-hardware.org/?probe=58bc94c592) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [7201ee94b8](https://linux-hardware.org/?probe=7201ee94b8) | Nov 07, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4567d9bca4](https://linux-hardware.org/?probe=4567d9bca4) | Nov 02, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 56        | 17.78%  |
| Ubuntu 18.04                 | 21        | 6.67%   |
| OpenMandriva 4.3             | 14        | 4.44%   |
| OpenMandriva 4.2             | 12        | 3.81%   |
| Zorin 15                     | 10        | 3.17%   |
| Ubuntu 22.04                 | 10        | 3.17%   |
| Ubuntu 19.10                 | 9         | 2.86%   |
| Manjaro                      | 8         | 2.54%   |
| Debian 11                    | 7         | 2.22%   |
| KDE neon 20.04               | 6         | 1.9%    |
| Arch                         | 6         | 1.9%    |
| Xubuntu 20.04                | 5         | 1.59%   |
| ROSA R9                      | 5         | 1.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.59%   |
| Kubuntu 20.04                | 5         | 1.59%   |
| Debian 10                    | 5         | 1.59%   |
| Ubuntu 21.10                 | 4         | 1.27%   |
| Ubuntu 21.04                 | 4         | 1.27%   |
| Pop!_OS 21.10                | 4         | 1.27%   |
| Linux Mint 20.3              | 4         | 1.27%   |
| Linux Mint 20.1              | 4         | 1.27%   |
| Linux Mint 19.3              | 4         | 1.27%   |
| CentOS 8                     | 4         | 1.27%   |
| Ubuntu 19.04                 | 3         | 0.95%   |
| ROSA R11.1                   | 3         | 0.95%   |
| ROSA R10                     | 3         | 0.95%   |
| Pop!_OS 20.10                | 3         | 0.95%   |
| OpenMandriva 4.90            | 3         | 0.95%   |
| Manjaro 21.2.6               | 3         | 0.95%   |
| Manjaro 20.1                 | 3         | 0.95%   |
| Fedora 32                    | 3         | 0.95%   |
| Elementary 5.1.7             | 3         | 0.95%   |
| Arch Rolling                 | 3         | 0.95%   |
| Zorin 16                     | 2         | 0.63%   |
| Ubuntu MATE 18.04            | 2         | 0.63%   |
| ROSA R8                      | 2         | 0.63%   |
| ROSA R11                     | 2         | 0.63%   |
| ROSA 12.2                    | 2         | 0.63%   |
| Pop!_OS 22.04                | 2         | 0.63%   |
| Pop!_OS 20.04                | 2         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 103       | 33.66%  |
| OpenMandriva | 30        | 9.8%    |
| Linux Mint   | 21        | 6.86%   |
| Manjaro      | 16        | 5.23%   |
| ROSA         | 15        | 4.9%    |
| Zorin        | 12        | 3.92%   |
| Pop!_OS      | 12        | 3.92%   |
| Debian       | 12        | 3.92%   |
| Fedora       | 10        | 3.27%   |
| Arch         | 10        | 3.27%   |
| Ubuntu MATE  | 7         | 2.29%   |
| openSUSE     | 7         | 2.29%   |
| Xubuntu      | 6         | 1.96%   |
| KDE neon     | 6         | 1.96%   |
| Kubuntu      | 5         | 1.63%   |
| Endless      | 5         | 1.63%   |
| Lubuntu      | 4         | 1.31%   |
| Elementary   | 4         | 1.31%   |
| CentOS       | 4         | 1.31%   |
| Linux Lite   | 3         | 0.98%   |
| Ubuntu Unity | 2         | 0.65%   |
| Peppermint   | 2         | 0.65%   |
| Void Linux   | 1         | 0.33%   |
| Solus        | 1         | 0.33%   |
| Parrot       | 1         | 0.33%   |
| MX           | 1         | 0.33%   |
| Manjaro-ARM  | 1         | 0.33%   |
| LMDE         | 1         | 0.33%   |
| Laxer OS     | 1         | 0.33%   |
| Kali         | 1         | 0.33%   |
| Feren OS     | 1         | 0.33%   |
| ArcoLinux    | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 14        | 4.06%   |
| 5.10.14-desktop-1omv4002        | 10        | 2.9%    |
| 5.3.0-40-generic                | 8         | 2.32%   |
| 5.4.0-66-generic                | 5         | 1.45%   |
| 5.4.0-28-generic                | 5         | 1.45%   |
| 5.13.0-40-generic               | 5         | 1.45%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 5         | 1.45%   |
| 5.4.0-70-generic                | 4         | 1.16%   |
| 5.4.0-58-generic                | 4         | 1.16%   |
| 5.4.0-52-generic                | 4         | 1.16%   |
| 5.4.0-42-generic                | 4         | 1.16%   |
| 5.4.0-37-generic                | 4         | 1.16%   |
| 5.4.0-31-generic                | 4         | 1.16%   |
| 5.4.0-26-generic                | 4         | 1.16%   |
| 5.11.0-40-generic               | 4         | 1.16%   |
| 5.10.0-13-amd64                 | 4         | 1.16%   |
| 5.4.0-73-generic                | 3         | 0.87%   |
| 5.4.0-40-generic                | 3         | 0.87%   |
| 5.4.0-39-generic                | 3         | 0.87%   |
| 5.4.0-33-generic                | 3         | 0.87%   |
| 5.3.0-46-generic                | 3         | 0.87%   |
| 5.3.0-42-generic                | 3         | 0.87%   |
| 5.3.0-26-generic                | 3         | 0.87%   |
| 5.18.12-desktop-3omv4090        | 3         | 0.87%   |
| 5.17.5-arch1-1                  | 3         | 0.87%   |
| 5.15.0-25-generic               | 3         | 0.87%   |
| 5.13.0-51-generic               | 3         | 0.87%   |
| 5.13.0-30-generic               | 3         | 0.87%   |
| 5.11.0-27-generic               | 3         | 0.87%   |
| 5.11.0-25-generic               | 3         | 0.87%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.87%   |
| 4.18.0-15-generic               | 3         | 0.87%   |
| 5.9.11-3-MANJARO                | 2         | 0.58%   |
| 5.8.0-63-generic                | 2         | 0.58%   |
| 5.8.0-48-generic                | 2         | 0.58%   |
| 5.8.0-44-generic                | 2         | 0.58%   |
| 5.4.0-81-generic                | 2         | 0.58%   |
| 5.4.0-7642-generic              | 2         | 0.58%   |
| 5.4.0-65-generic                | 2         | 0.58%   |
| 5.4.0-54-generic                | 2         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 20.99%  |
| 5.3.0   | 23        | 7.1%    |
| 5.11.0  | 20        | 6.17%   |
| 5.13.0  | 18        | 5.56%   |
| 4.15.0  | 18        | 5.56%   |
| 5.15.0  | 15        | 4.63%   |
| 5.16.7  | 14        | 4.32%   |
| 5.8.0   | 13        | 4.01%   |
| 4.18.0  | 12        | 3.7%    |
| 5.10.14 | 10        | 3.09%   |
| 5.10.0  | 8         | 2.47%   |
| 5.0.0   | 8         | 2.47%   |
| 4.9.20  | 5         | 1.54%   |
| 5.17.5  | 4         | 1.23%   |
| 4.9.60  | 4         | 1.23%   |
| 5.18.12 | 3         | 0.93%   |
| 5.17.1  | 3         | 0.93%   |
| 5.9.11  | 2         | 0.62%   |
| 5.4.83  | 2         | 0.62%   |
| 5.3.18  | 2         | 0.62%   |
| 5.19.0  | 2         | 0.62%   |
| 5.16.19 | 2         | 0.62%   |
| 5.16.0  | 2         | 0.62%   |
| 5.15.49 | 2         | 0.62%   |
| 5.12.10 | 2         | 0.62%   |
| 5.11.12 | 2         | 0.62%   |
| 5.10.74 | 2         | 0.62%   |
| 4.19.0  | 2         | 0.62%   |
| 5.9.16  | 1         | 0.31%   |
| 5.8.7   | 1         | 0.31%   |
| 5.8.6   | 1         | 0.31%   |
| 5.8.4   | 1         | 0.31%   |
| 5.8.11  | 1         | 0.31%   |
| 5.7.9   | 1         | 0.31%   |
| 5.7.4   | 1         | 0.31%   |
| 5.7.17  | 1         | 0.31%   |
| 5.7.14  | 1         | 0.31%   |
| 5.6.6   | 1         | 0.31%   |
| 5.6.19  | 1         | 0.31%   |
| 5.6.18  | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 23.13%  |
| 5.15    | 26        | 8.13%   |
| 5.3     | 25        | 7.81%   |
| 5.10    | 25        | 7.81%   |
| 5.11    | 24        | 7.5%    |
| 5.16    | 19        | 5.94%   |
| 5.13    | 19        | 5.94%   |
| 4.15    | 18        | 5.63%   |
| 5.8     | 17        | 5.31%   |
| 4.18    | 12        | 3.75%   |
| 5.17    | 10        | 3.13%   |
| 5.0     | 8         | 2.5%    |
| 4.9     | 8         | 2.5%    |
| 5.6     | 5         | 1.56%   |
| 5.18    | 5         | 1.56%   |
| 5.7     | 4         | 1.25%   |
| 5.12    | 4         | 1.25%   |
| 5.9     | 3         | 0.94%   |
| 5.19    | 3         | 0.94%   |
| 5.14    | 3         | 0.94%   |
| 4.19    | 2         | 0.63%   |
| 4.1     | 2         | 0.63%   |
| 5.1     | 1         | 0.31%   |
| 4.8     | 1         | 0.31%   |
| 4.4     | 1         | 0.31%   |
| 4.16    | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 274       | 93.84%  |
| i686    | 16        | 5.48%   |
| aarch64 | 2         | 0.68%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 135       | 44.55%  |
| KDE5            | 51        | 16.83%  |
| XFCE            | 27        | 8.91%   |
| Unknown         | 24        | 7.92%   |
| X-Cinnamon      | 17        | 5.61%   |
| MATE            | 12        | 3.96%   |
| KDE4            | 9         | 2.97%   |
| KDE             | 8         | 2.64%   |
| Pantheon        | 4         | 1.32%   |
| LXDE            | 4         | 1.32%   |
| Unity           | 2         | 0.66%   |
| LXQt            | 2         | 0.66%   |
| i3              | 2         | 0.66%   |
| GNOME Flashback | 2         | 0.66%   |
| Budgie          | 2         | 0.66%   |
| spectrwm        | 1         | 0.33%   |
| awesome         | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 243       | 81%     |
| Wayland | 36        | 12%     |
| Unknown | 20        | 6.67%   |
| Tty     | 1         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 150       | 49.34%  |
| SDDM    | 46        | 15.13%  |
| GDM     | 41        | 13.49%  |
| LightDM | 26        | 8.55%   |
| GDM3    | 25        | 8.22%   |
| KDM     | 9         | 2.96%   |
| TDM     | 6         | 1.97%   |
| XDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_PE   | 150       | 50.17%  |
| en_US   | 71        | 23.75%  |
| es_ES   | 30        | 10.03%  |
| Unknown | 28        | 9.36%   |
| en_GB   | 4         | 1.34%   |
| C       | 4         | 1.34%   |
| es_MX   | 3         | 1%      |
| it_IT   | 2         | 0.67%   |
| en_CA   | 2         | 0.67%   |
| fr_FR   | 1         | 0.33%   |
| es_US   | 1         | 0.33%   |
| es_CO   | 1         | 0.33%   |
| Default | 1         | 0.33%   |
| ca_ES   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 155       | 52.54%  |
| EFI  | 140       | 47.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 233       | 77.67%  |
| Overlay | 30        | 10%     |
| Unknown | 15        | 5%      |
| Btrfs   | 12        | 4%      |
| Xfs     | 7         | 2.33%   |
| Ext3    | 3         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 180       | 60.2%   |
| GPT     | 86        | 28.76%  |
| MBR     | 33        | 11.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 253       | 84.62%  |
| Yes       | 46        | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 58.45%  |
| Yes       | 123       | 41.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 55        | 18.9%   |
| Hewlett-Packard         | 54        | 18.56%  |
| ASUSTek Computer        | 32        | 11%     |
| Gigabyte Technology     | 29        | 9.97%   |
| Dell                    | 24        | 8.25%   |
| Intel                   | 23        | 7.9%    |
| MSI                     | 16        | 5.5%    |
| Toshiba                 | 12        | 4.12%   |
| Acer                    | 12        | 4.12%   |
| Foxconn                 | 6         | 2.06%   |
| Sony                    | 4         | 1.37%   |
| ASRock                  | 4         | 1.37%   |
| Raspberry Pi Foundation | 2         | 0.69%   |
| Chuwi                   | 2         | 0.69%   |
| Unknown                 | 2         | 0.69%   |
| SZMZ                    | 1         | 0.34%   |
| Samsung Electronics     | 1         | 0.34%   |
| Razer                   | 1         | 0.34%   |
| PCChips                 | 1         | 0.34%   |
| Microsoft               | 1         | 0.34%   |
| HUAWEI                  | 1         | 0.34%   |
| efirstview              | 1         | 0.34%   |
| ECS                     | 1         | 0.34%   |
| Compal                  | 1         | 0.34%   |
| Biostar                 | 1         | 0.34%   |
| AZW                     | 1         | 0.34%   |
| Apple                   | 1         | 0.34%   |
| AMI                     | 1         | 0.34%   |
| Advance                 | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                   | 4         | 1.37%   |
| MSI MS-7721                              | 3         | 1.03%   |
| Lenovo V310-15ISK 80SY                   | 3         | 1.03%   |
| HP Pavilion Laptop 15-cw1xxx             | 3         | 1.03%   |
| Gigabyte 970A-DS3P                       | 3         | 1.03%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.69%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.69%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.69%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 2         | 0.69%   |
| Intel DH55PJ AAE93812-303                | 2         | 0.69%   |
| HP ProBook 645 G4                        | 2         | 0.69%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.69%   |
| HP 450                                   | 2         | 0.69%   |
| HP 14                                    | 2         | 0.69%   |
| Gigabyte Z77X-UD5H                       | 2         | 0.69%   |
| Gigabyte B75M-D3H                        | 2         | 0.69%   |
| Gigabyte A520M H                         | 2         | 0.69%   |
| Foxconn 500B Microtower                  | 2         | 0.69%   |
| Dell XPS 13 9360                         | 2         | 0.69%   |
| Dell OptiPlex 7010                       | 2         | 0.69%   |
| ASUS TUF Gaming B550M-PLUS               | 2         | 0.69%   |
| ASUS PRIME X570-P                        | 2         | 0.69%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.69%   |
| ASUS All Series                          | 2         | 0.69%   |
| Unknown                                  | 2         | 0.69%   |
| Toshiba Satellite P755                   | 1         | 0.34%   |
| Toshiba Satellite L855                   | 1         | 0.34%   |
| Toshiba Satellite L45-B                  | 1         | 0.34%   |
| Toshiba Satellite L35                    | 1         | 0.34%   |
| Toshiba Satellite E205                   | 1         | 0.34%   |
| Toshiba Satellite C845                   | 1         | 0.34%   |
| Toshiba Satellite C655D                  | 1         | 0.34%   |
| Toshiba Satellite C645                   | 1         | 0.34%   |
| Toshiba Satellite C55-B                  | 1         | 0.34%   |
| Toshiba Satellite A665                   | 1         | 0.34%   |
| Toshiba QOSMIO X775                      | 1         | 0.34%   |
| Toshiba NB505                            | 1         | 0.34%   |
| SZMZ X99 DUAL Z8                         | 1         | 0.34%   |
| Sony VPCEC2JFX                           | 1         | 0.34%   |
| Sony VGN-FW56M                           | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 14        | 4.81%   |
| Lenovo IdeaPad     | 14        | 4.81%   |
| HP Pavilion        | 14        | 4.81%   |
| Toshiba Satellite  | 10        | 3.44%   |
| Acer Aspire        | 10        | 3.44%   |
| Dell Latitude      | 7         | 2.41%   |
| HP ProBook         | 6         | 2.06%   |
| HP Compaq          | 6         | 2.06%   |
| Dell Inspiron      | 6         | 2.06%   |
| ASUS VivoBook      | 6         | 2.06%   |
| HP Laptop          | 5         | 1.72%   |
| Dell OptiPlex      | 5         | 1.72%   |
| ASUS PRIME         | 5         | 1.72%   |
| Lenovo V330-15IKB  | 4         | 1.37%   |
| Lenovo ThinkCentre | 4         | 1.37%   |
| MSI MS-7721        | 3         | 1.03%   |
| Lenovo V310-15ISK  | 3         | 1.03%   |
| Lenovo Legion      | 3         | 1.03%   |
| HP ENVY            | 3         | 1.03%   |
| Gigabyte 970A-DS3P | 3         | 1.03%   |
| ASUS TUF           | 3         | 1.03%   |
| RPi Raspberry      | 2         | 0.69%   |
| Lenovo Yoga        | 2         | 0.69%   |
| Intel DH61WW       | 2         | 0.69%   |
| Intel DH55PJ       | 2         | 0.69%   |
| Intel DG31PR       | 2         | 0.69%   |
| Intel D945GCNL     | 2         | 0.69%   |
| HP ZBook           | 2         | 0.69%   |
| HP Stream          | 2         | 0.69%   |
| HP EliteDesk       | 2         | 0.69%   |
| HP 450             | 2         | 0.69%   |
| HP 240             | 2         | 0.69%   |
| HP 14              | 2         | 0.69%   |
| Gigabyte Z77X-UD5H | 2         | 0.69%   |
| Gigabyte B75M-D3H  | 2         | 0.69%   |
| Gigabyte A520M     | 2         | 0.69%   |
| Foxconn H61MXE     | 2         | 0.69%   |
| Foxconn 500B       | 2         | 0.69%   |
| Dell XPS           | 2         | 0.69%   |
| ASUS ROG           | 2         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 36        | 12.37%  |
| 2019    | 31        | 10.65%  |
| 2012    | 30        | 10.31%  |
| 2018    | 26        | 8.93%   |
| 2016    | 21        | 7.22%   |
| 2011    | 21        | 7.22%   |
| 2017    | 20        | 6.87%   |
| 2013    | 20        | 6.87%   |
| 2014    | 18        | 6.19%   |
| 2010    | 16        | 5.5%    |
| 2015    | 14        | 4.81%   |
| 2008    | 9         | 3.09%   |
| 2007    | 9         | 3.09%   |
| 2021    | 7         | 2.41%   |
| 2009    | 7         | 2.41%   |
| 2006    | 3         | 1.03%   |
| Unknown | 2         | 0.69%   |
| 2004    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 167       | 57.39%  |
| Desktop        | 111       | 38.14%  |
| Convertible    | 5         | 1.72%   |
| System on chip | 2         | 0.69%   |
| Tablet         | 2         | 0.69%   |
| Mini pc        | 2         | 0.69%   |
| All in one     | 2         | 0.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 272       | 93.47%  |
| Enabled  | 19        | 6.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 291       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 73        | 24.33%  |
| 8.01-16.0   | 71        | 23.67%  |
| 3.01-4.0    | 69        | 23%     |
| 16.01-24.0  | 49        | 16.33%  |
| 32.01-64.0  | 11        | 3.67%   |
| 1.01-2.0    | 11        | 3.67%   |
| 2.01-3.0    | 6         | 2%      |
| 24.01-32.0  | 4         | 1.33%   |
| 64.01-256.0 | 3         | 1%      |
| 0.51-1.0    | 3         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 117       | 36%     |
| 2.01-3.0   | 89        | 27.38%  |
| 4.01-8.0   | 41        | 12.62%  |
| 3.01-4.0   | 36        | 11.08%  |
| 0.51-1.0   | 31        | 9.54%   |
| 8.01-16.0  | 9         | 2.77%   |
| 16.01-24.0 | 1         | 0.31%   |
| 0.01-0.5   | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 197       | 66.11%  |
| 2      | 76        | 25.5%   |
| 3      | 15        | 5.03%   |
| 4      | 8         | 2.68%   |
| 5      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 57.39%  |
| Yes       | 124       | 42.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 262       | 89.42%  |
| No        | 31        | 10.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 71.28%  |
| No        | 85        | 28.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 57.34%  |
| No        | 125       | 42.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Peru    | 291       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lima                  | 201       | 67%     |
| Arequipa              | 24        | 8%      |
| Trujillo              | 21        | 7%      |
| Tacna                 | 5         | 1.67%   |
| Piura                 | 5         | 1.67%   |
| Huancayo              | 5         | 1.67%   |
| Cusco                 | 5         | 1.67%   |
| Chiclayo              | 5         | 1.67%   |
| Moquegua              | 4         | 1.33%   |
| Junin                 | 2         | 0.67%   |
| Ica                   | 2         | 0.67%   |
| Distrito de Lima      | 2         | 0.67%   |
| Callao                | 2         | 0.67%   |
| Barranco              | 2         | 0.67%   |
| Abancay               | 2         | 0.67%   |
| Villa                 | 1         | 0.33%   |
| Sullana               | 1         | 0.33%   |
| Santiago de Surco     | 1         | 0.33%   |
| San Vicente de Canete | 1         | 0.33%   |
| San Isidro            | 1         | 0.33%   |
| San Borja             | 1         | 0.33%   |
| Punta Colorada        | 1         | 0.33%   |
| Puno                  | 1         | 0.33%   |
| Pucallpa              | 1         | 0.33%   |
| Oxapampa              | 1         | 0.33%   |
| La Libertad           | 1         | 0.33%   |
| Juliaca               | 1         | 0.33%   |
| Iquitos               | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 84        | 129    | 21.99%  |
| WDC                            | 72        | 101    | 18.85%  |
| Toshiba                        | 50        | 59     | 13.09%  |
| Kingston                       | 41        | 51     | 10.73%  |
| Samsung Electronics            | 28        | 37     | 7.33%   |
| Crucial                        | 13        | 17     | 3.4%    |
| SanDisk                        | 12        | 14     | 3.14%   |
| Unknown                        | 7         | 11     | 1.83%   |
| Hitachi                        | 7         | 11     | 1.83%   |
| SK hynix                       | 6         | 8      | 1.57%   |
| Hewlett-Packard                | 6         | 7      | 1.57%   |
| Intel                          | 5         | 6      | 1.31%   |
| LITEON                         | 4         | 4      | 1.05%   |
| KIOXIA                         | 4         | 5      | 1.05%   |
| HGST                           | 4         | 4      | 1.05%   |
| A-DATA Technology              | 4         | 4      | 1.05%   |
| Silicon Motion                 | 3         | 3      | 0.79%   |
| PNY                            | 3         | 3      | 0.79%   |
| Micron/Crucial Technology      | 3         | 3      | 0.79%   |
| Micron Technology              | 3         | 3      | 0.79%   |
| Team                           | 2         | 2      | 0.52%   |
| China                          | 2         | 2      | 0.52%   |
| WD MediaMax                    | 1         | 1      | 0.26%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.26%   |
| UMIS                           | 1         | 1      | 0.26%   |
| TO Exter                       | 1         | 2      | 0.26%   |
| Solid State Storage Technology | 1         | 1      | 0.26%   |
| Phison                         | 1         | 1      | 0.26%   |
| NGFF                           | 1         | 1      | 0.26%   |
| Netac                          | 1         | 1      | 0.26%   |
| Mushkin                        | 1         | 2      | 0.26%   |
| Maxone                         | 1         | 2      | 0.26%   |
| KingSpec                       | 1         | 1      | 0.26%   |
| KESU                           | 1         | 1      | 0.26%   |
| ITHOO                          | 1         | 1      | 0.26%   |
| GLOWAY                         | 1         | 1      | 0.26%   |
| Gigabyte Technology            | 1         | 1      | 0.26%   |
| Fujitsu                        | 1         | 1      | 0.26%   |
| Dogfish                        | 1         | 1      | 0.26%   |
| Apple                          | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 18        | 4.29%   |
| Seagate ST500DM002-1BD142 500GB      | 13        | 3.1%    |
| Kingston SA400S37240G 240GB SSD      | 12        | 2.86%   |
| Toshiba MQ01ABD100 1TB               | 10        | 2.38%   |
| Toshiba MQ04ABF100 1TB               | 9         | 2.14%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 6         | 1.43%   |
| Seagate ST1000DM010-2EP102 1TB       | 6         | 1.43%   |
| Kingston SA400S37480G 480GB SSD      | 6         | 1.43%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 1.43%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.19%   |
| HP SSD S700 500GB                    | 5         | 1.19%   |
| WDC WD10SPZX-24Z10 1TB               | 4         | 0.95%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.95%   |
| Seagate ST3500418AS 500GB            | 4         | 0.95%   |
| Seagate ST3500413AS 500GB            | 4         | 0.95%   |
| Seagate ST2000DM001-1ER164 2TB       | 4         | 0.95%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.71%   |
| WDC WD10JPCX-24UE4T0 1TB             | 3         | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.71%   |
| Seagate ST9500325AS 500GB            | 3         | 0.71%   |
| Seagate ST3500312CS 500GB            | 3         | 0.71%   |
| Seagate ST2000DM006-2DM164 2TB       | 3         | 0.71%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.71%   |
| Kingston SNVS250G 250GB              | 3         | 0.71%   |
| Kingston NVMe SSD Drive 500GB        | 3         | 0.71%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.48%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.48%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 2         | 0.48%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.48%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2         | 0.48%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.48%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.48%   |
| Unknown MMC Card  32GB               | 2         | 0.48%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.48%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.48%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.48%   |
| Toshiba DT01ACA050 500GB             | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 122    | 39.61%  |
| WDC                 | 50        | 65     | 24.15%  |
| Toshiba             | 49        | 58     | 23.67%  |
| Samsung Electronics | 12        | 16     | 5.8%    |
| Hitachi             | 7         | 11     | 3.38%   |
| HGST                | 4         | 4      | 1.93%   |
| KESU                | 1         | 1      | 0.48%   |
| Fujitsu             | 1         | 1      | 0.48%   |
| Apple               | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 32        | 37     | 30.48%  |
| WDC                 | 22        | 28     | 20.95%  |
| Crucial             | 10        | 13     | 9.52%   |
| Hewlett-Packard     | 6         | 6      | 5.71%   |
| SanDisk             | 5         | 7      | 4.76%   |
| LITEON              | 4         | 4      | 3.81%   |
| A-DATA Technology   | 4         | 4      | 3.81%   |
| Seagate             | 3         | 7      | 2.86%   |
| Samsung Electronics | 3         | 3      | 2.86%   |
| PNY                 | 3         | 3      | 2.86%   |
| Team                | 2         | 2      | 1.9%    |
| China               | 2         | 2      | 1.9%    |
| TO Exter            | 1         | 2      | 0.95%   |
| SK hynix            | 1         | 2      | 0.95%   |
| NGFF                | 1         | 1      | 0.95%   |
| Netac               | 1         | 1      | 0.95%   |
| Maxone              | 1         | 2      | 0.95%   |
| KingSpec            | 1         | 1      | 0.95%   |
| Intel               | 1         | 1      | 0.95%   |
| GLOWAY              | 1         | 1      | 0.95%   |
| Dogfish             | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 190       | 279    | 52.78%  |
| SSD     | 95        | 128    | 26.39%  |
| NVMe    | 65        | 85     | 18.06%  |
| MMC     | 8         | 12     | 2.22%   |
| Unknown | 2         | 2      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 245       | 402    | 75.62%  |
| NVMe | 65        | 85     | 20.06%  |
| MMC  | 8         | 12     | 2.47%   |
| SAS  | 6         | 7      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 243    | 55.52%  |
| 0.51-1.0   | 111       | 134    | 38.28%  |
| 1.01-2.0   | 13        | 22     | 4.48%   |
| 3.01-4.0   | 2         | 3      | 0.69%   |
| 4.01-10.0  | 2         | 4      | 0.69%   |
| 2.01-3.0   | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 76        | 24.6%   |
| 101-250        | 70        | 22.65%  |
| 501-1000       | 57        | 18.45%  |
| 51-100         | 25        | 8.09%   |
| 21-50          | 20        | 6.47%   |
| 1-20           | 19        | 6.15%   |
| 1001-2000      | 17        | 5.5%    |
| 2001-3000      | 12        | 3.88%   |
| More than 3000 | 7         | 2.27%   |
| Unknown        | 6         | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 125       | 39.68%  |
| 21-50          | 63        | 20%     |
| 101-250        | 35        | 11.11%  |
| 251-500        | 29        | 9.21%   |
| 51-100         | 26        | 8.25%   |
| 501-1000       | 17        | 5.4%    |
| 1001-2000      | 9         | 2.86%   |
| Unknown        | 6         | 1.9%    |
| More than 3000 | 3         | 0.95%   |
| 2001-3000      | 2         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3         | 3      | 9.09%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1         | 1      | 3.03%   |
| WDC WDS100T2G0A-00JH30 1TB SSD    | 1         | 1      | 3.03%   |
| WDC WD800BD-00MRA1 80GB           | 1         | 1      | 3.03%   |
| WDC WD3200AAJS-56M0A0 320GB       | 1         | 1      | 3.03%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1         | 1      | 3.03%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 3.03%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 3.03%   |
| Toshiba MK2035GSS 200GB           | 1         | 1      | 3.03%   |
| Toshiba HDWJ110 1TB               | 1         | 1      | 3.03%   |
| Seagate ST980811AS 80GB           | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 3.03%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 3.03%   |
| Seagate ST500DM002-9YN14C 500GB   | 1         | 1      | 3.03%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 3.03%   |
| Seagate ST3250820AS 250GB         | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 3.03%   |
| Seagate ST1000LM014-1EJ164 1TB    | 1         | 1      | 3.03%   |
| Seagate ST1000DM003-9YN162 1TB    | 1         | 1      | 3.03%   |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 1      | 3.03%   |
| Samsung Electronics SP1644N 160GB | 1         | 1      | 3.03%   |
| Samsung Electronics HD161HJ 160GB | 1         | 2      | 3.03%   |
| Kingston SA400S37480G 480GB SSD   | 1         | 1      | 3.03%   |
| Hitachi HTS725050A7E630 500GB     | 1         | 1      | 3.03%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 3.03%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 3      | 3.03%   |
| Hitachi HTS545032B9A302 320GB     | 1         | 1      | 3.03%   |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 3.03%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 3.03%   |
| A-DATA Technology SP550 240GB SSD | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 39.39%  |
| WDC                 | 6         | 6      | 18.18%  |
| Hitachi             | 5         | 7      | 15.15%  |
| Toshiba             | 4         | 4      | 12.12%  |
| Samsung Electronics | 2         | 3      | 6.06%   |
| Kingston            | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 44.83%  |
| Hitachi             | 5         | 7      | 17.24%  |
| WDC                 | 4         | 4      | 13.79%  |
| Toshiba             | 4         | 4      | 13.79%  |
| Samsung Electronics | 2         | 3      | 6.9%    |
| HGST                | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 32     | 87.1%   |
| SSD  | 4         | 4      | 12.9%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 183       | 313    | 58.1%   |
| Works    | 101       | 155    | 32.06%  |
| Malfunc  | 30        | 36     | 9.52%   |
| Failed   | 1         | 2      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 195       | 57.52%  |
| AMD                              | 65        | 19.17%  |
| SanDisk                          | 13        | 3.83%   |
| Samsung Electronics              | 13        | 3.83%   |
| Kingston Technology Company      | 10        | 2.95%   |
| Micron/Crucial Technology        | 6         | 1.77%   |
| Marvell Technology Group         | 6         | 1.77%   |
| SK hynix                         | 5         | 1.47%   |
| Silicon Motion                   | 5         | 1.47%   |
| Nvidia                           | 4         | 1.18%   |
| KIOXIA                           | 4         | 1.18%   |
| Micron Technology                | 3         | 0.88%   |
| JMicron Technology               | 3         | 0.88%   |
| Unknown                          | 1         | 0.29%   |
| Union Memory (Shenzhen)          | 1         | 0.29%   |
| Toshiba America Info Systems     | 1         | 0.29%   |
| Solid State Storage Technology   | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Phison Electronics               | 1         | 0.29%   |
| LSI Logic / Symbios Logic        | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 45        | 11.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 26        | 6.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 4.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 3.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12        | 3.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 2.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7         | 1.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.28%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.03%   |
| Micron/Crucial NVMe Controller                                                          | 4         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 4         | 1.03%   |
| Kingston Company Company Non-Volatile memory controller                                 | 4         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 1.03%   |
| SK hynix BC511                                                                          | 3         | 0.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.77%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.77%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.77%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.77%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.77%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 213       | 62.28%  |
| NVMe | 65        | 19.01%  |
| IDE  | 45        | 13.16%  |
| RAID | 18        | 5.26%   |
| SCSI | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 212       | 72.85%  |
| AMD    | 77        | 26.46%  |
| ARM    | 2         | 0.69%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 2.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 2.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 2.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.71%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.37%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.37%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 3         | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.03%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.03%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.03%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.68%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.68%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 2         | 0.68%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.68%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 2         | 0.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2         | 0.68%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 2         | 0.68%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.68%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 68        | 23.37%  |
| Intel Core i5           | 60        | 20.62%  |
| Intel Core i3           | 32        | 11%     |
| AMD Ryzen 5             | 18        | 6.19%   |
| AMD Ryzen 7             | 13        | 4.47%   |
| Intel Celeron           | 10        | 3.44%   |
| Intel Core 2 Duo        | 9         | 3.09%   |
| Other                   | 8         | 2.75%   |
| Intel Pentium           | 6         | 2.06%   |
| AMD Ryzen 3             | 6         | 2.06%   |
| Intel Atom              | 5         | 1.72%   |
| Intel Pentium Dual      | 4         | 1.37%   |
| AMD Ryzen 9             | 4         | 1.37%   |
| AMD FX                  | 4         | 1.37%   |
| AMD A8                  | 4         | 1.37%   |
| Intel Xeon              | 3         | 1.03%   |
| AMD E1                  | 3         | 1.03%   |
| AMD Athlon              | 3         | 1.03%   |
| AMD A10                 | 3         | 1.03%   |
| Intel Pentium Dual-Core | 2         | 0.69%   |
| Intel Pentium 4         | 2         | 0.69%   |
| Intel Core 2 Quad       | 2         | 0.69%   |
| Intel Core 2            | 2         | 0.69%   |
| AMD Sempron             | 2         | 0.69%   |
| AMD Ryzen 7 PRO         | 2         | 0.69%   |
| AMD Phenom II X4        | 2         | 0.69%   |
| AMD A6                  | 2         | 0.69%   |
| Intel Pentium D         | 1         | 0.34%   |
| Intel Genuine           | 1         | 0.34%   |
| Intel Celeron M         | 1         | 0.34%   |
| AMD Phenom II X3        | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |
| AMD C-50                | 1         | 0.34%   |
| AMD Athlon X4           | 1         | 0.34%   |
| AMD Athlon II X3        | 1         | 0.34%   |
| AMD Athlon II X2        | 1         | 0.34%   |
| AMD Athlon 64 X2        | 1         | 0.34%   |
| AMD A4                  | 1         | 0.34%   |
| AMD A12                 | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 124       | 42.61%  |
| 4       | 113       | 38.83%  |
| 6       | 19        | 6.53%   |
| 8       | 15        | 5.15%   |
| 1       | 12        | 4.12%   |
| 3       | 3         | 1.03%   |
| Unknown | 2         | 0.69%   |
| 20      | 1         | 0.34%   |
| 16      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 291       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 204       | 70.1%   |
| 1       | 85        | 29.21%  |
| Unknown | 2         | 0.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 94.92%  |
| 64-bit         | 6         | 2.03%   |
| Unknown        | 6         | 2.03%   |
| 32-bit         | 3         | 1.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 13.51%  |
| 0x306a9    | 23        | 7.77%   |
| 0x206a7    | 22        | 7.43%   |
| 0x306c3    | 11        | 3.72%   |
| 0x806ec    | 10        | 3.38%   |
| 0x806ea    | 10        | 3.38%   |
| 0x40651    | 10        | 3.38%   |
| 0x806e9    | 9         | 3.04%   |
| 0x406e3    | 9         | 3.04%   |
| 0x08108109 | 9         | 3.04%   |
| 0x1067a    | 7         | 2.36%   |
| 0x08701021 | 7         | 2.36%   |
| 0x906ea    | 6         | 2.03%   |
| 0x506e3    | 6         | 2.03%   |
| 0x306d4    | 6         | 2.03%   |
| 0x08108102 | 6         | 2.03%   |
| 0x6fd      | 5         | 1.69%   |
| 0x20655    | 5         | 1.69%   |
| 0x906e9    | 4         | 1.35%   |
| 0x406c4    | 4         | 1.35%   |
| 0x06003106 | 4         | 1.35%   |
| 0x010000c8 | 4         | 1.35%   |
| 0xa0652    | 3         | 1.01%   |
| 0x806eb    | 3         | 1.01%   |
| 0x6fb      | 3         | 1.01%   |
| 0x30678    | 3         | 1.01%   |
| 0x10676    | 3         | 1.01%   |
| 0x0810100b | 3         | 1.01%   |
| 0x07030105 | 3         | 1.01%   |
| 0x06001119 | 3         | 1.01%   |
| 0xf64      | 2         | 0.68%   |
| 0x806c1    | 2         | 0.68%   |
| 0x706e5    | 2         | 0.68%   |
| 0x706a8    | 2         | 0.68%   |
| 0x20652    | 2         | 0.68%   |
| 0x10661    | 2         | 0.68%   |
| 0x0a50000c | 2         | 0.68%   |
| 0x08701013 | 2         | 0.68%   |
| 0x08600106 | 2         | 0.68%   |
| 0x08600104 | 2         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 54        | 18.56%  |
| IvyBridge     | 26        | 8.93%   |
| SandyBridge   | 23        | 7.9%    |
| Haswell       | 22        | 7.56%   |
| Zen+          | 18        | 6.19%   |
| Zen 2         | 17        | 5.84%   |
| Skylake       | 16        | 5.5%    |
| Core          | 12        | 4.12%   |
| Penryn        | 11        | 3.78%   |
| Westmere      | 9         | 3.09%   |
| K10           | 8         | 2.75%   |
| Zen           | 7         | 2.41%   |
| Silvermont    | 7         | 2.41%   |
| Broadwell     | 7         | 2.41%   |
| Piledriver    | 6         | 2.06%   |
| CometLake     | 6         | 2.06%   |
| Steamroller   | 5         | 1.72%   |
| Puma          | 4         | 1.37%   |
| IceLake       | 4         | 1.37%   |
| Zen 3         | 3         | 1.03%   |
| NetBurst      | 3         | 1.03%   |
| Goldmont plus | 3         | 1.03%   |
| Excavator     | 3         | 1.03%   |
| Unknown       | 3         | 1.03%   |
| TigerLake     | 2         | 0.69%   |
| P6            | 2         | 0.69%   |
| Nehalem       | 2         | 0.69%   |
| Bonnell       | 2         | 0.69%   |
| Bobcat        | 2         | 0.69%   |
| K8 Hammer     | 1         | 0.34%   |
| K10 Llano     | 1         | 0.34%   |
| Jaguar        | 1         | 0.34%   |
| Bulldozer     | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 176       | 50.29%  |
| AMD                              | 95        | 27.14%  |
| Nvidia                           | 78        | 22.29%  |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 4.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 3.87%   |
| Intel UHD Graphics 620                                                                   | 13        | 3.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.04%   |
| Intel HD Graphics 620                                                                    | 10        | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.49%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 2.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.93%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.66%   |
| AMD Renoir                                                                               | 6         | 1.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.38%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.1%    |
| Intel HD Graphics 530                                                                    | 4         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.83%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.83%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.83%   |
| Intel HD Graphics 630                                                                    | 3         | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.83%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3         | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.83%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3         | 0.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 117       | 40.07%  |
| 1 x AMD        | 67        | 22.95%  |
| 1 x Nvidia     | 39        | 13.36%  |
| Intel + Nvidia | 37        | 12.67%  |
| Intel + AMD    | 18        | 6.16%   |
| 2 x AMD        | 8         | 2.74%   |
| Other          | 2         | 0.68%   |
| AMD + Nvidia   | 2         | 0.68%   |
| 2 x Intel      | 1         | 0.34%   |
| 1 x SiS        | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 250       | 84.46%  |
| Proprietary | 38        | 12.84%  |
| Unknown     | 8         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 144       | 48.16%  |
| 1.01-2.0   | 61        | 20.4%   |
| 0.01-0.5   | 34        | 11.37%  |
| 0.51-1.0   | 22        | 7.36%   |
| 3.01-4.0   | 19        | 6.35%   |
| 5.01-6.0   | 9         | 3.01%   |
| 7.01-8.0   | 8         | 2.68%   |
| 8.01-16.0  | 2         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 48        | 15.69%  |
| Chimei Innolux       | 45        | 14.71%  |
| Goldstar             | 34        | 11.11%  |
| BOE                  | 34        | 11.11%  |
| AU Optronics         | 32        | 10.46%  |
| LG Display           | 23        | 7.52%   |
| AOC                  | 14        | 4.58%   |
| Hewlett-Packard      | 13        | 4.25%   |
| Lenovo               | 7         | 2.29%   |
| Sony                 | 5         | 1.63%   |
| Dell                 | 5         | 1.63%   |
| ViewSonic            | 4         | 1.31%   |
| Unknown              | 4         | 1.31%   |
| Sharp                | 3         | 0.98%   |
| PANDA                | 3         | 0.98%   |
| BenQ                 | 3         | 0.98%   |
| LG Electronics       | 2         | 0.65%   |
| JRY                  | 2         | 0.65%   |
| HannStar             | 2         | 0.65%   |
| ASUSTek Computer     | 2         | 0.65%   |
| Viotek               | 1         | 0.33%   |
| Unknown (XXX)        | 1         | 0.33%   |
| TMX                  | 1         | 0.33%   |
| Panasonic            | 1         | 0.33%   |
| NEW                  | 1         | 0.33%   |
| Mi                   | 1         | 0.33%   |
| LGD                  | 1         | 0.33%   |
| Lenovo Group Limited | 1         | 0.33%   |
| InnoLux Display      | 1         | 0.33%   |
| InfoVision           | 1         | 0.33%   |
| Hyundai ImageQuest   | 1         | 0.33%   |
| Huion                | 1         | 0.33%   |
| Hitachi              | 1         | 0.33%   |
| Gigabyte Technology  | 1         | 0.33%   |
| EXP                  | 1         | 0.33%   |
| Eizo                 | 1         | 0.33%   |
| DZX                  | 1         | 0.33%   |
| DMT                  | 1         | 0.33%   |
| Apple                | 1         | 0.33%   |
| AGO                  | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 10        | 3.21%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 7         | 2.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 1.6%    |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch   | 4         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch        | 3         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 3         | 0.96%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 3         | 0.96%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                       | 2         | 0.64%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.64%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                         | 2         | 0.64%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch           | 2         | 0.64%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch           | 2         | 0.64%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 2         | 0.64%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 2         | 0.64%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2         | 0.64%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                    | 2         | 0.64%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                    | 2         | 0.64%   |
| Dell 3008WFP DEL4036 2560x1600 641x400mm 29.7-inch                     | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 2         | 0.64%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.64%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                   | 2         | 0.64%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                   | 2         | 0.64%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                   | 2         | 0.64%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                   | 2         | 0.64%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                   | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch          | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch          | 2         | 0.64%   |
| AOC 2239 AOC2239 1920x1080 477x268mm 21.5-inch                         | 2         | 0.64%   |
| Viotek FI24D VTK0238 2560x1440 530x290mm 23.8-inch                     | 1         | 0.32%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch          | 1         | 0.32%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch          | 1         | 0.32%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch          | 1         | 0.32%   |
| ViewSonic LCD Monitor VSCDE2E 1920x1080 520x290mm 23.4-inch            | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 117       | 39.26%  |
| 1920x1080 (FHD)   | 96        | 32.21%  |
| 1600x900 (HD+)    | 21        | 7.05%   |
| 1360x768          | 12        | 4.03%   |
| 3840x2160 (4K)    | 10        | 3.36%   |
| 1440x900 (WXGA+)  | 6         | 2.01%   |
| 2560x1440 (QHD)   | 5         | 1.68%   |
| 1024x768 (XGA)    | 5         | 1.68%   |
| Unknown           | 4         | 1.34%   |
| 3840x1080         | 3         | 1.01%   |
| 1280x800 (WXGA)   | 3         | 1.01%   |
| 3200x1800 (QHD+)  | 2         | 0.67%   |
| 2560x1600         | 2         | 0.67%   |
| 1920x1200 (WUXGA) | 2         | 0.67%   |
| 1280x1024 (SXGA)  | 2         | 0.67%   |
| 1024x600          | 2         | 0.67%   |
| 3440x1440         | 1         | 0.34%   |
| 3200x2000         | 1         | 0.34%   |
| 2736x1824         | 1         | 0.34%   |
| 2560x1080         | 1         | 0.34%   |
| 2160x1440         | 1         | 0.34%   |
| 1280x720 (HD)     | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 95        | 31.15%  |
| 13      | 39        | 12.79%  |
| 21      | 27        | 8.85%   |
| 14      | 26        | 8.52%   |
| 23      | 21        | 6.89%   |
| 18      | 14        | 4.59%   |
| 20      | 12        | 3.93%   |
| Unknown | 11        | 3.61%   |
| 27      | 9         | 2.95%   |
| 19      | 8         | 2.62%   |
| 17      | 8         | 2.62%   |
| 24      | 6         | 1.97%   |
| 48      | 3         | 0.98%   |
| 32      | 3         | 0.98%   |
| 31      | 3         | 0.98%   |
| 12      | 3         | 0.98%   |
| 11      | 3         | 0.98%   |
| 84      | 2         | 0.66%   |
| 72      | 2         | 0.66%   |
| 30      | 2         | 0.66%   |
| 10      | 2         | 0.66%   |
| 60      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 46      | 1         | 0.33%   |
| 43      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 150       | 49.83%  |
| 401-500     | 58        | 19.27%  |
| 501-600     | 35        | 11.63%  |
| 201-300     | 16        | 5.32%   |
| Unknown     | 11        | 3.65%   |
| 351-400     | 10        | 3.32%   |
| 1001-1500   | 6         | 1.99%   |
| 601-700     | 5         | 1.66%   |
| 701-800     | 4         | 1.33%   |
| 1501-2000   | 4         | 1.33%   |
| 801-900     | 1         | 0.33%   |
| 901-1000    | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 232       | 84.98%  |
| 16/10   | 16        | 5.86%   |
| Unknown | 11        | 4.03%   |
| 4/3     | 7         | 2.56%   |
| 5/4     | 4         | 1.47%   |
| 3/2     | 2         | 0.73%   |
| 21/9    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 31.46%  |
| 81-90          | 58        | 19.21%  |
| 201-250        | 41        | 13.58%  |
| 151-200        | 29        | 9.6%    |
| 141-150        | 16        | 5.3%    |
| Unknown        | 11        | 3.64%   |
| More than 1000 | 9         | 2.98%   |
| 351-500        | 9         | 2.98%   |
| 301-350        | 9         | 2.98%   |
| 71-80          | 8         | 2.65%   |
| 121-130        | 4         | 1.32%   |
| 51-60          | 3         | 0.99%   |
| 501-1000       | 3         | 0.99%   |
| 41-50          | 2         | 0.66%   |
| 131-140        | 2         | 0.66%   |
| 61-70          | 1         | 0.33%   |
| 251-300        | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 139       | 46.96%  |
| 51-100        | 79        | 26.69%  |
| 121-160       | 46        | 15.54%  |
| 1-50          | 12        | 4.05%   |
| Unknown       | 11        | 3.72%   |
| 161-240       | 5         | 1.69%   |
| More than 240 | 4         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 249       | 83.56%  |
| 2     | 40        | 13.42%  |
| 0     | 7         | 2.35%   |
| 3     | 2         | 0.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 187       | 43.59%  |
| Intel                            | 103       | 24.01%  |
| Qualcomm Atheros                 | 63        | 14.69%  |
| TP-Link                          | 13        | 3.03%   |
| Broadcom                         | 13        | 3.03%   |
| Ralink Technology                | 6         | 1.4%    |
| Ralink                           | 5         | 1.17%   |
| Qualcomm Atheros Communications  | 4         | 0.93%   |
| Nvidia                           | 4         | 0.93%   |
| Marvell Technology Group         | 4         | 0.93%   |
| Xiaomi                           | 3         | 0.7%    |
| ICS Advent                       | 3         | 0.7%    |
| Broadcom Limited                 | 3         | 0.7%    |
| ASIX Electronics                 | 3         | 0.7%    |
| Motorola PCS                     | 2         | 0.47%   |
| Huawei Technologies              | 2         | 0.47%   |
| D-Link System                    | 2         | 0.47%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.23%   |
| T & A Mobile Phones              | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Samsung Electronics              | 1         | 0.23%   |
| Microsoft                        | 1         | 0.23%   |
| MediaTek                         | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| D-Link                           | 1         | 0.23%   |
| Apple                            | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133       | 26.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 5.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.2%    |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1%      |
| Intel Wireless 7265                                               | 5         | 1%      |
| Intel Wireless 7260                                               | 5         | 1%      |
| Intel I211 Gigabit Network Connection                             | 5         | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.8%    |
| Intel Wireless 8265 / 8275                                        | 4         | 0.8%    |
| Intel Wireless 8260                                               | 4         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.6%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 3         | 0.6%    |
| TP-Link 802.11n NIC                                               | 3         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 3         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 32.27%  |
| Qualcomm Atheros                | 55        | 25%     |
| Realtek Semiconductor           | 51        | 23.18%  |
| TP-Link                         | 11        | 5%      |
| Broadcom                        | 11        | 5%      |
| Ralink Technology               | 6         | 2.73%   |
| Ralink                          | 5         | 2.27%   |
| Qualcomm Atheros Communications | 4         | 1.82%   |
| Microsoft                       | 1         | 0.45%   |
| MediaTek                        | 1         | 0.45%   |
| Marvell Technology Group        | 1         | 0.45%   |
| D-Link System                   | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |
| Broadcom Limited                | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 6.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 5.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 4.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 3.18%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 3.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.73%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.27%   |
| Intel Wireless 7265                                            | 5         | 2.27%   |
| Intel Wireless 7260                                            | 5         | 2.27%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 1.82%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.82%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.82%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.82%   |
| Intel Wireless 8260                                            | 4         | 1.82%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 3         | 1.36%   |
| TP-Link 802.11n NIC                                            | 3         | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 1.36%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                        | 2         | 0.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.91%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.91%   |
| Intel Wireless 3165                                            | 2         | 0.91%   |
| Intel WiFi Link 5100                                           | 2         | 0.91%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 171       | 61.96%  |
| Intel                            | 57        | 20.65%  |
| Qualcomm Atheros                 | 14        | 5.07%   |
| Nvidia                           | 4         | 1.45%   |
| Xiaomi                           | 3         | 1.09%   |
| Marvell Technology Group         | 3         | 1.09%   |
| ICS Advent                       | 3         | 1.09%   |
| Broadcom                         | 3         | 1.09%   |
| ASIX Electronics                 | 3         | 1.09%   |
| TP-Link                          | 2         | 0.72%   |
| Motorola PCS                     | 2         | 0.72%   |
| Huawei Technologies              | 2         | 0.72%   |
| Broadcom Limited                 | 2         | 0.72%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.36%   |
| T & A Mobile Phones              | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] | 1         | 0.36%   |
| Samsung Electronics              | 1         | 0.36%   |
| Lenovo                           | 1         | 0.36%   |
| D-Link System                    | 1         | 0.36%   |
| Apple                            | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 133       | 47.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 3.93%   |
| Intel 82579V Gigabit Network Connection                                        | 6         | 2.14%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 1.79%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.07%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.07%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.07%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.07%   |
| Intel 82578DC Gigabit Network Connection                                       | 3         | 1.07%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 3         | 1.07%   |
| TP-Link USB 10/100 LAN                                                         | 2         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.71%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.71%   |
| Motorola PCS Moto G (5) Plus                                                   | 2         | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.71%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.71%   |
| Huawei YAL-L21                                                                 | 2         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.71%   |
| ZTE WCDMA MSM ZTE                                                              | 1         | 0.36%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.36%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.36%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.36%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.36%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.36%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.36%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 262       | 55.39%  |
| WiFi     | 211       | 44.61%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 53.09%  |
| Ethernet | 144       | 46.91%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 159       | 54.45%  |
| 1     | 127       | 43.49%  |
| 0     | 4         | 1.37%   |
| 3     | 2         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 250       | 85.03%  |
| Yes  | 44        | 14.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 31.55%  |
| Realtek Semiconductor           | 34        | 20.24%  |
| Qualcomm Atheros Communications | 30        | 17.86%  |
| Cambridge Silicon Radio         | 10        | 5.95%   |
| Lite-On Technology              | 9         | 5.36%   |
| IMC Networks                    | 8         | 4.76%   |
| Toshiba                         | 4         | 2.38%   |
| Ralink                          | 4         | 2.38%   |
| Broadcom                        | 4         | 2.38%   |
| Hewlett-Packard                 | 2         | 1.19%   |
| Foxconn / Hon Hai               | 2         | 1.19%   |
| Dell                            | 2         | 1.19%   |
| TRENDnet                        | 1         | 0.6%    |
| TP-Link                         | 1         | 0.6%    |
| Integrated System Solution      | 1         | 0.6%    |
| Foxconn International           | 1         | 0.6%    |
| Apple                           | 1         | 0.6%    |
| Alps Electric                   | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 20        | 11.9%   |
| Realtek  Bluetooth 4.2 Adapter                        | 17        | 10.12%  |
| Qualcomm Atheros  Bluetooth Device                    | 17        | 10.12%  |
| Realtek Bluetooth Radio                               | 15        | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10        | 5.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 10        | 5.95%   |
| Intel AX201 Bluetooth                                 | 9         | 5.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 3.57%   |
| Intel AX200 Bluetooth                                 | 6         | 3.57%   |
| Ralink RT3290 Bluetooth                               | 4         | 2.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3         | 1.79%   |
| Lite-On Bluetooth Device                              | 3         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.79%   |
| IMC Networks Bluetooth Radio                          | 3         | 1.79%   |
| IMC Networks Bluetooth Device                         | 3         | 1.79%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 2         | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 1.19%   |
| Lite-On Bluetooth Radio                               | 2         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 1.19%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 2         | 1.19%   |
| TRENDnet TBW-108UB USB Adapter                        | 1         | 0.6%    |
| TP-Link UB500 Adapter                                 | 1         | 0.6%    |
| Toshiba RT Bluetooth Radio                            | 1         | 0.6%    |
| Toshiba Bluetooth Device                              | 1         | 0.6%    |
| Toshiba BCM43142A0                                    | 1         | 0.6%    |
| Toshiba Askey Bluetooth Module                        | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.6%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.6%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1         | 0.6%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.6%    |
| IMC Networks Wireless_Device                          | 1         | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module     | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth Device                    | 1         | 0.6%    |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 205       | 55.86%  |
| AMD                              | 90        | 24.52%  |
| Nvidia                           | 55        | 14.99%  |
| C-Media Electronics              | 3         | 0.82%   |
| Texas Instruments                | 2         | 0.54%   |
| Microsoft                        | 2         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Samson Technologies              | 1         | 0.27%   |
| Razer USA                        | 1         | 0.27%   |
| Pixart Imaging                   | 1         | 0.27%   |
| Logitech                         | 1         | 0.27%   |
| Kingston Technology              | 1         | 0.27%   |
| Hewlett-Packard                  | 1         | 0.27%   |
| Generalplus Technology           | 1         | 0.27%   |
| Creative Labs                    | 1         | 0.27%   |
| Chicony Electronics              | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 34        | 7.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 31        | 6.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28        | 6.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 4.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 3.33%   |
| AMD FCH Azalia Controller                                                  | 14        | 3.11%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 2.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 2%      |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.33%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.89%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.89%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4         | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.67%   |
| Nvidia MCP61 High Definition Audio                                         | 3         | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 49        | 24.62%  |
| Kingston                     | 46        | 23.12%  |
| SK hynix                     | 34        | 17.09%  |
| Micron Technology            | 25        | 12.56%  |
| Unknown                      | 12        | 6.03%   |
| Ramaxel Technology           | 6         | 3.02%   |
| Corsair                      | 6         | 3.02%   |
| Crucial                      | 4         | 2.01%   |
| Hewlett-Packard              | 3         | 1.51%   |
| Unknown (ABCD)               | 2         | 1.01%   |
| Team                         | 2         | 1.01%   |
| Unknown (0x7FA8000000000000) | 1         | 0.5%    |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.5%    |
| Qumo                         | 1         | 0.5%    |
| Princeton                    | 1         | 0.5%    |
| Patriot                      | 1         | 0.5%    |
| Nanya Technology             | 1         | 0.5%    |
| Goldkey                      | 1         | 0.5%    |
| GeIL                         | 1         | 0.5%    |
| CSX                          | 1         | 0.5%    |
| A-DATA Technology            | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 6         | 2.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 5         | 2.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 5         | 2.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.9%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 3         | 1.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.42%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s  | 3         | 1.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 1.42%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 3         | 1.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 2         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.95%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.95%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2         | 0.95%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 2         | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 0.95%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 2         | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 0.95%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s | 2         | 0.95%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s     | 2         | 0.95%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 2         | 0.95%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 2         | 0.95%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s      | 2         | 0.95%   |
| Kingston RAM CL16-18-18 D4-3200 8192MB DIMM DDR4 3200MT/s | 2         | 0.95%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s   | 2         | 0.95%   |
| Kingston RAM 9905471-017.A00LF 4096MB DIMM DDR3 1333MT/s  | 2         | 0.95%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.47%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.47%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2                          | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                    | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s               | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 70        | 46.36%  |
| DDR3    | 57        | 37.75%  |
| DDR2    | 8         | 5.3%    |
| LPDDR4  | 7         | 4.64%   |
| LPDDR3  | 5         | 3.31%   |
| SDRAM   | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 62.25%  |
| DIMM         | 51        | 33.77%  |
| Row Of Chips | 6         | 3.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 68        | 37.99%  |
| 4096  | 67        | 37.43%  |
| 2048  | 21        | 11.73%  |
| 16384 | 16        | 8.94%   |
| 1024  | 3         | 1.68%   |
| 512   | 3         | 1.68%   |
| 32768 | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 45        | 25.28%  |
| 1600    | 38        | 21.35%  |
| 3200    | 20        | 11.24%  |
| 1333    | 16        | 8.99%   |
| 2400    | 10        | 5.62%   |
| 2133    | 8         | 4.49%   |
| 3266    | 6         | 3.37%   |
| Unknown | 5         | 2.81%   |
| 1867    | 4         | 2.25%   |
| 3600    | 3         | 1.69%   |
| 3466    | 3         | 1.69%   |
| 1334    | 3         | 1.69%   |
| 1067    | 3         | 1.69%   |
| 1800    | 2         | 1.12%   |
| 800     | 2         | 1.12%   |
| 533     | 2         | 1.12%   |
| 3400    | 1         | 0.56%   |
| 3151    | 1         | 0.56%   |
| 3100    | 1         | 0.56%   |
| 2733    | 1         | 0.56%   |
| 2200    | 1         | 0.56%   |
| 2134    | 1         | 0.56%   |
| 667     | 1         | 0.56%   |
| 400     | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 22.22%  |
| Hewlett-Packard    | 2         | 22.22%  |
| Canon              | 2         | 22.22%  |
| Brother Industries | 2         | 22.22%  |
| Star Micronics     | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Star Micronics TUP592 (STR_T-001) | 1         | 11.11%  |
| Seiko Epson L3250 Series          | 1         | 11.11%  |
| Seiko Epson ET-2710 Series        | 1         | 11.11%  |
| HP PSC 1400                       | 1         | 11.11%  |
| HP LaserJet Professional P 1102w  | 1         | 11.11%  |
| Canon PIXMA MG3600 Series         | 1         | 11.11%  |
| Canon E400 series                 | 1         | 11.11%  |
| Brother DCP-T310                  | 1         | 11.11%  |
| Brother DCP-T300                  | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP ScanJet 2400c       | 1         | 50%     |
| Canon CanoScan LIDE 25 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 19.17%  |
| Microdia                               | 18        | 9.33%   |
| IMC Networks                           | 17        | 8.81%   |
| Acer                                   | 16        | 8.29%   |
| Realtek Semiconductor                  | 14        | 7.25%   |
| Syntek                                 | 11        | 5.7%    |
| Sunplus Innovation Technology          | 10        | 5.18%   |
| Lite-On Technology                     | 10        | 5.18%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.18%   |
| Quanta                                 | 9         | 4.66%   |
| Suyin                                  | 8         | 4.15%   |
| Z-Star Microelectronics                | 4         | 2.07%   |
| Microsoft                              | 4         | 2.07%   |
| Logitech                               | 4         | 2.07%   |
| Importek                               | 4         | 2.07%   |
| Samsung Electronics                    | 3         | 1.55%   |
| Sonix Technology                       | 2         | 1.04%   |
| Ricoh                                  | 2         | 1.04%   |
| Generalplus Technology                 | 2         | 1.04%   |
| Alcor Micro                            | 2         | 1.04%   |
| Xiongmai                               | 1         | 0.52%   |
| Luxvisions Innotech Limited            | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |
| Aveo Technology                        | 1         | 0.52%   |
| Apple                                  | 1         | 0.52%   |
| ANYKA                                  | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 4.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 3.08%   |
| Chicony Integrated Camera                                                  | 5         | 2.56%   |
| Acer Integrated Camera                                                     | 5         | 2.56%   |
| Lite-On Integrated Camera                                                  | 4         | 2.05%   |
| IMC Networks Integrated Camera                                             | 4         | 2.05%   |
| Chicony EasyCamera                                                         | 4         | 2.05%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.54%   |
| Samsung Galaxy A5 (MTP)                                                    | 3         | 1.54%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.54%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 1.54%   |
| Lite-On HP HD Camera                                                       | 3         | 1.54%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.54%   |
| Chicony HP Truevision HD                                                   | 3         | 1.54%   |
| Chicony HD WebCam                                                          | 3         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.54%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 1.03%   |
| Sunplus Integrated Webcam                                                  | 2         | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 2         | 1.03%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 1.03%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.03%   |
| Realtek Integrated Webcam                                                  | 2         | 1.03%   |
| Quanta HP Webcam                                                           | 2         | 1.03%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 1.03%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                        | 2         | 1.03%   |
| Microdia Webcam Vitade AF                                                  | 2         | 1.03%   |
| Microdia CyberTrack H7                                                     | 2         | 1.03%   |
| Microdia Camera                                                            | 2         | 1.03%   |
| Lite-On HP Wide Vision HD Camera                                           | 2         | 1.03%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 1.03%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 1.03%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 1.03%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.03%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 1.03%   |
| Chicony HP Webcam                                                          | 2         | 1.03%   |
| Chicony HP TrueVision HD Camera                                            | 2         | 1.03%   |
| Chicony HP HD Camera                                                       | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.03%   |
| Alcor Micro TOSHIBA Web Camera - MP                                        | 2         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 47.5%   |
| Synaptics                  | 12        | 30%     |
| Shenzhen Goodix Technology | 4         | 10%     |
| Elan Microelectronics      | 3         | 7.5%    |
| STMicroelectronics         | 1         | 2.5%    |
| AuthenTec                  | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 15%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 15%     |
| Synaptics  WBDI                                            | 4         | 10%     |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 7.5%    |
| Unknown                                                    | 3         | 7.5%    |
| Validity Sensors Fingerprint scanner                       | 2         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 5%      |
| Elan ELAN:Fingerprint                                      | 2         | 5%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.5%    |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.5%    |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.5%    |
| Validity Sensors Synaptics WBDI                            | 1         | 2.5%    |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.5%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.5%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.5%    |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.5%    |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.5%    |
| Elan ELAN:ARM-M4                                           | 1         | 2.5%    |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 3         | 30%     |
| Broadcom    | 3         | 30%     |
| Alcor Micro | 2         | 20%     |
| Yubico.com  | 1         | 10%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 212       | 71.14%  |
| 1     | 72        | 24.16%  |
| 2     | 10        | 3.36%   |
| 3     | 3         | 1.01%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 40        | 39.6%   |
| Graphics card            | 19        | 18.81%  |
| Net/wireless             | 13        | 12.87%  |
| Chipcard                 | 9         | 8.91%   |
| Bluetooth                | 6         | 5.94%   |
| Sound                    | 2         | 1.98%   |
| Multimedia controller    | 2         | 1.98%   |
| Card reader              | 2         | 1.98%   |
| Camera                   | 2         | 1.98%   |
| Unassigned class         | 1         | 0.99%   |
| Storage                  | 1         | 0.99%   |
| Network                  | 1         | 0.99%   |
| Net/ethernet             | 1         | 0.99%   |
| Firewire controller      | 1         | 0.99%   |
| Communication controller | 1         | 0.99%   |


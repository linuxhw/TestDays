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

Total: 426

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 56        | 18.12%  |
| Ubuntu 18.04                 | 21        | 6.8%    |
| OpenMandriva 4.3             | 14        | 4.53%   |
| OpenMandriva 4.2             | 12        | 3.88%   |
| Zorin 15                     | 10        | 3.24%   |
| Ubuntu 19.10                 | 9         | 2.91%   |
| Ubuntu 22.04                 | 8         | 2.59%   |
| Manjaro                      | 8         | 2.59%   |
| Debian 11                    | 7         | 2.27%   |
| KDE neon 20.04               | 6         | 1.94%   |
| Arch                         | 6         | 1.94%   |
| Xubuntu 20.04                | 5         | 1.62%   |
| ROSA R9                      | 5         | 1.62%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.62%   |
| Kubuntu 20.04                | 5         | 1.62%   |
| Debian 10                    | 5         | 1.62%   |
| Ubuntu 21.10                 | 4         | 1.29%   |
| Ubuntu 21.04                 | 4         | 1.29%   |
| Pop!_OS 21.10                | 4         | 1.29%   |
| Linux Mint 20.3              | 4         | 1.29%   |
| Linux Mint 20.1              | 4         | 1.29%   |
| Linux Mint 19.3              | 4         | 1.29%   |
| CentOS 8                     | 4         | 1.29%   |
| Ubuntu 19.04                 | 3         | 0.97%   |
| ROSA R11.1                   | 3         | 0.97%   |
| ROSA R10                     | 3         | 0.97%   |
| Pop!_OS 20.10                | 3         | 0.97%   |
| Manjaro 21.2.6               | 3         | 0.97%   |
| Manjaro 20.1                 | 3         | 0.97%   |
| Fedora 32                    | 3         | 0.97%   |
| Elementary 5.1.7             | 3         | 0.97%   |
| Arch Rolling                 | 3         | 0.97%   |
| Zorin 16                     | 2         | 0.65%   |
| Ubuntu MATE 18.04            | 2         | 0.65%   |
| ROSA R8                      | 2         | 0.65%   |
| ROSA R11                     | 2         | 0.65%   |
| ROSA 12.2                    | 2         | 0.65%   |
| Pop!_OS 22.04                | 2         | 0.65%   |
| Pop!_OS 20.04                | 2         | 0.65%   |
| Peppermint 10                | 2         | 0.65%   |
| OpenMandriva 4.90            | 2         | 0.65%   |
| Lubuntu 18.04                | 2         | 0.65%   |
| Linux Mint 20.2              | 2         | 0.65%   |
| Linux Mint 20                | 2         | 0.65%   |
| Linux Mint 19.2              | 2         | 0.65%   |
| Linux Mint 19.1              | 2         | 0.65%   |
| Fedora 35                    | 2         | 0.65%   |
| Fedora 34                    | 2         | 0.65%   |
| Fedora 33                    | 2         | 0.65%   |
| Endless 3.5.7                | 2         | 0.65%   |
| Xubuntu 18.04                | 1         | 0.32%   |
| Void Linux                   | 1         | 0.32%   |
| Ubuntu MATE 22.04            | 1         | 0.32%   |
| Ubuntu MATE 21.04            | 1         | 0.32%   |
| Ubuntu MATE 20.10            | 1         | 0.32%   |
| Ubuntu MATE 20.04            | 1         | 0.32%   |
| Ubuntu MATE 16.04            | 1         | 0.32%   |
| Ubuntu 18.10                 | 1         | 0.32%   |
| Solus 4.1                    | 1         | 0.32%   |
| ROSA 12.1                    | 1         | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 102       | 34%     |
| OpenMandriva | 28        | 9.33%   |
| Linux Mint   | 20        | 6.67%   |
| Manjaro      | 16        | 5.33%   |
| ROSA         | 15        | 5%      |
| Zorin        | 12        | 4%      |
| Pop!_OS      | 12        | 4%      |
| Debian       | 12        | 4%      |
| Fedora       | 10        | 3.33%   |
| Arch         | 10        | 3.33%   |
| Ubuntu MATE  | 7         | 2.33%   |
| openSUSE     | 7         | 2.33%   |
| Xubuntu      | 6         | 2%      |
| KDE neon     | 6         | 2%      |
| Kubuntu      | 5         | 1.67%   |
| Endless      | 5         | 1.67%   |
| Lubuntu      | 4         | 1.33%   |
| Elementary   | 4         | 1.33%   |
| CentOS       | 4         | 1.33%   |
| Linux Lite   | 3         | 1%      |
| Peppermint   | 2         | 0.67%   |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 14        | 4.14%   |
| 5.10.14-desktop-1omv4002           | 10        | 2.96%   |
| 5.3.0-40-generic                   | 8         | 2.37%   |
| 5.4.0-66-generic                   | 5         | 1.48%   |
| 5.4.0-28-generic                   | 5         | 1.48%   |
| 5.13.0-40-generic                  | 5         | 1.48%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 5         | 1.48%   |
| 5.4.0-70-generic                   | 4         | 1.18%   |
| 5.4.0-58-generic                   | 4         | 1.18%   |
| 5.4.0-52-generic                   | 4         | 1.18%   |
| 5.4.0-42-generic                   | 4         | 1.18%   |
| 5.4.0-37-generic                   | 4         | 1.18%   |
| 5.4.0-31-generic                   | 4         | 1.18%   |
| 5.4.0-26-generic                   | 4         | 1.18%   |
| 5.11.0-40-generic                  | 4         | 1.18%   |
| 5.10.0-13-amd64                    | 4         | 1.18%   |
| 5.4.0-73-generic                   | 3         | 0.89%   |
| 5.4.0-40-generic                   | 3         | 0.89%   |
| 5.4.0-39-generic                   | 3         | 0.89%   |
| 5.4.0-33-generic                   | 3         | 0.89%   |
| 5.3.0-46-generic                   | 3         | 0.89%   |
| 5.3.0-42-generic                   | 3         | 0.89%   |
| 5.3.0-26-generic                   | 3         | 0.89%   |
| 5.17.5-arch1-1                     | 3         | 0.89%   |
| 5.15.0-25-generic                  | 3         | 0.89%   |
| 5.13.0-51-generic                  | 3         | 0.89%   |
| 5.13.0-30-generic                  | 3         | 0.89%   |
| 5.11.0-27-generic                  | 3         | 0.89%   |
| 5.11.0-25-generic                  | 3         | 0.89%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 0.89%   |
| 4.18.0-15-generic                  | 3         | 0.89%   |
| 5.9.11-3-MANJARO                   | 2         | 0.59%   |
| 5.8.0-63-generic                   | 2         | 0.59%   |
| 5.8.0-48-generic                   | 2         | 0.59%   |
| 5.8.0-44-generic                   | 2         | 0.59%   |
| 5.4.0-81-generic                   | 2         | 0.59%   |
| 5.4.0-7642-generic                 | 2         | 0.59%   |
| 5.4.0-65-generic                   | 2         | 0.59%   |
| 5.4.0-54-generic                   | 2         | 0.59%   |
| 5.4.0-48-generic                   | 2         | 0.59%   |
| 5.4.0-29-generic                   | 2         | 0.59%   |
| 5.4.0-109-generic                  | 2         | 0.59%   |
| 5.3.0-45-generic                   | 2         | 0.59%   |
| 5.3.0-23-generic                   | 2         | 0.59%   |
| 5.18.12-desktop-3omv4090           | 2         | 0.59%   |
| 5.17.1-3-MANJARO                   | 2         | 0.59%   |
| 5.16.19-76051619-generic           | 2         | 0.59%   |
| 5.15.49-1-lts                      | 2         | 0.59%   |
| 5.15.0-43-generic                  | 2         | 0.59%   |
| 5.15.0-27-generic                  | 2         | 0.59%   |
| 5.13.0-35-generic                  | 2         | 0.59%   |
| 5.13.0-20-generic                  | 2         | 0.59%   |
| 5.11.12-desktop-1omv4002           | 2         | 0.59%   |
| 5.11.0-7614-generic                | 2         | 0.59%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 0.59%   |
| 5.10.0-16-amd64                    | 2         | 0.59%   |
| 5.10.0-15-amd64                    | 2         | 0.59%   |
| 5.0.0-37-generic                   | 2         | 0.59%   |
| 4.15.0-54-generic                  | 2         | 0.59%   |
| 4.15.0-112-generic                 | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 21.45%  |
| 5.3.0   | 23        | 7.26%   |
| 5.11.0  | 20        | 6.31%   |
| 5.13.0  | 18        | 5.68%   |
| 4.15.0  | 18        | 5.68%   |
| 5.16.7  | 14        | 4.42%   |
| 5.8.0   | 13        | 4.1%    |
| 4.18.0  | 12        | 3.79%   |
| 5.15.0  | 11        | 3.47%   |
| 5.10.14 | 10        | 3.15%   |
| 5.10.0  | 8         | 2.52%   |
| 5.0.0   | 8         | 2.52%   |
| 4.9.20  | 5         | 1.58%   |
| 5.17.5  | 4         | 1.26%   |
| 4.9.60  | 4         | 1.26%   |
| 5.17.1  | 3         | 0.95%   |
| 5.9.11  | 2         | 0.63%   |
| 5.4.83  | 2         | 0.63%   |
| 5.3.18  | 2         | 0.63%   |
| 5.18.12 | 2         | 0.63%   |
| 5.16.19 | 2         | 0.63%   |
| 5.16.0  | 2         | 0.63%   |
| 5.15.49 | 2         | 0.63%   |
| 5.12.10 | 2         | 0.63%   |
| 5.11.12 | 2         | 0.63%   |
| 5.10.74 | 2         | 0.63%   |
| 4.19.0  | 2         | 0.63%   |
| 5.9.16  | 1         | 0.32%   |
| 5.8.7   | 1         | 0.32%   |
| 5.8.6   | 1         | 0.32%   |
| 5.8.4   | 1         | 0.32%   |
| 5.8.11  | 1         | 0.32%   |
| 5.7.9   | 1         | 0.32%   |
| 5.7.4   | 1         | 0.32%   |
| 5.7.17  | 1         | 0.32%   |
| 5.7.14  | 1         | 0.32%   |
| 5.6.6   | 1         | 0.32%   |
| 5.6.19  | 1         | 0.32%   |
| 5.6.18  | 1         | 0.32%   |
| 5.6.14  | 1         | 0.32%   |
| 5.6.0   | 1         | 0.32%   |
| 5.4.64  | 1         | 0.32%   |
| 5.4.61  | 1         | 0.32%   |
| 5.4.51  | 1         | 0.32%   |
| 5.4.118 | 1         | 0.32%   |
| 5.19.0  | 1         | 0.32%   |
| 5.18.6  | 1         | 0.32%   |
| 5.18.0  | 1         | 0.32%   |
| 5.17.9  | 1         | 0.32%   |
| 5.17.7  | 1         | 0.32%   |
| 5.17.6  | 1         | 0.32%   |
| 5.16.18 | 1         | 0.32%   |
| 5.15.8  | 1         | 0.32%   |
| 5.15.6  | 1         | 0.32%   |
| 5.15.33 | 1         | 0.32%   |
| 5.15.32 | 1         | 0.32%   |
| 5.15.2  | 1         | 0.32%   |
| 5.15.18 | 1         | 0.32%   |
| 5.15.16 | 1         | 0.32%   |
| 5.15.15 | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 23.64%  |
| 5.3     | 25        | 7.99%   |
| 5.10    | 25        | 7.99%   |
| 5.11    | 24        | 7.67%   |
| 5.15    | 22        | 7.03%   |
| 5.16    | 19        | 6.07%   |
| 5.13    | 19        | 6.07%   |
| 4.15    | 18        | 5.75%   |
| 5.8     | 17        | 5.43%   |
| 4.18    | 12        | 3.83%   |
| 5.17    | 10        | 3.19%   |
| 5.0     | 8         | 2.56%   |
| 4.9     | 8         | 2.56%   |
| 5.6     | 5         | 1.6%    |
| 5.7     | 4         | 1.28%   |
| 5.18    | 4         | 1.28%   |
| 5.12    | 4         | 1.28%   |
| 5.9     | 3         | 0.96%   |
| 5.14    | 3         | 0.96%   |
| 4.19    | 2         | 0.64%   |
| 4.1     | 2         | 0.64%   |
| 5.19    | 1         | 0.32%   |
| 5.1     | 1         | 0.32%   |
| 4.8     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.16    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 269       | 93.73%  |
| i686    | 16        | 5.57%   |
| aarch64 | 2         | 0.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 133       | 44.78%  |
| KDE5            | 49        | 16.5%   |
| XFCE            | 27        | 9.09%   |
| Unknown         | 24        | 8.08%   |
| X-Cinnamon      | 16        | 5.39%   |
| MATE            | 12        | 4.04%   |
| KDE4            | 9         | 3.03%   |
| KDE             | 8         | 2.69%   |
| Pantheon        | 4         | 1.35%   |
| LXDE            | 4         | 1.35%   |
| Unity           | 2         | 0.67%   |
| LXQt            | 2         | 0.67%   |
| i3              | 2         | 0.67%   |
| Budgie          | 2         | 0.67%   |
| spectrwm        | 1         | 0.34%   |
| GNOME Flashback | 1         | 0.34%   |
| awesome         | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 239       | 81.02%  |
| Wayland | 35        | 11.86%  |
| Unknown | 20        | 6.78%   |
| Tty     | 1         | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 149       | 49.83%  |
| SDDM    | 44        | 14.72%  |
| GDM     | 41        | 13.71%  |
| LightDM | 25        | 8.36%   |
| GDM3    | 24        | 8.03%   |
| KDM     | 9         | 3.01%   |
| TDM     | 6         | 2.01%   |
| XDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_PE   | 150       | 51.02%  |
| en_US   | 67        | 22.79%  |
| es_ES   | 29        | 9.86%   |
| Unknown | 28        | 9.52%   |
| en_GB   | 4         | 1.36%   |
| C       | 4         | 1.36%   |
| es_MX   | 3         | 1.02%   |
| it_IT   | 2         | 0.68%   |
| en_CA   | 2         | 0.68%   |
| fr_FR   | 1         | 0.34%   |
| es_US   | 1         | 0.34%   |
| es_CO   | 1         | 0.34%   |
| Default | 1         | 0.34%   |
| ca_ES   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 152       | 52.41%  |
| EFI  | 138       | 47.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 230       | 77.97%  |
| Overlay | 28        | 9.49%   |
| Unknown | 15        | 5.08%   |
| Btrfs   | 12        | 4.07%   |
| Xfs     | 7         | 2.37%   |
| Ext3    | 3         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 178       | 60.54%  |
| GPT     | 85        | 28.91%  |
| MBR     | 31        | 10.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 250       | 85.03%  |
| Yes       | 44        | 14.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 169       | 58.28%  |
| Yes       | 121       | 41.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 54        | 18.88%  |
| Lenovo                  | 53        | 18.53%  |
| ASUSTek Computer        | 32        | 11.19%  |
| Gigabyte Technology     | 28        | 9.79%   |
| Dell                    | 24        | 8.39%   |
| Intel                   | 22        | 7.69%   |
| MSI                     | 16        | 5.59%   |
| Toshiba                 | 12        | 4.2%    |
| Acer                    | 12        | 4.2%    |
| Foxconn                 | 6         | 2.1%    |
| Sony                    | 4         | 1.4%    |
| ASRock                  | 4         | 1.4%    |
| Raspberry Pi Foundation | 2         | 0.7%    |
| Chuwi                   | 2         | 0.7%    |
| Unknown                 | 2         | 0.7%    |
| SZMZ                    | 1         | 0.35%   |
| Samsung Electronics     | 1         | 0.35%   |
| Razer                   | 1         | 0.35%   |
| PCChips                 | 1         | 0.35%   |
| Microsoft               | 1         | 0.35%   |
| HUAWEI                  | 1         | 0.35%   |
| efirstview              | 1         | 0.35%   |
| ECS                     | 1         | 0.35%   |
| Compal                  | 1         | 0.35%   |
| Biostar                 | 1         | 0.35%   |
| Apple                   | 1         | 0.35%   |
| AMI                     | 1         | 0.35%   |
| Advance                 | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| MSI MS-7721                                           | 3         | 1.05%   |
| Lenovo V330-15IKB 81AX                                | 3         | 1.05%   |
| Lenovo V310-15ISK 80SY                                | 3         | 1.05%   |
| HP Pavilion Laptop 15-cw1xxx                          | 3         | 1.05%   |
| Gigabyte 970A-DS3P                                    | 3         | 1.05%   |
| Lenovo IdeaPad S540-14API 81NH                        | 2         | 0.7%    |
| Lenovo IdeaPad S145-15IWL 81MV                        | 2         | 0.7%    |
| Lenovo IdeaPad 330S-14IKB 81F4                        | 2         | 0.7%    |
| Lenovo IdeaPad 3 14ADA05 81W0                         | 2         | 0.7%    |
| Intel DH55PJ AAE93812-303                             | 2         | 0.7%    |
| HP ProBook 645 G4                                     | 2         | 0.7%    |
| HP Laptop 15-ef1xxx                                   | 2         | 0.7%    |
| HP 450                                                | 2         | 0.7%    |
| HP 14                                                 | 2         | 0.7%    |
| Gigabyte Z77X-UD5H                                    | 2         | 0.7%    |
| Gigabyte B75M-D3H                                     | 2         | 0.7%    |
| Foxconn 500B Microtower                               | 2         | 0.7%    |
| Dell XPS 13 9360                                      | 2         | 0.7%    |
| Dell OptiPlex 7010                                    | 2         | 0.7%    |
| ASUS TUF Gaming B550M-PLUS                            | 2         | 0.7%    |
| ASUS PRIME X570-P                                     | 2         | 0.7%    |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV              | 2         | 0.7%    |
| ASUS All Series                                       | 2         | 0.7%    |
| Unknown                                               | 2         | 0.7%    |
| Toshiba Satellite P755                                | 1         | 0.35%   |
| Toshiba Satellite L855                                | 1         | 0.35%   |
| Toshiba Satellite L45-B                               | 1         | 0.35%   |
| Toshiba Satellite L35                                 | 1         | 0.35%   |
| Toshiba Satellite E205                                | 1         | 0.35%   |
| Toshiba Satellite C845                                | 1         | 0.35%   |
| Toshiba Satellite C655D                               | 1         | 0.35%   |
| Toshiba Satellite C645                                | 1         | 0.35%   |
| Toshiba Satellite C55-B                               | 1         | 0.35%   |
| Toshiba Satellite A665                                | 1         | 0.35%   |
| Toshiba QOSMIO X775                                   | 1         | 0.35%   |
| Toshiba NB505                                         | 1         | 0.35%   |
| SZMZ X99 DUAL Z8                                      | 1         | 0.35%   |
| Sony VPCEC2JFX                                        | 1         | 0.35%   |
| Sony VGN-FW56M                                        | 1         | 0.35%   |
| Sony VGN-FW170J                                       | 1         | 0.35%   |
| Sony SVF15A17CLB                                      | 1         | 0.35%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.35%   |
| Razer Blade                                           | 1         | 0.35%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 1         | 0.35%   |
| RPi Raspberry Pi                                      | 1         | 0.35%   |
| PCChips P49G                                          | 1         | 0.35%   |
| MSI Prestige 14 A10SC                                 | 1         | 0.35%   |
| MSI MS-7D18                                           | 1         | 0.35%   |
| MSI MS-7C88                                           | 1         | 0.35%   |
| MSI MS-7C52                                           | 1         | 0.35%   |
| MSI MS-7B53                                           | 1         | 0.35%   |
| MSI MS-7A33                                           | 1         | 0.35%   |
| MSI MS-7A15                                           | 1         | 0.35%   |
| MSI MS-7978                                           | 1         | 0.35%   |
| MSI MS-7900                                           | 1         | 0.35%   |
| MSI MS-7817                                           | 1         | 0.35%   |
| MSI MS-7758                                           | 1         | 0.35%   |
| MSI MS-7693                                           | 1         | 0.35%   |
| MSI GL65 Leopard 10SEK                                | 1         | 0.35%   |
| Microsoft Surface Pro                                 | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 14        | 4.9%    |
| HP Pavilion        | 14        | 4.9%    |
| Lenovo IdeaPad     | 13        | 4.55%   |
| Toshiba Satellite  | 10        | 3.5%    |
| Acer Aspire        | 10        | 3.5%    |
| Dell Latitude      | 7         | 2.45%   |
| HP ProBook         | 6         | 2.1%    |
| HP Compaq          | 6         | 2.1%    |
| Dell Inspiron      | 6         | 2.1%    |
| ASUS VivoBook      | 6         | 2.1%    |
| HP Laptop          | 5         | 1.75%   |
| Dell OptiPlex      | 5         | 1.75%   |
| ASUS PRIME         | 5         | 1.75%   |
| Lenovo ThinkCentre | 4         | 1.4%    |
| MSI MS-7721        | 3         | 1.05%   |
| Lenovo V330-15IKB  | 3         | 1.05%   |
| Lenovo V310-15ISK  | 3         | 1.05%   |
| Lenovo Legion      | 3         | 1.05%   |
| HP ENVY            | 3         | 1.05%   |
| Gigabyte 970A-DS3P | 3         | 1.05%   |
| ASUS TUF           | 3         | 1.05%   |
| RPi Raspberry      | 2         | 0.7%    |
| Lenovo Yoga        | 2         | 0.7%    |
| Intel DH61WW       | 2         | 0.7%    |
| Intel DH55PJ       | 2         | 0.7%    |
| Intel DG31PR       | 2         | 0.7%    |
| HP ZBook           | 2         | 0.7%    |
| HP Stream          | 2         | 0.7%    |
| HP EliteDesk       | 2         | 0.7%    |
| HP 450             | 2         | 0.7%    |
| HP 240             | 2         | 0.7%    |
| HP 14              | 2         | 0.7%    |
| Gigabyte Z77X-UD5H | 2         | 0.7%    |
| Gigabyte B75M-D3H  | 2         | 0.7%    |
| Foxconn H61MXE     | 2         | 0.7%    |
| Foxconn 500B       | 2         | 0.7%    |
| Dell XPS           | 2         | 0.7%    |
| ASUS ROG           | 2         | 0.7%    |
| ASUS ASUS          | 2         | 0.7%    |
| ASUS All           | 2         | 0.7%    |
| ASRock X570        | 2         | 0.7%    |
| Unknown            | 2         | 0.7%    |
| Toshiba QOSMIO     | 1         | 0.35%   |
| Toshiba NB505      | 1         | 0.35%   |
| SZMZ X99           | 1         | 0.35%   |
| Sony VPCEC2JFX     | 1         | 0.35%   |
| Sony VGN-FW56M     | 1         | 0.35%   |
| Sony VGN-FW170J    | 1         | 0.35%   |
| Sony SVF15A17CLB   | 1         | 0.35%   |
| Samsung 300E5EV    | 1         | 0.35%   |
| Razer Blade        | 1         | 0.35%   |
| PCChips P49G       | 1         | 0.35%   |
| MSI Prestige       | 1         | 0.35%   |
| MSI MS-7D18        | 1         | 0.35%   |
| MSI MS-7C88        | 1         | 0.35%   |
| MSI MS-7C52        | 1         | 0.35%   |
| MSI MS-7B53        | 1         | 0.35%   |
| MSI MS-7A33        | 1         | 0.35%   |
| MSI MS-7A15        | 1         | 0.35%   |
| MSI MS-7978        | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 35        | 12.24%  |
| 2019    | 31        | 10.84%  |
| 2012    | 30        | 10.49%  |
| 2018    | 26        | 9.09%   |
| 2016    | 21        | 7.34%   |
| 2011    | 21        | 7.34%   |
| 2013    | 20        | 6.99%   |
| 2017    | 18        | 6.29%   |
| 2014    | 18        | 6.29%   |
| 2010    | 16        | 5.59%   |
| 2015    | 14        | 4.9%    |
| 2007    | 9         | 3.15%   |
| 2008    | 8         | 2.8%    |
| 2009    | 7         | 2.45%   |
| 2021    | 6         | 2.1%    |
| 2006    | 3         | 1.05%   |
| Unknown | 2         | 0.7%    |
| 2004    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 165       | 57.69%  |
| Desktop        | 109       | 38.11%  |
| Convertible    | 5         | 1.75%   |
| System on chip | 2         | 0.7%    |
| Tablet         | 2         | 0.7%    |
| All in one     | 2         | 0.7%    |
| Mini pc        | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 267       | 93.36%  |
| Enabled  | 19        | 6.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 286       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 71        | 24.15%  |
| 8.01-16.0   | 70        | 23.81%  |
| 3.01-4.0    | 68        | 23.13%  |
| 16.01-24.0  | 47        | 15.99%  |
| 32.01-64.0  | 11        | 3.74%   |
| 1.01-2.0    | 11        | 3.74%   |
| 2.01-3.0    | 6         | 2.04%   |
| 24.01-32.0  | 4         | 1.36%   |
| 64.01-256.0 | 3         | 1.02%   |
| 0.51-1.0    | 3         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 115       | 36.05%  |
| 2.01-3.0   | 89        | 27.9%   |
| 4.01-8.0   | 40        | 12.54%  |
| 3.01-4.0   | 36        | 11.29%  |
| 0.51-1.0   | 30        | 9.4%    |
| 8.01-16.0  | 7         | 2.19%   |
| 16.01-24.0 | 1         | 0.31%   |
| 0.01-0.5   | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 193       | 65.87%  |
| 2      | 75        | 25.6%   |
| 3      | 15        | 5.12%   |
| 4      | 8         | 2.73%   |
| 5      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 56.99%  |
| Yes       | 123       | 43.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 257       | 89.24%  |
| No        | 31        | 10.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 71.48%  |
| No        | 83        | 28.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 57.29%  |
| No        | 123       | 42.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Peru    | 286       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lima                  | 196       | 66.44%  |
| Arequipa              | 24        | 8.14%   |
| Trujillo              | 21        | 7.12%   |
| Tacna                 | 5         | 1.69%   |
| Piura                 | 5         | 1.69%   |
| Huancayo              | 5         | 1.69%   |
| Cusco                 | 5         | 1.69%   |
| Chiclayo              | 5         | 1.69%   |
| Moquegua              | 4         | 1.36%   |
| Junin                 | 2         | 0.68%   |
| Ica                   | 2         | 0.68%   |
| Distrito de Lima      | 2         | 0.68%   |
| Callao                | 2         | 0.68%   |
| Barranco              | 2         | 0.68%   |
| Abancay               | 2         | 0.68%   |
| Villa                 | 1         | 0.34%   |
| Sullana               | 1         | 0.34%   |
| Santiago de Surco     | 1         | 0.34%   |
| San Vicente de Canete | 1         | 0.34%   |
| San Isidro            | 1         | 0.34%   |
| San Borja             | 1         | 0.34%   |
| Punta Colorada        | 1         | 0.34%   |
| Puno                  | 1         | 0.34%   |
| Pucallpa              | 1         | 0.34%   |
| Oxapampa              | 1         | 0.34%   |
| La Libertad           | 1         | 0.34%   |
| Juliaca               | 1         | 0.34%   |
| Iquitos               | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 83        | 128    | 22.07%  |
| WDC                            | 71        | 100    | 18.88%  |
| Toshiba                        | 49        | 58     | 13.03%  |
| Kingston                       | 39        | 49     | 10.37%  |
| Samsung Electronics            | 28        | 37     | 7.45%   |
| Crucial                        | 13        | 17     | 3.46%   |
| SanDisk                        | 12        | 13     | 3.19%   |
| Unknown                        | 7         | 11     | 1.86%   |
| Hitachi                        | 7         | 10     | 1.86%   |
| SK hynix                       | 6         | 8      | 1.6%    |
| Hewlett-Packard                | 6         | 7      | 1.6%    |
| Intel                          | 5         | 6      | 1.33%   |
| LITEON                         | 4         | 4      | 1.06%   |
| KIOXIA                         | 4         | 4      | 1.06%   |
| HGST                           | 4         | 4      | 1.06%   |
| A-DATA Technology              | 4         | 4      | 1.06%   |
| Silicon Motion                 | 3         | 3      | 0.8%    |
| PNY                            | 3         | 3      | 0.8%    |
| Micron/Crucial Technology      | 3         | 3      | 0.8%    |
| Micron Technology              | 3         | 3      | 0.8%    |
| Team                           | 2         | 2      | 0.53%   |
| China                          | 2         | 2      | 0.53%   |
| WD MediaMax                    | 1         | 1      | 0.27%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.27%   |
| UMIS                           | 1         | 1      | 0.27%   |
| TO Exter                       | 1         | 2      | 0.27%   |
| Solid State Storage Technology | 1         | 1      | 0.27%   |
| Phison                         | 1         | 1      | 0.27%   |
| Netac                          | 1         | 1      | 0.27%   |
| Mushkin                        | 1         | 2      | 0.27%   |
| Maxone                         | 1         | 2      | 0.27%   |
| KingSpec                       | 1         | 1      | 0.27%   |
| KESU                           | 1         | 1      | 0.27%   |
| ITHOO                          | 1         | 1      | 0.27%   |
| GLOWAY                         | 1         | 1      | 0.27%   |
| Gigabyte Technology            | 1         | 1      | 0.27%   |
| Fujitsu                        | 1         | 1      | 0.27%   |
| Dogfish                        | 1         | 1      | 0.27%   |
| Apple                          | 1         | 1      | 0.27%   |
| Unknown                        | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 18        | 4.35%   |
| Seagate ST500DM002-1BD142 500GB      | 13        | 3.14%   |
| Kingston SA400S37240G 240GB SSD      | 11        | 2.66%   |
| Toshiba MQ01ABD100 1TB               | 10        | 2.42%   |
| Toshiba MQ04ABF100 1TB               | 9         | 2.17%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 6         | 1.45%   |
| Seagate ST1000DM010-2EP102 1TB       | 6         | 1.45%   |
| Kingston SA400S37480G 480GB SSD      | 6         | 1.45%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 1.45%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.21%   |
| HP SSD S700 500GB                    | 5         | 1.21%   |
| WDC WD10SPZX-24Z10 1TB               | 4         | 0.97%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.97%   |
| Seagate ST3500418AS 500GB            | 4         | 0.97%   |
| Seagate ST3500413AS 500GB            | 4         | 0.97%   |
| Seagate ST2000DM001-1ER164 2TB       | 4         | 0.97%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB             | 3         | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.72%   |
| Seagate ST9500325AS 500GB            | 3         | 0.72%   |
| Seagate ST3500312CS 500GB            | 3         | 0.72%   |
| Seagate ST2000DM006-2DM164 2TB       | 3         | 0.72%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.72%   |
| Kingston NVMe SSD Drive 500GB        | 3         | 0.72%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.48%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.48%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 2         | 0.48%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.48%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2         | 0.48%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.48%   |
| Unknown MMC Card  32GB               | 2         | 0.48%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.48%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.48%   |
| Toshiba DT01ACA050 500GB             | 2         | 0.48%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.48%   |
| Seagate ST2000DL003-9VT166 2TB       | 2         | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.48%   |
| Seagate Expansion 500GB              | 2         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.48%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.48%   |
| Samsung HD322HJ 320GB                | 2         | 0.48%   |
| Samsung HD161HJ 160GB                | 2         | 0.48%   |
| Samsung HD080HJ 80GB                 | 2         | 0.48%   |
| Micron/Crucial NVMe SSD Drive 1TB    | 2         | 0.48%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.48%   |
| Kingston SNVS250G 250GB              | 2         | 0.48%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.48%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.48%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.48%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 0.48%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.48%   |
| A-DATA SP550 240GB SSD               | 2         | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.24%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.24%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.24%   |
| WDC WDS250G2B0B 250GB SSD            | 1         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 121    | 39.71%  |
| WDC                 | 49        | 64     | 24.02%  |
| Toshiba             | 48        | 57     | 23.53%  |
| Samsung Electronics | 12        | 16     | 5.88%   |
| Hitachi             | 7         | 10     | 3.43%   |
| HGST                | 4         | 4      | 1.96%   |
| KESU                | 1         | 1      | 0.49%   |
| Fujitsu             | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 31        | 36     | 30.1%   |
| WDC                 | 22        | 28     | 21.36%  |
| Crucial             | 10        | 13     | 9.71%   |
| Hewlett-Packard     | 6         | 6      | 5.83%   |
| SanDisk             | 5         | 6      | 4.85%   |
| LITEON              | 4         | 4      | 3.88%   |
| A-DATA Technology   | 4         | 4      | 3.88%   |
| Seagate             | 3         | 7      | 2.91%   |
| Samsung Electronics | 3         | 3      | 2.91%   |
| PNY                 | 3         | 3      | 2.91%   |
| Team                | 2         | 2      | 1.94%   |
| China               | 2         | 2      | 1.94%   |
| TO Exter            | 1         | 2      | 0.97%   |
| SK hynix            | 1         | 2      | 0.97%   |
| Netac               | 1         | 1      | 0.97%   |
| Maxone              | 1         | 2      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| Intel               | 1         | 1      | 0.97%   |
| GLOWAY              | 1         | 1      | 0.97%   |
| Dogfish             | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 187       | 275    | 52.82%  |
| SSD     | 93        | 125    | 26.27%  |
| NVMe    | 64        | 83     | 18.08%  |
| MMC     | 8         | 12     | 2.26%   |
| Unknown | 2         | 2      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 240       | 395    | 75.47%  |
| NVMe | 64        | 83     | 20.13%  |
| MMC  | 8         | 12     | 2.52%   |
| SAS  | 6         | 7      | 1.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 158       | 241    | 55.83%  |
| 0.51-1.0   | 107       | 129    | 37.81%  |
| 1.01-2.0   | 13        | 22     | 4.59%   |
| 3.01-4.0   | 2         | 3      | 0.71%   |
| 4.01-10.0  | 2         | 4      | 0.71%   |
| 2.01-3.0   | 1         | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 75        | 24.75%  |
| 101-250        | 69        | 22.77%  |
| 501-1000       | 57        | 18.81%  |
| 51-100         | 25        | 8.25%   |
| 21-50          | 19        | 6.27%   |
| 1-20           | 18        | 5.94%   |
| 1001-2000      | 15        | 4.95%   |
| 2001-3000      | 12        | 3.96%   |
| More than 3000 | 7         | 2.31%   |
| Unknown        | 6         | 1.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 39.94%  |
| 21-50          | 63        | 20.45%  |
| 101-250        | 33        | 10.71%  |
| 251-500        | 27        | 8.77%   |
| 51-100         | 26        | 8.44%   |
| 501-1000       | 16        | 5.19%   |
| 1001-2000      | 9         | 2.92%   |
| Unknown        | 6         | 1.95%   |
| More than 3000 | 3         | 0.97%   |
| 2001-3000      | 2         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3         | 3      | 9.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1         | 1      | 3.13%   |
| WDC WDS100T2G0A-00JH30 1TB SSD    | 1         | 1      | 3.13%   |
| WDC WD800BD-00MRA1 80GB           | 1         | 1      | 3.13%   |
| WDC WD3200AAJS-56M0A0 320GB       | 1         | 1      | 3.13%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1         | 1      | 3.13%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 3.13%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 3.13%   |
| Toshiba MK2035GSS 200GB           | 1         | 1      | 3.13%   |
| Seagate ST980811AS 80GB           | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 3.13%   |
| Seagate ST500DM002-9YN14C 500GB   | 1         | 1      | 3.13%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 3.13%   |
| Seagate ST3250820AS 250GB         | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 3.13%   |
| Seagate ST1000LM014-1EJ164 1TB    | 1         | 1      | 3.13%   |
| Seagate ST1000DM003-9YN162 1TB    | 1         | 1      | 3.13%   |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 1      | 3.13%   |
| Samsung Electronics SP1644N 160GB | 1         | 1      | 3.13%   |
| Samsung Electronics HD161HJ 160GB | 1         | 2      | 3.13%   |
| Kingston SA400S37480G 480GB SSD   | 1         | 1      | 3.13%   |
| Hitachi HTS725050A7E630 500GB     | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 2      | 3.13%   |
| Hitachi HTS545032B9A302 320GB     | 1         | 1      | 3.13%   |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 3.13%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 3.13%   |
| A-DATA Technology SP550 240GB SSD | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 40.63%  |
| WDC                 | 6         | 6      | 18.75%  |
| Hitachi             | 5         | 6      | 15.63%  |
| Toshiba             | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 3      | 6.25%   |
| Kingston            | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 46.43%  |
| Hitachi             | 5         | 6      | 17.86%  |
| WDC                 | 4         | 4      | 14.29%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Samsung Electronics | 2         | 3      | 7.14%   |
| HGST                | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 30     | 86.67%  |
| SSD  | 4         | 4      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 181       | 309    | 58.39%  |
| Works    | 99        | 152    | 31.94%  |
| Malfunc  | 29        | 34     | 9.35%   |
| Failed   | 1         | 2      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 191       | 57.36%  |
| AMD                              | 64        | 19.22%  |
| SanDisk                          | 13        | 3.9%    |
| Samsung Electronics              | 13        | 3.9%    |
| Kingston Technology Company      | 9         | 2.7%    |
| Micron/Crucial Technology        | 6         | 1.8%    |
| Marvell Technology Group         | 6         | 1.8%    |
| SK hynix                         | 5         | 1.5%    |
| Silicon Motion                   | 5         | 1.5%    |
| Nvidia                           | 4         | 1.2%    |
| KIOXIA                           | 4         | 1.2%    |
| Micron Technology                | 3         | 0.9%    |
| JMicron Technology               | 3         | 0.9%    |
| Unknown                          | 1         | 0.3%    |
| Union Memory (Shenzhen)          | 1         | 0.3%    |
| Toshiba America Info Systems     | 1         | 0.3%    |
| Solid State Storage Technology   | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Phison Electronics               | 1         | 0.3%    |
| LSI Logic / Symbios Logic        | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 45        | 11.75%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 24        | 6.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 4.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 3.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 2.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 2.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 2.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 2.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.83%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 1.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.31%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.04%   |
| Micron/Crucial NVMe Controller                                                          | 4         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 4         | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 1.04%   |
| SK hynix BC511                                                                          | 3         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.78%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.78%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.78%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.78%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 0.78%   |
| SanDisk PC SN520 NVMe SSD                                                               | 2         | 0.52%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.52%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2         | 0.52%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2         | 0.52%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 2         | 0.52%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.52%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 2         | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 2         | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 0.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.52%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2         | 0.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 0.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.52%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 209       | 62.2%   |
| NVMe | 64        | 19.05%  |
| IDE  | 44        | 13.1%   |
| RAID | 18        | 5.36%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 208       | 72.73%  |
| AMD    | 76        | 26.57%  |
| ARM    | 2         | 0.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 8         | 2.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 6         | 2.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 6         | 2.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 2.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 5         | 1.74%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 5         | 1.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 4         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 1.39%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 1.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 3         | 1.05%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 3         | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 3         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 3         | 1.05%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 3         | 1.05%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 3         | 1.05%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 2         | 0.7%    |
| Intel Pentium CPU G4560 @ 3.50GHz               | 2         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2         | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 0.7%    |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 2         | 0.7%    |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 0.7%    |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 0.7%    |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.7%    |
| Intel Core i3-2328M CPU @ 2.20GHz               | 2         | 0.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 2         | 0.7%    |
| Intel Core 2 CPU 6300 @ 1.86GHz                 | 2         | 0.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 0.7%    |
| Intel Celeron CPU 550 @ 2.00GHz                 | 2         | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 0.7%    |
| ARM Processor                                   | 2         | 0.7%    |
| AMD Sempron 140 Processor                       | 2         | 0.7%    |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor               | 2         | 0.7%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 2         | 0.7%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 2         | 0.7%    |
| AMD FX-8350 Eight-Core Processor                | 2         | 0.7%    |
| AMD E1-6010 APU with AMD Radeon R2 Graphics     | 2         | 0.7%    |
| AMD Athlon Silver 3050U with Radeon Graphics    | 2         | 0.7%    |
| Intel Xeon CPU X5650 @ 2.67GHz                  | 1         | 0.35%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz             | 1         | 0.35%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz              | 1         | 0.35%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 1         | 0.35%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 0.35%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz          | 1         | 0.35%   |
| Intel Pentium D CPU 3.00GHz                     | 1         | 0.35%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.35%   |
| Intel Pentium CPU G620 @ 2.60GHz                | 1         | 0.35%   |
| Intel Pentium CPU E5500 @ 2.80GHz               | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 68        | 23.78%  |
| Intel Core i5           | 59        | 20.63%  |
| Intel Core i3           | 31        | 10.84%  |
| AMD Ryzen 5             | 18        | 6.29%   |
| AMD Ryzen 7             | 13        | 4.55%   |
| Intel Core 2 Duo        | 9         | 3.15%   |
| Intel Celeron           | 9         | 3.15%   |
| Other                   | 8         | 2.8%    |
| Intel Pentium           | 6         | 2.1%    |
| Intel Atom              | 5         | 1.75%   |
| AMD Ryzen 3             | 5         | 1.75%   |
| AMD Ryzen 9             | 4         | 1.4%    |
| AMD FX                  | 4         | 1.4%    |
| AMD A8                  | 4         | 1.4%    |
| Intel Xeon              | 3         | 1.05%   |
| Intel Pentium Dual      | 3         | 1.05%   |
| AMD E1                  | 3         | 1.05%   |
| AMD Athlon              | 3         | 1.05%   |
| AMD A10                 | 3         | 1.05%   |
| Intel Pentium Dual-Core | 2         | 0.7%    |
| Intel Pentium 4         | 2         | 0.7%    |
| Intel Core 2 Quad       | 2         | 0.7%    |
| Intel Core 2            | 2         | 0.7%    |
| AMD Sempron             | 2         | 0.7%    |
| AMD Ryzen 7 PRO         | 2         | 0.7%    |
| AMD Phenom II X4        | 2         | 0.7%    |
| AMD A6                  | 2         | 0.7%    |
| Intel Pentium D         | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| AMD Phenom II X3        | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-50                | 1         | 0.35%   |
| AMD Athlon X4           | 1         | 0.35%   |
| AMD Athlon II X3        | 1         | 0.35%   |
| AMD Athlon II X2        | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |
| AMD A4                  | 1         | 0.35%   |
| AMD A12                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 122       | 42.66%  |
| 4       | 110       | 38.46%  |
| 6       | 19        | 6.64%   |
| 8       | 15        | 5.24%   |
| 1       | 12        | 4.2%    |
| 3       | 3         | 1.05%   |
| Unknown | 2         | 0.7%    |
| 20      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 12      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 286       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 201       | 70.28%  |
| 1       | 83        | 29.02%  |
| Unknown | 2         | 0.7%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 275       | 94.83%  |
| 64-bit         | 6         | 2.07%   |
| Unknown        | 6         | 2.07%   |
| 32-bit         | 3         | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 13.06%  |
| 0x306a9    | 23        | 7.9%    |
| 0x206a7    | 22        | 7.56%   |
| 0x306c3    | 11        | 3.78%   |
| 0x806ec    | 10        | 3.44%   |
| 0x40651    | 10        | 3.44%   |
| 0x806ea    | 9         | 3.09%   |
| 0x806e9    | 9         | 3.09%   |
| 0x406e3    | 9         | 3.09%   |
| 0x08108109 | 9         | 3.09%   |
| 0x1067a    | 7         | 2.41%   |
| 0x08701021 | 7         | 2.41%   |
| 0x906ea    | 6         | 2.06%   |
| 0x506e3    | 6         | 2.06%   |
| 0x306d4    | 6         | 2.06%   |
| 0x08108102 | 6         | 2.06%   |
| 0x20655    | 5         | 1.72%   |
| 0x906e9    | 4         | 1.37%   |
| 0x6fd      | 4         | 1.37%   |
| 0x406c4    | 4         | 1.37%   |
| 0x06003106 | 4         | 1.37%   |
| 0x010000c8 | 4         | 1.37%   |
| 0xa0652    | 3         | 1.03%   |
| 0x806eb    | 3         | 1.03%   |
| 0x6fb      | 3         | 1.03%   |
| 0x30678    | 3         | 1.03%   |
| 0x10676    | 3         | 1.03%   |
| 0x0810100b | 3         | 1.03%   |
| 0x07030105 | 3         | 1.03%   |
| 0x06001119 | 3         | 1.03%   |
| 0xf64      | 2         | 0.69%   |
| 0x806c1    | 2         | 0.69%   |
| 0x706e5    | 2         | 0.69%   |
| 0x20652    | 2         | 0.69%   |
| 0x10661    | 2         | 0.69%   |
| 0x0a50000c | 2         | 0.69%   |
| 0x08701013 | 2         | 0.69%   |
| 0x08600106 | 2         | 0.69%   |
| 0x08600104 | 2         | 0.69%   |
| 0x06000852 | 2         | 0.69%   |
| 0x05000029 | 2         | 0.69%   |
| 0x010000c7 | 2         | 0.69%   |
| 0xf49      | 1         | 0.34%   |
| 0xa0671    | 1         | 0.34%   |
| 0xa0655    | 1         | 0.34%   |
| 0xa0653    | 1         | 0.34%   |
| 0x906ed    | 1         | 0.34%   |
| 0x706a8    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6f6      | 1         | 0.34%   |
| 0x6f2      | 1         | 0.34%   |
| 0x6e8      | 1         | 0.34%   |
| 0x6d8      | 1         | 0.34%   |
| 0x406f1    | 1         | 0.34%   |
| 0x206c2    | 1         | 0.34%   |
| 0x106e5    | 1         | 0.34%   |
| 0x106ca    | 1         | 0.34%   |
| 0x106c2    | 1         | 0.34%   |
| 0x0a201009 | 1         | 0.34%   |
| 0x08600102 | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 53        | 18.53%  |
| IvyBridge     | 26        | 9.09%   |
| SandyBridge   | 23        | 8.04%   |
| Haswell       | 22        | 7.69%   |
| Zen+          | 18        | 6.29%   |
| Zen 2         | 16        | 5.59%   |
| Skylake       | 15        | 5.24%   |
| Penryn        | 11        | 3.85%   |
| Core          | 11        | 3.85%   |
| Westmere      | 9         | 3.15%   |
| K10           | 8         | 2.8%    |
| Zen           | 7         | 2.45%   |
| Silvermont    | 7         | 2.45%   |
| Broadwell     | 7         | 2.45%   |
| Piledriver    | 6         | 2.1%    |
| CometLake     | 6         | 2.1%    |
| Steamroller   | 5         | 1.75%   |
| Puma          | 4         | 1.4%    |
| IceLake       | 4         | 1.4%    |
| Zen 3         | 3         | 1.05%   |
| NetBurst      | 3         | 1.05%   |
| Excavator     | 3         | 1.05%   |
| Unknown       | 3         | 1.05%   |
| TigerLake     | 2         | 0.7%    |
| P6            | 2         | 0.7%    |
| Nehalem       | 2         | 0.7%    |
| Goldmont plus | 2         | 0.7%    |
| Bonnell       | 2         | 0.7%    |
| Bobcat        | 2         | 0.7%    |
| K8 Hammer     | 1         | 0.35%   |
| K10 Llano     | 1         | 0.35%   |
| Jaguar        | 1         | 0.35%   |
| Bulldozer     | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 173       | 50.29%  |
| AMD                              | 93        | 27.03%  |
| Nvidia                           | 77        | 22.38%  |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 4.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 3.93%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.09%   |
| Intel HD Graphics 620                                                                    | 10        | 2.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 2.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.97%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.69%   |
| AMD Renoir                                                                               | 6         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.4%    |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.12%   |
| Intel HD Graphics 530                                                                    | 4         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.84%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.84%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.84%   |
| Intel HD Graphics 630                                                                    | 3         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.84%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3         | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.84%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3         | 0.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.56%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                                      | 2         | 0.56%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.56%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.56%   |
| Intel HD Graphics 610                                                                    | 2         | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.56%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.56%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.56%   |
| AMD RV370 [Radeon X300]                                                                  | 2         | 0.56%   |
| AMD RV370 [Radeon X300 SE]                                                               | 2         | 0.56%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 115       | 40.07%  |
| 1 x AMD        | 66        | 23%     |
| 1 x Nvidia     | 38        | 13.24%  |
| Intel + Nvidia | 37        | 12.89%  |
| Intel + AMD    | 17        | 5.92%   |
| 2 x AMD        | 8         | 2.79%   |
| Other          | 2         | 0.7%    |
| AMD + Nvidia   | 2         | 0.7%    |
| 2 x Intel      | 1         | 0.35%   |
| 1 x SiS        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 245       | 84.19%  |
| Proprietary | 38        | 13.06%  |
| Unknown     | 8         | 2.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 47.96%  |
| 1.01-2.0   | 60        | 20.41%  |
| 0.01-0.5   | 33        | 11.22%  |
| 0.51-1.0   | 22        | 7.48%   |
| 3.01-4.0   | 19        | 6.46%   |
| 5.01-6.0   | 9         | 3.06%   |
| 7.01-8.0   | 8         | 2.72%   |
| 8.01-16.0  | 2         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 46        | 15.23%  |
| Chimei Innolux       | 43        | 14.24%  |
| Goldstar             | 34        | 11.26%  |
| BOE                  | 34        | 11.26%  |
| AU Optronics         | 32        | 10.6%   |
| LG Display           | 23        | 7.62%   |
| AOC                  | 14        | 4.64%   |
| Hewlett-Packard      | 13        | 4.3%    |
| Lenovo               | 7         | 2.32%   |
| Sony                 | 5         | 1.66%   |
| Dell                 | 5         | 1.66%   |
| ViewSonic            | 4         | 1.32%   |
| Unknown              | 4         | 1.32%   |
| Sharp                | 3         | 0.99%   |
| PANDA                | 3         | 0.99%   |
| BenQ                 | 3         | 0.99%   |
| LG Electronics       | 2         | 0.66%   |
| JRY                  | 2         | 0.66%   |
| HannStar             | 2         | 0.66%   |
| ASUSTek Computer     | 2         | 0.66%   |
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
| Unknown              | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 9         | 2.93%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 7         | 2.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 1.63%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 440x250mm 19.9-inch  | 3         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 3         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 3         | 0.98%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 3         | 0.98%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 890x500mm 40.2-inch | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                      | 2         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.65%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                        | 2         | 0.65%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch          | 2         | 0.65%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 2         | 0.65%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 2         | 0.65%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.65%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.65%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                   | 2         | 0.65%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                   | 2         | 0.65%   |
| Dell 3008WFP DEL4036 2560x1600 641x400mm 29.7-inch                    | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.65%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.65%   |
| AOC 2239 AOC2239 1920x1080 477x268mm 21.5-inch                        | 2         | 0.65%   |
| Viotek FI24D VTK0238 2560x1440 530x290mm 23.8-inch                    | 1         | 0.33%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1         | 0.33%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch         | 1         | 0.33%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 1         | 0.33%   |
| ViewSonic LCD Monitor VSCDE2E 1920x1080 520x290mm 23.4-inch           | 1         | 0.33%   |
| Unknown LCD Monitor RJT HDMI                                          | 1         | 0.33%   |
| Unknown LCD Monitor OOO TE-3190N 2560x1440                            | 1         | 0.33%   |
| Unknown LCD Monitor OOO MA2224W 1920x1080                             | 1         | 0.33%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                             | 1         | 0.33%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch             | 1         | 0.33%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.33%   |
| Sony TV SNYEF03 1600x900                                              | 1         | 0.33%   |
| Sony TV SNY2601 1360x768 710x400mm 32.1-inch                          | 1         | 0.33%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 1         | 0.33%   |
| Sony LCD Monitor TV 1360x768                                          | 1         | 0.33%   |
| Sony LCD Monitor TV                                                   | 1         | 0.33%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x287mm 23.0-inch  | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM022E 1024x768 267x200mm 13.1-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.33%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch    | 1         | 0.33%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch  | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 115       | 39.25%  |
| 1920x1080 (FHD)   | 94        | 32.08%  |
| 1600x900 (HD+)    | 20        | 6.83%   |
| 1360x768          | 12        | 4.1%    |
| 3840x2160 (4K)    | 10        | 3.41%   |
| 1440x900 (WXGA+)  | 6         | 2.05%   |
| 2560x1440 (QHD)   | 5         | 1.71%   |
| 1024x768 (XGA)    | 5         | 1.71%   |
| Unknown           | 4         | 1.37%   |
| 3840x1080         | 3         | 1.02%   |
| 1280x800 (WXGA)   | 3         | 1.02%   |
| 3200x1800 (QHD+)  | 2         | 0.68%   |
| 2560x1600         | 2         | 0.68%   |
| 1920x1200 (WUXGA) | 2         | 0.68%   |
| 1280x1024 (SXGA)  | 2         | 0.68%   |
| 1024x600          | 2         | 0.68%   |
| 3440x1440         | 1         | 0.34%   |
| 3200x2000         | 1         | 0.34%   |
| 2736x1824         | 1         | 0.34%   |
| 2560x1080         | 1         | 0.34%   |
| 2160x1440         | 1         | 0.34%   |
| 1280x720 (HD)     | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 93        | 31%     |
| 13      | 39        | 13%     |
| 21      | 27        | 9%      |
| 14      | 26        | 8.67%   |
| 23      | 21        | 7%      |
| 18      | 13        | 4.33%   |
| 20      | 11        | 3.67%   |
| Unknown | 11        | 3.67%   |
| 27      | 9         | 3%      |
| 19      | 8         | 2.67%   |
| 17      | 8         | 2.67%   |
| 24      | 5         | 1.67%   |
| 48      | 3         | 1%      |
| 32      | 3         | 1%      |
| 31      | 3         | 1%      |
| 12      | 3         | 1%      |
| 11      | 3         | 1%      |
| 84      | 2         | 0.67%   |
| 72      | 2         | 0.67%   |
| 30      | 2         | 0.67%   |
| 10      | 2         | 0.67%   |
| 60      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 46      | 1         | 0.33%   |
| 43      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 148       | 50%     |
| 401-500     | 56        | 18.92%  |
| 501-600     | 34        | 11.49%  |
| 201-300     | 16        | 5.41%   |
| Unknown     | 11        | 3.72%   |
| 351-400     | 10        | 3.38%   |
| 1001-1500   | 6         | 2.03%   |
| 601-700     | 5         | 1.69%   |
| 701-800     | 4         | 1.35%   |
| 1501-2000   | 4         | 1.35%   |
| 801-900     | 1         | 0.34%   |
| 901-1000    | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 228       | 84.76%  |
| 16/10   | 16        | 5.95%   |
| Unknown | 11        | 4.09%   |
| 4/3     | 7         | 2.6%    |
| 5/4     | 4         | 1.49%   |
| 3/2     | 2         | 0.74%   |
| 21/9    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 31.31%  |
| 81-90          | 58        | 19.53%  |
| 201-250        | 40        | 13.47%  |
| 151-200        | 28        | 9.43%   |
| 141-150        | 15        | 5.05%   |
| Unknown        | 11        | 3.7%    |
| More than 1000 | 9         | 3.03%   |
| 351-500        | 9         | 3.03%   |
| 301-350        | 9         | 3.03%   |
| 71-80          | 8         | 2.69%   |
| 121-130        | 4         | 1.35%   |
| 51-60          | 3         | 1.01%   |
| 501-1000       | 3         | 1.01%   |
| 41-50          | 2         | 0.67%   |
| 131-140        | 2         | 0.67%   |
| 61-70          | 1         | 0.34%   |
| 251-300        | 1         | 0.34%   |
| 91-100         | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 138       | 47.26%  |
| 51-100        | 77        | 26.37%  |
| 121-160       | 45        | 15.41%  |
| 1-50          | 12        | 4.11%   |
| Unknown       | 11        | 3.77%   |
| 161-240       | 5         | 1.71%   |
| More than 240 | 4         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 245       | 83.62%  |
| 2     | 39        | 13.31%  |
| 0     | 7         | 2.39%   |
| 3     | 2         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 182       | 43.33%  |
| Intel                            | 100       | 23.81%  |
| Qualcomm Atheros                 | 63        | 15%     |
| Broadcom                         | 13        | 3.1%    |
| TP-Link                          | 12        | 2.86%   |
| Ralink Technology                | 6         | 1.43%   |
| Ralink                           | 5         | 1.19%   |
| Qualcomm Atheros Communications  | 4         | 0.95%   |
| Nvidia                           | 4         | 0.95%   |
| Marvell Technology Group         | 4         | 0.95%   |
| Xiaomi                           | 3         | 0.71%   |
| ICS Advent                       | 3         | 0.71%   |
| Broadcom Limited                 | 3         | 0.71%   |
| ASIX Electronics                 | 3         | 0.71%   |
| Motorola PCS                     | 2         | 0.48%   |
| Huawei Technologies              | 2         | 0.48%   |
| D-Link System                    | 2         | 0.48%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.24%   |
| T & A Mobile Phones              | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Samsung Electronics              | 1         | 0.24%   |
| Microsoft                        | 1         | 0.24%   |
| MediaTek                         | 1         | 0.24%   |
| Lenovo                           | 1         | 0.24%   |
| D-Link                           | 1         | 0.24%   |
| Apple                            | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128       | 26.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 5.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 4.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 2.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.02%   |
| Intel Wireless 7265                                               | 5         | 1.02%   |
| Intel Wireless 7260                                               | 5         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.81%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.81%   |
| Intel Wireless 8260                                               | 4         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.61%   |
| TP-Link 802.11n NIC                                               | 3         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.61%   |
| Intel 82578DC Gigabit Network Connection                          | 3         | 0.61%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 3         | 0.61%   |
| TP-Link USB 10/100 LAN                                            | 2         | 0.41%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                           | 2         | 0.41%   |
| TP-Link TL-WN722N v2                                              | 2         | 0.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.41%   |
| Motorola PCS Moto E (4) Plus                                      | 2         | 0.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.41%   |
| Intel WiFi Link 5100                                              | 2         | 0.41%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.41%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.41%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 31.48%  |
| Qualcomm Atheros                | 55        | 25.46%  |
| Realtek Semiconductor           | 51        | 23.61%  |
| Broadcom                        | 11        | 5.09%   |
| TP-Link                         | 10        | 4.63%   |
| Ralink Technology               | 6         | 2.78%   |
| Ralink                          | 5         | 2.31%   |
| Qualcomm Atheros Communications | 4         | 1.85%   |
| Microsoft                       | 1         | 0.46%   |
| MediaTek                        | 1         | 0.46%   |
| Marvell Technology Group        | 1         | 0.46%   |
| D-Link System                   | 1         | 0.46%   |
| D-Link                          | 1         | 0.46%   |
| Broadcom Limited                | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 20        | 9.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 14        | 6.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 12        | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 9         | 4.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 7         | 3.24%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 7         | 3.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 6         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                           | 6         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 5         | 2.31%   |
| Intel Wireless 7265                                                           | 5         | 2.31%   |
| Intel Wireless 7260                                                           | 5         | 2.31%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                               | 4         | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 4         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 1.85%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 1.85%   |
| Intel Wireless 8260                                                           | 4         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 4         | 1.85%   |
| TP-Link 802.11n NIC                                                           | 3         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 3         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 3         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.39%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                       | 2         | 0.93%   |
| TP-Link TL-WN722N v2                                                          | 2         | 0.93%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2         | 0.93%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 0.93%   |
| Intel WiFi Link 5100                                                          | 2         | 0.93%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 0.93%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 0.46%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.46%   |
| Realtek RTL8187 Wireless Adapter                                              | 1         | 0.46%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1         | 0.46%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1         | 0.46%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.46%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.46%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1         | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.46%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 0.46%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.46%   |
| Intel Wireless 3165                                                           | 1         | 0.46%   |
| Intel Wireless 3160                                                           | 1         | 0.46%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 166       | 61.25%  |
| Intel                            | 57        | 21.03%  |
| Qualcomm Atheros                 | 14        | 5.17%   |
| Nvidia                           | 4         | 1.48%   |
| Xiaomi                           | 3         | 1.11%   |
| Marvell Technology Group         | 3         | 1.11%   |
| ICS Advent                       | 3         | 1.11%   |
| Broadcom                         | 3         | 1.11%   |
| ASIX Electronics                 | 3         | 1.11%   |
| TP-Link                          | 2         | 0.74%   |
| Motorola PCS                     | 2         | 0.74%   |
| Huawei Technologies              | 2         | 0.74%   |
| Broadcom Limited                 | 2         | 0.74%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.37%   |
| T & A Mobile Phones              | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Samsung Electronics              | 1         | 0.37%   |
| Lenovo                           | 1         | 0.37%   |
| D-Link System                    | 1         | 0.37%   |
| Apple                            | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 128       | 46.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 10.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4%      |
| Intel 82579V Gigabit Network Connection                                        | 6         | 2.18%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 1.82%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.09%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.09%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.09%   |
| Intel 82578DC Gigabit Network Connection                                       | 3         | 1.09%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 3         | 1.09%   |
| TP-Link USB 10/100 LAN                                                         | 2         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.73%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.73%   |
| Motorola PCS Moto E (4) Plus                                                   | 2         | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.73%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.73%   |
| Huawei JNY-LX1                                                                 | 2         | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.73%   |
| ZTE WCDMA MSM Z6201V                                                           | 1         | 0.36%   |
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
| Intel Ethernet Connection I217-V                                               | 1         | 0.36%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.36%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.36%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (12) I219-V                                          | 1         | 0.36%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.36%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.36%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 1         | 0.36%   |
| Intel 82567V-4 Gigabit Network Connection                                      | 1         | 0.36%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.36%   |
| Intel 82567LM-2 Gigabit Network Connection                                     | 1         | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.36%   |
| Intel 82566DM Gigabit Network Connection                                       | 1         | 0.36%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 0.36%   |
| Intel 82566DC Gigabit Network Connection                                       | 1         | 0.36%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 257       | 55.27%  |
| WiFi     | 208       | 44.73%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 161       | 53.31%  |
| Ethernet | 141       | 46.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 156       | 54.36%  |
| 1     | 125       | 43.55%  |
| 0     | 4         | 1.39%   |
| 3     | 2         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 247       | 85.47%  |
| Yes  | 42        | 14.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 30.3%   |
| Realtek Semiconductor           | 34        | 20.61%  |
| Qualcomm Atheros Communications | 30        | 18.18%  |
| Cambridge Silicon Radio         | 10        | 6.06%   |
| Lite-On Technology              | 9         | 5.45%   |
| IMC Networks                    | 8         | 4.85%   |
| Toshiba                         | 4         | 2.42%   |
| Ralink                          | 4         | 2.42%   |
| Broadcom                        | 4         | 2.42%   |
| Hewlett-Packard                 | 2         | 1.21%   |
| Foxconn / Hon Hai               | 2         | 1.21%   |
| Dell                            | 2         | 1.21%   |
| TRENDnet                        | 1         | 0.61%   |
| TP-Link                         | 1         | 0.61%   |
| Integrated System Solution      | 1         | 0.61%   |
| Foxconn International           | 1         | 0.61%   |
| Apple                           | 1         | 0.61%   |
| Alps Electric                   | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Realtek  Bluetooth 4.2 Adapter                        | 17        | 10.3%   |
| Qualcomm Atheros  Bluetooth Device                    | 17        | 10.3%   |
| Intel Bluetooth wireless interface                    | 17        | 10.3%   |
| Realtek Bluetooth Radio                               | 14        | 8.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10        | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 10        | 6.06%   |
| Intel AX201 Bluetooth                                 | 9         | 5.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 3.64%   |
| Intel AX200 Bluetooth                                 | 6         | 3.64%   |
| Ralink RT3290 Bluetooth                               | 4         | 2.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3         | 1.82%   |
| Lite-On Bluetooth Device                              | 3         | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.82%   |
| IMC Networks Bluetooth Radio                          | 3         | 1.82%   |
| IMC Networks Bluetooth Device                         | 3         | 1.82%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.21%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 2         | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 1.21%   |
| Lite-On Bluetooth Radio                               | 2         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 1.21%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 2         | 1.21%   |
| TRENDnet TBW-108UB USB Adapter                        | 1         | 0.61%   |
| TP-Link UB500 Adapter                                 | 1         | 0.61%   |
| Toshiba RT Bluetooth Radio                            | 1         | 0.61%   |
| Toshiba Bluetooth Device                              | 1         | 0.61%   |
| Toshiba BCM43142A0                                    | 1         | 0.61%   |
| Toshiba Askey Bluetooth Module                        | 1         | 0.61%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1         | 0.61%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.61%   |
| IMC Networks Wireless_Device                          | 1         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module     | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1         | 0.61%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 0.61%   |
| Dell DW375 Bluetooth Module                           | 1         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.61%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.61%   |
| Apple Bluetooth USB Host Controller                   | 1         | 0.61%   |
| Alps Electric BCM2046 Bluetooth Device                | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 201       | 55.83%  |
| AMD                              | 88        | 24.44%  |
| Nvidia                           | 54        | 15%     |
| C-Media Electronics              | 3         | 0.83%   |
| Texas Instruments                | 2         | 0.56%   |
| Microsoft                        | 2         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Samson Technologies              | 1         | 0.28%   |
| Razer USA                        | 1         | 0.28%   |
| Pixart Imaging                   | 1         | 0.28%   |
| Logitech                         | 1         | 0.28%   |
| Kingston Technology              | 1         | 0.28%   |
| Hewlett-Packard                  | 1         | 0.28%   |
| Generalplus Technology           | 1         | 0.28%   |
| Creative Labs                    | 1         | 0.28%   |
| Chicony Electronics              | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 7.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 6.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 6.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 4.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 3.17%   |
| AMD FCH Azalia Controller                                                                         | 14        | 3.17%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.49%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 2.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 2.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.36%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.9%    |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.68%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.68%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.45%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.45%   |
| Microsoft LifeChat LX-3000 Headset                                                                | 2         | 0.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.45%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 0.45%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.45%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.45%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.45%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.45%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 2         | 0.45%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 48        | 24.87%  |
| Kingston                     | 44        | 22.8%   |
| SK hynix                     | 34        | 17.62%  |
| Micron Technology            | 25        | 12.95%  |
| Unknown                      | 12        | 6.22%   |
| Ramaxel Technology           | 6         | 3.11%   |
| Corsair                      | 6         | 3.11%   |
| Crucial                      | 4         | 2.07%   |
| Hewlett-Packard              | 3         | 1.55%   |
| Unknown (ABCD)               | 1         | 0.52%   |
| Unknown (0x7FA8000000000000) | 1         | 0.52%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.52%   |
| Team                         | 1         | 0.52%   |
| Qumo                         | 1         | 0.52%   |
| Princeton                    | 1         | 0.52%   |
| Patriot                      | 1         | 0.52%   |
| Goldkey                      | 1         | 0.52%   |
| GeIL                         | 1         | 0.52%   |
| CSX                          | 1         | 0.52%   |
| A-DATA Technology            | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 2.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 5         | 2.44%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1.95%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.46%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 1.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 3         | 1.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.98%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.98%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 2         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.98%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.98%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 0.98%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.98%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 2         | 0.98%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s                 | 2         | 0.98%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s             | 2         | 0.98%   |
| Kingston RAM CL16-18-18 D4-3200 8192MB DIMM DDR4 3200MT/s           | 2         | 0.98%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s             | 2         | 0.98%   |
| Kingston RAM 9905471-017.A00LF 4096MB DIMM DDR3 1333MT/s            | 2         | 0.98%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                          | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2                                    | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM 800MT/s                                 | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.49%   |
| Unknown (0x7FA8000000000000) RAM Module 512MB DIMM DDR2 533MT/s     | 1         | 0.49%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s     | 1         | 0.49%   |
| Team RAM TEAMGROUP-SD3-1600 8192MB SODIMM DDR3 1600MT/s             | 1         | 0.49%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1         | 0.49%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.49%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.49%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.49%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s    | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 68        | 46.26%  |
| DDR3    | 57        | 38.78%  |
| DDR2    | 7         | 4.76%   |
| LPDDR4  | 6         | 4.08%   |
| LPDDR3  | 5         | 3.4%    |
| SDRAM   | 2         | 1.36%   |
| Unknown | 2         | 1.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 93        | 63.27%  |
| DIMM         | 48        | 32.65%  |
| Row Of Chips | 6         | 4.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 71        | 40.8%   |
| 8192  | 65        | 37.36%  |
| 2048  | 20        | 11.49%  |
| 16384 | 12        | 6.9%    |
| 1024  | 3         | 1.72%   |
| 512   | 3         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 44        | 25.43%  |
| 1600    | 38        | 21.97%  |
| 3200    | 19        | 10.98%  |
| 1333    | 16        | 9.25%   |
| 2400    | 8         | 4.62%   |
| 2133    | 8         | 4.62%   |
| 3266    | 6         | 3.47%   |
| Unknown | 5         | 2.89%   |
| 1867    | 4         | 2.31%   |
| 3600    | 3         | 1.73%   |
| 3466    | 3         | 1.73%   |
| 1334    | 3         | 1.73%   |
| 1067    | 3         | 1.73%   |
| 1800    | 2         | 1.16%   |
| 800     | 2         | 1.16%   |
| 533     | 2         | 1.16%   |
| 3400    | 1         | 0.58%   |
| 3151    | 1         | 0.58%   |
| 3100    | 1         | 0.58%   |
| 2733    | 1         | 0.58%   |
| 2200    | 1         | 0.58%   |
| 2134    | 1         | 0.58%   |
| 400     | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 28.57%  |
| Brother Industries | 2         | 28.57%  |
| Star Micronics     | 1         | 14.29%  |
| Seiko Epson        | 1         | 14.29%  |
| Canon              | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Star Micronics TUP592 (STR_T-001) | 1         | 14.29%  |
| Seiko Epson L3150 Series          | 1         | 14.29%  |
| HP PSC 1400                       | 1         | 14.29%  |
| HP LaserJet Professional P 1102w  | 1         | 14.29%  |
| Canon PIXMA MG3600 Series         | 1         | 14.29%  |
| Brother DCP-T310                  | 1         | 14.29%  |
| Brother DCP-T300                  | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP ScanJet 2400c       | 1         | 50%     |
| Canon CanoScan LIDE 25 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 19.37%  |
| Microdia                               | 18        | 9.42%   |
| IMC Networks                           | 17        | 8.9%    |
| Realtek Semiconductor                  | 14        | 7.33%   |
| Acer                                   | 13        | 6.81%   |
| Syntek                                 | 11        | 5.76%   |
| Sunplus Innovation Technology          | 10        | 5.24%   |
| Lite-On Technology                     | 10        | 5.24%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.24%   |
| Quanta                                 | 9         | 4.71%   |
| Suyin                                  | 8         | 4.19%   |
| Z-Star Microelectronics                | 4         | 2.09%   |
| Microsoft                              | 4         | 2.09%   |
| Logitech                               | 4         | 2.09%   |
| Importek                               | 4         | 2.09%   |
| Samsung Electronics                    | 3         | 1.57%   |
| Sonix Technology                       | 2         | 1.05%   |
| Ricoh                                  | 2         | 1.05%   |
| Generalplus Technology                 | 2         | 1.05%   |
| Alcor Micro                            | 2         | 1.05%   |
| Xiongmai                               | 1         | 0.52%   |
| Vimicro                                | 1         | 0.52%   |
| Luxvisions Innotech Limited            | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |
| Aveo Technology                        | 1         | 0.52%   |
| Apple                                  | 1         | 0.52%   |
| ANYKA                                  | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 4.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 3.11%   |
| Chicony Integrated Camera                                                  | 5         | 2.59%   |
| Acer Integrated Camera                                                     | 5         | 2.59%   |
| Lite-On Integrated Camera                                                  | 4         | 2.07%   |
| IMC Networks Integrated Camera                                             | 4         | 2.07%   |
| Chicony EasyCamera                                                         | 4         | 2.07%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.55%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 3         | 1.55%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.55%   |
| Microdia USB 2.0 Camera                                                    | 3         | 1.55%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 1.55%   |
| Lite-On HP HD Camera                                                       | 3         | 1.55%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.55%   |
| Chicony HP Truevision HD                                                   | 3         | 1.55%   |
| Chicony HD WebCam                                                          | 3         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.55%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 1.04%   |
| Sunplus Integrated Webcam                                                  | 2         | 1.04%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 2         | 1.04%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 1.04%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.04%   |
| Realtek Integrated Webcam                                                  | 2         | 1.04%   |
| Quanta HP Webcam                                                           | 2         | 1.04%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 1.04%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                        | 2         | 1.04%   |
| Microdia Webcam Vitade AF                                                  | 2         | 1.04%   |
| Microdia Camera                                                            | 2         | 1.04%   |
| Lite-On HP Wide Vision HD Camera                                           | 2         | 1.04%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 1.04%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 1.04%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.04%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 1.04%   |
| Chicony HP Webcam                                                          | 2         | 1.04%   |
| Chicony HP TrueVision HD Camera                                            | 2         | 1.04%   |
| Chicony HP HD Camera                                                       | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.04%   |
| Alcor Micro TOSHIBA Web Camera - MP                                        | 2         | 1.04%   |
| Z-Star Venus USB2.0 Camera                                                 | 1         | 0.52%   |
| Z-Star Sirius USB2.0 Camera                                                | 1         | 0.52%   |
| Z-Star Integrated Camera                                                   | 1         | 0.52%   |
| Z-Star A4 TECH USB2.0 PC Camera E                                          | 1         | 0.52%   |
| Xiongmai web camera                                                        | 1         | 0.52%   |
| Vimicro Integrated Camera                                                  | 1         | 0.52%   |
| Syntek USB Video Device                                                    | 1         | 0.52%   |
| Syntek USB Camera Device                                                   | 1         | 0.52%   |
| Syntek LENOVO LBG 720P CAM                                                 | 1         | 0.52%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.52%   |
| Suyin TOSHIBA Web Camera - HD                                              | 1         | 0.52%   |
| Suyin HP Truevision HD                                                     | 1         | 0.52%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.52%   |
| Suyin HD WebCam                                                            | 1         | 0.52%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.52%   |
| Sunplus SPCA2087 PC Camera                                                 | 1         | 0.52%   |
| Sunplus Lenovo EasyCamera                                                  | 1         | 0.52%   |
| Sunplus Laptop Integrated Webcam FHD                                       | 1         | 0.52%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.52%   |
| Sunplus HD WebCam                                                          | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 48.72%  |
| Synaptics                  | 11        | 28.21%  |
| Shenzhen Goodix Technology | 4         | 10.26%  |
| Elan Microelectronics      | 3         | 7.69%   |
| STMicroelectronics         | 1         | 2.56%   |
| AuthenTec                  | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 15.38%  |
| Synaptics  WBDI                                            | 3         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 7.69%   |
| Unknown                                                    | 3         | 7.69%   |
| Validity Sensors Fingerprint scanner                       | 2         | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 5.13%   |
| Elan ELAN:Fingerprint                                      | 2         | 5.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.56%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.56%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.56%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.56%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.56%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.56%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.56%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 210       | 71.67%  |
| 1     | 69        | 23.55%  |
| 2     | 10        | 3.41%   |
| 3     | 3         | 1.02%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 39.8%   |
| Graphics card            | 17        | 17.35%  |
| Net/wireless             | 13        | 13.27%  |
| Chipcard                 | 9         | 9.18%   |
| Bluetooth                | 6         | 6.12%   |
| Sound                    | 2         | 2.04%   |
| Multimedia controller    | 2         | 2.04%   |
| Card reader              | 2         | 2.04%   |
| Camera                   | 2         | 2.04%   |
| Unassigned class         | 1         | 1.02%   |
| Storage                  | 1         | 1.02%   |
| Network                  | 1         | 1.02%   |
| Net/ethernet             | 1         | 1.02%   |
| Firewire controller      | 1         | 1.02%   |
| Communication controller | 1         | 1.02%   |


Linux in Romania - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 650

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Z97 GAMING 7                | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Gigabyte      | EP45-DS3P                   | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Intel         | DQ67SW AAG12527-309         | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Unknown       | 1.0                         | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Unknown       | 1.0                         | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| HP            | 8704                        | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| Gigabyte      | B450 AORUS M                | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| ASUSTek       | P5KC                        | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| HP            | 1790                        | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | 07WP95 A02                  | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Dell          | 096JG8 A01                  | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Foxconn       | 2ADA                        | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| ASUSTek       | P5KC                        | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| HP            | 0AA8h                       | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | 0D6H9T A00                  | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| ASRock        | B450 Pro4                   | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Dell          | 07WP95 A02                  | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Unknown       | Unknown                     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Gigabyte      | Z690 UD AX                  | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Dell          | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| ASUSTek       | PRIME H410M-R               | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | 0YXT71 A03                  | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Daewoo Luc... | Solo Top                    | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | MS-7392                     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Gigabyte      | B365M H                     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| HP            | 09F8h                       | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| MSI           | A320M PRO-VD/S              | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| Acer          | RS880M05                    | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Gigabyte      | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Gigabyte      | Z690 UD AX                  | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Dell          | 0YXT71 A03                  | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| MSI           | 2A9C                        | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Acer          | Aspire T3-710 V:1.1         | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Unknown       | Unknown                     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| HP            | 843B                        | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| HP            | 1497                        | [540458f943](https://linux-hardware.org/?probe=540458f943) | Jan 02, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [a8b3cc88b1](https://linux-hardware.org/?probe=a8b3cc88b1) | Dec 29, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| HP            | 18E7                        | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| HP            | 1998                        | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ed065155fb](https://linux-hardware.org/?probe=ed065155fb) | Dec 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [7fe98389c6](https://linux-hardware.org/?probe=7fe98389c6) | Dec 11, 2021 |
| Dell          | 0J3C2F A02                  | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Unknown       | Unknown                     | [1c6db4a61b](https://linux-hardware.org/?probe=1c6db4a61b) | Dec 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Unknown       | Unknown                     | [e73cda5c1e](https://linux-hardware.org/?probe=e73cda5c1e) | Dec 02, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| Dell          | 0YNVJG A01                  | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Lenovo        | SHARKBAY NOK                | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | A58M-K                      | [0dbc01db57](https://linux-hardware.org/?probe=0dbc01db57) | Nov 08, 2021 |
| Gigabyte      | P31-DS3L                    | [c0ef5646a8](https://linux-hardware.org/?probe=c0ef5646a8) | Nov 07, 2021 |
| HP            | 18E4                        | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| ASUSTek       | H61M-K                      | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| Dell          | 07T4MC A11                  | [219a3a234f](https://linux-hardware.org/?probe=219a3a234f) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | [870145802c](https://linux-hardware.org/?probe=870145802c) | Oct 27, 2021 |
| IBM           | 82121QG                     | [765d524e7f](https://linux-hardware.org/?probe=765d524e7f) | Oct 26, 2021 |
| ASUSTek       | P5KC                        | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| ASRock        | A75 Extreme6                | [5735bac676](https://linux-hardware.org/?probe=5735bac676) | Oct 16, 2021 |
| ASRock        | 4X4-4000 Series             | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| HP            | 3031h                       | [eb48a6bfe5](https://linux-hardware.org/?probe=eb48a6bfe5) | Oct 10, 2021 |
| MSI           | H110M PRO-VD                | [ec7609239e](https://linux-hardware.org/?probe=ec7609239e) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| Dell          | 0T10XW A02                  | [97333f9cab](https://linux-hardware.org/?probe=97333f9cab) | Oct 04, 2021 |
| ASUSTek       | H81M-K                      | [06d254591f](https://linux-hardware.org/?probe=06d254591f) | Oct 02, 2021 |
| ASUSTek       | P5QL PRO                    | [02d6cacb04](https://linux-hardware.org/?probe=02d6cacb04) | Sep 30, 2021 |
| Gigabyte      | J4005ND2P-CF                | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| MSI           | H110M PRO-VD                | [68a76785a0](https://linux-hardware.org/?probe=68a76785a0) | Sep 27, 2021 |
| ASRock        | 970 Extreme4                | [7baf276ca0](https://linux-hardware.org/?probe=7baf276ca0) | Sep 26, 2021 |
| Dell          | 0GM819                      | [708ca8f58a](https://linux-hardware.org/?probe=708ca8f58a) | Sep 22, 2021 |
| Dell          | 0GM819                      | [37f5afac35](https://linux-hardware.org/?probe=37f5afac35) | Sep 22, 2021 |
| MSI           | A55M-E33                    | [695bc5477d](https://linux-hardware.org/?probe=695bc5477d) | Sep 22, 2021 |
| ASRock        | Z68 Pro3-M                  | [c7e3f44f44](https://linux-hardware.org/?probe=c7e3f44f44) | Sep 19, 2021 |
| HP            | 3397                        | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | [d47952ec42](https://linux-hardware.org/?probe=d47952ec42) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | [9c310e15bd](https://linux-hardware.org/?probe=9c310e15bd) | Sep 15, 2021 |
| ASUSTek       | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [da1dd9bb01](https://linux-hardware.org/?probe=da1dd9bb01) | Sep 13, 2021 |
| Dell          | 0YXT71 A03                  | [151a3381f0](https://linux-hardware.org/?probe=151a3381f0) | Sep 09, 2021 |
| MSI           | B350 TOMAHAWK               | [638993c7b0](https://linux-hardware.org/?probe=638993c7b0) | Sep 06, 2021 |
| Dell          | 0YXT71 A03                  | [bb0ef0735f](https://linux-hardware.org/?probe=bb0ef0735f) | Sep 05, 2021 |
| ASUSTek       | D340MC-C                    | [cf81a7ddc2](https://linux-hardware.org/?probe=cf81a7ddc2) | Sep 02, 2021 |
| HP            | 18E9                        | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| MSI           | A88XM-E35                   | [66070c788f](https://linux-hardware.org/?probe=66070c788f) | Sep 01, 2021 |
| HP            | 3032h                       | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| HP            | 18E9                        | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Gigabyte      | H61M-DS2                    | [fd9d91270d](https://linux-hardware.org/?probe=fd9d91270d) | Aug 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | [30d745e8d3](https://linux-hardware.org/?probe=30d745e8d3) | Aug 28, 2021 |
| HP            | 1587h                       | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| ASUSTek       | PRIME Z390-P                | [8cf3477dd1](https://linux-hardware.org/?probe=8cf3477dd1) | Aug 18, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [4b4a995bad](https://linux-hardware.org/?probe=4b4a995bad) | Aug 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [99763e52f1](https://linux-hardware.org/?probe=99763e52f1) | Aug 09, 2021 |
| HP            | 2AE2                        | [e8a9a769fe](https://linux-hardware.org/?probe=e8a9a769fe) | Aug 07, 2021 |
| Gigabyte      | A520 AORUS ELITE            | [1d3167cdf0](https://linux-hardware.org/?probe=1d3167cdf0) | Aug 05, 2021 |
| MSI           | Z370 TOMAHAWK               | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| ASRock        | X570 Taichi                 | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [a7c1a61e9f](https://linux-hardware.org/?probe=a7c1a61e9f) | Aug 03, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [d58be51f72](https://linux-hardware.org/?probe=d58be51f72) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| Gigabyte      | P75-D3                      | [5f0bee42c2](https://linux-hardware.org/?probe=5f0bee42c2) | Aug 01, 2021 |
| HP            | 2AE2                        | [61acec4a9c](https://linux-hardware.org/?probe=61acec4a9c) | Aug 01, 2021 |
| HP            | 2AE2                        | [3de122823e](https://linux-hardware.org/?probe=3de122823e) | Aug 01, 2021 |
| MSI           | Z97 GAMING 3                | [a5cc51aec1](https://linux-hardware.org/?probe=a5cc51aec1) | Jul 26, 2021 |
| MSI           | Z97 GAMING 3                | [9e05add91a](https://linux-hardware.org/?probe=9e05add91a) | Jul 26, 2021 |
| HP            | 1850                        | [76e386707a](https://linux-hardware.org/?probe=76e386707a) | Jul 24, 2021 |
| Gigabyte      | Z170X-GamingG1              | [b0ce1bc8f5](https://linux-hardware.org/?probe=b0ce1bc8f5) | Jul 24, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | [11daeb0d8d](https://linux-hardware.org/?probe=11daeb0d8d) | Jul 24, 2021 |
| HP            | 0AA8h                       | [a04f3a673d](https://linux-hardware.org/?probe=a04f3a673d) | Jul 23, 2021 |
| HP            | 0AA8h                       | [b3bbc0186c](https://linux-hardware.org/?probe=b3bbc0186c) | Jul 22, 2021 |
| Dell          | 0YXT71 A03                  | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell          | 0YXT71 A03                  | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| HP            | 3047h                       | [ac149ca840](https://linux-hardware.org/?probe=ac149ca840) | Jul 17, 2021 |
| ASUSTek       | Z97-K                       | [a2a1798503](https://linux-hardware.org/?probe=a2a1798503) | Jul 15, 2021 |
| Dell          | 0X9X1W A00                  | [702d489268](https://linux-hardware.org/?probe=702d489268) | Jul 13, 2021 |
| Lenovo        | 3102 NOK                    | [71974ffb04](https://linux-hardware.org/?probe=71974ffb04) | Jul 12, 2021 |
| Biostar       | N61PA-M2S                   | [346b5914bf](https://linux-hardware.org/?probe=346b5914bf) | Jul 11, 2021 |
| Dell          | 0YXT71 A03                  | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |
| Dell          | 04GJJT A00                  | [257e9719c0](https://linux-hardware.org/?probe=257e9719c0) | Jul 07, 2021 |
| Dell          | 0VD5HY A07                  | [398ee87d95](https://linux-hardware.org/?probe=398ee87d95) | Jul 04, 2021 |
| Dell          | 0VD5HY A07                  | [0fa3ef38f2](https://linux-hardware.org/?probe=0fa3ef38f2) | Jul 04, 2021 |
| MSI           | B350 TOMAHAWK               | [42fcbcb1e4](https://linux-hardware.org/?probe=42fcbcb1e4) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [2e13a4aff4](https://linux-hardware.org/?probe=2e13a4aff4) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [618b266cc7](https://linux-hardware.org/?probe=618b266cc7) | Jul 02, 2021 |
| Gigabyte      | P55-UD5                     | [934948c85f](https://linux-hardware.org/?probe=934948c85f) | Jun 27, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [59b653ec10](https://linux-hardware.org/?probe=59b653ec10) | Jun 25, 2021 |
| ASUSTek       | H81M-K                      | [aa753c135b](https://linux-hardware.org/?probe=aa753c135b) | Jun 21, 2021 |
| MSI           | Z87-G43                     | [c049769b6b](https://linux-hardware.org/?probe=c049769b6b) | Jun 20, 2021 |
| ASRock        | A320M-DVS R4.0              | [4bc7b480e0](https://linux-hardware.org/?probe=4bc7b480e0) | Jun 16, 2021 |
| ASRock        | G41M-VS3                    | [1df7b23225](https://linux-hardware.org/?probe=1df7b23225) | Jun 11, 2021 |
| HP            | 1494                        | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| ASUSTek       | P5LD2-VM                    | [6b68ceb0b3](https://linux-hardware.org/?probe=6b68ceb0b3) | Jun 02, 2021 |
| ASUSTek       | P5LD2-VM                    | [3bdb847f96](https://linux-hardware.org/?probe=3bdb847f96) | Jun 01, 2021 |
| Huanan        | X99-TF                      | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| HP            | 3031h                       | [d69cd77c4d](https://linux-hardware.org/?probe=d69cd77c4d) | May 28, 2021 |
| Gigabyte      | 965GM-S2                    | [05ac3124f9](https://linux-hardware.org/?probe=05ac3124f9) | May 26, 2021 |
| Gigabyte      | G41M-Combo                  | [87aca59a7c](https://linux-hardware.org/?probe=87aca59a7c) | May 25, 2021 |
| Gigabyte      | H310M H x.x                 | [141475f02b](https://linux-hardware.org/?probe=141475f02b) | May 25, 2021 |
| HP            | 3029h                       | [1f0ebaa79c](https://linux-hardware.org/?probe=1f0ebaa79c) | May 20, 2021 |
| HP            | 3029h                       | [9eac66bf17](https://linux-hardware.org/?probe=9eac66bf17) | May 20, 2021 |
| Pegatron      | IPPPV-D3G                   | [d4187bad77](https://linux-hardware.org/?probe=d4187bad77) | May 20, 2021 |
| ASRock        | Z77 Extreme4                | [9bc3a8a33e](https://linux-hardware.org/?probe=9bc3a8a33e) | May 20, 2021 |
| Gigabyte      | 965GM-S2                    | [7db6d2bc1a](https://linux-hardware.org/?probe=7db6d2bc1a) | May 20, 2021 |
| ASUSTek       | H170 PRO GAMING             | [110d291fde](https://linux-hardware.org/?probe=110d291fde) | May 13, 2021 |
| HP            | 1494                        | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | J1800I-C                    | [2554e9ed0c](https://linux-hardware.org/?probe=2554e9ed0c) | May 10, 2021 |
| HP            | 1496                        | [ef4e0697d7](https://linux-hardware.org/?probe=ef4e0697d7) | May 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [356c77df30](https://linux-hardware.org/?probe=356c77df30) | May 07, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5927d6bfa2](https://linux-hardware.org/?probe=5927d6bfa2) | May 06, 2021 |
| Intel         | DQ77MK AAG39642-500         | [b1a5da541f](https://linux-hardware.org/?probe=b1a5da541f) | May 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | [155da00fc0](https://linux-hardware.org/?probe=155da00fc0) | May 03, 2021 |
| Gigabyte      | B250M-D2V-CF                | [3eeaf82899](https://linux-hardware.org/?probe=3eeaf82899) | May 01, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [7f935099f0](https://linux-hardware.org/?probe=7f935099f0) | Apr 28, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [8dbfa5594e](https://linux-hardware.org/?probe=8dbfa5594e) | Apr 27, 2021 |
| Dell          | 0YXT71 A03                  | [ed71084f85](https://linux-hardware.org/?probe=ed71084f85) | Apr 27, 2021 |
| MSI           | MS-7502 Fab D               | [2a2d112995](https://linux-hardware.org/?probe=2a2d112995) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [42b2eb88ad](https://linux-hardware.org/?probe=42b2eb88ad) | Apr 19, 2021 |
| MSI           | MS-7367                     | [1a103f941a](https://linux-hardware.org/?probe=1a103f941a) | Apr 18, 2021 |
| HP            | 1790                        | [75557f3294](https://linux-hardware.org/?probe=75557f3294) | Apr 18, 2021 |
| Dell          | 0YXT71 A03                  | [a83dfd361b](https://linux-hardware.org/?probe=a83dfd361b) | Apr 14, 2021 |
| Dell          | 0YXT71 A03                  | [b8e3c87a38](https://linux-hardware.org/?probe=b8e3c87a38) | Apr 14, 2021 |
| Dell          | 04GJJT A00                  | [b687e379b9](https://linux-hardware.org/?probe=b687e379b9) | Apr 11, 2021 |
| Gigabyte      | Z68P-DS3                    | [7b4c090391](https://linux-hardware.org/?probe=7b4c090391) | Apr 11, 2021 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [79febd76c3](https://linux-hardware.org/?probe=79febd76c3) | Apr 11, 2021 |
| HP            | 2215                        | [0ce403b929](https://linux-hardware.org/?probe=0ce403b929) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M58 7373WB7     | [57e7329bf2](https://linux-hardware.org/?probe=57e7329bf2) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | [0784afdde4](https://linux-hardware.org/?probe=0784afdde4) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | [3c49f2205f](https://linux-hardware.org/?probe=3c49f2205f) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | [ac0a48160a](https://linux-hardware.org/?probe=ac0a48160a) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | [533ebeaa6e](https://linux-hardware.org/?probe=533ebeaa6e) | Apr 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [93285dae9e](https://linux-hardware.org/?probe=93285dae9e) | Mar 29, 2021 |
| ASUSTek       | P5KC                        | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| HP            | 3029h                       | [0ddf4fe8c8](https://linux-hardware.org/?probe=0ddf4fe8c8) | Mar 20, 2021 |
| HP            | 3047h                       | [d4a58313d6](https://linux-hardware.org/?probe=d4a58313d6) | Mar 16, 2021 |
| Dell          | 0RY007                      | [8c2cacd439](https://linux-hardware.org/?probe=8c2cacd439) | Mar 15, 2021 |
| Dell          | 0RY007                      | [e2527f8f11](https://linux-hardware.org/?probe=e2527f8f11) | Mar 15, 2021 |
| MSI           | 760GM -E51                  | [ed4ec28115](https://linux-hardware.org/?probe=ed4ec28115) | Mar 13, 2021 |
| Gigabyte      | P55-UD5                     | [203d98c6a0](https://linux-hardware.org/?probe=203d98c6a0) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [3f9b2942e1](https://linux-hardware.org/?probe=3f9b2942e1) | Mar 10, 2021 |
| HP            | 3047h                       | [970a03f12b](https://linux-hardware.org/?probe=970a03f12b) | Mar 09, 2021 |
| HP            | 3047h                       | [2277d0a259](https://linux-hardware.org/?probe=2277d0a259) | Mar 09, 2021 |
| HP            | 3029h                       | [163d32c75c](https://linux-hardware.org/?probe=163d32c75c) | Mar 09, 2021 |
| Dell          | 0GY6Y8 A02                  | [6eac92f735](https://linux-hardware.org/?probe=6eac92f735) | Mar 08, 2021 |
| HP            | 1497                        | [6d49e950fe](https://linux-hardware.org/?probe=6d49e950fe) | Mar 03, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8b2adea4fc](https://linux-hardware.org/?probe=8b2adea4fc) | Feb 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8f08d3592d](https://linux-hardware.org/?probe=8f08d3592d) | Feb 20, 2021 |
| MSI           | 760GM-P23                   | [2f9c20e9ed](https://linux-hardware.org/?probe=2f9c20e9ed) | Feb 20, 2021 |
| HP            | 1998                        | [a574c0a6bb](https://linux-hardware.org/?probe=a574c0a6bb) | Feb 18, 2021 |
| ASUSTek       | M4A785D-M PRO               | [dcc226166f](https://linux-hardware.org/?probe=dcc226166f) | Feb 17, 2021 |
| ASUSTek       | M4A785D-M PRO               | [d326bb69fd](https://linux-hardware.org/?probe=d326bb69fd) | Feb 16, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | [d288f0a8cd](https://linux-hardware.org/?probe=d288f0a8cd) | Feb 16, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | [656a59d9a6](https://linux-hardware.org/?probe=656a59d9a6) | Feb 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [7450b827a1](https://linux-hardware.org/?probe=7450b827a1) | Feb 14, 2021 |
| ASRock        | B550M Steel Legend          | [4744d31675](https://linux-hardware.org/?probe=4744d31675) | Feb 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [19dc97c5e3](https://linux-hardware.org/?probe=19dc97c5e3) | Feb 13, 2021 |
| HP            | 3048h                       | [2c055ef572](https://linux-hardware.org/?probe=2c055ef572) | Feb 13, 2021 |
| MSI           | MS-7502 Fab D               | [147ca461b7](https://linux-hardware.org/?probe=147ca461b7) | Feb 12, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5fff5b3dd5](https://linux-hardware.org/?probe=5fff5b3dd5) | Feb 12, 2021 |
| Lenovo        | ThinkStation D20 415892G    | [4abbaf6f5b](https://linux-hardware.org/?probe=4abbaf6f5b) | Feb 11, 2021 |
| MSI           | A68HM-E33 V2                | [353831c5ff](https://linux-hardware.org/?probe=353831c5ff) | Feb 11, 2021 |
| Complet       | MY8313                      | [c730316a6b](https://linux-hardware.org/?probe=c730316a6b) | Feb 03, 2021 |
| ASUSTek       | M11BB                       | [30ab270226](https://linux-hardware.org/?probe=30ab270226) | Feb 02, 2021 |
| ASUSTek       | M11BB                       | [58e5dd3c71](https://linux-hardware.org/?probe=58e5dd3c71) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | [eee3d9cfa2](https://linux-hardware.org/?probe=eee3d9cfa2) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M58 7373A25     | [80c84ece52](https://linux-hardware.org/?probe=80c84ece52) | Jan 30, 2021 |
| Lenovo        | ThinkCentre M58 7373A25     | [1610c2fab2](https://linux-hardware.org/?probe=1610c2fab2) | Jan 28, 2021 |
| ASUSTek       | CS-B                        | [46b5f91f9e](https://linux-hardware.org/?probe=46b5f91f9e) | Jan 27, 2021 |
| ASUSTek       | CS-B                        | [cf20b0834e](https://linux-hardware.org/?probe=cf20b0834e) | Jan 27, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [83922cd9de](https://linux-hardware.org/?probe=83922cd9de) | Jan 23, 2021 |
| Acer          | Predator G3610              | [582803fed3](https://linux-hardware.org/?probe=582803fed3) | Jan 23, 2021 |
| Gigabyte      | H61M-DS2                    | [9939bcc31c](https://linux-hardware.org/?probe=9939bcc31c) | Jan 20, 2021 |
| Lenovo        | ThinkCentre M58 7373A25     | [2f06637fa5](https://linux-hardware.org/?probe=2f06637fa5) | Jan 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | [bda205658e](https://linux-hardware.org/?probe=bda205658e) | Jan 19, 2021 |
| Gigabyte      | P55-UD5                     | [8552ebd200](https://linux-hardware.org/?probe=8552ebd200) | Jan 18, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [72500dd03c](https://linux-hardware.org/?probe=72500dd03c) | Jan 16, 2021 |
| Packard Be... | VG300                       | [9a025e03bb](https://linux-hardware.org/?probe=9a025e03bb) | Jan 15, 2021 |
| Packard Be... | VG300                       | [7649b086c0](https://linux-hardware.org/?probe=7649b086c0) | Jan 15, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [4aeb7c78a2](https://linux-hardware.org/?probe=4aeb7c78a2) | Jan 12, 2021 |
| MSI           | B450M PRO-VDH MAX           | [0efd730397](https://linux-hardware.org/?probe=0efd730397) | Jan 12, 2021 |
| ASRock        | B450 Pro4                   | [c4bd6738dd](https://linux-hardware.org/?probe=c4bd6738dd) | Jan 05, 2021 |
| ASRock        | B450 Pro4                   | [462a5eec6c](https://linux-hardware.org/?probe=462a5eec6c) | Jan 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [65d3eda43c](https://linux-hardware.org/?probe=65d3eda43c) | Jan 02, 2021 |
| MSI           | MS-7346                     | [3e709ba6e1](https://linux-hardware.org/?probe=3e709ba6e1) | Dec 26, 2020 |
| HP            | 18E9                        | [a33c671a96](https://linux-hardware.org/?probe=a33c671a96) | Dec 26, 2020 |
| ASUSTek       | Maximus VIII HERO           | [56d4ff7c49](https://linux-hardware.org/?probe=56d4ff7c49) | Dec 22, 2020 |
| ASUSTek       | Maximus VIII HERO           | [33193096fe](https://linux-hardware.org/?probe=33193096fe) | Dec 22, 2020 |
| ECS           | nForce3-A                   | [0150835d63](https://linux-hardware.org/?probe=0150835d63) | Dec 21, 2020 |
| ECS           | nForce3-A                   | [c08a9c2d3a](https://linux-hardware.org/?probe=c08a9c2d3a) | Dec 21, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [c74c628d8a](https://linux-hardware.org/?probe=c74c628d8a) | Dec 19, 2020 |
| Gigabyte      | B85M-D3H-A                  | [f0c5adfa14](https://linux-hardware.org/?probe=f0c5adfa14) | Dec 15, 2020 |
| Acer          | Nitro GX50-600              | [ca40ac648d](https://linux-hardware.org/?probe=ca40ac648d) | Dec 14, 2020 |
| Acer          | Nitro GX50-600              | [61f4f9991a](https://linux-hardware.org/?probe=61f4f9991a) | Dec 13, 2020 |
| Acer          | Nitro N50-610               | [560e5d0b17](https://linux-hardware.org/?probe=560e5d0b17) | Dec 12, 2020 |
| HP            | 3047h                       | [b7967b4e02](https://linux-hardware.org/?probe=b7967b4e02) | Dec 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e452d60d3e](https://linux-hardware.org/?probe=e452d60d3e) | Dec 09, 2020 |
| Gigabyte      | B250M-D3H-CF                | [b8cf7df3c1](https://linux-hardware.org/?probe=b8cf7df3c1) | Dec 09, 2020 |
| MSI           | H170A PC MATE               | [5cc4fd552a](https://linux-hardware.org/?probe=5cc4fd552a) | Dec 07, 2020 |
| Gigabyte      | B550M DS3H                  | [01fa23f0fc](https://linux-hardware.org/?probe=01fa23f0fc) | Dec 07, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3f93555527](https://linux-hardware.org/?probe=3f93555527) | Dec 05, 2020 |
| HP            | 2820h                       | [eb04cf12aa](https://linux-hardware.org/?probe=eb04cf12aa) | Dec 05, 2020 |
| OEM_MB        | Acacia                      | [e6eacc1023](https://linux-hardware.org/?probe=e6eacc1023) | Dec 03, 2020 |
| ASUSTek       | PRIME A320M-E               | [9d05f29b71](https://linux-hardware.org/?probe=9d05f29b71) | Dec 02, 2020 |
| HP            | 18E9                        | [0358f91af6](https://linux-hardware.org/?probe=0358f91af6) | Dec 01, 2020 |
| Dell          | 0GM819                      | [2555a4411a](https://linux-hardware.org/?probe=2555a4411a) | Nov 30, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [194ae6839d](https://linux-hardware.org/?probe=194ae6839d) | Nov 30, 2020 |
| Dell          | 0XPDFK A01                  | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| MSI           | A320M-A PRO MAX             | [4b40e4f17c](https://linux-hardware.org/?probe=4b40e4f17c) | Nov 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [294c2bf2e7](https://linux-hardware.org/?probe=294c2bf2e7) | Nov 28, 2020 |
| ASUSTek       | Z97-A                       | [ab840ac981](https://linux-hardware.org/?probe=ab840ac981) | Nov 26, 2020 |
| HP            | 2820h                       | [2afd23d45d](https://linux-hardware.org/?probe=2afd23d45d) | Nov 26, 2020 |
| Gigabyte      | TRX40 AORUS MASTER          | [a6e62c55c4](https://linux-hardware.org/?probe=a6e62c55c4) | Nov 24, 2020 |
| Dell          | 0C27VV A02                  | [0ed1683811](https://linux-hardware.org/?probe=0ed1683811) | Nov 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [6e5f3102d1](https://linux-hardware.org/?probe=6e5f3102d1) | Nov 21, 2020 |
| ASUSTek       | PRIME B250M-K               | [e8b8c79116](https://linux-hardware.org/?probe=e8b8c79116) | Nov 20, 2020 |
| ASUSTek       | PRIME B250M-K               | [0f5dcabdb8](https://linux-hardware.org/?probe=0f5dcabdb8) | Nov 20, 2020 |
| Gigabyte      | H81M-DS2V                   | [32e27e5b75](https://linux-hardware.org/?probe=32e27e5b75) | Nov 19, 2020 |
| Gigabyte      | H81M-DS2V                   | [dc3e802782](https://linux-hardware.org/?probe=dc3e802782) | Nov 19, 2020 |
| HP            | 3048h                       | [7fe9c668aa](https://linux-hardware.org/?probe=7fe9c668aa) | Nov 18, 2020 |
| Gigabyte      | Z77X-D3H                    | [d7dc793c40](https://linux-hardware.org/?probe=d7dc793c40) | Nov 15, 2020 |
| Gigabyte      | X570 UD                     | [9003c7f0b1](https://linux-hardware.org/?probe=9003c7f0b1) | Nov 15, 2020 |
| ASUSTek       | J1800I-C                    | [d93f8d1bbc](https://linux-hardware.org/?probe=d93f8d1bbc) | Nov 13, 2020 |
| Unknown       | Unknown                     | [5f2dac9c99](https://linux-hardware.org/?probe=5f2dac9c99) | Nov 11, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [05b7d97ed0](https://linux-hardware.org/?probe=05b7d97ed0) | Nov 08, 2020 |
| ASRock        | N68-GE3 UCC                 | [325e278ffe](https://linux-hardware.org/?probe=325e278ffe) | Nov 08, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [d584773eee](https://linux-hardware.org/?probe=d584773eee) | Nov 08, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [6b84bce70f](https://linux-hardware.org/?probe=6b84bce70f) | Nov 08, 2020 |
| MSI           | MS-7367                     | [1caace16cf](https://linux-hardware.org/?probe=1caace16cf) | Nov 08, 2020 |
| MSI           | H110M PRO-VD                | [bb789b7196](https://linux-hardware.org/?probe=bb789b7196) | Nov 04, 2020 |
| MSI           | B365M PRO-VH                | [2f0b8b27c3](https://linux-hardware.org/?probe=2f0b8b27c3) | Nov 03, 2020 |
| ASUSTek       | CS-B                        | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Fujitsu Si... | D2594-A1 S26361-D2594-A1    | [b04f10e40a](https://linux-hardware.org/?probe=b04f10e40a) | Nov 01, 2020 |
| MSI           | MEG Z490I UNIFY             | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Gigabyte      | A320M-S2H-CF                | [85c49d42c4](https://linux-hardware.org/?probe=85c49d42c4) | Oct 29, 2020 |
| MSI           | MS-7253                     | [5a04962352](https://linux-hardware.org/?probe=5a04962352) | Oct 24, 2020 |
| MSI           | MS-7253                     | [b8ace166e0](https://linux-hardware.org/?probe=b8ace166e0) | Oct 23, 2020 |
| Dell          | 0J3C2F A02                  | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [910418d797](https://linux-hardware.org/?probe=910418d797) | Oct 22, 2020 |
| Gigabyte      | H310M H x.x                 | [72566da264](https://linux-hardware.org/?probe=72566da264) | Oct 18, 2020 |
| ASUSTek       | H81M-K                      | [799659ac10](https://linux-hardware.org/?probe=799659ac10) | Oct 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [5fa86b3b29](https://linux-hardware.org/?probe=5fa86b3b29) | Oct 18, 2020 |
| Foxconn       | 2ADA                        | [4365f32962](https://linux-hardware.org/?probe=4365f32962) | Oct 16, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [dff0f9c7be](https://linux-hardware.org/?probe=dff0f9c7be) | Oct 16, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [98b9a321a8](https://linux-hardware.org/?probe=98b9a321a8) | Oct 15, 2020 |
| HP            | 843B                        | [86632c3a3e](https://linux-hardware.org/?probe=86632c3a3e) | Oct 15, 2020 |
| Dell          | 0PC5F7 A02                  | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| ASUSTek       | H110M-C                     | [8e61f49a7f](https://linux-hardware.org/?probe=8e61f49a7f) | Oct 14, 2020 |
| Gigabyte      | Z270X-Gaming 5              | [f700963cf3](https://linux-hardware.org/?probe=f700963cf3) | Oct 11, 2020 |
| MSI           | H61M-P20                    | [0bf2f11818](https://linux-hardware.org/?probe=0bf2f11818) | Oct 08, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [091b86b414](https://linux-hardware.org/?probe=091b86b414) | Oct 06, 2020 |
| ASRock        | 970 Extreme4                | [e4bb5bfc52](https://linux-hardware.org/?probe=e4bb5bfc52) | Oct 02, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | [baf6875e8d](https://linux-hardware.org/?probe=baf6875e8d) | Sep 29, 2020 |
| ASRock        | H87 Pro4                    | [c9e5c6c639](https://linux-hardware.org/?probe=c9e5c6c639) | Sep 29, 2020 |
| Acer          | FG43D                       | [6b0868f448](https://linux-hardware.org/?probe=6b0868f448) | Sep 27, 2020 |
| MSI           | B350 TOMAHAWK               | [3be86ad86b](https://linux-hardware.org/?probe=3be86ad86b) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [a0de953cb3](https://linux-hardware.org/?probe=a0de953cb3) | Sep 26, 2020 |
| ASUSTek       | P8H77-M PRO                 | [2b3c2ec612](https://linux-hardware.org/?probe=2b3c2ec612) | Sep 22, 2020 |
| Gigabyte      | GA-870A-USB3L               | [bfff15642e](https://linux-hardware.org/?probe=bfff15642e) | Sep 22, 2020 |
| HP            | 0A54h                       | [0ee20adf26](https://linux-hardware.org/?probe=0ee20adf26) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| HP            | 0A54h                       | [0095e33a1e](https://linux-hardware.org/?probe=0095e33a1e) | Sep 20, 2020 |
| ASUSTek       | PRIME X470-PRO              | [6c0de749d5](https://linux-hardware.org/?probe=6c0de749d5) | Sep 12, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [bdc2121d7e](https://linux-hardware.org/?probe=bdc2121d7e) | Sep 11, 2020 |
| Gigabyte      | Z77-DS3H                    | [ab95a02da7](https://linux-hardware.org/?probe=ab95a02da7) | Sep 09, 2020 |
| HP            | 0A54h                       | [a519d456a2](https://linux-hardware.org/?probe=a519d456a2) | Sep 05, 2020 |
| Gigabyte      | X570 AORUS PRO              | [4a6b216d3f](https://linux-hardware.org/?probe=4a6b216d3f) | Sep 03, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [ed48b53c8f](https://linux-hardware.org/?probe=ed48b53c8f) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [55f5a50f2f](https://linux-hardware.org/?probe=55f5a50f2f) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS PRO              | [106859ac08](https://linux-hardware.org/?probe=106859ac08) | Sep 03, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [89e7ddc6ec](https://linux-hardware.org/?probe=89e7ddc6ec) | Sep 01, 2020 |
| Dell          | 0GTK4K A02                  | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| HP            | 2215                        | [3a17574701](https://linux-hardware.org/?probe=3a17574701) | Aug 25, 2020 |
| ECS           | nForce3-A                   | [749e54bb87](https://linux-hardware.org/?probe=749e54bb87) | Aug 24, 2020 |
| ASUSTek       | P8H77-M PRO                 | [bab7cedeb6](https://linux-hardware.org/?probe=bab7cedeb6) | Aug 15, 2020 |
| HP            | 0A54h                       | [2267cb3001](https://linux-hardware.org/?probe=2267cb3001) | Aug 14, 2020 |
| Gigabyte      | B360M HD3                   | [be8312bb93](https://linux-hardware.org/?probe=be8312bb93) | Aug 14, 2020 |
| MSI           | 760GM -E51                  | [a519c7c3b0](https://linux-hardware.org/?probe=a519c7c3b0) | Aug 06, 2020 |
| Foxconn       | 2ABF                        | [d35ce8ed45](https://linux-hardware.org/?probe=d35ce8ed45) | Aug 05, 2020 |
| HP            | 2820h                       | [07f1d4d4c5](https://linux-hardware.org/?probe=07f1d4d4c5) | Aug 01, 2020 |
| MSI           | H61M-P20                    | [0f9ddb6d2d](https://linux-hardware.org/?probe=0f9ddb6d2d) | Jul 29, 2020 |
| MSI           | H61M-P20                    | [5c52b6abf8](https://linux-hardware.org/?probe=5c52b6abf8) | Jul 29, 2020 |
| ASRock        | G41M-VS3                    | [f8c988d901](https://linux-hardware.org/?probe=f8c988d901) | Jul 22, 2020 |
| ASRock        | G41M-VS3                    | [1ea1f6acd1](https://linux-hardware.org/?probe=1ea1f6acd1) | Jul 22, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [01f8c369e0](https://linux-hardware.org/?probe=01f8c369e0) | Jul 21, 2020 |
| MSI           | B360M PRO-VDH               | [d0203a02fc](https://linux-hardware.org/?probe=d0203a02fc) | Jul 21, 2020 |
| Dell          | 0C27VV A00                  | [60cd9f8b7e](https://linux-hardware.org/?probe=60cd9f8b7e) | Jul 19, 2020 |
| HP            | 158A                        | [7bd0d3ac0a](https://linux-hardware.org/?probe=7bd0d3ac0a) | Jul 17, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [b48720d1bf](https://linux-hardware.org/?probe=b48720d1bf) | Jul 16, 2020 |
| HP            | 2215                        | [fbd9395652](https://linux-hardware.org/?probe=fbd9395652) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2e464f5c9a](https://linux-hardware.org/?probe=2e464f5c9a) | Jul 11, 2020 |
| Biostar       | N61PA-M2S                   | [42e0cd75c1](https://linux-hardware.org/?probe=42e0cd75c1) | Jul 10, 2020 |
| Biostar       | N61PA-M2S                   | [d8c6dd9ca2](https://linux-hardware.org/?probe=d8c6dd9ca2) | Jul 10, 2020 |
| ASRock        | K8Upgrade-NF3               | [c083fb4bfe](https://linux-hardware.org/?probe=c083fb4bfe) | Jul 08, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | [27ee239e69](https://linux-hardware.org/?probe=27ee239e69) | Jul 07, 2020 |
| MSI           | MS-7367                     | [f34fd6f016](https://linux-hardware.org/?probe=f34fd6f016) | Jul 07, 2020 |
| ASRock        | K8Upgrade-NF3               | [8ee0cf7d01](https://linux-hardware.org/?probe=8ee0cf7d01) | Jul 06, 2020 |
| ASRock        | 990FX Extreme3              | [e5ec01d31c](https://linux-hardware.org/?probe=e5ec01d31c) | Jul 05, 2020 |
| ASUSTek       | PRIME X370-PRO              | [333fcb65b5](https://linux-hardware.org/?probe=333fcb65b5) | Jul 04, 2020 |
| ASRock        | 990FX Extreme3              | [318ea016b3](https://linux-hardware.org/?probe=318ea016b3) | Jul 04, 2020 |
| Gigabyte      | H110M-S2H DDR3-CF           | [647c30ca0c](https://linux-hardware.org/?probe=647c30ca0c) | Jul 03, 2020 |
| Foxconn       | 2ADA                        | [478ff4e2a2](https://linux-hardware.org/?probe=478ff4e2a2) | Jul 01, 2020 |
| Foxconn       | 2ADA                        | [d63d4101a2](https://linux-hardware.org/?probe=d63d4101a2) | Jul 01, 2020 |
| Dell          | 0JJW8N A03                  | [f3f1076643](https://linux-hardware.org/?probe=f3f1076643) | Jul 01, 2020 |
| HP            | 0A54h                       | [2613499d80](https://linux-hardware.org/?probe=2613499d80) | Jun 30, 2020 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [a40e30b62b](https://linux-hardware.org/?probe=a40e30b62b) | Jun 29, 2020 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [cb20f6e877](https://linux-hardware.org/?probe=cb20f6e877) | Jun 29, 2020 |
| HP            | 0A54h                       | [89d11a0415](https://linux-hardware.org/?probe=89d11a0415) | Jun 27, 2020 |
| Dell          | 0RW203                      | [8ba004d478](https://linux-hardware.org/?probe=8ba004d478) | Jun 25, 2020 |
| Dell          | 0RW203                      | [7e50eb34dc](https://linux-hardware.org/?probe=7e50eb34dc) | Jun 24, 2020 |
| Dell          | 0RW203                      | [b853674a1a](https://linux-hardware.org/?probe=b853674a1a) | Jun 24, 2020 |
| HP            | 3032h                       | [5976308dd2](https://linux-hardware.org/?probe=5976308dd2) | Jun 23, 2020 |
| Gigabyte      | H81M-S2V                    | [5834d675d4](https://linux-hardware.org/?probe=5834d675d4) | Jun 22, 2020 |
| ASRock        | H61M-VS                     | [a7873af7a8](https://linux-hardware.org/?probe=a7873af7a8) | Jun 22, 2020 |
| HP            | 3032h                       | [e8f5c5f1dd](https://linux-hardware.org/?probe=e8f5c5f1dd) | Jun 22, 2020 |
| Gigabyte      | GA-870A-USB3L               | [5a16692c62](https://linux-hardware.org/?probe=5a16692c62) | Jun 21, 2020 |
| MSI           | H110M PRO-D                 | [c69d5f5bf9](https://linux-hardware.org/?probe=c69d5f5bf9) | Jun 20, 2020 |
| ASUSTek       | P5GC-MX/1333                | [c8f7c8e815](https://linux-hardware.org/?probe=c8f7c8e815) | Jun 15, 2020 |
| Gigabyte      | 990XA-UD3                   | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| Lenovo        | NOK                         | [b61ac858bf](https://linux-hardware.org/?probe=b61ac858bf) | Jun 06, 2020 |
| Gigabyte      | Z390 D                      | [b1a29e63a6](https://linux-hardware.org/?probe=b1a29e63a6) | Jun 06, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [aa7fa3a7d6](https://linux-hardware.org/?probe=aa7fa3a7d6) | Jun 05, 2020 |
| Intel         | DQ77MK AAG39642-302         | [dee8f8adaa](https://linux-hardware.org/?probe=dee8f8adaa) | Jun 03, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [0bd408c7b1](https://linux-hardware.org/?probe=0bd408c7b1) | Jun 03, 2020 |
| MSI           | X570-A PRO                  | [aeb2569425](https://linux-hardware.org/?probe=aeb2569425) | Jun 03, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [b56fca6b80](https://linux-hardware.org/?probe=b56fca6b80) | Jun 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [1cfddc628b](https://linux-hardware.org/?probe=1cfddc628b) | Jun 02, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [9db69a23c3](https://linux-hardware.org/?probe=9db69a23c3) | May 31, 2020 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [570ec797bb](https://linux-hardware.org/?probe=570ec797bb) | May 26, 2020 |
| Lenovo        | NOK                         | [1533aaa14e](https://linux-hardware.org/?probe=1533aaa14e) | May 25, 2020 |
| Lenovo        | NOK                         | [870f6a7371](https://linux-hardware.org/?probe=870f6a7371) | May 25, 2020 |
| Lenovo        | NOK                         | [65e8f4a17a](https://linux-hardware.org/?probe=65e8f4a17a) | May 25, 2020 |
| ASUSTek       | P8H77-M PRO                 | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASRock        | 970 Pro3 R2.0               | [194b0f5144](https://linux-hardware.org/?probe=194b0f5144) | May 19, 2020 |
| Gigabyte      | Z390 AORUS PRO-CF           | [efbb3a1981](https://linux-hardware.org/?probe=efbb3a1981) | May 19, 2020 |
| MSI           | B350 PC MATE                | [e451a207b9](https://linux-hardware.org/?probe=e451a207b9) | May 17, 2020 |
| MSI           | B350 PC MATE                | [0ad7002dd0](https://linux-hardware.org/?probe=0ad7002dd0) | May 15, 2020 |
| ASUSTek       | P5KC                        | [430457f5ee](https://linux-hardware.org/?probe=430457f5ee) | May 15, 2020 |
| OEM_MB        | Acacia                      | [728c9bcc6f](https://linux-hardware.org/?probe=728c9bcc6f) | May 13, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [bd619a1dbf](https://linux-hardware.org/?probe=bd619a1dbf) | May 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [50fc5c1115](https://linux-hardware.org/?probe=50fc5c1115) | May 09, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [9e0089ee78](https://linux-hardware.org/?probe=9e0089ee78) | May 09, 2020 |
| Dell          | 09KPNV A00                  | [4a3b4d800c](https://linux-hardware.org/?probe=4a3b4d800c) | May 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [24005d0bbd](https://linux-hardware.org/?probe=24005d0bbd) | May 08, 2020 |
| Dell          | 0XC7MM A00                  | [93a90c984c](https://linux-hardware.org/?probe=93a90c984c) | May 07, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [a4c12b7e1d](https://linux-hardware.org/?probe=a4c12b7e1d) | May 05, 2020 |
| Lenovo        | 3102 NOK                    | [a5548bc2a2](https://linux-hardware.org/?probe=a5548bc2a2) | May 05, 2020 |
| Lenovo        | 3102 NOK                    | [9045fced05](https://linux-hardware.org/?probe=9045fced05) | May 05, 2020 |
| ASRock        | N68-S                       | [6fe5619a96](https://linux-hardware.org/?probe=6fe5619a96) | May 04, 2020 |
| Gigabyte      | B250M-D2V-CF                | [fe8ae782e5](https://linux-hardware.org/?probe=fe8ae782e5) | May 04, 2020 |
| Complet       | MY8313                      | [9113ead08c](https://linux-hardware.org/?probe=9113ead08c) | May 01, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6bcd8b58d1](https://linux-hardware.org/?probe=6bcd8b58d1) | Apr 28, 2020 |
| Gigabyte      | EQ45M-S2                    | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Gigabyte      | Z97X-Gaming 7               | [ae0a57779f](https://linux-hardware.org/?probe=ae0a57779f) | Apr 24, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4f21b4b167](https://linux-hardware.org/?probe=4f21b4b167) | Apr 18, 2020 |
| ASUSTek       | H81M-K                      | [13f01f24a0](https://linux-hardware.org/?probe=13f01f24a0) | Apr 18, 2020 |
| Intel         | P61A-D3                     | [0f22534587](https://linux-hardware.org/?probe=0f22534587) | Apr 16, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e9be68d1ba](https://linux-hardware.org/?probe=e9be68d1ba) | Apr 13, 2020 |
| Gigabyte      | B150M-HD3-CF                | [cd8a2159c3](https://linux-hardware.org/?probe=cd8a2159c3) | Apr 13, 2020 |
| Intel         | DH77EB AAG39073-304         | [fcdb9f69df](https://linux-hardware.org/?probe=fcdb9f69df) | Apr 05, 2020 |
| Intel         | DH77EB AAG39073-304         | [e482f59a9f](https://linux-hardware.org/?probe=e482f59a9f) | Apr 04, 2020 |
| ASRock        | Q1900M                      | [ef0888b755](https://linux-hardware.org/?probe=ef0888b755) | Mar 31, 2020 |
| Dell          | 0M863N A00                  | [39201e0067](https://linux-hardware.org/?probe=39201e0067) | Mar 30, 2020 |
| HP            | 3047h                       | [82d80b5b7b](https://linux-hardware.org/?probe=82d80b5b7b) | Mar 28, 2020 |
| Pegatron      | 2A94h                       | [b48f3764dd](https://linux-hardware.org/?probe=b48f3764dd) | Mar 27, 2020 |
| Dell          | 0HR330                      | [45d93c28db](https://linux-hardware.org/?probe=45d93c28db) | Mar 27, 2020 |
| ASUSTek       | Maximus IV Extreme          | [0f6b13c96c](https://linux-hardware.org/?probe=0f6b13c96c) | Mar 26, 2020 |
| Gigabyte      | B450M DS3H-CF               | [63493eaa7c](https://linux-hardware.org/?probe=63493eaa7c) | Mar 26, 2020 |
| Gigabyte      | A320M-S2H-CF                | [7f673748d3](https://linux-hardware.org/?probe=7f673748d3) | Mar 25, 2020 |
| ASUSTek       | PRIME Z370-A                | [29e5b3da4d](https://linux-hardware.org/?probe=29e5b3da4d) | Mar 20, 2020 |
| MSI           | B250M PRO-VDH               | [76e711b112](https://linux-hardware.org/?probe=76e711b112) | Mar 19, 2020 |
| MSI           | B250M PRO-VDH               | [8dfaccae3f](https://linux-hardware.org/?probe=8dfaccae3f) | Mar 19, 2020 |
| Gigabyte      | B250M-D2V-CF                | [0a4936eac1](https://linux-hardware.org/?probe=0a4936eac1) | Mar 18, 2020 |
| Acer          | RS780DV                     | [e8a070d344](https://linux-hardware.org/?probe=e8a070d344) | Mar 15, 2020 |
| Gigabyte      | B450M DS3H-CF               | [5f9a0dc8a8](https://linux-hardware.org/?probe=5f9a0dc8a8) | Mar 12, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9b5408936f](https://linux-hardware.org/?probe=9b5408936f) | Mar 09, 2020 |
| MSI           | MS-7367                     | [8eb4606ae2](https://linux-hardware.org/?probe=8eb4606ae2) | Mar 07, 2020 |
| Gigabyte      | B250M-D2V-CF                | [f625e9f2ae](https://linux-hardware.org/?probe=f625e9f2ae) | Mar 06, 2020 |
| ASRock        | N68-S                       | [dfa1f67ae9](https://linux-hardware.org/?probe=dfa1f67ae9) | Mar 03, 2020 |
| Intel         | P61A-D3                     | [21fe352cc4](https://linux-hardware.org/?probe=21fe352cc4) | Feb 29, 2020 |
| Gigabyte      | B250M-D2V-CF                | [6549fb9401](https://linux-hardware.org/?probe=6549fb9401) | Feb 25, 2020 |
| MSI           | MS-7367                     | [fd923525d3](https://linux-hardware.org/?probe=fd923525d3) | Feb 21, 2020 |
| ASRock        | X99 Professional Gaming ... | [d1589dfc12](https://linux-hardware.org/?probe=d1589dfc12) | Feb 21, 2020 |
| ASRock        | X570 Taichi                 | [4af950f796](https://linux-hardware.org/?probe=4af950f796) | Feb 21, 2020 |
| ASUSTek       | J1800I-C                    | [a1311f8998](https://linux-hardware.org/?probe=a1311f8998) | Feb 18, 2020 |
| ASUSTek       | J1800I-C                    | [35e0f9b772](https://linux-hardware.org/?probe=35e0f9b772) | Feb 18, 2020 |
| ASUSTek       | Maximus IV Extreme          | [daf1f1f048](https://linux-hardware.org/?probe=daf1f1f048) | Feb 18, 2020 |
| ASUSTek       | Maximus IV Extreme          | [48767aacae](https://linux-hardware.org/?probe=48767aacae) | Feb 18, 2020 |
| ASUSTek       | Z170-A                      | [1ef6222ab2](https://linux-hardware.org/?probe=1ef6222ab2) | Feb 16, 2020 |
| ASUSTek       | Z170-A                      | [c96f9af8a3](https://linux-hardware.org/?probe=c96f9af8a3) | Feb 16, 2020 |
| ASUSTek       | Z10PA-D8 Series             | [150fb396a7](https://linux-hardware.org/?probe=150fb396a7) | Feb 10, 2020 |
| Gigabyte      | P61A-D3                     | [2bc82261f2](https://linux-hardware.org/?probe=2bc82261f2) | Feb 10, 2020 |
| MSI           | A320M PRO-VD PLUS           | [e6ac4bad03](https://linux-hardware.org/?probe=e6ac4bad03) | Feb 04, 2020 |
| MSI           | A320M PRO-VD PLUS           | [3b23ebaf4a](https://linux-hardware.org/?probe=3b23ebaf4a) | Feb 04, 2020 |
| ASUSTek       | P8H61-M LX2/CSM             | [68ecdc80d6](https://linux-hardware.org/?probe=68ecdc80d6) | Jan 30, 2020 |
| ASUSTek       | Maximus IV Extreme          | [c693069d4a](https://linux-hardware.org/?probe=c693069d4a) | Jan 30, 2020 |
| HP            | 83F0                        | [89a6f21080](https://linux-hardware.org/?probe=89a6f21080) | Jan 27, 2020 |
| ASRock        | N68-S                       | [ce51ddbd14](https://linux-hardware.org/?probe=ce51ddbd14) | Jan 20, 2020 |
| HP            | 339B                        | [2660198e55](https://linux-hardware.org/?probe=2660198e55) | Jan 18, 2020 |
| Gigabyte      | AX370-Gaming 5              | [25c8c37228](https://linux-hardware.org/?probe=25c8c37228) | Jan 16, 2020 |
| ASUSTek       | Maximus IV Extreme          | [317c6352fb](https://linux-hardware.org/?probe=317c6352fb) | Jan 13, 2020 |
| HP            | 1850                        | [2b217c7053](https://linux-hardware.org/?probe=2b217c7053) | Jan 12, 2020 |
| ASRock        | B150M-HDV                   | [51120580b6](https://linux-hardware.org/?probe=51120580b6) | Jan 12, 2020 |
| Acer          | RS780DV                     | [ce332a3ede](https://linux-hardware.org/?probe=ce332a3ede) | Jan 08, 2020 |
| ASRock        | G41M-VS3                    | [746152d015](https://linux-hardware.org/?probe=746152d015) | Jan 08, 2020 |
| HP            | 3396                        | [ab6fc8a364](https://linux-hardware.org/?probe=ab6fc8a364) | Jan 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [02c480f1df](https://linux-hardware.org/?probe=02c480f1df) | Jan 04, 2020 |
| Dell          | 0TY565                      | [f4507c2fdb](https://linux-hardware.org/?probe=f4507c2fdb) | Jan 03, 2020 |
| Gigabyte      | B365M HD3                   | [38e87e8eda](https://linux-hardware.org/?probe=38e87e8eda) | Dec 31, 2019 |
| Gigabyte      | B365M HD3                   | [27b598fbcd](https://linux-hardware.org/?probe=27b598fbcd) | Dec 31, 2019 |
| ASUSTek       | PRIME Z370-P                | [6b8999dfe2](https://linux-hardware.org/?probe=6b8999dfe2) | Dec 31, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [89c89d30f5](https://linux-hardware.org/?probe=89c89d30f5) | Dec 29, 2019 |
| ASRock        | G41M-VS3                    | [6fdb8dfe61](https://linux-hardware.org/?probe=6fdb8dfe61) | Dec 26, 2019 |
| MSI           | H81M-P33                    | [ad72c20454](https://linux-hardware.org/?probe=ad72c20454) | Dec 15, 2019 |
| Dell          | 0GXM1W A00                  | [0ef6e2666a](https://linux-hardware.org/?probe=0ef6e2666a) | Dec 12, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [94934b2da3](https://linux-hardware.org/?probe=94934b2da3) | Dec 07, 2019 |
| Pegatron      | 2A94                        | [f94ced2773](https://linux-hardware.org/?probe=f94ced2773) | Dec 05, 2019 |
| HP            | 3396                        | [aa20ad778c](https://linux-hardware.org/?probe=aa20ad778c) | Dec 01, 2019 |
| ZOTAC         | AMD HUDSON-M1               | [d26292844b](https://linux-hardware.org/?probe=d26292844b) | Nov 29, 2019 |
| Gigabyte      | G31M-ES2L                   | [cc5e341359](https://linux-hardware.org/?probe=cc5e341359) | Nov 22, 2019 |
| Packard Be... | IMEDIA L4880                | [3dc7cd311b](https://linux-hardware.org/?probe=3dc7cd311b) | Nov 21, 2019 |
| MSI           | A55M-P33                    | [ae27e5ac51](https://linux-hardware.org/?probe=ae27e5ac51) | Nov 18, 2019 |
| Pegatron      | Benicia                     | [50c16b189c](https://linux-hardware.org/?probe=50c16b189c) | Nov 15, 2019 |
| MSI           | A55M-P33                    | [29dd833843](https://linux-hardware.org/?probe=29dd833843) | Nov 14, 2019 |
| ASUSTek       | Z97-K                       | [1d74a5a6c1](https://linux-hardware.org/?probe=1d74a5a6c1) | Nov 12, 2019 |
| MSI           | Z170A XPOWER GAMING TITA... | [8868e8087f](https://linux-hardware.org/?probe=8868e8087f) | Nov 07, 2019 |
| MSI           | MS-7360                     | [d3a716b66f](https://linux-hardware.org/?probe=d3a716b66f) | Nov 03, 2019 |
| MSI           | MS-7360                     | [441f1bb5cc](https://linux-hardware.org/?probe=441f1bb5cc) | Nov 03, 2019 |
| HP            | 2820h                       | [61f956fa74](https://linux-hardware.org/?probe=61f956fa74) | Nov 02, 2019 |
| HP            | 2820h                       | [aa5b0ed445](https://linux-hardware.org/?probe=aa5b0ed445) | Nov 02, 2019 |
| HP            | 2820h                       | [2215b346af](https://linux-hardware.org/?probe=2215b346af) | Nov 02, 2019 |
| Dell          | 0RW199                      | [eec984cf36](https://linux-hardware.org/?probe=eec984cf36) | Oct 27, 2019 |
| MSI           | H81M-P33                    | [2b781a9140](https://linux-hardware.org/?probe=2b781a9140) | Oct 16, 2019 |
| MSI           | H81M-P33                    | [ebec8ad331](https://linux-hardware.org/?probe=ebec8ad331) | Oct 16, 2019 |
| Gigabyte      | 8I915P Duo                  | [62d61d6cf7](https://linux-hardware.org/?probe=62d61d6cf7) | Sep 23, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [4c3108daed](https://linux-hardware.org/?probe=4c3108daed) | Sep 22, 2019 |
| Gigabyte      | G31M-S2C                    | [a6ba57e034](https://linux-hardware.org/?probe=a6ba57e034) | Sep 14, 2019 |
| Dell          | 0NK70N A03                  | [c7e1e32971](https://linux-hardware.org/?probe=c7e1e32971) | Sep 12, 2019 |
| MSI           | H110M PRO-D                 | [50b9ccd9d4](https://linux-hardware.org/?probe=50b9ccd9d4) | Aug 20, 2019 |
| Pegatron      | 2A94h                       | [036d8fd0d2](https://linux-hardware.org/?probe=036d8fd0d2) | Aug 11, 2019 |
| Foxconn       | 2A8C                        | [8c6027330f](https://linux-hardware.org/?probe=8c6027330f) | Aug 07, 2019 |
| Gigabyte      | B85-HD3-A                   | [49b5471963](https://linux-hardware.org/?probe=49b5471963) | Aug 06, 2019 |
| ASRock        | H81M-VG4 R2.0               | [5df54937af](https://linux-hardware.org/?probe=5df54937af) | Aug 01, 2019 |
| ASRock        | H81M-VG4 R2.0               | [fde713212c](https://linux-hardware.org/?probe=fde713212c) | Aug 01, 2019 |
| ASRock        | H81M-VG4 R2.0               | [f59241f4fe](https://linux-hardware.org/?probe=f59241f4fe) | Aug 01, 2019 |
| ASUSTek       | Z170 PRO GAMING             | [6dc8d77438](https://linux-hardware.org/?probe=6dc8d77438) | Jul 30, 2019 |
| Pegatron      | 2A73h                       | [dd83d661bd](https://linux-hardware.org/?probe=dd83d661bd) | Jul 22, 2019 |
| Gigabyte      | A320M-H-CF                  | [be4f0a278a](https://linux-hardware.org/?probe=be4f0a278a) | Jul 20, 2019 |
| Gigabyte      | A320M-H-CF                  | [2179866533](https://linux-hardware.org/?probe=2179866533) | Jul 12, 2019 |
| ASUSTek       | P5LD2-Deluxe                | [2bf9512ad1](https://linux-hardware.org/?probe=2bf9512ad1) | Jun 29, 2019 |
| ASUSTek       | P5LD2-Deluxe                | [a14cd7c7f6](https://linux-hardware.org/?probe=a14cd7c7f6) | Jun 29, 2019 |
| Gigabyte      | P41T-D3                     | [e6c57b3382](https://linux-hardware.org/?probe=e6c57b3382) | Jun 28, 2019 |
| Foxconn       | 2A8C                        | [928d183726](https://linux-hardware.org/?probe=928d183726) | Jun 21, 2019 |
| ASUSTek       | PRIME Z370-P                | [bbf26abf59](https://linux-hardware.org/?probe=bbf26abf59) | Jun 08, 2019 |
| AMI           | Cherry Trail CR             | [b22cee1c35](https://linux-hardware.org/?probe=b22cee1c35) | Jun 03, 2019 |
| ASRock        | A320M-DVS R4.0              | [6ca9fbd415](https://linux-hardware.org/?probe=6ca9fbd415) | May 28, 2019 |
| Gigabyte      | F2A78M-HD2                  | [57098a751c](https://linux-hardware.org/?probe=57098a751c) | May 23, 2019 |
| Dell          | 0Y7WYT A00                  | [5e6308d089](https://linux-hardware.org/?probe=5e6308d089) | May 21, 2019 |
| ASRock        | H97 Pro4                    | [3ce2141ee6](https://linux-hardware.org/?probe=3ce2141ee6) | May 20, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [d7d3d4f56b](https://linux-hardware.org/?probe=d7d3d4f56b) | May 19, 2019 |
| MSI           | Z270 GAMING PRO CARBON      | [8a74ee23bc](https://linux-hardware.org/?probe=8a74ee23bc) | May 17, 2019 |
| Foxconn       | 945 7AE Series              | [3845e956b9](https://linux-hardware.org/?probe=3845e956b9) | May 07, 2019 |
| HP            | 3397                        | [6ae2115a36](https://linux-hardware.org/?probe=6ae2115a36) | Apr 30, 2019 |
| ASUSTek       | A88X-PLUS                   | [a9fe63d8fe](https://linux-hardware.org/?probe=a9fe63d8fe) | Apr 30, 2019 |
| MSI           | G31TM-P21                   | [99777b72f9](https://linux-hardware.org/?probe=99777b72f9) | Apr 26, 2019 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [cf5404d629](https://linux-hardware.org/?probe=cf5404d629) | Apr 19, 2019 |
| ASUSTek       | P5B-Premium                 | [40f56d3108](https://linux-hardware.org/?probe=40f56d3108) | Apr 14, 2019 |
| Dell          | 02YYK5 A01                  | [9dcd7b3dd8](https://linux-hardware.org/?probe=9dcd7b3dd8) | Apr 10, 2019 |
| ASUSTek       | P5B-Premium                 | [90ab4e39e8](https://linux-hardware.org/?probe=90ab4e39e8) | Apr 07, 2019 |
| ASUSTek       | Maximus IV Extreme-Z        | [995bc4566a](https://linux-hardware.org/?probe=995bc4566a) | Apr 04, 2019 |
| ASUSTek       | P5K SE                      | [31de6cd2d0](https://linux-hardware.org/?probe=31de6cd2d0) | Mar 30, 2019 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [41b11ce878](https://linux-hardware.org/?probe=41b11ce878) | Mar 27, 2019 |
| Gigabyte      | P61A-D3                     | [16fcc7801b](https://linux-hardware.org/?probe=16fcc7801b) | Mar 17, 2019 |
| ASUSTek       | A88XM-A                     | [42af7fc1f3](https://linux-hardware.org/?probe=42af7fc1f3) | Mar 14, 2019 |
| MSI           | MS-7346                     | [3baabb1753](https://linux-hardware.org/?probe=3baabb1753) | Mar 14, 2019 |
| ASRock        | B150 Gaming K4/Hyper        | [fcd2e0fac9](https://linux-hardware.org/?probe=fcd2e0fac9) | Mar 05, 2019 |
| Dell          | 0KRC95 A02                  | [a1988b9c4d](https://linux-hardware.org/?probe=a1988b9c4d) | Jan 30, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [cb29bdbf2d](https://linux-hardware.org/?probe=cb29bdbf2d) | Jan 28, 2019 |
| ASUSTek       | A88XM-A                     | [8727337204](https://linux-hardware.org/?probe=8727337204) | Jan 03, 2019 |
| MSI           | GF615M-P33                  | [5ea14f0cad](https://linux-hardware.org/?probe=5ea14f0cad) | Dec 06, 2018 |
| Gigabyte      | A320M-S2H-CF                | [0dc3a4c1d2](https://linux-hardware.org/?probe=0dc3a4c1d2) | Nov 25, 2018 |
| Gigabyte      | A320M-S2H-CF                | [d50f5a68ba](https://linux-hardware.org/?probe=d50f5a68ba) | Nov 25, 2018 |
| Gigabyte      | A320M-S2H-CF                | [a72d5458ff](https://linux-hardware.org/?probe=a72d5458ff) | Nov 23, 2018 |
| Gigabyte      | X48-DS5                     | [c40e02daf8](https://linux-hardware.org/?probe=c40e02daf8) | Nov 23, 2018 |
| Gigabyte      | GA-MA74GM-S2H               | [ce695c7b55](https://linux-hardware.org/?probe=ce695c7b55) | Nov 18, 2018 |
| ASRock        | 970A-G                      | [c94c26c4fe](https://linux-hardware.org/?probe=c94c26c4fe) | Nov 17, 2018 |
| ASRock        | 970A-G                      | [eafdda2dc2](https://linux-hardware.org/?probe=eafdda2dc2) | Nov 17, 2018 |
| Gigabyte      | H55M-S2                     | [cdc9ee702d](https://linux-hardware.org/?probe=cdc9ee702d) | Nov 17, 2018 |
| Gigabyte      | H61M-S1                     | [66f67078ab](https://linux-hardware.org/?probe=66f67078ab) | Nov 13, 2018 |
| MSI           | MS-7346                     | [5a3b5f371e](https://linux-hardware.org/?probe=5a3b5f371e) | Nov 06, 2018 |
| Gigabyte      | EP41-UD3L                   | [0dcbf3f2de](https://linux-hardware.org/?probe=0dcbf3f2de) | Oct 25, 2018 |
| Gigabyte      | X48-DS5                     | [fcc7ff886e](https://linux-hardware.org/?probe=fcc7ff886e) | Sep 30, 2018 |
| MSI           | MS-7346                     | [faf555551b](https://linux-hardware.org/?probe=faf555551b) | Sep 26, 2018 |
| Gigabyte      | X48-DS5                     | [c02908e70d](https://linux-hardware.org/?probe=c02908e70d) | Sep 19, 2018 |
| MSI           | H110M PRO-D                 | [da7af8d522](https://linux-hardware.org/?probe=da7af8d522) | Sep 19, 2018 |
| Foxconn       | 2A8C                        | [82d6455d21](https://linux-hardware.org/?probe=82d6455d21) | Sep 19, 2018 |
| MSI           | MS-7346                     | [b3c93d2eb7](https://linux-hardware.org/?probe=b3c93d2eb7) | May 31, 2018 |
| MSI           | MS-7346                     | [545037fda5](https://linux-hardware.org/?probe=545037fda5) | May 31, 2018 |
| Gigabyte      | G31M-S2L                    | [cb713e1fdc](https://linux-hardware.org/?probe=cb713e1fdc) | May 16, 2018 |
| Gigabyte      | AX370-Gaming 5              | [2f17066f92](https://linux-hardware.org/?probe=2f17066f92) | Mar 19, 2018 |
| Gigabyte      | AX370-Gaming 5              | [69127de08f](https://linux-hardware.org/?probe=69127de08f) | Mar 16, 2018 |
| ASUSTek       | H110M-K                     | [978f84d6c0](https://linux-hardware.org/?probe=978f84d6c0) | Mar 13, 2018 |
| ABIT          | IP35                        | [0bb2462820](https://linux-hardware.org/?probe=0bb2462820) | Feb 24, 2018 |
| MSI           | G41M4                       | [a00139a613](https://linux-hardware.org/?probe=a00139a613) | Feb 20, 2018 |
| Gigabyte      | EP43-UD3L                   | [585d110911](https://linux-hardware.org/?probe=585d110911) | Dec 17, 2017 |
| MSI           | G41M4                       | [36c4e313ac](https://linux-hardware.org/?probe=36c4e313ac) | Dec 08, 2017 |
| ASUSTek       | H110M-K                     | [6d7e86c85a](https://linux-hardware.org/?probe=6d7e86c85a) | Dec 08, 2017 |
| ASUSTek       | M3A78 PRO                   | [2c258a2915](https://linux-hardware.org/?probe=2c258a2915) | Dec 07, 2017 |
| ASRock        | H81M-HDS                    | [ab1774560b](https://linux-hardware.org/?probe=ab1774560b) | Dec 05, 2017 |
| ASUSTek       | P5K SE                      | [40bd9b1ada](https://linux-hardware.org/?probe=40bd9b1ada) | Oct 26, 2017 |
| Gigabyte      | H110M-DS2-CF                | [6d0e45f3ce](https://linux-hardware.org/?probe=6d0e45f3ce) | Sep 19, 2017 |
| MSI           | 2A78h                       | [11214e5016](https://linux-hardware.org/?probe=11214e5016) | May 31, 2017 |
| MSI           | G41M4                       | [238edf60a9](https://linux-hardware.org/?probe=238edf60a9) | May 13, 2017 |
| Foxconn       | 2A8C                        | [40bd4d1f0c](https://linux-hardware.org/?probe=40bd4d1f0c) | Apr 22, 2017 |
| ASRock        | B85M-DGS                    | [e85a15a247](https://linux-hardware.org/?probe=e85a15a247) | Apr 02, 2017 |
| HP            | 3029h                       | [3a677087d4](https://linux-hardware.org/?probe=3a677087d4) | Mar 11, 2017 |
| Gigabyte      | P75-D3                      | [c489105947](https://linux-hardware.org/?probe=c489105947) | Mar 10, 2017 |
| Gigabyte      | P75-D3                      | [185a41377a](https://linux-hardware.org/?probe=185a41377a) | Mar 10, 2017 |
| Gigabyte      | EP35-DS3                    | [a9bf5b385b](https://linux-hardware.org/?probe=a9bf5b385b) | Mar 09, 2017 |
| ASRock        | B85 Killer                  | [a59bf1823c](https://linux-hardware.org/?probe=a59bf1823c) | Feb 24, 2017 |
| ASRock        | B150M-HDV                   | [d95ccebd88](https://linux-hardware.org/?probe=d95ccebd88) | Feb 08, 2017 |
| Gigabyte      | B250-HD3P-CF                | [6126e55d1a](https://linux-hardware.org/?probe=6126e55d1a) | Jan 19, 2017 |
| ASRock        | B150M-HDV                   | [14e2cbe871](https://linux-hardware.org/?probe=14e2cbe871) | Jan 10, 2017 |
| Gigabyte      | EP45-DS3R                   | [86b3438b9e](https://linux-hardware.org/?probe=86b3438b9e) | Dec 05, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 62       | 13.51%  |
| Ubuntu 18.04                 | 37       | 8.06%   |
| BlackPanther 18.1            | 30       | 6.54%   |
| OpenMandriva 4.2             | 21       | 4.58%   |
| ROSA R10                     | 11       | 2.4%    |
| Manjaro                      | 11       | 2.4%    |
| Arch                         | 9        | 1.96%   |
| Xubuntu 20.04                | 8        | 1.74%   |
| Pop!_OS 20.04                | 8        | 1.74%   |
| Linux Mint 20.2              | 8        | 1.74%   |
| ROSA R11                     | 7        | 1.53%   |
| OpenMandriva 4.3             | 7        | 1.53%   |
| ArcoLinux Rolling            | 7        | 1.53%   |
| Ubuntu 19.10                 | 6        | 1.31%   |
| Pop!_OS 20.10                | 6        | 1.31%   |
| KDE neon 20.04               | 6        | 1.31%   |
| Fedora 31                    | 6        | 1.31%   |
| Ubuntu 22.04                 | 5        | 1.09%   |
| Ubuntu 21.04                 | 5        | 1.09%   |
| Ubuntu 19.04                 | 5        | 1.09%   |
| ROSA R9                      | 5        | 1.09%   |
| ROSA R8                      | 5        | 1.09%   |
| Linux Mint 20.1              | 5        | 1.09%   |
| Fedora 35                    | 5        | 1.09%   |
| Debian 11                    | 5        | 1.09%   |
| Ubuntu 20.10                 | 4        | 0.87%   |
| Ubuntu 18.10                 | 4        | 0.87%   |
| Ubuntu 16.04                 | 4        | 0.87%   |
| ROSA R11.1                   | 4        | 0.87%   |
| Pop!_OS 21.10                | 4        | 0.87%   |
| Pop!_OS 21.04                | 4        | 0.87%   |
| Linux Mint 20.3              | 4        | 0.87%   |
| Linux Mint 19.3              | 4        | 0.87%   |
| Fedora 34                    | 4        | 0.87%   |
| Fedora 33                    | 4        | 0.87%   |
| Endless 3.7.8                | 4        | 0.87%   |
| Debian 10                    | 4        | 0.87%   |
| Arch Rolling                 | 4        | 0.87%   |
| Zorin 16                     | 3        | 0.65%   |
| ROSA R8.1                    | 3        | 0.65%   |
| Pop!_OS 22.04                | 3        | 0.65%   |
| OpenMandriva 4.50            | 3        | 0.65%   |
| Linux Mint 20                | 3        | 0.65%   |
| Kubuntu 20.04                | 3        | 0.65%   |
| Fedora 30                    | 3        | 0.65%   |
| Endless 3.7.5                | 3        | 0.65%   |
| Zorin 15                     | 2        | 0.44%   |
| Zorin 12                     | 2        | 0.44%   |
| Peppermint 10                | 2        | 0.44%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.44%   |
| Manjaro 20.1                 | 2        | 0.44%   |
| Linux Mint 19.2              | 2        | 0.44%   |
| Gentoo 2.6                   | 2        | 0.44%   |
| Garuda Linux                 | 2        | 0.44%   |
| Fedora 36                    | 2        | 0.44%   |
| Fedora 32                    | 2        | 0.44%   |
| Endless 3.9.5                | 2        | 0.44%   |
| Endless 3.9.4                | 2        | 0.44%   |
| Endless 3.9.1                | 2        | 0.44%   |
| Endless 3.8.4                | 2        | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu            | 128      | 29.22%  |
| OpenMandriva      | 31       | 7.08%   |
| BlackPanther      | 31       | 7.08%   |
| ROSA              | 30       | 6.85%   |
| Endless           | 29       | 6.62%   |
| Linux Mint        | 26       | 5.94%   |
| Fedora            | 26       | 5.94%   |
| Pop!_OS           | 25       | 5.71%   |
| Manjaro           | 20       | 4.57%   |
| Arch              | 13       | 2.97%   |
| Debian            | 11       | 2.51%   |
| Xubuntu           | 8        | 1.83%   |
| ArcoLinux         | 8        | 1.83%   |
| Zorin             | 7        | 1.6%    |
| KDE neon          | 7        | 1.6%    |
| Clear Linux       | 5        | 1.14%   |
| Gentoo            | 4        | 0.91%   |
| openSUSE          | 3        | 0.68%   |
| Kubuntu           | 3        | 0.68%   |
| Garuda Linux      | 3        | 0.68%   |
| CentOS            | 3        | 0.68%   |
| Ubuntu MATE       | 2        | 0.46%   |
| Ubuntu Budgie     | 2        | 0.46%   |
| Peppermint        | 2        | 0.46%   |
| Lubuntu           | 2        | 0.46%   |
| Elementary        | 2        | 0.46%   |
| Ultramarine Linux | 1        | 0.23%   |
| Ubuntu Studio     | 1        | 0.23%   |
| Redcore           | 1        | 0.23%   |
| Parrot            | 1        | 0.23%   |
| Oracle Linux      | 1        | 0.23%   |
| LMDE              | 1        | 0.23%   |
| Deepin            | 1        | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.18.16-desktop-1bP             | 26       | 5.12%   |
| 5.10.14-desktop-1omv4002        | 20       | 3.94%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 10       | 1.97%   |
| 5.4.0-42-generic                | 8        | 1.57%   |
| 5.8.0-14-generic                | 7        | 1.38%   |
| 5.4.0-40-generic                | 7        | 1.38%   |
| 5.16.7-desktop-1omv4003         | 7        | 1.38%   |
| 5.6.14-desktop-2bP              | 5        | 0.98%   |
| 5.4.0-74-generic                | 5        | 0.98%   |
| 5.4.0-72-generic                | 5        | 0.98%   |
| 5.4.0-52-generic                | 5        | 0.98%   |
| 5.4.0-29-generic                | 5        | 0.98%   |
| 5.3.0-28-generic                | 5        | 0.98%   |
| 5.8.0-7630-generic              | 4        | 0.79%   |
| 5.4.0-89-generic                | 4        | 0.79%   |
| 5.4.0-7634-generic              | 4        | 0.79%   |
| 5.4.0-66-generic                | 4        | 0.79%   |
| 5.4.0-51-generic                | 4        | 0.79%   |
| 5.4.0-48-generic                | 4        | 0.79%   |
| 5.4.0-47-generic                | 4        | 0.79%   |
| 5.4.0-19-generic                | 4        | 0.79%   |
| 5.3.0-46-generic                | 4        | 0.79%   |
| 5.3.0-23-generic                | 4        | 0.79%   |
| 5.3.0-19-generic                | 4        | 0.79%   |
| 5.11.0-34-generic               | 4        | 0.79%   |
| 4.15.0-50-generic               | 4        | 0.79%   |
| 5.8.0-7642-generic              | 3        | 0.59%   |
| 5.4.0-91-generic                | 3        | 0.59%   |
| 5.4.0-77-generic                | 3        | 0.59%   |
| 5.4.0-54-generic                | 3        | 0.59%   |
| 5.4.0-37-generic                | 3        | 0.59%   |
| 5.4.0-31-generic                | 3        | 0.59%   |
| 5.11.0-7620-generic             | 3        | 0.59%   |
| 5.11.0-43-generic               | 3        | 0.59%   |
| 5.11.0-38-generic               | 3        | 0.59%   |
| 4.9.76-nrj-desktop-1rosa-x86_64 | 3        | 0.59%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3        | 0.59%   |
| 4.18.0-15-generic               | 3        | 0.59%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3        | 0.59%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 3        | 0.59%   |
| 5.9.16-1-MANJARO                | 2        | 0.39%   |
| 5.8.3-2-MANJARO                 | 2        | 0.39%   |
| 5.8.18-100.fc31.x86_64          | 2        | 0.39%   |
| 5.8.18-1-MANJARO                | 2        | 0.39%   |
| 5.8.0-41-generic                | 2        | 0.39%   |
| 5.8.0-36-generic                | 2        | 0.39%   |
| 5.8.0-29-generic                | 2        | 0.39%   |
| 5.4.32-generic-2rosa-x86_64     | 2        | 0.39%   |
| 5.4.18-100.fc30.x86_64          | 2        | 0.39%   |
| 5.4.0-80-generic                | 2        | 0.39%   |
| 5.4.0-70-generic                | 2        | 0.39%   |
| 5.4.0-58-generic                | 2        | 0.39%   |
| 5.4.0-56-generic                | 2        | 0.39%   |
| 5.4.0-45-generic                | 2        | 0.39%   |
| 5.4.0-33-generic                | 2        | 0.39%   |
| 5.4.0-26-generic                | 2        | 0.39%   |
| 5.4.0-122-generic               | 2        | 0.39%   |
| 5.4.0-107-generic               | 2        | 0.39%   |
| 5.4.0-100-generic               | 2        | 0.39%   |
| 5.3.0-42-generic                | 2        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 93       | 19.54%  |
| 4.15.0  | 35       | 7.35%   |
| 5.8.0   | 28       | 5.88%   |
| 5.11.0  | 27       | 5.67%   |
| 4.18.16 | 26       | 5.46%   |
| 5.3.0   | 25       | 5.25%   |
| 5.10.14 | 20       | 4.2%    |
| 5.0.0   | 15       | 3.15%   |
| 4.18.0  | 11       | 2.31%   |
| 4.9.60  | 10       | 2.1%    |
| 5.15.0  | 8        | 1.68%   |
| 5.13.0  | 8        | 1.68%   |
| 5.16.7  | 7        | 1.47%   |
| 5.10.0  | 6        | 1.26%   |
| 4.9.20  | 6        | 1.26%   |
| 5.8.18  | 5        | 1.05%   |
| 5.6.14  | 5        | 1.05%   |
| 5.15.12 | 4        | 0.84%   |
| 4.19.0  | 4        | 0.84%   |
| 5.18.10 | 3        | 0.63%   |
| 5.16.11 | 3        | 0.63%   |
| 4.9.76  | 3        | 0.63%   |
| 4.1.34  | 3        | 0.63%   |
| 5.9.16  | 2        | 0.42%   |
| 5.9.14  | 2        | 0.42%   |
| 5.8.3   | 2        | 0.42%   |
| 5.7.9   | 2        | 0.42%   |
| 5.6.8   | 2        | 0.42%   |
| 5.4.38  | 2        | 0.42%   |
| 5.4.32  | 2        | 0.42%   |
| 5.4.18  | 2        | 0.42%   |
| 5.16.15 | 2        | 0.42%   |
| 5.15.4  | 2        | 0.42%   |
| 5.15.26 | 2        | 0.42%   |
| 5.14.0  | 2        | 0.42%   |
| 5.12.4  | 2        | 0.42%   |
| 5.10.15 | 2        | 0.42%   |
| 4.9.9   | 2        | 0.42%   |
| 4.9.155 | 2        | 0.42%   |
| 4.9.124 | 2        | 0.42%   |
| 4.13.0  | 2        | 0.42%   |
| 4.1.38  | 2        | 0.42%   |
| 5.9.13  | 1        | 0.21%   |
| 5.9.11  | 1        | 0.21%   |
| 5.9.0   | 1        | 0.21%   |
| 5.8.6   | 1        | 0.21%   |
| 5.8.4   | 1        | 0.21%   |
| 5.8.17  | 1        | 0.21%   |
| 5.8.16  | 1        | 0.21%   |
| 5.8.14  | 1        | 0.21%   |
| 5.8.13  | 1        | 0.21%   |
| 5.7.7   | 1        | 0.21%   |
| 5.7.19  | 1        | 0.21%   |
| 5.6.6   | 1        | 0.21%   |
| 5.6.3   | 1        | 0.21%   |
| 5.6.15  | 1        | 0.21%   |
| 5.6.10  | 1        | 0.21%   |
| 5.6.0   | 1        | 0.21%   |
| 5.5.3   | 1        | 0.21%   |
| 5.5.11  | 1        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 107      | 22.96%  |
| 5.8     | 41       | 8.8%    |
| 4.18    | 37       | 7.94%   |
| 4.15    | 35       | 7.51%   |
| 5.11    | 31       | 6.65%   |
| 5.10    | 30       | 6.44%   |
| 5.3     | 27       | 5.79%   |
| 5.15    | 21       | 4.51%   |
| 4.9     | 21       | 4.51%   |
| 5.0     | 18       | 3.86%   |
| 5.16    | 14       | 3%      |
| 5.6     | 11       | 2.36%   |
| 5.13    | 11       | 2.36%   |
| 5.18    | 9        | 1.93%   |
| 5.14    | 8        | 1.72%   |
| 5.9     | 7        | 1.5%    |
| 5.17    | 6        | 1.29%   |
| 5.12    | 6        | 1.29%   |
| 4.19    | 5        | 1.07%   |
| 4.1     | 5        | 1.07%   |
| 5.7     | 4        | 0.86%   |
| 5.2     | 3        | 0.64%   |
| 5.5     | 2        | 0.43%   |
| 4.8     | 2        | 0.43%   |
| 4.13    | 2        | 0.43%   |
| 5.1     | 1        | 0.21%   |
| 4.4     | 1        | 0.21%   |
| 4.14    | 1        | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 417      | 98.82%  |
| i686   | 5        | 1.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 174      | 39.37%  |
| KDE5            | 94       | 21.27%  |
| Unknown         | 64       | 14.48%  |
| X-Cinnamon      | 23       | 5.2%    |
| XFCE            | 22       | 4.98%   |
| KDE4            | 18       | 4.07%   |
| KDE             | 16       | 3.62%   |
| MATE            | 6        | 1.36%   |
| LXQt            | 5        | 1.13%   |
| Unity           | 4        | 0.9%    |
| LXDE            | 4        | 0.9%    |
| Cinnamon        | 3        | 0.68%   |
| Budgie          | 2        | 0.45%   |
| sway            | 1        | 0.23%   |
| Pantheon        | 1        | 0.23%   |
| i3              | 1        | 0.23%   |
| GNUstep         | 1        | 0.23%   |
| GNOME Flashback | 1        | 0.23%   |
| dusk            | 1        | 0.23%   |
| Deepin          | 1        | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 357      | 82.83%  |
| Unknown     | 37       | 8.58%   |
| Wayland     | 32       | 7.42%   |
| Tty         | 4        | 0.93%   |
| Unspecified | 1        | 0.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 244      | 55.2%   |
| SDDM    | 91       | 20.59%  |
| GDM     | 37       | 8.37%   |
| LightDM | 21       | 4.75%   |
| KDM     | 19       | 4.3%    |
| GDM3    | 15       | 3.39%   |
| TDM     | 12       | 2.71%   |
| XDM     | 1        | 0.23%   |
| Ly      | 1        | 0.23%   |
| LXDM    | 1        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 219      | 50.58%  |
| Unknown     | 108      | 24.94%  |
| ro_RO       | 81       | 18.71%  |
| en_GB       | 6        | 1.39%   |
| hu_HU       | 4        | 0.92%   |
| C           | 4        | 0.92%   |
| fr_FR       | 2        | 0.46%   |
| de_DE       | 2        | 0.46%   |
| ru_RU       | 1        | 0.23%   |
| it_IT       | 1        | 0.23%   |
| es_ES       | 1        | 0.23%   |
| en_US.UTF8  | 1        | 0.23%   |
| en_US.utf-8 | 1        | 0.23%   |
| en_IN       | 1        | 0.23%   |
| en_DE       | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 275      | 64.71%  |
| EFI  | 150      | 35.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 303      | 70.14%  |
| Overlay | 54       | 12.5%   |
| Unknown | 41       | 9.49%   |
| Btrfs   | 19       | 4.4%    |
| Xfs     | 8        | 1.85%   |
| Zfs     | 2        | 0.46%   |
| F2fs    | 2        | 0.46%   |
| Jfs     | 1        | 0.23%   |
| Ext3    | 1        | 0.23%   |
| Ext2    | 1        | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 247      | 57.85%  |
| GPT     | 94       | 22.01%  |
| MBR     | 86       | 20.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 353      | 81.34%  |
| Yes       | 81       | 18.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 295      | 68.29%  |
| Yes       | 137      | 31.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 103      | 24.47%  |
| ASUSTek Computer    | 84       | 19.95%  |
| MSI                 | 54       | 12.83%  |
| Hewlett-Packard     | 40       | 9.5%    |
| Dell                | 36       | 8.55%   |
| ASRock              | 35       | 8.31%   |
| Lenovo              | 18       | 4.28%   |
| Acer                | 8        | 1.9%    |
| Intel               | 6        | 1.43%   |
| Foxconn             | 6        | 1.43%   |
| Pegatron            | 5        | 1.19%   |
| Fujitsu Siemens     | 5        | 1.19%   |
| Unknown             | 4        | 0.95%   |
| Fujitsu             | 3        | 0.71%   |
| Complet             | 2        | 0.48%   |
| ZOTAC               | 1        | 0.24%   |
| Packard Bell        | 1        | 0.24%   |
| OEM_MB              | 1        | 0.24%   |
| Medion              | 1        | 0.24%   |
| IBM                 | 1        | 0.24%   |
| Huanan              | 1        | 0.24%   |
| ECS                 | 1        | 0.24%   |
| Daewoo Lucoms       | 1        | 0.24%   |
| Biostar             | 1        | 0.24%   |
| ASRockRack          | 1        | 0.24%   |
| AMI                 | 1        | 0.24%   |
| ABIT                | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 11       | 2.61%   |
| Gigabyte B450M DS3H                    | 5        | 1.19%   |
| MSI MS-7996                            | 4        | 0.95%   |
| MSI MS-7721                            | 4        | 0.95%   |
| Gigabyte X470 AORUS ULTRA GAMING       | 4        | 0.95%   |
| Dell OptiPlex 7010                     | 4        | 0.95%   |
| Unknown                                | 4        | 0.95%   |
| Gigabyte TRX40 AORUS MASTER            | 3        | 0.71%   |
| Gigabyte A320M-S2H                     | 3        | 0.71%   |
| ASUS Z170 PRO GAMING                   | 3        | 0.71%   |
| ASUS PRIME H310M-R R2.0                | 3        | 0.71%   |
| ASUS PRIME A320M-K                     | 3        | 0.71%   |
| ASRock G41M-VS3                        | 3        | 0.71%   |
| MSI MS-7C52                            | 2        | 0.48%   |
| MSI MS-7C37                            | 2        | 0.48%   |
| MSI MS-7B38                            | 2        | 0.48%   |
| MSI MS-7A34                            | 2        | 0.48%   |
| MSI MS-7817                            | 2        | 0.48%   |
| MSI MS-7596                            | 2        | 0.48%   |
| Lenovo ThinkCentre M83 10AHS0FM00      | 2        | 0.48%   |
| HP EliteDesk 800 G1 SFF                | 2        | 0.48%   |
| HP Compaq Elite 8300 SFF               | 2        | 0.48%   |
| HP Compaq dc7900 Small Form Factor     | 2        | 0.48%   |
| HP Compaq dc7900 Convertible Minitower | 2        | 0.48%   |
| HP Compaq dc7800p Small Form Factor    | 2        | 0.48%   |
| HP Compaq dc5800 Small Form Factor     | 2        | 0.48%   |
| HP Compaq 8200 Elite CMT PC            | 2        | 0.48%   |
| HP Compaq 6200 Pro SFF PC              | 2        | 0.48%   |
| HP Compaq 6005 Pro SFF PC              | 2        | 0.48%   |
| Gigabyte X570 AORUS PRO                | 2        | 0.48%   |
| Gigabyte X570 AORUS ELITE              | 2        | 0.48%   |
| Gigabyte P75-D3                        | 2        | 0.48%   |
| Gigabyte H61M-DS2                      | 2        | 0.48%   |
| Gigabyte GA-78LMT-USB3 6.0             | 2        | 0.48%   |
| Gigabyte G31M-ES2L                     | 2        | 0.48%   |
| Gigabyte AB350-Gaming 3                | 2        | 0.48%   |
| Gigabyte A320M-H                       | 2        | 0.48%   |
| Foxconn 500B Microtower                | 2        | 0.48%   |
| Dell Precision WorkStation T3500       | 2        | 0.48%   |
| Dell OptiPlex 780                      | 2        | 0.48%   |
| Dell OptiPlex 755                      | 2        | 0.48%   |
| Dell OptiPlex 745                      | 2        | 0.48%   |
| Dell OptiPlex 7040                     | 2        | 0.48%   |
| Complet MY8313                         | 2        | 0.48%   |
| ASUS UNLOCK INSTALL                    | 2        | 0.48%   |
| ASUS ROG STRIX X570-E GAMING           | 2        | 0.48%   |
| ASUS PRIME X470-PRO                    | 2        | 0.48%   |
| ASUS P5K SE                            | 2        | 0.48%   |
| ASUS M5A78L-M/USB3                     | 2        | 0.48%   |
| ASRock X570 Taichi                     | 2        | 0.48%   |
| ASRock B450 Pro4                       | 2        | 0.48%   |
| ASRock A320M-DVS R4.0                  | 2        | 0.48%   |
| ZOTAC AMD HUDSON-M1                    | 1        | 0.24%   |
| Pegatron Pro 3120 Small Form Factor PC | 1        | 0.24%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.24%   |
| Pegatron KJ379AAR-ABA a6400f           | 1        | 0.24%   |
| Pegatron IPPPV-D3G                     | 1        | 0.24%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.24%   |
| Packard Bell IPOWER X9975              | 1        | 0.24%   |
| OEM_MB FR650AA-ABF s3642fr             | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 27       | 6.41%   |
| Dell OptiPlex           | 23       | 5.46%   |
| ASUS PRIME              | 19       | 4.51%   |
| Lenovo ThinkCentre      | 12       | 2.85%   |
| ASUS All                | 11       | 2.61%   |
| ASUS ROG                | 9        | 2.14%   |
| Gigabyte X570           | 6        | 1.43%   |
| Dell Precision          | 6        | 1.43%   |
| Gigabyte B450M          | 5        | 1.19%   |
| MSI MS-7996             | 4        | 0.95%   |
| MSI MS-7721             | 4        | 0.95%   |
| HP EliteDesk            | 4        | 0.95%   |
| Gigabyte X470           | 4        | 0.95%   |
| Gigabyte TRX40          | 4        | 0.95%   |
| ASUS TUF                | 4        | 0.95%   |
| ASUS Maximus            | 4        | 0.95%   |
| Unknown                 | 4        | 0.95%   |
| HP ProDesk              | 3        | 0.71%   |
| Gigabyte Z390           | 3        | 0.71%   |
| Gigabyte B450           | 3        | 0.71%   |
| Gigabyte A320M-S2H      | 3        | 0.71%   |
| Fujitsu Siemens ESPRIMO | 3        | 0.71%   |
| Fujitsu ESPRIMO         | 3        | 0.71%   |
| Dell PowerEdge          | 3        | 0.71%   |
| ASUS Z170               | 3        | 0.71%   |
| ASRock G41M-VS3         | 3        | 0.71%   |
| Acer Veriton            | 3        | 0.71%   |
| Pegatron Pro            | 2        | 0.48%   |
| MSI MS-7C52             | 2        | 0.48%   |
| MSI MS-7C37             | 2        | 0.48%   |
| MSI MS-7B38             | 2        | 0.48%   |
| MSI MS-7A34             | 2        | 0.48%   |
| MSI MS-7817             | 2        | 0.48%   |
| MSI MS-7596             | 2        | 0.48%   |
| Lenovo ThinkStation     | 2        | 0.48%   |
| Intel DQ77MK            | 2        | 0.48%   |
| Gigabyte Z97X-Gaming    | 2        | 0.48%   |
| Gigabyte P75-D3         | 2        | 0.48%   |
| Gigabyte H61M-DS2       | 2        | 0.48%   |
| Gigabyte GA-78LMT-USB3  | 2        | 0.48%   |
| Gigabyte G31M-ES2L      | 2        | 0.48%   |
| Gigabyte B550M          | 2        | 0.48%   |
| Gigabyte AB350-Gaming   | 2        | 0.48%   |
| Gigabyte A320M-H        | 2        | 0.48%   |
| Fujitsu Siemens CELSIUS | 2        | 0.48%   |
| Foxconn 500B            | 2        | 0.48%   |
| Dell Vostro             | 2        | 0.48%   |
| Dell Inspiron           | 2        | 0.48%   |
| Complet MY8313          | 2        | 0.48%   |
| ASUS UNLOCK             | 2        | 0.48%   |
| ASUS P8H61-M            | 2        | 0.48%   |
| ASUS P5K                | 2        | 0.48%   |
| ASUS M5A78L-M           | 2        | 0.48%   |
| ASRock X570             | 2        | 0.48%   |
| ASRock B450             | 2        | 0.48%   |
| ASRock A320M-DVS        | 2        | 0.48%   |
| ASRock 970              | 2        | 0.48%   |
| Acer Nitro              | 2        | 0.48%   |
| Acer Aspire             | 2        | 0.48%   |
| ZOTAC AMD               | 1        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 53       | 12.59%  |
| 2013 | 37       | 8.79%   |
| 2012 | 33       | 7.84%   |
| 2008 | 33       | 7.84%   |
| 2019 | 32       | 7.6%    |
| 2009 | 27       | 6.41%   |
| 2011 | 25       | 5.94%   |
| 2007 | 25       | 5.94%   |
| 2015 | 24       | 5.7%    |
| 2017 | 23       | 5.46%   |
| 2014 | 23       | 5.46%   |
| 2020 | 22       | 5.23%   |
| 2016 | 22       | 5.23%   |
| 2010 | 22       | 5.23%   |
| 2021 | 11       | 2.61%   |
| 2005 | 4        | 0.95%   |
| 2006 | 3        | 0.71%   |
| 2022 | 1        | 0.24%   |
| 2004 | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 421      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 418      | 99.05%  |
| Enabled  | 4        | 0.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 421      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 99       | 22.97%  |
| 3.01-4.0    | 93       | 21.58%  |
| 16.01-24.0  | 77       | 17.87%  |
| 4.01-8.0    | 63       | 14.62%  |
| 32.01-64.0  | 46       | 10.67%  |
| 1.01-2.0    | 24       | 5.57%   |
| 64.01-256.0 | 19       | 4.41%   |
| 24.01-32.0  | 4        | 0.93%   |
| 2.01-3.0    | 3        | 0.7%    |
| 0.51-1.0    | 3        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 166      | 35.32%  |
| 2.01-3.0    | 107      | 22.77%  |
| 3.01-4.0    | 52       | 11.06%  |
| 0.51-1.0    | 52       | 11.06%  |
| 4.01-8.0    | 46       | 9.79%   |
| 0.01-0.5    | 23       | 4.89%   |
| 8.01-16.0   | 17       | 3.62%   |
| 16.01-24.0  | 3        | 0.64%   |
| 64.01-256.0 | 2        | 0.43%   |
| 32.01-64.0  | 1        | 0.21%   |
| 24.01-32.0  | 1        | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 199      | 45.23%  |
| 2      | 117      | 26.59%  |
| 3      | 65       | 14.77%  |
| 4      | 30       | 6.82%   |
| 5      | 14       | 3.18%   |
| 6      | 4        | 0.91%   |
| 0      | 4        | 0.91%   |
| 9      | 2        | 0.45%   |
| 8      | 2        | 0.45%   |
| 24     | 1        | 0.23%   |
| 14     | 1        | 0.23%   |
| 11     | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 221      | 51.76%  |
| No        | 206      | 48.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 419      | 99.52%  |
| No        | 2        | 0.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 307      | 71.9%   |
| Yes       | 120      | 28.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 350      | 81.78%  |
| Yes       | 78       | 18.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Romania | 421      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Bucharest             | 133      | 29.95%  |
| Cluj-Napoca           | 33       | 7.43%   |
| Timișoara            | 20       | 4.5%    |
| Iasi                  | 19       | 4.28%   |
| Oradea                | 13       | 2.93%   |
| Brasov                | 12       | 2.7%    |
| Târgu Mureş         | 9        | 2.03%   |
| Sibiu                 | 9        | 2.03%   |
| Arad                  | 9        | 2.03%   |
| Baia Mare             | 8        | 1.8%    |
| Piatra Neamţ         | 7        | 1.58%   |
| Galati                | 7        | 1.58%   |
| Craiova               | 7        | 1.58%   |
| Popesti-Leordeni      | 6        | 1.35%   |
| Constanța            | 6        | 1.35%   |
| Zalău                | 5        | 1.13%   |
| Targoviste            | 5        | 1.13%   |
| Satu Mare             | 5        | 1.13%   |
| Ploieşti             | 4        | 0.9%    |
| Braila                | 4        | 0.9%    |
| Bacau                 | 4        | 0.9%    |
| Voluntari             | 3        | 0.68%   |
| Târgu Jiu            | 3        | 0.68%   |
| Sfantu Gheorghe       | 3        | 0.68%   |
| Reşiţa              | 3        | 0.68%   |
| Râmnicu Vâlcea      | 3        | 0.68%   |
| Piteşti              | 3        | 0.68%   |
| Otopeni               | 3        | 0.68%   |
| Miercurea-Ciuc        | 3        | 0.68%   |
| Focşani              | 3        | 0.68%   |
| Botosani              | 3        | 0.68%   |
| Alexandria            | 3        | 0.68%   |
| Alba Iulia            | 3        | 0.68%   |
| Tulcea                | 2        | 0.45%   |
| Sovata                | 2        | 0.45%   |
| Mogosoaia             | 2        | 0.45%   |
| Mediaş               | 2        | 0.45%   |
| Giurgiu               | 2        | 0.45%   |
| Floresti              | 2        | 0.45%   |
| Fagaras               | 2        | 0.45%   |
| Drobeta-Turnu Severin | 2        | 0.45%   |
| Codlea                | 2        | 0.45%   |
| Beiuș                | 2        | 0.45%   |
| Bârlad               | 2        | 0.45%   |
| Vintila Voda          | 1        | 0.23%   |
| Videle                | 1        | 0.23%   |
| Valenii de Munte      | 1        | 0.23%   |
| Urziceni              | 1        | 0.23%   |
| Ungheni               | 1        | 0.23%   |
| Turulung              | 1        | 0.23%   |
| Tureni                | 1        | 0.23%   |
| Turda                 | 1        | 0.23%   |
| Tortoman              | 1        | 0.23%   |
| TimiÈ™oara         | 1        | 0.23%   |
| Tecuci                | 1        | 0.23%   |
| Tatarusi              | 1        | 0.23%   |
| Tartasesti            | 1        | 0.23%   |
| Târnăveni           | 1        | 0.23%   |
| Targu Frumos          | 1        | 0.23%   |
| Stefanesti            | 1        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 164      | 252    | 21.98%  |
| Seagate                   | 143      | 235    | 19.17%  |
| Kingston                  | 101      | 146    | 13.54%  |
| Samsung Electronics       | 99       | 139    | 13.27%  |
| Toshiba                   | 31       | 38     | 4.16%   |
| A-DATA Technology         | 30       | 45     | 4.02%   |
| Hitachi                   | 23       | 33     | 3.08%   |
| Intel                     | 14       | 16     | 1.88%   |
| Maxtor                    | 12       | 18     | 1.61%   |
| Crucial                   | 11       | 12     | 1.47%   |
| HGST                      | 10       | 19     | 1.34%   |
| SanDisk                   | 9        | 14     | 1.21%   |
| Unknown                   | 8        | 11     | 1.07%   |
| Patriot                   | 8        | 10     | 1.07%   |
| Phison                    | 6        | 8      | 0.8%    |
| OCZ                       | 6        | 11     | 0.8%    |
| XPG                       | 5        | 8      | 0.67%   |
| Transcend                 | 5        | 7      | 0.67%   |
| Kingmax                   | 5        | 6      | 0.67%   |
| Hewlett-Packard           | 5        | 6      | 0.67%   |
| SPCC                      | 4        | 5      | 0.54%   |
| Team                      | 3        | 3      | 0.4%    |
| SK hynix                  | 3        | 3      | 0.4%    |
| Plextor                   | 3        | 3      | 0.4%    |
| GOODRAM                   | 3        | 3      | 0.4%    |
| China                     | 3        | 3      | 0.4%    |
| Verbatim                  | 2        | 2      | 0.27%   |
| Silicon Motion            | 2        | 2      | 0.27%   |
| Realtek Semiconductor     | 2        | 2      | 0.27%   |
| Micron/Crucial Technology | 2        | 3      | 0.27%   |
| LaCie                     | 2        | 5      | 0.27%   |
| Gigabyte Technology       | 2        | 2      | 0.27%   |
| Fujitsu                   | 2        | 2      | 0.27%   |
| Emtec                     | 2        | 2      | 0.27%   |
| Corsair                   | 2        | 3      | 0.27%   |
| OCZ-VERTEX3               | 1        | 1      | 0.13%   |
| Lite-On                   | 1        | 1      | 0.13%   |
| Kston                     | 1        | 4      | 0.13%   |
| KIOXIA                    | 1        | 1      | 0.13%   |
| KingFast                  | 1        | 1      | 0.13%   |
| KingDian                  | 1        | 1      | 0.13%   |
| Intenso                   | 1        | 1      | 0.13%   |
| ExcelStor                 | 1        | 1      | 0.13%   |
| ELECOM                    | 1        | 1      | 0.13%   |
| ASMT109x                  | 1        | 1      | 0.13%   |
| ASMT                      | 1        | 1      | 0.13%   |
| Apricorn                  | 1        | 1      | 0.13%   |
| Apacer                    | 1        | 2      | 0.13%   |
| AMD                       | 1        | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 33       | 3.91%   |
| Seagate ST1000DM010-2EP102 1TB   | 21       | 2.49%   |
| Kingston SA400S37120G 120GB SSD  | 16       | 1.9%    |
| Kingston SV300S37A120G 120GB SSD | 15       | 1.78%   |
| WDC WD10EZEX-08WN4A0 1TB         | 12       | 1.42%   |
| Seagate ST500DM002-1BD142 500GB  | 12       | 1.42%   |
| Samsung SSD 850 EVO 250GB        | 12       | 1.42%   |
| Toshiba DT01ACA050 500GB         | 11       | 1.3%    |
| Samsung SSD 860 EVO 500GB        | 11       | 1.3%    |
| Kingston SA400S37480G 480GB SSD  | 11       | 1.3%    |
| A-DATA SU650 240GB SSD           | 8        | 0.95%   |
| Patriot Burst 120GB SSD          | 6        | 0.71%   |
| WDC WD5000AAKX-001CA0 500GB      | 5        | 0.59%   |
| WDC WD5000AADS-00S9B0 500GB      | 5        | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB         | 5        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB   | 5        | 0.59%   |
| Samsung SSD 860 EVO 250GB        | 5        | 0.59%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 4        | 0.47%   |
| WDC WD10EADS-00L5B1 1TB          | 4        | 0.47%   |
| Unknown NVMe SSD Drive 512GB     | 4        | 0.47%   |
| Toshiba DT01ACA100 1TB           | 4        | 0.47%   |
| Seagate ST3500418AS 500GB        | 4        | 0.47%   |
| Seagate ST3250318AS 250GB        | 4        | 0.47%   |
| Seagate ST1000DM003-1SB102 1TB   | 4        | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB   | 4        | 0.47%   |
| Seagate Expansion Desk 4TB       | 4        | 0.47%   |
| Samsung SSD 860 QVO 1TB          | 4        | 0.47%   |
| Samsung SSD 850 EVO 500GB        | 4        | 0.47%   |
| Samsung NVMe SSD Drive 500GB     | 4        | 0.47%   |
| Samsung NVMe SSD Drive 250GB     | 4        | 0.47%   |
| Kingston SHFS37A120G 120GB SSD   | 4        | 0.47%   |
| A-DATA SU650 480GB SSD           | 4        | 0.47%   |
| A-DATA SU650 120GB SSD           | 4        | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 3        | 0.36%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 3        | 0.36%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 3        | 0.36%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 0.36%   |
| WDC WD10PURX-64E5EY0 1TB         | 3        | 0.36%   |
| WDC WD10EZEX-60WN4A1 1TB         | 3        | 0.36%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 0.36%   |
| WDC WD10EZEX-21WN4A0 1TB         | 3        | 0.36%   |
| WDC WD10EZEX-00WN4A0 1TB         | 3        | 0.36%   |
| Unknown SD/MMC/MS PRO 128GB      | 3        | 0.36%   |
| Toshiba DT01ACA300 3TB           | 3        | 0.36%   |
| Seagate ST3500320AS 500GB        | 3        | 0.36%   |
| Seagate ST3500312CS 500GB        | 3        | 0.36%   |
| Seagate ST250DM000-1BD141 250GB  | 3        | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.36%   |
| Seagate ST1000DM003-1SB10C 1TB   | 3        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.36%   |
| Seagate Expansion 500GB          | 3        | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.36%   |
| Samsung SSD 960 EVO 250GB        | 3        | 0.36%   |
| Samsung SSD 860 EVO 1TB          | 3        | 0.36%   |
| Samsung SSD 850 PRO 512GB        | 3        | 0.36%   |
| Samsung NVMe SSD Drive 512GB     | 3        | 0.36%   |
| Phison NVMe SSD Drive 1TB        | 3        | 0.36%   |
| OCZ TRION100 120GB SSD           | 3        | 0.36%   |
| Maxtor STM3250310AS 250GB        | 3        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 156      | 241    | 38.24%  |
| Seagate             | 142      | 234    | 34.8%   |
| Toshiba             | 30       | 37     | 7.35%   |
| Samsung Electronics | 24       | 28     | 5.88%   |
| Hitachi             | 23       | 33     | 5.64%   |
| Maxtor              | 12       | 18     | 2.94%   |
| HGST                | 10       | 19     | 2.45%   |
| Unknown             | 3        | 3      | 0.74%   |
| Fujitsu             | 2        | 2      | 0.49%   |
| LaCie               | 1        | 4      | 0.25%   |
| Intenso             | 1        | 1      | 0.25%   |
| Hewlett-Packard     | 1        | 1      | 0.25%   |
| ExcelStor           | 1        | 1      | 0.25%   |
| ASMT109x            | 1        | 1      | 0.25%   |
| ASMT                | 1        | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 91       | 128    | 35.41%  |
| Samsung Electronics | 53       | 76     | 20.62%  |
| A-DATA Technology   | 29       | 44     | 11.28%  |
| Intel               | 9        | 11     | 3.5%    |
| Crucial             | 9        | 10     | 3.5%    |
| Patriot             | 8        | 10     | 3.11%   |
| WDC                 | 7        | 9      | 2.72%   |
| SanDisk             | 6        | 10     | 2.33%   |
| OCZ                 | 6        | 11     | 2.33%   |
| Kingmax             | 5        | 6      | 1.95%   |
| Transcend           | 4        | 6      | 1.56%   |
| SPCC                | 4        | 5      | 1.56%   |
| Team                | 3        | 3      | 1.17%   |
| Goodram             | 3        | 3      | 1.17%   |
| China               | 3        | 3      | 1.17%   |
| Verbatim            | 2        | 2      | 0.78%   |
| SK hynix            | 2        | 2      | 0.78%   |
| Hewlett-Packard     | 2        | 2      | 0.78%   |
| Gigabyte Technology | 2        | 2      | 0.78%   |
| Emtec               | 2        | 2      | 0.78%   |
| Toshiba             | 1        | 1      | 0.39%   |
| OCZ-VERTEX3         | 1        | 1      | 0.39%   |
| Kston               | 1        | 4      | 0.39%   |
| KingDian            | 1        | 1      | 0.39%   |
| Corsair             | 1        | 1      | 0.39%   |
| Apacer              | 1        | 2      | 0.39%   |
| AMD                 | 1        | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 315      | 624    | 50.97%  |
| SSD     | 223      | 356    | 36.08%  |
| NVMe    | 75       | 110    | 12.14%  |
| Unknown | 4        | 4      | 0.65%   |
| MMC     | 1        | 1      | 0.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 395      | 956    | 80.78%  |
| NVMe | 75       | 110    | 15.34%  |
| SAS  | 18       | 28     | 3.68%   |
| MMC  | 1        | 1      | 0.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 329      | 616    | 60.26%  |
| 0.51-1.0   | 138      | 205    | 25.27%  |
| 1.01-2.0   | 39       | 56     | 7.14%   |
| 3.01-4.0   | 18       | 33     | 3.3%    |
| 2.01-3.0   | 11       | 33     | 2.01%   |
| 4.01-10.0  | 9        | 33     | 1.65%   |
| 10.01-20.0 | 2        | 4      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 111      | 24.08%  |
| 251-500        | 72       | 15.62%  |
| 501-1000       | 68       | 14.75%  |
| 1-20           | 45       | 9.76%   |
| 51-100         | 41       | 8.89%   |
| Unknown        | 35       | 7.59%   |
| 1001-2000      | 32       | 6.94%   |
| 21-50          | 24       | 5.21%   |
| More than 3000 | 18       | 3.9%    |
| 2001-3000      | 15       | 3.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 191      | 40.55%  |
| 21-50          | 68       | 14.44%  |
| 51-100         | 45       | 9.55%   |
| 101-250        | 40       | 8.49%   |
| Unknown        | 35       | 7.43%   |
| 251-500        | 31       | 6.58%   |
| 501-1000       | 31       | 6.58%   |
| 1001-2000      | 16       | 3.4%    |
| More than 3000 | 10       | 2.12%   |
| 2001-3000      | 4        | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB           | 3        | 3      | 3.37%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 3        | 6      | 3.37%   |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 2.25%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 2.25%   |
| Seagate ST3500320AS 500GB             | 2        | 3      | 2.25%   |
| Seagate ST3500312CS 500GB             | 2        | 2      | 2.25%   |
| Seagate ST3250318AS 250GB             | 2        | 3      | 2.25%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 2.25%   |
| OCZ ARC100 240GB SSD                  | 2        | 2      | 2.25%   |
| Maxtor STM3250310AS 250GB             | 2        | 3      | 2.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1        | 1      | 1.12%   |
| WDC WD400EB-00CPF0 40GB               | 1        | 1      | 1.12%   |
| WDC WD400BD-08JMC0 40GB               | 1        | 1      | 1.12%   |
| WDC WD3200AVVS-63L2B0 320GB           | 1        | 1      | 1.12%   |
| WDC WD3200AVBS-63TAA0 320GB           | 1        | 1      | 1.12%   |
| WDC WD3200AAKS-75L9A0 320GB           | 1        | 1      | 1.12%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 10     | 1.12%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 1      | 1.12%   |
| WDC WD2500JS-60MHB5 250GB             | 1        | 3      | 1.12%   |
| WDC WD2500JB-00REA0 250GB             | 1        | 1      | 1.12%   |
| WDC WD2500BEKT-75PVMT1 250GB          | 1        | 1      | 1.12%   |
| WDC WD2000JD-22HBC0 200GB             | 1        | 1      | 1.12%   |
| WDC WD1600AAJS-07M0A0 160GB           | 1        | 1      | 1.12%   |
| WDC WD1600AAJS-00PSA0 160GB           | 1        | 2      | 1.12%   |
| WDC WD15EARS-00MVWB0 1TB              | 1        | 1      | 1.12%   |
| WDC WD1502FAEX-007BA0 1TB             | 1        | 1      | 1.12%   |
| WDC WD10EZEX-21WN4A0 1TB              | 1        | 1      | 1.12%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.12%   |
| WDC WD10EAVS-22D7B0 1TB               | 1        | 1      | 1.12%   |
| WDC WD10EARS-22Y5B1 1TB               | 1        | 1      | 1.12%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 1      | 1.12%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 1.12%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.12%   |
| Seagate STM3250318AS 250GB            | 1        | 2      | 1.12%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 1      | 1.12%   |
| Seagate ST500DM005 HD502HJ 500GB      | 1        | 2      | 1.12%   |
| Seagate ST3750528AS 752GB             | 1        | 1      | 1.12%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 1.12%   |
| Seagate ST340015A 40GB                | 1        | 2      | 1.12%   |
| Seagate ST3250410AS 250GB             | 1        | 1      | 1.12%   |
| Seagate ST3250312AS 250GB             | 1        | 1      | 1.12%   |
| Seagate ST3000DM001-1ER166 3TB        | 1        | 1      | 1.12%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 1.12%   |
| Seagate ST2000DM006-2DM164 2TB        | 1        | 1      | 1.12%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 1.12%   |
| Seagate ST1000DX001-1NS162 1TB        | 1        | 1      | 1.12%   |
| Seagate ST1000DX001-1CM162 1TB        | 1        | 1      | 1.12%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 1      | 1.12%   |
| Samsung Electronics SSD 850 EVO 250GB | 1        | 1      | 1.12%   |
| Samsung Electronics SP2004C 200GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HM160HI 160GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 2      | 1.12%   |
| Samsung Electronics HD502HJ 500GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HD502HI 500GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HD322HJ 320GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HD251HJ 249GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HD161HJ 160GB     | 1        | 1      | 1.12%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 1.12%   |
| Plextor PX-512M8PeG 512GB             | 1        | 1      | 1.12%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 45     | 33.33%  |
| Seagate             | 24       | 31     | 28.57%  |
| Samsung Electronics | 10       | 11     | 11.9%   |
| Maxtor              | 5        | 7      | 5.95%   |
| Hitachi             | 5        | 5      | 5.95%   |
| OCZ                 | 2        | 2      | 2.38%   |
| Kingston            | 2        | 2      | 2.38%   |
| Intel               | 2        | 2      | 2.38%   |
| Toshiba             | 1        | 1      | 1.19%   |
| Plextor             | 1        | 1      | 1.19%   |
| HGST                | 1        | 1      | 1.19%   |
| Hewlett-Packard     | 1        | 1      | 1.19%   |
| Apacer              | 1        | 2      | 1.19%   |
| A-DATA Technology   | 1        | 1      | 1.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 44     | 37.5%   |
| Seagate             | 24       | 31     | 33.33%  |
| Samsung Electronics | 9        | 10     | 12.5%   |
| Maxtor              | 5        | 7      | 6.94%   |
| Hitachi             | 5        | 5      | 6.94%   |
| Toshiba             | 1        | 1      | 1.39%   |
| HGST                | 1        | 1      | 1.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 63       | 99     | 84%     |
| SSD  | 11       | 12     | 14.67%  |
| NVMe | 1        | 1      | 1.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST3160215A 160GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 250      | 623    | 52.52%  |
| Works    | 156      | 359    | 32.77%  |
| Malfunc  | 69       | 112    | 14.5%   |
| Failed   | 1        | 1      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 287      | 51.34%  |
| AMD                           | 121      | 21.65%  |
| Samsung Electronics           | 32       | 5.72%   |
| ASMedia Technology            | 16       | 2.86%   |
| Marvell Technology Group      | 15       | 2.68%   |
| Kingston Technology Company   | 15       | 2.68%   |
| JMicron Technology            | 13       | 2.33%   |
| Nvidia                        | 10       | 1.79%   |
| ADATA Technology              | 8        | 1.43%   |
| Phison Electronics            | 7        | 1.25%   |
| Silicon Motion                | 6        | 1.07%   |
| SanDisk                       | 5        | 0.89%   |
| Realtek Semiconductor         | 4        | 0.72%   |
| Lite-On Technology            | 4        | 0.72%   |
| VIA Technologies              | 3        | 0.54%   |
| Silicon Image                 | 3        | 0.54%   |
| Micron/Crucial Technology     | 3        | 0.54%   |
| LSI Logic / Symbios Logic     | 2        | 0.36%   |
| SK hynix                      | 1        | 0.18%   |
| Seagate Technology            | 1        | 0.18%   |
| KIOXIA                        | 1        | 0.18%   |
| Integrated Technology Express | 1        | 0.18%   |
| Broadcom / LSI                | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 77       | 10.52%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31       | 4.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 27       | 3.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 27       | 3.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 25       | 3.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 25       | 3.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20       | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19       | 2.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17       | 2.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 2.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16       | 2.19%   |
| AMD FCH SATA Controller D                                                               | 16       | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 2.05%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 15       | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 1.91%   |
| Intel SATA Controller [RAID mode]                                                       | 13       | 1.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 13       | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 1.78%   |
| Kingston Company A2000 NVMe SSD                                                         | 12       | 1.64%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 12       | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 11       | 1.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 8        | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.96%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.96%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 7        | 0.96%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 7        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 7        | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 0.82%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.82%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 6        | 0.82%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 6        | 0.82%   |
| Nvidia MCP61 IDE                                                                        | 5        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.68%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.55%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 0.55%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 0.55%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.55%   |
| AMD FCH IDE Controller                                                                  | 4        | 0.55%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.41%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.41%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 3        | 0.41%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 0.41%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3        | 0.41%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.41%   |
| JMicron JMB362 SATA Controller                                                          | 3        | 0.41%   |
| Intel SSD 660P Series                                                                   | 3        | 0.41%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.41%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.41%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 317      | 57.01%  |
| IDE  | 131      | 23.56%  |
| NVMe | 80       | 14.39%  |
| RAID | 24       | 4.32%   |
| SAS  | 4        | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 290      | 68.88%  |
| AMD    | 131      | 31.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 9        | 2.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 8        | 1.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 8        | 1.89%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 8        | 1.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 7        | 1.65%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 6        | 1.42%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz           | 6        | 1.42%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 5        | 1.18%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 5        | 1.18%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 5        | 1.18%   |
| Intel Core 2 CPU 6400 @ 2.13GHz                | 5        | 1.18%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 5        | 1.18%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 5        | 1.18%   |
| AMD Ryzen 5 3600 6-Core Processor              | 5        | 1.18%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 5        | 1.18%   |
| Intel Pentium CPU G4560 @ 3.50GHz              | 4        | 0.95%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 4        | 0.95%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 4        | 0.95%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 4        | 0.95%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 4        | 0.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 4        | 0.95%   |
| Intel Core i3-9100F CPU @ 3.60GHz              | 4        | 0.95%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 4        | 0.95%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 4        | 0.95%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz           | 4        | 0.95%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 4        | 0.95%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 4        | 0.95%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 4        | 0.95%   |
| AMD A4-5300 APU with Radeon HD Graphics        | 4        | 0.95%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 3        | 0.71%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 3        | 0.71%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 3        | 0.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 3        | 0.71%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 3        | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 3        | 0.71%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 3        | 0.71%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 3        | 0.71%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 3        | 0.71%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 3        | 0.71%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3        | 0.71%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 3        | 0.71%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz           | 3        | 0.71%   |
| Intel Celeron CPU J3455 @ 1.50GHz              | 3        | 0.71%   |
| Intel Celeron CPU J1800 @ 2.41GHz              | 3        | 0.71%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 3        | 0.71%   |
| AMD Ryzen 5 1600X Six-Core Processor           | 3        | 0.71%   |
| AMD FX-6300 Six-Core Processor                 | 3        | 0.71%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz         | 2        | 0.47%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 2        | 0.47%   |
| Intel Pentium D CPU 3.00GHz                    | 2        | 0.47%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 2        | 0.47%   |
| Intel Pentium CPU G3220 @ 3.00GHz              | 2        | 0.47%   |
| Intel Pentium 4 CPU 3.00GHz                    | 2        | 0.47%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 2        | 0.47%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 0.47%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 0.47%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 2        | 0.47%   |
| Intel Core i5-8500 CPU @ 3.00GHz               | 2        | 0.47%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 2        | 0.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 69       | 16.39%  |
| Intel Core i7           | 46       | 10.93%  |
| Intel Core i3           | 37       | 8.79%   |
| Intel Core 2 Duo        | 34       | 8.08%   |
| AMD Ryzen 5             | 28       | 6.65%   |
| AMD Ryzen 7             | 21       | 4.99%   |
| Intel Pentium           | 17       | 4.04%   |
| Intel Core 2 Quad       | 16       | 3.8%    |
| Intel Celeron           | 16       | 3.8%    |
| Intel Xeon              | 14       | 3.33%   |
| AMD Ryzen 3             | 12       | 2.85%   |
| Intel Pentium Dual-Core | 11       | 2.61%   |
| AMD FX                  | 10       | 2.38%   |
| AMD A8                  | 8        | 1.9%    |
| AMD A4                  | 8        | 1.9%    |
| Intel Core i9           | 7        | 1.66%   |
| Intel Core 2            | 6        | 1.43%   |
| AMD Ryzen 9             | 6        | 1.43%   |
| AMD Phenom II X4        | 6        | 1.43%   |
| AMD Sempron             | 4        | 0.95%   |
| AMD Ryzen Threadripper  | 4        | 0.95%   |
| Other                   | 3        | 0.71%   |
| Intel Pentium Dual      | 3        | 0.71%   |
| Intel Atom              | 3        | 0.71%   |
| AMD Athlon II X4        | 3        | 0.71%   |
| Intel Pentium Gold      | 2        | 0.48%   |
| Intel Pentium D         | 2        | 0.48%   |
| Intel Pentium 4         | 2        | 0.48%   |
| Intel Genuine           | 2        | 0.48%   |
| AMD Phenom II X3        | 2        | 0.48%   |
| AMD Phenom              | 2        | 0.48%   |
| AMD Athlon X4           | 2        | 0.48%   |
| AMD Athlon II X3        | 2        | 0.48%   |
| AMD Athlon 64 X2        | 2        | 0.48%   |
| AMD Athlon              | 2        | 0.48%   |
| Intel Core 2 Extreme    | 1        | 0.24%   |
| AMD Ryzen 7 PRO         | 1        | 0.24%   |
| AMD Ryzen 5 PRO         | 1        | 0.24%   |
| AMD Ryzen 3 PRO         | 1        | 0.24%   |
| AMD Phenom II X2        | 1        | 0.24%   |
| AMD E                   | 1        | 0.24%   |
| AMD Athlon II X2        | 1        | 0.24%   |
| AMD Athlon Dual Core    | 1        | 0.24%   |
| AMD Athlon 64           | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 168      | 39.9%   |
| 2      | 133      | 31.59%  |
| 6      | 41       | 9.74%   |
| 8      | 33       | 7.84%   |
| 1      | 17       | 4.04%   |
| 12     | 9        | 2.14%   |
| 3      | 9        | 2.14%   |
| 32     | 3        | 0.71%   |
| 16     | 3        | 0.71%   |
| 10     | 3        | 0.71%   |
| 24     | 1        | 0.24%   |
| 20     | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 415      | 98.57%  |
| 2      | 6        | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 231      | 54.87%  |
| 2      | 190      | 45.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 411      | 97.16%  |
| Unknown        | 12       | 2.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 76       | 17.59%  |
| 0x306c3    | 36       | 8.33%   |
| 0x1067a    | 32       | 7.41%   |
| 0x206a7    | 28       | 6.48%   |
| 0x306a9    | 25       | 5.79%   |
| 0x906ea    | 17       | 3.94%   |
| 0x906e9    | 17       | 3.94%   |
| 0x506e3    | 17       | 3.94%   |
| 0x10676    | 13       | 3.01%   |
| 0x010000c8 | 13       | 3.01%   |
| 0x08701013 | 10       | 2.31%   |
| 0x6fb      | 9        | 2.08%   |
| 0x08701021 | 8        | 1.85%   |
| 0x0800820d | 8        | 1.85%   |
| 0x06001119 | 8        | 1.85%   |
| 0x6fd      | 7        | 1.62%   |
| 0x08101016 | 7        | 1.62%   |
| 0x906eb    | 6        | 1.39%   |
| 0x06000852 | 6        | 1.39%   |
| 0x0810100b | 5        | 1.16%   |
| 0x6f2      | 4        | 0.93%   |
| 0x506c9    | 4        | 0.93%   |
| 0x08001137 | 4        | 0.93%   |
| 0xf62      | 3        | 0.69%   |
| 0xa0655    | 3        | 0.69%   |
| 0xa0653    | 3        | 0.69%   |
| 0x106e5    | 3        | 0.69%   |
| 0x0a201009 | 3        | 0.69%   |
| 0x906ed    | 2        | 0.46%   |
| 0x90672    | 2        | 0.46%   |
| 0x6f6      | 2        | 0.46%   |
| 0x406c4    | 2        | 0.46%   |
| 0x30678    | 2        | 0.46%   |
| 0x20655    | 2        | 0.46%   |
| 0x106a5    | 2        | 0.46%   |
| 0x10677    | 2        | 0.46%   |
| 0x0a201016 | 2        | 0.46%   |
| 0x08600106 | 2        | 0.46%   |
| 0x08108109 | 2        | 0.46%   |
| 0x08008206 | 2        | 0.46%   |
| 0x08001138 | 2        | 0.46%   |
| 0x08001129 | 2        | 0.46%   |
| 0x01000083 | 2        | 0.46%   |
| 0xf49      | 1        | 0.23%   |
| 0x906ec    | 1        | 0.23%   |
| 0x706a8    | 1        | 0.23%   |
| 0x706a1    | 1        | 0.23%   |
| 0x6f7      | 1        | 0.23%   |
| 0x506e1    | 1        | 0.23%   |
| 0x406f1    | 1        | 0.23%   |
| 0x306f2    | 1        | 0.23%   |
| 0x306f1    | 1        | 0.23%   |
| 0x306e4    | 1        | 0.23%   |
| 0x30679    | 1        | 0.23%   |
| 0x106ca    | 1        | 0.23%   |
| 0x0a50000d | 1        | 0.23%   |
| 0x0a50000c | 1        | 0.23%   |
| 0x08600103 | 1        | 0.23%   |
| 0x0800820b | 1        | 0.23%   |
| 0x08001126 | 1        | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 51       | 12.06%  |
| Penryn           | 49       | 11.58%  |
| Haswell          | 45       | 10.64%  |
| SandyBridge      | 30       | 7.09%   |
| IvyBridge        | 30       | 7.09%   |
| Zen 2            | 28       | 6.62%   |
| Core             | 26       | 6.15%   |
| Zen              | 23       | 5.44%   |
| Skylake          | 21       | 4.96%   |
| Piledriver       | 21       | 4.96%   |
| K10              | 21       | 4.96%   |
| Zen+             | 17       | 4.02%   |
| Zen 3            | 8        | 1.89%   |
| CometLake        | 8        | 1.89%   |
| K8 Hammer        | 7        | 1.65%   |
| Silvermont       | 6        | 1.42%   |
| Nehalem          | 6        | 1.42%   |
| NetBurst         | 5        | 1.18%   |
| Goldmont         | 4        | 0.95%   |
| Westmere         | 3        | 0.71%   |
| K10 Llano        | 2        | 0.47%   |
| Goldmont plus    | 2        | 0.47%   |
| Excavator        | 2        | 0.47%   |
| Alderlake Hybrid | 2        | 0.47%   |
| Steamroller      | 1        | 0.24%   |
| Bulldozer        | 1        | 0.24%   |
| Broadwell        | 1        | 0.24%   |
| Bonnell          | 1        | 0.24%   |
| Bobcat           | 1        | 0.24%   |
| Unknown          | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 171      | 38.34%  |
| Intel             | 149      | 33.41%  |
| AMD               | 124      | 27.8%   |
| ASPEED Technology | 2        | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 27       | 5.95%   |
| Nvidia GK208B [GeForce GT 710]                                              | 19       | 4.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 4.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18       | 3.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 14       | 3.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 12       | 2.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 12       | 2.64%   |
| Intel HD Graphics 630                                                       | 11       | 2.42%   |
| Intel HD Graphics 530                                                       | 11       | 2.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 1.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 1.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 1.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.54%   |
| Nvidia GF108 [GeForce GT 730]                                               | 7        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 5        | 1.1%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.1%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 1.1%    |
| Nvidia GK107 [GeForce GT 740]                                               | 5        | 1.1%    |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 1.1%    |
| Nvidia G96C [GeForce 9500 GT]                                               | 5        | 1.1%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 5        | 1.1%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 5        | 1.1%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 1.1%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 0.88%   |
| Nvidia G92 [GeForce GTS 250]                                                | 4        | 0.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4        | 0.88%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 4        | 0.88%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.66%   |
| Nvidia GF106GL [Quadro 2000]                                                | 3        | 0.66%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 3        | 0.66%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 3        | 0.66%   |
| Intel HD Graphics 500                                                       | 3        | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.66%   |
| Intel 82Q33 Express Integrated Graphics Controller                          | 3        | 0.66%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 0.66%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 0.66%   |
| AMD Renoir                                                                  | 3        | 0.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 0.66%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 0.66%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 0.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.66%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.66%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.44%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                       | 2        | 0.44%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.44%   |
| Nvidia GT216 [GeForce 210]                                                  | 2        | 0.44%   |
| Nvidia GT215 [GeForce GT 240]                                               | 2        | 0.44%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.44%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.44%   |
| Nvidia GK106GL [Quadro K4000]                                               | 2        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 160      | 37.83%  |
| 1 x Intel      | 129      | 30.5%   |
| 1 x AMD        | 115      | 27.19%  |
| Intel + Nvidia | 8        | 1.89%   |
| 2 x AMD        | 5        | 1.18%   |
| AMD + Nvidia   | 2        | 0.47%   |
| 2 x Nvidia     | 1        | 0.24%   |
| Intel + AMD    | 1        | 0.24%   |
| 1 x ASPEED     | 1        | 0.24%   |
| AMD + ASPEED   | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 322      | 75.59%  |
| Proprietary | 90       | 21.13%  |
| Unknown     | 14       | 3.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 177      | 40.78%  |
| 1.01-2.0   | 60       | 13.82%  |
| 0.51-1.0   | 59       | 13.59%  |
| 0.01-0.5   | 48       | 11.06%  |
| 7.01-8.0   | 35       | 8.06%   |
| 3.01-4.0   | 35       | 8.06%   |
| 5.01-6.0   | 10       | 2.3%    |
| 2.01-3.0   | 5        | 1.15%   |
| 8.01-16.0  | 4        | 0.92%   |
| 16.01-24.0 | 1        | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 76       | 17.39%  |
| Dell                    | 60       | 13.73%  |
| Goldstar                | 51       | 11.67%  |
| Philips                 | 48       | 10.98%  |
| BenQ                    | 28       | 6.41%   |
| AOC                     | 20       | 4.58%   |
| Hewlett-Packard         | 18       | 4.12%   |
| Ancor Communications    | 17       | 3.89%   |
| Acer                    | 17       | 3.89%   |
| Fujitsu Siemens         | 15       | 3.43%   |
| LG Electronics          | 9        | 2.06%   |
| Unknown                 | 8        | 1.83%   |
| Lenovo                  | 8        | 1.83%   |
| KTC                     | 5        | 1.14%   |
| ASUSTek Computer        | 5        | 1.14%   |
| Vestel Elektronik       | 4        | 0.92%   |
| Toshiba                 | 4        | 0.92%   |
| Panasonic               | 4        | 0.92%   |
| Eizo                    | 4        | 0.92%   |
| ViewSonic               | 3        | 0.69%   |
| Sony                    | 3        | 0.69%   |
| Lenovo Group Limited    | 3        | 0.69%   |
| Iiyama                  | 3        | 0.69%   |
| FUS                     | 2        | 0.46%   |
| Belinea                 | 2        | 0.46%   |
| ___                     | 1        | 0.23%   |
| Yakumo                  | 1        | 0.23%   |
| Xerox                   | 1        | 0.23%   |
| VIE                     | 1        | 0.23%   |
| Unknown (XXX)           | 1        | 0.23%   |
| RTD                     | 1        | 0.23%   |
| OEM                     | 1        | 0.23%   |
| NAD                     | 1        | 0.23%   |
| MSI                     | 1        | 0.23%   |
| Idek Iiyama             | 1        | 0.23%   |
| IBM                     | 1        | 0.23%   |
| Hyundai ImageQuest      | 1        | 0.23%   |
| HUAWEI                  | 1        | 0.23%   |
| Hitachi                 | 1        | 0.23%   |
| HannStar                | 1        | 0.23%   |
| CTV                     | 1        | 0.23%   |
| CTT                     | 1        | 0.23%   |
| Chi Mei Optoelectronics | 1        | 0.23%   |
| Balance                 | 1        | 0.23%   |
| AGO                     | 1        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 6        | 1.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 6        | 1.3%    |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6        | 1.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4        | 0.87%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 4        | 0.87%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.87%   |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                  | 4        | 0.87%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 4        | 0.87%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 3        | 0.65%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 3        | 0.65%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 0.65%   |
| Philips 220E PHLC02E 1920x1080 476x268mm 21.5-inch                     | 3        | 0.65%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 3        | 0.65%   |
| Goldstar W1941 GSM4B91 1360x768 406x229mm 18.4-inch                    | 3        | 0.65%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 3        | 0.65%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 3        | 0.65%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                      | 3        | 0.65%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 0.65%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                    | 3        | 0.65%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                      | 3        | 0.65%   |
| AOC Q2770 AOC2770 2560x1440 597x336mm 27.0-inch                        | 3        | 0.65%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 2        | 0.43%   |
| Unknown LCD Monitor SAMSUNG                                            | 2        | 0.43%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch      | 2        | 0.43%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 340x270mm 17.1-inch   | 2        | 0.43%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 2        | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.43%   |
| Samsung Electronics LCD Monitor SAM07BF 1920x1080 886x498mm 40.0-inch  | 2        | 0.43%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 2        | 0.43%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch      | 2        | 0.43%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 2        | 0.43%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 2        | 0.43%   |
| LG Electronics LCD Monitor M2380D 1920x1080                            | 2        | 0.43%   |
| LG Electronics LCD Monitor LG TV                                       | 2        | 0.43%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                   | 2        | 0.43%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 476x268mm 21.5-inch               | 2        | 0.43%   |
| Hewlett-Packard S2231 HWP2905 1920x1080 477x268mm 21.5-inch            | 2        | 0.43%   |
| Hewlett-Packard LA1905 HWP2844 1440x900 408x255mm 18.9-inch            | 2        | 0.43%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 2        | 0.43%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 2        | 0.43%   |
| Fujitsu Siemens B22T-7 LED PG FUS0829 1920x1080 477x268mm 21.5-inch    | 2        | 0.43%   |
| Fujitsu Siemens B22T-7 LED PG FUS0828 1920x1080 477x268mm 21.5-inch    | 2        | 0.43%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                  | 2        | 0.43%   |
| Dell LCD Monitor DELF112 1920x1080 530x300mm 24.0-inch                 | 2        | 0.43%   |
| Dell 2209WA DELF010 1680x1050 474x296mm 22.0-inch                      | 2        | 0.43%   |
| BenQ T201W BNQ7719 1680x1050 433x271mm 20.1-inch                       | 2        | 0.43%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                      | 2        | 0.43%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                   | 2        | 0.43%   |
| ASUSTek Computer PG349Q AUS343B 3440x1440 798x335mm 34.1-inch          | 2        | 0.43%   |
| AOC 2590G4 AOC2590 1920x1080 544x303mm 24.5-inch                       | 2        | 0.43%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch   | 2        | 0.43%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                       | 2        | 0.43%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 0.22%   |
| Yakumo 17XJ YAK01B2 1280x1024 338x270mm 17.0-inch                      | 1        | 0.22%   |
| Xerox XM3-22W XER08A3 1680x1050 474x296mm 22.0-inch                    | 1        | 0.22%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.22%   |
| ViewSonic VG2433mh VSC6A34 1920x1080 521x293mm 23.5-inch               | 1        | 0.22%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch          | 1        | 0.22%   |
| VIE A2256 VIEE001 1920x1080 509x286mm 23.0-inch                        | 1        | 0.22%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 190      | 44.39%  |
| 1280x1024 (SXGA)   | 56       | 13.08%  |
| 3840x2160 (4K)     | 28       | 6.54%   |
| 1680x1050 (WSXGA+) | 27       | 6.31%   |
| 2560x1440 (QHD)    | 25       | 5.84%   |
| 1366x768 (WXGA)    | 16       | 3.74%   |
| 1440x900 (WXGA+)   | 14       | 3.27%   |
| Unknown            | 13       | 3.04%   |
| 1920x1200 (WUXGA)  | 11       | 2.57%   |
| 1360x768           | 9        | 2.1%    |
| 3440x1440          | 8        | 1.87%   |
| 3840x1080          | 5        | 1.17%   |
| 2560x1080          | 5        | 1.17%   |
| 5120x1440          | 2        | 0.47%   |
| 1600x900 (HD+)     | 2        | 0.47%   |
| 1600x1200          | 2        | 0.47%   |
| 1024x768 (XGA)     | 2        | 0.47%   |
| 800x600            | 1        | 0.23%   |
| 7680x1440          | 1        | 0.23%   |
| 6400x1440          | 1        | 0.23%   |
| 6000x1440          | 1        | 0.23%   |
| 3840x1600          | 1        | 0.23%   |
| 3600x1200          | 1        | 0.23%   |
| 3286x1080          | 1        | 0.23%   |
| 2960x1050          | 1        | 0.23%   |
| 2720x1024          | 1        | 0.23%   |
| 2624x1200          | 1        | 0.23%   |
| 1920x540           | 1        | 0.23%   |
| 1280x960           | 1        | 0.23%   |
| 1280x720 (HD)      | 1        | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 63       | 14.79%  |
| 24      | 58       | 13.62%  |
| Unknown | 49       | 11.5%   |
| 23      | 46       | 10.8%   |
| 27      | 39       | 9.15%   |
| 19      | 36       | 8.45%   |
| 18      | 23       | 5.4%    |
| 17      | 21       | 4.93%   |
| 22      | 19       | 4.46%   |
| 34      | 13       | 3.05%   |
| 84      | 10       | 2.35%   |
| 31      | 10       | 2.35%   |
| 20      | 7        | 1.64%   |
| 72      | 5        | 1.17%   |
| 32      | 4        | 0.94%   |
| 15      | 4        | 0.94%   |
| 65      | 3        | 0.7%    |
| 54      | 3        | 0.7%    |
| 40      | 3        | 0.7%    |
| 49      | 1        | 0.23%   |
| 47      | 1        | 0.23%   |
| 46      | 1        | 0.23%   |
| 43      | 1        | 0.23%   |
| 42      | 1        | 0.23%   |
| 37      | 1        | 0.23%   |
| 26      | 1        | 0.23%   |
| 25      | 1        | 0.23%   |
| 16      | 1        | 0.23%   |
| 12      | 1        | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 130      | 31.25%  |
| 401-500     | 117      | 28.13%  |
| Unknown     | 49       | 11.78%  |
| 351-400     | 31       | 7.45%   |
| 301-350     | 26       | 6.25%   |
| 701-800     | 17       | 4.09%   |
| 601-700     | 15       | 3.61%   |
| 1501-2000   | 15       | 3.61%   |
| 1001-1500   | 9        | 2.16%   |
| 801-900     | 4        | 0.96%   |
| 901-1000    | 2        | 0.48%   |
| 201-300     | 1        | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 235      | 58.17%  |
| 16/10   | 50       | 12.38%  |
| 5/4     | 48       | 11.88%  |
| Unknown | 43       | 10.64%  |
| 21/9    | 14       | 3.47%   |
| 4/3     | 7        | 1.73%   |
| 6/5     | 4        | 0.99%   |
| 3/2     | 2        | 0.5%    |
| 32/9    | 1        | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 147      | 35.25%  |
| 151-200        | 67       | 16.07%  |
| Unknown        | 49       | 11.75%  |
| 301-350        | 40       | 9.59%   |
| 141-150        | 37       | 8.87%   |
| 351-500        | 26       | 6.24%   |
| More than 1000 | 21       | 5.04%   |
| 251-300        | 15       | 3.6%    |
| 501-1000       | 9        | 2.16%   |
| 101-110        | 3        | 0.72%   |
| 71-80          | 1        | 0.24%   |
| 131-140        | 1        | 0.24%   |
| 111-120        | 1        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 244      | 59.95%  |
| 101-120 | 86       | 21.13%  |
| Unknown | 49       | 12.04%  |
| 1-50    | 15       | 3.69%   |
| 121-160 | 9        | 2.21%   |
| 161-240 | 4        | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 352      | 81.48%  |
| 2     | 50       | 11.57%  |
| 0     | 22       | 5.09%   |
| 3     | 8        | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 233      | 42.44%  |
| Intel                           | 155      | 28.23%  |
| Qualcomm Atheros                | 35       | 6.38%   |
| TP-Link                         | 24       | 4.37%   |
| Broadcom                        | 19       | 3.46%   |
| Nvidia                          | 10       | 1.82%   |
| Ralink Technology               | 8        | 1.46%   |
| Broadcom Limited                | 7        | 1.28%   |
| Ralink                          | 6        | 1.09%   |
| ASUSTek Computer                | 6        | 1.09%   |
| Marvell Technology Group        | 5        | 0.91%   |
| D-Link                          | 5        | 0.91%   |
| Aquantia                        | 5        | 0.91%   |
| Microsoft                       | 4        | 0.73%   |
| Qualcomm Atheros Communications | 3        | 0.55%   |
| VIA Technologies                | 2        | 0.36%   |
| Samsung Electronics             | 2        | 0.36%   |
| MediaTek                        | 2        | 0.36%   |
| IMC Networks                    | 2        | 0.36%   |
| Giga-Byte Technology            | 2        | 0.36%   |
| Belkin Components               | 2        | 0.36%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.18%   |
| Xiaomi                          | 1        | 0.18%   |
| QLogic                          | 1        | 0.18%   |
| NetGear                         | 1        | 0.18%   |
| Micro Star International        | 1        | 0.18%   |
| Mercucys                        | 1        | 0.18%   |
| Huawei Technologies             | 1        | 0.18%   |
| HMD Global                      | 1        | 0.18%   |
| Fitbit                          | 1        | 0.18%   |
| Edimax Technology               | 1        | 0.18%   |
| D-Link System                   | 1        | 0.18%   |
| 3Com                            | 1        | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 208      | 34.72%  |
| Intel I211 Gigabit Network Connection                             | 26       | 4.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 4.17%   |
| Intel Ethernet Connection (2) I219-V                              | 15       | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 12       | 2%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 12       | 2%      |
| Intel Wi-Fi 6 AX200                                               | 11       | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 1.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9        | 1.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7        | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1%      |
| Nvidia MCP61 Ethernet                                             | 6        | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1%      |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 6        | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5        | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.67%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.67%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 3        | 0.5%    |
| TP-Link TL-WN722N v2                                              | 3        | 0.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 3        | 0.5%    |
| Ralink RT2501/RT2573 Wireless Adapter                             | 3        | 0.5%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.5%    |
| Intel Wireless-AC 9260                                            | 3        | 0.5%    |
| Intel Wireless 3165                                               | 3        | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 3        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 3        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.5%    |
| Intel 82583V Gigabit Network Connection                           | 3        | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.5%    |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 3        | 0.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.33%   |
| TP-Link Archer T4U ver.3                                          | 2        | 0.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.33%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.33%   |
| Nvidia CK8S Ethernet Controller                                   | 2        | 0.33%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.33%   |
| Intel Wireless 8265 / 8275                                        | 2        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.33%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 26.4%   |
| TP-Link                         | 22       | 17.6%   |
| Realtek Semiconductor           | 18       | 14.4%   |
| Ralink Technology               | 8        | 6.4%    |
| Qualcomm Atheros                | 8        | 6.4%    |
| Ralink                          | 6        | 4.8%    |
| ASUSTek Computer                | 6        | 4.8%    |
| D-Link                          | 5        | 4%      |
| Microsoft                       | 4        | 3.2%    |
| Qualcomm Atheros Communications | 3        | 2.4%    |
| IMC Networks                    | 2        | 1.6%    |
| Broadcom                        | 2        | 1.6%    |
| Belkin Components               | 2        | 1.6%    |
| NetGear                         | 1        | 0.8%    |
| Micro Star International        | 1        | 0.8%    |
| Mercucys                        | 1        | 0.8%    |
| MediaTek                        | 1        | 0.8%    |
| Edimax Technology               | 1        | 0.8%    |
| Broadcom Limited                | 1        | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 11       | 8.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 6        | 4.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 5        | 4%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 4        | 3.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                            | 4        | 3.2%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 3        | 2.4%    |
| TP-Link TL-WN722N v2                                                       | 3        | 2.4%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 3        | 2.4%    |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 3        | 2.4%    |
| Ralink MT7601U Wireless Adapter                                            | 3        | 2.4%    |
| Intel Wireless-AC 9260                                                     | 3        | 2.4%    |
| Intel Wireless 3165                                                        | 3        | 2.4%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 3        | 2.4%    |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]            | 3        | 2.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 2        | 1.6%    |
| TP-Link Archer T4U ver.3                                                   | 2        | 1.6%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 2        | 1.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 2        | 1.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 2        | 1.6%    |
| Qualcomm Atheros AR9271 802.11n                                            | 2        | 1.6%    |
| Microsoft Xbox 360 Wireless Adapter                                        | 2        | 1.6%    |
| Intel Wireless 8265 / 8275                                                 | 2        | 1.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 1.6%    |
| D-Link 802.11n WLAN Adapter                                                | 2        | 1.6%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 2        | 1.6%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                  | 1        | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 1        | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1        | 0.8%    |
| Ralink RT5370 Wireless Adapter                                             | 1        | 0.8%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                          | 1        | 0.8%    |
| Ralink RT5592 PCIe Wireless Network Adapter                                | 1        | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 0.8%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 0.8%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 0.8%    |
| Ralink RT2561/RT61 rev B 802.11g                                           | 1        | 0.8%    |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 0.8%    |
| Qualcomm Atheros AR5523                                                    | 1        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 0.8%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                           | 1        | 0.8%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 0.8%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]     | 1        | 0.8%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                 | 1        | 0.8%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]        | 1        | 0.8%    |
| NetGear WNDA3100v3 802.11abgn 2x2:2 [MediaTek MT7632U]                     | 1        | 0.8%    |
| Microsoft XBOX ACC                                                         | 1        | 0.8%    |
| Microsoft Wireless XBox Controller Dongle                                  | 1        | 0.8%    |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 0.8%    |
| Mercucys MW300UM RTL8192EU wifi                                            | 1        | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 1        | 0.8%    |
| Intel Wireless 7265                                                        | 1        | 0.8%    |
| Intel Wireless 3160                                                        | 1        | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 1        | 0.8%    |
| IMC Networks RTL8191S WLAN Adapter                                         | 1        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 229      | 50.33%  |
| Intel                    | 140      | 30.77%  |
| Qualcomm Atheros         | 28       | 6.15%   |
| Broadcom                 | 17       | 3.74%   |
| Nvidia                   | 10       | 2.2%    |
| Broadcom Limited         | 6        | 1.32%   |
| Marvell Technology Group | 5        | 1.1%    |
| Aquantia                 | 5        | 1.1%    |
| VIA Technologies         | 2        | 0.44%   |
| TP-Link                  | 2        | 0.44%   |
| Samsung Electronics      | 2        | 0.44%   |
| Giga-Byte Technology     | 2        | 0.44%   |
| Xiaomi                   | 1        | 0.22%   |
| QLogic                   | 1        | 0.22%   |
| MediaTek                 | 1        | 0.22%   |
| Huawei Technologies      | 1        | 0.22%   |
| HMD Global               | 1        | 0.22%   |
| D-Link System            | 1        | 0.22%   |
| 3Com                     | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 208      | 44.16%  |
| Intel I211 Gigabit Network Connection                             | 26       | 5.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 5.31%   |
| Intel Ethernet Connection (2) I219-V                              | 15       | 3.18%   |
| Intel Ethernet Connection I217-LM                                 | 12       | 2.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 12       | 2.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9        | 1.91%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 1.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7        | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.27%   |
| Nvidia MCP61 Ethernet                                             | 6        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 6        | 1.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5        | 1.06%   |
| Intel I210 Gigabit Network Connection                             | 5        | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.06%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.85%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.64%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.64%   |
| Intel 82583V Gigabit Network Connection                           | 3        | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.42%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.42%   |
| Nvidia CK8S Ethernet Controller                                   | 2        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.42%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.42%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.42%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.42%   |
| Giga-Byte MT65xx Android Phone                                    | 2        | 0.42%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 0.42%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 2        | 0.42%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.21%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.21%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.21%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.21%   |
| TP-Link M7200                                                     | 1        | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.21%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.21%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.21%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.21%   |
| QLogic ISP4022-based Ethernet NIC                                 | 1        | 0.21%   |
| MediaTek moto e6s                                                 | 1        | 0.21%   |
| Marvell Group 88E8075 PCI-E Gigabit Ethernet Controller           | 1        | 0.21%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.21%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.21%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.21%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 419      | 77.31%  |
| WiFi     | 120      | 22.14%  |
| Unknown  | 2        | 0.37%   |
| Modem    | 1        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 366      | 85.51%  |
| WiFi     | 62       | 14.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 323      | 76.54%  |
| 2     | 79       | 18.72%  |
| 3     | 18       | 4.27%   |
| 4     | 1        | 0.24%   |
| 0     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 385      | 89.95%  |
| Yes  | 43       | 10.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 39.74%  |
| Cambridge Silicon Radio         | 20       | 25.64%  |
| ASUSTek Computer                | 18       | 23.08%  |
| Realtek Semiconductor           | 2        | 2.56%   |
| Unknown                         | 1        | 1.28%   |
| Qualcomm Atheros Communications | 1        | 1.28%   |
| Micro Star International        | 1        | 1.28%   |
| MediaTek                        | 1        | 1.28%   |
| Integrated System Solution      | 1        | 1.28%   |
| Conwise Technology              | 1        | 1.28%   |
| Broadcom                        | 1        | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 25.64%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 16       | 20.51%  |
| Intel AX200 Bluetooth                               | 10       | 12.82%  |
| Intel Bluetooth wireless interface                  | 7        | 8.97%   |
| Intel AX201 Bluetooth                               | 5        | 6.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 5.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 3.85%   |
| ASUS ASUS USB-BT500                                 | 2        | 2.56%   |
| Unknown Bluetooth Device                            | 1        | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.28%   |
| Realtek Bluetooth Radio                             | 1        | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 1.28%   |
| Micro Star International Bluetooth Device           | 1        | 1.28%   |
| MediaTek Wireless_Device                            | 1        | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.28%   |
| Intel AX210 Bluetooth                               | 1        | 1.28%   |
| Integrated System Solution Bluetooth Device         | 1        | 1.28%   |
| Conwise CW6622                                      | 1        | 1.28%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 274      | 40.71%  |
| AMD                                          | 154      | 22.88%  |
| Nvidia                                       | 149      | 22.14%  |
| C-Media Electronics                          | 20       | 2.97%   |
| Creative Labs                                | 19       | 2.82%   |
| Logitech                                     | 6        | 0.89%   |
| Giga-Byte Technology                         | 5        | 0.74%   |
| Trust                                        | 4        | 0.59%   |
| Sennheiser Communications                    | 4        | 0.59%   |
| Creative Technology                          | 4        | 0.59%   |
| Texas Instruments                            | 3        | 0.45%   |
| Kingston Technology                          | 3        | 0.45%   |
| Tenx Technology                              | 2        | 0.3%    |
| GYROCOM C&C                                  | 2        | 0.3%    |
| Audio-Technica                               | 2        | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.15%   |
| VIA Technologies                             | 1        | 0.15%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.15%   |
| TEAC                                         | 1        | 0.15%   |
| Studiologic                                  | 1        | 0.15%   |
| Samson Technologies                          | 1        | 0.15%   |
| Razer USA                                    | 1        | 0.15%   |
| Plantronics                                  | 1        | 0.15%   |
| OnePlus Technology (Shenzhen)                | 1        | 0.15%   |
| Nam Tai E&E Products                         | 1        | 0.15%   |
| JMTek                                        | 1        | 0.15%   |
| iCreate Technologies                         | 1        | 0.15%   |
| Holtek Semiconductor                         | 1        | 0.15%   |
| GN Netcom                                    | 1        | 0.15%   |
| Generalplus Technology                       | 1        | 0.15%   |
| Focusrite-Novation                           | 1        | 0.15%   |
| Dell                                         | 1        | 0.15%   |
| Corsair                                      | 1        | 0.15%   |
| Cambridge Audio                              | 1        | 0.15%   |
| BEHRINGER International                      | 1        | 0.15%   |
| AKAI Professional M.I.                       | 1        | 0.15%   |
| A4Tech                                       | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 35       | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 34       | 4.38%   |
| AMD Starship/Matisse HD Audio Controller                                          | 29       | 3.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 28       | 3.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 27       | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 27       | 3.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 27       | 3.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 25       | 3.22%   |
| Intel 200 Series PCH HD Audio                                                     | 24       | 3.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 22       | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 22       | 2.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 21       | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 21       | 2.7%    |
| AMD Family 17h/19h HD Audio Controller                                            | 18       | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                        | 17       | 2.19%   |
| Nvidia GP104 High Definition Audio Controller                                     | 15       | 1.93%   |
| AMD FCH Azalia Controller                                                         | 15       | 1.93%   |
| Nvidia GF108 High Definition Audio Controller                                     | 14       | 1.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 13       | 1.67%   |
| Nvidia High Definition Audio Controller                                           | 12       | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 11       | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 11       | 1.42%   |
| AMD Navi 10 HDMI Audio                                                            | 10       | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                                | 8        | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 8        | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                | 6        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 0.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 6        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5        | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 0.64%   |
| Nvidia TU104 HD Audio Controller                                                  | 5        | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5        | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                                     | 5        | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                                | 5        | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5        | 0.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5        | 0.64%   |
| Giga-Byte Technology USB Audio                                                    | 5        | 0.64%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 5        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                 | 5        | 0.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 0.51%   |
| Intel Comet Lake PCH cAVS                                                         | 4        | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 4        | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 4        | 0.51%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 4        | 0.51%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 4        | 0.51%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4        | 0.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 0.51%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 0.39%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3        | 0.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.39%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.39%   |
| Nvidia GF104 High Definition Audio Controller                                     | 3        | 0.39%   |
| Kingston Technology HyperX 7.1 Audio                                              | 3        | 0.39%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 3        | 0.39%   |
| C-Media Electronics CM108 Audio Controller                                        | 3        | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 53       | 21.46%  |
| Unknown             | 42       | 17%     |
| Corsair             | 39       | 15.79%  |
| Samsung Electronics | 21       | 8.5%    |
| SK hynix            | 19       | 7.69%   |
| Crucial             | 10       | 4.05%   |
| Micron Technology   | 9        | 3.64%   |
| G.Skill             | 9        | 3.64%   |
| Ramaxel Technology  | 7        | 2.83%   |
| Nanya Technology    | 7        | 2.83%   |
| A-DATA Technology   | 7        | 2.83%   |
| Kingmax             | 5        | 2.02%   |
| Elpida              | 4        | 1.62%   |
| Patriot             | 3        | 1.21%   |
| Unknown             | 3        | 1.21%   |
| Qimonda             | 2        | 0.81%   |
| Goodram             | 2        | 0.81%   |
| Unknown (ABCD)      | 1        | 0.4%    |
| TakeMS              | 1        | 0.4%    |
| S                   | 1        | 0.4%    |
| H                   | 1        | 0.4%    |
| Apacer              | 1        | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 7        | 2.53%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 6        | 2.17%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 5        | 1.81%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s       | 5        | 1.81%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3             | 3        | 1.08%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s       | 3        | 1.08%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 3        | 1.08%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s       | 3        | 1.08%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s     | 3        | 1.08%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 3        | 1.08%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s    | 3        | 1.08%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s  | 3        | 1.08%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.08%   |
| Unknown                                                 | 3        | 1.08%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 2        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 2        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 2        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 2        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 0.72%   |
| Unknown RAM Module 1024MB DIMM                          | 2        | 0.72%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 2        | 0.72%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 2        | 0.72%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 0.72%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 2        | 0.72%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s     | 2        | 0.72%   |
| Ramaxel RAM RML1520EC48D7W-800 1024MB DIMM DDR2 800MT/s | 2        | 0.72%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s        | 2        | 0.72%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s      | 2        | 0.72%   |
| Nanya RAM M2Y2G64TU8HD6B-AC 2GB DIMM DDR2 800MT/s       | 2        | 0.72%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s  | 2        | 0.72%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s     | 2        | 0.72%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM 1333MT/s        | 2        | 0.72%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s   | 2        | 0.72%   |
| Corsair RAM CMY32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s    | 2        | 0.72%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s  | 2        | 0.72%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s   | 2        | 0.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.36%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.36%   |
| Unknown RAM Module 512MB DIMM 800MT/s                   | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM 667MT/s            | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM                    | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR2 1067MT/s            | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s            | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s             | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s             | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 1        | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s               | 1        | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                 | 1        | 0.36%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s             | 1        | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 1        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 83       | 37.73%  |
| DDR3    | 78       | 35.45%  |
| DDR2    | 21       | 9.55%   |
| SDRAM   | 17       | 7.73%   |
| Unknown | 17       | 7.73%   |
| DDR     | 3        | 1.36%   |
| LPDDR4  | 1        | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 201      | 96.63%  |
| SODIMM  | 5        | 2.4%    |
| RIMM    | 1        | 0.48%   |
| FB-DIMM | 1        | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 67       | 28.88%  |
| 4096  | 60       | 25.86%  |
| 2048  | 46       | 19.83%  |
| 16384 | 26       | 11.21%  |
| 1024  | 25       | 10.78%  |
| 32768 | 6        | 2.59%   |
| 512   | 2        | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 40       | 16.6%   |
| 1333    | 34       | 14.11%  |
| 2400    | 21       | 8.71%   |
| 800     | 19       | 7.88%   |
| 667     | 15       | 6.22%   |
| 2667    | 14       | 5.81%   |
| 3600    | 12       | 4.98%   |
| 2133    | 9        | 3.73%   |
| Unknown | 9        | 3.73%   |
| 3200    | 7        | 2.9%    |
| 2933    | 6        | 2.49%   |
| 3466    | 5        | 2.07%   |
| 3000    | 5        | 2.07%   |
| 1867    | 4        | 1.66%   |
| 2800    | 3        | 1.24%   |
| 2666    | 3        | 1.24%   |
| 1866    | 3        | 1.24%   |
| 533     | 3        | 1.24%   |
| 3733    | 2        | 0.83%   |
| 3400    | 2        | 0.83%   |
| 2048    | 2        | 0.83%   |
| 1800    | 2        | 0.83%   |
| 1334    | 2        | 0.83%   |
| 1067    | 2        | 0.83%   |
| 1066    | 2        | 0.83%   |
| 49926   | 1        | 0.41%   |
| 8192    | 1        | 0.41%   |
| 4800    | 1        | 0.41%   |
| 4266    | 1        | 0.41%   |
| 3500    | 1        | 0.41%   |
| 3334    | 1        | 0.41%   |
| 3266    | 1        | 0.41%   |
| 3151    | 1        | 0.41%   |
| 3100    | 1        | 0.41%   |
| 3007    | 1        | 0.41%   |
| 2934    | 1        | 0.41%   |
| 2600    | 1        | 0.41%   |
| 2187    | 1        | 0.41%   |
| 1639    | 1        | 0.41%   |
| 400     | 1        | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 6        | 24%     |
| Hewlett-Packard     | 5        | 20%     |
| Canon               | 4        | 16%     |
| Seiko Epson         | 3        | 12%     |
| Samsung Electronics | 3        | 12%     |
| Zebra               | 1        | 4%      |
| Xerox               | 1        | 4%      |
| QinHeng Electronics | 1        | 4%      |
| ATEN International  | 1        | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Canon MF4010 series                           | 2        | 8%      |
| Zebra GK420t Label Printer                    | 1        | 4%      |
| Xerox Phaser 6130N                            | 1        | 4%      |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 4%      |
| Seiko Epson L395 Series                       | 1        | 4%      |
| Seiko Epson ET-3750 Series                    | 1        | 4%      |
| Samsung ML-216x Series Laser Printer          | 1        | 4%      |
| Samsung M2070 Series                          | 1        | 4%      |
| Samsung CLP-310 Color Laser Printer           | 1        | 4%      |
| QinHeng CH340S                                | 1        | 4%      |
| HP LaserJet M14-M17                           | 1        | 4%      |
| HP LaserJet 3050                              | 1        | 4%      |
| HP DeskJet F2492 All-in-One                   | 1        | 4%      |
| HP Deskjet 3050A                              | 1        | 4%      |
| HP DeskJet 2130 series                        | 1        | 4%      |
| Canon PIXMA MP280                             | 1        | 4%      |
| Canon MF3110                                  | 1        | 4%      |
| Brother MFC-7420                              | 1        | 4%      |
| Brother HL-5380DN series                      | 1        | 4%      |
| Brother HL-5250DN Printer                     | 1        | 4%      |
| Brother HL-1210W series                       | 1        | 4%      |
| Brother HL-1110 series                        | 1        | 4%      |
| Brother DCP-7030                              | 1        | 4%      |
| ATEN International UC-1284B Printer Port      | 1        | 4%      |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 18       | 25.71%  |
| Microdia                      | 12       | 17.14%  |
| Microsoft                     | 6        | 8.57%   |
| Sunplus Innovation Technology | 4        | 5.71%   |
| GEMBIRD                       | 3        | 4.29%   |
| Z-Star Microelectronics       | 2        | 2.86%   |
| Samsung Electronics           | 2        | 2.86%   |
| Realtek Semiconductor         | 2        | 2.86%   |
| Cubeternet                    | 2        | 2.86%   |
| Chicony Electronics           | 2        | 2.86%   |
| Aveo Technology               | 2        | 2.86%   |
| Apple                         | 2        | 2.86%   |
| WaveRider Communications      | 1        | 1.43%   |
| Unknown                       | 1        | 1.43%   |
| Novatek Microelectronics      | 1        | 1.43%   |
| Lenovo                        | 1        | 1.43%   |
| KYE Systems (Mouse Systems)   | 1        | 1.43%   |
| Jieli Technology              | 1        | 1.43%   |
| Jeilin Technology             | 1        | 1.43%   |
| IMC Networks                  | 1        | 1.43%   |
| Huawei Technologies           | 1        | 1.43%   |
| Generalplus Technology        | 1        | 1.43%   |
| Arkmicro Technologies         | 1        | 1.43%   |
| ARC International             | 1        | 1.43%   |
| Alcor Micro                   | 1        | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                   | 4        | 5.71%   |
| Microdia Camera                             | 4        | 5.71%   |
| Logitech HD Pro Webcam C920                 | 4        | 5.71%   |
| Sunplus Full HD webcam                      | 2        | 2.86%   |
| Sunplus Depstech webcam MIC                 | 2        | 2.86%   |
| Samsung Galaxy series, misc. (MTP mode)     | 2        | 2.86%   |
| Microdia Sonix USB 2.0 Camera               | 2        | 2.86%   |
| Microdia Integrated Camera                  | 2        | 2.86%   |
| Microdia HP Integrated Webcam               | 2        | 2.86%   |
| Logitech Webcam C270                        | 2        | 2.86%   |
| Logitech QuickCam Pro 9000                  | 2        | 2.86%   |
| GEMBIRD USB2.0 PC CAMERA                    | 2        | 2.86%   |
| Z-Star Venus USB2.0 Camera                  | 1        | 1.43%   |
| Z-Star A4 TECH HD PC Camera                 | 1        | 1.43%   |
| WaveRider USB Live camera                   | 1        | 1.43%   |
| Unknown HD camera                           | 1        | 1.43%   |
| Realtek USB Camera                          | 1        | 1.43%   |
| Realtek FULL HD 1080P Webcam                | 1        | 1.43%   |
| Novatek HP High Definition 2MP Webcam       | 1        | 1.43%   |
| Microsoft LifeCam VX-7000 (UVC-compliant)   | 1        | 1.43%   |
| Microsoft LifeCam VX-500 [1357]             | 1        | 1.43%   |
| Microdia USB 2.0 Camera                     | 1        | 1.43%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 1.43%   |
| Logitech Webcam C310                        | 1        | 1.43%   |
| Logitech Webcam C250                        | 1        | 1.43%   |
| Logitech Webcam C170                        | 1        | 1.43%   |
| Logitech Webcam C110                        | 1        | 1.43%   |
| Logitech Webcam B500                        | 1        | 1.43%   |
| Logitech Logitech Webcam C100               | 1        | 1.43%   |
| Logitech HD Webcam C615                     | 1        | 1.43%   |
| Logitech HD Webcam C525                     | 1        | 1.43%   |
| Logitech BCC950 ConferenceCam               | 1        | 1.43%   |
| Logitech B525 HD Webcam                     | 1        | 1.43%   |
| Lenovo 500 RGB Camera                       | 1        | 1.43%   |
| KYE Systems (Mouse Systems) Slim 1322AF     | 1        | 1.43%   |
| Jieli USB PHY 2.0                           | 1        | 1.43%   |
| Jeilin Kodak S101 Webcam                    | 1        | 1.43%   |
| IMC Networks XHC Camera                     | 1        | 1.43%   |
| Huawei UVC Camera                           | 1        | 1.43%   |
| Generalplus 808 Camera #9 (web-cam mode)    | 1        | 1.43%   |
| GEMBIRD TIGA Device                         | 1        | 1.43%   |
| Cubeternet USB2.0 Camera                    | 1        | 1.43%   |
| Cubeternet GL-UPC822 UVC WebCam             | 1        | 1.43%   |
| Chicony PLEOMAX 1.3MP UVC Webcam            | 1        | 1.43%   |
| Chicony ASUS USB2.0 Webcam                  | 1        | 1.43%   |
| Aveo UVC camera (Bresser microscope)        | 1        | 1.43%   |
| Aveo USB2.0 UVC PC Camera                   | 1        | 1.43%   |
| Arkmicro USB2.0 PC CAMERA                   | 1        | 1.43%   |
| ARC International Camera                    | 1        | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE                   | 1        | 1.43%   |
| Apple iPhone 4S                             | 1        | 1.43%   |
| Alcor Micro USB 2.0 PC Camera               | 1        | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Fujitsu Siemens Computers | 1        | 50%     |
| Chicony Electronics       | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Fujitsu Siemens Computers SmartCard Reader 2A        | 1        | 50%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 372      | 86.92%  |
| 1     | 48       | 11.21%  |
| 2     | 7        | 1.64%   |
| 3     | 1        | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 30.65%  |
| Net/wireless             | 15       | 24.19%  |
| Communication controller | 6        | 9.68%   |
| Unassigned class         | 4        | 6.45%   |
| Multimedia controller    | 4        | 6.45%   |
| Storage/ide              | 2        | 3.23%   |
| Sound                    | 2        | 3.23%   |
| Camera                   | 2        | 3.23%   |
| Bluetooth                | 2        | 3.23%   |
| Unclassified device      | 1        | 1.61%   |
| Storage/raid             | 1        | 1.61%   |
| Storage                  | 1        | 1.61%   |
| Net/ethernet             | 1        | 1.61%   |
| Chipcard                 | 1        | 1.61%   |
| Card reader              | 1        | 1.61%   |


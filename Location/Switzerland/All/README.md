Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 3333

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d772da19a0](https://linux-hardware.org/?probe=d772da19a0) | Jun 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [566b883024](https://linux-hardware.org/?probe=566b883024) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ad91997e3e](https://linux-hardware.org/?probe=ad91997e3e) | Jun 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [7f5dfae0db](https://linux-hardware.org/?probe=7f5dfae0db) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| Unknown       | Unknown                     | Soc         | [baebeebbdb](https://linux-hardware.org/?probe=baebeebbdb) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [66f2fbfdf4](https://linux-hardware.org/?probe=66f2fbfdf4) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | Notebook    | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [cb554fb8f8](https://linux-hardware.org/?probe=cb554fb8f8) | Jun 24, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [f8dee044e2](https://linux-hardware.org/?probe=f8dee044e2) | Jun 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [24db241d7a](https://linux-hardware.org/?probe=24db241d7a) | Jun 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [23ea485e5e](https://linux-hardware.org/?probe=23ea485e5e) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [223c8d15d4](https://linux-hardware.org/?probe=223c8d15d4) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f008d4c0db](https://linux-hardware.org/?probe=f008d4c0db) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | Notebook    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c45597704a](https://linux-hardware.org/?probe=c45597704a) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a312151081](https://linux-hardware.org/?probe=a312151081) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8ea9d60a21](https://linux-hardware.org/?probe=8ea9d60a21) | Jun 12, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [794030a707](https://linux-hardware.org/?probe=794030a707) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [212ff65852](https://linux-hardware.org/?probe=212ff65852) | Jun 09, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | Notebook    | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5b7a78b32e](https://linux-hardware.org/?probe=5b7a78b32e) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [14f68da7a7](https://linux-hardware.org/?probe=14f68da7a7) | Jun 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [f077d744cb](https://linux-hardware.org/?probe=f077d744cb) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| GPD           | P2 MAX                      | Notebook    | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [2f3952dcfe](https://linux-hardware.org/?probe=2f3952dcfe) | May 27, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [246b95d20f](https://linux-hardware.org/?probe=246b95d20f) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Samsung       | 930QED                      | Convertible | [14f0193b6a](https://linux-hardware.org/?probe=14f0193b6a) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Intel         | S2600STB J17012-601         | Server      | [2fa80c021a](https://linux-hardware.org/?probe=2fa80c021a) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [aa0bf32546](https://linux-hardware.org/?probe=aa0bf32546) | May 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [c956e9cbab](https://linux-hardware.org/?probe=c956e9cbab) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| Dell          | Latitude E6530              | Notebook    | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [019a851aeb](https://linux-hardware.org/?probe=019a851aeb) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [5d4070956a](https://linux-hardware.org/?probe=5d4070956a) | May 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [b595a4a849](https://linux-hardware.org/?probe=b595a4a849) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Dell          | Latitude 5520               | Notebook    | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [d71435c79a](https://linux-hardware.org/?probe=d71435c79a) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [62e7f77fdc](https://linux-hardware.org/?probe=62e7f77fdc) | May 12, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f6c8b6c33e](https://linux-hardware.org/?probe=f6c8b6c33e) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [41d9417c57](https://linux-hardware.org/?probe=41d9417c57) | May 11, 2023 |
| Acer          | Aspire 5332                 | Notebook    | [e74870bf17](https://linux-hardware.org/?probe=e74870bf17) | May 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| HP            | Compaq 6910p                | Notebook    | [c17dc1abcf](https://linux-hardware.org/?probe=c17dc1abcf) | May 08, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [f0f22d5d3f](https://linux-hardware.org/?probe=f0f22d5d3f) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c95999b5ad](https://linux-hardware.org/?probe=c95999b5ad) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [670e910889](https://linux-hardware.org/?probe=670e910889) | May 08, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [7502ce9679](https://linux-hardware.org/?probe=7502ce9679) | May 08, 2023 |
| Medion        | MS-7797                     | Desktop     | [590e39bef4](https://linux-hardware.org/?probe=590e39bef4) | May 07, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| Medion        | MS-7797                     | Desktop     | [d7eb2caa26](https://linux-hardware.org/?probe=d7eb2caa26) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 212B                        | Desktop     | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [4b705b9dca](https://linux-hardware.org/?probe=4b705b9dca) | May 03, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [61873cde49](https://linux-hardware.org/?probe=61873cde49) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbd9496296](https://linux-hardware.org/?probe=bbd9496296) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [71ec2fc5ea](https://linux-hardware.org/?probe=71ec2fc5ea) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [6936dcf305](https://linux-hardware.org/?probe=6936dcf305) | May 03, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [7a44b651f4](https://linux-hardware.org/?probe=7a44b651f4) | May 03, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [a720d9d42e](https://linux-hardware.org/?probe=a720d9d42e) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [c8c9c1e591](https://linux-hardware.org/?probe=c8c9c1e591) | Apr 30, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [910d4a6ad8](https://linux-hardware.org/?probe=910d4a6ad8) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [00d8186404](https://linux-hardware.org/?probe=00d8186404) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [50e1b8e197](https://linux-hardware.org/?probe=50e1b8e197) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Dell          | Latitude 5520               | Notebook    | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | Notebook    | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | Notebook    | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| AZW           | GTR V02                     | Desktop     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| Gigabyte      | P55A-UD7                    | Desktop     | [59f8c4d262](https://linux-hardware.org/?probe=59f8c4d262) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [9bb50174ef](https://linux-hardware.org/?probe=9bb50174ef) | Apr 20, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [51412400ba](https://linux-hardware.org/?probe=51412400ba) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [d765a92052](https://linux-hardware.org/?probe=d765a92052) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | Desktop     | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | Desktop     | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| Intel         | S2600WFT H48104-860         | Server      | [f5848d1ba2](https://linux-hardware.org/?probe=f5848d1ba2) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [5fba63c085](https://linux-hardware.org/?probe=5fba63c085) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| Gigabyte      | MZ12-HD3-00 01010101        | Server      | [def4067c8e](https://linux-hardware.org/?probe=def4067c8e) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [3e6b182473](https://linux-hardware.org/?probe=3e6b182473) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | Desktop     | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| ASRock        | B560M-HDV                   | Desktop     | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [b076a9a807](https://linux-hardware.org/?probe=b076a9a807) | Apr 18, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [ddbd926522](https://linux-hardware.org/?probe=ddbd926522) | Apr 18, 2023 |
| Dell          | 0R4CNN A02                  | Server      | [237a3cd682](https://linux-hardware.org/?probe=237a3cd682) | Apr 18, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [dc155ce308](https://linux-hardware.org/?probe=dc155ce308) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [aaff05d28f](https://linux-hardware.org/?probe=aaff05d28f) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | Notebook    | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [fc6c4adaa4](https://linux-hardware.org/?probe=fc6c4adaa4) | Apr 17, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8dd4721bd1](https://linux-hardware.org/?probe=8dd4721bd1) | Apr 16, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [a0f5ba360c](https://linux-hardware.org/?probe=a0f5ba360c) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9c885fa5cf](https://linux-hardware.org/?probe=9c885fa5cf) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | Latitude 7530               | Notebook    | [133059c3d6](https://linux-hardware.org/?probe=133059c3d6) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [8fb4ed64eb](https://linux-hardware.org/?probe=8fb4ed64eb) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5943787304](https://linux-hardware.org/?probe=5943787304) | Apr 16, 2023 |
| ASUSTek       | X756UJ                      | Notebook    | [a374f8dd26](https://linux-hardware.org/?probe=a374f8dd26) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [817e4bb939](https://linux-hardware.org/?probe=817e4bb939) | Apr 13, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ec028424ea](https://linux-hardware.org/?probe=ec028424ea) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ccdf29023](https://linux-hardware.org/?probe=9ccdf29023) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [6a8c52faa7](https://linux-hardware.org/?probe=6a8c52faa7) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [32f5d43e96](https://linux-hardware.org/?probe=32f5d43e96) | Apr 04, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| Sony          | VPCF22C5E                   | Notebook    | [9d122b8bdd](https://linux-hardware.org/?probe=9d122b8bdd) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [36d245f86b](https://linux-hardware.org/?probe=36d245f86b) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6f3e488e2b](https://linux-hardware.org/?probe=6f3e488e2b) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [17fb0ed43a](https://linux-hardware.org/?probe=17fb0ed43a) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| HP            | Unknown                     | Notebook    | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [3494b0fdd9](https://linux-hardware.org/?probe=3494b0fdd9) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [c885b5da6c](https://linux-hardware.org/?probe=c885b5da6c) | Mar 30, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [452a3fa4a8](https://linux-hardware.org/?probe=452a3fa4a8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [e1d01990f4](https://linux-hardware.org/?probe=e1d01990f4) | Mar 27, 2023 |
| HP            | 844C                        | Desktop     | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [405ce5a9c8](https://linux-hardware.org/?probe=405ce5a9c8) | Mar 27, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [35e0a73e8f](https://linux-hardware.org/?probe=35e0a73e8f) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| Acer          | Predator G9-791             | Notebook    | [1f820516a3](https://linux-hardware.org/?probe=1f820516a3) | Mar 26, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [728f83932f](https://linux-hardware.org/?probe=728f83932f) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a94081c24](https://linux-hardware.org/?probe=5a94081c24) | Mar 24, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [704fb36197](https://linux-hardware.org/?probe=704fb36197) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [74be0519cc](https://linux-hardware.org/?probe=74be0519cc) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [5074a23172](https://linux-hardware.org/?probe=5074a23172) | Mar 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9ba3333988](https://linux-hardware.org/?probe=9ba3333988) | Mar 20, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [0fb09c29cb](https://linux-hardware.org/?probe=0fb09c29cb) | Mar 20, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [6c83c2a089](https://linux-hardware.org/?probe=6c83c2a089) | Mar 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3c00ca015f](https://linux-hardware.org/?probe=3c00ca015f) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Google        | Lillipup                    | Notebook    | [3eca64113c](https://linux-hardware.org/?probe=3eca64113c) | Mar 18, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [4e6f4d1197](https://linux-hardware.org/?probe=4e6f4d1197) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [bfdb73f825](https://linux-hardware.org/?probe=bfdb73f825) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [839899a14d](https://linux-hardware.org/?probe=839899a14d) | Mar 15, 2023 |
| ASUSTek       | UX32A                       | Notebook    | [05121bc6af](https://linux-hardware.org/?probe=05121bc6af) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f4926b859a](https://linux-hardware.org/?probe=f4926b859a) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Notebook      | NS50MU                      | Notebook    | [f5e64711f3](https://linux-hardware.org/?probe=f5e64711f3) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [36bcd11bd3](https://linux-hardware.org/?probe=36bcd11bd3) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [aca12aa4c5](https://linux-hardware.org/?probe=aca12aa4c5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | Notebook    | [aa5eb19101](https://linux-hardware.org/?probe=aa5eb19101) | Mar 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [433c3d165a](https://linux-hardware.org/?probe=433c3d165a) | Mar 13, 2023 |
| HP            | 212B                        | Desktop     | [8d5ef71d93](https://linux-hardware.org/?probe=8d5ef71d93) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [55fe24706a](https://linux-hardware.org/?probe=55fe24706a) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6c90dd73e7](https://linux-hardware.org/?probe=6c90dd73e7) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [c792b83b69](https://linux-hardware.org/?probe=c792b83b69) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | Notebook    | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d7535fd29e](https://linux-hardware.org/?probe=d7535fd29e) | Mar 10, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [0e1279e96d](https://linux-hardware.org/?probe=0e1279e96d) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5b8db1d628](https://linux-hardware.org/?probe=5b8db1d628) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9946c1c6dc](https://linux-hardware.org/?probe=9946c1c6dc) | Mar 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [e280beba92](https://linux-hardware.org/?probe=e280beba92) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d52a175b61](https://linux-hardware.org/?probe=d52a175b61) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| Fujitsu       | CELSIUS H780                | Notebook    | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [359903fe58](https://linux-hardware.org/?probe=359903fe58) | Mar 07, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [5656c3015d](https://linux-hardware.org/?probe=5656c3015d) | Mar 06, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Lenovo        | ThinkPad E590 20NB000YMZ    | Notebook    | [fb05511be8](https://linux-hardware.org/?probe=fb05511be8) | Mar 05, 2023 |
| HP            | Compaq 15                   | Notebook    | [5c8a185273](https://linux-hardware.org/?probe=5c8a185273) | Mar 05, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e57a377381](https://linux-hardware.org/?probe=e57a377381) | Mar 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e45794963a](https://linux-hardware.org/?probe=e45794963a) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [02df2ea534](https://linux-hardware.org/?probe=02df2ea534) | Mar 03, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [cacb713046](https://linux-hardware.org/?probe=cacb713046) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [117d283b7a](https://linux-hardware.org/?probe=117d283b7a) | Mar 02, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [0780656106](https://linux-hardware.org/?probe=0780656106) | Mar 01, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [0855d319b4](https://linux-hardware.org/?probe=0855d319b4) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | Notebook    | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Intel         | NUC7i3DNB J57625-510        | Mini pc     | [aedbb176f7](https://linux-hardware.org/?probe=aedbb176f7) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [ef74f90ec1](https://linux-hardware.org/?probe=ef74f90ec1) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| Samsung       | 930QED                      | Convertible | [9e03711ee7](https://linux-hardware.org/?probe=9e03711ee7) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [db7a713397](https://linux-hardware.org/?probe=db7a713397) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | Notebook    | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | 8653 A                      | Desktop     | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| HP            | ProBook 4720s               | Notebook    | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [9e7d0b79cf](https://linux-hardware.org/?probe=9e7d0b79cf) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0ca0b99aa3](https://linux-hardware.org/?probe=0ca0b99aa3) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b83c8fb5a1](https://linux-hardware.org/?probe=b83c8fb5a1) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [e04cbf47d6](https://linux-hardware.org/?probe=e04cbf47d6) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [163afb997a](https://linux-hardware.org/?probe=163afb997a) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Medion        | MS-7728                     | Desktop     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | Desktop     | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [80f8925010](https://linux-hardware.org/?probe=80f8925010) | Jan 17, 2023 |
| Acer          | Aspire M5910                | Desktop     | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | 212B                        | Desktop     | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| ELSKY         | QM10u                       | Desktop     | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a7b0b9f2e](https://linux-hardware.org/?probe=9a7b0b9f2e) | Jan 10, 2023 |
| Medion        | MS-7728                     | Desktop     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | Desktop     | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | Notebook    | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [97335b8723](https://linux-hardware.org/?probe=97335b8723) | Jan 07, 2023 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ac69fa3d31](https://linux-hardware.org/?probe=ac69fa3d31) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | Desktop     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | Notebook    | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| Acer          | Predator G9-591             | Notebook    | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0b9972387e](https://linux-hardware.org/?probe=0b9972387e) | Jan 05, 2023 |
| Medion        | MS-7728                     | Desktop     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| Medion        | MS-7728                     | Desktop     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [b341980e6c](https://linux-hardware.org/?probe=b341980e6c) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [cc24dc6f72](https://linux-hardware.org/?probe=cc24dc6f72) | Dec 31, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [bf3922e95d](https://linux-hardware.org/?probe=bf3922e95d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | Notebook    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [77ee14ad98](https://linux-hardware.org/?probe=77ee14ad98) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [1c022f7ff8](https://linux-hardware.org/?probe=1c022f7ff8) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [907ca44afe](https://linux-hardware.org/?probe=907ca44afe) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| ASUSTek       | PN64                        | Mini pc     | [a5fdbdb0c8](https://linux-hardware.org/?probe=a5fdbdb0c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | Notebook    | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3282a529f0](https://linux-hardware.org/?probe=3282a529f0) | Dec 11, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [6c26c9ff8c](https://linux-hardware.org/?probe=6c26c9ff8c) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [62986b3426](https://linux-hardware.org/?probe=62986b3426) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [439e89b31f](https://linux-hardware.org/?probe=439e89b31f) | Dec 07, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [ee9c9e919b](https://linux-hardware.org/?probe=ee9c9e919b) | Dec 05, 2022 |
| HP            | ENVY dv7                    | Notebook    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [9a0718a60f](https://linux-hardware.org/?probe=9a0718a60f) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | Notebook    | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | Notebook    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | Notebook    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8d98938198](https://linux-hardware.org/?probe=8d98938198) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [8d37e3e327](https://linux-hardware.org/?probe=8d37e3e327) | Nov 29, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [e41751f26a](https://linux-hardware.org/?probe=e41751f26a) | Nov 29, 2022 |
| Notebook      | L140PU                      | Notebook    | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Pegatron      | VIOLET                      | Desktop     | [f0f25e6854](https://linux-hardware.org/?probe=f0f25e6854) | Nov 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [b565b4082e](https://linux-hardware.org/?probe=b565b4082e) | Nov 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [90f931841d](https://linux-hardware.org/?probe=90f931841d) | Nov 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [111f6a1fc2](https://linux-hardware.org/?probe=111f6a1fc2) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | Notebook    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b5ed1b189a](https://linux-hardware.org/?probe=b5ed1b189a) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b25dd25478](https://linux-hardware.org/?probe=b25dd25478) | Nov 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| HP            | 212B                        | Desktop     | [574a94ad86](https://linux-hardware.org/?probe=574a94ad86) | Nov 18, 2022 |
| HP            | 212B                        | Desktop     | [3995268826](https://linux-hardware.org/?probe=3995268826) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | Notebook    | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | Notebook    | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | Notebook    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c6c7120833](https://linux-hardware.org/?probe=c6c7120833) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2053688baa](https://linux-hardware.org/?probe=2053688baa) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [15f6c6a1aa](https://linux-hardware.org/?probe=15f6c6a1aa) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [f320cc2659](https://linux-hardware.org/?probe=f320cc2659) | Nov 11, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [33a4a1ea9a](https://linux-hardware.org/?probe=33a4a1ea9a) | Nov 09, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ff7014b9b8](https://linux-hardware.org/?probe=ff7014b9b8) | Nov 06, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| HP            | 8458                        | Mini pc     | [4da864256d](https://linux-hardware.org/?probe=4da864256d) | Nov 03, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fd4d484f61](https://linux-hardware.org/?probe=fd4d484f61) | Nov 02, 2022 |
| Dell          | Precision 5520              | Notebook    | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | Notebook    | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| HP            | 3396                        | Desktop     | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [9a540d96f5](https://linux-hardware.org/?probe=9a540d96f5) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c55b37c393](https://linux-hardware.org/?probe=c55b37c393) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b81dd63334](https://linux-hardware.org/?probe=b81dd63334) | Oct 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [55a46537f8](https://linux-hardware.org/?probe=55a46537f8) | Oct 21, 2022 |
| Medion        | S15449                      | Notebook    | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a83d0f0ade](https://linux-hardware.org/?probe=a83d0f0ade) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| HP            | 829A                        | Mini pc     | [3470bd9a76](https://linux-hardware.org/?probe=3470bd9a76) | Oct 17, 2022 |
| HP            | 829A                        | Mini pc     | [3ab01040ef](https://linux-hardware.org/?probe=3ab01040ef) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | Notebook    | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [9d2cf83f81](https://linux-hardware.org/?probe=9d2cf83f81) | Oct 12, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [feb997ebfc](https://linux-hardware.org/?probe=feb997ebfc) | Oct 12, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [10e153f71e](https://linux-hardware.org/?probe=10e153f71e) | Oct 10, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [7f03ff4490](https://linux-hardware.org/?probe=7f03ff4490) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | Notebook    | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [24da875cf7](https://linux-hardware.org/?probe=24da875cf7) | Oct 04, 2022 |
| HP            | 213D A01                    | Desktop     | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6a5067b548](https://linux-hardware.org/?probe=6a5067b548) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2044c11c98](https://linux-hardware.org/?probe=2044c11c98) | Oct 02, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| MSI           | 2A9C                        | Desktop     | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [5e38213b3b](https://linux-hardware.org/?probe=5e38213b3b) | Sep 30, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [6c3ab0f793](https://linux-hardware.org/?probe=6c3ab0f793) | Sep 27, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3c87156766](https://linux-hardware.org/?probe=3c87156766) | Sep 25, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6f492f55c3](https://linux-hardware.org/?probe=6f492f55c3) | Sep 24, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [75ed13ea90](https://linux-hardware.org/?probe=75ed13ea90) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [f9c071cdd8](https://linux-hardware.org/?probe=f9c071cdd8) | Sep 23, 2022 |
| System76      | Darter Pro                  | Notebook    | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| HP            | 8053                        | Desktop     | [d46ac6d7db](https://linux-hardware.org/?probe=d46ac6d7db) | Sep 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [074a9f8433](https://linux-hardware.org/?probe=074a9f8433) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3aa36dda04](https://linux-hardware.org/?probe=3aa36dda04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [ec15390099](https://linux-hardware.org/?probe=ec15390099) | Sep 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c54a63e1a3](https://linux-hardware.org/?probe=c54a63e1a3) | Sep 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [4aa1954c0c](https://linux-hardware.org/?probe=4aa1954c0c) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e2d13711aa](https://linux-hardware.org/?probe=e2d13711aa) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | Notebook    | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [ce9d09e18a](https://linux-hardware.org/?probe=ce9d09e18a) | Sep 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [6a4fa8ebe7](https://linux-hardware.org/?probe=6a4fa8ebe7) | Sep 09, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [965f8fe14d](https://linux-hardware.org/?probe=965f8fe14d) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [6c5483e3f5](https://linux-hardware.org/?probe=6c5483e3f5) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| Dell          | 0GN6JF A01                  | Desktop     | [390fbaaca7](https://linux-hardware.org/?probe=390fbaaca7) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| Acer          | Aspire S5-371               | Notebook    | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |
| Acer          | Aspire 5942                 | Notebook    | [c2c893f2c2](https://linux-hardware.org/?probe=c2c893f2c2) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [4808984401](https://linux-hardware.org/?probe=4808984401) | Aug 31, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39faa4acc5](https://linux-hardware.org/?probe=39faa4acc5) | Aug 31, 2022 |
| Lenovo        | ThinkPad P43s 20RJS0D100    | Notebook    | [afbf0f6021](https://linux-hardware.org/?probe=afbf0f6021) | Aug 31, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | Notebook    | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| HP            | 2B36                        | Desktop     | [c6de6225af](https://linux-hardware.org/?probe=c6de6225af) | Aug 29, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [eb19c533e0](https://linux-hardware.org/?probe=eb19c533e0) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [8f0f345242](https://linux-hardware.org/?probe=8f0f345242) | Aug 28, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [9edb57e041](https://linux-hardware.org/?probe=9edb57e041) | Aug 28, 2022 |
| Acer          | V3-771                      | Notebook    | [3efe8f2f41](https://linux-hardware.org/?probe=3efe8f2f41) | Aug 28, 2022 |
| Shuttle       | DS437                       | Notebook    | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| Acer          | Aspire 5942                 | Notebook    | [528e0a954b](https://linux-hardware.org/?probe=528e0a954b) | Aug 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| Unknown       | Unknown                     | All in one  | [da8e3c67be](https://linux-hardware.org/?probe=da8e3c67be) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| HP            | 2B36                        | Desktop     | [9890b96e0e](https://linux-hardware.org/?probe=9890b96e0e) | Aug 21, 2022 |
| HP            | 212B                        | Desktop     | [ba5bf87e58](https://linux-hardware.org/?probe=ba5bf87e58) | Aug 21, 2022 |
| Acer          | Predator G9-791             | Notebook    | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8a48025d15](https://linux-hardware.org/?probe=8a48025d15) | Aug 18, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [d0c25e4ba8](https://linux-hardware.org/?probe=d0c25e4ba8) | Aug 17, 2022 |
| ASUSTek       | Berkeley                    | Desktop     | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [98ea1068a3](https://linux-hardware.org/?probe=98ea1068a3) | Aug 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fee71ca4bf](https://linux-hardware.org/?probe=fee71ca4bf) | Aug 15, 2022 |
| Acer          | Aspire XC-605               | Desktop     | [125a8c791a](https://linux-hardware.org/?probe=125a8c791a) | Aug 14, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| HP            | Unknown                     | Notebook    | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [7d2cd4cc35](https://linux-hardware.org/?probe=7d2cd4cc35) | Aug 11, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [7e2bf60517](https://linux-hardware.org/?probe=7e2bf60517) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASUSTek       | H81T                        | Desktop     | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [49098497d4](https://linux-hardware.org/?probe=49098497d4) | Aug 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [06422a72b8](https://linux-hardware.org/?probe=06422a72b8) | Aug 08, 2022 |
| ASRock        | 880GM-LE FX                 | Desktop     | [957edc332a](https://linux-hardware.org/?probe=957edc332a) | Aug 06, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [283eb3c040](https://linux-hardware.org/?probe=283eb3c040) | Aug 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [42cb82f584](https://linux-hardware.org/?probe=42cb82f584) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [e82d9ce558](https://linux-hardware.org/?probe=e82d9ce558) | Jul 29, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [9cb4896eba](https://linux-hardware.org/?probe=9cb4896eba) | Jul 28, 2022 |
| Lenovo        | ThinkPad T470s 20HGS36K0... | Notebook    | [caf10d48a0](https://linux-hardware.org/?probe=caf10d48a0) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| Lenovo        | ThinkPad P51 20HH001RMZ     | Notebook    | [3fee9267ba](https://linux-hardware.org/?probe=3fee9267ba) | Jul 27, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [c086eb22b3](https://linux-hardware.org/?probe=c086eb22b3) | Jul 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [44a5e2107e](https://linux-hardware.org/?probe=44a5e2107e) | Jul 27, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [5b5fe46f75](https://linux-hardware.org/?probe=5b5fe46f75) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a3e446c9e](https://linux-hardware.org/?probe=9a3e446c9e) | Jul 26, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [e8da564bb8](https://linux-hardware.org/?probe=e8da564bb8) | Jul 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [7d3501365a](https://linux-hardware.org/?probe=7d3501365a) | Jul 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [e80a3e71e2](https://linux-hardware.org/?probe=e80a3e71e2) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Alienware     | 17 R5                       | Notebook    | [29b538f1c0](https://linux-hardware.org/?probe=29b538f1c0) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| HP            | 1998                        | Desktop     | [8aa7e05c70](https://linux-hardware.org/?probe=8aa7e05c70) | Jul 17, 2022 |
| Acer          | V3-771                      | Notebook    | [809bd80b9a](https://linux-hardware.org/?probe=809bd80b9a) | Jul 17, 2022 |
| Lenovo        | ThinkPad T410 25379UG       | Notebook    | [00478c63ba](https://linux-hardware.org/?probe=00478c63ba) | Jul 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [41c6118825](https://linux-hardware.org/?probe=41c6118825) | Jul 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [6db5d85e5c](https://linux-hardware.org/?probe=6db5d85e5c) | Jul 13, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f5982952c2](https://linux-hardware.org/?probe=f5982952c2) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2435f08ee8](https://linux-hardware.org/?probe=2435f08ee8) | Jul 10, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [0e5d573899](https://linux-hardware.org/?probe=0e5d573899) | Jul 09, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [3dc1d7b18a](https://linux-hardware.org/?probe=3dc1d7b18a) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [c58559e78c](https://linux-hardware.org/?probe=c58559e78c) | Jul 09, 2022 |
| Unknown       | Unknown                     | Tablet      | [bf70ad93f5](https://linux-hardware.org/?probe=bf70ad93f5) | Jul 06, 2022 |
| Unknown       | Unknown                     | Tablet      | [6edba7f033](https://linux-hardware.org/?probe=6edba7f033) | Jul 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [ee1a040981](https://linux-hardware.org/?probe=ee1a040981) | Jul 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5819973ca4](https://linux-hardware.org/?probe=5819973ca4) | Jul 05, 2022 |
| MSI           | GE62 2QF                    | Notebook    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6fa5768750](https://linux-hardware.org/?probe=6fa5768750) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [564950d244](https://linux-hardware.org/?probe=564950d244) | Jul 02, 2022 |
| Medion        | MS-7667                     | Desktop     | [22ac257e4a](https://linux-hardware.org/?probe=22ac257e4a) | Jul 02, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [0d40af60b2](https://linux-hardware.org/?probe=0d40af60b2) | Jul 01, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21cba60be3](https://linux-hardware.org/?probe=21cba60be3) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [0dcbb35983](https://linux-hardware.org/?probe=0dcbb35983) | Jun 30, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [a2729b2e3b](https://linux-hardware.org/?probe=a2729b2e3b) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [d8190f3da8](https://linux-hardware.org/?probe=d8190f3da8) | Jun 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [9f64d5f095](https://linux-hardware.org/?probe=9f64d5f095) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Dell          | Precision M6800             | Notebook    | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [00ce30e950](https://linux-hardware.org/?probe=00ce30e950) | Jun 28, 2022 |
| MSI           | 2A9C                        | Desktop     | [c4d999a9a5](https://linux-hardware.org/?probe=c4d999a9a5) | Jun 26, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [800f6f5802](https://linux-hardware.org/?probe=800f6f5802) | Jun 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2103486702](https://linux-hardware.org/?probe=2103486702) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [62aec95456](https://linux-hardware.org/?probe=62aec95456) | Jun 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | Desktop     | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| Intel         | NUC11PHBi7 M26151-403       | Mini pc     | [7c3f1cd4c1](https://linux-hardware.org/?probe=7c3f1cd4c1) | Jun 21, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [5cde38b27f](https://linux-hardware.org/?probe=5cde38b27f) | Jun 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [6ec8ece12d](https://linux-hardware.org/?probe=6ec8ece12d) | Jun 19, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21f78f9cf4](https://linux-hardware.org/?probe=21f78f9cf4) | Jun 19, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [d84600d5b0](https://linux-hardware.org/?probe=d84600d5b0) | Jun 17, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [de123e03c3](https://linux-hardware.org/?probe=de123e03c3) | Jun 16, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [31aa19ff98](https://linux-hardware.org/?probe=31aa19ff98) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Clevo         | W150ER                      | Notebook    | [9121da24a8](https://linux-hardware.org/?probe=9121da24a8) | Jun 13, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | Notebook    | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| Microsoft     | Surface Book 3              | Tablet      | [26c417012f](https://linux-hardware.org/?probe=26c417012f) | Jun 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b31c452186](https://linux-hardware.org/?probe=b31c452186) | Jun 11, 2022 |
| HP            | 3032h                       | Desktop     | [fee76c58db](https://linux-hardware.org/?probe=fee76c58db) | Jun 09, 2022 |
| HP            | 8710                        | Mini pc     | [a4b6fd8f8a](https://linux-hardware.org/?probe=a4b6fd8f8a) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [6a14acf011](https://linux-hardware.org/?probe=6a14acf011) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0fbc627b7e](https://linux-hardware.org/?probe=0fbc627b7e) | Jun 07, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Shuttle       | DS10U                       | Desktop     | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [878cae499d](https://linux-hardware.org/?probe=878cae499d) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [0c53f7240c](https://linux-hardware.org/?probe=0c53f7240c) | Jun 03, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | Notebook    | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d8134fd2fe](https://linux-hardware.org/?probe=d8134fd2fe) | Jun 02, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [1fb17fc133](https://linux-hardware.org/?probe=1fb17fc133) | Jun 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [d4283c0b8b](https://linux-hardware.org/?probe=d4283c0b8b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e474768a25](https://linux-hardware.org/?probe=e474768a25) | May 30, 2022 |
| Minix         | NEO Z83-4A V1.1             | Desktop     | [e828d9bd38](https://linux-hardware.org/?probe=e828d9bd38) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [03a4099a33](https://linux-hardware.org/?probe=03a4099a33) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [cde5dba599](https://linux-hardware.org/?probe=cde5dba599) | May 27, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [e6ee61fdd8](https://linux-hardware.org/?probe=e6ee61fdd8) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| Lenovo        | V320-17IKB 81AH             | Notebook    | [c5d9a03264](https://linux-hardware.org/?probe=c5d9a03264) | May 27, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [6c7cfb5226](https://linux-hardware.org/?probe=6c7cfb5226) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [41529bd0e1](https://linux-hardware.org/?probe=41529bd0e1) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [da6bd78cdb](https://linux-hardware.org/?probe=da6bd78cdb) | May 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [071bc80c0b](https://linux-hardware.org/?probe=071bc80c0b) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [5f505dd767](https://linux-hardware.org/?probe=5f505dd767) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| HP            | 8703                        | Desktop     | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| Timi          | TM1613                      | Notebook    | [695d8d5ff0](https://linux-hardware.org/?probe=695d8d5ff0) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [da6b66b74f](https://linux-hardware.org/?probe=da6b66b74f) | May 21, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Acer          | V3-771                      | Notebook    | [8bcab66496](https://linux-hardware.org/?probe=8bcab66496) | May 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 301       | 12.73%  |
| Ubuntu 18.04                 | 271       | 11.46%  |
| Ubuntu 22.04                 | 207       | 8.75%   |
| Debian 11                    | 93        | 3.93%   |
| Linux Mint 20.3              | 56        | 2.37%   |
| OpenMandriva 4.3             | 43        | 1.82%   |
| Debian 10                    | 40        | 1.69%   |
| Ubuntu 21.10                 | 38        | 1.61%   |
| Linux Mint 20.2              | 36        | 1.52%   |
| Linux Mint 20.1              | 36        | 1.52%   |
| KDE neon 20.04               | 36        | 1.52%   |
| openSUSE Tumbleweed-XXXXXXXX | 35        | 1.48%   |
| Arch Rolling                 | 33        | 1.4%    |
| Zorin 16                     | 30        | 1.27%   |
| OpenMandriva 4.2             | 30        | 1.27%   |
| Arch                         | 28        | 1.18%   |
| Pop!_OS 22.04                | 27        | 1.14%   |
| Linux Mint 21.1              | 26        | 1.1%    |
| Ubuntu 20.10                 | 25        | 1.06%   |
| Fedora 32                    | 24        | 1.01%   |
| OpenMandriva 23.01           | 23        | 0.97%   |
| Manjaro                      | 23        | 0.97%   |
| Fedora 37                    | 23        | 0.97%   |
| Ubuntu 22.10                 | 22        | 0.93%   |
| Ubuntu 21.04                 | 22        | 0.93%   |
| Fedora 34                    | 22        | 0.93%   |
| Ubuntu 19.10                 | 21        | 0.89%   |
| Pop!_OS 21.04                | 21        | 0.89%   |
| Pop!_OS 20.10                | 21        | 0.89%   |
| Pop!_OS 20.04                | 21        | 0.89%   |
| Fedora 33                    | 21        | 0.89%   |
| ArcoLinux Rolling            | 21        | 0.89%   |
| Ubuntu 19.04                 | 20        | 0.85%   |
| Fedora 35                    | 20        | 0.85%   |
| Linux Mint 19.3              | 18        | 0.76%   |
| Fedora 36                    | 16        | 0.68%   |
| Zorin 15                     | 15        | 0.63%   |
| Linux Mint 21                | 15        | 0.63%   |
| Kubuntu 20.04                | 15        | 0.63%   |
| Fedora 38                    | 15        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 858       | 39.54%  |
| Linux Mint    | 189       | 8.71%   |
| Debian        | 163       | 7.51%   |
| Fedora        | 144       | 6.64%   |
| OpenMandriva  | 119       | 5.48%   |
| Pop!_OS       | 89        | 4.1%    |
| Manjaro       | 65        | 3%      |
| Arch          | 60        | 2.76%   |
| openSUSE      | 47        | 2.17%   |
| Zorin         | 45        | 2.07%   |
| Kubuntu       | 44        | 2.03%   |
| KDE neon      | 41        | 1.89%   |
| ROSA          | 26        | 1.2%    |
| ArcoLinux     | 24        | 1.11%   |
| Xubuntu       | 22        | 1.01%   |
| Kali          | 18        | 0.83%   |
| Gentoo        | 18        | 0.83%   |
| Ubuntu MATE   | 17        | 0.78%   |
| Lubuntu       | 15        | 0.69%   |
| Elementary    | 14        | 0.65%   |
| CentOS        | 12        | 0.55%   |
| Ubuntu Budgie | 10        | 0.46%   |
| Feren OS      | 10        | 0.46%   |
| Clear Linux   | 9         | 0.41%   |
| EndeavourOS   | 8         | 0.37%   |
| Ubuntu Unity  | 7         | 0.32%   |
| LMDE          | 7         | 0.32%   |
| Endless       | 7         | 0.32%   |
| BlackPanther  | 7         | 0.32%   |
| MX            | 6         | 0.28%   |
| SteamOS       | 4         | 0.18%   |
| RHEL          | 4         | 0.18%   |
| NixOS         | 4         | 0.18%   |
| Garuda Linux  | 4         | 0.18%   |
| Artix         | 4         | 0.18%   |
| Void Linux    | 3         | 0.14%   |
| Virtuozzo     | 3         | 0.14%   |
| TUXEDO OS     | 3         | 0.14%   |
| Solus         | 3         | 0.14%   |
| Parrot        | 3         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 1.66%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.44%   |
| 5.15.0-67-generic        | 35        | 1.32%   |
| 5.4.0-42-generic         | 32        | 1.21%   |
| 5.15.0-58-generic        | 32        | 1.21%   |
| 5.15.0-56-generic        | 31        | 1.17%   |
| 5.15.0-69-generic        | 30        | 1.13%   |
| 5.10.14-desktop-1omv4002 | 29        | 1.1%    |
| 4.15.0-91-generic        | 27        | 1.02%   |
| 5.15.0-46-generic        | 25        | 0.95%   |
| 5.4.0-52-generic         | 22        | 0.83%   |
| 5.4.0-48-generic         | 22        | 0.83%   |
| 5.19.0-35-generic        | 22        | 0.83%   |
| 4.15.0-96-generic        | 22        | 0.83%   |
| 5.4.0-58-generic         | 21        | 0.79%   |
| 6.1.1-desktop-1omv2290   | 19        | 0.72%   |
| 5.10.0-8-arm64           | 17        | 0.64%   |
| 5.8.0-43-generic         | 15        | 0.57%   |
| 5.4.0-91-generic         | 15        | 0.57%   |
| 5.10.0-21-amd64          | 15        | 0.57%   |
| 5.15.0-60-generic        | 14        | 0.53%   |
| 5.13.0-35-generic        | 14        | 0.53%   |
| 5.4.0-80-generic         | 13        | 0.49%   |
| 5.4.0-26-generic         | 13        | 0.49%   |
| 5.15.0-52-generic        | 13        | 0.49%   |
| 5.11.0-43-generic        | 13        | 0.49%   |
| 5.11.0-27-generic        | 13        | 0.49%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.45%   |
| 5.4.0-81-generic         | 12        | 0.45%   |
| 5.4.0-47-generic         | 12        | 0.45%   |
| 5.15.0-48-generic        | 12        | 0.45%   |
| 5.15.0-43-generic        | 12        | 0.45%   |
| 5.13.0-39-generic        | 12        | 0.45%   |
| 5.13.0-30-generic        | 12        | 0.45%   |
| 5.10.0-8-amd64           | 12        | 0.45%   |
| 5.0.0-37-generic         | 12        | 0.45%   |
| 5.8.0-55-generic         | 11        | 0.42%   |
| 5.8.0-53-generic         | 11        | 0.42%   |
| 5.8.0-48-generic         | 11        | 0.42%   |
| 5.8.0-44-generic         | 11        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 375       | 15.21%  |
| 5.15.0  | 284       | 11.52%  |
| 4.15.0  | 205       | 8.32%   |
| 5.8.0   | 128       | 5.19%   |
| 5.11.0  | 117       | 4.75%   |
| 5.13.0  | 107       | 4.34%   |
| 5.10.0  | 94        | 3.81%   |
| 5.3.0   | 72        | 2.92%   |
| 5.19.0  | 72        | 2.92%   |
| 5.0.0   | 50        | 2.03%   |
| 4.18.0  | 41        | 1.66%   |
| 5.16.7  | 39        | 1.58%   |
| 4.19.0  | 37        | 1.5%    |
| 5.10.14 | 30        | 1.22%   |
| 6.1.1   | 23        | 0.93%   |
| 6.2.0   | 18        | 0.73%   |
| 6.2.6   | 17        | 0.69%   |
| 6.1.0   | 16        | 0.65%   |
| 5.14.0  | 15        | 0.61%   |
| 5.17.5  | 13        | 0.53%   |
| 6.0.0   | 12        | 0.49%   |
| 5.6.0   | 11        | 0.45%   |
| 5.7.0   | 9         | 0.37%   |
| 5.18.0  | 9         | 0.37%   |
| 5.16.13 | 8         | 0.32%   |
| 3.10.0  | 8         | 0.32%   |
| 6.0.12  | 7         | 0.28%   |
| 5.10.7  | 7         | 0.28%   |
| 4.9.60  | 7         | 0.28%   |
| 6.0.7   | 6         | 0.24%   |
| 6.0.15  | 6         | 0.24%   |
| 5.6.14  | 6         | 0.24%   |
| 5.3.18  | 6         | 0.24%   |
| 5.16.0  | 6         | 0.24%   |
| 4.18.16 | 6         | 0.24%   |
| 5.9.16  | 5         | 0.2%    |
| 5.9.11  | 5         | 0.2%    |
| 5.7.1   | 5         | 0.2%    |
| 5.6.15  | 5         | 0.2%    |
| 5.17.1  | 5         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 394       | 16.27%  |
| 5.15    | 338       | 13.96%  |
| 4.15    | 206       | 8.51%   |
| 5.10    | 164       | 6.77%   |
| 5.8     | 161       | 6.65%   |
| 5.11    | 146       | 6.03%   |
| 5.13    | 124       | 5.12%   |
| 5.3     | 85        | 3.51%   |
| 5.19    | 85        | 3.51%   |
| 5.16    | 75        | 3.1%    |
| 6.1     | 63        | 2.6%    |
| 6.2     | 58        | 2.39%   |
| 5.0     | 55        | 2.27%   |
| 6.0     | 50        | 2.06%   |
| 4.18    | 49        | 2.02%   |
| 4.19    | 44        | 1.82%   |
| 5.6     | 41        | 1.69%   |
| 5.17    | 38        | 1.57%   |
| 5.14    | 38        | 1.57%   |
| 5.9     | 29        | 1.2%    |
| 5.7     | 29        | 1.2%    |
| 5.18    | 28        | 1.16%   |
| 5.12    | 25        | 1.03%   |
| 4.9     | 23        | 0.95%   |
| 6.3     | 19        | 0.78%   |
| 5.5     | 11        | 0.45%   |
| 3.10    | 8         | 0.33%   |
| 4.4     | 5         | 0.21%   |
| 4.14    | 4         | 0.17%   |
| 5.2     | 3         | 0.12%   |
| 4.20    | 3         | 0.12%   |
| 4.13    | 3         | 0.12%   |
| 4.1     | 3         | 0.12%   |
| 2.6     | 3         | 0.12%   |
| 4.10    | 2         | 0.08%   |
| 3.16    | 2         | 0.08%   |
| 5.1     | 1         | 0.04%   |
| 5       | 1         | 0.04%   |
| 4.2     | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2021      | 96.42%  |
| aarch64 | 40        | 1.91%   |
| i686    | 33        | 1.57%   |
| armv8l  | 1         | 0.05%   |
| armv7l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 878       | 40.09%  |
| KDE5            | 325       | 14.84%  |
| Unknown         | 310       | 14.16%  |
| GNUstep         | 153       | 6.99%   |
| X-Cinnamon      | 148       | 6.76%   |
| XFCE            | 105       | 4.79%   |
| MATE            | 56        | 2.56%   |
| KDE             | 43        | 1.96%   |
| Cinnamon        | 34        | 1.55%   |
| LXQt            | 21        | 0.96%   |
| LXDE            | 16        | 0.73%   |
| KDE4            | 16        | 0.73%   |
| Pantheon        | 15        | 0.68%   |
| Budgie          | 15        | 0.68%   |
| i3              | 14        | 0.64%   |
| GNOME Flashback | 12        | 0.55%   |
| Unity           | 6         | 0.27%   |
| bspwm           | 5         | 0.23%   |
| qtile           | 4         | 0.18%   |
| Trinity         | 2         | 0.09%   |
| sway            | 2         | 0.09%   |
| GNOME Classic   | 2         | 0.09%   |
| DWM             | 2         | 0.09%   |
| xmonad          | 1         | 0.05%   |
| openbox         | 1         | 0.05%   |
| none+awesome    | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| herbstluftwm    | 1         | 0.05%   |
| fluxbox         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1510      | 67.9%   |
| Wayland | 377       | 16.95%  |
| Unknown | 177       | 7.96%   |
| Tty     | 157       | 7.06%   |
| Web     | 3         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 918       | 41.73%  |
| LightDM | 384       | 17.45%  |
| SDDM    | 286       | 13%     |
| GDM     | 272       | 12.36%  |
| GDM3    | 235       | 10.68%  |
| TDM     | 80        | 3.64%   |
| KDM     | 15        | 0.68%   |
| XDM     | 4         | 0.18%   |
| SLiM    | 3         | 0.14%   |
| NODM    | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 775       | 35.18%  |
| de_CH      | 499       | 22.65%  |
| Unknown    | 352       | 15.98%  |
| fr_CH      | 149       | 6.76%   |
| de_DE      | 131       | 5.95%   |
| en_GB      | 96        | 4.36%   |
| fr_FR      | 44        | 2%      |
| C          | 44        | 2%      |
| pt_PT      | 17        | 0.77%   |
| it_CH      | 17        | 0.77%   |
| it_IT      | 16        | 0.73%   |
| es_ES      | 9         | 0.41%   |
| pl_PL      | 8         | 0.36%   |
| ru_RU      | 7         | 0.32%   |
| en_CH      | 6         | 0.27%   |
| en_AU      | 4         | 0.18%   |
| de_AT      | 4         | 0.18%   |
| POSIX      | 3         | 0.14%   |
| en_IE      | 3         | 0.14%   |
| en_CA      | 2         | 0.09%   |
| de_IT      | 2         | 0.09%   |
| tr_TR      | 1         | 0.05%   |
| sk_SK      | 1         | 0.05%   |
| ru_UA      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| nl_BE      | 1         | 0.05%   |
| hu_HU      | 1         | 0.05%   |
| hsb_DE     | 1         | 0.05%   |
| gsw_CH     | 1         | 0.05%   |
| fr_CA      | 1         | 0.05%   |
| en_AG      | 1         | 0.05%   |
| de_LI      | 1         | 0.05%   |
| de_CH.UTF8 | 1         | 0.05%   |
| cs_CZ      | 1         | 0.05%   |
| ca_ES      | 1         | 0.05%   |
| C.UTF8     | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1199      | 56%     |
| BIOS | 942       | 44%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1681      | 78.22%  |
| Btrfs   | 183       | 8.52%   |
| Overlay | 134       | 6.24%   |
| Unknown | 65        | 3.02%   |
| Xfs     | 41        | 1.91%   |
| Tmpfs   | 14        | 0.65%   |
| Zfs     | 13        | 0.6%    |
| Ext2    | 6         | 0.28%   |
| Ext3    | 5         | 0.23%   |
| F2fs    | 4         | 0.19%   |
| Jfs     | 1         | 0.05%   |
| ExX4    | 1         | 0.05%   |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 987       | 45.97%  |
| Unknown | 927       | 43.18%  |
| MBR     | 233       | 10.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1817      | 84.71%  |
| Yes       | 328       | 15.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1604      | 75.2%   |
| Yes       | 529       | 24.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 394       | 18.82%  |
| Hewlett-Packard         | 347       | 16.57%  |
| Lenovo                  | 340       | 16.24%  |
| Dell                    | 165       | 7.88%   |
| Acer                    | 119       | 5.68%   |
| Gigabyte Technology     | 91        | 4.35%   |
| Apple                   | 83        | 3.96%   |
| MSI                     | 68        | 3.25%   |
| Intel                   | 67        | 3.2%    |
| ASRock                  | 64        | 3.06%   |
| Fujitsu                 | 38        | 1.81%   |
| Raspberry Pi Foundation | 34        | 1.62%   |
| Medion                  | 29        | 1.38%   |
| Supermicro              | 19        | 0.91%   |
| Toshiba                 | 17        | 0.81%   |
| Microsoft               | 16        | 0.76%   |
| Sony                    | 14        | 0.67%   |
| TUXEDO                  | 12        | 0.57%   |
| Samsung Electronics     | 12        | 0.57%   |
| Notebook                | 12        | 0.57%   |
| Unknown                 | 11        | 0.53%   |
| Shuttle                 | 9         | 0.43%   |
| HUAWEI                  | 9         | 0.43%   |
| ZOTAC                   | 8         | 0.38%   |
| TrekStor                | 7         | 0.33%   |
| Pegatron                | 7         | 0.33%   |
| PC Engines              | 7         | 0.33%   |
| Razer                   | 6         | 0.29%   |
| DALCO AG Switzerland    | 6         | 0.29%   |
| Packard Bell            | 5         | 0.24%   |
| Alienware               | 5         | 0.24%   |
| Valve                   | 4         | 0.19%   |
| Schenker                | 4         | 0.19%   |
| Timi                    | 3         | 0.14%   |
| GPD                     | 3         | 0.14%   |
| Fujitsu Siemens         | 3         | 0.14%   |
| Clevo                   | 3         | 0.14%   |
| Biostar                 | 3         | 0.14%   |
| AMI                     | 3         | 0.14%   |
| whyopencomputing        | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 34        | 1.62%   |
| Unknown                                    | 18        | 0.86%   |
| ASUS PRIME Z590-P                          | 17        | 0.81%   |
| Fujitsu CELSIUS_W550                       | 12        | 0.57%   |
| ASUS PRIME X570-PRO                        | 12        | 0.57%   |
| ASUS ROG STRIX X570-E GAMING               | 11        | 0.53%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 10        | 0.48%   |
| ASUS PRIME B550M-A                         | 10        | 0.48%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 9         | 0.43%   |
| RPi Raspberry Pi 3 Model B Rev 1.2         | 8         | 0.38%   |
| HP Pavilion dv7                            | 8         | 0.38%   |
| ASUS STRIX Z270F GAMING                    | 8         | 0.38%   |
| Dell Latitude 7490                         | 7         | 0.33%   |
| ASUS P9X79 WS                              | 7         | 0.33%   |
| ASUS P8Z77-V LX                            | 7         | 0.33%   |
| MSI MS-7C02                                | 6         | 0.29%   |
| Microsoft Surface Pro 4                    | 6         | 0.29%   |
| DALCO AG Switzerland +41 44 908 38 38      | 6         | 0.29%   |
| Apple iMac12,2                             | 6         | 0.29%   |
| PC Engines APU2                            | 5         | 0.24%   |
| Intel S4600LH                              | 5         | 0.24%   |
| Intel DP67BA AAG10219-303                  | 5         | 0.24%   |
| HP Pavilion dv6                            | 5         | 0.24%   |
| HP Notebook                                | 5         | 0.24%   |
| HP ENVY 15                                 | 5         | 0.24%   |
| HP EliteDesk 800 G1 SFF                    | 5         | 0.24%   |
| Fujitsu CELSIUS W570                       | 5         | 0.24%   |
| Dell XPS 15 9570                           | 5         | 0.24%   |
| Dell OptiPlex 9020                         | 5         | 0.24%   |
| Dell Latitude E7240                        | 5         | 0.24%   |
| ASUS ROG STRIX Z370-F GAMING               | 5         | 0.24%   |
| Apple MacBookPro9,2                        | 5         | 0.24%   |
| Apple MacBookPro8,1                        | 5         | 0.24%   |
| Apple iMac8,1                              | 5         | 0.24%   |
| Valve Jupiter                              | 4         | 0.19%   |
| Supermicro X8DTN+-F                        | 4         | 0.19%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.19%   |
| Lenovo MIIX 310-10ICR 80SG                 | 4         | 0.19%   |
| Intel NUC8i7BEH                            | 4         | 0.19%   |
| Intel DP55WB AAE64798-207                  | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 218       | 10.41%  |
| ASUS PRIME         | 74        | 3.53%   |
| Acer Aspire        | 71        | 3.39%   |
| ASUS ROG           | 69        | 3.3%    |
| HP EliteBook       | 64        | 3.06%   |
| HP Pavilion        | 55        | 2.63%   |
| Dell XPS           | 48        | 2.29%   |
| Dell Latitude      | 48        | 2.29%   |
| HP ProBook         | 36        | 1.72%   |
| RPi Raspberry      | 34        | 1.62%   |
| HP ENVY            | 34        | 1.62%   |
| ASUS All           | 34        | 1.62%   |
| Lenovo Yoga        | 32        | 1.53%   |
| Dell OptiPlex      | 30        | 1.43%   |
| Fujitsu CELSIUS    | 28        | 1.34%   |
| HP Compaq          | 25        | 1.19%   |
| HP EliteDesk       | 23        | 1.1%    |
| Lenovo IdeaPad     | 21        | 1%      |
| HP Laptop          | 18        | 0.86%   |
| Unknown            | 18        | 0.86%   |
| ASUS TUF           | 17        | 0.81%   |
| Microsoft Surface  | 16        | 0.76%   |
| HP ZBook           | 14        | 0.67%   |
| Dell Inspiron      | 14        | 0.67%   |
| ASUS VivoBook      | 14        | 0.67%   |
| Acer Swift         | 14        | 0.67%   |
| Dell Precision     | 12        | 0.57%   |
| Toshiba Satellite  | 11        | 0.53%   |
| ASUS ZenBook       | 11        | 0.53%   |
| Lenovo ThinkCentre | 10        | 0.48%   |
| HP ProLiant        | 9         | 0.43%   |
| Gigabyte X570      | 9         | 0.43%   |
| ASUS STRIX         | 9         | 0.43%   |
| Acer Predator      | 9         | 0.43%   |
| Lenovo Legion      | 8         | 0.38%   |
| Lenovo IdeaPadFlex | 8         | 0.38%   |
| HP Spectre         | 8         | 0.38%   |
| HP ProDesk         | 8         | 0.38%   |
| HP OMEN            | 8         | 0.38%   |
| ASUS P9X79         | 8         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 219       | 10.46%  |
| 2018    | 215       | 10.27%  |
| 2020    | 200       | 9.55%   |
| 2017    | 168       | 8.02%   |
| 2012    | 155       | 7.4%    |
| 2021    | 140       | 6.69%   |
| 2011    | 137       | 6.54%   |
| 2013    | 124       | 5.92%   |
| 2015    | 121       | 5.78%   |
| 2014    | 120       | 5.73%   |
| 2016    | 112       | 5.35%   |
| 2010    | 96        | 4.58%   |
| 2022    | 69        | 3.3%    |
| 2008    | 62        | 2.96%   |
| 2009    | 56        | 2.67%   |
| 2007    | 35        | 1.67%   |
| Unknown | 29        | 1.38%   |
| 2006    | 15        | 0.72%   |
| 2023    | 11        | 0.53%   |
| 2005    | 6         | 0.29%   |
| 2004    | 3         | 0.14%   |
| 2003    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 955       | 45.61%  |
| Desktop        | 804       | 38.4%   |
| Convertible    | 107       | 5.11%   |
| Mini pc        | 53        | 2.53%   |
| Server         | 50        | 2.39%   |
| All in one     | 47        | 2.24%   |
| System on chip | 39        | 1.86%   |
| Tablet         | 36        | 1.72%   |
| Phone          | 3         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1924      | 91.06%  |
| Enabled  | 189       | 8.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2079      | 99.28%  |
| Yes  | 15        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 535       | 25.04%  |
| 4.01-8.0        | 351       | 16.42%  |
| 32.01-64.0      | 349       | 16.33%  |
| 8.01-16.0       | 334       | 15.63%  |
| 3.01-4.0        | 260       | 12.17%  |
| 64.01-256.0     | 143       | 6.69%   |
| 1.01-2.0        | 55        | 2.57%   |
| 24.01-32.0      | 46        | 2.15%   |
| More than 256.0 | 25        | 1.17%   |
| 0.51-1.0        | 22        | 1.03%   |
| 2.01-3.0        | 16        | 0.75%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 752       | 31.6%   |
| 2.01-3.0        | 535       | 22.48%  |
| 4.01-8.0        | 388       | 16.3%   |
| 3.01-4.0        | 278       | 11.68%  |
| 0.51-1.0        | 173       | 7.27%   |
| 8.01-16.0       | 152       | 6.39%   |
| 0.01-0.5        | 42        | 1.76%   |
| 16.01-24.0      | 26        | 1.09%   |
| 32.01-64.0      | 10        | 0.42%   |
| 24.01-32.0      | 10        | 0.42%   |
| 64.01-256.0     | 8         | 0.34%   |
| Unknown         | 4         | 0.17%   |
| More than 256.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1289      | 59.37%  |
| 2       | 521       | 24%     |
| 3       | 183       | 8.43%   |
| 4       | 68        | 3.13%   |
| 5       | 47        | 2.16%   |
| 6       | 21        | 0.97%   |
| 0       | 20        | 0.92%   |
| 7       | 16        | 0.74%   |
| 14      | 2         | 0.09%   |
| 11      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |
| 8       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1372      | 64.84%  |
| Yes       | 744       | 35.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1793      | 85.06%  |
| No        | 315       | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1489      | 70.64%  |
| No        | 619       | 29.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1247      | 58.79%  |
| No        | 874       | 41.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 2094      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 608       | 26.68%  |
| Bern                               | 108       | 4.74%   |
| Geneva                             | 78        | 3.42%   |
| Lucerne                            | 59        | 2.59%   |
| Lausanne                           | 38        | 1.67%   |
| Basel                              | 38        | 1.67%   |
| Winterthur                         | 36        | 1.58%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 1.45%   |
| Neuchatel                          | 28        | 1.23%   |
| Thun                               | 26        | 1.14%   |
| Lugano                             | 20        | 0.88%   |
| Dietikon                           | 20        | 0.88%   |
| Lyss                               | 18        | 0.79%   |
| Wil                                | 17        | 0.75%   |
| St. Gallen                         | 17        | 0.75%   |
| Aarau                              | 13        | 0.57%   |
| Sion                               | 12        | 0.53%   |
| Munchenstein                       | 12        | 0.53%   |
| Herrliberg                         | 12        | 0.53%   |
| Wettingen                          | 11        | 0.48%   |
| Dubendorf                          | 11        | 0.48%   |
| Biel/Bienne                        | 10        | 0.44%   |
| Willisau                           | 9         | 0.39%   |
| Schaffhausen                       | 9         | 0.39%   |
| Oberwil-Lieli                      | 9         | 0.39%   |
| Ittigen                            | 9         | 0.39%   |
| Glattbrugg                         | 9         | 0.39%   |
| Baden                              | 9         | 0.39%   |
| Zollikofen                         | 8         | 0.35%   |
| Wetzikon                           | 8         | 0.35%   |
| Wallisellen                        | 8         | 0.35%   |
| Uster                              | 8         | 0.35%   |
| Solothurn                          | 8         | 0.35%   |
| Onex                               | 8         | 0.35%   |
| Morges                             | 8         | 0.35%   |
| Kloten                             | 8         | 0.35%   |
| Burgdorf                           | 8         | 0.35%   |
| Bulle                              | 8         | 0.35%   |
| Bulach                             | 8         | 0.35%   |
| Bosingen                           | 8         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 790       | 1420   | 26.39%  |
| WDC                       | 420       | 684    | 14.03%  |
| Seagate                   | 357       | 516    | 11.92%  |
| SanDisk                   | 157       | 197    | 5.24%   |
| Toshiba                   | 144       | 197    | 4.81%   |
| Unknown                   | 143       | 213    | 4.78%   |
| Intel                     | 135       | 193    | 4.51%   |
| Hitachi                   | 95        | 130    | 3.17%   |
| SK hynix                  | 90        | 107    | 3.01%   |
| Crucial                   | 85        | 121    | 2.84%   |
| Kingston                  | 82        | 122    | 2.74%   |
| Micron Technology         | 47        | 61     | 1.57%   |
| Apple                     | 42        | 46     | 1.4%    |
| HGST                      | 35        | 45     | 1.17%   |
| Corsair                   | 27        | 32     | 0.9%    |
| OCZ                       | 25        | 30     | 0.84%   |
| A-DATA Technology         | 23        | 35     | 0.77%   |
| Phison                    | 19        | 30     | 0.63%   |
| LITEON                    | 19        | 25     | 0.63%   |
| Intenso                   | 19        | 20     | 0.63%   |
| LITEONIT                  | 14        | 16     | 0.47%   |
| KIOXIA                    | 14        | 19     | 0.47%   |
| Transcend                 | 13        | 23     | 0.43%   |
| China                     | 13        | 14     | 0.43%   |
| Phison Electronics        | 12        | 21     | 0.4%    |
| ASMT                      | 10        | 15     | 0.33%   |
| Hewlett-Packard           | 9         | 11     | 0.3%    |
| KingSpec                  | 8         | 13     | 0.27%   |
| SPCC                      | 7         | 8      | 0.23%   |
| Plextor                   | 7         | 7      | 0.23%   |
| Fujitsu                   | 7         | 10     | 0.23%   |
| Unknown                   | 7         | 7      | 0.23%   |
| Silicon Motion            | 6         | 7      | 0.2%    |
| Micron/Crucial Technology | 6         | 9      | 0.2%    |
| LaCie                     | 6         | 6      | 0.2%    |
| JMicron Technology        | 6         | 6      | 0.2%    |
| Patriot                   | 5         | 6      | 0.17%   |
| HPE                       | 5         | 12     | 0.17%   |
| PNY                       | 4         | 9      | 0.13%   |
| Maxtor                    | 4         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                           | 42        | 1.25%   |
| Samsung SSD 860 EVO 1TB                             | 35        | 1.04%   |
| Samsung SSD 850 EVO 250GB                           | 34        | 1.01%   |
| Samsung NVMe SSD Drive 1TB                          | 34        | 1.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 29        | 0.86%   |
| Samsung SSD 860 EVO 500GB                           | 27        | 0.8%    |
| Samsung SSD 860 EVO 250GB                           | 27        | 0.8%    |
| Samsung SSD 980 PRO 1TB                             | 26        | 0.77%   |
| Samsung SSD 970 EVO Plus 1TB                        | 26        | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB                      | 24        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.71%   |
| Unknown MMC Card  32GB                              | 21        | 0.62%   |
| Samsung SSD 840 EVO 250GB                           | 19        | 0.56%   |
| Seagate ST2000DM006-2DM164 2TB                      | 18        | 0.53%   |
| Samsung NVMe SSD Drive 500GB                        | 18        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 18        | 0.53%   |
| Unknown MMC Card  128GB                             | 17        | 0.51%   |
| Unknown MMC Card  64GB                              | 16        | 0.48%   |
| Samsung SSD 860 QVO 1TB                             | 15        | 0.45%   |
| Samsung SSD 850 EVO 1TB                             | 15        | 0.45%   |
| HGST HTS721010A9E630 1TB                            | 15        | 0.45%   |
| Seagate Expansion 1TB                               | 14        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                      | 14        | 0.42%   |
| Samsung NVMe SSD Drive 1024GB                       | 14        | 0.42%   |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.39%   |
| Samsung NVMe SSD Drive 256GB                        | 13        | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 12        | 0.36%   |
| SanDisk NVMe SSD Drive 1TB                          | 12        | 0.36%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.36%   |
| Samsung SSD 870 EVO 500GB                           | 12        | 0.36%   |
| Samsung SSD 850 PRO 256GB                           | 12        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB                         | 12        | 0.36%   |
| Unknown SD/MMC/MS PRO 250GB                         | 11        | 0.33%   |
| Samsung SSD 970 EVO Plus 2TB                        | 11        | 0.33%   |
| Samsung SSD 850 PRO 512GB                           | 11        | 0.33%   |
| Samsung SSD 840 PRO Series 256GB                    | 11        | 0.33%   |
| Samsung NVMe SSD Drive 2TB                          | 11        | 0.33%   |
| Samsung HD103SJ 1TB                                 | 11        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 346       | 494    | 36.12%  |
| WDC                 | 314       | 526    | 32.78%  |
| Hitachi             | 95        | 130    | 9.92%   |
| Toshiba             | 74        | 94     | 7.72%   |
| Samsung Electronics | 40        | 58     | 4.18%   |
| HGST                | 35        | 45     | 3.65%   |
| Unknown             | 12        | 13     | 1.25%   |
| Apple               | 9         | 9      | 0.94%   |
| Fujitsu             | 7         | 10     | 0.73%   |
| Maxtor              | 4         | 5      | 0.42%   |
| Intenso             | 4         | 4      | 0.42%   |
| ASMT                | 3         | 4      | 0.31%   |
| HPE                 | 2         | 8      | 0.21%   |
| Hewlett-Packard     | 2         | 4      | 0.21%   |
| ASMedia             | 2         | 2      | 0.21%   |
| USB3.0              | 1         | 2      | 0.1%    |
| Unknown (CF)        | 1         | 1      | 0.1%    |
| MARVELL             | 1         | 1      | 0.1%    |
| IET                 | 1         | 1      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| External            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 429       | 743    | 39.58%  |
| SanDisk             | 94        | 118    | 8.67%   |
| Crucial             | 80        | 116    | 7.38%   |
| Intel               | 66        | 85     | 6.09%   |
| WDC                 | 61        | 81     | 5.63%   |
| Kingston            | 59        | 94     | 5.44%   |
| Toshiba             | 26        | 39     | 2.4%    |
| Micron Technology   | 26        | 37     | 2.4%    |
| Apple               | 26        | 28     | 2.4%    |
| OCZ                 | 25        | 30     | 2.31%   |
| SK hynix            | 19        | 23     | 1.75%   |
| LITEON              | 18        | 24     | 1.66%   |
| A-DATA Technology   | 15        | 24     | 1.38%   |
| LITEONIT            | 14        | 16     | 1.29%   |
| Intenso             | 13        | 14     | 1.2%    |
| Corsair             | 13        | 14     | 1.2%    |
| China               | 13        | 14     | 1.2%    |
| Transcend           | 12        | 22     | 1.11%   |
| KingSpec            | 8         | 13     | 0.74%   |
| Plextor             | 7         | 7      | 0.65%   |
| SPCC                | 6         | 7      | 0.55%   |
| ASMT                | 6         | 10     | 0.55%   |
| Patriot             | 5         | 6      | 0.46%   |
| Seagate             | 3         | 3      | 0.28%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.28%   |
| Hewlett-Packard     | 3         | 4      | 0.28%   |
| PNY                 | 2         | 3      | 0.18%   |
| Mushkin             | 2         | 2      | 0.18%   |
| Initio              | 2         | 2      | 0.18%   |
| HPE                 | 2         | 2      | 0.18%   |
| Dogfish             | 2         | 2      | 0.18%   |
| Adaptec             | 2         | 2      | 0.18%   |
| XSTAR               | 1         | 1      | 0.09%   |
| WDC WDS             | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| Phison              | 1         | 3      | 0.09%   |
| Palit               | 1         | 1      | 0.09%   |
| OWC                 | 1         | 1      | 0.09%   |
| ORICO               | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 948       | 1616   | 34.51%  |
| NVMe    | 815       | 1253   | 29.67%  |
| HDD     | 814       | 1417   | 29.63%  |
| MMC     | 138       | 204    | 5.02%   |
| Unknown | 32        | 48     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1394      | 2920   | 56.48%  |
| NVMe | 810       | 1247   | 32.82%  |
| MMC  | 138       | 204    | 5.59%   |
| SAS  | 126       | 167    | 5.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 944       | 1528   | 49.97%  |
| 0.51-1.0   | 536       | 860    | 28.37%  |
| 1.01-2.0   | 224       | 365    | 11.86%  |
| 3.01-4.0   | 75        | 123    | 3.97%   |
| 2.01-3.0   | 49        | 74     | 2.59%   |
| 4.01-10.0  | 45        | 58     | 2.38%   |
| 10.01-20.0 | 16        | 25     | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 506       | 22.45%  |
| 251-500        | 420       | 18.63%  |
| 501-1000       | 345       | 15.31%  |
| 1001-2000      | 236       | 10.47%  |
| More than 3000 | 167       | 7.41%   |
| 1-20           | 164       | 7.28%   |
| Unknown        | 113       | 5.01%   |
| 2001-3000      | 111       | 4.92%   |
| 51-100         | 111       | 4.92%   |
| 21-50          | 81        | 3.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 791       | 33.8%   |
| 21-50          | 299       | 12.78%  |
| 101-250        | 295       | 12.61%  |
| 51-100         | 256       | 10.94%  |
| 251-500        | 211       | 9.02%   |
| 501-1000       | 172       | 7.35%   |
| Unknown        | 113       | 4.83%   |
| 1001-2000      | 102       | 4.36%   |
| More than 3000 | 71        | 3.03%   |
| 2001-3000      | 30        | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB         | 2         | 2      | 1.42%   |
| WDC WD10EARS-00Y5B1 1TB              | 2         | 2      | 1.42%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 1.42%   |
| Seagate ST3250310AS 250GB            | 2         | 2      | 1.42%   |
| Seagate ST31500341AS 1TB             | 2         | 5      | 1.42%   |
| Samsung Electronics SSD 850 EVO 1TB  | 2         | 2      | 1.42%   |
| Initio 3639S 1TB                     | 2         | 2      | 1.42%   |
| Hitachi HUA722020ALA330 2TB          | 2         | 2      | 1.42%   |
| Hitachi HTS545050B9SA00 500GB        | 2         | 2      | 1.42%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 1.42%   |
| XSTAR SSD 128GB                      | 1         | 1      | 0.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 0.71%   |
| WDC WD5000AAKS-65A7B0 500GB          | 1         | 1      | 0.71%   |
| WDC WD5000AAKS-00TMA0 500GB          | 1         | 1      | 0.71%   |
| WDC WD5000AAKS-00E4A0 500GB          | 1         | 1      | 0.71%   |
| WDC WD40EZRZ-00WN9B0 4TB             | 1         | 1      | 0.71%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 2      | 0.71%   |
| WDC WD3200AAKS-00B3A0 320GB          | 1         | 1      | 0.71%   |
| WDC WD3200AAJS-40VWA1 320GB          | 1         | 1      | 0.71%   |
| WDC WD30EZRX-00D8PB0 3TB             | 1         | 1      | 0.71%   |
| WDC WD2502ABYS-01B7A0 256GB          | 1         | 1      | 0.71%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 1      | 0.71%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 2      | 0.71%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 1      | 0.71%   |
| WDC WD20EARS-00J99B0 2TB             | 1         | 1      | 0.71%   |
| WDC WD1600BEKT-60A25T1 160GB         | 1         | 1      | 0.71%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 0.71%   |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EADS-11M2B3 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 1      | 0.71%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 1      | 0.71%   |
| WDC WD1001FALS-403AA0 1TB            | 1         | 1      | 0.71%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 1      | 0.71%   |
| Toshiba THNSN5256GPUK 256GB          | 1         | 1      | 0.71%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 0.71%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 0.71%   |
| Toshiba MK7575GSX 752GB              | 1         | 3      | 0.71%   |
| Toshiba MK1652GSX 160GB              | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 28     | 18.57%  |
| Seagate             | 22        | 33     | 15.71%  |
| Samsung Electronics | 18        | 21     | 12.86%  |
| Hitachi             | 13        | 14     | 9.29%   |
| Toshiba             | 9         | 11     | 6.43%   |
| SK hynix            | 9         | 10     | 6.43%   |
| Intel               | 8         | 9      | 5.71%   |
| SanDisk             | 5         | 6      | 3.57%   |
| Kingston            | 5         | 6      | 3.57%   |
| HGST                | 4         | 4      | 2.86%   |
| OCZ                 | 3         | 4      | 2.14%   |
| Micron Technology   | 3         | 4      | 2.14%   |
| A-DATA Technology   | 3         | 5      | 2.14%   |
| Initio              | 2         | 2      | 1.43%   |
| Crucial             | 2         | 2      | 1.43%   |
| XSTAR               | 1         | 1      | 0.71%   |
| Patriot             | 1         | 2      | 0.71%   |
| LITEONIT            | 1         | 1      | 0.71%   |
| Intenso             | 1         | 1      | 0.71%   |
| Fujitsu             | 1         | 1      | 0.71%   |
| China               | 1         | 1      | 0.71%   |
| ASMedia             | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 24        | 26     | 30.38%  |
| Seagate             | 22        | 33     | 27.85%  |
| Hitachi             | 13        | 14     | 16.46%  |
| Toshiba             | 8         | 10     | 10.13%  |
| Samsung Electronics | 5         | 6      | 6.33%   |
| HGST                | 4         | 4      | 5.06%   |
| Fujitsu             | 1         | 1      | 1.27%   |
| ASMedia             | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 72        | 96     | 54.14%  |
| SSD  | 50        | 60     | 37.59%  |
| NVMe | 11        | 12     | 8.27%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

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
| Detected | 1176      | 2418   | 51.35%  |
| Works    | 988       | 1951   | 43.14%  |
| Malfunc  | 125       | 168    | 5.46%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1374      | 50.26%  |
| Samsung Electronics            | 414       | 15.14%  |
| AMD                            | 319       | 11.67%  |
| SanDisk                        | 111       | 4.06%   |
| SK hynix                       | 63        | 2.3%    |
| ASMedia Technology             | 61        | 2.23%   |
| Marvell Technology Group       | 55        | 2.01%   |
| Toshiba America Info Systems   | 49        | 1.79%   |
| Phison Electronics             | 44        | 1.61%   |
| JMicron Technology             | 33        | 1.21%   |
| Nvidia                         | 29        | 1.06%   |
| Kingston Technology Company    | 27        | 0.99%   |
| Micron Technology              | 22        | 0.8%    |
| LSI Logic / Symbios Logic      | 16        | 0.59%   |
| KIOXIA                         | 13        | 0.48%   |
| Areca Technology               | 13        | 0.48%   |
| Silicon Motion                 | 11        | 0.4%    |
| Seagate Technology             | 11        | 0.4%    |
| Micron/Crucial Technology      | 9         | 0.33%   |
| ADATA Technology               | 9         | 0.33%   |
| Hewlett-Packard                | 8         | 0.29%   |
| Broadcom / LSI                 | 7         | 0.26%   |
| Apple                          | 5         | 0.18%   |
| Union Memory (Shenzhen)        | 4         | 0.15%   |
| Solid State Storage Technology | 4         | 0.15%   |
| Lite-On Technology             | 4         | 0.15%   |
| Lenovo                         | 4         | 0.15%   |
| Adaptec                        | 4         | 0.15%   |
| VIA Technologies               | 3         | 0.11%   |
| Realtek Semiconductor          | 3         | 0.11%   |
| Silicon Image                  | 2         | 0.07%   |
| Transcend                      | 1         | 0.04%   |
| Tekram Technology              | 1         | 0.04%   |
| Biwin Storage Technology       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 218       | 7.02%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 217       | 6.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 108       | 3.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 87        | 2.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 85        | 2.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 83        | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 67        | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 60        | 1.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 57        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 56        | 1.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 54        | 1.74%   |
| Intel Volume Management Device NVMe RAID Controller                            | 50        | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 50        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 48        | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 43        | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 41        | 1.32%   |
| Intel SATA Controller [RAID mode]                                              | 40        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 38        | 1.22%   |
| Samsung NVMe SSD Controller 980                                                | 37        | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 34        | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 34        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 32        | 1.03%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 32        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 32        | 1.03%   |
| Intel SSD 660P Series                                                          | 30        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 30        | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 29        | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 28        | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 23        | 0.74%   |
| Phison E12 NVMe Controller                                                     | 22        | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 22        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 22        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 22        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 21        | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 21        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1452      | 53.68%  |
| NVMe | 815       | 30.13%  |
| IDE  | 209       | 7.73%   |
| RAID | 203       | 7.5%    |
| SAS  | 25        | 0.92%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1640      | 78.32%  |
| AMD          | 409       | 19.53%  |
| ARM          | 39        | 1.86%   |
| QUALCOMM     | 2         | 0.1%    |
| CentaurHauls | 2         | 0.1%    |
| Unknown      | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 47        | 2.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 44        | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 39        | 1.86%   |
| ARM Processor                              | 38        | 1.81%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 22        | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 21        | 1%      |
| Intel Core i7-6700 CPU @ 3.40GHz           | 21        | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz          | 21        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz          | 21        | 1%      |
| Intel Core i7-2600 CPU @ 3.40GHz           | 20        | 0.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 18        | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 18        | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 18        | 0.86%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 17        | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 16        | 0.76%   |
| Intel 11th Gen Core i9-11900F @ 2.50GHz    | 16        | 0.76%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 16        | 0.76%   |
| AMD Ryzen 5 3600 6-Core Processor          | 16        | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 15        | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 14        | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 14        | 0.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 13        | 0.62%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 13        | 0.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 13        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 13        | 0.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 13        | 0.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.57%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 12        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 12        | 0.57%   |
| Intel 12th Gen Core i7-1260P               | 12        | 0.57%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 11        | 0.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 11        | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 11        | 0.53%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 11        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 10        | 0.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 10        | 0.48%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 10        | 0.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 10        | 0.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 10        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 666       | 31.79%  |
| Intel Core i5           | 408       | 19.47%  |
| Other                   | 198       | 9.45%   |
| AMD Ryzen 7             | 109       | 5.2%    |
| Intel Xeon              | 86        | 4.11%   |
| AMD Ryzen 5             | 84        | 4.01%   |
| Intel Core 2 Duo        | 70        | 3.34%   |
| Intel Core i3           | 57        | 2.72%   |
| Intel Celeron           | 50        | 2.39%   |
| AMD Ryzen 9             | 50        | 2.39%   |
| Intel Atom              | 32        | 1.53%   |
| Intel Pentium           | 28        | 1.34%   |
| Intel Core i9           | 20        | 0.95%   |
| AMD Ryzen 7 PRO         | 20        | 0.95%   |
| AMD FX                  | 20        | 0.95%   |
| Intel Pentium Dual-Core | 14        | 0.67%   |
| Intel Core 2            | 14        | 0.67%   |
| AMD Ryzen Threadripper  | 14        | 0.67%   |
| Intel Core 2 Quad       | 13        | 0.62%   |
| AMD Ryzen 3             | 9         | 0.43%   |
| AMD A8                  | 9         | 0.43%   |
| AMD Quad-Core Opteron   | 8         | 0.38%   |
| AMD GX                  | 8         | 0.38%   |
| Intel Xeon Gold         | 7         | 0.33%   |
| AMD EPYC                | 7         | 0.33%   |
| AMD E                   | 6         | 0.29%   |
| AMD Phenom II X4        | 5         | 0.24%   |
| AMD Opteron             | 5         | 0.24%   |
| AMD Athlon              | 5         | 0.24%   |
| Intel Pentium 4         | 4         | 0.19%   |
| AMD Phenom II X6        | 4         | 0.19%   |
| AMD A10                 | 4         | 0.19%   |
| Intel Pentium Silver    | 3         | 0.14%   |
| Intel Pentium M         | 3         | 0.14%   |
| Intel Genuine           | 3         | 0.14%   |
| Intel Core M            | 3         | 0.14%   |
| AMD Ryzen 5 PRO         | 3         | 0.14%   |
| AMD Phenom              | 3         | 0.14%   |
| AMD E2                  | 3         | 0.14%   |
| AMD E1                  | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 880       | 41.96%  |
| 2       | 579       | 27.61%  |
| 8       | 234       | 11.16%  |
| 6       | 217       | 10.35%  |
| 12      | 58        | 2.77%   |
| 16      | 31        | 1.48%   |
| 1       | 20        | 0.95%   |
| 10      | 18        | 0.86%   |
| 14      | 12        | 0.57%   |
| 24      | 11        | 0.52%   |
| 32      | 10        | 0.48%   |
| 3       | 7         | 0.33%   |
| Unknown | 6         | 0.29%   |
| 40      | 5         | 0.24%   |
| 128     | 3         | 0.14%   |
| 48      | 3         | 0.14%   |
| 64      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2031      | 96.95%  |
| 2       | 48        | 2.29%   |
| 4       | 11        | 0.53%   |
| Unknown | 4         | 0.19%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1549      | 73.66%  |
| 1       | 548       | 26.06%  |
| Unknown | 6         | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2055      | 97.86%  |
| Unknown        | 32        | 1.52%   |
| 32-bit         | 12        | 0.57%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 500       | 22.99%  |
| 0x306a9    | 123       | 5.66%   |
| 0x206a7    | 103       | 4.74%   |
| 0x306c3    | 97        | 4.46%   |
| 0x806ea    | 78        | 3.59%   |
| 0x506e3    | 65        | 2.99%   |
| 0x906ea    | 60        | 2.76%   |
| 0x806ec    | 55        | 2.53%   |
| 0x40651    | 54        | 2.48%   |
| 0x1067a    | 54        | 2.48%   |
| 0x806e9    | 53        | 2.44%   |
| 0x806c1    | 52        | 2.39%   |
| 0x906e9    | 37        | 1.7%    |
| 0x306d4    | 32        | 1.47%   |
| 0x08701021 | 32        | 1.47%   |
| 0x406e3    | 27        | 1.24%   |
| 0x20655    | 25        | 1.15%   |
| 0x30678    | 22        | 1.01%   |
| 0xa0671    | 20        | 0.92%   |
| 0xa0655    | 19        | 0.87%   |
| 0x0a50000c | 19        | 0.87%   |
| 0x0800820d | 19        | 0.87%   |
| 0x706e5    | 18        | 0.83%   |
| 0x10676    | 18        | 0.83%   |
| 0x806eb    | 17        | 0.78%   |
| 0x206d7    | 15        | 0.69%   |
| 0x106e5    | 15        | 0.69%   |
| 0xa0652    | 14        | 0.64%   |
| 0x50654    | 14        | 0.64%   |
| 0x406c4    | 14        | 0.64%   |
| 0x306e4    | 14        | 0.64%   |
| 0x20652    | 14        | 0.64%   |
| 0x0a201016 | 14        | 0.64%   |
| 0x906ed    | 13        | 0.6%    |
| 0x306f2    | 13        | 0.6%    |
| 0x0a404102 | 13        | 0.6%    |
| 0x08701013 | 13        | 0.6%    |
| 0x906a3    | 12        | 0.55%   |
| 0x206c2    | 12        | 0.55%   |
| 0x706a1    | 11        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 410       | 19.54%  |
| Haswell          | 203       | 9.68%   |
| IvyBridge        | 159       | 7.58%   |
| SandyBridge      | 147       | 7.01%   |
| Skylake          | 140       | 6.67%   |
| Unknown          | 117       | 5.58%   |
| Zen 2            | 106       | 5.05%   |
| Penryn           | 83        | 3.96%   |
| Zen 3            | 79        | 3.77%   |
| TigerLake        | 67        | 3.19%   |
| Westmere         | 59        | 2.81%   |
| CometLake        | 52        | 2.48%   |
| Silvermont       | 51        | 2.43%   |
| Broadwell        | 49        | 2.34%   |
| IceLake          | 45        | 2.14%   |
| Zen+             | 43        | 2.05%   |
| Core             | 36        | 1.72%   |
| Nehalem          | 35        | 1.67%   |
| Zen              | 34        | 1.62%   |
| Alderlake Hybrid | 31        | 1.48%   |
| K10              | 30        | 1.43%   |
| Piledriver       | 23        | 1.1%    |
| Goldmont plus    | 17        | 0.81%   |
| Bobcat           | 13        | 0.62%   |
| Goldmont         | 12        | 0.57%   |
| Puma             | 10        | 0.48%   |
| K8 Hammer        | 8         | 0.38%   |
| Jaguar           | 8         | 0.38%   |
| P6               | 6         | 0.29%   |
| Excavator        | 5         | 0.24%   |
| Bulldozer        | 5         | 0.24%   |
| Bonnell          | 5         | 0.24%   |
| NetBurst         | 4         | 0.19%   |
| K10 Llano        | 4         | 0.19%   |
| Steamroller      | 2         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1139      | 47.52%  |
| Nvidia                                       | 756       | 31.54%  |
| AMD                                          | 441       | 18.4%   |
| Matrox Electronics Systems                   | 35        | 1.46%   |
| ASPEED Technology                            | 15        | 0.63%   |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.38%   |
| VIA Technologies                             | 2         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 88        | 3.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 85        | 3.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 83        | 3.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 2.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 64        | 2.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 61        | 2.5%    |
| Intel HD Graphics 620                                                                    | 55        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 1.68%   |
| Intel HD Graphics 530                                                                    | 39        | 1.6%    |
| AMD Renoir                                                                               | 38        | 1.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 38        | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.27%   |
| Intel HD Graphics 5500                                                                   | 30        | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.11%   |
| Intel HD Graphics 630                                                                    | 26        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 0.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 21        | 0.86%   |
| Nvidia GP107GL [Quadro P400]                                                             | 20        | 0.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 20        | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 18        | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.66%   |
| AMD Rembrandt [Radeon 680M]                                                              | 16        | 0.66%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15        | 0.61%   |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 15        | 0.61%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 15        | 0.61%   |
| AMD Lucienne                                                                             | 15        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 14        | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 0.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 0.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 829       | 39.29%  |
| 1 x Nvidia               | 482       | 22.84%  |
| 1 x AMD                  | 364       | 17.25%  |
| Intel + Nvidia           | 238       | 11.28%  |
| Other                    | 52        | 2.46%   |
| Intel + AMD              | 41        | 1.94%   |
| 1 x Matrox               | 32        | 1.52%   |
| AMD + Nvidia             | 24        | 1.14%   |
| 2 x AMD                  | 11        | 0.52%   |
| 1 x XGI                  | 9         | 0.43%   |
| 1 x ASPEED               | 9         | 0.43%   |
| 2 x Nvidia               | 5         | 0.24%   |
| Nvidia + ASPEED          | 5         | 0.24%   |
| 2 x Intel                | 2         | 0.09%   |
| 1 x VIA                  | 2         | 0.09%   |
| Nvidia + Matrox          | 2         | 0.09%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + Matrox             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1537      | 72.6%   |
| Proprietary | 456       | 21.54%  |
| Unknown     | 124       | 5.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1138      | 52.98%  |
| 1.01-2.0   | 269       | 12.52%  |
| 0.01-0.5   | 192       | 8.94%   |
| 3.01-4.0   | 150       | 6.98%   |
| 0.51-1.0   | 143       | 6.66%   |
| 7.01-8.0   | 117       | 5.45%   |
| 8.01-16.0  | 71        | 3.31%   |
| 5.01-6.0   | 40        | 1.86%   |
| 2.01-3.0   | 14        | 0.65%   |
| 16.01-24.0 | 13        | 0.61%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 307       | 13.61%  |
| AU Optronics            | 250       | 11.08%  |
| LG Display              | 208       | 9.22%   |
| Dell                    | 160       | 7.09%   |
| Chimei Innolux          | 132       | 5.85%   |
| BOE                     | 114       | 5.05%   |
| Hewlett-Packard         | 105       | 4.65%   |
| Acer                    | 101       | 4.48%   |
| Philips                 | 89        | 3.95%   |
| Apple                   | 85        | 3.77%   |
| BenQ                    | 71        | 3.15%   |
| Ancor Communications    | 64        | 2.84%   |
| Sharp                   | 61        | 2.7%    |
| Lenovo                  | 56        | 2.48%   |
| AOC                     | 53        | 2.35%   |
| Goldstar                | 48        | 2.13%   |
| Eizo                    | 41        | 1.82%   |
| Unknown                 | 23        | 1.02%   |
| Chi Mei Optoelectronics | 23        | 1.02%   |
| ASUSTek Computer        | 22        | 0.98%   |
| Sony                    | 21        | 0.93%   |
| InfoVision              | 21        | 0.93%   |
| Iiyama                  | 15        | 0.66%   |
| CSO                     | 15        | 0.66%   |
| NEC Computers           | 14        | 0.62%   |
| Panasonic               | 10        | 0.44%   |
| PANDA                   | 9         | 0.4%    |
| Toshiba                 | 8         | 0.35%   |
| Vestel Elektronik       | 7         | 0.31%   |
| Medion                  | 7         | 0.31%   |
| Fujitsu Siemens         | 6         | 0.27%   |
| ViewSonic               | 5         | 0.22%   |
| MSI                     | 5         | 0.22%   |
| LG Philips              | 5         | 0.22%   |
| LG Electronics          | 5         | 0.22%   |
| Gigabyte Technology     | 5         | 0.22%   |
| AUS                     | 5         | 0.22%   |
| Valve                   | 4         | 0.18%   |
| LGD                     | 4         | 0.18%   |
| JDI                     | 4         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                   | 15        | 0.63%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 11        | 0.46%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 11        | 0.46%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 9         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.38%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                   | 9         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.34%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 7         | 0.29%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                              | 7         | 0.29%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.29%   |
| Dell LCD Monitor P2719H 3840x1080                                     | 7         | 0.29%   |
| Dell LCD Monitor P2719H                                               | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 7         | 0.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.25%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 6         | 0.25%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 6         | 0.25%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 6         | 0.25%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 6         | 0.25%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 5         | 0.21%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch  | 5         | 0.21%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 5         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.21%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 5         | 0.21%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.21%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.21%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 5         | 0.21%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 5         | 0.21%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 5         | 0.21%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                      | 5         | 0.21%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                 | 5         | 0.21%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 0.17%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 4         | 0.17%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 4         | 0.17%   |
| Sharp HDMI SHP1022 1920x1080 820x460mm 37.0-inch                      | 4         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 906       | 41.28%  |
| 3840x2160 (4K)     | 199       | 9.07%   |
| 2560x1440 (QHD)    | 162       | 7.38%   |
| 1366x768 (WXGA)    | 158       | 7.2%    |
| 1920x1200 (WUXGA)  | 115       | 5.24%   |
| 1600x900 (HD+)     | 85        | 3.87%   |
| 1680x1050 (WSXGA+) | 79        | 3.6%    |
| 1280x1024 (SXGA)   | 66        | 3.01%   |
| Unknown            | 65        | 2.96%   |
| 3440x1440          | 38        | 1.73%   |
| 1280x800 (WXGA)    | 37        | 1.69%   |
| 1440x900 (WXGA+)   | 32        | 1.46%   |
| 2560x1600          | 30        | 1.37%   |
| 3840x1080          | 29        | 1.32%   |
| 1600x1200          | 26        | 1.18%   |
| 2880x1800          | 12        | 0.55%   |
| 3840x2400          | 11        | 0.5%    |
| 3200x1800 (QHD+)   | 11        | 0.5%    |
| 2736x1824          | 11        | 0.5%    |
| 2560x1080          | 11        | 0.5%    |
| 3840x1200          | 10        | 0.46%   |
| 3840x1600          | 7         | 0.32%   |
| 1360x768           | 7         | 0.32%   |
| 1024x768 (XGA)     | 7         | 0.32%   |
| 4480x1440          | 6         | 0.27%   |
| 3000x2000          | 6         | 0.27%   |
| 1920x540           | 6         | 0.27%   |
| 1024x600           | 5         | 0.23%   |
| 800x1280           | 4         | 0.18%   |
| 3520x1200          | 4         | 0.18%   |
| 2160x1440          | 4         | 0.18%   |
| 5120x1440          | 3         | 0.14%   |
| 3360x1050          | 3         | 0.14%   |
| 2048x1152          | 3         | 0.14%   |
| 7680x2160          | 2         | 0.09%   |
| 6400x1440          | 2         | 0.09%   |
| 3840x1100          | 2         | 0.09%   |
| 3456x2160          | 2         | 0.09%   |
| 3200x1080          | 2         | 0.09%   |
| 3072x1920          | 2         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 401       | 17.92%  |
| 27      | 229       | 10.23%  |
| Unknown | 211       | 9.43%   |
| 13      | 204       | 9.12%   |
| 14      | 183       | 8.18%   |
| 24      | 179       | 8%      |
| 17      | 140       | 6.26%   |
| 23      | 115       | 5.14%   |
| 21      | 90        | 4.02%   |
| 31      | 59        | 2.64%   |
| 12      | 59        | 2.64%   |
| 34      | 38        | 1.7%    |
| 20      | 38        | 1.7%    |
| 19      | 38        | 1.7%    |
| 22      | 37        | 1.65%   |
| 84      | 17        | 0.76%   |
| 32      | 17        | 0.76%   |
| 16      | 17        | 0.76%   |
| 72      | 14        | 0.63%   |
| 40      | 14        | 0.63%   |
| 25      | 14        | 0.63%   |
| 11      | 12        | 0.54%   |
| 37      | 10        | 0.45%   |
| 33      | 10        | 0.45%   |
| 46      | 9         | 0.4%    |
| 29      | 9         | 0.4%    |
| 18      | 9         | 0.4%    |
| 54      | 7         | 0.31%   |
| 10      | 7         | 0.31%   |
| 49      | 6         | 0.27%   |
| 28      | 6         | 0.27%   |
| 48      | 5         | 0.22%   |
| 26      | 5         | 0.22%   |
| 7       | 4         | 0.18%   |
| 65      | 3         | 0.13%   |
| 55      | 3         | 0.13%   |
| 35      | 3         | 0.13%   |
| 142     | 2         | 0.09%   |
| 60      | 2         | 0.09%   |
| 43      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 674       | 30.59%  |
| 501-600        | 486       | 22.06%  |
| 201-300        | 213       | 9.67%   |
| Unknown        | 211       | 9.58%   |
| 401-500        | 175       | 7.94%   |
| 351-400        | 171       | 7.76%   |
| 601-700        | 98        | 4.45%   |
| 701-800        | 65        | 2.95%   |
| 1001-1500      | 39        | 1.77%   |
| 1501-2000      | 32        | 1.45%   |
| 801-900        | 29        | 1.32%   |
| 1-100          | 4         | 0.18%   |
| 901-1000       | 3         | 0.14%   |
| More than 2000 | 2         | 0.09%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1335      | 65.89%  |
| 16/10   | 301       | 14.86%  |
| Unknown | 197       | 9.72%   |
| 5/4     | 57        | 2.81%   |
| 21/9    | 49        | 2.42%   |
| 3/2     | 32        | 1.58%   |
| 4/3     | 29        | 1.43%   |
| 32/9    | 10        | 0.49%   |
| 6/5     | 4         | 0.2%    |
| 0.67    | 4         | 0.2%    |
| 1.00    | 3         | 0.15%   |
| 3.40    | 2         | 0.1%    |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 2.50    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 399       | 17.99%  |
| 201-250        | 303       | 13.66%  |
| 81-90          | 266       | 11.99%  |
| 301-350        | 233       | 10.5%   |
| Unknown        | 211       | 9.51%   |
| 351-500        | 140       | 6.31%   |
| 71-80          | 119       | 5.37%   |
| 121-130        | 106       | 4.78%   |
| 251-300        | 102       | 4.6%    |
| 151-200        | 100       | 4.51%   |
| 61-70          | 55        | 2.48%   |
| More than 1000 | 54        | 2.43%   |
| 501-1000       | 45        | 2.03%   |
| 141-150        | 22        | 0.99%   |
| 131-140        | 16        | 0.72%   |
| 111-120        | 16        | 0.72%   |
| 51-60          | 15        | 0.68%   |
| 41-50          | 6         | 0.27%   |
| 1-40           | 5         | 0.23%   |
| 91-100         | 5         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 625       | 29.14%  |
| 121-160       | 572       | 26.67%  |
| 101-120       | 411       | 19.16%  |
| Unknown       | 211       | 9.84%   |
| 161-240       | 175       | 8.16%   |
| More than 240 | 100       | 4.66%   |
| 1-50          | 51        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1566      | 72.07%  |
| 2     | 388       | 17.86%  |
| 0     | 160       | 7.36%   |
| 3     | 55        | 2.53%   |
| 4     | 4         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1269      | 41.52%  |
| Realtek Semiconductor             | 852       | 27.88%  |
| Qualcomm Atheros                  | 229       | 7.49%   |
| Broadcom                          | 180       | 5.89%   |
| Broadcom Limited                  | 43        | 1.41%   |
| Marvell Technology Group          | 40        | 1.31%   |
| MediaTek                          | 33        | 1.08%   |
| Ralink                            | 31        | 1.01%   |
| Aquantia                          | 28        | 0.92%   |
| ASIX Electronics                  | 25        | 0.82%   |
| Nvidia                            | 23        | 0.75%   |
| Lenovo                            | 23        | 0.75%   |
| Ralink Technology                 | 19        | 0.62%   |
| Sierra Wireless                   | 18        | 0.59%   |
| TP-Link                           | 17        | 0.56%   |
| Dell                              | 15        | 0.49%   |
| Hewlett-Packard                   | 14        | 0.46%   |
| DisplayLink                       | 14        | 0.46%   |
| Huawei Technologies               | 13        | 0.43%   |
| Ericsson Business Mobile Networks | 13        | 0.43%   |
| Edimax Technology                 | 13        | 0.43%   |
| Samsung Electronics               | 11        | 0.36%   |
| Qualcomm                          | 11        | 0.36%   |
| NetGear                           | 11        | 0.36%   |
| Microchip Technology              | 10        | 0.33%   |
| D-Link                            | 9         | 0.29%   |
| Xiaomi                            | 8         | 0.26%   |
| Microsoft                         | 8         | 0.26%   |
| ASUSTek Computer                  | 8         | 0.26%   |
| Fibocom                           | 5         | 0.16%   |
| Linksys                           | 4         | 0.13%   |
| IMC Networks                      | 4         | 0.13%   |
| ICS Advent                        | 4         | 0.13%   |
| D-Link System                     | 4         | 0.13%   |
| AVM                               | 4         | 0.13%   |
| Wilocity                          | 3         | 0.1%    |
| NetXen Incorporated               | 3         | 0.1%    |
| Mellanox Technologies             | 3         | 0.1%    |
| Arduino SA                        | 3         | 0.1%    |
| Qualcomm Atheros Communications   | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 592       | 16.18%  |
| Intel Wi-Fi 6 AX200                                               | 129       | 3.53%   |
| Intel Wireless 8265 / 8275                                        | 102       | 2.79%   |
| Intel I211 Gigabit Network Connection                             | 92        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 86        | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 79        | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 57        | 1.56%   |
| Intel Wi-Fi 6 AX201                                               | 54        | 1.48%   |
| Intel Wireless 7260                                               | 51        | 1.39%   |
| Intel Wireless 7265                                               | 46        | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 40        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 39        | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                             | 39        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 38        | 1.04%   |
| Intel Wireless 8260                                               | 37        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 35        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 35        | 0.96%   |
| Intel 82574L Gigabit Network Connection                           | 32        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 29        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 27        | 0.74%   |
| Intel Ethernet Controller I225-V                                  | 27        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 25        | 0.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 24        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 24        | 0.66%   |
| Intel Wireless-AC 9260                                            | 23        | 0.63%   |
| Intel Wireless 3165                                               | 23        | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 23        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 872       | 55.4%   |
| Qualcomm Atheros                      | 189       | 12.01%  |
| Realtek Semiconductor                 | 162       | 10.29%  |
| Broadcom                              | 101       | 6.42%   |
| Ralink                                | 31        | 1.97%   |
| MediaTek                              | 30        | 1.91%   |
| Broadcom Limited                      | 28        | 1.78%   |
| Ralink Technology                     | 19        | 1.21%   |
| Sierra Wireless                       | 18        | 1.14%   |
| TP-Link                               | 14        | 0.89%   |
| Edimax Technology                     | 13        | 0.83%   |
| NetGear                               | 10        | 0.64%   |
| Marvell Technology Group              | 10        | 0.64%   |
| Qualcomm                              | 9         | 0.57%   |
| Dell                                  | 8         | 0.51%   |
| D-Link                                | 8         | 0.51%   |
| ASUSTek Computer                      | 8         | 0.51%   |
| Hewlett-Packard                       | 7         | 0.44%   |
| Microsoft                             | 5         | 0.32%   |
| Fibocom                               | 5         | 0.32%   |
| IMC Networks                          | 4         | 0.25%   |
| AVM                                   | 4         | 0.25%   |
| Wilocity                              | 3         | 0.19%   |
| D-Link System                         | 3         | 0.19%   |
| Qualcomm Atheros Communications       | 2         | 0.13%   |
| Micro Star International              | 2         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.13%   |
| Philips (or NXP)                      | 1         | 0.06%   |
| Netopia                               | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| Gemtek                                | 1         | 0.06%   |
| CyberTAN Technology                   | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |
| Arduino SA                            | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 129       | 8.14%   |
| Intel Wireless 8265 / 8275                                     | 102       | 6.44%   |
| Intel Wi-Fi 6 AX201                                            | 54        | 3.41%   |
| Intel Wireless 7260                                            | 51        | 3.22%   |
| Intel Wireless 7265                                            | 46        | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 40        | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 39        | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 38        | 2.4%    |
| Intel Wireless 8260                                            | 37        | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 27        | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 25        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 24        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 24        | 1.52%   |
| Intel Wireless-AC 9260                                         | 23        | 1.45%   |
| Intel Wireless 3165                                            | 23        | 1.45%   |
| Intel Centrino Ultimate-N 6300                                 | 23        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 19        | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 17        | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 17        | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 16        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16        | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 1.01%   |
| Intel Wireless 3160                                            | 15        | 0.95%   |
| Intel Centrino Advanced-N 6235                                 | 15        | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 13        | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 0.69%   |
| Sierra Wireless EM7455                                         | 10        | 0.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 10        | 0.63%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 0.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 10        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 780       | 40.1%   |
| Intel                         | 773       | 39.74%  |
| Broadcom                      | 104       | 5.35%   |
| Qualcomm Atheros              | 66        | 3.39%   |
| Marvell Technology Group      | 30        | 1.54%   |
| Aquantia                      | 28        | 1.44%   |
| ASIX Electronics              | 25        | 1.29%   |
| Nvidia                        | 23        | 1.18%   |
| Lenovo                        | 23        | 1.18%   |
| Broadcom Limited              | 15        | 0.77%   |
| DisplayLink                   | 14        | 0.72%   |
| Xiaomi                        | 8         | 0.41%   |
| Microchip Technology          | 8         | 0.41%   |
| Huawei Technologies           | 8         | 0.41%   |
| Samsung Electronics           | 4         | 0.21%   |
| ICS Advent                    | 4         | 0.21%   |
| TP-Link                       | 3         | 0.15%   |
| NetXen Incorporated           | 3         | 0.15%   |
| MediaTek                      | 3         | 0.15%   |
| Linksys                       | 3         | 0.15%   |
| Qualcomm                      | 2         | 0.1%    |
| Microsoft                     | 2         | 0.1%    |
| Mellanox Technologies         | 2         | 0.1%    |
| Standard Microsystems         | 1         | 0.05%   |
| QNAP System                   | 1         | 0.05%   |
| OnePlus Technology (Shenzhen) | 1         | 0.05%   |
| NetGear                       | 1         | 0.05%   |
| Netchip Technology            | 1         | 0.05%   |
| MosChip Semiconductor         | 1         | 0.05%   |
| JMicron Technology            | 1         | 0.05%   |
| HMD Global                    | 1         | 0.05%   |
| Hewlett-Packard               | 1         | 0.05%   |
| D-Link System                 | 1         | 0.05%   |
| D-Link                        | 1         | 0.05%   |
| Cypress Semiconductor         | 1         | 0.05%   |
| Apple                         | 1         | 0.05%   |
| ADMtek                        | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 592       | 29.38%  |
| Intel I211 Gigabit Network Connection                             | 92        | 4.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 86        | 4.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 79        | 3.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 2.98%   |
| Intel Ethernet Connection (2) I219-V                              | 57        | 2.83%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 2.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 39        | 1.94%   |
| Intel 82579V Gigabit Network Connection                           | 35        | 1.74%   |
| Intel 82574L Gigabit Network Connection                           | 32        | 1.59%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 1.39%   |
| Intel Ethernet Controller I225-V                                  | 27        | 1.34%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21        | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.99%   |
| Intel I350 Gigabit Network Connection                             | 19        | 0.94%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 18        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 17        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 16        | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.69%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 13        | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.6%    |
| Intel Ethernet Connection I219-V                                  | 10        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 9         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.45%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.4%    |
| Lenovo ThinkPad Lan                                               | 8         | 0.4%    |
| Intel Ethernet Connection (11) I219-LM                            | 8         | 0.4%    |
| Intel 82576 Gigabit Network Connection                            | 8         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1787      | 53.65%  |
| WiFi     | 1487      | 44.64%  |
| Modem    | 53        | 1.59%   |
| Unknown  | 4         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1063      | 50.38%  |
| Ethernet | 1046      | 49.57%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1063      | 50.5%   |
| 1     | 838       | 39.81%  |
| 3     | 94        | 4.47%   |
| 0     | 70        | 3.33%   |
| 4     | 24        | 1.14%   |
| 6     | 8         | 0.38%   |
| 5     | 4         | 0.19%   |
| 8     | 2         | 0.1%    |
| 10    | 1         | 0.05%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1714      | 79.61%  |
| Yes  | 439       | 20.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 704       | 55.96%  |
| Realtek Semiconductor           | 77        | 6.12%   |
| Apple                           | 76        | 6.04%   |
| Broadcom                        | 68        | 5.41%   |
| Cambridge Silicon Radio         | 57        | 4.53%   |
| Qualcomm Atheros Communications | 56        | 4.45%   |
| Foxconn / Hon Hai               | 44        | 3.5%    |
| IMC Networks                    | 37        | 2.94%   |
| Lite-On Technology              | 33        | 2.62%   |
| ASUSTek Computer                | 28        | 2.23%   |
| Hewlett-Packard                 | 14        | 1.11%   |
| Dell                            | 13        | 1.03%   |
| Ralink                          | 9         | 0.72%   |
| Marvell Semiconductor           | 8         | 0.64%   |
| MediaTek                        | 6         | 0.48%   |
| USI                             | 5         | 0.4%    |
| Toshiba                         | 3         | 0.24%   |
| Realtek                         | 3         | 0.24%   |
| Micro Star International        | 3         | 0.24%   |
| Alps Electric                   | 3         | 0.24%   |
| Ralink Technology               | 2         | 0.16%   |
| Chicony Electronics             | 2         | 0.16%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Logitech                        | 1         | 0.08%   |
| Integrated System Solution      | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |
| Foxconn International           | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 269       | 21.35%  |
| Intel AX201 Bluetooth                               | 123       | 9.76%   |
| Intel AX200 Bluetooth                               | 122       | 9.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 76        | 6.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 57        | 4.52%   |
| Realtek Bluetooth Radio                             | 50        | 3.97%   |
| Intel Bluetooth Device                              | 33        | 2.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 23        | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 23        | 1.83%   |
| Apple Bluetooth USB Host Controller                 | 23        | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.67%   |
| Apple Bluetooth Host Controller                     | 20        | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 1.51%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.43%   |
| Intel AX210 Bluetooth                               | 15        | 1.19%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.95%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.79%   |
| Apple Bluetooth HCI                                 | 10        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.71%   |
| IMC Networks Wireless_Device                        | 9         | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.56%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.56%   |
| MediaTek Wireless_Device                            | 6         | 0.48%   |
| Marvell Bluetooth and Wireless LAN Composite        | 6         | 0.48%   |
| Lite-On Bluetooth Device                            | 6         | 0.48%   |
| IMC Networks Bluetooth Device                       | 6         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.48%   |
| USI Bluetooth Device                                | 5         | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 1549      | 52.87%  |
| Nvidia                    | 583       | 19.9%   |
| AMD                       | 484       | 16.52%  |
| GN Netcom                 | 35        | 1.19%   |
| Logitech                  | 34        | 1.16%   |
| C-Media Electronics       | 32        | 1.09%   |
| Lenovo                    | 17        | 0.58%   |
| ASUSTek Computer          | 17        | 0.58%   |
| Hewlett-Packard           | 11        | 0.38%   |
| Plantronics               | 10        | 0.34%   |
| Creative Labs             | 10        | 0.34%   |
| SteelSeries ApS           | 9         | 0.31%   |
| RODE Microphones          | 9         | 0.31%   |
| Kingston Technology       | 9         | 0.31%   |
| Realtek Semiconductor     | 8         | 0.27%   |
| BEHRINGER International   | 6         | 0.2%    |
| Apple                     | 6         | 0.2%    |
| Texas Instruments         | 5         | 0.17%   |
| Tenx Technology           | 5         | 0.17%   |
| Razer USA                 | 5         | 0.17%   |
| Generalplus Technology    | 5         | 0.17%   |
| Samson Technologies       | 4         | 0.14%   |
| Corsair                   | 4         | 0.14%   |
| Conexant Systems          | 4         | 0.14%   |
| ROCCAT                    | 3         | 0.1%    |
| JMTek                     | 3         | 0.1%    |
| Creative Technology       | 3         | 0.1%    |
| Yamaha                    | 2         | 0.07%   |
| XMOS                      | 2         | 0.07%   |
| VIA Technologies          | 2         | 0.07%   |
| TerraTec Electronic       | 2         | 0.07%   |
| Sennheiser Communications | 2         | 0.07%   |
| Roland                    | 2         | 0.07%   |
| Magic Control Technology  | 2         | 0.07%   |
| HiFiBerry                 | 2         | 0.07%   |
| GYROCOM C&C               | 2         | 0.07%   |
| Giga-Byte Technology      | 2         | 0.07%   |
| Focusrite-Novation        | 2         | 0.07%   |
| AudioQuest                | 2         | 0.07%   |
| Audinate                  | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 202       | 5.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 150       | 4.45%   |
| AMD Family 17h/19h HD Audio Controller                                     | 125       | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 118       | 3.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 107       | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 95        | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 84        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 76        | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 76        | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 73        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 70        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 67        | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 62        | 1.84%   |
| Intel 8 Series HD Audio Controller                                         | 62        | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 62        | 1.84%   |
| Intel 200 Series PCH HD Audio                                              | 58        | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 52        | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 49        | 1.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 47        | 1.39%   |
| Nvidia GK107 HDMI Audio Controller                                         | 46        | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 42        | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 40        | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 39        | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 39        | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 38        | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37        | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 34        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 34        | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 32        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 30        | 0.89%   |
| Nvidia GP102 HDMI Audio Controller                                         | 29        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 28        | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 28        | 0.83%   |
| Nvidia GK104 HDMI Audio Controller                                         | 28        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 28        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 27        | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.8%    |
| AMD FCH Azalia Controller                                                  | 26        | 0.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 0.74%   |
| Nvidia GA102 High Definition Audio Controller                              | 24        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 338       | 23.74%  |
| SK hynix            | 268       | 18.82%  |
| Kingston            | 239       | 16.78%  |
| Micron Technology   | 155       | 10.88%  |
| Corsair             | 143       | 10.04%  |
| Unknown             | 96        | 6.74%   |
| Crucial             | 50        | 3.51%   |
| G.Skill             | 39        | 2.74%   |
| Elpida              | 20        | 1.4%    |
| Ramaxel Technology  | 13        | 0.91%   |
| A-DATA Technology   | 13        | 0.91%   |
| Nanya Technology    | 8         | 0.56%   |
| Patriot             | 5         | 0.35%   |
| Unknown             | 5         | 0.35%   |
| Unknown (ABCD)      | 3         | 0.21%   |
| Hewlett-Packard     | 3         | 0.21%   |
| Avant               | 3         | 0.21%   |
| Unknown (0x9801)    | 2         | 0.14%   |
| ASint Technology    | 2         | 0.14%   |
| Apacer              | 2         | 0.14%   |
| Unknown (08AE)      | 1         | 0.07%   |
| Unifosa             | 1         | 0.07%   |
| Team                | 1         | 0.07%   |
| Smart               | 1         | 0.07%   |
| Princeton           | 1         | 0.07%   |
| Patriot Memory      | 1         | 0.07%   |
| OnBoard             | 1         | 0.07%   |
| OCZ                 | 1         | 0.07%   |
| Melco               | 1         | 0.07%   |
| Kingmax             | 1         | 0.07%   |
| KANMEIQi            | 1         | 0.07%   |
| HPE                 | 1         | 0.07%   |
| GOODRAM             | 1         | 0.07%   |
| G-Alantic           | 1         | 0.07%   |
| Advantech           | 1         | 0.07%   |
| A-DA                | 1         | 0.07%   |
| 48spaces            | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.97%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s            | 13        | 0.84%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 13        | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 12        | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.65%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s            | 9         | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 8         | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 8         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.52%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s           | 8         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.45%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 7         | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.45%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s           | 7         | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.39%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.39%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 6         | 0.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.39%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 6         | 0.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.32%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.32%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 0.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.32%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 5         | 0.32%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s            | 5         | 0.32%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 5         | 0.32%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 5         | 0.32%   |
| Corsair RAM CM4X16GC3000C16K8 16GB DIMM DDR4 3000MT/s            | 5         | 0.32%   |
| Unknown                                                          | 5         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 653       | 50.62%  |
| DDR3    | 423       | 32.79%  |
| LPDDR3  | 56        | 4.34%   |
| LPDDR4  | 46        | 3.57%   |
| DDR2    | 39        | 3.02%   |
| Unknown | 21        | 1.63%   |
| SDRAM   | 18        | 1.4%    |
| DDR5    | 18        | 1.4%    |
| LPDDR5  | 11        | 0.85%   |
| DDR     | 5         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 636       | 49.49%  |
| DIMM         | 528       | 41.09%  |
| Row Of Chips | 103       | 8.02%   |
| Chip         | 9         | 0.7%    |
| RIMM         | 5         | 0.39%   |
| Unknown      | 3         | 0.23%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 544       | 39.51%  |
| 16384 | 309       | 22.44%  |
| 4096  | 297       | 21.57%  |
| 2048  | 124       | 9.01%   |
| 32768 | 66        | 4.79%   |
| 1024  | 31        | 2.25%   |
| 65536 | 5         | 0.36%   |
| 512   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 260       | 18.87%  |
| 3200    | 215       | 15.6%   |
| 2667    | 190       | 13.79%  |
| 2133    | 104       | 7.55%   |
| 1333    | 96        | 6.97%   |
| 2400    | 92        | 6.68%   |
| 1334    | 46        | 3.34%   |
| 3600    | 28        | 2.03%   |
| 3000    | 26        | 1.89%   |
| 1867    | 26        | 1.89%   |
| 800     | 26        | 1.89%   |
| 4267    | 23        | 1.67%   |
| 2666    | 22        | 1.6%    |
| 3400    | 19        | 1.38%   |
| 667     | 18        | 1.31%   |
| 1067    | 16        | 1.16%   |
| 4800    | 15        | 1.09%   |
| 3266    | 12        | 0.87%   |
| 6400    | 11        | 0.8%    |
| Unknown | 11        | 0.8%    |
| 1066    | 10        | 0.73%   |
| 3733    | 9         | 0.65%   |
| 3800    | 7         | 0.51%   |
| 2933    | 7         | 0.51%   |
| 8400    | 6         | 0.44%   |
| 4266    | 5         | 0.36%   |
| 3533    | 5         | 0.36%   |
| 3100    | 5         | 0.36%   |
| 2000    | 5         | 0.36%   |
| 1866    | 5         | 0.36%   |
| 4199    | 4         | 0.29%   |
| 3666    | 4         | 0.29%   |
| 2465    | 4         | 0.29%   |
| 2048    | 4         | 0.29%   |
| 1800    | 4         | 0.29%   |
| 5808    | 3         | 0.22%   |
| 3500    | 3         | 0.22%   |
| 333     | 3         | 0.22%   |
| 6000    | 2         | 0.15%   |
| 3933    | 2         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 26        | 43.33%  |
| Brother Industries       | 14        | 23.33%  |
| Samsung Electronics      | 5         | 8.33%   |
| Canon                    | 4         | 6.67%   |
| STMicroelectronics       | 3         | 5%      |
| Seiko Epson              | 2         | 3.33%   |
| Oki Data                 | 2         | 3.33%   |
| Zhuhai Poskey Technology | 1         | 1.67%   |
| Prolific Technology      | 1         | 1.67%   |
| Konica Minolta           | 1         | 1.67%   |
| Dymo-CoStar              | 1         | 1.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 3         | 5%      |
| Samsung M337x 387x 407x Series                             | 2         | 3.33%   |
| Oki Data USB Device                                        | 2         | 3.33%   |
| HP OfficeJet Pro 7730 series                               | 2         | 3.33%   |
| HP OfficeJet 6950                                          | 2         | 3.33%   |
| HP LaserJet Pro M148f-M149f                                | 2         | 3.33%   |
| HP ENVY 5540 series                                        | 2         | 3.33%   |
| HP Deskjet 2540 series                                     | 2         | 3.33%   |
| Brother Printer                                            | 2         | 3.33%   |
| Brother MFC Composite Device                               | 2         | 3.33%   |
| Zhuhai Poskey Printer                                      | 1         | 1.67%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.67%   |
| Seiko Epson ET-2820 Series                                 | 1         | 1.67%   |
| Samsung M332x 382x 402x Series                             | 1         | 1.67%   |
| Samsung C48x Series                                        | 1         | 1.67%   |
| Samsung C1860 Series                                       | 1         | 1.67%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.67%   |
| Konica Minolta Printer                                     | 1         | 1.67%   |
| HP Smart Tank Plus 550 series                              | 1         | 1.67%   |
| HP Smart Tank 7000 series                                  | 1         | 1.67%   |
| HP Officejet 4630 series                                   | 1         | 1.67%   |
| HP LaserJet P3010 Series                                   | 1         | 1.67%   |
| HP LaserJet P2055 series                                   | 1         | 1.67%   |
| HP Laserjet P1505                                          | 1         | 1.67%   |
| HP LaserJet P1102                                          | 1         | 1.67%   |
| HP LaserJet 3050                                           | 1         | 1.67%   |
| HP LaserJet 3020                                           | 1         | 1.67%   |
| HP LaserJet 1320                                           | 1         | 1.67%   |
| HP LaserJet 1020                                           | 1         | 1.67%   |
| HP Laser 107a                                              | 1         | 1.67%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.67%   |
| HP ENVY 6400 series                                        | 1         | 1.67%   |
| HP ENVY 4520 series                                        | 1         | 1.67%   |
| HP DeskJet F2100 Printer series                            | 1         | 1.67%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.67%   |
| Canon TS3300 series                                        | 1         | 1.67%   |
| Canon PIXMA TS6250                                         | 1         | 1.67%   |
| Canon PIXMA MX450 Series                                   | 1         | 1.67%   |
| Canon iP7200 series                                        | 1         | 1.67%   |
| Brother MFC-9320CW                                         | 1         | 1.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 46.67%  |
| Seiko Epson       | 4         | 26.67%  |
| Hewlett-Packard   | 2         | 13.33%  |
| Fujitsu           | 1         | 6.67%   |
| Canon Electronics | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 2         | 13.33%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                   | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 6.67%   |
| HP ScanJet 4070 PhotoSmart                                    | 1         | 6.67%   |
| HP ScanJet 2400c                                              | 1         | 6.67%   |
| Fujitsu ScanSnap SV600                                        | 1         | 6.67%   |
| Canon P-150 Scanner                                           | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 1         | 6.67%   |
| Canon CanoScan N650U/N656U                                    | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                        | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                       | 1         | 6.67%   |
| Canon CanoScan LiDE 100                                       | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 323       | 27.58%  |
| IMC Networks                           | 91        | 7.77%   |
| Logitech                               | 84        | 7.17%   |
| Apple                                  | 73        | 6.23%   |
| Microdia                               | 70        | 5.98%   |
| Realtek Semiconductor                  | 58        | 4.95%   |
| Bison Electronics                      | 56        | 4.78%   |
| Quanta                                 | 55        | 4.7%    |
| Sunplus Innovation Technology          | 49        | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 3.67%   |
| Acer                                   | 35        | 2.99%   |
| Lite-On Technology                     | 34        | 2.9%    |
| Suyin                                  | 31        | 2.65%   |
| Syntek                                 | 20        | 1.71%   |
| Lenovo                                 | 17        | 1.45%   |
| Luxvisions Innotech Limited            | 15        | 1.28%   |
| Ricoh                                  | 13        | 1.11%   |
| Microsoft                              | 12        | 1.02%   |
| Alcor Micro                            | 12        | 1.02%   |
| Samsung Electronics                    | 11        | 0.94%   |
| Silicon Motion                         | 7         | 0.6%    |
| Z-Star Microelectronics                | 5         | 0.43%   |
| Sonix Technology                       | 5         | 0.43%   |
| Primax Electronics                     | 5         | 0.43%   |
| Generalplus Technology                 | 5         | 0.43%   |
| ALi                                    | 4         | 0.34%   |
| Xiaomi                                 | 2         | 0.17%   |
| Tripath Technology                     | 2         | 0.17%   |
| OmniVision Technologies                | 2         | 0.17%   |
| MacroSilicon                           | 2         | 0.17%   |
| Intel                                  | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| DigiTech                               | 2         | 0.17%   |
| Creative Technology                    | 2         | 0.17%   |
| YGTek                                  | 1         | 0.09%   |
| WCM_USB                                | 1         | 0.09%   |
| Tobii Technology AB                    | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |
| Novatek Microelectronics               | 1         | 0.09%   |
| Nikon                                  | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 83        | 6.99%   |
| IMC Networks Integrated Camera          | 43        | 3.62%   |
| Microdia Integrated_Webcam_HD           | 36        | 3.03%   |
| Chicony HD WebCam                       | 34        | 2.86%   |
| Chicony HP HD Camera                    | 24        | 2.02%   |
| Apple Built-in iSight                   | 23        | 1.94%   |
| Apple FaceTime HD Camera (Built-in)     | 22        | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam       | 20        | 1.68%   |
| Realtek Integrated_Webcam_HD            | 19        | 1.6%    |
| Bison Integrated Camera                 | 19        | 1.6%    |
| Lite-On Integrated Camera               | 16        | 1.35%   |
| Quanta HP HD Camera                     | 15        | 1.26%   |
| Logitech HD Pro Webcam C920             | 15        | 1.26%   |
| Chicony HP Wide Vision HD Camera        | 14        | 1.18%   |
| Logitech Webcam C270                    | 13        | 1.09%   |
| Chicony USB2.0 Camera                   | 13        | 1.09%   |
| Sunplus HD WebCam                       | 12        | 1.01%   |
| Syntek Integrated Camera                | 11        | 0.93%   |
| Samsung Galaxy A5 (MTP)                 | 11        | 0.93%   |
| Chicony HP Truevision HD                | 11        | 0.93%   |
| Microdia Integrated Webcam              | 10        | 0.84%   |
| Chicony Integrated Camera (1280x720@30) | 10        | 0.84%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 10        | 0.84%   |
| Apple FaceTime HD Camera                | 10        | 0.84%   |
| Sunplus Integrated_Webcam_HD            | 9         | 0.76%   |
| Lite-On HP HD Camera                    | 9         | 0.76%   |
| Chicony HD User Facing                  | 9         | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 8         | 0.67%   |
| Suyin HP Truevision HD                  | 7         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam            | 7         | 0.59%   |
| Logitech HD Webcam C615                 | 7         | 0.59%   |
| Lenovo Integrated Webcam                | 7         | 0.59%   |
| Chicony VGA WebCam                      | 7         | 0.59%   |
| Chicony Integrated IR Camera            | 7         | 0.59%   |
| Chicony HP HD Webcam                    | 7         | 0.59%   |
| Bison SunplusIT Integrated Camera       | 7         | 0.59%   |
| Acer Integrated Camera                  | 7         | 0.59%   |
| Syntek Lenovo EasyCamera                | 6         | 0.51%   |
| Quanta HD User Facing                   | 6         | 0.51%   |
| Logitech StreamCam                      | 6         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 129       | 36.96%  |
| Synaptics                  | 128       | 36.68%  |
| Shenzhen Goodix Technology | 28        | 8.02%   |
| Upek                       | 19        | 5.44%   |
| Elan Microelectronics      | 18        | 5.16%   |
| AuthenTec                  | 14        | 4.01%   |
| LighTuning Technology      | 11        | 3.15%   |
| STMicroelectronics         | 2         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 12.61%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 7.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 5.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.3%    |
| Validity Sensors Synaptics WBDI                                            | 15        | 4.3%    |
| Synaptics  WBDI                                                            | 13        | 3.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 3.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.44%   |
| Elan ELAN:ARM-M4                                                           | 12        | 3.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 3.15%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 3.15%   |
| Synaptics UWP WBDI                                                         | 10        | 2.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.58%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 2.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.58%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 2.58%   |
| Validity Sensors VFS491                                                    | 8         | 2.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.01%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 2.01%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.01%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.72%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.43%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.43%   |
| AuthenTec AES2810                                                          | 5         | 1.43%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.43%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.15%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.86%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.86%   |
| Synaptics WBDI                                                             | 3         | 0.86%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.86%   |
| Unknown                                                                    | 3         | 0.86%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.57%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 51        | 42.15%  |
| Broadcom                  | 38        | 31.4%   |
| Upek                      | 12        | 9.92%   |
| Yubico.com                | 5         | 4.13%   |
| O2 Micro                  | 5         | 4.13%   |
| Lenovo                    | 3         | 2.48%   |
| Clay Logic                | 2         | 1.65%   |
| OmniKey                   | 1         | 0.83%   |
| Gemalto (was Gemplus)     | 1         | 0.83%   |
| Bit4id                    | 1         | 0.83%   |
| Aladdin Knowledge Systems | 1         | 0.83%   |
| Advanced Card Systems     | 1         | 0.83%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 42.15%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 10.74%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 9.92%   |
| Broadcom 5880                                                                | 11        | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 5.79%   |
| Broadcom 58200                                                               | 7         | 5.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.13%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 2.48%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.48%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 0.83%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.83%   |
| OmniKey CardMan 4321                                                         | 1         | 0.83%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.83%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.83%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.83%   |
| Bit4id miniLector-s                                                          | 1         | 0.83%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.83%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.83%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1409      | 65.32%  |
| 1     | 574       | 26.61%  |
| 2     | 133       | 6.17%   |
| 3     | 25        | 1.16%   |
| 4     | 11        | 0.51%   |
| 7     | 2         | 0.09%   |
| 6     | 2         | 0.09%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 344       | 36.52%  |
| Graphics card            | 147       | 15.61%  |
| Chipcard                 | 101       | 10.72%  |
| Net/wireless             | 96        | 10.19%  |
| Multimedia controller    | 51        | 5.41%   |
| Communication controller | 50        | 5.31%   |
| Unassigned class         | 36        | 3.82%   |
| Camera                   | 27        | 2.87%   |
| Bluetooth                | 22        | 2.34%   |
| Sound                    | 14        | 1.49%   |
| Card reader              | 12        | 1.27%   |
| Net/ethernet             | 10        | 1.06%   |
| Storage                  | 8         | 0.85%   |
| Network                  | 6         | 0.64%   |
| Modem                    | 5         | 0.53%   |
| Storage/raid             | 4         | 0.42%   |
| Dvb card                 | 3         | 0.32%   |
| Storage/nvme             | 2         | 0.21%   |
| Wireless                 | 1         | 0.11%   |
| Storage/ata              | 1         | 0.11%   |
| Flash memory             | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |


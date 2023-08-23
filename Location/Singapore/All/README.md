Linux in Singapore - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Singapore/Desktop/README.md) and [notebooks](/Location/Singapore/Notebook/README.md).

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

Total: 588

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [a936584caa](https://linux-hardware.org/?probe=a936584caa) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| Dell          | 09M8Y8 A02                  | Desktop     | [4b57bbf30e](https://linux-hardware.org/?probe=4b57bbf30e) | Aug 04, 2023 |
| Lenovo        | ThinkPad X250 20CL0007SG    | Notebook    | [f30d61c851](https://linux-hardware.org/?probe=f30d61c851) | Aug 01, 2023 |
| Intel         | JSL MRD                     | Desktop     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [5bc4bf8334](https://linux-hardware.org/?probe=5bc4bf8334) | Jul 28, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [57e295e5cf](https://linux-hardware.org/?probe=57e295e5cf) | Jul 27, 2023 |
| MECHREVO      | F7BFD V1.0                  | Desktop     | [f9be0fc5a7](https://linux-hardware.org/?probe=f9be0fc5a7) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [78560cbf59](https://linux-hardware.org/?probe=78560cbf59) | Jul 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [556e4cd2c9](https://linux-hardware.org/?probe=556e4cd2c9) | Jul 21, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [3a257c75fc](https://linux-hardware.org/?probe=3a257c75fc) | Jul 19, 2023 |
| AZW           | Gemini J45                  | Desktop     | [0ed36a4286](https://linux-hardware.org/?probe=0ed36a4286) | Jul 18, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [dfe9381867](https://linux-hardware.org/?probe=dfe9381867) | Jul 14, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [e141746297](https://linux-hardware.org/?probe=e141746297) | Jul 05, 2023 |
| Gigabyte      | Z690 AERO D                 | Desktop     | [f42140d294](https://linux-hardware.org/?probe=f42140d294) | Jul 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [d94ad2e231](https://linux-hardware.org/?probe=d94ad2e231) | Jun 28, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Lenovo        | Legion R7000P2021 82JW      | Notebook    | [df59b5e8b7](https://linux-hardware.org/?probe=df59b5e8b7) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | Desktop     | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| Dell          | Precision 5520              | Notebook    | [8d5ec720c1](https://linux-hardware.org/?probe=8d5ec720c1) | Jun 19, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | Notebook    | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | Notebook    | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [386f19f4f1](https://linux-hardware.org/?probe=386f19f4f1) | Jun 03, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [f17ae033ef](https://linux-hardware.org/?probe=f17ae033ef) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | Notebook    | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | Notebook    | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [3a92115c6c](https://linux-hardware.org/?probe=3a92115c6c) | May 12, 2023 |
| AZW           | MINI S 10                   | Desktop     | [c64432906e](https://linux-hardware.org/?probe=c64432906e) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [64f08f10f3](https://linux-hardware.org/?probe=64f08f10f3) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [d21ef87b63](https://linux-hardware.org/?probe=d21ef87b63) | May 10, 2023 |
| Unknown       | AG958                       | Notebook    | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| American M... | IPPBT-RO                    | All in one  | [ea620e0681](https://linux-hardware.org/?probe=ea620e0681) | May 04, 2023 |
| American M... | IPPBT-RO                    | All in one  | [a2921975cd](https://linux-hardware.org/?probe=a2921975cd) | May 02, 2023 |
| Acer          | Swift SF314-57G             | Notebook    | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| AZW           | GT-R                        | Notebook    | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| Dell          | Latitude 7400               | Notebook    | [0f917420a1](https://linux-hardware.org/?probe=0f917420a1) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [c518902ba7](https://linux-hardware.org/?probe=c518902ba7) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [7eee4a859e](https://linux-hardware.org/?probe=7eee4a859e) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [874513db8d](https://linux-hardware.org/?probe=874513db8d) | Apr 12, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [7e0735056c](https://linux-hardware.org/?probe=7e0735056c) | Apr 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [ac4522914d](https://linux-hardware.org/?probe=ac4522914d) | Apr 02, 2023 |
| Pegatron      | 2ADC                        | Desktop     | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| ASUSTek       | X45A                        | Notebook    | [a0401520d5](https://linux-hardware.org/?probe=a0401520d5) | Mar 27, 2023 |
| ASUSTek       | X45A                        | Notebook    | [dbe8e77436](https://linux-hardware.org/?probe=dbe8e77436) | Mar 27, 2023 |
| ASUSTek       | X45A                        | Notebook    | [675de376da](https://linux-hardware.org/?probe=675de376da) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| Unknown       | GB01                        | Desktop     | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [c02aa4b9e1](https://linux-hardware.org/?probe=c02aa4b9e1) | Mar 23, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [7542f3fe88](https://linux-hardware.org/?probe=7542f3fe88) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | Notebook    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| HP            | 1589                        | Desktop     | [2fc61ae7b4](https://linux-hardware.org/?probe=2fc61ae7b4) | Mar 09, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [63f1f6f5dd](https://linux-hardware.org/?probe=63f1f6f5dd) | Mar 08, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e2244668d1](https://linux-hardware.org/?probe=e2244668d1) | Mar 02, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [4e45d95aa1](https://linux-hardware.org/?probe=4e45d95aa1) | Mar 01, 2023 |
| Dell          | Inspiron 3468               | Notebook    | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| Novatte       | M20                         | Desktop     | [f3b00d12f2](https://linux-hardware.org/?probe=f3b00d12f2) | Feb 14, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [de144d5025](https://linux-hardware.org/?probe=de144d5025) | Feb 12, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [e7cc1c6b15](https://linux-hardware.org/?probe=e7cc1c6b15) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [9a9b3eed69](https://linux-hardware.org/?probe=9a9b3eed69) | Feb 05, 2023 |
| Foxconn       | 17A0                        | Desktop     | [1a98ed31ed](https://linux-hardware.org/?probe=1a98ed31ed) | Feb 05, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [c172555349](https://linux-hardware.org/?probe=c172555349) | Jan 25, 2023 |
| Lenovo        | NOK                         | Desktop     | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Acer          | Aspire V5-132               | Notebook    | [7f74397112](https://linux-hardware.org/?probe=7f74397112) | Jan 24, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [7fef453cdb](https://linux-hardware.org/?probe=7fef453cdb) | Jan 23, 2023 |
| Acer          | Aspire ES1-432              | Notebook    | [4a81caf8b2](https://linux-hardware.org/?probe=4a81caf8b2) | Jan 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [d696233b84](https://linux-hardware.org/?probe=d696233b84) | Jan 18, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a73de9a5b9](https://linux-hardware.org/?probe=a73de9a5b9) | Jan 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cc5d8632f5](https://linux-hardware.org/?probe=cc5d8632f5) | Jan 13, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a8ee39edc5](https://linux-hardware.org/?probe=a8ee39edc5) | Jan 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [ae506ac561](https://linux-hardware.org/?probe=ae506ac561) | Jan 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2e6f75ca07](https://linux-hardware.org/?probe=2e6f75ca07) | Jan 06, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [3af1bc02b8](https://linux-hardware.org/?probe=3af1bc02b8) | Jan 05, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [0a1360a7dc](https://linux-hardware.org/?probe=0a1360a7dc) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | Inspiron 1420               | Notebook    | [fe6a8714da](https://linux-hardware.org/?probe=fe6a8714da) | Dec 31, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [6dac0c0943](https://linux-hardware.org/?probe=6dac0c0943) | Dec 29, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [8633f00865](https://linux-hardware.org/?probe=8633f00865) | Dec 26, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [802e7982de](https://linux-hardware.org/?probe=802e7982de) | Dec 26, 2022 |
| HP            | 8061                        | Desktop     | [4427032526](https://linux-hardware.org/?probe=4427032526) | Dec 24, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [e24692f75f](https://linux-hardware.org/?probe=e24692f75f) | Dec 24, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [61f064d35f](https://linux-hardware.org/?probe=61f064d35f) | Dec 22, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [d387b553bd](https://linux-hardware.org/?probe=d387b553bd) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [51f520d152](https://linux-hardware.org/?probe=51f520d152) | Dec 21, 2022 |
| Foxconn       | 17A0                        | Desktop     | [58a3486afd](https://linux-hardware.org/?probe=58a3486afd) | Dec 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [d5171f9491](https://linux-hardware.org/?probe=d5171f9491) | Dec 19, 2022 |
| Foxconn       | 17A0                        | Desktop     | [be57227f43](https://linux-hardware.org/?probe=be57227f43) | Dec 17, 2022 |
| Foxconn       | 17A0                        | Desktop     | [b2185eeab5](https://linux-hardware.org/?probe=b2185eeab5) | Dec 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| Foxconn       | 17A0                        | Desktop     | [4518247b07](https://linux-hardware.org/?probe=4518247b07) | Dec 14, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| Foxconn       | 17A0                        | Desktop     | [2f3b2f9fbb](https://linux-hardware.org/?probe=2f3b2f9fbb) | Dec 07, 2022 |
| HP            | 8061                        | Desktop     | [6e4cb7cde8](https://linux-hardware.org/?probe=6e4cb7cde8) | Dec 07, 2022 |
| HP            | 8061                        | Desktop     | [9d30b0126f](https://linux-hardware.org/?probe=9d30b0126f) | Dec 05, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| HP            | ZBook 15                    | Notebook    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | Notebook    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Dell          | Precision 3571              | Notebook    | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| Google        | Atlas                       | Notebook    | [77922a522d](https://linux-hardware.org/?probe=77922a522d) | Nov 09, 2022 |
| Google        | Atlas                       | Notebook    | [829fcb8f6a](https://linux-hardware.org/?probe=829fcb8f6a) | Nov 09, 2022 |
| Dell          | Precision 3571              | Notebook    | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [9da55445b0](https://linux-hardware.org/?probe=9da55445b0) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [0a0922ed82](https://linux-hardware.org/?probe=0a0922ed82) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Acer          | RS880M05                    | Desktop     | [7adee2fd97](https://linux-hardware.org/?probe=7adee2fd97) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [18893915f3](https://linux-hardware.org/?probe=18893915f3) | Oct 17, 2022 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [9ec02e49a3](https://linux-hardware.org/?probe=9ec02e49a3) | Oct 13, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | Notebook    | [855ad327a4](https://linux-hardware.org/?probe=855ad327a4) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | Notebook    | [829ec8aac1](https://linux-hardware.org/?probe=829ec8aac1) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [93680a7429](https://linux-hardware.org/?probe=93680a7429) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ae5fd894b6](https://linux-hardware.org/?probe=ae5fd894b6) | Sep 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Lenovo        | 10051                       | All in one  | [195ec7cb8c](https://linux-hardware.org/?probe=195ec7cb8c) | Sep 23, 2022 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [0f698c857c](https://linux-hardware.org/?probe=0f698c857c) | Sep 16, 2022 |
| Dell          | Precision 3561              | Notebook    | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| ASUSTek       | X99-E WS                    | Desktop     | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [db7f9099f2](https://linux-hardware.org/?probe=db7f9099f2) | Sep 05, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [5e20db2905](https://linux-hardware.org/?probe=5e20db2905) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f0c2f3a689](https://linux-hardware.org/?probe=f0c2f3a689) | Aug 24, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| Acer          | Aspire V5-471PG             | Notebook    | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| Timi          | TM1701                      | Notebook    | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | Notebook    | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | G15 5520                    | Notebook    | [07feaad5d2](https://linux-hardware.org/?probe=07feaad5d2) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [5931b46fe1](https://linux-hardware.org/?probe=5931b46fe1) | Aug 10, 2022 |
| HP            | 843B                        | Desktop     | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [681326262a](https://linux-hardware.org/?probe=681326262a) | Aug 08, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| HP            | ZBook 15v G5                | Notebook    | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| Acer          | Spin SP513-52N              | Convertible | [975a56edb1](https://linux-hardware.org/?probe=975a56edb1) | Jul 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [366f3c9611](https://linux-hardware.org/?probe=366f3c9611) | Jul 14, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [27f2c99f99](https://linux-hardware.org/?probe=27f2c99f99) | Jul 14, 2022 |
| Sony          | SVF1531V8CW                 | Notebook    | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Dell          | Latitude 3120               | Notebook    | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [a49c763e59](https://linux-hardware.org/?probe=a49c763e59) | Jun 23, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [c434fdda77](https://linux-hardware.org/?probe=c434fdda77) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [b30a078392](https://linux-hardware.org/?probe=b30a078392) | Jun 15, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [0415226162](https://linux-hardware.org/?probe=0415226162) | Jun 11, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [df2d1b5c12](https://linux-hardware.org/?probe=df2d1b5c12) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| Sony          | VPCCA15FG                   | Notebook    | [d155f5ee52](https://linux-hardware.org/?probe=d155f5ee52) | Jun 08, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Unknown       | ZynqMP SMK-K26 Rev1/B/A     | Soc         | [1acb6dc064](https://linux-hardware.org/?probe=1acb6dc064) | May 31, 2022 |
| Lenovo        | 14w 81MQS02H00              | Notebook    | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [8deb85f8e2](https://linux-hardware.org/?probe=8deb85f8e2) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3a7cd290f6](https://linux-hardware.org/?probe=3a7cd290f6) | Apr 30, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c6b9dfe36e](https://linux-hardware.org/?probe=c6b9dfe36e) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [b8c46a667d](https://linux-hardware.org/?probe=b8c46a667d) | Apr 12, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [8e602bc358](https://linux-hardware.org/?probe=8e602bc358) | Apr 07, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [7309102f77](https://linux-hardware.org/?probe=7309102f77) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [f4d3207c6d](https://linux-hardware.org/?probe=f4d3207c6d) | Mar 22, 2022 |
| AMI           | Intel                       | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [17b7d9dd0c](https://linux-hardware.org/?probe=17b7d9dd0c) | Mar 10, 2022 |
| HP            | 8054                        | Desktop     | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7f14afdd4](https://linux-hardware.org/?probe=d7f14afdd4) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [9eb75ab42f](https://linux-hardware.org/?probe=9eb75ab42f) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fbb2caeacf](https://linux-hardware.org/?probe=fbb2caeacf) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [c5acc050e4](https://linux-hardware.org/?probe=c5acc050e4) | Feb 19, 2022 |
| Dell          | Precision 7560              | Notebook    | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [55550ca825](https://linux-hardware.org/?probe=55550ca825) | Feb 13, 2022 |
| COPELION I... | ZX Series                   | Notebook    | [764c80257b](https://linux-hardware.org/?probe=764c80257b) | Feb 12, 2022 |
| COPELION I... | ZX Series                   | Notebook    | [958dcebefa](https://linux-hardware.org/?probe=958dcebefa) | Feb 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [a01c295f77](https://linux-hardware.org/?probe=a01c295f77) | Feb 09, 2022 |
| Acer          | Predator G9-792             | Notebook    | [c030ff8b96](https://linux-hardware.org/?probe=c030ff8b96) | Feb 09, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [5cb4dcfe48](https://linux-hardware.org/?probe=5cb4dcfe48) | Jan 29, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [39cac76612](https://linux-hardware.org/?probe=39cac76612) | Jan 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [a172ae51cf](https://linux-hardware.org/?probe=a172ae51cf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [efbe19b07b](https://linux-hardware.org/?probe=efbe19b07b) | Jan 20, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [af9aaff7ee](https://linux-hardware.org/?probe=af9aaff7ee) | Jan 05, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [9f745065df](https://linux-hardware.org/?probe=9f745065df) | Dec 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [aae3ae242f](https://linux-hardware.org/?probe=aae3ae242f) | Dec 21, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [ef12425b00](https://linux-hardware.org/?probe=ef12425b00) | Dec 19, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell          | 0VD5HY A04                  | Desktop     | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [b92a9a109f](https://linux-hardware.org/?probe=b92a9a109f) | Dec 18, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell          | 0C96W1 A02                  | Desktop     | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| Dell          | Inspiron 5580               | Notebook    | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| INET          | Z12B                        | Mini pc     | [a18fff612e](https://linux-hardware.org/?probe=a18fff612e) | Dec 05, 2021 |
| ASUSTek       | K501UX                      | Notebook    | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [4b9f5aed33](https://linux-hardware.org/?probe=4b9f5aed33) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7ad1f07edb](https://linux-hardware.org/?probe=7ad1f07edb) | Oct 21, 2021 |
| congatec      | conga-MA5 B.2               | Mini pc     | [a393bc32f9](https://linux-hardware.org/?probe=a393bc32f9) | Oct 18, 2021 |
| congatec      | conga-MA5 B.2               | Mini pc     | [10851c579f](https://linux-hardware.org/?probe=10851c579f) | Oct 16, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | UX32LA                      | Notebook    | [9763fb0928](https://linux-hardware.org/?probe=9763fb0928) | Sep 25, 2021 |
| ASUSTek       | UX32LA                      | Notebook    | [e97b7fce6b](https://linux-hardware.org/?probe=e97b7fce6b) | Sep 25, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [e1c9dadb12](https://linux-hardware.org/?probe=e1c9dadb12) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [fc440eee50](https://linux-hardware.org/?probe=fc440eee50) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [24cfb86539](https://linux-hardware.org/?probe=24cfb86539) | Sep 12, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [b7ff195931](https://linux-hardware.org/?probe=b7ff195931) | Sep 02, 2021 |
| Dell          | Precision 7560              | Notebook    | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [606b3cf160](https://linux-hardware.org/?probe=606b3cf160) | Aug 23, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f4ec2b8446](https://linux-hardware.org/?probe=f4ec2b8446) | Aug 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [d0952296d7](https://linux-hardware.org/?probe=d0952296d7) | Aug 17, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [b702f17a07](https://linux-hardware.org/?probe=b702f17a07) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | Notebook    | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Biostar       | TB250-BTC+                  | Desktop     | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | Notebook    | [978dbea880](https://linux-hardware.org/?probe=978dbea880) | Jul 27, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | Notebook    | [e3c0726e19](https://linux-hardware.org/?probe=e3c0726e19) | Jul 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f938836ae3](https://linux-hardware.org/?probe=f938836ae3) | Jul 24, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| ASUSTek       | K45VM                       | Notebook    | [6d08e71c4e](https://linux-hardware.org/?probe=6d08e71c4e) | Jul 07, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | Notebook    | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| LattePanda    | Alpha                       | Desktop     | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda    | Alpha                       | Desktop     | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| Sony          | VPCSB36FG                   | Notebook    | [c834499816](https://linux-hardware.org/?probe=c834499816) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [650e1b9bf5](https://linux-hardware.org/?probe=650e1b9bf5) | Jun 05, 2021 |
| Dell          | Latitude 7490               | Notebook    | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8bf489a0cb](https://linux-hardware.org/?probe=8bf489a0cb) | May 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e16504b6f4](https://linux-hardware.org/?probe=e16504b6f4) | May 25, 2021 |
| HP            | 198E                        | Desktop     | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [920ef637b1](https://linux-hardware.org/?probe=920ef637b1) | May 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c9c9d02ede](https://linux-hardware.org/?probe=c9c9d02ede) | May 20, 2021 |
| Sony          | VPCSB36FG                   | Notebook    | [828a8ac75d](https://linux-hardware.org/?probe=828a8ac75d) | May 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ffa207ed1e](https://linux-hardware.org/?probe=ffa207ed1e) | May 14, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d2d2eb910a](https://linux-hardware.org/?probe=d2d2eb910a) | May 12, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c17ba8c1a6](https://linux-hardware.org/?probe=c17ba8c1a6) | May 04, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock        | HM55-MXM                    | Desktop     | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| Lenovo        | ThinkCentre M90p 5864BM3    | Desktop     | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [e26f3c0f44](https://linux-hardware.org/?probe=e26f3c0f44) | Mar 29, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [e4c813c694](https://linux-hardware.org/?probe=e4c813c694) | Mar 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ce138f71dd](https://linux-hardware.org/?probe=ce138f71dd) | Mar 15, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [81b4d6916d](https://linux-hardware.org/?probe=81b4d6916d) | Mar 11, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [46ff93e8b8](https://linux-hardware.org/?probe=46ff93e8b8) | Mar 09, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [98a5817785](https://linux-hardware.org/?probe=98a5817785) | Mar 09, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [eb33727eff](https://linux-hardware.org/?probe=eb33727eff) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [b2795c1a02](https://linux-hardware.org/?probe=b2795c1a02) | Feb 13, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [e67e7f24e8](https://linux-hardware.org/?probe=e67e7f24e8) | Feb 11, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [cbb8e959b4](https://linux-hardware.org/?probe=cbb8e959b4) | Feb 05, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [a8f5211aee](https://linux-hardware.org/?probe=a8f5211aee) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [f4505630e3](https://linux-hardware.org/?probe=f4505630e3) | Feb 03, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [0e5eeb215d](https://linux-hardware.org/?probe=0e5eeb215d) | Jan 28, 2021 |
| ASUSTek       | UX360UAK                    | Convertible | [93b1606116](https://linux-hardware.org/?probe=93b1606116) | Jan 27, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Notebook      | P65_P67SE                   | Notebook    | [1b4cd968fd](https://linux-hardware.org/?probe=1b4cd968fd) | Jan 22, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [dc6edb4a25](https://linux-hardware.org/?probe=dc6edb4a25) | Jan 14, 2021 |
| Dell          | G3 3500                     | Notebook    | [27386ee67b](https://linux-hardware.org/?probe=27386ee67b) | Jan 12, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | Notebook    | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [10b66f86e5](https://linux-hardware.org/?probe=10b66f86e5) | Jan 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [4b19f38fcd](https://linux-hardware.org/?probe=4b19f38fcd) | Jan 02, 2021 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [3f041f4b71](https://linux-hardware.org/?probe=3f041f4b71) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [c30d1c7374](https://linux-hardware.org/?probe=c30d1c7374) | Dec 31, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [ccd41dd67e](https://linux-hardware.org/?probe=ccd41dd67e) | Dec 28, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [2fd914ada2](https://linux-hardware.org/?probe=2fd914ada2) | Dec 25, 2020 |
| Microsoft     | Surface Pro                 | Tablet      | [38d64b5845](https://linux-hardware.org/?probe=38d64b5845) | Dec 22, 2020 |
| Acer          | Aspire one                  | Notebook    | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| ASUSTek       | P9D-X Series                | Server      | [519b6669d2](https://linux-hardware.org/?probe=519b6669d2) | Dec 11, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [e28bcb99e5](https://linux-hardware.org/?probe=e28bcb99e5) | Dec 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| ASUSTek       | K45VM                       | Notebook    | [9dedb35f93](https://linux-hardware.org/?probe=9dedb35f93) | Dec 04, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Aftershock    | N15_N17RF1                  | Notebook    | [09b42b449a](https://linux-hardware.org/?probe=09b42b449a) | Nov 27, 2020 |
| Dell          | Precision 7530              | Notebook    | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [1250c7dfbe](https://linux-hardware.org/?probe=1250c7dfbe) | Nov 25, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [cc79643d27](https://linux-hardware.org/?probe=cc79643d27) | Nov 22, 2020 |
| Dell          | Latitude 7400               | Notebook    | [3154149e40](https://linux-hardware.org/?probe=3154149e40) | Nov 21, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [93678477d7](https://linux-hardware.org/?probe=93678477d7) | Nov 20, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [c0ab31022d](https://linux-hardware.org/?probe=c0ab31022d) | Nov 20, 2020 |
| Dell          | 0D441T A03                  | Desktop     | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| HP            | 81C6 MVB 0C                 | Server      | [298cea57e1](https://linux-hardware.org/?probe=298cea57e1) | Nov 19, 2020 |
| Dell          | Inspiron 5379               | Notebook    | [63815d0103](https://linux-hardware.org/?probe=63815d0103) | Nov 15, 2020 |
| ASUSTek       | M4A78-EM-1394               | Desktop     | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| Fujitsu       | LIFEBOOK SH561              | Notebook    | [759718c54b](https://linux-hardware.org/?probe=759718c54b) | Nov 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [f3f5326846](https://linux-hardware.org/?probe=f3f5326846) | Nov 08, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| HP            | 81C6 MVB 0C                 | Server      | [eaa10c5051](https://linux-hardware.org/?probe=eaa10c5051) | Oct 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [14cf318590](https://linux-hardware.org/?probe=14cf318590) | Oct 29, 2020 |
| Acer          | Swift SF314-54              | Notebook    | [35aa366265](https://linux-hardware.org/?probe=35aa366265) | Oct 18, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [8396c1d9e6](https://linux-hardware.org/?probe=8396c1d9e6) | Oct 13, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [b47f8da412](https://linux-hardware.org/?probe=b47f8da412) | Oct 09, 2020 |
| ASRock        | 990FX Killer                | Desktop     | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| HP            | Compaq 6510b                | Notebook    | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2dada3cfbe](https://linux-hardware.org/?probe=2dada3cfbe) | Sep 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0f7498f1b](https://linux-hardware.org/?probe=c0f7498f1b) | Sep 30, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [05ef194f79](https://linux-hardware.org/?probe=05ef194f79) | Sep 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [78566669f0](https://linux-hardware.org/?probe=78566669f0) | Sep 27, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [9ca4cba592](https://linux-hardware.org/?probe=9ca4cba592) | Sep 27, 2020 |
| Dell          | Inspiron 3476               | Notebook    | [021351472c](https://linux-hardware.org/?probe=021351472c) | Sep 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| HP            | Compaq 6510b                | Notebook    | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| HP            | Compaq 6510b                | Notebook    | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| HP            | Compaq 6510b                | Notebook    | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [4a4a01267c](https://linux-hardware.org/?probe=4a4a01267c) | Sep 18, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [dc9532c57b](https://linux-hardware.org/?probe=dc9532c57b) | Sep 12, 2020 |
| Samsung       | 305U1A                      | Notebook    | [9949d76953](https://linux-hardware.org/?probe=9949d76953) | Sep 09, 2020 |
| Samsung       | 305U1A                      | Notebook    | [9dbf37ad63](https://linux-hardware.org/?probe=9dbf37ad63) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [c9d6ce6954](https://linux-hardware.org/?probe=c9d6ce6954) | Sep 05, 2020 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Aftershock    | N8xxEP6                     | Notebook    | [d8e9d4edfd](https://linux-hardware.org/?probe=d8e9d4edfd) | Sep 04, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Dell          | Precision 7530              | Notebook    | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Aftershock    | N15_N17RF1                  | Notebook    | [e3e85f51cc](https://linux-hardware.org/?probe=e3e85f51cc) | Sep 03, 2020 |
| Dell          | Latitude 5400               | Notebook    | [498b1be7bd](https://linux-hardware.org/?probe=498b1be7bd) | Sep 02, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d6a3031f11](https://linux-hardware.org/?probe=d6a3031f11) | Aug 30, 2020 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| HP            | Compaq 6510b                | Notebook    | [7db74443d5](https://linux-hardware.org/?probe=7db74443d5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | Notebook    | [20f281e6e5](https://linux-hardware.org/?probe=20f281e6e5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | Notebook    | [2791e33d53](https://linux-hardware.org/?probe=2791e33d53) | Aug 24, 2020 |
| ASUSTek       | V200IB                      | All in one  | [16748c4ba8](https://linux-hardware.org/?probe=16748c4ba8) | Aug 23, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [8bc9e504d7](https://linux-hardware.org/?probe=8bc9e504d7) | Aug 13, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [9f944b581d](https://linux-hardware.org/?probe=9f944b581d) | Aug 09, 2020 |
| Sony          | VGN-CR32G_W                 | Notebook    | [faf8f6a6fa](https://linux-hardware.org/?probe=faf8f6a6fa) | Aug 08, 2020 |
| Sony          | VGN-CR32G_W                 | Notebook    | [421ed7dcba](https://linux-hardware.org/?probe=421ed7dcba) | Aug 08, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [4dffd28998](https://linux-hardware.org/?probe=4dffd28998) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | Notebook    | [4319315cd0](https://linux-hardware.org/?probe=4319315cd0) | Jul 25, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b6111e69ca](https://linux-hardware.org/?probe=b6111e69ca) | Jul 19, 2020 |
| ASRock        | HM55-MXM                    | Desktop     | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [b554a2c8ec](https://linux-hardware.org/?probe=b554a2c8ec) | Jul 14, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| HP            | Pavilion dv6000 (GF659EA... | Notebook    | [84a4ec9209](https://linux-hardware.org/?probe=84a4ec9209) | Jul 09, 2020 |
| HP            | EliteBook 725 G4            | Notebook    | [941e94f528](https://linux-hardware.org/?probe=941e94f528) | Jul 09, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | Notebook    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [16b4aed55f](https://linux-hardware.org/?probe=16b4aed55f) | Jul 07, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [e794850de2](https://linux-hardware.org/?probe=e794850de2) | Jul 05, 2020 |
| HP            | EliteBook 725 G4            | Notebook    | [b3e1336d2f](https://linux-hardware.org/?probe=b3e1336d2f) | Jul 04, 2020 |
| Acer          | Swift SF514-54GT            | Notebook    | [a5b63702a2](https://linux-hardware.org/?probe=a5b63702a2) | Jul 03, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3769ee6e50](https://linux-hardware.org/?probe=3769ee6e50) | Jul 01, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [121efa47d4](https://linux-hardware.org/?probe=121efa47d4) | Jul 01, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | Notebook    | [8d9ec3fd6e](https://linux-hardware.org/?probe=8d9ec3fd6e) | Jun 27, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [7b35a1c840](https://linux-hardware.org/?probe=7b35a1c840) | Jun 26, 2020 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [dd0834c2dd](https://linux-hardware.org/?probe=dd0834c2dd) | Jun 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| Lenovo        | IdeaPad U460 20056          | Notebook    | [31c7edc616](https://linux-hardware.org/?probe=31c7edc616) | Jun 17, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2c22387cdf](https://linux-hardware.org/?probe=2c22387cdf) | Jun 17, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [4add01698f](https://linux-hardware.org/?probe=4add01698f) | Jun 14, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| Dell          | Latitude E7440              | Notebook    | [1664235765](https://linux-hardware.org/?probe=1664235765) | Jun 03, 2020 |
| Dell          | Latitude E7440              | Notebook    | [d71cf3dba2](https://linux-hardware.org/?probe=d71cf3dba2) | Jun 03, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [a8c4b1a8cf](https://linux-hardware.org/?probe=a8c4b1a8cf) | Jun 01, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | Notebook    | [da2a23020c](https://linux-hardware.org/?probe=da2a23020c) | May 21, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [c91cd5679c](https://linux-hardware.org/?probe=c91cd5679c) | May 19, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [10e8823c6b](https://linux-hardware.org/?probe=10e8823c6b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Acer          | Predator PH315-52           | Notebook    | [7adb1a873c](https://linux-hardware.org/?probe=7adb1a873c) | May 04, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | Notebook    | [09817eac19](https://linux-hardware.org/?probe=09817eac19) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [c173e838c3](https://linux-hardware.org/?probe=c173e838c3) | Apr 26, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [6311e7f4b5](https://linux-hardware.org/?probe=6311e7f4b5) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [a9cd8ef28f](https://linux-hardware.org/?probe=a9cd8ef28f) | Apr 22, 2020 |
| Acer          | Prespa1                     | Notebook    | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [d5124038f4](https://linux-hardware.org/?probe=d5124038f4) | Apr 15, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [7e6120b5c7](https://linux-hardware.org/?probe=7e6120b5c7) | Apr 10, 2020 |
| Lenovo        | B50-30 20382                | Notebook    | [57b8f867a1](https://linux-hardware.org/?probe=57b8f867a1) | Apr 09, 2020 |
| Acer          | Aspire E5-473G              | Notebook    | [17f3a0e473](https://linux-hardware.org/?probe=17f3a0e473) | Apr 08, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Dell          | Latitude E6410              | Notebook    | [920a80dc90](https://linux-hardware.org/?probe=920a80dc90) | Mar 31, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [3c9bd63848](https://linux-hardware.org/?probe=3c9bd63848) | Mar 30, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [2a99d0f76b](https://linux-hardware.org/?probe=2a99d0f76b) | Mar 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [93d970f678](https://linux-hardware.org/?probe=93d970f678) | Mar 24, 2020 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [daa4d098dc](https://linux-hardware.org/?probe=daa4d098dc) | Mar 13, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | Notebook    | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [819116ee69](https://linux-hardware.org/?probe=819116ee69) | Feb 16, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [93c40180a2](https://linux-hardware.org/?probe=93c40180a2) | Feb 11, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [f6c3a576c2](https://linux-hardware.org/?probe=f6c3a576c2) | Feb 11, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [627909b9e5](https://linux-hardware.org/?probe=627909b9e5) | Feb 04, 2020 |
| Dell          | Inspiron 7591               | Notebook    | [b33d5cddc5](https://linux-hardware.org/?probe=b33d5cddc5) | Jan 25, 2020 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7910582d7c](https://linux-hardware.org/?probe=7910582d7c) | Jan 06, 2020 |
| Microsoft     | Surface Laptop 3            | Tablet      | [eb592eeb36](https://linux-hardware.org/?probe=eb592eeb36) | Jan 05, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer          | Aspire X3950                | Desktop     | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASUSTek       | U24E                        | Notebook    | [563b794d8a](https://linux-hardware.org/?probe=563b794d8a) | Dec 23, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [54109739eb](https://linux-hardware.org/?probe=54109739eb) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [5d75e45350](https://linux-hardware.org/?probe=5d75e45350) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [fb27c8cabb](https://linux-hardware.org/?probe=fb27c8cabb) | Dec 20, 2019 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [adec400398](https://linux-hardware.org/?probe=adec400398) | Dec 19, 2019 |
| ASRock        | Z370 Pro4                   | Desktop     | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [86221df903](https://linux-hardware.org/?probe=86221df903) | Nov 30, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell          | 0F3KHR A00                  | Desktop     | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| HP            | ZBook Studio G5             | Notebook    | [87503b1263](https://linux-hardware.org/?probe=87503b1263) | Aug 22, 2019 |
| ASUSTek       | X406UAR                     | Notebook    | [5e3ebad239](https://linux-hardware.org/?probe=5e3ebad239) | Jul 05, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [1d4494ee1f](https://linux-hardware.org/?probe=1d4494ee1f) | Jul 03, 2019 |
| Lenovo        | S20-30 20421                | Notebook    | [5c27867f6e](https://linux-hardware.org/?probe=5c27867f6e) | Jun 26, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [f938ce631a](https://linux-hardware.org/?probe=f938ce631a) | Jun 17, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [5e33156c57](https://linux-hardware.org/?probe=5e33156c57) | Jun 17, 2019 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0ab22425ea](https://linux-hardware.org/?probe=0ab22425ea) | May 28, 2019 |
| Apple         | MacBookPro11,5              | Notebook    | [ab95788992](https://linux-hardware.org/?probe=ab95788992) | May 18, 2019 |
| ASUSTek       | S500CA                      | Notebook    | [c0218275f7](https://linux-hardware.org/?probe=c0218275f7) | Apr 28, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [6a82c09344](https://linux-hardware.org/?probe=6a82c09344) | Apr 16, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [037f7f95c0](https://linux-hardware.org/?probe=037f7f95c0) | Apr 15, 2019 |
| ASUSTek       | ET2020I                     | Desktop     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| Acer          | AO751h                      | Notebook    | [0ee57513c5](https://linux-hardware.org/?probe=0ee57513c5) | Apr 07, 2019 |
| MSI           | X299 RAIDER                 | Desktop     | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI           | X299 RAIDER                 | Desktop     | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI           | Boston                      | Desktop     | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |
| MSI           | GE63VR 7RE                  | Notebook    | [635226b290](https://linux-hardware.org/?probe=635226b290) | May 31, 2018 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [ecd2f8138f](https://linux-hardware.org/?probe=ecd2f8138f) | Dec 27, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Singapore/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 78        | 18.14%  |
| Ubuntu 18.04                 | 39        | 9.07%   |
| Ubuntu 22.04                 | 29        | 6.74%   |
| Arch Rolling                 | 17        | 3.95%   |
| Fedora 33                    | 12        | 2.79%   |
| Linux Mint 21                | 9         | 2.09%   |
| Debian 11                    | 9         | 2.09%   |
| Pop!_OS 20.04                | 8         | 1.86%   |
| Fedora 38                    | 8         | 1.86%   |
| Arch                         | 8         | 1.86%   |
| Pop!_OS 22.04                | 7         | 1.63%   |
| Fedora 37                    | 7         | 1.63%   |
| ArcoLinux Rolling            | 7         | 1.63%   |
| OpenMandriva 23.01           | 6         | 1.4%    |
| KDE neon 20.04               | 6         | 1.4%    |
| Zorin 16                     | 5         | 1.16%   |
| Ubuntu 21.10                 | 5         | 1.16%   |
| Ubuntu 21.04                 | 5         | 1.16%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.16%   |
| OpenMandriva 23.03           | 5         | 1.16%   |
| Manjaro                      | 5         | 1.16%   |
| Linux Mint 20                | 5         | 1.16%   |
| Kubuntu 22.04                | 5         | 1.16%   |
| Debian 12                    | 5         | 1.16%   |
| Xubuntu 20.04                | 4         | 0.93%   |
| Pop!_OS 21.04                | 4         | 0.93%   |
| OpenMandriva 4.3             | 4         | 0.93%   |
| Linux Mint 21.1              | 4         | 0.93%   |
| Linux Mint 20.3              | 4         | 0.93%   |
| Fedora 36                    | 4         | 0.93%   |
| EndeavourOS Rolling          | 4         | 0.93%   |
| Debian Testing               | 4         | 0.93%   |
| Ubuntu 23.04                 | 3         | 0.7%    |
| Ubuntu 22.10                 | 3         | 0.7%    |
| Garuda Linux Soaring         | 3         | 0.7%    |
| Fedora 34                    | 3         | 0.7%    |
| Fedora 32                    | 3         | 0.7%    |
| Elementary 6.1               | 3         | 0.7%    |
| Debian                       | 3         | 0.7%    |
| Zorin 15                     | 2         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 164       | 40.1%   |
| Fedora        | 33        | 8.07%   |
| Arch          | 24        | 5.87%   |
| Pop!_OS       | 23        | 5.62%   |
| Debian        | 23        | 5.62%   |
| OpenMandriva  | 22        | 5.38%   |
| Linux Mint    | 21        | 5.13%   |
| Manjaro       | 10        | 2.44%   |
| Kubuntu       | 8         | 1.96%   |
| KDE neon      | 8         | 1.96%   |
| Zorin         | 7         | 1.71%   |
| ArcoLinux     | 7         | 1.71%   |
| Xubuntu       | 5         | 1.22%   |
| openSUSE      | 5         | 1.22%   |
| Ubuntu Unity  | 4         | 0.98%   |
| EndeavourOS   | 4         | 0.98%   |
| Rocky Linux   | 3         | 0.73%   |
| Lubuntu       | 3         | 0.73%   |
| Gentoo        | 3         | 0.73%   |
| Garuda Linux  | 3         | 0.73%   |
| Elementary    | 3         | 0.73%   |
| ROSA          | 2         | 0.49%   |
| RHEL          | 2         | 0.49%   |
| Raspbian      | 2         | 0.49%   |
| Nobara        | 2         | 0.49%   |
| MX            | 2         | 0.49%   |
| Kali          | 2         | 0.49%   |
| Endless       | 2         | 0.49%   |
| Clear Linux   | 2         | 0.49%   |
| Ubuntu MATE   | 1         | 0.24%   |
| Ubuntu Budgie | 1         | 0.24%   |
| Q4OS          | 1         | 0.24%   |
| NixOS         | 1         | 0.24%   |
| LMDE          | 1         | 0.24%   |
| Linux Lite    | 1         | 0.24%   |
| Devuan        | 1         | 0.24%   |
| Deepin        | 1         | 0.24%   |
| CentOS        | 1         | 0.24%   |
| Atz           | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-56-generic       | 14        | 2.96%   |
| 5.15.0-46-generic       | 9         | 1.9%    |
| 5.9.8-200.fc33.x86_64   | 6         | 1.27%   |
| 5.4.0-48-generic        | 6         | 1.27%   |
| 5.4.0-42-generic        | 6         | 1.27%   |
| 5.4.0-40-generic        | 6         | 1.27%   |
| 5.4.0-37-generic        | 6         | 1.27%   |
| 5.4.0-29-generic        | 6         | 1.27%   |
| 6.2.6-desktop-1omv2390  | 5         | 1.06%   |
| 6.1.1-desktop-1omv2290  | 5         | 1.06%   |
| 5.4.0-52-generic        | 5         | 1.06%   |
| 5.11.0-43-generic       | 5         | 1.06%   |
| 5.4.0-65-generic        | 4         | 0.85%   |
| 5.3.0-62-generic        | 4         | 0.85%   |
| 5.16.7-desktop-1omv4003 | 4         | 0.85%   |
| 5.15.0-58-generic       | 4         | 0.85%   |
| 5.15.0-43-generic       | 4         | 0.85%   |
| 5.15.0-41-generic       | 4         | 0.85%   |
| 6.3.8-200.fc38.x86_64   | 3         | 0.63%   |
| 6.2.15-300.fc38.x86_64  | 3         | 0.63%   |
| 6.2.14-300.fc38.x86_64  | 3         | 0.63%   |
| 6.2.0-20-generic        | 3         | 0.63%   |
| 5.4.0-7634-generic      | 3         | 0.63%   |
| 5.4.0-47-generic        | 3         | 0.63%   |
| 5.4.0-26-generic        | 3         | 0.63%   |
| 5.3.0-51-generic        | 3         | 0.63%   |
| 5.15.0-71-generic       | 3         | 0.63%   |
| 5.15.0-52-generic       | 3         | 0.63%   |
| 5.15.0-48-generic       | 3         | 0.63%   |
| 5.15.0-47-generic       | 3         | 0.63%   |
| 5.13.0-40-generic       | 3         | 0.63%   |
| 5.13.0-28-generic       | 3         | 0.63%   |
| 5.11.0-38-generic       | 3         | 0.63%   |
| 5.11.0-37-generic       | 3         | 0.63%   |
| 5.11.0-25-generic       | 3         | 0.63%   |
| 5.10.0-11-amd64         | 3         | 0.63%   |
| 5.0.0-23-generic        | 3         | 0.63%   |
| 6.3.8-zen1-1-zen        | 2         | 0.42%   |
| 6.3.5-desktop-3omv2390  | 2         | 0.42%   |
| 6.2.9-300.fc38.x86_64   | 2         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 73        | 16.22%  |
| 5.15.0  | 58        | 12.89%  |
| 5.11.0  | 21        | 4.67%   |
| 5.13.0  | 17        | 3.78%   |
| 5.8.0   | 16        | 3.56%   |
| 5.19.0  | 13        | 2.89%   |
| 4.18.0  | 13        | 2.89%   |
| 5.3.0   | 12        | 2.67%   |
| 5.10.0  | 12        | 2.67%   |
| 5.0.0   | 11        | 2.44%   |
| 4.15.0  | 11        | 2.44%   |
| 6.3.8   | 6         | 1.33%   |
| 6.1.1   | 6         | 1.33%   |
| 6.1.0   | 6         | 1.33%   |
| 5.9.8   | 6         | 1.33%   |
| 5.18.0  | 6         | 1.33%   |
| 6.2.6   | 5         | 1.11%   |
| 6.3.5   | 4         | 0.89%   |
| 6.2.0   | 4         | 0.89%   |
| 5.16.7  | 4         | 0.89%   |
| 6.2.15  | 3         | 0.67%   |
| 6.2.14  | 3         | 0.67%   |
| 6.0.0   | 3         | 0.67%   |
| 5.17.5  | 3         | 0.67%   |
| 5.13.13 | 3         | 0.67%   |
| 6.4.7   | 2         | 0.44%   |
| 6.3.9   | 2         | 0.44%   |
| 6.2.9   | 2         | 0.44%   |
| 6.2.10  | 2         | 0.44%   |
| 6.1.14  | 2         | 0.44%   |
| 6.0.7   | 2         | 0.44%   |
| 6.0.6   | 2         | 0.44%   |
| 6.0.2   | 2         | 0.44%   |
| 6.0.15  | 2         | 0.44%   |
| 5.4.51  | 2         | 0.44%   |
| 5.4.5   | 2         | 0.44%   |
| 5.19.13 | 2         | 0.44%   |
| 5.15.5  | 2         | 0.44%   |
| 5.15.10 | 2         | 0.44%   |
| 5.13.12 | 2         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 83        | 18.91%  |
| 5.15    | 72        | 16.4%   |
| 5.13    | 25        | 5.69%   |
| 5.8     | 24        | 5.47%   |
| 5.11    | 23        | 5.24%   |
| 5.10    | 21        | 4.78%   |
| 6.1     | 18        | 4.1%    |
| 5.19    | 17        | 3.87%   |
| 6.3     | 16        | 3.64%   |
| 6.2     | 15        | 3.42%   |
| 4.18    | 13        | 2.96%   |
| 5.3     | 12        | 2.73%   |
| 5.0     | 12        | 2.73%   |
| 6.0     | 11        | 2.51%   |
| 5.18    | 11        | 2.51%   |
| 4.15    | 11        | 2.51%   |
| 5.9     | 10        | 2.28%   |
| 5.16    | 10        | 2.28%   |
| 5.12    | 6         | 1.37%   |
| 6.4     | 5         | 1.14%   |
| 5.17    | 5         | 1.14%   |
| 5.6     | 4         | 0.91%   |
| 5.14    | 3         | 0.68%   |
| 4.19    | 3         | 0.68%   |
| 5.5     | 2         | 0.46%   |
| 4.16    | 2         | 0.46%   |
| 3.10    | 2         | 0.46%   |
| 6.3.0   | 1         | 0.23%   |
| 5.7     | 1         | 0.23%   |
| 4.4     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 389       | 98.23%  |
| aarch64 | 3         | 0.76%   |
| i686    | 2         | 0.51%   |
| armv7l  | 2         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 217       | 52.54%  |
| KDE5            | 65        | 15.74%  |
| Unknown         | 52        | 12.59%  |
| X-Cinnamon      | 24        | 5.81%   |
| XFCE            | 18        | 4.36%   |
| LXQt            | 6         | 1.45%   |
| KDE             | 6         | 1.45%   |
| Cinnamon        | 6         | 1.45%   |
| Unity           | 4         | 0.97%   |
| Pantheon        | 3         | 0.73%   |
| i3              | 3         | 0.73%   |
| MATE            | 2         | 0.48%   |
| GNOME Classic   | 2         | 0.48%   |
| Budgie          | 2         | 0.48%   |
| KDE4            | 1         | 0.24%   |
| Hyprland        | 1         | 0.24%   |
| GNOME Flashback | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 301       | 72.53%  |
| Wayland | 71        | 17.11%  |
| Unknown | 25        | 6.02%   |
| Tty     | 18        | 4.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 187       | 45.5%   |
| GDM     | 72        | 17.52%  |
| SDDM    | 59        | 14.36%  |
| GDM3    | 56        | 13.63%  |
| LightDM | 30        | 7.3%    |
| TDM     | 5         | 1.22%   |
| KDM     | 1         | 0.24%   |
| GREETD  | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_SG   | 162       | 39.8%   |
| en_US   | 155       | 38.08%  |
| Unknown | 28        | 6.88%   |
| zh_CN   | 14        | 3.44%   |
| C       | 14        | 3.44%   |
| en_IN   | 7         | 1.72%   |
| en_GB   | 7         | 1.72%   |
| en_AU   | 6         | 1.47%   |
| de_DE   | 6         | 1.47%   |
| en_PH   | 4         | 0.98%   |
| zh_SG   | 1         | 0.25%   |
| ru_UA   | 1         | 0.25%   |
| fr_FR   | 1         | 0.25%   |
| en_IE   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 271       | 67.92%  |
| BIOS | 128       | 32.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 307       | 75.99%  |
| Btrfs   | 45        | 11.14%  |
| Overlay | 22        | 5.45%   |
| Xfs     | 12        | 2.97%   |
| Unknown | 10        | 2.48%   |
| Tmpfs   | 6         | 1.49%   |
| Zfs     | 2         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 198       | 49.5%   |
| Unknown | 181       | 45.25%  |
| MBR     | 21        | 5.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 348       | 85.71%  |
| Yes       | 58        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 63.34%  |
| Yes       | 147       | 36.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 73        | 18.43%  |
| ASUSTek Computer                     | 67        | 16.92%  |
| Dell                                 | 65        | 16.41%  |
| Acer                                 | 31        | 7.83%   |
| Hewlett-Packard                      | 24        | 6.06%   |
| Gigabyte Technology                  | 22        | 5.56%   |
| MSI                                  | 21        | 5.3%    |
| Apple                                | 15        | 3.79%   |
| ASRock                               | 13        | 3.28%   |
| Intel                                | 6         | 1.52%   |
| Foxconn                              | 6         | 1.52%   |
| Sony                                 | 5         | 1.26%   |
| Unknown                              | 5         | 1.26%   |
| Raspberry Pi Foundation              | 4         | 1.01%   |
| Microsoft                            | 3         | 0.76%   |
| congatec                             | 3         | 0.76%   |
| AZW                                  | 3         | 0.76%   |
| Toshiba                              | 2         | 0.51%   |
| Timi                                 | 2         | 0.51%   |
| Samsung Electronics                  | 2         | 0.51%   |
| MECHREVO                             | 2         | 0.51%   |
| HUAWEI                               | 2         | 0.51%   |
| Fujitsu                              | 2         | 0.51%   |
| AMI                                  | 2         | 0.51%   |
| Aftershock                           | 2         | 0.51%   |
| SZMZ                                 | 1         | 0.25%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.25%   |
| Razer                                | 1         | 0.25%   |
| Pegatron                             | 1         | 0.25%   |
| Novatte                              | 1         | 0.25%   |
| Notebook                             | 1         | 0.25%   |
| LattePanda                           | 1         | 0.25%   |
| INET                                 | 1         | 0.25%   |
| HPE                                  | 1         | 0.25%   |
| Google                               | 1         | 0.25%   |
| ECS                                  | 1         | 0.25%   |
| COPELION INTERNATIONAL               | 1         | 0.25%   |
| Biostar                              | 1         | 0.25%   |
| American Megatrends                  | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 5         | 1.26%   |
| Unknown                                  | 5         | 1.26%   |
| Gigabyte X570 AORUS PRO WIFI             | 4         | 1.01%   |
| MSI MS-7C84                              | 3         | 0.76%   |
| Foxconn Pro 3330 MT                      | 3         | 0.76%   |
| Dell OptiPlex 9020                       | 3         | 0.76%   |
| Dell Inspiron 15 5510                    | 3         | 0.76%   |
| congatec conga-MA5 B.2                   | 3         | 0.76%   |
| RPi Raspberry Pi 4 Model B Rev 1.4       | 2         | 0.51%   |
| RPi Raspberry Pi 4 Model B Rev 1.2       | 2         | 0.51%   |
| Lenovo ThinkPad X220 42911H8             | 2         | 0.51%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 2         | 0.51%   |
| Lenovo IdeaPad S340-14API 81NB           | 2         | 0.51%   |
| Intel NUC11PAHi7                         | 2         | 0.51%   |
| HP Compaq 6510b                          | 2         | 0.51%   |
| Gigabyte B550I AORUS PRO AX              | 2         | 0.51%   |
| Foxconn Kangaroo Mobile Desktop          | 2         | 0.51%   |
| Dell XPS 13 9310                         | 2         | 0.51%   |
| Dell XPS 13 7390                         | 2         | 0.51%   |
| Dell OptiPlex 990                        | 2         | 0.51%   |
| Dell Latitude 3320                       | 2         | 0.51%   |
| Dell Latitude 3120                       | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 2         | 0.51%   |
| ASUS T300LA                              | 2         | 0.51%   |
| ASUS ROG STRIX B550-I GAMING             | 2         | 0.51%   |
| ASUS K45VM                               | 2         | 0.51%   |
| ASRock B450 Pro4                         | 2         | 0.51%   |
| Apple MacBookPro8,1                      | 2         | 0.51%   |
| Apple MacBookPro11,5                     | 2         | 0.51%   |
| Apple iMac19,1                           | 2         | 0.51%   |
| Acer Swift SF314-57G                     | 2         | 0.51%   |
| Acer Spin SP513-52N                      | 2         | 0.51%   |
| Acer ConceptD CN715-71                   | 2         | 0.51%   |
| Toshiba PORTEGE Z10t-A                   | 1         | 0.25%   |
| Toshiba PORTEGE R930                     | 1         | 0.25%   |
| Timi TM1701                              | 1         | 0.25%   |
| Timi Redmi Book Pro 14 2022              | 1         | 0.25%   |
| SZMZ X99M-H2                             | 1         | 0.25%   |
| Sony VPCSB36FG                           | 1         | 0.25%   |
| Sony VPCCA15FG                           | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 37        | 9.34%   |
| Dell Inspiron       | 19        | 4.8%    |
| Acer Aspire         | 14        | 3.54%   |
| Dell Latitude       | 13        | 3.28%   |
| Lenovo IdeaPad      | 11        | 2.78%   |
| Dell OptiPlex       | 11        | 2.78%   |
| ASUS VivoBook       | 11        | 2.78%   |
| Dell XPS            | 10        | 2.53%   |
| Lenovo Legion       | 8         | 2.02%   |
| Dell Precision      | 8         | 2.02%   |
| Acer Swift          | 8         | 2.02%   |
| HP Pavilion         | 7         | 1.77%   |
| ASUS ROG            | 7         | 1.77%   |
| Lenovo Yoga         | 6         | 1.52%   |
| ASUS ZenBook        | 5         | 1.26%   |
| ASUS All            | 5         | 1.26%   |
| Unknown             | 5         | 1.26%   |
| RPi Raspberry       | 4         | 1.01%   |
| Gigabyte X570       | 4         | 1.01%   |
| Apple MacBookPro11  | 4         | 1.01%   |
| MSI MS-7C84         | 3         | 0.76%   |
| Microsoft Surface   | 3         | 0.76%   |
| Lenovo ThinkCentre  | 3         | 0.76%   |
| HP ZBook            | 3         | 0.76%   |
| HP ENVY             | 3         | 0.76%   |
| HP EliteBook        | 3         | 0.76%   |
| Foxconn Pro         | 3         | 0.76%   |
| congatec conga-MA5  | 3         | 0.76%   |
| ASUS TUF            | 3         | 0.76%   |
| ASUS PRIME          | 3         | 0.76%   |
| Toshiba PORTEGE     | 2         | 0.51%   |
| Lenovo ThinkStation | 2         | 0.51%   |
| Intel NUC11PAHi7    | 2         | 0.51%   |
| HP ProDesk          | 2         | 0.51%   |
| HP Compaq           | 2         | 0.51%   |
| Gigabyte B550I      | 2         | 0.51%   |
| Gigabyte B450M      | 2         | 0.51%   |
| Gigabyte B365M      | 2         | 0.51%   |
| Fujitsu LIFEBOOK    | 2         | 0.51%   |
| Foxconn Kangaroo    | 2         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 54        | 13.64%  |
| 2018    | 46        | 11.62%  |
| 2020    | 45        | 11.36%  |
| 2021    | 44        | 11.11%  |
| 2013    | 24        | 6.06%   |
| 2012    | 23        | 5.81%   |
| 2011    | 23        | 5.81%   |
| 2022    | 22        | 5.56%   |
| 2016    | 20        | 5.05%   |
| 2017    | 19        | 4.8%    |
| 2014    | 19        | 4.8%    |
| 2015    | 18        | 4.55%   |
| 2010    | 12        | 3.03%   |
| 2008    | 8         | 2.02%   |
| 2007    | 7         | 1.77%   |
| 2023    | 4         | 1.01%   |
| 2009    | 4         | 1.01%   |
| Unknown | 4         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 229       | 57.83%  |
| Desktop        | 126       | 31.82%  |
| Mini pc        | 11        | 2.78%   |
| Convertible    | 10        | 2.53%   |
| All in one     | 8         | 2.02%   |
| System on chip | 5         | 1.26%   |
| Tablet         | 5         | 1.26%   |
| Server         | 2         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 351       | 88.19%  |
| Enabled  | 47        | 11.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 395       | 99.75%  |
| Yes  | 1         | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 105       | 25.99%  |
| 4.01-8.0        | 89        | 22.03%  |
| 8.01-16.0       | 65        | 16.09%  |
| 32.01-64.0      | 59        | 14.6%   |
| 3.01-4.0        | 48        | 11.88%  |
| 64.01-256.0     | 15        | 3.71%   |
| 24.01-32.0      | 11        | 2.72%   |
| 1.01-2.0        | 9         | 2.23%   |
| 2.01-3.0        | 2         | 0.5%    |
| More than 256.0 | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 117       | 26.35%  |
| 2.01-3.0   | 103       | 23.2%   |
| 4.01-8.0   | 85        | 19.14%  |
| 3.01-4.0   | 77        | 17.34%  |
| 8.01-16.0  | 32        | 7.21%   |
| 0.51-1.0   | 18        | 4.05%   |
| 0.01-0.5   | 7         | 1.58%   |
| 16.01-24.0 | 3         | 0.68%   |
| 32.01-64.0 | 1         | 0.23%   |
| 24.01-32.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 58.92%  |
| 2      | 106       | 25.92%  |
| 3      | 35        | 8.56%   |
| 4      | 16        | 3.91%   |
| 5      | 7         | 1.71%   |
| 0      | 4         | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 309       | 77.64%  |
| Yes       | 89        | 22.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 299       | 75.13%  |
| No        | 99        | 24.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 326       | 81.5%   |
| No        | 74        | 18.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 69.17%  |
| No        | 123       | 30.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Singapore | 396       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Singapore            | 380       | 95.48%  |
| Jurong West          | 7         | 1.76%   |
| Kampong Pasir Ris    | 5         | 1.26%   |
| Queenstown Estate    | 2         | 0.5%    |
| Yio Chu Kang         | 1         | 0.25%   |
| Sembawang Estate     | 1         | 0.25%   |
| Kampong Ulu Jurong   | 1         | 0.25%   |
| Bukit Batok New Town | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 106       | 161    | 17.91%  |
| Seagate                     | 65        | 80     | 10.98%  |
| WDC                         | 63        | 111    | 10.64%  |
| Toshiba                     | 43        | 59     | 7.26%   |
| SanDisk                     | 43        | 55     | 7.26%   |
| Unknown                     | 25        | 30     | 4.22%   |
| SK hynix                    | 25        | 27     | 4.22%   |
| Intel                       | 17        | 19     | 2.87%   |
| Crucial                     | 17        | 21     | 2.87%   |
| Micron Technology           | 15        | 17     | 2.53%   |
| Kingston                    | 15        | 20     | 2.53%   |
| Hitachi                     | 15        | 16     | 2.53%   |
| HGST                        | 13        | 20     | 2.2%    |
| KIOXIA                      | 8         | 8      | 1.35%   |
| Phison                      | 7         | 9      | 1.18%   |
| Silicon Motion              | 6         | 7      | 1.01%   |
| Phison Electronics          | 6         | 7      | 1.01%   |
| JMicron Technology          | 6         | 10     | 1.01%   |
| China                       | 6         | 6      | 1.01%   |
| Apple                       | 6         | 7      | 1.01%   |
| A-DATA Technology           | 6         | 7      | 1.01%   |
| Hewlett-Packard             | 5         | 6      | 0.84%   |
| Lexar                       | 4         | 4      | 0.68%   |
| Unknown                     | 4         | 4      | 0.68%   |
| Transcend                   | 3         | 4      | 0.51%   |
| Micron/Crucial Technology   | 3         | 4      | 0.51%   |
| Lenovo                      | 3         | 3      | 0.51%   |
| External                    | 3         | 3      | 0.51%   |
| Yangtze Memory Technologies | 2         | 2      | 0.34%   |
| SPCC                        | 2         | 2      | 0.34%   |
| SAGE                        | 2         | 2      | 0.34%   |
| Plextor                     | 2         | 2      | 0.34%   |
| Patriot                     | 2         | 2      | 0.34%   |
| OCZ                         | 2         | 2      | 0.34%   |
| Maxtor                      | 2         | 2      | 0.34%   |
| LITEON                      | 2         | 3      | 0.34%   |
| KLEVV                       | 2         | 2      | 0.34%   |
| YMTC                        | 1         | 1      | 0.17%   |
| WALRAM                      | 1         | 1      | 0.17%   |
| Vaseky                      | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB                                | 8         | 1.24%   |
| Seagate ST1000LM035-1RK172 1TB                        | 7         | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 7         | 1.09%   |
| Samsung SSD 860 EVO 500GB                             | 6         | 0.93%   |
| Samsung SSD 850 EVO 250GB                             | 6         | 0.93%   |
| Samsung NVMe SSD Drive 1024GB                         | 6         | 0.93%   |
| Unknown MMC Card  64GB                                | 5         | 0.78%   |
| Unknown MMC Card  32GB                                | 5         | 0.78%   |
| Toshiba DT01ACA200 2TB                                | 5         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB                        | 5         | 0.78%   |
| JMicron Generic 512GB                                 | 5         | 0.78%   |
| Crucial CT500MX500SSD1 500GB                          | 5         | 0.78%   |
| Toshiba MQ04ABF100 1TB                                | 4         | 0.62%   |
| Toshiba MQ01ABD100 1TB                                | 4         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 4         | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                        | 4         | 0.62%   |
| SanDisk SSD PLUS 480GB                                | 4         | 0.62%   |
| SanDisk NVMe SSD Drive 500GB                          | 4         | 0.62%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 4         | 0.62%   |
| HGST HTS721010A9E630 1TB                              | 4         | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                           | 4         | 0.62%   |
| Unknown                                               | 4         | 0.62%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 3         | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3         | 0.47%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 3         | 0.47%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 3         | 0.47%   |
| Seagate ST500DM002-1BD142 500GB                       | 3         | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 0.47%   |
| Seagate Expansion 1TB                                 | 3         | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                          | 3         | 0.47%   |
| Samsung SSD 980 500GB                                 | 3         | 0.47%   |
| Samsung SSD 860 EVO 1TB                               | 3         | 0.47%   |
| Samsung SSD 850 EVO 500GB                             | 3         | 0.47%   |
| Samsung SSD 850 EVO 1TB                               | 3         | 0.47%   |
| Samsung SSD 840 EVO 250GB                             | 3         | 0.47%   |
| Samsung NVMe SSD Drive 500GB                          | 3         | 0.47%   |
| Samsung NVMe SSD Drive 256GB                          | 3         | 0.47%   |
| Hitachi HTS545050A7E380 500GB                         | 3         | 0.47%   |
| HGST HTS545050A7E380 500GB                            | 3         | 0.47%   |
| External USB3.0 752GB                                 | 3         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 76     | 33.33%  |
| WDC                 | 44        | 72     | 23.66%  |
| Toshiba             | 33        | 47     | 17.74%  |
| Hitachi             | 15        | 16     | 8.06%   |
| HGST                | 13        | 20     | 6.99%   |
| JMicron Technology  | 5         | 9      | 2.69%   |
| Samsung Electronics | 3         | 5      | 1.61%   |
| External            | 3         | 3      | 1.61%   |
| Maxtor              | 2         | 2      | 1.08%   |
| Apple               | 2         | 2      | 1.08%   |
| SSK                 | 1         | 1      | 0.54%   |
| MARVELL             | 1         | 1      | 0.54%   |
| KESU                | 1         | 1      | 0.54%   |
| Fujitsu             | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 56        | 87     | 32.75%  |
| SanDisk             | 24        | 32     | 14.04%  |
| Crucial             | 11        | 14     | 6.43%   |
| Kingston            | 9         | 12     | 5.26%   |
| Micron Technology   | 6         | 8      | 3.51%   |
| China               | 6         | 6      | 3.51%   |
| WDC                 | 4         | 5      | 2.34%   |
| SK hynix            | 4         | 4      | 2.34%   |
| Hewlett-Packard     | 4         | 5      | 2.34%   |
| Apple               | 4         | 4      | 2.34%   |
| Transcend           | 3         | 4      | 1.75%   |
| A-DATA Technology   | 3         | 4      | 1.75%   |
| SPCC                | 2         | 2      | 1.17%   |
| SAGE                | 2         | 2      | 1.17%   |
| Plextor             | 2         | 2      | 1.17%   |
| Patriot             | 2         | 2      | 1.17%   |
| OCZ                 | 2         | 2      | 1.17%   |
| LITEON              | 2         | 3      | 1.17%   |
| Lexar               | 2         | 2      | 1.17%   |
| Intel               | 2         | 2      | 1.17%   |
| WALRAM              | 1         | 1      | 0.58%   |
| Vaseky              | 1         | 1      | 0.58%   |
| USB30               | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |
| Toshiba             | 1         | 1      | 0.58%   |
| TO Exter            | 1         | 1      | 0.58%   |
| Teclast             | 1         | 1      | 0.58%   |
| Pioneer             | 1         | 1      | 0.58%   |
| Netac               | 1         | 1      | 0.58%   |
| MidasForce          | 1         | 1      | 0.58%   |
| LITEONIT            | 1         | 1      | 0.58%   |
| KLEVV               | 1         | 1      | 0.58%   |
| Kingmax             | 1         | 1      | 0.58%   |
| KINGBANK            | 1         | 1      | 0.58%   |
| HS-SSD-E100         | 1         | 1      | 0.58%   |
| Haizhide            | 1         | 1      | 0.58%   |
| GAMER               | 1         | 1      | 0.58%   |
| GALAX               | 1         | 1      | 0.58%   |
| CT1000MX            | 1         | 2      | 0.58%   |
| Apacer              | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 190       | 273    | 36.12%  |
| HDD     | 162       | 256    | 30.8%   |
| SSD     | 146       | 224    | 27.76%  |
| MMC     | 22        | 27     | 4.18%   |
| Unknown | 6         | 6      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 242       | 448    | 49.69%  |
| NVMe | 190       | 267    | 39.01%  |
| SAS  | 33        | 44     | 6.78%   |
| MMC  | 22        | 27     | 4.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 163       | 250    | 50.62%  |
| 0.51-1.0   | 107       | 158    | 33.23%  |
| 1.01-2.0   | 26        | 34     | 8.07%   |
| 3.01-4.0   | 10        | 14     | 3.11%   |
| 4.01-10.0  | 10        | 17     | 3.11%   |
| 2.01-3.0   | 5         | 5      | 1.55%   |
| 10.01-20.0 | 1         | 2      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 24.11%  |
| 251-500        | 81        | 19.33%  |
| 501-1000       | 72        | 17.18%  |
| 1001-2000      | 38        | 9.07%   |
| More than 3000 | 30        | 7.16%   |
| 1-20           | 29        | 6.92%   |
| 51-100         | 23        | 5.49%   |
| 21-50          | 16        | 3.82%   |
| Unknown        | 15        | 3.58%   |
| 2001-3000      | 14        | 3.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 152       | 35.6%   |
| 21-50          | 71        | 16.63%  |
| 101-250        | 59        | 13.82%  |
| 251-500        | 43        | 10.07%  |
| 51-100         | 36        | 8.43%   |
| 501-1000       | 24        | 5.62%   |
| 1001-2000      | 16        | 3.75%   |
| Unknown        | 15        | 3.51%   |
| More than 3000 | 7         | 1.64%   |
| 2001-3000      | 4         | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB                    | 3         | 5      | 10.71%  |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 3.57%   |
| WDC WD5000BPVT-16HXZT1 500GB                   | 1         | 1      | 3.57%   |
| WDC WD5000AVDS-73U7B1 500GB                    | 1         | 1      | 3.57%   |
| WDC WD5000AAKS-22V1A0 500GB                    | 1         | 1      | 3.57%   |
| WDC WD50 EZRX-00MVLB1 5TB                      | 1         | 1      | 3.57%   |
| WDC WD10SPZX-21Z10T0 1TB                       | 1         | 2      | 3.57%   |
| WDC WD10EZEX-60M2NA0 1TB                       | 1         | 1      | 3.57%   |
| WDC WD1002FAEX-00Z3A0 1TB                      | 1         | 1      | 3.57%   |
| WDC WD1002FAEX-00Y9A0 1TB                      | 1         | 1      | 3.57%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 3.57%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 3.57%   |
| Teclast 480GB A800 SSD                         | 1         | 1      | 3.57%   |
| Seagate ST8000NM0055-1RM112 8TB                | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 3.57%   |
| Seagate ST31500341AS 1TB                       | 1         | 1      | 3.57%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 1         | 1      | 3.57%   |
| Seagate ST1000LM024 HN-M 1TB                   | 1         | 1      | 3.57%   |
| SanDisk SSD U100 24GB                          | 1         | 1      | 3.57%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 3.57%   |
| Hitachi HTS545032B9A300 320GB                  | 1         | 1      | 3.57%   |
| Hitachi HTS541010A9E680 1TB                    | 1         | 1      | 3.57%   |
| Hitachi HDS721010CLA632 1TB                    | 1         | 1      | 3.57%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 3.57%   |
| Crucial CT120M500SSD1 120GB                    | 1         | 3      | 3.57%   |
| China SSD 128GB                                | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 11        | 15     | 42.31%  |
| Seagate           | 4         | 5      | 15.38%  |
| Hitachi           | 3         | 3      | 11.54%  |
| Toshiba           | 2         | 2      | 7.69%   |
| Teclast           | 1         | 1      | 3.85%   |
| SanDisk           | 1         | 1      | 3.85%   |
| Micron Technology | 1         | 1      | 3.85%   |
| HGST              | 1         | 1      | 3.85%   |
| Crucial           | 1         | 3      | 3.85%   |
| China             | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 15     | 52.38%  |
| Seagate | 4         | 5      | 19.05%  |
| Hitachi | 3         | 3      | 14.29%  |
| Toshiba | 2         | 2      | 9.52%   |
| HGST    | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 26     | 80.77%  |
| SSD  | 5         | 7      | 19.23%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD1002FAEX-00Z3A0 1TB     | 1         | 1      | 50%     |
| JMicron Technology Tech 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 1         | 1      | 50%     |
| JMicron Technology | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 227       | 391    | 51.36%  |
| Works    | 187       | 360    | 42.31%  |
| Malfunc  | 26        | 33     | 5.88%   |
| Failed   | 2         | 2      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 247       | 46.08%  |
| AMD                          | 67        | 12.5%   |
| Samsung Electronics          | 62        | 11.57%  |
| SanDisk                      | 35        | 6.53%   |
| SK hynix                     | 21        | 3.92%   |
| Phison Electronics           | 12        | 2.24%   |
| Toshiba America Info Systems | 10        | 1.87%   |
| Silicon Motion               | 9         | 1.68%   |
| Micron/Crucial Technology    | 9         | 1.68%   |
| Micron Technology            | 9         | 1.68%   |
| KIOXIA                       | 9         | 1.68%   |
| ASMedia Technology           | 9         | 1.68%   |
| Kingston Technology Company  | 7         | 1.31%   |
| ADATA Technology             | 4         | 0.75%   |
| Shenzhen Longsys Electronics | 3         | 0.56%   |
| Nvidia                       | 3         | 0.56%   |
| Marvell Technology Group     | 3         | 0.56%   |
| Lenovo                       | 3         | 0.56%   |
| Yangtze Memory Technologies  | 2         | 0.37%   |
| Seagate Technology           | 2         | 0.37%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.37%   |
| Adaptec                      | 2         | 0.37%   |
| VIA Technologies             | 1         | 0.19%   |
| Union Memory (Shenzhen)      | 1         | 0.19%   |
| Realtek Semiconductor        | 1         | 0.19%   |
| JMicron Technology           | 1         | 0.19%   |
| INNOGRIT                     | 1         | 0.19%   |
| Broadcom / LSI               | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 51        | 8.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 35        | 6.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 21        | 3.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 15        | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 2.07%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.72%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 1.55%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 1.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 1.38%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 8         | 1.38%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 8         | 1.38%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 1.38%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 1.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 7         | 1.2%    |
| Intel SSD 660P Series                                                          | 7         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 0.86%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 4         | 0.69%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 265       | 50.57%  |
| NVMe | 191       | 36.45%  |
| RAID | 38        | 7.25%   |
| IDE  | 26        | 4.96%   |
| SAS  | 4         | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 302       | 76.26%  |
| AMD    | 89        | 22.47%  |
| ARM    | 5         | 1.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 2.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 2.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 2.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 1.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.26%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.26%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 1.26%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 5         | 1.26%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 1.01%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.01%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.76%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.76%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 3         | 0.76%   |
| ARM Processor                                 | 3         | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.76%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.51%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.51%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.51%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.51%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.51%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.51%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.51%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.51%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.51%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.51%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.51%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 88        | 22.22%  |
| Intel Core i5           | 88        | 22.22%  |
| Other                   | 46        | 11.62%  |
| AMD Ryzen 7             | 27        | 6.82%   |
| AMD Ryzen 5             | 27        | 6.82%   |
| Intel Celeron           | 16        | 4.04%   |
| Intel Xeon              | 15        | 3.79%   |
| Intel Core i3           | 11        | 2.78%   |
| Intel Core 2 Duo        | 11        | 2.78%   |
| AMD Ryzen 9             | 8         | 2.02%   |
| Intel Atom              | 6         | 1.52%   |
| Intel Pentium Silver    | 4         | 1.01%   |
| Intel Pentium           | 4         | 1.01%   |
| Intel Core i9           | 4         | 1.01%   |
| Intel Core m3           | 3         | 0.76%   |
| AMD Ryzen 7 PRO         | 3         | 0.76%   |
| AMD Ryzen 3             | 3         | 0.76%   |
| Intel Pentium Dual      | 2         | 0.51%   |
| Intel Core 2 Quad       | 2         | 0.51%   |
| ARM BCM                 | 2         | 0.51%   |
| AMD Ryzen Threadripper  | 2         | 0.51%   |
| AMD Ryzen 5 PRO         | 2         | 0.51%   |
| AMD PRO A10             | 2         | 0.51%   |
| AMD FX                  | 2         | 0.51%   |
| AMD Athlon              | 2         | 0.51%   |
| AMD A10                 | 2         | 0.51%   |
| Intel Xeon Silver       | 1         | 0.25%   |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Pentium Dual-Core | 1         | 0.25%   |
| Intel Pentium 4         | 1         | 0.25%   |
| Intel Core m7           | 1         | 0.25%   |
| Intel Core 2            | 1         | 0.25%   |
| AMD Turion 64 X2 Mobile | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD Phenom II X4        | 1         | 0.25%   |
| AMD Opteron             | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD E1                  | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD A6                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 166       | 41.92%  |
| 2      | 109       | 27.53%  |
| 6      | 47        | 11.87%  |
| 8      | 45        | 11.36%  |
| 16     | 7         | 1.77%   |
| 12     | 7         | 1.77%   |
| 14     | 5         | 1.26%   |
| 10     | 5         | 1.26%   |
| 1      | 3         | 0.76%   |
| 24     | 1         | 0.25%   |
| 3      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 394       | 99.49%  |
| 2      | 2         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 292       | 73.37%  |
| 1      | 106       | 26.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 389       | 98.23%  |
| Unknown        | 5         | 1.26%   |
| 32-bit         | 2         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 22.52%  |
| 0x306a9    | 21        | 5.08%   |
| 0x906ea    | 18        | 4.36%   |
| 0x806ea    | 17        | 4.12%   |
| 0x206a7    | 17        | 4.12%   |
| 0x306c3    | 15        | 3.63%   |
| 0x806ec    | 14        | 3.39%   |
| 0x806c1    | 13        | 3.15%   |
| 0x506e3    | 11        | 2.66%   |
| 0x0a50000c | 10        | 2.42%   |
| 0x20655    | 8         | 1.94%   |
| 0x806eb    | 7         | 1.69%   |
| 0x806e9    | 7         | 1.69%   |
| 0x40651    | 7         | 1.69%   |
| 0x6fd      | 6         | 1.45%   |
| 0x406e3    | 6         | 1.45%   |
| 0x306d4    | 6         | 1.45%   |
| 0x1067a    | 6         | 1.45%   |
| 0x08701021 | 6         | 1.45%   |
| 0x08108109 | 5         | 1.21%   |
| 0x906e9    | 4         | 0.97%   |
| 0x906c0    | 4         | 0.97%   |
| 0x90672    | 4         | 0.97%   |
| 0x806d1    | 4         | 0.97%   |
| 0x306e4    | 4         | 0.97%   |
| 0x0a404102 | 4         | 0.97%   |
| 0x08600106 | 4         | 0.97%   |
| 0xa0652    | 3         | 0.73%   |
| 0x906ed    | 3         | 0.73%   |
| 0x806c2    | 3         | 0.73%   |
| 0x706a1    | 3         | 0.73%   |
| 0x506ca    | 3         | 0.73%   |
| 0x50654    | 3         | 0.73%   |
| 0x406c3    | 3         | 0.73%   |
| 0x40661    | 3         | 0.73%   |
| 0x0a201016 | 3         | 0.73%   |
| 0x08701013 | 3         | 0.73%   |
| 0x08108102 | 3         | 0.73%   |
| 0x06003106 | 3         | 0.73%   |
| 0xa0660    | 2         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 85        | 21.46%  |
| Haswell          | 30        | 7.58%   |
| IvyBridge        | 29        | 7.32%   |
| Unknown          | 23        | 5.81%   |
| Zen 3            | 22        | 5.56%   |
| TigerLake        | 22        | 5.56%   |
| Skylake          | 22        | 5.56%   |
| SandyBridge      | 22        | 5.56%   |
| Zen 2            | 21        | 5.3%    |
| Zen+             | 14        | 3.54%   |
| Core             | 9         | 2.27%   |
| Broadwell        | 9         | 2.27%   |
| Alderlake Hybrid | 9         | 2.27%   |
| Westmere         | 8         | 2.02%   |
| Silvermont       | 8         | 2.02%   |
| Penryn           | 8         | 2.02%   |
| Icelake          | 8         | 2.02%   |
| CometLake        | 8         | 2.02%   |
| Goldmont         | 6         | 1.52%   |
| Zen              | 5         | 1.26%   |
| Goldmont plus    | 5         | 1.26%   |
| Tremont          | 4         | 1.01%   |
| Excavator        | 4         | 1.01%   |
| Steamroller      | 3         | 0.76%   |
| K10              | 3         | 0.76%   |
| Piledriver       | 2         | 0.51%   |
| Bonnell          | 2         | 0.51%   |
| Bobcat           | 2         | 0.51%   |
| NetBurst         | 1         | 0.25%   |
| K8 Hammer        | 1         | 0.25%   |
| Jaguar           | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 250       | 49.6%   |
| Nvidia            | 155       | 30.75%  |
| AMD               | 97        | 19.25%  |
| ASPEED Technology | 2         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 21        | 4.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 4.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.92%   |
| Intel HD Graphics 620                                                                    | 9         | 1.73%   |
| Intel HD Graphics 530                                                                    | 9         | 1.73%   |
| AMD Renoir                                                                               | 8         | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.35%   |
| AMD Rembrandt [Radeon 680M]                                                              | 7         | 1.35%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.15%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 5         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.96%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.96%   |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 0.96%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.77%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 4         | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.77%   |
| Intel HD Graphics 500                                                                    | 4         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.77%   |
| Intel AlderLake-S GT1                                                                    | 4         | 0.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.58%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.58%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 158       | 39.21%  |
| Intel + Nvidia  | 75        | 18.61%  |
| 1 x AMD         | 67        | 16.63%  |
| 1 x Nvidia      | 63        | 15.63%  |
| AMD + Nvidia    | 12        | 2.98%   |
| Intel + AMD     | 11        | 2.73%   |
| 2 x AMD         | 6         | 1.49%   |
| Other           | 5         | 1.24%   |
| 2 x Nvidia      | 4         | 0.99%   |
| Nvidia + ASPEED | 2         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 288       | 71.29%  |
| Proprietary | 97        | 24.01%  |
| Unknown     | 19        | 4.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 239       | 57.73%  |
| 1.01-2.0   | 53        | 12.8%   |
| 3.01-4.0   | 31        | 7.49%   |
| 0.01-0.5   | 28        | 6.76%   |
| 7.01-8.0   | 21        | 5.07%   |
| 0.51-1.0   | 18        | 4.35%   |
| 8.01-16.0  | 13        | 3.14%   |
| 5.01-6.0   | 10        | 2.42%   |
| 2.01-3.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 73        | 17.06%  |
| Dell                 | 60        | 14.02%  |
| Samsung Electronics  | 46        | 10.75%  |
| BOE                  | 35        | 8.18%   |
| LG Display           | 32        | 7.48%   |
| Chimei Innolux       | 24        | 5.61%   |
| Acer                 | 16        | 3.74%   |
| Apple                | 14        | 3.27%   |
| Sharp                | 13        | 3.04%   |
| Goldstar             | 13        | 3.04%   |
| Hewlett-Packard      | 12        | 2.8%    |
| Philips              | 11        | 2.57%   |
| AOC                  | 6         | 1.4%    |
| Lenovo               | 5         | 1.17%   |
| InfoVision           | 5         | 1.17%   |
| CSO                  | 5         | 1.17%   |
| PANDA                | 4         | 0.93%   |
| ASUSTek Computer     | 4         | 0.93%   |
| PRISM+               | 3         | 0.7%    |
| Denver               | 3         | 0.7%    |
| Ancor Communications | 3         | 0.7%    |
| ViewSonic            | 2         | 0.47%   |
| Toshiba              | 2         | 0.47%   |
| Sony                 | 2         | 0.47%   |
| Pixio                | 2         | 0.47%   |
| Mi                   | 2         | 0.47%   |
| LG Philips           | 2         | 0.47%   |
| Lenovo Group Limited | 2         | 0.47%   |
| CVT                  | 2         | 0.47%   |
| Unknown              | 2         | 0.47%   |
| Xiaomi               | 1         | 0.23%   |
| Wacom                | 1         | 0.23%   |
| Unknown (XXX)        | 1         | 0.23%   |
| Unknown              | 1         | 0.23%   |
| TMX                  | 1         | 0.23%   |
| Tianma XM            | 1         | 0.23%   |
| SGT                  | 1         | 0.23%   |
| SAC                  | 1         | 0.23%   |
| RTK                  | 1         | 0.23%   |
| Panasonic            | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 4         | 0.92%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 4         | 0.92%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                       | 4         | 0.92%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 4         | 0.92%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3         | 0.69%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                   | 3         | 0.69%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch              | 3         | 0.69%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                       | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch          | 3         | 0.69%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 2         | 0.46%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch    | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0F18 3840x2160 1872x1053mm 84.6-inch | 2         | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2         | 0.46%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch                 | 2         | 0.46%   |
| Pixio DP WAM2700 1920x1080 598x336mm 27.0-inch                          | 2         | 0.46%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch                 | 2         | 0.46%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch            | 2         | 0.46%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 2         | 0.46%   |
| Goldstar IPS224 GSM58D5 1920x1080 477x268mm 21.5-inch                   | 2         | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 0.46%   |
| Denver GB-2461CF LHC0236 1920x1080 530x280mm 23.6-inch                  | 2         | 0.46%   |
| Dell U2720Q DEL41B3 3840x2160 597x336mm 27.0-inch                       | 2         | 0.46%   |
| Dell SE2723DS DELD153 2560x1440 598x336mm 27.0-inch                     | 2         | 0.46%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                     | 2         | 0.46%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                     | 2         | 0.46%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                       | 2         | 0.46%   |
| Dell LCD Monitor P2217H 1920x1080                                       | 2         | 0.46%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                      | 2         | 0.46%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                       | 2         | 0.46%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                        | 2         | 0.46%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                        | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch        | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch        | 2         | 0.46%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                   | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 201       | 49.51%  |
| 1366x768 (WXGA)    | 50        | 12.32%  |
| 3840x2160 (4K)     | 38        | 9.36%   |
| 2560x1440 (QHD)    | 32        | 7.88%   |
| 1600x900 (HD+)     | 14        | 3.45%   |
| 1280x800 (WXGA)    | 10        | 2.46%   |
| 2560x1600          | 9         | 2.22%   |
| 1920x1200 (WUXGA)  | 8         | 1.97%   |
| 2880x1800          | 6         | 1.48%   |
| 3440x1440          | 5         | 1.23%   |
| 1360x768           | 5         | 1.23%   |
| 3000x2000          | 3         | 0.74%   |
| 1440x900 (WXGA+)   | 3         | 0.74%   |
| 1280x1024 (SXGA)   | 3         | 0.74%   |
| 3840x2400          | 2         | 0.49%   |
| 3200x1800 (QHD+)   | 2         | 0.49%   |
| 3072x1920          | 2         | 0.49%   |
| 2736x1824          | 2         | 0.49%   |
| 2560x1080          | 2         | 0.49%   |
| 2240x1400          | 2         | 0.49%   |
| 1680x1050 (WSXGA+) | 2         | 0.49%   |
| 3840x1600          | 1         | 0.25%   |
| 3286x1080          | 1         | 0.25%   |
| 2496x1664          | 1         | 0.25%   |
| 1024x600           | 1         | 0.25%   |
| Unknown            | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 78        | 18.4%   |
| 13      | 67        | 15.8%   |
| 14      | 52        | 12.26%  |
| 27      | 41        | 9.67%   |
| 23      | 29        | 6.84%   |
| 24      | 24        | 5.66%   |
| Unknown | 20        | 4.72%   |
| 21      | 19        | 4.48%   |
| 12      | 14        | 3.3%    |
| 20      | 10        | 2.36%   |
| 31      | 8         | 1.89%   |
| 11      | 8         | 1.89%   |
| 19      | 7         | 1.65%   |
| 18      | 6         | 1.42%   |
| 16      | 6         | 1.42%   |
| 40      | 4         | 0.94%   |
| 34      | 4         | 0.94%   |
| 84      | 3         | 0.71%   |
| 32      | 3         | 0.71%   |
| 28      | 3         | 0.71%   |
| 65      | 2         | 0.47%   |
| 54      | 2         | 0.47%   |
| 25      | 2         | 0.47%   |
| 17      | 2         | 0.47%   |
| 55      | 1         | 0.24%   |
| 52      | 1         | 0.24%   |
| 50      | 1         | 0.24%   |
| 39      | 1         | 0.24%   |
| 37      | 1         | 0.24%   |
| 35      | 1         | 0.24%   |
| 26      | 1         | 0.24%   |
| 22      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |
| 8       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 160       | 38%     |
| 501-600     | 93        | 22.09%  |
| 201-300     | 62        | 14.73%  |
| 401-500     | 40        | 9.5%    |
| Unknown     | 20        | 4.75%   |
| 601-700     | 12        | 2.85%   |
| 351-400     | 9         | 2.14%   |
| 801-900     | 7         | 1.66%   |
| 701-800     | 7         | 1.66%   |
| 1001-1500   | 7         | 1.66%   |
| 1501-2000   | 3         | 0.71%   |
| 101-200     | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 303       | 79.32%  |
| 16/10   | 43        | 11.26%  |
| Unknown | 17        | 4.45%   |
| 3/2     | 7         | 1.83%   |
| 21/9    | 7         | 1.83%   |
| 5/4     | 3         | 0.79%   |
| 6/5     | 1         | 0.26%   |
| 0.62    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 84        | 19.91%  |
| 101-110        | 79        | 18.72%  |
| 201-250        | 60        | 14.22%  |
| 301-350        | 42        | 9.95%   |
| 71-80          | 33        | 7.82%   |
| 151-200        | 23        | 5.45%   |
| Unknown        | 20        | 4.74%   |
| 351-500        | 18        | 4.27%   |
| 61-70          | 13        | 3.08%   |
| More than 1000 | 10        | 2.37%   |
| 251-300        | 9         | 2.13%   |
| 51-60          | 8         | 1.9%    |
| 141-150        | 6         | 1.42%   |
| 501-1000       | 6         | 1.42%   |
| 111-120        | 5         | 1.18%   |
| 91-100         | 3         | 0.71%   |
| 41-50          | 1         | 0.24%   |
| 1-40           | 1         | 0.24%   |
| 121-130        | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 122       | 29.47%  |
| 51-100        | 109       | 26.33%  |
| 101-120       | 76        | 18.36%  |
| 161-240       | 59        | 14.25%  |
| More than 240 | 20        | 4.83%   |
| Unknown       | 20        | 4.83%   |
| 1-50          | 8         | 1.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 328       | 79.42%  |
| 2     | 61        | 14.77%  |
| 0     | 21        | 5.08%   |
| 3     | 3         | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 225       | 39.68%  |
| Realtek Semiconductor    | 173       | 30.51%  |
| Qualcomm Atheros         | 63        | 11.11%  |
| Broadcom                 | 31        | 5.47%   |
| MediaTek                 | 14        | 2.47%   |
| TP-Link                  | 8         | 1.41%   |
| ASIX Electronics         | 8         | 1.41%   |
| Marvell Technology Group | 6         | 1.06%   |
| Ralink Technology        | 4         | 0.71%   |
| Sierra Wireless          | 3         | 0.53%   |
| Samsung Electronics      | 3         | 0.53%   |
| Qualcomm                 | 3         | 0.53%   |
| Broadcom Limited         | 3         | 0.53%   |
| ASUSTek Computer         | 3         | 0.53%   |
| Linksys                  | 2         | 0.35%   |
| Lenovo                   | 2         | 0.35%   |
| Hewlett-Packard          | 2         | 0.35%   |
| Aquantia                 | 2         | 0.35%   |
| STMicroelectronics       | 1         | 0.18%   |
| Ralink                   | 1         | 0.18%   |
| Nvidia                   | 1         | 0.18%   |
| MosChip Semiconductor    | 1         | 0.18%   |
| Microsoft                | 1         | 0.18%   |
| Google                   | 1         | 0.18%   |
| Fargo                    | 1         | 0.18%   |
| Exar                     | 1         | 0.18%   |
| Edimax Technology        | 1         | 0.18%   |
| Dell                     | 1         | 0.18%   |
| D-Link                   | 1         | 0.18%   |
| Apple                    | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 109       | 16.24%  |
| Intel Wi-Fi 6 AX200                                               | 34        | 5.07%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 2.24%   |
| Intel Wireless 7265                                               | 15        | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 2.09%   |
| Intel Wireless 8265 / 8275                                        | 14        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 1.94%   |
| Intel I211 Gigabit Network Connection                             | 13        | 1.94%   |
| Intel Ethernet Controller I225-V                                  | 13        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.49%   |
| Intel Wireless 7260                                               | 9         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.34%   |
| Intel Wireless 3165                                               | 8         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.19%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.75%   |
| Intel Wireless 8260                                               | 5         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.75%   |
| Realtek 802.11ac NIC                                              | 4         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 0.6%    |
| Intel Wireless-AC 9260                                            | 4         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.6%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.6%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 185       | 54.57%  |
| Qualcomm Atheros         | 53        | 15.63%  |
| Realtek Semiconductor    | 35        | 10.32%  |
| Broadcom                 | 22        | 6.49%   |
| MediaTek                 | 14        | 4.13%   |
| TP-Link                  | 8         | 2.36%   |
| Ralink Technology        | 4         | 1.18%   |
| Sierra Wireless          | 3         | 0.88%   |
| ASUSTek Computer         | 3         | 0.88%   |
| Qualcomm                 | 2         | 0.59%   |
| Marvell Technology Group | 2         | 0.59%   |
| Broadcom Limited         | 2         | 0.59%   |
| Ralink                   | 1         | 0.29%   |
| Linksys                  | 1         | 0.29%   |
| Hewlett-Packard          | 1         | 0.29%   |
| Edimax Technology        | 1         | 0.29%   |
| Dell                     | 1         | 0.29%   |
| D-Link                   | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                             | 34        | 9.94%   |
| Intel Wi-Fi 6 AX201                                             | 21        | 6.14%   |
| Intel Wireless 7265                                             | 15        | 4.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 14        | 4.09%   |
| Intel Wireless 8265 / 8275                                      | 14        | 4.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 11        | 3.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 10        | 2.92%   |
| Intel Wireless 7260                                             | 9         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 9         | 2.63%   |
| Intel Wireless 3165                                             | 8         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 8         | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 7         | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 7         | 2.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter   | 7         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 6         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                | 6         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 5         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 5         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 5         | 1.46%   |
| Intel Wireless 8260                                             | 5         | 1.46%   |
| Realtek 802.11ac NIC                                            | 4         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 4         | 1.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 4         | 1.17%   |
| Intel Wireless-AC 9260                                          | 4         | 1.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 4         | 1.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                     | 4         | 1.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.17%   |
| Sierra Wireless EM7455                                          | 3         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter        | 3         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                 | 3         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 3         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 3         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 3         | 0.88%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 3         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 3         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 3         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 3         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 3         | 0.88%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3         | 0.88%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                      | 2         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 151       | 47.78%  |
| Intel                    | 107       | 33.86%  |
| Qualcomm Atheros         | 15        | 4.75%   |
| Broadcom                 | 15        | 4.75%   |
| ASIX Electronics         | 8         | 2.53%   |
| Marvell Technology Group | 4         | 1.27%   |
| Samsung Electronics      | 3         | 0.95%   |
| Lenovo                   | 2         | 0.63%   |
| Aquantia                 | 2         | 0.63%   |
| Qualcomm                 | 1         | 0.32%   |
| Nvidia                   | 1         | 0.32%   |
| MosChip Semiconductor    | 1         | 0.32%   |
| Microsoft                | 1         | 0.32%   |
| Linksys                  | 1         | 0.32%   |
| Hewlett-Packard          | 1         | 0.32%   |
| Google                   | 1         | 0.32%   |
| Broadcom Limited         | 1         | 0.32%   |
| Apple                    | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 109       | 33.44%  |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 4.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.99%   |
| Intel I211 Gigabit Network Connection                             | 13        | 3.99%   |
| Intel Ethernet Controller I225-V                                  | 13        | 3.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.07%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 2.45%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.53%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.53%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.23%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.61%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.61%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.61%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.61%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 326       | 51.91%  |
| Ethernet | 299       | 47.61%  |
| Modem    | 2         | 0.32%   |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 262       | 62.23%  |
| Ethernet | 158       | 37.53%  |
| Unknown  | 1         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 200       | 50.38%  |
| 1     | 183       | 46.1%   |
| 0     | 7         | 1.76%   |
| 3     | 6         | 1.51%   |
| 4     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 369       | 93.18%  |
| Yes  | 27        | 6.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 55.87%  |
| Qualcomm Atheros Communications | 18        | 6.41%   |
| IMC Networks                    | 14        | 4.98%   |
| Foxconn / Hon Hai               | 13        | 4.63%   |
| Realtek Semiconductor           | 12        | 4.27%   |
| Lite-On Technology              | 12        | 4.27%   |
| Cambridge Silicon Radio         | 12        | 4.27%   |
| Apple                           | 12        | 4.27%   |
| Broadcom                        | 10        | 3.56%   |
| MediaTek                        | 5         | 1.78%   |
| TP-Link                         | 4         | 1.42%   |
| Marvell Semiconductor           | 2         | 0.71%   |
| USI                             | 1         | 0.36%   |
| Toshiba                         | 1         | 0.36%   |
| SINO WEALTH                     | 1         | 0.36%   |
| Realtek                         | 1         | 0.36%   |
| Ralink Technology               | 1         | 0.36%   |
| Foxconn International           | 1         | 0.36%   |
| Dell                            | 1         | 0.36%   |
| Chicony Electronics             | 1         | 0.36%   |
| Askey Computer                  | 1         | 0.36%   |
| Alps Electric                   | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 17.02%  |
| Intel AX201 Bluetooth                               | 40        | 14.18%  |
| Intel AX200 Bluetooth                               | 29        | 10.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 26        | 9.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 4.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 3.55%   |
| Realtek Bluetooth Radio                             | 7         | 2.48%   |
| Apple Bluetooth Host Controller                     | 7         | 2.48%   |
| Intel Bluetooth Device                              | 6         | 2.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.77%   |
| MediaTek Wireless_Device                            | 5         | 1.77%   |
| Lite-On Bluetooth Device                            | 5         | 1.77%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.77%   |
| TP-Link UB500 Adapter                               | 4         | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.42%   |
| IMC Networks Wireless_Device                        | 4         | 1.42%   |
| IMC Networks Bluetooth Device                       | 4         | 1.42%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.42%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.06%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.71%   |
| Lite-On Bluetooth Radio                             | 2         | 0.71%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.71%   |
| Intel AX210 Bluetooth                               | 2         | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.71%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.71%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.71%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.71%   |
| USI Bluetooth Device                                | 1         | 0.35%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.35%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.35%   |
| Realtek Bluetooth Radio                             | 1         | 0.35%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 292       | 54.07%  |
| Nvidia                                       | 102       | 18.89%  |
| AMD                                          | 99        | 18.33%  |
| C-Media Electronics                          | 4         | 0.74%   |
| Logitech                                     | 3         | 0.56%   |
| SteelSeries ApS                              | 2         | 0.37%   |
| SAVITECH                                     | 2         | 0.37%   |
| Plantronics                                  | 2         | 0.37%   |
| Lenovo                                       | 2         | 0.37%   |
| Kingston Technology                          | 2         | 0.37%   |
| Creative Labs                                | 2         | 0.37%   |
| ASUSTek Computer                             | 2         | 0.37%   |
| Apple                                        | 2         | 0.37%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.19%   |
| XMOS                                         | 1         | 0.19%   |
| TTGK Technology                              | 1         | 0.19%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.19%   |
| Tenx Technology                              | 1         | 0.19%   |
| Sony                                         | 1         | 0.19%   |
| Setek Elektronik                             | 1         | 0.19%   |
| Sennheiser Communications                    | 1         | 0.19%   |
| Samson Technologies                          | 1         | 0.19%   |
| RODE Microphones                             | 1         | 0.19%   |
| Realtek Semiconductor                        | 1         | 0.19%   |
| Razer USA                                    | 1         | 0.19%   |
| NXP Semiconductors                           | 1         | 0.19%   |
| MV                                           | 1         | 0.19%   |
| Micro Star International                     | 1         | 0.19%   |
| JMTek                                        | 1         | 0.19%   |
| Jieli Technology                             | 1         | 0.19%   |
| JBL                                          | 1         | 0.19%   |
| Huawei Technologies                          | 1         | 0.19%   |
| GN Netcom                                    | 1         | 0.19%   |
| Giga-Byte Technology                         | 1         | 0.19%   |
| FiiO Electronics Technology                  | 1         | 0.19%   |
| Cooler Master                                | 1         | 0.19%   |
| Conexant Systems                             | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 48        | 7.54%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 4.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 3.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20        | 3.14%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 2.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 9         | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.26%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 1.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 1.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8         | 1.26%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.1%    |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.94%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 0.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.78%   |
| Intel Jasper Lake HD Audio                                                 | 5         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 57        | 20.14%  |
| SK hynix                       | 56        | 19.79%  |
| Micron Technology              | 35        | 12.37%  |
| Kingston                       | 30        | 10.6%   |
| Crucial                        | 25        | 8.83%   |
| Unknown                        | 12        | 4.24%   |
| Corsair                        | 10        | 3.53%   |
| G.Skill                        | 8         | 2.83%   |
| A-DATA Technology              | 6         | 2.12%   |
| Transcend                      | 5         | 1.77%   |
| Ramaxel Technology             | 4         | 1.41%   |
| KLEVV                          | 4         | 1.41%   |
| Elpida                         | 4         | 1.41%   |
| Unknown (ABCD)                 | 3         | 1.06%   |
| Undefi                         | 3         | 1.06%   |
| Nanya Technology               | 3         | 1.06%   |
| Patriot                        | 2         | 0.71%   |
| Lexar                          | 2         | 0.71%   |
| Kingmax                        | 2         | 0.71%   |
| ASint Technology               | 2         | 0.71%   |
| V-GeN                          | 1         | 0.35%   |
| Unknown (0x0E9D)               | 1         | 0.35%   |
| Unknown (0x0B92)               | 1         | 0.35%   |
| Unknown (0x02BA)               | 1         | 0.35%   |
| Team                           | 1         | 0.35%   |
| Qimonda                        | 1         | 0.35%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.35%   |
| Essencore Limited              | 1         | 0.35%   |
| Carry                          | 1         | 0.35%   |
| Unknown                        | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 4         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 4         | 1.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 3         | 0.99%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s           | 3         | 0.99%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 3         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 3         | 0.99%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s         | 3         | 0.99%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 2         | 0.66%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 2         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 0.66%   |
| Undefi RAM Module 2GB SODIMM DDR3 1866MT/s                        | 2         | 0.66%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 2         | 0.66%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 0.66%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 2         | 0.66%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 0.66%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.66%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s        | 2         | 0.66%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 0.66%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s             | 2         | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 2         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s          | 2         | 0.66%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.66%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s    | 2         | 0.66%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s           | 2         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 2         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s             | 2         | 0.66%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s            | 2         | 0.66%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                    | 2         | 0.66%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 2         | 0.66%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s             | 2         | 0.66%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s            | 2         | 0.66%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s               | 2         | 0.66%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                        | 2         | 0.66%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s           | 2         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 126       | 52.72%  |
| DDR3    | 66        | 27.62%  |
| LPDDR4  | 14        | 5.86%   |
| LPDDR3  | 14        | 5.86%   |
| DDR5    | 6         | 2.51%   |
| SDRAM   | 5         | 2.09%   |
| LPDDR5  | 3         | 1.26%   |
| DDR2    | 3         | 1.26%   |
| Unknown | 2         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 133       | 56.36%  |
| DIMM         | 71        | 30.08%  |
| Row Of Chips | 29        | 12.29%  |
| Chip         | 2         | 0.85%   |
| Unknown      | 1         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 97        | 37.02%  |
| 4096  | 65        | 24.81%  |
| 16384 | 63        | 24.05%  |
| 2048  | 20        | 7.63%   |
| 32768 | 14        | 5.34%   |
| 1024  | 3         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 51        | 19.17%  |
| 1600    | 46        | 17.29%  |
| 2667    | 39        | 14.66%  |
| 2400    | 24        | 9.02%   |
| 2133    | 14        | 5.26%   |
| 1333    | 13        | 4.89%   |
| 4267    | 9         | 3.38%   |
| 3600    | 9         | 3.38%   |
| 1867    | 6         | 2.26%   |
| 1334    | 6         | 2.26%   |
| 4800    | 5         | 1.88%   |
| 1866    | 5         | 1.88%   |
| 6400    | 4         | 1.5%    |
| 3266    | 4         | 1.5%    |
| 2666    | 4         | 1.5%    |
| 1067    | 3         | 1.13%   |
| 8400    | 2         | 0.75%   |
| 3733    | 2         | 0.75%   |
| 3400    | 2         | 0.75%   |
| 2048    | 2         | 0.75%   |
| 1800    | 2         | 0.75%   |
| 800     | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 5808    | 1         | 0.38%   |
| 5600    | 1         | 0.38%   |
| 4333    | 1         | 0.38%   |
| 4199    | 1         | 0.38%   |
| 4000    | 1         | 0.38%   |
| 3666    | 1         | 0.38%   |
| 2200    | 1         | 0.38%   |
| 2134    | 1         | 0.38%   |
| 1200    | 1         | 0.38%   |
| 667     | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Philips (or NXP)    | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung M2020 Series         | 1         | 50%     |
| Philips (or NXP) USB Printer | 1         | 50%     |

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
| Chicony Electronics                    | 56        | 23.53%  |
| IMC Networks                           | 34        | 14.29%  |
| Microdia                               | 29        | 12.18%  |
| Realtek Semiconductor                  | 20        | 8.4%    |
| Sunplus Innovation Technology          | 14        | 5.88%   |
| Logitech                               | 12        | 5.04%   |
| Apple                                  | 12        | 5.04%   |
| Bison Electronics                      | 8         | 3.36%   |
| Suyin                                  | 7         | 2.94%   |
| Lite-On Technology                     | 7         | 2.94%   |
| Acer                                   | 6         | 2.52%   |
| Syntek                                 | 5         | 2.1%    |
| Samsung Electronics                    | 5         | 2.1%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.26%   |
| Silicon Motion                         | 2         | 0.84%   |
| Ricoh                                  | 2         | 0.84%   |
| OmniVision Technologies                | 2         | 0.84%   |
| Luxvisions Innotech Limited            | 2         | 0.84%   |
| Alcor Micro                            | 2         | 0.84%   |
| Z-Star Microelectronics                | 1         | 0.42%   |
| SunplusIT                              | 1         | 0.42%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.42%   |
| Sonix Technology                       | 1         | 0.42%   |
| Quanta                                 | 1         | 0.42%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.42%   |
| Microsoft                              | 1         | 0.42%   |
| Magic Control Technology               | 1         | 0.42%   |
| Lenovo                                 | 1         | 0.42%   |
| Intel                                  | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 18        | 7.5%    |
| Chicony Integrated Camera                        | 13        | 5.42%   |
| Chicony HD WebCam                                | 12        | 5%      |
| IMC Networks Integrated Camera                   | 10        | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                | 9         | 3.75%   |
| Sunplus Integrated_Webcam_HD                     | 7         | 2.92%   |
| Realtek Integrated_Webcam_HD                     | 7         | 2.92%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 2.5%    |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 2.08%   |
| Acer Integrated Camera                           | 5         | 2.08%   |
| Lite-On Integrated Camera                        | 4         | 1.67%   |
| IMC Networks USB2.0 HD IR UVC WebCam             | 4         | 1.67%   |
| Chicony HP HD Camera                             | 4         | 1.67%   |
| Apple FaceTime HD Camera (Built-in)              | 4         | 1.67%   |
| Syntek Integrated Camera                         | 3         | 1.25%   |
| Microdia USB 2.0 Camera                          | 3         | 1.25%   |
| Logitech HD Webcam C615                          | 3         | 1.25%   |
| Logitech HD Pro Webcam C920                      | 3         | 1.25%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 1.25%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.25%   |
| Bison Integrated Camera                          | 3         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 3         | 1.25%   |
| Apple FaceTime HD Camera                         | 3         | 1.25%   |
| Realtek Integrated Webcam_HD                     | 2         | 0.83%   |
| Realtek Asus 2.0 USB Webcam                      | 2         | 0.83%   |
| OmniVision OV2640 Webcam                         | 2         | 0.83%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 0.83%   |
| Microdia Integrated Camera                       | 2         | 0.83%   |
| Luxvisions Innotech Limited Integrated Camera    | 2         | 0.83%   |
| Logitech Webcam C270                             | 2         | 0.83%   |
| Logitech C922 Pro Stream Webcam                  | 2         | 0.83%   |
| Lite-On HP Wide Vision HD Camera                 | 2         | 0.83%   |
| IMC Networks Lenovo EasyCamera                   | 2         | 0.83%   |
| Chicony VGA Webcam                               | 2         | 0.83%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.83%   |
| Chicony USB2.0 Camera                            | 2         | 0.83%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 0.83%   |
| Chicony HD User Facing                           | 2         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 0.83%   |
| Bison BisonCam, NB Pro                           | 2         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 18        | 26.47%  |
| Validity Sensors                   | 13        | 19.12%  |
| Elan Microelectronics              | 9         | 13.24%  |
| Shenzhen Goodix Technology         | 8         | 11.76%  |
| LighTuning Technology              | 7         | 10.29%  |
| Upek                               | 6         | 8.82%   |
| AuthenTec                          | 6         | 8.82%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 13.24%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 10.29%  |
| Elan ELAN:Fingerprint                                                      | 7         | 10.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 8.82%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.41%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 4.41%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 4.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.94%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.94%   |
| AuthenTec AES2810                                                          | 2         | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.94%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.47%   |
| Synaptics WBDI                                                             | 1         | 1.47%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.47%   |
| Synaptics Fingerprint scanner                                              | 1         | 1.47%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.47%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.47%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.47%   |
| Unknown                                                                    | 1         | 1.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 70%     |
| Alcor Micro | 2         | 20%     |
| Clay Logic  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 40%     |
| Broadcom BCM5880 Secure Applications Processor | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 20%     |
| Clay Logic Nitrokey Start                      | 1         | 10%     |
| Broadcom 5880                                  | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 265       | 64.63%  |
| 1     | 112       | 27.32%  |
| 2     | 27        | 6.59%   |
| 3     | 4         | 0.98%   |
| 5     | 1         | 0.24%   |
| 4     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 63        | 34.81%  |
| Graphics card            | 45        | 24.86%  |
| Net/wireless             | 20        | 11.05%  |
| Multimedia controller    | 14        | 7.73%   |
| Chipcard                 | 9         | 4.97%   |
| Communication controller | 7         | 3.87%   |
| Camera                   | 7         | 3.87%   |
| Net/ethernet             | 4         | 2.21%   |
| Unassigned class         | 3         | 1.66%   |
| Network                  | 2         | 1.1%    |
| Bluetooth                | 2         | 1.1%    |
| Wireless                 | 1         | 0.55%   |
| Storage/raid             | 1         | 0.55%   |
| Sound                    | 1         | 0.55%   |
| Firewire controller      | 1         | 0.55%   |
| Dvb card                 | 1         | 0.55%   |


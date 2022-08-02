Linux in Czechia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Czechia/Desktop/README.md) and [notebooks](/Location/Czechia/Notebook/README.md).

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

Total: 2209

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d704ff7364](https://linux-hardware.org/?probe=d704ff7364) | Jul 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| HP            | 1494                        | Desktop     | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [55e2c27aaa](https://linux-hardware.org/?probe=55e2c27aaa) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [e8c6448552](https://linux-hardware.org/?probe=e8c6448552) | Jul 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [2986a26253](https://linux-hardware.org/?probe=2986a26253) | Jul 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [c6888145e7](https://linux-hardware.org/?probe=c6888145e7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | Notebook    | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9e77145b20](https://linux-hardware.org/?probe=9e77145b20) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [02a8803d9a](https://linux-hardware.org/?probe=02a8803d9a) | Jul 07, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Dell          | Latitude 7520               | Notebook    | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | Notebook    | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [38b91d59e7](https://linux-hardware.org/?probe=38b91d59e7) | Jul 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [01fb492b9d](https://linux-hardware.org/?probe=01fb492b9d) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [b4b8457bd9](https://linux-hardware.org/?probe=b4b8457bd9) | Jul 01, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [de5734cbe0](https://linux-hardware.org/?probe=de5734cbe0) | Jul 01, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [dd8c266ad2](https://linux-hardware.org/?probe=dd8c266ad2) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [7b07f30b17](https://linux-hardware.org/?probe=7b07f30b17) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| Gigabyte      | Z690 UD                     | Desktop     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | Notebook    | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | Notebook    | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| HP            | 8711                        | Mini pc     | [6ceafddb10](https://linux-hardware.org/?probe=6ceafddb10) | Jun 13, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [bbba4fae4b](https://linux-hardware.org/?probe=bbba4fae4b) | Jun 12, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8b02f3e420](https://linux-hardware.org/?probe=8b02f3e420) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | Notebook    | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [805f88e697](https://linux-hardware.org/?probe=805f88e697) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [a473dc4060](https://linux-hardware.org/?probe=a473dc4060) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | Notebook    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | Desktop     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [276f8565dc](https://linux-hardware.org/?probe=276f8565dc) | May 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1a31d93797](https://linux-hardware.org/?probe=1a31d93797) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | Notebook    | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [e7c21e067a](https://linux-hardware.org/?probe=e7c21e067a) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [8ed772fb1d](https://linux-hardware.org/?probe=8ed772fb1d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | Notebook    | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Acer          | Z2621G                      | All in one  | [139c780029](https://linux-hardware.org/?probe=139c780029) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| MSI           | B85M-G43                    | Desktop     | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [77c7c34b9e](https://linux-hardware.org/?probe=77c7c34b9e) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HP            | 22F8                        | Desktop     | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [e8915a5023](https://linux-hardware.org/?probe=e8915a5023) | May 15, 2022 |
| ASUSTek       | X555LB                      | Notebook    | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [5f148de534](https://linux-hardware.org/?probe=5f148de534) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [14905c8ec7](https://linux-hardware.org/?probe=14905c8ec7) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | Notebook    | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [d2deff798c](https://linux-hardware.org/?probe=d2deff798c) | May 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a3e95474a0](https://linux-hardware.org/?probe=a3e95474a0) | May 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [97a95fa1af](https://linux-hardware.org/?probe=97a95fa1af) | May 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [09944d29bf](https://linux-hardware.org/?probe=09944d29bf) | May 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | Notebook    | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f4a6777382](https://linux-hardware.org/?probe=f4a6777382) | Apr 30, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [3b927afe90](https://linux-hardware.org/?probe=3b927afe90) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [97c0bfb76c](https://linux-hardware.org/?probe=97c0bfb76c) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| HP            | 22F8                        | Desktop     | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [ab5986371d](https://linux-hardware.org/?probe=ab5986371d) | Apr 23, 2022 |
| HP            | 22F8                        | Desktop     | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | Notebook    | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | Notebook    | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [68d9ef89c7](https://linux-hardware.org/?probe=68d9ef89c7) | Apr 19, 2022 |
| MSI           | B150 PC MATE                | Desktop     | [34c7fe45bc](https://linux-hardware.org/?probe=34c7fe45bc) | Apr 19, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [497807c732](https://linux-hardware.org/?probe=497807c732) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [874e39c8ef](https://linux-hardware.org/?probe=874e39c8ef) | Apr 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a2b841241d](https://linux-hardware.org/?probe=a2b841241d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| Acer          | Aspire V3-112P              | Notebook    | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [b1944bf89e](https://linux-hardware.org/?probe=b1944bf89e) | Apr 15, 2022 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [19b11d696f](https://linux-hardware.org/?probe=19b11d696f) | Apr 15, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | Notebook    | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Gigabyte      | Z590 VISION D               | Desktop     | [4bde7cc5cd](https://linux-hardware.org/?probe=4bde7cc5cd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8a5920ae1a](https://linux-hardware.org/?probe=8a5920ae1a) | Apr 13, 2022 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [46dc99c237](https://linux-hardware.org/?probe=46dc99c237) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | Desktop     | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c01d51d1f5](https://linux-hardware.org/?probe=c01d51d1f5) | Apr 09, 2022 |
| Acer          | TravelMate 4670             | Notebook    | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| HP            | 1495                        | Desktop     | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Dell          | 0VD5HY A04                  | Desktop     | [8672ef6c18](https://linux-hardware.org/?probe=8672ef6c18) | Apr 07, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [0f8ce13fb9](https://linux-hardware.org/?probe=0f8ce13fb9) | Apr 06, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [046d0eb6c8](https://linux-hardware.org/?probe=046d0eb6c8) | Apr 05, 2022 |
| Acer          | Extensa 5630                | Notebook    | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [d95c37955a](https://linux-hardware.org/?probe=d95c37955a) | Apr 03, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | Notebook    | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Intel         | DG45ID AAE27729-310         | Desktop     | [4a15651672](https://linux-hardware.org/?probe=4a15651672) | Apr 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Dell          | OptiPlex 7010               | Desktop     | [f1167c797e](https://linux-hardware.org/?probe=f1167c797e) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | Notebook    | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [b951c3cc48](https://linux-hardware.org/?probe=b951c3cc48) | Mar 29, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | Notebook    | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | Notebook    | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| Le Cube 1     | Unknown                     | Desktop     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | Notebook    | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | Notebook    | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [4ee969ac04](https://linux-hardware.org/?probe=4ee969ac04) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3193e91c83](https://linux-hardware.org/?probe=3193e91c83) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a5d1f1ec32](https://linux-hardware.org/?probe=a5d1f1ec32) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | Notebook    | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| MSI           | B85M-G43                    | Desktop     | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| MSI           | B85M-E45 2015-08-19         | Desktop     | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9ba6eb4ae](https://linux-hardware.org/?probe=c9ba6eb4ae) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [038e9b79ef](https://linux-hardware.org/?probe=038e9b79ef) | Mar 08, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [ce5f22f97a](https://linux-hardware.org/?probe=ce5f22f97a) | Mar 08, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| Acer          | Extensa 5620                | Notebook    | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [047ff4ad80](https://linux-hardware.org/?probe=047ff4ad80) | Mar 04, 2022 |
| MSI           | B85M-G43                    | Desktop     | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Dell          | Latitude 7520               | Notebook    | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| HP            | 3031h                       | Desktop     | [52a519941d](https://linux-hardware.org/?probe=52a519941d) | Mar 03, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | Notebook    | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| Gigabyte      | G1.Sniper                   | Desktop     | [59b1ae56dd](https://linux-hardware.org/?probe=59b1ae56dd) | Mar 01, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 821D                        | Desktop     | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| ASUSTek       | P8Q67-M DO/TPM              | Desktop     | [ee784c0a7e](https://linux-hardware.org/?probe=ee784c0a7e) | Feb 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| ASRock        | Z370M Pro4                  | Desktop     | [8e08f3846b](https://linux-hardware.org/?probe=8e08f3846b) | Feb 27, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [b2e75d51bb](https://linux-hardware.org/?probe=b2e75d51bb) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [1a4f0d32ab](https://linux-hardware.org/?probe=1a4f0d32ab) | Feb 22, 2022 |
| Gigabyte      | G1.Sniper                   | Desktop     | [615669f693](https://linux-hardware.org/?probe=615669f693) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [de7189b0d4](https://linux-hardware.org/?probe=de7189b0d4) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| MSI           | Boston                      | Desktop     | [0f7a7dd744](https://linux-hardware.org/?probe=0f7a7dd744) | Feb 19, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Google        | Chell                       | Notebook    | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [51dfd147ef](https://linux-hardware.org/?probe=51dfd147ef) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | Notebook    | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [bec0b9ac1e](https://linux-hardware.org/?probe=bec0b9ac1e) | Feb 13, 2022 |
| Google        | Homestar (rev3)             | Soc         | [313894dec8](https://linux-hardware.org/?probe=313894dec8) | Feb 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b5dd380b9a](https://linux-hardware.org/?probe=b5dd380b9a) | Feb 10, 2022 |
| Dell          | Latitude 5480               | Notebook    | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| HP            | 18E7                        | Desktop     | [11c3f1c67f](https://linux-hardware.org/?probe=11c3f1c67f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Google        | Homestar (rev3)             | Soc         | [58d09ccbf3](https://linux-hardware.org/?probe=58d09ccbf3) | Feb 04, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4aece000f1](https://linux-hardware.org/?probe=4aece000f1) | Feb 03, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [4cf4045deb](https://linux-hardware.org/?probe=4cf4045deb) | Feb 01, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | Notebook    | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [182ad67187](https://linux-hardware.org/?probe=182ad67187) | Feb 01, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [6afebcc975](https://linux-hardware.org/?probe=6afebcc975) | Feb 01, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [8fba4698c9](https://linux-hardware.org/?probe=8fba4698c9) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | Notebook    | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | Notebook    | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [dcc55138d2](https://linux-hardware.org/?probe=dcc55138d2) | Jan 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | Notebook    | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0977601aad](https://linux-hardware.org/?probe=0977601aad) | Jan 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | Notebook    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | Notebook    | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | Notebook    | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [a920db9f29](https://linux-hardware.org/?probe=a920db9f29) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | Notebook    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | Notebook    | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | Notebook    | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | Notebook    | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | Notebook    | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | Notebook    | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [c0039193bb](https://linux-hardware.org/?probe=c0039193bb) | Jan 09, 2022 |
| HP            | 18E7                        | Desktop     | [2598720ae1](https://linux-hardware.org/?probe=2598720ae1) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b4f5f6f8da](https://linux-hardware.org/?probe=b4f5f6f8da) | Jan 08, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | Notebook    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | Notebook    | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | Desktop     | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5107953369](https://linux-hardware.org/?probe=5107953369) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | Notebook    | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | Notebook    | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | Notebook    | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [c5c108c138](https://linux-hardware.org/?probe=c5c108c138) | Jan 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | Notebook    | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [5d1e83c959](https://linux-hardware.org/?probe=5d1e83c959) | Jan 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| HP            | 18E7                        | Desktop     | [8fe0391d59](https://linux-hardware.org/?probe=8fe0391d59) | Dec 28, 2021 |
| HP            | ProLiant DL380e Gen8        | Server      | [a28b637049](https://linux-hardware.org/?probe=a28b637049) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | Notebook    | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| HP            | 872E                        | Mini pc     | [84eb03ce6d](https://linux-hardware.org/?probe=84eb03ce6d) | Dec 25, 2021 |
| HP            | 872E                        | Mini pc     | [c2eff247c6](https://linux-hardware.org/?probe=c2eff247c6) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| HP            | 1905                        | Desktop     | [9e2637fa00](https://linux-hardware.org/?probe=9e2637fa00) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [180954acf2](https://linux-hardware.org/?probe=180954acf2) | Dec 23, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| Dell          | Latitude 5400               | Notebook    | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| UMAX          | VisionBook 10Wi-S 64G       | Tablet      | [5143e2a3fe](https://linux-hardware.org/?probe=5143e2a3fe) | Dec 18, 2021 |
| Dell          | 0478VN A00                  | Desktop     | [67955910cb](https://linux-hardware.org/?probe=67955910cb) | Dec 18, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | Notebook    | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | Notebook    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [86aff395eb](https://linux-hardware.org/?probe=86aff395eb) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6b3727344c](https://linux-hardware.org/?probe=6b3727344c) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | Notebook    | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [efb6380716](https://linux-hardware.org/?probe=efb6380716) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | Notebook    | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| Acer          | Extensa 5220                | Notebook    | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | Notebook    | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [e96b1f7f6b](https://linux-hardware.org/?probe=e96b1f7f6b) | Dec 07, 2021 |
| Dell          | 0PTTT9 A01                  | Desktop     | [fb7c5092e9](https://linux-hardware.org/?probe=fb7c5092e9) | Dec 07, 2021 |
| HP            | 1905                        | Desktop     | [e16a65e786](https://linux-hardware.org/?probe=e16a65e786) | Dec 06, 2021 |
| HP            | 1905                        | Desktop     | [d58c2f29a4](https://linux-hardware.org/?probe=d58c2f29a4) | Dec 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [63319937d0](https://linux-hardware.org/?probe=63319937d0) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | Notebook    | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | Notebook    | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [24800d20ac](https://linux-hardware.org/?probe=24800d20ac) | Dec 01, 2021 |
| Google        | Akemi                       | Notebook    | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | Notebook    | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | Notebook    | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | Notebook    | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | Notebook    | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| EVGA          | 142-SS-E178                 | Desktop     | [8ad978bbf2](https://linux-hardware.org/?probe=8ad978bbf2) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | Desktop     | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d6e422cfc](https://linux-hardware.org/?probe=6d6e422cfc) | Nov 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [021a54d6d2](https://linux-hardware.org/?probe=021a54d6d2) | Nov 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [5edbaed472](https://linux-hardware.org/?probe=5edbaed472) | Nov 18, 2021 |
| Supermicro    | X10SLL-F                    | Server      | [f9e64483fd](https://linux-hardware.org/?probe=f9e64483fd) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | Notebook    | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [19a21ae965](https://linux-hardware.org/?probe=19a21ae965) | Nov 17, 2021 |
| Biostar       | TH67B                       | Desktop     | [5d655fd2bd](https://linux-hardware.org/?probe=5d655fd2bd) | Nov 17, 2021 |
| HP            | ProBook 4510s               | Notebook    | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| MSI           | A88X-G43                    | Desktop     | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | Desktop     | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| ASUSTek       | P5KPL                       | Desktop     | [6e52b269ee](https://linux-hardware.org/?probe=6e52b269ee) | Nov 15, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [89c5a1af70](https://linux-hardware.org/?probe=89c5a1af70) | Nov 15, 2021 |
| Dell          | Latitude E6420              | Notebook    | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6bc1b40b7](https://linux-hardware.org/?probe=b6bc1b40b7) | Nov 14, 2021 |
| Seeed Stud... | ODYSSEY-TGL-A               | Desktop     | [b05c5533b0](https://linux-hardware.org/?probe=b05c5533b0) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| HP            | 1998                        | Desktop     | [2e830badd5](https://linux-hardware.org/?probe=2e830badd5) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| MSI           | 970A-G43                    | Desktop     | [da61ca8b52](https://linux-hardware.org/?probe=da61ca8b52) | Nov 13, 2021 |
| MSI           | 970A-G43                    | Desktop     | [d27f131cce](https://linux-hardware.org/?probe=d27f131cce) | Nov 13, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [59ca43cb01](https://linux-hardware.org/?probe=59ca43cb01) | Nov 12, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [0f4ebd720e](https://linux-hardware.org/?probe=0f4ebd720e) | Nov 11, 2021 |
| Dell          | Latitude E5440              | Notebook    | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | Notebook    | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [2af76d7459](https://linux-hardware.org/?probe=2af76d7459) | Nov 09, 2021 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [ecf35bff43](https://linux-hardware.org/?probe=ecf35bff43) | Nov 09, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| HP            | 1998                        | Desktop     | [c2ab98c42f](https://linux-hardware.org/?probe=c2ab98c42f) | Nov 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [68d7274a99](https://linux-hardware.org/?probe=68d7274a99) | Nov 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [12800ce664](https://linux-hardware.org/?probe=12800ce664) | Nov 06, 2021 |
| HP            | Pavilion dv6                | Notebook    | [9b00744856](https://linux-hardware.org/?probe=9b00744856) | Nov 06, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [1ae65e25ca](https://linux-hardware.org/?probe=1ae65e25ca) | Nov 06, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [3cea241e9d](https://linux-hardware.org/?probe=3cea241e9d) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | Notebook    | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [510bf1ba13](https://linux-hardware.org/?probe=510bf1ba13) | Nov 03, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [7295833004](https://linux-hardware.org/?probe=7295833004) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| MSI           | GE76 Raider 11UG            | Notebook    | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Purism        | librem_15v4                 | Notebook    | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | Notebook    | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [7a2e7c66e9](https://linux-hardware.org/?probe=7a2e7c66e9) | Oct 31, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eadbbabab0](https://linux-hardware.org/?probe=eadbbabab0) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| Dell          | Latitude E7240              | Notebook    | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | Notebook    | [3678e02e46](https://linux-hardware.org/?probe=3678e02e46) | Oct 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | Notebook    | [5a44640ff8](https://linux-hardware.org/?probe=5a44640ff8) | Oct 27, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Sony          | VPCZ13M9E                   | Notebook    | [2d1739dc58](https://linux-hardware.org/?probe=2d1739dc58) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Alienware     | 15                          | Notebook    | [5a84b0e8e8](https://linux-hardware.org/?probe=5a84b0e8e8) | Oct 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Acer          | Aspire E5-721               | Notebook    | [0b2ec748f2](https://linux-hardware.org/?probe=0b2ec748f2) | Oct 23, 2021 |
| Acer          | Aspire E5-721               | Notebook    | [46ae1c3c30](https://linux-hardware.org/?probe=46ae1c3c30) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | Notebook    | [d727cf6e00](https://linux-hardware.org/?probe=d727cf6e00) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | Notebook    | [6ccc652e28](https://linux-hardware.org/?probe=6ccc652e28) | Oct 22, 2021 |
| Alienware     | 15                          | Notebook    | [8c4eaaa333](https://linux-hardware.org/?probe=8c4eaaa333) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Dell          | Latitude 5400               | Notebook    | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | Notebook    | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f60949a3cc](https://linux-hardware.org/?probe=f60949a3cc) | Oct 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9f21330313](https://linux-hardware.org/?probe=9f21330313) | Oct 18, 2021 |
| Sony          | VPCEB1E1E                   | Notebook    | [1473b3d2ca](https://linux-hardware.org/?probe=1473b3d2ca) | Oct 18, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Dell          | Latitude E5420              | Notebook    | [a1027f938f](https://linux-hardware.org/?probe=a1027f938f) | Oct 16, 2021 |
| Medion        | E7218                       | Notebook    | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d890edb314](https://linux-hardware.org/?probe=d890edb314) | Oct 16, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [ae854c2ff2](https://linux-hardware.org/?probe=ae854c2ff2) | Oct 16, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| MSI           | MS-7309                     | Desktop     | [33faf5dbef](https://linux-hardware.org/?probe=33faf5dbef) | Oct 14, 2021 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [878347dd71](https://linux-hardware.org/?probe=878347dd71) | Oct 13, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [2269836aab](https://linux-hardware.org/?probe=2269836aab) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| MSI           | MS-7309                     | Desktop     | [b0ddfaaa86](https://linux-hardware.org/?probe=b0ddfaaa86) | Oct 12, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [928665d302](https://linux-hardware.org/?probe=928665d302) | Oct 12, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [b624e54271](https://linux-hardware.org/?probe=b624e54271) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Lenovo        | ThinkPad T570 20H90000MC    | Notebook    | [51c709d90c](https://linux-hardware.org/?probe=51c709d90c) | Oct 09, 2021 |
| UMAX          | J42 Nano                    | Desktop     | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5174e188c0](https://linux-hardware.org/?probe=5174e188c0) | Oct 09, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [81c36c3a21](https://linux-hardware.org/?probe=81c36c3a21) | Oct 09, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b3a9a2c025](https://linux-hardware.org/?probe=b3a9a2c025) | Oct 08, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [13444fc399](https://linux-hardware.org/?probe=13444fc399) | Oct 08, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [7034e6708d](https://linux-hardware.org/?probe=7034e6708d) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | Notebook    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3cab016500](https://linux-hardware.org/?probe=3cab016500) | Oct 06, 2021 |
| ASUSTek       | ET2010AG                    | All in one  | [86cd4a72d1](https://linux-hardware.org/?probe=86cd4a72d1) | Oct 05, 2021 |
| ASUSTek       | ET2010AG                    | All in one  | [a96edf35cd](https://linux-hardware.org/?probe=a96edf35cd) | Oct 05, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [2615e61a63](https://linux-hardware.org/?probe=2615e61a63) | Oct 05, 2021 |
| Acer          | Aspire M1930                | Desktop     | [0f21c5864a](https://linux-hardware.org/?probe=0f21c5864a) | Oct 05, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [f6518ea548](https://linux-hardware.org/?probe=f6518ea548) | Oct 04, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [43115b1585](https://linux-hardware.org/?probe=43115b1585) | Oct 04, 2021 |
| HP            | 3047h                       | Desktop     | [15f4144ba7](https://linux-hardware.org/?probe=15f4144ba7) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [38422d16b5](https://linux-hardware.org/?probe=38422d16b5) | Oct 02, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [21453a290c](https://linux-hardware.org/?probe=21453a290c) | Oct 02, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [26fb963760](https://linux-hardware.org/?probe=26fb963760) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [7f17ddd3af](https://linux-hardware.org/?probe=7f17ddd3af) | Sep 30, 2021 |
| Acer          | Extensa 5235                | Notebook    | [aadc334520](https://linux-hardware.org/?probe=aadc334520) | Sep 29, 2021 |
| MSI           | GL72 6QD                    | Notebook    | [4a25280ba6](https://linux-hardware.org/?probe=4a25280ba6) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [7e82dd3e6d](https://linux-hardware.org/?probe=7e82dd3e6d) | Sep 25, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [f64736711c](https://linux-hardware.org/?probe=f64736711c) | Sep 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [b39008d274](https://linux-hardware.org/?probe=b39008d274) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [0f57a946c9](https://linux-hardware.org/?probe=0f57a946c9) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [5422161d82](https://linux-hardware.org/?probe=5422161d82) | Sep 21, 2021 |
| Lenovo        | C200 10040                  | All in one  | [0c9232361d](https://linux-hardware.org/?probe=0c9232361d) | Sep 21, 2021 |
| HP            | 255 G4                      | Notebook    | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| Toshiba       | Satellite C850-19P          | Notebook    | [be0e0fc39c](https://linux-hardware.org/?probe=be0e0fc39c) | Sep 19, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [4dae78bc6e](https://linux-hardware.org/?probe=4dae78bc6e) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Lenovo        | B51-80 80LM                 | Notebook    | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [507fbfc464](https://linux-hardware.org/?probe=507fbfc464) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [8bd0f5b675](https://linux-hardware.org/?probe=8bd0f5b675) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [e044b5770b](https://linux-hardware.org/?probe=e044b5770b) | Sep 15, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [61c16353ce](https://linux-hardware.org/?probe=61c16353ce) | Sep 14, 2021 |
| Intel         | S2600WFT H48104-850         | Server      | [36c4acac2d](https://linux-hardware.org/?probe=36c4acac2d) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [49a26a21af](https://linux-hardware.org/?probe=49a26a21af) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | UX303LA                     | Notebook    | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [5ef10e99fc](https://linux-hardware.org/?probe=5ef10e99fc) | Sep 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d069d8c301](https://linux-hardware.org/?probe=d069d8c301) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [4078ccd6f6](https://linux-hardware.org/?probe=4078ccd6f6) | Sep 08, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [fb3c4b683c](https://linux-hardware.org/?probe=fb3c4b683c) | Sep 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [75e4394ca1](https://linux-hardware.org/?probe=75e4394ca1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [7d28c4a737](https://linux-hardware.org/?probe=7d28c4a737) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [c33f77f320](https://linux-hardware.org/?probe=c33f77f320) | Sep 07, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [9e43cd58cd](https://linux-hardware.org/?probe=9e43cd58cd) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6db0aec69b](https://linux-hardware.org/?probe=6db0aec69b) | Sep 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [eb43b257f2](https://linux-hardware.org/?probe=eb43b257f2) | Sep 05, 2021 |
| Acer          | Spin SP111-33               | Convertible | [2a5ddf7be8](https://linux-hardware.org/?probe=2a5ddf7be8) | Sep 05, 2021 |
| ASUSTek       | P5KPL                       | Desktop     | [5abf2f2b22](https://linux-hardware.org/?probe=5abf2f2b22) | Sep 05, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d0d9c89285](https://linux-hardware.org/?probe=d0d9c89285) | Sep 04, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e9741b1baf](https://linux-hardware.org/?probe=e9741b1baf) | Sep 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [c31af0c00d](https://linux-hardware.org/?probe=c31af0c00d) | Sep 02, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7f23204904](https://linux-hardware.org/?probe=7f23204904) | Sep 02, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| MSI           | GP72MVR 7RFX                | Notebook    | [8bf96cd534](https://linux-hardware.org/?probe=8bf96cd534) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [9ac57ec075](https://linux-hardware.org/?probe=9ac57ec075) | Aug 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [47c81ea7a3](https://linux-hardware.org/?probe=47c81ea7a3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d744798f8c](https://linux-hardware.org/?probe=d744798f8c) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| HP            | Pavilion dv7                | Notebook    | [89e7202467](https://linux-hardware.org/?probe=89e7202467) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [2a6bfff91f](https://linux-hardware.org/?probe=2a6bfff91f) | Aug 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Supermicro    | X10DRi                      | Server      | [c04f902b93](https://linux-hardware.org/?probe=c04f902b93) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7e6371d41f](https://linux-hardware.org/?probe=7e6371d41f) | Aug 22, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a253cd3e21](https://linux-hardware.org/?probe=a253cd3e21) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Dell          | Latitude 7320               | Notebook    | [33536a85d3](https://linux-hardware.org/?probe=33536a85d3) | Aug 19, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [7306b98101](https://linux-hardware.org/?probe=7306b98101) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| Lenovo        | 3176 NOK                    | Desktop     | [ed11430a97](https://linux-hardware.org/?probe=ed11430a97) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |
| ASRock        | B460M-ITX/ac                | Desktop     | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Dell          | 02YYK5 A00                  | Desktop     | [2918bafc50](https://linux-hardware.org/?probe=2918bafc50) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [7b007be9fd](https://linux-hardware.org/?probe=7b007be9fd) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f9243be85f](https://linux-hardware.org/?probe=f9243be85f) | Aug 16, 2021 |
| Acer          | Extensa 5630                | Notebook    | [29a71214dd](https://linux-hardware.org/?probe=29a71214dd) | Aug 15, 2021 |
| AMI           | Intel                       | Convertible | [c96146f531](https://linux-hardware.org/?probe=c96146f531) | Aug 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [465b8fec82](https://linux-hardware.org/?probe=465b8fec82) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [80cfc9b687](https://linux-hardware.org/?probe=80cfc9b687) | Aug 12, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [5e65f099db](https://linux-hardware.org/?probe=5e65f099db) | Aug 12, 2021 |
| Acer          | Extensa 5630                | Notebook    | [43a2f7646a](https://linux-hardware.org/?probe=43a2f7646a) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASUSTek       | X553SA                      | Notebook    | [58875de3c3](https://linux-hardware.org/?probe=58875de3c3) | Aug 12, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4651e027d9](https://linux-hardware.org/?probe=4651e027d9) | Aug 11, 2021 |
| Dell          | Latitude 5400               | Notebook    | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [28897c5b5f](https://linux-hardware.org/?probe=28897c5b5f) | Aug 09, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a52650a605](https://linux-hardware.org/?probe=a52650a605) | Aug 09, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [17e8358196](https://linux-hardware.org/?probe=17e8358196) | Aug 08, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [5c64722433](https://linux-hardware.org/?probe=5c64722433) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [88c691e7f1](https://linux-hardware.org/?probe=88c691e7f1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [32c82c54b5](https://linux-hardware.org/?probe=32c82c54b5) | Aug 06, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [983611f01f](https://linux-hardware.org/?probe=983611f01f) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [5e399cedc5](https://linux-hardware.org/?probe=5e399cedc5) | Aug 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [1e458b84be](https://linux-hardware.org/?probe=1e458b84be) | Aug 04, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [8951f246ed](https://linux-hardware.org/?probe=8951f246ed) | Aug 04, 2021 |
| ASUSTek       | G55VW                       | Notebook    | [9e7dc8e8cf](https://linux-hardware.org/?probe=9e7dc8e8cf) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [ffee1e0026](https://linux-hardware.org/?probe=ffee1e0026) | Aug 03, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [f557538404](https://linux-hardware.org/?probe=f557538404) | Aug 03, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [54a72c496f](https://linux-hardware.org/?probe=54a72c496f) | Aug 03, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [752c8e7000](https://linux-hardware.org/?probe=752c8e7000) | Aug 03, 2021 |
| Acer          | Swift SF514-54GT            | Notebook    | [bbe1d82ec7](https://linux-hardware.org/?probe=bbe1d82ec7) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [1d638fd7ae](https://linux-hardware.org/?probe=1d638fd7ae) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [44b0620279](https://linux-hardware.org/?probe=44b0620279) | Jul 29, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [617fd327a3](https://linux-hardware.org/?probe=617fd327a3) | Jul 28, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b90f06f2eb](https://linux-hardware.org/?probe=b90f06f2eb) | Jul 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d27d622754](https://linux-hardware.org/?probe=d27d622754) | Jul 27, 2021 |
| ASUSTek       | X556UQ                      | Notebook    | [9dee8d2c07](https://linux-hardware.org/?probe=9dee8d2c07) | Jul 27, 2021 |
| ASUSTek       | X556UQ                      | Notebook    | [88b38f3c6b](https://linux-hardware.org/?probe=88b38f3c6b) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [1ac5feaf25](https://linux-hardware.org/?probe=1ac5feaf25) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [3ca5d000c3](https://linux-hardware.org/?probe=3ca5d000c3) | Jul 26, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 429137G       | Notebook    | [ab41516068](https://linux-hardware.org/?probe=ab41516068) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [e3aca6b408](https://linux-hardware.org/?probe=e3aca6b408) | Jul 24, 2021 |
| Acer          | Swift SF514-55GT            | Notebook    | [bb95e7c75b](https://linux-hardware.org/?probe=bb95e7c75b) | Jul 24, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [44103309b6](https://linux-hardware.org/?probe=44103309b6) | Jul 24, 2021 |
| Lenovo        | ThinkPad E495 20NE000BMC    | Notebook    | [487f5a67bf](https://linux-hardware.org/?probe=487f5a67bf) | Jul 24, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [54f44d70c5](https://linux-hardware.org/?probe=54f44d70c5) | Jul 24, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [72cbbe92a0](https://linux-hardware.org/?probe=72cbbe92a0) | Jul 22, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [62a0cf7f70](https://linux-hardware.org/?probe=62a0cf7f70) | Jul 21, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [d0a8afe992](https://linux-hardware.org/?probe=d0a8afe992) | Jul 20, 2021 |
| Sony          | VPCEB1E1E                   | Notebook    | [b57d8d169b](https://linux-hardware.org/?probe=b57d8d169b) | Jul 20, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [214c59a169](https://linux-hardware.org/?probe=214c59a169) | Jul 19, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3b293f18b7](https://linux-hardware.org/?probe=3b293f18b7) | Jul 18, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [db3e0c8073](https://linux-hardware.org/?probe=db3e0c8073) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [594fbbbb38](https://linux-hardware.org/?probe=594fbbbb38) | Jul 17, 2021 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [c6fa7a1e42](https://linux-hardware.org/?probe=c6fa7a1e42) | Jul 16, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [d67f028892](https://linux-hardware.org/?probe=d67f028892) | Jul 15, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [1697c7eaf6](https://linux-hardware.org/?probe=1697c7eaf6) | Jul 15, 2021 |
| HP            | 3047h                       | Desktop     | [9e162f2640](https://linux-hardware.org/?probe=9e162f2640) | Jul 15, 2021 |
| Lenovo        | 0769BLG                     | Notebook    | [2d8e74d05c](https://linux-hardware.org/?probe=2d8e74d05c) | Jul 15, 2021 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [8834700cd9](https://linux-hardware.org/?probe=8834700cd9) | Jul 14, 2021 |
| HP            | 872E                        | Mini pc     | [dfca28cc5f](https://linux-hardware.org/?probe=dfca28cc5f) | Jul 14, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | Notebook    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| ASUSTek       | EX-B250-V7                  | Desktop     | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| HP            | Compaq 6730b (GB988EA)      | Notebook    | [ca4426ce30](https://linux-hardware.org/?probe=ca4426ce30) | Jul 11, 2021 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [ac44464839](https://linux-hardware.org/?probe=ac44464839) | Jul 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [eb84cf8198](https://linux-hardware.org/?probe=eb84cf8198) | Jul 10, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | Notebook    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [e661874cb2](https://linux-hardware.org/?probe=e661874cb2) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a88a1df2f5](https://linux-hardware.org/?probe=a88a1df2f5) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [77f6869d84](https://linux-hardware.org/?probe=77f6869d84) | Jul 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [dcad6f0184](https://linux-hardware.org/?probe=dcad6f0184) | Jul 06, 2021 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [43afdddf0e](https://linux-hardware.org/?probe=43afdddf0e) | Jul 04, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [27b614c70e](https://linux-hardware.org/?probe=27b614c70e) | Jul 04, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [f751fa4ae6](https://linux-hardware.org/?probe=f751fa4ae6) | Jul 04, 2021 |
| HP            | 805B                        | Desktop     | [5d5a6504aa](https://linux-hardware.org/?probe=5d5a6504aa) | Jul 03, 2021 |
| HP            | ProBook 4720s               | Notebook    | [2112bd8af0](https://linux-hardware.org/?probe=2112bd8af0) | Jul 03, 2021 |
| HP            | 805B                        | Desktop     | [83f501a4c5](https://linux-hardware.org/?probe=83f501a4c5) | Jul 03, 2021 |
| HP            | ProBook 4720s               | Notebook    | [f6be4a39bb](https://linux-hardware.org/?probe=f6be4a39bb) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [48a36ae4a4](https://linux-hardware.org/?probe=48a36ae4a4) | Jul 03, 2021 |
| Dell          | Latitude E6400              | Notebook    | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [6e5f031c7a](https://linux-hardware.org/?probe=6e5f031c7a) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| Dell          | Latitude E6430              | Notebook    | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Acer          | E1-510                      | Notebook    | [74ed9018a7](https://linux-hardware.org/?probe=74ed9018a7) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [c19ad895a0](https://linux-hardware.org/?probe=c19ad895a0) | Jul 02, 2021 |
| Acer          | E1-510                      | Notebook    | [1f5fc816d2](https://linux-hardware.org/?probe=1f5fc816d2) | Jul 02, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [0260c559c1](https://linux-hardware.org/?probe=0260c559c1) | Jul 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [ee813e9b02](https://linux-hardware.org/?probe=ee813e9b02) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d26e9b673d](https://linux-hardware.org/?probe=d26e9b673d) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4327921246](https://linux-hardware.org/?probe=4327921246) | Jun 30, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [858ab16aee](https://linux-hardware.org/?probe=858ab16aee) | Jun 29, 2021 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [ca207b7cd3](https://linux-hardware.org/?probe=ca207b7cd3) | Jun 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1894c1b871](https://linux-hardware.org/?probe=1894c1b871) | Jun 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7c24f1f698](https://linux-hardware.org/?probe=7c24f1f698) | Jun 27, 2021 |
| HP            | 2B28                        | Desktop     | [9f9e5ad8f7](https://linux-hardware.org/?probe=9f9e5ad8f7) | Jun 27, 2021 |
| HP            | 2B28                        | Desktop     | [7eb7cb002a](https://linux-hardware.org/?probe=7eb7cb002a) | Jun 27, 2021 |
| Lenovo        | 3176 NOK                    | Desktop     | [9dad112b64](https://linux-hardware.org/?probe=9dad112b64) | Jun 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [4d4040c7bd](https://linux-hardware.org/?probe=4d4040c7bd) | Jun 27, 2021 |
| HP            | 3647h                       | Desktop     | [838bf8880c](https://linux-hardware.org/?probe=838bf8880c) | Jun 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [e6e76d81ec](https://linux-hardware.org/?probe=e6e76d81ec) | Jun 19, 2021 |
| ASUSTek       | H170-PRO                    | Desktop     | [27b4b0831d](https://linux-hardware.org/?probe=27b4b0831d) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cf48431ab4](https://linux-hardware.org/?probe=cf48431ab4) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [0db05d1420](https://linux-hardware.org/?probe=0db05d1420) | Jun 18, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [8c980bf3ca](https://linux-hardware.org/?probe=8c980bf3ca) | Jun 17, 2021 |
| Gigabyte      | M61PME-S2                   | Desktop     | [528c4990aa](https://linux-hardware.org/?probe=528c4990aa) | Jun 16, 2021 |
| MSI           | B250I PRO                   | Desktop     | [02087ebc8a](https://linux-hardware.org/?probe=02087ebc8a) | Jun 15, 2021 |
| MSI           | B250I PRO                   | Desktop     | [05b0b94ace](https://linux-hardware.org/?probe=05b0b94ace) | Jun 15, 2021 |
| Acer          | Aspire XC-603               | Desktop     | [b8e13ff999](https://linux-hardware.org/?probe=b8e13ff999) | Jun 15, 2021 |
| HP            | 2B28                        | Desktop     | [67c946572f](https://linux-hardware.org/?probe=67c946572f) | Jun 15, 2021 |
| HP            | 2B28                        | Desktop     | [49bcd8e078](https://linux-hardware.org/?probe=49bcd8e078) | Jun 15, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [ed5ee6c4fd](https://linux-hardware.org/?probe=ed5ee6c4fd) | Jun 14, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| HP            | Pavilion dv5                | Notebook    | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| Dell          | Latitude E5510              | Notebook    | [648d4a58e1](https://linux-hardware.org/?probe=648d4a58e1) | Jun 06, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [6466886164](https://linux-hardware.org/?probe=6466886164) | Jun 06, 2021 |
| ASUSTek       | X55U                        | Notebook    | [4a44c680de](https://linux-hardware.org/?probe=4a44c680de) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ca0eb881c4](https://linux-hardware.org/?probe=ca0eb881c4) | Jun 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f0057c8374](https://linux-hardware.org/?probe=f0057c8374) | Jun 03, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1bbb6d6e34](https://linux-hardware.org/?probe=1bbb6d6e34) | Jun 03, 2021 |
| ASRock        | H410M-ITX/ac                | Desktop     | [1f2d258849](https://linux-hardware.org/?probe=1f2d258849) | Jun 02, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [e50e7e65b4](https://linux-hardware.org/?probe=e50e7e65b4) | May 28, 2021 |
| Insyde        | Braswell                    | Notebook    | [cedca78b3a](https://linux-hardware.org/?probe=cedca78b3a) | May 28, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [fc1870a101](https://linux-hardware.org/?probe=fc1870a101) | May 28, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [75f763a124](https://linux-hardware.org/?probe=75f763a124) | May 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [91d0ba53c9](https://linux-hardware.org/?probe=91d0ba53c9) | May 28, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [91eacced05](https://linux-hardware.org/?probe=91eacced05) | May 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cfb66b647f](https://linux-hardware.org/?probe=cfb66b647f) | May 27, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [a8fd68fccc](https://linux-hardware.org/?probe=a8fd68fccc) | May 26, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [8222525f6a](https://linux-hardware.org/?probe=8222525f6a) | May 26, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [947c13ccd9](https://linux-hardware.org/?probe=947c13ccd9) | May 24, 2021 |
| Dell          | G5 5587                     | Notebook    | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [fd98fd839e](https://linux-hardware.org/?probe=fd98fd839e) | May 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [38380cec21](https://linux-hardware.org/?probe=38380cec21) | May 22, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [a51030d9a0](https://linux-hardware.org/?probe=a51030d9a0) | May 22, 2021 |
| Dell          | Latitude 5511               | Notebook    | [6fdc31e1e9](https://linux-hardware.org/?probe=6fdc31e1e9) | May 21, 2021 |
| MSI           | GE72 7RE                    | Notebook    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| HP            | 0B54h D                     | Desktop     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |
| ASUSTek       | P8H61-M                     | Desktop     | [5d5163972e](https://linux-hardware.org/?probe=5d5163972e) | May 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| ASUSTek       | P5N-D                       | Desktop     | [3965d087b0](https://linux-hardware.org/?probe=3965d087b0) | May 17, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [cbde33b709](https://linux-hardware.org/?probe=cbde33b709) | May 16, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [da913ed8d3](https://linux-hardware.org/?probe=da913ed8d3) | May 16, 2021 |
| MSI           | G41M-P25                    | Desktop     | [57d1c4dafa](https://linux-hardware.org/?probe=57d1c4dafa) | May 16, 2021 |
| HP            | ProBook 4520s (WT121EA)     | Notebook    | [af5a9f1662](https://linux-hardware.org/?probe=af5a9f1662) | May 15, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [faeed14705](https://linux-hardware.org/?probe=faeed14705) | May 15, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [5a9153e5cc](https://linux-hardware.org/?probe=5a9153e5cc) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| HP            | 1850                        | Desktop     | [c904ea417d](https://linux-hardware.org/?probe=c904ea417d) | May 13, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [8d22fdb15f](https://linux-hardware.org/?probe=8d22fdb15f) | May 12, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [33069aaebb](https://linux-hardware.org/?probe=33069aaebb) | May 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [e6eed05cc3](https://linux-hardware.org/?probe=e6eed05cc3) | May 12, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [6a58a91c19](https://linux-hardware.org/?probe=6a58a91c19) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Acer          | Aspire VN7-591G             | Notebook    | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [fdac79e308](https://linux-hardware.org/?probe=fdac79e308) | May 10, 2021 |
| Acer          | Aspire 5740                 | Notebook    | [ed5c778d4f](https://linux-hardware.org/?probe=ed5c778d4f) | May 09, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [ee32f4a115](https://linux-hardware.org/?probe=ee32f4a115) | May 07, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [3ad4ad9793](https://linux-hardware.org/?probe=3ad4ad9793) | May 07, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [ec56f6327d](https://linux-hardware.org/?probe=ec56f6327d) | May 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ffaf24e2ab](https://linux-hardware.org/?probe=ffaf24e2ab) | May 06, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3fdf6b4559](https://linux-hardware.org/?probe=3fdf6b4559) | May 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [86a8e25430](https://linux-hardware.org/?probe=86a8e25430) | May 04, 2021 |
| Lenovo        | B70-80 80MR                 | Notebook    | [17bea3da43](https://linux-hardware.org/?probe=17bea3da43) | May 04, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4acf6ce595](https://linux-hardware.org/?probe=4acf6ce595) | May 04, 2021 |
| Intel         | S3210SH FRU Ver             | Server      | [591107ec98](https://linux-hardware.org/?probe=591107ec98) | May 04, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f416ff0dc2](https://linux-hardware.org/?probe=f416ff0dc2) | May 04, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [0b347a19e2](https://linux-hardware.org/?probe=0b347a19e2) | May 02, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [9f2372a38c](https://linux-hardware.org/?probe=9f2372a38c) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [36cd5135b6](https://linux-hardware.org/?probe=36cd5135b6) | May 02, 2021 |
| Sony          | VGN-FW31J                   | Notebook    | [87da15d562](https://linux-hardware.org/?probe=87da15d562) | May 01, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| Unknown       | Unknown                     | Phone       | [b610d5eb39](https://linux-hardware.org/?probe=b610d5eb39) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| Dell          | Latitude 5401               | Notebook    | [cd8363b187](https://linux-hardware.org/?probe=cd8363b187) | Apr 27, 2021 |
| Lenovo        | ThinkPad T430 23501F9       | Notebook    | [d855b9bf0f](https://linux-hardware.org/?probe=d855b9bf0f) | Apr 26, 2021 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [4f7a626b9b](https://linux-hardware.org/?probe=4f7a626b9b) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a5d42684da](https://linux-hardware.org/?probe=a5d42684da) | Apr 25, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [31d974ab0d](https://linux-hardware.org/?probe=31d974ab0d) | Apr 24, 2021 |
| Acer          | TravelMate 6460             | Notebook    | [287952fb68](https://linux-hardware.org/?probe=287952fb68) | Apr 24, 2021 |
| Dell          | 0H19HD A06                  | Server      | [1a05144c7e](https://linux-hardware.org/?probe=1a05144c7e) | Apr 23, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a9626f1580](https://linux-hardware.org/?probe=a9626f1580) | Apr 23, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [c51e03b281](https://linux-hardware.org/?probe=c51e03b281) | Apr 23, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [0f9a641322](https://linux-hardware.org/?probe=0f9a641322) | Apr 22, 2021 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [d8e49fec64](https://linux-hardware.org/?probe=d8e49fec64) | Apr 22, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [edd61e3d95](https://linux-hardware.org/?probe=edd61e3d95) | Apr 22, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [4198628d9f](https://linux-hardware.org/?probe=4198628d9f) | Apr 22, 2021 |
| Lenovo        | ThinkPad R500 2714AAG       | Notebook    | [0f62cca304](https://linux-hardware.org/?probe=0f62cca304) | Apr 20, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6b7033f43d](https://linux-hardware.org/?probe=6b7033f43d) | Apr 20, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b5e763d4f7](https://linux-hardware.org/?probe=b5e763d4f7) | Apr 20, 2021 |
| ASUSTek       | F5SL                        | Notebook    | [e1a84e3bdf](https://linux-hardware.org/?probe=e1a84e3bdf) | Apr 17, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [45189929cc](https://linux-hardware.org/?probe=45189929cc) | Apr 17, 2021 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [105bd71875](https://linux-hardware.org/?probe=105bd71875) | Apr 16, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [6c871ab8be](https://linux-hardware.org/?probe=6c871ab8be) | Apr 16, 2021 |
| Lenovo        | Dory CRB                    | Desktop     | [676ace5d71](https://linux-hardware.org/?probe=676ace5d71) | Apr 15, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [4cc6403330](https://linux-hardware.org/?probe=4cc6403330) | Apr 15, 2021 |
| ASUSTek       | N73JQ                       | Notebook    | [29398a5494](https://linux-hardware.org/?probe=29398a5494) | Apr 15, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [26b69278f1](https://linux-hardware.org/?probe=26b69278f1) | Apr 14, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [1dd1d4d667](https://linux-hardware.org/?probe=1dd1d4d667) | Apr 14, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [c294906b60](https://linux-hardware.org/?probe=c294906b60) | Apr 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [0a501933e1](https://linux-hardware.org/?probe=0a501933e1) | Apr 13, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [efb35be24f](https://linux-hardware.org/?probe=efb35be24f) | Apr 13, 2021 |
| Intel         | D525MW AAE93082-401         | Desktop     | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d46010346c](https://linux-hardware.org/?probe=d46010346c) | Apr 12, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [538618720c](https://linux-hardware.org/?probe=538618720c) | Apr 11, 2021 |
| HP            | ProBook 4530s               | Notebook    | [6b62bad9ad](https://linux-hardware.org/?probe=6b62bad9ad) | Apr 11, 2021 |
| HP            | Notebook                    | Notebook    | [b50b4aa14f](https://linux-hardware.org/?probe=b50b4aa14f) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [22901fcbc7](https://linux-hardware.org/?probe=22901fcbc7) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [71a5cf1e09](https://linux-hardware.org/?probe=71a5cf1e09) | Apr 11, 2021 |
| Fujitsu       | LIFEBOOK E5510              | Notebook    | [034e192416](https://linux-hardware.org/?probe=034e192416) | Apr 11, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [cc2dcd8258](https://linux-hardware.org/?probe=cc2dcd8258) | Apr 10, 2021 |
| Sony          | VPCEB1E1E                   | Notebook    | [d73e70bc03](https://linux-hardware.org/?probe=d73e70bc03) | Apr 10, 2021 |
| Toshiba       | Unknown                     | Notebook    | [0c98d143f2](https://linux-hardware.org/?probe=0c98d143f2) | Apr 09, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [f41c784317](https://linux-hardware.org/?probe=f41c784317) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | Notebook    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Dell          | 0GWHMW A03                  | Desktop     | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [a1481ccf2a](https://linux-hardware.org/?probe=a1481ccf2a) | Apr 07, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [e293d1c2a3](https://linux-hardware.org/?probe=e293d1c2a3) | Apr 07, 2021 |
| Dell          | Inspiron 7348               | Notebook    | [bd1d84d6e7](https://linux-hardware.org/?probe=bd1d84d6e7) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b867fe3dc8](https://linux-hardware.org/?probe=b867fe3dc8) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c96223f666](https://linux-hardware.org/?probe=c96223f666) | Apr 06, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | Notebook    | [c7a893da2e](https://linux-hardware.org/?probe=c7a893da2e) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | Notebook    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| MSI           | MS-7418 100                 | Desktop     | [af5ab7c73f](https://linux-hardware.org/?probe=af5ab7c73f) | Apr 06, 2021 |
| Dell          | Precision 5530              | Notebook    | [64ca23f74b](https://linux-hardware.org/?probe=64ca23f74b) | Apr 06, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7a299e175f](https://linux-hardware.org/?probe=7a299e175f) | Apr 05, 2021 |
| Toshiba       | Satellite L300D             | Notebook    | [35514af81d](https://linux-hardware.org/?probe=35514af81d) | Apr 04, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [bf647eb6cd](https://linux-hardware.org/?probe=bf647eb6cd) | Apr 03, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [6fe414f2da](https://linux-hardware.org/?probe=6fe414f2da) | Apr 02, 2021 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [0b8822b65d](https://linux-hardware.org/?probe=0b8822b65d) | Apr 02, 2021 |
| MSI           | MS-7061                     | Desktop     | [ff8b934f8d](https://linux-hardware.org/?probe=ff8b934f8d) | Mar 31, 2021 |
| HP            | 8299                        | Desktop     | [12120a16f6](https://linux-hardware.org/?probe=12120a16f6) | Mar 30, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [4ceb1f2a16](https://linux-hardware.org/?probe=4ceb1f2a16) | Mar 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [fc6346c32b](https://linux-hardware.org/?probe=fc6346c32b) | Mar 29, 2021 |
| Dell          | Latitude 3400               | Notebook    | [e1cab5dc75](https://linux-hardware.org/?probe=e1cab5dc75) | Mar 29, 2021 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [178235fdc8](https://linux-hardware.org/?probe=178235fdc8) | Mar 28, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [1b8abaccfb](https://linux-hardware.org/?probe=1b8abaccfb) | Mar 26, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [889d834138](https://linux-hardware.org/?probe=889d834138) | Mar 26, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [53380cdda7](https://linux-hardware.org/?probe=53380cdda7) | Mar 25, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d40fdda820](https://linux-hardware.org/?probe=d40fdda820) | Mar 25, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [84c62ff65b](https://linux-hardware.org/?probe=84c62ff65b) | Mar 25, 2021 |
| HP            | 250 G2                      | Notebook    | [54d0d70b5f](https://linux-hardware.org/?probe=54d0d70b5f) | Mar 24, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [2200a1532c](https://linux-hardware.org/?probe=2200a1532c) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [98195974ff](https://linux-hardware.org/?probe=98195974ff) | Mar 24, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [4faf6a3407](https://linux-hardware.org/?probe=4faf6a3407) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [e2a76e43e7](https://linux-hardware.org/?probe=e2a76e43e7) | Mar 23, 2021 |
| HP            | EliteBook 8530p             | Notebook    | [7ee41a2d5d](https://linux-hardware.org/?probe=7ee41a2d5d) | Mar 23, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [e4bd78422e](https://linux-hardware.org/?probe=e4bd78422e) | Mar 22, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [5860ac9ed4](https://linux-hardware.org/?probe=5860ac9ed4) | Mar 21, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [c99d44a48e](https://linux-hardware.org/?probe=c99d44a48e) | Mar 21, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [5318e4fc82](https://linux-hardware.org/?probe=5318e4fc82) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [39c5751f26](https://linux-hardware.org/?probe=39c5751f26) | Mar 20, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ffad8b5cba](https://linux-hardware.org/?probe=ffad8b5cba) | Mar 19, 2021 |
| Dell          | Latitude E6400              | Notebook    | [ae7a7ffce1](https://linux-hardware.org/?probe=ae7a7ffce1) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0cbaa85995](https://linux-hardware.org/?probe=0cbaa85995) | Mar 17, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [240e99298f](https://linux-hardware.org/?probe=240e99298f) | Mar 17, 2021 |
| Dell          | Latitude E6420              | Notebook    | [e7f5f57404](https://linux-hardware.org/?probe=e7f5f57404) | Mar 17, 2021 |
| Clevo         | W250ENQ / W270ENQ           | Notebook    | [aad8ca4f6f](https://linux-hardware.org/?probe=aad8ca4f6f) | Mar 17, 2021 |
| Biostar       | TB250-BTC PRO               | Desktop     | [e53aecefd9](https://linux-hardware.org/?probe=e53aecefd9) | Mar 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [9f125de705](https://linux-hardware.org/?probe=9f125de705) | Mar 16, 2021 |
| Dell          | Latitude 5411               | Notebook    | [e992a2c9e6](https://linux-hardware.org/?probe=e992a2c9e6) | Mar 16, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [8e366d0ac5](https://linux-hardware.org/?probe=8e366d0ac5) | Mar 16, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [c8bdece188](https://linux-hardware.org/?probe=c8bdece188) | Mar 15, 2021 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [38b0010bcd](https://linux-hardware.org/?probe=38b0010bcd) | Mar 14, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [878ef5b5a9](https://linux-hardware.org/?probe=878ef5b5a9) | Mar 14, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [0072a02a5d](https://linux-hardware.org/?probe=0072a02a5d) | Mar 14, 2021 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [9a6cc50c52](https://linux-hardware.org/?probe=9a6cc50c52) | Mar 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [65c8aaa5aa](https://linux-hardware.org/?probe=65c8aaa5aa) | Mar 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5eed23aaf7](https://linux-hardware.org/?probe=5eed23aaf7) | Mar 13, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [453b938647](https://linux-hardware.org/?probe=453b938647) | Mar 13, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [a837738425](https://linux-hardware.org/?probe=a837738425) | Mar 12, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ecb1d8ee1d](https://linux-hardware.org/?probe=ecb1d8ee1d) | Mar 11, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [fc3b7d2f2b](https://linux-hardware.org/?probe=fc3b7d2f2b) | Mar 10, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [b1a4fc67b5](https://linux-hardware.org/?probe=b1a4fc67b5) | Mar 10, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [da00de06ed](https://linux-hardware.org/?probe=da00de06ed) | Mar 10, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [82a9fbf842](https://linux-hardware.org/?probe=82a9fbf842) | Mar 10, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [dc06698753](https://linux-hardware.org/?probe=dc06698753) | Mar 10, 2021 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [b0a0929002](https://linux-hardware.org/?probe=b0a0929002) | Mar 09, 2021 |
| ZOTAC         | ZBOX-BI324                  | Mini pc     | [0d05b404dd](https://linux-hardware.org/?probe=0d05b404dd) | Mar 08, 2021 |
| ASUSTek       | UX51VZA                     | Notebook    | [14ae24e6d8](https://linux-hardware.org/?probe=14ae24e6d8) | Mar 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [590b33fc27](https://linux-hardware.org/?probe=590b33fc27) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [094e63ef62](https://linux-hardware.org/?probe=094e63ef62) | Mar 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [fb0bf9134c](https://linux-hardware.org/?probe=fb0bf9134c) | Mar 06, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [5737dda498](https://linux-hardware.org/?probe=5737dda498) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [192f0fd756](https://linux-hardware.org/?probe=192f0fd756) | Mar 05, 2021 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [d75d9b7907](https://linux-hardware.org/?probe=d75d9b7907) | Mar 05, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [c4265bb6c4](https://linux-hardware.org/?probe=c4265bb6c4) | Mar 04, 2021 |
| HP            | 872E                        | Mini pc     | [95939e2aed](https://linux-hardware.org/?probe=95939e2aed) | Mar 04, 2021 |
| Lenovo        | Flex 2 Pro-15 80FL          | Notebook    | [8e5ead087c](https://linux-hardware.org/?probe=8e5ead087c) | Mar 04, 2021 |
| Toshiba       | Satellite L740              | Notebook    | [91b7d3fb4d](https://linux-hardware.org/?probe=91b7d3fb4d) | Mar 02, 2021 |
| HP            | 8299                        | Desktop     | [e8e31dfc6e](https://linux-hardware.org/?probe=e8e31dfc6e) | Mar 01, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d35de9f29e](https://linux-hardware.org/?probe=d35de9f29e) | Feb 28, 2021 |
| Fujitsu       | D3024-A1 S26361-D3024-A1    | Desktop     | [00cab9c594](https://linux-hardware.org/?probe=00cab9c594) | Feb 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [bec2f7357a](https://linux-hardware.org/?probe=bec2f7357a) | Feb 28, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c3d85c83ec](https://linux-hardware.org/?probe=c3d85c83ec) | Feb 28, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [675be05d71](https://linux-hardware.org/?probe=675be05d71) | Feb 27, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [3026ac5e90](https://linux-hardware.org/?probe=3026ac5e90) | Feb 27, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [de86804d84](https://linux-hardware.org/?probe=de86804d84) | Feb 27, 2021 |
| Dell          | Latitude E6230              | Notebook    | [c3772d78aa](https://linux-hardware.org/?probe=c3772d78aa) | Feb 26, 2021 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [5ebac513c1](https://linux-hardware.org/?probe=5ebac513c1) | Feb 26, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5dcdaebb4e](https://linux-hardware.org/?probe=5dcdaebb4e) | Feb 26, 2021 |
| Dell          | Latitude E6410              | Notebook    | [6f3fa9e9f2](https://linux-hardware.org/?probe=6f3fa9e9f2) | Feb 26, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [94d8e7faa5](https://linux-hardware.org/?probe=94d8e7faa5) | Feb 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [9ab78f21ad](https://linux-hardware.org/?probe=9ab78f21ad) | Feb 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [dd4d88de48](https://linux-hardware.org/?probe=dd4d88de48) | Feb 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [07f4d11bd6](https://linux-hardware.org/?probe=07f4d11bd6) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [3c13afb411](https://linux-hardware.org/?probe=3c13afb411) | Feb 25, 2021 |
| ASUSTek       | M50Vc                       | Notebook    | [8abf85e052](https://linux-hardware.org/?probe=8abf85e052) | Feb 24, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [58d3bac346](https://linux-hardware.org/?probe=58d3bac346) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | Notebook    | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [9cd18dc0e4](https://linux-hardware.org/?probe=9cd18dc0e4) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | Notebook    | [3a9a5e9b7c](https://linux-hardware.org/?probe=3a9a5e9b7c) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | Notebook    | [295654ca20](https://linux-hardware.org/?probe=295654ca20) | Feb 24, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [f1d7117dc7](https://linux-hardware.org/?probe=f1d7117dc7) | Feb 23, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [55cfaaee1b](https://linux-hardware.org/?probe=55cfaaee1b) | Feb 22, 2021 |
| ASUSTek       | M4N78 SE                    | Desktop     | [da1fd4246e](https://linux-hardware.org/?probe=da1fd4246e) | Feb 22, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [9d65892538](https://linux-hardware.org/?probe=9d65892538) | Feb 22, 2021 |
| Dell          | G5 5587                     | Notebook    | [0b0fc3b694](https://linux-hardware.org/?probe=0b0fc3b694) | Feb 22, 2021 |
| Lenovo        | ThinkPad T490 20N2000CMC    | Notebook    | [b23d98dd6a](https://linux-hardware.org/?probe=b23d98dd6a) | Feb 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [db101fb87e](https://linux-hardware.org/?probe=db101fb87e) | Feb 21, 2021 |
| ASUSTek       | K55VM                       | Notebook    | [7e11b6bd85](https://linux-hardware.org/?probe=7e11b6bd85) | Feb 20, 2021 |
| Lenovo        | 316E NOK                    | Mini pc     | [7146acbc96](https://linux-hardware.org/?probe=7146acbc96) | Feb 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [8ec77495b5](https://linux-hardware.org/?probe=8ec77495b5) | Feb 17, 2021 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [150d692c9a](https://linux-hardware.org/?probe=150d692c9a) | Feb 16, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [36d10d9091](https://linux-hardware.org/?probe=36d10d9091) | Feb 16, 2021 |
| Biostar       | TB250-BTC PRO               | Desktop     | [b0d416dfbc](https://linux-hardware.org/?probe=b0d416dfbc) | Feb 16, 2021 |
| Dell          | Latitude 3400               | Notebook    | [38dbd98cd4](https://linux-hardware.org/?probe=38dbd98cd4) | Feb 15, 2021 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [40dd819b23](https://linux-hardware.org/?probe=40dd819b23) | Feb 15, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [c9694dd19b](https://linux-hardware.org/?probe=c9694dd19b) | Feb 15, 2021 |
| UMAX          | VisionBook 14Wa Plus        | Notebook    | [85de5460d8](https://linux-hardware.org/?probe=85de5460d8) | Feb 15, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4b0521d0ee](https://linux-hardware.org/?probe=4b0521d0ee) | Feb 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [23ecc9c16e](https://linux-hardware.org/?probe=23ecc9c16e) | Feb 13, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [a94647b020](https://linux-hardware.org/?probe=a94647b020) | Feb 12, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [fae8d202da](https://linux-hardware.org/?probe=fae8d202da) | Feb 12, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [6379e4d092](https://linux-hardware.org/?probe=6379e4d092) | Feb 12, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [d822d59913](https://linux-hardware.org/?probe=d822d59913) | Feb 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c6487b7947](https://linux-hardware.org/?probe=c6487b7947) | Feb 11, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4ce0e6df68](https://linux-hardware.org/?probe=4ce0e6df68) | Feb 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| ASUSTek       | X453SA                      | Notebook    | [5e4fcc2492](https://linux-hardware.org/?probe=5e4fcc2492) | Feb 10, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [40877f0c5d](https://linux-hardware.org/?probe=40877f0c5d) | Feb 10, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [4caff97f56](https://linux-hardware.org/?probe=4caff97f56) | Feb 08, 2021 |
| Dell          | Latitude E6230              | Notebook    | [6562ca7135](https://linux-hardware.org/?probe=6562ca7135) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [2ef8a250d3](https://linux-hardware.org/?probe=2ef8a250d3) | Feb 07, 2021 |
| Sony          | VGN-FW31J                   | Notebook    | [3ac086a40c](https://linux-hardware.org/?probe=3ac086a40c) | Feb 07, 2021 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [aae7eb09bf](https://linux-hardware.org/?probe=aae7eb09bf) | Feb 06, 2021 |
| Dell          | Latitude E5450              | Notebook    | [9b2f037a8e](https://linux-hardware.org/?probe=9b2f037a8e) | Feb 06, 2021 |
| Dell          | Latitude E5450              | Notebook    | [9cce8a2306](https://linux-hardware.org/?probe=9cce8a2306) | Feb 06, 2021 |
| Dell          | Latitude E6410              | Notebook    | [02a7d362ab](https://linux-hardware.org/?probe=02a7d362ab) | Feb 05, 2021 |
| Dell          | Latitude E6400              | Notebook    | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [36c87ef485](https://linux-hardware.org/?probe=36c87ef485) | Feb 03, 2021 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [706a8c3c73](https://linux-hardware.org/?probe=706a8c3c73) | Feb 03, 2021 |
| Acer          | Aspire S3-391               | Notebook    | [c7205a1bc6](https://linux-hardware.org/?probe=c7205a1bc6) | Feb 02, 2021 |
| ASRock        | G41C-GS                     | Desktop     | [47cbf95a16](https://linux-hardware.org/?probe=47cbf95a16) | Feb 02, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [29483c03e0](https://linux-hardware.org/?probe=29483c03e0) | Feb 01, 2021 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [3a99ca2e3a](https://linux-hardware.org/?probe=3a99ca2e3a) | Feb 01, 2021 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0a61c5b666](https://linux-hardware.org/?probe=0a61c5b666) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [46453067b0](https://linux-hardware.org/?probe=46453067b0) | Jan 31, 2021 |
| HP            | 8299                        | Desktop     | [16e50ec1cd](https://linux-hardware.org/?probe=16e50ec1cd) | Jan 31, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [bbfd58bb17](https://linux-hardware.org/?probe=bbfd58bb17) | Jan 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a51a715f7b](https://linux-hardware.org/?probe=a51a715f7b) | Jan 30, 2021 |
| Acer          | Aspire one                  | Notebook    | [596cf5fb05](https://linux-hardware.org/?probe=596cf5fb05) | Jan 30, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [ebe001400f](https://linux-hardware.org/?probe=ebe001400f) | Jan 30, 2021 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [a01fc6e6fc](https://linux-hardware.org/?probe=a01fc6e6fc) | Jan 28, 2021 |
| Acer          | Aspire V7-581G              | Notebook    | [bc8dcae398](https://linux-hardware.org/?probe=bc8dcae398) | Jan 28, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [655fd94c5b](https://linux-hardware.org/?probe=655fd94c5b) | Jan 27, 2021 |
| Dell          | Precision 5510              | Notebook    | [f548cf6034](https://linux-hardware.org/?probe=f548cf6034) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [59a1df6c23](https://linux-hardware.org/?probe=59a1df6c23) | Jan 27, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [0d9fb09cb0](https://linux-hardware.org/?probe=0d9fb09cb0) | Jan 27, 2021 |
| HP            | EliteBook x360 830 G6       | Convertible | [d270107ee9](https://linux-hardware.org/?probe=d270107ee9) | Jan 27, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8405804af1](https://linux-hardware.org/?probe=8405804af1) | Jan 26, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b024107bc](https://linux-hardware.org/?probe=5b024107bc) | Jan 26, 2021 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [386196c0dd](https://linux-hardware.org/?probe=386196c0dd) | Jan 26, 2021 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [f428258e3c](https://linux-hardware.org/?probe=f428258e3c) | Jan 26, 2021 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [f5b2931f56](https://linux-hardware.org/?probe=f5b2931f56) | Jan 26, 2021 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [daaa93aeda](https://linux-hardware.org/?probe=daaa93aeda) | Jan 26, 2021 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [353cfbeabe](https://linux-hardware.org/?probe=353cfbeabe) | Jan 26, 2021 |
| HP            | 872E                        | Mini pc     | [453436fd86](https://linux-hardware.org/?probe=453436fd86) | Jan 25, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e92acb1c9f](https://linux-hardware.org/?probe=e92acb1c9f) | Jan 25, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [a519fed9ad](https://linux-hardware.org/?probe=a519fed9ad) | Jan 25, 2021 |
| HP            | 0AA8h                       | Desktop     | [3a726e28e4](https://linux-hardware.org/?probe=3a726e28e4) | Jan 23, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [f950b8cb2c](https://linux-hardware.org/?probe=f950b8cb2c) | Jan 23, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [7177dfdace](https://linux-hardware.org/?probe=7177dfdace) | Jan 23, 2021 |
| Dell          | Latitude E5500              | Notebook    | [bf4f6f14c2](https://linux-hardware.org/?probe=bf4f6f14c2) | Jan 22, 2021 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [39bb07129a](https://linux-hardware.org/?probe=39bb07129a) | Jan 21, 2021 |
| Dell          | Precision 5510              | Notebook    | [023ebcd846](https://linux-hardware.org/?probe=023ebcd846) | Jan 21, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e6246a62eb](https://linux-hardware.org/?probe=e6246a62eb) | Jan 20, 2021 |
| Dell          | Latitude E5440              | Notebook    | [462f80efe3](https://linux-hardware.org/?probe=462f80efe3) | Jan 20, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [8f063fe8f1](https://linux-hardware.org/?probe=8f063fe8f1) | Jan 19, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [5a83f4c70e](https://linux-hardware.org/?probe=5a83f4c70e) | Jan 19, 2021 |
| Dell          | Latitude D430               | Notebook    | [e364de4914](https://linux-hardware.org/?probe=e364de4914) | Jan 19, 2021 |
| Dell          | Latitude D430               | Notebook    | [632ede8190](https://linux-hardware.org/?probe=632ede8190) | Jan 19, 2021 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [177818b63b](https://linux-hardware.org/?probe=177818b63b) | Jan 19, 2021 |
| HP            | ProBook 4545s               | Notebook    | [a1361456ee](https://linux-hardware.org/?probe=a1361456ee) | Jan 19, 2021 |
| Lenovo        | ThinkPad T400 6475Y4M       | Notebook    | [e6ea4283a5](https://linux-hardware.org/?probe=e6ea4283a5) | Jan 18, 2021 |
| Lenovo        | ThinkPad T400 6475Y4M       | Notebook    | [af004cce06](https://linux-hardware.org/?probe=af004cce06) | Jan 18, 2021 |
| ASUSTek       | M4A77TD                     | Desktop     | [8dff00cfff](https://linux-hardware.org/?probe=8dff00cfff) | Jan 18, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [79848dc213](https://linux-hardware.org/?probe=79848dc213) | Jan 17, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [f26799f89e](https://linux-hardware.org/?probe=f26799f89e) | Jan 17, 2021 |
| MSI           | 970A-G46                    | Desktop     | [139738eab5](https://linux-hardware.org/?probe=139738eab5) | Jan 16, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [16ded24529](https://linux-hardware.org/?probe=16ded24529) | Jan 15, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [8ada2201db](https://linux-hardware.org/?probe=8ada2201db) | Jan 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [beaa31df09](https://linux-hardware.org/?probe=beaa31df09) | Jan 14, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [0a975a35b9](https://linux-hardware.org/?probe=0a975a35b9) | Jan 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| Lenovo        | ThinkPad T460 20FN004CMC    | Notebook    | [dc80798934](https://linux-hardware.org/?probe=dc80798934) | Jan 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b5b9926afa](https://linux-hardware.org/?probe=b5b9926afa) | Jan 11, 2021 |
| Sony          | VPCEB1M1E                   | Notebook    | [47b920b10a](https://linux-hardware.org/?probe=47b920b10a) | Jan 10, 2021 |
| HP            | Presario CQ57               | Notebook    | [f87fc12d71](https://linux-hardware.org/?probe=f87fc12d71) | Jan 10, 2021 |
| MSI           | IONA                        | Desktop     | [d28e052ec6](https://linux-hardware.org/?probe=d28e052ec6) | Jan 10, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [986a4852e5](https://linux-hardware.org/?probe=986a4852e5) | Jan 09, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [260ee629ec](https://linux-hardware.org/?probe=260ee629ec) | Jan 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [33c8efc4d3](https://linux-hardware.org/?probe=33c8efc4d3) | Jan 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [6d373a3972](https://linux-hardware.org/?probe=6d373a3972) | Jan 09, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MS-7061                     | Desktop     | [5701f637e7](https://linux-hardware.org/?probe=5701f637e7) | Jan 04, 2021 |
| ASUSTek       | G60JX                       | Notebook    | [e193018885](https://linux-hardware.org/?probe=e193018885) | Jan 03, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [0c506c630e](https://linux-hardware.org/?probe=0c506c630e) | Jan 02, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [9c7e318dbb](https://linux-hardware.org/?probe=9c7e318dbb) | Jan 01, 2021 |
| Acer          | TravelMate X314-51-MG       | Notebook    | [f2d686d743](https://linux-hardware.org/?probe=f2d686d743) | Jan 01, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [776e78f155](https://linux-hardware.org/?probe=776e78f155) | Jan 01, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [044a6a709e](https://linux-hardware.org/?probe=044a6a709e) | Dec 31, 2020 |
| Dell          | 0T10XW A01                  | Desktop     | [7170404b87](https://linux-hardware.org/?probe=7170404b87) | Dec 31, 2020 |
| ASUSTek       | F3E                         | Notebook    | [76935b8cde](https://linux-hardware.org/?probe=76935b8cde) | Dec 30, 2020 |
| ASUSTek       | F3E                         | Notebook    | [db7f14138d](https://linux-hardware.org/?probe=db7f14138d) | Dec 30, 2020 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [391f80ae12](https://linux-hardware.org/?probe=391f80ae12) | Dec 29, 2020 |
| Lenovo        | ThinkPad T430 23444ZG       | Notebook    | [5904ca74c2](https://linux-hardware.org/?probe=5904ca74c2) | Dec 29, 2020 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [a975124fe9](https://linux-hardware.org/?probe=a975124fe9) | Dec 29, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [cd80521f36](https://linux-hardware.org/?probe=cd80521f36) | Dec 29, 2020 |
| Acer          | Aspire S3-391               | Notebook    | [cbb35e678a](https://linux-hardware.org/?probe=cbb35e678a) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [3994a22935](https://linux-hardware.org/?probe=3994a22935) | Dec 27, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [772dc9d4d7](https://linux-hardware.org/?probe=772dc9d4d7) | Dec 27, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | Notebook    | [e43e83e37e](https://linux-hardware.org/?probe=e43e83e37e) | Dec 26, 2020 |
| Intel         | DQ67OW AAG12528-309         | Desktop     | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | Notebook    | [2352b3bdff](https://linux-hardware.org/?probe=2352b3bdff) | Dec 26, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d5fa351273](https://linux-hardware.org/?probe=d5fa351273) | Dec 26, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [fa8a07845c](https://linux-hardware.org/?probe=fa8a07845c) | Dec 25, 2020 |
| MSI           | GE60 2QE                    | Notebook    | [57f71a51e7](https://linux-hardware.org/?probe=57f71a51e7) | Dec 25, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [edb4c27530](https://linux-hardware.org/?probe=edb4c27530) | Dec 24, 2020 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [a268e961d2](https://linux-hardware.org/?probe=a268e961d2) | Dec 24, 2020 |
| Dell          | Latitude E6430s             | Notebook    | [d9e710f80e](https://linux-hardware.org/?probe=d9e710f80e) | Dec 24, 2020 |
| Lenovo        | G780 20138                  | Notebook    | [337ed92b96](https://linux-hardware.org/?probe=337ed92b96) | Dec 21, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [14e569e26c](https://linux-hardware.org/?probe=14e569e26c) | Dec 20, 2020 |
| HP            | 18E7                        | Desktop     | [a84ff44872](https://linux-hardware.org/?probe=a84ff44872) | Dec 20, 2020 |
| ASRock        | B75M-GL R2.0                | Desktop     | [91c33b15fe](https://linux-hardware.org/?probe=91c33b15fe) | Dec 18, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [c904ecb72d](https://linux-hardware.org/?probe=c904ecb72d) | Dec 18, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [94b7599bed](https://linux-hardware.org/?probe=94b7599bed) | Dec 16, 2020 |
| Dell          | Latitude 7390               | Notebook    | [30de38003f](https://linux-hardware.org/?probe=30de38003f) | Dec 16, 2020 |
| ASUSTek       | M2N-E                       | Desktop     | [8fa83ff1f4](https://linux-hardware.org/?probe=8fa83ff1f4) | Dec 16, 2020 |
| Apple         | MacBookPro6,2               | Notebook    | [d4f9ccd7a6](https://linux-hardware.org/?probe=d4f9ccd7a6) | Dec 16, 2020 |
| Apple         | MacBookPro6,2               | Notebook    | [7faceca969](https://linux-hardware.org/?probe=7faceca969) | Dec 16, 2020 |
| ASUSTek       | M2N-E                       | Desktop     | [6a68ea590f](https://linux-hardware.org/?probe=6a68ea590f) | Dec 15, 2020 |
| ASUSTek       | M2N-E                       | Desktop     | [5b0148344f](https://linux-hardware.org/?probe=5b0148344f) | Dec 15, 2020 |
| MSI           | IONA                        | Desktop     | [e0c6ee5ff1](https://linux-hardware.org/?probe=e0c6ee5ff1) | Dec 15, 2020 |
| HP            | ProBook x360 435 G7         | Convertible | [05fe7ca9d3](https://linux-hardware.org/?probe=05fe7ca9d3) | Dec 15, 2020 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [8c7c33ba8b](https://linux-hardware.org/?probe=8c7c33ba8b) | Dec 14, 2020 |
| HP            | ProBook x360 435 G7         | Convertible | [e5bf7702bf](https://linux-hardware.org/?probe=e5bf7702bf) | Dec 14, 2020 |
| Gigabyte      | EG41MF-S2H                  | Desktop     | [81d8b34e8e](https://linux-hardware.org/?probe=81d8b34e8e) | Dec 14, 2020 |
| Lenovo        | ThinkPad T470 20HES18R19    | Notebook    | [11ce58f939](https://linux-hardware.org/?probe=11ce58f939) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8f96733244](https://linux-hardware.org/?probe=8f96733244) | Dec 13, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f86eaf1968](https://linux-hardware.org/?probe=f86eaf1968) | Dec 12, 2020 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [a767404d0e](https://linux-hardware.org/?probe=a767404d0e) | Dec 12, 2020 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [5edf82c417](https://linux-hardware.org/?probe=5edf82c417) | Dec 12, 2020 |
| MSI           | MS-1688                     | Notebook    | [b56c16909d](https://linux-hardware.org/?probe=b56c16909d) | Dec 12, 2020 |
| Dell          | Precision 3551              | Notebook    | [ffc4c549c8](https://linux-hardware.org/?probe=ffc4c549c8) | Dec 11, 2020 |
| ASRock        | B75M-GL R2.0                | Desktop     | [b083b46acb](https://linux-hardware.org/?probe=b083b46acb) | Dec 10, 2020 |
| ASUSTek       | X550MJ                      | Notebook    | [66ed5909f8](https://linux-hardware.org/?probe=66ed5909f8) | Dec 10, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [ac22f08b80](https://linux-hardware.org/?probe=ac22f08b80) | Dec 09, 2020 |
| Dell          | Latitude E6520              | Notebook    | [ae5183024d](https://linux-hardware.org/?probe=ae5183024d) | Dec 08, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [a1c00e55f5](https://linux-hardware.org/?probe=a1c00e55f5) | Dec 08, 2020 |
| Dell          | Inspiron 7386               | Convertible | [dc323143f1](https://linux-hardware.org/?probe=dc323143f1) | Dec 08, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8572ec4934](https://linux-hardware.org/?probe=8572ec4934) | Dec 08, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [99ba99aa39](https://linux-hardware.org/?probe=99ba99aa39) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| Intel         | STCK1A8LFC H67494-302       | Notebook    | [5cd8520aac](https://linux-hardware.org/?probe=5cd8520aac) | Dec 05, 2020 |
| Sony          | VGN-FW31J                   | Notebook    | [f12caf061a](https://linux-hardware.org/?probe=f12caf061a) | Dec 05, 2020 |
| HP            | 1905                        | Desktop     | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5AD0... | Notebook    | [019dc4a90e](https://linux-hardware.org/?probe=019dc4a90e) | Dec 03, 2020 |
| MSI           | H81M-P33                    | Desktop     | [9c614066cc](https://linux-hardware.org/?probe=9c614066cc) | Dec 03, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| Acer          | Extensa 5620                | Notebook    | [f2087b24cf](https://linux-hardware.org/?probe=f2087b24cf) | Dec 02, 2020 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [80ed74b9e9](https://linux-hardware.org/?probe=80ed74b9e9) | Dec 02, 2020 |
| ASUSTek       | GL552VX                     | Notebook    | [c93b1307eb](https://linux-hardware.org/?probe=c93b1307eb) | Dec 01, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [36e6f5226e](https://linux-hardware.org/?probe=36e6f5226e) | Nov 30, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [9ef03140e1](https://linux-hardware.org/?probe=9ef03140e1) | Nov 30, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [78cf05bb96](https://linux-hardware.org/?probe=78cf05bb96) | Nov 29, 2020 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [5d92c2dda4](https://linux-hardware.org/?probe=5d92c2dda4) | Nov 28, 2020 |
| Sony          | VGN-Z21XN_B                 | Notebook    | [155a9f6fa6](https://linux-hardware.org/?probe=155a9f6fa6) | Nov 28, 2020 |
| HP            | Compaq 8510w                | Notebook    | [aa775a9324](https://linux-hardware.org/?probe=aa775a9324) | Nov 28, 2020 |
| HP            | ProBook 6570b               | Notebook    | [679b85fd07](https://linux-hardware.org/?probe=679b85fd07) | Nov 27, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [db9601a874](https://linux-hardware.org/?probe=db9601a874) | Nov 26, 2020 |
| Dell          | Latitude 7390               | Notebook    | [f95f774a38](https://linux-hardware.org/?probe=f95f774a38) | Nov 26, 2020 |
| Jumper        | EZpad                       | Notebook    | [2c2ae2e061](https://linux-hardware.org/?probe=2c2ae2e061) | Nov 25, 2020 |
| HP            | 8618                        | Desktop     | [91f724f25b](https://linux-hardware.org/?probe=91f724f25b) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [d39ba59434](https://linux-hardware.org/?probe=d39ba59434) | Nov 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7e1033e8f3](https://linux-hardware.org/?probe=7e1033e8f3) | Nov 22, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [2a3f3bd4a4](https://linux-hardware.org/?probe=2a3f3bd4a4) | Nov 22, 2020 |
| Jumper        | EZpad                       | Notebook    | [807a525352](https://linux-hardware.org/?probe=807a525352) | Nov 21, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [a49a6f5cd0](https://linux-hardware.org/?probe=a49a6f5cd0) | Nov 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [6b203577af](https://linux-hardware.org/?probe=6b203577af) | Nov 20, 2020 |
| ASUSTek       | H110M-K                     | Desktop     | [985b5c933d](https://linux-hardware.org/?probe=985b5c933d) | Nov 20, 2020 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [a706435b39](https://linux-hardware.org/?probe=a706435b39) | Nov 20, 2020 |
| MSI           | Z97 GAMING 7                | Desktop     | [c1e3c06f22](https://linux-hardware.org/?probe=c1e3c06f22) | Nov 20, 2020 |
| ASRock        | B75M-GL R2.0                | Desktop     | [1c9a604ba6](https://linux-hardware.org/?probe=1c9a604ba6) | Nov 20, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [b536f1bb57](https://linux-hardware.org/?probe=b536f1bb57) | Nov 19, 2020 |
| HP            | Pavilion TS 11              | Notebook    | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| Lenovo        | ThinkPad R61 8935WFB        | Notebook    | [b82d043b71](https://linux-hardware.org/?probe=b82d043b71) | Nov 18, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [020d4844ae](https://linux-hardware.org/?probe=020d4844ae) | Nov 18, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [c8af4ac482](https://linux-hardware.org/?probe=c8af4ac482) | Nov 18, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [e9b53cc836](https://linux-hardware.org/?probe=e9b53cc836) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ded8f80f0a](https://linux-hardware.org/?probe=ded8f80f0a) | Nov 18, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bbd45f8b19](https://linux-hardware.org/?probe=bbd45f8b19) | Nov 17, 2020 |
| Acer          | Aspire V7-482P              | Notebook    | [c7b8a90092](https://linux-hardware.org/?probe=c7b8a90092) | Nov 17, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [f1f13f5b38](https://linux-hardware.org/?probe=f1f13f5b38) | Nov 17, 2020 |
| In-Sing       | NK81J                       | Notebook    | [2f129a4a67](https://linux-hardware.org/?probe=2f129a4a67) | Nov 16, 2020 |
| In-Sing       | NK81J                       | Notebook    | [a3282a8f65](https://linux-hardware.org/?probe=a3282a8f65) | Nov 16, 2020 |
| Lenovo        | ThinkPad Edge E530 3259B... | Notebook    | [c46ceddde5](https://linux-hardware.org/?probe=c46ceddde5) | Nov 16, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [8b8a83f80b](https://linux-hardware.org/?probe=8b8a83f80b) | Nov 15, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [3568e22cde](https://linux-hardware.org/?probe=3568e22cde) | Nov 14, 2020 |
| Acer          | Aspire V7-482P              | Notebook    | [cff0a4d702](https://linux-hardware.org/?probe=cff0a4d702) | Nov 14, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5e2da261c7](https://linux-hardware.org/?probe=5e2da261c7) | Nov 14, 2020 |
| ASUSTek       | T102HA                      | Tablet      | [8804e25000](https://linux-hardware.org/?probe=8804e25000) | Nov 13, 2020 |
| Dell          | XPS 13 9343                 | Notebook    | [4f86cf4cbf](https://linux-hardware.org/?probe=4f86cf4cbf) | Nov 13, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0bd4668348](https://linux-hardware.org/?probe=0bd4668348) | Nov 13, 2020 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [9f86ed3e72](https://linux-hardware.org/?probe=9f86ed3e72) | Nov 13, 2020 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5292c3d1c6](https://linux-hardware.org/?probe=5292c3d1c6) | Nov 13, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [08124a672d](https://linux-hardware.org/?probe=08124a672d) | Nov 12, 2020 |
| Dell          | 0DR845                      | Desktop     | [fdc86c4e1a](https://linux-hardware.org/?probe=fdc86c4e1a) | Nov 10, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [f816f90302](https://linux-hardware.org/?probe=f816f90302) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | Notebook    | [41f4ce9090](https://linux-hardware.org/?probe=41f4ce9090) | Nov 10, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [df7527ce9d](https://linux-hardware.org/?probe=df7527ce9d) | Nov 08, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [11e2a64b37](https://linux-hardware.org/?probe=11e2a64b37) | Nov 07, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [1adcc4379a](https://linux-hardware.org/?probe=1adcc4379a) | Nov 07, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [366328b790](https://linux-hardware.org/?probe=366328b790) | Nov 07, 2020 |
| Dell          | 0HR330                      | Desktop     | [6c239e76c2](https://linux-hardware.org/?probe=6c239e76c2) | Nov 07, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [233cd75348](https://linux-hardware.org/?probe=233cd75348) | Nov 05, 2020 |
| Dell          | Precision 7740              | Notebook    | [887976cf88](https://linux-hardware.org/?probe=887976cf88) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | Compaq 6910p                | Notebook    | [116434c462](https://linux-hardware.org/?probe=116434c462) | Nov 04, 2020 |
| MSI           | PS42 Modern 8RA             | Notebook    | [80629e1f55](https://linux-hardware.org/?probe=80629e1f55) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [4b34114e72](https://linux-hardware.org/?probe=4b34114e72) | Nov 03, 2020 |
| Dell          | Latitude E5520              | Notebook    | [59e9f4557e](https://linux-hardware.org/?probe=59e9f4557e) | Nov 02, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [e49822ee09](https://linux-hardware.org/?probe=e49822ee09) | Nov 02, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [54079a5e32](https://linux-hardware.org/?probe=54079a5e32) | Nov 02, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [f97fa98c1f](https://linux-hardware.org/?probe=f97fa98c1f) | Nov 01, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [d6ea9e1cd2](https://linux-hardware.org/?probe=d6ea9e1cd2) | Nov 01, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [0cfcb95449](https://linux-hardware.org/?probe=0cfcb95449) | Nov 01, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | Notebook    | [dda213843b](https://linux-hardware.org/?probe=dda213843b) | Nov 01, 2020 |
| ASUSTek       | N73SV                       | Notebook    | [b2d4729f22](https://linux-hardware.org/?probe=b2d4729f22) | Nov 01, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [9c630c8d83](https://linux-hardware.org/?probe=9c630c8d83) | Nov 01, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [f9755b992e](https://linux-hardware.org/?probe=f9755b992e) | Nov 01, 2020 |
| HP            | 255 G4                      | Notebook    | [e841543a23](https://linux-hardware.org/?probe=e841543a23) | Oct 31, 2020 |
| HP            | 255 G4                      | Notebook    | [79d387d0ab](https://linux-hardware.org/?probe=79d387d0ab) | Oct 31, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [b4f040feaa](https://linux-hardware.org/?probe=b4f040feaa) | Oct 31, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [85435abf0b](https://linux-hardware.org/?probe=85435abf0b) | Oct 31, 2020 |
| Gigabyte      | H81ND2H                     | Desktop     | [5d76ba9ebd](https://linux-hardware.org/?probe=5d76ba9ebd) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [287e2c5d14](https://linux-hardware.org/?probe=287e2c5d14) | Oct 30, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | Notebook    | [87ff568248](https://linux-hardware.org/?probe=87ff568248) | Oct 29, 2020 |
| Acer          | Extensa 5620                | Notebook    | [e7fab7440e](https://linux-hardware.org/?probe=e7fab7440e) | Oct 29, 2020 |
| Dell          | Inspiron 5593               | Notebook    | [3fbb5a72d7](https://linux-hardware.org/?probe=3fbb5a72d7) | Oct 28, 2020 |
| Gigabyte      | B550 GAMING X               | Desktop     | [c78aeb9bad](https://linux-hardware.org/?probe=c78aeb9bad) | Oct 28, 2020 |
| Toshiba       | Satellite P100              | Notebook    | [ea537c7d93](https://linux-hardware.org/?probe=ea537c7d93) | Oct 28, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [b52e1d7ccf](https://linux-hardware.org/?probe=b52e1d7ccf) | Oct 27, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Lenovo        | B51-80 80LM                 | Notebook    | [c40197b546](https://linux-hardware.org/?probe=c40197b546) | Oct 27, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6cff7fdaf7](https://linux-hardware.org/?probe=6cff7fdaf7) | Oct 27, 2020 |
| Lenovo        | Yoga S740-15IRH 81NX        | Convertible | [d3d59d0498](https://linux-hardware.org/?probe=d3d59d0498) | Oct 26, 2020 |
| HP            | EliteBook 830 G5            | Notebook    | [2ca9995218](https://linux-hardware.org/?probe=2ca9995218) | Oct 26, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [4ef991873c](https://linux-hardware.org/?probe=4ef991873c) | Oct 26, 2020 |
| Acer          | Aspire 8930                 | Notebook    | [fde733b7c7](https://linux-hardware.org/?probe=fde733b7c7) | Oct 25, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [4bba55301d](https://linux-hardware.org/?probe=4bba55301d) | Oct 24, 2020 |
| Dell          | Inspiron 5593               | Notebook    | [4f0c0f034e](https://linux-hardware.org/?probe=4f0c0f034e) | Oct 22, 2020 |
| Dell          | Inspiron 5593               | Notebook    | [aa31ceeb8f](https://linux-hardware.org/?probe=aa31ceeb8f) | Oct 22, 2020 |
| Dell          | Latitude E5520              | Notebook    | [2a250b5803](https://linux-hardware.org/?probe=2a250b5803) | Oct 22, 2020 |
| Dell          | Vostro 3350                 | Notebook    | [88e849444f](https://linux-hardware.org/?probe=88e849444f) | Oct 22, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4b7b836641](https://linux-hardware.org/?probe=4b7b836641) | Oct 21, 2020 |
| Dell          | Vostro 1510                 | Notebook    | [dd9a477473](https://linux-hardware.org/?probe=dd9a477473) | Oct 21, 2020 |
| INET          | P201P                       | Notebook    | [644453ac6f](https://linux-hardware.org/?probe=644453ac6f) | Oct 21, 2020 |
| Dell          | Latitude E5540              | Notebook    | [7baf46ea1a](https://linux-hardware.org/?probe=7baf46ea1a) | Oct 21, 2020 |
| MSI           | X370 GAMING PLUS            | Desktop     | [66088ce191](https://linux-hardware.org/?probe=66088ce191) | Oct 20, 2020 |
| Sony          | VGN-FW31J                   | Notebook    | [a2ab2b1bee](https://linux-hardware.org/?probe=a2ab2b1bee) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [04aed365e7](https://linux-hardware.org/?probe=04aed365e7) | Oct 18, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [054a64d6f2](https://linux-hardware.org/?probe=054a64d6f2) | Oct 18, 2020 |
| MSI           | GE60 2QE                    | Notebook    | [246e6f7276](https://linux-hardware.org/?probe=246e6f7276) | Oct 17, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [0adb1dec20](https://linux-hardware.org/?probe=0adb1dec20) | Oct 16, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [c20f8b68f4](https://linux-hardware.org/?probe=c20f8b68f4) | Oct 16, 2020 |
| Acer          | EM61SM/EM61PM               | Desktop     | [d123fda7a8](https://linux-hardware.org/?probe=d123fda7a8) | Oct 16, 2020 |
| Unknown       | Unknown                     | Desktop     | [0dbef68451](https://linux-hardware.org/?probe=0dbef68451) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | Notebook    | [9b67d68beb](https://linux-hardware.org/?probe=9b67d68beb) | Oct 14, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | Notebook    | [b0407d39c3](https://linux-hardware.org/?probe=b0407d39c3) | Oct 14, 2020 |
| MSI           | X370 GAMING PLUS            | Desktop     | [46840b02f0](https://linux-hardware.org/?probe=46840b02f0) | Oct 14, 2020 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [519db3b4c6](https://linux-hardware.org/?probe=519db3b4c6) | Oct 14, 2020 |
| HP            | 1905                        | Desktop     | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [adba0a4782](https://linux-hardware.org/?probe=adba0a4782) | Oct 14, 2020 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [fca58ff529](https://linux-hardware.org/?probe=fca58ff529) | Oct 13, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [65aff7828e](https://linux-hardware.org/?probe=65aff7828e) | Oct 13, 2020 |
| Sony          | VGN-FW31J                   | Notebook    | [eee35eb8e9](https://linux-hardware.org/?probe=eee35eb8e9) | Oct 13, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8bdcdd3b6a](https://linux-hardware.org/?probe=8bdcdd3b6a) | Oct 13, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [c8fea4471d](https://linux-hardware.org/?probe=c8fea4471d) | Oct 11, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [93221fbe75](https://linux-hardware.org/?probe=93221fbe75) | Oct 11, 2020 |
| Acer          | Aspire GX-781               | Desktop     | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [1a53ead300](https://linux-hardware.org/?probe=1a53ead300) | Oct 10, 2020 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [80079c46e3](https://linux-hardware.org/?probe=80079c46e3) | Oct 10, 2020 |
| Acer          | Aspire V3-551G              | Notebook    | [30f77b0594](https://linux-hardware.org/?probe=30f77b0594) | Oct 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | Notebook    | [a14e9d2839](https://linux-hardware.org/?probe=a14e9d2839) | Oct 10, 2020 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [bb231aa749](https://linux-hardware.org/?probe=bb231aa749) | Oct 09, 2020 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [a89dffe004](https://linux-hardware.org/?probe=a89dffe004) | Oct 09, 2020 |
| Lenovo        | Yoga S740-15IRH 81NX        | Convertible | [5317a344a7](https://linux-hardware.org/?probe=5317a344a7) | Oct 09, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [9911a6b479](https://linux-hardware.org/?probe=9911a6b479) | Oct 09, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | Notebook    | [726bdf3762](https://linux-hardware.org/?probe=726bdf3762) | Oct 08, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [289f93a7e6](https://linux-hardware.org/?probe=289f93a7e6) | Oct 08, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [95a78ff474](https://linux-hardware.org/?probe=95a78ff474) | Oct 08, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [d01a07b619](https://linux-hardware.org/?probe=d01a07b619) | Oct 08, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [13fa4df109](https://linux-hardware.org/?probe=13fa4df109) | Oct 08, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [9649d645a8](https://linux-hardware.org/?probe=9649d645a8) | Oct 08, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [6870ec982e](https://linux-hardware.org/?probe=6870ec982e) | Oct 07, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [46ebc8c075](https://linux-hardware.org/?probe=46ebc8c075) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [86aa78e5af](https://linux-hardware.org/?probe=86aa78e5af) | Oct 05, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [c535d537e1](https://linux-hardware.org/?probe=c535d537e1) | Oct 05, 2020 |
| HP            | 1998                        | Desktop     | [8d941cca29](https://linux-hardware.org/?probe=8d941cca29) | Oct 05, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4df9440dcd](https://linux-hardware.org/?probe=4df9440dcd) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | Desktop     | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| Timi          | TM1701                      | Notebook    | [816373e2e3](https://linux-hardware.org/?probe=816373e2e3) | Oct 03, 2020 |
| Lenovo        | ThinkPad Edge E535 3260E... | Notebook    | [0803716b4c](https://linux-hardware.org/?probe=0803716b4c) | Oct 02, 2020 |
| ASUSTek       | X202E                       | Notebook    | [12592ec3e9](https://linux-hardware.org/?probe=12592ec3e9) | Oct 01, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [07e10b13eb](https://linux-hardware.org/?probe=07e10b13eb) | Sep 30, 2020 |
| ASRock        | N68-S                       | Desktop     | [e867c049a3](https://linux-hardware.org/?probe=e867c049a3) | Sep 30, 2020 |
| ASRock        | N68-S                       | Desktop     | [5e39fce3e2](https://linux-hardware.org/?probe=5e39fce3e2) | Sep 30, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| MSI           | 870-C45                     | Desktop     | [0c99fa95e9](https://linux-hardware.org/?probe=0c99fa95e9) | Sep 28, 2020 |
| HP            | 843B                        | Desktop     | [759b4e1098](https://linux-hardware.org/?probe=759b4e1098) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [6882b482eb](https://linux-hardware.org/?probe=6882b482eb) | Sep 27, 2020 |
| Acer          | Aspire V3-551G              | Notebook    | [8d1b0cab97](https://linux-hardware.org/?probe=8d1b0cab97) | Sep 27, 2020 |
| Acer          | Extensa 5620                | Notebook    | [7826e95ae0](https://linux-hardware.org/?probe=7826e95ae0) | Sep 27, 2020 |
| HP            | 500 Notebook PC (RQ260AA... | Notebook    | [01927c1bb9](https://linux-hardware.org/?probe=01927c1bb9) | Sep 27, 2020 |
| Lenovo        | ThinkPad T440 20B7A0VQMC    | Notebook    | [ee12117181](https://linux-hardware.org/?probe=ee12117181) | Sep 25, 2020 |
| HP            | 1905                        | Desktop     | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [6790f8d26f](https://linux-hardware.org/?probe=6790f8d26f) | Sep 24, 2020 |
| HP            | 1905                        | Desktop     | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | Desktop     | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| Dell          | Latitude E7440              | Notebook    | [c6208fcbea](https://linux-hardware.org/?probe=c6208fcbea) | Sep 23, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [2c385e1a66](https://linux-hardware.org/?probe=2c385e1a66) | Sep 20, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1699708a5b](https://linux-hardware.org/?probe=1699708a5b) | Sep 20, 2020 |
| Kiano         | IntelectX3HD+               | Tablet      | [378da04daa](https://linux-hardware.org/?probe=378da04daa) | Sep 20, 2020 |
| ASRock        | 980DE3/U3S3 R2.0            | Desktop     | [8bfe52a7d7](https://linux-hardware.org/?probe=8bfe52a7d7) | Sep 19, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2f26cddf81](https://linux-hardware.org/?probe=2f26cddf81) | Sep 19, 2020 |
| HP            | 843F                        | Desktop     | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [440e2b757b](https://linux-hardware.org/?probe=440e2b757b) | Sep 18, 2020 |
| ASUSTek       | X202E                       | Notebook    | [e9e1d090a6](https://linux-hardware.org/?probe=e9e1d090a6) | Sep 17, 2020 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [c5a9bb91be](https://linux-hardware.org/?probe=c5a9bb91be) | Sep 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [2399ed18fd](https://linux-hardware.org/?probe=2399ed18fd) | Sep 14, 2020 |
| Panasonic     | CF-NX2LDHTS                 | Notebook    | [0a48a263df](https://linux-hardware.org/?probe=0a48a263df) | Sep 13, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [d7d1e754de](https://linux-hardware.org/?probe=d7d1e754de) | Sep 13, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [18a6803124](https://linux-hardware.org/?probe=18a6803124) | Sep 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [5111093893](https://linux-hardware.org/?probe=5111093893) | Sep 10, 2020 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [9ccc9861eb](https://linux-hardware.org/?probe=9ccc9861eb) | Sep 10, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [df6578f3e9](https://linux-hardware.org/?probe=df6578f3e9) | Sep 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d2c7725115](https://linux-hardware.org/?probe=d2c7725115) | Sep 06, 2020 |
| Lenovo        | B50-80 80EW                 | Notebook    | [d29a056568](https://linux-hardware.org/?probe=d29a056568) | Sep 05, 2020 |
| Dell          | Latitude 3400               | Notebook    | [e1a6c8dd9b](https://linux-hardware.org/?probe=e1a6c8dd9b) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 4291B66       | Notebook    | [2f215c5090](https://linux-hardware.org/?probe=2f215c5090) | Sep 03, 2020 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [63815ec19a](https://linux-hardware.org/?probe=63815ec19a) | Sep 03, 2020 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [bcc958126a](https://linux-hardware.org/?probe=bcc958126a) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [0295f343f4](https://linux-hardware.org/?probe=0295f343f4) | Sep 03, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [9372f4dfac](https://linux-hardware.org/?probe=9372f4dfac) | Sep 03, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [1563288867](https://linux-hardware.org/?probe=1563288867) | Sep 03, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [1975c693cb](https://linux-hardware.org/?probe=1975c693cb) | Sep 02, 2020 |
| Dell          | Latitude E5420              | Notebook    | [e384c49b73](https://linux-hardware.org/?probe=e384c49b73) | Sep 02, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [e3ff6fe1b2](https://linux-hardware.org/?probe=e3ff6fe1b2) | Sep 01, 2020 |
| Lenovo        | G580 20150                  | Notebook    | [0615cf6255](https://linux-hardware.org/?probe=0615cf6255) | Aug 30, 2020 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b48f1779ec](https://linux-hardware.org/?probe=b48f1779ec) | Aug 30, 2020 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [f5f3758bed](https://linux-hardware.org/?probe=f5f3758bed) | Aug 30, 2020 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [e53f585923](https://linux-hardware.org/?probe=e53f585923) | Aug 30, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [557964d138](https://linux-hardware.org/?probe=557964d138) | Aug 29, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [37dc85cc8b](https://linux-hardware.org/?probe=37dc85cc8b) | Aug 29, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [91d1161c68](https://linux-hardware.org/?probe=91d1161c68) | Aug 28, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [02f4a89992](https://linux-hardware.org/?probe=02f4a89992) | Aug 28, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [129e313b94](https://linux-hardware.org/?probe=129e313b94) | Aug 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | Notebook    | [82eff7291c](https://linux-hardware.org/?probe=82eff7291c) | Aug 28, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [70559c8ed2](https://linux-hardware.org/?probe=70559c8ed2) | Aug 28, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [09562f975b](https://linux-hardware.org/?probe=09562f975b) | Aug 28, 2020 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [4d58eb3965](https://linux-hardware.org/?probe=4d58eb3965) | Aug 27, 2020 |
| Dell          | Latitude 5401               | Notebook    | [fdb1d25e99](https://linux-hardware.org/?probe=fdb1d25e99) | Aug 27, 2020 |
| MSI           | A320M PRO-VD/S              | Desktop     | [febc06a11a](https://linux-hardware.org/?probe=febc06a11a) | Aug 25, 2020 |
| HP            | Presario CQ61               | Notebook    | [109f1ed355](https://linux-hardware.org/?probe=109f1ed355) | Aug 24, 2020 |
| Sony          | VGN-FW31J                   | Notebook    | [529ce44f71](https://linux-hardware.org/?probe=529ce44f71) | Aug 24, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e7c4cf1576](https://linux-hardware.org/?probe=e7c4cf1576) | Aug 23, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| Dell          | 073MMW A01                  | Desktop     | [c9cc3e1a0f](https://linux-hardware.org/?probe=c9cc3e1a0f) | Aug 20, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [51ef1db220](https://linux-hardware.org/?probe=51ef1db220) | Aug 20, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [9754808d3d](https://linux-hardware.org/?probe=9754808d3d) | Aug 20, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [a178b4c510](https://linux-hardware.org/?probe=a178b4c510) | Aug 18, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [177085a712](https://linux-hardware.org/?probe=177085a712) | Aug 18, 2020 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [66477c8d6d](https://linux-hardware.org/?probe=66477c8d6d) | Aug 16, 2020 |
| Sony          | VGN-FW31J                   | Notebook    | [d8328832cd](https://linux-hardware.org/?probe=d8328832cd) | Aug 15, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [22fb77a6ee](https://linux-hardware.org/?probe=22fb77a6ee) | Aug 14, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [6b1a65c794](https://linux-hardware.org/?probe=6b1a65c794) | Aug 13, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7b143c1637](https://linux-hardware.org/?probe=7b143c1637) | Aug 13, 2020 |
| Lenovo        | ThinkPad P51 20HHS16Q00     | Notebook    | [6742184806](https://linux-hardware.org/?probe=6742184806) | Aug 12, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [fafcd60747](https://linux-hardware.org/?probe=fafcd60747) | Aug 12, 2020 |
| Bluechip C... | Crestline & ICH8M Chipse... | Notebook    | [9b8c4353cc](https://linux-hardware.org/?probe=9b8c4353cc) | Aug 09, 2020 |
| HP            | 806A                        | Desktop     | [9b5a07dcd9](https://linux-hardware.org/?probe=9b5a07dcd9) | Aug 08, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [3790f3b233](https://linux-hardware.org/?probe=3790f3b233) | Aug 07, 2020 |
| DATABOX       | BusinessTab A10             | Notebook    | [40935402ee](https://linux-hardware.org/?probe=40935402ee) | Aug 06, 2020 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [b9fddd15e8](https://linux-hardware.org/?probe=b9fddd15e8) | Aug 05, 2020 |
| AMI           | Intel                       | Notebook    | [0158c3e564](https://linux-hardware.org/?probe=0158c3e564) | Aug 05, 2020 |
| DATABOX       | BusinessTab A10             | Notebook    | [3c57bb6b77](https://linux-hardware.org/?probe=3c57bb6b77) | Aug 05, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [62f9d9cc6b](https://linux-hardware.org/?probe=62f9d9cc6b) | Aug 03, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [4eb7fb1ff6](https://linux-hardware.org/?probe=4eb7fb1ff6) | Jul 30, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [f946f61a7b](https://linux-hardware.org/?probe=f946f61a7b) | Jul 29, 2020 |
| Intel         | DCP847SKE G80890-104        | Desktop     | [33d9cddf98](https://linux-hardware.org/?probe=33d9cddf98) | Jul 28, 2020 |
| HP            | 1495                        | Desktop     | [8a51ce66a3](https://linux-hardware.org/?probe=8a51ce66a3) | Jul 27, 2020 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [f37d0fb96a](https://linux-hardware.org/?probe=f37d0fb96a) | Jul 26, 2020 |
| Acer          | Aspire one                  | Notebook    | [7b088b2172](https://linux-hardware.org/?probe=7b088b2172) | Jul 25, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [87d5cec59e](https://linux-hardware.org/?probe=87d5cec59e) | Jul 25, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [31e73b2be3](https://linux-hardware.org/?probe=31e73b2be3) | Jul 25, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [902de9f2a2](https://linux-hardware.org/?probe=902de9f2a2) | Jul 23, 2020 |
| ASUSTek       | UX303UB                     | Notebook    | [09c02580de](https://linux-hardware.org/?probe=09c02580de) | Jul 23, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [95225ea41e](https://linux-hardware.org/?probe=95225ea41e) | Jul 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [20568abfd1](https://linux-hardware.org/?probe=20568abfd1) | Jul 22, 2020 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e7f8121d46](https://linux-hardware.org/?probe=e7f8121d46) | Jul 22, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [683c0937ec](https://linux-hardware.org/?probe=683c0937ec) | Jul 21, 2020 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [6de4bc2195](https://linux-hardware.org/?probe=6de4bc2195) | Jul 21, 2020 |
| Intel         | DG33TL AAD89517-803         | Desktop     | [b50a829b37](https://linux-hardware.org/?probe=b50a829b37) | Jul 19, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2541c55ef9](https://linux-hardware.org/?probe=2541c55ef9) | Jul 18, 2020 |
| Sony          | VGN-FW21M                   | Notebook    | [d1010c28c7](https://linux-hardware.org/?probe=d1010c28c7) | Jul 18, 2020 |
| Dell          | Latitude 5401               | Notebook    | [31ac483afd](https://linux-hardware.org/?probe=31ac483afd) | Jul 18, 2020 |
| Lenovo        | ThinkPad T420 4180B12       | Notebook    | [8d78aded6b](https://linux-hardware.org/?probe=8d78aded6b) | Jul 17, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [300e34bdff](https://linux-hardware.org/?probe=300e34bdff) | Jul 17, 2020 |
| HP            | 843F                        | Desktop     | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2a545cac20](https://linux-hardware.org/?probe=2a545cac20) | Jul 16, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [7e5966439c](https://linux-hardware.org/?probe=7e5966439c) | Jul 16, 2020 |
| HP            | Presario CQ61               | Notebook    | [3471fd4461](https://linux-hardware.org/?probe=3471fd4461) | Jul 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| Dell          | Latitude 5401               | Notebook    | [d5cde026f3](https://linux-hardware.org/?probe=d5cde026f3) | Jul 14, 2020 |
| Acer          | Aspire 5930                 | Notebook    | [cf11228939](https://linux-hardware.org/?probe=cf11228939) | Jul 13, 2020 |
| Dell          | Latitude E7440              | Notebook    | [aec15e23f5](https://linux-hardware.org/?probe=aec15e23f5) | Jul 12, 2020 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [7e2596c52f](https://linux-hardware.org/?probe=7e2596c52f) | Jul 12, 2020 |
| Dell          | Latitude 5401               | Notebook    | [98717741ba](https://linux-hardware.org/?probe=98717741ba) | Jul 11, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [20b96fb678](https://linux-hardware.org/?probe=20b96fb678) | Jul 11, 2020 |
| MSI           | MS-7061                     | Desktop     | [ec0257fb90](https://linux-hardware.org/?probe=ec0257fb90) | Jul 11, 2020 |
| MSI           | MS-7061                     | Desktop     | [5c76906c4c](https://linux-hardware.org/?probe=5c76906c4c) | Jul 11, 2020 |
| Packard Be... | PT890-8237A                 | Desktop     | [089d020111](https://linux-hardware.org/?probe=089d020111) | Jul 08, 2020 |
| ICP / iEi     | AFLMB-9652 V1.00            | All in one  | [ca755b34fd](https://linux-hardware.org/?probe=ca755b34fd) | Jul 05, 2020 |
| ICP / iEi     | AFLMB-9652 V1.00            | All in one  | [d2873ee26f](https://linux-hardware.org/?probe=d2873ee26f) | Jul 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [32cb4f1652](https://linux-hardware.org/?probe=32cb4f1652) | Jul 04, 2020 |
| Intel         | DG33TL AAD89517-803         | Desktop     | [5b3d9f328a](https://linux-hardware.org/?probe=5b3d9f328a) | Jul 03, 2020 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f033f59c7f](https://linux-hardware.org/?probe=f033f59c7f) | Jul 03, 2020 |
| Intel         | DG33TL AAD89517-803         | Desktop     | [2b1fcc4155](https://linux-hardware.org/?probe=2b1fcc4155) | Jul 03, 2020 |
| Acer          | Extensa 5235                | Notebook    | [50f85b5c1d](https://linux-hardware.org/?probe=50f85b5c1d) | Jul 03, 2020 |
| Acer          | Extensa 5235                | Notebook    | [d03201b49a](https://linux-hardware.org/?probe=d03201b49a) | Jul 03, 2020 |
| MSI           | GF63 8RC                    | Notebook    | [080ebd9b80](https://linux-hardware.org/?probe=080ebd9b80) | Jul 02, 2020 |
| MSI           | GF63 8RC                    | Notebook    | [14e7833eea](https://linux-hardware.org/?probe=14e7833eea) | Jul 02, 2020 |
| ASUSTek       | P5K-E                       | Desktop     | [5923c246c4](https://linux-hardware.org/?probe=5923c246c4) | Jun 30, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [0f6ba1b2e7](https://linux-hardware.org/?probe=0f6ba1b2e7) | Jun 29, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [28e120bcfc](https://linux-hardware.org/?probe=28e120bcfc) | Jun 29, 2020 |
| Lenovo        | ThinkPad E580 20KS006AMC    | Notebook    | [1e8b0ede4b](https://linux-hardware.org/?probe=1e8b0ede4b) | Jun 29, 2020 |
| Acer          | Predator G5-793             | Notebook    | [83238b7fee](https://linux-hardware.org/?probe=83238b7fee) | Jun 28, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [51b7fb4eed](https://linux-hardware.org/?probe=51b7fb4eed) | Jun 28, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [dcdaf862fd](https://linux-hardware.org/?probe=dcdaf862fd) | Jun 28, 2020 |
| ASRock        | 970M Pro3                   | Desktop     | [98ee7025f4](https://linux-hardware.org/?probe=98ee7025f4) | Jun 27, 2020 |
| Acer          | EM61SM/EM61PM               | Desktop     | [c7523734df](https://linux-hardware.org/?probe=c7523734df) | Jun 26, 2020 |
| HP            | ProLiant DL380e Gen8        | Server      | [1e7a730fcc](https://linux-hardware.org/?probe=1e7a730fcc) | Jun 25, 2020 |
| HP            | ProLiant DL380e Gen8        | Server      | [bc37531931](https://linux-hardware.org/?probe=bc37531931) | Jun 25, 2020 |
| HP            | ProLiant DL380e Gen8        | Server      | [7edb6de577](https://linux-hardware.org/?probe=7edb6de577) | Jun 25, 2020 |
| HP            | ProLiant DL380e Gen8        | Server      | [0e6067d550](https://linux-hardware.org/?probe=0e6067d550) | Jun 25, 2020 |
| HP            | ProLiant DL380e Gen8        | Server      | [4049cb19c5](https://linux-hardware.org/?probe=4049cb19c5) | Jun 25, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [f31e3e1831](https://linux-hardware.org/?probe=f31e3e1831) | Jun 24, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [b5cf346e5d](https://linux-hardware.org/?probe=b5cf346e5d) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Gigabyte      | H55M-USB3                   | Desktop     | [6e57629563](https://linux-hardware.org/?probe=6e57629563) | Jun 22, 2020 |
| ASUSTek       | G750JX                      | Notebook    | [f13199ca2e](https://linux-hardware.org/?probe=f13199ca2e) | Jun 22, 2020 |
| Acer          | Aspire 5310                 | Notebook    | [08abc8a867](https://linux-hardware.org/?probe=08abc8a867) | Jun 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5b3ce338db](https://linux-hardware.org/?probe=5b3ce338db) | Jun 21, 2020 |
| Sony          | VPCEH2J1E                   | Notebook    | [5cc5278df7](https://linux-hardware.org/?probe=5cc5278df7) | Jun 21, 2020 |
| IBM           | ThinkPad T42 2374Q16        | Notebook    | [58f9ce5671](https://linux-hardware.org/?probe=58f9ce5671) | Jun 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [6f425e04b7](https://linux-hardware.org/?probe=6f425e04b7) | Jun 20, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [a75d5e3368](https://linux-hardware.org/?probe=a75d5e3368) | Jun 20, 2020 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [7793dd92b0](https://linux-hardware.org/?probe=7793dd92b0) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f6cfdc816b](https://linux-hardware.org/?probe=f6cfdc816b) | Jun 20, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [b90590bf42](https://linux-hardware.org/?probe=b90590bf42) | Jun 19, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d9f9497fd7](https://linux-hardware.org/?probe=d9f9497fd7) | Jun 19, 2020 |
| HP            | 15                          | Notebook    | [72292536fc](https://linux-hardware.org/?probe=72292536fc) | Jun 18, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| ASUSTek       | A55BM-E                     | Desktop     | [ff4c765cf8](https://linux-hardware.org/?probe=ff4c765cf8) | Jun 15, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [fa273cd6e3](https://linux-hardware.org/?probe=fa273cd6e3) | Jun 14, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [bdbf5c3068](https://linux-hardware.org/?probe=bdbf5c3068) | Jun 14, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [65159c7bfd](https://linux-hardware.org/?probe=65159c7bfd) | Jun 14, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [43d3a1e357](https://linux-hardware.org/?probe=43d3a1e357) | Jun 14, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| HP            | 1495                        | Desktop     | [c9c1099add](https://linux-hardware.org/?probe=c9c1099add) | Jun 12, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [244e7941f0](https://linux-hardware.org/?probe=244e7941f0) | Jun 12, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [92527e490f](https://linux-hardware.org/?probe=92527e490f) | Jun 11, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [62b8ebc9dc](https://linux-hardware.org/?probe=62b8ebc9dc) | Jun 11, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [aae53d6154](https://linux-hardware.org/?probe=aae53d6154) | Jun 09, 2020 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [d65021b09d](https://linux-hardware.org/?probe=d65021b09d) | Jun 09, 2020 |
| Acer          | Aspire V3-112P              | Notebook    | [9a6e18cb80](https://linux-hardware.org/?probe=9a6e18cb80) | Jun 08, 2020 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [1d365cfa28](https://linux-hardware.org/?probe=1d365cfa28) | Jun 08, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | Notebook    | [2902bb9460](https://linux-hardware.org/?probe=2902bb9460) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | Notebook    | [065bddf59b](https://linux-hardware.org/?probe=065bddf59b) | Jun 06, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [0d9a285392](https://linux-hardware.org/?probe=0d9a285392) | Jun 05, 2020 |
| Acer          | Aspire 5530                 | Notebook    | [ebb35f1079](https://linux-hardware.org/?probe=ebb35f1079) | Jun 05, 2020 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [146b8e892a](https://linux-hardware.org/?probe=146b8e892a) | Jun 05, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [efa1beda42](https://linux-hardware.org/?probe=efa1beda42) | Jun 04, 2020 |
| ASUSTek       | X555LD                      | Notebook    | [5fcb4e6866](https://linux-hardware.org/?probe=5fcb4e6866) | Jun 03, 2020 |
| Acer          | Aspire V3-551G              | Notebook    | [e205e6c135](https://linux-hardware.org/?probe=e205e6c135) | Jun 03, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [a84d2b6813](https://linux-hardware.org/?probe=a84d2b6813) | May 31, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [ee9f7329ff](https://linux-hardware.org/?probe=ee9f7329ff) | May 31, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [911a12baa7](https://linux-hardware.org/?probe=911a12baa7) | May 31, 2020 |
| Lenovo        | ThinkPad T490 20N2S03R00    | Notebook    | [707f01ab45](https://linux-hardware.org/?probe=707f01ab45) | May 30, 2020 |
| ASUSTek       | T102HA                      | Tablet      | [43ba03faf3](https://linux-hardware.org/?probe=43ba03faf3) | May 30, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [5d11e43736](https://linux-hardware.org/?probe=5d11e43736) | May 30, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a25818fe46](https://linux-hardware.org/?probe=a25818fe46) | May 30, 2020 |
| Acer          | Aspire XC-830               | Desktop     | [b260486efb](https://linux-hardware.org/?probe=b260486efb) | May 29, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6289a0fd13](https://linux-hardware.org/?probe=6289a0fd13) | May 28, 2020 |
| Acer          | Aspire XC-830               | Desktop     | [90501ddf39](https://linux-hardware.org/?probe=90501ddf39) | May 27, 2020 |
| Acer          | Aspire XC-830               | Desktop     | [bb81a1b4c7](https://linux-hardware.org/?probe=bb81a1b4c7) | May 27, 2020 |
| ASUSTek       | A7Sv                        | Notebook    | [785a42eb5b](https://linux-hardware.org/?probe=785a42eb5b) | May 27, 2020 |
| ASUSTek       | A7Sv                        | Notebook    | [a820cc1186](https://linux-hardware.org/?probe=a820cc1186) | May 27, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [d2f6e88d35](https://linux-hardware.org/?probe=d2f6e88d35) | May 26, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8f5cbe37da](https://linux-hardware.org/?probe=8f5cbe37da) | May 26, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [396660cc0e](https://linux-hardware.org/?probe=396660cc0e) | May 26, 2020 |
| ASUSTek       | P5QL PRO                    | Desktop     | [cd5a927598](https://linux-hardware.org/?probe=cd5a927598) | May 26, 2020 |
| ASRock        | Z97 Anniversary             | Desktop     | [9182b64cda](https://linux-hardware.org/?probe=9182b64cda) | May 25, 2020 |
| MSI           | PS63 Modern 8M              | Notebook    | [a0f30a47ee](https://linux-hardware.org/?probe=a0f30a47ee) | May 24, 2020 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [37c69ea279](https://linux-hardware.org/?probe=37c69ea279) | May 24, 2020 |
| Lenovo        | ThinkPad E480 20KN001NMC    | Notebook    | [1dcc1bede5](https://linux-hardware.org/?probe=1dcc1bede5) | May 24, 2020 |
| Acer          | Aspire A315-32              | Notebook    | [ce0e45003c](https://linux-hardware.org/?probe=ce0e45003c) | May 24, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d8ecbfe382](https://linux-hardware.org/?probe=d8ecbfe382) | May 23, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [e02d9dc211](https://linux-hardware.org/?probe=e02d9dc211) | May 23, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [b0deaea4a8](https://linux-hardware.org/?probe=b0deaea4a8) | May 22, 2020 |
| Sony          | VPCEB3S1E                   | Notebook    | [14c94e8a5d](https://linux-hardware.org/?probe=14c94e8a5d) | May 22, 2020 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [b51348e9b8](https://linux-hardware.org/?probe=b51348e9b8) | May 22, 2020 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [e25ab96f44](https://linux-hardware.org/?probe=e25ab96f44) | May 22, 2020 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [4a5ed96b1d](https://linux-hardware.org/?probe=4a5ed96b1d) | May 22, 2020 |
| Dell          | Vostro 5568                 | Notebook    | [be3b19e976](https://linux-hardware.org/?probe=be3b19e976) | May 20, 2020 |
| IBM           | I/O Port                    | Server      | [7c109612b9](https://linux-hardware.org/?probe=7c109612b9) | May 20, 2020 |
| ASUSTek       | M2N-CM DVI                  | Desktop     | [e2c38feac9](https://linux-hardware.org/?probe=e2c38feac9) | May 19, 2020 |
| Dell          | Latitude E7450              | Notebook    | [3d80b3ce29](https://linux-hardware.org/?probe=3d80b3ce29) | May 19, 2020 |
| Dell          | Latitude 5500               | Notebook    | [2264b71779](https://linux-hardware.org/?probe=2264b71779) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| Dell          | Latitude 5500               | Notebook    | [57af2e8877](https://linux-hardware.org/?probe=57af2e8877) | May 19, 2020 |
| HP            | 304Ah                       | Desktop     | [c27cabd96c](https://linux-hardware.org/?probe=c27cabd96c) | May 19, 2020 |
| HP            | 304Ah                       | Desktop     | [c6d530a3fb](https://linux-hardware.org/?probe=c6d530a3fb) | May 19, 2020 |
| ASRock        | B75M-GL R2.0                | Desktop     | [5d07d6db8e](https://linux-hardware.org/?probe=5d07d6db8e) | May 17, 2020 |
| ASUSTek       | A6R                         | Notebook    | [233eb1cb5a](https://linux-hardware.org/?probe=233eb1cb5a) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [96677ee210](https://linux-hardware.org/?probe=96677ee210) | May 16, 2020 |
| HP            | ProBook 655 G1              | Notebook    | [b692081c5e](https://linux-hardware.org/?probe=b692081c5e) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [15d0451825](https://linux-hardware.org/?probe=15d0451825) | May 16, 2020 |
| ASUSTek       | A6R                         | Notebook    | [5336380e70](https://linux-hardware.org/?probe=5336380e70) | May 16, 2020 |
| ASUSTek       | A6R                         | Notebook    | [b8bb81dd95](https://linux-hardware.org/?probe=b8bb81dd95) | May 16, 2020 |
| ASUSTek       | A6R                         | Notebook    | [6253744b9d](https://linux-hardware.org/?probe=6253744b9d) | May 16, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [453202ad57](https://linux-hardware.org/?probe=453202ad57) | May 15, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [99e7ac6aa7](https://linux-hardware.org/?probe=99e7ac6aa7) | May 15, 2020 |
| HP            | EliteBook 745 G6            | Notebook    | [3ae8a35f34](https://linux-hardware.org/?probe=3ae8a35f34) | May 15, 2020 |
| Gigabyte      | M61SME-S2                   | Desktop     | [bd4b1dc757](https://linux-hardware.org/?probe=bd4b1dc757) | May 12, 2020 |
| Dell          | Precision 5530              | Notebook    | [4cdc8a6d48](https://linux-hardware.org/?probe=4cdc8a6d48) | May 12, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [74b2ff5470](https://linux-hardware.org/?probe=74b2ff5470) | May 12, 2020 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [1523e8f4a8](https://linux-hardware.org/?probe=1523e8f4a8) | May 11, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [56fbe252d0](https://linux-hardware.org/?probe=56fbe252d0) | May 11, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [709526e6b6](https://linux-hardware.org/?probe=709526e6b6) | May 10, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [6d6afe11e6](https://linux-hardware.org/?probe=6d6afe11e6) | May 10, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [c2edd5fbaf](https://linux-hardware.org/?probe=c2edd5fbaf) | May 09, 2020 |
| HP            | ProBook 655 G1              | Notebook    | [7260da6e47](https://linux-hardware.org/?probe=7260da6e47) | May 09, 2020 |
| Google        | Eve                         | Convertible | [5f781e103c](https://linux-hardware.org/?probe=5f781e103c) | May 07, 2020 |
| Dell          | Latitude 5401               | Notebook    | [051cf9ab6f](https://linux-hardware.org/?probe=051cf9ab6f) | May 05, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [324efc564b](https://linux-hardware.org/?probe=324efc564b) | May 05, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [b225d7378d](https://linux-hardware.org/?probe=b225d7378d) | May 04, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ada5fbf86d](https://linux-hardware.org/?probe=ada5fbf86d) | May 03, 2020 |
| Lenovo        | ThinkPad X131e 3368A77      | Notebook    | [c376fe66df](https://linux-hardware.org/?probe=c376fe66df) | May 03, 2020 |
| HP            | Notebook                    | Notebook    | [44e80e2be4](https://linux-hardware.org/?probe=44e80e2be4) | May 02, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e60aeab4a5](https://linux-hardware.org/?probe=e60aeab4a5) | May 02, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [bbcfbdb441](https://linux-hardware.org/?probe=bbcfbdb441) | May 02, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [88fa9aea33](https://linux-hardware.org/?probe=88fa9aea33) | May 01, 2020 |
| HP            | Notebook                    | Notebook    | [f423ba2d9f](https://linux-hardware.org/?probe=f423ba2d9f) | May 01, 2020 |
| MSI           | MS-7507                     | Desktop     | [120f09865e](https://linux-hardware.org/?probe=120f09865e) | Apr 30, 2020 |
| Dell          | Latitude E6420              | Notebook    | [8adb8146f8](https://linux-hardware.org/?probe=8adb8146f8) | Apr 30, 2020 |
| Dell          | Latitude E6420              | Notebook    | [c5901834f5](https://linux-hardware.org/?probe=c5901834f5) | Apr 30, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [87a660b2af](https://linux-hardware.org/?probe=87a660b2af) | Apr 30, 2020 |
| Gigabyte      | N3050ND3H                   | Desktop     | [3f7cfb988e](https://linux-hardware.org/?probe=3f7cfb988e) | Apr 29, 2020 |
| Lenovo        | IdeaPad Y580                | Notebook    | [147e7ec673](https://linux-hardware.org/?probe=147e7ec673) | Apr 29, 2020 |
| Acer          | EM61SM/EM61PM               | Desktop     | [94e7ff927b](https://linux-hardware.org/?probe=94e7ff927b) | Apr 27, 2020 |
| Acer          | EM61SM/EM61PM               | Desktop     | [8b0fba21d2](https://linux-hardware.org/?probe=8b0fba21d2) | Apr 27, 2020 |
| Dell          | Latitude E5520              | Notebook    | [36e044faf3](https://linux-hardware.org/?probe=36e044faf3) | Apr 26, 2020 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [b0e15a571e](https://linux-hardware.org/?probe=b0e15a571e) | Apr 26, 2020 |
| Dell          | Inspiron 5593               | Notebook    | [85d76a23e6](https://linux-hardware.org/?probe=85d76a23e6) | Apr 26, 2020 |
| Dell          | Latitude E6400              | Notebook    | [a4ed50bb29](https://linux-hardware.org/?probe=a4ed50bb29) | Apr 26, 2020 |
| MSI           | B360M MORTAR                | Desktop     | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| Lenovo        | ThinkPad R61 8933W6M        | Notebook    | [5fb1e739a2](https://linux-hardware.org/?probe=5fb1e739a2) | Apr 26, 2020 |
| HP            | 339A                        | Desktop     | [a4b2a57cc3](https://linux-hardware.org/?probe=a4b2a57cc3) | Apr 25, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [bc9a01a10e](https://linux-hardware.org/?probe=bc9a01a10e) | Apr 24, 2020 |
| Lenovo        | ThinkPad R61 8933W6M        | Notebook    | [536beaf5b9](https://linux-hardware.org/?probe=536beaf5b9) | Apr 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [87b901a1b9](https://linux-hardware.org/?probe=87b901a1b9) | Apr 23, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [ffe9b12dd4](https://linux-hardware.org/?probe=ffe9b12dd4) | Apr 23, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2d8aac7989](https://linux-hardware.org/?probe=2d8aac7989) | Apr 21, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1a161abbf2](https://linux-hardware.org/?probe=1a161abbf2) | Apr 21, 2020 |
| MSI           | MS-7267                     | Desktop     | [678e22693c](https://linux-hardware.org/?probe=678e22693c) | Apr 21, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [a1227639ac](https://linux-hardware.org/?probe=a1227639ac) | Apr 20, 2020 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [a1ba861a3d](https://linux-hardware.org/?probe=a1ba861a3d) | Apr 20, 2020 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [695ccb4b40](https://linux-hardware.org/?probe=695ccb4b40) | Apr 18, 2020 |
| ASUSTek       | P43SJ                       | Notebook    | [43a6fcc05e](https://linux-hardware.org/?probe=43a6fcc05e) | Apr 18, 2020 |
| Intel         | DP35DP AAD81073-207         | Desktop     | [43157cc32b](https://linux-hardware.org/?probe=43157cc32b) | Apr 18, 2020 |
| Lenovo        | IdeaPad Y580                | Notebook    | [07c55f3d7b](https://linux-hardware.org/?probe=07c55f3d7b) | Apr 17, 2020 |
| Lenovo        | IdeaPad Y580                | Notebook    | [4f7c17303a](https://linux-hardware.org/?probe=4f7c17303a) | Apr 16, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4998a5a5b5](https://linux-hardware.org/?probe=4998a5a5b5) | Apr 15, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [fcc4ad36bb](https://linux-hardware.org/?probe=fcc4ad36bb) | Apr 13, 2020 |
| Lenovo        | G40-45 80E1                 | Notebook    | [218110c7a1](https://linux-hardware.org/?probe=218110c7a1) | Apr 13, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [3c52d09634](https://linux-hardware.org/?probe=3c52d09634) | Apr 12, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [5817c93bd7](https://linux-hardware.org/?probe=5817c93bd7) | Apr 12, 2020 |
| ASUSTek       | A6R                         | Notebook    | [e298b642f1](https://linux-hardware.org/?probe=e298b642f1) | Apr 11, 2020 |
| UMAX          | VisionBook 14Wg Pro         | Notebook    | [7a1832a78f](https://linux-hardware.org/?probe=7a1832a78f) | Apr 11, 2020 |
| Dynabook      | PORTEGE X30-F               | Notebook    | [6b0ed71af5](https://linux-hardware.org/?probe=6b0ed71af5) | Apr 09, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7153cca02a](https://linux-hardware.org/?probe=7153cca02a) | Apr 07, 2020 |
| Acer          | Aspire 1410                 | Notebook    | [6cba695c63](https://linux-hardware.org/?probe=6cba695c63) | Apr 06, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [64f6604a82](https://linux-hardware.org/?probe=64f6604a82) | Apr 06, 2020 |
| Lenovo        | ThinkPad T510 4384Y13       | Notebook    | [327f86287f](https://linux-hardware.org/?probe=327f86287f) | Apr 06, 2020 |
| Lenovo        | ThinkPad T510 4384Y13       | Notebook    | [cb50b8f064](https://linux-hardware.org/?probe=cb50b8f064) | Apr 06, 2020 |
| MSI           | B150 GAMING M3              | Desktop     | [c5221a134d](https://linux-hardware.org/?probe=c5221a134d) | Apr 06, 2020 |
| MSI           | B150 GAMING M3              | Desktop     | [4d2bcc0613](https://linux-hardware.org/?probe=4d2bcc0613) | Apr 06, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [399229abd3](https://linux-hardware.org/?probe=399229abd3) | Apr 05, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [cd2c9976bc](https://linux-hardware.org/?probe=cd2c9976bc) | Apr 05, 2020 |
| Lenovo        | G40-45 80E1                 | Notebook    | [e34e785eb4](https://linux-hardware.org/?probe=e34e785eb4) | Apr 04, 2020 |
| Lenovo        | G40-45 80E1                 | Notebook    | [e3164413c4](https://linux-hardware.org/?probe=e3164413c4) | Apr 04, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [d556695db0](https://linux-hardware.org/?probe=d556695db0) | Apr 03, 2020 |
| HP            | Laptop 17-bs0xx             | Notebook    | [7ed301984e](https://linux-hardware.org/?probe=7ed301984e) | Apr 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| HP            | ProBook 4525s               | Notebook    | [cb0a6c08db](https://linux-hardware.org/?probe=cb0a6c08db) | Mar 31, 2020 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | Desktop     | [736d155f37](https://linux-hardware.org/?probe=736d155f37) | Mar 30, 2020 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | Desktop     | [b8b840e5a5](https://linux-hardware.org/?probe=b8b840e5a5) | Mar 30, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [4a2233bf6d](https://linux-hardware.org/?probe=4a2233bf6d) | Mar 29, 2020 |
| HP            | ProBook 4525s               | Notebook    | [dc9164d939](https://linux-hardware.org/?probe=dc9164d939) | Mar 28, 2020 |
| MSI           | MS-7357                     | Desktop     | [dd315713e7](https://linux-hardware.org/?probe=dd315713e7) | Mar 28, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ab1ea8323a](https://linux-hardware.org/?probe=ab1ea8323a) | Mar 27, 2020 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [7e177f1dae](https://linux-hardware.org/?probe=7e177f1dae) | Mar 26, 2020 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [79c8660f50](https://linux-hardware.org/?probe=79c8660f50) | Mar 26, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [c3ef67f0ed](https://linux-hardware.org/?probe=c3ef67f0ed) | Mar 25, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6188581fde](https://linux-hardware.org/?probe=6188581fde) | Mar 25, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [624e23640a](https://linux-hardware.org/?probe=624e23640a) | Mar 24, 2020 |
| Acer          | TravelMate 2490             | Notebook    | [00d179f01a](https://linux-hardware.org/?probe=00d179f01a) | Mar 23, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [029a5e5e9e](https://linux-hardware.org/?probe=029a5e5e9e) | Mar 23, 2020 |
| Intel         | DG43RK AAE78175-402         | Desktop     | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [788ddff20c](https://linux-hardware.org/?probe=788ddff20c) | Mar 22, 2020 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [3454a872c0](https://linux-hardware.org/?probe=3454a872c0) | Mar 22, 2020 |
| Acer          | TravelMate 5720             | Notebook    | [8c2056a761](https://linux-hardware.org/?probe=8c2056a761) | Mar 21, 2020 |
| Dell          | Inspiron 7347               | Notebook    | [77c2f26115](https://linux-hardware.org/?probe=77c2f26115) | Mar 20, 2020 |
| Lenovo        | 36F4 SDK0J40709 WIN 3259... | All in one  | [773be13aa2](https://linux-hardware.org/?probe=773be13aa2) | Mar 19, 2020 |
| Lenovo        | 36F4 SDK0J40709 WIN 3259... | All in one  | [b831a0abab](https://linux-hardware.org/?probe=b831a0abab) | Mar 19, 2020 |
| ASUSTek       | G73Jh                       | Notebook    | [8fab458245](https://linux-hardware.org/?probe=8fab458245) | Mar 18, 2020 |
| Lenovo        | ThinkPad X201 33238UG       | Notebook    | [ef40bcb4bd](https://linux-hardware.org/?probe=ef40bcb4bd) | Mar 18, 2020 |
| Gigabyte      | N3050ND3H                   | Desktop     | [9306c157ae](https://linux-hardware.org/?probe=9306c157ae) | Mar 16, 2020 |
| Acer          | Aspire ES1-711G             | Notebook    | [b34059b677](https://linux-hardware.org/?probe=b34059b677) | Mar 16, 2020 |
| ASUSTek       | K54C                        | Notebook    | [83b39008d5](https://linux-hardware.org/?probe=83b39008d5) | Mar 16, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [bfb2fb34f1](https://linux-hardware.org/?probe=bfb2fb34f1) | Mar 16, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [bbfa59e02d](https://linux-hardware.org/?probe=bbfa59e02d) | Mar 15, 2020 |
| HP            | Compaq 6715b (KE065EA#AK... | Notebook    | [6933f971d0](https://linux-hardware.org/?probe=6933f971d0) | Mar 14, 2020 |
| HP            | Compaq 6715b (KE065EA#AK... | Notebook    | [4f35448ece](https://linux-hardware.org/?probe=4f35448ece) | Mar 14, 2020 |
| HP            | Compaq 6715b (KE065EA#AK... | Notebook    | [6720a1a4dd](https://linux-hardware.org/?probe=6720a1a4dd) | Mar 14, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [e7634e66cc](https://linux-hardware.org/?probe=e7634e66cc) | Mar 14, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [857c21cba9](https://linux-hardware.org/?probe=857c21cba9) | Mar 13, 2020 |
| MSI           | H81M-P33                    | Desktop     | [6727ba0937](https://linux-hardware.org/?probe=6727ba0937) | Mar 12, 2020 |
| HP            | 843F                        | Desktop     | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| MSI           | NF520T-C35                  | Desktop     | [e9c434add5](https://linux-hardware.org/?probe=e9c434add5) | Mar 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6f3950f01a](https://linux-hardware.org/?probe=6f3950f01a) | Mar 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5aad033c6b](https://linux-hardware.org/?probe=5aad033c6b) | Mar 11, 2020 |
| Gigabyte      | N3050ND3H                   | Desktop     | [531eedbf04](https://linux-hardware.org/?probe=531eedbf04) | Mar 11, 2020 |
| MSI           | H81M-P33                    | Desktop     | [4fd88fa0cd](https://linux-hardware.org/?probe=4fd88fa0cd) | Mar 11, 2020 |
| ASUSTek       | X51R                        | Notebook    | [27bb6f3f14](https://linux-hardware.org/?probe=27bb6f3f14) | Mar 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [601a1539ce](https://linux-hardware.org/?probe=601a1539ce) | Mar 11, 2020 |
| HP            | 843F                        | Desktop     | [8e3653137c](https://linux-hardware.org/?probe=8e3653137c) | Mar 10, 2020 |
| ASUSTek       | G73Jh                       | Notebook    | [05775bfd66](https://linux-hardware.org/?probe=05775bfd66) | Mar 09, 2020 |
| HP            | ProBook 6570b               | Notebook    | [c6d9be95fe](https://linux-hardware.org/?probe=c6d9be95fe) | Mar 09, 2020 |
| HP            | ProBook 470 G2              | Notebook    | [8ded132046](https://linux-hardware.org/?probe=8ded132046) | Mar 09, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [fc5a75980b](https://linux-hardware.org/?probe=fc5a75980b) | Mar 07, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [f1f0d87afd](https://linux-hardware.org/?probe=f1f0d87afd) | Mar 06, 2020 |
| HP            | ProBook 4540s               | Notebook    | [492404a7b5](https://linux-hardware.org/?probe=492404a7b5) | Mar 06, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [93e8da5f2a](https://linux-hardware.org/?probe=93e8da5f2a) | Mar 06, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [033da87d24](https://linux-hardware.org/?probe=033da87d24) | Mar 06, 2020 |
| Acer          | Extensa 5635ZG              | Notebook    | [bfda801594](https://linux-hardware.org/?probe=bfda801594) | Mar 04, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [f61491f270](https://linux-hardware.org/?probe=f61491f270) | Mar 03, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [92032f62ef](https://linux-hardware.org/?probe=92032f62ef) | Mar 01, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [c2d4a2cffa](https://linux-hardware.org/?probe=c2d4a2cffa) | Mar 01, 2020 |
| ASUSTek       | G73Jh                       | Notebook    | [01afb8cba8](https://linux-hardware.org/?probe=01afb8cba8) | Mar 01, 2020 |
| Dell          | 0NW73C A00                  | Desktop     | [079032cab6](https://linux-hardware.org/?probe=079032cab6) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | Notebook    | [3e260beb60](https://linux-hardware.org/?probe=3e260beb60) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | Notebook    | [5c56805de1](https://linux-hardware.org/?probe=5c56805de1) | Feb 29, 2020 |
| Dell          | 0NW73C A00                  | Desktop     | [4f94baa369](https://linux-hardware.org/?probe=4f94baa369) | Feb 28, 2020 |
| Dell          | 0NW73C A00                  | Desktop     | [ee7108cb91](https://linux-hardware.org/?probe=ee7108cb91) | Feb 28, 2020 |
| Dell          | 0NW73C A00                  | Desktop     | [1cfd8f7014](https://linux-hardware.org/?probe=1cfd8f7014) | Feb 28, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMC    | Notebook    | [b511ab5202](https://linux-hardware.org/?probe=b511ab5202) | Feb 27, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3ab01ccb21](https://linux-hardware.org/?probe=3ab01ccb21) | Feb 26, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8474de61ef](https://linux-hardware.org/?probe=8474de61ef) | Feb 26, 2020 |
| Lenovo        | ThinkPad X270 20K5S0R100    | Notebook    | [50bddb4fd0](https://linux-hardware.org/?probe=50bddb4fd0) | Feb 26, 2020 |
| ASUSTek       | X555LD                      | Notebook    | [c3ba184dbb](https://linux-hardware.org/?probe=c3ba184dbb) | Feb 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [18b1fee704](https://linux-hardware.org/?probe=18b1fee704) | Feb 25, 2020 |
| ASUSTek       | CUSL2-M                     | Desktop     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [73e5d55bdb](https://linux-hardware.org/?probe=73e5d55bdb) | Feb 23, 2020 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [a221d53be6](https://linux-hardware.org/?probe=a221d53be6) | Feb 22, 2020 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [5bd0e60cb9](https://linux-hardware.org/?probe=5bd0e60cb9) | Feb 21, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [86b54afeaf](https://linux-hardware.org/?probe=86b54afeaf) | Feb 20, 2020 |
| Dell          | Precision 3530              | Notebook    | [a847df5d95](https://linux-hardware.org/?probe=a847df5d95) | Feb 20, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5986ac405a](https://linux-hardware.org/?probe=5986ac405a) | Feb 20, 2020 |
| Toshiba       | Satellite P70-A             | Notebook    | [c575900b39](https://linux-hardware.org/?probe=c575900b39) | Feb 19, 2020 |
| HP            | 1495                        | Desktop     | [ce0ebaa644](https://linux-hardware.org/?probe=ce0ebaa644) | Feb 16, 2020 |
| HP            | 1495                        | Desktop     | [e07a108e6f](https://linux-hardware.org/?probe=e07a108e6f) | Feb 16, 2020 |
| Dell          | Precision 5540              | Notebook    | [4e027cdac7](https://linux-hardware.org/?probe=4e027cdac7) | Feb 15, 2020 |
| Dell          | Precision M6500             | Notebook    | [71a22eff06](https://linux-hardware.org/?probe=71a22eff06) | Feb 15, 2020 |
| HP            | ProBook 6555b               | Notebook    | [786df34e10](https://linux-hardware.org/?probe=786df34e10) | Feb 12, 2020 |
| HP            | ProBook 6555b               | Notebook    | [b09d4a9a07](https://linux-hardware.org/?probe=b09d4a9a07) | Feb 12, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a84be71f79](https://linux-hardware.org/?probe=a84be71f79) | Feb 05, 2020 |
| ASUSTek       | N75SF                       | Notebook    | [708afdd130](https://linux-hardware.org/?probe=708afdd130) | Feb 05, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [58fbde79b5](https://linux-hardware.org/?probe=58fbde79b5) | Feb 04, 2020 |
| Gigabyte      | EP35-DS3                    | Desktop     | [5a3ef0f23c](https://linux-hardware.org/?probe=5a3ef0f23c) | Feb 03, 2020 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [9d5365623d](https://linux-hardware.org/?probe=9d5365623d) | Feb 03, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | Notebook    | [38058cfd32](https://linux-hardware.org/?probe=38058cfd32) | Feb 02, 2020 |
| Acer          | Aspire SW5-271              | Notebook    | [193ff2efc6](https://linux-hardware.org/?probe=193ff2efc6) | Jan 31, 2020 |
| Sony          | VPCEB3L1E                   | Notebook    | [157ce63cf3](https://linux-hardware.org/?probe=157ce63cf3) | Jan 30, 2020 |
| ASUSTek       | N73SV                       | Notebook    | [38f088b8c0](https://linux-hardware.org/?probe=38f088b8c0) | Jan 29, 2020 |
| Lenovo        | ThinkPad L480 20LS0017MC    | Notebook    | [55c9260451](https://linux-hardware.org/?probe=55c9260451) | Jan 29, 2020 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [503c223716](https://linux-hardware.org/?probe=503c223716) | Jan 28, 2020 |
| HP            | 806A                        | Desktop     | [bfc2676644](https://linux-hardware.org/?probe=bfc2676644) | Jan 26, 2020 |
| Sony          | VPCEA1S1E                   | Notebook    | [bcfcf8ae93](https://linux-hardware.org/?probe=bcfcf8ae93) | Jan 26, 2020 |
| Unknown       | V141                        | Notebook    | [d4b01fc8cb](https://linux-hardware.org/?probe=d4b01fc8cb) | Jan 26, 2020 |
| Alienware     | M17xR3                      | Notebook    | [4e9804e6ed](https://linux-hardware.org/?probe=4e9804e6ed) | Jan 24, 2020 |
| Supermicro    | X9SRL-F                     | Server      | [1ff0ee8759](https://linux-hardware.org/?probe=1ff0ee8759) | Jan 24, 2020 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [453ed2482f](https://linux-hardware.org/?probe=453ed2482f) | Jan 24, 2020 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [436f08bfd7](https://linux-hardware.org/?probe=436f08bfd7) | Jan 24, 2020 |
| Lenovo        | ThinkPad T490 20N2S2UH00    | Notebook    | [832335bf08](https://linux-hardware.org/?probe=832335bf08) | Jan 24, 2020 |
| ASUSTek       | K50C                        | Notebook    | [a8f036e32b](https://linux-hardware.org/?probe=a8f036e32b) | Jan 23, 2020 |
| ASUSTek       | K50C                        | Notebook    | [db872fd6b0](https://linux-hardware.org/?probe=db872fd6b0) | Jan 21, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [1c841791ef](https://linux-hardware.org/?probe=1c841791ef) | Jan 20, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [731e144435](https://linux-hardware.org/?probe=731e144435) | Jan 20, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [1edaf69823](https://linux-hardware.org/?probe=1edaf69823) | Jan 20, 2020 |
| Dell          | Precision M6500             | Notebook    | [2bce7c4d41](https://linux-hardware.org/?probe=2bce7c4d41) | Jan 19, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [80245136bd](https://linux-hardware.org/?probe=80245136bd) | Jan 18, 2020 |
| Dell          | G3 3779                     | Notebook    | [1a75467376](https://linux-hardware.org/?probe=1a75467376) | Jan 18, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [701f52dd25](https://linux-hardware.org/?probe=701f52dd25) | Jan 17, 2020 |
| Dell          | 0Y1057                      | Desktop     | [bf78aaecc3](https://linux-hardware.org/?probe=bf78aaecc3) | Jan 17, 2020 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [6c64315bcf](https://linux-hardware.org/?probe=6c64315bcf) | Jan 15, 2020 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [c570563513](https://linux-hardware.org/?probe=c570563513) | Jan 15, 2020 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [5173e103d5](https://linux-hardware.org/?probe=5173e103d5) | Jan 15, 2020 |
| HP            | EliteBook 735 G6            | Notebook    | [57d80b3164](https://linux-hardware.org/?probe=57d80b3164) | Jan 15, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [1c675dd7d7](https://linux-hardware.org/?probe=1c675dd7d7) | Jan 15, 2020 |
| Gigabyte      | EP45-DS4                    | Desktop     | [4bd613ef39](https://linux-hardware.org/?probe=4bd613ef39) | Jan 14, 2020 |
| Gigabyte      | EP45-DS4                    | Desktop     | [081fbf92ef](https://linux-hardware.org/?probe=081fbf92ef) | Jan 14, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [7c5c1cff72](https://linux-hardware.org/?probe=7c5c1cff72) | Jan 14, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [745edd74fb](https://linux-hardware.org/?probe=745edd74fb) | Jan 14, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [4a82019d80](https://linux-hardware.org/?probe=4a82019d80) | Jan 13, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2a51f23df2](https://linux-hardware.org/?probe=2a51f23df2) | Jan 13, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [dbace2bb0a](https://linux-hardware.org/?probe=dbace2bb0a) | Jan 13, 2020 |
| Sony          | VGN-FW31E                   | Notebook    | [754869cea8](https://linux-hardware.org/?probe=754869cea8) | Jan 13, 2020 |
| Sony          | VGN-FW31E                   | Notebook    | [b9a26f01e9](https://linux-hardware.org/?probe=b9a26f01e9) | Jan 13, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2f9a0ca1ce](https://linux-hardware.org/?probe=2f9a0ca1ce) | Jan 12, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2f98991cfb](https://linux-hardware.org/?probe=2f98991cfb) | Jan 12, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [d93b8a1a22](https://linux-hardware.org/?probe=d93b8a1a22) | Jan 12, 2020 |
| ASUSTek       | X540SC                      | Notebook    | [67a473453a](https://linux-hardware.org/?probe=67a473453a) | Jan 12, 2020 |
| ASUSTek       | X540SC                      | Notebook    | [083adaccfd](https://linux-hardware.org/?probe=083adaccfd) | Jan 12, 2020 |
| ASUSTek       | X540SC                      | Notebook    | [35892a76e9](https://linux-hardware.org/?probe=35892a76e9) | Jan 12, 2020 |
| ASUSTek       | P5K Premium                 | Desktop     | [8b39be3e8f](https://linux-hardware.org/?probe=8b39be3e8f) | Jan 10, 2020 |
| Dell          | 0Y1057                      | Desktop     | [6c5515c415](https://linux-hardware.org/?probe=6c5515c415) | Jan 10, 2020 |
| HP            | ZBook 15 G5                 | Notebook    | [09c73320da](https://linux-hardware.org/?probe=09c73320da) | Jan 08, 2020 |
| HP            | ProBook 4530s               | Notebook    | [371bf68041](https://linux-hardware.org/?probe=371bf68041) | Jan 07, 2020 |
| Acer          | Coniston                    | Notebook    | [239f09af80](https://linux-hardware.org/?probe=239f09af80) | Jan 05, 2020 |
| Dell          | Precision M6500             | Notebook    | [9cf869c61a](https://linux-hardware.org/?probe=9cf869c61a) | Jan 05, 2020 |
| ASUSTek       | K50C                        | Notebook    | [cd9b2523a4](https://linux-hardware.org/?probe=cd9b2523a4) | Jan 03, 2020 |
| Dell          | Precision M6500             | Notebook    | [c481909dee](https://linux-hardware.org/?probe=c481909dee) | Dec 31, 2019 |
| HP            | ProBook 6560b               | Notebook    | [354538a3e7](https://linux-hardware.org/?probe=354538a3e7) | Dec 29, 2019 |
| MSI           | MS-7366                     | Desktop     | [7b29163b46](https://linux-hardware.org/?probe=7b29163b46) | Dec 28, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [88f8ae0302](https://linux-hardware.org/?probe=88f8ae0302) | Dec 27, 2019 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [b470e45c2c](https://linux-hardware.org/?probe=b470e45c2c) | Dec 26, 2019 |
| Acer          | Aspire E3-111               | Notebook    | [f61e2d2b7b](https://linux-hardware.org/?probe=f61e2d2b7b) | Dec 26, 2019 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [832f6ef100](https://linux-hardware.org/?probe=832f6ef100) | Dec 25, 2019 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [49bc4a3291](https://linux-hardware.org/?probe=49bc4a3291) | Dec 24, 2019 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [b162d0fd81](https://linux-hardware.org/?probe=b162d0fd81) | Dec 22, 2019 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [2dc8b3f35d](https://linux-hardware.org/?probe=2dc8b3f35d) | Dec 22, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [98794aceb7](https://linux-hardware.org/?probe=98794aceb7) | Dec 21, 2019 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [5b00879915](https://linux-hardware.org/?probe=5b00879915) | Dec 21, 2019 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [8194a016bc](https://linux-hardware.org/?probe=8194a016bc) | Dec 21, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [df4413af58](https://linux-hardware.org/?probe=df4413af58) | Dec 17, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [e5cda35a9a](https://linux-hardware.org/?probe=e5cda35a9a) | Dec 16, 2019 |
| Wortmann      | NA92                        | All in one  | [19478ff625](https://linux-hardware.org/?probe=19478ff625) | Dec 15, 2019 |
| HP            | Compaq nw8440 (RY852EP#A... | Notebook    | [b38a821821](https://linux-hardware.org/?probe=b38a821821) | Dec 14, 2019 |
| HP            | Compaq 6510b (KV177EC#AB... | Notebook    | [a4d3f8a8ac](https://linux-hardware.org/?probe=a4d3f8a8ac) | Dec 13, 2019 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [08fd697014](https://linux-hardware.org/?probe=08fd697014) | Dec 12, 2019 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [6337a251d7](https://linux-hardware.org/?probe=6337a251d7) | Dec 12, 2019 |
| Lenovo        | Z50-70 20354                | Notebook    | [5377350816](https://linux-hardware.org/?probe=5377350816) | Dec 11, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7cc0e44901](https://linux-hardware.org/?probe=7cc0e44901) | Dec 08, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [6c2647ab1f](https://linux-hardware.org/?probe=6c2647ab1f) | Dec 07, 2019 |
| HP            | ENVY x360 Convertible 13... | Convertible | [70f1d3bf36](https://linux-hardware.org/?probe=70f1d3bf36) | Dec 07, 2019 |
| MSI           | Z97 PC Mate                 | Desktop     | [72bbff1151](https://linux-hardware.org/?probe=72bbff1151) | Dec 06, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f473523657](https://linux-hardware.org/?probe=f473523657) | Dec 04, 2019 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [6bd7363656](https://linux-hardware.org/?probe=6bd7363656) | Nov 30, 2019 |
| ASUSTek       | 1000H                       | Notebook    | [22b31ccf0f](https://linux-hardware.org/?probe=22b31ccf0f) | Nov 29, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [f80e2e7a87](https://linux-hardware.org/?probe=f80e2e7a87) | Nov 29, 2019 |
| HP            | ProBook 4530s               | Notebook    | [7988187508](https://linux-hardware.org/?probe=7988187508) | Nov 25, 2019 |
| HP            | ProBook 4530s               | Notebook    | [130b1900ea](https://linux-hardware.org/?probe=130b1900ea) | Nov 25, 2019 |
| ASRock        | B75M-GL R2.0                | Desktop     | [af0f782566](https://linux-hardware.org/?probe=af0f782566) | Nov 23, 2019 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [a620a7cc4f](https://linux-hardware.org/?probe=a620a7cc4f) | Nov 22, 2019 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [16108ce66a](https://linux-hardware.org/?probe=16108ce66a) | Nov 19, 2019 |
| Lenovo        | ThinkPad L480 20LS0017MC    | Notebook    | [e512a5e1ee](https://linux-hardware.org/?probe=e512a5e1ee) | Nov 18, 2019 |
| Microsoft     | Surface Pro 2               | Tablet      | [2c6b301bc3](https://linux-hardware.org/?probe=2c6b301bc3) | Nov 15, 2019 |
| Microsoft     | Surface Pro 2               | Tablet      | [79347f84aa](https://linux-hardware.org/?probe=79347f84aa) | Nov 15, 2019 |
| ASUSTek       | P5K Premium                 | Desktop     | [5cb1d8f9b9](https://linux-hardware.org/?probe=5cb1d8f9b9) | Nov 15, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| ASUSTek       | P5K SE                      | Desktop     | [47ed174456](https://linux-hardware.org/?probe=47ed174456) | Nov 14, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [e7b1fa1aa9](https://linux-hardware.org/?probe=e7b1fa1aa9) | Nov 14, 2019 |
| HP            | Notebook                    | Notebook    | [51d2b963e3](https://linux-hardware.org/?probe=51d2b963e3) | Nov 13, 2019 |
| Acer          | Aspire 5110                 | Notebook    | [2d2cbc0a8d](https://linux-hardware.org/?probe=2d2cbc0a8d) | Nov 12, 2019 |
| Acer          | Aspire 5110                 | Notebook    | [ff6142d68c](https://linux-hardware.org/?probe=ff6142d68c) | Nov 12, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c78f6913ae](https://linux-hardware.org/?probe=c78f6913ae) | Nov 11, 2019 |
| ASUSTek       | P5K Premium                 | Desktop     | [ead46dee7b](https://linux-hardware.org/?probe=ead46dee7b) | Nov 11, 2019 |
| HP            | EliteBook 745 G2            | Notebook    | [1c82c3c564](https://linux-hardware.org/?probe=1c82c3c564) | Nov 11, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c9d96d72e1](https://linux-hardware.org/?probe=c9d96d72e1) | Nov 10, 2019 |
| MSI           | MS-7360                     | Desktop     | [ef6c3da38a](https://linux-hardware.org/?probe=ef6c3da38a) | Nov 07, 2019 |
| MSI           | MS-7360                     | Desktop     | [3c13191b90](https://linux-hardware.org/?probe=3c13191b90) | Nov 07, 2019 |
| Lenovo        | SHARKBAY 31900058 STD       | All in one  | [647613f22b](https://linux-hardware.org/?probe=647613f22b) | Nov 05, 2019 |
| HP            | EliteBook 8470p             | Notebook    | [905fa1bd8b](https://linux-hardware.org/?probe=905fa1bd8b) | Nov 04, 2019 |
| Acer          | Aspire E1-531               | Notebook    | [41c23f1259](https://linux-hardware.org/?probe=41c23f1259) | Nov 04, 2019 |
| HP            | EliteBook 840 G6            | Notebook    | [f6a8a19103](https://linux-hardware.org/?probe=f6a8a19103) | Nov 04, 2019 |
| Gigabyte      | GA-M55PLUS-S3G              | Desktop     | [6027467f3b](https://linux-hardware.org/?probe=6027467f3b) | Nov 01, 2019 |
| Sony          | VPCEH2J1E                   | Notebook    | [09359ba2ca](https://linux-hardware.org/?probe=09359ba2ca) | Nov 01, 2019 |
| HP            | Pavilion dv6                | Notebook    | [4ba52172ad](https://linux-hardware.org/?probe=4ba52172ad) | Oct 28, 2019 |
| HP            | Pavilion g6                 | Notebook    | [12b4f13a70](https://linux-hardware.org/?probe=12b4f13a70) | Oct 27, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f1aa402558](https://linux-hardware.org/?probe=f1aa402558) | Oct 26, 2019 |
| Lenovo        | ThinkPad T440p 20ANA01P0... | Notebook    | [be20a32d4d](https://linux-hardware.org/?probe=be20a32d4d) | Oct 24, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [55012132f6](https://linux-hardware.org/?probe=55012132f6) | Oct 21, 2019 |
| Dell          | Precision 5510              | Notebook    | [f9346dd032](https://linux-hardware.org/?probe=f9346dd032) | Oct 20, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [fb8f7369fa](https://linux-hardware.org/?probe=fb8f7369fa) | Oct 20, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [2830c369c8](https://linux-hardware.org/?probe=2830c369c8) | Oct 20, 2019 |
| Acer          | Extensa 5620                | Notebook    | [c4feff7f79](https://linux-hardware.org/?probe=c4feff7f79) | Oct 17, 2019 |
| Acer          | Extensa 5235                | Notebook    | [525bd2b38a](https://linux-hardware.org/?probe=525bd2b38a) | Oct 17, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [cdf28aa8cc](https://linux-hardware.org/?probe=cdf28aa8cc) | Oct 16, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [24f7e5bb5b](https://linux-hardware.org/?probe=24f7e5bb5b) | Oct 16, 2019 |
| Acer          | Extensa 5235                | Notebook    | [0da32ec2d0](https://linux-hardware.org/?probe=0da32ec2d0) | Oct 16, 2019 |
| ASUSTek       | UX310UAK                    | Notebook    | [05d33156f9](https://linux-hardware.org/?probe=05d33156f9) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a302fca76](https://linux-hardware.org/?probe=4a302fca76) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | Notebook    | [3a7cedc107](https://linux-hardware.org/?probe=3a7cedc107) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | Notebook    | [6e1e8080d0](https://linux-hardware.org/?probe=6e1e8080d0) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | Notebook    | [678c55d478](https://linux-hardware.org/?probe=678c55d478) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | Notebook    | [16b9adda22](https://linux-hardware.org/?probe=16b9adda22) | Oct 14, 2019 |
| Sony          | VPCEH2J1E                   | Notebook    | [45f4c3c1fe](https://linux-hardware.org/?probe=45f4c3c1fe) | Oct 13, 2019 |
| HP            | 1998                        | Desktop     | [342c447028](https://linux-hardware.org/?probe=342c447028) | Oct 11, 2019 |
| Unknown       | Unknown                     | Desktop     | [c125474c31](https://linux-hardware.org/?probe=c125474c31) | Oct 10, 2019 |
| Acer          | Extensa 5620                | Notebook    | [e731e5a628](https://linux-hardware.org/?probe=e731e5a628) | Oct 10, 2019 |
| Dell          | Latitude 7480               | Notebook    | [df1f8299a4](https://linux-hardware.org/?probe=df1f8299a4) | Oct 09, 2019 |
| Dell          | Latitude 7480               | Notebook    | [77c51cdba1](https://linux-hardware.org/?probe=77c51cdba1) | Oct 09, 2019 |
| Dell          | Latitude 7480               | Notebook    | [211534820a](https://linux-hardware.org/?probe=211534820a) | Oct 09, 2019 |
| Acer          | Extensa 5220                | Notebook    | [5fe44df1d6](https://linux-hardware.org/?probe=5fe44df1d6) | Oct 08, 2019 |
| HP            | Spectre x360 Convertible... | Convertible | [d10677209e](https://linux-hardware.org/?probe=d10677209e) | Oct 08, 2019 |
| Sony          | VPCEB1E1E                   | Notebook    | [aa7b7564e5](https://linux-hardware.org/?probe=aa7b7564e5) | Oct 07, 2019 |
| MSI           | 970 GAMING                  | Desktop     | [1bb3b162b8](https://linux-hardware.org/?probe=1bb3b162b8) | Oct 03, 2019 |
| Dell          | Precision 5530              | Notebook    | [56b4b63a9d](https://linux-hardware.org/?probe=56b4b63a9d) | Oct 03, 2019 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [42ef2aa13b](https://linux-hardware.org/?probe=42ef2aa13b) | Sep 30, 2019 |
| HP            | 655                         | Notebook    | [31291ad75e](https://linux-hardware.org/?probe=31291ad75e) | Sep 29, 2019 |
| HP            | 655                         | Notebook    | [9d49ceb29a](https://linux-hardware.org/?probe=9d49ceb29a) | Sep 29, 2019 |
| HP            | Pavilion g6                 | Notebook    | [5bbd20265c](https://linux-hardware.org/?probe=5bbd20265c) | Sep 29, 2019 |
| Dell          | Vostro 5581                 | Notebook    | [27fdc7a402](https://linux-hardware.org/?probe=27fdc7a402) | Sep 27, 2019 |
| MSI           | 970 GAMING                  | Desktop     | [f8858e6fb6](https://linux-hardware.org/?probe=f8858e6fb6) | Sep 22, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [9cf22baa29](https://linux-hardware.org/?probe=9cf22baa29) | Sep 19, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2a12e1f7bf](https://linux-hardware.org/?probe=2a12e1f7bf) | Sep 18, 2019 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [1eced47226](https://linux-hardware.org/?probe=1eced47226) | Sep 18, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [b03fca451e](https://linux-hardware.org/?probe=b03fca451e) | Sep 18, 2019 |
| ASUSTek       | K50IJ                       | Notebook    | [43f9f6d938](https://linux-hardware.org/?probe=43f9f6d938) | Sep 16, 2019 |
| ASUSTek       | K50IJ                       | Notebook    | [a32aea019e](https://linux-hardware.org/?probe=a32aea019e) | Sep 16, 2019 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [23bf069faa](https://linux-hardware.org/?probe=23bf069faa) | Sep 15, 2019 |
| ASUSTek       | A8E                         | Notebook    | [ac8e6224b3](https://linux-hardware.org/?probe=ac8e6224b3) | Sep 14, 2019 |
| Dell          | Latitude E5470              | Notebook    | [dfb91a065c](https://linux-hardware.org/?probe=dfb91a065c) | Sep 13, 2019 |
| Lenovo        | ThinkPad T460 20FMS0QJ0P    | Notebook    | [c37e8c9e3e](https://linux-hardware.org/?probe=c37e8c9e3e) | Sep 12, 2019 |
| MSI           | 0A90                        | Desktop     | [70949e4cac](https://linux-hardware.org/?probe=70949e4cac) | Sep 12, 2019 |
| ASUSTek       | A8E                         | Notebook    | [3bfd78cdf3](https://linux-hardware.org/?probe=3bfd78cdf3) | Sep 12, 2019 |
| ASRock        | X470 Master SLI             | Desktop     | [49e321f31a](https://linux-hardware.org/?probe=49e321f31a) | Sep 10, 2019 |
| HP            | 250 G2                      | Notebook    | [0ee1d25c7e](https://linux-hardware.org/?probe=0ee1d25c7e) | Sep 07, 2019 |
| HP            | 250 G2                      | Notebook    | [169eb648ba](https://linux-hardware.org/?probe=169eb648ba) | Sep 07, 2019 |
| ASRock        | X470 Master SLI             | Desktop     | [9cf2d3e877](https://linux-hardware.org/?probe=9cf2d3e877) | Sep 02, 2019 |
| MSI           | A78M-E45                    | Desktop     | [c5735a3943](https://linux-hardware.org/?probe=c5735a3943) | Aug 31, 2019 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [7c54a20d12](https://linux-hardware.org/?probe=7c54a20d12) | Aug 29, 2019 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [7b7f45b3fd](https://linux-hardware.org/?probe=7b7f45b3fd) | Aug 29, 2019 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dfc2d9b353](https://linux-hardware.org/?probe=dfc2d9b353) | Aug 26, 2019 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e9decbc4fd](https://linux-hardware.org/?probe=e9decbc4fd) | Aug 26, 2019 |
| Dell          | Inspiron 7537               | Notebook    | [19d02b1151](https://linux-hardware.org/?probe=19d02b1151) | Aug 24, 2019 |
| Intel         | NUC7JYB J67967-402          | Mini pc     | [64a12a13ca](https://linux-hardware.org/?probe=64a12a13ca) | Aug 23, 2019 |
| HP            | G72                         | Notebook    | [dac5510694](https://linux-hardware.org/?probe=dac5510694) | Aug 23, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [a777349d95](https://linux-hardware.org/?probe=a777349d95) | Aug 21, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [3f3395ff9f](https://linux-hardware.org/?probe=3f3395ff9f) | Aug 21, 2019 |
| HP            | EliteBook 8730w             | Notebook    | [2b533b1416](https://linux-hardware.org/?probe=2b533b1416) | Aug 17, 2019 |
| MSI           | 0A90                        | Desktop     | [12b46024d1](https://linux-hardware.org/?probe=12b46024d1) | Aug 16, 2019 |
| Dell          | Latitude 7390               | Notebook    | [d360b45394](https://linux-hardware.org/?probe=d360b45394) | Aug 15, 2019 |
| Acer          | Extensa 5220                | Notebook    | [dfec154035](https://linux-hardware.org/?probe=dfec154035) | Aug 14, 2019 |
| Sony          | SVE14135CXP                 | Notebook    | [1b1819d6c0](https://linux-hardware.org/?probe=1b1819d6c0) | Aug 13, 2019 |
| Dell          | Latitude 7390               | Notebook    | [05cdc89a9d](https://linux-hardware.org/?probe=05cdc89a9d) | Aug 12, 2019 |
| Acer          | Extensa 5220                | Notebook    | [b33c5c819b](https://linux-hardware.org/?probe=b33c5c819b) | Aug 10, 2019 |
| ELSKY         | Nano9F-2C                   | Desktop     | [a3eb79407f](https://linux-hardware.org/?probe=a3eb79407f) | Aug 08, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [4db48dfe19](https://linux-hardware.org/?probe=4db48dfe19) | Aug 08, 2019 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3ffa6aa435](https://linux-hardware.org/?probe=3ffa6aa435) | Aug 07, 2019 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1b466fc315](https://linux-hardware.org/?probe=1b466fc315) | Jul 31, 2019 |
| MSI           | A78M-E45                    | Desktop     | [5b9ab2b30a](https://linux-hardware.org/?probe=5b9ab2b30a) | Jul 31, 2019 |
| HP            | ZBook 17                    | Notebook    | [9d1c8ffb20](https://linux-hardware.org/?probe=9d1c8ffb20) | Jul 30, 2019 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [394c81b911](https://linux-hardware.org/?probe=394c81b911) | Jul 28, 2019 |
| EUROCOM       | Sky X4C                     | Notebook    | [4ced599618](https://linux-hardware.org/?probe=4ced599618) | Jul 26, 2019 |
| Insyde        | AS Series                   | Notebook    | [0994a3eeb3](https://linux-hardware.org/?probe=0994a3eeb3) | Jul 24, 2019 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [048229855f](https://linux-hardware.org/?probe=048229855f) | Jul 23, 2019 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | Desktop     | [077a9b9d45](https://linux-hardware.org/?probe=077a9b9d45) | Jul 22, 2019 |
| ASRock        | Q1900B-ITX                  | Desktop     | [9f5937d37e](https://linux-hardware.org/?probe=9f5937d37e) | Jul 21, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [029641c14a](https://linux-hardware.org/?probe=029641c14a) | Jul 19, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [eba01de2ba](https://linux-hardware.org/?probe=eba01de2ba) | Jul 19, 2019 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [6e181005c4](https://linux-hardware.org/?probe=6e181005c4) | Jul 16, 2019 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | Desktop     | [7fc111342c](https://linux-hardware.org/?probe=7fc111342c) | Jul 14, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [ec150f49de](https://linux-hardware.org/?probe=ec150f49de) | Jul 14, 2019 |
| Acer          | Monserrat                   | Notebook    | [c57ddb8581](https://linux-hardware.org/?probe=c57ddb8581) | Jul 14, 2019 |
| Acer          | Monserrat                   | Notebook    | [b38c638fe2](https://linux-hardware.org/?probe=b38c638fe2) | Jul 14, 2019 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | Notebook    | [83f2ff723d](https://linux-hardware.org/?probe=83f2ff723d) | Jul 13, 2019 |
| HP            | ProBook 4525s               | Notebook    | [23e7475693](https://linux-hardware.org/?probe=23e7475693) | Jul 10, 2019 |
| ASUSTek       | X101CH                      | Notebook    | [6fb4432f5a](https://linux-hardware.org/?probe=6fb4432f5a) | Jul 09, 2019 |
| Acer          | Extensa 5220                | Notebook    | [7387d70ad5](https://linux-hardware.org/?probe=7387d70ad5) | Jul 06, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | Notebook    | [23dac0f1b6](https://linux-hardware.org/?probe=23dac0f1b6) | Jul 05, 2019 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [65cf4f7f82](https://linux-hardware.org/?probe=65cf4f7f82) | Jul 05, 2019 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [d28cd9f74d](https://linux-hardware.org/?probe=d28cd9f74d) | Jul 04, 2019 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [feda3b155d](https://linux-hardware.org/?probe=feda3b155d) | Jul 04, 2019 |
| Gigabyte      | P35-DS3                     | Desktop     | [8168ba11e3](https://linux-hardware.org/?probe=8168ba11e3) | Jul 02, 2019 |
| Acer          | Aspire E1-522               | Notebook    | [5f96135c9a](https://linux-hardware.org/?probe=5f96135c9a) | Jun 30, 2019 |
| Acer          | Extensa 5220                | Notebook    | [9e0e784c24](https://linux-hardware.org/?probe=9e0e784c24) | Jun 30, 2019 |
| Gigabyte      | H77-DS3H                    | Desktop     | [87233b6bd2](https://linux-hardware.org/?probe=87233b6bd2) | Jun 28, 2019 |
| HP            | ProBook 430 G1              | Notebook    | [9be61e9a2d](https://linux-hardware.org/?probe=9be61e9a2d) | Jun 24, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [6582422be8](https://linux-hardware.org/?probe=6582422be8) | Jun 21, 2019 |
| Lenovo        | No DPK                      | All in one  | [46e2d4b676](https://linux-hardware.org/?probe=46e2d4b676) | Jun 20, 2019 |
| Lenovo        | ThinkPad T460s 20FAS2BM0... | Notebook    | [78932b3c9b](https://linux-hardware.org/?probe=78932b3c9b) | Jun 20, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [583c276ad3](https://linux-hardware.org/?probe=583c276ad3) | Jun 18, 2019 |
| UMAX          | VisionBook 13Wa Pro         | Notebook    | [237f54eb53](https://linux-hardware.org/?probe=237f54eb53) | Jun 17, 2019 |
| ASUSTek       | X453SA                      | Notebook    | [7a4394875f](https://linux-hardware.org/?probe=7a4394875f) | Jun 17, 2019 |
| MSI           | B350 TOMAHAWK               | Desktop     | [84ec84c6f6](https://linux-hardware.org/?probe=84ec84c6f6) | Jun 16, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c6c915f346](https://linux-hardware.org/?probe=c6c915f346) | Jun 14, 2019 |
| UMAX          | VisionBook 13Wa Pro         | Notebook    | [299bc30247](https://linux-hardware.org/?probe=299bc30247) | Jun 13, 2019 |
| MSI           | B350 TOMAHAWK               | Desktop     | [ec5e14a2fc](https://linux-hardware.org/?probe=ec5e14a2fc) | Jun 12, 2019 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [8a3d697836](https://linux-hardware.org/?probe=8a3d697836) | Jun 12, 2019 |
| EUROCOM       | Sky X4C                     | Notebook    | [bd8361fe34](https://linux-hardware.org/?probe=bd8361fe34) | Jun 11, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [8373600eb6](https://linux-hardware.org/?probe=8373600eb6) | Jun 09, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | Notebook    | [c90ba0b154](https://linux-hardware.org/?probe=c90ba0b154) | Jun 08, 2019 |
| HP            | 15                          | Notebook    | [b4e1df2016](https://linux-hardware.org/?probe=b4e1df2016) | Jun 05, 2019 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [e938889e72](https://linux-hardware.org/?probe=e938889e72) | Jun 04, 2019 |
| ASUSTek       | X453SA                      | Notebook    | [48a7d9e35b](https://linux-hardware.org/?probe=48a7d9e35b) | May 27, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [586cd3ab4a](https://linux-hardware.org/?probe=586cd3ab4a) | May 25, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [54ed095d80](https://linux-hardware.org/?probe=54ed095d80) | May 24, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [994ff4beb4](https://linux-hardware.org/?probe=994ff4beb4) | May 21, 2019 |
| Acer          | Extensa 5620                | Notebook    | [2a3f563e9d](https://linux-hardware.org/?probe=2a3f563e9d) | May 21, 2019 |
| HP            | ZBook 17                    | Notebook    | [561770352f](https://linux-hardware.org/?probe=561770352f) | May 17, 2019 |
| UMAX          | 13Wa_Flex                   | Notebook    | [1b3276fb60](https://linux-hardware.org/?probe=1b3276fb60) | May 14, 2019 |
| Acer          | Extensa 5620                | Notebook    | [f80a434ab1](https://linux-hardware.org/?probe=f80a434ab1) | May 13, 2019 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [8984f382ef](https://linux-hardware.org/?probe=8984f382ef) | May 12, 2019 |
| ASUSTek       | P5K SE                      | Desktop     | [fe7f2c780a](https://linux-hardware.org/?probe=fe7f2c780a) | May 11, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [d6f5348ec7](https://linux-hardware.org/?probe=d6f5348ec7) | May 09, 2019 |
| MSI           | B350 GAMING PLUS            | Desktop     | [63c8391791](https://linux-hardware.org/?probe=63c8391791) | May 09, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [8169b27ee7](https://linux-hardware.org/?probe=8169b27ee7) | May 09, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [b9c026d844](https://linux-hardware.org/?probe=b9c026d844) | May 09, 2019 |
| ASUSTek       | P5K Premium                 | Desktop     | [aaecfa3e56](https://linux-hardware.org/?probe=aaecfa3e56) | May 08, 2019 |
| Dell          | 0HHV7N A00                  | Desktop     | [945e8a152d](https://linux-hardware.org/?probe=945e8a152d) | May 06, 2019 |
| Dell          | Latitude 7290               | Notebook    | [3e31be830b](https://linux-hardware.org/?probe=3e31be830b) | May 06, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [c949572837](https://linux-hardware.org/?probe=c949572837) | May 05, 2019 |
| Gigabyte      | G33M-S2L                    | Desktop     | [74f9393d09](https://linux-hardware.org/?probe=74f9393d09) | Apr 27, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [d4041548f7](https://linux-hardware.org/?probe=d4041548f7) | Apr 27, 2019 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [a6769b6b22](https://linux-hardware.org/?probe=a6769b6b22) | Apr 26, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [0509a7b376](https://linux-hardware.org/?probe=0509a7b376) | Apr 22, 2019 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [5c06550c98](https://linux-hardware.org/?probe=5c06550c98) | Apr 16, 2019 |
| UMAX          | VisionBook 13Wa             | Notebook    | [f53622af88](https://linux-hardware.org/?probe=f53622af88) | Apr 14, 2019 |
| Acer          | Aspire 3750G                | Notebook    | [6f36d97878](https://linux-hardware.org/?probe=6f36d97878) | Apr 12, 2019 |
| ASUSTek       | E502SA                      | Notebook    | [bd2b6260c9](https://linux-hardware.org/?probe=bd2b6260c9) | Apr 12, 2019 |
| ASUSTek       | E502SA                      | Notebook    | [d4cd483c7e](https://linux-hardware.org/?probe=d4cd483c7e) | Apr 12, 2019 |
| Sony          | VPCEB1E1E                   | Notebook    | [9976a35e60](https://linux-hardware.org/?probe=9976a35e60) | Apr 12, 2019 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [6011d46330](https://linux-hardware.org/?probe=6011d46330) | Apr 10, 2019 |
| MSI           | P45 Platinum                | Desktop     | [7999e0452a](https://linux-hardware.org/?probe=7999e0452a) | Apr 07, 2019 |
| MSI           | P45 Platinum                | Desktop     | [4e9d6c8e02](https://linux-hardware.org/?probe=4e9d6c8e02) | Apr 07, 2019 |
| UMAX          | VisionBook 13Wa             | Notebook    | [568d0511c5](https://linux-hardware.org/?probe=568d0511c5) | Apr 06, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [bb454edeb2](https://linux-hardware.org/?probe=bb454edeb2) | Apr 06, 2019 |
| Dell          | Precision M6500             | Notebook    | [089056d291](https://linux-hardware.org/?probe=089056d291) | Apr 06, 2019 |
| ASUSTek       | K55VJ                       | Notebook    | [fac5cee3e3](https://linux-hardware.org/?probe=fac5cee3e3) | Apr 05, 2019 |
| ASUSTek       | J1800I-C                    | Desktop     | [35cfa6018f](https://linux-hardware.org/?probe=35cfa6018f) | Apr 03, 2019 |
| ASUSTek       | K53BY                       | Notebook    | [7eae69fedb](https://linux-hardware.org/?probe=7eae69fedb) | Mar 31, 2019 |
| ASUSTek       | Leonite2                    | Desktop     | [acd81f03f2](https://linux-hardware.org/?probe=acd81f03f2) | Mar 28, 2019 |
| Lenovo        | Y50-70 20378                | Notebook    | [bc4e358c02](https://linux-hardware.org/?probe=bc4e358c02) | Mar 28, 2019 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ae7d79f749](https://linux-hardware.org/?probe=ae7d79f749) | Mar 27, 2019 |
| Sony          | VPCEA1S1E                   | Notebook    | [30221f58ec](https://linux-hardware.org/?probe=30221f58ec) | Mar 26, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [aeef8eb693](https://linux-hardware.org/?probe=aeef8eb693) | Mar 26, 2019 |
| MSI           | G41M4                       | Desktop     | [34263c5455](https://linux-hardware.org/?probe=34263c5455) | Mar 22, 2019 |
| MSI           | G41M-P26                    | Desktop     | [fb80aa717a](https://linux-hardware.org/?probe=fb80aa717a) | Mar 21, 2019 |
| HP            | 1497                        | Desktop     | [645891d86b](https://linux-hardware.org/?probe=645891d86b) | Mar 21, 2019 |
| HP            | 1497                        | Desktop     | [50753b9ba5](https://linux-hardware.org/?probe=50753b9ba5) | Mar 21, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [2f4122790d](https://linux-hardware.org/?probe=2f4122790d) | Mar 20, 2019 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a462f23545](https://linux-hardware.org/?probe=a462f23545) | Mar 20, 2019 |
| HP            | 198E                        | Desktop     | [556ffdb3d3](https://linux-hardware.org/?probe=556ffdb3d3) | Mar 17, 2019 |
| HP            | 198E                        | Desktop     | [c722407ee3](https://linux-hardware.org/?probe=c722407ee3) | Mar 17, 2019 |
| ASUSTek       | K8VSEDX                     | Desktop     | [e75f4538bc](https://linux-hardware.org/?probe=e75f4538bc) | Mar 13, 2019 |
| ASUSTek       | K8VSEDX                     | Desktop     | [af41e6a893](https://linux-hardware.org/?probe=af41e6a893) | Mar 11, 2019 |
| Dell          | XPS 15 9575                 | Notebook    | [f5fdc69851](https://linux-hardware.org/?probe=f5fdc69851) | Mar 09, 2019 |
| MSI           | B360M MORTAR                | Desktop     | [f86dada1e8](https://linux-hardware.org/?probe=f86dada1e8) | Mar 08, 2019 |
| HP            | Compaq dc7600 Small Form... | Desktop     | [126f2d8b0f](https://linux-hardware.org/?probe=126f2d8b0f) | Mar 07, 2019 |
| HP            | Compaq dc7600 Small Form... | Desktop     | [3ffe7337bd](https://linux-hardware.org/?probe=3ffe7337bd) | Mar 04, 2019 |
| HP            | Compaq dc7600 Small Form... | Desktop     | [06472f3d2c](https://linux-hardware.org/?probe=06472f3d2c) | Mar 03, 2019 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [e3ef0760f5](https://linux-hardware.org/?probe=e3ef0760f5) | Mar 03, 2019 |
| MSI           | 970A-G43                    | Desktop     | [631892b31b](https://linux-hardware.org/?probe=631892b31b) | Feb 22, 2019 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [3799326d94](https://linux-hardware.org/?probe=3799326d94) | Feb 18, 2019 |
| ASUSTek       | P5K Premium                 | Desktop     | [f6f1f3d526](https://linux-hardware.org/?probe=f6f1f3d526) | Feb 16, 2019 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [b139926981](https://linux-hardware.org/?probe=b139926981) | Feb 16, 2019 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [80b80427e7](https://linux-hardware.org/?probe=80b80427e7) | Feb 16, 2019 |
| Fujitsu Si... | D2598-A1 S26361-D2598-A1    | Desktop     | [9bc9c716d7](https://linux-hardware.org/?probe=9bc9c716d7) | Feb 15, 2019 |
| ASUSTek       | P5K Premium                 | Desktop     | [13dbdc3bfe](https://linux-hardware.org/?probe=13dbdc3bfe) | Feb 11, 2019 |
| ASUSTek       | P5K Premium                 | Desktop     | [52d7ba736e](https://linux-hardware.org/?probe=52d7ba736e) | Feb 11, 2019 |
| Intel         | NUC7i7DNB J83500-202        | Mini pc     | [242161effc](https://linux-hardware.org/?probe=242161effc) | Feb 07, 2019 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [a8632b914f](https://linux-hardware.org/?probe=a8632b914f) | Feb 07, 2019 |
| HP            | EliteBook 8530p             | Notebook    | [5358bdeae7](https://linux-hardware.org/?probe=5358bdeae7) | Feb 05, 2019 |
| ASUSTek       | K70IC                       | Notebook    | [17e1c5ea47](https://linux-hardware.org/?probe=17e1c5ea47) | Feb 03, 2019 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [b854c8f19f](https://linux-hardware.org/?probe=b854c8f19f) | Jan 31, 2019 |
| Gigabyte      | GA-A75M-S2V                 | Desktop     | [190b100445](https://linux-hardware.org/?probe=190b100445) | Jan 27, 2019 |
| ASUSTek       | K70IC                       | Notebook    | [0a857f39b3](https://linux-hardware.org/?probe=0a857f39b3) | Jan 23, 2019 |
| Lenovo        | ThinkPad T440p 20ANA01P0... | Notebook    | [075bb02ebf](https://linux-hardware.org/?probe=075bb02ebf) | Jan 17, 2019 |
| Gigabyte      | GA-K8NMF-9                  | Desktop     | [06d9e6367f](https://linux-hardware.org/?probe=06d9e6367f) | Jan 13, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [cecb4beb0b](https://linux-hardware.org/?probe=cecb4beb0b) | Jan 11, 2019 |
| Acer          | Aspire E1-530               | Notebook    | [c8bbd66689](https://linux-hardware.org/?probe=c8bbd66689) | Jan 10, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [e15bdbf5d9](https://linux-hardware.org/?probe=e15bdbf5d9) | Jan 10, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [3f6457cfd5](https://linux-hardware.org/?probe=3f6457cfd5) | Jan 10, 2019 |
| Dell          | 040DDP A01                  | Desktop     | [b930102736](https://linux-hardware.org/?probe=b930102736) | Jan 09, 2019 |
| Dell          | 040DDP A01                  | Desktop     | [40c27cbf90](https://linux-hardware.org/?probe=40c27cbf90) | Jan 09, 2019 |
| Lenovo        | ThinkPad T460s 20FAS2BM0... | Notebook    | [5a912fd2ea](https://linux-hardware.org/?probe=5a912fd2ea) | Jan 03, 2019 |
| HP            | ProBook 4320s               | Notebook    | [44c1e7bb5c](https://linux-hardware.org/?probe=44c1e7bb5c) | Jan 03, 2019 |
| HP            | Pavilion x2 Detachable      | Notebook    | [40e42cb215](https://linux-hardware.org/?probe=40e42cb215) | Dec 30, 2018 |
| Acer          | Aspire A315-21G             | Notebook    | [fc3c439818](https://linux-hardware.org/?probe=fc3c439818) | Dec 30, 2018 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1192b16b2a](https://linux-hardware.org/?probe=1192b16b2a) | Dec 29, 2018 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f1b5bc1e1f](https://linux-hardware.org/?probe=f1b5bc1e1f) | Dec 29, 2018 |
| Sony          | VPCEB1E1E                   | Notebook    | [7d1522f747](https://linux-hardware.org/?probe=7d1522f747) | Dec 26, 2018 |
| Sony          | VPCEB1E1E                   | Notebook    | [64be9e8809](https://linux-hardware.org/?probe=64be9e8809) | Dec 25, 2018 |
| HP            | Pavilion dv6                | Notebook    | [ed828ba9f4](https://linux-hardware.org/?probe=ed828ba9f4) | Dec 22, 2018 |
| HP            | Pavilion dv6                | Notebook    | [8f15df54b3](https://linux-hardware.org/?probe=8f15df54b3) | Dec 22, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [0dad2407e3](https://linux-hardware.org/?probe=0dad2407e3) | Dec 20, 2018 |
| MSI           | H55M-E33                    | Desktop     | [b780e08bb9](https://linux-hardware.org/?probe=b780e08bb9) | Dec 16, 2018 |
| MSI           | MS-B0731 110                | Desktop     | [c3d309bfb3](https://linux-hardware.org/?probe=c3d309bfb3) | Dec 14, 2018 |
| MSI           | MS-B0731 110                | Desktop     | [e827df73dc](https://linux-hardware.org/?probe=e827df73dc) | Dec 14, 2018 |
| ASUSTek       | H170-PRO                    | Desktop     | [0938abc248](https://linux-hardware.org/?probe=0938abc248) | Dec 11, 2018 |
| ASUSTek       | X553SA                      | Notebook    | [f308c7c04a](https://linux-hardware.org/?probe=f308c7c04a) | Dec 10, 2018 |
| ASUSTek       | X553SA                      | Notebook    | [f4ae14c49b](https://linux-hardware.org/?probe=f4ae14c49b) | Dec 10, 2018 |
| Acer          | Aspire 6920                 | Notebook    | [c7f73c8073](https://linux-hardware.org/?probe=c7f73c8073) | Dec 06, 2018 |
| Acer          | Aspire 6920                 | Notebook    | [5703320f98](https://linux-hardware.org/?probe=5703320f98) | Dec 06, 2018 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [f905cc3870](https://linux-hardware.org/?probe=f905cc3870) | Dec 05, 2018 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [e6d3282cf3](https://linux-hardware.org/?probe=e6d3282cf3) | Dec 05, 2018 |
| Lenovo        | ThinkPad T460s 20FAS2BN0... | Notebook    | [ac90cab72c](https://linux-hardware.org/?probe=ac90cab72c) | Dec 04, 2018 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bb2e4203aa](https://linux-hardware.org/?probe=bb2e4203aa) | Nov 29, 2018 |
| Acer          | Aspire XC-330               | Desktop     | [f8f3bade01](https://linux-hardware.org/?probe=f8f3bade01) | Nov 26, 2018 |
| ASUSTek       | M2R32-MVP                   | Desktop     | [c55fd274a8](https://linux-hardware.org/?probe=c55fd274a8) | Nov 25, 2018 |
| HP            | Pavilion dv7                | Notebook    | [d0378a64aa](https://linux-hardware.org/?probe=d0378a64aa) | Nov 24, 2018 |
| ASUSTek       | P5KC                        | Desktop     | [8a3e1d567d](https://linux-hardware.org/?probe=8a3e1d567d) | Nov 24, 2018 |
| Acer          | Aspire XC-330               | Desktop     | [68b982def0](https://linux-hardware.org/?probe=68b982def0) | Nov 24, 2018 |
| HP            | ProBook 450 G5              | Notebook    | [70d66c5819](https://linux-hardware.org/?probe=70d66c5819) | Nov 22, 2018 |
| HP            | G62                         | Notebook    | [3dcd149ca9](https://linux-hardware.org/?probe=3dcd149ca9) | Nov 22, 2018 |
| Dell          | Latitude E6400              | Notebook    | [2ee9ca1698](https://linux-hardware.org/?probe=2ee9ca1698) | Nov 17, 2018 |
| MSI           | B450-A PRO                  | Desktop     | [69d51e68b0](https://linux-hardware.org/?probe=69d51e68b0) | Nov 17, 2018 |
| ASUSTek       | Z170-P                      | Desktop     | [89df305ae0](https://linux-hardware.org/?probe=89df305ae0) | Nov 16, 2018 |
| MSI           | B450-A PRO                  | Desktop     | [e19f3cd86b](https://linux-hardware.org/?probe=e19f3cd86b) | Nov 13, 2018 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [785b8234d8](https://linux-hardware.org/?probe=785b8234d8) | Nov 11, 2018 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [8647c5f6bf](https://linux-hardware.org/?probe=8647c5f6bf) | Nov 11, 2018 |
| MSI           | P45 Platinum                | Desktop     | [a37ef3f804](https://linux-hardware.org/?probe=a37ef3f804) | Nov 10, 2018 |
| ASUSTek       | K55VJ                       | Notebook    | [292714e2c9](https://linux-hardware.org/?probe=292714e2c9) | Nov 10, 2018 |
| ASUSTek       | K55VJ                       | Notebook    | [ee7e6a7365](https://linux-hardware.org/?probe=ee7e6a7365) | Nov 10, 2018 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [bb570c89e7](https://linux-hardware.org/?probe=bb570c89e7) | Nov 10, 2018 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [eb0530deb6](https://linux-hardware.org/?probe=eb0530deb6) | Nov 10, 2018 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [afa6ff3556](https://linux-hardware.org/?probe=afa6ff3556) | Nov 10, 2018 |
| Prestigio     | Multipad Visconte V         | Notebook    | [47813421d8](https://linux-hardware.org/?probe=47813421d8) | Oct 31, 2018 |
| Lenovo        | ThinkPad T540p 20BFS1Y50... | Notebook    | [dda01f57c1](https://linux-hardware.org/?probe=dda01f57c1) | Oct 30, 2018 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [72b7400f99](https://linux-hardware.org/?probe=72b7400f99) | Oct 21, 2018 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [a31f08667c](https://linux-hardware.org/?probe=a31f08667c) | Oct 21, 2018 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [51dce6d904](https://linux-hardware.org/?probe=51dce6d904) | Oct 21, 2018 |
| Supermicro    | X8STi                       | Desktop     | [a265bad98f](https://linux-hardware.org/?probe=a265bad98f) | Oct 19, 2018 |
| Gigabyte      | P67A-UD4-B3                 | Desktop     | [cbbd77219d](https://linux-hardware.org/?probe=cbbd77219d) | Aug 10, 2018 |
| ASUSTek       | K8VSEDX                     | Desktop     | [ef07e2c2ef](https://linux-hardware.org/?probe=ef07e2c2ef) | Aug 10, 2018 |
| Lenovo        | ThinkPad W541 20EGS0R60R    | Notebook    | [3583ec2729](https://linux-hardware.org/?probe=3583ec2729) | Jul 18, 2018 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e1d0272f03](https://linux-hardware.org/?probe=e1d0272f03) | Jul 04, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [c90fdb8aae](https://linux-hardware.org/?probe=c90fdb8aae) | Jun 09, 2018 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8f9240e65b](https://linux-hardware.org/?probe=8f9240e65b) | May 30, 2018 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [2457e81077](https://linux-hardware.org/?probe=2457e81077) | May 12, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [91699cbaf8](https://linux-hardware.org/?probe=91699cbaf8) | Apr 18, 2018 |
| Lenovo        | ThinkPad X220 4291EJ3       | Notebook    | [6ff9f41b4f](https://linux-hardware.org/?probe=6ff9f41b4f) | Mar 04, 2018 |
| Supermicro    | X10DRi                      | Server      | [bf0a7f04b4](https://linux-hardware.org/?probe=bf0a7f04b4) | Mar 04, 2018 |
| ASUSTek       | K8VSEDX                     | Desktop     | [dff4a09807](https://linux-hardware.org/?probe=dff4a09807) | Feb 02, 2018 |
| Acer          | TravelMate P277-MG          | Notebook    | [4b3b9a06f5](https://linux-hardware.org/?probe=4b3b9a06f5) | Jan 23, 2018 |
| MSI           | H81M-P33 V2                 | Desktop     | [ab7edede3c](https://linux-hardware.org/?probe=ab7edede3c) | Jan 17, 2018 |
| Lenovo        | ThinkPad X230 2330A33       | Notebook    | [2c83a63531](https://linux-hardware.org/?probe=2c83a63531) | Dec 30, 2017 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [d7e0b7ca2e](https://linux-hardware.org/?probe=d7e0b7ca2e) | Dec 14, 2017 |
| ASUSTek       | M2A74-AM                    | Desktop     | [f3d795bddd](https://linux-hardware.org/?probe=f3d795bddd) | Nov 24, 2017 |
| ASUSTek       | J1800I-C                    | Desktop     | [44deca13f0](https://linux-hardware.org/?probe=44deca13f0) | Oct 15, 2017 |
| ASUSTek       | J1800I-C                    | Desktop     | [043af9db42](https://linux-hardware.org/?probe=043af9db42) | Oct 11, 2017 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1843755019](https://linux-hardware.org/?probe=1843755019) | Aug 22, 2017 |
| Acer          | Aspire 3690                 | Notebook    | [833fd8cc02](https://linux-hardware.org/?probe=833fd8cc02) | Jul 27, 2017 |
| Gigabyte      | M68MT-S2                    | Desktop     | [5fbed0d6a1](https://linux-hardware.org/?probe=5fbed0d6a1) | Jul 15, 2017 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [cf39a21a77](https://linux-hardware.org/?probe=cf39a21a77) | Jul 02, 2017 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [fd5fde7a28](https://linux-hardware.org/?probe=fd5fde7a28) | Jun 15, 2017 |
| Acer          | TravelMate P253             | Notebook    | [1de286539e](https://linux-hardware.org/?probe=1de286539e) | May 21, 2017 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [602f0c766a](https://linux-hardware.org/?probe=602f0c766a) | Apr 23, 2017 |
| Acer          | TravelMate P277-MG          | Notebook    | [303cee3407](https://linux-hardware.org/?probe=303cee3407) | Feb 23, 2017 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [ce0d84e8c5](https://linux-hardware.org/?probe=ce0d84e8c5) | Dec 25, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 238       | 14.74%  |
| Ubuntu 18.04                 | 150       | 9.29%   |
| OpenMandriva 4.2             | 115       | 7.12%   |
| OpenMandriva 4.50            | 58        | 3.59%   |
| Ubuntu 21.10                 | 38        | 2.35%   |
| Ubuntu 20.10                 | 35        | 2.17%   |
| Fedora 34                    | 35        | 2.17%   |
| Ubuntu 22.04                 | 29        | 1.8%    |
| OpenMandriva 4.3             | 29        | 1.8%    |
| Ubuntu 19.10                 | 28        | 1.73%   |
| Linux Mint 20.1              | 28        | 1.73%   |
| Ubuntu 21.04                 | 27        | 1.67%   |
| Fedora 35                    | 26        | 1.61%   |
| Debian 11                    | 26        | 1.61%   |
| Linux Mint 20                | 25        | 1.55%   |
| Fedora 32                    | 25        | 1.55%   |
| Ubuntu 19.04                 | 24        | 1.49%   |
| Linux Mint 20.2              | 23        | 1.42%   |
| Fedora 33                    | 23        | 1.42%   |
| Arch                         | 22        | 1.36%   |
| Linux Mint 19.3              | 21        | 1.3%    |
| Zorin 16                     | 20        | 1.24%   |
| Zorin 15                     | 18        | 1.11%   |
| Fedora 31                    | 18        | 1.11%   |
| Kubuntu 20.04                | 17        | 1.05%   |
| Ubuntu 16.04                 | 16        | 0.99%   |
| Linux Mint 20.3              | 16        | 0.99%   |
| Arch Rolling                 | 16        | 0.99%   |
| Xubuntu 20.04                | 15        | 0.93%   |
| Pop!_OS 20.04                | 15        | 0.93%   |
| Xubuntu 18.04                | 14        | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 13        | 0.8%    |
| KDE neon 20.04               | 13        | 0.8%    |
| Debian 10                    | 13        | 0.8%    |
| Ubuntu 18.10                 | 11        | 0.68%   |
| RHEL 8                       | 11        | 0.68%   |
| Manjaro                      | 10        | 0.62%   |
| Gentoo 2.6                   | 10        | 0.62%   |
| ROSA R9                      | 9         | 0.56%   |
| Fedora 36                    | 9         | 0.56%   |
| Debian Testing               | 9         | 0.56%   |
| ROSA R10                     | 8         | 0.5%    |
| Pop!_OS 21.04                | 8         | 0.5%    |
| Gentoo 2.7                   | 8         | 0.5%    |
| Ubuntu MATE 20.04            | 7         | 0.43%   |
| Linux Mint 19.2              | 7         | 0.43%   |
| Linux Mint 19.1              | 7         | 0.43%   |
| Lubuntu 18.04                | 6         | 0.37%   |
| ArcoLinux Rolling            | 6         | 0.37%   |
| ROSA R11.1                   | 5         | 0.31%   |
| ROSA R11                     | 5         | 0.31%   |
| Pop!_OS 21.10                | 5         | 0.31%   |
| Lubuntu 20.04                | 5         | 0.31%   |
| Linux Mint 19                | 5         | 0.31%   |
| CentOS 7                     | 5         | 0.31%   |
| ACI 3.5.4                    | 5         | 0.31%   |
| Zorin 12                     | 4         | 0.25%   |
| Xubuntu 21.04                | 4         | 0.25%   |
| Void Linux Rolling           | 4         | 0.25%   |
| ROSA R8.1                    | 4         | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 563       | 36.68%  |
| OpenMandriva     | 203       | 13.22%  |
| Fedora           | 138       | 8.99%   |
| Linux Mint       | 126       | 8.21%   |
| Debian           | 50        | 3.26%   |
| Manjaro          | 43        | 2.8%    |
| Zorin            | 42        | 2.74%   |
| Xubuntu          | 38        | 2.48%   |
| Arch             | 38        | 2.48%   |
| ROSA             | 31        | 2.02%   |
| Pop!_OS          | 31        | 2.02%   |
| Kubuntu          | 31        | 2.02%   |
| Gentoo           | 19        | 1.24%   |
| openSUSE         | 18        | 1.17%   |
| KDE neon         | 16        | 1.04%   |
| Lubuntu          | 14        | 0.91%   |
| RHEL             | 13        | 0.85%   |
| Endless          | 13        | 0.85%   |
| Ubuntu MATE      | 11        | 0.72%   |
| Kali             | 11        | 0.72%   |
| Elementary       | 11        | 0.72%   |
| CentOS           | 9         | 0.59%   |
| ArcoLinux        | 8         | 0.52%   |
| Void Linux       | 6         | 0.39%   |
| EndeavourOS      | 5         | 0.33%   |
| ACI              | 5         | 0.33%   |
| Parrot           | 4         | 0.26%   |
| BlackPanther     | 4         | 0.26%   |
| Rocky Linux      | 3         | 0.2%    |
| MX               | 3         | 0.2%    |
| LMDE             | 3         | 0.2%    |
| LinuxFX          | 3         | 0.2%    |
| SystemRescue     | 1         | 0.07%   |
| SteamOS          | 1         | 0.07%   |
| Sparky           | 1         | 0.07%   |
| Sabayon          | 1         | 0.07%   |
| Rockstor         | 1         | 0.07%   |
| Reborn OS        | 1         | 0.07%   |
| Peppermint       | 1         | 0.07%   |
| org.kde.Platform | 1         | 0.07%   |
| NixOS            | 1         | 0.07%   |
| Mageia           | 1         | 0.07%   |
| LFS              | 1         | 0.07%   |
| GNOME OS         | 1         | 0.07%   |
| Garuda Linux     | 1         | 0.07%   |
| Drauger OS       | 1         | 0.07%   |
| Deepin           | 1         | 0.07%   |
| Clear Linux      | 1         | 0.07%   |
| BunsenLabs       | 1         | 0.07%   |
| Artix            | 1         | 0.07%   |
| Archman          | 1         | 0.07%   |
| Android          | 1         | 0.07%   |
| ALT Linux        | 1         | 0.07%   |
| Alpine           | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 113       | 6.36%   |
| 5.14.7-desktop-1omv4050         | 51        | 2.87%   |
| 5.4.0-42-generic                | 34        | 1.91%   |
| 5.16.7-desktop-1omv4003         | 29        | 1.63%   |
| 5.4.0-58-generic                | 22        | 1.24%   |
| 5.4.0-52-generic                | 22        | 1.24%   |
| 5.4.0-26-generic                | 20        | 1.13%   |
| 5.11.0-27-generic               | 16        | 0.9%    |
| 5.3.0-40-generic                | 15        | 0.84%   |
| 5.0.0-37-generic                | 15        | 0.84%   |
| 5.13.0-30-generic               | 14        | 0.79%   |
| 5.4.0-48-generic                | 12        | 0.68%   |
| 5.4.0-40-generic                | 12        | 0.68%   |
| 5.3.0-28-generic                | 12        | 0.68%   |
| 5.4.0-65-generic                | 11        | 0.62%   |
| 5.4.0-29-generic                | 10        | 0.56%   |
| 5.11.0-37-generic               | 10        | 0.56%   |
| 5.8.0-53-generic                | 9         | 0.51%   |
| 5.4.0-91-generic                | 9         | 0.51%   |
| 5.4.0-37-generic                | 9         | 0.51%   |
| 5.10.0-8-amd64                  | 9         | 0.51%   |
| 4.15.0-43-generic               | 9         | 0.51%   |
| 5.8.0-59-generic                | 8         | 0.45%   |
| 5.8.0-50-generic                | 8         | 0.45%   |
| 5.4.0-72-generic                | 8         | 0.45%   |
| 5.4.0-56-generic                | 8         | 0.45%   |
| 5.4.0-33-generic                | 8         | 0.45%   |
| 5.3.0-42-generic                | 8         | 0.45%   |
| 5.13.0-21-generic               | 8         | 0.45%   |
| 5.0.0-32-generic                | 8         | 0.45%   |
| 5.0.0-31-generic                | 8         | 0.45%   |
| 5.0.0-29-generic                | 8         | 0.45%   |
| 5.0.0-25-generic                | 8         | 0.45%   |
| 5.8.0-48-generic                | 7         | 0.39%   |
| 5.8.0-43-generic                | 7         | 0.39%   |
| 5.8.0-41-generic                | 7         | 0.39%   |
| 5.4.0-88-generic                | 7         | 0.39%   |
| 5.4.0-67-generic                | 7         | 0.39%   |
| 5.4.0-51-generic                | 7         | 0.39%   |
| 5.3.0-45-generic                | 7         | 0.39%   |
| 5.15.0-41-generic               | 7         | 0.39%   |
| 5.15.0-40-generic               | 7         | 0.39%   |
| 5.15.0-25-generic               | 7         | 0.39%   |
| 5.13.0-39-generic               | 7         | 0.39%   |
| 5.13.0-22-generic               | 7         | 0.39%   |
| 5.11.0-25-generic               | 7         | 0.39%   |
| 5.11.0-22-generic               | 7         | 0.39%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 7         | 0.39%   |
| 4.18.0-25-generic               | 7         | 0.39%   |
| 5.8.0-38-generic                | 6         | 0.34%   |
| 5.8.0-29-generic                | 6         | 0.34%   |
| 5.4.0-80-generic                | 6         | 0.34%   |
| 5.4.0-77-generic                | 6         | 0.34%   |
| 5.4.0-7642-generic              | 6         | 0.34%   |
| 5.4.0-70-generic                | 6         | 0.34%   |
| 5.4.0-62-generic                | 6         | 0.34%   |
| 5.4.0-53-generic                | 6         | 0.34%   |
| 5.4.0-31-generic                | 6         | 0.34%   |
| 5.3.0-46-generic                | 6         | 0.34%   |
| 5.3.0-26-generic                | 6         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 298       | 18.03%  |
| 5.10.14 | 113       | 6.84%   |
| 4.15.0  | 109       | 6.59%   |
| 5.8.0   | 100       | 6.05%   |
| 5.11.0  | 96        | 5.81%   |
| 5.3.0   | 92        | 5.57%   |
| 5.13.0  | 87        | 5.26%   |
| 5.0.0   | 71        | 4.3%    |
| 4.18.0  | 55        | 3.33%   |
| 5.14.7  | 52        | 3.15%   |
| 5.15.0  | 38        | 2.3%    |
| 5.10.0  | 32        | 1.94%   |
| 5.16.7  | 30        | 1.81%   |
| 4.19.0  | 16        | 0.97%   |
| 3.10.0  | 11        | 0.67%   |
| 4.9.20  | 9         | 0.54%   |
| 5.16.11 | 8         | 0.48%   |
| 5.15.12 | 7         | 0.42%   |
| 5.11.12 | 7         | 0.42%   |
| 5.9.16  | 6         | 0.36%   |
| 5.9.0   | 6         | 0.36%   |
| 5.12.4  | 6         | 0.36%   |
| 4.4.0   | 6         | 0.36%   |
| 4.13.0  | 6         | 0.36%   |
| 5.8.18  | 5         | 0.3%    |
| 5.14.10 | 5         | 0.3%    |
| 5.14.0  | 5         | 0.3%    |
| 5.7.0   | 4         | 0.24%   |
| 5.6.6   | 4         | 0.24%   |
| 5.6.16  | 4         | 0.24%   |
| 5.6.0   | 4         | 0.24%   |
| 5.3.18  | 4         | 0.24%   |
| 5.17.5  | 4         | 0.24%   |
| 5.17.1  | 4         | 0.24%   |
| 5.16.0  | 4         | 0.24%   |
| 5.13.4  | 4         | 0.24%   |
| 5.13.19 | 4         | 0.24%   |
| 5.11.16 | 4         | 0.24%   |
| 5.11.11 | 4         | 0.24%   |
| 5.10.74 | 4         | 0.24%   |
| 5.10.52 | 4         | 0.24%   |
| 4.9.60  | 4         | 0.24%   |
| 5.8.9   | 3         | 0.18%   |
| 5.8.15  | 3         | 0.18%   |
| 5.8.13  | 3         | 0.18%   |
| 5.8.11  | 3         | 0.18%   |
| 5.7.12  | 3         | 0.18%   |
| 5.4.72  | 3         | 0.18%   |
| 5.4.15  | 3         | 0.18%   |
| 5.18.0  | 3         | 0.18%   |
| 5.17.9  | 3         | 0.18%   |
| 5.17.7  | 3         | 0.18%   |
| 5.17.4  | 3         | 0.18%   |
| 5.16.2  | 3         | 0.18%   |
| 5.15.6  | 3         | 0.18%   |
| 5.15.5  | 3         | 0.18%   |
| 5.15.34 | 3         | 0.18%   |
| 5.15.13 | 3         | 0.18%   |
| 5.14.15 | 3         | 0.18%   |
| 5.14.14 | 3         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 322       | 19.6%   |
| 5.10    | 183       | 11.14%  |
| 5.8     | 133       | 8.09%   |
| 5.11    | 129       | 7.85%   |
| 4.15    | 111       | 6.76%   |
| 5.13    | 104       | 6.33%   |
| 5.3     | 103       | 6.27%   |
| 5.0     | 77        | 4.69%   |
| 5.14    | 76        | 4.63%   |
| 5.15    | 71        | 4.32%   |
| 5.16    | 59        | 3.59%   |
| 4.18    | 58        | 3.53%   |
| 5.9     | 25        | 1.52%   |
| 5.17    | 25        | 1.52%   |
| 5.6     | 23        | 1.4%    |
| 5.12    | 21        | 1.28%   |
| 4.19    | 21        | 1.28%   |
| 4.9     | 20        | 1.22%   |
| 5.7     | 14        | 0.85%   |
| 5.18    | 14        | 0.85%   |
| 3.10    | 12        | 0.73%   |
| 5.5     | 11        | 0.67%   |
| 4.4     | 6         | 0.37%   |
| 4.13    | 6         | 0.37%   |
| 5.1     | 4         | 0.24%   |
| 5.2     | 3         | 0.18%   |
| 4.17    | 3         | 0.18%   |
| 4.14    | 3         | 0.18%   |
| 4.1     | 2         | 0.12%   |
| 4.8     | 1         | 0.06%   |
| 4.20    | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 2.6     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1444      | 95.76%  |
| i686    | 53        | 3.51%   |
| aarch64 | 9         | 0.6%    |
| armv8l  | 1         | 0.07%   |
| armv7l  | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 613       | 39.29%  |
| KDE5            | 319       | 20.45%  |
| Unknown         | 250       | 16.03%  |
| XFCE            | 114       | 7.31%   |
| X-Cinnamon      | 70        | 4.49%   |
| KDE             | 46        | 2.95%   |
| MATE            | 36        | 2.31%   |
| Cinnamon        | 30        | 1.92%   |
| KDE4            | 13        | 0.83%   |
| Unity           | 11        | 0.71%   |
| Pantheon        | 11        | 0.71%   |
| LXQt            | 10        | 0.64%   |
| LXDE            | 9         | 0.58%   |
| GNOME Flashback | 7         | 0.45%   |
| i3              | 4         | 0.26%   |
| awesome         | 4         | 0.26%   |
| openbox         | 3         | 0.19%   |
| XSession        | 1         | 0.06%   |
| xinitrc         | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| GNUstep         | 1         | 0.06%   |
| GNOME Classic   | 1         | 0.06%   |
| Enlightenment   | 1         | 0.06%   |
| DWM             | 1         | 0.06%   |
| custom          | 1         | 0.06%   |
| Core            | 1         | 0.06%   |
| Budgie          | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1210      | 78.27%  |
| Wayland | 179       | 11.58%  |
| Unknown | 136       | 8.8%    |
| Tty     | 21        | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 798       | 51.32%  |
| SDDM    | 305       | 19.61%  |
| GDM     | 184       | 11.83%  |
| LightDM | 91        | 5.85%   |
| GDM3    | 86        | 5.53%   |
| TDM     | 71        | 4.57%   |
| KDM     | 12        | 0.77%   |
| XDM     | 4         | 0.26%   |
| LXDM    | 2         | 0.13%   |
| SLiM    | 1         | 0.06%   |
| Ly      | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| cs_CZ   | 802       | 52.11%  |
| en_US   | 416       | 27.03%  |
| Unknown | 224       | 14.55%  |
| en_GB   | 34        | 2.21%   |
| C       | 24        | 1.56%   |
| ru_RU   | 10        | 0.65%   |
| sk_SK   | 8         | 0.52%   |
| POSIX   | 4         | 0.26%   |
| pl_PL   | 3         | 0.19%   |
| fr_FR   | 2         | 0.13%   |
| uk_UA   | 1         | 0.06%   |
| ro_RO   | 1         | 0.06%   |
| pt_PT   | 1         | 0.06%   |
| it_IT   | 1         | 0.06%   |
| fi_FI   | 1         | 0.06%   |
| es_ES   | 1         | 0.06%   |
| en_NG   | 1         | 0.06%   |
| en_CA   | 1         | 0.06%   |
| en_AU   | 1         | 0.06%   |
| en_150  | 1         | 0.06%   |
| el_GR   | 1         | 0.06%   |
| de_DE   | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 857       | 55.58%  |
| EFI  | 685       | 44.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1067      | 69.38%  |
| Overlay  | 226       | 14.69%  |
| Btrfs    | 115       | 7.48%   |
| Unknown  | 64        | 4.16%   |
| Xfs      | 41        | 2.67%   |
| Zfs      | 9         | 0.59%   |
| Ext3     | 4         | 0.26%   |
| Ext2     | 4         | 0.26%   |
| Tmpfs    | 2         | 0.13%   |
| Reiserfs | 2         | 0.13%   |
| F2fs     | 2         | 0.13%   |
| Aufs     | 2         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 830       | 54.21%  |
| GPT     | 441       | 28.8%   |
| MBR     | 260       | 16.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1339      | 87.69%  |
| Yes       | 188       | 12.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1004      | 65.36%  |
| Yes       | 532       | 34.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 327       | 21.7%   |
| Lenovo                  | 260       | 17.25%  |
| Hewlett-Packard         | 240       | 15.93%  |
| Dell                    | 160       | 10.62%  |
| Gigabyte Technology     | 117       | 7.76%   |
| Acer                    | 101       | 6.7%    |
| MSI                     | 90        | 5.97%   |
| ASRock                  | 33        | 2.19%   |
| Intel                   | 25        | 1.66%   |
| Toshiba                 | 14        | 0.93%   |
| Sony                    | 13        | 0.86%   |
| Fujitsu                 | 12        | 0.8%    |
| UMAX                    | 9         | 0.6%    |
| Raspberry Pi Foundation | 9         | 0.6%    |
| Unknown                 | 9         | 0.6%    |
| Fujitsu Siemens         | 6         | 0.4%    |
| Apple                   | 6         | 0.4%    |
| AMI                     | 5         | 0.33%   |
| Supermicro              | 4         | 0.27%   |
| Pegatron                | 4         | 0.27%   |
| HUAWEI                  | 4         | 0.27%   |
| Google                  | 4         | 0.27%   |
| ZOTAC                   | 3         | 0.2%    |
| TUXEDO                  | 3         | 0.2%    |
| Packard Bell            | 3         | 0.2%    |
| Microsoft               | 3         | 0.2%    |
| Timi                    | 2         | 0.13%   |
| Insyde                  | 2         | 0.13%   |
| IBM                     | 2         | 0.13%   |
| Foxconn                 | 2         | 0.13%   |
| Clientron               | 2         | 0.13%   |
| Chuwi                   | 2         | 0.13%   |
| Biostar                 | 2         | 0.13%   |
| Alienware               | 2         | 0.13%   |
| Wortmann AG             | 1         | 0.07%   |
| Valve                   | 1         | 0.07%   |
| SIEMENS                 | 1         | 0.07%   |
| Seeed Studio            | 1         | 0.07%   |
| Samsung Electronics     | 1         | 0.07%   |
| Purism                  | 1         | 0.07%   |
| Prestigio               | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| Notebook                | 1         | 0.07%   |
| Minix                   | 1         | 0.07%   |
| Medion                  | 1         | 0.07%   |
| Le Cube 1               | 1         | 0.07%   |
| Kiano                   | 1         | 0.07%   |
| Jumper                  | 1         | 0.07%   |
| INET                    | 1         | 0.07%   |
| In-Sing                 | 1         | 0.07%   |
| ICP / iEi               | 1         | 0.07%   |
| EVGA                    | 1         | 0.07%   |
| EUROCOM                 | 1         | 0.07%   |
| ELSKY                   | 1         | 0.07%   |
| Dynabook                | 1         | 0.07%   |
| DATABOX                 | 1         | 0.07%   |
| Clevo                   | 1         | 0.07%   |
| Cisco Systems           | 1         | 0.07%   |
| Bluechip Computer       | 1         | 0.07%   |
| ASRockRack              | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 95        | 6.3%    |
| Unknown                               | 11        | 0.73%   |
| ASUS All Series                       | 7         | 0.46%   |
| HP ProBook 455 G7                     | 6         | 0.4%    |
| RPi Raspberry Pi                      | 5         | 0.33%   |
| MSI MS-7A34                           | 5         | 0.33%   |
| MSI MS-7693                           | 5         | 0.33%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.33%   |
| HP ProLiant DL380e Gen8               | 5         | 0.33%   |
| Dell Latitude E6400                   | 5         | 0.33%   |
| Dell Latitude 5401                    | 5         | 0.33%   |
| MSI MS-7C02                           | 4         | 0.27%   |
| HP ProDesk 405 G6 Desktop Mini PC     | 4         | 0.27%   |
| HP ProBook 4540s                      | 4         | 0.27%   |
| HP ProBook 4530s                      | 4         | 0.27%   |
| HP ProBook 450 G5                     | 4         | 0.27%   |
| HP Notebook                           | 4         | 0.27%   |
| HP EliteBook 840 G6                   | 4         | 0.27%   |
| Dell XPS 15 7590                      | 4         | 0.27%   |
| Dell Precision M6500                  | 4         | 0.27%   |
| Acer Extensa 5620                     | 4         | 0.27%   |
| MSI MS-7592                           | 3         | 0.2%    |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.2%    |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.2%    |
| HP ProBook 4510s                      | 3         | 0.2%    |
| HP Pavilion dv7                       | 3         | 0.2%    |
| HP Pavilion dv6                       | 3         | 0.2%    |
| HP ENVY x360 Convertible 15-cn0xxx    | 3         | 0.2%    |
| HP EliteBook 855 G7 Notebook PC       | 3         | 0.2%    |
| HP EliteBook 850 G6                   | 3         | 0.2%    |
| HP EliteBook 840 G3                   | 3         | 0.2%    |
| HP Compaq 8200 Elite SFF PC           | 3         | 0.2%    |
| HP 250 G6 Notebook PC                 | 3         | 0.2%    |
| Gigabyte B450 AORUS ELITE             | 3         | 0.2%    |
| Gigabyte 970A-DS3P                    | 3         | 0.2%    |
| Dell XPS 15 9560                      | 3         | 0.2%    |
| Dell Latitude E6420                   | 3         | 0.2%    |
| Dell Latitude E5520                   | 3         | 0.2%    |
| Dell Latitude E5470                   | 3         | 0.2%    |
| Dell Latitude 5480                    | 3         | 0.2%    |
| ASUS T102HA                           | 3         | 0.2%    |
| ASUS ROG STRIX B550-F GAMING          | 3         | 0.2%    |
| ASUS P5G41T-M LX                      | 3         | 0.2%    |
| ASUS E502SA                           | 3         | 0.2%    |
| Acer Extensa 5235                     | 3         | 0.2%    |
| Acer Extensa 5220                     | 3         | 0.2%    |
| RPi Raspberry Pi 4 Model B Rev 1.1    | 2         | 0.13%   |
| Pegatron h9-1000cs                    | 2         | 0.13%   |
| MSI MS-7C91                           | 2         | 0.13%   |
| MSI MS-7C84                           | 2         | 0.13%   |
| MSI MS-7C37                           | 2         | 0.13%   |
| MSI MS-7B79                           | 2         | 0.13%   |
| MSI MS-7817                           | 2         | 0.13%   |
| MSI MS-7512                           | 2         | 0.13%   |
| MSI GE620/GE620DX/FX620DX/FX623       | 2         | 0.13%   |
| Lenovo Z50-75 80EC                    | 2         | 0.13%   |
| Lenovo Yoga Duet 7 13ITL6 82MA        | 2         | 0.13%   |
| Lenovo Yoga C740-14IML 81TC           | 2         | 0.13%   |
| Lenovo Yoga 500-15IBD 80N6            | 2         | 0.13%   |
| Lenovo V330-15IKB 81AX                | 2         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 129       | 8.56%   |
| ASUS UX31E            | 95        | 6.3%    |
| Dell Latitude         | 68        | 4.51%   |
| Acer Aspire           | 61        | 4.05%   |
| HP ProBook            | 53        | 3.52%   |
| HP EliteBook          | 52        | 3.45%   |
| Lenovo IdeaPad        | 40        | 2.65%   |
| HP Compaq             | 27        | 1.79%   |
| HP Pavilion           | 25        | 1.66%   |
| Dell XPS              | 22        | 1.46%   |
| ASUS ROG              | 21        | 1.39%   |
| ASUS PRIME            | 20        | 1.33%   |
| Dell Precision        | 19        | 1.26%   |
| Dell Inspiron         | 19        | 1.26%   |
| Lenovo Yoga           | 17        | 1.13%   |
| Toshiba Satellite     | 13        | 0.86%   |
| Dell OptiPlex         | 13        | 0.86%   |
| Acer Extensa          | 13        | 0.86%   |
| ASUS TUF              | 12        | 0.8%    |
| HP ENVY               | 11        | 0.73%   |
| Unknown               | 11        | 0.73%   |
| Lenovo ThinkCentre    | 10        | 0.66%   |
| RPi Raspberry         | 9         | 0.6%    |
| Lenovo Legion         | 9         | 0.6%    |
| HP ProDesk            | 9         | 0.6%    |
| Dell Vostro           | 9         | 0.6%    |
| Acer TravelMate       | 9         | 0.6%    |
| Lenovo ThinkBook      | 8         | 0.53%   |
| HP ZBook              | 8         | 0.53%   |
| HP Laptop             | 8         | 0.53%   |
| ASUS ZenBook          | 8         | 0.53%   |
| ASUS VivoBook         | 8         | 0.53%   |
| Fujitsu LIFEBOOK      | 7         | 0.46%   |
| ASUS All              | 7         | 0.46%   |
| Acer Swift            | 7         | 0.46%   |
| UMAX VisionBook       | 6         | 0.4%    |
| HP ProLiant           | 6         | 0.4%    |
| HP EliteDesk          | 6         | 0.4%    |
| HP 250                | 6         | 0.4%    |
| Gigabyte B450         | 6         | 0.4%    |
| MSI MS-7A34           | 5         | 0.33%   |
| MSI MS-7693           | 5         | 0.33%   |
| MSI MS-7C02           | 4         | 0.27%   |
| HP Notebook           | 4         | 0.27%   |
| Gigabyte X570         | 4         | 0.27%   |
| ASUS M5A97            | 4         | 0.27%   |
| ASRock B450M          | 4         | 0.27%   |
| MSI MS-7592           | 3         | 0.2%    |
| Microsoft Surface     | 3         | 0.2%    |
| HP Spectre            | 3         | 0.2%    |
| Gigabyte Z390         | 3         | 0.2%    |
| Gigabyte TRILINE      | 3         | 0.2%    |
| Gigabyte 970A-DS3P    | 3         | 0.2%    |
| Fujitsu Siemens AMILO | 3         | 0.2%    |
| Fujitsu ESPRIMO       | 3         | 0.2%    |
| Dell PowerEdge        | 3         | 0.2%    |
| Dell G5               | 3         | 0.2%    |
| ASUS T102HA           | 3         | 0.2%    |
| ASUS P5G41T-M         | 3         | 0.2%    |
| ASUS E502SA           | 3         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 187       | 12.41%  |
| 2018    | 142       | 9.42%   |
| 2019    | 137       | 9.09%   |
| 2020    | 134       | 8.89%   |
| 2012    | 113       | 7.5%    |
| 2017    | 111       | 7.37%   |
| 2014    | 84        | 5.57%   |
| 2013    | 84        | 5.57%   |
| 2008    | 79        | 5.24%   |
| 2015    | 78        | 5.18%   |
| 2021    | 66        | 4.38%   |
| 2016    | 66        | 4.38%   |
| 2010    | 61        | 4.05%   |
| 2007    | 60        | 3.98%   |
| 2009    | 58        | 3.85%   |
| 2006    | 20        | 1.33%   |
| Unknown | 13        | 0.86%   |
| 2005    | 6         | 0.4%    |
| 2004    | 4         | 0.27%   |
| 2022    | 3         | 0.2%    |
| 2000    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 908       | 60.25%  |
| Desktop        | 486       | 32.25%  |
| Convertible    | 41        | 2.72%   |
| Mini pc        | 22        | 1.46%   |
| Server         | 15        | 1%      |
| Tablet         | 12        | 0.8%    |
| All in one     | 12        | 0.8%    |
| System on chip | 10        | 0.66%   |
| Phone          | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1380      | 90.73%  |
| Enabled  | 141       | 9.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1503      | 99.73%  |
| Yes  | 4         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 401       | 26.11%  |
| 4.01-8.0        | 276       | 17.97%  |
| 8.01-16.0       | 264       | 17.19%  |
| 16.01-24.0      | 262       | 17.06%  |
| 32.01-64.0      | 146       | 9.51%   |
| 1.01-2.0        | 89        | 5.79%   |
| 24.01-32.0      | 27        | 1.76%   |
| 64.01-256.0     | 27        | 1.76%   |
| 2.01-3.0        | 26        | 1.69%   |
| 0.51-1.0        | 14        | 0.91%   |
| More than 256.0 | 2         | 0.13%   |
| 0.01-0.5        | 2         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 641       | 38.59%  |
| 2.01-3.0   | 345       | 20.77%  |
| 4.01-8.0   | 244       | 14.69%  |
| 3.01-4.0   | 181       | 10.9%   |
| 0.51-1.0   | 117       | 7.04%   |
| 8.01-16.0  | 88        | 5.3%    |
| 0.01-0.5   | 21        | 1.26%   |
| 16.01-24.0 | 14        | 0.84%   |
| 32.01-64.0 | 6         | 0.36%   |
| 24.01-32.0 | 3         | 0.18%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1009      | 64.97%  |
| 2      | 330       | 21.25%  |
| 3      | 101       | 6.5%    |
| 4      | 42        | 2.7%    |
| 5      | 24        | 1.55%   |
| 0      | 20        | 1.29%   |
| 6      | 13        | 0.84%   |
| 7      | 9         | 0.58%   |
| 8      | 4         | 0.26%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 942       | 62.01%  |
| Yes       | 577       | 37.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1328      | 87.66%  |
| No        | 187       | 12.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1108      | 73.23%  |
| No        | 405       | 26.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 824       | 54.03%  |
| No        | 701       | 45.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Czechia | 1507      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Prague               | 585       | 37.74%  |
| Brno                 | 143       | 9.23%   |
| Ostrava              | 41        | 2.65%   |
| Pilsen               | 30        | 1.94%   |
| Hradec Králové     | 23        | 1.48%   |
| Pardubice            | 20        | 1.29%   |
| České Budějovice  | 20        | 1.29%   |
| Olomouc              | 19        | 1.23%   |
| Liberec              | 18        | 1.16%   |
| Zlín                | 16        | 1.03%   |
| Havířov            | 13        | 0.84%   |
| Znojmo               | 10        | 0.65%   |
| Chomutov             | 10        | 0.65%   |
| Jihlava              | 9         | 0.58%   |
| Ústí nad Labem     | 8         | 0.52%   |
| Most                 | 8         | 0.52%   |
| Frýdek-Místek      | 8         | 0.52%   |
| Přerov              | 7         | 0.45%   |
| Uherské Hradiště  | 6         | 0.39%   |
| Praha 10             | 6         | 0.39%   |
| Opava                | 6         | 0.39%   |
| Kralupy nad Vltavou  | 6         | 0.39%   |
| Kladno               | 6         | 0.39%   |
| Karlovy Vary         | 6         | 0.39%   |
| As                   | 6         | 0.39%   |
| Třebíč            | 5         | 0.32%   |
| Teplice              | 5         | 0.32%   |
| Rumburk              | 5         | 0.32%   |
| Roznov pod Radhostem | 5         | 0.32%   |
| Příbram            | 5         | 0.32%   |
| Odolena Voda         | 5         | 0.32%   |
| Mariánské Lázně  | 5         | 0.32%   |
| Litoměřice         | 5         | 0.32%   |
| Česká Lípa        | 5         | 0.32%   |
| Vyškov              | 4         | 0.26%   |
| Vsetin               | 4         | 0.26%   |
| Uvaly                | 4         | 0.26%   |
| Uhlirske Janovice    | 4         | 0.26%   |
| Trinec               | 4         | 0.26%   |
| Sokolov              | 4         | 0.26%   |
| Slavkov u Brna       | 4         | 0.26%   |
| Roztoky              | 4         | 0.26%   |
| Rakvice              | 4         | 0.26%   |
| Novy Jicin           | 4         | 0.26%   |
| Mladá Boleslav      | 4         | 0.26%   |
| Klasterec nad Ohri   | 4         | 0.26%   |
| Jindrichuv Hradec    | 4         | 0.26%   |
| Dolni Roven          | 4         | 0.26%   |
| Český Těšín     | 4         | 0.26%   |
| Celakovice           | 4         | 0.26%   |
| Bohumin              | 4         | 0.26%   |
| Zelenec              | 3         | 0.19%   |
| Zdar                 | 3         | 0.19%   |
| Zdanice              | 3         | 0.19%   |
| Žatec               | 3         | 0.19%   |
| Vrchlabi             | 3         | 0.19%   |
| Velke Mezirici       | 3         | 0.19%   |
| Trutnov              | 3         | 0.19%   |
| Tábor               | 3         | 0.19%   |
| Rakovnik             | 3         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 356       | 564    | 17.05%  |
| Samsung Electronics            | 317       | 449    | 15.18%  |
| Seagate                        | 306       | 462    | 14.66%  |
| SanDisk                        | 154       | 163    | 7.38%   |
| Kingston                       | 145       | 174    | 6.94%   |
| Toshiba                        | 128       | 158    | 6.13%   |
| Unknown                        | 90        | 122    | 4.31%   |
| Hitachi                        | 70        | 81     | 3.35%   |
| SK hynix                       | 58        | 67     | 2.78%   |
| A-DATA Technology              | 56        | 68     | 2.68%   |
| Intel                          | 53        | 62     | 2.54%   |
| Crucial                        | 48        | 59     | 2.3%    |
| HGST                           | 41        | 49     | 1.96%   |
| Patriot                        | 36        | 46     | 1.72%   |
| Micron Technology              | 36        | 52     | 1.72%   |
| Transcend                      | 15        | 23     | 0.72%   |
| Phison                         | 13        | 24     | 0.62%   |
| KIOXIA                         | 11        | 15     | 0.53%   |
| OCZ                            | 10        | 29     | 0.48%   |
| Gigabyte Technology            | 10        | 14     | 0.48%   |
| Maxtor                         | 9         | 13     | 0.43%   |
| Fujitsu                        | 9         | 10     | 0.43%   |
| LITEONIT                       | 8         | 10     | 0.38%   |
| Apacer                         | 8         | 11     | 0.38%   |
| China                          | 7         | 8      | 0.34%   |
| XPG                            | 6         | 8      | 0.29%   |
| Verbatim                       | 6         | 6      | 0.29%   |
| LITEON                         | 6         | 7      | 0.29%   |
| Silicon Motion                 | 5         | 5      | 0.24%   |
| JMicron Technology             | 5         | 6      | 0.24%   |
| GOODRAM                        | 5         | 8      | 0.24%   |
| Corsair                        | 5         | 5      | 0.24%   |
| ASMedia                        | 4         | 6      | 0.19%   |
| Apple                          | 4         | 7      | 0.19%   |
| UMAX                           | 3         | 3      | 0.14%   |
| Team                           | 3         | 3      | 0.14%   |
| SPCC                           | 2         | 2      | 0.1%    |
| pqi                            | 2         | 2      | 0.1%    |
| Micron/Crucial Technology      | 2         | 2      | 0.1%    |
| Lite-On                        | 2         | 4      | 0.1%    |
| Lenovo                         | 2         | 3      | 0.1%    |
| HPE                            | 2         | 3      | 0.1%    |
| External                       | 2         | 2      | 0.1%    |
| ASMT                           | 2         | 2      | 0.1%    |
| Unknown                        | 2         | 2      | 0.1%    |
| XrayDisk                       | 1         | 1      | 0.05%   |
| Western Digital                | 1         | 1      | 0.05%   |
| WDC WUH                        | 1         | 1      | 0.05%   |
| WDC WDS1                       | 1         | 1      | 0.05%   |
| UMIS                           | 1         | 1      | 0.05%   |
| TO Exter                       | 1         | 2      | 0.05%   |
| TCSUNBOW                       | 1         | 1      | 0.05%   |
| Solid State Storage Technology | 1         | 1      | 0.05%   |
| ShanDianZhe                    | 1         | 1      | 0.05%   |
| SABRENT                        | 1         | 1      | 0.05%   |
| NVMe                           | 1         | 1      | 0.05%   |
| Netac                          | 1         | 1      | 0.05%   |
| Mushkin                        | 1         | 1      | 0.05%   |
| Mass                           | 1         | 1      | 0.05%   |
| Linux                          | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB               | 95        | 4.15%   |
| Samsung SSD 860 EVO 500GB            | 28        | 1.22%   |
| Samsung NVMe SSD Drive 512GB         | 22        | 0.96%   |
| Kingston SA400S37240G 240GB SSD      | 22        | 0.96%   |
| Kingston SA400S37120G 120GB SSD      | 18        | 0.79%   |
| Unknown MMC Card  64GB               | 17        | 0.74%   |
| Samsung SSD 850 EVO 250GB            | 16        | 0.7%    |
| Kingston SA400S37480G 480GB SSD      | 16        | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB       | 15        | 0.65%   |
| HGST HTS721010A9E630 1TB             | 14        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 13        | 0.57%   |
| Unknown MMC Card  32GB               | 13        | 0.57%   |
| Toshiba NVMe SSD Drive 256GB         | 13        | 0.57%   |
| Samsung NVMe SSD Drive 500GB         | 13        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 12        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB       | 12        | 0.52%   |
| Samsung NVMe SSD Drive 256GB         | 12        | 0.52%   |
| Seagate ST3500418AS 500GB            | 11        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB       | 11        | 0.48%   |
| Patriot Burst 120GB SSD              | 11        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD     | 11        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 0.44%   |
| Samsung SSD 860 EVO 1TB              | 10        | 0.44%   |
| Patriot Burst 480GB SSD              | 10        | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB             | 9         | 0.39%   |
| Toshiba MQ01ABD100 1TB               | 9         | 0.39%   |
| Samsung SSD 850 EVO 500GB            | 9         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB             | 8         | 0.35%   |
| SK hynix NVMe SSD Drive 512GB        | 8         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB      | 8         | 0.35%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 0.35%   |
| SanDisk NVMe SSD Drive 512GB         | 8         | 0.35%   |
| Samsung SSD 970 EVO 1TB              | 8         | 0.35%   |
| Kingston SHFS37A120G 120GB SSD       | 8         | 0.35%   |
| Intel NVMe SSD Drive 512GB           | 8         | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 7         | 0.31%   |
| WDC WD10EZEX-08M2NA0 1TB             | 7         | 0.31%   |
| Unknown MMC Card  16GB               | 7         | 0.31%   |
| Unknown MMC Card  128GB              | 7         | 0.31%   |
| Toshiba MQ04ABF100 1TB               | 7         | 0.31%   |
| Toshiba MQ01ABF050 500GB             | 7         | 0.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB       | 7         | 0.31%   |
| SanDisk NVMe SSD Drive 1024GB        | 7         | 0.31%   |
| Samsung NVMe SSD Drive 250GB         | 7         | 0.31%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 7         | 0.31%   |
| Samsung HD103SI 1TB                  | 7         | 0.31%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 7         | 0.31%   |
| HGST HTS725050A7E630 500GB           | 7         | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 6         | 0.26%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 6         | 0.26%   |
| Toshiba NVMe SSD Drive 512GB         | 6         | 0.26%   |
| Seagate ST500LM000-SSHD-8GB          | 6         | 0.26%   |
| Seagate ST4000DM004-2CV104 4TB       | 6         | 0.26%   |
| Samsung SSD 860 EVO 250GB            | 6         | 0.26%   |
| Samsung NVMe SSD Drive 1TB           | 6         | 0.26%   |
| Samsung HD322HJ 320GB                | 6         | 0.26%   |
| Kingston SV300S37A240G 240GB SSD     | 6         | 0.26%   |
| Crucial CT480BX500SSD1 480GB         | 6         | 0.26%   |
| A-DATA SU800 256GB SSD               | 6         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 300       | 455    | 35.97%  |
| WDC                 | 276       | 446    | 33.09%  |
| Toshiba             | 73        | 81     | 8.75%   |
| Hitachi             | 70        | 81     | 8.39%   |
| Samsung Electronics | 42        | 61     | 5.04%   |
| HGST                | 41        | 49     | 4.92%   |
| Maxtor              | 9         | 13     | 1.08%   |
| Fujitsu             | 9         | 10     | 1.08%   |
| Unknown             | 4         | 4      | 0.48%   |
| pqi                 | 2         | 2      | 0.24%   |
| ASMedia             | 2         | 3      | 0.24%   |
| SABRENT             | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| External            | 1         | 1      | 0.12%   |
| ASUSTOR             | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |
| Apple               | 1         | 4      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 144       | 185    | 19.38%  |
| SanDisk             | 125       | 130    | 16.82%  |
| Kingston            | 122       | 149    | 16.42%  |
| WDC                 | 60        | 77     | 8.08%   |
| A-DATA Technology   | 51        | 61     | 6.86%   |
| Crucial             | 45        | 56     | 6.06%   |
| Patriot             | 35        | 45     | 4.71%   |
| Intel               | 22        | 25     | 2.96%   |
| Micron Technology   | 20        | 32     | 2.69%   |
| Transcend           | 14        | 21     | 1.88%   |
| Toshiba             | 12        | 14     | 1.62%   |
| SK hynix            | 12        | 12     | 1.62%   |
| OCZ                 | 8         | 13     | 1.08%   |
| LITEONIT            | 8         | 10     | 1.08%   |
| Apacer              | 8         | 11     | 1.08%   |
| China               | 7         | 8      | 0.94%   |
| Verbatim            | 6         | 6      | 0.81%   |
| LITEON              | 5         | 6      | 0.67%   |
| GOODRAM             | 5         | 8      | 0.67%   |
| Gigabyte Technology | 4         | 6      | 0.54%   |
| UMAX                | 3         | 3      | 0.4%    |
| Seagate             | 3         | 3      | 0.4%    |
| Team                | 2         | 2      | 0.27%   |
| SPCC                | 2         | 2      | 0.27%   |
| Apple               | 2         | 2      | 0.27%   |
| WDC WDS1            | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |
| UMIS                | 1         | 1      | 0.13%   |
| TO Exter            | 1         | 2      | 0.13%   |
| TCSUNBOW            | 1         | 1      | 0.13%   |
| ShanDianZhe         | 1         | 1      | 0.13%   |
| Phison              | 1         | 1      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |
| Mushkin             | 1         | 1      | 0.13%   |
| Linux               | 1         | 1      | 0.13%   |
| Innodisk            | 1         | 1      | 0.13%   |
| Hewlett-Packard     | 1         | 1      | 0.13%   |
| FORESEE             | 1         | 1      | 0.13%   |
| CT500MX5            | 1         | 1      | 0.13%   |
| ASMT                | 1         | 1      | 0.13%   |
| ADATA SU            | 1         | 1      | 0.13%   |
| ADATA SP            | 1         | 1      | 0.13%   |
| 2.5"                | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 710       | 1214   | 37.39%  |
| SSD     | 671       | 906    | 35.33%  |
| NVMe    | 419       | 586    | 22.06%  |
| MMC     | 87        | 122    | 4.58%   |
| Unknown | 12        | 16     | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1142      | 2062   | 66.82%  |
| NVMe | 418       | 584    | 24.46%  |
| MMC  | 87        | 122    | 5.09%   |
| SAS  | 62        | 76     | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 944       | 1368   | 65.88%  |
| 0.51-1.0   | 341       | 477    | 23.8%   |
| 1.01-2.0   | 72        | 145    | 5.02%   |
| 2.01-3.0   | 25        | 38     | 1.74%   |
| 3.01-4.0   | 24        | 36     | 1.67%   |
| 4.01-10.0  | 20        | 45     | 1.4%    |
| 10.01-20.0 | 7         | 11     | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 414       | 26.3%   |
| 251-500        | 310       | 19.7%   |
| 1-20           | 214       | 13.6%   |
| 501-1000       | 192       | 12.2%   |
| 51-100         | 119       | 7.56%   |
| 1001-2000      | 104       | 6.61%   |
| 21-50          | 68        | 4.32%   |
| Unknown        | 66        | 4.19%   |
| More than 3000 | 61        | 3.88%   |
| 2001-3000      | 26        | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 712       | 43.79%  |
| 21-50          | 206       | 12.67%  |
| 101-250        | 195       | 11.99%  |
| 51-100         | 161       | 9.9%    |
| 251-500        | 120       | 7.38%   |
| 501-1000       | 78        | 4.8%    |
| Unknown        | 66        | 4.06%   |
| 1001-2000      | 42        | 2.58%   |
| More than 3000 | 31        | 1.91%   |
| 2001-3000      | 15        | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 95        | 95     | 44.81%  |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.42%   |
| WDC WD60EFRX-68L0BN1 6TB              | 2         | 3      | 0.94%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.94%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 2         | 2      | 0.94%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.94%   |
| Seagate ST3160318AS 160GB             | 2         | 2      | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.94%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.94%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.94%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.47%   |
| WDC WD800BB-00JHA0 80GB               | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.47%   |
| WDC WD7500AADS-00M2B0 752GB           | 1         | 1      | 0.47%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.47%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.47%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.47%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.47%   |
| WDC WD2500BPVT-22JJ5T0 250GB          | 1         | 1      | 0.47%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.47%   |
| WDC WD2500AAKX-60U6AA0 250GB          | 1         | 1      | 0.47%   |
| WDC WD2500AAKX-603CA0 250GB           | 1         | 1      | 0.47%   |
| WDC WD2500AAKX-083CA1 250GB           | 1         | 1      | 0.47%   |
| WDC WD2500AAJS-08L7A0 250GB           | 1         | 2      | 0.47%   |
| WDC WD20EARX-008FB0 2TB               | 1         | 2      | 0.47%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 0.47%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 1      | 0.47%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 1      | 0.47%   |
| WDC WD10EZEX-35M2NA0 1TB              | 1         | 1      | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.47%   |
| WDC WD1001FALS-40K1B0 1TB             | 1         | 1      | 0.47%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.47%   |
| Toshiba MK8037GSX 80GB                | 1         | 1      | 0.47%   |
| Toshiba MK6465GSXN 640GB              | 1         | 1      | 0.47%   |
| Toshiba MK5056GSY 500GB               | 1         | 1      | 0.47%   |
| Toshiba MK2552GSX 250GB               | 1         | 1      | 0.47%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 0.47%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 1      | 0.47%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.47%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 0.47%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 0.47%   |
| Seagate ST9250410ASG 250GB            | 1         | 1      | 0.47%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 0.47%   |
| Seagate ST9200420ASG 200GB            | 1         | 1      | 0.47%   |
| Seagate ST8000VN0002-1Z8112 8TB       | 1         | 1      | 0.47%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 0.47%   |
| Seagate ST500LT0 12-1DG142 500GB      | 1         | 1      | 0.47%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 0.47%   |
| Seagate ST500DM005 HD502HJ 500GB      | 1         | 3      | 0.47%   |
| Seagate ST500DM002-1SB10A 500GB       | 1         | 1      | 0.47%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 0.47%   |
| Seagate ST3500410SV 500GB             | 1         | 1      | 0.47%   |
| Seagate ST3320620A 320GB              | 1         | 1      | 0.47%   |
| Seagate ST3250620NS 250GB             | 1         | 2      | 0.47%   |
| Seagate ST3250410AS 250GB             | 1         | 2      | 0.47%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 0.47%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 0.47%   |
| Seagate ST3160815SV 160GB             | 1         | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 97        | 97     | 46.19%  |
| Seagate             | 34        | 42     | 16.19%  |
| WDC                 | 23        | 27     | 10.95%  |
| Hitachi             | 12        | 12     | 5.71%   |
| Toshiba             | 8         | 8      | 3.81%   |
| Samsung Electronics | 8         | 8      | 3.81%   |
| HGST                | 6         | 6      | 2.86%   |
| SK hynix            | 4         | 4      | 1.9%    |
| Kingston            | 4         | 4      | 1.9%    |
| Micron Technology   | 3         | 3      | 1.43%   |
| A-DATA Technology   | 3         | 4      | 1.43%   |
| Intel               | 2         | 2      | 0.95%   |
| Crucial             | 2         | 2      | 0.95%   |
| Maxtor              | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |
| Fujitsu             | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 42     | 37.78%  |
| WDC                 | 22        | 25     | 24.44%  |
| Hitachi             | 12        | 12     | 13.33%  |
| Toshiba             | 8         | 8      | 8.89%   |
| HGST                | 6         | 6      | 6.67%   |
| Samsung Electronics | 5         | 5      | 5.56%   |
| Maxtor              | 1         | 1      | 1.11%   |
| IBM/Hitachi         | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 1      | 1.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 118       | 119    | 56.46%  |
| HDD  | 88        | 101    | 42.11%  |
| NVMe | 3         | 3      | 1.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 2         | 3      | 66.67%  |
| Unknown 00000  16GB       | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 66.67%  |
| Unknown | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 870       | 1741   | 54.14%  |
| Works    | 527       | 876    | 32.79%  |
| Malfunc  | 207       | 223    | 12.88%  |
| Failed   | 3         | 4      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1007      | 54.73%  |
| AMD                              | 289       | 15.71%  |
| Samsung Electronics              | 154       | 8.37%   |
| SanDisk                          | 59        | 3.21%   |
| SK hynix                         | 43        | 2.34%   |
| Toshiba America Info Systems     | 42        | 2.28%   |
| JMicron Technology               | 31        | 1.68%   |
| Kingston Technology Company      | 23        | 1.25%   |
| Nvidia                           | 22        | 1.2%    |
| Marvell Technology Group         | 22        | 1.2%    |
| ASMedia Technology               | 22        | 1.2%    |
| Phison Electronics               | 21        | 1.14%   |
| Micron Technology                | 16        | 0.87%   |
| KIOXIA                           | 14        | 0.76%   |
| ADATA Technology                 | 13        | 0.71%   |
| Silicon Motion                   | 10        | 0.54%   |
| VIA Technologies                 | 8         | 0.43%   |
| Hewlett-Packard                  | 6         | 0.33%   |
| Micron/Crucial Technology        | 5         | 0.27%   |
| Union Memory (Shenzhen)          | 3         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| Seagate Technology               | 3         | 0.16%   |
| LSI Logic / Symbios Logic        | 3         | 0.16%   |
| Lite-On Technology               | 3         | 0.16%   |
| Adaptec                          | 3         | 0.16%   |
| Silicon Image                    | 2         | 0.11%   |
| OCZ Technology Group             | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| Integrated Technology Express    | 2         | 0.11%   |
| Western Digital                  | 1         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| Promise Technology               | 1         | 0.05%   |
| Chelsio Communications           | 1         | 0.05%   |
| Broadcom / LSI                   | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| 3ware                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 180       | 8.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 142       | 6.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 85        | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 73        | 3.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 61        | 2.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 59        | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 47        | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 39        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 39        | 1.8%    |
| AMD 400 Series Chipset SATA Controller                                           | 38        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 37        | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 35        | 1.62%   |
| Samsung NVMe SSD Controller 980                                                  | 34        | 1.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 33        | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 31        | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 28        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 27        | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 25        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 23        | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 23        | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 22        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                              | 22        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 22        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 22        | 1.02%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 21        | 0.97%   |
| JMicron JMB363 SATA/IDE Controller                                               | 20        | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 20        | 0.92%   |
| AMD 500 Series Chipset SATA Controller                                           | 20        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 19        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 17        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 17        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 17        | 0.78%   |
| Micron Non-Volatile memory controller                                            | 16        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 15        | 0.69%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 15        | 0.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 15        | 0.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 15        | 0.69%   |
| SK hynix Gold P31 SSD                                                            | 14        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 14        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                           | 14        | 0.65%   |
| Intel SSD 660P Series                                                            | 13        | 0.6%    |
| Intel SATA Controller [RAID mode]                                                | 13        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 13        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 13        | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 12        | 0.55%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 12        | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 12        | 0.55%   |
| SK hynix BC511                                                                   | 11        | 0.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 10        | 0.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.46%   |
| SK hynix Non-Volatile memory controller                                          | 9         | 0.42%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.42%   |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1084      | 57.69%  |
| NVMe | 425       | 22.62%  |
| IDE  | 262       | 13.94%  |
| RAID | 100       | 5.32%   |
| SAS  | 4         | 0.21%   |
| SCSI | 4         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1138      | 75.51%  |
| AMD      | 358       | 23.76%  |
| ARM      | 10        | 0.66%   |
| QUALCOMM | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 95        | 6.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 14        | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 0.86%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.86%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.79%   |
| AMD Ryzen 5 3600 6-Core Processor             | 12        | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 10        | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.66%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 9         | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.59%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 9         | 0.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.53%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 8         | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.53%   |
| ARM Processor                                 | 8         | 0.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.53%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.46%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 7         | 0.46%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 7         | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.46%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 7         | 0.46%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 7         | 0.46%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 6         | 0.4%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 6         | 0.4%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.4%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 0.4%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.4%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 0.4%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.4%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.4%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 6         | 0.4%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 0.4%    |
| AMD Ryzen 7 1700 Eight-Core Processor         | 6         | 0.4%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 0.4%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 6         | 0.4%    |
| AMD FX-8350 Eight-Core Processor              | 6         | 0.4%    |
| AMD FX-8300 Eight-Core Processor              | 6         | 0.4%    |
| AMD FX-6300 Six-Core Processor                | 6         | 0.4%    |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 5         | 0.33%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 5         | 0.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 5         | 0.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.33%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 346       | 22.84%  |
| Intel Core i5           | 288       | 19.01%  |
| Intel Core 2 Duo        | 103       | 6.8%    |
| Intel Core i3           | 82        | 5.41%   |
| Intel Celeron           | 82        | 5.41%   |
| AMD Ryzen 5             | 82        | 5.41%   |
| Other                   | 55        | 3.63%   |
| AMD Ryzen 7             | 54        | 3.56%   |
| Intel Pentium           | 44        | 2.9%    |
| Intel Xeon              | 31        | 2.05%   |
| Intel Atom              | 30        | 1.98%   |
| AMD FX                  | 30        | 1.98%   |
| AMD Ryzen 7 PRO         | 24        | 1.58%   |
| Intel Pentium Dual-Core | 17        | 1.12%   |
| AMD Ryzen 9             | 16        | 1.06%   |
| AMD A8                  | 14        | 0.92%   |
| Intel Core 2            | 13        | 0.86%   |
| AMD A4                  | 13        | 0.86%   |
| AMD Athlon 64 X2        | 12        | 0.79%   |
| AMD A6                  | 12        | 0.79%   |
| Intel Pentium Dual      | 10        | 0.66%   |
| Intel Core 2 Quad       | 10        | 0.66%   |
| AMD A10                 | 10        | 0.66%   |
| AMD Ryzen 3             | 9         | 0.59%   |
| AMD Phenom II X4        | 9         | 0.59%   |
| Intel Pentium Silver    | 7         | 0.46%   |
| AMD Ryzen 5 PRO         | 7         | 0.46%   |
| Intel Pentium Gold      | 6         | 0.4%    |
| Intel Core i9           | 6         | 0.4%    |
| Intel Celeron M         | 6         | 0.4%    |
| AMD Athlon II X2        | 6         | 0.4%    |
| AMD Athlon              | 6         | 0.4%    |
| Intel Pentium M         | 4         | 0.26%   |
| Intel Pentium 4         | 4         | 0.26%   |
| AMD Turion II           | 4         | 0.26%   |
| AMD E1                  | 4         | 0.26%   |
| AMD Athlon II X4        | 4         | 0.26%   |
| Intel Genuine           | 3         | 0.2%    |
| Intel Celeron Dual-Core | 3         | 0.2%    |
| AMD Turion 64 X2 Mobile | 3         | 0.2%    |
| AMD Sempron             | 3         | 0.2%    |
| AMD Mobile Sempron      | 3         | 0.2%    |
| AMD E                   | 3         | 0.2%    |
| AMD Athlon II X3        | 3         | 0.2%    |
| AMD Athlon 64           | 3         | 0.2%    |
| Intel Pentium D         | 2         | 0.13%   |
| AMD Ryzen Threadripper  | 2         | 0.13%   |
| AMD Phenom II X2        | 2         | 0.13%   |
| AMD E2                  | 2         | 0.13%   |
| AMD Athlon X4           | 2         | 0.13%   |
| AMD Athlon X2           | 2         | 0.13%   |
| AMD A12                 | 2         | 0.13%   |
| Intel Xeon Gold         | 1         | 0.07%   |
| Intel Pentium III       | 1         | 0.07%   |
| Intel Core m5           | 1         | 0.07%   |
| Intel Core Duo          | 1         | 0.07%   |
| ARM BCM                 | 1         | 0.07%   |
| ARM AArch64             | 1         | 0.07%   |
| AMD Turion              | 1         | 0.07%   |
| AMD Ryzen 3 PRO         | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 701       | 46.27%  |
| 4       | 495       | 32.67%  |
| 6       | 138       | 9.11%   |
| 8       | 94        | 6.2%    |
| 1       | 50        | 3.3%    |
| 12      | 15        | 0.99%   |
| 3       | 11        | 0.73%   |
| 16      | 6         | 0.4%    |
| Unknown | 3         | 0.2%    |
| 32      | 1         | 0.07%   |
| 20      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1494      | 99.14%  |
| 2      | 13        | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 949       | 62.81%  |
| 1       | 559       | 37%     |
| Unknown | 3         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1454      | 95.97%  |
| Unknown        | 35        | 2.31%   |
| 32-bit         | 23        | 1.52%   |
| 64-bit         | 3         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 251       | 16.13%  |
| 0x206a7    | 169       | 10.86%  |
| 0x306c3    | 64        | 4.11%   |
| 0x306a9    | 64        | 4.11%   |
| 0x1067a    | 64        | 4.11%   |
| 0x906ea    | 46        | 2.96%   |
| 0x806ec    | 43        | 2.76%   |
| 0x806ea    | 42        | 2.7%    |
| 0x406e3    | 31        | 1.99%   |
| 0x806e9    | 29        | 1.86%   |
| 0x6fd      | 29        | 1.86%   |
| 0x806c1    | 28        | 1.8%    |
| 0x40651    | 28        | 1.8%    |
| 0x906e9    | 25        | 1.61%   |
| 0x506e3    | 23        | 1.48%   |
| 0x08600106 | 23        | 1.48%   |
| 0x306d4    | 20        | 1.29%   |
| 0x30678    | 19        | 1.22%   |
| 0x010000c8 | 19        | 1.22%   |
| 0x6fb      | 18        | 1.16%   |
| 0x10676    | 18        | 1.16%   |
| 0x406c4    | 16        | 1.03%   |
| 0x06000852 | 16        | 1.03%   |
| 0x08701021 | 15        | 0.96%   |
| 0x20655    | 14        | 0.9%    |
| 0x0800820d | 14        | 0.9%    |
| 0x906ed    | 13        | 0.84%   |
| 0x0a50000c | 13        | 0.84%   |
| 0x06001119 | 13        | 0.84%   |
| 0xa0652    | 12        | 0.77%   |
| 0x706a1    | 12        | 0.77%   |
| 0x506c9    | 12        | 0.77%   |
| 0x08600104 | 12        | 0.77%   |
| 0x08108102 | 12        | 0.77%   |
| 0x406c3    | 11        | 0.71%   |
| 0x08701013 | 11        | 0.71%   |
| 0x20652    | 10        | 0.64%   |
| 0x706e5    | 9         | 0.58%   |
| 0x6f6      | 9         | 0.58%   |
| 0x106e5    | 9         | 0.58%   |
| 0x08600103 | 9         | 0.58%   |
| 0x08001138 | 9         | 0.58%   |
| 0x07030105 | 9         | 0.58%   |
| 0x06003106 | 9         | 0.58%   |
| 0xa0653    | 8         | 0.51%   |
| 0x206d7    | 8         | 0.51%   |
| 0x0810100b | 8         | 0.51%   |
| 0x06006705 | 8         | 0.51%   |
| 0x806eb    | 7         | 0.45%   |
| 0x10661    | 7         | 0.45%   |
| 0x706a8    | 6         | 0.39%   |
| 0x30673    | 6         | 0.39%   |
| 0x106c2    | 6         | 0.39%   |
| 0x0a201009 | 6         | 0.39%   |
| 0x08608103 | 6         | 0.39%   |
| 0x6e8      | 5         | 0.32%   |
| 0x08108109 | 5         | 0.32%   |
| 0x08101016 | 5         | 0.32%   |
| 0x03000027 | 5         | 0.32%   |
| 0x010000db | 5         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 247       | 16.37%  |
| SandyBridge      | 192       | 12.72%  |
| Haswell          | 114       | 7.55%   |
| Penryn           | 99        | 6.56%   |
| Zen 2            | 83        | 5.5%    |
| IvyBridge        | 81        | 5.37%   |
| Core             | 69        | 4.57%   |
| Skylake          | 61        | 4.04%   |
| Silvermont       | 59        | 3.91%   |
| Piledriver       | 41        | 2.72%   |
| Zen              | 37        | 2.45%   |
| Zen+             | 35        | 2.32%   |
| TigerLake        | 33        | 2.19%   |
| K10              | 33        | 2.19%   |
| Zen 3            | 32        | 2.12%   |
| Westmere         | 32        | 2.12%   |
| CometLake        | 27        | 1.79%   |
| K8 Hammer        | 24        | 1.59%   |
| Broadwell        | 24        | 1.59%   |
| Unknown          | 23        | 1.52%   |
| Goldmont plus    | 21        | 1.39%   |
| Excavator        | 17        | 1.13%   |
| Nehalem          | 15        | 0.99%   |
| Goldmont         | 14        | 0.93%   |
| Bonnell          | 13        | 0.86%   |
| Steamroller      | 12        | 0.8%    |
| IceLake          | 12        | 0.8%    |
| Puma             | 11        | 0.73%   |
| P6               | 11        | 0.73%   |
| NetBurst         | 7         | 0.46%   |
| Bobcat           | 7         | 0.46%   |
| K10 Llano        | 5         | 0.33%   |
| Jaguar           | 5         | 0.33%   |
| Tremont          | 3         | 0.2%    |
| K8 & K10 hybrid  | 3         | 0.2%    |
| Bulldozer        | 3         | 0.2%    |
| Alderlake Hybrid | 3         | 0.2%    |
| K6               | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 894       | 51.11%  |
| Nvidia                           | 437       | 24.99%  |
| AMD                              | 399       | 22.81%  |
| Matrox Electronics Systems       | 11        | 0.63%   |
| ASPEED Technology                | 4         | 0.23%   |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| VIA Technologies                 | 1         | 0.06%   |
| ATI Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 165       | 9.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 52        | 2.84%   |
| Intel UHD Graphics 620                                                                   | 51        | 2.79%   |
| AMD Renoir                                                                               | 47        | 2.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 1.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 1.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 1.7%    |
| Intel HD Graphics 620                                                                    | 31        | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 1.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.37%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.15%   |
| Intel HD Graphics 630                                                                    | 20        | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 16        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15        | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 0.82%   |
| Intel HD Graphics 500                                                                    | 14        | 0.77%   |
| AMD Cezanne                                                                              | 14        | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.71%   |
| Intel HD Graphics 530                                                                    | 13        | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 0.66%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 12        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 10        | 0.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 0.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.55%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 9         | 0.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.49%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 9         | 0.49%   |
| AMD Lucienne                                                                             | 9         | 0.49%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 9         | 0.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 8         | 0.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.44%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 8         | 0.44%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 8         | 0.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 0.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7         | 0.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7         | 0.38%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 7         | 0.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.38%   |
| Nvidia TU117M [GeForce MX450]                                                            | 6         | 0.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 665       | 43.92%  |
| 1 x AMD        | 312       | 20.61%  |
| 1 x Nvidia     | 240       | 15.85%  |
| Intel + Nvidia | 177       | 11.69%  |
| Intel + AMD    | 45        | 2.97%   |
| 2 x AMD        | 29        | 1.92%   |
| AMD + Nvidia   | 13        | 0.86%   |
| Other          | 11        | 0.73%   |
| 1 x Matrox     | 10        | 0.66%   |
| 1 x ASPEED     | 4         | 0.26%   |
| 3 x Nvidia     | 2         | 0.13%   |
| 2 x Nvidia     | 2         | 0.13%   |
| 1 x SiS        | 2         | 0.13%   |
| 1 x VIA        | 1         | 0.07%   |
| AMD + Matrox   | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1261      | 82.63%  |
| Proprietary | 206       | 13.5%   |
| Unknown     | 59        | 3.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 863       | 55.68%  |
| 0.01-0.5   | 205       | 13.23%  |
| 1.01-2.0   | 188       | 12.13%  |
| 0.51-1.0   | 117       | 7.55%   |
| 3.01-4.0   | 89        | 5.74%   |
| 7.01-8.0   | 41        | 2.65%   |
| 5.01-6.0   | 21        | 1.35%   |
| 2.01-3.0   | 18        | 1.16%   |
| 8.01-16.0  | 7         | 0.45%   |
| 16.01-24.0 | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 206       | 11.95%  |
| Samsung Electronics     | 197       | 11.43%  |
| LG Display              | 148       | 8.58%   |
| Chimei Innolux          | 125       | 7.25%   |
| Dell                    | 111       | 6.44%   |
| BOE                     | 98        | 5.68%   |
| CPT                     | 97        | 5.63%   |
| Goldstar                | 73        | 4.23%   |
| BenQ                    | 68        | 3.94%   |
| Acer                    | 68        | 3.94%   |
| Hewlett-Packard         | 53        | 3.07%   |
| Eizo                    | 48        | 2.78%   |
| Philips                 | 47        | 2.73%   |
| Lenovo                  | 40        | 2.32%   |
| AOC                     | 37        | 2.15%   |
| Sharp                   | 36        | 2.09%   |
| Ancor Communications    | 35        | 2.03%   |
| Chi Mei Optoelectronics | 26        | 1.51%   |
| Iiyama                  | 21        | 1.22%   |
| PANDA                   | 17        | 0.99%   |
| Sony                    | 14        | 0.81%   |
| LG Philips              | 14        | 0.81%   |
| NEC Computers           | 10        | 0.58%   |
| Fujitsu Siemens         | 10        | 0.58%   |
| Panasonic               | 9         | 0.52%   |
| InfoVision              | 7         | 0.41%   |
| ASUSTek Computer        | 7         | 0.41%   |
| ViewSonic               | 6         | 0.35%   |
| Quanta Display          | 6         | 0.35%   |
| CSO                     | 6         | 0.35%   |
| Apple                   | 6         | 0.35%   |
| Vestel Elektronik       | 5         | 0.29%   |
| LG Electronics          | 5         | 0.29%   |
| Unknown                 | 4         | 0.23%   |
| Toshiba                 | 4         | 0.23%   |
| Lenovo Group Limited    | 4         | 0.23%   |
| Hitachi                 | 4         | 0.23%   |
| HannStar                | 4         | 0.23%   |
| OEM                     | 3         | 0.17%   |
| MStar                   | 3         | 0.17%   |
| CHR                     | 3         | 0.17%   |
| Onkyo                   | 2         | 0.12%   |
| MSI                     | 2         | 0.12%   |
| DENON                   | 2         | 0.12%   |
| CON                     | 2         | 0.12%   |
| Belinea                 | 2         | 0.12%   |
| Arnos Instruments       | 2         | 0.12%   |
| Xerox                   | 1         | 0.06%   |
| Wacom                   | 1         | 0.06%   |
| Vestel                  | 1         | 0.06%   |
| TMX                     | 1         | 0.06%   |
| TCL                     | 1         | 0.06%   |
| S2-Tek                  | 1         | 0.06%   |
| RTK                     | 1         | 0.06%   |
| NCS                     | 1         | 0.06%   |
| MiTAC                   | 1         | 0.06%   |
| LPL                     | 1         | 0.06%   |
| LLL                     | 1         | 0.06%   |
| LGD                     | 1         | 0.06%   |
| Jean                    | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 95        | 5.26%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 31        | 1.72%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 12        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 11        | 0.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 10        | 0.55%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 8         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 7         | 0.39%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 7         | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 6         | 0.33%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.33%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch     | 5         | 0.28%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.28%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 5         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 5         | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 5         | 0.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.28%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 4         | 0.22%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                   | 4         | 0.22%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 0.22%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch                  | 4         | 0.22%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                      | 4         | 0.22%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                         | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 4         | 0.22%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 4         | 0.22%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                         | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch            | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 4         | 0.22%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 4         | 0.22%   |
| AOC G2770 AOC2770 1920x1080 598x336mm 27.0-inch                           | 4         | 0.22%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                           | 4         | 0.22%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                     | 3         | 0.17%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch         | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch      | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch     | 3         | 0.17%   |
| Quanta Display LCD Monitor QDS0041 1280x800 331x207mm 15.4-inch           | 3         | 0.17%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                   | 3         | 0.17%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 3         | 0.17%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                       | 3         | 0.17%   |
| Panasonic TV MEIC303 1920x1080 698x392mm 31.5-inch                        | 3         | 0.17%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                        | 3         | 0.17%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                           | 3         | 0.17%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch               | 3         | 0.17%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 3         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 709       | 43.36%  |
| 1366x768 (WXGA)    | 203       | 12.42%  |
| 1600x900 (HD+)     | 156       | 9.54%   |
| 3840x2160 (4K)     | 109       | 6.67%   |
| 2560x1440 (QHD)    | 68        | 4.16%   |
| 1280x1024 (SXGA)   | 66        | 4.04%   |
| 1920x1200 (WUXGA)  | 64        | 3.91%   |
| 1680x1050 (WSXGA+) | 61        | 3.73%   |
| 1280x800 (WXGA)    | 56        | 3.43%   |
| 1440x900 (WXGA+)   | 29        | 1.77%   |
| 1024x768 (XGA)     | 11        | 0.67%   |
| Unknown            | 11        | 0.67%   |
| 3840x1080          | 7         | 0.43%   |
| 1600x1200          | 7         | 0.43%   |
| 1360x768           | 7         | 0.43%   |
| 3440x1440          | 6         | 0.37%   |
| 2560x1080          | 6         | 0.37%   |
| 2560x1600          | 5         | 0.31%   |
| 1920x540           | 5         | 0.31%   |
| 1024x600           | 5         | 0.31%   |
| 2160x1350          | 4         | 0.24%   |
| 1280x720 (HD)      | 4         | 0.24%   |
| 2288x1287          | 3         | 0.18%   |
| 1400x1050          | 3         | 0.18%   |
| 3840x2400          | 2         | 0.12%   |
| 3456x2160          | 2         | 0.12%   |
| 3200x1800 (QHD+)   | 2         | 0.12%   |
| 3000x2000          | 2         | 0.12%   |
| 2736x1824          | 2         | 0.12%   |
| 2160x1440          | 2         | 0.12%   |
| 1280x768           | 2         | 0.12%   |
| 9600x2160          | 1         | 0.06%   |
| 8320x2160          | 1         | 0.06%   |
| 800x1280           | 1         | 0.06%   |
| 7680x2160          | 1         | 0.06%   |
| 640x480            | 1         | 0.06%   |
| 6400x2160          | 1         | 0.06%   |
| 6080x1440          | 1         | 0.06%   |
| 5840x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5520x1080          | 1         | 0.06%   |
| 4240x1440          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 2880x1800          | 1         | 0.06%   |
| 2400x1600          | 1         | 0.06%   |
| 2048x1152          | 1         | 0.06%   |
| 1920x515           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 389       | 22.36%  |
| 13      | 245       | 14.08%  |
| 24      | 179       | 10.29%  |
| 14      | 125       | 7.18%   |
| 27      | 116       | 6.67%   |
| 23      | 95        | 5.46%   |
| 17      | 93        | 5.34%   |
| 21      | 77        | 4.43%   |
| 19      | 63        | 3.62%   |
| Unknown | 63        | 3.62%   |
| 31      | 57        | 3.28%   |
| 22      | 38        | 2.18%   |
| 12      | 30        | 1.72%   |
| 20      | 28        | 1.61%   |
| 11      | 22        | 1.26%   |
| 18      | 20        | 1.15%   |
| 84      | 12        | 0.69%   |
| 34      | 10        | 0.57%   |
| 25      | 10        | 0.57%   |
| 72      | 7         | 0.4%    |
| 54      | 7         | 0.4%    |
| 26      | 6         | 0.34%   |
| 10      | 6         | 0.34%   |
| 33      | 5         | 0.29%   |
| 32      | 5         | 0.29%   |
| 52      | 4         | 0.23%   |
| 47      | 4         | 0.23%   |
| 39      | 4         | 0.23%   |
| 65      | 3         | 0.17%   |
| 46      | 3         | 0.17%   |
| 16      | 3         | 0.17%   |
| 40      | 2         | 0.11%   |
| 60      | 1         | 0.06%   |
| 59      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 599       | 35.32%  |
| 501-600     | 359       | 21.17%  |
| 201-300     | 228       | 13.44%  |
| 401-500     | 175       | 10.32%  |
| 351-400     | 130       | 7.67%   |
| 601-700     | 69        | 4.07%   |
| Unknown     | 63        | 3.71%   |
| 1001-1500   | 27        | 1.59%   |
| 701-800     | 19        | 1.12%   |
| 1501-2000   | 19        | 1.12%   |
| 801-900     | 7         | 0.41%   |
| 901-1000    | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1103      | 72.66%  |
| 16/10   | 240       | 15.81%  |
| 5/4     | 71        | 4.68%   |
| Unknown | 53        | 3.49%   |
| 4/3     | 24        | 1.58%   |
| 3/2     | 13        | 0.86%   |
| 21/9    | 9         | 0.59%   |
| 32/9    | 2         | 0.13%   |
| 3.73    | 1         | 0.07%   |
| 3.20    | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 383       | 22.15%  |
| 201-250        | 296       | 17.12%  |
| 81-90          | 204       | 11.8%   |
| 71-80          | 169       | 9.77%   |
| 301-350        | 122       | 7.06%   |
| 151-200        | 107       | 6.19%   |
| 251-300        | 82        | 4.74%   |
| 351-500        | 78        | 4.51%   |
| Unknown        | 63        | 3.64%   |
| 121-130        | 56        | 3.24%   |
| 141-150        | 38        | 2.2%    |
| More than 1000 | 36        | 2.08%   |
| 61-70          | 26        | 1.5%    |
| 51-60          | 22        | 1.27%   |
| 501-1000       | 18        | 1.04%   |
| 131-140        | 13        | 0.75%   |
| 41-50          | 6         | 0.35%   |
| 91-100         | 6         | 0.35%   |
| 111-120        | 4         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 576       | 35.21%  |
| 121-160       | 543       | 33.19%  |
| 101-120       | 308       | 18.83%  |
| 161-240       | 93        | 5.68%   |
| Unknown       | 63        | 3.85%   |
| 1-50          | 30        | 1.83%   |
| More than 240 | 23        | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1158      | 74.47%  |
| 2     | 282       | 18.14%  |
| 0     | 70        | 4.5%    |
| 3     | 43        | 2.77%   |
| 4     | 2         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 711       | 31.34%  |
| Realtek Semiconductor             | 708       | 31.2%   |
| Qualcomm Atheros                  | 348       | 15.34%  |
| Broadcom                          | 103       | 4.54%   |
| Samsung Electronics               | 97        | 4.28%   |
| Broadcom Limited                  | 40        | 1.76%   |
| Marvell Technology Group          | 33        | 1.45%   |
| TP-Link                           | 23        | 1.01%   |
| Lenovo                            | 19        | 0.84%   |
| Nvidia                            | 17        | 0.75%   |
| MediaTek                          | 16        | 0.71%   |
| Qualcomm Atheros Communications   | 14        | 0.62%   |
| Ralink Technology                 | 13        | 0.57%   |
| Ralink                            | 12        | 0.53%   |
| Dell                              | 12        | 0.53%   |
| Sierra Wireless                   | 9         | 0.4%    |
| DisplayLink                       | 8         | 0.35%   |
| ASUSTek Computer                  | 8         | 0.35%   |
| ASIX Electronics                  | 7         | 0.31%   |
| QLogic                            | 5         | 0.22%   |
| Microsoft                         | 5         | 0.22%   |
| VIA Technologies                  | 4         | 0.18%   |
| D-Link                            | 4         | 0.18%   |
| ZyDAS                             | 3         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.13%   |
| Huawei Technologies               | 3         | 0.13%   |
| Hewlett-Packard                   | 3         | 0.13%   |
| Ericsson Business Mobile Networks | 3         | 0.13%   |
| Edimax Technology                 | 3         | 0.13%   |
| Attansic Technology               | 3         | 0.13%   |
| Xiaomi                            | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.09%   |
| Mellanox Technologies             | 2         | 0.09%   |
| Arduino SA                        | 2         | 0.09%   |
| ZyXEL Communications              | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| SIEMENS                           | 1         | 0.04%   |
| Seeed Technology                  | 1         | 0.04%   |
| Qualcomm                          | 1         | 0.04%   |
| MosChip Semiconductor             | 1         | 0.04%   |
| MICRORISC                         | 1         | 0.04%   |
| Microchip Technology              | 1         | 0.04%   |
| LSI                               | 1         | 0.04%   |
| JMicron Technology                | 1         | 0.04%   |
| Intersil                          | 1         | 0.04%   |
| ICS Advent                        | 1         | 0.04%   |
| IBM                               | 1         | 0.04%   |
| Google                            | 1         | 0.04%   |
| Fujitsu Siemens Computers         | 1         | 0.04%   |
| Foxconn / Hon Hai                 | 1         | 0.04%   |
| Fibocom                           | 1         | 0.04%   |
| Emulex                            | 1         | 0.04%   |
| D-Link System                     | 1         | 0.04%   |
| Chelsio Communications            | 1         | 0.04%   |
| Aquantia                          | 1         | 0.04%   |
| American Megatrends               | 1         | 0.04%   |
| AMD                               | 1         | 0.04%   |
| 3Com                              | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 516       | 19.58%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 118       | 4.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 96        | 3.64%   |
| Intel Wi-Fi 6 AX200                                               | 80        | 3.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 65        | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 55        | 2.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 54        | 2.05%   |
| Intel Wireless 8265 / 8275                                        | 51        | 1.94%   |
| Intel Wireless 7260                                               | 38        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 36        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 35        | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 30        | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 28        | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.02%   |
| Intel Wireless 8260                                               | 26        | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 26        | 0.99%   |
| Intel Wi-Fi 6 AX201                                               | 25        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 24        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.91%   |
| Intel Wireless 7265                                               | 23        | 0.87%   |
| Intel Wireless 3165                                               | 23        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.57%   |
| Intel Wireless 3160                                               | 15        | 0.57%   |
| Intel WiFi Link 5100                                              | 15        | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 15        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 13        | 0.49%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 12        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.46%   |
| Intel Centrino Wireless-N 2230                                    | 12        | 0.46%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11        | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.42%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 10        | 0.38%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 0.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 9         | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 0.34%   |
| Intel Wireless-AC 9260                                            | 9         | 0.34%   |
| Intel Ultimate N WiFi Link 5300                                   | 9         | 0.34%   |
| Intel Ethernet Controller I225-V                                  | 9         | 0.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 8         | 0.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 563       | 48.79%  |
| Qualcomm Atheros                | 280       | 24.26%  |
| Realtek Semiconductor           | 113       | 9.79%   |
| Broadcom                        | 57        | 4.94%   |
| TP-Link                         | 22        | 1.91%   |
| Broadcom Limited                | 21        | 1.82%   |
| MediaTek                        | 15        | 1.3%    |
| Qualcomm Atheros Communications | 14        | 1.21%   |
| Ralink Technology               | 13        | 1.13%   |
| Ralink                          | 12        | 1.04%   |
| Sierra Wireless                 | 9         | 0.78%   |
| ASUSTek Computer                | 7         | 0.61%   |
| Dell                            | 6         | 0.52%   |
| Microsoft                       | 5         | 0.43%   |
| ZyDAS                           | 3         | 0.26%   |
| Edimax Technology               | 3         | 0.26%   |
| D-Link                          | 3         | 0.26%   |
| Marvell Technology Group        | 2         | 0.17%   |
| ZyXEL Communications            | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| Intersil                        | 1         | 0.09%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| Fujitsu Siemens Computers       | 1         | 0.09%   |
| Fibocom                         | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 118       | 10.2%   |
| Intel Wi-Fi 6 AX200                                                           | 80        | 6.91%   |
| Intel Wireless 8265 / 8275                                                    | 51        | 4.41%   |
| Intel Wireless 7260                                                           | 38        | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 36        | 3.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 35        | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 30        | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 29        | 2.51%   |
| Intel Wireless 8260                                                           | 26        | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 26        | 2.25%   |
| Intel Wi-Fi 6 AX201                                                           | 25        | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 25        | 2.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 24        | 2.07%   |
| Intel Wireless 7265                                                           | 23        | 1.99%   |
| Intel Wireless 3165                                                           | 23        | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 23        | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 19        | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 17        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 16        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 16        | 1.38%   |
| Intel Wireless 3160                                                           | 15        | 1.3%    |
| Intel WiFi Link 5100                                                          | 15        | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 15        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 13        | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 12        | 1.04%   |
| Intel Centrino Wireless-N 2230                                                | 12        | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                               | 11        | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 10        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 10        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 9         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 9         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 9         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 9         | 0.78%   |
| Intel Wireless-AC 9260                                                        | 9         | 0.78%   |
| Intel Ultimate N WiFi Link 5300                                               | 9         | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 8         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 8         | 0.69%   |
| Intel Centrino Advanced-N 6235                                                | 8         | 0.69%   |
| Intel Centrino Advanced-N 6200                                                | 8         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 7         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 7         | 0.61%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 7         | 0.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 7         | 0.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 6         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 6         | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 6         | 0.52%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 6         | 0.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 6         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 0.43%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5         | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 5         | 0.43%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.43%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                          | 5         | 0.43%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 5         | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 0.35%   |
| Sierra Wireless EM7455                                                        | 4         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 656       | 46.46%  |
| Intel                            | 364       | 25.78%  |
| Qualcomm Atheros                 | 103       | 7.29%   |
| Samsung Electronics              | 97        | 6.87%   |
| Broadcom                         | 53        | 3.75%   |
| Marvell Technology Group         | 32        | 2.27%   |
| Lenovo                           | 19        | 1.35%   |
| Broadcom Limited                 | 19        | 1.35%   |
| Nvidia                           | 17        | 1.2%    |
| DisplayLink                      | 8         | 0.57%   |
| ASIX Electronics                 | 7         | 0.5%    |
| QLogic                           | 5         | 0.35%   |
| VIA Technologies                 | 3         | 0.21%   |
| Attansic Technology              | 3         | 0.21%   |
| Xiaomi                           | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Huawei Technologies              | 2         | 0.14%   |
| TP-Link                          | 1         | 0.07%   |
| Spreadtrum Communications        | 1         | 0.07%   |
| MosChip Semiconductor            | 1         | 0.07%   |
| Microchip Technology             | 1         | 0.07%   |
| Mellanox Technologies            | 1         | 0.07%   |
| MediaTek                         | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |
| IBM                              | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Google                           | 1         | 0.07%   |
| Foxconn / Hon Hai                | 1         | 0.07%   |
| Emulex                           | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| D-Link                           | 1         | 0.07%   |
| Chelsio Communications           | 1         | 0.07%   |
| ASUSTek Computer                 | 1         | 0.07%   |
| Aquantia                         | 1         | 0.07%   |
| American Megatrends              | 1         | 0.07%   |
| 3Com                             | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 516       | 35.59%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 96        | 6.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 65        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 55        | 3.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 54        | 3.72%   |
| Intel I211 Gigabit Network Connection                                          | 28        | 1.93%   |
| Intel Ethernet Connection I217-LM                                              | 27        | 1.86%   |
| Intel Ethernet Connection (4) I219-LM                                          | 24        | 1.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 18        | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 18        | 1.24%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                              | 17        | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                           | 17        | 1.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 15        | 1.03%   |
| Intel Ethernet Connection I219-LM                                              | 14        | 0.97%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 0.9%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 0.83%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                          | 12        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                           | 11        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.62%   |
| Intel Ethernet Controller I225-V                                               | 9         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 8         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 8         | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 8         | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 8         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 0.48%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 7         | 0.48%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 6         | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 6         | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 6         | 0.41%   |
| Intel I210 Gigabit Network Connection                                          | 6         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 0.41%   |
| QLogic cLOM8214 1/10GbE Controller                                             | 5         | 0.34%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.34%   |
| Intel Ethernet Connection (2) I218-V                                           | 5         | 0.34%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5         | 0.34%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 0.34%   |
| Intel 82566MM Gigabit Network Connection                                       | 5         | 0.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 0.34%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 5         | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.28%   |
| Nvidia MCP73 Ethernet                                                          | 4         | 0.28%   |
| Nvidia MCP61 Ethernet                                                          | 4         | 0.28%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 4         | 0.28%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.28%   |
| Intel I350 Gigabit Network Connection                                          | 4         | 0.28%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1327      | 53.9%   |
| WiFi     | 1108      | 45%     |
| Modem    | 22        | 0.89%   |
| Unknown  | 5         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 802       | 51.41%  |
| Ethernet | 757       | 48.53%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 773       | 51.09%  |
| 1     | 664       | 43.89%  |
| 0     | 36        | 2.38%   |
| 3     | 28        | 1.85%   |
| 4     | 5         | 0.33%   |
| 8     | 4         | 0.26%   |
| 5     | 2         | 0.13%   |
| 10    | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1379      | 90.25%  |
| Yes  | 149       | 9.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 412       | 49.58%  |
| Realtek Semiconductor           | 62        | 7.46%   |
| Qualcomm Atheros Communications | 58        | 6.98%   |
| Broadcom                        | 51        | 6.14%   |
| IMC Networks                    | 50        | 6.02%   |
| Cambridge Silicon Radio         | 43        | 5.17%   |
| Lite-On Technology              | 32        | 3.85%   |
| ASUSTek Computer                | 28        | 3.37%   |
| Foxconn / Hon Hai               | 26        | 3.13%   |
| Hewlett-Packard                 | 21        | 2.53%   |
| Dell                            | 14        | 1.68%   |
| Apple                           | 5         | 0.6%    |
| Alps Electric                   | 5         | 0.6%    |
| MediaTek                        | 4         | 0.48%   |
| Toshiba                         | 3         | 0.36%   |
| Ralink                          | 3         | 0.36%   |
| Realtek                         | 2         | 0.24%   |
| Ralink Technology               | 2         | 0.24%   |
| Marvell Semiconductor           | 2         | 0.24%   |
| Integrated System Solution      | 2         | 0.24%   |
| TP-Link                         | 1         | 0.12%   |
| Mobile Action Technology        | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| Fujitsu Siemens Computers       | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Askey Computer                  | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 167       | 20.1%   |
| Intel AX200 Bluetooth                                                               | 77        | 9.27%   |
| Intel AX201 Bluetooth                                                               | 65        | 7.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 55        | 6.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 43        | 5.17%   |
| Realtek Bluetooth Radio                                                             | 32        | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 31        | 3.73%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 2.41%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 2.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 17        | 2.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 16        | 1.93%   |
| IMC Networks Bluetooth Device                                                       | 16        | 1.93%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 1.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.32%   |
| Broadcom BCM2045 Bluetooth                                                          | 11        | 1.32%   |
| Intel Bluetooth Device                                                              | 10        | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 0.96%   |
| IMC Networks Wireless_Device                                                        | 8         | 0.96%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 0.96%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 0.96%   |
| Dell DW375 Bluetooth Module                                                         | 8         | 0.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 8         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 0.84%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.72%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 6         | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.6%    |
| Intel AX210 Bluetooth                                                               | 5         | 0.6%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.6%    |
| ASUS ASUS USB-BT500                                                                 | 5         | 0.6%    |
| Lite-On Bluetooth Device                                                            | 4         | 0.48%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.48%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 4         | 0.48%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 3         | 0.36%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.36%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 3         | 0.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.36%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 0.36%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.24%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.24%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.24%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.24%   |
| MediaTek BT                                                                         | 2         | 0.24%   |
| Lite-On Wireless_Device                                                             | 2         | 0.24%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.24%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.24%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.24%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.24%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 0.24%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.24%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.24%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.24%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.24%   |
| Broadcom Bluetooth                                                                  | 2         | 0.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.24%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1081      | 54.27%  |
| AMD                                  | 430       | 21.59%  |
| Nvidia                               | 275       | 13.81%  |
| C-Media Electronics                  | 39        | 1.96%   |
| Lenovo                               | 23        | 1.15%   |
| Realtek Semiconductor                | 19        | 0.95%   |
| Creative Labs                        | 13        | 0.65%   |
| Creative Technology                  | 12        | 0.6%    |
| Logitech                             | 10        | 0.5%    |
| VIA Technologies                     | 9         | 0.45%   |
| GN Netcom                            | 7         | 0.35%   |
| JMTek                                | 6         | 0.3%    |
| Hewlett-Packard                      | 6         | 0.3%    |
| Plantronics                          | 5         | 0.25%   |
| Dell                                 | 5         | 0.25%   |
| GYROCOM C&C                          | 4         | 0.2%    |
| Silicon Integrated Systems [SiS]     | 3         | 0.15%   |
| Razer USA                            | 3         | 0.15%   |
| Kingston Technology                  | 3         | 0.15%   |
| Focusrite-Novation                   | 3         | 0.15%   |
| BEHRINGER International              | 3         | 0.15%   |
| ASUSTek Computer                     | 3         | 0.15%   |
| Trust                                | 2         | 0.1%    |
| RODE Microphones                     | 2         | 0.1%    |
| M-Audio                              | 2         | 0.1%    |
| DigiTech                             | 2         | 0.1%    |
| Conexant Systems                     | 2         | 0.1%    |
| Toshiba                              | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Texas Instruments                    | 1         | 0.05%   |
| Tenx Technology                      | 1         | 0.05%   |
| SteelSeries ApS                      | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Sennheiser Communications            | 1         | 0.05%   |
| Samson Technologies                  | 1         | 0.05%   |
| Orbbec 3D Technology International   | 1         | 0.05%   |
| Microsoft                            | 1         | 0.05%   |
| Micro Star International             | 1         | 0.05%   |
| KORG                                 | 1         | 0.05%   |
| Generalplus Technology               | 1         | 0.05%   |
| fifinemicrophone.com                 | 1         | 0.05%   |
| ESI Audiotechnik                     | 1         | 0.05%   |
| ELMCU                                | 1         | 0.05%   |
| Datelink Technology                  | 1         | 0.05%   |
| AudioQuest                           | 1         | 0.05%   |
| Audio-Technica                       | 1         | 0.05%   |
| Apple                                | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 176       | 7.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 117       | 4.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 113       | 4.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 82        | 3.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 73        | 3.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 68        | 2.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 67        | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 65        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 60        | 2.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 55        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 53        | 2.25%   |
| AMD FCH Azalia Controller                                                                         | 51        | 2.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 45        | 1.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 40        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 37        | 1.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 34        | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 33        | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 31        | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 30        | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 29        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 28        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 27        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 25        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 24        | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 1.02%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 21        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 20        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 20        | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 20        | 0.85%   |
| Realtek Semiconductor USB Audio                                                                   | 18        | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 17        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 16        | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 16        | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 0.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 13        | 0.55%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 13        | 0.55%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 12        | 0.51%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.51%   |
| AMD High Definition Audio Controller                                                              | 12        | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 11        | 0.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 11        | 0.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 11        | 0.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 11        | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10        | 0.42%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 10        | 0.42%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10        | 0.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 10        | 0.42%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 9         | 0.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.38%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 9         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 179       | 19.04%  |
| Kingston            | 158       | 16.81%  |
| SK hynix            | 152       | 16.17%  |
| Elpida              | 109       | 11.6%   |
| Unknown             | 103       | 10.96%  |
| Micron Technology   | 90        | 9.57%   |
| Crucial             | 39        | 4.15%   |
| Corsair             | 23        | 2.45%   |
| Ramaxel Technology  | 18        | 1.91%   |
| Patriot             | 18        | 1.91%   |
| A-DATA Technology   | 18        | 1.91%   |
| Unknown (ABCD)      | 8         | 0.85%   |
| Transcend           | 5         | 0.53%   |
| Nanya Technology    | 5         | 0.53%   |
| G.Skill             | 5         | 0.53%   |
| Unknown (AB)        | 1         | 0.11%   |
| Toshiba             | 1         | 0.11%   |
| PDPSystems          | 1         | 0.11%   |
| OnBoard             | 1         | 0.11%   |
| Nayna               | 1         | 0.11%   |
| Kingmax             | 1         | 0.11%   |
| Kimtigo             | 1         | 0.11%   |
| H                   | 1         | 0.11%   |
| Goodram             | 1         | 0.11%   |
| Golden Empire       | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                          | 95        | 9.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 8         | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 7         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 7         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 7         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.59%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 6         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 6         | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 5         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 5         | 0.5%    |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 5         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 5         | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 0.5%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 5         | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 5         | 0.5%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 5         | 0.5%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s                 | 5         | 0.5%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 5         | 0.5%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 4         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s    | 4         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s      | 4         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.4%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.4%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 4         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.4%    |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s          | 4         | 0.4%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 4         | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 4         | 0.4%    |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 4         | 0.4%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                   | 4         | 0.4%    |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s                 | 4         | 0.4%    |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s             | 4         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 3         | 0.3%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 3         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 0.3%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                     | 3         | 0.3%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s                | 3         | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.3%    |
| SK hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.3%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.3%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.3%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 3         | 0.3%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 3         | 0.3%    |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                        | 3         | 0.3%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 3         | 0.3%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.3%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.3%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 343       | 41.88%  |
| DDR3    | 332       | 40.54%  |
| DDR2    | 45        | 5.49%   |
| LPDDR4  | 32        | 3.91%   |
| Unknown | 27        | 3.3%    |
| LPDDR3  | 20        | 2.44%   |
| SDRAM   | 15        | 1.83%   |
| DDR     | 4         | 0.49%   |
| DRAM    | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 525       | 63.87%  |
| DIMM         | 239       | 29.08%  |
| Row Of Chips | 45        | 5.47%   |
| Chip         | 11        | 1.34%   |
| RIMM         | 2         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 283       | 31.87%  |
| 4096  | 210       | 23.65%  |
| 2048  | 194       | 21.85%  |
| 16384 | 130       | 14.64%  |
| 1024  | 34        | 3.83%   |
| 32768 | 29        | 3.27%   |
| 512   | 4         | 0.45%   |
| 256   | 2         | 0.23%   |
| 6144  | 1         | 0.11%   |
| 3072  | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1333    | 150       | 16.93%  |
| 1600    | 146       | 16.48%  |
| 2667    | 117       | 13.21%  |
| 3200    | 114       | 12.87%  |
| 2400    | 69        | 7.79%   |
| 2133    | 46        | 5.19%   |
| 800     | 30        | 3.39%   |
| 1334    | 25        | 2.82%   |
| 3600    | 19        | 2.14%   |
| Unknown | 19        | 2.14%   |
| 667     | 16        | 1.81%   |
| 1867    | 14        | 1.58%   |
| 4267    | 12        | 1.35%   |
| 1067    | 11        | 1.24%   |
| 1866    | 8         | 0.9%    |
| 3266    | 7         | 0.79%   |
| 2933    | 7         | 0.79%   |
| 2666    | 6         | 0.68%   |
| 3733    | 5         | 0.56%   |
| 3466    | 5         | 0.56%   |
| 1066    | 5         | 0.56%   |
| 4199    | 4         | 0.45%   |
| 3800    | 4         | 0.45%   |
| 3000    | 4         | 0.45%   |
| 975     | 4         | 0.45%   |
| 533     | 4         | 0.45%   |
| 4266    | 3         | 0.34%   |
| 3400    | 3         | 0.34%   |
| 3333    | 3         | 0.34%   |
| 400     | 3         | 0.34%   |
| 8400    | 2         | 0.23%   |
| 4133    | 2         | 0.23%   |
| 3666    | 2         | 0.23%   |
| 3334    | 2         | 0.23%   |
| 2800    | 2         | 0.23%   |
| 2048    | 2         | 0.23%   |
| 1400    | 2         | 0.23%   |
| 4800    | 1         | 0.11%   |
| 3151    | 1         | 0.11%   |
| 2934    | 1         | 0.11%   |
| 2200    | 1         | 0.11%   |
| 2000    | 1         | 0.11%   |
| 1800    | 1         | 0.11%   |
| 1648    | 1         | 0.11%   |
| 1639    | 1         | 0.11%   |
| 1599    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 9         | 29.03%  |
| Hewlett-Packard     | 7         | 22.58%  |
| Samsung Electronics | 5         | 16.13%  |
| Brother Industries  | 5         | 16.13%  |
| Seiko Epson         | 1         | 3.23%   |
| QinHeng Electronics | 1         | 3.23%   |
| Prolific Technology | 1         | 3.23%   |
| Minolta             | 1         | 3.23%   |
| ICS Advent          | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer      | 3         | 9.68%   |
| Samsung M2070 Series                    | 2         | 6.45%   |
| Seiko Epson L365 Series                 | 1         | 3.23%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 3.23%   |
| Samsung M267x 287x Series               | 1         | 3.23%   |
| Samsung C460 Series                     | 1         | 3.23%   |
| QinHeng CH340S                          | 1         | 3.23%   |
| Prolific PL2305 Parallel Port           | 1         | 3.23%   |
| Minolta PagePro 1300W                   | 1         | 3.23%   |
| ICS Advent Parallel Adapter             | 1         | 3.23%   |
| HP Officejet 4500 G510g-m               | 1         | 3.23%   |
| HP Neverstop Laser 100x                 | 1         | 3.23%   |
| HP LaserJet P2014                       | 1         | 3.23%   |
| HP Deskjet 3050 J610 series             | 1         | 3.23%   |
| Canon TS6300 series                     | 1         | 3.23%   |
| Canon PIXMA MX720 Series                | 1         | 3.23%   |
| Canon PIXMA MP280                       | 1         | 3.23%   |
| Canon PIXMA MG3500 Series               | 1         | 3.23%   |
| Canon PIXMA MG2500 Series               | 1         | 3.23%   |
| Canon MG5600 series                     | 1         | 3.23%   |
| Canon MF4100 series                     | 1         | 3.23%   |
| Canon LBP3010/LBP3018/LBP3050           | 1         | 3.23%   |
| Canon iP7200 series                     | 1         | 3.23%   |
| Brother MFC-J3930DW                     | 1         | 3.23%   |
| Brother HL-2030 Laser Printer           | 1         | 3.23%   |
| Brother HL-1430 Laser Printer           | 1         | 3.23%   |
| Brother DCP-J105                        | 1         | 3.23%   |
| Brother DCP-1610W                       | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 5         | 83.33%  |
| Mustek Systems | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210             | 2         | 33.33%  |
| Mustek Systems BearPaw 1200 CU Plus | 1         | 16.67%  |
| Canon CanoScan LIDE 25              | 1         | 16.67%  |
| Canon CanoScan LiDE 200             | 1         | 16.67%  |
| Canon CanoScan LiDE 100             | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 215       | 25.75%  |
| Realtek Semiconductor                  | 87        | 10.42%  |
| Acer                                   | 73        | 8.74%   |
| Microdia                               | 66        | 7.9%    |
| IMC Networks                           | 66        | 7.9%    |
| Sunplus Innovation Technology          | 48        | 5.75%   |
| Lite-On Technology                     | 39        | 4.67%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.19%   |
| Quanta                                 | 29        | 3.47%   |
| Suyin                                  | 24        | 2.87%   |
| Syntek                                 | 21        | 2.51%   |
| Logitech                               | 21        | 2.51%   |
| Alcor Micro                            | 11        | 1.32%   |
| Samsung Electronics                    | 10        | 1.2%    |
| Ricoh                                  | 10        | 1.2%    |
| KYE Systems (Mouse Systems)            | 10        | 1.2%    |
| Lenovo                                 | 8         | 0.96%   |
| Creative Technology                    | 8         | 0.96%   |
| Apple                                  | 8         | 0.96%   |
| Microsoft                              | 7         | 0.84%   |
| Z-Star Microelectronics                | 6         | 0.72%   |
| Unknown                                | 4         | 0.48%   |
| GEMBIRD                                | 4         | 0.48%   |
| Primax Electronics                     | 3         | 0.36%   |
| Luxvisions Innotech Limited            | 3         | 0.36%   |
| Hewlett-Packard                        | 2         | 0.24%   |
| Generalplus Technology                 | 2         | 0.24%   |
| Sunplus Technology                     | 1         | 0.12%   |
| Sonix Technology                       | 1         | 0.12%   |
| Silicon Motion                         | 1         | 0.12%   |
| Ruision                                | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Orbbec 3D Technology International     | 1         | 0.12%   |
| Nokia Mobile Phones                    | 1         | 0.12%   |
| MacroSilicon                           | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| Genesys Logic                          | 1         | 0.12%   |
| eMPIA Technology                       | 1         | 0.12%   |
| Elecom                                 | 1         | 0.12%   |
| Cubeternet                             | 1         | 0.12%   |
| ALi                                    | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 55        | 6.51%   |
| Realtek Integrated_Webcam_HD                                             | 31        | 3.67%   |
| Microdia Integrated_Webcam_HD                                            | 30        | 3.55%   |
| IMC Networks Integrated Camera                                           | 29        | 3.43%   |
| Chicony HD WebCam                                                        | 21        | 2.49%   |
| Chicony HP HD Camera                                                     | 20        | 2.37%   |
| Acer Lenovo EasyCamera                                                   | 19        | 2.25%   |
| Lite-On HP HD Camera                                                     | 17        | 2.01%   |
| Acer Integrated Camera                                                   | 14        | 1.66%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 13        | 1.54%   |
| Chicony Integrated Camera (1280x720@30)                                  | 13        | 1.54%   |
| Lite-On Integrated Camera                                                | 11        | 1.3%    |
| Samsung Galaxy A5 (MTP)                                                  | 10        | 1.18%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 9         | 1.07%   |
| Sunplus Integrated_Webcam_HD                                             | 9         | 1.07%   |
| Syntek Lenovo EasyCamera                                                 | 8         | 0.95%   |
| Realtek Integrated Webcam HD                                             | 8         | 0.95%   |
| Quanta HP HD Camera                                                      | 8         | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 8         | 0.95%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 8         | 0.95%   |
| Microdia Integrated Webcam                                               | 7         | 0.83%   |
| Logitech Webcam C270                                                     | 7         | 0.83%   |
| Lenovo Integrated Webcam                                                 | 7         | 0.83%   |
| Acer SunplusIT Integrated Camera                                         | 7         | 0.83%   |
| Acer EasyCamera                                                          | 7         | 0.83%   |
| Syntek Integrated Camera                                                 | 6         | 0.71%   |
| Sunplus Laptop Integrated WebCam HD                                      | 6         | 0.71%   |
| Sunplus HD WebCam                                                        | 6         | 0.71%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 6         | 0.71%   |
| Quanta HP Wide Vision HD Camera                                          | 6         | 0.71%   |
| Creative Live! Cam Sync HD [VF0770]                                      | 6         | 0.71%   |
| Chicony Lenovo EasyCamera                                                | 6         | 0.71%   |
| Chicony HP HD Webcam                                                     | 6         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 6         | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 6         | 0.71%   |
| Alcor Micro USB 2.0 PC cam                                               | 6         | 0.71%   |
| Sunplus ASUS USB2.0 Webcam                                               | 5         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 0.59%   |
| Realtek USB Camera                                                       | 5         | 0.59%   |
| Quanta HD User Facing                                                    | 5         | 0.59%   |
| Chicony FJ Camera                                                        | 5         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera          | 5         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 5         | 0.59%   |
| Acer Lenovo Integrated Webcam                                            | 5         | 0.59%   |
| Unknown FULL HD 1080P Webcam                                             | 4         | 0.47%   |
| Sunplus HP HD Webcam [Fixed]                                             | 4         | 0.47%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 4         | 0.47%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                       | 4         | 0.47%   |
| Realtek HP Webcam-101                                                    | 4         | 0.47%   |
| Microsoft LifeCam HD-3000                                                | 4         | 0.47%   |
| Lite-On HP Wide Vision HD Camera                                         | 4         | 0.47%   |
| Lite-On HP HD Webcam                                                     | 4         | 0.47%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                                | 4         | 0.47%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                        | 4         | 0.47%   |
| Chicony TOSHIBA Web Camera - HD                                          | 4         | 0.47%   |
| Chicony HP Wide Vision HD Camera                                         | 4         | 0.47%   |
| Chicony HP Truevision HD                                                 | 4         | 0.47%   |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 0.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 4         | 0.47%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 4         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 85        | 33.86%  |
| Validity Sensors           | 84        | 33.47%  |
| Shenzhen Goodix Technology | 27        | 10.76%  |
| AuthenTec                  | 24        | 9.56%   |
| Elan Microelectronics      | 13        | 5.18%   |
| Upek                       | 11        | 4.38%   |
| LighTuning Technology      | 5         | 1.99%   |
| Microsoft                  | 1         | 0.4%    |
| Dell                       | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 9.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 8.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 7.17%   |
| Unknown                                                                    | 18        | 7.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 5.58%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 5.18%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 4.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 4.38%   |
| AuthenTec AES2810                                                          | 10        | 3.98%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.59%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.59%   |
| Validity Sensors VFS491                                                    | 8         | 3.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.79%   |
| AuthenTec AES1600                                                          | 6         | 2.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.99%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.99%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.99%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.99%   |
| Synaptics  WBDI                                                            | 4         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.59%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.8%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.4%    |
| Synaptics WBDI Device                                                      | 1         | 0.4%    |
| Microsoft Fingerprint Reader                                               | 1         | 0.4%    |
| LighTuning Fingerprint Sensor                                              | 1         | 0.4%    |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 46        | 48.94%  |
| Alcor Micro               | 27        | 28.72%  |
| O2 Micro                  | 8         | 8.51%   |
| Lenovo                    | 5         | 5.32%   |
| SCM Microsystems          | 2         | 2.13%   |
| Aladdin Knowledge Systems | 2         | 2.13%   |
| Upek                      | 1         | 1.06%   |
| Purism, SPC               | 1         | 1.06%   |
| OmniKey                   | 1         | 1.06%   |
| Fujitsu Siemens Computers | 1         | 1.06%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 28.72%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 13.83%  |
| Broadcom 58200                                                               | 13        | 13.83%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 10.64%  |
| Broadcom 5880                                                                | 10        | 10.64%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 7.45%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.32%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.13%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 2.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.06%   |
| Purism, SPC Librem Key                                                       | 1         | 1.06%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 1.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.06%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.06%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1034      | 67.54%  |
| 1     | 381       | 24.89%  |
| 2     | 89        | 5.81%   |
| 3     | 20        | 1.31%   |
| 4     | 4         | 0.26%   |
| 5     | 3         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 246       | 39.36%  |
| Graphics card            | 116       | 18.56%  |
| Chipcard                 | 81        | 12.96%  |
| Net/wireless             | 45        | 7.2%    |
| Multimedia controller    | 30        | 4.8%    |
| Communication controller | 18        | 2.88%   |
| Storage                  | 16        | 2.56%   |
| Bluetooth                | 13        | 2.08%   |
| Camera                   | 10        | 1.6%    |
| Unassigned class         | 9         | 1.44%   |
| Net/ethernet             | 8         | 1.28%   |
| Sound                    | 7         | 1.12%   |
| Card reader              | 7         | 1.12%   |
| Modem                    | 6         | 0.96%   |
| Flash memory             | 6         | 0.96%   |
| Network                  | 3         | 0.48%   |
| Storage/raid             | 1         | 0.16%   |
| Storage/ide              | 1         | 0.16%   |
| Storage/ata              | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |


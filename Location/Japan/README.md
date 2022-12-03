Linux in Japan - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Japan/Desktop/README.md) and [notebooks](/Location/Japan/Notebook/README.md).

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

Total: 1425

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Spectre x360 Convertible... | Convertible | [ecfe0cfab0](https://linux-hardware.org/?probe=ecfe0cfab0) | Nov 25, 2022 |
| ASUSTek       | X99-PRO                     | Desktop     | [6906303697](https://linux-hardware.org/?probe=6906303697) | Nov 25, 2022 |
| Biostar       | X470GTA                     | Desktop     | [83dcb407ba](https://linux-hardware.org/?probe=83dcb407ba) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [4dbcde603b](https://linux-hardware.org/?probe=4dbcde603b) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [b52fed6965](https://linux-hardware.org/?probe=b52fed6965) | Nov 23, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | Notebook    | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [4956957df8](https://linux-hardware.org/?probe=4956957df8) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | Notebook    | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| NEC Comput... | PC-VK27MCZDM                | Notebook    | [fce4afe996](https://linux-hardware.org/?probe=fce4afe996) | Nov 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [14318910c1](https://linux-hardware.org/?probe=14318910c1) | Nov 18, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [c4bf12a3e5](https://linux-hardware.org/?probe=c4bf12a3e5) | Nov 18, 2022 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [5802e3e5d6](https://linux-hardware.org/?probe=5802e3e5d6) | Nov 17, 2022 |
| NEC Comput... | NEC VERSA M160              | Notebook    | [a49b4b95b9](https://linux-hardware.org/?probe=a49b4b95b9) | Nov 17, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [09569f3154](https://linux-hardware.org/?probe=09569f3154) | Nov 17, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [4ba72d9f3b](https://linux-hardware.org/?probe=4ba72d9f3b) | Nov 16, 2022 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [69f54ed610](https://linux-hardware.org/?probe=69f54ed610) | Nov 16, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [c53f301391](https://linux-hardware.org/?probe=c53f301391) | Nov 16, 2022 |
| HP            | 83EE                        | Desktop     | [182682b17c](https://linux-hardware.org/?probe=182682b17c) | Nov 16, 2022 |
| HP            | 83EE                        | Desktop     | [65d7bade6e](https://linux-hardware.org/?probe=65d7bade6e) | Nov 16, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | Notebook    | [96db8793b2](https://linux-hardware.org/?probe=96db8793b2) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | Notebook    | [c576805c81](https://linux-hardware.org/?probe=c576805c81) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [69d4f912f9](https://linux-hardware.org/?probe=69d4f912f9) | Nov 15, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [c6cc7b7785](https://linux-hardware.org/?probe=c6cc7b7785) | Nov 12, 2022 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [16bf4c059c](https://linux-hardware.org/?probe=16bf4c059c) | Nov 11, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [dfa4a8aa7f](https://linux-hardware.org/?probe=dfa4a8aa7f) | Nov 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [07a9b0efe0](https://linux-hardware.org/?probe=07a9b0efe0) | Nov 10, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | Notebook    | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d87e75abbf](https://linux-hardware.org/?probe=d87e75abbf) | Nov 04, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | Desktop     | [573a028791](https://linux-hardware.org/?probe=573a028791) | Nov 03, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [0a42c1156c](https://linux-hardware.org/?probe=0a42c1156c) | Oct 28, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [1627ad94ef](https://linux-hardware.org/?probe=1627ad94ef) | Oct 27, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [00e64f6075](https://linux-hardware.org/?probe=00e64f6075) | Oct 25, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [daa76e4b78](https://linux-hardware.org/?probe=daa76e4b78) | Oct 25, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [f1841f9564](https://linux-hardware.org/?probe=f1841f9564) | Oct 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [cd2e9dd7af](https://linux-hardware.org/?probe=cd2e9dd7af) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [5962a98f24](https://linux-hardware.org/?probe=5962a98f24) | Oct 23, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [fed2714893](https://linux-hardware.org/?probe=fed2714893) | Oct 19, 2022 |
| HP            | 18E7                        | Desktop     | [db33d9c2c2](https://linux-hardware.org/?probe=db33d9c2c2) | Oct 18, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [5fb0a15135](https://linux-hardware.org/?probe=5fb0a15135) | Oct 18, 2022 |
| ASRock        | X300-ITX                    | Desktop     | [a391ce99bf](https://linux-hardware.org/?probe=a391ce99bf) | Oct 17, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [16239dbee4](https://linux-hardware.org/?probe=16239dbee4) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | Notebook    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| HP            | 2AF7                        | Desktop     | [e5cd1d0cce](https://linux-hardware.org/?probe=e5cd1d0cce) | Oct 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [13581dc0a2](https://linux-hardware.org/?probe=13581dc0a2) | Oct 13, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [2e8206e823](https://linux-hardware.org/?probe=2e8206e823) | Oct 12, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [5eab8a8351](https://linux-hardware.org/?probe=5eab8a8351) | Oct 12, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [55bb52409c](https://linux-hardware.org/?probe=55bb52409c) | Oct 12, 2022 |
| Lenovo        | ThinkPad X220 42873LJ       | Notebook    | [b96b26c09b](https://linux-hardware.org/?probe=b96b26c09b) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [dd3d3724d6](https://linux-hardware.org/?probe=dd3d3724d6) | Oct 10, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [d5f7a80d34](https://linux-hardware.org/?probe=d5f7a80d34) | Oct 06, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [68a9782e38](https://linux-hardware.org/?probe=68a9782e38) | Oct 06, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [53516b2a9d](https://linux-hardware.org/?probe=53516b2a9d) | Oct 06, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5a1df518da](https://linux-hardware.org/?probe=5a1df518da) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [be11beaedd](https://linux-hardware.org/?probe=be11beaedd) | Oct 02, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| NEC Comput... | PC-VRL21FB6S3R7             | Notebook    | [2001e2e28e](https://linux-hardware.org/?probe=2001e2e28e) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [d1b6a74f84](https://linux-hardware.org/?probe=d1b6a74f84) | Sep 29, 2022 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [571cb4bb05](https://linux-hardware.org/?probe=571cb4bb05) | Sep 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3052bded51](https://linux-hardware.org/?probe=3052bded51) | Sep 28, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Fujitsu       | FMVA1200G                   | Notebook    | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [efe1609ac0](https://linux-hardware.org/?probe=efe1609ac0) | Sep 24, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | Notebook    | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [e074efb108](https://linux-hardware.org/?probe=e074efb108) | Sep 18, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [4b8841b706](https://linux-hardware.org/?probe=4b8841b706) | Sep 18, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| EPSON DIRE... | Endeavor NJ3100E            | Notebook    | [47cb342ecf](https://linux-hardware.org/?probe=47cb342ecf) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| Sony          | VAIO                        | All in one  | [71ae1045da](https://linux-hardware.org/?probe=71ae1045da) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| System76      | Lemur Pro                   | Notebook    | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Dell          | Latitude 7420               | Notebook    | [211c7ab44c](https://linux-hardware.org/?probe=211c7ab44c) | Sep 12, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [3bdc70035e](https://linux-hardware.org/?probe=3bdc70035e) | Sep 11, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e6bf2b7f3f](https://linux-hardware.org/?probe=e6bf2b7f3f) | Sep 10, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [21db941a5b](https://linux-hardware.org/?probe=21db941a5b) | Sep 10, 2022 |
| ASRock        | H370 Pro4                   | Desktop     | [f6b34cb2b6](https://linux-hardware.org/?probe=f6b34cb2b6) | Sep 10, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [678759289b](https://linux-hardware.org/?probe=678759289b) | Sep 09, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [c34e343671](https://linux-hardware.org/?probe=c34e343671) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [c21f59dee9](https://linux-hardware.org/?probe=c21f59dee9) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [adfeeb4193](https://linux-hardware.org/?probe=adfeeb4193) | Sep 04, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [57a4b23951](https://linux-hardware.org/?probe=57a4b23951) | Sep 03, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [9f5dc24fa0](https://linux-hardware.org/?probe=9f5dc24fa0) | Sep 02, 2022 |
| Intel         | D34010WYB H14771-304        | Desktop     | [47d9609ba8](https://linux-hardware.org/?probe=47d9609ba8) | Sep 01, 2022 |
| Intel         | D34010WYB H14771-304        | Desktop     | [fd34481bf8](https://linux-hardware.org/?probe=fd34481bf8) | Sep 01, 2022 |
| HP            | 18E7                        | Desktop     | [613d55d0e9](https://linux-hardware.org/?probe=613d55d0e9) | Aug 27, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| Biostar       | B660MX-E                    | Desktop     | [4fa9d132c2](https://linux-hardware.org/?probe=4fa9d132c2) | Aug 26, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [05a337504b](https://linux-hardware.org/?probe=05a337504b) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | Notebook    | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| Sony          | VAIO                        | All in one  | [3ed1ad79e4](https://linux-hardware.org/?probe=3ed1ad79e4) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | Desktop     | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [f50babde6a](https://linux-hardware.org/?probe=f50babde6a) | Aug 23, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [7596762e80](https://linux-hardware.org/?probe=7596762e80) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [bbcdb246aa](https://linux-hardware.org/?probe=bbcdb246aa) | Aug 16, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [79b28d4c5f](https://linux-hardware.org/?probe=79b28d4c5f) | Aug 16, 2022 |
| Toshiba       | dynabook T75/RW             | Notebook    | [ff35aa835d](https://linux-hardware.org/?probe=ff35aa835d) | Aug 15, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [5106d4eda8](https://linux-hardware.org/?probe=5106d4eda8) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| Dell          | 0978PJ A03                  | Server      | [382f999542](https://linux-hardware.org/?probe=382f999542) | Aug 14, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [e59ee250ad](https://linux-hardware.org/?probe=e59ee250ad) | Aug 13, 2022 |
| System76      | Oryx Pro                    | Notebook    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [4ec9a5896d](https://linux-hardware.org/?probe=4ec9a5896d) | Aug 12, 2022 |
| Sony          | VAIO                        | All in one  | [2defaa2f88](https://linux-hardware.org/?probe=2defaa2f88) | Aug 10, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| Sony          | VAIO                        | All in one  | [dd9f2633fe](https://linux-hardware.org/?probe=dd9f2633fe) | Aug 07, 2022 |
| Toshiba       | dynabook R732/G             | Notebook    | [82ef8736b3](https://linux-hardware.org/?probe=82ef8736b3) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9be9a3e83b](https://linux-hardware.org/?probe=9be9a3e83b) | Aug 01, 2022 |
| Toshiba       | All In One PC MP            | All in one  | [4d493ab3df](https://linux-hardware.org/?probe=4d493ab3df) | Jul 31, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [ea8bb6486b](https://linux-hardware.org/?probe=ea8bb6486b) | Jul 30, 2022 |
| ASUSTek       | M4N78                       | Desktop     | [870702db59](https://linux-hardware.org/?probe=870702db59) | Jul 29, 2022 |
| Toshiba       | dynabook B350/22A           | Notebook    | [7a5344db19](https://linux-hardware.org/?probe=7a5344db19) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | Desktop     | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Toshiba       | dynabook R734/K             | Notebook    | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| NEC Comput... | U2                          | Notebook    | [22314f4475](https://linux-hardware.org/?probe=22314f4475) | Jul 25, 2022 |
| Dell          | Latitude 7320               | Notebook    | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| ASRock        | H470M Pro4                  | Desktop     | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b63e85ff7e](https://linux-hardware.org/?probe=b63e85ff7e) | Jul 25, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | Desktop     | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | Desktop     | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| GALAX         | H310M-A V2                  | Desktop     | [db46aaa3aa](https://linux-hardware.org/?probe=db46aaa3aa) | Jul 24, 2022 |
| Alienware     | m17                         | Notebook    | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [a09d9de883](https://linux-hardware.org/?probe=a09d9de883) | Jul 23, 2022 |
| NEC Comput... | PC-VJ24LLZCB                | Notebook    | [9b0955cfe2](https://linux-hardware.org/?probe=9b0955cfe2) | Jul 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| MouseCompu... | L140MU                      | Notebook    | [5206d679a2](https://linux-hardware.org/?probe=5206d679a2) | Jul 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [a81e48e206](https://linux-hardware.org/?probe=a81e48e206) | Jul 15, 2022 |
| Panasonic     | CF-S10EYADR                 | Notebook    | [1990cd2a08](https://linux-hardware.org/?probe=1990cd2a08) | Jul 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [08b3f5414e](https://linux-hardware.org/?probe=08b3f5414e) | Jul 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [42d81e0803](https://linux-hardware.org/?probe=42d81e0803) | Jul 13, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| ASRock        | AMCP7A-ION                  | Desktop     | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8cf2a64c6b](https://linux-hardware.org/?probe=8cf2a64c6b) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [85fe785be5](https://linux-hardware.org/?probe=85fe785be5) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [27c1dae829](https://linux-hardware.org/?probe=27c1dae829) | Jul 08, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d403c021c](https://linux-hardware.org/?probe=6d403c021c) | Jun 29, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [ba68b99167](https://linux-hardware.org/?probe=ba68b99167) | Jun 27, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [fc3e083086](https://linux-hardware.org/?probe=fc3e083086) | Jun 26, 2022 |
| MSI           | Creator X299                | Desktop     | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b841edf2b7](https://linux-hardware.org/?probe=b841edf2b7) | Jun 19, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [2f722cf462](https://linux-hardware.org/?probe=2f722cf462) | Jun 17, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [cbf5603095](https://linux-hardware.org/?probe=cbf5603095) | Jun 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [197482fd83](https://linux-hardware.org/?probe=197482fd83) | Jun 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [1ae160fee2](https://linux-hardware.org/?probe=1ae160fee2) | Jun 13, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9de5875af1](https://linux-hardware.org/?probe=9de5875af1) | Jun 08, 2022 |
| Sony          | VGN-Z71JB                   | Notebook    | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [d4a2222ff7](https://linux-hardware.org/?probe=d4a2222ff7) | Jun 07, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| Alienware     | 13 R3                       | Notebook    | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [0d24b53837](https://linux-hardware.org/?probe=0d24b53837) | Jun 02, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [ca67455f28](https://linux-hardware.org/?probe=ca67455f28) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| Teclast       | X16                         | Tablet      | [f896e98656](https://linux-hardware.org/?probe=f896e98656) | May 28, 2022 |
| ASUSTek       | 900                         | Notebook    | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | Notebook    | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| Gateway       | NV57H                       | Notebook    | [75c484ec74](https://linux-hardware.org/?probe=75c484ec74) | May 26, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [515c374814](https://linux-hardware.org/?probe=515c374814) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| MouseCompu... | B5-R5RENASW11               | Notebook    | [35eae81eca](https://linux-hardware.org/?probe=35eae81eca) | May 25, 2022 |
| ASUSTek       | 900                         | Notebook    | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| MouseCompu... | B360M-ITX                   | Desktop     | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [671279f960](https://linux-hardware.org/?probe=671279f960) | May 18, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [05d8136964](https://linux-hardware.org/?probe=05d8136964) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Alienware     | 17                          | Notebook    | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [95339de38e](https://linux-hardware.org/?probe=95339de38e) | May 13, 2022 |
| Unknown       | MSL01 Series                | Desktop     | [1c66319969](https://linux-hardware.org/?probe=1c66319969) | May 11, 2022 |
| MouseCompu... | X99-S01                     | Desktop     | [69ac1048e9](https://linux-hardware.org/?probe=69ac1048e9) | May 11, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [fff817aea6](https://linux-hardware.org/?probe=fff817aea6) | May 10, 2022 |
| Thirdwave     | DX-T7                       | Notebook    | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Fujitsu       | FMVNTCAKB                   | Notebook    | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| ASUSTek       | 900                         | Notebook    | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [78b1868a67](https://linux-hardware.org/?probe=78b1868a67) | May 08, 2022 |
| ASUSTek       | 900                         | Notebook    | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| Toshiba       | dynabook R731/37EK          | Notebook    | [10ed6c8741](https://linux-hardware.org/?probe=10ed6c8741) | May 06, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| ASRock        | QC5000-ITX/WiFi             | Desktop     | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| AZW           | GK mini                     | Mini pc     | [9d00f58b53](https://linux-hardware.org/?probe=9d00f58b53) | May 04, 2022 |
| AZW           | GK mini                     | Mini pc     | [d474b9b330](https://linux-hardware.org/?probe=d474b9b330) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | 900                         | Notebook    | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | Inspiron 15-3565            | Notebook    | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [b07e1c97aa](https://linux-hardware.org/?probe=b07e1c97aa) | Apr 29, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [5e6c23c3b5](https://linux-hardware.org/?probe=5e6c23c3b5) | Apr 28, 2022 |
| Dell          | Inspiron 15-3565            | Notebook    | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f6df392394](https://linux-hardware.org/?probe=f6df392394) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c9fb277b57](https://linux-hardware.org/?probe=c9fb277b57) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [bbb524450f](https://linux-hardware.org/?probe=bbb524450f) | Apr 27, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| MouseCompu... | NH55Dx                      | Notebook    | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Dell          | 0NW73C A01                  | Desktop     | [430f7b0e3a](https://linux-hardware.org/?probe=430f7b0e3a) | Apr 23, 2022 |
| ASRock        | P5B-DE                      | Desktop     | [b9b6d17274](https://linux-hardware.org/?probe=b9b6d17274) | Apr 23, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [589bc2d17a](https://linux-hardware.org/?probe=589bc2d17a) | Apr 20, 2022 |
| Panasonic     | CF-S10EYADR                 | Notebook    | [efd3e5ce84](https://linux-hardware.org/?probe=efd3e5ce84) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [a3996b5033](https://linux-hardware.org/?probe=a3996b5033) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Thirdwave     | DX-T7                       | Notebook    | [b03707283b](https://linux-hardware.org/?probe=b03707283b) | Apr 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0ad6471ecf](https://linux-hardware.org/?probe=0ad6471ecf) | Apr 16, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [973d2cc2f1](https://linux-hardware.org/?probe=973d2cc2f1) | Apr 15, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [fd8d5ab56a](https://linux-hardware.org/?probe=fd8d5ab56a) | Apr 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3fade276ac](https://linux-hardware.org/?probe=3fade276ac) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c40cfcc7fe](https://linux-hardware.org/?probe=c40cfcc7fe) | Apr 12, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI           | H170A PC MATE               | Desktop     | [404f32fc8a](https://linux-hardware.org/?probe=404f32fc8a) | Apr 11, 2022 |
| MSI           | B350I PRO AC                | Desktop     | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [5a344e20d6](https://linux-hardware.org/?probe=5a344e20d6) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | Notebook    | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [188a7794dd](https://linux-hardware.org/?probe=188a7794dd) | Apr 04, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [b7c7776f50](https://linux-hardware.org/?probe=b7c7776f50) | Apr 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [2759f18a1f](https://linux-hardware.org/?probe=2759f18a1f) | Apr 04, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [41cd5e79c8](https://linux-hardware.org/?probe=41cd5e79c8) | Apr 03, 2022 |
| MouseCompu... | MB-J370                     | Notebook    | [2c72ea9b17](https://linux-hardware.org/?probe=2c72ea9b17) | Apr 02, 2022 |
| ASUSTek       | PB50                        | Desktop     | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [d17d5e5310](https://linux-hardware.org/?probe=d17d5e5310) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [20aac26c6d](https://linux-hardware.org/?probe=20aac26c6d) | Mar 31, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | Desktop     | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| ASUSTek       | T103HAF                     | Tablet      | [fd9c463d07](https://linux-hardware.org/?probe=fd9c463d07) | Mar 28, 2022 |
| ASUSTek       | T103HAF                     | Tablet      | [a3ac6c88a7](https://linux-hardware.org/?probe=a3ac6c88a7) | Mar 27, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | Desktop     | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| System76      | Lemur Pro                   | Notebook    | [cd847b5e6a](https://linux-hardware.org/?probe=cd847b5e6a) | Mar 23, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [0e17f0194f](https://linux-hardware.org/?probe=0e17f0194f) | Mar 22, 2022 |
| Fujitsu       | FMVA05003                   | Notebook    | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [46f513206b](https://linux-hardware.org/?probe=46f513206b) | Mar 18, 2022 |
| Dell          | G3 3500                     | Notebook    | [9ca3e10f43](https://linux-hardware.org/?probe=9ca3e10f43) | Mar 14, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5c3993ef06](https://linux-hardware.org/?probe=5c3993ef06) | Mar 14, 2022 |
| R.W.C         | RM-A107-SR                  | Notebook    | [ab4bef6a90](https://linux-hardware.org/?probe=ab4bef6a90) | Mar 13, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b170ce8fbe](https://linux-hardware.org/?probe=b170ce8fbe) | Mar 11, 2022 |
| Dell          | Latitude E5470              | Notebook    | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [f1d0d25b44](https://linux-hardware.org/?probe=f1d0d25b44) | Mar 06, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | Notebook    | [2f2d99c83f](https://linux-hardware.org/?probe=2f2d99c83f) | Mar 03, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | Notebook    | [0d0a2bab7a](https://linux-hardware.org/?probe=0d0a2bab7a) | Mar 03, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| HP            | Notebook                    | Notebook    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| HP            | 18E7                        | Desktop     | [07d0861eff](https://linux-hardware.org/?probe=07d0861eff) | Feb 28, 2022 |
| ASRock        | H77M                        | Desktop     | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | Notebook    | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Fujitsu       | FMVA33LB2                   | Notebook    | [2dc30249b7](https://linux-hardware.org/?probe=2dc30249b7) | Feb 26, 2022 |
| Lenovo        | ThinkPad X220 4290LG4       | Notebook    | [bfb13999b0](https://linux-hardware.org/?probe=bfb13999b0) | Feb 26, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [0fadf2b0fa](https://linux-hardware.org/?probe=0fadf2b0fa) | Feb 23, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [ec10edeb39](https://linux-hardware.org/?probe=ec10edeb39) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [9483d7b48e](https://linux-hardware.org/?probe=9483d7b48e) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2c1109afb8](https://linux-hardware.org/?probe=2c1109afb8) | Feb 21, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [f869338cb0](https://linux-hardware.org/?probe=f869338cb0) | Feb 20, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [4675d06ffb](https://linux-hardware.org/?probe=4675d06ffb) | Feb 19, 2022 |
| NEC Comput... | IH81M                       | Desktop     | [5e60991665](https://linux-hardware.org/?probe=5e60991665) | Feb 18, 2022 |
| Apple         | MacBookAir3,2               | Notebook    | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [15ae5870b9](https://linux-hardware.org/?probe=15ae5870b9) | Feb 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [e55e0df499](https://linux-hardware.org/?probe=e55e0df499) | Feb 16, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [041b4e9976](https://linux-hardware.org/?probe=041b4e9976) | Feb 16, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [b2414fb6fc](https://linux-hardware.org/?probe=b2414fb6fc) | Feb 15, 2022 |
| Fujitsu       | FARQ02010                   | Notebook    | [04fbabcfd2](https://linux-hardware.org/?probe=04fbabcfd2) | Feb 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [efcb060233](https://linux-hardware.org/?probe=efcb060233) | Feb 14, 2022 |
| Toshiba       | dynabook QOSMIO V65/86LY... | Notebook    | [681aa0b345](https://linux-hardware.org/?probe=681aa0b345) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [1ee503a497](https://linux-hardware.org/?probe=1ee503a497) | Feb 13, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [976cefe591](https://linux-hardware.org/?probe=976cefe591) | Feb 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a5d02d3a03](https://linux-hardware.org/?probe=a5d02d3a03) | Feb 13, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [f5cef9fe9b](https://linux-hardware.org/?probe=f5cef9fe9b) | Feb 13, 2022 |
| Intel         | NUC8BEB J72692-305          | Mini pc     | [c39feb563d](https://linux-hardware.org/?probe=c39feb563d) | Feb 12, 2022 |
| MouseCompu... | B75H2-M2                    | Desktop     | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [bc3f44c0b9](https://linux-hardware.org/?probe=bc3f44c0b9) | Feb 10, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0c54ad1557](https://linux-hardware.org/?probe=0c54ad1557) | Feb 10, 2022 |
| ASUSTek       | U24A                        | Notebook    | [47e8fc096a](https://linux-hardware.org/?probe=47e8fc096a) | Feb 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [218f370835](https://linux-hardware.org/?probe=218f370835) | Feb 10, 2022 |
| Dell          | XPS L401X                   | Notebook    | [1db7a71e79](https://linux-hardware.org/?probe=1db7a71e79) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [76a7934681](https://linux-hardware.org/?probe=76a7934681) | Feb 09, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [ed806edbbb](https://linux-hardware.org/?probe=ed806edbbb) | Feb 09, 2022 |
| ASRock        | H55DE3                      | Desktop     | [7d4fb5775f](https://linux-hardware.org/?probe=7d4fb5775f) | Feb 09, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [fcaddfe60e](https://linux-hardware.org/?probe=fcaddfe60e) | Feb 09, 2022 |
| MCJ           | H67H2-M4                    | Desktop     | [3814208f36](https://linux-hardware.org/?probe=3814208f36) | Feb 08, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b9c77d9df2](https://linux-hardware.org/?probe=b9c77d9df2) | Feb 08, 2022 |
| Lenovo        | ThinkPad X240 20ALCTO1WW    | Notebook    | [1620a85467](https://linux-hardware.org/?probe=1620a85467) | Feb 08, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [afafec99f9](https://linux-hardware.org/?probe=afafec99f9) | Feb 08, 2022 |
| Toshiba       | dynabook Satellite B453/... | Notebook    | [279ff9b0f0](https://linux-hardware.org/?probe=279ff9b0f0) | Feb 08, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [61cc7bdcc2](https://linux-hardware.org/?probe=61cc7bdcc2) | Feb 06, 2022 |
| ASUSTek       | S101                        | Notebook    | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [aa1c79ab75](https://linux-hardware.org/?probe=aa1c79ab75) | Feb 03, 2022 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [7f27062e48](https://linux-hardware.org/?probe=7f27062e48) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek       | P8Z77-M                     | Desktop     | [cb5f618a4b](https://linux-hardware.org/?probe=cb5f618a4b) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | Desktop     | [0c1b8480b6](https://linux-hardware.org/?probe=0c1b8480b6) | Jan 31, 2022 |
| ASUSTek       | U24A                        | Notebook    | [c49e4b9513](https://linux-hardware.org/?probe=c49e4b9513) | Jan 31, 2022 |
| AMI           | Intel                       | Notebook    | [33011a4745](https://linux-hardware.org/?probe=33011a4745) | Jan 31, 2022 |
| AMI           | Intel                       | Notebook    | [f749123fdd](https://linux-hardware.org/?probe=f749123fdd) | Jan 31, 2022 |
| ASUSTek       | U24A                        | Notebook    | [cc19cff1a9](https://linux-hardware.org/?probe=cc19cff1a9) | Jan 30, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [ee9b2f44e9](https://linux-hardware.org/?probe=ee9b2f44e9) | Jan 29, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| ASUSTek       | UX303LA                     | Notebook    | [b5e498daf0](https://linux-hardware.org/?probe=b5e498daf0) | Jan 28, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [3d4087dc2a](https://linux-hardware.org/?probe=3d4087dc2a) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [4ba92ab5ea](https://linux-hardware.org/?probe=4ba92ab5ea) | Jan 23, 2022 |
| Dell          | Latitude 3540               | Notebook    | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [9418716c6b](https://linux-hardware.org/?probe=9418716c6b) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [57fe150494](https://linux-hardware.org/?probe=57fe150494) | Jan 14, 2022 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [56b639daeb](https://linux-hardware.org/?probe=56b639daeb) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| ASUSTek       | N3150I-C                    | Desktop     | [ae91e3cc7b](https://linux-hardware.org/?probe=ae91e3cc7b) | Jan 13, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [8f0b1342b0](https://linux-hardware.org/?probe=8f0b1342b0) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [73ff2bcb33](https://linux-hardware.org/?probe=73ff2bcb33) | Jan 10, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [7539f3648f](https://linux-hardware.org/?probe=7539f3648f) | Jan 09, 2022 |
| ASUSTek       | P8H61-I                     | Desktop     | [261ea10bf8](https://linux-hardware.org/?probe=261ea10bf8) | Jan 08, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [7f928f794b](https://linux-hardware.org/?probe=7f928f794b) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | Notebook    | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9a29b00ea8](https://linux-hardware.org/?probe=9a29b00ea8) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [618b37e477](https://linux-hardware.org/?probe=618b37e477) | Jan 01, 2022 |
| Dell          | Inspiron 5557               | Notebook    | [53d769eaf7](https://linux-hardware.org/?probe=53d769eaf7) | Dec 31, 2021 |
| System76      | Lemur Pro                   | Notebook    | [287aa601fe](https://linux-hardware.org/?probe=287aa601fe) | Dec 29, 2021 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | Notebook    | [0b20db823c](https://linux-hardware.org/?probe=0b20db823c) | Dec 29, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| HP            | 83EE                        | Desktop     | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [68010a3af5](https://linux-hardware.org/?probe=68010a3af5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [2d4a0a1823](https://linux-hardware.org/?probe=2d4a0a1823) | Dec 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| Intel         | NUC7JYB J67967-405          | Mini pc     | [d6850cd8f7](https://linux-hardware.org/?probe=d6850cd8f7) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [526e490544](https://linux-hardware.org/?probe=526e490544) | Dec 17, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [7d976b30fc](https://linux-hardware.org/?probe=7d976b30fc) | Dec 17, 2021 |
| ASRock        | B550 TW                     | Desktop     | [83c53ad524](https://linux-hardware.org/?probe=83c53ad524) | Dec 17, 2021 |
| Dell          | Inspiron 13 5310            | Notebook    | [bdad2f1618](https://linux-hardware.org/?probe=bdad2f1618) | Dec 14, 2021 |
| HP            | 8054                        | Desktop     | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [dac259cc34](https://linux-hardware.org/?probe=dac259cc34) | Dec 13, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [1b14f17a6e](https://linux-hardware.org/?probe=1b14f17a6e) | Dec 11, 2021 |
| NEC Comput... | PC-TW508CAS                 | Tablet      | [06fe78096e](https://linux-hardware.org/?probe=06fe78096e) | Dec 09, 2021 |
| NEC Comput... | PC-TW508CAS                 | Tablet      | [7e305e10d6](https://linux-hardware.org/?probe=7e305e10d6) | Dec 09, 2021 |
| sunxi         | FriendlyARM NanoPi NEO      | Soc         | [031d844c3a](https://linux-hardware.org/?probe=031d844c3a) | Dec 05, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [3e6b2c12f8](https://linux-hardware.org/?probe=3e6b2c12f8) | Dec 05, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [b3c78d548b](https://linux-hardware.org/?probe=b3c78d548b) | Dec 03, 2021 |
| Apple         | MacBookPro13,2              | Notebook    | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [d63f7874c8](https://linux-hardware.org/?probe=d63f7874c8) | Nov 29, 2021 |
| Dell          | G3 3779                     | Notebook    | [cd6dace549](https://linux-hardware.org/?probe=cd6dace549) | Nov 26, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [dca6d021bb](https://linux-hardware.org/?probe=dca6d021bb) | Nov 23, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| ASUSTek       | P8H61-I                     | Desktop     | [bb8c25b299](https://linux-hardware.org/?probe=bb8c25b299) | Nov 20, 2021 |
| MouseCompu... | B75M-D3V-JP                 | Desktop     | [161d355bcc](https://linux-hardware.org/?probe=161d355bcc) | Nov 18, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [268e60a948](https://linux-hardware.org/?probe=268e60a948) | Nov 17, 2021 |
| MouseCompu... | B360M                       | Desktop     | [cab585062a](https://linux-hardware.org/?probe=cab585062a) | Nov 13, 2021 |
| ASUSTek       | H97-PRO                     | Desktop     | [99f09523d8](https://linux-hardware.org/?probe=99f09523d8) | Nov 12, 2021 |
| ASUSTek       | H170-PRO                    | Desktop     | [f3a3f86928](https://linux-hardware.org/?probe=f3a3f86928) | Nov 12, 2021 |
| HP            | 3047h                       | Desktop     | [192742e5a6](https://linux-hardware.org/?probe=192742e5a6) | Nov 12, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | 3047h                       | Desktop     | [935aac64ef](https://linux-hardware.org/?probe=935aac64ef) | Nov 11, 2021 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [982fbc9995](https://linux-hardware.org/?probe=982fbc9995) | Nov 10, 2021 |
| Lenovo        | G580 26897JJ                | Notebook    | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| MouseCompu... | Z490M-S01                   | Desktop     | [bd810f8122](https://linux-hardware.org/?probe=bd810f8122) | Nov 10, 2021 |
| Dell          | Inspiron M5110              | Notebook    | [4a6d42444c](https://linux-hardware.org/?probe=4a6d42444c) | Nov 10, 2021 |
| System76      | Lemur Pro                   | Notebook    | [92a5e9c183](https://linux-hardware.org/?probe=92a5e9c183) | Nov 09, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [34e330ff50](https://linux-hardware.org/?probe=34e330ff50) | Nov 07, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | Notebook    | [0193f0b7a0](https://linux-hardware.org/?probe=0193f0b7a0) | Nov 06, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [80a8e89f7e](https://linux-hardware.org/?probe=80a8e89f7e) | Nov 06, 2021 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [470204d924](https://linux-hardware.org/?probe=470204d924) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d62808ad60](https://linux-hardware.org/?probe=d62808ad60) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6321f2a677](https://linux-hardware.org/?probe=6321f2a677) | Nov 03, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [834bf06329](https://linux-hardware.org/?probe=834bf06329) | Nov 03, 2021 |
| Dell          | 0P301D A02                  | Desktop     | [26462404f4](https://linux-hardware.org/?probe=26462404f4) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| HP            | 3047h                       | Desktop     | [afa4f5c1d0](https://linux-hardware.org/?probe=afa4f5c1d0) | Oct 28, 2021 |
| HP            | 3047h                       | Desktop     | [d5e5504f54](https://linux-hardware.org/?probe=d5e5504f54) | Oct 28, 2021 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Dell          | G5 5500                     | Notebook    | [cf10cd5b99](https://linux-hardware.org/?probe=cf10cd5b99) | Oct 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [a0bf764d45](https://linux-hardware.org/?probe=a0bf764d45) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | Desktop     | [1d14b9b944](https://linux-hardware.org/?probe=1d14b9b944) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6aa4ae0da5](https://linux-hardware.org/?probe=6aa4ae0da5) | Oct 23, 2021 |
| HP            | ProBook 6550b               | Notebook    | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Dell          | G3 3779                     | Notebook    | [a84248c5d5](https://linux-hardware.org/?probe=a84248c5d5) | Oct 21, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| EPSON DIRE... | ST170E                      | Desktop     | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Jumper        | Ezbook X3                   | Notebook    | [fe510b821a](https://linux-hardware.org/?probe=fe510b821a) | Oct 17, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | Desktop     | [4efe80812c](https://linux-hardware.org/?probe=4efe80812c) | Oct 16, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [e7ab53c038](https://linux-hardware.org/?probe=e7ab53c038) | Oct 15, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [42b4e70ef9](https://linux-hardware.org/?probe=42b4e70ef9) | Oct 15, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| NEC Comput... | PC-LL550VG6R                | Notebook    | [5879ce1d61](https://linux-hardware.org/?probe=5879ce1d61) | Oct 13, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [5ed3b7e62d](https://linux-hardware.org/?probe=5ed3b7e62d) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| ASRock        | H67DE                       | Desktop     | [491ac17e42](https://linux-hardware.org/?probe=491ac17e42) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [e1543ea8f8](https://linux-hardware.org/?probe=e1543ea8f8) | Oct 09, 2021 |
| Toshiba       | dynabook R634/K             | Notebook    | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [6918b927d0](https://linux-hardware.org/?probe=6918b927d0) | Oct 07, 2021 |
| ASUSTek       | M51AC                       | Desktop     | [0d9722a373](https://linux-hardware.org/?probe=0d9722a373) | Oct 05, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [0b768f6fac](https://linux-hardware.org/?probe=0b768f6fac) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c920ce007](https://linux-hardware.org/?probe=1c920ce007) | Oct 03, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0d05812341](https://linux-hardware.org/?probe=0d05812341) | Oct 02, 2021 |
| Fujitsu       | U9311                       | Notebook    | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| Panasonic     | CFSV9-2                     | Notebook    | [05b8edc925](https://linux-hardware.org/?probe=05b8edc925) | Sep 29, 2021 |
| ASRock        | H67DE                       | Desktop     | [296abe4896](https://linux-hardware.org/?probe=296abe4896) | Sep 28, 2021 |
| ASRock        | H67DE                       | Desktop     | [e663e151d6](https://linux-hardware.org/?probe=e663e151d6) | Sep 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [8b3dfbb8a4](https://linux-hardware.org/?probe=8b3dfbb8a4) | Sep 25, 2021 |
| NEC Comput... | PC-GN15B79AA                | Notebook    | [a1046b626e](https://linux-hardware.org/?probe=a1046b626e) | Sep 23, 2021 |
| NEC Comput... | PC-GN15B79AA                | Notebook    | [a1b9f1dc30](https://linux-hardware.org/?probe=a1b9f1dc30) | Sep 23, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | Notebook    | [b0289ef67d](https://linux-hardware.org/?probe=b0289ef67d) | Sep 22, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [5164ba24f6](https://linux-hardware.org/?probe=5164ba24f6) | Sep 21, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b613f0c8a9](https://linux-hardware.org/?probe=b613f0c8a9) | Sep 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6f52a2ebed](https://linux-hardware.org/?probe=6f52a2ebed) | Sep 18, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [19173612af](https://linux-hardware.org/?probe=19173612af) | Sep 18, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [06d99f6a80](https://linux-hardware.org/?probe=06d99f6a80) | Sep 17, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [34aff1f974](https://linux-hardware.org/?probe=34aff1f974) | Sep 17, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [8c9476bcae](https://linux-hardware.org/?probe=8c9476bcae) | Sep 17, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [0ab25d0365](https://linux-hardware.org/?probe=0ab25d0365) | Sep 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3534d3e5f1](https://linux-hardware.org/?probe=3534d3e5f1) | Sep 13, 2021 |
| Panasonic     | CF-S10EYTDR                 | Notebook    | [a90d037dcf](https://linux-hardware.org/?probe=a90d037dcf) | Sep 10, 2021 |
| ASUSTek       | G551JM                      | Notebook    | [9f323164cd](https://linux-hardware.org/?probe=9f323164cd) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [617e5dd237](https://linux-hardware.org/?probe=617e5dd237) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | Notebook    | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [f5d32061ec](https://linux-hardware.org/?probe=f5d32061ec) | Sep 08, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [2a289951de](https://linux-hardware.org/?probe=2a289951de) | Sep 07, 2021 |
| Toshiba       | dynabook T55/PW             | Notebook    | [1ce1b25ad5](https://linux-hardware.org/?probe=1ce1b25ad5) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 2306A44       | Notebook    | [8f97e284a7](https://linux-hardware.org/?probe=8f97e284a7) | Sep 03, 2021 |
| Toshiba       | dynabook R73/A              | Notebook    | [deb0351e19](https://linux-hardware.org/?probe=deb0351e19) | Sep 03, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [919b7c1304](https://linux-hardware.org/?probe=919b7c1304) | Sep 01, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [469dc0f2ef](https://linux-hardware.org/?probe=469dc0f2ef) | Aug 31, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [47f44e561f](https://linux-hardware.org/?probe=47f44e561f) | Aug 31, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | Desktop     | [22d7fff01c](https://linux-hardware.org/?probe=22d7fff01c) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | Desktop     | [5736465e27](https://linux-hardware.org/?probe=5736465e27) | Aug 27, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| EPSON DIRE... | ST150E                      | Desktop     | [797ec7ec81](https://linux-hardware.org/?probe=797ec7ec81) | Aug 24, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Sony          | VGN-S55B_S                  | Notebook    | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [85b8505955](https://linux-hardware.org/?probe=85b8505955) | Aug 20, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [68496a4cb7](https://linux-hardware.org/?probe=68496a4cb7) | Aug 18, 2021 |
| ASRock        | N3150M                      | Desktop     | [932c7baf1a](https://linux-hardware.org/?probe=932c7baf1a) | Aug 17, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| HP            | ProBook 6470b               | Notebook    | [4d338e7f16](https://linux-hardware.org/?probe=4d338e7f16) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [ab538f5af7](https://linux-hardware.org/?probe=ab538f5af7) | Aug 15, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS8E700    | Notebook    | [467f177df6](https://linux-hardware.org/?probe=467f177df6) | Aug 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [5b7a8411f5](https://linux-hardware.org/?probe=5b7a8411f5) | Aug 09, 2021 |
| THD           | RX2                         | Mini pc     | [f7f9324872](https://linux-hardware.org/?probe=f7f9324872) | Aug 09, 2021 |
| NEC Comput... | PC-GN246W3A5                | Notebook    | [dfc05750e3](https://linux-hardware.org/?probe=dfc05750e3) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Teclast       | X6 Pro                      | Tablet      | [ed972212e1](https://linux-hardware.org/?probe=ed972212e1) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Panasonic     | CF-S10EYTDR                 | Notebook    | [b965812f09](https://linux-hardware.org/?probe=b965812f09) | Aug 06, 2021 |
| NEC Comput... | MS-7770HH                   | Desktop     | [7ca677a33c](https://linux-hardware.org/?probe=7ca677a33c) | Aug 03, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [ff5bee5ff8](https://linux-hardware.org/?probe=ff5bee5ff8) | Aug 01, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [0401734340](https://linux-hardware.org/?probe=0401734340) | Jul 31, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [1e02007526](https://linux-hardware.org/?probe=1e02007526) | Jul 30, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [161a673775](https://linux-hardware.org/?probe=161a673775) | Jul 28, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [264959862d](https://linux-hardware.org/?probe=264959862d) | Jul 28, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [63b014e84e](https://linux-hardware.org/?probe=63b014e84e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [478d06f2df](https://linux-hardware.org/?probe=478d06f2df) | Jul 26, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [fbf1f240f4](https://linux-hardware.org/?probe=fbf1f240f4) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | Notebook    | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| HP            | 18E7                        | Desktop     | [c0cddf4243](https://linux-hardware.org/?probe=c0cddf4243) | Jul 23, 2021 |
| Unknown       | XH61X000.100                | Desktop     | [6604251e58](https://linux-hardware.org/?probe=6604251e58) | Jul 23, 2021 |
| HP            | 14                          | Notebook    | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [93a813bbba](https://linux-hardware.org/?probe=93a813bbba) | Jul 22, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| HP            | 1906                        | Desktop     | [6cd7c6ec7f](https://linux-hardware.org/?probe=6cd7c6ec7f) | Jul 20, 2021 |
| HP            | 14                          | Notebook    | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| ASRock        | 880GM-LE                    | Desktop     | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Fujitsu       | FMVS54CD1                   | Notebook    | [7e6aa1f514](https://linux-hardware.org/?probe=7e6aa1f514) | Jul 18, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [80b10e8187](https://linux-hardware.org/?probe=80b10e8187) | Jul 18, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| Fujitsu       | FMVS54CD1                   | Notebook    | [ad9e144c6a](https://linux-hardware.org/?probe=ad9e144c6a) | Jul 15, 2021 |
| HP            | 18E7                        | Desktop     | [03d84525e8](https://linux-hardware.org/?probe=03d84525e8) | Jul 13, 2021 |
| Dell          | Latitude E5510              | Notebook    | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| Toshiba       | dynabook T954/89L           | Notebook    | [176e4906db](https://linux-hardware.org/?probe=176e4906db) | Jul 12, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [d6410ac1a0](https://linux-hardware.org/?probe=d6410ac1a0) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | Notebook    | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3df3921e13](https://linux-hardware.org/?probe=3df3921e13) | Jul 10, 2021 |
| HP            | 872E                        | Mini pc     | [b1de952c4e](https://linux-hardware.org/?probe=b1de952c4e) | Jul 09, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [1b63a19bd1](https://linux-hardware.org/?probe=1b63a19bd1) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [673b1c670f](https://linux-hardware.org/?probe=673b1c670f) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [14789c0301](https://linux-hardware.org/?probe=14789c0301) | Jul 07, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| HP            | 872E                        | Mini pc     | [1cacfccdb9](https://linux-hardware.org/?probe=1cacfccdb9) | Jul 03, 2021 |
| Google        | Helios                      | Notebook    | [644f9f9062](https://linux-hardware.org/?probe=644f9f9062) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | Desktop     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [db7536f5a7](https://linux-hardware.org/?probe=db7536f5a7) | Jun 29, 2021 |
| HP            | 1906                        | Desktop     | [95bfd2283b](https://linux-hardware.org/?probe=95bfd2283b) | Jun 29, 2021 |
| Dell          | Inspiron 5583               | Notebook    | [a1f0396c8e](https://linux-hardware.org/?probe=a1f0396c8e) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | Desktop     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [be23e213b9](https://linux-hardware.org/?probe=be23e213b9) | Jun 26, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [6c86be2586](https://linux-hardware.org/?probe=6c86be2586) | Jun 24, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c2285d9014](https://linux-hardware.org/?probe=c2285d9014) | Jun 22, 2021 |
| Toshiba       | dynabook T954/89L           | Notebook    | [c4b1b8aabb](https://linux-hardware.org/?probe=c4b1b8aabb) | Jun 21, 2021 |
| Toshiba       | dynabook T954/89L           | Notebook    | [b6a5d80f8a](https://linux-hardware.org/?probe=b6a5d80f8a) | Jun 21, 2021 |
| Lenovo        | S10-3                       | Notebook    | [eb48df4717](https://linux-hardware.org/?probe=eb48df4717) | Jun 20, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [76096c0075](https://linux-hardware.org/?probe=76096c0075) | Jun 19, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [03b329894a](https://linux-hardware.org/?probe=03b329894a) | Jun 18, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [4c0e4ebaa4](https://linux-hardware.org/?probe=4c0e4ebaa4) | Jun 16, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [0b50c157fe](https://linux-hardware.org/?probe=0b50c157fe) | Jun 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [2da9390d91](https://linux-hardware.org/?probe=2da9390d91) | Jun 11, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [c33921449f](https://linux-hardware.org/?probe=c33921449f) | Jun 10, 2021 |
| Toshiba       | dynabook R73/BN             | Notebook    | [c9cdf2bc57](https://linux-hardware.org/?probe=c9cdf2bc57) | Jun 06, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| ECS           | G41T-M2                     | Desktop     | [3005be6650](https://linux-hardware.org/?probe=3005be6650) | Jun 04, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [0860242147](https://linux-hardware.org/?probe=0860242147) | Jun 04, 2021 |
| Sony          | VAIO                        | All in one  | [afa509714d](https://linux-hardware.org/?probe=afa509714d) | Jun 03, 2021 |
| Biostar       | B350GTN                     | Notebook    | [6ba7f458da](https://linux-hardware.org/?probe=6ba7f458da) | Jun 01, 2021 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [74057c8385](https://linux-hardware.org/?probe=74057c8385) | May 30, 2021 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [36fb4e2aba](https://linux-hardware.org/?probe=36fb4e2aba) | May 29, 2021 |
| Lenovo        | S10-3                       | Notebook    | [8dfadf5edb](https://linux-hardware.org/?probe=8dfadf5edb) | May 27, 2021 |
| NEC Comput... | PC-LL730TG                  | Notebook    | [e4172892e9](https://linux-hardware.org/?probe=e4172892e9) | May 26, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [4d1d4e61c3](https://linux-hardware.org/?probe=4d1d4e61c3) | May 25, 2021 |
| NEC Comput... | PC-VK22TGGCN                | Notebook    | [b6a2893c7e](https://linux-hardware.org/?probe=b6a2893c7e) | May 25, 2021 |
| Dell          | Latitude E6420              | Notebook    | [4ef6253092](https://linux-hardware.org/?probe=4ef6253092) | May 22, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [4ea4747cbf](https://linux-hardware.org/?probe=4ea4747cbf) | May 18, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [5d215fafdd](https://linux-hardware.org/?probe=5d215fafdd) | May 15, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [fdc8841fca](https://linux-hardware.org/?probe=fdc8841fca) | May 14, 2021 |
| ASUSTek       | PRIME X299-A                | Desktop     | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [6c767dc0df](https://linux-hardware.org/?probe=6c767dc0df) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [5ed8fb5a9f](https://linux-hardware.org/?probe=5ed8fb5a9f) | May 13, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [0e4daa1de2](https://linux-hardware.org/?probe=0e4daa1de2) | May 11, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [232c90ce25](https://linux-hardware.org/?probe=232c90ce25) | May 10, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [c796c57372](https://linux-hardware.org/?probe=c796c57372) | May 10, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [e7238c107c](https://linux-hardware.org/?probe=e7238c107c) | May 09, 2021 |
| Fujitsu       | FMVNF40UK                   | Notebook    | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [f416a7a6b3](https://linux-hardware.org/?probe=f416a7a6b3) | May 09, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aa1f42a8a9](https://linux-hardware.org/?probe=aa1f42a8a9) | May 08, 2021 |
| MouseCompu... | W150ERQ                     | Notebook    | [1ccfec5c8f](https://linux-hardware.org/?probe=1ccfec5c8f) | May 07, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [f001bddea6](https://linux-hardware.org/?probe=f001bddea6) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [65dce9cf99](https://linux-hardware.org/?probe=65dce9cf99) | May 03, 2021 |
| Dynabook      | P1-T6NP-EG                  | Notebook    | [887c9157d0](https://linux-hardware.org/?probe=887c9157d0) | May 03, 2021 |
| HP            | 3047h                       | Desktop     | [3de6f89fae](https://linux-hardware.org/?probe=3de6f89fae) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| Toshiba       | dynabook Satellite J61 1... | Notebook    | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Maibenben     | S431                        | Notebook    | [a4db49a83f](https://linux-hardware.org/?probe=a4db49a83f) | Apr 29, 2021 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [0f15e44442](https://linux-hardware.org/?probe=0f15e44442) | Apr 26, 2021 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [c64bf46d8b](https://linux-hardware.org/?probe=c64bf46d8b) | Apr 24, 2021 |
| ASRock        | P5B-DE                      | Desktop     | [04084bd0ef](https://linux-hardware.org/?probe=04084bd0ef) | Apr 24, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [7a4d236e06](https://linux-hardware.org/?probe=7a4d236e06) | Apr 24, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [dae1fdda5f](https://linux-hardware.org/?probe=dae1fdda5f) | Apr 23, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [fff82cb538](https://linux-hardware.org/?probe=fff82cb538) | Apr 22, 2021 |
| ASUSTek       | N3150I-C                    | Desktop     | [4cfbe212a4](https://linux-hardware.org/?probe=4cfbe212a4) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [af34567550](https://linux-hardware.org/?probe=af34567550) | Apr 17, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [4afc76cdbe](https://linux-hardware.org/?probe=4afc76cdbe) | Apr 17, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b7991a35ba](https://linux-hardware.org/?probe=b7991a35ba) | Apr 16, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [a7ed7cc477](https://linux-hardware.org/?probe=a7ed7cc477) | Apr 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [7a2924ab2a](https://linux-hardware.org/?probe=7a2924ab2a) | Apr 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [c5ed691eb7](https://linux-hardware.org/?probe=c5ed691eb7) | Apr 13, 2021 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [18adf344fe](https://linux-hardware.org/?probe=18adf344fe) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| ASUSTek       | P4V800D-X                   | Desktop     | [c469d16946](https://linux-hardware.org/?probe=c469d16946) | Apr 09, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [122641cd7e](https://linux-hardware.org/?probe=122641cd7e) | Apr 08, 2021 |
| NEC Comput... | PC-VK25TXZCE                | Notebook    | [e6acc84298](https://linux-hardware.org/?probe=e6acc84298) | Apr 07, 2021 |
| Toshiba       | dynabook BX/33M             | Notebook    | [06580ff422](https://linux-hardware.org/?probe=06580ff422) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 23245Y1       | Notebook    | [83430b3adf](https://linux-hardware.org/?probe=83430b3adf) | Apr 06, 2021 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [a5b2555cc2](https://linux-hardware.org/?probe=a5b2555cc2) | Apr 06, 2021 |
| Dynabook      | P1-T6NP-EG                  | Notebook    | [3f0b2d7c1d](https://linux-hardware.org/?probe=3f0b2d7c1d) | Apr 05, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ba17a463a7](https://linux-hardware.org/?probe=ba17a463a7) | Apr 03, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [a579757204](https://linux-hardware.org/?probe=a579757204) | Apr 03, 2021 |
| Toshiba       | dynabook CX/48F             | Notebook    | [d32bf9dced](https://linux-hardware.org/?probe=d32bf9dced) | Apr 02, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [a82050e3ae](https://linux-hardware.org/?probe=a82050e3ae) | Apr 01, 2021 |
| NEC Comput... | MILO2-H 3A3B                | All in one  | [1494683bb9](https://linux-hardware.org/?probe=1494683bb9) | Apr 01, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [0a547ba59a](https://linux-hardware.org/?probe=0a547ba59a) | Mar 31, 2021 |
| Dell          | Latitude E6320              | Notebook    | [2c01829c5b](https://linux-hardware.org/?probe=2c01829c5b) | Mar 28, 2021 |
| Dell          | G3 3500                     | Notebook    | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [22b865b40a](https://linux-hardware.org/?probe=22b865b40a) | Mar 26, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [43c49d259d](https://linux-hardware.org/?probe=43c49d259d) | Mar 26, 2021 |
| HP            | G60                         | Notebook    | [a97ca105eb](https://linux-hardware.org/?probe=a97ca105eb) | Mar 25, 2021 |
| HP            | G60                         | Notebook    | [e8cc7247c7](https://linux-hardware.org/?probe=e8cc7247c7) | Mar 23, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [22b092fe80](https://linux-hardware.org/?probe=22b092fe80) | Mar 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [a4b57558c3](https://linux-hardware.org/?probe=a4b57558c3) | Mar 22, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [52b2fb4ebb](https://linux-hardware.org/?probe=52b2fb4ebb) | Mar 22, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [d5722fd82b](https://linux-hardware.org/?probe=d5722fd82b) | Mar 22, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [e5ce81269b](https://linux-hardware.org/?probe=e5ce81269b) | Mar 22, 2021 |
| HP            | ProBook 430 G7              | Notebook    | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| ASRock        | X370 Pro4                   | Desktop     | [6c6d145ad3](https://linux-hardware.org/?probe=6c6d145ad3) | Mar 20, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [56a39af725](https://linux-hardware.org/?probe=56a39af725) | Mar 20, 2021 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [64164ccce2](https://linux-hardware.org/?probe=64164ccce2) | Mar 19, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [2d9b9381bd](https://linux-hardware.org/?probe=2d9b9381bd) | Mar 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | Notebook    | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [b36b41329b](https://linux-hardware.org/?probe=b36b41329b) | Mar 14, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [cff1baf251](https://linux-hardware.org/?probe=cff1baf251) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [aac22af3a1](https://linux-hardware.org/?probe=aac22af3a1) | Mar 13, 2021 |
| HP            | 212B                        | Desktop     | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T3C... | Notebook    | [7cda624782](https://linux-hardware.org/?probe=7cda624782) | Mar 12, 2021 |
| Biostar       | Hi-Fi A88ZN                 | Desktop     | [72cff94e15](https://linux-hardware.org/?probe=72cff94e15) | Mar 12, 2021 |
| Dynabook      | GCX83/PLE                   | Notebook    | [2ef2ac3448](https://linux-hardware.org/?probe=2ef2ac3448) | Mar 12, 2021 |
| Fujitsu       | FMVS54EB                    | Notebook    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| HP            | 8446                        | All in one  | [2cdf1fd3be](https://linux-hardware.org/?probe=2cdf1fd3be) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bca1731a58](https://linux-hardware.org/?probe=bca1731a58) | Mar 08, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3feff6616d](https://linux-hardware.org/?probe=3feff6616d) | Mar 07, 2021 |
| Dell          | Latitude 7280               | Notebook    | [64e390d0d6](https://linux-hardware.org/?probe=64e390d0d6) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [24088afc25](https://linux-hardware.org/?probe=24088afc25) | Mar 06, 2021 |
| HP            | 212B                        | Desktop     | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| Timi          | RedmiBook 16                | Notebook    | [7139d19a98](https://linux-hardware.org/?probe=7139d19a98) | Mar 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e840817785](https://linux-hardware.org/?probe=e840817785) | Mar 03, 2021 |
| MSI           | C236A WORKSTATION           | Desktop     | [dc9e6c2670](https://linux-hardware.org/?probe=dc9e6c2670) | Mar 03, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [3d2e576c95](https://linux-hardware.org/?probe=3d2e576c95) | Mar 03, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [aa41662477](https://linux-hardware.org/?probe=aa41662477) | Mar 02, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [c08f9a30dc](https://linux-hardware.org/?probe=c08f9a30dc) | Feb 28, 2021 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [16cf45ce16](https://linux-hardware.org/?probe=16cf45ce16) | Feb 28, 2021 |
| Dell          | 0T1D10 A01                  | Desktop     | [3577c78a56](https://linux-hardware.org/?probe=3577c78a56) | Feb 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [65a5a31ae8](https://linux-hardware.org/?probe=65a5a31ae8) | Feb 26, 2021 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [501d2317f9](https://linux-hardware.org/?probe=501d2317f9) | Feb 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5f5d47e737](https://linux-hardware.org/?probe=5f5d47e737) | Feb 26, 2021 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [b1a878b7d0](https://linux-hardware.org/?probe=b1a878b7d0) | Feb 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4ea5b4b7e](https://linux-hardware.org/?probe=f4ea5b4b7e) | Feb 25, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [3e009dec2f](https://linux-hardware.org/?probe=3e009dec2f) | Feb 23, 2021 |
| NEC Comput... | PC-LL750FS6R                | Notebook    | [2708ba9972](https://linux-hardware.org/?probe=2708ba9972) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | Notebook    | [fa1eb2a97a](https://linux-hardware.org/?probe=fa1eb2a97a) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | Notebook    | [cf754cecc4](https://linux-hardware.org/?probe=cf754cecc4) | Feb 23, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7e4e426453](https://linux-hardware.org/?probe=7e4e426453) | Feb 22, 2021 |
| Biostar       | B450GT3                     | Desktop     | [18e0346ed0](https://linux-hardware.org/?probe=18e0346ed0) | Feb 22, 2021 |
| MSI           | C236A WORKSTATION           | Desktop     | [9e2effbe63](https://linux-hardware.org/?probe=9e2effbe63) | Feb 22, 2021 |
| Toshiba       | dynabook Satellite TXW/6... | Notebook    | [51128d9716](https://linux-hardware.org/?probe=51128d9716) | Feb 19, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [5c5b3ce155](https://linux-hardware.org/?probe=5c5b3ce155) | Feb 19, 2021 |
| Toshiba       | dynabook EX/35KWH           | Notebook    | [c52a95f06c](https://linux-hardware.org/?probe=c52a95f06c) | Feb 18, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [e8e114704d](https://linux-hardware.org/?probe=e8e114704d) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [977e293baa](https://linux-hardware.org/?probe=977e293baa) | Feb 16, 2021 |
| MSI           | A78M-E35 V2                 | Desktop     | [173e28a6b2](https://linux-hardware.org/?probe=173e28a6b2) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a2e399875d](https://linux-hardware.org/?probe=a2e399875d) | Feb 15, 2021 |
| Fujitsu       | FMVNFB40J                   | Notebook    | [8a3d6bcc89](https://linux-hardware.org/?probe=8a3d6bcc89) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [c364bd22bf](https://linux-hardware.org/?probe=c364bd22bf) | Feb 14, 2021 |
| Fujitsu       | FMVA05002                   | Notebook    | [a758e3201d](https://linux-hardware.org/?probe=a758e3201d) | Feb 14, 2021 |
| Biostar       | X470NH                      | Desktop     | [b4ae665275](https://linux-hardware.org/?probe=b4ae665275) | Feb 13, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [6b1142fdaa](https://linux-hardware.org/?probe=6b1142fdaa) | Feb 13, 2021 |
| Lenovo        | ThinkPad T61 7659D92        | Notebook    | [8d9f56460d](https://linux-hardware.org/?probe=8d9f56460d) | Feb 13, 2021 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [b384cb32dc](https://linux-hardware.org/?probe=b384cb32dc) | Feb 13, 2021 |
| MSI           | H270I GAMING PRO AC         | Desktop     | [dcae892f29](https://linux-hardware.org/?probe=dcae892f29) | Feb 13, 2021 |
| Fujitsu       | FMVA56GBX                   | Notebook    | [bdc337bd04](https://linux-hardware.org/?probe=bdc337bd04) | Feb 13, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a45a89930f](https://linux-hardware.org/?probe=a45a89930f) | Feb 13, 2021 |
| Fujitsu       | FMVA05002                   | Notebook    | [db95456803](https://linux-hardware.org/?probe=db95456803) | Feb 12, 2021 |
| Panasonic     | CF-SX3EDHCS                 | Notebook    | [3f7a156241](https://linux-hardware.org/?probe=3f7a156241) | Feb 11, 2021 |
| NEC Comput... | PC-VK19SGZDF                | Notebook    | [624a2eee47](https://linux-hardware.org/?probe=624a2eee47) | Feb 10, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [168dfeabe8](https://linux-hardware.org/?probe=168dfeabe8) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | Notebook    | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | Notebook    | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [256969ebac](https://linux-hardware.org/?probe=256969ebac) | Feb 07, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [72061bcca7](https://linux-hardware.org/?probe=72061bcca7) | Feb 06, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [1b421bc93c](https://linux-hardware.org/?probe=1b421bc93c) | Feb 05, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Biostar       | B450GT                      | Desktop     | [2cb5b97972](https://linux-hardware.org/?probe=2cb5b97972) | Feb 02, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [ebe6b1d494](https://linux-hardware.org/?probe=ebe6b1d494) | Feb 02, 2021 |
| Wistron       | J361Y                       | Desktop     | [347eb6b747](https://linux-hardware.org/?probe=347eb6b747) | Jan 31, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [1205deb78e](https://linux-hardware.org/?probe=1205deb78e) | Jan 27, 2021 |
| NEC Comput... | IS8XM                       | Desktop     | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| HP            | 0A54h                       | Desktop     | [9f8677d69a](https://linux-hardware.org/?probe=9f8677d69a) | Jan 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| HP            | 0A54h                       | Desktop     | [6b91501381](https://linux-hardware.org/?probe=6b91501381) | Jan 21, 2021 |
| Microsoft     | Surface 3                   | Tablet      | [66a11d584d](https://linux-hardware.org/?probe=66a11d584d) | Jan 20, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a161a19f04](https://linux-hardware.org/?probe=a161a19f04) | Jan 20, 2021 |
| NEC Comput... | MILO2-H 3A3B                | All in one  | [198709ea08](https://linux-hardware.org/?probe=198709ea08) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| NEC Comput... | PC-LL750SG6R                | Notebook    | [7c9081a73a](https://linux-hardware.org/?probe=7c9081a73a) | Jan 16, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [e5c02d2922](https://linux-hardware.org/?probe=e5c02d2922) | Jan 15, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [8b4d24c14c](https://linux-hardware.org/?probe=8b4d24c14c) | Jan 14, 2021 |
| Gigabyte      | G33-DS3R                    | Desktop     | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | Notebook    | [735d00e026](https://linux-hardware.org/?probe=735d00e026) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | Notebook    | [5df5433a1c](https://linux-hardware.org/?probe=5df5433a1c) | Jan 13, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [1d6691dffe](https://linux-hardware.org/?probe=1d6691dffe) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c77878fdf4](https://linux-hardware.org/?probe=c77878fdf4) | Jan 12, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [5cea01c3c1](https://linux-hardware.org/?probe=5cea01c3c1) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3b66143d43](https://linux-hardware.org/?probe=3b66143d43) | Jan 11, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [293bb6fc26](https://linux-hardware.org/?probe=293bb6fc26) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [8c2793a502](https://linux-hardware.org/?probe=8c2793a502) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [44b1f16e92](https://linux-hardware.org/?probe=44b1f16e92) | Jan 10, 2021 |
| Dell          | 0R7935 A03                  | Desktop     | [1d936da792](https://linux-hardware.org/?probe=1d936da792) | Jan 09, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| HP            | 158A                        | Desktop     | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| MSI           | Creator X299                | Desktop     | [b66f2c1d16](https://linux-hardware.org/?probe=b66f2c1d16) | Jan 06, 2021 |
| ASRock        | J5005-ITX                   | Desktop     | [81bba5a535](https://linux-hardware.org/?probe=81bba5a535) | Jan 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [34d77cfa6e](https://linux-hardware.org/?probe=34d77cfa6e) | Jan 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [07fb95c682](https://linux-hardware.org/?probe=07fb95c682) | Jan 03, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| HUAWEI        | MRC-WX0                     | Notebook    | [f650998a3d](https://linux-hardware.org/?probe=f650998a3d) | Jan 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [f56caad73c](https://linux-hardware.org/?probe=f56caad73c) | Jan 02, 2021 |
| NEC Comput... | MILO2-H 3A3B                | All in one  | [db058b1012](https://linux-hardware.org/?probe=db058b1012) | Jan 01, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [c6ea824e48](https://linux-hardware.org/?probe=c6ea824e48) | Dec 31, 2020 |
| Fujitsu       | FMVLCE50B                   | Notebook    | [03569af3cb](https://linux-hardware.org/?probe=03569af3cb) | Dec 31, 2020 |
| ASRock        | B360M-ITX/ac                | Desktop     | [8e0bce5edb](https://linux-hardware.org/?probe=8e0bce5edb) | Dec 30, 2020 |
| Gateway       | G33M05G1 MP                 | Desktop     | [460acf5c52](https://linux-hardware.org/?probe=460acf5c52) | Dec 30, 2020 |
| MSI           | Modern 14 B4MW              | Notebook    | [ec110ae347](https://linux-hardware.org/?probe=ec110ae347) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | Notebook    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2c76a9b0e9](https://linux-hardware.org/?probe=2c76a9b0e9) | Dec 28, 2020 |
| MSI           | FM2-A75IA-E53               | Desktop     | [ec03bb47a4](https://linux-hardware.org/?probe=ec03bb47a4) | Dec 28, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | Notebook    | [84b2b1cba7](https://linux-hardware.org/?probe=84b2b1cba7) | Dec 26, 2020 |
| Thirdwave     | Diginnos PC                 | Notebook    | [4573bf9eeb](https://linux-hardware.org/?probe=4573bf9eeb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | Notebook    | [f4fe782260](https://linux-hardware.org/?probe=f4fe782260) | Dec 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [fcc97d1fdb](https://linux-hardware.org/?probe=fcc97d1fdb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | Notebook    | [21e571b40f](https://linux-hardware.org/?probe=21e571b40f) | Dec 25, 2020 |
| Dynabook      | P1-T6NP-EG                  | Notebook    | [9f6b496aaf](https://linux-hardware.org/?probe=9f6b496aaf) | Dec 25, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [3ea410030c](https://linux-hardware.org/?probe=3ea410030c) | Dec 24, 2020 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [5401d7dd29](https://linux-hardware.org/?probe=5401d7dd29) | Dec 23, 2020 |
| ASRock        | B360M-ITX/ac                | Desktop     | [39d7373b8e](https://linux-hardware.org/?probe=39d7373b8e) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [d236c778e1](https://linux-hardware.org/?probe=d236c778e1) | Dec 21, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | Notebook    | [6a74695399](https://linux-hardware.org/?probe=6a74695399) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [ca0c3d2795](https://linux-hardware.org/?probe=ca0c3d2795) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [97e9570360](https://linux-hardware.org/?probe=97e9570360) | Dec 21, 2020 |
| HP            | 158A                        | Desktop     | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Dell          | Latitude E6230              | Notebook    | [c0f67befa0](https://linux-hardware.org/?probe=c0f67befa0) | Dec 18, 2020 |
| Dell          | Latitude E6230              | Notebook    | [9dd587de7a](https://linux-hardware.org/?probe=9dd587de7a) | Dec 18, 2020 |
| FIC           | PTM33 PCB                   | Desktop     | [0e1437dede](https://linux-hardware.org/?probe=0e1437dede) | Dec 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [52b0b77ef7](https://linux-hardware.org/?probe=52b0b77ef7) | Dec 17, 2020 |
| Supermicro    | X9DA7/E                     | Desktop     | [7d84e25468](https://linux-hardware.org/?probe=7d84e25468) | Dec 14, 2020 |
| NEC Comput... | PC-LL750SG6R                | Notebook    | [867c1b37b1](https://linux-hardware.org/?probe=867c1b37b1) | Dec 14, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [d988af7e73](https://linux-hardware.org/?probe=d988af7e73) | Dec 13, 2020 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [bf27b4bfee](https://linux-hardware.org/?probe=bf27b4bfee) | Dec 12, 2020 |
| NEC Comput... | MS9666 012                  | Desktop     | [9cc98a743f](https://linux-hardware.org/?probe=9cc98a743f) | Dec 11, 2020 |
| Dell          | Inspiron 5370               | Notebook    | [9cf5fbfe60](https://linux-hardware.org/?probe=9cf5fbfe60) | Dec 09, 2020 |
| Sony          | VAIO                        | All in one  | [68937cf6bb](https://linux-hardware.org/?probe=68937cf6bb) | Dec 08, 2020 |
| Dell          | 002KVM A01                  | Desktop     | [bee5c78b3b](https://linux-hardware.org/?probe=bee5c78b3b) | Dec 08, 2020 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [575c848b52](https://linux-hardware.org/?probe=575c848b52) | Dec 07, 2020 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [58cf889053](https://linux-hardware.org/?probe=58cf889053) | Dec 07, 2020 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [772f864f4e](https://linux-hardware.org/?probe=772f864f4e) | Dec 05, 2020 |
| MSI           | H270 PC MATE                | Desktop     | [35866ce8fb](https://linux-hardware.org/?probe=35866ce8fb) | Dec 02, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [1190e2392c](https://linux-hardware.org/?probe=1190e2392c) | Dec 02, 2020 |
| ASRock        | B550 Taichi                 | Desktop     | [dd9ebdf6b5](https://linux-hardware.org/?probe=dd9ebdf6b5) | Dec 02, 2020 |
| MSI           | H270 PC MATE                | Desktop     | [3151fefb19](https://linux-hardware.org/?probe=3151fefb19) | Dec 02, 2020 |
| Gateway       | G33M05G1 MP                 | Desktop     | [8ec0050494](https://linux-hardware.org/?probe=8ec0050494) | Dec 01, 2020 |
| HP            | G7000                       | Notebook    | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | Notebook    | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | Notebook    | [e8e9e6770b](https://linux-hardware.org/?probe=e8e9e6770b) | Nov 29, 2020 |
| Dell          | 0NW73C A01                  | Desktop     | [1ddf8958ef](https://linux-hardware.org/?probe=1ddf8958ef) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ca9077ede2](https://linux-hardware.org/?probe=ca9077ede2) | Nov 27, 2020 |
| ASRock        | B550 Taichi                 | Desktop     | [047af22dea](https://linux-hardware.org/?probe=047af22dea) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [9148a1a402](https://linux-hardware.org/?probe=9148a1a402) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [054642cdd4](https://linux-hardware.org/?probe=054642cdd4) | Nov 25, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [bf758d0821](https://linux-hardware.org/?probe=bf758d0821) | Nov 23, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [22ef67e9e2](https://linux-hardware.org/?probe=22ef67e9e2) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | Desktop     | [92a6a98f06](https://linux-hardware.org/?probe=92a6a98f06) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | Desktop     | [a826e1045e](https://linux-hardware.org/?probe=a826e1045e) | Nov 22, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [3a74151cb6](https://linux-hardware.org/?probe=3a74151cb6) | Nov 22, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [5fd1f62125](https://linux-hardware.org/?probe=5fd1f62125) | Nov 21, 2020 |
| Gateway       | IPISB-VR                    | Desktop     | [9a9f3b244c](https://linux-hardware.org/?probe=9a9f3b244c) | Nov 21, 2020 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [8d591fed02](https://linux-hardware.org/?probe=8d591fed02) | Nov 21, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [593013a504](https://linux-hardware.org/?probe=593013a504) | Nov 20, 2020 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [da70709a86](https://linux-hardware.org/?probe=da70709a86) | Nov 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | Notebook    | [f34c508c5a](https://linux-hardware.org/?probe=f34c508c5a) | Nov 19, 2020 |
| Gateway       | SX2370                      | Desktop     | [69a18194ba](https://linux-hardware.org/?probe=69a18194ba) | Nov 19, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [8d4468ec71](https://linux-hardware.org/?probe=8d4468ec71) | Nov 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | Notebook    | [f827ecc142](https://linux-hardware.org/?probe=f827ecc142) | Nov 16, 2020 |
| ASRock        | B460M Pro4                  | Desktop     | [ac90684a5f](https://linux-hardware.org/?probe=ac90684a5f) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | Desktop     | [300e280e8c](https://linux-hardware.org/?probe=300e280e8c) | Nov 15, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [adbf017e43](https://linux-hardware.org/?probe=adbf017e43) | Nov 13, 2020 |
| NEC Comput... | G1BJN A                     | Desktop     | [7344b2e1a1](https://linux-hardware.org/?probe=7344b2e1a1) | Nov 12, 2020 |
| Intel         | NUC10i5FNB K61361-304       | Mini pc     | [7518979765](https://linux-hardware.org/?probe=7518979765) | Nov 11, 2020 |
| Intel         | NUC10i5FNB K61361-304       | Mini pc     | [3d188297e0](https://linux-hardware.org/?probe=3d188297e0) | Nov 11, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [3d8a88a6dd](https://linux-hardware.org/?probe=3d8a88a6dd) | Nov 08, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [64fbbc3a2c](https://linux-hardware.org/?probe=64fbbc3a2c) | Nov 08, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [d746af6cfd](https://linux-hardware.org/?probe=d746af6cfd) | Nov 07, 2020 |
| ASRock        | H110 Pro BTC+               | Desktop     | [fa4cc0d2b6](https://linux-hardware.org/?probe=fa4cc0d2b6) | Nov 07, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [595b65bc4b](https://linux-hardware.org/?probe=595b65bc4b) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | Notebook    | [32a742ccd5](https://linux-hardware.org/?probe=32a742ccd5) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | Notebook    | [497c61e3d1](https://linux-hardware.org/?probe=497c61e3d1) | Nov 07, 2020 |
| Panasonic     | CF-SX1GDHYS                 | Notebook    | [e8f3a6867e](https://linux-hardware.org/?probe=e8f3a6867e) | Nov 06, 2020 |
| ECS           | H77H2-M4                    | Desktop     | [e2dc1539b4](https://linux-hardware.org/?probe=e2dc1539b4) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e14517c94a](https://linux-hardware.org/?probe=e14517c94a) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [4fa2fb6c5b](https://linux-hardware.org/?probe=4fa2fb6c5b) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [aedfc24e7e](https://linux-hardware.org/?probe=aedfc24e7e) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [6039056d5c](https://linux-hardware.org/?probe=6039056d5c) | Nov 05, 2020 |
| ASRock        | H110 Pro BTC+               | Desktop     | [38482fe4b4](https://linux-hardware.org/?probe=38482fe4b4) | Nov 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a2303d47d0](https://linux-hardware.org/?probe=a2303d47d0) | Nov 04, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| HP            | 0AECh D                     | Desktop     | [84f95d0a66](https://linux-hardware.org/?probe=84f95d0a66) | Nov 04, 2020 |
| Apple         | MacBookAir6,1               | Notebook    | [102aa409db](https://linux-hardware.org/?probe=102aa409db) | Nov 03, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | Desktop     | [7b86aebf60](https://linux-hardware.org/?probe=7b86aebf60) | Nov 03, 2020 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [c885924d12](https://linux-hardware.org/?probe=c885924d12) | Nov 02, 2020 |
| Dell          | 0F428D A00                  | Desktop     | [e70707332f](https://linux-hardware.org/?probe=e70707332f) | Nov 01, 2020 |
| Dell          | 0F428D A00                  | Desktop     | [86139a47f6](https://linux-hardware.org/?probe=86139a47f6) | Nov 01, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | Notebook    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [5621053db7](https://linux-hardware.org/?probe=5621053db7) | Nov 01, 2020 |
| HUAWEI        | MRC-WX0                     | Notebook    | [57608acdc4](https://linux-hardware.org/?probe=57608acdc4) | Oct 31, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [207aee1b3f](https://linux-hardware.org/?probe=207aee1b3f) | Oct 31, 2020 |
| Intel         | S1200BTL E98681-352         | Server      | [57162ca72c](https://linux-hardware.org/?probe=57162ca72c) | Oct 30, 2020 |
| ASRock        | 939A785GMH/128M             | Desktop     | [e5b7c1b0d3](https://linux-hardware.org/?probe=e5b7c1b0d3) | Oct 30, 2020 |
| Dell          | Vostro 2520                 | Notebook    | [196d3c6a8d](https://linux-hardware.org/?probe=196d3c6a8d) | Oct 30, 2020 |
| HP            | ENVY 15                     | Notebook    | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | Notebook    | [d4b681e245](https://linux-hardware.org/?probe=d4b681e245) | Oct 28, 2020 |
| Shuttle       | FS61                        | Desktop     | [c8b13a3e56](https://linux-hardware.org/?probe=c8b13a3e56) | Oct 25, 2020 |
| Shuttle       | FS61                        | Desktop     | [0e89874393](https://linux-hardware.org/?probe=0e89874393) | Oct 25, 2020 |
| Dell          | Vostro 2520                 | Notebook    | [b660b39908](https://linux-hardware.org/?probe=b660b39908) | Oct 25, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [2b7dc5564c](https://linux-hardware.org/?probe=2b7dc5564c) | Oct 24, 2020 |
| HP            | ProBook 4525s               | Notebook    | [157a86205d](https://linux-hardware.org/?probe=157a86205d) | Oct 24, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [c6e251789a](https://linux-hardware.org/?probe=c6e251789a) | Oct 24, 2020 |
| Unknown       | Unknown                     | Notebook    | [046bfed81f](https://linux-hardware.org/?probe=046bfed81f) | Oct 23, 2020 |
| Sony          | VPCEB49FJ                   | Notebook    | [a7b30aea08](https://linux-hardware.org/?probe=a7b30aea08) | Oct 21, 2020 |
| EPSON DIRE... | Endeavor NJ7000E            | Notebook    | [fd0992fec0](https://linux-hardware.org/?probe=fd0992fec0) | Oct 21, 2020 |
| ASUSTek       | PN50                        | Mini pc     | [004e2befa6](https://linux-hardware.org/?probe=004e2befa6) | Oct 20, 2020 |
| MouseCompu... | NG-N-i5730                  | Notebook    | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [01f02e3868](https://linux-hardware.org/?probe=01f02e3868) | Oct 19, 2020 |
| ASRock        | B460M Pro4                  | Desktop     | [40a43c769a](https://linux-hardware.org/?probe=40a43c769a) | Oct 18, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [af9ba22806](https://linux-hardware.org/?probe=af9ba22806) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [70b6395f2f](https://linux-hardware.org/?probe=70b6395f2f) | Oct 17, 2020 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [d7c4496b69](https://linux-hardware.org/?probe=d7c4496b69) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ba5634435e](https://linux-hardware.org/?probe=ba5634435e) | Oct 17, 2020 |
| HP            | ProBook 4525s               | Notebook    | [67efc6e80a](https://linux-hardware.org/?probe=67efc6e80a) | Oct 16, 2020 |
| UNITCOM       | W35_37ET                    | Notebook    | [13ddafa560](https://linux-hardware.org/?probe=13ddafa560) | Oct 16, 2020 |
| Supermicro    | C7B75                       | Desktop     | [34cb26f10c](https://linux-hardware.org/?probe=34cb26f10c) | Oct 14, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7925c419a6](https://linux-hardware.org/?probe=7925c419a6) | Oct 13, 2020 |
| Pegatron      | IPM41G                      | Desktop     | [fa3b72447f](https://linux-hardware.org/?probe=fa3b72447f) | Oct 12, 2020 |
| Pegatron      | IPM41G                      | Desktop     | [4d26fb41ea](https://linux-hardware.org/?probe=4d26fb41ea) | Oct 12, 2020 |
| NEC Comput... | PC-LL750F26C                | Notebook    | [7b9dc13b94](https://linux-hardware.org/?probe=7b9dc13b94) | Oct 10, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [467a3d55ed](https://linux-hardware.org/?probe=467a3d55ed) | Oct 09, 2020 |
| NEC Comput... | PC-LL750F26C                | Notebook    | [eb148db6e7](https://linux-hardware.org/?probe=eb148db6e7) | Oct 09, 2020 |
| ECS           | G43T-3L                     | Desktop     | [7cf090fb8f](https://linux-hardware.org/?probe=7cf090fb8f) | Oct 08, 2020 |
| ECS           | G43T-3L                     | Desktop     | [3533b87774](https://linux-hardware.org/?probe=3533b87774) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | Desktop     | [26497a27c8](https://linux-hardware.org/?probe=26497a27c8) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | Desktop     | [969cdedc18](https://linux-hardware.org/?probe=969cdedc18) | Oct 08, 2020 |
| Sony          | VPCS129FJ                   | Notebook    | [ababc3caff](https://linux-hardware.org/?probe=ababc3caff) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | Notebook    | [e4b06fc3af](https://linux-hardware.org/?probe=e4b06fc3af) | Oct 07, 2020 |
| HP            | ENVY 15                     | Notebook    | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Fujitsu       | FMVWW11W                    | Notebook    | [e1a03b47aa](https://linux-hardware.org/?probe=e1a03b47aa) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [ebe29c2e8c](https://linux-hardware.org/?probe=ebe29c2e8c) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [4c90a49a16](https://linux-hardware.org/?probe=4c90a49a16) | Oct 05, 2020 |
| HP            | ProBook 6560b               | Notebook    | [4f60a7aca9](https://linux-hardware.org/?probe=4f60a7aca9) | Oct 05, 2020 |
| Supermicro    | X11SPL-F                    | Server      | [4d0ed95e02](https://linux-hardware.org/?probe=4d0ed95e02) | Oct 05, 2020 |
| Unknown       | Unknown                     | Desktop     | [89eee20d80](https://linux-hardware.org/?probe=89eee20d80) | Oct 05, 2020 |
| ECS           | G43T-3L                     | Desktop     | [b97fcd2011](https://linux-hardware.org/?probe=b97fcd2011) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [117567ed8a](https://linux-hardware.org/?probe=117567ed8a) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [c1729c7402](https://linux-hardware.org/?probe=c1729c7402) | Oct 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [51fb8f3cad](https://linux-hardware.org/?probe=51fb8f3cad) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| MSI           | H270 PC MATE                | Desktop     | [3c5eb42494](https://linux-hardware.org/?probe=3c5eb42494) | Sep 30, 2020 |
| Lenovo        | M4450 20302                 | Notebook    | [0614174763](https://linux-hardware.org/?probe=0614174763) | Sep 29, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [121f0b68c0](https://linux-hardware.org/?probe=121f0b68c0) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [84913584dc](https://linux-hardware.org/?probe=84913584dc) | Sep 27, 2020 |
| ASUSTek       | P8H77-V                     | Desktop     | [954984a1e5](https://linux-hardware.org/?probe=954984a1e5) | Sep 23, 2020 |
| Sharp         | PC-WE/WT Series             | Notebook    | [91e9663e3a](https://linux-hardware.org/?probe=91e9663e3a) | Sep 22, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [21822dbd0d](https://linux-hardware.org/?probe=21822dbd0d) | Sep 19, 2020 |
| HP            | ProBook 6550b               | Notebook    | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [692295c2b0](https://linux-hardware.org/?probe=692295c2b0) | Sep 19, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | Notebook    | [087fa4f531](https://linux-hardware.org/?probe=087fa4f531) | Sep 17, 2020 |
| HP            | ProBook 6570b               | Notebook    | [db08cfd499](https://linux-hardware.org/?probe=db08cfd499) | Sep 17, 2020 |
| Supermicro    | X11DPH-T                    | Server      | [a484f1a6e6](https://linux-hardware.org/?probe=a484f1a6e6) | Sep 16, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [988b8ec0f7](https://linux-hardware.org/?probe=988b8ec0f7) | Sep 14, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| Foxconn       | A7DA-S/A7DA                 | Desktop     | [7974b8af2f](https://linux-hardware.org/?probe=7974b8af2f) | Sep 11, 2020 |
| HP            | 0AECh D                     | Desktop     | [acc13196ef](https://linux-hardware.org/?probe=acc13196ef) | Sep 11, 2020 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [ea5edd6a1b](https://linux-hardware.org/?probe=ea5edd6a1b) | Sep 11, 2020 |
| Sony          | VGN-NW50JB                  | Notebook    | [f5115778c1](https://linux-hardware.org/?probe=f5115778c1) | Sep 11, 2020 |
| ASRock        | X79 Extreme4                | Desktop     | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ECS           | G31T-M                      | Desktop     | [5b10fa37b2](https://linux-hardware.org/?probe=5b10fa37b2) | Sep 09, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [37e43e92e5](https://linux-hardware.org/?probe=37e43e92e5) | Sep 07, 2020 |
| HP            | ENVY Notebook               | Notebook    | [4da75a6d49](https://linux-hardware.org/?probe=4da75a6d49) | Sep 07, 2020 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [d9a2738dd0](https://linux-hardware.org/?probe=d9a2738dd0) | Sep 07, 2020 |
| ASRock        | Z170 Extreme4               | Desktop     | [688b4a3ae6](https://linux-hardware.org/?probe=688b4a3ae6) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | Desktop     | [b9e6801288](https://linux-hardware.org/?probe=b9e6801288) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | Desktop     | [176ca21f28](https://linux-hardware.org/?probe=176ca21f28) | Sep 06, 2020 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [415e105225](https://linux-hardware.org/?probe=415e105225) | Sep 06, 2020 |
| Toshiba       | dynabook T554/56KW          | Notebook    | [03f3e6b816](https://linux-hardware.org/?probe=03f3e6b816) | Sep 04, 2020 |
| Samsung       | 940X3G/930X3G               | Notebook    | [d63abb12ee](https://linux-hardware.org/?probe=d63abb12ee) | Sep 03, 2020 |
| Toshiba       | dynabook SS MX/25AE         | Notebook    | [8d195475bf](https://linux-hardware.org/?probe=8d195475bf) | Sep 02, 2020 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [b782fe1564](https://linux-hardware.org/?probe=b782fe1564) | Aug 31, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [7451d691b9](https://linux-hardware.org/?probe=7451d691b9) | Aug 31, 2020 |
| Dell          | 0NW73C A01                  | Desktop     | [6d64ca0ffc](https://linux-hardware.org/?probe=6d64ca0ffc) | Aug 29, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a2c94f7fdd](https://linux-hardware.org/?probe=a2c94f7fdd) | Aug 29, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Japan/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 209       | 20.71%  |
| Ubuntu 18.04       | 111       | 11%     |
| OpenMandriva 4.3   | 52        | 5.15%   |
| OpenMandriva 4.2   | 35        | 3.47%   |
| Ubuntu 22.04       | 34        | 3.37%   |
| Debian 11          | 28        | 2.78%   |
| Xubuntu 20.04      | 25        | 2.48%   |
| Arch               | 21        | 2.08%   |
| BlackPanther 18.1  | 18        | 1.78%   |
| Xubuntu 18.04      | 17        | 1.68%   |
| Ubuntu 21.04       | 17        | 1.68%   |
| Ubuntu 20.10       | 17        | 1.68%   |
| OpenMandriva 4.90  | 16        | 1.59%   |
| Arch Rolling       | 16        | 1.59%   |
| Ubuntu 19.04       | 14        | 1.39%   |
| Zorin 16           | 13        | 1.29%   |
| Ubuntu 21.10       | 13        | 1.29%   |
| Linux Mint 19.3    | 12        | 1.19%   |
| Zorin 15           | 10        | 0.99%   |
| Pop!_OS 22.04      | 10        | 0.99%   |
| OpenMandriva 4.50  | 10        | 0.99%   |
| Manjaro            | 10        | 0.99%   |
| Fedora 36          | 10        | 0.99%   |
| Ubuntu 19.10       | 9         | 0.89%   |
| KDE neon 20.04     | 9         | 0.89%   |
| Fedora 34          | 9         | 0.89%   |
| Fedora 32          | 9         | 0.89%   |
| Pop!_OS 21.04      | 8         | 0.79%   |
| Pop!_OS 20.10      | 8         | 0.79%   |
| Linux Mint 20.3    | 8         | 0.79%   |
| ArcoLinux Rolling  | 8         | 0.79%   |
| Ubuntu 16.04       | 7         | 0.69%   |
| Gentoo 2.7         | 7         | 0.69%   |
| Fedora 35          | 7         | 0.69%   |
| Fedora 33          | 7         | 0.69%   |
| Pop!_OS 21.10      | 6         | 0.59%   |
| Pop!_OS 20.04      | 6         | 0.59%   |
| Linux Mint 20.2    | 6         | 0.59%   |
| Linux Mint 20      | 6         | 0.59%   |
| Ubuntu Unity 16.04 | 5         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 423       | 43.83%  |
| OpenMandriva  | 111       | 11.5%   |
| Fedora        | 45        | 4.66%   |
| Xubuntu       | 41        | 4.25%   |
| Debian        | 40        | 4.15%   |
| Linux Mint    | 39        | 4.04%   |
| Arch          | 37        | 3.83%   |
| Pop!_OS       | 35        | 3.63%   |
| Zorin         | 24        | 2.49%   |
| Manjaro       | 20        | 2.07%   |
| BlackPanther  | 18        | 1.87%   |
| ROSA          | 11        | 1.14%   |
| Gentoo        | 10        | 1.04%   |
| Ubuntu Unity  | 9         | 0.93%   |
| Kubuntu       | 9         | 0.93%   |
| KDE neon      | 9         | 0.93%   |
| ArcoLinux     | 8         | 0.83%   |
| Lubuntu       | 7         | 0.73%   |
| openSUSE      | 6         | 0.62%   |
| Kali          | 6         | 0.62%   |
| Ubuntu Budgie | 5         | 0.52%   |
| Slackware     | 5         | 0.52%   |
| Elementary    | 5         | 0.52%   |
| Ubuntu MATE   | 4         | 0.41%   |
| Endless       | 4         | 0.41%   |
| CentOS        | 4         | 0.41%   |
| Peppermint    | 3         | 0.31%   |
| Guix          | 3         | 0.31%   |
| Deepin        | 3         | 0.31%   |
| antiX         | 3         | 0.31%   |
| RHEL          | 2         | 0.21%   |
| Raspbian      | 2         | 0.21%   |
| LMDE          | 2         | 0.21%   |
| Clear Linux   | 2         | 0.21%   |
| SystemRescue  | 1         | 0.1%    |
| SteamOS       | 1         | 0.1%    |
| Sparky        | 1         | 0.1%    |
| Solus         | 1         | 0.1%    |
| Rocky Linux   | 1         | 0.1%    |
| Plamo         | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 50        | 4.47%   |
| 5.10.14-desktop-1omv4002 | 33        | 2.95%   |
| 5.4.0-42-generic         | 24        | 2.15%   |
| 5.4.0-52-generic         | 18        | 1.61%   |
| 5.4.0-58-generic         | 17        | 1.52%   |
| 4.18.16-desktop-1bP      | 15        | 1.34%   |
| 5.4.0-40-generic         | 13        | 1.16%   |
| 5.4.0-33-generic         | 12        | 1.07%   |
| 5.4.0-48-generic         | 10        | 0.89%   |
| 5.4.0-37-generic         | 10        | 0.89%   |
| 5.8.0-48-generic         | 9         | 0.81%   |
| 5.8.0-43-generic         | 8         | 0.72%   |
| 5.4.0-54-generic         | 8         | 0.72%   |
| 5.4.0-31-generic         | 8         | 0.72%   |
| 5.11.0-38-generic        | 8         | 0.72%   |
| 5.8.0-50-generic         | 7         | 0.63%   |
| 5.4.0-29-generic         | 7         | 0.63%   |
| 5.13.0-40-generic        | 7         | 0.63%   |
| 5.13.0-30-generic        | 7         | 0.63%   |
| 5.12.4-desktop-1omv4050  | 7         | 0.63%   |
| 5.11.0-37-generic        | 7         | 0.63%   |
| 5.11.0-27-generic        | 7         | 0.63%   |
| 5.0.0-37-generic         | 7         | 0.63%   |
| 5.0.0-29-generic         | 7         | 0.63%   |
| 5.8.0-59-generic         | 6         | 0.54%   |
| 5.4.0-51-generic         | 6         | 0.54%   |
| 5.4.0-47-generic         | 6         | 0.54%   |
| 5.4.0-39-generic         | 6         | 0.54%   |
| 5.3.0-40-generic         | 6         | 0.54%   |
| 5.3.0-28-generic         | 6         | 0.54%   |
| 5.15.0-52-generic        | 6         | 0.54%   |
| 5.15.0-46-generic        | 6         | 0.54%   |
| 5.13.0-39-generic        | 6         | 0.54%   |
| 5.13.0-27-generic        | 6         | 0.54%   |
| 5.11.0-41-generic        | 6         | 0.54%   |
| 5.11.0-25-generic        | 6         | 0.54%   |
| 5.0.0-25-generic         | 6         | 0.54%   |
| 5.8.0-7642-generic       | 5         | 0.45%   |
| 5.8.0-41-generic         | 5         | 0.45%   |
| 5.4.0-72-generic         | 5         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 219       | 20.82%  |
| 4.15.0  | 88        | 8.37%   |
| 5.8.0   | 72        | 6.84%   |
| 5.11.0  | 61        | 5.8%    |
| 5.13.0  | 55        | 5.23%   |
| 5.16.7  | 51        | 4.85%   |
| 5.15.0  | 47        | 4.47%   |
| 5.3.0   | 41        | 3.9%    |
| 5.0.0   | 36        | 3.42%   |
| 5.10.14 | 34        | 3.23%   |
| 5.10.0  | 28        | 2.66%   |
| 4.18.16 | 15        | 1.43%   |
| 4.18.0  | 14        | 1.33%   |
| 5.19.0  | 11        | 1.05%   |
| 5.12.4  | 8         | 0.76%   |
| 4.4.0   | 8         | 0.76%   |
| 4.19.0  | 7         | 0.67%   |
| 5.19.1  | 6         | 0.57%   |
| 6.0.8   | 5         | 0.48%   |
| 5.18.12 | 5         | 0.48%   |
| 5.14.0  | 5         | 0.48%   |
| 6.0.2   | 4         | 0.38%   |
| 5.9.0   | 4         | 0.38%   |
| 5.6.14  | 4         | 0.38%   |
| 5.3.18  | 4         | 0.38%   |
| 5.19.11 | 4         | 0.38%   |
| 5.18.0  | 4         | 0.38%   |
| 5.16.11 | 4         | 0.38%   |
| 4.9.60  | 4         | 0.38%   |
| 6.0.6   | 3         | 0.29%   |
| 5.8.13  | 3         | 0.29%   |
| 5.19.8  | 3         | 0.29%   |
| 5.19.5  | 3         | 0.29%   |
| 5.18.5  | 3         | 0.29%   |
| 5.18.13 | 3         | 0.29%   |
| 5.17.5  | 3         | 0.29%   |
| 5.16.19 | 3         | 0.29%   |
| 5.16.13 | 3         | 0.29%   |
| 5.13.19 | 3         | 0.29%   |
| 5.9.16  | 2         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 227       | 21.79%  |
| 4.15    | 88        | 8.45%   |
| 5.8     | 83        | 7.97%   |
| 5.10    | 82        | 7.87%   |
| 5.16    | 70        | 6.72%   |
| 5.13    | 70        | 6.72%   |
| 5.15    | 67        | 6.43%   |
| 5.11    | 66        | 6.33%   |
| 5.3     | 46        | 4.41%   |
| 5.0     | 39        | 3.74%   |
| 5.19    | 33        | 3.17%   |
| 4.18    | 29        | 2.78%   |
| 5.18    | 21        | 2.02%   |
| 5.14    | 16        | 1.54%   |
| 5.12    | 16        | 1.54%   |
| 6.0     | 13        | 1.25%   |
| 5.9     | 12        | 1.15%   |
| 5.6     | 12        | 1.15%   |
| 5.17    | 11        | 1.06%   |
| 4.19    | 10        | 0.96%   |
| 4.9     | 8         | 0.77%   |
| 4.4     | 8         | 0.77%   |
| 5.7     | 6         | 0.58%   |
| 5.5     | 4         | 0.38%   |
| 5.2     | 3         | 0.29%   |
| 3.10    | 2         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 893       | 94.6%   |
| i686    | 37        | 3.92%   |
| aarch64 | 12        | 1.27%   |
| armv7l  | 2         | 0.21%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 444       | 46.01%  |
| KDE5                     | 175       | 18.13%  |
| Unknown                  | 127       | 13.16%  |
| XFCE                     | 77        | 7.98%   |
| X-Cinnamon               | 32        | 3.32%   |
| MATE                     | 15        | 1.55%   |
| KDE                      | 15        | 1.55%   |
| LXDE                     | 10        | 1.04%   |
| Unity                    | 9         | 0.93%   |
| Budgie                   | 9         | 0.93%   |
| LXQt                     | 8         | 0.83%   |
| sway                     | 7         | 0.73%   |
| Cinnamon                 | 6         | 0.62%   |
| Pantheon                 | 5         | 0.52%   |
| KDE4                     | 5         | 0.52%   |
| Deepin                   | 5         | 0.52%   |
| awesome                  | 3         | 0.31%   |
| XSession                 | 2         | 0.21%   |
| Openbox                  | 2         | 0.21%   |
| icewm                    | 2         | 0.21%   |
| i3                       | 2         | 0.21%   |
| xmonad                   | 1         | 0.1%    |
| qtile                    | 1         | 0.1%    |
| GNOME Flashback          | 1         | 0.1%    |
| GNOME Classic            | 1         | 0.1%    |
| /usr/bin/openbox-session | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 749       | 77.78%  |
| Wayland | 116       | 12.05%  |
| Unknown | 78        | 8.1%    |
| Tty     | 20        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 513       | 52.78%  |
| SDDM    | 173       | 17.8%   |
| GDM     | 98        | 10.08%  |
| GDM3    | 89        | 9.16%   |
| LightDM | 56        | 5.76%   |
| TDM     | 23        | 2.37%   |
| XDM     | 5         | 0.51%   |
| KDM     | 4         | 0.41%   |
| GREETD  | 4         | 0.41%   |
| LXDM    | 3         | 0.31%   |
| NODM    | 2         | 0.21%   |
| SLiM    | 1         | 0.1%    |
| EMPTTY  | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ja_JP       | 444       | 46.11%  |
| en_US       | 286       | 29.7%   |
| Unknown     | 134       | 13.91%  |
| pt_BR       | 25        | 2.6%    |
| zh_CN       | 17        | 1.77%   |
| en_GB       | 17        | 1.77%   |
| C           | 9         | 0.93%   |
| fr_FR       | 4         | 0.42%   |
| en_AU       | 3         | 0.31%   |
| zh_TW       | 2         | 0.21%   |
| sk_SK       | 2         | 0.21%   |
| ru_RU       | 2         | 0.21%   |
| es_ES       | 2         | 0.21%   |
| sv_SE       | 1         | 0.1%    |
| sr_RS       | 1         | 0.1%    |
| pl_PL       | 1         | 0.1%    |
| nb_NO       | 1         | 0.1%    |
| ja_JP.utf-8 | 1         | 0.1%    |
| it_IT       | 1         | 0.1%    |
| fr_CA       | 1         | 0.1%    |
| fi_FI       | 1         | 0.1%    |
| es_GT       | 1         | 0.1%    |
| en_SG       | 1         | 0.1%    |
| en_PH       | 1         | 0.1%    |
| en_NL       | 1         | 0.1%    |
| en_IN       | 1         | 0.1%    |
| en_AG       | 1         | 0.1%    |
| de_DE       | 1         | 0.1%    |
| af_ZA       | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 524       | 54.75%  |
| EFI  | 433       | 45.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 751       | 78.8%   |
| Overlay | 95        | 9.97%   |
| Btrfs   | 58        | 6.09%   |
| Unknown | 22        | 2.31%   |
| Xfs     | 14        | 1.47%   |
| Zfs     | 7         | 0.73%   |
| Jfs     | 2         | 0.21%   |
| F2fs    | 2         | 0.21%   |
| Ntfs    | 1         | 0.1%    |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 561       | 58.62%  |
| GPT     | 306       | 31.97%  |
| MBR     | 90        | 9.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 758       | 78.71%  |
| Yes       | 205       | 21.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 673       | 70.25%  |
| Yes       | 285       | 29.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 138       | 14.67%  |
| Lenovo                  | 94        | 9.99%   |
| ASRock                  | 83        | 8.82%   |
| Hewlett-Packard         | 75        | 7.97%   |
| Dell                    | 75        | 7.97%   |
| Gigabyte Technology     | 57        | 6.06%   |
| Toshiba                 | 48        | 5.1%    |
| MSI                     | 43        | 4.57%   |
| Fujitsu                 | 39        | 4.14%   |
| NEC Computers           | 36        | 3.83%   |
| Apple                   | 26        | 2.76%   |
| Intel                   | 24        | 2.55%   |
| Sony                    | 17        | 1.81%   |
| MouseComputer           | 17        | 1.81%   |
| Acer                    | 17        | 1.81%   |
| Raspberry Pi Foundation | 12        | 1.28%   |
| Panasonic               | 12        | 1.28%   |
| Unknown                 | 10        | 1.06%   |
| Biostar                 | 9         | 0.96%   |
| Gateway                 | 7         | 0.74%   |
| ECS                     | 7         | 0.74%   |
| Supermicro              | 6         | 0.64%   |
| Novastar                | 4         | 0.43%   |
| MCJ                     | 4         | 0.43%   |
| HUAWEI                  | 4         | 0.43%   |
| EPSON DIRECT            | 4         | 0.43%   |
| Alienware               | 4         | 0.43%   |
| UNITCOM                 | 3         | 0.32%   |
| Teclast                 | 3         | 0.32%   |
| System76                | 3         | 0.32%   |
| Shuttle                 | 3         | 0.32%   |
| Pegatron                | 3         | 0.32%   |
| Notebook                | 3         | 0.32%   |
| Microsoft               | 3         | 0.32%   |
| Foxconn                 | 3         | 0.32%   |
| Dynabook                | 3         | 0.32%   |
| Wistron                 | 2         | 0.21%   |
| Timi                    | 2         | 0.21%   |
| Thirdwave               | 2         | 0.21%   |
| SLIMBOOK                | 2         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba dynabook T653/46JR                 | 11        | 1.17%   |
| ASUS All Series                            | 10        | 1.06%   |
| Unknown                                    | 10        | 1.06%   |
| RPi Raspberry Pi                           | 6         | 0.64%   |
| Toshiba dynabook Satellite B552/G          | 5         | 0.53%   |
| Novastar KL55                              | 4         | 0.43%   |
| HP ProDesk 600 G1 SFF                      | 4         | 0.43%   |
| ASRock Z87 Killer                          | 4         | 0.43%   |
| ASRock B450M Pro4                          | 4         | 0.43%   |
| Apple MacBookPro9,2                        | 4         | 0.43%   |
| Supermicro Super Server                    | 3         | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 3         | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 3         | 0.32%   |
| MSI MS-7A40                                | 3         | 0.32%   |
| Lenovo G570 4334                           | 3         | 0.32%   |
| Intel NUC10i7FNH                           | 3         | 0.32%   |
| Intel NUC10i5FNH                           | 3         | 0.32%   |
| ECS G31T-M                                 | 3         | 0.32%   |
| Dell Precision WorkStation T3500           | 3         | 0.32%   |
| Dell OptiPlex 3020                         | 3         | 0.32%   |
| ASUS P7H55-M                               | 3         | 0.32%   |
| ASRock Prime Series                        | 3         | 0.32%   |
| ASRock J5005-ITX                           | 3         | 0.32%   |
| ASRock B450 Pro4                           | 3         | 0.32%   |
| ASRock A300M-STX                           | 3         | 0.32%   |
| Toshiba dynabook R73/BN                    | 2         | 0.21%   |
| System76 Lemur Pro                         | 2         | 0.21%   |
| Panasonic CF-S10EYADR                      | 2         | 0.21%   |
| Onkyo ONKYOPC                              | 2         | 0.21%   |
| NEC Computers Express5800/S70 [N8100-9021] | 2         | 0.21%   |
| MSI MS-7D16                                | 2         | 0.21%   |
| MSI MS-7C94                                | 2         | 0.21%   |
| MSI MS-7C37                                | 2         | 0.21%   |
| MSI MS-7C35                                | 2         | 0.21%   |
| MSI MS-7C02                                | 2         | 0.21%   |
| MSI MS-7B79                                | 2         | 0.21%   |
| MSI MS-7A72                                | 2         | 0.21%   |
| MSI MS-7865                                | 2         | 0.21%   |
| MouseComputer B360M                        | 2         | 0.21%   |
| Lenovo ThinkPad X230 2325SSF               | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 61        | 6.48%   |
| Toshiba dynabook      | 45        | 4.78%   |
| Dell Inspiron         | 23        | 2.44%   |
| ASUS PRIME            | 19        | 2.02%   |
| ASUS TUF              | 15        | 1.59%   |
| HP ProBook            | 14        | 1.49%   |
| ASUS ROG              | 14        | 1.49%   |
| RPi Raspberry         | 12        | 1.28%   |
| Dell Latitude         | 12        | 1.28%   |
| Acer Aspire           | 12        | 1.28%   |
| Dell XPS              | 10        | 1.06%   |
| ASUS All              | 10        | 1.06%   |
| Unknown               | 10        | 1.06%   |
| HP ProDesk            | 8         | 0.85%   |
| HP Compaq             | 8         | 0.85%   |
| Dell Vostro           | 8         | 0.85%   |
| HP Pavilion           | 7         | 0.74%   |
| Dell OptiPlex         | 7         | 0.74%   |
| ASUS VivoBook         | 6         | 0.64%   |
| ASRock B450           | 6         | 0.64%   |
| Lenovo ThinkBook      | 5         | 0.53%   |
| HP ENVY               | 5         | 0.53%   |
| HP EliteBook          | 5         | 0.53%   |
| Fujitsu PRIMERGY      | 5         | 0.53%   |
| Dell Precision        | 5         | 0.53%   |
| ASUS P8Z77-V          | 5         | 0.53%   |
| ASRock Z87            | 5         | 0.53%   |
| Novastar KL55         | 4         | 0.43%   |
| Lenovo ThinkCentre    | 4         | 0.43%   |
| Lenovo IdeaPad        | 4         | 0.43%   |
| HP Laptop             | 4         | 0.43%   |
| Gigabyte Z390         | 4         | 0.43%   |
| EPSON DIRECT Endeavor | 4         | 0.43%   |
| ASRock Prime          | 4         | 0.43%   |
| ASRock B450M          | 4         | 0.43%   |
| Apple MacBookPro9     | 4         | 0.43%   |
| Supermicro Super      | 3         | 0.32%   |
| MSI MS-7A40           | 3         | 0.32%   |
| Microsoft Surface     | 3         | 0.32%   |
| Lenovo Yoga           | 3         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 101       | 10.73%  |
| 2018    | 100       | 10.63%  |
| 2020    | 85        | 9.03%   |
| 2013    | 76        | 8.08%   |
| 2019    | 70        | 7.44%   |
| 2011    | 64        | 6.8%    |
| 2021    | 59        | 6.27%   |
| 2010    | 53        | 5.63%   |
| 2009    | 53        | 5.63%   |
| 2016    | 52        | 5.53%   |
| 2015    | 41        | 4.36%   |
| 2017    | 37        | 3.93%   |
| 2008    | 37        | 3.93%   |
| 2014    | 36        | 3.83%   |
| 2007    | 33        | 3.51%   |
| 2006    | 15        | 1.59%   |
| Unknown | 12        | 1.28%   |
| 2022    | 10        | 1.06%   |
| 2005    | 6         | 0.64%   |
| 2003    | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 435       | 46.23%  |
| Desktop        | 419       | 44.53%  |
| Mini pc        | 21        | 2.23%   |
| All in one     | 18        | 1.91%   |
| System on chip | 14        | 1.49%   |
| Server         | 13        | 1.38%   |
| Convertible    | 11        | 1.17%   |
| Tablet         | 10        | 1.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 880       | 92.83%  |
| Enabled  | 68        | 7.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 936       | 99.47%  |
| Yes  | 5         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 204       | 21.32%  |
| 4.01-8.0        | 192       | 20.06%  |
| 8.01-16.0       | 172       | 17.97%  |
| 16.01-24.0      | 169       | 17.66%  |
| 32.01-64.0      | 96        | 10.03%  |
| 1.01-2.0        | 46        | 4.81%   |
| 64.01-256.0     | 33        | 3.45%   |
| 24.01-32.0      | 22        | 2.3%    |
| 2.01-3.0        | 14        | 1.46%   |
| 0.51-1.0        | 7         | 0.73%   |
| More than 256.0 | 1         | 0.1%    |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 438       | 42.12%  |
| 2.01-3.0   | 224       | 21.54%  |
| 0.51-1.0   | 110       | 10.58%  |
| 3.01-4.0   | 102       | 9.81%   |
| 4.01-8.0   | 99        | 9.52%   |
| 8.01-16.0  | 36        | 3.46%   |
| 0.01-0.5   | 18        | 1.73%   |
| 16.01-24.0 | 9         | 0.87%   |
| 24.01-32.0 | 3         | 0.29%   |
| 32.01-64.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 573       | 59.32%  |
| 2      | 249       | 25.78%  |
| 3      | 69        | 7.14%   |
| 4      | 38        | 3.93%   |
| 5      | 14        | 1.45%   |
| 0      | 10        | 1.04%   |
| 6      | 6         | 0.62%   |
| 7      | 5         | 0.52%   |
| 11     | 1         | 0.1%    |
| 9      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 483       | 51%     |
| Yes       | 464       | 49%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 835       | 88.64%  |
| No        | 107       | 11.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 619       | 65.43%  |
| No        | 327       | 34.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 500       | 52.47%  |
| Yes       | 453       | 47.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Japan   | 941       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Tokyo       | 77        | 7.72%   |
| Yokohama    | 58        | 5.81%   |
| Osaka       | 49        | 4.91%   |
| Shinjuku    | 28        | 2.81%   |
| Nagoya      | 27        | 2.71%   |
| Minato-ku   | 23        | 2.3%    |
| Saitama     | 20        | 2%      |
| Shibuya     | 16        | 1.6%    |
| Sapporo     | 16        | 1.6%    |
| Setagaya-ku | 15        | 1.5%    |
| Chiyoda     | 14        | 1.4%    |
| Honcho      | 13        | 1.3%    |
| Niigata     | 12        | 1.2%    |
| Kobe        | 12        | 1.2%    |
| Kyoto       | 11        | 1.1%    |
| Fukuoka     | 11        | 1.1%    |
| Tsukuba     | 9         | 0.9%    |
| Shinagawa   | 9         | 0.9%    |
| Adachi      | 9         | 0.9%    |
| Kagoshima   | 8         | 0.8%    |
| Okayama     | 7         | 0.7%    |
| Nagasaki    | 7         | 0.7%    |
| Morioka     | 7         | 0.7%    |
| Miyazaki    | 7         | 0.7%    |
| Mito        | 7         | 0.7%    |
| Matsudo     | 7         | 0.7%    |
| Koto        | 7         | 0.7%    |
| Kitakyushu  | 7         | 0.7%    |
| Ichikawa    | 7         | 0.7%    |
| Himeji      | 7         | 0.7%    |
| Chiba       | 7         | 0.7%    |
| Ōtsu       | 6         | 0.6%    |
| Meguro-ku   | 6         | 0.6%    |
| Gifu City   | 6         | 0.6%    |
| Bunkyo-ku   | 6         | 0.6%    |
| Utsunomiya  | 5         | 0.5%    |
| Takamatsu   | 5         | 0.5%    |
| Taito       | 5         | 0.5%    |
| Ōta-ku     | 5         | 0.5%    |
| Okazaki     | 5         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 200       | 303    | 14.62%  |
| Seagate                   | 200       | 300    | 14.62%  |
| Samsung Electronics       | 143       | 201    | 10.45%  |
| Toshiba                   | 113       | 141    | 8.26%   |
| Crucial                   | 75        | 94     | 5.48%   |
| Hitachi                   | 73        | 90     | 5.34%   |
| SanDisk                   | 66        | 87     | 4.82%   |
| Unknown                   | 63        | 79     | 4.61%   |
| Intel                     | 48        | 67     | 3.51%   |
| A-DATA Technology         | 30        | 34     | 2.19%   |
| Kingston                  | 27        | 31     | 1.97%   |
| SPCC                      | 24        | 31     | 1.75%   |
| SK hynix                  | 19        | 19     | 1.39%   |
| HGST                      | 19        | 22     | 1.39%   |
| Apple                     | 17        | 21     | 1.24%   |
| Micron Technology         | 16        | 26     | 1.17%   |
| Transcend                 | 14        | 18     | 1.02%   |
| Phison                    | 14        | 19     | 1.02%   |
| Plextor                   | 12        | 16     | 0.88%   |
| China                     | 10        | 14     | 0.73%   |
| Silicon Motion            | 9         | 16     | 0.66%   |
| Fujitsu                   | 9         | 10     | 0.66%   |
| Unknown                   | 9         | 9      | 0.66%   |
| KIOXIA                    | 8         | 11     | 0.58%   |
| OCZ                       | 7         | 7      | 0.51%   |
| Micron/Crucial Technology | 7         | 9      | 0.51%   |
| KIOXIA-EXCERIA            | 7         | 8      | 0.51%   |
| Zheino                    | 6         | 7      | 0.44%   |
| SUNEAST                   | 6         | 7      | 0.44%   |
| Green House               | 6         | 8      | 0.44%   |
| Teclast                   | 5         | 5      | 0.37%   |
| Patriot                   | 5         | 6      | 0.37%   |
| Dogfish                   | 5         | 5      | 0.37%   |
| Maxtor                    | 4         | 6      | 0.29%   |
| JMicron Technology        | 4         | 4      | 0.29%   |
| Apacer                    | 4         | 6      | 0.29%   |
| Team                      | 3         | 4      | 0.22%   |
| Netac                     | 3         | 3      | 0.22%   |
| Lexar                     | 3         | 4      | 0.22%   |
| KLEVV                     | 3         | 8      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB           | 17        | 1.13%   |
| Toshiba DT01ACA100 1TB                 | 16        | 1.07%   |
| Unknown MMC Card  64GB                 | 14        | 0.93%   |
| Unknown MMC Card  32GB                 | 11        | 0.73%   |
| Toshiba MQ01ABD075 752GB               | 11        | 0.73%   |
| Crucial CT240BX500SSD1 240GB           | 11        | 0.73%   |
| Seagate ST4000DM004-2CV104 4TB         | 9         | 0.6%    |
| Unknown                                | 9         | 0.6%    |
| WDC WD40EZRZ-00GXCB0 4TB               | 8         | 0.53%   |
| SPCC Solid State Disk 256GB            | 8         | 0.53%   |
| Seagate ST3500418AS 500GB              | 8         | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB         | 8         | 0.53%   |
| Toshiba MQ01ABD100 1TB                 | 7         | 0.47%   |
| Toshiba DT01ACA200 2TB                 | 7         | 0.47%   |
| Seagate ST9500325AS 500GB              | 7         | 0.47%   |
| Crucial CT525MX300SSD1 528GB           | 7         | 0.47%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 6         | 0.4%    |
| WDC WD20EZRX-00DC0B0 2TB               | 6         | 0.4%    |
| Unknown MMC Card  128GB                | 6         | 0.4%    |
| Seagate ST500DM002-1BD142 500GB        | 6         | 0.4%    |
| Seagate ST2000DM008-2FR102 2TB         | 6         | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB         | 6         | 0.4%    |
| Seagate ST2000DM005-2CW102 2TB         | 6         | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB         | 6         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB         | 6         | 0.4%    |
| Samsung NVMe SSD Drive 250GB           | 6         | 0.4%    |
| Intel NVMe SSD Drive 512GB             | 6         | 0.4%    |
| Crucial CT120BX500SSD1 120GB           | 6         | 0.4%    |
| Toshiba MQ01ABF050 500GB               | 5         | 0.33%   |
| SPCC Solid State Disk 240GB            | 5         | 0.33%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB         | 5         | 0.33%   |
| Seagate Expansion 1TB                  | 5         | 0.33%   |
| SanDisk NVMe SSD Drive 1TB             | 5         | 0.33%   |
| Samsung SSD 860 EVO 500GB              | 5         | 0.33%   |
| Samsung SSD 840 Series 120GB           | 5         | 0.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 5         | 0.33%   |
| Samsung NVMe SSD Drive 1TB             | 5         | 0.33%   |
| Crucial CT1000MX500SSD1 1TB            | 5         | 0.33%   |
| WDC WD20EZAZ-00GGJB0 2TB               | 4         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 195       | 292    | 33.22%  |
| WDC                 | 158       | 231    | 26.92%  |
| Toshiba             | 95        | 116    | 16.18%  |
| Hitachi             | 72        | 89     | 12.27%  |
| HGST                | 19        | 22     | 3.24%   |
| Samsung Electronics | 17        | 20     | 2.9%    |
| Fujitsu             | 9         | 10     | 1.53%   |
| Unknown             | 4         | 4      | 0.68%   |
| Maxtor              | 4         | 6      | 0.68%   |
| Apple               | 3         | 4      | 0.51%   |
| QC-FT-D             | 2         | 2      | 0.34%   |
| MARVELL             | 2         | 4      | 0.34%   |
| ASMT                | 2         | 3      | 0.34%   |
| StoreJet            | 1         | 1      | 0.17%   |
| Quantum             | 1         | 1      | 0.17%   |
| MARSHAL             | 1         | 2      | 0.17%   |
| KESU                | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 75        | 101    | 15.53%  |
| Crucial             | 73        | 91     | 15.11%  |
| SanDisk             | 42        | 53     | 8.7%    |
| WDC                 | 30        | 39     | 6.21%   |
| A-DATA Technology   | 27        | 31     | 5.59%   |
| Intel               | 26        | 31     | 5.38%   |
| SPCC                | 22        | 29     | 4.55%   |
| Kingston            | 20        | 23     | 4.14%   |
| Transcend           | 13        | 17     | 2.69%   |
| Plextor             | 12        | 16     | 2.48%   |
| Toshiba             | 11        | 12     | 2.28%   |
| China               | 10        | 14     | 2.07%   |
| Apple               | 8         | 10     | 1.66%   |
| OCZ                 | 7         | 7      | 1.45%   |
| Micron Technology   | 7         | 11     | 1.45%   |
| SUNEAST             | 6         | 7      | 1.24%   |
| Green House         | 6         | 8      | 1.24%   |
| Unknown             | 6         | 6      | 1.24%   |
| Unknown             | 5         | 5      | 1.04%   |
| Dogfish             | 5         | 5      | 1.04%   |
| Teclast             | 4         | 4      | 0.83%   |
| KIOXIA-EXCERIA      | 4         | 5      | 0.83%   |
| Apacer              | 4         | 6      | 0.83%   |
| Zheino              | 3         | 3      | 0.62%   |
| Team                | 3         | 4      | 0.62%   |
| Seagate             | 3         | 5      | 0.62%   |
| Patriot             | 3         | 4      | 0.62%   |
| Lexar               | 3         | 4      | 0.62%   |
| KLEVV               | 3         | 8      | 0.62%   |
| TCSUNBOW            | 2         | 2      | 0.41%   |
| PNY                 | 2         | 2      | 0.41%   |
| Palit               | 2         | 3      | 0.41%   |
| Netac               | 2         | 2      | 0.41%   |
| LITEONIT            | 2         | 3      | 0.41%   |
| Kingmax             | 2         | 2      | 0.41%   |
| BUFFALO             | 2         | 2      | 0.41%   |
| Biostar             | 2         | 2      | 0.41%   |
| AEGO                | 2         | 2      | 0.41%   |
| XSTAR               | 1         | 1      | 0.21%   |
| SK hynix            | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 497       | 809    | 40.84%  |
| SSD     | 426       | 606    | 35%     |
| NVMe    | 222       | 333    | 18.24%  |
| MMC     | 48        | 62     | 3.94%   |
| Unknown | 24        | 33     | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 758       | 1385   | 70.51%  |
| NVMe | 221       | 328    | 20.56%  |
| SAS  | 48        | 68     | 4.47%   |
| MMC  | 48        | 62     | 4.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 576       | 863    | 59.81%  |
| 0.51-1.0   | 215       | 284    | 22.33%  |
| 1.01-2.0   | 89        | 128    | 9.24%   |
| 3.01-4.0   | 35        | 55     | 3.63%   |
| 4.01-10.0  | 24        | 47     | 2.49%   |
| 2.01-3.0   | 19        | 30     | 1.97%   |
| 10.01-20.0 | 5         | 8      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 303       | 30.67%  |
| 251-500        | 169       | 17.11%  |
| 501-1000       | 128       | 12.96%  |
| 51-100         | 76        | 7.69%   |
| 1-20           | 70        | 7.09%   |
| 1001-2000      | 63        | 6.38%   |
| More than 3000 | 53        | 5.36%   |
| 21-50          | 44        | 4.45%   |
| Unknown        | 44        | 4.45%   |
| 2001-3000      | 38        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 455       | 44.09%  |
| 21-50          | 187       | 18.12%  |
| 101-250        | 95        | 9.21%   |
| 51-100         | 82        | 7.95%   |
| 251-500        | 63        | 6.1%    |
| 501-1000       | 48        | 4.65%   |
| Unknown        | 44        | 4.26%   |
| 1001-2000      | 28        | 2.71%   |
| More than 3000 | 20        | 1.94%   |
| 2001-3000      | 10        | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB           | 11        | 11     | 15.28%  |
| Seagate ST9500325AS 500GB          | 5         | 5      | 6.94%   |
| WDC WD10EADS-22M2B0 1TB            | 4         | 4      | 5.56%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 4         | 4      | 5.56%   |
| Seagate ST9160314AS 160GB          | 2         | 2      | 2.78%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1         | 1      | 1.39%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1         | 2      | 1.39%   |
| WDC WD25EZRX-00MMMB0 2TB           | 1         | 1      | 1.39%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 1      | 1.39%   |
| Transcend TS240GSSD220S 240GB      | 1         | 1      | 1.39%   |
| Toshiba MK5055GSX 500GB            | 1         | 1      | 1.39%   |
| Toshiba MK1255GSX H 120GB          | 1         | 1      | 1.39%   |
| SPCC Solid State DiskB28 128GB     | 1         | 1      | 1.39%   |
| SPCC Solid State Disk 512GB        | 1         | 2      | 1.39%   |
| Seagate ST9320320AS 320GB          | 1         | 1      | 1.39%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 1.39%   |
| Seagate ST3500418AS 500GB          | 1         | 1      | 1.39%   |
| Seagate ST3250310AS 250GB          | 1         | 2      | 1.39%   |
| Seagate ST3120026A 120GB           | 1         | 1      | 1.39%   |
| Seagate ST31000528AS 1TB           | 1         | 1      | 1.39%   |
| Seagate ST31000333AS 1TB           | 1         | 1      | 1.39%   |
| Seagate ST3000VM002-1ET166 3TB     | 1         | 1      | 1.39%   |
| Seagate ST2000DX002-2DV164 2TB     | 1         | 1      | 1.39%   |
| Seagate ST2000DX001-1NS164 2TB     | 1         | 1      | 1.39%   |
| Seagate ST2000DM001-1CH164 2TB     | 1         | 1      | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 1.39%   |
| SanDisk SSD PLUS 1000GB            | 1         | 2      | 1.39%   |
| SanDisk SSD P4 32GB                | 1         | 1      | 1.39%   |
| Samsung Electronics HM641JI 640GB  | 1         | 2      | 1.39%   |
| MARSHAL MAL2020SA 80 20GB          | 1         | 1      | 1.39%   |
| LITEON CV8-8E128-HP 128GB SSD      | 1         | 2      | 1.39%   |
| Intel SSDSCKKF180H6H 180GB         | 1         | 1      | 1.39%   |
| Hitachi HTS727575A9E364 752GB      | 1         | 1      | 1.39%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 1.39%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 1.39%   |
| Hitachi HTS545025B9SA02 250GB      | 1         | 1      | 1.39%   |
| Hitachi HDT725032VLA360 320GB      | 1         | 1      | 1.39%   |
| Hitachi HDT721032SLA360 320GB      | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 28.57%  |
| Toshiba             | 13        | 13     | 18.57%  |
| WDC                 | 8         | 9      | 11.43%  |
| Hitachi             | 8         | 9      | 11.43%  |
| SanDisk             | 6         | 7      | 8.57%   |
| SPCC                | 2         | 3      | 2.86%   |
| HGST                | 2         | 2      | 2.86%   |
| Crucial             | 2         | 3      | 2.86%   |
| A-DATA Technology   | 2         | 2      | 2.86%   |
| Transcend           | 1         | 1      | 1.43%   |
| Samsung Electronics | 1         | 2      | 1.43%   |
| MARSHAL             | 1         | 1      | 1.43%   |
| LITEON              | 1         | 2      | 1.43%   |
| Intel               | 1         | 1      | 1.43%   |
| Corsair             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 37.74%  |
| Toshiba             | 13        | 13     | 24.53%  |
| WDC                 | 8         | 9      | 15.09%  |
| Hitachi             | 8         | 9      | 15.09%  |
| HGST                | 2         | 2      | 3.77%   |
| Samsung Electronics | 1         | 2      | 1.89%   |
| MARSHAL             | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 58     | 75%     |
| SSD  | 17        | 21     | 25%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 606       | 1212   | 61.21%  |
| Works    | 321       | 552    | 32.42%  |
| Malfunc  | 63        | 79     | 6.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 663       | 56.62%  |
| AMD                              | 174       | 14.86%  |
| Samsung Electronics              | 67        | 5.72%   |
| SanDisk                          | 40        | 3.42%   |
| ASMedia Technology               | 36        | 3.07%   |
| Marvell Technology Group         | 20        | 1.71%   |
| SK hynix                         | 19        | 1.62%   |
| Phison Electronics               | 18        | 1.54%   |
| JMicron Technology               | 16        | 1.37%   |
| Silicon Motion                   | 15        | 1.28%   |
| Nvidia                           | 11        | 0.94%   |
| KIOXIA                           | 11        | 0.94%   |
| VIA Technologies                 | 9         | 0.77%   |
| Micron/Crucial Technology        | 9         | 0.77%   |
| Micron Technology                | 9         | 0.77%   |
| Toshiba America Info Systems     | 8         | 0.68%   |
| Kingston Technology Company      | 7         | 0.6%    |
| Broadcom / LSI                   | 6         | 0.51%   |
| Apple                            | 6         | 0.51%   |
| ADATA Technology                 | 6         | 0.51%   |
| Seagate Technology               | 3         | 0.26%   |
| Adaptec                          | 3         | 0.26%   |
| Silicon Image                    | 2         | 0.17%   |
| Realtek Semiconductor            | 2         | 0.17%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.17%   |
| LSI Logic / Symbios Logic        | 2         | 0.17%   |
| HighPoint Technologies           | 2         | 0.17%   |
| Yangtze Memory Technologies      | 1         | 0.09%   |
| ULi Electronics                  | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| Promise Technology               | 1         | 0.09%   |
| Unknown                          | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 110       | 7.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 68        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 39        | 2.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 36        | 2.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 33        | 2.37%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 31        | 2.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 31        | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 29        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 1.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 22        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 22        | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 21        | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 19        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 19        | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 1.22%   |
| AMD 500 Series Chipset SATA Controller                                         | 17        | 1.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 16        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 15        | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 1.08%   |
| Intel SATA Controller [RAID mode]                                              | 14        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 13        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 12        | 0.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 12        | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 12        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 11        | 0.79%   |
| SanDisk Non-Volatile memory controller                                         | 11        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                             | 10        | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 0.72%   |
| Intel SSD 660P Series                                                          | 10        | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 10        | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 10        | 0.72%   |
| Micron Non-Volatile memory controller                                          | 9         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 702       | 60.05%  |
| NVMe | 224       | 19.16%  |
| IDE  | 174       | 14.88%  |
| RAID | 59        | 5.05%   |
| SAS  | 6         | 0.51%   |
| SCSI | 4         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 731       | 77.68%  |
| AMD    | 196       | 20.83%  |
| ARM    | 14        | 1.49%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz       | 11        | 1.17%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 11        | 1.17%   |
| ARM Processor                           | 11        | 1.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 10        | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor       | 10        | 1.06%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 9         | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 9         | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 8         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 8         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 0.74%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 7         | 0.74%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 7         | 0.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 7         | 0.74%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 7         | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 0.64%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 6         | 0.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 6         | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 5         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 5         | 0.53%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 5         | 0.53%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 5         | 0.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 5         | 0.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 5         | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 5         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 5         | 0.53%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 5         | 0.53%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 5         | 0.53%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz    | 5         | 0.53%   |
| Intel Core 2 CPU 6600 @ 2.40GHz         | 5         | 0.53%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 5         | 0.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 0.53%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 5         | 0.53%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 5         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 0.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 205       | 21.76%  |
| Intel Core i7           | 170       | 18.05%  |
| Intel Celeron           | 67        | 7.11%   |
| Intel Core i3           | 62        | 6.58%   |
| Intel Core 2 Duo        | 57        | 6.05%   |
| AMD Ryzen 5             | 45        | 4.78%   |
| Other                   | 43        | 4.56%   |
| AMD Ryzen 7             | 40        | 4.25%   |
| Intel Xeon              | 29        | 3.08%   |
| Intel Atom              | 21        | 2.23%   |
| Intel Core 2            | 16        | 1.7%    |
| Intel Pentium           | 13        | 1.38%   |
| Intel Core i9           | 11        | 1.17%   |
| AMD Athlon              | 11        | 1.17%   |
| Intel Core 2 Quad       | 10        | 1.06%   |
| AMD Ryzen 9             | 9         | 0.96%   |
| AMD Ryzen 3             | 9         | 0.96%   |
| AMD A10                 | 7         | 0.74%   |
| Intel Pentium Dual-Core | 6         | 0.64%   |
| AMD Phenom II X4        | 6         | 0.64%   |
| AMD FX                  | 6         | 0.64%   |
| AMD Athlon 64 X2        | 6         | 0.64%   |
| Intel Pentium 4         | 5         | 0.53%   |
| Intel Celeron M         | 5         | 0.53%   |
| AMD A8                  | 5         | 0.53%   |
| AMD A6                  | 5         | 0.53%   |
| Intel Pentium Gold      | 4         | 0.42%   |
| Intel Pentium Silver    | 3         | 0.32%   |
| Intel Celeron Dual-Core | 3         | 0.32%   |
| AMD Sempron             | 3         | 0.32%   |
| AMD Ryzen 7 PRO         | 3         | 0.32%   |
| AMD Ryzen 5 PRO         | 3         | 0.32%   |
| AMD E2                  | 3         | 0.32%   |
| Intel Pentium M         | 2         | 0.21%   |
| Intel Genuine           | 2         | 0.21%   |
| Intel Core m3           | 2         | 0.21%   |
| Intel Core M            | 2         | 0.21%   |
| ARM BCM                 | 2         | 0.21%   |
| AMD Turion 64 X2 Mobile | 2         | 0.21%   |
| AMD Ryzen Threadripper  | 2         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 421       | 44.69%  |
| 4      | 285       | 30.25%  |
| 6      | 101       | 10.72%  |
| 8      | 66        | 7.01%   |
| 1      | 32        | 3.4%    |
| 16     | 13        | 1.38%   |
| 12     | 6         | 0.64%   |
| 10     | 6         | 0.64%   |
| 14     | 4         | 0.42%   |
| 3      | 4         | 0.42%   |
| 56     | 1         | 0.11%   |
| 32     | 1         | 0.11%   |
| 24     | 1         | 0.11%   |
| 20     | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 931       | 98.94%  |
| 2      | 9         | 0.96%   |
| 3      | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 600       | 63.69%  |
| 1      | 342       | 36.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 902       | 95.65%  |
| Unknown        | 24        | 2.55%   |
| 32-bit         | 17        | 1.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 187       | 19.26%  |
| 0x306a9    | 81        | 8.34%   |
| 0x206a7    | 73        | 7.52%   |
| 0x1067a    | 51        | 5.25%   |
| 0x306c3    | 40        | 4.12%   |
| 0x906ea    | 25        | 2.57%   |
| 0x806ec    | 22        | 2.27%   |
| 0x20655    | 20        | 2.06%   |
| 0x08701021 | 20        | 2.06%   |
| 0x306d4    | 19        | 1.96%   |
| 0x506e3    | 18        | 1.85%   |
| 0x906e9    | 14        | 1.44%   |
| 0x10676    | 14        | 1.44%   |
| 0x806e9    | 13        | 1.34%   |
| 0x40651    | 13        | 1.34%   |
| 0x406c4    | 12        | 1.24%   |
| 0x806ea    | 11        | 1.13%   |
| 0x406e3    | 11        | 1.13%   |
| 0x806c1    | 10        | 1.03%   |
| 0x6f6      | 10        | 1.03%   |
| 0x20652    | 10        | 1.03%   |
| 0x0a50000c | 10        | 1.03%   |
| 0xa0652    | 9         | 0.93%   |
| 0x906ed    | 9         | 0.93%   |
| 0x08108102 | 8         | 0.82%   |
| 0x406c3    | 7         | 0.72%   |
| 0x106e5    | 7         | 0.72%   |
| 0x106c2    | 7         | 0.72%   |
| 0x08600106 | 7         | 0.72%   |
| 0x08108109 | 7         | 0.72%   |
| 0x0810100b | 7         | 0.72%   |
| 0x0800820d | 7         | 0.72%   |
| 0xa0655    | 6         | 0.62%   |
| 0x806eb    | 6         | 0.62%   |
| 0x06003106 | 6         | 0.62%   |
| 0x06001119 | 6         | 0.62%   |
| 0x010000db | 6         | 0.62%   |
| 0x706a1    | 5         | 0.51%   |
| 0x6fb      | 5         | 0.51%   |
| 0x506c9    | 5         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 131       | 13.91%  |
| IvyBridge        | 95        | 10.08%  |
| SandyBridge      | 90        | 9.55%   |
| Penryn           | 73        | 7.75%   |
| Haswell          | 71        | 7.54%   |
| Zen 2            | 47        | 4.99%   |
| Skylake          | 43        | 4.56%   |
| Westmere         | 36        | 3.82%   |
| CometLake        | 30        | 3.18%   |
| Zen+             | 29        | 3.08%   |
| Unknown          | 28        | 2.97%   |
| Core             | 27        | 2.87%   |
| Silvermont       | 25        | 2.65%   |
| Zen              | 22        | 2.34%   |
| Broadwell        | 22        | 2.34%   |
| Zen 3            | 21        | 2.23%   |
| K10              | 16        | 1.7%    |
| K8 Hammer        | 15        | 1.59%   |
| TigerLake        | 13        | 1.38%   |
| Nehalem          | 12        | 1.27%   |
| Goldmont plus    | 11        | 1.17%   |
| Bonnell          | 11        | 1.17%   |
| Piledriver       | 10        | 1.06%   |
| P6               | 8         | 0.85%   |
| NetBurst         | 7         | 0.74%   |
| Alderlake Hybrid | 7         | 0.74%   |
| Steamroller      | 6         | 0.64%   |
| Jaguar           | 6         | 0.64%   |
| IceLake          | 6         | 0.64%   |
| Goldmont         | 5         | 0.53%   |
| K10 Llano        | 4         | 0.42%   |
| Bulldozer        | 4         | 0.42%   |
| Puma             | 3         | 0.32%   |
| Excavator        | 3         | 0.32%   |
| Bobcat           | 3         | 0.32%   |
| K8 & K10 hybrid  | 2         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 541       | 53.04%  |
| Nvidia                     | 249       | 24.41%  |
| AMD                        | 222       | 21.76%  |
| Matrox Electronics Systems | 4         | 0.39%   |
| ASPEED Technology          | 3         | 0.29%   |
| VIA Technologies           | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 72        | 6.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 53        | 4.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 2.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 20        | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 1.6%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.41%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.41%   |
| AMD Renoir                                                                               | 15        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 1.22%   |
| Intel UHD Graphics 620                                                                   | 13        | 1.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 1.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 1.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 11        | 1.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 1.03%   |
| Intel HD Graphics 620                                                                    | 11        | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 1.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 10        | 0.94%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 10        | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 0.94%   |
| Intel HD Graphics 530                                                                    | 9         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.75%   |
| Intel HD Graphics 630                                                                    | 8         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.75%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 7         | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 6         | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 464       | 49.05%  |
| 1 x AMD                  | 191       | 20.19%  |
| 1 x Nvidia               | 179       | 18.92%  |
| Intel + Nvidia           | 49        | 5.18%   |
| Other                    | 16        | 1.69%   |
| Intel + AMD              | 11        | 1.16%   |
| AMD + Nvidia             | 9         | 0.95%   |
| 2 x AMD                  | 8         | 0.85%   |
| 2 x Nvidia               | 6         | 0.63%   |
| 1 x Matrox               | 3         | 0.32%   |
| Nvidia + ASPEED          | 2         | 0.21%   |
| Intel + 2 x Nvidia       | 2         | 0.21%   |
| 2 x Intel                | 1         | 0.11%   |
| 1 x VIA                  | 1         | 0.11%   |
| Intel + 2 x AMD          | 1         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.11%   |
| 1 x ASPEED               | 1         | 0.11%   |
| AMD + Matrox             | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 777       | 81.7%   |
| Proprietary | 132       | 13.88%  |
| Unknown     | 42        | 4.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 542       | 56.17%  |
| 0.01-0.5   | 120       | 12.44%  |
| 1.01-2.0   | 106       | 10.98%  |
| 0.51-1.0   | 75        | 7.77%   |
| 3.01-4.0   | 51        | 5.28%   |
| 7.01-8.0   | 32        | 3.32%   |
| 5.01-6.0   | 20        | 2.07%   |
| 8.01-16.0  | 12        | 1.24%   |
| 16.01-24.0 | 5         | 0.52%   |
| 24.01-32.0 | 1         | 0.1%    |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 92        | 9.71%   |
| AU Optronics            | 75        | 7.92%   |
| Dell                    | 59        | 6.23%   |
| Samsung Electronics     | 55        | 5.81%   |
| Goldstar                | 55        | 5.81%   |
| Chimei Innolux          | 45        | 4.75%   |
| IOD                     | 44        | 4.65%   |
| Sharp                   | 41        | 4.33%   |
| BOE                     | 33        | 3.48%   |
| BenQ                    | 33        | 3.48%   |
| Mitsubishi              | 31        | 3.27%   |
| Iiyama                  | 29        | 3.06%   |
| Acer                    | 27        | 2.85%   |
| Hewlett-Packard         | 24        | 2.53%   |
| Philips                 | 22        | 2.32%   |
| Eizo                    | 22        | 2.32%   |
| Lenovo                  | 21        | 2.22%   |
| Apple                   | 21        | 2.22%   |
| Ancor Communications    | 17        | 1.8%    |
| Unknown                 | 16        | 1.69%   |
| Chi Mei Optoelectronics | 16        | 1.69%   |
| AOC                     | 14        | 1.48%   |
| Sony                    | 12        | 1.27%   |
| Panasonic               | 10        | 1.06%   |
| NEC Computers           | 10        | 1.06%   |
| Toshiba                 | 9         | 0.95%   |
| PANDA                   | 8         | 0.84%   |
| ASUSTek Computer        | 8         | 0.84%   |
| Idek Iiyama             | 7         | 0.74%   |
| LG Electronics          | 6         | 0.63%   |
| ViewSonic               | 5         | 0.53%   |
| NOV                     | 4         | 0.42%   |
| LG Philips              | 4         | 0.42%   |
| Hitachi                 | 4         | 0.42%   |
| CSO                     | 4         | 0.42%   |
| Unknown (XXX)           | 3         | 0.32%   |
| InfoVision              | 3         | 0.32%   |
| Fujitsu                 | 3         | 0.32%   |
| CPT                     | 3         | 0.32%   |
| ___                     | 2         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 11        | 1.11%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 6         | 0.61%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                      | 5         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.51%   |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                         | 5         | 0.51%   |
| NOV NOVA HD CARD NOV0405 1920x1080 459x296mm 21.5-inch                   | 4         | 0.4%    |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch              | 4         | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.4%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.4%    |
| LG Display LCD Monitor LGD02CB 1366x768 344x194mm 15.5-inch              | 4         | 0.4%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 4         | 0.4%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.4%    |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                        | 4         | 0.4%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch               | 3         | 0.3%    |
| Toshiba TV TSB020A 1920x1080                                             | 3         | 0.3%    |
| Sharp HDMI SHP0FDB 1360x768 820x460mm 37.0-inch                          | 3         | 0.3%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 3         | 0.3%    |
| Mitsubishi RDT1714VM MEL4764 1280x1024 338x270mm 17.0-inch               | 3         | 0.3%    |
| Mitsubishi MDT241WG MEL478E 1920x1200 520x320mm 24.0-inch                | 3         | 0.3%    |
| Iiyama PL3291 IVM7605 1920x1080 698x393mm 31.5-inch                      | 3         | 0.3%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 3         | 0.3%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 3         | 0.3%    |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch                | 3         | 0.3%    |
| Dell U3219Q DELA120 3840x2160 697x392mm 31.5-inch                        | 3         | 0.3%    |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.3%    |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch         | 3         | 0.3%    |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                          | 3         | 0.3%    |
| ___ LCD TV ___9000 1360x768                                              | 2         | 0.2%    |
| YTH YTH156KC YTH1560 3840x2160 600x330mm 27.0-inch                       | 2         | 0.2%    |
| ViewSonic VX3211-2K VSCF634 2560x1440 700x390mm 31.5-inch                | 2         | 0.2%    |
| Unknown LCD Monitor Mitsubishi RDT233WLM 1920x1080                       | 2         | 0.2%    |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch    | 2         | 0.2%    |
| SKY TV-monitor SKY1901 3840x2160 1210x680mm 54.6-inch                    | 2         | 0.2%    |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                  | 2         | 0.2%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.2%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 386       | 41.51%  |
| 1366x768 (WXGA)    | 154       | 16.56%  |
| 3840x2160 (4K)     | 73        | 7.85%   |
| 1280x1024 (SXGA)   | 50        | 5.38%   |
| 2560x1440 (QHD)    | 42        | 4.52%   |
| 1920x1200 (WUXGA)  | 33        | 3.55%   |
| 1280x800 (WXGA)    | 25        | 2.69%   |
| 1680x1050 (WSXGA+) | 18        | 1.94%   |
| 1440x900 (WXGA+)   | 18        | 1.94%   |
| 1600x900 (HD+)     | 15        | 1.61%   |
| Unknown            | 14        | 1.51%   |
| 1920x540           | 11        | 1.18%   |
| 1360x768           | 9         | 0.97%   |
| 1600x1200          | 8         | 0.86%   |
| 2560x1080          | 7         | 0.75%   |
| 1024x768 (XGA)     | 7         | 0.75%   |
| 2560x1600          | 6         | 0.65%   |
| 2880x1800          | 5         | 0.54%   |
| 3440x1440          | 4         | 0.43%   |
| 1400x1050          | 4         | 0.43%   |
| 3840x2400          | 3         | 0.32%   |
| 3840x1080          | 3         | 0.32%   |
| 3200x1800 (QHD+)   | 3         | 0.32%   |
| 2160x1440          | 3         | 0.32%   |
| 1024x600           | 3         | 0.32%   |
| 3200x1200          | 2         | 0.22%   |
| 3072x1920          | 2         | 0.22%   |
| 1360x765           | 2         | 0.22%   |
| 1280x960           | 2         | 0.22%   |
| 800x480            | 1         | 0.11%   |
| 7680x2160          | 1         | 0.11%   |
| 640x480            | 1         | 0.11%   |
| 5760x1200          | 1         | 0.11%   |
| 4480x1080          | 1         | 0.11%   |
| 3520x1080          | 1         | 0.11%   |
| 3200x2160          | 1         | 0.11%   |
| 3200x1080          | 1         | 0.11%   |
| 3000x2000          | 1         | 0.11%   |
| 2880x1920          | 1         | 0.11%   |
| 2560x1024          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 178       | 18.9%   |
| 13      | 95        | 10.08%  |
| 23      | 77        | 8.17%   |
| 27      | 76        | 8.07%   |
| 24      | 75        | 7.96%   |
| 21      | 75        | 7.96%   |
| Unknown | 70        | 7.43%   |
| 17      | 44        | 4.67%   |
| 14      | 42        | 4.46%   |
| 19      | 34        | 3.61%   |
| 12      | 30        | 3.18%   |
| 31      | 27        | 2.87%   |
| 20      | 16        | 1.7%    |
| 11      | 14        | 1.49%   |
| 72      | 10        | 1.06%   |
| 22      | 10        | 1.06%   |
| 34      | 9         | 0.96%   |
| 18      | 9         | 0.96%   |
| 37      | 8         | 0.85%   |
| 10      | 7         | 0.74%   |
| 84      | 4         | 0.42%   |
| 54      | 4         | 0.42%   |
| 42      | 3         | 0.32%   |
| 40      | 3         | 0.32%   |
| 32      | 3         | 0.32%   |
| 16      | 3         | 0.32%   |
| 43      | 2         | 0.21%   |
| 30      | 2         | 0.21%   |
| 25      | 2         | 0.21%   |
| 74      | 1         | 0.11%   |
| 64      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 35      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 259       | 27.82%  |
| 501-600     | 218       | 23.42%  |
| 201-300     | 125       | 13.43%  |
| 401-500     | 117       | 12.57%  |
| Unknown     | 70        | 7.52%   |
| 351-400     | 53        | 5.69%   |
| 601-700     | 35        | 3.76%   |
| 1501-2000   | 15        | 1.61%   |
| 801-900     | 14        | 1.5%    |
| 701-800     | 11        | 1.18%   |
| 1001-1500   | 9         | 0.97%   |
| 901-1000    | 5         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 616       | 70.32%  |
| 16/10   | 113       | 12.9%   |
| Unknown | 58        | 6.62%   |
| 5/4     | 45        | 5.14%   |
| 4/3     | 17        | 1.94%   |
| 21/9    | 11        | 1.26%   |
| 3/2     | 8         | 0.91%   |
| 32/9    | 5         | 0.57%   |
| 6/5     | 1         | 0.11%   |
| 1.96    | 1         | 0.11%   |
| 1.00    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 178       | 18.92%  |
| 201-250        | 172       | 18.28%  |
| 151-200        | 84        | 8.93%   |
| 301-350        | 76        | 8.08%   |
| 81-90          | 71        | 7.55%   |
| Unknown        | 70        | 7.44%   |
| 71-80          | 63        | 6.7%    |
| 351-500        | 42        | 4.46%   |
| 251-300        | 38        | 4.04%   |
| 61-70          | 30        | 3.19%   |
| 141-150        | 30        | 3.19%   |
| More than 1000 | 22        | 2.34%   |
| 501-1000       | 18        | 1.91%   |
| 121-130        | 16        | 1.7%    |
| 51-60          | 14        | 1.49%   |
| 41-50          | 7         | 0.74%   |
| 131-140        | 4         | 0.43%   |
| 111-120        | 3         | 0.32%   |
| 91-100         | 3         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 347       | 37.84%  |
| 101-120       | 213       | 23.23%  |
| 121-160       | 163       | 17.78%  |
| 161-240       | 82        | 8.94%   |
| Unknown       | 70        | 7.63%   |
| More than 240 | 21        | 2.29%   |
| 1-50          | 21        | 2.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 793       | 83.21%  |
| 2     | 109       | 11.44%  |
| 0     | 41        | 4.3%    |
| 3     | 7         | 0.73%   |
| 4     | 2         | 0.21%   |
| 6     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 467       | 34.44%  |
| Realtek Semiconductor            | 440       | 32.45%  |
| Qualcomm Atheros                 | 161       | 11.87%  |
| Broadcom                         | 97        | 7.15%   |
| Marvell Technology Group         | 28        | 2.06%   |
| BUFFALO                          | 21        | 1.55%   |
| Broadcom Limited                 | 16        | 1.18%   |
| TP-Link                          | 15        | 1.11%   |
| ASIX Electronics                 | 14        | 1.03%   |
| PLANEX                           | 13        | 0.96%   |
| Nvidia                           | 9         | 0.66%   |
| MediaTek                         | 7         | 0.52%   |
| Huawei Technologies              | 7         | 0.52%   |
| Ralink                           | 6         | 0.44%   |
| Elecom                           | 6         | 0.44%   |
| Aquantia                         | 6         | 0.44%   |
| Ralink Technology                | 4         | 0.29%   |
| VIA Technologies                 | 3         | 0.22%   |
| Lenovo                           | 3         | 0.22%   |
| Apple                            | 3         | 0.22%   |
| Samsung Electronics              | 2         | 0.15%   |
| Qualcomm Atheros Communications  | 2         | 0.15%   |
| Prolific Technology              | 2         | 0.15%   |
| NEC Computers                    | 2         | 0.15%   |
| Logitec                          | 2         | 0.15%   |
| JMicron Technology               | 2         | 0.15%   |
| D-Link                           | 2         | 0.15%   |
| Xiaomi                           | 1         | 0.07%   |
| Wilocity                         | 1         | 0.07%   |
| ULi Electronics                  | 1         | 0.07%   |
| U-Blox                           | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Sierra Wireless                  | 1         | 0.07%   |
| Padix (Rockfire)                 | 1         | 0.07%   |
| NetGear                          | 1         | 0.07%   |
| Netchip Technology               | 1         | 0.07%   |
| LSI                              | 1         | 0.07%   |
| Google                           | 1         | 0.07%   |
| Edimax Technology                | 1         | 0.07%   |
| DisplayLink                      | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 307       | 19.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 38        | 2.37%   |
| Intel Wi-Fi 6 AX200                                                     | 36        | 2.25%   |
| Intel 82579V Gigabit Network Connection                                 | 30        | 1.87%   |
| Intel Ethernet Connection (2) I219-V                                    | 27        | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 26        | 1.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 1.62%   |
| Intel I211 Gigabit Network Connection                                   | 24        | 1.5%    |
| Intel Wireless 7265                                                     | 20        | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 19        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                    | 19        | 1.19%   |
| Intel Wireless 8265 / 8275                                              | 17        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 1%      |
| Intel Wireless 7260                                                     | 16        | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.87%   |
| Intel Wireless 3165                                                     | 14        | 0.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 13        | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 13        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.75%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                   | 12        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                           | 12        | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.62%   |
| Intel Wireless 8260                                                     | 10        | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 10        | 0.62%   |
| Intel Ethernet Connection I217-V                                        | 10        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.62%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 10        | 0.62%   |
| TP-Link 802.11ac WLAN Adapter                                           | 9         | 0.56%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 9         | 0.56%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.56%   |
| Intel Wireless 3160                                                     | 9         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 291       | 44.43%  |
| Qualcomm Atheros                | 119       | 18.17%  |
| Realtek Semiconductor           | 94        | 14.35%  |
| Broadcom                        | 53        | 8.09%   |
| BUFFALO                         | 21        | 3.21%   |
| TP-Link                         | 15        | 2.29%   |
| PLANEX                          | 13        | 1.98%   |
| Broadcom Limited                | 13        | 1.98%   |
| MediaTek                        | 7         | 1.07%   |
| Ralink                          | 6         | 0.92%   |
| Elecom                          | 5         | 0.76%   |
| Ralink Technology               | 4         | 0.61%   |
| Qualcomm Atheros Communications | 2         | 0.31%   |
| Marvell Technology Group        | 2         | 0.31%   |
| Logitec                         | 2         | 0.31%   |
| D-Link                          | 2         | 0.31%   |
| Wilocity                        | 1         | 0.15%   |
| Sierra Wireless                 | 1         | 0.15%   |
| NetGear                         | 1         | 0.15%   |
| NEC Computers                   | 1         | 0.15%   |
| Edimax Technology               | 1         | 0.15%   |
| Dell                            | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 36        | 5.46%   |
| Intel Wireless 7265                                                     | 20        | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 2.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 2.43%   |
| Intel Wireless 7260                                                     | 16        | 2.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 2.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 2.12%   |
| Intel Wireless 3165                                                     | 14        | 2.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 13        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 1.82%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.52%   |
| Intel Wireless 8260                                                     | 10        | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 10        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.52%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 10        | 1.52%   |
| TP-Link 802.11ac WLAN Adapter                                           | 9         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 1.37%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 9         | 1.37%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.37%   |
| Intel Wireless 3160                                                     | 9         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.06%   |
| Intel WiFi Link 5100                                                    | 7         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.91%   |
| BUFFALO 802.11ac WLAN Adapter                                           | 6         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 6         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 391       | 43.4%   |
| Intel                            | 306       | 33.96%  |
| Qualcomm Atheros                 | 62        | 6.88%   |
| Broadcom                         | 56        | 6.22%   |
| Marvell Technology Group         | 26        | 2.89%   |
| ASIX Electronics                 | 14        | 1.55%   |
| Nvidia                           | 9         | 1%      |
| Huawei Technologies              | 7         | 0.78%   |
| Aquantia                         | 6         | 0.67%   |
| VIA Technologies                 | 3         | 0.33%   |
| Lenovo                           | 3         | 0.33%   |
| Broadcom Limited                 | 3         | 0.33%   |
| Apple                            | 3         | 0.33%   |
| Samsung Electronics              | 2         | 0.22%   |
| JMicron Technology               | 2         | 0.22%   |
| Xiaomi                           | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| Netchip Technology               | 1         | 0.11%   |
| Google                           | 1         | 0.11%   |
| Elecom                           | 1         | 0.11%   |
| DisplayLink                      | 1         | 0.11%   |
| Corega K.K.                      | 1         | 0.11%   |
| ADMtek                           | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 307       | 33.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 38        | 4.09%   |
| Intel 82579V Gigabit Network Connection                                        | 30        | 3.23%   |
| Intel Ethernet Connection (2) I219-V                                           | 27        | 2.9%    |
| Realtek RTL8125 2.5GbE Controller                                              | 26        | 2.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 26        | 2.8%    |
| Intel I211 Gigabit Network Connection                                          | 24        | 2.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 19        | 2.04%   |
| Intel Ethernet Connection (7) I219-V                                           | 19        | 2.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 13        | 1.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 12        | 1.29%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12        | 1.29%   |
| Intel Ethernet Connection I217-V                                               | 10        | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8         | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 8         | 0.86%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 0.86%   |
| Intel 82574L Gigabit Network Connection                                        | 8         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 0.75%   |
| Intel WiMAX Connection 2400m                                                   | 7         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 0.75%   |
| Huawei E353/E3131                                                              | 7         | 0.75%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 7         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 0.65%   |
| Intel Ethernet Connection (2) I218-V                                           | 6         | 0.65%   |
| Intel 82577LC Gigabit Network Connection                                       | 6         | 0.65%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 6         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.65%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 6         | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.54%   |
| Intel I210 Gigabit Network Connection                                          | 5         | 0.54%   |
| Intel Ethernet Controller I225-V                                               | 5         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.43%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.43%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 835       | 56.88%  |
| WiFi     | 621       | 42.3%   |
| Modem    | 9         | 0.61%   |
| Unknown  | 3         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 532       | 54.62%  |
| WiFi     | 442       | 45.38%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 467       | 49.58%  |
| 1     | 426       | 45.22%  |
| 3     | 23        | 2.44%   |
| 0     | 23        | 2.44%   |
| 4     | 3         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 755       | 78.16%  |
| Yes  | 211       | 21.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 216       | 46.96%  |
| Cambridge Silicon Radio         | 70        | 15.22%  |
| Realtek Semiconductor           | 29        | 6.3%    |
| Broadcom                        | 27        | 5.87%   |
| Qualcomm Atheros Communications | 25        | 5.43%   |
| Apple                           | 20        | 4.35%   |
| IMC Networks                    | 18        | 3.91%   |
| Foxconn / Hon Hai               | 9         | 1.96%   |
| Alps Electric                   | 8         | 1.74%   |
| ASUSTek Computer                | 7         | 1.52%   |
| Fujitsu                         | 6         | 1.3%    |
| Lite-On Technology              | 4         | 0.87%   |
| TP-Link                         | 3         | 0.65%   |
| Realtek                         | 3         | 0.65%   |
| Marvell Semiconductor           | 3         | 0.65%   |
| Toshiba                         | 2         | 0.43%   |
| Ralink                          | 2         | 0.43%   |
| Ralink Technology               | 1         | 0.22%   |
| Opticis                         | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Hewlett-Packard                 | 1         | 0.22%   |
| Dell                            | 1         | 0.22%   |
| Creative Technology             | 1         | 0.22%   |
| BUFFALO                         | 1         | 0.22%   |
| Askey Computer                  | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 83        | 18.04%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 70        | 15.22%  |
| Intel AX201 Bluetooth                                                               | 39        | 8.48%   |
| Intel AX200 Bluetooth                                                               | 34        | 7.39%   |
| Realtek Bluetooth Radio                                                             | 21        | 4.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 4.57%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 12        | 2.61%   |
| Intel AX210 Bluetooth                                                               | 10        | 2.17%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 1.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.96%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 1.96%   |
| Apple Bluetooth Host Controller                                                     | 9         | 1.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 8         | 1.74%   |
| IMC Networks Bluetooth Device                                                       | 8         | 1.74%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 1.09%   |
| Fujitsu Bluetooth Device                                                            | 5         | 1.09%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 5         | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 0.87%   |
| Intel Bluetooth Device                                                              | 4         | 0.87%   |
| TP-Link UB500 Adapter                                                               | 3         | 0.65%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.65%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 3         | 0.65%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 2         | 0.43%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.43%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 0.43%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.43%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.43%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.43%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 688       | 53.67%  |
| AMD                                             | 252       | 19.66%  |
| Nvidia                                          | 201       | 15.68%  |
| C-Media Electronics                             | 23        | 1.79%   |
| Creative Technology                             | 16        | 1.25%   |
| Texas Instruments                               | 14        | 1.09%   |
| VIA Technologies                                | 9         | 0.7%    |
| Harman                                          | 9         | 0.7%    |
| JMTek                                           | 6         | 0.47%   |
| Creative Labs                                   | 6         | 0.47%   |
| Yamaha                                          | 5         | 0.39%   |
| Apple                                           | 5         | 0.39%   |
| Elitegroup Computer Systems (ECS)               | 4         | 0.31%   |
| TOWA Electronics                                | 3         | 0.23%   |
| Sony                                            | 3         | 0.23%   |
| Realtek Semiconductor                           | 3         | 0.23%   |
| Lenovo                                          | 3         | 0.23%   |
| GN Netcom                                       | 3         | 0.23%   |
| Generalplus Technology                          | 3         | 0.23%   |
| Roland                                          | 2         | 0.16%   |
| Onkyo                                           | 2         | 0.16%   |
| ASUSTek Computer                                | 2         | 0.16%   |
| XMOS                                            | 1         | 0.08%   |
| ULi Electronics                                 | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.08%   |
| SteelSeries ApS                                 | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.08%   |
| Sennheiser Communications                       | 1         | 0.08%   |
| RME                                             | 1         | 0.08%   |
| RATOC System                                    | 1         | 0.08%   |
| Rasteme                                         | 1         | 0.08%   |
| Philips (or NXP)                                | 1         | 0.08%   |
| Medeli Electronics                              | 1         | 0.08%   |
| M2Tech                                          | 1         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.08%   |
| JAVS                                            | 1         | 0.08%   |
| iCreate Technologies                            | 1         | 0.08%   |
| Focusrite-Novation                              | 1         | 0.08%   |
| Corsair                                         | 1         | 0.08%   |
| CMX Systems                                     | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 102       | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 68        | 4.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 65        | 4.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 45        | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 41        | 2.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 39        | 2.62%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 38        | 2.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 36        | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 35        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 2.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33        | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 31        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 29        | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 27        | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 24        | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 23        | 1.54%   |
| Intel 200 Series PCH HD Audio                                                                     | 23        | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 21        | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 20        | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 19        | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 19        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 18        | 1.21%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17        | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 16        | 1.07%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 14        | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 11        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 10        | 0.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 0.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 10        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 94        | 19.92%  |
| SK hynix            | 65        | 13.77%  |
| Unknown             | 55        | 11.65%  |
| Micron Technology   | 48        | 10.17%  |
| Crucial             | 36        | 7.63%   |
| Kingston            | 35        | 7.42%   |
| A-DATA Technology   | 17        | 3.6%    |
| Corsair             | 14        | 2.97%   |
| Team                | 12        | 2.54%   |
| Nanya Technology    | 12        | 2.54%   |
| G.Skill             | 10        | 2.12%   |
| Silicon Power       | 8         | 1.69%   |
| Elpida              | 8         | 1.69%   |
| Unknown (ABCD)      | 7         | 1.48%   |
| Transcend           | 6         | 1.27%   |
| SanMax              | 6         | 1.27%   |
| Panram              | 5         | 1.06%   |
| KLEVV               | 5         | 1.06%   |
| Unknown             | 5         | 1.06%   |
| Ramaxel Technology  | 4         | 0.85%   |
| CFD                 | 2         | 0.42%   |
| ASint Technology    | 2         | 0.42%   |
| V-Color             | 1         | 0.21%   |
| Unknown (8AD3)      | 1         | 0.21%   |
| Unknown (0x09EE)    | 1         | 0.21%   |
| UMAX                | 1         | 0.21%   |
| Toshiba             | 1         | 0.21%   |
| Ramos Technology    | 1         | 0.21%   |
| Patriot             | 1         | 0.21%   |
| Neo Forza           | 1         | 0.21%   |
| Kingmax             | 1         | 0.21%   |
| Goldkey             | 1         | 0.21%   |
| GeIL                | 1         | 0.21%   |
| EUDAR               | 1         | 0.21%   |
| Essencore Limited   | 1         | 0.21%   |
| Essencore           | 1         | 0.21%   |
| ChangXin Memory     | 1         | 0.21%   |
| Century Micro       | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 12        | 2.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.01%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.01%   |
| Unknown                                                          | 5         | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 4         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.81%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.81%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 4         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 3         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.61%   |
| Nanya RAM M2X4G64CB8HG9N-DG 4GB DIMM DDR3 1600MT/s               | 3         | 0.61%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s               | 3         | 0.61%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 3         | 0.61%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s            | 3         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 0.4%    |
| Unknown RAM Module 1GB DIMM 800MT/s                              | 2         | 0.4%    |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s               | 2         | 0.4%    |
| Team RAM TEAMGROUP-UD3-1600 2GB DIMM DDR3 1600MT/s               | 2         | 0.4%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.4%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.4%    |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s           | 2         | 0.4%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.4%    |
| Silicon Power RAM DCLT8GN128S 8192MB DIMM DDR3 1600MT/s          | 2         | 0.4%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.4%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 194       | 45.75%  |
| DDR3    | 146       | 34.43%  |
| DDR2    | 22        | 5.19%   |
| LPDDR3  | 19        | 4.48%   |
| LPDDR4  | 16        | 3.77%   |
| SDRAM   | 14        | 3.3%    |
| Unknown | 9         | 2.12%   |
| DDR5    | 2         | 0.47%   |
| DDR     | 2         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 228       | 54.03%  |
| DIMM         | 159       | 37.68%  |
| Row Of Chips | 27        | 6.4%    |
| Unknown      | 5         | 1.18%   |
| Chip         | 2         | 0.47%   |
| RIMM         | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 143       | 32.35%  |
| 4096  | 133       | 30.09%  |
| 16384 | 73        | 16.52%  |
| 2048  | 57        | 12.9%   |
| 1024  | 18        | 4.07%   |
| 32768 | 16        | 3.62%   |
| 65536 | 1         | 0.23%   |
| 256   | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 102       | 23.02%  |
| 3200    | 70        | 15.8%   |
| 2667    | 62        | 14%     |
| 2400    | 37        | 8.35%   |
| 2133    | 22        | 4.97%   |
| 1333    | 17        | 3.84%   |
| 1334    | 15        | 3.39%   |
| 1067    | 12        | 2.71%   |
| Unknown | 12        | 2.71%   |
| 2666    | 10        | 2.26%   |
| 3600    | 8         | 1.81%   |
| 800     | 8         | 1.81%   |
| 667     | 7         | 1.58%   |
| 1867    | 6         | 1.35%   |
| 4267    | 5         | 1.13%   |
| 4199    | 5         | 1.13%   |
| 1066    | 5         | 1.13%   |
| 3400    | 4         | 0.9%    |
| 1866    | 4         | 0.9%    |
| 3800    | 3         | 0.68%   |
| 3266    | 3         | 0.68%   |
| 2933    | 3         | 0.68%   |
| 1800    | 3         | 0.68%   |
| 533     | 3         | 0.68%   |
| 4800    | 2         | 0.45%   |
| 3733    | 2         | 0.45%   |
| 975     | 2         | 0.45%   |
| 400     | 2         | 0.45%   |
| 4266    | 1         | 0.23%   |
| 4133    | 1         | 0.23%   |
| 3100    | 1         | 0.23%   |
| 3007    | 1         | 0.23%   |
| 3000    | 1         | 0.23%   |
| 2733    | 1         | 0.23%   |
| 333     | 1         | 0.23%   |
| 266     | 1         | 0.23%   |
| 100     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 4         | 33.33%  |
| Seiko Epson         | 3         | 25%     |
| Brother Industries  | 3         | 25%     |
| Samsung Electronics | 1         | 8.33%   |
| Hewlett-Packard     | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson WF-2010 Series    | 1         | 8.33%   |
| Seiko Epson PX-045A Series    | 1         | 8.33%   |
| Seiko Epson EP-306 Series     | 1         | 8.33%   |
| Samsung SCX-3200 Series       | 1         | 8.33%   |
| HP ENVY 5000 series           | 1         | 8.33%   |
| Canon PIXMA MG3600 Series     | 1         | 8.33%   |
| Canon PIXMA iX6850 Printer    | 1         | 8.33%   |
| Canon PIXMA iP4600 Printer    | 1         | 8.33%   |
| Canon iP2700 series           | 1         | 8.33%   |
| Brother HL-L2360D series      | 1         | 8.33%   |
| Brother HL-2130 series        | 1         | 8.33%   |
| Brother HL-1440 Laser Printer | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 78        | 21.67%  |
| Microdia                               | 30        | 8.33%   |
| Acer                                   | 30        | 8.33%   |
| IMC Networks                           | 29        | 8.06%   |
| Sunplus Innovation Technology          | 28        | 7.78%   |
| Realtek Semiconductor                  | 19        | 5.28%   |
| Apple                                  | 18        | 5%      |
| Logitech                               | 15        | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.61%   |
| Quanta                                 | 11        | 3.06%   |
| Suyin                                  | 8         | 2.22%   |
| Ricoh                                  | 8         | 2.22%   |
| Alcor Micro                            | 7         | 1.94%   |
| Syntek                                 | 6         | 1.67%   |
| Microsoft                              | 5         | 1.39%   |
| Silicon Motion                         | 4         | 1.11%   |
| Lite-On Technology                     | 4         | 1.11%   |
| Samsung Electronics                    | 3         | 0.83%   |
| MacroSilicon                           | 3         | 0.83%   |
| Importek                               | 3         | 0.83%   |
| Generalplus Technology                 | 3         | 0.83%   |
| Elecom                                 | 3         | 0.83%   |
| Cubeternet                             | 3         | 0.83%   |
| Luxvisions Innotech Limited            | 2         | 0.56%   |
| Lenovo                                 | 2         | 0.56%   |
| Huawei Technologies                    | 2         | 0.56%   |
| Genesys Logic                          | 2         | 0.56%   |
| GEMBIRD                                | 2         | 0.56%   |
| Etron Technology                       | 2         | 0.56%   |
| BUFFALO                                | 2         | 0.56%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| WaveRider Communications               | 1         | 0.28%   |
| SunplusIT                              | 1         | 0.28%   |
| SJ-180517-N                            | 1         | 0.28%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.28%   |
| Ruision                                | 1         | 0.28%   |
| Primax Electronics                     | 1         | 0.28%   |
| OmniVision Technologies                | 1         | 0.28%   |
| Omnivision                             | 1         | 0.28%   |
| Oculus VR                              | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 14        | 3.81%   |
| IMC Networks Integrated Camera                          | 12        | 3.27%   |
| Chicony FJ Camera                                       | 12        | 3.27%   |
| Chicony Integrated Camera                               | 10        | 2.72%   |
| Realtek Integrated_Webcam_HD                            | 8         | 2.18%   |
| Chicony USB2.0 Camera                                   | 8         | 2.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 1.63%   |
| Logitech Webcam C270                                    | 5         | 1.36%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 1.36%   |
| Chicony TOSHIBA Web Camera - HD                         | 5         | 1.36%   |
| Apple FaceTime HD Camera (Built-in)                     | 5         | 1.36%   |
| Apple Built-in iSight                                   | 5         | 1.36%   |
| Sunplus HD WebCam                                       | 4         | 1.09%   |
| Ricoh Sony Vaio Integrated Webcam                       | 4         | 1.09%   |
| Microdia Webcam Vitade AF                               | 4         | 1.09%   |
| Lite-On Integrated Camera                               | 4         | 1.09%   |
| Chicony HD WebCam                                       | 4         | 1.09%   |
| Apple iPhone 5/5C/5S/6/SE                               | 4         | 1.09%   |
| Apple FaceTime HD Camera                                | 4         | 1.09%   |
| Acer USB HD Webcam                                      | 4         | 1.09%   |
| Acer Integrated Camera                                  | 4         | 1.09%   |
| Acer BisonCam, NB Pro                                   | 4         | 1.09%   |
| Syntek Integrated Camera                                | 3         | 0.82%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 0.82%   |
| Sunplus Integrated_Webcam_FHD                           | 3         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 3         | 0.82%   |
| Ricoh Sony Visual Communication Camera                  | 3         | 0.82%   |
| Realtek Lenovo EasyCamera                               | 3         | 0.82%   |
| Quanta HD User Facing                                   | 3         | 0.82%   |
| Microdia Integrated Webcam HD                           | 3         | 0.82%   |
| MacroSilicon USB Video                                  | 3         | 0.82%   |
| Logitech HD Pro Webcam C920                             | 3         | 0.82%   |
| Chicony USB 2.0 Camera                                  | 3         | 0.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 0.82%   |
| Chicony Lenovo EasyCamera                               | 3         | 0.82%   |
| Chicony HP Wide Vision HD Camera                        | 3         | 0.82%   |
| Chicony HP TrueVision HD Camera                         | 3         | 0.82%   |
| Chicony HP HD Camera                                    | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 0.82%   |
| Acer HD Webcam                                          | 3         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 26.37%  |
| Synaptics                  | 18        | 19.78%  |
| AuthenTec                  | 13        | 14.29%  |
| Shenzhen Goodix Technology | 12        | 13.19%  |
| Upek                       | 7         | 7.69%   |
| STMicroelectronics         | 6         | 6.59%   |
| LighTuning Technology      | 5         | 5.49%   |
| Elan Microelectronics      | 5         | 5.49%   |
| Focal-systems.Corp         | 1         | 1.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 11        | 12.09%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 6         | 6.59%   |
| STMicroelectronics Fingerprint Reader                  | 6         | 6.59%   |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 5.49%   |
| Shenzhen Goodix  FingerPrint Device                    | 5         | 5.49%   |
| Shenzhen Goodix Fingerprint Reader                     | 5         | 5.49%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 4         | 4.4%    |
| Validity Sensors Swipe Fingerprint Sensor              | 4         | 4.4%    |
| AuthenTec Fingerprint Sensor                           | 4         | 4.4%    |
| Unknown                                                | 4         | 4.4%    |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 3.3%    |
| AuthenTec AES2810                                      | 3         | 3.3%    |
| AuthenTec AES1600                                      | 3         | 3.3%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 2.2%    |
| Validity Sensors VFS491                                | 2         | 2.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 2.2%    |
| Shenzhen Goodix FingerPrint                            | 2         | 2.2%    |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 2.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 2.2%    |
| Elan fingerprint sensor [FeinTech FPS00200]            | 2         | 2.2%    |
| Elan ELAN:Fingerprint                                  | 2         | 2.2%    |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 2.2%    |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.1%    |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 1.1%    |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.1%    |
| Validity Sensors Synaptics WBDI                        | 1         | 1.1%    |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.1%    |
| Synaptics WBDI Device                                  | 1         | 1.1%    |
| LighTuning Fingerprint Reader                          | 1         | 1.1%    |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 1.1%    |
| Elan ELAN:ARM-M4                                       | 1         | 1.1%    |
| AuthenTec AES2660 Fingerprint Sensor                   | 1         | 1.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 8         | 30.77%  |
| Upek             | 7         | 26.92%  |
| Alcor Micro      | 5         | 19.23%  |
| O2 Micro         | 3         | 11.54%  |
| SCM Microsystems | 2         | 7.69%   |
| Yubico.com       | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 26.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 19.23%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 11.54%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 7.69%   |
| Broadcom 58200                                                               | 2         | 7.69%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.85%   |
| Broadcom 5880                                                                | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 687       | 71.86%  |
| 1     | 223       | 23.33%  |
| 2     | 33        | 3.45%   |
| 3     | 6         | 0.63%   |
| 6     | 2         | 0.21%   |
| 4     | 2         | 0.21%   |
| 8     | 1         | 0.1%    |
| 7     | 1         | 0.1%    |
| 5     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 89        | 27.55%  |
| Graphics card            | 48        | 14.86%  |
| Net/wireless             | 44        | 13.62%  |
| Multimedia controller    | 38        | 11.76%  |
| Chipcard                 | 22        | 6.81%   |
| Communication controller | 19        | 5.88%   |
| Unassigned class         | 12        | 3.72%   |
| Storage                  | 12        | 3.72%   |
| Bluetooth                | 9         | 2.79%   |
| Sound                    | 8         | 2.48%   |
| Camera                   | 6         | 1.86%   |
| Modem                    | 5         | 1.55%   |
| Storage/ata              | 3         | 0.93%   |
| Network                  | 3         | 0.93%   |
| Net/ethernet             | 3         | 0.93%   |
| Tv card                  | 1         | 0.31%   |
| Storage/nvme             | 1         | 0.31%   |


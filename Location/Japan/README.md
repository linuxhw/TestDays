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

Total: 1929

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [4f7bb0e30b](https://linux-hardware.org/?probe=4f7bb0e30b) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [594257aca2](https://linux-hardware.org/?probe=594257aca2) | Nov 03, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [328a40f6fe](https://linux-hardware.org/?probe=328a40f6fe) | Nov 03, 2023 |
| NEC Comput... | MS-7770MH                   | Desktop     | [9d2ab645d4](https://linux-hardware.org/?probe=9d2ab645d4) | Nov 03, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [28c1330071](https://linux-hardware.org/?probe=28c1330071) | Nov 01, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [771ada77a7](https://linux-hardware.org/?probe=771ada77a7) | Oct 30, 2023 |
| Toshiba       | dynabook T350/56ARK         | Notebook    | [802dacc8cc](https://linux-hardware.org/?probe=802dacc8cc) | Oct 27, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [2021aa6173](https://linux-hardware.org/?probe=2021aa6173) | Oct 27, 2023 |
| HP            | 3397                        | Desktop     | [50b7d4272d](https://linux-hardware.org/?probe=50b7d4272d) | Oct 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [f3802ecf63](https://linux-hardware.org/?probe=f3802ecf63) | Oct 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [15526c62b8](https://linux-hardware.org/?probe=15526c62b8) | Oct 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1ad6c144a3](https://linux-hardware.org/?probe=1ad6c144a3) | Oct 26, 2023 |
| NEC Comput... | PC-VJ22LFWZHSRF             | Notebook    | [b229c83a28](https://linux-hardware.org/?probe=b229c83a28) | Oct 25, 2023 |
| Dell          | 06FW8P A02                  | Desktop     | [4efc493619](https://linux-hardware.org/?probe=4efc493619) | Oct 24, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [480f22e1b7](https://linux-hardware.org/?probe=480f22e1b7) | Oct 24, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [b61468f9c5](https://linux-hardware.org/?probe=b61468f9c5) | Oct 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [8d2894b3d1](https://linux-hardware.org/?probe=8d2894b3d1) | Oct 24, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [35e54833e8](https://linux-hardware.org/?probe=35e54833e8) | Oct 23, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [a70e21055d](https://linux-hardware.org/?probe=a70e21055d) | Oct 23, 2023 |
| Dell          | G15 5515                    | Notebook    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| Shenzhen M... | F7BRC                       | Desktop     | [f61616bfcb](https://linux-hardware.org/?probe=f61616bfcb) | Oct 22, 2023 |
| MSI           | MS-7309                     | Desktop     | [b747d8e3a3](https://linux-hardware.org/?probe=b747d8e3a3) | Oct 22, 2023 |
| Fujitsu       | FARQ1801LZ                  | Tablet      | [e03dce2361](https://linux-hardware.org/?probe=e03dce2361) | Oct 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2682d3f618](https://linux-hardware.org/?probe=2682d3f618) | Oct 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [8765923ff6](https://linux-hardware.org/?probe=8765923ff6) | Oct 21, 2023 |
| HP            | 0AA0h                       | Desktop     | [4175b0f530](https://linux-hardware.org/?probe=4175b0f530) | Oct 20, 2023 |
| NEC Comput... | PC-VK26TLNZ39ZJ             | Notebook    | [86f3d9bdbe](https://linux-hardware.org/?probe=86f3d9bdbe) | Oct 19, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [9c4b6341e0](https://linux-hardware.org/?probe=9c4b6341e0) | Oct 18, 2023 |
| EPSON DIRE... | MR4400E                     | Desktop     | [3c07bfb5a0](https://linux-hardware.org/?probe=3c07bfb5a0) | Oct 18, 2023 |
| EPSON DIRE... | MR4400E                     | Desktop     | [8559cb634e](https://linux-hardware.org/?probe=8559cb634e) | Oct 17, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [4b4319490d](https://linux-hardware.org/?probe=4b4319490d) | Oct 17, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [bc01f51395](https://linux-hardware.org/?probe=bc01f51395) | Oct 17, 2023 |
| MouseCompu... | GTN83G15H19C                | Notebook    | [39e86c5be4](https://linux-hardware.org/?probe=39e86c5be4) | Oct 17, 2023 |
| NEC Comput... | PC-VK27MDZDN                | Notebook    | [052e2dbcc2](https://linux-hardware.org/?probe=052e2dbcc2) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | Notebook    | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [2bda5e79a4](https://linux-hardware.org/?probe=2bda5e79a4) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [4bc1c4e1b6](https://linux-hardware.org/?probe=4bc1c4e1b6) | Oct 14, 2023 |
| Fujitsu       | FMVNS7HE                    | Notebook    | [2408a69be7](https://linux-hardware.org/?probe=2408a69be7) | Oct 13, 2023 |
| HP            | 8714                        | Desktop     | [ab691c5017](https://linux-hardware.org/?probe=ab691c5017) | Oct 11, 2023 |
| Toshiba       | dynabook B452/22F           | Notebook    | [61777cd92a](https://linux-hardware.org/?probe=61777cd92a) | Oct 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [d739639932](https://linux-hardware.org/?probe=d739639932) | Oct 09, 2023 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [e95641d18d](https://linux-hardware.org/?probe=e95641d18d) | Oct 08, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3d6601e877](https://linux-hardware.org/?probe=3d6601e877) | Oct 08, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [1cbdc082a8](https://linux-hardware.org/?probe=1cbdc082a8) | Oct 08, 2023 |
| Intel         | NUC6CAYB J26842-405         | Mini pc     | [b5bbc87f1b](https://linux-hardware.org/?probe=b5bbc87f1b) | Oct 07, 2023 |
| AZW           | Green G4 10                 | Desktop     | [d8fb758dec](https://linux-hardware.org/?probe=d8fb758dec) | Oct 07, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [0aa9a5ddc3](https://linux-hardware.org/?probe=0aa9a5ddc3) | Oct 05, 2023 |
| Fujitsu       | FMVA05007                   | Notebook    | [265b66f904](https://linux-hardware.org/?probe=265b66f904) | Oct 05, 2023 |
| Timi          | A30                         | Notebook    | [36d352fb7f](https://linux-hardware.org/?probe=36d352fb7f) | Oct 04, 2023 |
| Gigabyte      | 5MMSV-RHD                   | Desktop     | [ec5e1c9b31](https://linux-hardware.org/?probe=ec5e1c9b31) | Oct 03, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [9d0b849593](https://linux-hardware.org/?probe=9d0b849593) | Oct 01, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [f2c369cb00](https://linux-hardware.org/?probe=f2c369cb00) | Oct 01, 2023 |
| ASUSTek       | P5B-E Plus                  | Desktop     | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| Unknown       | TB-5000                     | Desktop     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| GMKtec        | NucBox3                     | Desktop     | [c99750febd](https://linux-hardware.org/?probe=c99750febd) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| Dell          | Latitude 7390               | Notebook    | [93e22b6fc4](https://linux-hardware.org/?probe=93e22b6fc4) | Sep 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a7bfa2e285](https://linux-hardware.org/?probe=a7bfa2e285) | Sep 27, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [6554d255c3](https://linux-hardware.org/?probe=6554d255c3) | Sep 27, 2023 |
| AAEON         | MIX-H310D1 V1.0             | Desktop     | [7a3b3d3b2d](https://linux-hardware.org/?probe=7a3b3d3b2d) | Sep 27, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [48a8e36d5f](https://linux-hardware.org/?probe=48a8e36d5f) | Sep 25, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [8427efde7d](https://linux-hardware.org/?probe=8427efde7d) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [7aea90703a](https://linux-hardware.org/?probe=7aea90703a) | Sep 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [7e03b87e4b](https://linux-hardware.org/?probe=7e03b87e4b) | Sep 23, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [be07169f5c](https://linux-hardware.org/?probe=be07169f5c) | Sep 22, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [b90045e0f9](https://linux-hardware.org/?probe=b90045e0f9) | Sep 22, 2023 |
| ASUSTek       | TP550LAB                    | Notebook    | [3e07304aa5](https://linux-hardware.org/?probe=3e07304aa5) | Sep 20, 2023 |
| Dell          | Latitude 3540               | Notebook    | [3f1c99de44](https://linux-hardware.org/?probe=3f1c99de44) | Sep 20, 2023 |
| Lenovo        | ThinkPad X240 20AMA1S702    | Notebook    | [5be3b8fc11](https://linux-hardware.org/?probe=5be3b8fc11) | Sep 19, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c26fb8a8da](https://linux-hardware.org/?probe=c26fb8a8da) | Sep 18, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0f0607d7e4](https://linux-hardware.org/?probe=0f0607d7e4) | Sep 18, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [fa9b30f699](https://linux-hardware.org/?probe=fa9b30f699) | Sep 18, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [1e61961aef](https://linux-hardware.org/?probe=1e61961aef) | Sep 17, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [1a5acc2c10](https://linux-hardware.org/?probe=1a5acc2c10) | Sep 17, 2023 |
| NEC Comput... | PC-VK15EBZDG                | Notebook    | [83d74c1e9d](https://linux-hardware.org/?probe=83d74c1e9d) | Sep 17, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [e8f9c86131](https://linux-hardware.org/?probe=e8f9c86131) | Sep 16, 2023 |
| HP            | Pavilion dv2                | Notebook    | [ee227b3d35](https://linux-hardware.org/?probe=ee227b3d35) | Sep 16, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [b3d56132ec](https://linux-hardware.org/?probe=b3d56132ec) | Sep 15, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8c529cfaa8](https://linux-hardware.org/?probe=8c529cfaa8) | Sep 11, 2023 |
| Intel         | DG41TY AAE47335-202         | Desktop     | [cd00ffcda2](https://linux-hardware.org/?probe=cd00ffcda2) | Sep 09, 2023 |
| Intel         | DG41TY AAE47335-202         | Desktop     | [4cdbce3b75](https://linux-hardware.org/?probe=4cdbce3b75) | Sep 09, 2023 |
| Qualcomm T... | MSM 8996 v3 + PMI8994 MT... | Phone       | [3e988cbaf9](https://linux-hardware.org/?probe=3e988cbaf9) | Sep 09, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [b173b156f9](https://linux-hardware.org/?probe=b173b156f9) | Sep 04, 2023 |
| Dynabook      | G83/HS                      | Notebook    | [9db149b715](https://linux-hardware.org/?probe=9db149b715) | Sep 04, 2023 |
| Toshiba       | dynabook VC72/M             | Convertible | [988d354b55](https://linux-hardware.org/?probe=988d354b55) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| NEC Comput... | MS-7451MA                   | Desktop     | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| Toshiba       | dynabook R73/J              | Notebook    | [c63c97e4a8](https://linux-hardware.org/?probe=c63c97e4a8) | Sep 03, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [1c82c8d8b5](https://linux-hardware.org/?probe=1c82c8d8b5) | Sep 02, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [a8bdd5bcca](https://linux-hardware.org/?probe=a8bdd5bcca) | Sep 02, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [f90ed18892](https://linux-hardware.org/?probe=f90ed18892) | Sep 01, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [033a5ccf76](https://linux-hardware.org/?probe=033a5ccf76) | Sep 01, 2023 |
| MSI           | X99A WORKSTATION            | Desktop     | [46d1af7083](https://linux-hardware.org/?probe=46d1af7083) | Sep 01, 2023 |
| HP            | 806A                        | Desktop     | [638dfe4edc](https://linux-hardware.org/?probe=638dfe4edc) | Aug 31, 2023 |
| System76      | Lemur Pro                   | Notebook    | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [fab320d1d5](https://linux-hardware.org/?probe=fab320d1d5) | Aug 31, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [3bee4c1b45](https://linux-hardware.org/?probe=3bee4c1b45) | Aug 30, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [c95eb85e58](https://linux-hardware.org/?probe=c95eb85e58) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [ad154077da](https://linux-hardware.org/?probe=ad154077da) | Aug 28, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [0cda85fdd1](https://linux-hardware.org/?probe=0cda85fdd1) | Aug 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ccc34d5a51](https://linux-hardware.org/?probe=ccc34d5a51) | Aug 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [25dc707bff](https://linux-hardware.org/?probe=25dc707bff) | Aug 24, 2023 |
| Timi          | A35                         | Notebook    | [50e380e876](https://linux-hardware.org/?probe=50e380e876) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [62ac8a7715](https://linux-hardware.org/?probe=62ac8a7715) | Aug 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| HP            | 18E7                        | Desktop     | [7c200916bf](https://linux-hardware.org/?probe=7c200916bf) | Aug 22, 2023 |
| HP            | 18E7                        | Desktop     | [6cd6ef6396](https://linux-hardware.org/?probe=6cd6ef6396) | Aug 22, 2023 |
| Toshiba       | dynabook B350/22A           | Notebook    | [80ad4cd1ff](https://linux-hardware.org/?probe=80ad4cd1ff) | Aug 21, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9d07a3d5c7](https://linux-hardware.org/?probe=9d07a3d5c7) | Aug 21, 2023 |
| Alienware     | 17                          | Notebook    | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [94b9b057b4](https://linux-hardware.org/?probe=94b9b057b4) | Aug 17, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [0ddde115f9](https://linux-hardware.org/?probe=0ddde115f9) | Aug 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [a5086e207e](https://linux-hardware.org/?probe=a5086e207e) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| MSI           | Stealth 14Studio A13VG      | Notebook    | [a8035775f2](https://linux-hardware.org/?probe=a8035775f2) | Aug 14, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [9a680df78d](https://linux-hardware.org/?probe=9a680df78d) | Aug 14, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [453329dbff](https://linux-hardware.org/?probe=453329dbff) | Aug 12, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [8abafe1b65](https://linux-hardware.org/?probe=8abafe1b65) | Aug 12, 2023 |
| Fujitsu       | JIQ87Y                      | Desktop     | [b11d99014e](https://linux-hardware.org/?probe=b11d99014e) | Aug 12, 2023 |
| Gateway       | MD7309U                     | Notebook    | [18dbacfdab](https://linux-hardware.org/?probe=18dbacfdab) | Aug 10, 2023 |
| NEC Comput... | 312C                        | Desktop     | [770ffcfcf5](https://linux-hardware.org/?probe=770ffcfcf5) | Aug 10, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [ffb5c4343b](https://linux-hardware.org/?probe=ffb5c4343b) | Aug 10, 2023 |
| NEC Comput... | PC-GN246W3A5                | Notebook    | [2f37664ebd](https://linux-hardware.org/?probe=2f37664ebd) | Aug 10, 2023 |
| Sony          | VJF151                      | Notebook    | [b2768a0abf](https://linux-hardware.org/?probe=b2768a0abf) | Aug 09, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [83d5950b7a](https://linux-hardware.org/?probe=83d5950b7a) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | Notebook    | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [4bd753037a](https://linux-hardware.org/?probe=4bd753037a) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [b4cc5c436c](https://linux-hardware.org/?probe=b4cc5c436c) | Aug 06, 2023 |
| Biostar       | B350GTN                     | Desktop     | [5ae18cae6c](https://linux-hardware.org/?probe=5ae18cae6c) | Aug 04, 2023 |
| MouseCompu... | WHLD4-P1                    | Mini pc     | [3006496f16](https://linux-hardware.org/?probe=3006496f16) | Aug 03, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [4d0d3b78e7](https://linux-hardware.org/?probe=4d0d3b78e7) | Aug 02, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [2e59618067](https://linux-hardware.org/?probe=2e59618067) | Aug 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8559f3826b](https://linux-hardware.org/?probe=8559f3826b) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | Notebook    | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [52cefaf6dd](https://linux-hardware.org/?probe=52cefaf6dd) | Jul 28, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [06e3fae658](https://linux-hardware.org/?probe=06e3fae658) | Jul 24, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [3d41743a5d](https://linux-hardware.org/?probe=3d41743a5d) | Jul 23, 2023 |
| MSI           | Z87-G43                     | Desktop     | [f153badd8c](https://linux-hardware.org/?probe=f153badd8c) | Jul 23, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21EXC... | Notebook    | [5777fd52c6](https://linux-hardware.org/?probe=5777fd52c6) | Jul 22, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [a9639fb963](https://linux-hardware.org/?probe=a9639fb963) | Jul 22, 2023 |
| HP            | 158A                        | Desktop     | [a2a4176353](https://linux-hardware.org/?probe=a2a4176353) | Jul 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Sony          | VPCEB48FJ                   | Notebook    | [95cab43ae1](https://linux-hardware.org/?probe=95cab43ae1) | Jul 21, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| Pegatron      | IPM41G                      | Desktop     | [9d29cf9820](https://linux-hardware.org/?probe=9d29cf9820) | Jul 18, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [3cf00d1f89](https://linux-hardware.org/?probe=3cf00d1f89) | Jul 16, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [71e33b92ad](https://linux-hardware.org/?probe=71e33b92ad) | Jul 16, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [cf0f0d0820](https://linux-hardware.org/?probe=cf0f0d0820) | Jul 15, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| Lenovo        | ThinkPad Edge E535 3260C... | Notebook    | [9ff1a61e2a](https://linux-hardware.org/?probe=9ff1a61e2a) | Jul 14, 2023 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [835e924f6d](https://linux-hardware.org/?probe=835e924f6d) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [7bf81133fc](https://linux-hardware.org/?probe=7bf81133fc) | Jul 12, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [c952cab7d7](https://linux-hardware.org/?probe=c952cab7d7) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [00e22b8fa7](https://linux-hardware.org/?probe=00e22b8fa7) | Jul 10, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [703f4fd012](https://linux-hardware.org/?probe=703f4fd012) | Jul 10, 2023 |
| Pegatron      | IPM41G                      | Desktop     | [be1f42c658](https://linux-hardware.org/?probe=be1f42c658) | Jul 09, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [2349cf550c](https://linux-hardware.org/?probe=2349cf550c) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a5267b5818](https://linux-hardware.org/?probe=a5267b5818) | Jul 08, 2023 |
| Toshiba       | dynabook R73/Y              | Notebook    | [37e3897f65](https://linux-hardware.org/?probe=37e3897f65) | Jul 08, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| Gigabyte      | AERO 16 OLED BSF            | Notebook    | [1148bd3952](https://linux-hardware.org/?probe=1148bd3952) | Jul 04, 2023 |
| Lenovo        | ThinkPad L520 5015A12       | Notebook    | [0cb85712d9](https://linux-hardware.org/?probe=0cb85712d9) | Jul 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b025249305](https://linux-hardware.org/?probe=b025249305) | Jul 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [9f1aec7e08](https://linux-hardware.org/?probe=9f1aec7e08) | Jul 01, 2023 |
| Toshiba       | All In One PC MP            | All in one  | [d9f55bbac6](https://linux-hardware.org/?probe=d9f55bbac6) | Jun 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | Notebook    | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Sony          | VGN-AR74DB                  | Notebook    | [c51cc05c0a](https://linux-hardware.org/?probe=c51cc05c0a) | Jun 25, 2023 |
| HP            | 0A54h                       | Desktop     | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| HP            | 0A54h                       | Desktop     | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4e877b9c8d](https://linux-hardware.org/?probe=4e877b9c8d) | Jun 22, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [1b2f8eb529](https://linux-hardware.org/?probe=1b2f8eb529) | Jun 22, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [2e14ad6bce](https://linux-hardware.org/?probe=2e14ad6bce) | Jun 20, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [e3b13a5c7f](https://linux-hardware.org/?probe=e3b13a5c7f) | Jun 20, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | Notebook    | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [673cf6831d](https://linux-hardware.org/?probe=673cf6831d) | Jun 16, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| HP            | ProLiant DL360e Gen8        | Server      | [689a7f3ca3](https://linux-hardware.org/?probe=689a7f3ca3) | Jun 16, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [09b0f43143](https://linux-hardware.org/?probe=09b0f43143) | Jun 14, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [32069bc39d](https://linux-hardware.org/?probe=32069bc39d) | Jun 13, 2023 |
| MouseCompu... | B360M                       | Desktop     | [6a7f26bdae](https://linux-hardware.org/?probe=6a7f26bdae) | Jun 12, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Toshiba       | All In One PC MP            | All in one  | [8d7e520fef](https://linux-hardware.org/?probe=8d7e520fef) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [46c70e6e33](https://linux-hardware.org/?probe=46c70e6e33) | Jun 10, 2023 |
| ASRock        | G41C-GS R2.0                | Desktop     | [6e4835c7bc](https://linux-hardware.org/?probe=6e4835c7bc) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d48dc73993](https://linux-hardware.org/?probe=d48dc73993) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [374a3fef00](https://linux-hardware.org/?probe=374a3fef00) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [413d6e5373](https://linux-hardware.org/?probe=413d6e5373) | Jun 05, 2023 |
| NEC Comput... | MS-AD611                    | All in one  | [219795e31d](https://linux-hardware.org/?probe=219795e31d) | Jun 05, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [de1d4d9d23](https://linux-hardware.org/?probe=de1d4d9d23) | Jun 05, 2023 |
| Acer          | Veriton X4630G V:1.0        | Desktop     | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| Apple         | MacBookAir8,1               | Notebook    | [47b2ee3c0d](https://linux-hardware.org/?probe=47b2ee3c0d) | May 28, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [affdf49716](https://linux-hardware.org/?probe=affdf49716) | May 27, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [106bd355da](https://linux-hardware.org/?probe=106bd355da) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Fujitsu       | FMVA42ERKS                  | Notebook    | [91fa73184c](https://linux-hardware.org/?probe=91fa73184c) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [769f5c0d23](https://linux-hardware.org/?probe=769f5c0d23) | May 25, 2023 |
| EPSON DIRE... | MR7200E-L                   | Desktop     | [a436b49a11](https://linux-hardware.org/?probe=a436b49a11) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [00a6f60d75](https://linux-hardware.org/?probe=00a6f60d75) | May 23, 2023 |
| ASRock        | H77M                        | Desktop     | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [b03cb56dfa](https://linux-hardware.org/?probe=b03cb56dfa) | May 21, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [90b4889055](https://linux-hardware.org/?probe=90b4889055) | May 21, 2023 |
| Gigabyte      | GA-6LASL 01234567           | Server      | [13eb4e7266](https://linux-hardware.org/?probe=13eb4e7266) | May 19, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | Desktop     | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | Desktop     | [fed1ba2b90](https://linux-hardware.org/?probe=fed1ba2b90) | May 17, 2023 |
| NEC Comput... | SK15 3A3B                   | All in one  | [80a4b43ab9](https://linux-hardware.org/?probe=80a4b43ab9) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | Desktop     | [b0710623f7](https://linux-hardware.org/?probe=b0710623f7) | May 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [35990f19da](https://linux-hardware.org/?probe=35990f19da) | May 12, 2023 |
| Lenovo        | YangTian V340-15-IML 81V... | Notebook    | [cedb6136dc](https://linux-hardware.org/?probe=cedb6136dc) | May 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [8f41b17a9b](https://linux-hardware.org/?probe=8f41b17a9b) | May 10, 2023 |
| Fujitsu       | FMVA0500TP                  | Notebook    | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Acer          | EG43M                       | Desktop     | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | X202E                       | Notebook    | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| NEC Comput... | IH81M                       | Desktop     | [407098c17f](https://linux-hardware.org/?probe=407098c17f) | May 07, 2023 |
| ASUSTek       | STRIX B250I GAMING          | Desktop     | [536e6e7cc9](https://linux-hardware.org/?probe=536e6e7cc9) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| HP            | 1998                        | Desktop     | [92772a7c11](https://linux-hardware.org/?probe=92772a7c11) | May 06, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [893d6b37e8](https://linux-hardware.org/?probe=893d6b37e8) | May 05, 2023 |
| MouseCompu... | B75M-D3V-JP                 | Desktop     | [a72531bd2d](https://linux-hardware.org/?probe=a72531bd2d) | May 04, 2023 |
| Fujitsu       | FMVA705ABS                  | Notebook    | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | Notebook    | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Intel         | PH10LU E13069-531           | Desktop     | [432b5e380d](https://linux-hardware.org/?probe=432b5e380d) | May 03, 2023 |
| Intel         | PH10LU E13069-531           | Desktop     | [f34e545b00](https://linux-hardware.org/?probe=f34e545b00) | May 03, 2023 |
| Lenovo        | 4068AGJ                     | Notebook    | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [323e28fded](https://linux-hardware.org/?probe=323e28fded) | Apr 29, 2023 |
| HP            | 158A                        | Desktop     | [fb7aef7883](https://linux-hardware.org/?probe=fb7aef7883) | Apr 28, 2023 |
| MSI           | A78M-E35 V2                 | Desktop     | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | Notebook    | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| HP            | 158A                        | Desktop     | [c3189bccb1](https://linux-hardware.org/?probe=c3189bccb1) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | Notebook    | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | Notebook    | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | Notebook    | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | Notebook    | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [3c50d5d61c](https://linux-hardware.org/?probe=3c50d5d61c) | Apr 24, 2023 |
| ASUSTek       | STRIX B250I GAMING          | Desktop     | [beabf00341](https://linux-hardware.org/?probe=beabf00341) | Apr 24, 2023 |
| ASUSTek       | STRIX B250I GAMING          | Desktop     | [0e96ee4471](https://linux-hardware.org/?probe=0e96ee4471) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | Desktop     | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Toshiba       | dynabook BX/67TG            | Notebook    | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [08ebdd71ab](https://linux-hardware.org/?probe=08ebdd71ab) | Apr 23, 2023 |
| Fujitsu       | FJNB037                     | Desktop     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| Fujitsu       | FMVA42CW                    | Notebook    | [4fb1ab7ab8](https://linux-hardware.org/?probe=4fb1ab7ab8) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b3613186fa](https://linux-hardware.org/?probe=b3613186fa) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | Desktop     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | Desktop     | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| Toshiba       | dynabook T451/46EW          | Notebook    | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| ECS           | BSW-MINI                    | Desktop     | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [7981ad8440](https://linux-hardware.org/?probe=7981ad8440) | Apr 19, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| NEC Comput... | MS-7451VM                   | Desktop     | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| ASRock        | Z270 Taichi                 | Desktop     | [5f3eb929b7](https://linux-hardware.org/?probe=5f3eb929b7) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [eb66896af3](https://linux-hardware.org/?probe=eb66896af3) | Apr 18, 2023 |
| Fujitsu       | FMVNA6HE                    | Notebook    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [8f5803697f](https://linux-hardware.org/?probe=8f5803697f) | Apr 17, 2023 |
| ASRock        | A520M TW                    | Desktop     | [0fc8e9ca06](https://linux-hardware.org/?probe=0fc8e9ca06) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | Notebook    | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [3455570853](https://linux-hardware.org/?probe=3455570853) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| Gigabyte      | F2A85XN-WIFI                | Desktop     | [80a8d69a06](https://linux-hardware.org/?probe=80a8d69a06) | Apr 15, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | Desktop     | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | Desktop     | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dc66113388](https://linux-hardware.org/?probe=dc66113388) | Apr 11, 2023 |
| Intel         | NUC10i5FNB K61361-302       | Mini pc     | [03c7dc63da](https://linux-hardware.org/?probe=03c7dc63da) | Apr 09, 2023 |
| Dell          | G7 7700                     | Notebook    | [9552c2ecc0](https://linux-hardware.org/?probe=9552c2ecc0) | Apr 09, 2023 |
| Toshiba       | dynabook R732/H             | Notebook    | [ff99abe105](https://linux-hardware.org/?probe=ff99abe105) | Apr 08, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e34683f5f0](https://linux-hardware.org/?probe=e34683f5f0) | Apr 07, 2023 |
| Lenovo        | 3000 N200 0769DQJ           | Notebook    | [db1539e64a](https://linux-hardware.org/?probe=db1539e64a) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [78c525b19b](https://linux-hardware.org/?probe=78c525b19b) | Apr 05, 2023 |
| Fujitsu       | FMVA45MRP2                  | Notebook    | [80b1f5983b](https://linux-hardware.org/?probe=80b1f5983b) | Apr 05, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [4bbe18183a](https://linux-hardware.org/?probe=4bbe18183a) | Apr 04, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6bf9bb58c5](https://linux-hardware.org/?probe=6bf9bb58c5) | Apr 04, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [7f0e2d07b5](https://linux-hardware.org/?probe=7f0e2d07b5) | Apr 01, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [1f3b96d1a0](https://linux-hardware.org/?probe=1f3b96d1a0) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [eea311b1bb](https://linux-hardware.org/?probe=eea311b1bb) | Apr 01, 2023 |
| Acer          | Aspire 1410                 | Notebook    | [58be80ea51](https://linux-hardware.org/?probe=58be80ea51) | Mar 31, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [94a37d865e](https://linux-hardware.org/?probe=94a37d865e) | Mar 30, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [393fc00a5d](https://linux-hardware.org/?probe=393fc00a5d) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [405e95a907](https://linux-hardware.org/?probe=405e95a907) | Mar 28, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [e5644591de](https://linux-hardware.org/?probe=e5644591de) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [922d8a7941](https://linux-hardware.org/?probe=922d8a7941) | Mar 26, 2023 |
| MSI           | MEG B550 UNIFY              | Desktop     | [492a70f1c3](https://linux-hardware.org/?probe=492a70f1c3) | Mar 26, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [cf7ab8adb4](https://linux-hardware.org/?probe=cf7ab8adb4) | Mar 26, 2023 |
| Lenovo        | ThinkPad X230 2306A44       | Notebook    | [e948a25ef6](https://linux-hardware.org/?probe=e948a25ef6) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [f8fc6c74da](https://linux-hardware.org/?probe=f8fc6c74da) | Mar 25, 2023 |
| HP            | 158A                        | Desktop     | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e6ecf47eda](https://linux-hardware.org/?probe=e6ecf47eda) | Mar 24, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| HP            | 158A                        | Desktop     | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [33137a049e](https://linux-hardware.org/?probe=33137a049e) | Mar 20, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| HUAWEI        | FRD-WX9                     | Notebook    | [b5a517c552](https://linux-hardware.org/?probe=b5a517c552) | Mar 20, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [3718d345ca](https://linux-hardware.org/?probe=3718d345ca) | Mar 18, 2023 |
| Lenovo        | ThinkCentre A58 7522M4J     | Desktop     | [ba0a303be5](https://linux-hardware.org/?probe=ba0a303be5) | Mar 17, 2023 |
| HP            | 806A                        | Desktop     | [2203b83131](https://linux-hardware.org/?probe=2203b83131) | Mar 13, 2023 |
| ASUSTek       | X55U                        | Notebook    | [b06bd51348](https://linux-hardware.org/?probe=b06bd51348) | Mar 11, 2023 |
| Unknown       | HX90                        | Desktop     | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| Toshiba       | All In One PC MP            | All in one  | [2a3a0b15f8](https://linux-hardware.org/?probe=2a3a0b15f8) | Mar 11, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [70f4bed81b](https://linux-hardware.org/?probe=70f4bed81b) | Mar 08, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [a97c12b513](https://linux-hardware.org/?probe=a97c12b513) | Mar 08, 2023 |
| Google        | Bobba                       | Notebook    | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [149c782883](https://linux-hardware.org/?probe=149c782883) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| ASUSTek       | P9D-I Series                | Server      | [e2cebc5f47](https://linux-hardware.org/?probe=e2cebc5f47) | Mar 07, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [a36361538b](https://linux-hardware.org/?probe=a36361538b) | Mar 07, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f85824345a](https://linux-hardware.org/?probe=f85824345a) | Mar 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| Dell          | Latitude 5300               | Notebook    | [a77b29e10d](https://linux-hardware.org/?probe=a77b29e10d) | Mar 04, 2023 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [825b26708c](https://linux-hardware.org/?probe=825b26708c) | Mar 04, 2023 |
| NEC Comput... | MS-AE211                    | All in one  | [6f4a2d24c1](https://linux-hardware.org/?probe=6f4a2d24c1) | Mar 04, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [82ecc9ac72](https://linux-hardware.org/?probe=82ecc9ac72) | Mar 03, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [b0076c9250](https://linux-hardware.org/?probe=b0076c9250) | Mar 03, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [1d81bb5f08](https://linux-hardware.org/?probe=1d81bb5f08) | Mar 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ed5432e979](https://linux-hardware.org/?probe=ed5432e979) | Mar 01, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [dee37a9bd9](https://linux-hardware.org/?probe=dee37a9bd9) | Mar 01, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [3887cb1418](https://linux-hardware.org/?probe=3887cb1418) | Feb 26, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [93f09b28d6](https://linux-hardware.org/?probe=93f09b28d6) | Feb 26, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [51bd5c9f21](https://linux-hardware.org/?probe=51bd5c9f21) | Feb 26, 2023 |
| Gigabyte      | B85N PHOENIX                | Desktop     | [5fe00f35c4](https://linux-hardware.org/?probe=5fe00f35c4) | Feb 25, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [7864921f8d](https://linux-hardware.org/?probe=7864921f8d) | Feb 25, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [ac156d2c80](https://linux-hardware.org/?probe=ac156d2c80) | Feb 22, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [d6edc5401d](https://linux-hardware.org/?probe=d6edc5401d) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [5d62c279d2](https://linux-hardware.org/?probe=5d62c279d2) | Feb 21, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b8b41b7a6e](https://linux-hardware.org/?probe=b8b41b7a6e) | Feb 19, 2023 |
| HP            | 158A                        | Desktop     | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| Dell          | Latitude 5300               | Notebook    | [371d693177](https://linux-hardware.org/?probe=371d693177) | Feb 17, 2023 |
| Dell          | Latitude 5300               | Notebook    | [323f21bb1e](https://linux-hardware.org/?probe=323f21bb1e) | Feb 17, 2023 |
| Dell          | Latitude 5300               | Notebook    | [ca02606bea](https://linux-hardware.org/?probe=ca02606bea) | Feb 17, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [eb04bfdc84](https://linux-hardware.org/?probe=eb04bfdc84) | Feb 14, 2023 |
| EPSON DIRE... | Endeavor NY2200S            | Notebook    | [2be0a1a8a0](https://linux-hardware.org/?probe=2be0a1a8a0) | Feb 14, 2023 |
| EPSON DIRE... | Endeavor NY2200S            | Notebook    | [29b669f143](https://linux-hardware.org/?probe=29b669f143) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [7fc3c03910](https://linux-hardware.org/?probe=7fc3c03910) | Feb 13, 2023 |
| Compaq        | 420                         | Notebook    | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| Lenovo        | ThinkPad L512 4444PV3       | Notebook    | [8965eee02f](https://linux-hardware.org/?probe=8965eee02f) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWA1MDJ... | Notebook    | [cc5f5375d2](https://linux-hardware.org/?probe=cc5f5375d2) | Feb 09, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [2422c70d2e](https://linux-hardware.org/?probe=2422c70d2e) | Feb 09, 2023 |
| HP            | Notebook                    | Notebook    | [7d4a89adea](https://linux-hardware.org/?probe=7d4a89adea) | Feb 08, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| NEC Comput... | Artemis3 3A3B               | All in one  | [6f613e9791](https://linux-hardware.org/?probe=6f613e9791) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c5bdedaf17](https://linux-hardware.org/?probe=c5bdedaf17) | Feb 04, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [9de02793ea](https://linux-hardware.org/?probe=9de02793ea) | Feb 04, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [6c1119bb00](https://linux-hardware.org/?probe=6c1119bb00) | Feb 04, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [deec906907](https://linux-hardware.org/?probe=deec906907) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | Desktop     | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [4af666d5b3](https://linux-hardware.org/?probe=4af666d5b3) | Feb 02, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [b048f7d3e1](https://linux-hardware.org/?probe=b048f7d3e1) | Feb 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [e2721d08d6](https://linux-hardware.org/?probe=e2721d08d6) | Jan 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [d780984cf9](https://linux-hardware.org/?probe=d780984cf9) | Jan 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [935a50bce1](https://linux-hardware.org/?probe=935a50bce1) | Jan 30, 2023 |
| Google        | Helios                      | Notebook    | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| NEC Comput... | PC-NS350AAR-KS              | Notebook    | [c4aa0da6f4](https://linux-hardware.org/?probe=c4aa0da6f4) | Jan 27, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [af59cf3cd3](https://linux-hardware.org/?probe=af59cf3cd3) | Jan 26, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [00cabfbb97](https://linux-hardware.org/?probe=00cabfbb97) | Jan 24, 2023 |
| Neousys Te... | NVS-7000 Rev. A2            | Server      | [196c8eb317](https://linux-hardware.org/?probe=196c8eb317) | Jan 23, 2023 |
| Purism        | Librem 15 v3                | Notebook    | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [1acfabc208](https://linux-hardware.org/?probe=1acfabc208) | Jan 22, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [7068e861ba](https://linux-hardware.org/?probe=7068e861ba) | Jan 21, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [9790dcdef4](https://linux-hardware.org/?probe=9790dcdef4) | Jan 19, 2023 |
| Unknown       | HX90                        | Desktop     | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7b255b7fe7](https://linux-hardware.org/?probe=7b255b7fe7) | Jan 18, 2023 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [b43c8a95b7](https://linux-hardware.org/?probe=b43c8a95b7) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [b781eb32d2](https://linux-hardware.org/?probe=b781eb32d2) | Jan 18, 2023 |
| Dell          | XPS 9320                    | Notebook    | [bd7346b7c2](https://linux-hardware.org/?probe=bd7346b7c2) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| Dell          | Latitude 3540               | Notebook    | [01688be251](https://linux-hardware.org/?probe=01688be251) | Jan 15, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [c52d3b2b2f](https://linux-hardware.org/?probe=c52d3b2b2f) | Jan 15, 2023 |
| Fujitsu       | FMVNF70YX                   | Notebook    | [2817102c87](https://linux-hardware.org/?probe=2817102c87) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [fa1ebc0951](https://linux-hardware.org/?probe=fa1ebc0951) | Jan 14, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d89e9dec4](https://linux-hardware.org/?probe=4d89e9dec4) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | Notebook    | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | Notebook    | [b2965791cb](https://linux-hardware.org/?probe=b2965791cb) | Jan 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | Notebook    | [093e5ffc06](https://linux-hardware.org/?probe=093e5ffc06) | Jan 13, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [4d9f4512a6](https://linux-hardware.org/?probe=4d9f4512a6) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | Notebook    | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [20bc38b554](https://linux-hardware.org/?probe=20bc38b554) | Jan 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [9aaef76c2c](https://linux-hardware.org/?probe=9aaef76c2c) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [1d0cd9b040](https://linux-hardware.org/?probe=1d0cd9b040) | Jan 09, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [6a2ef2080d](https://linux-hardware.org/?probe=6a2ef2080d) | Jan 09, 2023 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [73e8740cb9](https://linux-hardware.org/?probe=73e8740cb9) | Jan 08, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [8fe8187a9e](https://linux-hardware.org/?probe=8fe8187a9e) | Jan 08, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [75cabfba4d](https://linux-hardware.org/?probe=75cabfba4d) | Jan 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [70b2e771b7](https://linux-hardware.org/?probe=70b2e771b7) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | Notebook    | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [d3bab9b69b](https://linux-hardware.org/?probe=d3bab9b69b) | Jan 02, 2023 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [cac689a705](https://linux-hardware.org/?probe=cac689a705) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| Dell          | XPS 9320                    | Notebook    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| Dell          | XPS 9320                    | Notebook    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [86dcc5a2ff](https://linux-hardware.org/?probe=86dcc5a2ff) | Dec 30, 2022 |
| HP            | 2B36                        | Desktop     | [4b363628a9](https://linux-hardware.org/?probe=4b363628a9) | Dec 30, 2022 |
| HP            | 2B36                        | Desktop     | [be6670b1ad](https://linux-hardware.org/?probe=be6670b1ad) | Dec 30, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [a1f59f6ff9](https://linux-hardware.org/?probe=a1f59f6ff9) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [e5a7b5b5be](https://linux-hardware.org/?probe=e5a7b5b5be) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [71d2c76079](https://linux-hardware.org/?probe=71d2c76079) | Dec 28, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e08cfee8e8](https://linux-hardware.org/?probe=e08cfee8e8) | Dec 27, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [071ff79fc2](https://linux-hardware.org/?probe=071ff79fc2) | Dec 27, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [2df0678d78](https://linux-hardware.org/?probe=2df0678d78) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0069729ebe](https://linux-hardware.org/?probe=0069729ebe) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [985e965dec](https://linux-hardware.org/?probe=985e965dec) | Dec 25, 2022 |
| HP            | 18E7                        | Desktop     | [260119e159](https://linux-hardware.org/?probe=260119e159) | Dec 25, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [ef194165fc](https://linux-hardware.org/?probe=ef194165fc) | Dec 24, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [1f10cd2a64](https://linux-hardware.org/?probe=1f10cd2a64) | Dec 22, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [4a1e660e7d](https://linux-hardware.org/?probe=4a1e660e7d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | Notebook    | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [3d866a7ec8](https://linux-hardware.org/?probe=3d866a7ec8) | Dec 19, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [17618a8281](https://linux-hardware.org/?probe=17618a8281) | Dec 18, 2022 |
| HP            | 8054                        | Desktop     | [98d0f316b3](https://linux-hardware.org/?probe=98d0f316b3) | Dec 18, 2022 |
| MSI           | MS-7360                     | Desktop     | [2f5a9baf11](https://linux-hardware.org/?probe=2f5a9baf11) | Dec 18, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [5a05dc8c43](https://linux-hardware.org/?probe=5a05dc8c43) | Dec 17, 2022 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [8b97211b80](https://linux-hardware.org/?probe=8b97211b80) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [c22c7dfa5c](https://linux-hardware.org/?probe=c22c7dfa5c) | Dec 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [2a7d6d1541](https://linux-hardware.org/?probe=2a7d6d1541) | Dec 08, 2022 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [769fed352d](https://linux-hardware.org/?probe=769fed352d) | Dec 06, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eeb0795100](https://linux-hardware.org/?probe=eeb0795100) | Dec 05, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [81576caeb1](https://linux-hardware.org/?probe=81576caeb1) | Dec 04, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [601575b385](https://linux-hardware.org/?probe=601575b385) | Dec 03, 2022 |
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
| ASRock        | Z370 Pro4                   | Desktop     | [cd2e9dd7af](https://linux-hardware.org/?probe=cd2e9dd7af) | Oct 23, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [5962a98f24](https://linux-hardware.org/?probe=5962a98f24) | Oct 23, 2022 |
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
| ASRock        | Z370 Pro4                   | Desktop     | [a0bf764d45](https://linux-hardware.org/?probe=a0bf764d45) | Oct 25, 2021 |
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
| Ubuntu 20.04       | 218       | 15.58%  |
| Ubuntu 18.04       | 113       | 8.08%   |
| Ubuntu 22.04       | 91        | 6.5%    |
| OpenMandriva 4.3   | 60        | 4.29%   |
| OpenMandriva 23.03 | 58        | 4.15%   |
| OpenMandriva 4.2   | 36        | 2.57%   |
| Debian 11          | 33        | 2.36%   |
| Arch Rolling       | 28        | 2%      |
| OpenMandriva 4.90  | 27        | 1.93%   |
| Xubuntu 20.04      | 26        | 1.86%   |
| OpenMandriva 23.01 | 26        | 1.86%   |
| Zorin 16           | 22        | 1.57%   |
| Pop!_OS 22.04      | 22        | 1.57%   |
| Arch               | 21        | 1.5%    |
| BlackPanther 18.1  | 18        | 1.29%   |
| Xubuntu 18.04      | 17        | 1.22%   |
| Ubuntu 21.04       | 17        | 1.22%   |
| Ubuntu 20.10       | 17        | 1.22%   |
| OpenMandriva 23.08 | 16        | 1.14%   |
| Manjaro            | 15        | 1.07%   |
| Ubuntu 19.04       | 14        | 1%      |
| Ubuntu 21.10       | 13        | 0.93%   |
| Linux Mint 21.1    | 13        | 0.93%   |
| Fedora 37          | 13        | 0.93%   |
| Linux Mint 19.3    | 12        | 0.86%   |
| ArcoLinux Rolling  | 12        | 0.86%   |
| OpenMandriva 4.50  | 11        | 0.79%   |
| Zorin 15           | 10        | 0.71%   |
| Fedora 38          | 10        | 0.71%   |
| Fedora 36          | 10        | 0.71%   |
| Ubuntu 22.10       | 9         | 0.64%   |
| Ubuntu 19.10       | 9         | 0.64%   |
| KDE neon 20.04     | 9         | 0.64%   |
| Fedora 35          | 9         | 0.64%   |
| Fedora 34          | 9         | 0.64%   |
| Fedora 32          | 9         | 0.64%   |
| Ubuntu 23.04       | 8         | 0.57%   |
| Pop!_OS 21.04      | 8         | 0.57%   |
| Pop!_OS 20.10      | 8         | 0.57%   |
| Linux Mint 20.3    | 8         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 498       | 37.58%  |
| OpenMandriva  | 233       | 17.58%  |
| Fedora        | 66        | 4.98%   |
| Linux Mint    | 59        | 4.45%   |
| Debian        | 57        | 4.3%    |
| Arch          | 49        | 3.7%    |
| Pop!_OS       | 47        | 3.55%   |
| Xubuntu       | 44        | 3.32%   |
| Zorin         | 33        | 2.49%   |
| Manjaro       | 26        | 1.96%   |
| BlackPanther  | 18        | 1.36%   |
| Kubuntu       | 13        | 0.98%   |
| Kali          | 13        | 0.98%   |
| Gentoo        | 13        | 0.98%   |
| ArcoLinux     | 12        | 0.91%   |
| ROSA          | 11        | 0.83%   |
| openSUSE      | 10        | 0.75%   |
| KDE neon      | 10        | 0.75%   |
| Ubuntu Unity  | 9         | 0.68%   |
| Slackware     | 7         | 0.53%   |
| Lubuntu       | 7         | 0.53%   |
| Ubuntu MATE   | 6         | 0.45%   |
| Ubuntu Budgie | 6         | 0.45%   |
| Elementary    | 6         | 0.45%   |
| SteamOS       | 5         | 0.38%   |
| CentOS        | 5         | 0.38%   |
| antiX         | 5         | 0.38%   |
| LMDE          | 4         | 0.3%    |
| Garuda Linux  | 4         | 0.3%    |
| Endless       | 4         | 0.3%    |
| RHEL          | 3         | 0.23%   |
| Peppermint    | 3         | 0.23%   |
| Guix          | 3         | 0.23%   |
| Deepin        | 3         | 0.23%   |
| Raspbian      | 2         | 0.15%   |
| Parrot        | 2         | 0.15%   |
| Nobara        | 2         | 0.15%   |
| NixOS         | 2         | 0.15%   |
| EndeavourOS   | 2         | 0.15%   |
| Clear Linux   | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 57        | 3.68%   |
| 6.2.6-desktop-1omv2390   | 54        | 3.48%   |
| 5.10.14-desktop-1omv4002 | 34        | 2.19%   |
| 6.1.1-desktop-1omv2290   | 26        | 1.68%   |
| 5.4.0-42-generic         | 24        | 1.55%   |
| 5.4.0-52-generic         | 18        | 1.16%   |
| 5.4.0-58-generic         | 17        | 1.1%    |
| 4.18.16-desktop-1bP      | 15        | 0.97%   |
| 6.4.11-desktop-1omv2390  | 14        | 0.9%    |
| 6.0.2-desktop-1omv4090   | 14        | 0.9%    |
| 5.4.0-40-generic         | 13        | 0.84%   |
| 5.15.0-56-generic        | 13        | 0.84%   |
| 5.4.0-33-generic         | 12        | 0.77%   |
| 5.4.0-48-generic         | 10        | 0.65%   |
| 5.4.0-37-generic         | 10        | 0.65%   |
| 5.16.13-desktop-1omv4003 | 10        | 0.65%   |
| 5.8.0-48-generic         | 9         | 0.58%   |
| 6.2.6-76060206-generic   | 8         | 0.52%   |
| 6.2.0-33-generic         | 8         | 0.52%   |
| 5.8.0-43-generic         | 8         | 0.52%   |
| 5.4.0-54-generic         | 8         | 0.52%   |
| 5.4.0-31-generic         | 8         | 0.52%   |
| 5.11.0-38-generic        | 8         | 0.52%   |
| 5.8.0-50-generic         | 7         | 0.45%   |
| 5.4.0-29-generic         | 7         | 0.45%   |
| 5.19.0-38-generic        | 7         | 0.45%   |
| 5.15.0-58-generic        | 7         | 0.45%   |
| 5.15.0-52-generic        | 7         | 0.45%   |
| 5.13.0-40-generic        | 7         | 0.45%   |
| 5.13.0-30-generic        | 7         | 0.45%   |
| 5.12.4-desktop-1omv4050  | 7         | 0.45%   |
| 5.11.0-37-generic        | 7         | 0.45%   |
| 5.11.0-27-generic        | 7         | 0.45%   |
| 5.0.0-37-generic         | 7         | 0.45%   |
| 5.0.0-29-generic         | 7         | 0.45%   |
| 6.3.5-desktop-3omv2390   | 6         | 0.39%   |
| 5.8.0-59-generic         | 6         | 0.39%   |
| 5.4.0-51-generic         | 6         | 0.39%   |
| 5.4.0-47-generic         | 6         | 0.39%   |
| 5.4.0-39-generic         | 6         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 224       | 15.34%  |
| 5.15.0  | 102       | 6.99%   |
| 4.15.0  | 88        | 6.03%   |
| 5.8.0   | 72        | 4.93%   |
| 6.2.6   | 62        | 4.25%   |
| 5.11.0  | 61        | 4.18%   |
| 5.16.7  | 58        | 3.97%   |
| 5.13.0  | 58        | 3.97%   |
| 5.19.0  | 43        | 2.95%   |
| 5.3.0   | 41        | 2.81%   |
| 5.10.0  | 39        | 2.67%   |
| 5.0.0   | 36        | 2.47%   |
| 5.10.14 | 35        | 2.4%    |
| 6.2.0   | 29        | 1.99%   |
| 6.1.1   | 28        | 1.92%   |
| 6.4.11  | 17        | 1.16%   |
| 6.0.2   | 15        | 1.03%   |
| 4.18.16 | 15        | 1.03%   |
| 4.18.0  | 14        | 0.96%   |
| 6.1.0   | 13        | 0.89%   |
| 5.16.13 | 11        | 0.75%   |
| 6.5.0   | 9         | 0.62%   |
| 5.12.4  | 8         | 0.55%   |
| 4.4.0   | 8         | 0.55%   |
| 6.3.5   | 7         | 0.48%   |
| 5.14.0  | 7         | 0.48%   |
| 4.19.0  | 7         | 0.48%   |
| 6.0.12  | 6         | 0.41%   |
| 6.0.0   | 6         | 0.41%   |
| 5.19.1  | 6         | 0.41%   |
| 6.4.12  | 5         | 0.34%   |
| 6.4.0   | 5         | 0.34%   |
| 6.0.8   | 5         | 0.34%   |
| 6.0.6   | 5         | 0.34%   |
| 5.18.12 | 5         | 0.34%   |
| 5.9.0   | 4         | 0.27%   |
| 5.6.14  | 4         | 0.27%   |
| 5.3.18  | 4         | 0.27%   |
| 5.19.11 | 4         | 0.27%   |
| 5.18.0  | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 232       | 16.13%  |
| 5.15    | 125       | 8.69%   |
| 6.2     | 106       | 7.37%   |
| 5.10    | 96        | 6.68%   |
| 4.15    | 88        | 6.12%   |
| 5.8     | 83        | 5.77%   |
| 5.16    | 78        | 5.42%   |
| 5.13    | 73        | 5.08%   |
| 5.19    | 66        | 4.59%   |
| 5.11    | 66        | 4.59%   |
| 6.1     | 60        | 4.17%   |
| 5.3     | 46        | 3.2%    |
| 6.0     | 42        | 2.92%   |
| 5.0     | 39        | 2.71%   |
| 6.4     | 35        | 2.43%   |
| 4.18    | 29        | 2.02%   |
| 6.5     | 21        | 1.46%   |
| 5.18    | 21        | 1.46%   |
| 6.3     | 19        | 1.32%   |
| 5.14    | 19        | 1.32%   |
| 5.12    | 16        | 1.11%   |
| 5.9     | 12        | 0.83%   |
| 5.6     | 12        | 0.83%   |
| 5.17    | 11        | 0.76%   |
| 4.19    | 10        | 0.7%    |
| 4.9     | 8         | 0.56%   |
| 4.4     | 8         | 0.56%   |
| 5.7     | 6         | 0.42%   |
| 5.5     | 4         | 0.28%   |
| 5.2     | 3         | 0.21%   |
| 3.10    | 2         | 0.14%   |
| 4.8     | 1         | 0.07%   |
| 3.18    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1240      | 95.83%  |
| i686        | 38        | 2.94%   |
| aarch64     | 13        | 1%      |
| armv7l      | 2         | 0.15%   |
| loongarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 583       | 44.07%  |
| KDE5                     | 314       | 23.73%  |
| Unknown                  | 136       | 10.28%  |
| XFCE                     | 97        | 7.33%   |
| X-Cinnamon               | 49        | 3.7%    |
| MATE                     | 22        | 1.66%   |
| LXQt                     | 15        | 1.13%   |
| KDE                      | 15        | 1.13%   |
| Unity                    | 10        | 0.76%   |
| LXDE                     | 10        | 0.76%   |
| Budgie                   | 10        | 0.76%   |
| Cinnamon                 | 9         | 0.68%   |
| sway                     | 8         | 0.6%    |
| Pantheon                 | 6         | 0.45%   |
| KDE4                     | 5         | 0.38%   |
| i3                       | 5         | 0.38%   |
| Deepin                   | 5         | 0.38%   |
| awesome                  | 4         | 0.3%    |
| GNOME Classic            | 3         | 0.23%   |
| XSession                 | 2         | 0.15%   |
| Openbox                  | 2         | 0.15%   |
| icewm                    | 2         | 0.15%   |
| Enlightenment            | 2         | 0.15%   |
| xwmconfig                | 1         | 0.08%   |
| xmonad                   | 1         | 0.08%   |
| qtile                    | 1         | 0.08%   |
| JWM                      | 1         | 0.08%   |
| Hyprland                 | 1         | 0.08%   |
| GNOME Flashback          | 1         | 0.08%   |
| dwm                      | 1         | 0.08%   |
| BunsenLabs               | 1         | 0.08%   |
| /usr/bin/openbox-session | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 967       | 72.82%  |
| Wayland | 244       | 18.37%  |
| Unknown | 83        | 6.25%   |
| Tty     | 34        | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 592       | 44.31%  |
| SDDM    | 307       | 22.98%  |
| GDM3    | 167       | 12.5%   |
| GDM     | 137       | 10.25%  |
| LightDM | 89        | 6.66%   |
| TDM     | 23        | 1.72%   |
| XDM     | 5         | 0.37%   |
| LXDM    | 4         | 0.3%    |
| KDM     | 4         | 0.3%    |
| GREETD  | 4         | 0.3%    |
| NODM    | 2         | 0.15%   |
| SLiM    | 1         | 0.07%   |
| EMPTTY  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ja_JP       | 563       | 42.65%  |
| en_US       | 456       | 34.55%  |
| Unknown     | 137       | 10.38%  |
| zh_CN       | 37        | 2.8%    |
| pt_BR       | 29        | 2.2%    |
| en_GB       | 28        | 2.12%   |
| C           | 14        | 1.06%   |
| fr_FR       | 9         | 0.68%   |
| en_AU       | 5         | 0.38%   |
| ru_RU       | 4         | 0.3%    |
| es_ES       | 4         | 0.3%    |
| en_AG       | 3         | 0.23%   |
| de_DE       | 3         | 0.23%   |
| zh_TW       | 2         | 0.15%   |
| UTF-8       | 2         | 0.15%   |
| sr_RS       | 2         | 0.15%   |
| sk_SK       | 2         | 0.15%   |
| it_IT       | 2         | 0.15%   |
| en_IN       | 2         | 0.15%   |
| tr_TR       | 1         | 0.08%   |
| sv_SE       | 1         | 0.08%   |
| pl_PL       | 1         | 0.08%   |
| nb_NO       | 1         | 0.08%   |
| ja_JP.UTF8  | 1         | 0.08%   |
| ja_JP.utf-8 | 1         | 0.08%   |
| fr_CA       | 1         | 0.08%   |
| fi_FI       | 1         | 0.08%   |
| es_GT       | 1         | 0.08%   |
| en_SG       | 1         | 0.08%   |
| en_PH       | 1         | 0.08%   |
| en_NL       | 1         | 0.08%   |
| en_DK       | 1         | 0.08%   |
| en_CA       | 1         | 0.08%   |
| el_GR       | 1         | 0.08%   |
| af_ZA       | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 690       | 52.51%  |
| EFI  | 624       | 47.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 980       | 73.74%  |
| Overlay | 145       | 10.91%  |
| Btrfs   | 103       | 7.75%   |
| Tmpfs   | 38        | 2.86%   |
| Xfs     | 23        | 1.73%   |
| Unknown | 23        | 1.73%   |
| Zfs     | 9         | 0.68%   |
| F2fs    | 3         | 0.23%   |
| Jfs     | 2         | 0.15%   |
| Ntfs    | 1         | 0.08%   |
| Ext3    | 1         | 0.08%   |
| Ext2    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 630       | 47.26%  |
| GPT     | 567       | 42.54%  |
| MBR     | 136       | 10.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1017      | 76.81%  |
| Yes       | 307       | 23.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 926       | 70.31%  |
| Yes       | 391       | 29.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 180       | 13.94%  |
| Lenovo                               | 131       | 10.15%  |
| ASRock                               | 105       | 8.13%   |
| Dell                                 | 103       | 7.98%   |
| Hewlett-Packard                      | 102       | 7.9%    |
| Toshiba                              | 74        | 5.73%   |
| Gigabyte Technology                  | 72        | 5.58%   |
| MSI                                  | 65        | 5.03%   |
| Fujitsu                              | 55        | 4.26%   |
| NEC Computers                        | 53        | 4.11%   |
| Apple                                | 43        | 3.33%   |
| Intel                                | 30        | 2.32%   |
| MouseComputer                        | 22        | 1.7%    |
| Sony                                 | 21        | 1.63%   |
| Acer                                 | 21        | 1.63%   |
| Panasonic                            | 17        | 1.32%   |
| Unknown                              | 15        | 1.16%   |
| Raspberry Pi Foundation              | 12        | 0.93%   |
| Biostar                              | 10        | 0.77%   |
| HUAWEI                               | 9         | 0.7%    |
| ECS                                  | 9         | 0.7%    |
| Gateway                              | 8         | 0.62%   |
| EPSON DIRECT                         | 8         | 0.62%   |
| Microsoft                            | 7         | 0.54%   |
| Supermicro                           | 6         | 0.46%   |
| Dynabook                             | 5         | 0.39%   |
| Alienware                            | 5         | 0.39%   |
| Valve                                | 4         | 0.31%   |
| Timi                                 | 4         | 0.31%   |
| Shenzhen Meigao Electronic Equipment | 4         | 0.31%   |
| Novastar                             | 4         | 0.31%   |
| MCJ                                  | 4         | 0.31%   |
| Wistron                              | 3         | 0.23%   |
| UNITCOM                              | 3         | 0.23%   |
| Teclast                              | 3         | 0.23%   |
| System76                             | 3         | 0.23%   |
| Shuttle                              | 3         | 0.23%   |
| Samsung Electronics                  | 3         | 0.23%   |
| Pegatron                             | 3         | 0.23%   |
| Notebook                             | 3         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba dynabook T653/46JR                 | 24        | 1.86%   |
| ASUS All Series                            | 16        | 1.24%   |
| Unknown                                    | 15        | 1.16%   |
| RPi Raspberry Pi                           | 6         | 0.46%   |
| Apple MacBookAir9,1                        | 6         | 0.46%   |
| Toshiba dynabook Satellite B552/G          | 5         | 0.39%   |
| HP ProDesk 600 G1 SFF                      | 5         | 0.39%   |
| ASRock B450M Pro4                          | 5         | 0.39%   |
| Valve Jupiter                              | 4         | 0.31%   |
| Novastar KL55                              | 4         | 0.31%   |
| MSI MS-7A40                                | 4         | 0.31%   |
| Lenovo G570 4334                           | 4         | 0.31%   |
| ASRock Z87 Killer                          | 4         | 0.31%   |
| ASRock B450 Pro4                           | 4         | 0.31%   |
| ASRock B450 Gaming-ITX/ac                  | 4         | 0.31%   |
| Apple MacBookPro9,2                        | 4         | 0.31%   |
| Toshiba dynabook REGZA PC D712/T3FWD       | 3         | 0.23%   |
| Supermicro Super Server                    | 3         | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 3         | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 3         | 0.23%   |
| NEC Computers Express5800/S70 [N8100-9021] | 3         | 0.23%   |
| MSI MS-7C95                                | 3         | 0.23%   |
| MSI MS-7C94                                | 3         | 0.23%   |
| Lenovo G550 2958                           | 3         | 0.23%   |
| Intel NUC10i7FNH                           | 3         | 0.23%   |
| Intel NUC10i5FNH                           | 3         | 0.23%   |
| HP Z620 Workstation                        | 3         | 0.23%   |
| ECS G31T-M                                 | 3         | 0.23%   |
| Dell Precision WorkStation T3500           | 3         | 0.23%   |
| Dell OptiPlex 3020                         | 3         | 0.23%   |
| Dell Inspiron 1545                         | 3         | 0.23%   |
| ASUS PRIME H670-PLUS D4                    | 3         | 0.23%   |
| ASUS P7H55-M                               | 3         | 0.23%   |
| ASUS H170-PRO                              | 3         | 0.23%   |
| ASRock Z370 Pro4                           | 3         | 0.23%   |
| ASRock Prime Series                        | 3         | 0.23%   |
| ASRock J5005-ITX                           | 3         | 0.23%   |
| ASRock B460M Pro4                          | 3         | 0.23%   |
| ASRock A300M-STX                           | 3         | 0.23%   |
| Apple MacBookPro15,1                       | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 81        | 6.27%   |
| Toshiba dynabook      | 71        | 5.5%    |
| Dell Inspiron         | 36        | 2.79%   |
| ASUS PRIME            | 26        | 2.01%   |
| ASUS ROG              | 18        | 1.39%   |
| Dell Latitude         | 16        | 1.24%   |
| ASUS TUF              | 16        | 1.24%   |
| ASUS All              | 16        | 1.24%   |
| HP ProBook            | 15        | 1.16%   |
| Acer Aspire           | 15        | 1.16%   |
| Unknown               | 15        | 1.16%   |
| RPi Raspberry         | 12        | 0.93%   |
| HP ProDesk            | 12        | 0.93%   |
| HP Pavilion           | 12        | 0.93%   |
| Dell XPS              | 12        | 0.93%   |
| HP Compaq             | 11        | 0.85%   |
| Dell Vostro           | 10        | 0.77%   |
| Dell OptiPlex         | 9         | 0.7%    |
| ASUS VivoBook         | 9         | 0.7%    |
| ASRock B450           | 9         | 0.7%    |
| HP Laptop             | 8         | 0.62%   |
| EPSON DIRECT Endeavor | 8         | 0.62%   |
| Microsoft Surface     | 7         | 0.54%   |
| Lenovo IdeaPad        | 7         | 0.54%   |
| HP EliteBook          | 7         | 0.54%   |
| Dell Precision        | 7         | 0.54%   |
| Lenovo ThinkCentre    | 6         | 0.46%   |
| Apple MacBookAir9     | 6         | 0.46%   |
| Lenovo Yoga           | 5         | 0.39%   |
| Lenovo ThinkBook      | 5         | 0.39%   |
| HP ENVY               | 5         | 0.39%   |
| Fujitsu PRIMERGY      | 5         | 0.39%   |
| ASUS P8Z77-V          | 5         | 0.39%   |
| ASRock Z87            | 5         | 0.39%   |
| ASRock B450M          | 5         | 0.39%   |
| Apple MacBookPro15    | 5         | 0.39%   |
| Valve Jupiter         | 4         | 0.31%   |
| Novastar KL55         | 4         | 0.31%   |
| MSI MS-7A40           | 4         | 0.31%   |
| Lenovo G570           | 4         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 132       | 10.22%  |
| 2013    | 127       | 9.84%   |
| 2012    | 120       | 9.3%    |
| 2020    | 116       | 8.99%   |
| 2021    | 98        | 7.59%   |
| 2019    | 83        | 6.43%   |
| 2011    | 78        | 6.04%   |
| 2010    | 68        | 5.27%   |
| 2016    | 64        | 4.96%   |
| 2009    | 63        | 4.88%   |
| 2015    | 58        | 4.49%   |
| 2017    | 56        | 4.34%   |
| 2014    | 48        | 3.72%   |
| 2008    | 48        | 3.72%   |
| 2007    | 40        | 3.1%    |
| 2022    | 38        | 2.94%   |
| 2006    | 17        | 1.32%   |
| 2023    | 15        | 1.16%   |
| Unknown | 14        | 1.08%   |
| 2005    | 6         | 0.46%   |
| 2004    | 1         | 0.08%   |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 617       | 47.79%  |
| Desktop        | 557       | 43.14%  |
| All in one     | 28        | 2.17%   |
| Mini pc        | 26        | 2.01%   |
| Tablet         | 17        | 1.32%   |
| Server         | 17        | 1.32%   |
| System on chip | 14        | 1.08%   |
| Convertible    | 14        | 1.08%   |
| Phone          | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1210      | 93.15%  |
| Enabled  | 89        | 6.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1285      | 99.54%  |
| Yes  | 6         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 273       | 20.76%  |
| 3.01-4.0        | 270       | 20.53%  |
| 8.01-16.0       | 242       | 18.4%   |
| 16.01-24.0      | 233       | 17.72%  |
| 32.01-64.0      | 137       | 10.42%  |
| 1.01-2.0        | 51        | 3.88%   |
| 64.01-256.0     | 45        | 3.42%   |
| 24.01-32.0      | 35        | 2.66%   |
| 2.01-3.0        | 19        | 1.44%   |
| 0.51-1.0        | 7         | 0.53%   |
| More than 256.0 | 2         | 0.15%   |
| 0.01-0.5        | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 587       | 40.91%  |
| 2.01-3.0   | 311       | 21.67%  |
| 3.01-4.0   | 160       | 11.15%  |
| 4.01-8.0   | 159       | 11.08%  |
| 0.51-1.0   | 128       | 8.92%   |
| 8.01-16.0  | 52        | 3.62%   |
| 0.01-0.5   | 19        | 1.32%   |
| 16.01-24.0 | 13        | 0.91%   |
| 24.01-32.0 | 5         | 0.35%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 785       | 58.98%  |
| 2      | 338       | 25.39%  |
| 3      | 105       | 7.89%   |
| 4      | 51        | 3.83%   |
| 5      | 22        | 1.65%   |
| 0      | 12        | 0.9%    |
| 6      | 8         | 0.6%    |
| 7      | 6         | 0.45%   |
| 8      | 2         | 0.15%   |
| 11     | 1         | 0.08%   |
| 9      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 682       | 52.34%  |
| Yes       | 621       | 47.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1131      | 87.54%  |
| No        | 161       | 12.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 891       | 68.7%   |
| No        | 406       | 31.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 656       | 50.04%  |
| Yes       | 655       | 49.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Japan   | 1291      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Tokyo       | 160       | 11.49%  |
| Yokohama    | 74        | 5.31%   |
| Osaka       | 57        | 4.09%   |
| Nagoya      | 33        | 2.37%   |
| Shinjuku    | 31        | 2.23%   |
| Minato-ku   | 31        | 2.23%   |
| Saitama     | 21        | 1.51%   |
| Chiyoda     | 21        | 1.51%   |
| Niigata     | 19        | 1.36%   |
| Shibuya     | 17        | 1.22%   |
| Setagaya-ku | 16        | 1.15%   |
| Sapporo     | 16        | 1.15%   |
| Kyoto       | 15        | 1.08%   |
| Kobe        | 14        | 1.01%   |
| Tsukuba     | 13        | 0.93%   |
| Honcho      | 13        | 0.93%   |
| Fukuoka     | 12        | 0.86%   |
| Takamatsu   | 11        | 0.79%   |
| Shinagawa   | 9         | 0.65%   |
| Nakano      | 9         | 0.65%   |
| Ichikawa    | 9         | 0.65%   |
| Chiyoda-ku  | 9         | 0.65%   |
| Adachi      | 9         | 0.65%   |
| Nagasaki    | 8         | 0.57%   |
| Morioka     | 8         | 0.57%   |
| Miyazaki    | 8         | 0.57%   |
| Mito        | 8         | 0.57%   |
| Minatomirai | 8         | 0.57%   |
| Kumamoto    | 8         | 0.57%   |
| Kagoshima   | 8         | 0.57%   |
| Utsunomiya  | 7         | 0.5%    |
| Ōtsu       | 7         | 0.5%    |
| Okayama     | 7         | 0.5%    |
| Meguro-ku   | 7         | 0.5%    |
| Matsudo     | 7         | 0.5%    |
| Koto        | 7         | 0.5%    |
| Kitakyushu  | 7         | 0.5%    |
| Kawasaki    | 7         | 0.5%    |
| Kanazawa    | 7         | 0.5%    |
| Hiroshima   | 7         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 272       | 414    | 14.24%  |
| Seagate                   | 241       | 365    | 12.62%  |
| Samsung Electronics       | 199       | 281    | 10.42%  |
| Toshiba                   | 168       | 204    | 8.8%    |
| Crucial                   | 102       | 135    | 5.34%   |
| Hitachi                   | 97        | 123    | 5.08%   |
| SanDisk                   | 94        | 126    | 4.92%   |
| Unknown                   | 83        | 103    | 4.35%   |
| Intel                     | 60        | 82     | 3.14%   |
| A-DATA Technology         | 45        | 55     | 2.36%   |
| Kingston                  | 39        | 44     | 2.04%   |
| SPCC                      | 34        | 44     | 1.78%   |
| Apple                     | 31        | 36     | 1.62%   |
| SK hynix                  | 28        | 29     | 1.47%   |
| Micron Technology         | 28        | 43     | 1.47%   |
| HGST                      | 22        | 25     | 1.15%   |
| Transcend                 | 21        | 27     | 1.1%    |
| Phison                    | 16        | 21     | 0.84%   |
| Micron/Crucial Technology | 16        | 21     | 0.84%   |
| Unknown                   | 16        | 18     | 0.84%   |
| China                     | 15        | 21     | 0.79%   |
| Silicon Motion            | 14        | 21     | 0.73%   |
| Plextor                   | 12        | 16     | 0.63%   |
| KIOXIA                    | 12        | 15     | 0.63%   |
| Fujitsu                   | 11        | 12     | 0.58%   |
| KIOXIA-EXCERIA            | 10        | 12     | 0.52%   |
| Teclast                   | 9         | 9      | 0.47%   |
| SUNEAST                   | 9         | 10     | 0.47%   |
| Phison Electronics        | 9         | 14     | 0.47%   |
| OCZ                       | 8         | 8      | 0.42%   |
| JMicron Technology        | 7         | 7      | 0.37%   |
| Dogfish                   | 7         | 9      | 0.37%   |
| Zheino                    | 6         | 7      | 0.31%   |
| Patriot                   | 6         | 7      | 0.31%   |
| Lexar                     | 6         | 8      | 0.31%   |
| Hewlett-Packard           | 6         | 19     | 0.31%   |
| Green House               | 6         | 9      | 0.31%   |
| Apacer                    | 6         | 9      | 0.31%   |
| Team                      | 5         | 6      | 0.26%   |
| BUFFALO                   | 5         | 6      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD075 752GB                          | 25        | 1.2%    |
| Crucial CT500MX500SSD1 500GB                      | 21        | 1.01%   |
| Unknown MMC Card  64GB                            | 20        | 0.96%   |
| Toshiba DT01ACA100 1TB                            | 19        | 0.91%   |
| Crucial CT240BX500SSD1 240GB                      | 19        | 0.91%   |
| Unknown                                           | 16        | 0.77%   |
| Unknown MMC Card  32GB                            | 12        | 0.58%   |
| Toshiba MQ01ABD100 1TB                            | 12        | 0.58%   |
| SPCC Solid State Disk 256GB                       | 10        | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB                    | 10        | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 10        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 9         | 0.43%   |
| Toshiba DT01ACA200 2TB                            | 9         | 0.43%   |
| Seagate ST9500325AS 500GB                         | 9         | 0.43%   |
| Seagate ST3500418AS 500GB                         | 9         | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB                    | 8         | 0.38%   |
| Seagate ST1000DM010-2EP102 1TB                    | 8         | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB                    | 8         | 0.38%   |
| Crucial CT525MX300SSD1 528GB                      | 8         | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                       | 8         | 0.38%   |
| WDC WD20EZRX-00DC0B0 2TB                          | 7         | 0.34%   |
| Unknown MMC Card  128GB                           | 7         | 0.34%   |
| Toshiba MQ01ABF050 500GB                          | 7         | 0.34%   |
| Seagate ST500DM002-1BD142 500GB                   | 7         | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB                    | 7         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB                    | 7         | 0.34%   |
| Samsung SSD 860 EVO 500GB                         | 7         | 0.34%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB             | 7         | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                  | 7         | 0.34%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                  | 6         | 0.29%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 6         | 0.29%   |
| Toshiba MQ01ABF032 320GB                          | 6         | 0.29%   |
| SPCC Solid State Disk 240GB                       | 6         | 0.29%   |
| Seagate ST31000528AS 1TB                          | 6         | 0.29%   |
| Seagate ST2000DM006-2DM164 2TB                    | 6         | 0.29%   |
| Seagate ST2000DM005-2CW102 2TB                    | 6         | 0.29%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 0.29%   |
| Seagate Expansion 1TB                             | 6         | 0.29%   |
| SanDisk NVMe SSD Drive 1TB                        | 6         | 0.29%   |
| Samsung SSD 860 EVO 250GB                         | 6         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 235       | 355    | 30.6%   |
| WDC                 | 219       | 325    | 28.52%  |
| Toshiba             | 134       | 158    | 17.45%  |
| Hitachi             | 95        | 121    | 12.37%  |
| Samsung Electronics | 23        | 28     | 2.99%   |
| HGST                | 22        | 25     | 2.86%   |
| Fujitsu             | 11        | 12     | 1.43%   |
| Unknown             | 5         | 6      | 0.65%   |
| Maxtor              | 4         | 6      | 0.52%   |
| Apple               | 4         | 5      | 0.52%   |
| Hewlett-Packard     | 3         | 9      | 0.39%   |
| SSK                 | 2         | 2      | 0.26%   |
| QC-FT-D             | 2         | 2      | 0.26%   |
| MARVELL             | 2         | 4      | 0.26%   |
| External            | 2         | 2      | 0.26%   |
| USB3.0              | 1         | 1      | 0.13%   |
| StoreJet            | 1         | 1      | 0.13%   |
| Quantum             | 1         | 1      | 0.13%   |
| MARSHAL             | 1         | 2      | 0.13%   |
| KESU                | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 95        | 125    | 14.12%  |
| Samsung Electronics | 93        | 131    | 13.82%  |
| SanDisk             | 55        | 73     | 8.17%   |
| A-DATA Technology   | 41        | 50     | 6.09%   |
| WDC                 | 37        | 48     | 5.5%    |
| Intel               | 32        | 37     | 4.75%   |
| SPCC                | 28        | 37     | 4.16%   |
| Kingston            | 28        | 32     | 4.16%   |
| Toshiba             | 22        | 27     | 3.27%   |
| Transcend           | 19        | 25     | 2.82%   |
| China               | 15        | 21     | 2.23%   |
| Unknown             | 13        | 14     | 1.93%   |
| Plextor             | 12        | 16     | 1.78%   |
| Micron Technology   | 11        | 15     | 1.63%   |
| Apple               | 11        | 13     | 1.63%   |
| SUNEAST             | 9         | 10     | 1.34%   |
| OCZ                 | 8         | 8      | 1.19%   |
| Teclast             | 7         | 7      | 1.04%   |
| Dogfish             | 7         | 9      | 1.04%   |
| Green House         | 6         | 9      | 0.89%   |
| Apacer              | 6         | 9      | 0.89%   |
| Unknown             | 5         | 5      | 0.74%   |
| Team                | 5         | 6      | 0.74%   |
| Seagate             | 5         | 7      | 0.74%   |
| Lexar               | 5         | 7      | 0.74%   |
| KIOXIA-EXCERIA      | 5         | 6      | 0.74%   |
| BUFFALO             | 5         | 6      | 0.74%   |
| PNY                 | 4         | 4      | 0.59%   |
| Patriot             | 4         | 5      | 0.59%   |
| KLEVV               | 4         | 10     | 0.59%   |
| Zheino              | 3         | 3      | 0.45%   |
| SK hynix            | 3         | 3      | 0.45%   |
| SABRENT             | 3         | 5      | 0.45%   |
| Netac               | 3         | 4      | 0.45%   |
| Kingmax             | 3         | 3      | 0.45%   |
| Hanye               | 3         | 3      | 0.45%   |
| CFD                 | 3         | 3      | 0.45%   |
| Biostar             | 3         | 3      | 0.45%   |
| ASMT                | 3         | 4      | 0.45%   |
| TCSUNBOW            | 2         | 2      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 645       | 1066   | 38.51%  |
| SSD     | 576       | 863    | 34.39%  |
| NVMe    | 358       | 526    | 21.37%  |
| MMC     | 66        | 83     | 3.94%   |
| Unknown | 30        | 46     | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1001      | 1867   | 66.56%  |
| NVMe | 356       | 519    | 23.67%  |
| SAS  | 81        | 115    | 5.39%   |
| MMC  | 66        | 83     | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 759       | 1187   | 59.81%  |
| 0.51-1.0   | 289       | 403    | 22.77%  |
| 1.01-2.0   | 122       | 170    | 9.61%   |
| 3.01-4.0   | 39        | 65     | 3.07%   |
| 4.01-10.0  | 29        | 60     | 2.29%   |
| 2.01-3.0   | 27        | 39     | 2.13%   |
| 10.01-20.0 | 4         | 5      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 413       | 30.15%  |
| 251-500        | 236       | 17.23%  |
| 501-1000       | 173       | 12.63%  |
| 1-20           | 115       | 8.39%   |
| 51-100         | 102       | 7.45%   |
| 1001-2000      | 90        | 6.57%   |
| More than 3000 | 73        | 5.33%   |
| 21-50          | 60        | 4.38%   |
| Unknown        | 56        | 4.09%   |
| 2001-3000      | 52        | 3.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 623       | 44.09%  |
| 21-50          | 232       | 16.42%  |
| 101-250        | 140       | 9.91%   |
| 51-100         | 129       | 9.13%   |
| 251-500        | 84        | 5.94%   |
| 501-1000       | 74        | 5.24%   |
| Unknown        | 56        | 3.96%   |
| 1001-2000      | 37        | 2.62%   |
| More than 3000 | 25        | 1.77%   |
| 2001-3000      | 13        | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB           | 24        | 24     | 18.32%  |
| Seagate ST9500325AS 500GB          | 6         | 7      | 4.58%   |
| WDC WD10EADS-22M2B0 1TB            | 5         | 5      | 3.82%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 5         | 5      | 3.82%   |
| Seagate ST9160314AS 160GB          | 2         | 2      | 1.53%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 1.53%   |
| Hitachi HDS721010CLA332 1TB        | 2         | 2      | 1.53%   |
| WDC WD5000LPLX-66ZNTT0 500GB       | 1         | 1      | 0.76%   |
| WDC WD5000BEVT-55A0RT0 500GB       | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1         | 1      | 0.76%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1         | 1      | 0.76%   |
| WDC WD3200LPCX-24C6HT0 320GB       | 1         | 1      | 0.76%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 0.76%   |
| WDC WD30EZRX-19D8PB0 3TB           | 1         | 1      | 0.76%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1         | 2      | 0.76%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1         | 1      | 0.76%   |
| WDC WD25EZRX-00MMMB0 2TB           | 1         | 1      | 0.76%   |
| WDC WD1600BEVS-26RST0 160GB        | 1         | 1      | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 1      | 0.76%   |
| WDC WD10EALX-009BA0 1TB            | 1         | 1      | 0.76%   |
| WDC WD10EADS-00L5B1 1TB            | 1         | 1      | 0.76%   |
| WDC WD10EACS-00D6B0 1TB            | 1         | 2      | 0.76%   |
| Transcend TS240GSSD220S 240GB      | 1         | 1      | 0.76%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 0.76%   |
| Toshiba MK5055GSX 500GB            | 1         | 1      | 0.76%   |
| Toshiba MK2555GSX 250GB            | 1         | 1      | 0.76%   |
| Toshiba MK2552GSX 250GB            | 1         | 1      | 0.76%   |
| Toshiba MK1652GSX 160GB            | 1         | 1      | 0.76%   |
| Toshiba MK1255GSX H 120GB          | 1         | 1      | 0.76%   |
| Teclast 240GB SSD                  | 1         | 1      | 0.76%   |
| Teclast 128GB SSD                  | 1         | 1      | 0.76%   |
| SSSTC CL1-4D128 128GB              | 1         | 1      | 0.76%   |
| SPCC Solid State DiskB28 128GB     | 1         | 1      | 0.76%   |
| SPCC Solid State Disk 512GB        | 1         | 2      | 0.76%   |
| Seagate ST9320320AS 320GB          | 1         | 1      | 0.76%   |
| Seagate ST9120817AS 120GB          | 1         | 1      | 0.76%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 0.76%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 0.76%   |
| Seagate ST3500418ASQ 500GB         | 1         | 1      | 0.76%   |
| Seagate ST3500418AS 500GB          | 1         | 2      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 30        | 30     | 23.26%  |
| Seagate             | 30        | 34     | 23.26%  |
| WDC                 | 20        | 22     | 15.5%   |
| Hitachi             | 13        | 15     | 10.08%  |
| SanDisk             | 7         | 8      | 5.43%   |
| Samsung Electronics | 4         | 5      | 3.1%    |
| Intel               | 3         | 3      | 2.33%   |
| A-DATA Technology   | 3         | 3      | 2.33%   |
| Teclast             | 2         | 2      | 1.55%   |
| SPCC                | 2         | 3      | 1.55%   |
| HGST                | 2         | 2      | 1.55%   |
| Crucial             | 2         | 4      | 1.55%   |
| Transcend           | 1         | 1      | 0.78%   |
| SSSTC               | 1         | 1      | 0.78%   |
| Netac               | 1         | 1      | 0.78%   |
| Micron Technology   | 1         | 1      | 0.78%   |
| MARSHAL             | 1         | 1      | 0.78%   |
| LITEON              | 1         | 3      | 0.78%   |
| Lite-On             | 1         | 1      | 0.78%   |
| Kingston            | 1         | 1      | 0.78%   |
| Corsair             | 1         | 1      | 0.78%   |
| China               | 1         | 1      | 0.78%   |
| C300-CTF            | 1         | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 30        | 30     | 30.61%  |
| Seagate             | 30        | 34     | 30.61%  |
| WDC                 | 20        | 22     | 20.41%  |
| Hitachi             | 13        | 15     | 13.27%  |
| Samsung Electronics | 2         | 3      | 2.04%   |
| HGST                | 2         | 2      | 2.04%   |
| MARSHAL             | 1         | 1      | 1.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 91        | 107    | 74.59%  |
| SSD  | 30        | 36     | 24.59%  |
| NVMe | 1         | 1      | 0.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 746       | 1541   | 53.79%  |
| Works    | 524       | 898    | 37.78%  |
| Malfunc  | 116       | 144    | 8.36%   |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 894       | 54.85%  |
| AMD                              | 226       | 13.87%  |
| Samsung Electronics              | 103       | 6.32%   |
| SanDisk                          | 60        | 3.68%   |
| ASMedia Technology               | 43        | 2.64%   |
| Phison Electronics               | 31        | 1.9%    |
| SK hynix                         | 26        | 1.6%    |
| Marvell Technology Group         | 24        | 1.47%   |
| Silicon Motion                   | 23        | 1.41%   |
| Micron/Crucial Technology        | 23        | 1.41%   |
| JMicron Technology               | 22        | 1.35%   |
| Micron Technology                | 18        | 1.1%    |
| KIOXIA                           | 18        | 1.1%    |
| Apple                            | 16        | 0.98%   |
| Nvidia                           | 14        | 0.86%   |
| Kingston Technology Company      | 13        | 0.8%    |
| Toshiba America Info Systems     | 12        | 0.74%   |
| VIA Technologies                 | 10        | 0.61%   |
| Broadcom / LSI                   | 10        | 0.61%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.43%   |
| ADATA Technology                 | 7         | 0.43%   |
| Yangtze Memory Technologies      | 3         | 0.18%   |
| Solid State Storage Technology   | 3         | 0.18%   |
| Seagate Technology               | 3         | 0.18%   |
| Realtek Semiconductor            | 3         | 0.18%   |
| LSI Logic / Symbios Logic        | 3         | 0.18%   |
| Adaptec                          | 3         | 0.18%   |
| Silicon Image                    | 2         | 0.12%   |
| HighPoint Technologies           | 2         | 0.12%   |
| ULi Electronics                  | 1         | 0.06%   |
| Solidigm                         | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Promise Technology               | 1         | 0.06%   |
| Loongson Technology              | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| Beijing Starblaze Technology     | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 140       | 7.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 95        | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 66        | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 52        | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 49        | 2.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 44        | 2.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 38        | 2%      |
| AMD 400 Series Chipset SATA Controller                                         | 38        | 2%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 35        | 1.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 31        | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 31        | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 30        | 1.58%   |
| AMD 500 Series Chipset SATA Controller                                         | 29        | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 27        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 24        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 23        | 1.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 22        | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 22        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                          | 21        | 1.11%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 20        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 20        | 1.05%   |
| Intel SATA Controller [RAID mode]                                              | 19        | 1%      |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 17        | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 16        | 0.84%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 16        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 15        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 15        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 15        | 0.79%   |
| Apple ANS2 NVMe Controller                                                     | 15        | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                             | 14        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 14        | 0.74%   |
| Intel SSD 660P Series                                                          | 13        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 13        | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 13        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 947       | 58.86%  |
| NVMe | 357       | 22.19%  |
| IDE  | 209       | 12.99%  |
| RAID | 81        | 5.03%   |
| SAS  | 8         | 0.5%    |
| SCSI | 7         | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1000      | 77.46%  |
| AMD      | 275       | 21.3%   |
| ARM      | 14        | 1.08%   |
| Qualcomm | 1         | 0.08%   |
| Loongson | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz         | 24        | 1.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 14        | 1.08%   |
| AMD Ryzen 5 3600 6-Core Processor       | 14        | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 12        | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 11        | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 11        | 0.85%   |
| ARM Processor                           | 11        | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 0.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 9         | 0.69%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 9         | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 9         | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 8         | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 0.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 8         | 0.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 0.62%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 8         | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 8         | 0.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 8         | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 8         | 0.62%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 8         | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 7         | 0.54%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 7         | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 7         | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 0.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 6         | 0.46%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 0.46%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 6         | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 6         | 0.46%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 6         | 0.46%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 6         | 0.46%   |
| Intel Core i3-1000NG4 CPU @ 1.10GHz     | 6         | 0.46%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 6         | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 6         | 0.46%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 6         | 0.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 5         | 0.39%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 5         | 0.39%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 5         | 0.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 5         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 281       | 21.73%  |
| Intel Core i7           | 222       | 17.17%  |
| Intel Celeron           | 104       | 8.04%   |
| Intel Core i3           | 88        | 6.81%   |
| Other                   | 78        | 6.03%   |
| Intel Core 2 Duo        | 69        | 5.34%   |
| AMD Ryzen 7             | 67        | 5.18%   |
| AMD Ryzen 5             | 65        | 5.03%   |
| Intel Xeon              | 41        | 3.17%   |
| Intel Atom              | 25        | 1.93%   |
| Intel Pentium           | 21        | 1.62%   |
| Intel Core 2            | 18        | 1.39%   |
| AMD Ryzen 9             | 17        | 1.31%   |
| Intel Core 2 Quad       | 16        | 1.24%   |
| Intel Core i9           | 13        | 1.01%   |
| AMD Ryzen 3             | 13        | 1.01%   |
| AMD Athlon              | 13        | 1.01%   |
| AMD A10                 | 9         | 0.7%    |
| Intel Pentium Dual-Core | 7         | 0.54%   |
| AMD Phenom II X4        | 6         | 0.46%   |
| AMD FX                  | 6         | 0.46%   |
| AMD Athlon 64 X2        | 6         | 0.46%   |
| AMD A8                  | 6         | 0.46%   |
| AMD A6                  | 6         | 0.46%   |
| Intel Pentium 4         | 5         | 0.39%   |
| Intel Celeron M         | 5         | 0.39%   |
| AMD Ryzen 7 PRO         | 5         | 0.39%   |
| AMD E2                  | 5         | 0.39%   |
| Intel Pentium Gold      | 4         | 0.31%   |
| Intel Celeron Dual-Core | 4         | 0.31%   |
| Intel Pentium Silver    | 3         | 0.23%   |
| Intel Genuine           | 3         | 0.23%   |
| AMD Sempron             | 3         | 0.23%   |
| AMD Ryzen 5 PRO         | 3         | 0.23%   |
| AMD A4                  | 3         | 0.23%   |
| Intel Pentium M         | 2         | 0.15%   |
| Intel Core m3           | 2         | 0.15%   |
| Intel Core M            | 2         | 0.15%   |
| Intel Core 2 Extreme    | 2         | 0.15%   |
| ARM BCM                 | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 557       | 43.04%  |
| 4      | 403       | 31.14%  |
| 6      | 129       | 9.97%   |
| 8      | 106       | 8.19%   |
| 1      | 38        | 2.94%   |
| 16     | 17        | 1.31%   |
| 12     | 13        | 1%      |
| 14     | 11        | 0.85%   |
| 10     | 9         | 0.7%    |
| 3      | 4         | 0.31%   |
| 24     | 3         | 0.23%   |
| 20     | 2         | 0.15%   |
| 56     | 1         | 0.08%   |
| 32     | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1279      | 99.07%  |
| 2      | 11        | 0.85%   |
| 3      | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 835       | 64.58%  |
| 1      | 457       | 35.34%  |
| 8      | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1251      | 96.75%  |
| Unknown        | 24        | 1.86%   |
| 32-bit         | 18        | 1.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 382       | 28.55%  |
| 0x206a7    | 90        | 6.73%   |
| 0x306a9    | 89        | 6.65%   |
| 0x1067a    | 58        | 4.33%   |
| 0x306c3    | 56        | 4.19%   |
| 0x906ea    | 27        | 2.02%   |
| 0x08701021 | 25        | 1.87%   |
| 0x806ec    | 24        | 1.79%   |
| 0x20655    | 24        | 1.79%   |
| 0x506e3    | 21        | 1.57%   |
| 0x306d4    | 21        | 1.57%   |
| 0x806ea    | 17        | 1.27%   |
| 0x0a50000c | 16        | 1.2%    |
| 0x906e9    | 15        | 1.12%   |
| 0x806e9    | 15        | 1.12%   |
| 0x40651    | 15        | 1.12%   |
| 0x10676    | 14        | 1.05%   |
| 0x806c1    | 13        | 0.97%   |
| 0x406e3    | 13        | 0.97%   |
| 0x406c4    | 13        | 0.97%   |
| 0x906ed    | 12        | 0.9%    |
| 0xa0652    | 11        | 0.82%   |
| 0x6f6      | 11        | 0.82%   |
| 0x20652    | 11        | 0.82%   |
| 0x106e5    | 11        | 0.82%   |
| 0x08600106 | 11        | 0.82%   |
| 0x08108109 | 11        | 0.82%   |
| 0x08108102 | 9         | 0.67%   |
| 0x906a3    | 8         | 0.6%    |
| 0x406c3    | 8         | 0.6%    |
| 0x106c2    | 8         | 0.6%    |
| 0x0800820d | 8         | 0.6%    |
| 0x06003106 | 8         | 0.6%    |
| 0x806eb    | 7         | 0.52%   |
| 0x0a50000d | 7         | 0.52%   |
| 0x0810100b | 7         | 0.52%   |
| 0x06001119 | 7         | 0.52%   |
| 0x010000c8 | 7         | 0.52%   |
| 0xa0655    | 6         | 0.45%   |
| 0x6fb      | 6         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 174       | 13.46%  |
| SandyBridge      | 120       | 9.28%   |
| IvyBridge        | 118       | 9.13%   |
| Haswell          | 118       | 9.13%   |
| Penryn           | 90        | 6.96%   |
| Zen 2            | 61        | 4.72%   |
| Skylake          | 59        | 4.56%   |
| Westmere         | 49        | 3.79%   |
| Unknown          | 49        | 3.79%   |
| Zen 3            | 48        | 3.71%   |
| Zen+             | 37        | 2.86%   |
| Core             | 36        | 2.78%   |
| CometLake        | 36        | 2.78%   |
| Silvermont       | 33        | 2.55%   |
| Zen              | 28        | 2.17%   |
| Broadwell        | 28        | 2.17%   |
| Alderlake Hybrid | 22        | 1.7%    |
| TigerLake        | 21        | 1.62%   |
| K10              | 19        | 1.47%   |
| Nehalem          | 17        | 1.31%   |
| K8 Hammer        | 17        | 1.31%   |
| Goldmont plus    | 16        | 1.24%   |
| Piledriver       | 12        | 0.93%   |
| Icelake          | 12        | 0.93%   |
| Bonnell          | 12        | 0.93%   |
| Steamroller      | 8         | 0.62%   |
| P6               | 8         | 0.62%   |
| Goldmont         | 8         | 0.62%   |
| NetBurst         | 7         | 0.54%   |
| Jaguar           | 6         | 0.46%   |
| K10 Llano        | 5         | 0.39%   |
| Excavator        | 4         | 0.31%   |
| Bulldozer        | 4         | 0.31%   |
| Bobcat           | 4         | 0.31%   |
| Puma             | 3         | 0.23%   |
| K8 & K10 hybrid  | 2         | 0.15%   |
| Tremont          | 1         | 0.08%   |
| Gracemont        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 751       | 53.38%  |
| Nvidia                                       | 327       | 23.24%  |
| AMD                                          | 315       | 22.39%  |
| Matrox Electronics Systems                   | 6         | 0.43%   |
| ASPEED Technology                            | 5         | 0.36%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.07%   |
| VIA Technologies                             | 1         | 0.07%   |
| Loongson Technology                          | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 100       | 6.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 4.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 2.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 23        | 1.57%   |
| Intel UHD Graphics 620                                                                   | 21        | 1.43%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 21        | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 1.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 1.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.3%    |
| Intel HD Graphics 5500                                                                   | 18        | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16        | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.09%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 14        | 0.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 0.95%   |
| Intel HD Graphics 620                                                                    | 14        | 0.95%   |
| Intel HD Graphics 530                                                                    | 14        | 0.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 13        | 0.89%   |
| Intel HD Graphics 630                                                                    | 13        | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.82%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 11        | 0.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 11        | 0.75%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 0.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 10        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 9         | 0.61%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 9         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 637       | 49.11%  |
| 1 x AMD                   | 267       | 20.59%  |
| 1 x Nvidia                | 226       | 17.42%  |
| Intel + Nvidia            | 73        | 5.63%   |
| Other                     | 18        | 1.39%   |
| Intel + AMD               | 15        | 1.16%   |
| AMD + Nvidia              | 15        | 1.16%   |
| 2 x AMD                   | 13        | 1%      |
| 2 x Intel                 | 9         | 0.69%   |
| 2 x Nvidia                | 6         | 0.46%   |
| 1 x Matrox                | 4         | 0.31%   |
| 1 x ASPEED                | 3         | 0.23%   |
| Nvidia + ASPEED           | 2         | 0.15%   |
| Intel + 2 x Nvidia        | 2         | 0.15%   |
| AMD + Matrox              | 2         | 0.15%   |
| 1 x XGI                   | 1         | 0.08%   |
| 1 x VIA                   | 1         | 0.08%   |
| Intel + 2 x AMD           | 1         | 0.08%   |
| Intel + AMD + 1 x Nvidia  | 1         | 0.08%   |
| AMD + Loongson Technology | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1079      | 82.68%  |
| Proprietary | 172       | 13.18%  |
| Unknown     | 54        | 4.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 786       | 59.46%  |
| 0.01-0.5   | 151       | 11.42%  |
| 1.01-2.0   | 129       | 9.76%   |
| 0.51-1.0   | 92        | 6.96%   |
| 3.01-4.0   | 67        | 5.07%   |
| 7.01-8.0   | 44        | 3.33%   |
| 5.01-6.0   | 24        | 1.82%   |
| 8.01-16.0  | 19        | 1.44%   |
| 16.01-24.0 | 5         | 0.38%   |
| 2.01-3.0   | 3         | 0.23%   |
| 4.01-5.0   | 1         | 0.08%   |
| 24.01-32.0 | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 140       | 10.74%  |
| AU Optronics            | 97        | 7.44%   |
| Dell                    | 80        | 6.13%   |
| Samsung Electronics     | 76        | 5.83%   |
| Goldstar                | 62        | 4.75%   |
| Chimei Innolux          | 60        | 4.6%    |
| BOE                     | 59        | 4.52%   |
| Sharp                   | 53        | 4.06%   |
| IOD                     | 53        | 4.06%   |
| BenQ                    | 47        | 3.6%    |
| Mitsubishi              | 37        | 2.84%   |
| Iiyama                  | 36        | 2.76%   |
| Apple                   | 36        | 2.76%   |
| Acer                    | 36        | 2.76%   |
| Hewlett-Packard         | 31        | 2.38%   |
| Philips                 | 30        | 2.3%    |
| Eizo                    | 27        | 2.07%   |
| Lenovo                  | 26        | 1.99%   |
| Chi Mei Optoelectronics | 22        | 1.69%   |
| Ancor Communications    | 19        | 1.46%   |
| Unknown                 | 17        | 1.3%    |
| NEC Computers           | 16        | 1.23%   |
| AOC                     | 16        | 1.23%   |
| Panasonic               | 14        | 1.07%   |
| Toshiba                 | 12        | 0.92%   |
| Sony                    | 12        | 0.92%   |
| ASUSTek Computer        | 11        | 0.84%   |
| PANDA                   | 10        | 0.77%   |
| ViewSonic               | 8         | 0.61%   |
| LG Electronics          | 7         | 0.54%   |
| Idek Iiyama             | 7         | 0.54%   |
| Fujitsu                 | 7         | 0.54%   |
| InfoVision              | 6         | 0.46%   |
| Unknown                 | 6         | 0.46%   |
| Hitachi                 | 5         | 0.38%   |
| CSO                     | 5         | 0.38%   |
| CPT                     | 5         | 0.38%   |
| Valve                   | 4         | 0.31%   |
| RTK                     | 4         | 0.31%   |
| Orion                   | 4         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 24        | 1.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 7         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.44%   |
| Apple Color LCD APPA041 2560x1600 286x179mm 13.3-inch                    | 6         | 0.44%   |
| Unknown                                                                  | 6         | 0.44%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                      | 5         | 0.37%   |
| Apple Cinema HD APP9223 1920x1200 495x310mm 23.0-inch                    | 5         | 0.37%   |
| AOC 28E850 AOC0CCD 2560x1440 480x270mm 21.7-inch                         | 5         | 0.37%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 4         | 0.29%   |
| NOV NOVA HD CARD NOV0405 1920x1080 459x296mm 21.5-inch                   | 4         | 0.29%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch              | 4         | 0.29%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 4         | 0.29%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.29%   |
| LG Display LCD Monitor LGD02CB 1366x768 344x194mm 15.5-inch              | 4         | 0.29%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 4         | 0.29%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 4         | 0.29%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 4         | 0.29%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.29%   |
| ASUSTek Computer VZ239 AUS23CC 1920x1080 509x286mm 23.0-inch             | 4         | 0.29%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                        | 4         | 0.29%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch               | 3         | 0.22%   |
| Toshiba TV TSB020A 1920x1080                                             | 3         | 0.22%   |
| Toshiba LCD Monitor TOS508F 1920x1080 476x268mm 21.5-inch                | 3         | 0.22%   |
| Sharp HDMI SHP0FDB 1360x768 820x460mm 37.0-inch                          | 3         | 0.22%   |
| Philips PHL 328P6VU PHL0927 3840x2160 698x393mm 31.5-inch                | 3         | 0.22%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch                  | 3         | 0.22%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                       | 3         | 0.22%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 3         | 0.22%   |
| Mitsubishi RDT1714VM MEL4764 1280x1024 338x270mm 17.0-inch               | 3         | 0.22%   |
| Mitsubishi MDT241WG MEL478E 1920x1200 520x320mm 24.0-inch                | 3         | 0.22%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.22%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 3         | 0.22%   |
| IOD EX-LD2071T IOD150D 1920x1080 458x258mm 20.7-inch                     | 3         | 0.22%   |
| Iiyama PL3291 IVM7605 1920x1080 698x393mm 31.5-inch                      | 3         | 0.22%   |
| Iiyama PL2390 IVM562D 1920x1080 509x286mm 23.0-inch                      | 3         | 0.22%   |
| Iiyama PL2283H IVM562E 1920x1080 480x270mm 21.7-inch                     | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 509       | 39.55%  |
| 1366x768 (WXGA)    | 225       | 17.48%  |
| 3840x2160 (4K)     | 102       | 7.93%   |
| 1280x1024 (SXGA)   | 65        | 5.05%   |
| 1920x1200 (WUXGA)  | 55        | 4.27%   |
| 2560x1440 (QHD)    | 53        | 4.12%   |
| 1280x800 (WXGA)    | 31        | 2.41%   |
| 1440x900 (WXGA+)   | 25        | 1.94%   |
| 1600x900 (HD+)     | 24        | 1.86%   |
| 1680x1050 (WSXGA+) | 22        | 1.71%   |
| 2560x1600          | 18        | 1.4%    |
| Unknown            | 18        | 1.4%    |
| 1920x540           | 16        | 1.24%   |
| 2560x1080          | 10        | 0.78%   |
| 2880x1800          | 9         | 0.7%    |
| 1600x1200          | 9         | 0.7%    |
| 1360x768           | 9         | 0.7%    |
| 1024x768 (XGA)     | 8         | 0.62%   |
| 3440x1440          | 6         | 0.47%   |
| 3840x1080          | 5         | 0.39%   |
| 2160x1440          | 5         | 0.39%   |
| 1400x1050          | 5         | 0.39%   |
| 800x1280           | 4         | 0.31%   |
| 3840x2400          | 4         | 0.31%   |
| 3200x1800 (QHD+)   | 3         | 0.23%   |
| 3072x1920          | 3         | 0.23%   |
| 1920x1280          | 3         | 0.23%   |
| 1280x720 (HD)      | 3         | 0.23%   |
| 1024x600           | 3         | 0.23%   |
| 3520x1080          | 2         | 0.16%   |
| 3456x2160          | 2         | 0.16%   |
| 3200x1200          | 2         | 0.16%   |
| 2880x1920          | 2         | 0.16%   |
| 2880x1620          | 2         | 0.16%   |
| 2560x1024          | 2         | 0.16%   |
| 1360x765           | 2         | 0.16%   |
| 1280x960           | 2         | 0.16%   |
| 1024x576           | 2         | 0.16%   |
| 800x480            | 1         | 0.08%   |
| 7680x2160          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 265       | 20.4%   |
| 13      | 126       | 9.7%    |
| 27      | 106       | 8.16%   |
| 23      | 104       | 8.01%   |
| 21      | 103       | 7.93%   |
| 24      | 98        | 7.54%   |
| Unknown | 84        | 6.47%   |
| 14      | 60        | 4.62%   |
| 17      | 59        | 4.54%   |
| 19      | 43        | 3.31%   |
| 12      | 42        | 3.23%   |
| 31      | 36        | 2.77%   |
| 20      | 23        | 1.77%   |
| 11      | 18        | 1.39%   |
| 18      | 13        | 1%      |
| 10      | 13        | 1%      |
| 34      | 12        | 0.92%   |
| 72      | 11        | 0.85%   |
| 22      | 11        | 0.85%   |
| 37      | 10        | 0.77%   |
| 16      | 10        | 0.77%   |
| 84      | 6         | 0.46%   |
| 32      | 6         | 0.46%   |
| 54      | 5         | 0.38%   |
| 42      | 4         | 0.31%   |
| 7       | 4         | 0.31%   |
| 43      | 3         | 0.23%   |
| 40      | 3         | 0.23%   |
| 26      | 3         | 0.23%   |
| 25      | 3         | 0.23%   |
| 52      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 30      | 2         | 0.15%   |
| 29      | 2         | 0.15%   |
| 74      | 1         | 0.08%   |
| 64      | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 38      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 378       | 29.44%  |
| 501-600     | 291       | 22.66%  |
| 201-300     | 171       | 13.32%  |
| 401-500     | 165       | 12.85%  |
| Unknown     | 84        | 6.54%   |
| 351-400     | 69        | 5.37%   |
| 601-700     | 51        | 3.97%   |
| 1501-2000   | 18        | 1.4%    |
| 801-900     | 17        | 1.32%   |
| 701-800     | 17        | 1.32%   |
| 1001-1500   | 13        | 1.01%   |
| 901-1000    | 6         | 0.47%   |
| 1-100       | 4         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 855       | 70.6%   |
| 16/10   | 165       | 13.63%  |
| Unknown | 67        | 5.53%   |
| 5/4     | 57        | 4.71%   |
| 4/3     | 20        | 1.65%   |
| 3/2     | 16        | 1.32%   |
| 21/9    | 15        | 1.24%   |
| 32/9    | 8         | 0.66%   |
| 0.67    | 4         | 0.33%   |
| 1.00    | 2         | 0.17%   |
| 6/5     | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 267       | 20.62%  |
| 201-250        | 228       | 17.61%  |
| 151-200        | 116       | 8.96%   |
| 301-350        | 108       | 8.34%   |
| 81-90          | 99        | 7.64%   |
| 71-80          | 84        | 6.49%   |
| Unknown        | 84        | 6.49%   |
| 351-500        | 58        | 4.48%   |
| 251-300        | 46        | 3.55%   |
| 61-70          | 41        | 3.17%   |
| 141-150        | 40        | 3.09%   |
| More than 1000 | 28        | 2.16%   |
| 121-130        | 23        | 1.78%   |
| 501-1000       | 22        | 1.7%    |
| 51-60          | 19        | 1.47%   |
| 41-50          | 12        | 0.93%   |
| 111-120        | 8         | 0.62%   |
| 1-40           | 4         | 0.31%   |
| 131-140        | 4         | 0.31%   |
| 91-100         | 4         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 475       | 37.58%  |
| 101-120       | 294       | 23.26%  |
| 121-160       | 228       | 18.04%  |
| 161-240       | 130       | 10.28%  |
| Unknown       | 84        | 6.65%   |
| More than 240 | 29        | 2.29%   |
| 1-50          | 24        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1091      | 83.09%  |
| 2     | 152       | 11.58%  |
| 0     | 56        | 4.27%   |
| 3     | 11        | 0.84%   |
| 4     | 2         | 0.15%   |
| 6     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 636       | 33.81%  |
| Realtek Semiconductor                  | 607       | 32.27%  |
| Qualcomm Atheros                       | 227       | 12.07%  |
| Broadcom                               | 127       | 6.75%   |
| Marvell Technology Group               | 38        | 2.02%   |
| MediaTek                               | 26        | 1.38%   |
| BUFFALO                                | 26        | 1.38%   |
| Broadcom Limited                       | 24        | 1.28%   |
| TP-Link                                | 21        | 1.12%   |
| ASIX Electronics                       | 20        | 1.06%   |
| PLANEX                                 | 15        | 0.8%    |
| Nvidia                                 | 12        | 0.64%   |
| Elecom                                 | 8         | 0.43%   |
| Ralink                                 | 7         | 0.37%   |
| Huawei Technologies                    | 7         | 0.37%   |
| Aquantia                               | 7         | 0.37%   |
| Apple                                  | 7         | 0.37%   |
| VIA Technologies                       | 4         | 0.21%   |
| Sierra Wireless                        | 4         | 0.21%   |
| Ralink Technology                      | 4         | 0.21%   |
| Logitec                                | 4         | 0.21%   |
| Lenovo                                 | 4         | 0.21%   |
| Qualcomm Atheros Communications        | 3         | 0.16%   |
| U-Blox                                 | 2         | 0.11%   |
| Samsung Electronics                    | 2         | 0.11%   |
| Prolific Technology                    | 2         | 0.11%   |
| OPPO Electronics                       | 2         | 0.11%   |
| NetGear                                | 2         | 0.11%   |
| NEC Computers                          | 2         | 0.11%   |
| JMicron Technology                     | 2         | 0.11%   |
| ICS Advent                             | 2         | 0.11%   |
| Gemtek                                 | 2         | 0.11%   |
| D-Link                                 | 2         | 0.11%   |
| Xiaomi                                 | 1         | 0.05%   |
| Wilocity                               | 1         | 0.05%   |
| Wacom                                  | 1         | 0.05%   |
| vivo                                   | 1         | 0.05%   |
| ULi Electronics                        | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 414       | 18.58%  |
| Intel Wi-Fi 6 AX200                                                     | 52        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 45        | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                       | 41        | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 38        | 1.71%   |
| Intel Ethernet Connection (2) I219-V                                    | 36        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 34        | 1.53%   |
| Intel 82579V Gigabit Network Connection                                 | 34        | 1.53%   |
| Intel I211 Gigabit Network Connection                                   | 32        | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 31        | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 28        | 1.26%   |
| Intel Wireless 7265                                                     | 28        | 1.26%   |
| Intel Wireless 8265 / 8275                                              | 25        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                    | 23        | 1.03%   |
| Intel Wireless 7260                                                     | 22        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 0.94%   |
| Intel Ethernet Connection I217-V                                        | 21        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 0.81%   |
| Intel Wireless 3165                                                     | 18        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 18        | 0.81%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                           | 18        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 17        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 17        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 0.76%   |
| Intel Ethernet Connection I217-LM                                       | 17        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 17        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 0.72%   |
| Intel Wireless 8260                                                     | 16        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 0.63%   |
| Intel Wireless 3160                                                     | 14        | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 0.58%   |
| Intel Ethernet Controller I225-V                                        | 13        | 0.58%   |
| Intel Ethernet Connection (10) I219-V                                   | 13        | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 410       | 43.57%  |
| Qualcomm Atheros                | 175       | 18.6%   |
| Realtek Semiconductor           | 136       | 14.45%  |
| Broadcom                        | 73        | 7.76%   |
| MediaTek                        | 26        | 2.76%   |
| BUFFALO                         | 26        | 2.76%   |
| TP-Link                         | 21        | 2.23%   |
| PLANEX                          | 15        | 1.59%   |
| Broadcom Limited                | 15        | 1.59%   |
| Ralink                          | 7         | 0.74%   |
| Elecom                          | 7         | 0.74%   |
| Sierra Wireless                 | 4         | 0.43%   |
| Ralink Technology               | 4         | 0.43%   |
| Logitec                         | 4         | 0.43%   |
| Qualcomm Atheros Communications | 3         | 0.32%   |
| Marvell Technology Group        | 3         | 0.32%   |
| NetGear                         | 2         | 0.21%   |
| D-Link                          | 2         | 0.21%   |
| Wilocity                        | 1         | 0.11%   |
| Wacom                           | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| NEC Computers                   | 1         | 0.11%   |
| I-O Data Device                 | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Dell                            | 1         | 0.11%   |
| ASUSTek Computer                | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 52        | 5.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 34        | 3.59%   |
| Intel Wireless 7265                                                     | 28        | 2.95%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.64%   |
| Intel Wireless 7260                                                     | 22        | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 1.9%    |
| Intel Wireless 3165                                                     | 18        | 1.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 18        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 17        | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 17        | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 17        | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.69%   |
| Intel Wireless 8260                                                     | 16        | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 1.48%   |
| Intel Wireless 3160                                                     | 14        | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 12        | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 10        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 1.05%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 10        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.95%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 0.95%   |
| Realtek 802.11ac NIC                                                    | 8         | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.84%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 537       | 44.09%  |
| Intel                            | 394       | 32.35%  |
| Qualcomm Atheros                 | 91        | 7.47%   |
| Broadcom                         | 70        | 5.75%   |
| Marvell Technology Group         | 35        | 2.87%   |
| ASIX Electronics                 | 20        | 1.64%   |
| Nvidia                           | 12        | 0.99%   |
| Broadcom Limited                 | 9         | 0.74%   |
| Huawei Technologies              | 7         | 0.57%   |
| Aquantia                         | 7         | 0.57%   |
| Apple                            | 7         | 0.57%   |
| VIA Technologies                 | 4         | 0.33%   |
| Lenovo                           | 4         | 0.33%   |
| Samsung Electronics              | 2         | 0.16%   |
| OPPO Electronics                 | 2         | 0.16%   |
| JMicron Technology               | 2         | 0.16%   |
| ICS Advent                       | 2         | 0.16%   |
| Gemtek                           | 2         | 0.16%   |
| Xiaomi                           | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| QNAP System                      | 1         | 0.08%   |
| Netchip Technology               | 1         | 0.08%   |
| Loongson Technology              | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |
| Elecom                           | 1         | 0.08%   |
| DisplayLink                      | 1         | 0.08%   |
| Corega K.K.                      | 1         | 0.08%   |
| ADMtek                           | 1         | 0.08%   |
| 3Com                             | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 414       | 32.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 3.02%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 2.86%   |
| Intel 82579V Gigabit Network Connection                           | 34        | 2.7%    |
| Intel I211 Gigabit Network Connection                             | 32        | 2.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 2.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 28        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 23        | 1.83%   |
| Intel Ethernet Connection I217-V                                  | 21        | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 1.35%   |
| Intel Ethernet Controller I225-V                                  | 13        | 1.03%   |
| Intel Ethernet Connection (10) I219-V                             | 13        | 1.03%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 10        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 8         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 7         | 0.56%   |
| Intel WiMAX Connection 2400m                                      | 7         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.56%   |
| Intel 82577LC Gigabit Network Connection                          | 7         | 0.56%   |
| Intel 82567V-2 Gigabit Network Connection                         | 7         | 0.56%   |
| Huawei E353/E3131                                                 | 7         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.56%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 7         | 0.56%   |
| Apple iBridge                                                     | 7         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1131      | 55.36%  |
| WiFi     | 891       | 43.61%  |
| Modem    | 11        | 0.54%   |
| Unknown  | 10        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 720       | 53.77%  |
| WiFi     | 619       | 46.23%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 660       | 50.97%  |
| 1     | 572       | 44.17%  |
| 3     | 30        | 2.32%   |
| 0     | 26        | 2.01%   |
| 4     | 4         | 0.31%   |
| 8     | 1         | 0.08%   |
| 7     | 1         | 0.08%   |
| 6     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 967       | 73.15%  |
| Yes  | 355       | 26.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 313       | 46.93%  |
| Cambridge Silicon Radio         | 90        | 13.49%  |
| Realtek Semiconductor           | 45        | 6.75%   |
| Qualcomm Atheros Communications | 37        | 5.55%   |
| IMC Networks                    | 32        | 4.8%    |
| Broadcom                        | 31        | 4.65%   |
| Apple                           | 27        | 4.05%   |
| Foxconn / Hon Hai               | 16        | 2.4%    |
| MediaTek                        | 10        | 1.5%    |
| Alps Electric                   | 10        | 1.5%    |
| ASUSTek Computer                | 9         | 1.35%   |
| Fujitsu                         | 8         | 1.2%    |
| Realtek                         | 7         | 1.05%   |
| TP-Link                         | 6         | 0.9%    |
| Lite-On Technology              | 6         | 0.9%    |
| Marvell Semiconductor           | 4         | 0.6%    |
| Toshiba                         | 3         | 0.45%   |
| Hewlett-Packard                 | 3         | 0.45%   |
| Ralink                          | 2         | 0.3%    |
| Ralink Technology               | 1         | 0.15%   |
| Opticis                         | 1         | 0.15%   |
| Dell                            | 1         | 0.15%   |
| Creative Technology             | 1         | 0.15%   |
| BUFFALO                         | 1         | 0.15%   |
| Askey Computer                  | 1         | 0.15%   |
| Actions                         | 1         | 0.15%   |
| 8BitDo                          | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 118       | 17.69%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 90        | 13.49%  |
| Intel AX201 Bluetooth                                                               | 50        | 7.5%    |
| Intel AX200 Bluetooth                                                               | 49        | 7.35%   |
| Realtek Bluetooth Radio                                                             | 34        | 5.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 29        | 4.35%   |
| Intel Bluetooth Device                                                              | 18        | 2.7%    |
| Intel AX210 Bluetooth                                                               | 18        | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 17        | 2.55%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 15        | 2.25%   |
| Apple Bluetooth Host Controller                                                     | 15        | 2.25%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 1.65%   |
| MediaTek Wireless_Device                                                            | 10        | 1.5%    |
| IMC Networks Bluetooth Device                                                       | 10        | 1.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 9         | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.35%   |
| IMC Networks Wireless_Device                                                        | 8         | 1.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.2%    |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.2%    |
| Realtek Bluetooth Radio                                                             | 7         | 1.05%   |
| Fujitsu Bluetooth Device                                                            | 7         | 1.05%   |
| TP-Link UB500 Adapter                                                               | 6         | 0.9%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.75%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 5         | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.6%    |
| Toshiba Atheros AR3012 Bluetooth                                                    | 3         | 0.45%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.45%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.45%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 0.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.45%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 3         | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.45%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 944       | 53.18%  |
| AMD                                          | 356       | 20.06%  |
| Nvidia                                       | 263       | 14.82%  |
| C-Media Electronics                          | 39        | 2.2%    |
| Texas Instruments                            | 19        | 1.07%   |
| Creative Technology                          | 17        | 0.96%   |
| Apple                                        | 15        | 0.85%   |
| VIA Technologies                             | 14        | 0.79%   |
| JMTek                                        | 10        | 0.56%   |
| Harman                                       | 10        | 0.56%   |
| Yamaha                                       | 7         | 0.39%   |
| Generalplus Technology                       | 7         | 0.39%   |
| Creative Labs                                | 7         | 0.39%   |
| Sony                                         | 4         | 0.23%   |
| Realtek Semiconductor                        | 4         | 0.23%   |
| Lenovo                                       | 4         | 0.23%   |
| GN Netcom                                    | 4         | 0.23%   |
| Elitegroup Computer Systems (ECS)            | 4         | 0.23%   |
| TOWA Electronics                             | 3         | 0.17%   |
| Roland                                       | 3         | 0.17%   |
| XMOS                                         | 2         | 0.11%   |
| Onkyo                                        | 2         | 0.11%   |
| DSEA A/S                                     | 2         | 0.11%   |
| Dell                                         | 2         | 0.11%   |
| ASUSTek Computer                             | 2         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| Xiaomi                                       | 1         | 0.06%   |
| www.hirestech.com 2012 REV 2.1               | 1         | 0.06%   |
| ULi Electronics                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.06%   |
| Tenx Technology                              | 1         | 0.06%   |
| SteelSeries ApS                              | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.06%   |
| RME                                          | 1         | 0.06%   |
| Razer USA                                    | 1         | 0.06%   |
| RATOC System                                 | 1         | 0.06%   |
| Rasteme                                      | 1         | 0.06%   |
| Philips (or NXP)                             | 1         | 0.06%   |
| Medeli Electronics                           | 1         | 0.06%   |
| M2Tech                                       | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 137       | 6.59%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 107       | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 83        | 3.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 74        | 3.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 66        | 3.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 60        | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 55        | 2.65%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 52        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 47        | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 46        | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 40        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 39        | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 37        | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 35        | 1.68%   |
| AMD FCH Azalia Controller                                                                         | 33        | 1.59%   |
| Intel 200 Series PCH HD Audio                                                                     | 31        | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 28        | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 1.3%    |
| Intel Broadwell-U Audio Controller                                                                | 26        | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 24        | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 24        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 24        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 22        | 1.06%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 22        | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 21        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 18        | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 0.72%   |
| Apple Audio Device                                                                                | 15        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 14        | 0.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 14        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 13        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 162       | 21.54%  |
| SK hynix                                | 116       | 15.43%  |
| Unknown                                 | 87        | 11.57%  |
| Micron Technology                       | 76        | 10.11%  |
| Kingston                                | 54        | 7.18%   |
| Crucial                                 | 50        | 6.65%   |
| A-DATA Technology                       | 25        | 3.32%   |
| Team                                    | 21        | 2.79%   |
| Nanya Technology                        | 18        | 2.39%   |
| Corsair                                 | 16        | 2.13%   |
| G.Skill                                 | 13        | 1.73%   |
| Unknown                                 | 12        | 1.6%    |
| Elpida                                  | 11        | 1.46%   |
| Silicon Power                           | 10        | 1.33%   |
| Unknown (ABCD)                          | 9         | 1.2%    |
| Transcend                               | 8         | 1.06%   |
| Panram                                  | 8         | 1.06%   |
| Ramaxel Technology                      | 7         | 0.93%   |
| SanMax                                  | 6         | 0.8%    |
| KLEVV                                   | 5         | 0.66%   |
| Patriot                                 | 3         | 0.4%    |
| ASint Technology                        | 3         | 0.4%    |
| Toshiba                                 | 2         | 0.27%   |
| Chun Well                               | 2         | 0.27%   |
| CFD                                     | 2         | 0.27%   |
| V-Color                                 | 1         | 0.13%   |
| Unknown (8AD3)                          | 1         | 0.13%   |
| Unknown (0x7FFF)                        | 1         | 0.13%   |
| Unknown (0x09EE)                        | 1         | 0.13%   |
| Unknown (08C8)                          | 1         | 0.13%   |
| Unknown (04E9)                          | 1         | 0.13%   |
| UMAX                                    | 1         | 0.13%   |
| Silicon Power Computer & Communications | 1         | 0.13%   |
| SHARETRONIC                             | 1         | 0.13%   |
| Ramos Technology                        | 1         | 0.13%   |
| Patriot Memory (PDP Systems)            | 1         | 0.13%   |
| Neo Forza                               | 1         | 0.13%   |
| Melco                                   | 1         | 0.13%   |
| Kingmax                                 | 1         | 0.13%   |
| Innodisk                                | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 25        | 3.15%   |
| Unknown                                                          | 12        | 1.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.76%   |
| Micron RAM MT53E512M64D4NW-053 4GB Row Of Chips LPDDR4 3733MT/s  | 6         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 5         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.5%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 4         | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.5%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.5%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s            | 4         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.38%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 3         | 0.38%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 3         | 0.38%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s              | 3         | 0.38%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 3         | 0.38%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.38%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.38%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.38%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 3         | 0.38%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.38%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 3         | 0.38%   |
| Nanya RAM M2X4G64CB8HG9N-DG 4GB DIMM DDR3 1600MT/s               | 3         | 0.38%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s               | 3         | 0.38%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 3         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 284       | 42.58%  |
| DDR3    | 234       | 35.08%  |
| DDR2    | 36        | 5.4%    |
| LPDDR4  | 30        | 4.5%    |
| LPDDR3  | 29        | 4.35%   |
| SDRAM   | 22        | 3.3%    |
| Unknown | 14        | 2.1%    |
| DDR5    | 9         | 1.35%   |
| LPDDR5  | 7         | 1.05%   |
| DDR     | 2         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 372       | 56.02%  |
| DIMM         | 226       | 34.04%  |
| Row Of Chips | 55        | 8.28%   |
| Unknown      | 5         | 0.75%   |
| Chip         | 4         | 0.6%    |
| RIMM         | 2         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 232       | 32.86%  |
| 4096  | 217       | 30.74%  |
| 16384 | 97        | 13.74%  |
| 2048  | 94        | 13.31%  |
| 32768 | 38        | 5.38%   |
| 1024  | 23        | 3.26%   |
| 512   | 3         | 0.42%   |
| 65536 | 1         | 0.14%   |
| 256   | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 160       | 22.6%   |
| 3200    | 108       | 15.25%  |
| 2667    | 84        | 11.86%  |
| 2400    | 54        | 7.63%   |
| 2133    | 39        | 5.51%   |
| 1333    | 30        | 4.24%   |
| 1334    | 29        | 4.1%    |
| 1067    | 15        | 2.12%   |
| 3600    | 13        | 1.84%   |
| 800     | 13        | 1.84%   |
| 667     | 13        | 1.84%   |
| Unknown | 13        | 1.84%   |
| 2933    | 11        | 1.55%   |
| 4199    | 10        | 1.41%   |
| 2666    | 10        | 1.41%   |
| 1066    | 10        | 1.41%   |
| 4267    | 9         | 1.27%   |
| 1867    | 9         | 1.27%   |
| 1800    | 9         | 1.27%   |
| 3733    | 8         | 1.13%   |
| 6400    | 7         | 0.99%   |
| 533     | 7         | 0.99%   |
| 4800    | 6         | 0.85%   |
| 3800    | 5         | 0.71%   |
| 1866    | 5         | 0.71%   |
| 5600    | 3         | 0.42%   |
| 3400    | 3         | 0.42%   |
| 3266    | 3         | 0.42%   |
| 975     | 3         | 0.42%   |
| 333     | 3         | 0.42%   |
| 4266    | 2         | 0.28%   |
| 3000    | 2         | 0.28%   |
| 400     | 2         | 0.28%   |
| 4133    | 1         | 0.14%   |
| 3534    | 1         | 0.14%   |
| 3100    | 1         | 0.14%   |
| 3007    | 1         | 0.14%   |
| 2733    | 1         | 0.14%   |
| 2048    | 1         | 0.14%   |
| 2000    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 5         | 29.41%  |
| Brother Industries  | 5         | 29.41%  |
| Seiko Epson         | 3         | 17.65%  |
| Samsung Electronics | 1         | 5.88%   |
| nemonic             | 1         | 5.88%   |
| Hewlett-Packard     | 1         | 5.88%   |
| Fuji Xerox          | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother HL-1440 Laser Printer | 2         | 11.76%  |
| Seiko Epson XP-100 Series     | 1         | 5.88%   |
| Seiko Epson WF-2010 Series    | 1         | 5.88%   |
| Seiko Epson EP-306 Series     | 1         | 5.88%   |
| Samsung SCX-3200 Series       | 1         | 5.88%   |
| nemonic MIP-001               | 1         | 5.88%   |
| HP ENVY 5000 series           | 1         | 5.88%   |
| Fuji Xerox MultiWriter 5600C  | 1         | 5.88%   |
| Canon TS5300 series           | 1         | 5.88%   |
| Canon PIXMA MG3600 Series     | 1         | 5.88%   |
| Canon PIXMA iX6850 Printer    | 1         | 5.88%   |
| Canon PIXMA iP4600 Printer    | 1         | 5.88%   |
| Canon iP2700 series           | 1         | 5.88%   |
| Brother HL-L2360D series      | 1         | 5.88%   |
| Brother HL-52x0 series        | 1         | 5.88%   |
| Brother HL-2130 series        | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 100                                       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 107       | 20.74%  |
| IMC Networks                           | 43        | 8.33%   |
| Microdia                               | 41        | 7.95%   |
| Bison Electronics                      | 38        | 7.36%   |
| Sunplus Innovation Technology          | 33        | 6.4%    |
| Realtek Semiconductor                  | 29        | 5.62%   |
| Apple                                  | 27        | 5.23%   |
| Logitech                               | 21        | 4.07%   |
| Quanta                                 | 18        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 2.91%   |
| Suyin                                  | 13        | 2.52%   |
| Syntek                                 | 12        | 2.33%   |
| Acer                                   | 12        | 2.33%   |
| Ricoh                                  | 10        | 1.94%   |
| BUFFALO                                | 8         | 1.55%   |
| Alcor Micro                            | 8         | 1.55%   |
| Elecom                                 | 7         | 1.36%   |
| Microsoft                              | 6         | 1.16%   |
| Importek                               | 6         | 1.16%   |
| Silicon Motion                         | 5         | 0.97%   |
| Luxvisions Innotech Limited            | 5         | 0.97%   |
| Lite-On Technology                     | 5         | 0.97%   |
| Sonix Technology                       | 4         | 0.78%   |
| Samsung Electronics                    | 3         | 0.58%   |
| MacroSilicon                           | 3         | 0.58%   |
| Genesys Logic                          | 3         | 0.58%   |
| Generalplus Technology                 | 3         | 0.58%   |
| Cubeternet                             | 3         | 0.58%   |
| Z-Star Microelectronics                | 2         | 0.39%   |
| SunplusIT                              | 2         | 0.39%   |
| Lenovo                                 | 2         | 0.39%   |
| Huawei Technologies                    | 2         | 0.39%   |
| GEMBIRD                                | 2         | 0.39%   |
| Etron Technology                       | 2         | 0.39%   |
| WaveRider Communications               | 1         | 0.19%   |
| Sunplus Technology                     | 1         | 0.19%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.19%   |
| Ruision                                | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| Pixart Imaging                         | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 19        | 3.63%   |
| IMC Networks Integrated Camera          | 16        | 3.06%   |
| Chicony Integrated Camera               | 16        | 3.06%   |
| Chicony FJ Camera                       | 15        | 2.87%   |
| Realtek Integrated_Webcam_HD            | 13        | 2.49%   |
| Apple FaceTime HD Camera (Built-in)     | 11        | 2.1%    |
| Logitech Webcam C270                    | 8         | 1.53%   |
| Chicony USB2.0 Camera                   | 8         | 1.53%   |
| BUFFALO USB 2.0 Camera                  | 8         | 1.53%   |
| IMC Networks USB2.0 HD UVC WebCam       | 7         | 1.34%   |
| Chicony TOSHIBA Web Camera - HD         | 7         | 1.34%   |
| Bison USB HD Webcam                     | 7         | 1.34%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 6         | 1.15%   |
| Apple Built-in iSight                   | 6         | 1.15%   |
| Syntek Integrated Camera                | 5         | 0.96%   |
| Chicony HD Webcam                       | 5         | 0.96%   |
| Bison Integrated Camera                 | 5         | 0.96%   |
| Apple FaceTime HD Camera                | 5         | 0.96%   |
| Sunplus Integrated_Webcam_HD            | 4         | 0.76%   |
| Sunplus HD WebCam                       | 4         | 0.76%   |
| Ricoh Sony Vaio Integrated Webcam       | 4         | 0.76%   |
| Quanta HD User Facing                   | 4         | 0.76%   |
| Microdia Webcam Vitade AF               | 4         | 0.76%   |
| Lite-On Integrated Camera               | 4         | 0.76%   |
| Importek TOSHIBA Web Camera - HD        | 4         | 0.76%   |
| Chicony Lenovo EasyCamera               | 4         | 0.76%   |
| Chicony HP Wide Vision HD Camera        | 4         | 0.76%   |
| Chicony HP HD Camera                    | 4         | 0.76%   |
| Bison ThinkPad Integrated Camera        | 4         | 0.76%   |
| Bison Lenovo Integrated Webcam          | 4         | 0.76%   |
| Bison Lenovo EasyCamera                 | 4         | 0.76%   |
| Bison HD Webcam                         | 4         | 0.76%   |
| Bison BisonCam, NB Pro                  | 4         | 0.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 4         | 0.76%   |
| Suyin HP Webcam                         | 3         | 0.57%   |
| Sunplus Integrated_Webcam_FHD           | 3         | 0.57%   |
| Sunplus Dell HD Webcam                  | 3         | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode) | 3         | 0.57%   |
| Ricoh Sony Visual Communication Camera  | 3         | 0.57%   |
| Realtek Lenovo EasyCamera               | 3         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 34        | 27.87%  |
| Synaptics                          | 23        | 18.85%  |
| Shenzhen Goodix Technology         | 17        | 13.93%  |
| AuthenTec                          | 16        | 13.11%  |
| Upek                               | 9         | 7.38%   |
| Elan Microelectronics              | 8         | 6.56%   |
| STMicroelectronics                 | 7         | 5.74%   |
| LighTuning Technology              | 5         | 4.1%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.64%   |
| Focal-systems.Corp                 | 1         | 0.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 12        | 9.84%   |
| Shenzhen Goodix  FingerPrint Device                             | 8         | 6.56%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 7         | 5.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 7         | 5.74%   |
| STMicroelectronics Fingerprint Reader                           | 7         | 5.74%   |
| Shenzhen Goodix Fingerprint Reader                              | 7         | 5.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 4.1%    |
| AuthenTec Fingerprint Sensor                                    | 5         | 4.1%    |
| Validity Sensors Swipe Fingerprint Sensor                       | 4         | 3.28%   |
| Elan ELAN:ARM-M4                                                | 4         | 3.28%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 2.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 2.46%   |
| AuthenTec AES2810                                               | 3         | 2.46%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 2.46%   |
| AuthenTec AES1600                                               | 3         | 2.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 2         | 1.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 1.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 1.64%   |
| Validity Sensors VFS491                                         | 2         | 1.64%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 1.64%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 1.64%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 1.64%   |
| Upek TCS5B Fingerprint sensor                                   | 2         | 1.64%   |
| Synaptics UWP WBDI                                              | 2         | 1.64%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 1.64%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 2         | 1.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 1.64%   |
| Elan fingerprint sensor [FeinTech FPS00200]                     | 2         | 1.64%   |
| Elan ELAN:Fingerprint                                           | 2         | 1.64%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 0.82%   |
| Synaptics WBDI Device                                           | 1         | 0.82%   |
| Synaptics WBDI                                                  | 1         | 0.82%   |
| Synaptics UWP WBDI Device                                       | 1         | 0.82%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                    | 1         | 0.82%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 0.82%   |
| LighTuning Fingerprint Reader                                   | 1         | 0.82%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 0.82%   |
| AuthenTec AES2660 Fingerprint Sensor                            | 1         | 0.82%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 0.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 10        | 30.3%   |
| Upek             | 8         | 24.24%  |
| Alcor Micro      | 8         | 24.24%  |
| O2 Micro         | 4         | 12.12%  |
| SCM Microsystems | 2         | 6.06%   |
| Yubico.com       | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 24.24%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 24.24%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 12.12%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 12.12%  |
| Broadcom 58200                                                               | 3         | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 6.06%   |
| Broadcom 5880                                                                | 2         | 6.06%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 3.03%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 947       | 71.91%  |
| 1     | 307       | 23.31%  |
| 2     | 49        | 3.72%   |
| 3     | 7         | 0.53%   |
| 6     | 2         | 0.15%   |
| 4     | 2         | 0.15%   |
| 8     | 1         | 0.08%   |
| 7     | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 120       | 27.52%  |
| Graphics card            | 77        | 17.66%  |
| Net/wireless             | 56        | 12.84%  |
| Multimedia controller    | 52        | 11.93%  |
| Chipcard                 | 29        | 6.65%   |
| Communication controller | 22        | 5.05%   |
| Unassigned class         | 16        | 3.67%   |
| Storage                  | 16        | 3.67%   |
| Sound                    | 13        | 2.98%   |
| Bluetooth                | 10        | 2.29%   |
| Camera                   | 7         | 1.61%   |
| Modem                    | 5         | 1.15%   |
| Storage/ata              | 3         | 0.69%   |
| Network                  | 3         | 0.69%   |
| Net/ethernet             | 3         | 0.69%   |
| Storage/raid             | 2         | 0.46%   |
| Tv card                  | 1         | 0.23%   |
| Storage/nvme             | 1         | 0.23%   |


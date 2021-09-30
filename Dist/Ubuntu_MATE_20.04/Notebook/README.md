Ubuntu MATE 20.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-mate-20.04

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 455 G7              | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Dell          | Vostro 3350                 | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Acer          | Aspire A515-43              | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Teclast       | F15S                        | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| Packard Be... | EasyNote SL65               | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| Acer          | Extensa 5630                | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| ASUSTek       | X556UAK                     | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Acer          | Aspire E1-571               | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Dell          | Studio 1558                 | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| HP            | EliteBook 2170p             | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Dell          | Latitude E6400              | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| ASUSTek       | K73SJ                       | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | Pavilion                    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| Dell          | Precision M4800             | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Dell          | Precision M4800             | [fd49c10a9f](https://linux-hardware.org/?probe=fd49c10a9f) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| HP            | Pavilion                    | [ade11f7a65](https://linux-hardware.org/?probe=ade11f7a65) | May 08, 2021 |
| Cube          | i18-L                       | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Dell          | G7 7588                     | [1393a855bb](https://linux-hardware.org/?probe=1393a855bb) | Apr 25, 2021 |
| ONE-NETBOO... | A1                          | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| Dell          | Inspiron 3480               | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | Pavilion dv6                | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| HP            | 15                          | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| HP            | ProBook 4530s               | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| Dell          | Latitude E7250              | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Dell          | Latitude E7250              | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| Acer          | Aspire 4740                 | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Samsung       | 760XBE                      | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Samsung       | 760XBE                      | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| ASUSTek       | K50IE                       | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | GF63 Thin 9SCSR             | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| HP            | Pavilion g7                 | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| Toshiba       | Satellite L350D             | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | [6d79297a65](https://linux-hardware.org/?probe=6d79297a65) | Feb 26, 2021 |
| HP            | Pavilion g7                 | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Dell          | Precision M4800             | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| Dell          | Latitude E6500              | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| Acer          | Aspire ES1-521              | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | G7 7588                     | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Dell          | G7 7588                     | [1006977f89](https://linux-hardware.org/?probe=1006977f89) | Jan 28, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | 250 G5 Notebook PC          | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| Dell          | XPS 13 9370                 | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| Star Labs     | LabTop                      | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| Toshiba       | Satellite Pro L500          | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Dell          | Latitude D630               | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| HP            | Pavilion 17                 | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| Acer          | Aspire E5-523               | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| HP            | EliteBook 830 G6            | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| HP            | 255 G7 Notebook PC          | [153a36bfa0](https://linux-hardware.org/?probe=153a36bfa0) | Nov 14, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook Folio 9470m       | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Dell          | Latitude E6420              | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| Acer          | Aspire 5715Z                | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| HP            | 255 G7 Notebook PC          | [07f3bdda40](https://linux-hardware.org/?probe=07f3bdda40) | Oct 25, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| Dell          | Latitude E6430              | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| HP            | Compaq 6730s                | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | Latitude E6420              | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| Medion        | E15302                      | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| System76      | Serval WS                   | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Dell          | Precision M6700             | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Apple         | MacBook4,1                  | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Dell          | Latitude E6410              | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | Latitude E6410              | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Acer          | Aspire A315-42G             | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Samsung       | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | Latitude E6420              | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| Positivo      | Mobile                      | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| HP            | 250 G4 Notebook PC          | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [5ffb6aaedb](https://linux-hardware.org/?probe=5ffb6aaedb) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| HP            | Pavilion dm1                | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | XPS L702X                   | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| Dell          | Inspiron 3421               | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| Lenovo        | Flex 2-14D 20376            | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Dell          | Inspiron 3421               | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| HP            | Pavilion g4                 | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| Dell          | Vostro 3560                 | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Dell          | G7 7588                     | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| Dell          | G7 7588                     | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| Sony          | VPCF1290X                   | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| HP            | 250 G4                      | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| HP            | Pavilion g6                 | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| HP            | Pavilion g6                 | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| Acer          | Nitro AN515-54              | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| Toshiba       | Satellite M500              | [96d989965c](https://linux-hardware.org/?probe=96d989965c) | Jun 04, 2020 |
| HP            | 250 G7 Notebook PC          | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| Packard Be... | EasyNote ME69BMP            | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Toshiba       | Satellite M500              | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| Sony          | VPCF1290X                   | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| ASUSTek       | X541SA                      | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | Latitude E6400              | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| Dell          | Latitude E6400              | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | [7402a2d316](https://linux-hardware.org/?probe=7402a2d316) | May 16, 2020 |
| Dell          | Latitude E6400              | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | [491ea13111](https://linux-hardware.org/?probe=491ea13111) | May 16, 2020 |
| Dell          | Latitude E6400              | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | XPS L502X                   | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| HP            | 250 G5 Notebook PC          | [33e1791dd6](https://linux-hardware.org/?probe=33e1791dd6) | May 06, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Dell          | Inspiron 3576               | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Sony          | VPCS12X9E                   | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| HP            | EliteBook 755 G5            | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Acer          | Aspire V3-574G              | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| MSI           | GP72 6QF                    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.4.0-42-generic     | 25        | 11.11%  |
| 5.4.0-52-generic     | 17        | 7.56%   |
| 5.4.0-47-generic     | 10        | 4.44%   |
| 5.4.0-40-generic     | 10        | 4.44%   |
| 5.4.0-58-generic     | 9         | 4%      |
| 5.4.0-48-generic     | 8         | 3.56%   |
| 5.4.0-31-generic     | 8         | 3.56%   |
| 5.8.0-50-generic     | 7         | 3.11%   |
| 5.4.0-65-generic     | 7         | 3.11%   |
| 5.4.0-54-generic     | 7         | 3.11%   |
| 5.4.0-56-generic     | 6         | 2.67%   |
| 5.4.0-45-generic     | 6         | 2.67%   |
| 5.4.0-26-generic     | 6         | 2.67%   |
| 5.8.0-59-generic     | 5         | 2.22%   |
| 5.8.0-48-generic     | 5         | 2.22%   |
| 5.8.0-43-generic     | 5         | 2.22%   |
| 5.4.0-81-generic     | 5         | 2.22%   |
| 5.4.0-37-generic     | 5         | 2.22%   |
| 5.4.0-29-generic     | 5         | 2.22%   |
| 5.8.0-53-generic     | 4         | 1.78%   |
| 5.4.0-51-generic     | 4         | 1.78%   |
| 5.4.0-74-generic     | 3         | 1.33%   |
| 5.4.0-73-generic     | 3         | 1.33%   |
| 5.4.0-39-generic     | 3         | 1.33%   |
| 5.4.0-33-generic     | 3         | 1.33%   |
| 5.4.0-28-generic     | 3         | 1.33%   |
| 5.8.0-63-generic     | 2         | 0.89%   |
| 5.8.0-45-generic     | 2         | 0.89%   |
| 5.8.0-38-generic     | 2         | 0.89%   |
| 5.4.0-80-generic     | 2         | 0.89%   |
| 5.4.0-72-generic     | 2         | 0.89%   |
| 5.4.0-70-generic     | 2         | 0.89%   |
| 5.4.0-67-generic     | 2         | 0.89%   |
| 5.4.0-66-generic     | 2         | 0.89%   |
| 5.4.0-34-generic     | 2         | 0.89%   |
| 5.4.0-14-generic     | 2         | 0.89%   |
| 5.9.3-050903-generic | 1         | 0.44%   |
| 5.8.17-rockchip64    | 1         | 0.44%   |
| 5.8.0-52-generic     | 1         | 0.44%   |
| 5.8.0-34-generic     | 1         | 0.44%   |
| 5.8.0-33-generic     | 1         | 0.44%   |
| 5.4.0-9-generic      | 1         | 0.44%   |
| 5.4.0-84-generic     | 1         | 0.44%   |
| 5.4.0-77-generic     | 1         | 0.44%   |
| 5.4.0-7642-generic   | 1         | 0.44%   |
| 5.4.0-64-generic     | 1         | 0.44%   |
| 5.4.0-62-generic     | 1         | 0.44%   |
| 5.4.0-59-generic     | 1         | 0.44%   |
| 5.4.0-58-lowlatency  | 1         | 0.44%   |
| 5.4.0-49-generic     | 1         | 0.44%   |
| 5.4.0-44-generic     | 1         | 0.44%   |
| 5.4.0-43-generic     | 1         | 0.44%   |
| 5.4.0-42-lowlatency  | 1         | 0.44%   |
| 5.4.0-38-generic     | 1         | 0.44%   |
| 5.4.0-32-generic     | 1         | 0.44%   |
| 5.4.0-24-generic     | 1         | 0.44%   |
| 5.4.0-21-generic     | 1         | 0.44%   |
| 5.3.0-41-generic     | 1         | 0.44%   |
| 5.3.0-18-generic     | 1         | 0.44%   |
| 5.11.0-27-generic    | 1         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 161       | 80.5%   |
| 5.8.0   | 32        | 16%     |
| 5.11.0  | 3         | 1.5%    |
| 5.3.0   | 2         | 1%      |
| 5.9.3   | 1         | 0.5%    |
| 5.8.17  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 161       | 80.5%   |
| 5.8     | 33        | 16.5%   |
| 5.11    | 3         | 1.5%    |
| 5.3     | 2         | 1%      |
| 5.9     | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 199       | 99.5%   |
| aarch64 | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 197       | 98.5%   |
| X-Cinnamon | 1         | 0.5%    |
| i3         | 1         | 0.5%    |
| GNOME      | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 196       | 98%     |
| Wayland | 2         | 1%      |
| Tty     | 2         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 98        | 47.8%   |
| Unknown | 68        | 33.17%  |
| LightDM | 25        | 12.2%   |
| GDM     | 13        | 6.34%   |
| SDDM    | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 64        | 31.84%  |
| pt_BR   | 27        | 13.43%  |
| fr_FR   | 18        | 8.96%   |
| en_GB   | 13        | 6.47%   |
| de_DE   | 12        | 5.97%   |
| it_IT   | 9         | 4.48%   |
| es_ES   | 8         | 3.98%   |
| ru_RU   | 7         | 3.48%   |
| ru_UA   | 4         | 1.99%   |
| pl_PL   | 4         | 1.99%   |
| es_AR   | 4         | 1.99%   |
| C       | 4         | 1.99%   |
| en_PH   | 3         | 1.49%   |
| nl_NL   | 2         | 1%      |
| de_CH   | 2         | 1%      |
| ca_ES   | 2         | 1%      |
| uk_UA   | 1         | 0.5%    |
| sv_SE   | 1         | 0.5%    |
| sk_SK   | 1         | 0.5%    |
| hu_HU   | 1         | 0.5%    |
| fr_CA   | 1         | 0.5%    |
| fr_BE   | 1         | 0.5%    |
| fi_FI   | 1         | 0.5%    |
| et_EE   | 1         | 0.5%    |
| es_UY   | 1         | 0.5%    |
| es_PE   | 1         | 0.5%    |
| es_MX   | 1         | 0.5%    |
| en_IN   | 1         | 0.5%    |
| en_IE   | 1         | 0.5%    |
| en_CA   | 1         | 0.5%    |
| en_AU   | 1         | 0.5%    |
| da_DK   | 1         | 0.5%    |
| cs_CZ   | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 103       | 51.5%   |
| EFI  | 97        | 48.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 186       | 92.08%  |
| Overlay | 8         | 3.96%   |
| Btrfs   | 3         | 1.49%   |
| Zfs     | 2         | 0.99%   |
| Xfs     | 2         | 0.99%   |
| Ext3    | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 72        | 35.64%  |
| Unknown | 69        | 34.16%  |
| MBR     | 61        | 30.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 181       | 89.16%  |
| Yes       | 22        | 10.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 71.64%  |
| Yes       | 57        | 28.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 47        | 23.5%   |
| Hewlett-Packard        | 42        | 21%     |
| Dell                   | 42        | 21%     |
| ASUSTek Computer       | 15        | 7.5%    |
| Acer                   | 13        | 6.5%    |
| MSI                    | 7         | 3.5%    |
| Toshiba                | 6         | 3%      |
| Samsung Electronics    | 5         | 2.5%    |
| Sony                   | 3         | 1.5%    |
| Positivo               | 2         | 1%      |
| Packard Bell           | 2         | 1%      |
| Notebook               | 2         | 1%      |
| Medion                 | 2         | 1%      |
| Wortmann AG            | 1         | 0.5%    |
| Teclast                | 1         | 0.5%    |
| System76               | 1         | 0.5%    |
| Star Labs              | 1         | 0.5%    |
| Pine Microsystems      | 1         | 0.5%    |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.5%    |
| Intel                  | 1         | 0.5%    |
| GPD                    | 1         | 0.5%    |
| Cube                   | 1         | 0.5%    |
| Chuwi                  | 1         | 0.5%    |
| Apple                  | 1         | 0.5%    |
| Unknown                | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Latitude E6420                        | 5         | 2.5%    |
| HP Notebook                                | 3         | 1.5%    |
| Dell Precision M4800                       | 3         | 1.5%    |
| Dell Latitude E6410                        | 3         | 1.5%    |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1%      |
| HP Pavilion g6                             | 2         | 1%      |
| HP Pavilion dv7                            | 2         | 1%      |
| HP EliteBook 8470p                         | 2         | 1%      |
| Dell Latitude E6430                        | 2         | 1%      |
| Dell Inspiron 3421                         | 2         | 1%      |
| ASUS ZenBook UX431DA_UM431DA               | 2         | 1%      |
| Wortmann AG TERRA_MOBILE_1749              | 1         | 0.5%    |
| Toshiba Satellite Pro L500                 | 1         | 0.5%    |
| Toshiba Satellite Pro C660                 | 1         | 0.5%    |
| Toshiba Satellite M500                     | 1         | 0.5%    |
| Toshiba Satellite L350D                    | 1         | 0.5%    |
| Toshiba Satellite C675                     | 1         | 0.5%    |
| Toshiba Satellite C660                     | 1         | 0.5%    |
| Teclast F15S                               | 1         | 0.5%    |
| System76 Serval WS                         | 1         | 0.5%    |
| Star Labs LabTop                           | 1         | 0.5%    |
| Sony VPCS12X9E                             | 1         | 0.5%    |
| Sony VPCF1290X                             | 1         | 0.5%    |
| Sony VPCEH1S1E                             | 1         | 0.5%    |
| Samsung SR58P                              | 1         | 0.5%    |
| Samsung 550P5C/550P7C                      | 1         | 0.5%    |
| Samsung 530U4E/540U4E                      | 1         | 0.5%    |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.5%    |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.5%    |
| Positivo N8X0EK1                           | 1         | 0.5%    |
| Positivo Mobile                            | 1         | 0.5%    |
| Pine Microsystems Pine64 Pinebook Pro      | 1         | 0.5%    |
| Packard Bell EasyNote SL65                 | 1         | 0.5%    |
| Packard Bell EasyNote ME69BMP              | 1         | 0.5%    |
| ONE-NETBOOK TECHNOLOGY A1                  | 1         | 0.5%    |
| Notebook W54_W94_W955TU,-T,-C              | 1         | 0.5%    |
| Notebook W310CZ/CZ-T                       | 1         | 0.5%    |
| MSI GV62 8RD                               | 1         | 0.5%    |
| MSI GP72MVR 7RFX                           | 1         | 0.5%    |
| MSI GP72 6QF                               | 1         | 0.5%    |
| MSI GF63 Thin 9SCSR                        | 1         | 0.5%    |
| MSI GE72 7RE                               | 1         | 0.5%    |
| MSI GE60 2OC\2OD\2OE                       | 1         | 0.5%    |
| MSI CR70 2M/CX70 2OC/CX70 2OD              | 1         | 0.5%    |
| Medion X682X                               | 1         | 0.5%    |
| Medion E15302                              | 1         | 0.5%    |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.5%    |
| Lenovo V570 HuronRiver Platform            | 1         | 0.5%    |
| Lenovo ThinkPad X270 20HN0013MX            | 1         | 0.5%    |
| Lenovo ThinkPad X250 20CLA32VLM            | 1         | 0.5%    |
| Lenovo ThinkPad X240 qqqq                  | 1         | 0.5%    |
| Lenovo ThinkPad X240 20AMS08816            | 1         | 0.5%    |
| Lenovo ThinkPad X230 23253Z5               | 1         | 0.5%    |
| Lenovo ThinkPad X201 Tablet 3093BL3        | 1         | 0.5%    |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW  | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 6th 20KH002HUS   | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0PS02   | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.5%    |
| Lenovo ThinkPad W530 24478K0               | 1         | 0.5%    |
| Lenovo ThinkPad W520 4284HP9               | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 32        | 16%     |
| Dell Latitude             | 18        | 9%      |
| HP Pavilion               | 13        | 6.5%    |
| Acer Aspire               | 11        | 5.5%    |
| Lenovo IdeaPad            | 8         | 4%      |
| HP EliteBook              | 8         | 4%      |
| Dell Inspiron             | 8         | 4%      |
| Toshiba Satellite         | 6         | 3%      |
| Dell Precision            | 6         | 3%      |
| HP 250                    | 5         | 2.5%    |
| HP ProBook                | 4         | 2%      |
| Dell XPS                  | 4         | 2%      |
| HP Notebook               | 3         | 1.5%    |
| ASUS VivoBook             | 3         | 1.5%    |
| Packard Bell EasyNote     | 2         | 1%      |
| Lenovo Legion             | 2         | 1%      |
| HP ZBook                  | 2         | 1%      |
| HP Laptop                 | 2         | 1%      |
| HP Compaq                 | 2         | 1%      |
| Dell Vostro               | 2         | 1%      |
| Dell Studio               | 2         | 1%      |
| ASUS ZenBook              | 2         | 1%      |
| Wortmann AG TERRA         | 1         | 0.5%    |
| Teclast F15S              | 1         | 0.5%    |
| System76 Serval           | 1         | 0.5%    |
| Star Labs LabTop          | 1         | 0.5%    |
| Sony VPCS12X9E            | 1         | 0.5%    |
| Sony VPCF1290X            | 1         | 0.5%    |
| Sony VPCEH1S1E            | 1         | 0.5%    |
| Samsung SR58P             | 1         | 0.5%    |
| Samsung 550P5C            | 1         | 0.5%    |
| Samsung 530U4E            | 1         | 0.5%    |
| Samsung 350V5C            | 1         | 0.5%    |
| Samsung 300E4A            | 1         | 0.5%    |
| Positivo N8X0EK1          | 1         | 0.5%    |
| Positivo Mobile           | 1         | 0.5%    |
| Pine Microsystems Pine64  | 1         | 0.5%    |
| ONE-NETBOOK TECHNOLOGY A1 | 1         | 0.5%    |
| Notebook W54              | 1         | 0.5%    |
| Notebook W310CZ           | 1         | 0.5%    |
| MSI GV62                  | 1         | 0.5%    |
| MSI GP72MVR               | 1         | 0.5%    |
| MSI GP72                  | 1         | 0.5%    |
| MSI GF63                  | 1         | 0.5%    |
| MSI GE72                  | 1         | 0.5%    |
| MSI GE60                  | 1         | 0.5%    |
| MSI CR70                  | 1         | 0.5%    |
| Medion X682X              | 1         | 0.5%    |
| Medion E15302             | 1         | 0.5%    |
| Lenovo Yoga               | 1         | 0.5%    |
| Lenovo V570               | 1         | 0.5%    |
| Lenovo ThinkBook          | 1         | 0.5%    |
| Lenovo G50-80             | 1         | 0.5%    |
| Lenovo Flex               | 1         | 0.5%    |
| Intel AMI                 | 1         | 0.5%    |
| HP G42                    | 1         | 0.5%    |
| HP 255                    | 1         | 0.5%    |
| HP 15                     | 1         | 0.5%    |
| GPD MicroPC               | 1         | 0.5%    |
| Dell G7                   | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 29        | 14.5%   |
| 2018    | 26        | 13%     |
| 2019    | 23        | 11.5%   |
| 2011    | 22        | 11%     |
| 2013    | 19        | 9.5%    |
| 2015    | 14        | 7%      |
| 2014    | 12        | 6%      |
| 2016    | 11        | 5.5%    |
| 2012    | 11        | 5.5%    |
| 2010    | 7         | 3.5%    |
| 2008    | 7         | 3.5%    |
| 2021    | 6         | 3%      |
| 2017    | 6         | 3%      |
| 2009    | 6         | 3%      |
| Unknown | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 200       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 182       | 90.55%  |
| Enabled  | 19        | 9.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 200       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 62        | 30.69%  |
| 4.01-8.0    | 57        | 28.22%  |
| 8.01-16.0   | 29        | 14.36%  |
| 16.01-24.0  | 28        | 13.86%  |
| 32.01-64.0  | 12        | 5.94%   |
| 2.01-3.0    | 5         | 2.48%   |
| 1.01-2.0    | 4         | 1.98%   |
| 24.01-32.0  | 3         | 1.49%   |
| 64.01-256.0 | 2         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 80        | 37.56%  |
| 2.01-3.0  | 59        | 27.7%   |
| 4.01-8.0  | 28        | 13.15%  |
| 3.01-4.0  | 23        | 10.8%   |
| 0.51-1.0  | 19        | 8.92%   |
| 8.01-16.0 | 4         | 1.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 145       | 71.08%  |
| 2      | 50        | 24.51%  |
| 3      | 7         | 3.43%   |
| 4      | 1         | 0.49%   |
| 0      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 52.74%  |
| Yes       | 95        | 47.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 87.5%   |
| No        | 25        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 98.01%  |
| No        | 4         | 1.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 76.24%  |
| No        | 48        | 23.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 32        | 15.92%  |
| USA         | 21        | 10.45%  |
| France      | 20        | 9.95%   |
| Germany     | 18        | 8.96%   |
| UK          | 12        | 5.97%   |
| Italy       | 11        | 5.47%   |
| Russia      | 10        | 4.98%   |
| Spain       | 9         | 4.48%   |
| Ukraine     | 7         | 3.48%   |
| Argentina   | 5         | 2.49%   |
| Switzerland | 4         | 1.99%   |
| Netherlands | 4         | 1.99%   |
| Turkey      | 3         | 1.49%   |
| Poland      | 3         | 1.49%   |
| Norway      | 3         | 1.49%   |
| Finland     | 3         | 1.49%   |
| Vietnam     | 2         | 1%      |
| Sweden      | 2         | 1%      |
| Philippines | 2         | 1%      |
| Mexico      | 2         | 1%      |
| Ireland     | 2         | 1%      |
| Indonesia   | 2         | 1%      |
| Chile       | 2         | 1%      |
| Canada      | 2         | 1%      |
| Uruguay     | 1         | 0.5%    |
| Thailand    | 1         | 0.5%    |
| Slovakia    | 1         | 0.5%    |
| Réunion    | 1         | 0.5%    |
| Peru        | 1         | 0.5%    |
| Malaysia    | 1         | 0.5%    |
| Luxembourg  | 1         | 0.5%    |
| Kenya       | 1         | 0.5%    |
| India       | 1         | 0.5%    |
| Hungary     | 1         | 0.5%    |
| Greece      | 1         | 0.5%    |
| Estonia     | 1         | 0.5%    |
| Ecuador     | 1         | 0.5%    |
| Denmark     | 1         | 0.5%    |
| Czechia     | 1         | 0.5%    |
| Croatia     | 1         | 0.5%    |
| Belgium     | 1         | 0.5%    |
| Belarus     | 1         | 0.5%    |
| Austria     | 1         | 0.5%    |
| Australia   | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| São Paulo             | 8         | 3.86%   |
| Itatiba                | 5         | 2.42%   |
| Rome                   | 4         | 1.93%   |
| Paris                  | 4         | 1.93%   |
| Rio de Janeiro         | 3         | 1.45%   |
| Jundiaí               | 3         | 1.45%   |
| Srednyaya Akhtuba      | 2         | 0.97%   |
| Oslo                   | 2         | 0.97%   |
| Marseille              | 2         | 0.97%   |
| Manchester             | 2         | 0.97%   |
| Le Kremlin-Bicetre     | 2         | 0.97%   |
| Kyiv                   | 2         | 0.97%   |
| Ho Chi Minh City       | 2         | 0.97%   |
| Herriman               | 2         | 0.97%   |
| Essen                  | 2         | 0.97%   |
| Durham                 | 2         | 0.97%   |
| Dublin                 | 2         | 0.97%   |
| Berlin                 | 2         | 0.97%   |
| Basel                  | 2         | 0.97%   |
| Barcelona              | 2         | 0.97%   |
| Ankara                 | 2         | 0.97%   |
| Zapopan                | 1         | 0.48%   |
| Zagreb                 | 1         | 0.48%   |
| Willimantic            | 1         | 0.48%   |
| West Babylon           | 1         | 0.48%   |
| Wake Forest            | 1         | 0.48%   |
| Viña del Mar          | 1         | 0.48%   |
| Vigo                   | 1         | 0.48%   |
| Vigneux-sur-Seine      | 1         | 0.48%   |
| Vienna                 | 1         | 0.48%   |
| Vedrin                 | 1         | 0.48%   |
| Ulm                    | 1         | 0.48%   |
| Trondheim              | 1         | 0.48%   |
| Toulouse               | 1         | 0.48%   |
| Thessaloniki           | 1         | 0.48%   |
| Thaire                 | 1         | 0.48%   |
| Tampere                | 1         | 0.48%   |
| São José dos Pinhais | 1         | 0.48%   |
| São José dos Campos  | 1         | 0.48%   |
| Sydney                 | 1         | 0.48%   |
| Sutton Coldfield       | 1         | 0.48%   |
| Seville                | 1         | 0.48%   |
| Sevastopol             | 1         | 0.48%   |
| Schwanden              | 1         | 0.48%   |
| S??o Paulo             | 1         | 0.48%   |
| Santos                 | 1         | 0.48%   |
| Santarém              | 1         | 0.48%   |
| Salta                  | 1         | 0.48%   |
| Saco                   | 1         | 0.48%   |
| Royal Oak              | 1         | 0.48%   |
| Riisipere              | 1         | 0.48%   |
| Reynosa                | 1         | 0.48%   |
| Ratingen               | 1         | 0.48%   |
| Quezon City            | 1         | 0.48%   |
| Presidente Prudente    | 1         | 0.48%   |
| Prague                 | 1         | 0.48%   |
| Poussan                | 1         | 0.48%   |
| Porto Alegre           | 1         | 0.48%   |
| Portland               | 1         | 0.48%   |
| Petaling Jaya          | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 37        | 43     | 14.62%  |
| Seagate               | 37        | 40     | 14.62%  |
| Samsung Electronics   | 32        | 37     | 12.65%  |
| Toshiba               | 26        | 32     | 10.28%  |
| Kingston              | 23        | 28     | 9.09%   |
| Unknown               | 13        | 16     | 5.14%   |
| SanDisk               | 10        | 13     | 3.95%   |
| Hitachi               | 10        | 11     | 3.95%   |
| Intel                 | 9         | 10     | 3.56%   |
| SK Hynix              | 8         | 11     | 3.16%   |
| Crucial               | 7         | 12     | 2.77%   |
| China                 | 5         | 6      | 1.98%   |
| HGST                  | 4         | 4      | 1.58%   |
| A-DATA Technology     | 4         | 4      | 1.58%   |
| PNY                   | 3         | 3      | 1.19%   |
| Phison                | 2         | 2      | 0.79%   |
| Patriot               | 2         | 2      | 0.79%   |
| Micron Technology     | 2         | 2      | 0.79%   |
| KIOXIA                | 2         | 2      | 0.79%   |
| Fujitsu               | 2         | 2      | 0.79%   |
| Vaseky                | 1         | 1      | 0.4%    |
| Transcend             | 1         | 1      | 0.4%    |
| Solid State Storage   | 1         | 1      | 0.4%    |
| SMART                 | 1         | 1      | 0.4%    |
| Silicon Motion        | 1         | 1      | 0.4%    |
| Realtek Semiconductor | 1         | 1      | 0.4%    |
| PLEXTOR               | 1         | 1      | 0.4%    |
| OCZ                   | 1         | 1      | 0.4%    |
| Netac                 | 1         | 1      | 0.4%    |
| LITEONIT              | 1         | 2      | 0.4%    |
| KingSpec              | 1         | 1      | 0.4%    |
| Intenso               | 1         | 1      | 0.4%    |
| FORESEE               | 1         | 1      | 0.4%    |
| faspeed               | 1         | 1      | 0.4%    |
| Apacer                | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB SSD      | 7         | 2.7%    |
| Toshiba MQ01ABF050 500GB             | 6         | 2.32%   |
| Seagate ST320LT007-9ZV142 320GB      | 6         | 2.32%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 2.32%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.54%   |
| WDC WD10SPZX-21Z10T0 1TB             | 3         | 1.16%   |
| Unknown MMC Card  16GB               | 3         | 1.16%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.16%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.16%   |
| Intel SSDPEKNW512G8 512GB            | 3         | 1.16%   |
| Hitachi HTS545050B9A300 500GB        | 3         | 1.16%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.77%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 2         | 0.77%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.77%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 2         | 0.77%   |
| Unknown DA4064  64GB                 | 2         | 0.77%   |
| Toshiba MQ01ACF032 320GB             | 2         | 0.77%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.77%   |
| Toshiba MK7559GSXP 752GB             | 2         | 0.77%   |
| Seagate ST9500420AS 500GB            | 2         | 0.77%   |
| Seagate ST9250410AS 250GB            | 2         | 0.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.77%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.77%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.77%   |
| Samsung SSD 860 QVO 1TB              | 2         | 0.77%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.77%   |
| PNY CS900 240GB SSD                  | 2         | 0.77%   |
| Kingston SUV500MS120G 120GB SSD      | 2         | 0.77%   |
| Hitachi HTS547564A9E384 640GB        | 2         | 0.77%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.77%   |
| China SSD 120GB                      | 2         | 0.77%   |
| WDC WDS250G2X0C-00L350 250GB         | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.39%   |
| WDC WDS200T3X0C-00SJG0 2TB           | 1         | 0.39%   |
| WDC WDS120G1G0A-00SS50 120GB SSD     | 1         | 0.39%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.39%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.39%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.39%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.39%   |
| WDC WD7500BPVT-75HXZT1 752GB         | 1         | 0.39%   |
| WDC WD7500BPKX-75HPJT0 752GB         | 1         | 0.39%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.39%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.39%   |
| WDC WD5000LPLX-75ZNTT0 500GB         | 1         | 0.39%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.39%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.39%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.39%   |
| WDC WD10SPZX-75Z10T3 1TB             | 1         | 0.39%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.39%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.39%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.39%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 1         | 0.39%   |
| WDC PC SN520 SDAPNUW-256G-1202 256GB | 1         | 0.39%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 1         | 0.39%   |
| Vaseky V820/1TB SSD                  | 1         | 0.39%   |
| Unknown USDU1  64GB                  | 1         | 0.39%   |
| Unknown SU16G  16GB                  | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 39     | 36.63%  |
| WDC                 | 25        | 29     | 24.75%  |
| Toshiba             | 20        | 26     | 19.8%   |
| Hitachi             | 10        | 11     | 9.9%    |
| HGST                | 4         | 4      | 3.96%   |
| Samsung Electronics | 2         | 2      | 1.98%   |
| Fujitsu             | 2         | 2      | 1.98%   |
| Unknown             | 1         | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 28     | 24.21%  |
| Kingston            | 22        | 27     | 23.16%  |
| SanDisk             | 6         | 9      | 6.32%   |
| Crucial             | 6         | 11     | 6.32%   |
| WDC                 | 5         | 5      | 5.26%   |
| China               | 5         | 6      | 5.26%   |
| A-DATA Technology   | 4         | 4      | 4.21%   |
| Toshiba             | 3         | 3      | 3.16%   |
| PNY                 | 3         | 3      | 3.16%   |
| Intel               | 3         | 3      | 3.16%   |
| Vaseky              | 1         | 1      | 1.05%   |
| Transcend           | 1         | 1      | 1.05%   |
| SMART               | 1         | 1      | 1.05%   |
| SK Hynix            | 1         | 4      | 1.05%   |
| Seagate             | 1         | 1      | 1.05%   |
| PLEXTOR             | 1         | 1      | 1.05%   |
| Patriot             | 1         | 1      | 1.05%   |
| OCZ                 | 1         | 1      | 1.05%   |
| Netac               | 1         | 1      | 1.05%   |
| Micron Technology   | 1         | 1      | 1.05%   |
| LITEONIT            | 1         | 2      | 1.05%   |
| KingSpec            | 1         | 1      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| FORESEE             | 1         | 1      | 1.05%   |
| Apacer              | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 97        | 114    | 40.59%  |
| SSD     | 85        | 118    | 35.56%  |
| NVMe    | 45        | 49     | 18.83%  |
| MMC     | 11        | 14     | 4.6%    |
| Unknown | 1         | 1      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 226    | 72%     |
| NVMe | 45        | 49     | 20%     |
| MMC  | 11        | 14     | 4.89%   |
| SAS  | 7         | 7      | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 121       | 159    | 66.12%  |
| 0.51-1.0   | 53        | 60     | 28.96%  |
| 1.01-2.0   | 8         | 12     | 4.37%   |
| 4.01-10.0  | 1         | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 64        | 31.22%  |
| 101-250        | 52        | 25.37%  |
| 501-1000       | 38        | 18.54%  |
| 1-20           | 14        | 6.83%   |
| 1001-2000      | 10        | 4.88%   |
| 51-100         | 10        | 4.88%   |
| 21-50          | 7         | 3.41%   |
| More than 3000 | 5         | 2.44%   |
| 2001-3000      | 5         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 35.21%  |
| 21-50          | 36        | 16.9%   |
| 101-250        | 33        | 15.49%  |
| 51-100         | 33        | 15.49%  |
| 251-500        | 20        | 9.39%   |
| 501-1000       | 11        | 5.16%   |
| 1001-2000      | 3         | 1.41%   |
| More than 3000 | 1         | 0.47%   |
| 2001-3000      | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 15.38%  |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 7.69%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 3.85%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 3.85%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 3.85%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 3.85%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 3.85%   |
| Vaseky V820/1TB SSD               | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 3.85%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 3.85%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 3.85%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 3.85%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 3.85%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 3.85%   |
| OCZ VERTEX450 128GB SSD           | 1         | 1      | 3.85%   |
| Hitachi HTS722016K9A300 160GB     | 1         | 1      | 3.85%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 3.85%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 3.85%   |
| Fujitsu MHZ2320BH G1 320GB        | 1         | 1      | 3.85%   |
| China SSD 120GB                   | 1         | 1      | 3.85%   |
| A-DATA Technology SP900 64GB SSD  | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 30.77%  |
| WDC                 | 5         | 6      | 19.23%  |
| Toshiba             | 4         | 4      | 15.38%  |
| Hitachi             | 3         | 3      | 11.54%  |
| Vaseky              | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| OCZ                 | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 36.36%  |
| WDC                 | 5         | 6      | 22.73%  |
| Toshiba             | 4         | 4      | 18.18%  |
| Hitachi             | 3         | 3      | 13.64%  |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 84.62%  |
| SSD  | 4         | 4      | 15.38%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 110       | 146    | 51.64%  |
| Detected | 77        | 123    | 36.15%  |
| Malfunc  | 26        | 27     | 12.21%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153       | 69.23%  |
| AMD                              | 25        | 11.31%  |
| Sandisk                          | 10        | 4.52%   |
| SK Hynix                         | 7         | 3.17%   |
| Samsung Electronics              | 7         | 3.17%   |
| Toshiba America Info Systems     | 3         | 1.36%   |
| KIOXIA                           | 3         | 1.36%   |
| Silicon Motion                   | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] | 2         | 0.9%    |
| Phison Electronics               | 2         | 0.9%    |
| Union Memory (Shenzhen)          | 1         | 0.45%   |
| Solid State Storage Technology   | 1         | 0.45%   |
| Realtek Semiconductor            | 1         | 0.45%   |
| Nvidia                           | 1         | 0.45%   |
| Micron/Crucial Technology        | 1         | 0.45%   |
| Micron Technology                | 1         | 0.45%   |
| Kingston Technology Company      | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 9.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 9.02%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 20        | 8.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 6.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 4.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 3.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.46%   |
| Intel SSD 660P Series                                                            | 5         | 2.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.05%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.64%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.23%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.23%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.82%   |
| SK Hynix BC511                                                                   | 2         | 0.82%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.82%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.82%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.82%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.82%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.82%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.82%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.82%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.41%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.41%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.41%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.41%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.41%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.41%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 0.41%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.41%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.41%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.41%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.41%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.41%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.41%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.41%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.41%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 157       | 67.38%  |
| NVMe | 44        | 18.88%  |
| RAID | 17        | 7.3%    |
| IDE  | 15        | 6.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 85.5%   |
| AMD    | 28        | 14%     |
| ARM    | 1         | 0.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2%      |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2%      |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 2%      |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.5%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.5%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.5%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1%      |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 1%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1%      |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 1%      |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1%      |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1%      |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1%      |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1%      |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 1%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1%      |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1%      |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 1%      |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 2         | 1%      |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1%      |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1%      |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 1%      |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1%      |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1%      |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 2         | 1%      |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.5%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.5%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.5%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.5%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.5%    |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.5%    |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.5%    |
| Intel Pentium CPU 3560M @ 2.40GHz             | 1         | 0.5%    |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.5%    |
| Intel Genuine CPU T1600 @ 1.66GHz             | 1         | 0.5%    |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.5%    |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.5%    |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.5%    |
| Intel Core i7-9750HF CPU @ 2.60GHz            | 1         | 0.5%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.5%    |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.5%    |
| Intel Core i7-6920HQ CPU @ 2.90GHz            | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 60        | 30%     |
| Intel Core i5                  | 54        | 27%     |
| Intel Core i3                  | 18        | 9%      |
| Intel Core 2 Duo               | 10        | 5%      |
| Intel Celeron                  | 10        | 5%      |
| Intel Pentium                  | 7         | 3.5%    |
| Other                          | 5         | 2.5%    |
| AMD Ryzen 5                    | 5         | 2.5%    |
| AMD Ryzen 7                    | 4         | 2%      |
| AMD A6                         | 4         | 2%      |
| Intel Pentium Dual-Core        | 2         | 1%      |
| Intel Core m3                  | 2         | 1%      |
| AMD Ryzen 3                    | 2         | 1%      |
| AMD A8                         | 2         | 1%      |
| AMD A4                         | 2         | 1%      |
| Intel Pentium Silver           | 1         | 0.5%    |
| Intel Pentium Dual             | 1         | 0.5%    |
| Intel Genuine                  | 1         | 0.5%    |
| Intel Core M                   | 1         | 0.5%    |
| Intel Core 2 Extreme           | 1         | 0.5%    |
| Intel Celeron Dual-Core        | 1         | 0.5%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.5%    |
| AMD Ryzen 7 PRO                | 1         | 0.5%    |
| AMD Ryzen 5 PRO                | 1         | 0.5%    |
| AMD Phenom II                  | 1         | 0.5%    |
| AMD E                          | 1         | 0.5%    |
| AMD Athlon X2                  | 1         | 0.5%    |
| AMD Athlon                     | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 57.5%   |
| 4      | 73        | 36.5%   |
| 6      | 8         | 4%      |
| 8      | 2         | 1%      |
| 3      | 1         | 0.5%    |
| 1      | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 199       | 99.5%   |
| 2      | 1         | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 147       | 73.5%   |
| 1      | 53        | 26.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 200       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 24        | 11.88%  |
| Unknown    | 23        | 11.39%  |
| 0x306a9    | 22        | 10.89%  |
| 0x306d4    | 10        | 4.95%   |
| 0x806ec    | 9         | 4.46%   |
| 0x1067a    | 9         | 4.46%   |
| 0x40651    | 7         | 3.47%   |
| 0x306c3    | 7         | 3.47%   |
| 0x806ea    | 6         | 2.97%   |
| 0x806e9    | 6         | 2.97%   |
| 0x906ea    | 5         | 2.48%   |
| 0x406e3    | 5         | 2.48%   |
| 0x20655    | 5         | 2.48%   |
| 0x20652    | 5         | 2.48%   |
| 0x08108102 | 5         | 2.48%   |
| 0x06006705 | 5         | 2.48%   |
| 0x906e9    | 3         | 1.49%   |
| 0x706e5    | 3         | 1.49%   |
| 0x706a1    | 3         | 1.49%   |
| 0x6fd      | 3         | 1.49%   |
| 0x08600106 | 3         | 1.49%   |
| 0x906ed    | 2         | 0.99%   |
| 0x806c1    | 2         | 0.99%   |
| 0x6fa      | 2         | 0.99%   |
| 0x506e3    | 2         | 0.99%   |
| 0x506c9    | 2         | 0.99%   |
| 0x406c3    | 2         | 0.99%   |
| 0x30678    | 2         | 0.99%   |
| 0x30673    | 2         | 0.99%   |
| 0x106e5    | 2         | 0.99%   |
| 0x10676    | 2         | 0.99%   |
| 0x08108109 | 2         | 0.99%   |
| 0x08101016 | 2         | 0.99%   |
| 0x02000032 | 2         | 0.99%   |
| 0xa0660    | 1         | 0.5%    |
| 0x406c4    | 1         | 0.5%    |
| 0x08701013 | 1         | 0.5%    |
| 0x08101007 | 1         | 0.5%    |
| 0x07030105 | 1         | 0.5%    |
| 0x07030104 | 1         | 0.5%    |
| 0x06006704 | 1         | 0.5%    |
| 0x05000029 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 37        | 18.5%   |
| SandyBridge     | 26        | 13%     |
| IvyBridge       | 24        | 12%     |
| Haswell         | 17        | 8.5%    |
| Broadwell       | 13        | 6.5%    |
| Penryn          | 11        | 5.5%    |
| Westmere        | 10        | 5%      |
| Skylake         | 8         | 4%      |
| Zen+            | 7         | 3.5%    |
| Silvermont      | 7         | 3.5%    |
| Excavator       | 6         | 3%      |
| Core            | 5         | 2.5%    |
| Zen 2           | 4         | 2%      |
| Zen             | 3         | 1.5%    |
| Puma            | 3         | 1.5%    |
| IceLake         | 3         | 1.5%    |
| Goldmont plus   | 3         | 1.5%    |
| TigerLake       | 2         | 1%      |
| Nehalem         | 2         | 1%      |
| K8 & K10 hybrid | 2         | 1%      |
| Goldmont        | 2         | 1%      |
| Piledriver      | 1         | 0.5%    |
| K10             | 1         | 0.5%    |
| CometLake       | 1         | 0.5%    |
| Bobcat          | 1         | 0.5%    |
| Unknown         | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153       | 62.2%   |
| Nvidia                           | 48        | 19.51%  |
| AMD                              | 44        | 17.89%  |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 8.3%    |
| Intel HD Graphics 5500                                                                   | 12        | 4.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.16%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.77%   |
| AMD Picasso                                                                              | 7         | 2.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 2.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.19%   |
| Intel HD Graphics 630                                                                    | 3         | 1.19%   |
| Intel HD Graphics 530                                                                    | 3         | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.19%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.19%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.19%   |
| AMD Renoir                                                                               | 3         | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.19%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.79%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 2         | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.79%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.79%   |
| Intel HD Graphics 620                                                                    | 2         | 0.79%   |
| Intel HD Graphics 500                                                                    | 2         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.79%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 2         | 0.79%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.4%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.4%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.4%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.4%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.4%    |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.4%    |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.4%    |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.4%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.4%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.4%    |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.4%    |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 0.4%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.4%    |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.4%    |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.4%    |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.4%    |
| Nvidia GK104GLM [Quadro K5000M]                                                          | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 53.5%   |
| Intel + Nvidia | 35        | 17.5%   |
| 1 x AMD        | 28        | 14%     |
| 1 x Nvidia     | 13        | 6.5%    |
| Intel + AMD    | 11        | 5.5%    |
| 2 x AMD        | 4         | 2%      |
| Other          | 1         | 0.5%    |
| 1 x SiS        | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 163       | 81.09%  |
| Proprietary | 29        | 14.43%  |
| Unknown     | 9         | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 65.67%  |
| 1.01-2.0   | 21        | 10.45%  |
| 0.01-0.5   | 18        | 8.96%   |
| 0.51-1.0   | 14        | 6.97%   |
| 3.01-4.0   | 11        | 5.47%   |
| 2.01-3.0   | 3         | 1.49%   |
| 7.01-8.0   | 1         | 0.5%    |
| 5.01-6.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 23.18%  |
| LG Display              | 38        | 17.27%  |
| Samsung Electronics     | 32        | 14.55%  |
| Chimei Innolux          | 28        | 12.73%  |
| BOE                     | 18        | 8.18%   |
| Dell                    | 9         | 4.09%   |
| PANDA                   | 6         | 2.73%   |
| Chi Mei Optoelectronics | 6         | 2.73%   |
| LG Philips              | 4         | 1.82%   |
| Sharp                   | 3         | 1.36%   |
| Philips                 | 3         | 1.36%   |
| Lenovo                  | 3         | 1.36%   |
| Goldstar                | 3         | 1.36%   |
| Sony                    | 2         | 0.91%   |
| InnoLux Display         | 2         | 0.91%   |
| Apple                   | 2         | 0.91%   |
| Acer                    | 2         | 0.91%   |
| Vizio                   | 1         | 0.45%   |
| Seiko/Epson             | 1         | 0.45%   |
| MS_ Nvidia              | 1         | 0.45%   |
| LGD                     | 1         | 0.45%   |
| InfoVision              | 1         | 0.45%   |
| Iiyama                  | 1         | 0.45%   |
| Hewlett-Packard         | 1         | 0.45%   |
| AOC                     | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 2.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 2.22%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 3         | 1.33%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch  | 2         | 0.89%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 2         | 0.89%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch           | 2         | 0.89%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.89%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch       | 2         | 0.89%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.89%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 2         | 0.89%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                   | 1         | 0.44%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch | 1         | 0.44%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                         | 1         | 0.44%   |
| Sharp LCD SHP4200 1920x1080 410x230mm 18.5-inch                       | 1         | 0.44%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.44%   |
| Seiko/Epson LCD Monitor 1440x900                                      | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch  | 1         | 0.44%   |
| Samsung Electronics SMBX2450L SAM0720 1920x1080 521x293mm 23.5-inch   | 1         | 0.44%   |
| Samsung Electronics S23B300 SAM08AE 1680x1050 510x290mm 23.1-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3441 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 230x130mm 10.4-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC3243 1366x768 256x144mm 11.6-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SAM0470 1920x1080                     | 1         | 0.44%   |
| Samsung Electronics C27F591 SAM0D38 1920x1080 598x336mm 27.0-inch     | 1         | 0.44%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.44%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch             | 1         | 0.44%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 0.44%   |
| Philips 225PL PHL088D 1680x1050 474x296mm 22.0-inch                   | 1         | 0.44%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| PANDA LCD Monitor NCP0032 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch               | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 77        | 37.02%  |
| 1366x768 (WXGA)    | 75        | 36.06%  |
| 1600x900 (HD+)     | 21        | 10.1%   |
| 1280x800 (WXGA)    | 11        | 5.29%   |
| 2560x1440 (QHD)    | 4         | 1.92%   |
| 1920x1200 (WUXGA)  | 3         | 1.44%   |
| 1680x1050 (WSXGA+) | 3         | 1.44%   |
| 1440x900 (WXGA+)   | 3         | 1.44%   |
| 3840x2160 (4K)     | 2         | 0.96%   |
| 3200x1800 (QHD+)   | 2         | 0.96%   |
| 3440x1440          | 1         | 0.48%   |
| 2560x1600          | 1         | 0.48%   |
| 2160x1440          | 1         | 0.48%   |
| 1680x945           | 1         | 0.48%   |
| 1600x1200          | 1         | 0.48%   |
| 1400x1050          | 1         | 0.48%   |
| 1360x768           | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 87        | 39.37%  |
| 14      | 31        | 14.03%  |
| 13      | 30        | 13.57%  |
| 17      | 20        | 9.05%   |
| 12      | 9         | 4.07%   |
| 23      | 8         | 3.62%   |
| 24      | 5         | 2.26%   |
| 21      | 5         | 2.26%   |
| 11      | 4         | 1.81%   |
| Unknown | 4         | 1.81%   |
| 27      | 3         | 1.36%   |
| 18      | 3         | 1.36%   |
| 22      | 2         | 0.9%    |
| 20      | 2         | 0.9%    |
| 10      | 2         | 0.9%    |
| 49      | 1         | 0.45%   |
| 40      | 1         | 0.45%   |
| 34      | 1         | 0.45%   |
| 29      | 1         | 0.45%   |
| 19      | 1         | 0.45%   |
| 8       | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 59.55%  |
| 201-300     | 27        | 12.27%  |
| 351-400     | 25        | 11.36%  |
| 501-600     | 15        | 6.82%   |
| 401-500     | 13        | 5.91%   |
| Unknown     | 4         | 1.82%   |
| 801-900     | 1         | 0.45%   |
| 701-800     | 1         | 0.45%   |
| 601-700     | 1         | 0.45%   |
| 101-200     | 1         | 0.45%   |
| 1001-1500   | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 176       | 86.27%  |
| 16/10   | 19        | 9.31%   |
| 3/2     | 3         | 1.47%   |
| Unknown | 3         | 1.47%   |
| 4/3     | 1         | 0.49%   |
| 21/9    | 1         | 0.49%   |
| 0.62    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 38.91%  |
| 81-90          | 50        | 22.62%  |
| 201-250        | 17        | 7.69%   |
| 121-130        | 15        | 6.79%   |
| 71-80          | 11        | 4.98%   |
| 61-70          | 9         | 4.07%   |
| 131-140        | 5         | 2.26%   |
| 51-60          | 4         | 1.81%   |
| Unknown        | 4         | 1.81%   |
| 301-350        | 3         | 1.36%   |
| 251-300        | 3         | 1.36%   |
| 151-200        | 3         | 1.36%   |
| 141-150        | 3         | 1.36%   |
| 351-500        | 2         | 0.9%    |
| 41-50          | 2         | 0.9%    |
| More than 1000 | 1         | 0.45%   |
| 1-40           | 1         | 0.45%   |
| 501-1000       | 1         | 0.45%   |
| 91-100         | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 81        | 37.16%  |
| 101-120       | 77        | 35.32%  |
| 51-100        | 38        | 17.43%  |
| 161-240       | 12        | 5.5%    |
| More than 240 | 5         | 2.29%   |
| Unknown       | 4         | 1.83%   |
| 1-50          | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 83%     |
| 2     | 26        | 13%     |
| 3     | 4         | 2%      |
| 0     | 4         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 106       | 33.54%  |
| Realtek Semiconductor             | 103       | 32.59%  |
| Qualcomm Atheros                  | 55        | 17.41%  |
| Broadcom                          | 21        | 6.65%   |
| Broadcom Limited                  | 8         | 2.53%   |
| Ralink                            | 4         | 1.27%   |
| Marvell Technology Group          | 4         | 1.27%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.63%   |
| Sierra Wireless                   | 2         | 0.63%   |
| Ralink Technology                 | 2         | 0.63%   |
| Xiaomi                            | 1         | 0.32%   |
| TP-Link                           | 1         | 0.32%   |
| Tenda                             | 1         | 0.32%   |
| Qualcomm Atheros Communications   | 1         | 0.32%   |
| Lenovo                            | 1         | 0.32%   |
| Hewlett-Packard                   | 1         | 0.32%   |
| Fibocom                           | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| Dell                              | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 17.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 7.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 5.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 3.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 3.1%    |
| Intel Wireless 7260                                               | 12        | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.07%   |
| Intel Wireless 7265                                               | 8         | 2.07%   |
| Intel Wireless 3165                                               | 8         | 2.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.81%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.81%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.29%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.29%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.78%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.78%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 3         | 0.78%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 3         | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.52%   |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 0.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 2         | 0.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.52%   |
| Intel Wireless-AC 9260                                            | 2         | 0.52%   |
| Intel Wireless 8260                                               | 2         | 0.52%   |
| Intel WiFi Link 5100                                              | 2         | 0.52%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.26%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.26%   |
| Tenda U12                                                         | 1         | 0.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.26%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.26%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.26%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.26%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 48.54%  |
| Qualcomm Atheros                | 45        | 21.84%  |
| Realtek Semiconductor           | 26        | 12.62%  |
| Broadcom                        | 16        | 7.77%   |
| Broadcom Limited                | 7         | 3.4%    |
| Ralink                          | 4         | 1.94%   |
| Ralink Technology               | 2         | 0.97%   |
| TP-Link                         | 1         | 0.49%   |
| Tenda                           | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| Hewlett-Packard                 | 1         | 0.49%   |
| Fibocom                         | 1         | 0.49%   |
| Dell                            | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 6.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 5.83%   |
| Intel Wireless 7260                                                     | 12        | 5.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 4.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 4.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.88%   |
| Intel Wireless 7265                                                     | 8         | 3.88%   |
| Intel Wireless 3165                                                     | 8         | 3.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.4%    |
| Intel Wireless 8265 / 8275                                              | 7         | 3.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.43%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.43%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 2.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.46%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.46%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.46%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.46%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 1.46%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 1.46%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.97%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.97%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.97%   |
| Intel Wireless 8260                                                     | 2         | 0.97%   |
| Intel WiFi Link 5100                                                    | 2         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.49%   |
| Tenda U12                                                               | 1         | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.49%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.49%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.49%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.49%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.49%   |
| Intel Wireless 3160                                                     | 1         | 0.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.49%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.49%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.49%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.49%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 98        | 54.75%  |
| Intel                            | 54        | 30.17%  |
| Qualcomm Atheros                 | 11        | 6.15%   |
| Broadcom                         | 5         | 2.79%   |
| Marvell Technology Group         | 4         | 2.23%   |
| Silicon Integrated Systems [SiS] | 2         | 1.12%   |
| Sierra Wireless                  | 2         | 1.12%   |
| Xiaomi                           | 1         | 0.56%   |
| Lenovo                           | 1         | 0.56%   |
| Broadcom Limited                 | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 36.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 15.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 11.11%  |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.78%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 1.11%   |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.11%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.11%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.56%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.56%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 197       | 52.82%  |
| Ethernet | 175       | 46.92%  |
| Modem    | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 64.08%  |
| Ethernet | 102       | 35.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 164       | 81.59%  |
| 1     | 35        | 17.41%  |
| 3     | 1         | 0.5%    |
| 0     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 187       | 93.03%  |
| Yes  | 14        | 6.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 45.16%  |
| Qualcomm Atheros Communications | 21        | 13.55%  |
| Realtek Semiconductor           | 16        | 10.32%  |
| Broadcom                        | 16        | 10.32%  |
| Dell                            | 9         | 5.81%   |
| IMC Networks                    | 7         | 4.52%   |
| Lite-On Technology              | 6         | 3.87%   |
| Foxconn / Hon Hai               | 3         | 1.94%   |
| Cambridge Silicon Radio         | 3         | 1.94%   |
| Ralink Technology               | 1         | 0.65%   |
| Ralink                          | 1         | 0.65%   |
| ASUSTek Computer                | 1         | 0.65%   |
| Apple                           | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 41        | 26.45%  |
| Intel Bluetooth wireless interface                  | 21        | 13.55%  |
| Realtek Bluetooth Radio                             | 8         | 5.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 4.52%   |
| Dell DW375 Bluetooth Module                         | 6         | 3.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 3.23%   |
| IMC Networks Bluetooth Device                       | 5         | 3.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 2.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 2.58%   |
| Intel AX200 Bluetooth                               | 4         | 2.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 2.58%   |
| Lite-On Bluetooth Device                            | 3         | 1.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.94%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.29%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 1.29%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.29%   |
| Realtek 802.11n WLAN Adapter                        | 1         | 0.65%   |
| Ralink CSR BS8510                                   | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.65%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.65%   |
| IMC Networks BCM20702A0                             | 1         | 0.65%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.65%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.65%   |
| Broadcom HP Portable Valentine                      | 1         | 0.65%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.65%   |
| Apple Bluetooth HCI                                 | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 167       | 68.72%  |
| AMD                                            | 34        | 13.99%  |
| Nvidia                                         | 29        | 11.93%  |
| Silicon Integrated Systems [SiS]               | 2         | 0.82%   |
| Lenovo                                         | 2         | 0.82%   |
| Sony                                           | 1         | 0.41%   |
| Siemens Information and Communication Products | 1         | 0.41%   |
| Realtek Semiconductor                          | 1         | 0.41%   |
| Plantronics                                    | 1         | 0.41%   |
| Logitech                                       | 1         | 0.41%   |
| Generalplus Technology                         | 1         | 0.41%   |
| FiiO Electronics Technology                    | 1         | 0.41%   |
| Corsair                                        | 1         | 0.41%   |
| C-Media Electronics                            | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 6%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 4.33%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 4.33%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 13        | 4.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 3%      |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.67%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.67%   |
| AMD High Definition Audio Controller                                                              | 6         | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1%      |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1%      |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1%      |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.67%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.67%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.67%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.67%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.33%   |
| Siemens Information and Communication Products optiPoint 500                                      | 1         | 0.33%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.33%   |
| Plantronics C320-M                                                                                | 1         | 0.33%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia stereo controller                                                                          | 1         | 0.33%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.33%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.33%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Logitech Headset H390                                                                             | 1         | 0.33%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.33%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 0.33%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.33%   |
| FiiO Electronics Technology Q1                                                                    | 1         | 0.33%   |
| Corsair HS70 Pro Wireless Gaming Headset                                                          | 1         | 0.33%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 41        | 23.98%  |
| SK Hynix                                         | 33        | 19.3%   |
| Micron Technology                                | 21        | 12.28%  |
| Unknown                                          | 13        | 7.6%    |
| Kingston                                         | 13        | 7.6%    |
| Crucial                                          | 10        | 5.85%   |
| Elpida                                           | 7         | 4.09%   |
| Nanya Technology                                 | 6         | 3.51%   |
| Smart                                            | 5         | 2.92%   |
| Ramaxel Technology                               | 3         | 1.75%   |
| A-DATA Technology                                | 3         | 1.75%   |
| Unknown (ABCD)                                   | 2         | 1.17%   |
| Teikon                                           | 2         | 1.17%   |
| Patriot                                          | 2         | 1.17%   |
| GOODRAM                                          | 2         | 1.17%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.58%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.58%   |
| Team                                             | 1         | 0.58%   |
| Qimonda                                          | 1         | 0.58%   |
| Netlist                                          | 1         | 0.58%   |
| Corsair                                          | 1         | 0.58%   |
| ASint Technology                                 | 1         | 0.58%   |
| Apacer                                           | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s                              | 6         | 3.28%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                                | 4         | 2.19%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s                              | 4         | 2.19%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s                              | 3         | 1.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                                 | 2         | 1.09%   |
| Unknown RAM Module 2048MB SODIMM DRAM                                                 | 2         | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s                   | 2         | 1.09%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s                                 | 2         | 1.09%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                                | 2         | 1.09%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                             | 2         | 1.09%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                             | 2         | 1.09%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                                | 2         | 1.09%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s                             | 2         | 1.09%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM 1334MT/s                                   | 2         | 1.09%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s                                 | 2         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                              | 2         | 1.09%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s                              | 2         | 1.09%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s                              | 2         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                                 | 2         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s                                 | 2         | 1.09%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s                              | 2         | 1.09%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s                              | 2         | 1.09%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s                      | 2         | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s                              | 2         | 1.09%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s                              | 2         | 1.09%   |
| Crucial RAM CT51264BF160BJ.M8F 4096MB SODIMM DDR3 1600MT/s                            | 2         | 1.09%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s                            | 2         | 1.09%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8192MB SODIMM DDR4 2667MT/s                               | 2         | 1.09%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                                      | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                                        | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                                        | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                                        | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                                 | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                         | 1         | 0.55%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s                                       | 1         | 0.55%   |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                                      | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                                 | 1         | 0.55%   |
| Unknown RAM 53E1G32D2NP-046 8GB Row Of Chips LPDDR4 4267MT/s                          | 1         | 0.55%   |
| Unknown (0x4D342037305435363633515A332D43463720) RAM Module 2048MB SODIMM DDR 800MT/s | 1         | 0.55%   |
| Unknown (0x36345431323830323045444C322E35433220) RAM Module 1024MB SODIMM DDR 800MT/s | 1         | 0.55%   |
| Teikon RAM TMT251S6FR8C-H9HC 4096MB SODIMM DDR3 1333MT/s                              | 1         | 0.55%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s                                | 1         | 0.55%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s                                 | 1         | 0.55%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.55%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1067MT/s                                 | 1         | 0.55%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s                                 | 1         | 0.55%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s                              | 1         | 0.55%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                                      | 1         | 0.55%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                                      | 1         | 0.55%   |
| SK Hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s                                 | 1         | 0.55%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s                                | 1         | 0.55%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                                | 1         | 0.55%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s                                  | 1         | 0.55%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                             | 1         | 0.55%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s                             | 1         | 0.55%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s                             | 1         | 0.55%   |
| SK Hynix RAM HMT125S6TFR8C-G7 2GB SODIMM 1067MT/s                                     | 1         | 0.55%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s                             | 1         | 0.55%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM 1067MT/s                                     | 1         | 0.55%   |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s                          | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 72        | 49.32%  |
| DDR4   | 48        | 32.88%  |
| LPDDR4 | 6         | 4.11%   |
| LPDDR3 | 6         | 4.11%   |
| DDR2   | 6         | 4.11%   |
| SDRAM  | 5         | 3.42%   |
| DRAM   | 2         | 1.37%   |
| DDR    | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 132       | 92.31%  |
| Row Of Chips | 9         | 6.29%   |
| Chip         | 2         | 1.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 65        | 40.63%  |
| 8192  | 46        | 28.75%  |
| 2048  | 28        | 17.5%   |
| 16384 | 13        | 8.13%   |
| 1024  | 4         | 2.5%    |
| 32768 | 3         | 1.88%   |
| 1536  | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 28.4%   |
| 2667    | 32        | 19.75%  |
| 1334    | 17        | 10.49%  |
| 1333    | 13        | 8.02%   |
| 3200    | 10        | 6.17%   |
| 2133    | 9         | 5.56%   |
| 3266    | 6         | 3.7%    |
| 2400    | 6         | 3.7%    |
| Unknown | 5         | 3.09%   |
| 4199    | 4         | 2.47%   |
| 1067    | 3         | 1.85%   |
| 800     | 3         | 1.85%   |
| 667     | 3         | 1.85%   |
| 4267    | 1         | 0.62%   |
| 2048    | 1         | 0.62%   |
| 1066    | 1         | 0.62%   |
| 975     | 1         | 0.62%   |
| 533     | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| QinHeng CH340S                   | 1         | 33.33%  |
| Canon PIXMA MG2500 Series        | 1         | 33.33%  |
| Brother DCP-7055 scanner/printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 50%     |
| Seiko Epson ES-D400 [GT-S80]                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 54        | 29.83%  |
| Acer                                   | 19        | 10.5%   |
| Microdia                               | 17        | 9.39%   |
| Sunplus Innovation Technology          | 15        | 8.29%   |
| IMC Networks                           | 12        | 6.63%   |
| Realtek Semiconductor                  | 9         | 4.97%   |
| Ricoh                                  | 8         | 4.42%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.42%   |
| Quanta                                 | 7         | 3.87%   |
| Silicon Motion                         | 5         | 2.76%   |
| Lite-On Technology                     | 5         | 2.76%   |
| Suyin                                  | 4         | 2.21%   |
| Syntek                                 | 3         | 1.66%   |
| Logitech                               | 3         | 1.66%   |
| Apple                                  | 2         | 1.1%    |
| Y Media                                | 1         | 0.55%   |
| Samsung Electronics                    | 1         | 0.55%   |
| Ruision                                | 1         | 0.55%   |
| Primax Electronics                     | 1         | 0.55%   |
| Microsoft                              | 1         | 0.55%   |
| Lenovo                                 | 1         | 0.55%   |
| DJKANA1BIEMDD7                         | 1         | 0.55%   |
| Cubeternet                             | 1         | 0.55%   |
| Aveo Technology                        | 1         | 0.55%   |
| Alcor Micro                            | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony integrated camera                        | 16        | 8.79%   |
| Sunplus Integrated_Webcam_HD                     | 7         | 3.85%   |
| Acer Integrated Camera                           | 6         | 3.3%    |
| Acer BisonCam, NB Pro                            | 6         | 3.3%    |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 2.75%   |
| Ricoh HD Webcam                                  | 4         | 2.2%    |
| Microdia Laptop_Integrated_Webcam_HD             | 4         | 2.2%    |
| Sunplus Laptop_Integrated_Webcam_FHD             | 3         | 1.65%   |
| Realtek Integrated_Webcam_HD                     | 3         | 1.65%   |
| Microdia Integrated Webcam                       | 3         | 1.65%   |
| Lite-On HP HD Camera                             | 3         | 1.65%   |
| Chicony USB2.0 VGA UVC WebCam                    | 3         | 1.65%   |
| Chicony Integrated Camera (1280x720@30)          | 3         | 1.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 1.65%   |
| Syntek EasyCamera                                | 2         | 1.1%    |
| Silicon Motion WebCam SC-13HDL11939N             | 2         | 1.1%    |
| Ricoh Sony Visual Communication Camera           | 2         | 1.1%    |
| Ricoh Laptop_Integrated_Webcam_FHD               | 2         | 1.1%    |
| Realtek USB Camera                               | 2         | 1.1%    |
| Quanta VGA WebCam                                | 2         | 1.1%    |
| Quanta Laptop_Integrated_Webcam_2HDM             | 2         | 1.1%    |
| Quanta HD User Facing                            | 2         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_2M             | 2         | 1.1%    |
| Microdia Integrated_Webcam_HD                    | 2         | 1.1%    |
| Microdia Dell Integrated HD Webcam               | 2         | 1.1%    |
| Chicony USB2.0 UVC WebCam                        | 2         | 1.1%    |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 1.1%    |
| Chicony HP Wide Vision HD Camera                 | 2         | 1.1%    |
| Chicony HP Webcam-101                            | 2         | 1.1%    |
| Chicony HP HD Webcam [Fixed]                     | 2         | 1.1%    |
| Chicony HD WebCam (Acer)                         | 2         | 1.1%    |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 2         | 1.1%    |
| Acer Lenovo EasyCamera                           | 2         | 1.1%    |
| Y Media USB Camera                               | 1         | 0.55%   |
| Syntek USB Video Device                          | 1         | 0.55%   |
| Suyin Sony Visual Communication Camera           | 1         | 0.55%   |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 0.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 0.55%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.55%   |
| Sunplus Integrated_Webcam_FHD                    | 1         | 0.55%   |
| Sunplus HP Universal Camera                      | 1         | 0.55%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.55%   |
| Sunplus HD WebCam                                | 1         | 0.55%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.55%   |
| Silicon Motion WebCam SCB-1100N                  | 1         | 0.55%   |
| Silicon Motion WebCam SC-10HDP12631N             | 1         | 0.55%   |
| Silicon Motion 300k Pixel Camera                 | 1         | 0.55%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.55%   |
| Ruision UVC Camera                               | 1         | 0.55%   |
| Realtek Lenovo EasyCamera                        | 1         | 0.55%   |
| Realtek HP Truevision HD                         | 1         | 0.55%   |
| Realtek EasyCamera                               | 1         | 0.55%   |
| Realtek Acer 640 x 480 laptop camera             | 1         | 0.55%   |
| Quanta HP HD Camera                              | 1         | 0.55%   |
| Primax HP HD Webcam [Fixed]                      | 1         | 0.55%   |
| Microsoft LifeCam HD-3000                        | 1         | 0.55%   |
| Microdia USB 2.0 Camera                          | 1         | 0.55%   |
| Microdia HP Webcam-101                           | 1         | 0.55%   |
| Microdia HP Webcam                               | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 48.39%  |
| Synaptics                  | 8         | 25.81%  |
| Upek                       | 3         | 9.68%   |
| Shenzhen Goodix Technology | 2         | 6.45%   |
| Elan Microelectronics      | 2         | 6.45%   |
| Focal-systems.Corp         | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 9.68%   |
| Validity Sensors VFS491                                    | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 9.68%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 9.68%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 6.45%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                      | 2         | 6.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors Synaptics WBDI                            | 1         | 3.23%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 3.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 3.23%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 20        | 64.52%  |
| Alcor Micro           | 4         | 12.9%   |
| Upek                  | 2         | 6.45%   |
| Lenovo                | 2         | 6.45%   |
| O2 Micro              | 1         | 3.23%   |
| Gemalto (was Gemplus) | 1         | 3.23%   |
| Advanced Card Systems | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 32.26%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 22.58%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 12.9%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 6.45%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.45%   |
| Broadcom 58200                                                               | 2         | 6.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 3.23%   |
| Broadcom 5880                                                                | 1         | 3.23%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 124       | 60.78%  |
| 1     | 61        | 29.9%   |
| 2     | 16        | 7.84%   |
| 8     | 2         | 0.98%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 28.97%  |
| Chipcard                 | 30        | 28.04%  |
| Graphics card            | 19        | 17.76%  |
| Storage                  | 8         | 7.48%   |
| Net/wireless             | 5         | 4.67%   |
| Camera                   | 3         | 2.8%    |
| Bluetooth                | 3         | 2.8%    |
| Sound                    | 2         | 1.87%   |
| Communication controller | 2         | 1.87%   |
| Network                  | 1         | 0.93%   |
| Multimedia controller    | 1         | 0.93%   |
| Firewire controller      | 1         | 0.93%   |
| Card reader              | 1         | 0.93%   |


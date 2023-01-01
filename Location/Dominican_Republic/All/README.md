Linux in Dominican Republic - Tested Hardware & Statistics
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Dominican Republic.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Dominican_Republic/Desktop/README.md) and [notebooks](/Location/Dominican_Republic/Notebook/README.md).

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

Total: 191

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5420               | Notebook    | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | OptiPlex 3020               | Desktop     | [2adcd09348](https://linux-hardware.org/?probe=2adcd09348) | Nov 25, 2022 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [ac7791c167](https://linux-hardware.org/?probe=ac7791c167) | Nov 24, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [1a1f5f8d90](https://linux-hardware.org/?probe=1a1f5f8d90) | Nov 22, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [b2772ed1b3](https://linux-hardware.org/?probe=b2772ed1b3) | Nov 22, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | Notebook    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Dell          | Latitude 5590               | Notebook    | [bbb332cf90](https://linux-hardware.org/?probe=bbb332cf90) | Nov 11, 2022 |
| Dell          | 0VNP2H A00                  | Desktop     | [dff6013531](https://linux-hardware.org/?probe=dff6013531) | Nov 09, 2022 |
| Eluktronic... | P670RE3                     | Notebook    | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [ff4216edcd](https://linux-hardware.org/?probe=ff4216edcd) | Oct 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [240d883d49](https://linux-hardware.org/?probe=240d883d49) | Oct 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Dell          | Latitude 2110               | Notebook    | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [08bd609dbe](https://linux-hardware.org/?probe=08bd609dbe) | Sep 20, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [2b09076619](https://linux-hardware.org/?probe=2b09076619) | Jul 30, 2022 |
| Dell          | OptiPlex 780                | Desktop     | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | Latitude E5440              | Notebook    | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [9cd0caeff2](https://linux-hardware.org/?probe=9cd0caeff2) | Jul 14, 2022 |
| ECS           | ClassMate                   | Notebook    | [c86fa72fe1](https://linux-hardware.org/?probe=c86fa72fe1) | Jun 13, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [fb6db84371](https://linux-hardware.org/?probe=fb6db84371) | Jun 11, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [578aee86ed](https://linux-hardware.org/?probe=578aee86ed) | May 27, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e1e9853d49](https://linux-hardware.org/?probe=e1e9853d49) | May 26, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [62c1081de8](https://linux-hardware.org/?probe=62c1081de8) | May 23, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [c72447a3ea](https://linux-hardware.org/?probe=c72447a3ea) | May 03, 2022 |
| TODOS INDU... | Easytouch_2022_V1           | Notebook    | [efc26220c4](https://linux-hardware.org/?probe=efc26220c4) | May 01, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [454226474b](https://linux-hardware.org/?probe=454226474b) | Apr 29, 2022 |
| Gigabyte      | Z87X-UD5 TH-CF              | Desktop     | [5dc83ea64b](https://linux-hardware.org/?probe=5dc83ea64b) | Apr 24, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [3447b4c67a](https://linux-hardware.org/?probe=3447b4c67a) | Apr 07, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [9d5011b41d](https://linux-hardware.org/?probe=9d5011b41d) | Mar 23, 2022 |
| ASUSTek       | K53E                        | Notebook    | [3a0af085ae](https://linux-hardware.org/?probe=3a0af085ae) | Mar 17, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| Samsung       | 930QCG                      | Convertible | [fb417d6589](https://linux-hardware.org/?probe=fb417d6589) | Feb 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [2322337991](https://linux-hardware.org/?probe=2322337991) | Feb 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [507f27294e](https://linux-hardware.org/?probe=507f27294e) | Feb 15, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [53e23140c0](https://linux-hardware.org/?probe=53e23140c0) | Jan 23, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [b32fd5f07f](https://linux-hardware.org/?probe=b32fd5f07f) | Dec 07, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [9164883468](https://linux-hardware.org/?probe=9164883468) | Nov 27, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [b137bf3459](https://linux-hardware.org/?probe=b137bf3459) | Nov 27, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [e402a0b407](https://linux-hardware.org/?probe=e402a0b407) | Aug 31, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| HP            | 8265                        | Desktop     | [9a7e706a6b](https://linux-hardware.org/?probe=9a7e706a6b) | Aug 07, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7fc508d633](https://linux-hardware.org/?probe=7fc508d633) | Jul 19, 2021 |
| Google        | Winky                       | Notebook    | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ed828bab0](https://linux-hardware.org/?probe=3ed828bab0) | Jul 11, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [9b650cfab3](https://linux-hardware.org/?probe=9b650cfab3) | Jul 11, 2021 |
| Dell          | Latitude E6420              | Notebook    | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [772842d291](https://linux-hardware.org/?probe=772842d291) | Jul 06, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cc6035ae99](https://linux-hardware.org/?probe=cc6035ae99) | Jun 28, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fda4879b12](https://linux-hardware.org/?probe=fda4879b12) | Jun 19, 2021 |
| Dell          | Latitude E6530              | Notebook    | [40566262f5](https://linux-hardware.org/?probe=40566262f5) | Jun 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [9ec2685f9d](https://linux-hardware.org/?probe=9ec2685f9d) | Jun 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [6098210314](https://linux-hardware.org/?probe=6098210314) | Jun 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [2170036527](https://linux-hardware.org/?probe=2170036527) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d310246b09](https://linux-hardware.org/?probe=d310246b09) | Apr 30, 2021 |
| Dell          | Latitude D830               | Notebook    | [f6f0884fca](https://linux-hardware.org/?probe=f6f0884fca) | Apr 28, 2021 |
| Dell          | Latitude E6540              | Notebook    | [522d36a07e](https://linux-hardware.org/?probe=522d36a07e) | Apr 21, 2021 |
| Dell          | Latitude E6540              | Notebook    | [3c76496221](https://linux-hardware.org/?probe=3c76496221) | Apr 21, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [dc8b47f73d](https://linux-hardware.org/?probe=dc8b47f73d) | Feb 14, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [4adcccb57c](https://linux-hardware.org/?probe=4adcccb57c) | Feb 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [96d33743db](https://linux-hardware.org/?probe=96d33743db) | Jan 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [2cf1c789ec](https://linux-hardware.org/?probe=2cf1c789ec) | Dec 29, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | Notebook    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [f18b7b439b](https://linux-hardware.org/?probe=f18b7b439b) | Dec 05, 2020 |
| Fujitsu       | LIFEBOOK AH562              | Notebook    | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [012580c2a7](https://linux-hardware.org/?probe=012580c2a7) | Nov 10, 2020 |
| HP            | Notebook                    | Notebook    | [5176e73c5a](https://linux-hardware.org/?probe=5176e73c5a) | Oct 27, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [d6729d6c6a](https://linux-hardware.org/?probe=d6729d6c6a) | Oct 17, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [907bc464e9](https://linux-hardware.org/?probe=907bc464e9) | Oct 13, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [03c52e4d49](https://linux-hardware.org/?probe=03c52e4d49) | Oct 10, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| HP            | 3647h                       | Desktop     | [5788758b90](https://linux-hardware.org/?probe=5788758b90) | Oct 08, 2020 |
| Dell          | 0MM599                      | Desktop     | [fce90bd449](https://linux-hardware.org/?probe=fce90bd449) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fd73b699f6](https://linux-hardware.org/?probe=fd73b699f6) | Oct 05, 2020 |
| Dell          | Latitude D620               | Notebook    | [3832d0c33e](https://linux-hardware.org/?probe=3832d0c33e) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [80611690cf](https://linux-hardware.org/?probe=80611690cf) | Sep 13, 2020 |
| Dell          | Latitude D620               | Notebook    | [d14cb277b7](https://linux-hardware.org/?probe=d14cb277b7) | Sep 12, 2020 |
| HP            | ProBook 6470b               | Notebook    | [c622e7298d](https://linux-hardware.org/?probe=c622e7298d) | Sep 07, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9b34b0a6c3](https://linux-hardware.org/?probe=9b34b0a6c3) | Sep 03, 2020 |
| Dell          | Vostro 5471                 | Notebook    | [6d24c75bcf](https://linux-hardware.org/?probe=6d24c75bcf) | Sep 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [d24cd3858d](https://linux-hardware.org/?probe=d24cd3858d) | Aug 29, 2020 |
| Nuvision      | L1W6_I1101_G Reserved       | Notebook    | [b3e73aa9ba](https://linux-hardware.org/?probe=b3e73aa9ba) | Aug 29, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9eda45f755](https://linux-hardware.org/?probe=9eda45f755) | Aug 20, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d7d672869f](https://linux-hardware.org/?probe=d7d672869f) | Aug 16, 2020 |
| MSI           | H81M-E33                    | Desktop     | [ba3577fb00](https://linux-hardware.org/?probe=ba3577fb00) | Aug 14, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [081a2c3e4c](https://linux-hardware.org/?probe=081a2c3e4c) | Aug 03, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [6bedf88c28](https://linux-hardware.org/?probe=6bedf88c28) | Jul 30, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [fcbd102a50](https://linux-hardware.org/?probe=fcbd102a50) | Jul 30, 2020 |
| MSI           | B350 GAMING PLUS            | Desktop     | [ca22d3b169](https://linux-hardware.org/?probe=ca22d3b169) | Jul 24, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [4877877772](https://linux-hardware.org/?probe=4877877772) | Jul 04, 2020 |
| Dell          | Vostro A860                 | Notebook    | [16ded4e283](https://linux-hardware.org/?probe=16ded4e283) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| MSI           | H81M-E33                    | Desktop     | [2d531766ab](https://linux-hardware.org/?probe=2d531766ab) | Jun 26, 2020 |
| HP            | 250 G3                      | Notebook    | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Biostar       | G41D3C                      | Desktop     | [15959c0828](https://linux-hardware.org/?probe=15959c0828) | Jun 15, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | Notebook    | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | Notebook    | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | Notebook    | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | Notebook    | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | Notebook    | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| HP            | 3031h                       | Desktop     | [0278ac4043](https://linux-hardware.org/?probe=0278ac4043) | Apr 07, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [87496c419f](https://linux-hardware.org/?probe=87496c419f) | Apr 07, 2020 |
| Dell          | 0WG864                      | Desktop     | [b7c74749f8](https://linux-hardware.org/?probe=b7c74749f8) | Mar 30, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [860893085c](https://linux-hardware.org/?probe=860893085c) | Mar 29, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [48e8186c4f](https://linux-hardware.org/?probe=48e8186c4f) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [080f6bbb80](https://linux-hardware.org/?probe=080f6bbb80) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [740334eed7](https://linux-hardware.org/?probe=740334eed7) | Mar 28, 2020 |
| Dell          | Latitude 3330               | Notebook    | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [44fe9bdc7d](https://linux-hardware.org/?probe=44fe9bdc7d) | Mar 20, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [970faeadaf](https://linux-hardware.org/?probe=970faeadaf) | Mar 19, 2020 |
| HP            | 3031h                       | Desktop     | [3b10a92ee2](https://linux-hardware.org/?probe=3b10a92ee2) | Mar 19, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4f152e3015](https://linux-hardware.org/?probe=4f152e3015) | Mar 06, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [4775efe228](https://linux-hardware.org/?probe=4775efe228) | Feb 27, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [3212549df1](https://linux-hardware.org/?probe=3212549df1) | Feb 05, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [661a8243a3](https://linux-hardware.org/?probe=661a8243a3) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ee353d9346](https://linux-hardware.org/?probe=ee353d9346) | Feb 01, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [51c3c0bb31](https://linux-hardware.org/?probe=51c3c0bb31) | Jan 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [4df330ed80](https://linux-hardware.org/?probe=4df330ed80) | Jan 07, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [a61df97ccd](https://linux-hardware.org/?probe=a61df97ccd) | Dec 19, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [4437a2deed](https://linux-hardware.org/?probe=4437a2deed) | Dec 18, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [edddb5eb5b](https://linux-hardware.org/?probe=edddb5eb5b) | Dec 18, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [e4a03527b5](https://linux-hardware.org/?probe=e4a03527b5) | Dec 11, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [a760ea9cb2](https://linux-hardware.org/?probe=a760ea9cb2) | Nov 14, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [b2477d7154](https://linux-hardware.org/?probe=b2477d7154) | Nov 07, 2019 |
| Gigabyte      | B450 AORUS M                | Desktop     | [628a2983df](https://linux-hardware.org/?probe=628a2983df) | Nov 05, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [cb7b5a4d2e](https://linux-hardware.org/?probe=cb7b5a4d2e) | Oct 13, 2019 |
| Dell          | Latitude E6430              | Notebook    | [49d71b26e7](https://linux-hardware.org/?probe=49d71b26e7) | Oct 08, 2019 |
| Dell          | Latitude E6430              | Notebook    | [b3ef7b4357](https://linux-hardware.org/?probe=b3ef7b4357) | Oct 06, 2019 |
| Dell          | 0M132G A00                  | Desktop     | [b79e419f05](https://linux-hardware.org/?probe=b79e419f05) | Aug 24, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [9a7d44bf28](https://linux-hardware.org/?probe=9a7d44bf28) | Aug 15, 2019 |
| HP            | Pavilion ze2000 (EC201UA... | Notebook    | [572baa05f4](https://linux-hardware.org/?probe=572baa05f4) | Jun 15, 2019 |
| HP            | 3397                        | Desktop     | [24770f4baf](https://linux-hardware.org/?probe=24770f4baf) | Jun 06, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [412e4da0ce](https://linux-hardware.org/?probe=412e4da0ce) | May 21, 2019 |
| HP            | 3396                        | Desktop     | [46d189dc80](https://linux-hardware.org/?probe=46d189dc80) | May 20, 2019 |
| Lenovo        | G40-70 20369                | Notebook    | [1f456620db](https://linux-hardware.org/?probe=1f456620db) | May 05, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0b9c00412b](https://linux-hardware.org/?probe=0b9c00412b) | Dec 14, 2018 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [e30bc2b8f2](https://linux-hardware.org/?probe=e30bc2b8f2) | Nov 02, 2018 |
| Dell          | 0PU052                      | Desktop     | [a5f063bc44](https://linux-hardware.org/?probe=a5f063bc44) | Apr 19, 2018 |
| Dell          | 0PU052                      | Desktop     | [e8fb115c06](https://linux-hardware.org/?probe=e8fb115c06) | Jan 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 21        | 15.91%  |
| Ubuntu 18.04                 | 17        | 12.88%  |
| Ubuntu 22.04                 | 6         | 4.55%   |
| OpenMandriva 4.2             | 5         | 3.79%   |
| Arch Rolling                 | 5         | 3.79%   |
| OpenMandriva 4.3             | 4         | 3.03%   |
| Fedora 36                    | 4         | 3.03%   |
| Linux Mint 20.3              | 3         | 2.27%   |
| Fedora 34                    | 3         | 2.27%   |
| Debian 11                    | 3         | 2.27%   |
| Arch                         | 3         | 2.27%   |
| Ubuntu 21.10                 | 2         | 1.52%   |
| Pop!_OS 20.10                | 2         | 1.52%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.52%   |
| Linux Mint 21                | 2         | 1.52%   |
| Linux Mint 20.1              | 2         | 1.52%   |
| Linux Mint 19.3              | 2         | 1.52%   |
| Fedora 37                    | 2         | 1.52%   |
| Fedora 33                    | 2         | 1.52%   |
| ArcoLinux Rolling            | 2         | 1.52%   |
| Zorin 16                     | 1         | 0.76%   |
| Xubuntu 19.10                | 1         | 0.76%   |
| Xubuntu 18.04                | 1         | 0.76%   |
| Void Linux Rolling           | 1         | 0.76%   |
| Ubuntu Budgie 22.04          | 1         | 0.76%   |
| Ubuntu Budgie 21.10          | 1         | 0.76%   |
| Ubuntu Budgie 20.04          | 1         | 0.76%   |
| Ubuntu 22.10                 | 1         | 0.76%   |
| Ubuntu 21.04                 | 1         | 0.76%   |
| Ubuntu 19.10                 | 1         | 0.76%   |
| Ubuntu 19.04                 | 1         | 0.76%   |
| Solus 4.1                    | 1         | 0.76%   |
| ROSA R10                     | 1         | 0.76%   |
| Pop!_OS 22.04                | 1         | 0.76%   |
| Pop!_OS 21.04                | 1         | 0.76%   |
| Pop!_OS 20.04                | 1         | 0.76%   |
| OpenMandriva 4.90            | 1         | 0.76%   |
| Manjaro 22.0.0               | 1         | 0.76%   |
| Manjaro 21.2.3               | 1         | 0.76%   |
| Manjaro 21.1.2               | 1         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 48        | 36.92%  |
| Fedora        | 14        | 10.77%  |
| Linux Mint    | 11        | 8.46%   |
| OpenMandriva  | 10        | 7.69%   |
| Arch          | 8         | 6.15%   |
| Pop!_OS       | 5         | 3.85%   |
| Manjaro       | 4         | 3.08%   |
| Debian        | 4         | 3.08%   |
| Ubuntu Budgie | 3         | 2.31%   |
| Clear Linux   | 3         | 2.31%   |
| Xubuntu       | 2         | 1.54%   |
| openSUSE      | 2         | 1.54%   |
| KDE neon      | 2         | 1.54%   |
| ArcoLinux     | 2         | 1.54%   |
| Zorin         | 1         | 0.77%   |
| Void Linux    | 1         | 0.77%   |
| Solus         | 1         | 0.77%   |
| ROSA          | 1         | 0.77%   |
| Lubuntu       | 1         | 0.77%   |
| LMDE          | 1         | 0.77%   |
| Kubuntu       | 1         | 0.77%   |
| Kali          | 1         | 0.77%   |
| Elementary    | 1         | 0.77%   |
| CentOS        | 1         | 0.77%   |
| BlackPanther  | 1         | 0.77%   |
| Archcraft     | 1         | 0.77%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 4         | 2.68%   |
| 5.4.0-42-generic         | 4         | 2.68%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.68%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.68%   |
| 5.15.0-53-generic        | 3         | 2.01%   |
| 5.13.0-22-generic        | 3         | 2.01%   |
| 5.4.0-77-generic         | 2         | 1.34%   |
| 5.4.0-52-generic         | 2         | 1.34%   |
| 5.4.0-33-generic         | 2         | 1.34%   |
| 5.3.0-51-generic         | 2         | 1.34%   |
| 5.3.0-46-generic         | 2         | 1.34%   |
| 5.3.0-42-generic         | 2         | 1.34%   |
| 5.15.0-50-generic        | 2         | 1.34%   |
| 5.15.0-41-generic        | 2         | 1.34%   |
| 5.11.0-40-generic        | 2         | 1.34%   |
| 5.11.0-25-generic        | 2         | 1.34%   |
| 5.0.0-32-generic         | 2         | 1.34%   |
| 6.0.6-300.fc37.x86_64    | 1         | 0.67%   |
| 6.0.14-300.fc37.x86_64   | 1         | 0.67%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.67%   |
| 5.9.12-xanmod1           | 1         | 0.67%   |
| 5.9.11-arch2-1           | 1         | 0.67%   |
| 5.9.1-arch1-1            | 1         | 0.67%   |
| 5.8.8-arch1-1            | 1         | 0.67%   |
| 5.8.5-arch1-1            | 1         | 0.67%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.67%   |
| 5.8.12_1                 | 1         | 0.67%   |
| 5.8.0-38-generic         | 1         | 0.67%   |
| 5.7.7-zen1-1-zen         | 1         | 0.67%   |
| 5.7.7-arch1-1            | 1         | 0.67%   |
| 5.7.10-201.fc32.x86_64   | 1         | 0.67%   |
| 5.6.19-158.current       | 1         | 0.67%   |
| 5.5.13-arch1-1           | 1         | 0.67%   |
| 5.4.60-2-MANJARO         | 1         | 0.67%   |
| 5.4.4-879.native         | 1         | 0.67%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.67%   |
| 5.4.0-7642-generic       | 1         | 0.67%   |
| 5.4.0-74-generic         | 1         | 0.67%   |
| 5.4.0-72-generic         | 1         | 0.67%   |
| 5.4.0-39-generic         | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 18.12%  |
| 5.15.0  | 11        | 7.97%   |
| 5.13.0  | 10        | 7.25%   |
| 5.3.0   | 9         | 6.52%   |
| 5.11.0  | 8         | 5.8%    |
| 4.15.0  | 6         | 4.35%   |
| 5.0.0   | 5         | 3.62%   |
| 5.16.7  | 4         | 2.9%    |
| 5.10.14 | 4         | 2.9%    |
| 5.10.0  | 3         | 2.17%   |
| 5.7.7   | 2         | 1.45%   |
| 4.19.0  | 2         | 1.45%   |
| 4.18.0  | 2         | 1.45%   |
| 6.0.6   | 1         | 0.72%   |
| 6.0.14  | 1         | 0.72%   |
| 5.9.16  | 1         | 0.72%   |
| 5.9.12  | 1         | 0.72%   |
| 5.9.11  | 1         | 0.72%   |
| 5.9.1   | 1         | 0.72%   |
| 5.8.8   | 1         | 0.72%   |
| 5.8.5   | 1         | 0.72%   |
| 5.8.15  | 1         | 0.72%   |
| 5.8.12  | 1         | 0.72%   |
| 5.8.0   | 1         | 0.72%   |
| 5.7.10  | 1         | 0.72%   |
| 5.6.19  | 1         | 0.72%   |
| 5.5.13  | 1         | 0.72%   |
| 5.4.60  | 1         | 0.72%   |
| 5.4.4   | 1         | 0.72%   |
| 5.4.15  | 1         | 0.72%   |
| 5.19.7  | 1         | 0.72%   |
| 5.19.14 | 1         | 0.72%   |
| 5.19.12 | 1         | 0.72%   |
| 5.19.0  | 1         | 0.72%   |
| 5.18.17 | 1         | 0.72%   |
| 5.18.13 | 1         | 0.72%   |
| 5.18.12 | 1         | 0.72%   |
| 5.18.11 | 1         | 0.72%   |
| 5.18.10 | 1         | 0.72%   |
| 5.17.6  | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 20.59%  |
| 5.15    | 13        | 9.56%   |
| 5.13    | 11        | 8.09%   |
| 5.11    | 10        | 7.35%   |
| 5.3     | 9         | 6.62%   |
| 5.10    | 8         | 5.88%   |
| 5.0     | 6         | 4.41%   |
| 4.15    | 6         | 4.41%   |
| 5.8     | 5         | 3.68%   |
| 5.9     | 4         | 2.94%   |
| 5.19    | 4         | 2.94%   |
| 5.18    | 4         | 2.94%   |
| 5.16    | 4         | 2.94%   |
| 5.12    | 4         | 2.94%   |
| 4.18    | 4         | 2.94%   |
| 5.7     | 3         | 2.21%   |
| 4.19    | 3         | 2.21%   |
| 6.0     | 2         | 1.47%   |
| 5.17    | 2         | 1.47%   |
| 5.1     | 2         | 1.47%   |
| 5.6     | 1         | 0.74%   |
| 5.5     | 1         | 0.74%   |
| 5.14    | 1         | 0.74%   |
| 4.9     | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 126       | 96.92%  |
| i686   | 4         | 3.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 64        | 48.85%  |
| KDE5       | 20        | 15.27%  |
| Unknown    | 12        | 9.16%   |
| XFCE       | 11        | 8.4%    |
| X-Cinnamon | 9         | 6.87%   |
| KDE        | 4         | 3.05%   |
| Budgie     | 4         | 3.05%   |
| MATE       | 2         | 1.53%   |
| sway       | 1         | 0.76%   |
| LXQt       | 1         | 0.76%   |
| LXDE       | 1         | 0.76%   |
| KDE4       | 1         | 0.76%   |
| DWM        | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 106       | 80.92%  |
| Wayland | 18        | 13.74%  |
| Unknown | 5         | 3.82%   |
| Tty     | 2         | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 53.08%  |
| SDDM    | 22        | 16.92%  |
| GDM     | 15        | 11.54%  |
| GDM3    | 11        | 8.46%   |
| LightDM | 8         | 6.15%   |
| TDM     | 4         | 3.08%   |
| KDM     | 1         | 0.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 69        | 52.27%  |
| es_DO   | 35        | 26.52%  |
| Unknown | 14        | 10.61%  |
| es_ES   | 5         | 3.79%   |
| es_MX   | 3         | 2.27%   |
| en_CA   | 2         | 1.52%   |
| ru_RU   | 1         | 0.76%   |
| fr_FR   | 1         | 0.76%   |
| es_US   | 1         | 0.76%   |
| C       | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 75        | 57.69%  |
| EFI  | 55        | 42.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 75.38%  |
| Btrfs   | 13        | 10%     |
| Overlay | 11        | 8.46%   |
| Xfs     | 4         | 3.08%   |
| Unknown | 2         | 1.54%   |
| Zfs     | 1         | 0.77%   |
| F2fs    | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 56.49%  |
| GPT     | 42        | 32.06%  |
| MBR     | 15        | 11.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 83.21%  |
| Yes       | 22        | 16.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 67.94%  |
| Yes       | 42        | 32.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 43        | 33.08%  |
| Lenovo              | 17        | 13.08%  |
| Hewlett-Packard     | 16        | 12.31%  |
| ASUSTek Computer    | 10        | 7.69%   |
| Gigabyte Technology | 9         | 6.92%   |
| Acer                | 5         | 3.85%   |
| MSI                 | 4         | 3.08%   |
| Apple               | 4         | 3.08%   |
| Samsung Electronics | 3         | 2.31%   |
| EVOO                | 2         | 1.54%   |
| ASRock              | 2         | 1.54%   |
| Unknown             | 2         | 1.54%   |
| Toshiba             | 1         | 0.77%   |
| TODOS INDUSTRIAL    | 1         | 0.77%   |
| SAELITE             | 1         | 0.77%   |
| Nuvision            | 1         | 0.77%   |
| Microsoft           | 1         | 0.77%   |
| Google              | 1         | 0.77%   |
| Fujitsu             | 1         | 0.77%   |
| Foxconn             | 1         | 0.77%   |
| Eluktronics         | 1         | 0.77%   |
| ECS                 | 1         | 0.77%   |
| Chuwi               | 1         | 0.77%   |
| Biostar             | 1         | 0.77%   |
| AMI                 | 1         | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Gigabyte GA-78LMT-USB3 6.0                        | 2         | 1.54%   |
| EVOO EV-C-116-7                                   | 2         | 1.54%   |
| Dell OptiPlex 990                                 | 2         | 1.54%   |
| Dell OptiPlex 3010                                | 2         | 1.54%   |
| Dell Latitude E6540                               | 2         | 1.54%   |
| Dell Latitude E6430                               | 2         | 1.54%   |
| Dell Latitude E6420                               | 2         | 1.54%   |
| Dell Latitude E6410                               | 2         | 1.54%   |
| Dell Inspiron 5570                                | 2         | 1.54%   |
| Apple MacBookPro8,1                               | 2         | 1.54%   |
| Unknown                                           | 2         | 1.54%   |
| Toshiba Satellite C55-A                           | 1         | 0.77%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.77%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.77%   |
| Samsung 930QCG                                    | 1         | 0.77%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.77%   |
| SAELITE ES1AU11                                   | 1         | 0.77%   |
| Nuvision NES11                                    | 1         | 0.77%   |
| MSI MS-7A34                                       | 1         | 0.77%   |
| MSI MS-7817                                       | 1         | 0.77%   |
| MSI GE62 6QC                                      | 1         | 0.77%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.77%   |
| Microsoft Surface Go                              | 1         | 0.77%   |
| Lenovo Z50-75 80EC                                | 1         | 0.77%   |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.77%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.77%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 0.77%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.77%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.77%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 0.77%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.77%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.77%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.77%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.77%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.77%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 0.77%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.77%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 0.77%   |
| Lenovo G505s 20255                                | 1         | 0.77%   |
| Lenovo G40-70 20369                               | 1         | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 18        | 13.85%  |
| Dell OptiPlex              | 12        | 9.23%   |
| Lenovo ThinkPad            | 8         | 6.15%   |
| Dell Inspiron              | 8         | 6.15%   |
| Acer Aspire                | 5         | 3.85%   |
| HP Compaq                  | 4         | 3.08%   |
| Lenovo IdeaPad             | 3         | 2.31%   |
| HP Pavilion                | 3         | 2.31%   |
| Gigabyte GA-78LMT-USB3     | 3         | 2.31%   |
| HP EliteBook               | 2         | 1.54%   |
| Gigabyte B450M             | 2         | 1.54%   |
| EVOO EV-C-116-7            | 2         | 1.54%   |
| Dell Vostro                | 2         | 1.54%   |
| ASUS VivoBook              | 2         | 1.54%   |
| Apple MacBookPro8          | 2         | 1.54%   |
| Unknown                    | 2         | 1.54%   |
| Toshiba Satellite          | 1         | 0.77%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.77%   |
| Samsung RV420              | 1         | 0.77%   |
| Samsung 930QCG             | 1         | 0.77%   |
| Samsung 905S3G             | 1         | 0.77%   |
| SAELITE ES1AU11            | 1         | 0.77%   |
| Nuvision NES11             | 1         | 0.77%   |
| MSI MS-7A34                | 1         | 0.77%   |
| MSI MS-7817                | 1         | 0.77%   |
| MSI GE62                   | 1         | 0.77%   |
| MSI CR70                   | 1         | 0.77%   |
| Microsoft Surface          | 1         | 0.77%   |
| Lenovo Z50-75              | 1         | 0.77%   |
| Lenovo Yoga                | 1         | 0.77%   |
| Lenovo ThinkBook           | 1         | 0.77%   |
| Lenovo Legion              | 1         | 0.77%   |
| Lenovo G505s               | 1         | 0.77%   |
| Lenovo G40-70              | 1         | 0.77%   |
| HP ProBook                 | 1         | 0.77%   |
| HP Notebook                | 1         | 0.77%   |
| HP Laptop                  | 1         | 0.77%   |
| HP G60                     | 1         | 0.77%   |
| HP ENVY                    | 1         | 0.77%   |
| HP EliteDesk               | 1         | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 16        | 12.31%  |
| 2017 | 14        | 10.77%  |
| 2014 | 12        | 9.23%   |
| 2013 | 12        | 9.23%   |
| 2019 | 10        | 7.69%   |
| 2012 | 10        | 7.69%   |
| 2020 | 7         | 5.38%   |
| 2018 | 7         | 5.38%   |
| 2016 | 6         | 4.62%   |
| 2015 | 6         | 4.62%   |
| 2010 | 6         | 4.62%   |
| 2008 | 6         | 4.62%   |
| 2021 | 5         | 3.85%   |
| 2009 | 5         | 3.85%   |
| 2007 | 4         | 3.08%   |
| 2006 | 2         | 1.54%   |
| 2022 | 1         | 0.77%   |
| 2005 | 1         | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 85        | 65.38%  |
| Desktop     | 39        | 30%     |
| Tablet      | 2         | 1.54%   |
| Convertible | 2         | 1.54%   |
| Mini pc     | 1         | 0.77%   |
| All in one  | 1         | 0.77%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 125       | 96.15%  |
| Enabled  | 5         | 3.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 99.23%  |
| Yes  | 1         | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 28.46%  |
| 4.01-8.0    | 34        | 26.15%  |
| 8.01-16.0   | 21        | 16.15%  |
| 16.01-24.0  | 18        | 13.85%  |
| 2.01-3.0    | 5         | 3.85%   |
| 1.01-2.0    | 5         | 3.85%   |
| 32.01-64.0  | 4         | 3.08%   |
| 24.01-32.0  | 3         | 2.31%   |
| 0.51-1.0    | 2         | 1.54%   |
| 64.01-256.0 | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 55        | 39.57%  |
| 2.01-3.0  | 36        | 25.9%   |
| 3.01-4.0  | 26        | 18.71%  |
| 4.01-8.0  | 12        | 8.63%   |
| 0.51-1.0  | 8         | 5.76%   |
| 8.01-16.0 | 2         | 1.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 90        | 68.7%   |
| 2      | 31        | 23.66%  |
| 3      | 6         | 4.58%   |
| 4      | 4         | 3.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 56.15%  |
| Yes       | 57        | 43.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 86.15%  |
| No        | 18        | 13.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 82.44%  |
| No        | 23        | 17.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 53.08%  |
| No        | 61        | 46.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 130       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 79        | 59.4%   |
| Santiago de los Caballeros | 14        | 10.53%  |
| La Romana                  | 5         | 3.76%   |
| Santo Domingo              | 4         | 3.01%   |
| Alejandro Bass             | 4         | 3.01%   |
| San Pedro de Macorís      | 3         | 2.26%   |
| Sosua, Cabarete            | 2         | 1.5%    |
| Santa Cruz de Barahona     | 2         | 1.5%    |
| San Juan                   | 2         | 1.5%    |
| San Cristobal              | 2         | 1.5%    |
| Nacional                   | 2         | 1.5%    |
| Constanza                  | 2         | 1.5%    |
| Bajos de Haina             | 2         | 1.5%    |
| Santo Domingo Oeste        | 1         | 0.75%   |
| San Francisco de Macorís  | 1         | 0.75%   |
| Salcedo                    | 1         | 0.75%   |
| Punta Cana                 | 1         | 0.75%   |
| Moca                       | 1         | 0.75%   |
| Los Hidalgos               | 1         | 0.75%   |
| Guaymate                   | 1         | 0.75%   |
| Concepción de la Vega     | 1         | 0.75%   |
| Boca Chica                 | 1         | 0.75%   |
| Baní                      | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 39        | 51     | 22.94%  |
| WDC                       | 18        | 23     | 10.59%  |
| Samsung Electronics       | 18        | 22     | 10.59%  |
| Toshiba                   | 17        | 22     | 10%     |
| Hitachi                   | 14        | 17     | 8.24%   |
| Kingston                  | 12        | 13     | 7.06%   |
| SanDisk                   | 10        | 14     | 5.88%   |
| Unknown                   | 7         | 9      | 4.12%   |
| SK hynix                  | 5         | 6      | 2.94%   |
| Intel                     | 4         | 4      | 2.35%   |
| Unknown                   | 3         | 3      | 1.76%   |
| Transcend                 | 2         | 2      | 1.18%   |
| Micron Technology         | 2         | 2      | 1.18%   |
| FORESEE                   | 2         | 2      | 1.18%   |
| A-DATA Technology         | 2         | 2      | 1.18%   |
| UMIS                      | 1         | 1      | 0.59%   |
| SPCC                      | 1         | 1      | 0.59%   |
| PNY                       | 1         | 1      | 0.59%   |
| Phison Electronics        | 1         | 1      | 0.59%   |
| Patriot                   | 1         | 1      | 0.59%   |
| OCZ                       | 1         | 1      | 0.59%   |
| Micron/Crucial Technology | 1         | 1      | 0.59%   |
| Maxtor                    | 1         | 1      | 0.59%   |
| LITEONIT                  | 1         | 2      | 0.59%   |
| Indilinx                  | 1         | 1      | 0.59%   |
| Hewlett-Packard           | 1         | 1      | 0.59%   |
| Eluktro                   | 1         | 1      | 0.59%   |
| ELOTEC                    | 1         | 1      | 0.59%   |
| Crucial                   | 1         | 1      | 0.59%   |
| China                     | 1         | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB  | 4         | 2.2%    |
| Unknown MMC Card  32GB           | 3         | 1.65%   |
| Toshiba MQ01ACF050 500GB         | 3         | 1.65%   |
| Toshiba MK3275GSX 320GB          | 3         | 1.65%   |
| Samsung SSD 860 EVO 500GB        | 3         | 1.65%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.65%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 1.65%   |
| Unknown                          | 3         | 1.65%   |
| Unknown MMC Card  64GB           | 2         | 1.1%    |
| Toshiba MK2556GSY 250GB          | 2         | 1.1%    |
| Toshiba DT01ACA050 500GB         | 2         | 1.1%    |
| Seagate ST9250315AS 250GB        | 2         | 1.1%    |
| Seagate ST500DM002-1BD142 500GB  | 2         | 1.1%    |
| Seagate ST380815AS 80GB          | 2         | 1.1%    |
| Seagate ST3160815AS 160GB        | 2         | 1.1%    |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB   | 2         | 1.1%    |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.1%    |
| Samsung SSD 850 EVO 250GB        | 2         | 1.1%    |
| Kingston SV300S37A120G 120GB SSD | 2         | 1.1%    |
| FORESEE 128GB SSD                | 2         | 1.1%    |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1         | 0.55%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 0.55%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1         | 0.55%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.55%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.55%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.55%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.55%   |
| WDC WD3200LPVX-75V0TT0 320GB     | 1         | 0.55%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 0.55%   |
| WDC WD2500BEVT-75A23T0 250GB     | 1         | 0.55%   |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 0.55%   |
| WDC WD2500AAKX-001CA0 250GB      | 1         | 0.55%   |
| WDC WD2500AAJS-75M0A0 249GB      | 1         | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.55%   |
| WDC WD1600BEVT-75ZCT1 160GB      | 1         | 0.55%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T1 1TB         | 1         | 0.55%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.55%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 51     | 44.32%  |
| WDC                 | 16        | 21     | 18.18%  |
| Toshiba             | 15        | 19     | 17.05%  |
| Hitachi             | 14        | 17     | 15.91%  |
| Samsung Electronics | 3         | 5      | 3.41%   |
| Maxtor              | 1         | 1      | 1.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 12     | 22%     |
| Samsung Electronics | 10        | 11     | 20%     |
| SanDisk             | 7         | 11     | 14%     |
| WDC                 | 2         | 2      | 4%      |
| Transcend           | 2         | 2      | 4%      |
| SK hynix            | 2         | 2      | 4%      |
| Intel               | 2         | 2      | 4%      |
| FORESEE             | 2         | 2      | 4%      |
| A-DATA Technology   | 2         | 2      | 4%      |
| SPCC                | 1         | 1      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| Patriot             | 1         | 1      | 2%      |
| OCZ                 | 1         | 1      | 2%      |
| LITEONIT            | 1         | 2      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Eluktro             | 1         | 1      | 2%      |
| Crucial             | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| Unknown             | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 76        | 114    | 49.35%  |
| SSD     | 45        | 57     | 29.22%  |
| NVMe    | 21        | 23     | 13.64%  |
| MMC     | 9         | 11     | 5.84%   |
| Unknown | 3         | 3      | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 108       | 169    | 76.06%  |
| NVMe | 21        | 23     | 14.79%  |
| MMC  | 9         | 11     | 6.34%   |
| SAS  | 4         | 5      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 126    | 70.16%  |
| 0.51-1.0   | 27        | 34     | 21.77%  |
| 1.01-2.0   | 5         | 5      | 4.03%   |
| 3.01-4.0   | 3         | 4      | 2.42%   |
| 4.01-10.0  | 2         | 2      | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 33.09%  |
| 251-500        | 24        | 17.65%  |
| 501-1000       | 24        | 17.65%  |
| 51-100         | 12        | 8.82%   |
| 1-20           | 11        | 8.09%   |
| 21-50          | 7         | 5.15%   |
| 1001-2000      | 5         | 3.68%   |
| More than 3000 | 4         | 2.94%   |
| Unknown        | 3         | 2.21%   |
| 2001-3000      | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 38.62%  |
| 21-50          | 29        | 20%     |
| 51-100         | 21        | 14.48%  |
| 101-250        | 14        | 9.66%   |
| 251-500        | 10        | 6.9%    |
| 501-1000       | 7         | 4.83%   |
| Unknown        | 3         | 2.07%   |
| 2001-3000      | 2         | 1.38%   |
| 1001-2000      | 2         | 1.38%   |
| More than 3000 | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK3275GSX 320GB         | 2         | 2      | 9.52%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1         | 1      | 4.76%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 1         | 1      | 4.76%   |
| Toshiba MK3276GSX 320GB         | 1         | 1      | 4.76%   |
| Toshiba MK2556GSY 250GB         | 1         | 1      | 4.76%   |
| Toshiba MK1655GSX 160GB         | 1         | 1      | 4.76%   |
| Seagate ST9750420AS 752GB       | 1         | 1      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB | 1         | 1      | 4.76%   |
| Seagate ST500LM000-1EJ162 500GB | 1         | 1      | 4.76%   |
| Seagate ST3250318AS 250GB       | 1         | 1      | 4.76%   |
| Seagate ST2000LM007-1R8174 2TB  | 1         | 1      | 4.76%   |
| Samsung Electronics HD154UI 1TB | 1         | 1      | 4.76%   |
| Hitachi HTS727550A9E364 500GB   | 1         | 1      | 4.76%   |
| Hitachi HTS725032A9A364 320GB   | 1         | 1      | 4.76%   |
| Hitachi HTS722020K9SA00 200GB   | 1         | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 4.76%   |
| Hitachi HTS547564A9E384 640GB   | 1         | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB   | 1         | 1      | 4.76%   |
| Hitachi HDT721025SLA380 250GB   | 1         | 1      | 4.76%   |
| Crucial CT240BX500SSD1 240GB    | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 33.33%  |
| Toshiba             | 5         | 5      | 23.81%  |
| Seagate             | 5         | 5      | 23.81%  |
| WDC                 | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 35%     |
| Toshiba             | 5         | 5      | 25%     |
| Seagate             | 5         | 5      | 25%     |
| WDC                 | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 94.44%  |
| SSD  | 1         | 1      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HDS721025CLA382 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 83        | 134    | 58.87%  |
| Works    | 40        | 52     | 28.37%  |
| Malfunc  | 17        | 21     | 12.06%  |
| Failed   | 1         | 1      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 92        | 65.71%  |
| AMD                              | 25        | 17.86%  |
| Samsung Electronics              | 6         | 4.29%   |
| SanDisk                          | 3         | 2.14%   |
| Toshiba America Info Systems     | 2         | 1.43%   |
| SK hynix                         | 2         | 1.43%   |
| Micron Technology                | 2         | 1.43%   |
| VIA Technologies                 | 1         | 0.71%   |
| Union Memory (Shenzhen)          | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |
| Phison Electronics               | 1         | 0.71%   |
| Nvidia                           | 1         | 0.71%   |
| Micron/Crucial Technology        | 1         | 0.71%   |
| Marvell Technology Group         | 1         | 0.71%   |
| Kingston Technology Company      | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 10.3%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 5.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 4.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.03%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 3.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.42%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.82%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.82%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.21%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 1.21%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.21%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 1.21%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.61%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 1         | 0.61%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.61%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.61%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 90        | 60%     |
| IDE  | 24        | 16%     |
| NVMe | 21        | 14%     |
| RAID | 15        | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 103       | 79.23%  |
| AMD    | 27        | 20.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 3.08%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 3.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.31%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 2.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.54%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.54%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.54%   |
| AMD FX-8320 Eight-Core Processor            | 2         | 1.54%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.54%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.77%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.77%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.77%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.77%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.77%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.77%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.77%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.77%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.77%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.77%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.77%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.77%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.77%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.77%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.77%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.77%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.77%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.77%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 0.77%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.77%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 30%     |
| Intel Core i7           | 15        | 11.54%  |
| Intel Celeron           | 13        | 10%     |
| Intel Core i3           | 10        | 7.69%   |
| AMD Ryzen 5             | 8         | 6.15%   |
| Intel Core 2 Duo        | 6         | 4.62%   |
| Intel Atom              | 4         | 3.08%   |
| AMD FX                  | 4         | 3.08%   |
| Intel Pentium           | 3         | 2.31%   |
| Intel Xeon              | 2         | 1.54%   |
| Intel Pentium Dual-Core | 2         | 1.54%   |
| Intel Core 2            | 2         | 1.54%   |
| AMD Ryzen 7             | 2         | 1.54%   |
| AMD A8                  | 2         | 1.54%   |
| AMD A10                 | 2         | 1.54%   |
| Other                   | 1         | 0.77%   |
| Intel Pentium Dual      | 1         | 0.77%   |
| Intel Pentium D         | 1         | 0.77%   |
| Intel Pentium 4         | 1         | 0.77%   |
| Intel Genuine           | 1         | 0.77%   |
| Intel Core i9           | 1         | 0.77%   |
| Intel Core 2 Quad       | 1         | 0.77%   |
| AMD Sempron             | 1         | 0.77%   |
| AMD Ryzen 3             | 1         | 0.77%   |
| AMD Quad-Core           | 1         | 0.77%   |
| AMD PRO A10             | 1         | 0.77%   |
| AMD Phenom II X4        | 1         | 0.77%   |
| AMD Mobile Sempron      | 1         | 0.77%   |
| AMD A6                  | 1         | 0.77%   |
| AMD A4                  | 1         | 0.77%   |
| AMD A12                 | 1         | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 70        | 53.85%  |
| 4      | 45        | 34.62%  |
| 6      | 6         | 4.62%   |
| 1      | 5         | 3.85%   |
| 8      | 2         | 1.54%   |
| 12     | 1         | 0.77%   |
| 3      | 1         | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 129       | 99.23%  |
| 2      | 1         | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 75        | 57.69%  |
| 1      | 55        | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 128       | 97.71%  |
| 64-bit         | 1         | 0.76%   |
| 32-bit         | 1         | 0.76%   |
| Unknown        | 1         | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 17.56%  |
| 0x206a7    | 13        | 9.92%   |
| 0x306a9    | 10        | 7.63%   |
| 0x306c3    | 7         | 5.34%   |
| 0x1067a    | 7         | 5.34%   |
| 0x806e9    | 6         | 4.58%   |
| 0x506e3    | 5         | 3.82%   |
| 0x40651    | 5         | 3.82%   |
| 0x806ea    | 4         | 3.05%   |
| 0x706a1    | 4         | 3.05%   |
| 0x0800820d | 3         | 2.29%   |
| 0x07030105 | 3         | 2.29%   |
| 0x06000852 | 3         | 2.29%   |
| 0x806ec    | 2         | 1.53%   |
| 0x6fb      | 2         | 1.53%   |
| 0x6f6      | 2         | 1.53%   |
| 0x30678    | 2         | 1.53%   |
| 0x20652    | 2         | 1.53%   |
| 0x08108109 | 2         | 1.53%   |
| 0x0600611a | 2         | 1.53%   |
| 0xf65      | 1         | 0.76%   |
| 0xf49      | 1         | 0.76%   |
| 0x906ea    | 1         | 0.76%   |
| 0x906e9    | 1         | 0.76%   |
| 0x806c1    | 1         | 0.76%   |
| 0x706e5    | 1         | 0.76%   |
| 0x6fd      | 1         | 0.76%   |
| 0x506c9    | 1         | 0.76%   |
| 0x406c3    | 1         | 0.76%   |
| 0x30679    | 1         | 0.76%   |
| 0x20655    | 1         | 0.76%   |
| 0x106ca    | 1         | 0.76%   |
| 0x106c2    | 1         | 0.76%   |
| 0x10676    | 1         | 0.76%   |
| 0x10661    | 1         | 0.76%   |
| 0x08608103 | 1         | 0.76%   |
| 0x08608102 | 1         | 0.76%   |
| 0x08600103 | 1         | 0.76%   |
| 0x08108102 | 1         | 0.76%   |
| 0x08101013 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 15.38%  |
| SandyBridge   | 14        | 10.77%  |
| Haswell       | 13        | 10%     |
| IvyBridge     | 12        | 9.23%   |
| Penryn        | 8         | 6.15%   |
| Silvermont    | 7         | 5.38%   |
| Zen+          | 6         | 4.62%   |
| Westmere      | 6         | 4.62%   |
| Core          | 6         | 4.62%   |
| Skylake       | 5         | 3.85%   |
| Goldmont plus | 5         | 3.85%   |
| Piledriver    | 4         | 3.08%   |
| Puma          | 3         | 2.31%   |
| NetBurst      | 2         | 1.54%   |
| K8 Hammer     | 2         | 1.54%   |
| Excavator     | 2         | 1.54%   |
| Bonnell       | 2         | 1.54%   |
| Unknown       | 2         | 1.54%   |
| Zen 3         | 1         | 0.77%   |
| Zen 2         | 1         | 0.77%   |
| Zen           | 1         | 0.77%   |
| TigerLake     | 1         | 0.77%   |
| Steamroller   | 1         | 0.77%   |
| K10 Llano     | 1         | 0.77%   |
| K10           | 1         | 0.77%   |
| Jaguar        | 1         | 0.77%   |
| IceLake       | 1         | 0.77%   |
| Goldmont      | 1         | 0.77%   |
| Bulldozer     | 1         | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 91        | 62.76%  |
| AMD                              | 31        | 21.38%  |
| Nvidia                           | 21        | 14.48%  |
| VIA Technologies                 | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 8%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 5.33%   |
| Intel UHD Graphics 620                                                                   | 6         | 4%      |
| Intel HD Graphics 620                                                                    | 6         | 4%      |
| Intel HD Graphics 530                                                                    | 5         | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2%      |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.33%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.33%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.33%   |
| AMD Lucienne                                                                             | 2         | 1.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.33%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.67%   |
| Nvidia TU117M                                                                            | 1         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.67%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.67%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.67%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.67%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 60%     |
| 1 x AMD        | 23        | 17.69%  |
| 1 x Nvidia     | 12        | 9.23%   |
| Intel + Nvidia | 7         | 5.38%   |
| Intel + AMD    | 4         | 3.08%   |
| 2 x AMD        | 2         | 1.54%   |
| AMD + Nvidia   | 2         | 1.54%   |
| 1 x VIA        | 1         | 0.77%   |
| 1 x SiS        | 1         | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 89.31%  |
| Proprietary | 11        | 8.4%    |
| Unknown     | 3         | 2.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 65.65%  |
| 1.01-2.0   | 14        | 10.69%  |
| 0.01-0.5   | 11        | 8.4%    |
| 0.51-1.0   | 10        | 7.63%   |
| 3.01-4.0   | 6         | 4.58%   |
| 7.01-8.0   | 2         | 1.53%   |
| 2.01-3.0   | 2         | 1.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 14.18%  |
| LG Display              | 15        | 11.19%  |
| BOE                     | 15        | 11.19%  |
| Dell                    | 14        | 10.45%  |
| Chimei Innolux          | 13        | 9.7%    |
| Samsung Electronics     | 12        | 8.96%   |
| Hewlett-Packard         | 7         | 5.22%   |
| Chi Mei Optoelectronics | 5         | 3.73%   |
| Apple                   | 4         | 2.99%   |
| AOC                     | 4         | 2.99%   |
| Sony                    | 3         | 2.24%   |
| Acer                    | 3         | 2.24%   |
| Goldstar                | 2         | 1.49%   |
| ZTR                     | 1         | 0.75%   |
| Westinghouse            | 1         | 0.75%   |
| Vizio                   | 1         | 0.75%   |
| ViewSonic               | 1         | 0.75%   |
| Unknown (XXX)           | 1         | 0.75%   |
| Sharp                   | 1         | 0.75%   |
| Philips                 | 1         | 0.75%   |
| PANDA                   | 1         | 0.75%   |
| NEC Computers           | 1         | 0.75%   |
| LG Philips              | 1         | 0.75%   |
| LG Electronics          | 1         | 0.75%   |
| Lenovo                  | 1         | 0.75%   |
| KTC                     | 1         | 0.75%   |
| KDC                     | 1         | 0.75%   |
| InnoLux Display         | 1         | 0.75%   |
| CHR                     | 1         | 0.75%   |
| BenQ                    | 1         | 0.75%   |
| Ancor Communications    | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                           | 2         | 1.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 1.47%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 2         | 1.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch           | 2         | 1.47%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                        | 2         | 1.47%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                    | 1         | 0.74%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch            | 1         | 0.74%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.74%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.74%   |
| Unknown (XXX) V56 XXX0030 1920x1080 708x398mm 32.0-inch                 | 1         | 0.74%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                           | 1         | 0.74%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch                 | 1         | 0.74%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch    | 1         | 0.74%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch               | 1         | 0.74%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch                 | 1         | 0.74%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch            | 1         | 0.74%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch             | 1         | 0.74%   |
| LG Electronics LCD Monitor W1943 1984x768                               | 1         | 0.74%   |
| LG Electronics LCD Monitor LG TV                                        | 1         | 0.74%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch             | 1         | 0.74%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch             | 1         | 0.74%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch             | 1         | 0.74%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch             | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 43        | 33.59%  |
| 1920x1080 (FHD)    | 41        | 32.03%  |
| 1600x900 (HD+)     | 7         | 5.47%   |
| 1280x800 (WXGA)    | 7         | 5.47%   |
| 1280x1024 (SXGA)   | 7         | 5.47%   |
| 1680x1050 (WSXGA+) | 5         | 3.91%   |
| 3840x2160 (4K)     | 3         | 2.34%   |
| 1360x768           | 3         | 2.34%   |
| 2560x1440 (QHD)    | 2         | 1.56%   |
| 1440x900 (WXGA+)   | 2         | 1.56%   |
| 1024x768 (XGA)     | 2         | 1.56%   |
| 3840x1100          | 1         | 0.78%   |
| 1984x768           | 1         | 0.78%   |
| 1800x1200          | 1         | 0.78%   |
| 1280x768           | 1         | 0.78%   |
| 1024x600           | 1         | 0.78%   |
| Unknown            | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 31.34%  |
| 13      | 18        | 13.43%  |
| 14      | 12        | 8.96%   |
| 17      | 9         | 6.72%   |
| 11      | 8         | 5.97%   |
| 22      | 6         | 4.48%   |
| 24      | 5         | 3.73%   |
| 21      | 5         | 3.73%   |
| 19      | 5         | 3.73%   |
| 27      | 4         | 2.99%   |
| 18      | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 50      | 2         | 1.49%   |
| 32      | 2         | 1.49%   |
| 10      | 2         | 1.49%   |
| 84      | 1         | 0.75%   |
| 72      | 1         | 0.75%   |
| 41      | 1         | 0.75%   |
| 40      | 1         | 0.75%   |
| 34      | 1         | 0.75%   |
| 31      | 1         | 0.75%   |
| 23      | 1         | 0.75%   |
| 20      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 49.62%  |
| 201-300     | 19        | 14.5%   |
| 401-500     | 18        | 13.74%  |
| 501-600     | 10        | 7.63%   |
| 351-400     | 6         | 4.58%   |
| 701-800     | 3         | 2.29%   |
| Unknown     | 3         | 2.29%   |
| 1501-2000   | 2         | 1.53%   |
| 1001-1500   | 2         | 1.53%   |
| 801-900     | 1         | 0.76%   |
| 601-700     | 1         | 0.76%   |
| 901-1000    | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 91        | 75.83%  |
| 16/10   | 16        | 13.33%  |
| 5/4     | 7         | 5.83%   |
| Unknown | 3         | 2.5%    |
| 4/3     | 1         | 0.83%   |
| 3/2     | 1         | 0.83%   |
| 3.40    | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 31.34%  |
| 81-90          | 23        | 17.16%  |
| 201-250        | 13        | 9.7%    |
| 51-60          | 9         | 6.72%   |
| 151-200        | 9         | 6.72%   |
| 141-150        | 9         | 6.72%   |
| 71-80          | 6         | 4.48%   |
| More than 1000 | 4         | 2.99%   |
| 301-350        | 4         | 2.99%   |
| 351-500        | 3         | 2.24%   |
| 121-130        | 3         | 2.24%   |
| 501-1000       | 3         | 2.24%   |
| Unknown        | 3         | 2.24%   |
| 41-50          | 2         | 1.49%   |
| 251-300        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 47        | 36.15%  |
| 51-100        | 37        | 28.46%  |
| 121-160       | 32        | 24.62%  |
| 1-50          | 6         | 4.62%   |
| 161-240       | 4         | 3.08%   |
| Unknown       | 3         | 2.31%   |
| More than 240 | 1         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 105       | 79.55%  |
| 2     | 19        | 14.39%  |
| 0     | 7         | 5.3%    |
| 3     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 65        | 33.33%  |
| Intel                           | 58        | 29.74%  |
| Qualcomm Atheros                | 29        | 14.87%  |
| Broadcom                        | 18        | 9.23%   |
| Ralink Technology               | 6         | 3.08%   |
| Qualcomm Atheros Communications | 3         | 1.54%   |
| Marvell Technology Group        | 2         | 1.03%   |
| Lenovo                          | 2         | 1.03%   |
| Broadcom Limited                | 2         | 1.03%   |
| VIA Technologies                | 1         | 0.51%   |
| Tul Corporation / PowerColor    | 1         | 0.51%   |
| TP-Link                         | 1         | 0.51%   |
| Nvidia                          | 1         | 0.51%   |
| MediaTek                        | 1         | 0.51%   |
| Linksys                         | 1         | 0.51%   |
| JCM                             | 1         | 0.51%   |
| HTC (High Tech Computer)        | 1         | 0.51%   |
| Dell                            | 1         | 0.51%   |
| AMD                             | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 16.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.12%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.69%   |
| Intel Wireless 7260                                               | 4         | 1.69%   |
| Intel Wireless 3165                                               | 4         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.27%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.27%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.27%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.85%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.85%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.85%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.42%   |
| Tul Corporation / PowerColor Network controller                   | 1         | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 37.39%  |
| Qualcomm Atheros                | 24        | 20.87%  |
| Realtek Semiconductor           | 23        | 20%     |
| Broadcom                        | 11        | 9.57%   |
| Ralink Technology               | 6         | 5.22%   |
| Qualcomm Atheros Communications | 3         | 2.61%   |
| TP-Link                         | 1         | 0.87%   |
| MediaTek                        | 1         | 0.87%   |
| Linksys                         | 1         | 0.87%   |
| Dell                            | 1         | 0.87%   |
| Broadcom Limited                | 1         | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 7         | 6.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 5.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 4.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 4.31%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.45%   |
| Intel Wireless 7260                                                                   | 4         | 3.45%   |
| Intel Wireless 3165                                                                   | 4         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 2.59%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 2.59%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.59%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.72%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 1.72%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.72%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.72%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.86%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.86%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.86%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.86%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.86%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                                | 1         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.86%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 55        | 47.01%  |
| Intel                    | 37        | 31.62%  |
| Broadcom                 | 10        | 8.55%   |
| Qualcomm Atheros         | 7         | 5.98%   |
| Marvell Technology Group | 2         | 1.71%   |
| Lenovo                   | 2         | 1.71%   |
| VIA Technologies         | 1         | 0.85%   |
| Nvidia                   | 1         | 0.85%   |
| HTC (High Tech Computer) | 1         | 0.85%   |
| Broadcom Limited         | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 32.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 10.26%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.42%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 3.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.71%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.71%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.85%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.85%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.85%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1         | 0.85%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.85%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.85%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 50.22%  |
| WiFi     | 108       | 48.43%  |
| Modem    | 2         | 0.9%    |
| Unknown  | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 62.69%  |
| Ethernet | 50        | 37.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 60.77%  |
| 1     | 46        | 35.38%  |
| 0     | 5         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 99.23%  |
| Yes  | 1         | 0.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 39.13%  |
| Qualcomm Atheros Communications | 12        | 17.39%  |
| IMC Networks                    | 7         | 10.14%  |
| Dell                            | 5         | 7.25%   |
| Realtek Semiconductor           | 4         | 5.8%    |
| Cambridge Silicon Radio         | 4         | 5.8%    |
| Apple                           | 4         | 5.8%    |
| Lite-On Technology              | 2         | 2.9%    |
| Broadcom                        | 2         | 2.9%    |
| Hewlett-Packard                 | 1         | 1.45%   |
| ASUSTek Computer                | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 20.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 10.14%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 5.8%    |
| IMC Networks Bluetooth Radio                        | 4         | 5.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 5.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.35%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 4.35%   |
| Apple Bluetooth Host Controller                     | 3         | 4.35%   |
| Realtek Bluetooth Radio                             | 2         | 2.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.9%    |
| Intel AX201 Bluetooth                               | 2         | 2.9%    |
| Intel AX200 Bluetooth                               | 2         | 2.9%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.45%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.45%   |
| Lite-On Wireless_Device                             | 1         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.45%   |
| IMC Networks Bluetooth Device                       | 1         | 1.45%   |
| IMC Networks Bluetooth                              | 1         | 1.45%   |
| IMC Networks BCM20702A0                             | 1         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.45%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.45%   |
| Dell Wireless 350 Bluetooth                         | 1         | 1.45%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.45%   |
| Apple Bluetooth HCI                                 | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 62.18%  |
| AMD                              | 30        | 19.23%  |
| Nvidia                           | 17        | 10.9%   |
| Logitech                         | 3         | 1.92%   |
| C-Media Electronics              | 2         | 1.28%   |
| VIA Technologies                 | 1         | 0.64%   |
| Sony                             | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] | 1         | 0.64%   |
| JMTek                            | 1         | 0.64%   |
| Creative Labs                    | 1         | 0.64%   |
| Blue Microphones                 | 1         | 0.64%   |
| BigBen Interactive               | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 7.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 6.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 5.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 4.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 4.26%   |
| AMD FCH Azalia Controller                                                  | 7         | 3.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 3.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.66%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 2.66%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.06%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2         | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.06%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.53%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 24        | 29.63%  |
| Samsung Electronics | 20        | 24.69%  |
| Micron Technology   | 7         | 8.64%   |
| Unknown             | 4         | 4.94%   |
| Kingston            | 4         | 4.94%   |
| Ramaxel Technology  | 3         | 3.7%    |
| Nanya Technology    | 3         | 3.7%    |
| Crucial             | 3         | 3.7%    |
| Unknown (ABCD)      | 2         | 2.47%   |
| Corsair             | 2         | 2.47%   |
| V-Color             | 1         | 1.23%   |
| Sesame              | 1         | 1.23%   |
| Qimonda             | 1         | 1.23%   |
| Patriot             | 1         | 1.23%   |
| G.Skill             | 1         | 1.23%   |
| Elpida              | 1         | 1.23%   |
| Avant               | 1         | 1.23%   |
| A-DATA Technology   | 1         | 1.23%   |
| Unknown             | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.33%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 2.33%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.33%   |
| V-Color RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s              | 1         | 1.16%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.16%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.16%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.16%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 1.16%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.16%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s               | 1         | 1.16%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s             | 1         | 1.16%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.16%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.16%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s          | 1         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.16%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.16%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 1         | 1.16%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.16%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.16%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.16%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 2667MT/s                | 1         | 1.16%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.16%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.16%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.16%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 24        | 37.5%   |
| DDR3    | 22        | 34.38%  |
| SDRAM   | 7         | 10.94%  |
| LPDDR4  | 5         | 7.81%   |
| DDR2    | 2         | 3.13%   |
| Unknown | 2         | 3.13%   |
| LPDDR3  | 1         | 1.56%   |
| DDR     | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 63.93%  |
| DIMM         | 19        | 31.15%  |
| Row Of Chips | 3         | 4.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 27        | 40.3%   |
| 8192  | 19        | 28.36%  |
| 2048  | 11        | 16.42%  |
| 16384 | 7         | 10.45%  |
| 1024  | 2         | 2.99%   |
| 512   | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 23.61%  |
| 2667    | 10        | 13.89%  |
| 1333    | 8         | 11.11%  |
| 2400    | 7         | 9.72%   |
| 3200    | 4         | 5.56%   |
| 2133    | 4         | 5.56%   |
| 4199    | 2         | 2.78%   |
| 2933    | 2         | 2.78%   |
| 1867    | 2         | 2.78%   |
| 1334    | 2         | 2.78%   |
| 1067    | 2         | 2.78%   |
| 667     | 2         | 2.78%   |
| 49926   | 1         | 1.39%   |
| 4267    | 1         | 1.39%   |
| 3600    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 2934    | 1         | 1.39%   |
| 2666    | 1         | 1.39%   |
| 2048    | 1         | 1.39%   |
| 1648    | 1         | 1.39%   |
| 533     | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 14        | 16.87%  |
| Microdia                               | 10        | 12.05%  |
| Sunplus Innovation Technology          | 8         | 9.64%   |
| IMC Networks                           | 7         | 8.43%   |
| Realtek Semiconductor                  | 6         | 7.23%   |
| Suyin                                  | 5         | 6.02%   |
| Apple                                  | 5         | 6.02%   |
| Syntek                                 | 4         | 4.82%   |
| Silicon Motion                         | 3         | 3.61%   |
| Ricoh                                  | 3         | 3.61%   |
| Microsoft                              | 3         | 3.61%   |
| OmniVision Technologies                | 2         | 2.41%   |
| Logitech                               | 2         | 2.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.41%   |
| Acer                                   | 2         | 2.41%   |
| Unknown                                | 1         | 1.2%    |
| Sonix Technology                       | 1         | 1.2%    |
| Samsung Electronics                    | 1         | 1.2%    |
| Primax Electronics                     | 1         | 1.2%    |
| Jieli Technology                       | 1         | 1.2%    |
| globaloptics                           | 1         | 1.2%    |
| Alcor Micro                            | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD               | 5         | 6.02%   |
| Chicony integrated camera                  | 4         | 4.82%   |
| IMC Networks Integrated Camera             | 3         | 3.61%   |
| Syntek Lenovo EasyCamera                   | 2         | 2.41%   |
| Microsoft MicrosoftÂ LifeCam HD-5001      | 2         | 2.41%   |
| Microdia Sonix USB 2.0 Camera              | 2         | 2.41%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.41%   |
| Microdia Integrated Webcam                 | 2         | 2.41%   |
| Microdia Dell Integrated HD Webcam         | 2         | 2.41%   |
| IMC Networks USB2.0 HD UVC WebCam          | 2         | 2.41%   |
| Chicony USB2.0 HD UVC WebCam               | 2         | 2.41%   |
| Apple iPhone5/5C/5S/6                      | 2         | 2.41%   |
| Apple FaceTime HD Camera                   | 2         | 2.41%   |
| Unknown 720p HD Camera                     | 1         | 1.2%    |
| Syntek Integrated Camera                   | 1         | 1.2%    |
| Syntek EasyCamera                          | 1         | 1.2%    |
| Suyin VGA Webcam                           | 1         | 1.2%    |
| Suyin TOSHIBA Web Camera - HD              | 1         | 1.2%    |
| Suyin HP TrueVision HD                     | 1         | 1.2%    |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.2%    |
| Suyin 1.3M HD WebCam                       | 1         | 1.2%    |
| Sunplus Laptop_Integrated_Webcam_HD        | 1         | 1.2%    |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.2%    |
| Sunplus Integrated_Webcam_FHD              | 1         | 1.2%    |
| Sonix HP Webcam-101                        | 1         | 1.2%    |
| Silicon Motion WebCam SCB-0385N            | 1         | 1.2%    |
| Silicon Motion WebCam SC-10HDD13335N       | 1         | 1.2%    |
| Silicon Motion Real HD WebCam              | 1         | 1.2%    |
| Samsung Galaxy A5 (MTP)                    | 1         | 1.2%    |
| Ricoh Laptop_Integrated_Webcam_FHD         | 1         | 1.2%    |
| Ricoh Integrated Webcam                    | 1         | 1.2%    |
| Ricoh HD Webcam                            | 1         | 1.2%    |
| Realtek USB2.0 camera                      | 1         | 1.2%    |
| Realtek Integrated Webcam HD               | 1         | 1.2%    |
| Realtek Integrated Webcam                  | 1         | 1.2%    |
| Realtek Integrated Camera                  | 1         | 1.2%    |
| Realtek HP Wide Vision HD Camera           | 1         | 1.2%    |
| Realtek HP Truevision HD integrated webcam | 1         | 1.2%    |
| Primax HP HD Webcam [Fixed]                | 1         | 1.2%    |
| OmniVision Monitor Webcam                  | 1         | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 46.15%  |
| Synaptics                  | 4         | 30.77%  |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| Samsung Electronics        | 1         | 7.69%   |
| LighTuning Technology      | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 7.69%   |
| Validity Sensors VFS491                           | 1         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 7.69%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                   | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner              | 1         | 7.69%   |
| Synaptics  WBDI                                   | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 7.69%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 70%     |
| O2 Micro    | 2         | 20%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 98        | 74.81%  |
| 1     | 29        | 22.14%  |
| 2     | 4         | 3.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 35.14%  |
| Chipcard              | 8         | 21.62%  |
| Graphics card         | 7         | 18.92%  |
| Storage               | 2         | 5.41%   |
| Multimedia controller | 2         | 5.41%   |
| Network               | 1         | 2.7%    |
| Net/wireless          | 1         | 2.7%    |
| Card reader           | 1         | 2.7%    |
| Camera                | 1         | 2.7%    |
| Bluetooth             | 1         | 2.7%    |


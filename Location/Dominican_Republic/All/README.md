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

Total: 175

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 21        | 17.95%  |
| Ubuntu 18.04                 | 17        | 14.53%  |
| OpenMandriva 4.2             | 5         | 4.27%   |
| Arch Rolling                 | 5         | 4.27%   |
| OpenMandriva 4.3             | 3         | 2.56%   |
| Linux Mint 20.3              | 3         | 2.56%   |
| Fedora 34                    | 3         | 2.56%   |
| Arch                         | 3         | 2.56%   |
| Ubuntu 22.04                 | 2         | 1.71%   |
| Ubuntu 21.10                 | 2         | 1.71%   |
| Pop!_OS 20.10                | 2         | 1.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.71%   |
| Linux Mint 20.1              | 2         | 1.71%   |
| Linux Mint 19.3              | 2         | 1.71%   |
| Fedora 36                    | 2         | 1.71%   |
| Fedora 33                    | 2         | 1.71%   |
| Debian 11                    | 2         | 1.71%   |
| ArcoLinux Rolling            | 2         | 1.71%   |
| Xubuntu 19.10                | 1         | 0.85%   |
| Xubuntu 18.04                | 1         | 0.85%   |
| Void Linux Rolling           | 1         | 0.85%   |
| Ubuntu Budgie 22.04          | 1         | 0.85%   |
| Ubuntu Budgie 21.10          | 1         | 0.85%   |
| Ubuntu Budgie 20.04          | 1         | 0.85%   |
| Ubuntu 21.04                 | 1         | 0.85%   |
| Ubuntu 19.10                 | 1         | 0.85%   |
| Ubuntu 19.04                 | 1         | 0.85%   |
| Solus 4.1                    | 1         | 0.85%   |
| ROSA R10                     | 1         | 0.85%   |
| Pop!_OS 22.04                | 1         | 0.85%   |
| Pop!_OS 21.04                | 1         | 0.85%   |
| Pop!_OS 20.04                | 1         | 0.85%   |
| OpenMandriva 4.90            | 1         | 0.85%   |
| Manjaro 21.2.3               | 1         | 0.85%   |
| Manjaro 21.1.2               | 1         | 0.85%   |
| Manjaro 20.1                 | 1         | 0.85%   |
| Lubuntu 21.04                | 1         | 0.85%   |
| LMDE 4                       | 1         | 0.85%   |
| Linux Mint 21                | 1         | 0.85%   |
| Linux Mint 20.2              | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 43        | 37.39%  |
| Linux Mint    | 10        | 8.7%    |
| Fedora        | 10        | 8.7%    |
| OpenMandriva  | 9         | 7.83%   |
| Arch          | 8         | 6.96%   |
| Pop!_OS       | 5         | 4.35%   |
| Ubuntu Budgie | 3         | 2.61%   |
| Manjaro       | 3         | 2.61%   |
| Debian        | 3         | 2.61%   |
| Clear Linux   | 3         | 2.61%   |
| Xubuntu       | 2         | 1.74%   |
| openSUSE      | 2         | 1.74%   |
| ArcoLinux     | 2         | 1.74%   |
| Void Linux    | 1         | 0.87%   |
| Solus         | 1         | 0.87%   |
| ROSA          | 1         | 0.87%   |
| Lubuntu       | 1         | 0.87%   |
| LMDE          | 1         | 0.87%   |
| Kubuntu       | 1         | 0.87%   |
| KDE neon      | 1         | 0.87%   |
| Kali          | 1         | 0.87%   |
| Elementary    | 1         | 0.87%   |
| CentOS        | 1         | 0.87%   |
| BlackPanther  | 1         | 0.87%   |
| Archcraft     | 1         | 0.87%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 4         | 2.99%   |
| 5.4.0-42-generic         | 4         | 2.99%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.99%   |
| 5.16.7-desktop-1omv4003  | 3         | 2.24%   |
| 5.13.0-22-generic        | 3         | 2.24%   |
| 5.4.0-77-generic         | 2         | 1.49%   |
| 5.4.0-52-generic         | 2         | 1.49%   |
| 5.4.0-33-generic         | 2         | 1.49%   |
| 5.3.0-51-generic         | 2         | 1.49%   |
| 5.3.0-46-generic         | 2         | 1.49%   |
| 5.3.0-42-generic         | 2         | 1.49%   |
| 5.15.0-41-generic        | 2         | 1.49%   |
| 5.11.0-40-generic        | 2         | 1.49%   |
| 5.11.0-25-generic        | 2         | 1.49%   |
| 5.0.0-32-generic         | 2         | 1.49%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.75%   |
| 5.9.12-xanmod1           | 1         | 0.75%   |
| 5.9.11-arch2-1           | 1         | 0.75%   |
| 5.9.1-arch1-1            | 1         | 0.75%   |
| 5.8.8-arch1-1            | 1         | 0.75%   |
| 5.8.5-arch1-1            | 1         | 0.75%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.75%   |
| 5.8.12_1                 | 1         | 0.75%   |
| 5.8.0-38-generic         | 1         | 0.75%   |
| 5.7.7-zen1-1-zen         | 1         | 0.75%   |
| 5.7.7-arch1-1            | 1         | 0.75%   |
| 5.7.10-201.fc32.x86_64   | 1         | 0.75%   |
| 5.6.19-158.current       | 1         | 0.75%   |
| 5.5.13-arch1-1           | 1         | 0.75%   |
| 5.4.60-2-MANJARO         | 1         | 0.75%   |
| 5.4.4-879.native         | 1         | 0.75%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.75%   |
| 5.4.0-7642-generic       | 1         | 0.75%   |
| 5.4.0-74-generic         | 1         | 0.75%   |
| 5.4.0-72-generic         | 1         | 0.75%   |
| 5.4.0-39-generic         | 1         | 0.75%   |
| 5.4.0-37-generic         | 1         | 0.75%   |
| 5.4.0-29-generic         | 1         | 0.75%   |
| 5.4.0-28-generic         | 1         | 0.75%   |
| 5.4.0-26-generic         | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 20.33%  |
| 5.13.0  | 10        | 8.13%   |
| 5.3.0   | 9         | 7.32%   |
| 5.11.0  | 8         | 6.5%    |
| 4.15.0  | 6         | 4.88%   |
| 5.0.0   | 5         | 4.07%   |
| 5.15.0  | 4         | 3.25%   |
| 5.10.14 | 4         | 3.25%   |
| 5.16.7  | 3         | 2.44%   |
| 5.7.7   | 2         | 1.63%   |
| 5.10.0  | 2         | 1.63%   |
| 4.19.0  | 2         | 1.63%   |
| 4.18.0  | 2         | 1.63%   |
| 5.9.16  | 1         | 0.81%   |
| 5.9.12  | 1         | 0.81%   |
| 5.9.11  | 1         | 0.81%   |
| 5.9.1   | 1         | 0.81%   |
| 5.8.8   | 1         | 0.81%   |
| 5.8.5   | 1         | 0.81%   |
| 5.8.15  | 1         | 0.81%   |
| 5.8.12  | 1         | 0.81%   |
| 5.8.0   | 1         | 0.81%   |
| 5.7.10  | 1         | 0.81%   |
| 5.6.19  | 1         | 0.81%   |
| 5.5.13  | 1         | 0.81%   |
| 5.4.60  | 1         | 0.81%   |
| 5.4.4   | 1         | 0.81%   |
| 5.4.15  | 1         | 0.81%   |
| 5.19.7  | 1         | 0.81%   |
| 5.18.17 | 1         | 0.81%   |
| 5.18.13 | 1         | 0.81%   |
| 5.18.12 | 1         | 0.81%   |
| 5.18.11 | 1         | 0.81%   |
| 5.18.10 | 1         | 0.81%   |
| 5.17.6  | 1         | 0.81%   |
| 5.17.4  | 1         | 0.81%   |
| 5.15.21 | 1         | 0.81%   |
| 5.14.13 | 1         | 0.81%   |
| 5.13.13 | 1         | 0.81%   |
| 5.12.9  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 23.14%  |
| 5.13    | 11        | 9.09%   |
| 5.11    | 10        | 8.26%   |
| 5.3     | 9         | 7.44%   |
| 5.10    | 7         | 5.79%   |
| 5.0     | 6         | 4.96%   |
| 4.15    | 6         | 4.96%   |
| 5.8     | 5         | 4.13%   |
| 5.15    | 5         | 4.13%   |
| 5.9     | 4         | 3.31%   |
| 5.18    | 4         | 3.31%   |
| 5.12    | 4         | 3.31%   |
| 4.18    | 4         | 3.31%   |
| 5.7     | 3         | 2.48%   |
| 5.16    | 3         | 2.48%   |
| 4.19    | 3         | 2.48%   |
| 5.17    | 2         | 1.65%   |
| 5.1     | 2         | 1.65%   |
| 5.6     | 1         | 0.83%   |
| 5.5     | 1         | 0.83%   |
| 5.19    | 1         | 0.83%   |
| 5.14    | 1         | 0.83%   |
| 4.9     | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 112       | 97.39%  |
| i686   | 3         | 2.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 56        | 48.28%  |
| KDE5       | 17        | 14.66%  |
| Unknown    | 11        | 9.48%   |
| XFCE       | 10        | 8.62%   |
| X-Cinnamon | 9         | 7.76%   |
| KDE        | 4         | 3.45%   |
| Budgie     | 4         | 3.45%   |
| sway       | 1         | 0.86%   |
| MATE       | 1         | 0.86%   |
| LXQt       | 1         | 0.86%   |
| KDE4       | 1         | 0.86%   |
| DWM        | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 97        | 83.62%  |
| Wayland | 13        | 11.21%  |
| Unknown | 4         | 3.45%   |
| Tty     | 2         | 1.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 55.65%  |
| SDDM    | 20        | 17.39%  |
| GDM     | 14        | 12.17%  |
| LightDM | 6         | 5.22%   |
| GDM3    | 6         | 5.22%   |
| TDM     | 4         | 3.48%   |
| KDM     | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 56        | 47.86%  |
| es_DO   | 34        | 29.06%  |
| Unknown | 14        | 11.97%  |
| es_ES   | 5         | 4.27%   |
| es_MX   | 3         | 2.56%   |
| en_CA   | 2         | 1.71%   |
| fr_FR   | 1         | 0.85%   |
| es_US   | 1         | 0.85%   |
| C       | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 60.87%  |
| EFI  | 45        | 39.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 89        | 77.39%  |
| Overlay | 11        | 9.57%   |
| Btrfs   | 9         | 7.83%   |
| Xfs     | 3         | 2.61%   |
| Unknown | 2         | 1.74%   |
| Zfs     | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 60.34%  |
| GPT     | 33        | 28.45%  |
| MBR     | 13        | 11.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 81.9%   |
| Yes       | 21        | 18.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 65.52%  |
| Yes       | 40        | 34.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 37        | 32.17%  |
| Hewlett-Packard     | 16        | 13.91%  |
| Lenovo              | 14        | 12.17%  |
| Gigabyte Technology | 9         | 7.83%   |
| ASUSTek Computer    | 8         | 6.96%   |
| Acer                | 5         | 4.35%   |
| Apple               | 4         | 3.48%   |
| Samsung Electronics | 3         | 2.61%   |
| MSI                 | 3         | 2.61%   |
| ASRock              | 2         | 1.74%   |
| Unknown             | 2         | 1.74%   |
| Toshiba             | 1         | 0.87%   |
| TODOS INDUSTRIAL    | 1         | 0.87%   |
| SAELITE             | 1         | 0.87%   |
| Nuvision            | 1         | 0.87%   |
| Microsoft           | 1         | 0.87%   |
| Google              | 1         | 0.87%   |
| Fujitsu             | 1         | 0.87%   |
| Foxconn             | 1         | 0.87%   |
| EVOO                | 1         | 0.87%   |
| ECS                 | 1         | 0.87%   |
| Chuwi               | 1         | 0.87%   |
| Biostar             | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Gigabyte GA-78LMT-USB3 6.0                        | 2         | 1.74%   |
| Dell OptiPlex 3010                                | 2         | 1.74%   |
| Dell Latitude E6540                               | 2         | 1.74%   |
| Dell Latitude E6430                               | 2         | 1.74%   |
| Dell Latitude E6420                               | 2         | 1.74%   |
| Dell Latitude E6410                               | 2         | 1.74%   |
| Apple MacBookPro8,1                               | 2         | 1.74%   |
| Unknown                                           | 2         | 1.74%   |
| Toshiba Satellite C55-A                           | 1         | 0.87%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.87%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.87%   |
| Samsung 930QCG                                    | 1         | 0.87%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.87%   |
| SAELITE ES1AU11                                   | 1         | 0.87%   |
| Nuvision NES11                                    | 1         | 0.87%   |
| MSI MS-7A34                                       | 1         | 0.87%   |
| MSI MS-7817                                       | 1         | 0.87%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.87%   |
| Microsoft Surface Go                              | 1         | 0.87%   |
| Lenovo Z50-75 80EC                                | 1         | 0.87%   |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.87%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.87%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.87%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.87%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.87%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.87%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.87%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.87%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.87%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 0.87%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.87%   |
| Lenovo G505s 20255                                | 1         | 0.87%   |
| Lenovo G40-70 20369                               | 1         | 0.87%   |
| HP ProBook 6470b                                  | 1         | 0.87%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 0.87%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 0.87%   |
| HP Pavilion dv6                                   | 1         | 0.87%   |
| HP Notebook                                       | 1         | 0.87%   |
| HP Laptop 15-bw0xx                                | 1         | 0.87%   |
| HP G60                                            | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 15        | 13.04%  |
| Dell OptiPlex              | 10        | 8.7%    |
| Dell Inspiron              | 7         | 6.09%   |
| Lenovo ThinkPad            | 6         | 5.22%   |
| Acer Aspire                | 5         | 4.35%   |
| HP Compaq                  | 4         | 3.48%   |
| HP Pavilion                | 3         | 2.61%   |
| Gigabyte GA-78LMT-USB3     | 3         | 2.61%   |
| Lenovo IdeaPad             | 2         | 1.74%   |
| HP EliteBook               | 2         | 1.74%   |
| Gigabyte B450M             | 2         | 1.74%   |
| Dell Vostro                | 2         | 1.74%   |
| Apple MacBookPro8          | 2         | 1.74%   |
| Unknown                    | 2         | 1.74%   |
| Toshiba Satellite          | 1         | 0.87%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.87%   |
| Samsung RV420              | 1         | 0.87%   |
| Samsung 930QCG             | 1         | 0.87%   |
| Samsung 905S3G             | 1         | 0.87%   |
| SAELITE ES1AU11            | 1         | 0.87%   |
| Nuvision NES11             | 1         | 0.87%   |
| MSI MS-7A34                | 1         | 0.87%   |
| MSI MS-7817                | 1         | 0.87%   |
| MSI CR70                   | 1         | 0.87%   |
| Microsoft Surface          | 1         | 0.87%   |
| Lenovo Z50-75              | 1         | 0.87%   |
| Lenovo Yoga                | 1         | 0.87%   |
| Lenovo ThinkBook           | 1         | 0.87%   |
| Lenovo Legion              | 1         | 0.87%   |
| Lenovo G505s               | 1         | 0.87%   |
| Lenovo G40-70              | 1         | 0.87%   |
| HP ProBook                 | 1         | 0.87%   |
| HP Notebook                | 1         | 0.87%   |
| HP Laptop                  | 1         | 0.87%   |
| HP G60                     | 1         | 0.87%   |
| HP ENVY                    | 1         | 0.87%   |
| HP EliteDesk               | 1         | 0.87%   |
| HP 250                     | 1         | 0.87%   |
| Google Winky               | 1         | 0.87%   |
| Gigabyte Z87X-UD5          | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 14        | 12.17%  |
| 2017 | 12        | 10.43%  |
| 2014 | 12        | 10.43%  |
| 2013 | 12        | 10.43%  |
| 2012 | 10        | 8.7%    |
| 2019 | 7         | 6.09%   |
| 2018 | 6         | 5.22%   |
| 2008 | 6         | 5.22%   |
| 2020 | 5         | 4.35%   |
| 2015 | 5         | 4.35%   |
| 2010 | 5         | 4.35%   |
| 2009 | 5         | 4.35%   |
| 2021 | 4         | 3.48%   |
| 2016 | 4         | 3.48%   |
| 2007 | 4         | 3.48%   |
| 2006 | 2         | 1.74%   |
| 2022 | 1         | 0.87%   |
| 2005 | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 73        | 63.48%  |
| Desktop     | 37        | 32.17%  |
| Tablet      | 2         | 1.74%   |
| Convertible | 2         | 1.74%   |
| All in one  | 1         | 0.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 112       | 97.39%  |
| Enabled  | 3         | 2.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 99.13%  |
| Yes  | 1         | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 35        | 30.43%  |
| 4.01-8.0    | 28        | 24.35%  |
| 8.01-16.0   | 18        | 15.65%  |
| 16.01-24.0  | 16        | 13.91%  |
| 1.01-2.0    | 5         | 4.35%   |
| 2.01-3.0    | 4         | 3.48%   |
| 32.01-64.0  | 3         | 2.61%   |
| 24.01-32.0  | 3         | 2.61%   |
| 0.51-1.0    | 2         | 1.74%   |
| 64.01-256.0 | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 51        | 41.13%  |
| 2.01-3.0  | 32        | 25.81%  |
| 3.01-4.0  | 22        | 17.74%  |
| 4.01-8.0  | 11        | 8.87%   |
| 0.51-1.0  | 7         | 5.65%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 68.1%   |
| 2      | 27        | 23.28%  |
| 3      | 6         | 5.17%   |
| 4      | 4         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 53.04%  |
| Yes       | 54        | 46.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 86.09%  |
| No        | 16        | 13.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 81.9%   |
| No        | 21        | 18.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 53.91%  |
| No        | 53        | 46.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 115       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 70        | 59.32%  |
| Santiago de los Caballeros | 12        | 10.17%  |
| La Romana                  | 5         | 4.24%   |
| San Pedro de Macorís      | 3         | 2.54%   |
| Alejandro Bass             | 3         | 2.54%   |
| Sosua, Cabarete            | 2         | 1.69%   |
| Santo Domingo              | 2         | 1.69%   |
| Santa Cruz de Barahona     | 2         | 1.69%   |
| San Juan                   | 2         | 1.69%   |
| San Cristobal              | 2         | 1.69%   |
| Nacional                   | 2         | 1.69%   |
| Bajos de Haina             | 2         | 1.69%   |
| Santo Domingo Oeste        | 1         | 0.85%   |
| San Francisco de Macorís  | 1         | 0.85%   |
| Salcedo                    | 1         | 0.85%   |
| Punta Cana                 | 1         | 0.85%   |
| Moca                       | 1         | 0.85%   |
| Los Hidalgos               | 1         | 0.85%   |
| Guaymate                   | 1         | 0.85%   |
| Constanza                  | 1         | 0.85%   |
| Concepción de la Vega     | 1         | 0.85%   |
| Boca Chica                 | 1         | 0.85%   |
| Baní                      | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 36        | 48     | 23.68%  |
| WDC                       | 17        | 22     | 11.18%  |
| Toshiba                   | 17        | 22     | 11.18%  |
| Samsung Electronics       | 16        | 20     | 10.53%  |
| Hitachi                   | 13        | 16     | 8.55%   |
| SanDisk                   | 10        | 14     | 6.58%   |
| Kingston                  | 10        | 11     | 6.58%   |
| Unknown                   | 7         | 9      | 4.61%   |
| Intel                     | 4         | 4      | 2.63%   |
| SK hynix                  | 3         | 4      | 1.97%   |
| Transcend                 | 2         | 2      | 1.32%   |
| FORESEE                   | 2         | 2      | 1.32%   |
| Unknown                   | 2         | 2      | 1.32%   |
| SPCC                      | 1         | 1      | 0.66%   |
| PNY                       | 1         | 1      | 0.66%   |
| Phison Electronics        | 1         | 1      | 0.66%   |
| Patriot                   | 1         | 1      | 0.66%   |
| OCZ                       | 1         | 1      | 0.66%   |
| Micron/Crucial Technology | 1         | 1      | 0.66%   |
| Micron Technology         | 1         | 1      | 0.66%   |
| Maxtor                    | 1         | 1      | 0.66%   |
| LITEONIT                  | 1         | 2      | 0.66%   |
| Indilinx                  | 1         | 1      | 0.66%   |
| Hewlett-Packard           | 1         | 1      | 0.66%   |
| Crucial                   | 1         | 1      | 0.66%   |
| A-DATA Technology         | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB  | 4         | 2.44%   |
| Unknown MMC Card  32GB           | 3         | 1.83%   |
| Toshiba MQ01ACF050 500GB         | 3         | 1.83%   |
| Toshiba MK3275GSX 320GB          | 3         | 1.83%   |
| Samsung SSD 860 EVO 500GB        | 3         | 1.83%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.83%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 1.83%   |
| Unknown MMC Card  64GB           | 2         | 1.22%   |
| Toshiba MK2556GSY 250GB          | 2         | 1.22%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.22%   |
| Seagate ST9250315AS 250GB        | 2         | 1.22%   |
| Seagate ST380815AS 80GB          | 2         | 1.22%   |
| Seagate ST3160815AS 160GB        | 2         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 1.22%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.22%   |
| Samsung SSD 850 EVO 250GB        | 2         | 1.22%   |
| Kingston SV300S37A120G 120GB SSD | 2         | 1.22%   |
| FORESEE 128GB SSD                | 2         | 1.22%   |
| Unknown                          | 2         | 1.22%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1         | 0.61%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 0.61%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1         | 0.61%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.61%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.61%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.61%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.61%   |
| WDC WD3200LPVX-75V0TT0 320GB     | 1         | 0.61%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 0.61%   |
| WDC WD2500BEVT-75A23T0 250GB     | 1         | 0.61%   |
| WDC WD2500AAKX-001CA0 250GB      | 1         | 0.61%   |
| WDC WD2500AAJS-75M0A0 250GB      | 1         | 0.61%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.61%   |
| WDC WD1600BEVT-75ZCT1 160GB      | 1         | 0.61%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.61%   |
| WDC WD10JPVX-60JC3T1 1TB         | 1         | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.61%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1         | 0.61%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1         | 0.61%   |
| Unknown MMC Card  16GB           | 1         | 0.61%   |
| Unknown MMC Card  128GB          | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 48     | 43.9%   |
| WDC                 | 15        | 20     | 18.29%  |
| Toshiba             | 15        | 19     | 18.29%  |
| Hitachi             | 13        | 16     | 15.85%  |
| Samsung Electronics | 2         | 4      | 2.44%   |
| Maxtor              | 1         | 1      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 22.22%  |
| Kingston            | 10        | 11     | 22.22%  |
| SanDisk             | 7         | 11     | 15.56%  |
| WDC                 | 2         | 2      | 4.44%   |
| Transcend           | 2         | 2      | 4.44%   |
| Intel               | 2         | 2      | 4.44%   |
| FORESEE             | 2         | 2      | 4.44%   |
| SPCC                | 1         | 1      | 2.22%   |
| SK hynix            | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| Patriot             | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 2      | 2.22%   |
| Hewlett-Packard     | 1         | 1      | 2.22%   |
| Crucial             | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |
| Unknown             | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 70        | 108    | 51.09%  |
| SSD     | 41        | 52     | 29.93%  |
| NVMe    | 16        | 18     | 11.68%  |
| MMC     | 8         | 10     | 5.84%   |
| Unknown | 2         | 2      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 157    | 77.95%  |
| NVMe | 16        | 18     | 12.6%   |
| MMC  | 8         | 10     | 6.3%    |
| SAS  | 4         | 5      | 3.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 117    | 69.57%  |
| 0.51-1.0   | 26        | 33     | 22.61%  |
| 1.01-2.0   | 5         | 5      | 4.35%   |
| 4.01-10.0  | 3         | 4      | 2.61%   |
| 3.01-4.0   | 1         | 1      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 39        | 32.23%  |
| 251-500        | 23        | 19.01%  |
| 501-1000       | 19        | 15.7%   |
| 1-20           | 11        | 9.09%   |
| 51-100         | 10        | 8.26%   |
| 21-50          | 7         | 5.79%   |
| More than 3000 | 4         | 3.31%   |
| 1001-2000      | 4         | 3.31%   |
| Unknown        | 3         | 2.48%   |
| 2001-3000      | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 50        | 38.46%  |
| 21-50          | 28        | 21.54%  |
| 51-100         | 16        | 12.31%  |
| 101-250        | 12        | 9.23%   |
| 251-500        | 9         | 6.92%   |
| 501-1000       | 7         | 5.38%   |
| Unknown        | 3         | 2.31%   |
| 2001-3000      | 2         | 1.54%   |
| 1001-2000      | 2         | 1.54%   |
| More than 3000 | 1         | 0.77%   |

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
| Hitachi HDS721025CLA382 165GB | 1         | 1      | 100%    |

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
| Detected | 74        | 124    | 58.73%  |
| Works    | 34        | 44     | 26.98%  |
| Malfunc  | 17        | 21     | 13.49%  |
| Failed   | 1         | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 80        | 66.12%  |
| AMD                              | 23        | 19.01%  |
| Samsung Electronics              | 5         | 4.13%   |
| SanDisk                          | 3         | 2.48%   |
| Toshiba America Info Systems     | 2         | 1.65%   |
| VIA Technologies                 | 1         | 0.83%   |
| SK hynix                         | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Phison Electronics               | 1         | 0.83%   |
| Nvidia                           | 1         | 0.83%   |
| Micron/Crucial Technology        | 1         | 0.83%   |
| Micron Technology                | 1         | 0.83%   |
| Marvell Technology Group         | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 10.27%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 5.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 4.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 3.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 3.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.74%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 2.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 2.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.05%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3         | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 2.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.37%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.37%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.68%   |
| VIA VIA VT6420 SATA RAID Controller                                              | 1         | 0.68%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.68%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.68%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.68%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.68%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.68%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 80        | 61.07%  |
| IDE  | 23        | 17.56%  |
| NVMe | 16        | 12.21%  |
| RAID | 12        | 9.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 90        | 78.26%  |
| AMD    | 25        | 21.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 3.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 2.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 2.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.74%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.74%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.74%   |
| AMD FX-8320 Eight-Core Processor            | 2         | 1.74%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.74%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.87%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.87%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.87%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.87%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.87%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.87%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.87%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.87%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.87%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.87%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.87%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.87%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.87%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.87%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.87%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.87%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.87%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.87%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.87%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.87%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 0.87%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.87%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.87%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.87%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 29.57%  |
| Intel Core i7           | 13        | 11.3%   |
| Intel Celeron           | 11        | 9.57%   |
| Intel Core i3           | 8         | 6.96%   |
| Intel Core 2 Duo        | 6         | 5.22%   |
| AMD Ryzen 5             | 6         | 5.22%   |
| AMD FX                  | 4         | 3.48%   |
| Intel Pentium           | 3         | 2.61%   |
| Intel Atom              | 3         | 2.61%   |
| Intel Xeon              | 2         | 1.74%   |
| Intel Pentium Dual-Core | 2         | 1.74%   |
| Intel Core 2            | 2         | 1.74%   |
| AMD Ryzen 7             | 2         | 1.74%   |
| AMD A8                  | 2         | 1.74%   |
| AMD A10                 | 2         | 1.74%   |
| Intel Pentium Dual      | 1         | 0.87%   |
| Intel Pentium D         | 1         | 0.87%   |
| Intel Pentium 4         | 1         | 0.87%   |
| Intel Genuine           | 1         | 0.87%   |
| Intel Core i9           | 1         | 0.87%   |
| Intel Core 2 Quad       | 1         | 0.87%   |
| AMD Sempron             | 1         | 0.87%   |
| AMD Ryzen 3             | 1         | 0.87%   |
| AMD Quad-Core           | 1         | 0.87%   |
| AMD PRO A10             | 1         | 0.87%   |
| AMD Phenom II X4        | 1         | 0.87%   |
| AMD Mobile Sempron      | 1         | 0.87%   |
| AMD A6                  | 1         | 0.87%   |
| AMD A4                  | 1         | 0.87%   |
| AMD A12                 | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 57.39%  |
| 4      | 36        | 31.3%   |
| 6      | 5         | 4.35%   |
| 1      | 4         | 3.48%   |
| 8      | 2         | 1.74%   |
| 12     | 1         | 0.87%   |
| 3      | 1         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 114       | 99.13%  |
| 2      | 1         | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 65        | 56.52%  |
| 1      | 50        | 43.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 113       | 97.41%  |
| 64-bit         | 1         | 0.86%   |
| 32-bit         | 1         | 0.86%   |
| Unknown        | 1         | 0.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 18.1%   |
| 0x206a7    | 12        | 10.34%  |
| 0x306a9    | 10        | 8.62%   |
| 0x1067a    | 7         | 6.03%   |
| 0x306c3    | 6         | 5.17%   |
| 0x806e9    | 5         | 4.31%   |
| 0x40651    | 5         | 4.31%   |
| 0x806ea    | 3         | 2.59%   |
| 0x706a1    | 3         | 2.59%   |
| 0x506e3    | 3         | 2.59%   |
| 0x0800820d | 3         | 2.59%   |
| 0x07030105 | 3         | 2.59%   |
| 0x06000852 | 3         | 2.59%   |
| 0x6fb      | 2         | 1.72%   |
| 0x6f6      | 2         | 1.72%   |
| 0x30678    | 2         | 1.72%   |
| 0x20652    | 2         | 1.72%   |
| 0x0600611a | 2         | 1.72%   |
| 0xf65      | 1         | 0.86%   |
| 0xf49      | 1         | 0.86%   |
| 0x906ea    | 1         | 0.86%   |
| 0x906e9    | 1         | 0.86%   |
| 0x806ec    | 1         | 0.86%   |
| 0x706e5    | 1         | 0.86%   |
| 0x6fd      | 1         | 0.86%   |
| 0x506c9    | 1         | 0.86%   |
| 0x406c3    | 1         | 0.86%   |
| 0x20655    | 1         | 0.86%   |
| 0x106c2    | 1         | 0.86%   |
| 0x10676    | 1         | 0.86%   |
| 0x10661    | 1         | 0.86%   |
| 0x08608102 | 1         | 0.86%   |
| 0x08600103 | 1         | 0.86%   |
| 0x08108109 | 1         | 0.86%   |
| 0x08108102 | 1         | 0.86%   |
| 0x08101013 | 1         | 0.86%   |
| 0x0700010f | 1         | 0.86%   |
| 0x06003106 | 1         | 0.86%   |
| 0x06001119 | 1         | 0.86%   |
| 0x010000db | 1         | 0.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 13.91%  |
| SandyBridge   | 12        | 10.43%  |
| IvyBridge     | 12        | 10.43%  |
| Haswell       | 12        | 10.43%  |
| Penryn        | 8         | 6.96%   |
| Westmere      | 6         | 5.22%   |
| Silvermont    | 6         | 5.22%   |
| Core          | 6         | 5.22%   |
| Zen+          | 5         | 4.35%   |
| Piledriver    | 4         | 3.48%   |
| Goldmont plus | 4         | 3.48%   |
| Skylake       | 3         | 2.61%   |
| Puma          | 3         | 2.61%   |
| NetBurst      | 2         | 1.74%   |
| K8 Hammer     | 2         | 1.74%   |
| Excavator     | 2         | 1.74%   |
| Zen 3         | 1         | 0.87%   |
| Zen 2         | 1         | 0.87%   |
| Zen           | 1         | 0.87%   |
| Steamroller   | 1         | 0.87%   |
| K10 Llano     | 1         | 0.87%   |
| K10           | 1         | 0.87%   |
| Jaguar        | 1         | 0.87%   |
| IceLake       | 1         | 0.87%   |
| Goldmont      | 1         | 0.87%   |
| Bulldozer     | 1         | 0.87%   |
| Bonnell       | 1         | 0.87%   |
| Unknown       | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 78        | 61.42%  |
| AMD                              | 29        | 22.83%  |
| Nvidia                           | 18        | 14.17%  |
| VIA Technologies                 | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 7.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 6.06%   |
| Intel HD Graphics 620                                                                    | 5         | 3.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.79%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.27%   |
| Intel HD Graphics 530                                                                    | 3         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.27%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.52%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 1.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.52%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.52%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.76%   |
| Nvidia TU117M                                                                            | 1         | 0.76%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.76%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.76%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.76%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.76%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.76%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.76%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 59.13%  |
| 1 x AMD        | 21        | 18.26%  |
| 1 x Nvidia     | 12        | 10.43%  |
| Intel + Nvidia | 4         | 3.48%   |
| Intel + AMD    | 4         | 3.48%   |
| 2 x AMD        | 2         | 1.74%   |
| AMD + Nvidia   | 2         | 1.74%   |
| 1 x VIA        | 1         | 0.87%   |
| 1 x SiS        | 1         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 87.93%  |
| Proprietary | 11        | 9.48%   |
| Unknown     | 3         | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 64.66%  |
| 1.01-2.0   | 11        | 9.48%   |
| 0.01-0.5   | 11        | 9.48%   |
| 0.51-1.0   | 10        | 8.62%   |
| 3.01-4.0   | 6         | 5.17%   |
| 7.01-8.0   | 2         | 1.72%   |
| 2.01-3.0   | 1         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 15.65%  |
| Samsung Electronics     | 12        | 10.43%  |
| LG Display              | 12        | 10.43%  |
| BOE                     | 12        | 10.43%  |
| Dell                    | 11        | 9.57%   |
| Chimei Innolux          | 9         | 7.83%   |
| Hewlett-Packard         | 6         | 5.22%   |
| Chi Mei Optoelectronics | 4         | 3.48%   |
| Apple                   | 4         | 3.48%   |
| AOC                     | 4         | 3.48%   |
| Sony                    | 3         | 2.61%   |
| Acer                    | 3         | 2.61%   |
| ZTR                     | 1         | 0.87%   |
| Westinghouse            | 1         | 0.87%   |
| Vizio                   | 1         | 0.87%   |
| ViewSonic               | 1         | 0.87%   |
| Sharp                   | 1         | 0.87%   |
| Philips                 | 1         | 0.87%   |
| PANDA                   | 1         | 0.87%   |
| NEC Computers           | 1         | 0.87%   |
| LG Philips              | 1         | 0.87%   |
| LG Electronics          | 1         | 0.87%   |
| Lenovo                  | 1         | 0.87%   |
| KTC                     | 1         | 0.87%   |
| KDC                     | 1         | 0.87%   |
| InnoLux Display         | 1         | 0.87%   |
| Goldstar                | 1         | 0.87%   |
| BenQ                    | 1         | 0.87%   |
| Ancor Communications    | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                           | 2         | 1.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch    | 2         | 1.71%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 2         | 1.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 1.71%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                         | 2         | 1.71%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                    | 1         | 0.85%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch            | 1         | 0.85%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                    | 1         | 0.85%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.85%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                           | 1         | 0.85%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch                 | 1         | 0.85%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 610x350mm 27.7-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch    | 1         | 0.85%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch               | 1         | 0.85%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch                 | 1         | 0.85%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch            | 1         | 0.85%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch             | 1         | 0.85%   |
| LG Electronics LCD Monitor W1943 1984x768                               | 1         | 0.85%   |
| LG Electronics LCD Monitor LG TV                                        | 1         | 0.85%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 0.85%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch                 | 1         | 0.85%   |
| KTC 32T72-H-AN KTC3200 1360x768 698x392mm 31.5-inch                     | 1         | 0.85%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                    | 1         | 0.85%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch        | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 40        | 35.71%  |
| 1920x1080 (FHD)    | 33        | 29.46%  |
| 1280x800 (WXGA)    | 7         | 6.25%   |
| 1280x1024 (SXGA)   | 7         | 6.25%   |
| 1600x900 (HD+)     | 5         | 4.46%   |
| 3840x2160 (4K)     | 3         | 2.68%   |
| 1680x1050 (WSXGA+) | 3         | 2.68%   |
| 1360x768           | 3         | 2.68%   |
| 2560x1440 (QHD)    | 2         | 1.79%   |
| 1440x900 (WXGA+)   | 2         | 1.79%   |
| 1024x768 (XGA)     | 2         | 1.79%   |
| 3840x1100          | 1         | 0.89%   |
| 1984x768           | 1         | 0.89%   |
| 1800x1200          | 1         | 0.89%   |
| 1280x768           | 1         | 0.89%   |
| Unknown            | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 33.04%  |
| 13      | 16        | 13.91%  |
| 14      | 11        | 9.57%   |
| 11      | 7         | 6.09%   |
| 17      | 6         | 5.22%   |
| 27      | 4         | 3.48%   |
| 24      | 4         | 3.48%   |
| 22      | 4         | 3.48%   |
| 21      | 4         | 3.48%   |
| 19      | 4         | 3.48%   |
| 18      | 3         | 2.61%   |
| Unknown | 3         | 2.61%   |
| 50      | 2         | 1.74%   |
| 84      | 1         | 0.87%   |
| 72      | 1         | 0.87%   |
| 41      | 1         | 0.87%   |
| 40      | 1         | 0.87%   |
| 34      | 1         | 0.87%   |
| 32      | 1         | 0.87%   |
| 31      | 1         | 0.87%   |
| 20      | 1         | 0.87%   |
| 10      | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 50.89%  |
| 201-300     | 17        | 15.18%  |
| 401-500     | 14        | 12.5%   |
| 501-600     | 8         | 7.14%   |
| 351-400     | 4         | 3.57%   |
| Unknown     | 3         | 2.68%   |
| 701-800     | 2         | 1.79%   |
| 1501-2000   | 2         | 1.79%   |
| 1001-1500   | 2         | 1.79%   |
| 801-900     | 1         | 0.89%   |
| 601-700     | 1         | 0.89%   |
| 901-1000    | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 78        | 75%     |
| 16/10   | 13        | 12.5%   |
| 5/4     | 6         | 5.77%   |
| Unknown | 3         | 2.88%   |
| 4/3     | 2         | 1.92%   |
| 3/2     | 1         | 0.96%   |
| 3.40    | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 33.04%  |
| 81-90          | 20        | 17.39%  |
| 201-250        | 9         | 7.83%   |
| 51-60          | 8         | 6.96%   |
| 151-200        | 8         | 6.96%   |
| 141-150        | 8         | 6.96%   |
| 71-80          | 6         | 5.22%   |
| More than 1000 | 4         | 3.48%   |
| 301-350        | 4         | 3.48%   |
| 501-1000       | 3         | 2.61%   |
| Unknown        | 3         | 2.61%   |
| 351-500        | 2         | 1.74%   |
| 41-50          | 1         | 0.87%   |
| 121-130        | 1         | 0.87%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 44        | 39.64%  |
| 51-100        | 30        | 27.03%  |
| 121-160       | 23        | 20.72%  |
| 1-50          | 6         | 5.41%   |
| 161-240       | 4         | 3.6%    |
| Unknown       | 3         | 2.7%    |
| More than 240 | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 94        | 80.34%  |
| 2     | 15        | 12.82%  |
| 0     | 7         | 5.98%   |
| 3     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 57        | 32.95%  |
| Intel                           | 51        | 29.48%  |
| Qualcomm Atheros                | 25        | 14.45%  |
| Broadcom                        | 17        | 9.83%   |
| Ralink Technology               | 5         | 2.89%   |
| Qualcomm Atheros Communications | 3         | 1.73%   |
| Marvell Technology Group        | 2         | 1.16%   |
| Broadcom Limited                | 2         | 1.16%   |
| VIA Technologies                | 1         | 0.58%   |
| Tul Corporation / PowerColor    | 1         | 0.58%   |
| TP-Link                         | 1         | 0.58%   |
| Nvidia                          | 1         | 0.58%   |
| MediaTek                        | 1         | 0.58%   |
| Linksys                         | 1         | 0.58%   |
| Lenovo                          | 1         | 0.58%   |
| JCM                             | 1         | 0.58%   |
| HTC (High Tech Computer)        | 1         | 0.58%   |
| Dell                            | 1         | 0.58%   |
| AMD                             | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 16.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.4%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.92%   |
| Intel Wireless 7260                                               | 4         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.92%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.44%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.44%   |
| Intel Wireless 3165                                               | 3         | 1.44%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.96%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.96%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.96%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.96%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.96%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.48%   |
| Tul Corporation / PowerColor Network controller                   | 1         | 0.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.48%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 36.63%  |
| Qualcomm Atheros                | 21        | 20.79%  |
| Realtek Semiconductor           | 20        | 19.8%   |
| Broadcom                        | 10        | 9.9%    |
| Ralink Technology               | 5         | 4.95%   |
| Qualcomm Atheros Communications | 3         | 2.97%   |
| TP-Link                         | 1         | 0.99%   |
| MediaTek                        | 1         | 0.99%   |
| Linksys                         | 1         | 0.99%   |
| Dell                            | 1         | 0.99%   |
| Broadcom Limited                | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 4.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 4.9%    |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.92%   |
| Intel Wireless 7260                                                                   | 4         | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 2.94%   |
| Intel Wireless 3165                                                                   | 3         | 2.94%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.96%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.96%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.96%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.96%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.98%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.98%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.98%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.98%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.98%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.98%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]                         | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 49        | 47.57%  |
| Intel                    | 32        | 31.07%  |
| Broadcom                 | 9         | 8.74%   |
| Qualcomm Atheros         | 6         | 5.83%   |
| Marvell Technology Group | 2         | 1.94%   |
| VIA Technologies         | 1         | 0.97%   |
| Nvidia                   | 1         | 0.97%   |
| Lenovo                   | 1         | 0.97%   |
| HTC (High Tech Computer) | 1         | 0.97%   |
| Broadcom Limited         | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 33.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 10.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 9.71%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.88%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 3.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.94%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.94%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.97%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.97%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.97%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.97%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.97%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.97%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.97%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1         | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.97%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.97%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.97%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.97%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 99        | 50.25%  |
| WiFi     | 95        | 48.22%  |
| Modem    | 2         | 1.02%   |
| Unknown  | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 63.87%  |
| Ethernet | 43        | 36.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 60%     |
| 1     | 42        | 36.52%  |
| 0     | 4         | 3.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 115       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 38.71%  |
| Qualcomm Atheros Communications | 11        | 17.74%  |
| IMC Networks                    | 5         | 8.06%   |
| Dell                            | 5         | 8.06%   |
| Cambridge Silicon Radio         | 4         | 6.45%   |
| Apple                           | 4         | 6.45%   |
| Realtek Semiconductor           | 3         | 4.84%   |
| Lite-On Technology              | 2         | 3.23%   |
| Broadcom                        | 2         | 3.23%   |
| Hewlett-Packard                 | 1         | 1.61%   |
| ASUSTek Computer                | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 19.35%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 9.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 6.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 4.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.84%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 4.84%   |
| Apple Bluetooth Host Controller                     | 3         | 4.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.23%   |
| Intel AX200 Bluetooth                               | 2         | 3.23%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.23%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.61%   |
| Realtek Bluetooth Radio                             | 1         | 1.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.61%   |
| Lite-On Wireless_Device                             | 1         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.61%   |
| Intel AX201 Bluetooth                               | 1         | 1.61%   |
| IMC Networks Bluetooth                              | 1         | 1.61%   |
| IMC Networks BCM20702A0                             | 1         | 1.61%   |
| IMC Networks 802.11ac WLAN Adapter                  | 1         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.61%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.61%   |
| Dell Wireless 350 Bluetooth                         | 1         | 1.61%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.61%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.61%   |
| Apple Bluetooth HCI                                 | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 61.76%  |
| AMD                              | 28        | 20.59%  |
| Nvidia                           | 16        | 11.76%  |
| VIA Technologies                 | 1         | 0.74%   |
| Sony                             | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |
| Logitech                         | 1         | 0.74%   |
| Creative Labs                    | 1         | 0.74%   |
| C-Media Electronics              | 1         | 0.74%   |
| Blue Microphones                 | 1         | 0.74%   |
| BigBen Interactive               | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 7.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 4.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.24%   |
| AMD FCH Azalia Controller                                                  | 7         | 4.24%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 3.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.03%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 3.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 2.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.21%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.21%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2         | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.21%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.61%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 30.3%   |
| Samsung Electronics | 15        | 22.73%  |
| Micron Technology   | 5         | 7.58%   |
| Unknown             | 4         | 6.06%   |
| Kingston            | 4         | 6.06%   |
| Ramaxel Technology  | 3         | 4.55%   |
| Nanya Technology    | 2         | 3.03%   |
| Corsair             | 2         | 3.03%   |
| V-Color             | 1         | 1.52%   |
| Unknown (ABCD)      | 1         | 1.52%   |
| Sesame              | 1         | 1.52%   |
| Qimonda             | 1         | 1.52%   |
| Patriot             | 1         | 1.52%   |
| G.Skill             | 1         | 1.52%   |
| Elpida              | 1         | 1.52%   |
| Crucial             | 1         | 1.52%   |
| Avant               | 1         | 1.52%   |
| A-DATA Technology   | 1         | 1.52%   |
| Unknown             | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.82%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.82%   |
| V-Color RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s              | 1         | 1.41%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 1.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.41%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 1.41%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.41%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 1.41%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.41%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 667MT/s              | 1         | 1.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.41%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.41%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s          | 1         | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s        | 1         | 1.41%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.41%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.41%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.41%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.41%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 20        | 38.46%  |
| DDR4    | 18        | 34.62%  |
| SDRAM   | 5         | 9.62%   |
| LPDDR4  | 3         | 5.77%   |
| DDR2    | 2         | 3.85%   |
| Unknown | 2         | 3.85%   |
| LPDDR3  | 1         | 1.92%   |
| DDR     | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 60%     |
| DIMM         | 18        | 36%     |
| Row Of Chips | 2         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 25        | 44.64%  |
| 8192  | 14        | 25%     |
| 2048  | 9         | 16.07%  |
| 16384 | 5         | 8.93%   |
| 1024  | 2         | 3.57%   |
| 512   | 1         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 28.33%  |
| 2667    | 7         | 11.67%  |
| 2400    | 6         | 10%     |
| 1333    | 6         | 10%     |
| 2133    | 3         | 5%      |
| 4199    | 2         | 3.33%   |
| 3200    | 2         | 3.33%   |
| 2933    | 2         | 3.33%   |
| 1867    | 2         | 3.33%   |
| 1067    | 2         | 3.33%   |
| 667     | 2         | 3.33%   |
| 49926   | 1         | 1.67%   |
| 4267    | 1         | 1.67%   |
| 3600    | 1         | 1.67%   |
| 3266    | 1         | 1.67%   |
| 2934    | 1         | 1.67%   |
| 2666    | 1         | 1.67%   |
| 1334    | 1         | 1.67%   |
| 533     | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

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
| Chicony Electronics                    | 12        | 16.22%  |
| Microdia                               | 7         | 9.46%   |
| Sunplus Innovation Technology          | 6         | 8.11%   |
| Realtek Semiconductor                  | 6         | 8.11%   |
| Suyin                                  | 5         | 6.76%   |
| IMC Networks                           | 5         | 6.76%   |
| Apple                                  | 5         | 6.76%   |
| Syntek                                 | 4         | 5.41%   |
| Silicon Motion                         | 3         | 4.05%   |
| Ricoh                                  | 3         | 4.05%   |
| Microsoft                              | 3         | 4.05%   |
| OmniVision Technologies                | 2         | 2.7%    |
| Logitech                               | 2         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.7%    |
| Acer                                   | 2         | 2.7%    |
| Unknown                                | 1         | 1.35%   |
| Sonix Technology                       | 1         | 1.35%   |
| Samsung Electronics                    | 1         | 1.35%   |
| Primax Electronics                     | 1         | 1.35%   |
| Jieli Technology                       | 1         | 1.35%   |
| globaloptics                           | 1         | 1.35%   |
| Alcor Micro                            | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD               | 4         | 5.41%   |
| Chicony Integrated Camera                  | 3         | 4.05%   |
| Syntek Lenovo EasyCamera                   | 2         | 2.7%    |
| Microsoft MicrosoftÂ LifeCam HD-5001      | 2         | 2.7%    |
| Microdia Integrated Webcam                 | 2         | 2.7%    |
| Microdia Dell Integrated HD Webcam         | 2         | 2.7%    |
| IMC Networks Integrated Camera             | 2         | 2.7%    |
| Chicony USB2.0 HD UVC WebCam               | 2         | 2.7%    |
| Apple iPhone5/5C/5S/6                      | 2         | 2.7%    |
| Apple FaceTime HD Camera                   | 2         | 2.7%    |
| Unknown 720p HD Camera                     | 1         | 1.35%   |
| Syntek Integrated Camera                   | 1         | 1.35%   |
| Syntek EasyCamera                          | 1         | 1.35%   |
| Suyin VGA Webcam                           | 1         | 1.35%   |
| Suyin TOSHIBA Web Camera - HD              | 1         | 1.35%   |
| Suyin HP TrueVision HD                     | 1         | 1.35%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.35%   |
| Suyin 1.3M HD WebCam                       | 1         | 1.35%   |
| Sunplus Laptop_Integrated_Webcam_HD        | 1         | 1.35%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.35%   |
| Sonix HP Webcam-101                        | 1         | 1.35%   |
| Silicon Motion WebCam SCB-0385N            | 1         | 1.35%   |
| Silicon Motion WebCam SC-10HDD13335N       | 1         | 1.35%   |
| Silicon Motion Real HD WebCam              | 1         | 1.35%   |
| Samsung Galaxy A5 (MTP)                    | 1         | 1.35%   |
| Ricoh Laptop_Integrated_Webcam_FHD         | 1         | 1.35%   |
| Ricoh Integrated Webcam                    | 1         | 1.35%   |
| Ricoh HD Webcam                            | 1         | 1.35%   |
| Realtek USB2.0 camera                      | 1         | 1.35%   |
| Realtek Integrated Webcam HD               | 1         | 1.35%   |
| Realtek Integrated Webcam                  | 1         | 1.35%   |
| Realtek Integrated Camera                  | 1         | 1.35%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.35%   |
| Realtek HP Truevision HD integrated webcam | 1         | 1.35%   |
| Primax HP HD Webcam [Fixed]                | 1         | 1.35%   |
| OmniVision Monitor Webcam                  | 1         | 1.35%   |
| OmniVision Monitor Integrated Webcam       | 1         | 1.35%   |
| Microsoft LifeCam VX-2000                  | 1         | 1.35%   |
| Microdia Sonix USB 2.0 Camera              | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_E4HD     | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 54.55%  |
| Synaptics                  | 3         | 27.27%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Samsung Electronics        | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 9.09%   |
| Validity Sensors VFS491                           | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner              | 1         | 9.09%   |
| Synaptics  WBDI                                   | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 9.09%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| O2 Micro    | 2         | 22.22%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 22.22%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 84        | 72.41%  |
| 1     | 28        | 24.14%  |
| 2     | 4         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 30.56%  |
| Graphics card         | 8         | 22.22%  |
| Chipcard              | 8         | 22.22%  |
| Storage               | 2         | 5.56%   |
| Multimedia controller | 2         | 5.56%   |
| Network               | 1         | 2.78%   |
| Net/wireless          | 1         | 2.78%   |
| Card reader           | 1         | 2.78%   |
| Camera                | 1         | 2.78%   |
| Bluetooth             | 1         | 2.78%   |


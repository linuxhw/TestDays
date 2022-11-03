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

Total: 181

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 21        | 17.07%  |
| Ubuntu 18.04                 | 17        | 13.82%  |
| OpenMandriva 4.2             | 5         | 4.07%   |
| Arch Rolling                 | 5         | 4.07%   |
| OpenMandriva 4.3             | 4         | 3.25%   |
| Fedora 36                    | 4         | 3.25%   |
| Ubuntu 22.04                 | 3         | 2.44%   |
| Linux Mint 20.3              | 3         | 2.44%   |
| Fedora 34                    | 3         | 2.44%   |
| Debian 11                    | 3         | 2.44%   |
| Arch                         | 3         | 2.44%   |
| Ubuntu 21.10                 | 2         | 1.63%   |
| Pop!_OS 20.10                | 2         | 1.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.63%   |
| Linux Mint 21                | 2         | 1.63%   |
| Linux Mint 20.1              | 2         | 1.63%   |
| Linux Mint 19.3              | 2         | 1.63%   |
| Fedora 33                    | 2         | 1.63%   |
| ArcoLinux Rolling            | 2         | 1.63%   |
| Xubuntu 19.10                | 1         | 0.81%   |
| Xubuntu 18.04                | 1         | 0.81%   |
| Void Linux Rolling           | 1         | 0.81%   |
| Ubuntu Budgie 22.04          | 1         | 0.81%   |
| Ubuntu Budgie 21.10          | 1         | 0.81%   |
| Ubuntu Budgie 20.04          | 1         | 0.81%   |
| Ubuntu 21.04                 | 1         | 0.81%   |
| Ubuntu 19.10                 | 1         | 0.81%   |
| Ubuntu 19.04                 | 1         | 0.81%   |
| Solus 4.1                    | 1         | 0.81%   |
| ROSA R10                     | 1         | 0.81%   |
| Pop!_OS 22.04                | 1         | 0.81%   |
| Pop!_OS 21.04                | 1         | 0.81%   |
| Pop!_OS 20.04                | 1         | 0.81%   |
| OpenMandriva 4.90            | 1         | 0.81%   |
| Manjaro 21.2.3               | 1         | 0.81%   |
| Manjaro 21.1.2               | 1         | 0.81%   |
| Manjaro 20.1                 | 1         | 0.81%   |
| Lubuntu 21.04                | 1         | 0.81%   |
| LMDE 4                       | 1         | 0.81%   |
| Linux Mint 20.2              | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 44        | 36.36%  |
| Fedora        | 12        | 9.92%   |
| Linux Mint    | 11        | 9.09%   |
| OpenMandriva  | 10        | 8.26%   |
| Arch          | 8         | 6.61%   |
| Pop!_OS       | 5         | 4.13%   |
| Debian        | 4         | 3.31%   |
| Ubuntu Budgie | 3         | 2.48%   |
| Manjaro       | 3         | 2.48%   |
| Clear Linux   | 3         | 2.48%   |
| Xubuntu       | 2         | 1.65%   |
| openSUSE      | 2         | 1.65%   |
| ArcoLinux     | 2         | 1.65%   |
| Void Linux    | 1         | 0.83%   |
| Solus         | 1         | 0.83%   |
| ROSA          | 1         | 0.83%   |
| Lubuntu       | 1         | 0.83%   |
| LMDE          | 1         | 0.83%   |
| Kubuntu       | 1         | 0.83%   |
| KDE neon      | 1         | 0.83%   |
| Kali          | 1         | 0.83%   |
| Elementary    | 1         | 0.83%   |
| CentOS        | 1         | 0.83%   |
| BlackPanther  | 1         | 0.83%   |
| Archcraft     | 1         | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 4         | 2.86%   |
| 5.4.0-42-generic         | 4         | 2.86%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.86%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.86%   |
| 5.13.0-22-generic        | 3         | 2.14%   |
| 5.4.0-77-generic         | 2         | 1.43%   |
| 5.4.0-52-generic         | 2         | 1.43%   |
| 5.4.0-33-generic         | 2         | 1.43%   |
| 5.3.0-51-generic         | 2         | 1.43%   |
| 5.3.0-46-generic         | 2         | 1.43%   |
| 5.3.0-42-generic         | 2         | 1.43%   |
| 5.15.0-50-generic        | 2         | 1.43%   |
| 5.15.0-41-generic        | 2         | 1.43%   |
| 5.11.0-40-generic        | 2         | 1.43%   |
| 5.11.0-25-generic        | 2         | 1.43%   |
| 5.0.0-32-generic         | 2         | 1.43%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.71%   |
| 5.9.12-xanmod1           | 1         | 0.71%   |
| 5.9.11-arch2-1           | 1         | 0.71%   |
| 5.9.1-arch1-1            | 1         | 0.71%   |
| 5.8.8-arch1-1            | 1         | 0.71%   |
| 5.8.5-arch1-1            | 1         | 0.71%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.71%   |
| 5.8.12_1                 | 1         | 0.71%   |
| 5.8.0-38-generic         | 1         | 0.71%   |
| 5.7.7-zen1-1-zen         | 1         | 0.71%   |
| 5.7.7-arch1-1            | 1         | 0.71%   |
| 5.7.10-201.fc32.x86_64   | 1         | 0.71%   |
| 5.6.19-158.current       | 1         | 0.71%   |
| 5.5.13-arch1-1           | 1         | 0.71%   |
| 5.4.60-2-MANJARO         | 1         | 0.71%   |
| 5.4.4-879.native         | 1         | 0.71%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.71%   |
| 5.4.0-7642-generic       | 1         | 0.71%   |
| 5.4.0-74-generic         | 1         | 0.71%   |
| 5.4.0-72-generic         | 1         | 0.71%   |
| 5.4.0-39-generic         | 1         | 0.71%   |
| 5.4.0-37-generic         | 1         | 0.71%   |
| 5.4.0-29-generic         | 1         | 0.71%   |
| 5.4.0-28-generic         | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 19.38%  |
| 5.13.0  | 10        | 7.75%   |
| 5.3.0   | 9         | 6.98%   |
| 5.11.0  | 8         | 6.2%    |
| 5.15.0  | 6         | 4.65%   |
| 4.15.0  | 6         | 4.65%   |
| 5.0.0   | 5         | 3.88%   |
| 5.16.7  | 4         | 3.1%    |
| 5.10.14 | 4         | 3.1%    |
| 5.10.0  | 3         | 2.33%   |
| 5.7.7   | 2         | 1.55%   |
| 4.19.0  | 2         | 1.55%   |
| 4.18.0  | 2         | 1.55%   |
| 5.9.16  | 1         | 0.78%   |
| 5.9.12  | 1         | 0.78%   |
| 5.9.11  | 1         | 0.78%   |
| 5.9.1   | 1         | 0.78%   |
| 5.8.8   | 1         | 0.78%   |
| 5.8.5   | 1         | 0.78%   |
| 5.8.15  | 1         | 0.78%   |
| 5.8.12  | 1         | 0.78%   |
| 5.8.0   | 1         | 0.78%   |
| 5.7.10  | 1         | 0.78%   |
| 5.6.19  | 1         | 0.78%   |
| 5.5.13  | 1         | 0.78%   |
| 5.4.60  | 1         | 0.78%   |
| 5.4.4   | 1         | 0.78%   |
| 5.4.15  | 1         | 0.78%   |
| 5.19.7  | 1         | 0.78%   |
| 5.19.14 | 1         | 0.78%   |
| 5.19.12 | 1         | 0.78%   |
| 5.18.17 | 1         | 0.78%   |
| 5.18.13 | 1         | 0.78%   |
| 5.18.12 | 1         | 0.78%   |
| 5.18.11 | 1         | 0.78%   |
| 5.18.10 | 1         | 0.78%   |
| 5.17.6  | 1         | 0.78%   |
| 5.17.4  | 1         | 0.78%   |
| 5.15.21 | 1         | 0.78%   |
| 5.14.13 | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 22.05%  |
| 5.13    | 11        | 8.66%   |
| 5.11    | 10        | 7.87%   |
| 5.3     | 9         | 7.09%   |
| 5.10    | 8         | 6.3%    |
| 5.15    | 7         | 5.51%   |
| 5.0     | 6         | 4.72%   |
| 4.15    | 6         | 4.72%   |
| 5.8     | 5         | 3.94%   |
| 5.9     | 4         | 3.15%   |
| 5.18    | 4         | 3.15%   |
| 5.16    | 4         | 3.15%   |
| 5.12    | 4         | 3.15%   |
| 4.18    | 4         | 3.15%   |
| 5.7     | 3         | 2.36%   |
| 5.19    | 3         | 2.36%   |
| 4.19    | 3         | 2.36%   |
| 5.17    | 2         | 1.57%   |
| 5.1     | 2         | 1.57%   |
| 5.6     | 1         | 0.79%   |
| 5.5     | 1         | 0.79%   |
| 5.14    | 1         | 0.79%   |
| 4.9     | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 96.69%  |
| i686   | 4         | 3.31%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 58        | 47.54%  |
| KDE5       | 18        | 14.75%  |
| XFCE       | 11        | 9.02%   |
| Unknown    | 11        | 9.02%   |
| X-Cinnamon | 9         | 7.38%   |
| KDE        | 4         | 3.28%   |
| Budgie     | 4         | 3.28%   |
| MATE       | 2         | 1.64%   |
| sway       | 1         | 0.82%   |
| LXQt       | 1         | 0.82%   |
| LXDE       | 1         | 0.82%   |
| KDE4       | 1         | 0.82%   |
| DWM        | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 101       | 82.79%  |
| Wayland | 15        | 12.3%   |
| Unknown | 4         | 3.28%   |
| Tty     | 2         | 1.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 54.55%  |
| SDDM    | 21        | 17.36%  |
| GDM     | 14        | 11.57%  |
| LightDM | 8         | 6.61%   |
| GDM3    | 7         | 5.79%   |
| TDM     | 4         | 3.31%   |
| KDM     | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 62        | 50.41%  |
| es_DO   | 34        | 27.64%  |
| Unknown | 14        | 11.38%  |
| es_ES   | 5         | 4.07%   |
| es_MX   | 3         | 2.44%   |
| en_CA   | 2         | 1.63%   |
| fr_FR   | 1         | 0.81%   |
| es_US   | 1         | 0.81%   |
| C       | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 71        | 58.68%  |
| EFI  | 50        | 41.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 92        | 76.03%  |
| Overlay | 11        | 9.09%   |
| Btrfs   | 10        | 8.26%   |
| Xfs     | 4         | 3.31%   |
| Unknown | 2         | 1.65%   |
| Zfs     | 1         | 0.83%   |
| F2fs    | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 72        | 59.02%  |
| GPT     | 36        | 29.51%  |
| MBR     | 14        | 11.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 82.79%  |
| Yes       | 21        | 17.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 66.39%  |
| Yes       | 41        | 33.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 39        | 32.23%  |
| Hewlett-Packard     | 16        | 13.22%  |
| Lenovo              | 14        | 11.57%  |
| Gigabyte Technology | 9         | 7.44%   |
| ASUSTek Computer    | 9         | 7.44%   |
| Acer                | 5         | 4.13%   |
| MSI                 | 4         | 3.31%   |
| Apple               | 4         | 3.31%   |
| Samsung Electronics | 3         | 2.48%   |
| EVOO                | 2         | 1.65%   |
| ASRock              | 2         | 1.65%   |
| Unknown             | 2         | 1.65%   |
| Toshiba             | 1         | 0.83%   |
| TODOS INDUSTRIAL    | 1         | 0.83%   |
| SAELITE             | 1         | 0.83%   |
| Nuvision            | 1         | 0.83%   |
| Microsoft           | 1         | 0.83%   |
| Google              | 1         | 0.83%   |
| Fujitsu             | 1         | 0.83%   |
| Foxconn             | 1         | 0.83%   |
| ECS                 | 1         | 0.83%   |
| Chuwi               | 1         | 0.83%   |
| Biostar             | 1         | 0.83%   |
| AMI                 | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Gigabyte GA-78LMT-USB3 6.0                        | 2         | 1.65%   |
| EVOO EV-C-116-7                                   | 2         | 1.65%   |
| Dell OptiPlex 3010                                | 2         | 1.65%   |
| Dell Latitude E6540                               | 2         | 1.65%   |
| Dell Latitude E6430                               | 2         | 1.65%   |
| Dell Latitude E6420                               | 2         | 1.65%   |
| Dell Latitude E6410                               | 2         | 1.65%   |
| Dell Inspiron 5570                                | 2         | 1.65%   |
| Apple MacBookPro8,1                               | 2         | 1.65%   |
| Unknown                                           | 2         | 1.65%   |
| Toshiba Satellite C55-A                           | 1         | 0.83%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.83%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.83%   |
| Samsung 930QCG                                    | 1         | 0.83%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.83%   |
| SAELITE ES1AU11                                   | 1         | 0.83%   |
| Nuvision NES11                                    | 1         | 0.83%   |
| MSI MS-7A34                                       | 1         | 0.83%   |
| MSI MS-7817                                       | 1         | 0.83%   |
| MSI GE62 6QC                                      | 1         | 0.83%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.83%   |
| Microsoft Surface Go                              | 1         | 0.83%   |
| Lenovo Z50-75 80EC                                | 1         | 0.83%   |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.83%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.83%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.83%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.83%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.83%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.83%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.83%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.83%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.83%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 0.83%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.83%   |
| Lenovo G505s 20255                                | 1         | 0.83%   |
| Lenovo G40-70 20369                               | 1         | 0.83%   |
| HP ProBook 6470b                                  | 1         | 0.83%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 0.83%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 0.83%   |
| HP Pavilion dv6                                   | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 16        | 13.22%  |
| Dell OptiPlex              | 10        | 8.26%   |
| Dell Inspiron              | 8         | 6.61%   |
| Lenovo ThinkPad            | 6         | 4.96%   |
| Acer Aspire                | 5         | 4.13%   |
| HP Compaq                  | 4         | 3.31%   |
| HP Pavilion                | 3         | 2.48%   |
| Gigabyte GA-78LMT-USB3     | 3         | 2.48%   |
| Lenovo IdeaPad             | 2         | 1.65%   |
| HP EliteBook               | 2         | 1.65%   |
| Gigabyte B450M             | 2         | 1.65%   |
| EVOO EV-C-116-7            | 2         | 1.65%   |
| Dell Vostro                | 2         | 1.65%   |
| Apple MacBookPro8          | 2         | 1.65%   |
| Unknown                    | 2         | 1.65%   |
| Toshiba Satellite          | 1         | 0.83%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.83%   |
| Samsung RV420              | 1         | 0.83%   |
| Samsung 930QCG             | 1         | 0.83%   |
| Samsung 905S3G             | 1         | 0.83%   |
| SAELITE ES1AU11            | 1         | 0.83%   |
| Nuvision NES11             | 1         | 0.83%   |
| MSI MS-7A34                | 1         | 0.83%   |
| MSI MS-7817                | 1         | 0.83%   |
| MSI GE62                   | 1         | 0.83%   |
| MSI CR70                   | 1         | 0.83%   |
| Microsoft Surface          | 1         | 0.83%   |
| Lenovo Z50-75              | 1         | 0.83%   |
| Lenovo Yoga                | 1         | 0.83%   |
| Lenovo ThinkBook           | 1         | 0.83%   |
| Lenovo Legion              | 1         | 0.83%   |
| Lenovo G505s               | 1         | 0.83%   |
| Lenovo G40-70              | 1         | 0.83%   |
| HP ProBook                 | 1         | 0.83%   |
| HP Notebook                | 1         | 0.83%   |
| HP Laptop                  | 1         | 0.83%   |
| HP G60                     | 1         | 0.83%   |
| HP ENVY                    | 1         | 0.83%   |
| HP EliteDesk               | 1         | 0.83%   |
| HP 250                     | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 14        | 11.57%  |
| 2017 | 13        | 10.74%  |
| 2014 | 12        | 9.92%   |
| 2013 | 12        | 9.92%   |
| 2012 | 10        | 8.26%   |
| 2019 | 9         | 7.44%   |
| 2020 | 6         | 4.96%   |
| 2018 | 6         | 4.96%   |
| 2010 | 6         | 4.96%   |
| 2008 | 6         | 4.96%   |
| 2016 | 5         | 4.13%   |
| 2015 | 5         | 4.13%   |
| 2009 | 5         | 4.13%   |
| 2021 | 4         | 3.31%   |
| 2007 | 4         | 3.31%   |
| 2006 | 2         | 1.65%   |
| 2022 | 1         | 0.83%   |
| 2005 | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 78        | 64.46%  |
| Desktop     | 37        | 30.58%  |
| Tablet      | 2         | 1.65%   |
| Convertible | 2         | 1.65%   |
| Mini pc     | 1         | 0.83%   |
| All in one  | 1         | 0.83%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 117       | 96.69%  |
| Enabled  | 4         | 3.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 120       | 99.17%  |
| Yes  | 1         | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 30.58%  |
| 4.01-8.0    | 30        | 24.79%  |
| 8.01-16.0   | 18        | 14.88%  |
| 16.01-24.0  | 16        | 13.22%  |
| 2.01-3.0    | 5         | 4.13%   |
| 1.01-2.0    | 5         | 4.13%   |
| 32.01-64.0  | 4         | 3.31%   |
| 24.01-32.0  | 3         | 2.48%   |
| 0.51-1.0    | 2         | 1.65%   |
| 64.01-256.0 | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 54        | 41.54%  |
| 2.01-3.0  | 34        | 26.15%  |
| 3.01-4.0  | 22        | 16.92%  |
| 4.01-8.0  | 11        | 8.46%   |
| 0.51-1.0  | 8         | 6.15%   |
| 8.01-16.0 | 1         | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 67.21%  |
| 2      | 30        | 24.59%  |
| 3      | 6         | 4.92%   |
| 4      | 4         | 3.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 54.55%  |
| Yes       | 55        | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 85.95%  |
| No        | 17        | 14.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 82.79%  |
| No        | 21        | 17.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 53.72%  |
| No        | 56        | 46.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 121       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 75        | 60.48%  |
| Santiago de los Caballeros | 12        | 9.68%   |
| La Romana                  | 5         | 4.03%   |
| Santo Domingo              | 3         | 2.42%   |
| San Pedro de Macorís      | 3         | 2.42%   |
| Alejandro Bass             | 3         | 2.42%   |
| Sosua, Cabarete            | 2         | 1.61%   |
| Santa Cruz de Barahona     | 2         | 1.61%   |
| San Juan                   | 2         | 1.61%   |
| San Cristobal              | 2         | 1.61%   |
| Nacional                   | 2         | 1.61%   |
| Bajos de Haina             | 2         | 1.61%   |
| Santo Domingo Oeste        | 1         | 0.81%   |
| San Francisco de Macorís  | 1         | 0.81%   |
| Salcedo                    | 1         | 0.81%   |
| Punta Cana                 | 1         | 0.81%   |
| Moca                       | 1         | 0.81%   |
| Los Hidalgos               | 1         | 0.81%   |
| Guaymate                   | 1         | 0.81%   |
| Constanza                  | 1         | 0.81%   |
| Concepción de la Vega     | 1         | 0.81%   |
| Boca Chica                 | 1         | 0.81%   |
| Baní                      | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 37        | 49     | 23.13%  |
| WDC                       | 18        | 23     | 11.25%  |
| Toshiba                   | 17        | 22     | 10.63%  |
| Samsung Electronics       | 16        | 20     | 10%     |
| Hitachi                   | 13        | 16     | 8.13%   |
| Kingston                  | 12        | 13     | 7.5%    |
| SanDisk                   | 10        | 14     | 6.25%   |
| Unknown                   | 7         | 9      | 4.38%   |
| SK hynix                  | 4         | 5      | 2.5%    |
| Intel                     | 4         | 4      | 2.5%    |
| Unknown                   | 3         | 3      | 1.88%   |
| Transcend                 | 2         | 2      | 1.25%   |
| FORESEE                   | 2         | 2      | 1.25%   |
| A-DATA Technology         | 2         | 2      | 1.25%   |
| SPCC                      | 1         | 1      | 0.63%   |
| PNY                       | 1         | 1      | 0.63%   |
| Phison Electronics        | 1         | 1      | 0.63%   |
| Patriot                   | 1         | 1      | 0.63%   |
| OCZ                       | 1         | 1      | 0.63%   |
| Micron/Crucial Technology | 1         | 1      | 0.63%   |
| Micron Technology         | 1         | 1      | 0.63%   |
| Maxtor                    | 1         | 1      | 0.63%   |
| LITEONIT                  | 1         | 2      | 0.63%   |
| Indilinx                  | 1         | 1      | 0.63%   |
| Hewlett-Packard           | 1         | 1      | 0.63%   |
| ELOTEC                    | 1         | 1      | 0.63%   |
| Crucial                   | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB  | 4         | 2.33%   |
| Unknown MMC Card  32GB           | 3         | 1.74%   |
| Toshiba MQ01ACF050 500GB         | 3         | 1.74%   |
| Toshiba MK3275GSX 320GB          | 3         | 1.74%   |
| Samsung SSD 860 EVO 500GB        | 3         | 1.74%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.74%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 1.74%   |
| Unknown                          | 3         | 1.74%   |
| Unknown MMC Card  64GB           | 2         | 1.16%   |
| Toshiba MK2556GSY 250GB          | 2         | 1.16%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.16%   |
| Seagate ST9250315AS 250GB        | 2         | 1.16%   |
| Seagate ST380815AS 80GB          | 2         | 1.16%   |
| Seagate ST3160815AS 160GB        | 2         | 1.16%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 1.16%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.16%   |
| Samsung SSD 850 EVO 250GB        | 2         | 1.16%   |
| Kingston SV300S37A120G 120GB SSD | 2         | 1.16%   |
| FORESEE 128GB SSD                | 2         | 1.16%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1         | 0.58%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 0.58%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1         | 0.58%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.58%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.58%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.58%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.58%   |
| WDC WD3200LPVX-75V0TT0 320GB     | 1         | 0.58%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 0.58%   |
| WDC WD2500BEVT-75A23T0 250GB     | 1         | 0.58%   |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 0.58%   |
| WDC WD2500AAKX-001CA0 250GB      | 1         | 0.58%   |
| WDC WD2500AAJS-75M0A0 250GB      | 1         | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.58%   |
| WDC WD1600BEVT-75ZCT1 160GB      | 1         | 0.58%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.58%   |
| WDC WD10JPVX-60JC3T1 1TB         | 1         | 0.58%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.58%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1         | 0.58%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1         | 0.58%   |
| Unknown MMC Card  16GB           | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 49     | 44.05%  |
| WDC                 | 16        | 21     | 19.05%  |
| Toshiba             | 15        | 19     | 17.86%  |
| Hitachi             | 13        | 16     | 15.48%  |
| Samsung Electronics | 2         | 4      | 2.38%   |
| Maxtor              | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 12     | 22.92%  |
| Samsung Electronics | 10        | 11     | 20.83%  |
| SanDisk             | 7         | 11     | 14.58%  |
| WDC                 | 2         | 2      | 4.17%   |
| Transcend           | 2         | 2      | 4.17%   |
| SK hynix            | 2         | 2      | 4.17%   |
| Intel               | 2         | 2      | 4.17%   |
| FORESEE             | 2         | 2      | 4.17%   |
| A-DATA Technology   | 2         | 2      | 4.17%   |
| SPCC                | 1         | 1      | 2.08%   |
| PNY                 | 1         | 1      | 2.08%   |
| Patriot             | 1         | 1      | 2.08%   |
| OCZ                 | 1         | 1      | 2.08%   |
| LITEONIT            | 1         | 2      | 2.08%   |
| Hewlett-Packard     | 1         | 1      | 2.08%   |
| Crucial             | 1         | 1      | 2.08%   |
| Unknown             | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 72        | 110    | 50%     |
| SSD     | 43        | 55     | 29.86%  |
| NVMe    | 17        | 19     | 11.81%  |
| MMC     | 9         | 11     | 6.25%   |
| Unknown | 3         | 3      | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 163    | 77.44%  |
| NVMe | 17        | 19     | 12.78%  |
| MMC  | 9         | 11     | 6.77%   |
| SAS  | 4         | 5      | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 121    | 69.75%  |
| 0.51-1.0   | 26        | 33     | 21.85%  |
| 1.01-2.0   | 6         | 6      | 5.04%   |
| 3.01-4.0   | 2         | 3      | 1.68%   |
| 4.01-10.0  | 2         | 2      | 1.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 33.07%  |
| 251-500        | 23        | 18.11%  |
| 501-1000       | 21        | 16.54%  |
| 1-20           | 11        | 8.66%   |
| 51-100         | 11        | 8.66%   |
| 21-50          | 7         | 5.51%   |
| More than 3000 | 4         | 3.15%   |
| 1001-2000      | 4         | 3.15%   |
| Unknown        | 3         | 2.36%   |
| 2001-3000      | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 54        | 39.71%  |
| 21-50          | 28        | 20.59%  |
| 51-100         | 17        | 12.5%   |
| 101-250        | 13        | 9.56%   |
| 251-500        | 9         | 6.62%   |
| 501-1000       | 7         | 5.15%   |
| Unknown        | 3         | 2.21%   |
| 2001-3000      | 2         | 1.47%   |
| 1001-2000      | 2         | 1.47%   |
| More than 3000 | 1         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 94.44%  |
| SSD  | 1         | 1      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HDS721025CLA382 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 77        | 127    | 58.33%  |
| Works    | 37        | 49     | 28.03%  |
| Malfunc  | 17        | 21     | 12.88%  |
| Failed   | 1         | 1      | 0.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 85        | 66.41%  |
| AMD                              | 24        | 18.75%  |
| Samsung Electronics              | 5         | 3.91%   |
| SanDisk                          | 3         | 2.34%   |
| Toshiba America Info Systems     | 2         | 1.56%   |
| VIA Technologies                 | 1         | 0.78%   |
| SK hynix                         | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Phison Electronics               | 1         | 0.78%   |
| Nvidia                           | 1         | 0.78%   |
| Micron/Crucial Technology        | 1         | 0.78%   |
| Micron Technology                | 1         | 0.78%   |
| Marvell Technology Group         | 1         | 0.78%   |
| Kingston Technology Company      | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 10.46%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 4.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 3.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 3.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.61%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 2.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.96%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 1.96%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.31%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.31%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.65%   |
| VIA VIA VT6420 SATA RAID Controller                                              | 1         | 0.65%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.65%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.65%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.65%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.65%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.65%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.65%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 60.87%  |
| IDE  | 24        | 17.39%  |
| NVMe | 17        | 12.32%  |
| RAID | 13        | 9.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 95        | 78.51%  |
| AMD    | 26        | 21.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 3.31%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 3.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 2.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.65%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.65%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.65%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.65%   |
| AMD FX-8320 Eight-Core Processor            | 2         | 1.65%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.65%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.83%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.83%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.83%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.83%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.83%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.83%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.83%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.83%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.83%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.83%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.83%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.83%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.83%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.83%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.83%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.83%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.83%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 0.83%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.83%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.83%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.83%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 28.93%  |
| Intel Core i7           | 14        | 11.57%  |
| Intel Celeron           | 13        | 10.74%  |
| Intel Core i3           | 8         | 6.61%   |
| AMD Ryzen 5             | 7         | 5.79%   |
| Intel Core 2 Duo        | 6         | 4.96%   |
| Intel Atom              | 4         | 3.31%   |
| AMD FX                  | 4         | 3.31%   |
| Intel Pentium           | 3         | 2.48%   |
| Intel Xeon              | 2         | 1.65%   |
| Intel Pentium Dual-Core | 2         | 1.65%   |
| Intel Core 2            | 2         | 1.65%   |
| AMD Ryzen 7             | 2         | 1.65%   |
| AMD A8                  | 2         | 1.65%   |
| AMD A10                 | 2         | 1.65%   |
| Intel Pentium Dual      | 1         | 0.83%   |
| Intel Pentium D         | 1         | 0.83%   |
| Intel Pentium 4         | 1         | 0.83%   |
| Intel Genuine           | 1         | 0.83%   |
| Intel Core i9           | 1         | 0.83%   |
| Intel Core 2 Quad       | 1         | 0.83%   |
| AMD Sempron             | 1         | 0.83%   |
| AMD Ryzen 3             | 1         | 0.83%   |
| AMD Quad-Core           | 1         | 0.83%   |
| AMD PRO A10             | 1         | 0.83%   |
| AMD Phenom II X4        | 1         | 0.83%   |
| AMD Mobile Sempron      | 1         | 0.83%   |
| AMD A6                  | 1         | 0.83%   |
| AMD A4                  | 1         | 0.83%   |
| AMD A12                 | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 55.37%  |
| 4      | 40        | 33.06%  |
| 6      | 5         | 4.13%   |
| 1      | 5         | 4.13%   |
| 8      | 2         | 1.65%   |
| 12     | 1         | 0.83%   |
| 3      | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 99.17%  |
| 2      | 1         | 0.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 68        | 56.2%   |
| 1      | 53        | 43.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 97.54%  |
| 64-bit         | 1         | 0.82%   |
| 32-bit         | 1         | 0.82%   |
| Unknown        | 1         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 17.21%  |
| 0x206a7    | 12        | 9.84%   |
| 0x306a9    | 10        | 8.2%    |
| 0x1067a    | 7         | 5.74%   |
| 0x306c3    | 6         | 4.92%   |
| 0x806e9    | 5         | 4.1%    |
| 0x40651    | 5         | 4.1%    |
| 0x806ea    | 4         | 3.28%   |
| 0x706a1    | 4         | 3.28%   |
| 0x506e3    | 4         | 3.28%   |
| 0x0800820d | 3         | 2.46%   |
| 0x07030105 | 3         | 2.46%   |
| 0x06000852 | 3         | 2.46%   |
| 0x6fb      | 2         | 1.64%   |
| 0x6f6      | 2         | 1.64%   |
| 0x30678    | 2         | 1.64%   |
| 0x20652    | 2         | 1.64%   |
| 0x08108109 | 2         | 1.64%   |
| 0x0600611a | 2         | 1.64%   |
| 0xf65      | 1         | 0.82%   |
| 0xf49      | 1         | 0.82%   |
| 0x906ea    | 1         | 0.82%   |
| 0x906e9    | 1         | 0.82%   |
| 0x806ec    | 1         | 0.82%   |
| 0x706e5    | 1         | 0.82%   |
| 0x6fd      | 1         | 0.82%   |
| 0x506c9    | 1         | 0.82%   |
| 0x406c3    | 1         | 0.82%   |
| 0x30679    | 1         | 0.82%   |
| 0x20655    | 1         | 0.82%   |
| 0x106ca    | 1         | 0.82%   |
| 0x106c2    | 1         | 0.82%   |
| 0x10676    | 1         | 0.82%   |
| 0x10661    | 1         | 0.82%   |
| 0x08608102 | 1         | 0.82%   |
| 0x08600103 | 1         | 0.82%   |
| 0x08108102 | 1         | 0.82%   |
| 0x08101013 | 1         | 0.82%   |
| 0x0700010f | 1         | 0.82%   |
| 0x06003106 | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 14.05%  |
| SandyBridge   | 12        | 9.92%   |
| IvyBridge     | 12        | 9.92%   |
| Haswell       | 12        | 9.92%   |
| Penryn        | 8         | 6.61%   |
| Silvermont    | 7         | 5.79%   |
| Zen+          | 6         | 4.96%   |
| Westmere      | 6         | 4.96%   |
| Core          | 6         | 4.96%   |
| Goldmont plus | 5         | 4.13%   |
| Skylake       | 4         | 3.31%   |
| Piledriver    | 4         | 3.31%   |
| Puma          | 3         | 2.48%   |
| NetBurst      | 2         | 1.65%   |
| K8 Hammer     | 2         | 1.65%   |
| Excavator     | 2         | 1.65%   |
| Bonnell       | 2         | 1.65%   |
| Zen 3         | 1         | 0.83%   |
| Zen 2         | 1         | 0.83%   |
| Zen           | 1         | 0.83%   |
| Steamroller   | 1         | 0.83%   |
| K10 Llano     | 1         | 0.83%   |
| K10           | 1         | 0.83%   |
| Jaguar        | 1         | 0.83%   |
| IceLake       | 1         | 0.83%   |
| Goldmont      | 1         | 0.83%   |
| Bulldozer     | 1         | 0.83%   |
| Unknown       | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 83        | 61.94%  |
| AMD                              | 30        | 22.39%  |
| Nvidia                           | 19        | 14.18%  |
| VIA Technologies                 | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 7.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 5.76%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.6%    |
| Intel HD Graphics 620                                                                    | 5         | 3.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 3.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.6%    |
| Intel HD Graphics 530                                                                    | 4         | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.16%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.44%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 1.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.44%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.44%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.44%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.72%   |
| Nvidia TU117M                                                                            | 1         | 0.72%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.72%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.72%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.72%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.72%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 59.5%   |
| 1 x AMD        | 22        | 18.18%  |
| 1 x Nvidia     | 12        | 9.92%   |
| Intel + Nvidia | 5         | 4.13%   |
| Intel + AMD    | 4         | 3.31%   |
| 2 x AMD        | 2         | 1.65%   |
| AMD + Nvidia   | 2         | 1.65%   |
| 1 x VIA        | 1         | 0.83%   |
| 1 x SiS        | 1         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 88.52%  |
| Proprietary | 11        | 9.02%   |
| Unknown     | 3         | 2.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 64.75%  |
| 1.01-2.0   | 13        | 10.66%  |
| 0.01-0.5   | 11        | 9.02%   |
| 0.51-1.0   | 10        | 8.2%    |
| 3.01-4.0   | 6         | 4.92%   |
| 7.01-8.0   | 2         | 1.64%   |
| 2.01-3.0   | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 15.57%  |
| BOE                     | 13        | 10.66%  |
| Samsung Electronics     | 12        | 9.84%   |
| LG Display              | 12        | 9.84%   |
| Dell                    | 11        | 9.02%   |
| Chimei Innolux          | 11        | 9.02%   |
| Hewlett-Packard         | 6         | 4.92%   |
| Chi Mei Optoelectronics | 5         | 4.1%    |
| Apple                   | 4         | 3.28%   |
| AOC                     | 4         | 3.28%   |
| Sony                    | 3         | 2.46%   |
| Acer                    | 3         | 2.46%   |
| ZTR                     | 1         | 0.82%   |
| Westinghouse            | 1         | 0.82%   |
| Vizio                   | 1         | 0.82%   |
| ViewSonic               | 1         | 0.82%   |
| Unknown (XXX)           | 1         | 0.82%   |
| Sharp                   | 1         | 0.82%   |
| Philips                 | 1         | 0.82%   |
| PANDA                   | 1         | 0.82%   |
| NEC Computers           | 1         | 0.82%   |
| LG Philips              | 1         | 0.82%   |
| LG Electronics          | 1         | 0.82%   |
| Lenovo                  | 1         | 0.82%   |
| KTC                     | 1         | 0.82%   |
| KDC                     | 1         | 0.82%   |
| InnoLux Display         | 1         | 0.82%   |
| Goldstar                | 1         | 0.82%   |
| CHR                     | 1         | 0.82%   |
| BenQ                    | 1         | 0.82%   |
| Ancor Communications    | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                         | 2         | 1.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.61%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 1.61%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                      | 2         | 1.61%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                  | 1         | 0.81%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.81%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.81%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1         | 0.81%   |
| Unknown (XXX) V56 XXX0030 1920x1080 708x398mm 32.0-inch               | 1         | 0.81%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 0.81%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 1         | 0.81%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 610x350mm 27.7-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch  | 1         | 0.81%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 0.81%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.81%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch          | 1         | 0.81%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.81%   |
| LG Electronics LCD Monitor W1943 1984x768                             | 1         | 0.81%   |
| LG Electronics LCD Monitor LG TV                                      | 1         | 0.81%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 0.81%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 42        | 35.59%  |
| 1920x1080 (FHD)    | 36        | 30.51%  |
| 1280x800 (WXGA)    | 7         | 5.93%   |
| 1280x1024 (SXGA)   | 7         | 5.93%   |
| 1600x900 (HD+)     | 5         | 4.24%   |
| 3840x2160 (4K)     | 3         | 2.54%   |
| 1680x1050 (WSXGA+) | 3         | 2.54%   |
| 1360x768           | 3         | 2.54%   |
| 2560x1440 (QHD)    | 2         | 1.69%   |
| 1440x900 (WXGA+)   | 2         | 1.69%   |
| 1024x768 (XGA)     | 2         | 1.69%   |
| 3840x1100          | 1         | 0.85%   |
| 1984x768           | 1         | 0.85%   |
| 1800x1200          | 1         | 0.85%   |
| 1280x768           | 1         | 0.85%   |
| 1024x600           | 1         | 0.85%   |
| Unknown            | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 32.79%  |
| 13      | 16        | 13.11%  |
| 14      | 11        | 9.02%   |
| 11      | 8         | 6.56%   |
| 17      | 7         | 5.74%   |
| 24      | 5         | 4.1%    |
| 27      | 4         | 3.28%   |
| 22      | 4         | 3.28%   |
| 21      | 4         | 3.28%   |
| 19      | 4         | 3.28%   |
| 18      | 3         | 2.46%   |
| Unknown | 3         | 2.46%   |
| 50      | 2         | 1.64%   |
| 32      | 2         | 1.64%   |
| 10      | 2         | 1.64%   |
| 84      | 1         | 0.82%   |
| 72      | 1         | 0.82%   |
| 41      | 1         | 0.82%   |
| 40      | 1         | 0.82%   |
| 34      | 1         | 0.82%   |
| 31      | 1         | 0.82%   |
| 20      | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 60        | 50.42%  |
| 201-300     | 19        | 15.97%  |
| 401-500     | 14        | 11.76%  |
| 501-600     | 9         | 7.56%   |
| 351-400     | 4         | 3.36%   |
| 701-800     | 3         | 2.52%   |
| Unknown     | 3         | 2.52%   |
| 1501-2000   | 2         | 1.68%   |
| 1001-1500   | 2         | 1.68%   |
| 801-900     | 1         | 0.84%   |
| 601-700     | 1         | 0.84%   |
| 901-1000    | 1         | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 83        | 75.45%  |
| 16/10   | 14        | 12.73%  |
| 5/4     | 7         | 6.36%   |
| Unknown | 3         | 2.73%   |
| 4/3     | 1         | 0.91%   |
| 3/2     | 1         | 0.91%   |
| 3.40    | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 32.79%  |
| 81-90          | 20        | 16.39%  |
| 51-60          | 9         | 7.38%   |
| 201-250        | 9         | 7.38%   |
| 141-150        | 9         | 7.38%   |
| 151-200        | 8         | 6.56%   |
| 71-80          | 6         | 4.92%   |
| More than 1000 | 4         | 3.28%   |
| 301-350        | 4         | 3.28%   |
| 351-500        | 3         | 2.46%   |
| 501-1000       | 3         | 2.46%   |
| Unknown        | 3         | 2.46%   |
| 41-50          | 2         | 1.64%   |
| 251-300        | 1         | 0.82%   |
| 121-130        | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 45        | 38.14%  |
| 51-100        | 33        | 27.97%  |
| 121-160       | 26        | 22.03%  |
| 1-50          | 6         | 5.08%   |
| 161-240       | 4         | 3.39%   |
| Unknown       | 3         | 2.54%   |
| More than 240 | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 99        | 80.49%  |
| 2     | 16        | 13.01%  |
| 0     | 7         | 5.69%   |
| 3     | 1         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 60        | 32.61%  |
| Intel                           | 52        | 28.26%  |
| Qualcomm Atheros                | 29        | 15.76%  |
| Broadcom                        | 18        | 9.78%   |
| Ralink Technology               | 6         | 3.26%   |
| Qualcomm Atheros Communications | 3         | 1.63%   |
| Marvell Technology Group        | 2         | 1.09%   |
| Lenovo                          | 2         | 1.09%   |
| Broadcom Limited                | 2         | 1.09%   |
| VIA Technologies                | 1         | 0.54%   |
| Tul Corporation / PowerColor    | 1         | 0.54%   |
| TP-Link                         | 1         | 0.54%   |
| Nvidia                          | 1         | 0.54%   |
| MediaTek                        | 1         | 0.54%   |
| Linksys                         | 1         | 0.54%   |
| JCM                             | 1         | 0.54%   |
| HTC (High Tech Computer)        | 1         | 0.54%   |
| Dell                            | 1         | 0.54%   |
| AMD                             | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 15.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.27%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.82%   |
| Intel Wireless 7260                                               | 4         | 1.82%   |
| Intel Wireless 3165                                               | 4         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.36%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.36%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.91%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.91%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.91%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.91%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.91%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.91%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.91%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.45%   |
| Tul Corporation / PowerColor Network controller                   | 1         | 0.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 35.19%  |
| Qualcomm Atheros                | 24        | 22.22%  |
| Realtek Semiconductor           | 21        | 19.44%  |
| Broadcom                        | 11        | 10.19%  |
| Ralink Technology               | 6         | 5.56%   |
| Qualcomm Atheros Communications | 3         | 2.78%   |
| TP-Link                         | 1         | 0.93%   |
| MediaTek                        | 1         | 0.93%   |
| Linksys                         | 1         | 0.93%   |
| Dell                            | 1         | 0.93%   |
| Broadcom Limited                | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 5.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 5.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 4.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 4.59%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 3.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.67%   |
| Intel Wireless 7260                                                                   | 4         | 3.67%   |
| Intel Wireless 3165                                                                   | 4         | 3.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 2.75%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 2.75%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.83%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 1.83%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.83%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.83%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.83%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.83%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.92%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.92%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.92%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.92%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 51        | 47.22%  |
| Intel                    | 32        | 29.63%  |
| Broadcom                 | 10        | 9.26%   |
| Qualcomm Atheros         | 7         | 6.48%   |
| Marvell Technology Group | 2         | 1.85%   |
| Lenovo                   | 2         | 1.85%   |
| VIA Technologies         | 1         | 0.93%   |
| Nvidia                   | 1         | 0.93%   |
| HTC (High Tech Computer) | 1         | 0.93%   |
| Broadcom Limited         | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 32.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 12.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 9.26%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.7%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 3.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.85%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.93%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.93%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1         | 0.93%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.93%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.93%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 50%     |
| WiFi     | 101       | 48.56%  |
| Modem    | 2         | 0.96%   |
| Unknown  | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 63.2%   |
| Ethernet | 46        | 36.8%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 73        | 60.33%  |
| 1     | 43        | 35.54%  |
| 0     | 5         | 4.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 121       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 38.46%  |
| Qualcomm Atheros Communications | 12        | 18.46%  |
| IMC Networks                    | 6         | 9.23%   |
| Dell                            | 5         | 7.69%   |
| Cambridge Silicon Radio         | 4         | 6.15%   |
| Apple                           | 4         | 6.15%   |
| Realtek Semiconductor           | 3         | 4.62%   |
| Lite-On Technology              | 2         | 3.08%   |
| Broadcom                        | 2         | 3.08%   |
| Hewlett-Packard                 | 1         | 1.54%   |
| ASUSTek Computer                | 1         | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 20%     |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 10.77%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 6.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 4.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.62%   |
| IMC Networks Bluetooth Radio                        | 3         | 4.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 4.62%   |
| Apple Bluetooth Host Controller                     | 3         | 4.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.08%   |
| Intel AX200 Bluetooth                               | 2         | 3.08%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.54%   |
| Realtek Bluetooth Radio                             | 1         | 1.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.54%   |
| Lite-On Wireless_Device                             | 1         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.54%   |
| Intel AX201 Bluetooth                               | 1         | 1.54%   |
| IMC Networks Bluetooth Device                       | 1         | 1.54%   |
| IMC Networks Bluetooth                              | 1         | 1.54%   |
| IMC Networks BCM20702A0                             | 1         | 1.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.54%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.54%   |
| Dell Wireless 350 Bluetooth                         | 1         | 1.54%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.54%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.54%   |
| Apple Bluetooth HCI                                 | 1         | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 89        | 62.68%  |
| AMD                              | 29        | 20.42%  |
| Nvidia                           | 16        | 11.27%  |
| VIA Technologies                 | 1         | 0.7%    |
| Sony                             | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| Logitech                         | 1         | 0.7%    |
| Creative Labs                    | 1         | 0.7%    |
| C-Media Electronics              | 1         | 0.7%    |
| Blue Microphones                 | 1         | 0.7%    |
| BigBen Interactive               | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 7.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 6.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 6.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.07%   |
| AMD FCH Azalia Controller                                                  | 7         | 4.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 4.07%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 3.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 2.91%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2         | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.16%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.58%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.58%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.58%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.58%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 30%     |
| Samsung Electronics | 16        | 22.86%  |
| Micron Technology   | 5         | 7.14%   |
| Unknown             | 4         | 5.71%   |
| Kingston            | 4         | 5.71%   |
| Ramaxel Technology  | 3         | 4.29%   |
| Nanya Technology    | 3         | 4.29%   |
| Unknown (ABCD)      | 2         | 2.86%   |
| Corsair             | 2         | 2.86%   |
| V-Color             | 1         | 1.43%   |
| Sesame              | 1         | 1.43%   |
| Qimonda             | 1         | 1.43%   |
| Patriot             | 1         | 1.43%   |
| G.Skill             | 1         | 1.43%   |
| Elpida              | 1         | 1.43%   |
| Crucial             | 1         | 1.43%   |
| Avant               | 1         | 1.43%   |
| A-DATA Technology   | 1         | 1.43%   |
| Unknown             | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.67%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.67%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 2.67%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.67%   |
| V-Color RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s              | 1         | 1.33%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 1.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.33%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.33%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 1.33%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.33%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s               | 1         | 1.33%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.33%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.33%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s          | 1         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.33%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.33%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.33%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 20        | 35.71%  |
| DDR3    | 20        | 35.71%  |
| SDRAM   | 6         | 10.71%  |
| LPDDR4  | 4         | 7.14%   |
| DDR2    | 2         | 3.57%   |
| Unknown | 2         | 3.57%   |
| LPDDR3  | 1         | 1.79%   |
| DDR     | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 62.96%  |
| DIMM         | 18        | 33.33%  |
| Row Of Chips | 2         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 26        | 43.33%  |
| 8192  | 15        | 25%     |
| 2048  | 10        | 16.67%  |
| 16384 | 6         | 10%     |
| 1024  | 2         | 3.33%   |
| 512   | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 26.56%  |
| 2667    | 8         | 12.5%   |
| 2400    | 7         | 10.94%  |
| 1333    | 6         | 9.38%   |
| 2133    | 4         | 6.25%   |
| 4199    | 2         | 3.13%   |
| 3200    | 2         | 3.13%   |
| 2933    | 2         | 3.13%   |
| 1867    | 2         | 3.13%   |
| 1067    | 2         | 3.13%   |
| 667     | 2         | 3.13%   |
| 49926   | 1         | 1.56%   |
| 4267    | 1         | 1.56%   |
| 3600    | 1         | 1.56%   |
| 3266    | 1         | 1.56%   |
| 2934    | 1         | 1.56%   |
| 2666    | 1         | 1.56%   |
| 2048    | 1         | 1.56%   |
| 1334    | 1         | 1.56%   |
| 533     | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 15.38%  |
| Microdia                               | 9         | 11.54%  |
| Sunplus Innovation Technology          | 7         | 8.97%   |
| Realtek Semiconductor                  | 6         | 7.69%   |
| IMC Networks                           | 6         | 7.69%   |
| Suyin                                  | 5         | 6.41%   |
| Apple                                  | 5         | 6.41%   |
| Syntek                                 | 4         | 5.13%   |
| Silicon Motion                         | 3         | 3.85%   |
| Ricoh                                  | 3         | 3.85%   |
| Microsoft                              | 3         | 3.85%   |
| OmniVision Technologies                | 2         | 2.56%   |
| Logitech                               | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.56%   |
| Acer                                   | 2         | 2.56%   |
| Unknown                                | 1         | 1.28%   |
| Sonix Technology                       | 1         | 1.28%   |
| Samsung Electronics                    | 1         | 1.28%   |
| Primax Electronics                     | 1         | 1.28%   |
| Jieli Technology                       | 1         | 1.28%   |
| globaloptics                           | 1         | 1.28%   |
| Alcor Micro                            | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD               | 5         | 6.41%   |
| Chicony Integrated Camera                  | 3         | 3.85%   |
| Syntek Lenovo EasyCamera                   | 2         | 2.56%   |
| Microsoft MicrosoftÂ LifeCam HD-5001      | 2         | 2.56%   |
| Microdia Sonix USB 2.0 Camera              | 2         | 2.56%   |
| Microdia Integrated Webcam                 | 2         | 2.56%   |
| Microdia Dell Integrated HD Webcam         | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam          | 2         | 2.56%   |
| IMC Networks Integrated Camera             | 2         | 2.56%   |
| Chicony USB2.0 HD UVC WebCam               | 2         | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE                  | 2         | 2.56%   |
| Apple FaceTime HD Camera                   | 2         | 2.56%   |
| Unknown 720p HD Camera                     | 1         | 1.28%   |
| Syntek Integrated Camera                   | 1         | 1.28%   |
| Syntek EasyCamera                          | 1         | 1.28%   |
| Suyin VGA Webcam                           | 1         | 1.28%   |
| Suyin TOSHIBA Web Camera - HD              | 1         | 1.28%   |
| Suyin HP TrueVision HD                     | 1         | 1.28%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.28%   |
| Suyin 1.3M HD WebCam                       | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_HD        | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.28%   |
| Sonix HP Webcam-101                        | 1         | 1.28%   |
| Silicon Motion WebCam SCB-0385N            | 1         | 1.28%   |
| Silicon Motion WebCam SC-10HDD13335N       | 1         | 1.28%   |
| Silicon Motion Real HD WebCam              | 1         | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)    | 1         | 1.28%   |
| Ricoh Laptop_Integrated_Webcam_FHD         | 1         | 1.28%   |
| Ricoh Integrated Webcam                    | 1         | 1.28%   |
| Ricoh HD Webcam                            | 1         | 1.28%   |
| Realtek MTD camera                         | 1         | 1.28%   |
| Realtek Integrated Webcam HD               | 1         | 1.28%   |
| Realtek Integrated Webcam                  | 1         | 1.28%   |
| Realtek Integrated Camera                  | 1         | 1.28%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.28%   |
| Realtek HP Truevision HD integrated webcam | 1         | 1.28%   |
| Primax HP HD Webcam [Fixed]                | 1         | 1.28%   |
| OmniVision Monitor Webcam                  | 1         | 1.28%   |
| OmniVision Monitor Integrated Webcam       | 1         | 1.28%   |
| Microsoft LifeCam VX-2000                  | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 54.55%  |
| Synaptics                  | 3         | 27.27%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Samsung Electronics        | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| O2 Micro    | 2         | 22.22%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 74.59%  |
| 1     | 27        | 22.13%  |
| 2     | 4         | 3.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 31.43%  |
| Chipcard              | 8         | 22.86%  |
| Graphics card         | 7         | 20%     |
| Storage               | 2         | 5.71%   |
| Multimedia controller | 2         | 5.71%   |
| Network               | 1         | 2.86%   |
| Net/wireless          | 1         | 2.86%   |
| Card reader           | 1         | 2.86%   |
| Camera                | 1         | 2.86%   |
| Bluetooth             | 1         | 2.86%   |


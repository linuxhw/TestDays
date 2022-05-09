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

Total: 180

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Apple         | MacBookPro8,1               | Notebook    | [9ba8148878](https://linux-hardware.org/?probe=9ba8148878) | Dec 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e110e5c127](https://linux-hardware.org/?probe=e110e5c127) | Dec 25, 2021 |
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
| Lenovo        | G505s 20255                 | Notebook    | [4dd5733d57](https://linux-hardware.org/?probe=4dd5733d57) | Nov 20, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [9627be57cd](https://linux-hardware.org/?probe=9627be57cd) | Aug 31, 2021 |
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
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [f1dca4815b](https://linux-hardware.org/?probe=f1dca4815b) | Oct 14, 2020 |
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
| MSI           | H81M-E33                    | Desktop     | [a34d064808](https://linux-hardware.org/?probe=a34d064808) | Jul 12, 2020 |
| MSI           | H81M-E33                    | Desktop     | [4d071c9443](https://linux-hardware.org/?probe=4d071c9443) | Jul 12, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [4877877772](https://linux-hardware.org/?probe=4877877772) | Jul 04, 2020 |
| MSI           | H81M-E33                    | Desktop     | [6043670a37](https://linux-hardware.org/?probe=6043670a37) | Jun 29, 2020 |
| MSI           | H81M-E33                    | Desktop     | [6f84864e2a](https://linux-hardware.org/?probe=6f84864e2a) | Jun 29, 2020 |
| Dell          | Vostro A860                 | Notebook    | [16ded4e283](https://linux-hardware.org/?probe=16ded4e283) | Jun 28, 2020 |
| Dell          | Vostro A860                 | Notebook    | [d061339806](https://linux-hardware.org/?probe=d061339806) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| MSI           | H81M-E33                    | Desktop     | [2d531766ab](https://linux-hardware.org/?probe=2d531766ab) | Jun 26, 2020 |
| HP            | 250 G3                      | Notebook    | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Biostar       | G41D3C                      | Desktop     | [15959c0828](https://linux-hardware.org/?probe=15959c0828) | Jun 15, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [db44dbab00](https://linux-hardware.org/?probe=db44dbab00) | May 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [0a9a57202f](https://linux-hardware.org/?probe=0a9a57202f) | May 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | Notebook    | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | Notebook    | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | Notebook    | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | Notebook    | [4b065ffe24](https://linux-hardware.org/?probe=4b065ffe24) | May 13, 2020 |
| HP            | G60                         | Notebook    | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [0eda848aff](https://linux-hardware.org/?probe=0eda848aff) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [ef841f6edb](https://linux-hardware.org/?probe=ef841f6edb) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | Notebook    | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| HP            | 3031h                       | Desktop     | [0278ac4043](https://linux-hardware.org/?probe=0278ac4043) | Apr 07, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [87496c419f](https://linux-hardware.org/?probe=87496c419f) | Apr 07, 2020 |
| Dell          | 0WG864                      | Desktop     | [b7c74749f8](https://linux-hardware.org/?probe=b7c74749f8) | Mar 30, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [860893085c](https://linux-hardware.org/?probe=860893085c) | Mar 29, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [d9eab98e7f](https://linux-hardware.org/?probe=d9eab98e7f) | Mar 29, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [48e8186c4f](https://linux-hardware.org/?probe=48e8186c4f) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [515c26af9d](https://linux-hardware.org/?probe=515c26af9d) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [8301a7e24e](https://linux-hardware.org/?probe=8301a7e24e) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [d0e72a9426](https://linux-hardware.org/?probe=d0e72a9426) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [080f6bbb80](https://linux-hardware.org/?probe=080f6bbb80) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [740334eed7](https://linux-hardware.org/?probe=740334eed7) | Mar 28, 2020 |
| Dell          | Latitude 3330               | Notebook    | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [44fe9bdc7d](https://linux-hardware.org/?probe=44fe9bdc7d) | Mar 20, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [970faeadaf](https://linux-hardware.org/?probe=970faeadaf) | Mar 19, 2020 |
| HP            | 3031h                       | Desktop     | [3b10a92ee2](https://linux-hardware.org/?probe=3b10a92ee2) | Mar 19, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4f152e3015](https://linux-hardware.org/?probe=4f152e3015) | Mar 06, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [4775efe228](https://linux-hardware.org/?probe=4775efe228) | Feb 27, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [ee967f9ecb](https://linux-hardware.org/?probe=ee967f9ecb) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [ee38ece603](https://linux-hardware.org/?probe=ee38ece603) | Feb 06, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [3b934e6808](https://linux-hardware.org/?probe=3b934e6808) | Feb 05, 2020 |
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
| Apple         | MacBookPro5,5               | Notebook    | [ee99851054](https://linux-hardware.org/?probe=ee99851054) | Oct 21, 2019 |
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


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 20        | 19.05%  |
| Ubuntu 18.04        | 17        | 16.19%  |
| OpenMandriva 4.2    | 5         | 4.76%   |
| Arch Rolling        | 5         | 4.76%   |
| Fedora 34           | 3         | 2.86%   |
| Arch                | 3         | 2.86%   |
| Ubuntu 21.10        | 2         | 1.9%    |
| Pop!_OS 20.10       | 2         | 1.9%    |
| OpenMandriva 4.3    | 2         | 1.9%    |
| Linux Mint 20.3     | 2         | 1.9%    |
| Linux Mint 20.1     | 2         | 1.9%    |
| Linux Mint 19.3     | 2         | 1.9%    |
| Fedora 33           | 2         | 1.9%    |
| Debian 11           | 2         | 1.9%    |
| ArcoLinux Rolling   | 2         | 1.9%    |
| Xubuntu 19.10       | 1         | 0.95%   |
| Xubuntu 18.04       | 1         | 0.95%   |
| Void Linux Rolling  | 1         | 0.95%   |
| Ubuntu Budgie 22.04 | 1         | 0.95%   |
| Ubuntu Budgie 21.10 | 1         | 0.95%   |
| Ubuntu Budgie 20.04 | 1         | 0.95%   |
| Ubuntu 21.04        | 1         | 0.95%   |
| Ubuntu 19.10        | 1         | 0.95%   |
| Ubuntu 19.04        | 1         | 0.95%   |
| Solus 4.1           | 1         | 0.95%   |
| ROSA R10            | 1         | 0.95%   |
| Pop!_OS 21.04       | 1         | 0.95%   |
| Pop!_OS 20.04       | 1         | 0.95%   |
| openSUSE 20181022   | 1         | 0.95%   |
| Manjaro 21.2.3      | 1         | 0.95%   |
| Manjaro 21.1.2      | 1         | 0.95%   |
| Manjaro 20.1        | 1         | 0.95%   |
| Lubuntu 21.04       | 1         | 0.95%   |
| LMDE 4              | 1         | 0.95%   |
| Linux Mint 20.2     | 1         | 0.95%   |
| Linux Mint 20       | 1         | 0.95%   |
| Kubuntu 20.04       | 1         | 0.95%   |
| KDE neon 20.04      | 1         | 0.95%   |
| Kali 2022.1         | 1         | 0.95%   |
| Fedora 32           | 1         | 0.95%   |
| Fedora 31           | 1         | 0.95%   |
| Fedora 30           | 1         | 0.95%   |
| Elementary 6        | 1         | 0.95%   |
| Debian 10           | 1         | 0.95%   |
| Clear Linux 36250   | 1         | 0.95%   |
| Clear Linux 34500   | 1         | 0.95%   |
| Clear Linux 31940   | 1         | 0.95%   |
| CentOS 8            | 1         | 0.95%   |
| BlackPanther 18.1   | 1         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 40        | 38.83%  |
| Linux Mint    | 8         | 7.77%   |
| Fedora        | 8         | 7.77%   |
| Arch          | 8         | 7.77%   |
| OpenMandriva  | 7         | 6.8%    |
| Pop!_OS       | 4         | 3.88%   |
| Ubuntu Budgie | 3         | 2.91%   |
| Manjaro       | 3         | 2.91%   |
| Debian        | 3         | 2.91%   |
| Clear Linux   | 3         | 2.91%   |
| Xubuntu       | 2         | 1.94%   |
| ArcoLinux     | 2         | 1.94%   |
| Void Linux    | 1         | 0.97%   |
| Solus         | 1         | 0.97%   |
| ROSA          | 1         | 0.97%   |
| openSUSE      | 1         | 0.97%   |
| Lubuntu       | 1         | 0.97%   |
| LMDE          | 1         | 0.97%   |
| Kubuntu       | 1         | 0.97%   |
| KDE neon      | 1         | 0.97%   |
| Kali          | 1         | 0.97%   |
| Elementary    | 1         | 0.97%   |
| CentOS        | 1         | 0.97%   |
| BlackPanther  | 1         | 0.97%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 4         | 3.36%   |
| 5.4.0-42-generic         | 4         | 3.36%   |
| 5.10.14-desktop-1omv4002 | 4         | 3.36%   |
| 5.13.0-22-generic        | 3         | 2.52%   |
| 5.4.0-77-generic         | 2         | 1.68%   |
| 5.4.0-52-generic         | 2         | 1.68%   |
| 5.4.0-33-generic         | 2         | 1.68%   |
| 5.3.0-51-generic         | 2         | 1.68%   |
| 5.3.0-46-generic         | 2         | 1.68%   |
| 5.3.0-42-generic         | 2         | 1.68%   |
| 5.16.7-desktop-1omv4003  | 2         | 1.68%   |
| 5.11.0-40-generic        | 2         | 1.68%   |
| 5.11.0-25-generic        | 2         | 1.68%   |
| 5.0.0-32-generic         | 2         | 1.68%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.84%   |
| 5.9.12-xanmod1           | 1         | 0.84%   |
| 5.9.11-arch2-1           | 1         | 0.84%   |
| 5.9.1-arch1-1            | 1         | 0.84%   |
| 5.8.8-arch1-1            | 1         | 0.84%   |
| 5.8.5-arch1-1            | 1         | 0.84%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.84%   |
| 5.8.12_1                 | 1         | 0.84%   |
| 5.8.0-38-generic         | 1         | 0.84%   |
| 5.7.7-zen1-1-zen         | 1         | 0.84%   |
| 5.7.7-arch1-1            | 1         | 0.84%   |
| 5.7.10-201.fc32.x86_64   | 1         | 0.84%   |
| 5.6.19-158.current       | 1         | 0.84%   |
| 5.5.13-arch1-1           | 1         | 0.84%   |
| 5.4.60-2-MANJARO         | 1         | 0.84%   |
| 5.4.4-879.native         | 1         | 0.84%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.84%   |
| 5.4.0-7642-generic       | 1         | 0.84%   |
| 5.4.0-74-generic         | 1         | 0.84%   |
| 5.4.0-72-generic         | 1         | 0.84%   |
| 5.4.0-39-generic         | 1         | 0.84%   |
| 5.4.0-37-generic         | 1         | 0.84%   |
| 5.4.0-29-generic         | 1         | 0.84%   |
| 5.4.0-28-generic         | 1         | 0.84%   |
| 5.4.0-26-generic         | 1         | 0.84%   |
| 5.4.0-109-generic        | 1         | 0.84%   |
| 5.4.0-107-generic        | 1         | 0.84%   |
| 5.4.0-105-generic        | 1         | 0.84%   |
| 5.3.0-61-generic         | 1         | 0.84%   |
| 5.3.0-40-generic         | 1         | 0.84%   |
| 5.3.0-28-generic         | 1         | 0.84%   |
| 5.3.0-19-generic         | 1         | 0.84%   |
| 5.17.4-1139.native       | 1         | 0.84%   |
| 5.15.21-1-MANJARO        | 1         | 0.84%   |
| 5.15.0-kali3-amd64       | 1         | 0.84%   |
| 5.14.13-200.fc34.x86_64  | 1         | 0.84%   |
| 5.13.13-1-MANJARO        | 1         | 0.84%   |
| 5.13.0-7614-generic      | 1         | 0.84%   |
| 5.13.0-40-generic        | 1         | 0.84%   |
| 5.13.0-35-generic        | 1         | 0.84%   |
| 5.13.0-27-generic        | 1         | 0.84%   |
| 5.13.0-19-generic        | 1         | 0.84%   |
| 5.12.9-051209-generic    | 1         | 0.84%   |
| 5.12.15-arch1-1          | 1         | 0.84%   |
| 5.12.14-300.fc34.x86_64  | 1         | 0.84%   |
| 5.12.12-300.fc34.x86_64  | 1         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 24        | 22.02%  |
| 5.3.0   | 9         | 8.26%   |
| 5.13.0  | 8         | 7.34%   |
| 5.11.0  | 8         | 7.34%   |
| 4.15.0  | 6         | 5.5%    |
| 5.0.0   | 5         | 4.59%   |
| 5.10.14 | 4         | 3.67%   |
| 5.7.7   | 2         | 1.83%   |
| 5.16.7  | 2         | 1.83%   |
| 5.10.0  | 2         | 1.83%   |
| 4.19.0  | 2         | 1.83%   |
| 4.18.0  | 2         | 1.83%   |
| 5.9.16  | 1         | 0.92%   |
| 5.9.12  | 1         | 0.92%   |
| 5.9.11  | 1         | 0.92%   |
| 5.9.1   | 1         | 0.92%   |
| 5.8.8   | 1         | 0.92%   |
| 5.8.5   | 1         | 0.92%   |
| 5.8.15  | 1         | 0.92%   |
| 5.8.12  | 1         | 0.92%   |
| 5.8.0   | 1         | 0.92%   |
| 5.7.10  | 1         | 0.92%   |
| 5.6.19  | 1         | 0.92%   |
| 5.5.13  | 1         | 0.92%   |
| 5.4.60  | 1         | 0.92%   |
| 5.4.4   | 1         | 0.92%   |
| 5.4.15  | 1         | 0.92%   |
| 5.17.4  | 1         | 0.92%   |
| 5.15.21 | 1         | 0.92%   |
| 5.15.0  | 1         | 0.92%   |
| 5.14.13 | 1         | 0.92%   |
| 5.13.13 | 1         | 0.92%   |
| 5.12.9  | 1         | 0.92%   |
| 5.12.15 | 1         | 0.92%   |
| 5.12.14 | 1         | 0.92%   |
| 5.12.12 | 1         | 0.92%   |
| 5.11.15 | 1         | 0.92%   |
| 5.11.12 | 1         | 0.92%   |
| 5.10.19 | 1         | 0.92%   |
| 5.1.6   | 1         | 0.92%   |
| 5.1.2   | 1         | 0.92%   |
| 5.0.10  | 1         | 0.92%   |
| 4.9.87  | 1         | 0.92%   |
| 4.9.60  | 1         | 0.92%   |
| 4.19.8  | 1         | 0.92%   |
| 4.18.16 | 1         | 0.92%   |
| 4.18.15 | 1         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 27        | 25%     |
| 5.11    | 10        | 9.26%   |
| 5.3     | 9         | 8.33%   |
| 5.13    | 9         | 8.33%   |
| 5.10    | 7         | 6.48%   |
| 5.0     | 6         | 5.56%   |
| 4.15    | 6         | 5.56%   |
| 5.8     | 5         | 4.63%   |
| 5.9     | 4         | 3.7%    |
| 5.12    | 4         | 3.7%    |
| 4.18    | 4         | 3.7%    |
| 5.7     | 3         | 2.78%   |
| 4.19    | 3         | 2.78%   |
| 5.16    | 2         | 1.85%   |
| 5.15    | 2         | 1.85%   |
| 5.1     | 2         | 1.85%   |
| 5.6     | 1         | 0.93%   |
| 5.5     | 1         | 0.93%   |
| 5.17    | 1         | 0.93%   |
| 5.14    | 1         | 0.93%   |
| 4.9     | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 97.09%  |
| i686   | 3         | 2.91%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 51        | 49.51%  |
| KDE5       | 13        | 12.62%  |
| Unknown    | 11        | 10.68%  |
| XFCE       | 9         | 8.74%   |
| X-Cinnamon | 7         | 6.8%    |
| KDE        | 4         | 3.88%   |
| Budgie     | 4         | 3.88%   |
| MATE       | 1         | 0.97%   |
| LXQt       | 1         | 0.97%   |
| KDE4       | 1         | 0.97%   |
| dwm        | 1         | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 88        | 85.44%  |
| Wayland | 9         | 8.74%   |
| Unknown | 4         | 3.88%   |
| Tty     | 2         | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 60        | 58.25%  |
| SDDM    | 16        | 15.53%  |
| GDM     | 12        | 11.65%  |
| LightDM | 6         | 5.83%   |
| TDM     | 4         | 3.88%   |
| GDM3    | 4         | 3.88%   |
| KDM     | 1         | 0.97%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 48        | 45.71%  |
| es_DO   | 31        | 29.52%  |
| Unknown | 14        | 13.33%  |
| es_ES   | 5         | 4.76%   |
| es_MX   | 3         | 2.86%   |
| en_CA   | 2         | 1.9%    |
| fr_FR   | 1         | 0.95%   |
| es_US   | 1         | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 64        | 62.14%  |
| EFI  | 39        | 37.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 79.61%  |
| Overlay | 9         | 8.74%   |
| Btrfs   | 8         | 7.77%   |
| Xfs     | 2         | 1.94%   |
| Unknown | 2         | 1.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 65        | 62.5%   |
| GPT     | 28        | 26.92%  |
| MBR     | 11        | 10.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 83.65%  |
| Yes       | 17        | 16.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 64.42%  |
| Yes       | 37        | 35.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 31        | 30.1%   |
| Hewlett-Packard     | 16        | 15.53%  |
| Lenovo              | 14        | 13.59%  |
| ASUSTek Computer    | 8         | 7.77%   |
| Gigabyte Technology | 7         | 6.8%    |
| Apple               | 4         | 3.88%   |
| Samsung Electronics | 3         | 2.91%   |
| MSI                 | 3         | 2.91%   |
| Acer                | 3         | 2.91%   |
| ASRock              | 2         | 1.94%   |
| Unknown             | 2         | 1.94%   |
| Toshiba             | 1         | 0.97%   |
| TODOS INDUSTRIAL    | 1         | 0.97%   |
| SAELITE             | 1         | 0.97%   |
| Nuvision            | 1         | 0.97%   |
| Google              | 1         | 0.97%   |
| Fujitsu             | 1         | 0.97%   |
| Foxconn             | 1         | 0.97%   |
| EVOO                | 1         | 0.97%   |
| Chuwi               | 1         | 0.97%   |
| Biostar             | 1         | 0.97%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Gigabyte GA-78LMT-USB3 6.0                        | 2         | 1.94%   |
| Dell Latitude E6430                               | 2         | 1.94%   |
| Dell Latitude E6410                               | 2         | 1.94%   |
| Apple MacBookPro8,1                               | 2         | 1.94%   |
| Unknown                                           | 2         | 1.94%   |
| Toshiba Satellite C55-A                           | 1         | 0.97%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.97%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.97%   |
| Samsung 930QCG                                    | 1         | 0.97%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.97%   |
| SAELITE ES1AU11                                   | 1         | 0.97%   |
| Nuvision NES11                                    | 1         | 0.97%   |
| MSI MS-7A34                                       | 1         | 0.97%   |
| MSI MS-7817                                       | 1         | 0.97%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.97%   |
| Lenovo Z50-75 80EC                                | 1         | 0.97%   |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.97%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.97%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.97%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.97%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.97%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.97%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.97%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.97%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.97%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 0.97%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.97%   |
| Lenovo G505s 20255                                | 1         | 0.97%   |
| Lenovo G40-70 20369                               | 1         | 0.97%   |
| HP ProBook 6470b                                  | 1         | 0.97%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 0.97%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 0.97%   |
| HP Pavilion dv6                                   | 1         | 0.97%   |
| HP Notebook                                       | 1         | 0.97%   |
| HP Laptop 15-bw0xx                                | 1         | 0.97%   |
| HP G60                                            | 1         | 0.97%   |
| HP ENVY Laptop 13-ad0xx                           | 1         | 0.97%   |
| HP EliteDesk 705 G3 SFF                           | 1         | 0.97%   |
| HP EliteBook 8540w                                | 1         | 0.97%   |
| HP EliteBook 8460p                                | 1         | 0.97%   |
| HP Compaq Elite 8300 SFF                          | 1         | 0.97%   |
| HP Compaq Elite 8300 CMT                          | 1         | 0.97%   |
| HP Compaq dc7900 Small Form Factor                | 1         | 0.97%   |
| HP Compaq 8000 Elite CMT PC                       | 1         | 0.97%   |
| HP 250 G3                                         | 1         | 0.97%   |
| Google Winky                                      | 1         | 0.97%   |
| Gigabyte Z87X-UD5 TH                              | 1         | 0.97%   |
| Gigabyte GA-78LMT-USB3 R2                         | 1         | 0.97%   |
| Gigabyte GA-78LMT-S2P                             | 1         | 0.97%   |
| Gigabyte B450M DS3H                               | 1         | 0.97%   |
| Gigabyte B450 AORUS M                             | 1         | 0.97%   |
| Fujitsu LIFEBOOK AH562                            | 1         | 0.97%   |
| Foxconn p6-2040fr                                 | 1         | 0.97%   |
| EVOO EV-C-116-7                                   | 1         | 0.97%   |
| Dell Vostro A860                                  | 1         | 0.97%   |
| Dell Vostro 5471                                  | 1         | 0.97%   |
| Dell Precision WorkStation T5500                  | 1         | 0.97%   |
| Dell PowerEdge T40                                | 1         | 0.97%   |
| Dell OptiPlex 990                                 | 1         | 0.97%   |
| Dell OptiPlex 9020                                | 1         | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 12        | 11.65%  |
| Dell OptiPlex              | 7         | 6.8%    |
| Dell Inspiron              | 7         | 6.8%    |
| Lenovo ThinkPad            | 6         | 5.83%   |
| HP Compaq                  | 4         | 3.88%   |
| HP Pavilion                | 3         | 2.91%   |
| Gigabyte GA-78LMT-USB3     | 3         | 2.91%   |
| Acer Aspire                | 3         | 2.91%   |
| Lenovo IdeaPad             | 2         | 1.94%   |
| HP EliteBook               | 2         | 1.94%   |
| Dell Vostro                | 2         | 1.94%   |
| Apple MacBookPro8          | 2         | 1.94%   |
| Unknown                    | 2         | 1.94%   |
| Toshiba Satellite          | 1         | 0.97%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.97%   |
| Samsung RV420              | 1         | 0.97%   |
| Samsung 930QCG             | 1         | 0.97%   |
| Samsung 905S3G             | 1         | 0.97%   |
| SAELITE ES1AU11            | 1         | 0.97%   |
| Nuvision NES11             | 1         | 0.97%   |
| MSI MS-7A34                | 1         | 0.97%   |
| MSI MS-7817                | 1         | 0.97%   |
| MSI CR70                   | 1         | 0.97%   |
| Lenovo Z50-75              | 1         | 0.97%   |
| Lenovo Yoga                | 1         | 0.97%   |
| Lenovo ThinkBook           | 1         | 0.97%   |
| Lenovo Legion              | 1         | 0.97%   |
| Lenovo G505s               | 1         | 0.97%   |
| Lenovo G40-70              | 1         | 0.97%   |
| HP ProBook                 | 1         | 0.97%   |
| HP Notebook                | 1         | 0.97%   |
| HP Laptop                  | 1         | 0.97%   |
| HP G60                     | 1         | 0.97%   |
| HP ENVY                    | 1         | 0.97%   |
| HP EliteDesk               | 1         | 0.97%   |
| HP 250                     | 1         | 0.97%   |
| Google Winky               | 1         | 0.97%   |
| Gigabyte Z87X-UD5          | 1         | 0.97%   |
| Gigabyte GA-78LMT-S2P      | 1         | 0.97%   |
| Gigabyte B450M             | 1         | 0.97%   |
| Gigabyte B450              | 1         | 0.97%   |
| Fujitsu LIFEBOOK           | 1         | 0.97%   |
| Foxconn p6-2040fr          | 1         | 0.97%   |
| EVOO EV-C-116-7            | 1         | 0.97%   |
| Dell Precision             | 1         | 0.97%   |
| Dell PowerEdge             | 1         | 0.97%   |
| Dell DM061                 | 1         | 0.97%   |
| Chuwi Hi10                 | 1         | 0.97%   |
| Biostar G41D3C             | 1         | 0.97%   |
| ASUS ZenBook               | 1         | 0.97%   |
| ASUS X553MA                | 1         | 0.97%   |
| ASUS V230IC-DDR4           | 1         | 0.97%   |
| ASUS TUF                   | 1         | 0.97%   |
| ASUS T100TA                | 1         | 0.97%   |
| ASUS K53E                  | 1         | 0.97%   |
| ASUS H170                  | 1         | 0.97%   |
| ASUS H110M-E               | 1         | 0.97%   |
| ASRock G41M-VS3            | 1         | 0.97%   |
| ASRock B450M-HDV           | 1         | 0.97%   |
| Apple MacBookPro5          | 1         | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 13        | 12.62%  |
| 2017 | 12        | 11.65%  |
| 2014 | 11        | 10.68%  |
| 2012 | 10        | 9.71%   |
| 2013 | 8         | 7.77%   |
| 2019 | 6         | 5.83%   |
| 2018 | 6         | 5.83%   |
| 2008 | 6         | 5.83%   |
| 2015 | 5         | 4.85%   |
| 2010 | 5         | 4.85%   |
| 2009 | 5         | 4.85%   |
| 2020 | 4         | 3.88%   |
| 2007 | 4         | 3.88%   |
| 2016 | 3         | 2.91%   |
| 2021 | 2         | 1.94%   |
| 2006 | 2         | 1.94%   |
| 2005 | 1         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 67        | 65.05%  |
| Desktop     | 32        | 31.07%  |
| Convertible | 2         | 1.94%   |
| Tablet      | 1         | 0.97%   |
| All in one  | 1         | 0.97%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 101       | 98.06%  |
| Enabled  | 2         | 1.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 99.03%  |
| Yes  | 1         | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 32        | 31.07%  |
| 4.01-8.0    | 24        | 23.3%   |
| 8.01-16.0   | 15        | 14.56%  |
| 16.01-24.0  | 14        | 13.59%  |
| 1.01-2.0    | 5         | 4.85%   |
| 2.01-3.0    | 4         | 3.88%   |
| 32.01-64.0  | 3         | 2.91%   |
| 24.01-32.0  | 3         | 2.91%   |
| 0.51-1.0    | 2         | 1.94%   |
| 64.01-256.0 | 1         | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 47        | 42.73%  |
| 2.01-3.0 | 30        | 27.27%  |
| 3.01-4.0 | 17        | 15.45%  |
| 4.01-8.0 | 9         | 8.18%   |
| 0.51-1.0 | 7         | 6.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 68.27%  |
| 2      | 24        | 23.08%  |
| 3      | 6         | 5.77%   |
| 4      | 3         | 2.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 51.46%  |
| Yes       | 50        | 48.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 86.41%  |
| No        | 14        | 13.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 79.81%  |
| No        | 21        | 20.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 51.46%  |
| No        | 50        | 48.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 103       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Santo Domingo Este          | 56        | 50.45%  |
| Santiago de los Caballeros  | 12        | 10.81%  |
| Alejandro Bass              | 4         | 3.6%    |
| San Pedro de MacorГ­s     | 3         | 2.7%    |
| Nagua                       | 2         | 1.8%    |
| La Romana                   | 2         | 1.8%    |
| Guaymate                    | 2         | 1.8%    |
| Constanza                   | 2         | 1.8%    |
| Bayahibe                    | 2         | 1.8%    |
| BanГ­                     | 2         | 1.8%    |
| Villa Bisono                | 1         | 0.9%    |
| Sosua, Cabarete             | 1         | 0.9%    |
| Santa Cruz de Barahona      | 1         | 0.9%    |
| San Pedro de Macorís       | 1         | 0.9%    |
| San Pedro de MacorÃ­s     | 1         | 0.9%    |
| San Jose de Ocoa            | 1         | 0.9%    |
| San Francisco de MacorÃ­s | 1         | 0.9%    |
| San Cristobal               | 1         | 0.9%    |
| Salcedo                     | 1         | 0.9%    |
| Nacional                    | 1         | 0.9%    |
| Mao                         | 1         | 0.9%    |
| Manuel Diaz                 | 1         | 0.9%    |
| Los Hidalgos                | 1         | 0.9%    |
| Las Terrenas                | 1         | 0.9%    |
| Jarabacoa                   | 1         | 0.9%    |
| Galvan                      | 1         | 0.9%    |
| Ensanche Ozama              | 1         | 0.9%    |
| El Mamey                    | 1         | 0.9%    |
| ConcepciГіn de la Vega    | 1         | 0.9%    |
| Boca Chica                  | 1         | 0.9%    |
| Bavaro                      | 1         | 0.9%    |
| Arroyo Hondo                | 1         | 0.9%    |
| Anton Sanchez               | 1         | 0.9%    |
| Anama                       | 1         | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 30        | 41     | 22.22%  |
| Toshiba                   | 17        | 22     | 12.59%  |
| WDC                       | 16        | 20     | 11.85%  |
| Samsung Electronics       | 16        | 20     | 11.85%  |
| Hitachi                   | 12        | 14     | 8.89%   |
| SanDisk                   | 9         | 13     | 6.67%   |
| Kingston                  | 9         | 10     | 6.67%   |
| Unknown                   | 5         | 7      | 3.7%    |
| Intel                     | 4         | 4      | 2.96%   |
| Transcend                 | 2         | 2      | 1.48%   |
| SK Hynix                  | 2         | 2      | 1.48%   |
| PNY                       | 1         | 1      | 0.74%   |
| Phison Electronics        | 1         | 1      | 0.74%   |
| Patriot                   | 1         | 1      | 0.74%   |
| OCZ                       | 1         | 1      | 0.74%   |
| Micron/Crucial Technology | 1         | 1      | 0.74%   |
| Micron Technology         | 1         | 1      | 0.74%   |
| MAXTOR                    | 1         | 1      | 0.74%   |
| LITEONIT                  | 1         | 2      | 0.74%   |
| Indilinx                  | 1         | 1      | 0.74%   |
| Hewlett-Packard           | 1         | 1      | 0.74%   |
| FORESEE                   | 1         | 1      | 0.74%   |
| A-DATA Technology         | 1         | 1      | 0.74%   |
| Unknown                   | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown MMC Card  32GB           | 3         | 2.05%   |
| Toshiba MQ01ACF050 500GB         | 3         | 2.05%   |
| Toshiba MK3275GSX 320GB          | 3         | 2.05%   |
| Samsung SSD 860 EVO 500GB        | 3         | 2.05%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 2.05%   |
| Toshiba MK2556GSY 250GB          | 2         | 1.37%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.37%   |
| Seagate ST9250315AS 250GB        | 2         | 1.37%   |
| Seagate ST500LM000-1EJ162 500GB  | 2         | 1.37%   |
| Seagate ST380815AS 80GB          | 2         | 1.37%   |
| Seagate ST3160815AS 160GB        | 2         | 1.37%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 1.37%   |
| Sandisk NVMe SSD Drive 256GB     | 2         | 1.37%   |
| Samsung SSD 850 EVO 250GB        | 2         | 1.37%   |
| Kingston SV300S37A120G 120GB SSD | 2         | 1.37%   |
| Hitachi HTS545050A7E380 500GB    | 2         | 1.37%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1         | 0.68%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 0.68%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1         | 0.68%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.68%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.68%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.68%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.68%   |
| WDC WD3200LPVX-75V0TT0 320GB     | 1         | 0.68%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 0.68%   |
| WDC WD2500BEVT-75A23T0 250GB     | 1         | 0.68%   |
| WDC WD2500AAKX-001CA0 250GB      | 1         | 0.68%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.68%   |
| WDC WD1600BEVT-75ZCT1 160GB      | 1         | 0.68%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.68%   |
| WDC WD10JPVX-60JC3T1 1TB         | 1         | 0.68%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.68%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1         | 0.68%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1         | 0.68%   |
| Unknown MMC Card  64GB           | 1         | 0.68%   |
| Unknown MMC Card  16GB           | 1         | 0.68%   |
| Unknown MMC Card  128GB          | 1         | 0.68%   |
| Unknown FK0032CAAZP 32GB         | 1         | 0.68%   |
| Transcend TS256GSSD340 256GB     | 1         | 0.68%   |
| Transcend TS128GSSD370S 128GB    | 1         | 0.68%   |
| Toshiba NVMe SSD Drive 256GB     | 1         | 0.68%   |
| Toshiba NVMe SSD Drive 1024GB    | 1         | 0.68%   |
| Toshiba MQ01ABF050 500GB         | 1         | 0.68%   |
| Toshiba MQ01ABD100 1TB           | 1         | 0.68%   |
| Toshiba MK6475GSX 640GB          | 1         | 0.68%   |
| Toshiba MK3276GSX 320GB          | 1         | 0.68%   |
| Toshiba MK1655GSX 160GB          | 1         | 0.68%   |
| Toshiba HDWE160 6TB              | 1         | 0.68%   |
| SK Hynix HCG8e  64GB             | 1         | 0.68%   |
| SK Hynix C2S3T/240G 240GB SSD    | 1         | 0.68%   |
| Seagate ST980412ASG 80GB         | 1         | 0.68%   |
| Seagate ST9750420AS 752GB        | 1         | 0.68%   |
| Seagate ST9500325AS 500GB        | 1         | 0.68%   |
| Seagate ST9320325AS 320GB        | 1         | 0.68%   |
| Seagate ST9250410AS 250GB        | 1         | 0.68%   |
| Seagate ST8000DM004-2CX188 8TB   | 1         | 0.68%   |
| Seagate ST640LM000 HM641JI 640GB | 1         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 0.68%   |
| Seagate ST500DM002-1BD142 500GB  | 1         | 0.68%   |
| Seagate ST3500418AS 500GB        | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 41     | 40.54%  |
| Toshiba             | 15        | 19     | 20.27%  |
| WDC                 | 14        | 18     | 18.92%  |
| Hitachi             | 12        | 14     | 16.22%  |
| Samsung Electronics | 2         | 4      | 2.7%    |
| MAXTOR              | 1         | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 25%     |
| Kingston            | 9         | 10     | 22.5%   |
| SanDisk             | 7         | 11     | 17.5%   |
| WDC                 | 2         | 2      | 5%      |
| Transcend           | 2         | 2      | 5%      |
| Intel               | 2         | 2      | 5%      |
| SK Hynix            | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| Patriot             | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| LITEONIT            | 1         | 2      | 2.5%    |
| Hewlett-Packard     | 1         | 1      | 2.5%    |
| FORESEE             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 63        | 97     | 52.07%  |
| SSD     | 36        | 47     | 29.75%  |
| NVMe    | 14        | 15     | 11.57%  |
| MMC     | 6         | 8      | 4.96%   |
| Unknown | 2         | 2      | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 141    | 78.76%  |
| NVMe | 14        | 15     | 12.39%  |
| MMC  | 6         | 8      | 5.31%   |
| SAS  | 4         | 5      | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 105    | 69.52%  |
| 0.51-1.0   | 23        | 29     | 21.9%   |
| 1.01-2.0   | 5         | 5      | 4.76%   |
| 3.01-4.0   | 2         | 3      | 1.9%    |
| 4.01-10.0  | 2         | 2      | 1.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 33.94%  |
| 251-500        | 20        | 18.35%  |
| 501-1000       | 17        | 15.6%   |
| 51-100         | 9         | 8.26%   |
| 1-20           | 8         | 7.34%   |
| 21-50          | 6         | 5.5%    |
| More than 3000 | 4         | 3.67%   |
| 1001-2000      | 4         | 3.67%   |
| Unknown        | 3         | 2.75%   |
| 2001-3000      | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 39.32%  |
| 21-50          | 24        | 20.51%  |
| 51-100         | 13        | 11.11%  |
| 101-250        | 12        | 10.26%  |
| 251-500        | 8         | 6.84%   |
| 501-1000       | 6         | 5.13%   |
| Unknown        | 3         | 2.56%   |
| 2001-3000      | 2         | 1.71%   |
| 1001-2000      | 2         | 1.71%   |
| More than 3000 | 1         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK3275GSX 320GB         | 2         | 2      | 11.76%  |
| WDC WD6400AAKS-22A7B2 640GB     | 1         | 1      | 5.88%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 1         | 1      | 5.88%   |
| Toshiba MK3276GSX 320GB         | 1         | 1      | 5.88%   |
| Toshiba MK2556GSY 250GB         | 1         | 1      | 5.88%   |
| Toshiba MK1655GSX 160GB         | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB       | 1         | 1      | 5.88%   |
| Seagate ST3250318AS 250GB       | 1         | 1      | 5.88%   |
| Seagate ST2000LM007-1R8174 2TB  | 1         | 1      | 5.88%   |
| Samsung Electronics HD154UI 1TB | 1         | 1      | 5.88%   |
| Hitachi HTS727550A9E364 500GB   | 1         | 1      | 5.88%   |
| Hitachi HTS725032A9A364 320GB   | 1         | 1      | 5.88%   |
| Hitachi HTS722020K9SA00 200GB   | 1         | 1      | 5.88%   |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 5.88%   |
| Hitachi HTS547564A9E384 640GB   | 1         | 1      | 5.88%   |
| Hitachi HDT721025SLA380 250GB   | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 6      | 35.29%  |
| Toshiba             | 5         | 5      | 29.41%  |
| Seagate             | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 6      | 35.29%  |
| Toshiba             | 5         | 5      | 29.41%  |
| Seagate             | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 17     | 100%    |

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
| Detected | 69        | 114    | 61.06%  |
| Works    | 28        | 37     | 24.78%  |
| Malfunc  | 15        | 17     | 13.27%  |
| Failed   | 1         | 1      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 72        | 66.67%  |
| AMD                              | 20        | 18.52%  |
| Samsung Electronics              | 5         | 4.63%   |
| Toshiba America Info Systems     | 2         | 1.85%   |
| Sandisk                          | 2         | 1.85%   |
| VIA Technologies                 | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |
| Phison Electronics               | 1         | 0.93%   |
| Nvidia                           | 1         | 0.93%   |
| Micron/Crucial Technology        | 1         | 0.93%   |
| Micron Technology                | 1         | 0.93%   |
| Marvell Technology Group         | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 9.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 5.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 4.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 4.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 3.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 3.05%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 2.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 2.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 2.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.53%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.53%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.53%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.53%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 0.76%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1         | 0.76%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.76%   |
| Toshiba America Info Systems NVMe Controller                                            | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1         | 0.76%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.76%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.76%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.76%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.76%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.76%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1         | 0.76%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 0.76%   |
| Intel SSD 660P Series                                                                   | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.76%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.76%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.76%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.76%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1         | 0.76%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.76%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.76%   |
| AMD IXP SB4x0 IDE Controller                                                            | 1         | 0.76%   |
| AMD FCH IDE Controller                                                                  | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 61.54%  |
| IDE  | 22        | 18.8%   |
| NVMe | 14        | 11.97%  |
| RAID | 9         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 78.64%  |
| AMD    | 22        | 21.36%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.94%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.94%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.94%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 1.94%   |
| AMD FX-8320 Eight-Core Processor            | 2         | 1.94%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.94%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.97%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.97%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.97%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.97%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.97%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.97%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.97%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.97%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.97%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.97%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.97%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.97%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.97%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.97%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.97%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.97%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.97%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.97%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.97%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 0.97%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.97%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.97%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 0.97%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 0.97%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.97%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 0.97%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 0.97%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 0.97%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 0.97%   |
| Intel Core i3-7130U CPU @ 2.70GHz           | 1         | 0.97%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1         | 0.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 0.97%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 0.97%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 0.97%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.97%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 1         | 0.97%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 0.97%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 28.16%  |
| Intel Core i7           | 13        | 12.62%  |
| Intel Celeron           | 10        | 9.71%   |
| Intel Core i3           | 7         | 6.8%    |
| Intel Core 2 Duo        | 5         | 4.85%   |
| AMD FX                  | 4         | 3.88%   |
| Intel Atom              | 3         | 2.91%   |
| AMD Ryzen 5             | 3         | 2.91%   |
| Intel Xeon              | 2         | 1.94%   |
| Intel Pentium Dual-Core | 2         | 1.94%   |
| Intel Pentium           | 2         | 1.94%   |
| Intel Core 2            | 2         | 1.94%   |
| AMD Ryzen 7             | 2         | 1.94%   |
| AMD A8                  | 2         | 1.94%   |
| AMD A10                 | 2         | 1.94%   |
| Intel Pentium Dual      | 1         | 0.97%   |
| Intel Pentium D         | 1         | 0.97%   |
| Intel Pentium 4         | 1         | 0.97%   |
| Intel Genuine           | 1         | 0.97%   |
| Intel Core i9           | 1         | 0.97%   |
| Intel Core 2 Quad       | 1         | 0.97%   |
| AMD Sempron             | 1         | 0.97%   |
| AMD Ryzen 3             | 1         | 0.97%   |
| AMD Quad-Core           | 1         | 0.97%   |
| AMD PRO A10             | 1         | 0.97%   |
| AMD Phenom II X4        | 1         | 0.97%   |
| AMD Mobile Sempron      | 1         | 0.97%   |
| AMD A6                  | 1         | 0.97%   |
| AMD A4                  | 1         | 0.97%   |
| AMD A12                 | 1         | 0.97%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 56.31%  |
| 4      | 35        | 33.98%  |
| 1      | 4         | 3.88%   |
| 8      | 2         | 1.94%   |
| 6      | 2         | 1.94%   |
| 12     | 1         | 0.97%   |
| 3      | 1         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 102       | 99.03%  |
| 2      | 1         | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 54.37%  |
| 1      | 47        | 45.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 101       | 97.12%  |
| 64-bit         | 1         | 0.96%   |
| 32-bit         | 1         | 0.96%   |
| Unknown        | 1         | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 17.48%  |
| 0x206a7    | 11        | 10.68%  |
| 0x306a9    | 9         | 8.74%   |
| 0x1067a    | 6         | 5.83%   |
| 0x806e9    | 5         | 4.85%   |
| 0x306c3    | 5         | 4.85%   |
| 0x806ea    | 3         | 2.91%   |
| 0x506e3    | 3         | 2.91%   |
| 0x40651    | 3         | 2.91%   |
| 0x07030105 | 3         | 2.91%   |
| 0x06000852 | 3         | 2.91%   |
| 0x706a1    | 2         | 1.94%   |
| 0x6fb      | 2         | 1.94%   |
| 0x6f6      | 2         | 1.94%   |
| 0x30678    | 2         | 1.94%   |
| 0x20652    | 2         | 1.94%   |
| 0x0800820d | 2         | 1.94%   |
| 0x0600611a | 2         | 1.94%   |
| 0xf65      | 1         | 0.97%   |
| 0xf49      | 1         | 0.97%   |
| 0x906ea    | 1         | 0.97%   |
| 0x806ec    | 1         | 0.97%   |
| 0x706e5    | 1         | 0.97%   |
| 0x6fd      | 1         | 0.97%   |
| 0x506c9    | 1         | 0.97%   |
| 0x406c3    | 1         | 0.97%   |
| 0x20655    | 1         | 0.97%   |
| 0x106c2    | 1         | 0.97%   |
| 0x10676    | 1         | 0.97%   |
| 0x10661    | 1         | 0.97%   |
| 0x08600103 | 1         | 0.97%   |
| 0x08108109 | 1         | 0.97%   |
| 0x08108102 | 1         | 0.97%   |
| 0x08101013 | 1         | 0.97%   |
| 0x0700010f | 1         | 0.97%   |
| 0x06003106 | 1         | 0.97%   |
| 0x06001119 | 1         | 0.97%   |
| 0x010000db | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 13.59%  |
| SandyBridge   | 11        | 10.68%  |
| IvyBridge     | 11        | 10.68%  |
| Haswell       | 9         | 8.74%   |
| Penryn        | 7         | 6.8%    |
| Westmere      | 6         | 5.83%   |
| Silvermont    | 6         | 5.83%   |
| Core          | 6         | 5.83%   |
| Zen+          | 4         | 3.88%   |
| Piledriver    | 4         | 3.88%   |
| Skylake       | 3         | 2.91%   |
| Puma          | 3         | 2.91%   |
| Goldmont plus | 3         | 2.91%   |
| NetBurst      | 2         | 1.94%   |
| K8 Hammer     | 2         | 1.94%   |
| Excavator     | 2         | 1.94%   |
| Zen 2         | 1         | 0.97%   |
| Zen           | 1         | 0.97%   |
| Steamroller   | 1         | 0.97%   |
| K10 Llano     | 1         | 0.97%   |
| K10           | 1         | 0.97%   |
| Jaguar        | 1         | 0.97%   |
| IceLake       | 1         | 0.97%   |
| Goldmont      | 1         | 0.97%   |
| Bulldozer     | 1         | 0.97%   |
| Bonnell       | 1         | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 71        | 62.28%  |
| AMD                              | 24        | 21.05%  |
| Nvidia                           | 17        | 14.91%  |
| VIA Technologies                 | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 7.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 6.72%   |
| Intel HD Graphics 620                                                                    | 5         | 4.2%    |
| Intel UHD Graphics 620                                                                   | 4         | 3.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.52%   |
| Intel HD Graphics 530                                                                    | 3         | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.68%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 1.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.68%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.68%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.68%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.84%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.84%   |
| Nvidia TU117M                                                                            | 1         | 0.84%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.84%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.84%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.84%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.84%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.84%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.84%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.84%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.84%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.84%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.84%   |
| Intel HD Graphics 500                                                                    | 1         | 0.84%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1         | 0.84%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 1         | 0.84%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 0.84%   |
| Intel 82G965 Integrated Graphics Controller                                              | 1         | 0.84%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.84%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.84%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.84%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.84%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 0.84%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 0.84%   |
| AMD Renoir                                                                               | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 60.19%  |
| 1 x AMD        | 17        | 16.5%   |
| 1 x Nvidia     | 11        | 10.68%  |
| Intel + Nvidia | 4         | 3.88%   |
| Intel + AMD    | 3         | 2.91%   |
| 2 x AMD        | 2         | 1.94%   |
| AMD + Nvidia   | 2         | 1.94%   |
| 1 x VIA        | 1         | 0.97%   |
| 1 x SiS        | 1         | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 86.54%  |
| Proprietary | 11        | 10.58%  |
| Unknown     | 3         | 2.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 65.38%  |
| 1.01-2.0   | 10        | 9.62%   |
| 0.01-0.5   | 10        | 9.62%   |
| 0.51-1.0   | 9         | 8.65%   |
| 3.01-4.0   | 4         | 3.85%   |
| 7.01-8.0   | 2         | 1.92%   |
| 2.01-3.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 15.53%  |
| Samsung Electronics     | 12        | 11.65%  |
| LG Display              | 11        | 10.68%  |
| BOE                     | 10        | 9.71%   |
| Dell                    | 9         | 8.74%   |
| Chimei Innolux          | 9         | 8.74%   |
| Hewlett-Packard         | 5         | 4.85%   |
| Chi Mei Optoelectronics | 4         | 3.88%   |
| Apple                   | 4         | 3.88%   |
| Sony                    | 3         | 2.91%   |
| Acer                    | 3         | 2.91%   |
| AOC                     | 2         | 1.94%   |
| ZTR                     | 1         | 0.97%   |
| Westinghouse            | 1         | 0.97%   |
| Vizio                   | 1         | 0.97%   |
| ViewSonic               | 1         | 0.97%   |
| Philips                 | 1         | 0.97%   |
| PANDA                   | 1         | 0.97%   |
| NEC Computers           | 1         | 0.97%   |
| LG Philips              | 1         | 0.97%   |
| LG Electronics          | 1         | 0.97%   |
| Lenovo                  | 1         | 0.97%   |
| KTC                     | 1         | 0.97%   |
| InnoLux Display         | 1         | 0.97%   |
| Goldstar                | 1         | 0.97%   |
| BenQ                    | 1         | 0.97%   |
| Ancor Communications    | 1         | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                           | 2         | 1.9%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 2         | 1.9%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.9%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 1.9%    |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                    | 1         | 0.95%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch            | 1         | 0.95%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                     | 1         | 0.95%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.95%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                           | 1         | 0.95%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch   | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch    | 1         | 0.95%   |
| Philips HDMI TV PHL4650 1280x768 576x324mm 26.0-inch                    | 1         | 0.95%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch                 | 1         | 0.95%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch            | 1         | 0.95%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch             | 1         | 0.95%   |
| LG Electronics LCD Monitor W1943 1984x768                               | 1         | 0.95%   |
| LG Electronics LCD Monitor LG TV                                        | 1         | 0.95%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                 | 1         | 0.95%   |
| KTC Q3202S KTC3200 2560x1440 708x398mm 32.0-inch                        | 1         | 0.95%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch        | 1         | 0.95%   |
| Hewlett-Packard w1858 HWP281A 1366x768 413x234mm 18.7-inch              | 1         | 0.95%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch            | 1         | 0.95%   |
| Hewlett-Packard L1730 HWP260E 1280x1024 338x270mm 17.0-inch             | 1         | 0.95%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch             | 1         | 0.95%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 0.95%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                     | 1         | 0.95%   |
| Goldstar TV GSM75E3 1024x768 920x518mm 41.6-inch                        | 1         | 0.95%   |
| Dell SP2208WFP DEL403A 1680x1050 473x296mm 22.0-inch                    | 1         | 0.95%   |
| Dell SE2717H/HX DELD0A0 1920x1080 598x336mm 27.0-inch                   | 1         | 0.95%   |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                       | 1         | 0.95%   |
| Dell P2210H DELD026 1920x1080 480x270mm 21.7-inch                       | 1         | 0.95%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                       | 1         | 0.95%   |
| Dell DEL 1708FPBLK DEL4045 1280x1024 338x270mm 17.0-inch                | 1         | 0.95%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                         | 1         | 0.95%   |
| Dell 1707FP DEL4013 1280x1024 340x270mm 17.1-inch                       | 1         | 0.95%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch        | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 344x194mm 15.5-inch        | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 35        | 35%     |
| 1920x1080 (FHD)    | 28        | 28%     |
| 1280x800 (WXGA)    | 7         | 7%      |
| 1280x1024 (SXGA)   | 6         | 6%      |
| 1600x900 (HD+)     | 5         | 5%      |
| 3840x2160 (4K)     | 3         | 3%      |
| 1680x1050 (WSXGA+) | 3         | 3%      |
| 1360x768           | 3         | 3%      |
| 2560x1440 (QHD)    | 2         | 2%      |
| 1440x900 (WXGA+)   | 2         | 2%      |
| 1024x768 (XGA)     | 2         | 2%      |
| 3840x1100          | 1         | 1%      |
| 1984x768           | 1         | 1%      |
| 1280x768           | 1         | 1%      |
| Unknown            | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 33.98%  |
| 13      | 15        | 14.56%  |
| 14      | 10        | 9.71%   |
| 17      | 6         | 5.83%   |
| 11      | 6         | 5.83%   |
| 27      | 4         | 3.88%   |
| 22      | 4         | 3.88%   |
| 24      | 3         | 2.91%   |
| 19      | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| 50      | 2         | 1.94%   |
| 21      | 2         | 1.94%   |
| 18      | 2         | 1.94%   |
| 84      | 1         | 0.97%   |
| 72      | 1         | 0.97%   |
| 41      | 1         | 0.97%   |
| 40      | 1         | 0.97%   |
| 34      | 1         | 0.97%   |
| 32      | 1         | 0.97%   |
| 31      | 1         | 0.97%   |
| 20      | 1         | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 52%     |
| 201-300     | 15        | 15%     |
| 401-500     | 11        | 11%     |
| 501-600     | 7         | 7%      |
| 351-400     | 3         | 3%      |
| Unknown     | 3         | 3%      |
| 701-800     | 2         | 2%      |
| 1501-2000   | 2         | 2%      |
| 1001-1500   | 2         | 2%      |
| 801-900     | 1         | 1%      |
| 601-700     | 1         | 1%      |
| 901-1000    | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 73.91%  |
| 16/10   | 13        | 14.13%  |
| 5/4     | 5         | 5.43%   |
| Unknown | 3         | 3.26%   |
| 4/3     | 2         | 2.17%   |
| 3.40    | 1         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 33.98%  |
| 81-90          | 18        | 17.48%  |
| 201-250        | 8         | 7.77%   |
| 51-60          | 7         | 6.8%    |
| 141-150        | 7         | 6.8%    |
| 71-80          | 6         | 5.83%   |
| 151-200        | 5         | 4.85%   |
| More than 1000 | 4         | 3.88%   |
| 301-350        | 4         | 3.88%   |
| 501-1000       | 3         | 2.91%   |
| Unknown        | 3         | 2.91%   |
| 351-500        | 2         | 1.94%   |
| 121-130        | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 39.39%  |
| 51-100        | 27        | 27.27%  |
| 121-160       | 20        | 20.2%   |
| 1-50          | 6         | 6.06%   |
| 161-240       | 3         | 3.03%   |
| Unknown       | 3         | 3.03%   |
| More than 240 | 1         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 78.85%  |
| 2     | 14        | 13.46%  |
| 0     | 7         | 6.73%   |
| 3     | 1         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 49        | 31.82%  |
| Intel                           | 46        | 29.87%  |
| Qualcomm Atheros                | 22        | 14.29%  |
| Broadcom                        | 17        | 11.04%  |
| Ralink Technology               | 4         | 2.6%    |
| Qualcomm Atheros Communications | 2         | 1.3%    |
| Marvell Technology Group        | 2         | 1.3%    |
| Broadcom Limited                | 2         | 1.3%    |
| VIA Technologies                | 1         | 0.65%   |
| Tul Corporation / PowerColor    | 1         | 0.65%   |
| TP-Link                         | 1         | 0.65%   |
| Nvidia                          | 1         | 0.65%   |
| Linksys                         | 1         | 0.65%   |
| Lenovo                          | 1         | 0.65%   |
| JCM                             | 1         | 0.65%   |
| HTC (High Tech Computer)        | 1         | 0.65%   |
| Dell                            | 1         | 0.65%   |
| AMD                             | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 29        | 15.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 11        | 6.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 9         | 4.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 2.73%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 4         | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 2.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 4         | 2.19%   |
| Intel 82577LM Gigabit Network Connection                                              | 4         | 2.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 1.64%   |
| Intel Wireless 7260                                                                   | 3         | 1.64%   |
| Intel Wireless 3165                                                                   | 3         | 1.64%   |
| Intel Ethernet Connection I217-LM                                                     | 3         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 2         | 1.09%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.09%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.09%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.09%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 2         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                      | 2         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 0.55%   |
| Tul Corporation / PowerColor Network controller                                       | 1         | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.55%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                       | 1         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.55%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.55%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 0.55%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]                         | 1         | 0.55%   |
| Lenovo Thinkpad USB LAN                                                               | 1         | 0.55%   |
| JCM UBA                                                                               | 1         | 0.55%   |
| Intel Wireless 7265                                                                   | 1         | 0.55%   |
| Intel Wireless 3160                                                                   | 1         | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 0.55%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 38.37%  |
| Qualcomm Atheros                | 18        | 20.93%  |
| Realtek Semiconductor           | 15        | 17.44%  |
| Broadcom                        | 10        | 11.63%  |
| Ralink Technology               | 4         | 4.65%   |
| Qualcomm Atheros Communications | 2         | 2.33%   |
| TP-Link                         | 1         | 1.16%   |
| Linksys                         | 1         | 1.16%   |
| Dell                            | 1         | 1.16%   |
| Broadcom Limited                | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 5.75%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 4.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 4         | 4.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 4.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 4.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 4         | 4.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 3.45%   |
| Intel Wireless 7260                                                                   | 3         | 3.45%   |
| Intel Wireless 3165                                                                   | 3         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.3%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 2.3%    |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.3%    |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.3%    |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.3%    |
| Intel Centrino Advanced-N 6235                                                        | 2         | 2.3%    |
| Intel Centrino Advanced-N 6200                                                        | 2         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 2.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.15%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.15%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.15%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.15%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 1.15%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.15%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]                         | 1         | 1.15%   |
| Intel Wireless 7265                                                                   | 1         | 1.15%   |
| Intel Wireless 3160                                                                   | 1         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.15%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 1.15%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.15%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 1.15%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 1.15%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 1.15%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.15%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 1         | 1.15%   |
| Broadcom BCM43217 802.11b/g/n                                                         | 1         | 1.15%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 1         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 46.24%  |
| Intel                    | 28        | 30.11%  |
| Broadcom                 | 9         | 9.68%   |
| Qualcomm Atheros         | 6         | 6.45%   |
| Marvell Technology Group | 2         | 2.15%   |
| VIA Technologies         | 1         | 1.08%   |
| Nvidia                   | 1         | 1.08%   |
| Lenovo                   | 1         | 1.08%   |
| HTC (High Tech Computer) | 1         | 1.08%   |
| Broadcom Limited         | 1         | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 31.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 11.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 9.68%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 4.3%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.15%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 2.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.15%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 2.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.08%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.08%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.08%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 1.08%   |
| HTC (High Tech Computer) 779                                      | 1         | 1.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.08%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 1.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.08%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 50.86%  |
| WiFi     | 83        | 47.43%  |
| Modem    | 2         | 1.14%   |
| Unknown  | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 56.69%  |
| Ethernet | 55        | 43.31%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 62        | 60.19%  |
| 1     | 37        | 35.92%  |
| 0     | 4         | 3.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 39.62%  |
| Qualcomm Atheros Communications | 10        | 18.87%  |
| IMC Networks                    | 5         | 9.43%   |
| Dell                            | 5         | 9.43%   |
| Apple                           | 4         | 7.55%   |
| Realtek Semiconductor           | 2         | 3.77%   |
| Cambridge Silicon Radio         | 2         | 3.77%   |
| Broadcom                        | 2         | 3.77%   |
| Hewlett-Packard                 | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 20.75%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 9.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 5.66%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 5.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.66%   |
| IMC Networks Bluetooth Radio                        | 3         | 5.66%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 5.66%   |
| Apple Bluetooth Host Controller                     | 3         | 5.66%   |
| Intel AX200 Bluetooth                               | 2         | 3.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.77%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.89%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.89%   |
| Intel AX201 Bluetooth                               | 1         | 1.89%   |
| IMC Networks Bluetooth                              | 1         | 1.89%   |
| IMC Networks BCM20702A0                             | 1         | 1.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.89%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.89%   |
| Dell Wireless 350 Bluetooth                         | 1         | 1.89%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.89%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.89%   |
| Apple Bluetooth HCI                                 | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 75        | 63.03%  |
| AMD                              | 24        | 20.17%  |
| Nvidia                           | 15        | 12.61%  |
| VIA Technologies                 | 1         | 0.84%   |
| Sony                             | 1         | 0.84%   |
| Silicon Integrated Systems [SiS] | 1         | 0.84%   |
| Creative Labs                    | 1         | 0.84%   |
| Blue Microphones                 | 1         | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 7.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 7.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 6.34%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 4.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 4.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 4.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.11%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.41%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.41%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.7%    |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.7%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.7%    |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.7%    |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.7%    |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.7%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.7%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.7%    |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.7%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.7%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 16        | 29.09%  |
| Samsung Electronics | 13        | 23.64%  |
| Micron Technology   | 5         | 9.09%   |
| Unknown             | 4         | 7.27%   |
| Ramaxel Technology  | 3         | 5.45%   |
| Nanya Technology    | 2         | 3.64%   |
| Kingston            | 2         | 3.64%   |
| V-Color             | 1         | 1.82%   |
| Unknown (ABCD)      | 1         | 1.82%   |
| Sesame              | 1         | 1.82%   |
| Qimonda             | 1         | 1.82%   |
| Patriot             | 1         | 1.82%   |
| G.Skill             | 1         | 1.82%   |
| Elpida              | 1         | 1.82%   |
| Corsair             | 1         | 1.82%   |
| Avant               | 1         | 1.82%   |
| A-DATA Technology   | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s                | 2         | 3.45%   |
| V-Color RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s                 | 1         | 1.72%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                             | 1         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 1.72%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 1         | 1.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.72%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.72%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s                       | 1         | 1.72%   |
| SK Hynix RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 1.72%   |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s                  | 1         | 1.72%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                | 1         | 1.72%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 1.72%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 1         | 1.72%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.72%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1.72%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.72%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 1.72%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.72%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1.72%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.72%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 1.72%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.72%   |
| Samsung RAM M378B5673FH0-CF8 2GB DIMM DDR3 1067MT/s                 | 1         | 1.72%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 1         | 1.72%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s                 | 1         | 1.72%   |
| Samsung RAM K4U6E3S4AA-MGCL 2GB Row Of Chips LPDDR4 4267MT/s        | 1         | 1.72%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s             | 1         | 1.72%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s             | 1         | 1.72%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s               | 1         | 1.72%   |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s                 | 1         | 1.72%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                     | 1         | 1.72%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s             | 1         | 1.72%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR2 49926MT/s                 | 1         | 1.72%   |
| Nanya RAM NT1GT64U88D0BY-3C 1024MB DIMM DDR2 667MT/s                | 1         | 1.72%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s              | 1         | 1.72%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 1         | 1.72%   |
| Kingston RAM 9965745-028.A00G 16384MB DIMM DDR4 2666MT/s            | 1         | 1.72%   |
| G.Skill RAM F4-2666C15-4GVR 4096MB DIMM DDR4 2933MT/s               | 1         | 1.72%   |
| Elpida RAM SyncMAX 512MB DIMM DDR 533MT/s                           | 1         | 1.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 1         | 1.72%   |
| Avant RAM F6428U52E6800F 1024MB DIMM DDR 533MT/s                    | 1         | 1.72%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                   | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 16        | 36.36%  |
| DDR3    | 16        | 36.36%  |
| SDRAM   | 4         | 9.09%   |
| LPDDR4  | 2         | 4.55%   |
| DDR2    | 2         | 4.55%   |
| Unknown | 2         | 4.55%   |
| LPDDR3  | 1         | 2.27%   |
| DDR     | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 62.79%  |
| DIMM         | 14        | 32.56%  |
| Row Of Chips | 2         | 4.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 42.86%  |
| 8192  | 13        | 26.53%  |
| 2048  | 7         | 14.29%  |
| 16384 | 5         | 10.2%   |
| 1024  | 2         | 4.08%   |
| 512   | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 26.53%  |
| 2667    | 6         | 12.24%  |
| 2400    | 5         | 10.2%   |
| 2133    | 3         | 6.12%   |
| 1333    | 3         | 6.12%   |
| 4199    | 2         | 4.08%   |
| 3200    | 2         | 4.08%   |
| 1067    | 2         | 4.08%   |
| 667     | 2         | 4.08%   |
| 49926   | 1         | 2.04%   |
| 4267    | 1         | 2.04%   |
| 3600    | 1         | 2.04%   |
| 3266    | 1         | 2.04%   |
| 2934    | 1         | 2.04%   |
| 2933    | 1         | 2.04%   |
| 2666    | 1         | 2.04%   |
| 1867    | 1         | 2.04%   |
| 1334    | 1         | 2.04%   |
| 533     | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

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
| Chicony Electronics                    | 10        | 14.49%  |
| Sunplus Innovation Technology          | 6         | 8.7%    |
| Realtek Semiconductor                  | 6         | 8.7%    |
| Microdia                               | 6         | 8.7%    |
| Suyin                                  | 5         | 7.25%   |
| IMC Networks                           | 5         | 7.25%   |
| Apple                                  | 5         | 7.25%   |
| Syntek                                 | 4         | 5.8%    |
| Silicon Motion                         | 3         | 4.35%   |
| Microsoft                              | 3         | 4.35%   |
| Ricoh                                  | 2         | 2.9%    |
| OmniVision Technologies                | 2         | 2.9%    |
| Logitech                               | 2         | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.9%    |
| Acer                                   | 2         | 2.9%    |
| Unknown                                | 1         | 1.45%   |
| Sonix Technology                       | 1         | 1.45%   |
| Samsung Electronics                    | 1         | 1.45%   |
| Primax Electronics                     | 1         | 1.45%   |
| Jieli Technology                       | 1         | 1.45%   |
| Alcor Micro                            | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 4         | 5.8%    |
| Chicony Integrated Camera                                                  | 3         | 4.35%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 2.9%    |
| Microsoft MicrosoftÃ‚ LifeCam HD-5001                                   | 2         | 2.9%    |
| Microdia Dell Integrated HD Webcam                                         | 2         | 2.9%    |
| IMC Networks Integrated Camera                                             | 2         | 2.9%    |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 2.9%    |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 2.9%    |
| Apple FaceTime HD Camera                                                   | 2         | 2.9%    |
| Unknown 720p HD Camera                                                     | 1         | 1.45%   |
| Syntek Integrated Camera                                                   | 1         | 1.45%   |
| Syntek EasyCamera                                                          | 1         | 1.45%   |
| Suyin VGA Webcam                                                           | 1         | 1.45%   |
| Suyin TOSHIBA Web Camera - HD                                              | 1         | 1.45%   |
| Suyin HP TrueVision HD                                                     | 1         | 1.45%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 1.45%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 1.45%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.45%   |
| Sonix HP Webcam-101                                                        | 1         | 1.45%   |
| Silicon Motion WebCam SCB-0385N                                            | 1         | 1.45%   |
| Silicon Motion WebCam SC-10HDD13335N                                       | 1         | 1.45%   |
| Silicon Motion Real HD WebCam                                              | 1         | 1.45%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.45%   |
| Ricoh Integrated Webcam                                                    | 1         | 1.45%   |
| Ricoh HD Webcam                                                            | 1         | 1.45%   |
| Realtek USB2.0 camera                                                      | 1         | 1.45%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.45%   |
| Realtek Integrated Webcam                                                  | 1         | 1.45%   |
| Realtek Integrated Camera                                                  | 1         | 1.45%   |
| Realtek HP Wide Vision HD Camera                                           | 1         | 1.45%   |
| Realtek HP Truevision HD                                                   | 1         | 1.45%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 1.45%   |
| OmniVision Monitor Webcam                                                  | 1         | 1.45%   |
| OmniVision Monitor Integrated Webcam                                       | 1         | 1.45%   |
| Microsoft LifeCam VX-2000                                                  | 1         | 1.45%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 1.45%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.45%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.45%   |
| Microdia Integrated Webcam                                                 | 1         | 1.45%   |
| Logitech Webcam Pro 9000                                                   | 1         | 1.45%   |
| Logitech QuickCam Pro 4000                                                 | 1         | 1.45%   |
| Jieli USB PHY 2.0                                                          | 1         | 1.45%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.45%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 1         | 1.45%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.45%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.45%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.45%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.45%   |
| Chicony FJ Camera                                                          | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.45%   |
| Apple Built-in iSight                                                      | 1         | 1.45%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.45%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.45%   |
| Acer EasyCamera                                                            | 1         | 1.45%   |

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
| Broadcom    | 5         | 62.5%   |
| O2 Micro    | 2         | 25%     |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 75        | 72.12%  |
| 1     | 26        | 25%     |
| 2     | 3         | 2.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 34.38%  |
| Graphics card         | 7         | 21.88%  |
| Chipcard              | 7         | 21.88%  |
| Storage               | 1         | 3.13%   |
| Network               | 1         | 3.13%   |
| Net/wireless          | 1         | 3.13%   |
| Multimedia controller | 1         | 3.13%   |
| Card reader           | 1         | 3.13%   |
| Camera                | 1         | 3.13%   |
| Bluetooth             | 1         | 3.13%   |


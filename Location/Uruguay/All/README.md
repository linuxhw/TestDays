Linux in Uruguay - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Uruguay/Desktop/README.md) and [notebooks](/Location/Uruguay/Notebook/README.md).

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

Total: 303

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| MSI           | 2A9C                        | Desktop     | [74482fb396](https://linux-hardware.org/?probe=74482fb396) | Oct 16, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [1c1d20a1ac](https://linux-hardware.org/?probe=1c1d20a1ac) | Oct 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [98ff35e2a7](https://linux-hardware.org/?probe=98ff35e2a7) | Oct 09, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [adde8098e4](https://linux-hardware.org/?probe=adde8098e4) | Oct 04, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | Desktop     | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [b03e32f37d](https://linux-hardware.org/?probe=b03e32f37d) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| HP            | 8265                        | Desktop     | [2b74e032bd](https://linux-hardware.org/?probe=2b74e032bd) | Sep 06, 2022 |
| HP            | 8265                        | Desktop     | [f7f460fb43](https://linux-hardware.org/?probe=f7f460fb43) | Sep 05, 2022 |
| Dell          | Latitude 3150               | Notebook    | [6bc88c696c](https://linux-hardware.org/?probe=6bc88c696c) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| ASRock        | N68-S                       | Desktop     | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASRock        | N68-S                       | Desktop     | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| ECS           | SF20PA2                     | Notebook    | [67dd8af18f](https://linux-hardware.org/?probe=67dd8af18f) | Aug 23, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| HP            | 3048h                       | Desktop     | [34e0bbc168](https://linux-hardware.org/?probe=34e0bbc168) | Aug 20, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Biostar       | B550MH                      | Desktop     | [228a44e3f0](https://linux-hardware.org/?probe=228a44e3f0) | Aug 06, 2022 |
| ASRock        | B75M                        | Desktop     | [78fbdcd0f7](https://linux-hardware.org/?probe=78fbdcd0f7) | Aug 05, 2022 |
| Gateway       | NV55C                       | Notebook    | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| Dell          | Latitude 3150               | Notebook    | [aecf1fe543](https://linux-hardware.org/?probe=aecf1fe543) | Aug 01, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | Desktop     | [e83fe522d7](https://linux-hardware.org/?probe=e83fe522d7) | Jul 31, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4eb7e0d085](https://linux-hardware.org/?probe=4eb7e0d085) | Jul 22, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [04affeedf7](https://linux-hardware.org/?probe=04affeedf7) | Jul 18, 2022 |
| GPU Compan... | GWTN156-9                   | Notebook    | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| HP            | 1632                        | Desktop     | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| iClever       | IC-T01                      | Notebook    | [f82c34c612](https://linux-hardware.org/?probe=f82c34c612) | Jun 17, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [6abbac5ca2](https://linux-hardware.org/?probe=6abbac5ca2) | Jun 15, 2022 |
| HP            | Pavilion g4                 | Notebook    | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [34e884bb50](https://linux-hardware.org/?probe=34e884bb50) | Jun 08, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [482ed9f535](https://linux-hardware.org/?probe=482ed9f535) | May 29, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [fa6da4906f](https://linux-hardware.org/?probe=fa6da4906f) | May 07, 2022 |
| Toshiba       | Satellite C645D             | Notebook    | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [7ad45f257f](https://linux-hardware.org/?probe=7ad45f257f) | Apr 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d2e2811388](https://linux-hardware.org/?probe=d2e2811388) | Apr 20, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2c6e96d91f](https://linux-hardware.org/?probe=2c6e96d91f) | Apr 18, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [73be944f6c](https://linux-hardware.org/?probe=73be944f6c) | Apr 14, 2022 |
| Dell          | Precision 7550              | Notebook    | [4619da9502](https://linux-hardware.org/?probe=4619da9502) | Apr 14, 2022 |
| Lenovo        | G405 20239                  | Notebook    | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7d203f8bc0](https://linux-hardware.org/?probe=7d203f8bc0) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [9bf7ed495b](https://linux-hardware.org/?probe=9bf7ed495b) | Mar 28, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [d9afd858b4](https://linux-hardware.org/?probe=d9afd858b4) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | Desktop     | [911987151a](https://linux-hardware.org/?probe=911987151a) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | Desktop     | [7d9cc6ac07](https://linux-hardware.org/?probe=7d9cc6ac07) | Mar 22, 2022 |
| HP            | ZBook 14u G4                | Notebook    | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| HP            | Pavilion dv5                | Notebook    | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| GPU Compan... | GWTN156-4                   | Notebook    | [89e7b9fa39](https://linux-hardware.org/?probe=89e7b9fa39) | Mar 02, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [9699b8889c](https://linux-hardware.org/?probe=9699b8889c) | Feb 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [37231251ed](https://linux-hardware.org/?probe=37231251ed) | Feb 21, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [52ca8c0d7c](https://linux-hardware.org/?probe=52ca8c0d7c) | Feb 13, 2022 |
| ECS           | SF20PA2                     | Notebook    | [3bddc7e08a](https://linux-hardware.org/?probe=3bddc7e08a) | Feb 11, 2022 |
| HP            | 3047h                       | Desktop     | [ee6260c5f4](https://linux-hardware.org/?probe=ee6260c5f4) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP            | 0AA8h                       | Desktop     | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Biostar       | Z490A-SILVER                | Desktop     | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [90f509fc24](https://linux-hardware.org/?probe=90f509fc24) | Dec 09, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [44b341f68d](https://linux-hardware.org/?probe=44b341f68d) | Nov 10, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [4e606c817f](https://linux-hardware.org/?probe=4e606c817f) | Nov 04, 2021 |
| ASRock        | N68-S                       | Desktop     | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [174875a3d4](https://linux-hardware.org/?probe=174875a3d4) | Oct 25, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [357ea9ab5d](https://linux-hardware.org/?probe=357ea9ab5d) | Oct 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [c04d448530](https://linux-hardware.org/?probe=c04d448530) | Oct 21, 2021 |
| ASUSTek       | Q324UAK                     | Convertible | [a8334894c5](https://linux-hardware.org/?probe=a8334894c5) | Oct 19, 2021 |
| Lenovo        | B51-30 80LK                 | Notebook    | [dea10156c6](https://linux-hardware.org/?probe=dea10156c6) | Sep 20, 2021 |
| Haitech       | H7141A                      | Notebook    | [496c0eb316](https://linux-hardware.org/?probe=496c0eb316) | Sep 18, 2021 |
| ECS           | SF20PA2                     | Notebook    | [6d17cf08ad](https://linux-hardware.org/?probe=6d17cf08ad) | Sep 12, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [fea193c839](https://linux-hardware.org/?probe=fea193c839) | Sep 10, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [dbeb8785e6](https://linux-hardware.org/?probe=dbeb8785e6) | Sep 01, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [fef0710fbd](https://linux-hardware.org/?probe=fef0710fbd) | Aug 24, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| Lenovo        | ThinkPad L490 20Q6S0NF00    | Notebook    | [a8f222614b](https://linux-hardware.org/?probe=a8f222614b) | Aug 11, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | Notebook    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | Notebook    | [4781e962e7](https://linux-hardware.org/?probe=4781e962e7) | Aug 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| HP            | Pavilion 15                 | Notebook    | [ec0019224a](https://linux-hardware.org/?probe=ec0019224a) | Jul 28, 2021 |
| ECS           | SF20PA2                     | Notebook    | [2016dfe42c](https://linux-hardware.org/?probe=2016dfe42c) | Jul 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b6c401b55e](https://linux-hardware.org/?probe=b6c401b55e) | Jul 15, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [27582e9e17](https://linux-hardware.org/?probe=27582e9e17) | Jun 21, 2021 |
| Acer          | TravelMate 5730             | Notebook    | [4a21735ce1](https://linux-hardware.org/?probe=4a21735ce1) | Jun 17, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [38ee95b416](https://linux-hardware.org/?probe=38ee95b416) | Jun 02, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [9357025bc9](https://linux-hardware.org/?probe=9357025bc9) | Jun 01, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ab4b1b7a15](https://linux-hardware.org/?probe=ab4b1b7a15) | May 31, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| HP            | Pavilion 17                 | Notebook    | [f12450cc62](https://linux-hardware.org/?probe=f12450cc62) | May 28, 2021 |
| Lenovo        | ThinkPad T590 20N5S2GP05    | Notebook    | [2444839350](https://linux-hardware.org/?probe=2444839350) | May 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [212d434e24](https://linux-hardware.org/?probe=212d434e24) | May 25, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [cb57bbefd0](https://linux-hardware.org/?probe=cb57bbefd0) | May 22, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [297e5b458a](https://linux-hardware.org/?probe=297e5b458a) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [0ed78505e8](https://linux-hardware.org/?probe=0ed78505e8) | May 19, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [321e5159ac](https://linux-hardware.org/?probe=321e5159ac) | May 15, 2021 |
| ECS           | SF20PA2                     | Notebook    | [f3cc58b0e4](https://linux-hardware.org/?probe=f3cc58b0e4) | May 13, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [6f67fbb9d4](https://linux-hardware.org/?probe=6f67fbb9d4) | May 08, 2021 |
| ECS           | SF20PA2                     | Notebook    | [cfbd36f40b](https://linux-hardware.org/?probe=cfbd36f40b) | May 07, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d1c6c7309a](https://linux-hardware.org/?probe=d1c6c7309a) | May 03, 2021 |
| ASUSTek       | N46VJ                       | Notebook    | [0d6e007969](https://linux-hardware.org/?probe=0d6e007969) | Apr 28, 2021 |
| Standard      | SF20BA2                     | Notebook    | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [bcee870f79](https://linux-hardware.org/?probe=bcee870f79) | Apr 24, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7d28bb0ba2](https://linux-hardware.org/?probe=7d28bb0ba2) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [5042e6d421](https://linux-hardware.org/?probe=5042e6d421) | Apr 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Dell          | Inspiron 5565               | Notebook    | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | 240 G7                      | Notebook    | [721c4c3dbd](https://linux-hardware.org/?probe=721c4c3dbd) | Apr 14, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2296b37506](https://linux-hardware.org/?probe=2296b37506) | Apr 12, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [9a7aa83895](https://linux-hardware.org/?probe=9a7aa83895) | Apr 07, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [9b0d9c1623](https://linux-hardware.org/?probe=9b0d9c1623) | Apr 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [118abf533e](https://linux-hardware.org/?probe=118abf533e) | Mar 28, 2021 |
| Supermicro    | P4DMS                       | Desktop     | [34867ad122](https://linux-hardware.org/?probe=34867ad122) | Mar 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Supermicro    | P4DMS                       | Desktop     | [9de21bc6ec](https://linux-hardware.org/?probe=9de21bc6ec) | Mar 14, 2021 |
| MSI           | GL65 Leopard 10SCXR         | Notebook    | [8497db47ab](https://linux-hardware.org/?probe=8497db47ab) | Mar 09, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [c1d21b6940](https://linux-hardware.org/?probe=c1d21b6940) | Mar 01, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [901fd74eaa](https://linux-hardware.org/?probe=901fd74eaa) | Feb 20, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7f1fc20897](https://linux-hardware.org/?probe=7f1fc20897) | Feb 19, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [9527a6802e](https://linux-hardware.org/?probe=9527a6802e) | Feb 19, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f51dac04a1](https://linux-hardware.org/?probe=f51dac04a1) | Feb 17, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [bea8cc11d5](https://linux-hardware.org/?probe=bea8cc11d5) | Feb 17, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9473725930](https://linux-hardware.org/?probe=9473725930) | Feb 15, 2021 |
| Unknown       | Unknown                     | Phone       | [d561348222](https://linux-hardware.org/?probe=d561348222) | Feb 14, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [0b52890aaf](https://linux-hardware.org/?probe=0b52890aaf) | Jan 29, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [3a777180a1](https://linux-hardware.org/?probe=3a777180a1) | Jan 29, 2021 |
| Intel         | H61M-DS2                    | Desktop     | [930418d2da](https://linux-hardware.org/?probe=930418d2da) | Jan 23, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [4b7df9598e](https://linux-hardware.org/?probe=4b7df9598e) | Jan 20, 2021 |
| MSI           | GL65 Leopard 10SCXR         | Notebook    | [ac71737361](https://linux-hardware.org/?probe=ac71737361) | Jan 16, 2021 |
| Intel         | H61M-DS2                    | Desktop     | [53bde98202](https://linux-hardware.org/?probe=53bde98202) | Jan 09, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Toshiba       | Satellite L55t-B            | Notebook    | [ab3b576bd1](https://linux-hardware.org/?probe=ab3b576bd1) | Jan 07, 2021 |
| Toshiba       | Satellite L55t-B            | Notebook    | [6fc9533a15](https://linux-hardware.org/?probe=6fc9533a15) | Jan 06, 2021 |
| ECS           | SF20PA2                     | Notebook    | [f26e0bf23f](https://linux-hardware.org/?probe=f26e0bf23f) | Jan 04, 2021 |
| HP            | 2000                        | Notebook    | [99481f08e3](https://linux-hardware.org/?probe=99481f08e3) | Dec 31, 2020 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | Notebook                    | Notebook    | [213a94eab7](https://linux-hardware.org/?probe=213a94eab7) | Dec 28, 2020 |
| HP            | Notebook                    | Notebook    | [bb3749dd61](https://linux-hardware.org/?probe=bb3749dd61) | Dec 28, 2020 |
| MSI           | A55M-P33                    | Desktop     | [43267cc6f4](https://linux-hardware.org/?probe=43267cc6f4) | Dec 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f55e2642ef](https://linux-hardware.org/?probe=f55e2642ef) | Dec 15, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [729161e56a](https://linux-hardware.org/?probe=729161e56a) | Dec 08, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [37f7b460d4](https://linux-hardware.org/?probe=37f7b460d4) | Dec 08, 2020 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f158fc821a](https://linux-hardware.org/?probe=f158fc821a) | Nov 10, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [19081a3c58](https://linux-hardware.org/?probe=19081a3c58) | Oct 27, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8ea63ec090](https://linux-hardware.org/?probe=8ea63ec090) | Oct 23, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [912852805f](https://linux-hardware.org/?probe=912852805f) | Oct 22, 2020 |
| HP            | Pavilion dm4                | Notebook    | [21a3ef42e0](https://linux-hardware.org/?probe=21a3ef42e0) | Oct 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [64e95b4174](https://linux-hardware.org/?probe=64e95b4174) | Oct 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0ffffb855b](https://linux-hardware.org/?probe=0ffffb855b) | Oct 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7ddfb80220](https://linux-hardware.org/?probe=7ddfb80220) | Oct 04, 2020 |
| Dell          | 0C27VV A00                  | Desktop     | [fd9547e219](https://linux-hardware.org/?probe=fd9547e219) | Oct 01, 2020 |
| Toshiba       | Satellite C75D-C            | Notebook    | [12c65e3222](https://linux-hardware.org/?probe=12c65e3222) | Sep 25, 2020 |
| Unknown       | Unknown                     | Phone       | [6ff556bf54](https://linux-hardware.org/?probe=6ff556bf54) | Sep 06, 2020 |
| MSI           | GE62 6QD                    | Notebook    | [cf444064fc](https://linux-hardware.org/?probe=cf444064fc) | Sep 03, 2020 |
| Acer          | One S1003                   | Tablet      | [c89be38d5c](https://linux-hardware.org/?probe=c89be38d5c) | Aug 29, 2020 |
| HP            | Casablanca H710             | Notebook    | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | Notebook    | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [f425b1dc48](https://linux-hardware.org/?probe=f425b1dc48) | Aug 17, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [759ee832fb](https://linux-hardware.org/?probe=759ee832fb) | Aug 17, 2020 |
| Gigabyte      | H310M A-CF                  | Desktop     | [ff30e910c4](https://linux-hardware.org/?probe=ff30e910c4) | Aug 12, 2020 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [0009968f3b](https://linux-hardware.org/?probe=0009968f3b) | Aug 05, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3c55f58986](https://linux-hardware.org/?probe=3c55f58986) | Jul 03, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d4c35c226e](https://linux-hardware.org/?probe=d4c35c226e) | Jul 01, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [178da315d2](https://linux-hardware.org/?probe=178da315d2) | Jul 01, 2020 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [6a4b069ed8](https://linux-hardware.org/?probe=6a4b069ed8) | Jun 30, 2020 |
| HP            | Presario CQ43               | Notebook    | [bba4f49ed1](https://linux-hardware.org/?probe=bba4f49ed1) | Jun 23, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [70acf4ea22](https://linux-hardware.org/?probe=70acf4ea22) | Jun 18, 2020 |
| HP            | Presario CQ43               | Notebook    | [3af51e5df2](https://linux-hardware.org/?probe=3af51e5df2) | Jun 13, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9f2577531a](https://linux-hardware.org/?probe=9f2577531a) | Jun 10, 2020 |
| ECS           | SF20PA2                     | Notebook    | [fc1653c118](https://linux-hardware.org/?probe=fc1653c118) | Jun 10, 2020 |
| Dell          | Inspiron 5748               | Notebook    | [d7010adabe](https://linux-hardware.org/?probe=d7010adabe) | Jun 09, 2020 |
| OEM           | V40SI2                      | Notebook    | [e2ad8d9479](https://linux-hardware.org/?probe=e2ad8d9479) | Jun 06, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [13b3a46069](https://linux-hardware.org/?probe=13b3a46069) | May 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [7e4107b1b4](https://linux-hardware.org/?probe=7e4107b1b4) | May 26, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [0a5437ade3](https://linux-hardware.org/?probe=0a5437ade3) | May 22, 2020 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [7e4e3c078f](https://linux-hardware.org/?probe=7e4e3c078f) | May 20, 2020 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [627fed813d](https://linux-hardware.org/?probe=627fed813d) | May 18, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [493ce118d1](https://linux-hardware.org/?probe=493ce118d1) | May 16, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [154224ff78](https://linux-hardware.org/?probe=154224ff78) | May 16, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [173008c9ff](https://linux-hardware.org/?probe=173008c9ff) | May 16, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [98a86c1397](https://linux-hardware.org/?probe=98a86c1397) | May 15, 2020 |
| MSI           | GL63 8RD                    | Notebook    | [7e41ab8d71](https://linux-hardware.org/?probe=7e41ab8d71) | May 15, 2020 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [1beb748dc0](https://linux-hardware.org/?probe=1beb748dc0) | May 12, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3b397b64f7](https://linux-hardware.org/?probe=3b397b64f7) | May 06, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a9832cd92e](https://linux-hardware.org/?probe=a9832cd92e) | May 05, 2020 |
| HP            | 090Ch                       | Desktop     | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | Desktop     | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a8857822b2](https://linux-hardware.org/?probe=a8857822b2) | May 03, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [8609a3503d](https://linux-hardware.org/?probe=8609a3503d) | May 02, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7fdc3c7af9](https://linux-hardware.org/?probe=7fdc3c7af9) | May 02, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [1532d55ba0](https://linux-hardware.org/?probe=1532d55ba0) | May 01, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [c931341a8c](https://linux-hardware.org/?probe=c931341a8c) | May 01, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [e52c07ce77](https://linux-hardware.org/?probe=e52c07ce77) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS72901    | Notebook    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Gateway       | DX4375                      | Desktop     | [1470b063f3](https://linux-hardware.org/?probe=1470b063f3) | Apr 28, 2020 |
| Standard      | EF20EA                      | Notebook    | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| ECS           | H310H5-M2                   | Desktop     | [b1aaebf57b](https://linux-hardware.org/?probe=b1aaebf57b) | Apr 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [3be039900b](https://linux-hardware.org/?probe=3be039900b) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [cf6e400de0](https://linux-hardware.org/?probe=cf6e400de0) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [bb8bd669f6](https://linux-hardware.org/?probe=bb8bd669f6) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [f1caefcea5](https://linux-hardware.org/?probe=f1caefcea5) | Apr 17, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [3036b319ab](https://linux-hardware.org/?probe=3036b319ab) | Apr 16, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [ebd210c2af](https://linux-hardware.org/?probe=ebd210c2af) | Apr 16, 2020 |
| HP            | 620                         | Notebook    | [812b274fd4](https://linux-hardware.org/?probe=812b274fd4) | Apr 13, 2020 |
| HP            | 620                         | Notebook    | [ca26b96168](https://linux-hardware.org/?probe=ca26b96168) | Apr 13, 2020 |
| Acer          | One S1003                   | Tablet      | [f1cf80584b](https://linux-hardware.org/?probe=f1cf80584b) | Apr 07, 2020 |
| MSI           | G31M2                       | Desktop     | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| HP            | 1497                        | Desktop     | [973b170ac6](https://linux-hardware.org/?probe=973b170ac6) | Mar 23, 2020 |
| Lenovo        | 312D NOK                    | Mini pc     | [36cb7c6a75](https://linux-hardware.org/?probe=36cb7c6a75) | Mar 23, 2020 |
| HP            | 1497                        | Desktop     | [26d8104c5e](https://linux-hardware.org/?probe=26d8104c5e) | Mar 02, 2020 |
| ECS           | SF20PA2                     | Notebook    | [d685560200](https://linux-hardware.org/?probe=d685560200) | Feb 01, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [743f3ff81c](https://linux-hardware.org/?probe=743f3ff81c) | Dec 22, 2019 |
| MSI           | A68HM-E33 V2                | Desktop     | [1d3a9ef0d2](https://linux-hardware.org/?probe=1d3a9ef0d2) | Dec 22, 2019 |
| MSI           | A68HM-E33 V2                | Desktop     | [806c1e6d78](https://linux-hardware.org/?probe=806c1e6d78) | Dec 22, 2019 |
| ECS           | SF20PA2                     | Notebook    | [e6212ece14](https://linux-hardware.org/?probe=e6212ece14) | Nov 27, 2019 |
| ECS           | SF20PA2                     | Notebook    | [1d4a07f181](https://linux-hardware.org/?probe=1d4a07f181) | Nov 19, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [1fab0cb871](https://linux-hardware.org/?probe=1fab0cb871) | Nov 16, 2019 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [c28821415f](https://linux-hardware.org/?probe=c28821415f) | Nov 15, 2019 |
| ECS           | SF20PA2                     | Notebook    | [063490d972](https://linux-hardware.org/?probe=063490d972) | Nov 03, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [273463747b](https://linux-hardware.org/?probe=273463747b) | Oct 29, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [dfda14135d](https://linux-hardware.org/?probe=dfda14135d) | Oct 28, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [3418011c79](https://linux-hardware.org/?probe=3418011c79) | Oct 27, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [cb622d3902](https://linux-hardware.org/?probe=cb622d3902) | Oct 27, 2019 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [623c96ec6e](https://linux-hardware.org/?probe=623c96ec6e) | Oct 07, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [0925f5642c](https://linux-hardware.org/?probe=0925f5642c) | Sep 24, 2019 |
| ECS           | SF20PA2                     | Notebook    | [3c9b29c0c7](https://linux-hardware.org/?probe=3c9b29c0c7) | Sep 20, 2019 |
| ECS           | SF20PA2                     | Notebook    | [6d35e092fa](https://linux-hardware.org/?probe=6d35e092fa) | Sep 16, 2019 |
| Dell          | Inspiron 13-5368            | Notebook    | [0dab5b3510](https://linux-hardware.org/?probe=0dab5b3510) | Sep 15, 2019 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [00a1738003](https://linux-hardware.org/?probe=00a1738003) | Aug 14, 2019 |
| ECS           | SF20PA2                     | Notebook    | [80d3b6b8cf](https://linux-hardware.org/?probe=80d3b6b8cf) | Aug 04, 2019 |
| ECS           | SF20PA2                     | Notebook    | [a7b095e2f0](https://linux-hardware.org/?probe=a7b095e2f0) | Jul 30, 2019 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [001551b002](https://linux-hardware.org/?probe=001551b002) | Jul 22, 2019 |
| ECS           | SF20PA2                     | Notebook    | [01cad0b14a](https://linux-hardware.org/?probe=01cad0b14a) | Jul 10, 2019 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [0e1338db33](https://linux-hardware.org/?probe=0e1338db33) | Jul 01, 2019 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [30ff6dab9f](https://linux-hardware.org/?probe=30ff6dab9f) | Jun 13, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [08c0f291e9](https://linux-hardware.org/?probe=08c0f291e9) | Jun 13, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [5619d594fa](https://linux-hardware.org/?probe=5619d594fa) | Jun 10, 2019 |
| ASUSTek       | M5A87                       | Desktop     | [cead36d312](https://linux-hardware.org/?probe=cead36d312) | May 18, 2019 |
| ASUSTek       | M5A87                       | Desktop     | [6dfdec0635](https://linux-hardware.org/?probe=6dfdec0635) | May 18, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [b8f0a4691d](https://linux-hardware.org/?probe=b8f0a4691d) | May 17, 2019 |
| HP            | 1998                        | Desktop     | [0ae1b2ac01](https://linux-hardware.org/?probe=0ae1b2ac01) | May 13, 2019 |
| Samsung       | 700T                        | Notebook    | [dcf693f16f](https://linux-hardware.org/?probe=dcf693f16f) | May 11, 2019 |
| HP            | Pavilion dv6                | Notebook    | [36299cef92](https://linux-hardware.org/?probe=36299cef92) | Apr 17, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b26531074c](https://linux-hardware.org/?probe=b26531074c) | Apr 16, 2019 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [547801f07c](https://linux-hardware.org/?probe=547801f07c) | Apr 15, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [7d9905cfe7](https://linux-hardware.org/?probe=7d9905cfe7) | Mar 27, 2019 |
| ASUSTek       | TP300LAB                    | Notebook    | [538b5e5d24](https://linux-hardware.org/?probe=538b5e5d24) | Mar 26, 2019 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [859c76fdf7](https://linux-hardware.org/?probe=859c76fdf7) | Mar 17, 2019 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [4684e2d239](https://linux-hardware.org/?probe=4684e2d239) | Dec 04, 2018 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [a26c805e14](https://linux-hardware.org/?probe=a26c805e14) | Dec 04, 2018 |
| MSI           | G41M-P26                    | Desktop     | [59c7d54670](https://linux-hardware.org/?probe=59c7d54670) | Nov 10, 2018 |
| HP            | Pavilion 15                 | Notebook    | [7376903dca](https://linux-hardware.org/?probe=7376903dca) | May 13, 2018 |
| HP            | Pavilion 15                 | Notebook    | [2cc0124d5d](https://linux-hardware.org/?probe=2cc0124d5d) | May 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 35        | 15.77%  |
| Ubuntu 18.04      | 28        | 12.61%  |
| OpenMandriva 4.3  | 12        | 5.41%   |
| Manjaro           | 10        | 4.5%    |
| KDE neon 20.04    | 8         | 3.6%    |
| OpenMandriva 4.2  | 7         | 3.15%   |
| Linux Mint 19.3   | 6         | 2.7%    |
| Ubuntu 19.04      | 5         | 2.25%   |
| Xubuntu 20.04     | 4         | 1.8%    |
| Ubuntu 21.10      | 4         | 1.8%    |
| Ubuntu 18.10      | 4         | 1.8%    |
| Arch Rolling      | 4         | 1.8%    |
| Xubuntu 18.04     | 3         | 1.35%   |
| Ubuntu 22.04      | 3         | 1.35%   |
| ROSA R11.1        | 3         | 1.35%   |
| Pop!_OS 22.04     | 3         | 1.35%   |
| Linux Mint 20     | 3         | 1.35%   |
| Linux Mint 19.1   | 3         | 1.35%   |
| Fedora 36         | 3         | 1.35%   |
| Debian 11         | 3         | 1.35%   |
| BlackPanther 18.1 | 3         | 1.35%   |
| Arch              | 3         | 1.35%   |
| Zorin 16          | 2         | 0.9%    |
| Zorin 15          | 2         | 0.9%    |
| Ubuntu 21.04      | 2         | 0.9%    |
| Ubuntu 19.10      | 2         | 0.9%    |
| Pop!_OS 20.04     | 2         | 0.9%    |
| Linux Mint 20.3   | 2         | 0.9%    |
| Linux Mint 20.2   | 2         | 0.9%    |
| Linux Mint 20.1   | 2         | 0.9%    |
| Linux Mint 19.2   | 2         | 0.9%    |
| Kubuntu 18.04     | 2         | 0.9%    |
| Fedora 35         | 2         | 0.9%    |
| Fedora 34         | 2         | 0.9%    |
| ArcoLinux Rolling | 2         | 0.9%    |
| Android           | 2         | 0.9%    |
| Xubuntu 21.04     | 1         | 0.45%   |
| Ubuntu MATE 20.04 | 1         | 0.45%   |
| Ubuntu 20.10      | 1         | 0.45%   |
| Ubuntu 17.10      | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 82        | 37.61%  |
| Linux Mint   | 22        | 10.09%  |
| OpenMandriva | 21        | 9.63%   |
| Manjaro      | 11        | 5.05%   |
| Fedora       | 10        | 4.59%   |
| KDE neon     | 9         | 4.13%   |
| Xubuntu      | 8         | 3.67%   |
| Pop!_OS      | 6         | 2.75%   |
| Arch         | 6         | 2.75%   |
| Endless      | 5         | 2.29%   |
| Zorin        | 4         | 1.83%   |
| Lubuntu      | 4         | 1.83%   |
| Kubuntu      | 4         | 1.83%   |
| Debian       | 4         | 1.83%   |
| ROSA         | 3         | 1.38%   |
| BlackPanther | 3         | 1.38%   |
| openSUSE     | 2         | 0.92%   |
| Elementary   | 2         | 0.92%   |
| ArcoLinux    | 2         | 0.92%   |
| Android      | 2         | 0.92%   |
| Ubuntu MATE  | 1         | 0.46%   |
| NixOS        | 1         | 0.46%   |
| MX           | 1         | 0.46%   |
| LMDE         | 1         | 0.46%   |
| LinuxFX      | 1         | 0.46%   |
| Gentoo       | 1         | 0.46%   |
| Feren OS     | 1         | 0.46%   |
| EndeavourOS  | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003     | 11        | 4.7%    |
| 5.10.14-desktop-1omv4002    | 7         | 2.99%   |
| 5.4.0-42-generic            | 6         | 2.56%   |
| 4.16.18-pa2-2bp1            | 6         | 2.56%   |
| 5.11.0-38-generic           | 5         | 2.14%   |
| 4.16.18-pa2-1bp5            | 5         | 2.14%   |
| 5.8.0-53-generic            | 4         | 1.71%   |
| 5.4.0-52-generic            | 4         | 1.71%   |
| 5.3.0-46-generic            | 4         | 1.71%   |
| 5.13.0-39-generic           | 4         | 1.71%   |
| 5.5.19-bp0                  | 3         | 1.28%   |
| 5.4.0-73-generic            | 3         | 1.28%   |
| 5.4.0-72-generic            | 3         | 1.28%   |
| 5.4.0-65-generic            | 3         | 1.28%   |
| 5.4.0-58-generic            | 3         | 1.28%   |
| 5.15.0-46-generic           | 3         | 1.28%   |
| 5.0.0-32-generic            | 3         | 1.28%   |
| 4.18.16-desktop-1bP         | 3         | 1.28%   |
| 5.8.0-50-generic            | 2         | 0.85%   |
| 5.8.0-43-generic            | 2         | 0.85%   |
| 5.4.83-generic-2rosa-x86_64 | 2         | 0.85%   |
| 5.4.0-62-generic            | 2         | 0.85%   |
| 5.4.0-39-generic            | 2         | 0.85%   |
| 5.3.0-51-generic            | 2         | 0.85%   |
| 5.3.0-28-generic            | 2         | 0.85%   |
| 5.17.5-76051705-generic     | 2         | 0.85%   |
| 5.15.60-1-MANJARO           | 2         | 0.85%   |
| 5.15.0-48-generic           | 2         | 0.85%   |
| 5.15.0-41-generic           | 2         | 0.85%   |
| 5.13.0-44-generic           | 2         | 0.85%   |
| 5.13.0-40-generic           | 2         | 0.85%   |
| 5.13.0-37-generic           | 2         | 0.85%   |
| 5.13.0-30-generic           | 2         | 0.85%   |
| 5.13.0-22-generic           | 2         | 0.85%   |
| 5.11.12-desktop-1omv4002    | 2         | 0.85%   |
| 5.0.0-13-generic            | 2         | 0.85%   |
| 4.18.0-17-generic           | 2         | 0.85%   |
| 4.18.0-15-generic           | 2         | 0.85%   |
| 4.15.0-99-generic           | 2         | 0.85%   |
| 4.15.0-51-generic           | 2         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 16.59%  |
| 4.15.0  | 19        | 8.3%    |
| 5.13.0  | 14        | 6.11%   |
| 5.8.0   | 12        | 5.24%   |
| 5.11.0  | 12        | 5.24%   |
| 5.3.0   | 11        | 4.8%    |
| 5.16.7  | 11        | 4.8%    |
| 4.16.18 | 11        | 4.8%    |
| 5.0.0   | 10        | 4.37%   |
| 5.15.0  | 9         | 3.93%   |
| 4.18.0  | 8         | 3.49%   |
| 5.10.14 | 7         | 3.06%   |
| 5.10.0  | 4         | 1.75%   |
| 5.5.19  | 3         | 1.31%   |
| 5.17.5  | 3         | 1.31%   |
| 4.18.16 | 3         | 1.31%   |
| 5.4.83  | 2         | 0.87%   |
| 5.18.12 | 2         | 0.87%   |
| 5.15.60 | 2         | 0.87%   |
| 5.11.12 | 2         | 0.87%   |
| 6.0.0   | 1         | 0.44%   |
| 5.8.11  | 1         | 0.44%   |
| 5.8.1   | 1         | 0.44%   |
| 5.6.8   | 1         | 0.44%   |
| 5.6.0   | 1         | 0.44%   |
| 5.4.60  | 1         | 0.44%   |
| 5.4.32  | 1         | 0.44%   |
| 5.3.7   | 1         | 0.44%   |
| 5.2.13  | 1         | 0.44%   |
| 5.19.16 | 1         | 0.44%   |
| 5.19.12 | 1         | 0.44%   |
| 5.18.18 | 1         | 0.44%   |
| 5.18.13 | 1         | 0.44%   |
| 5.18.10 | 1         | 0.44%   |
| 5.17.4  | 1         | 0.44%   |
| 5.17.12 | 1         | 0.44%   |
| 5.16.16 | 1         | 0.44%   |
| 5.16.13 | 1         | 0.44%   |
| 5.16.12 | 1         | 0.44%   |
| 5.16.0  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 42        | 18.34%  |
| 4.15    | 19        | 8.3%    |
| 5.11    | 18        | 7.86%   |
| 5.16    | 15        | 6.55%   |
| 5.15    | 15        | 6.55%   |
| 5.13    | 15        | 6.55%   |
| 5.10    | 15        | 6.55%   |
| 5.8     | 14        | 6.11%   |
| 5.3     | 12        | 5.24%   |
| 4.16    | 12        | 5.24%   |
| 4.18    | 11        | 4.8%    |
| 5.0     | 10        | 4.37%   |
| 5.18    | 5         | 2.18%   |
| 5.17    | 5         | 2.18%   |
| 5.12    | 4         | 1.75%   |
| 5.5     | 3         | 1.31%   |
| 5.6     | 2         | 0.87%   |
| 5.19    | 2         | 0.87%   |
| 5.14    | 2         | 0.87%   |
| 6.0     | 1         | 0.44%   |
| 5.2     | 1         | 0.44%   |
| 4.9     | 1         | 0.44%   |
| 4.8     | 1         | 0.44%   |
| 4.4     | 1         | 0.44%   |
| 4.17    | 1         | 0.44%   |
| 4.13    | 1         | 0.44%   |
| 4.12    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 204       | 96.68%  |
| i686   | 5         | 2.37%   |
| armv8l | 2         | 0.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 71        | 32.57%  |
| KDE5            | 43        | 19.72%  |
| Unknown         | 35        | 16.06%  |
| XFCE            | 16        | 7.34%   |
| X-Cinnamon      | 15        | 6.88%   |
| GNOME Flashback | 12        | 5.5%    |
| KDE             | 7         | 3.21%   |
| MATE            | 5         | 2.29%   |
| LXQt            | 3         | 1.38%   |
| LXDE            | 3         | 1.38%   |
| Cinnamon        | 3         | 1.38%   |
| Pantheon        | 2         | 0.92%   |
| KDE4            | 2         | 0.92%   |
| sway            | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 173       | 80.84%  |
| Wayland | 22        | 10.28%  |
| Unknown | 17        | 7.94%   |
| Tty     | 2         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 116       | 54.21%  |
| SDDM    | 39        | 18.22%  |
| GDM     | 28        | 13.08%  |
| LightDM | 15        | 7.01%   |
| GDM3    | 9         | 4.21%   |
| TDM     | 4         | 1.87%   |
| KDM     | 2         | 0.93%   |
| GREETD  | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_UY   | 105       | 47.73%  |
| en_US   | 45        | 20.45%  |
| Unknown | 31        | 14.09%  |
| es_ES   | 23        | 10.45%  |
| es_AR   | 6         | 2.73%   |
| C       | 4         | 1.82%   |
| es_MX   | 3         | 1.36%   |
| pt_BR   | 1         | 0.45%   |
| POSIX   | 1         | 0.45%   |
| en_CA   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 114       | 53.27%  |
| EFI  | 100       | 46.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 175       | 81.78%  |
| Overlay | 22        | 10.28%  |
| Unknown | 8         | 3.74%   |
| Btrfs   | 7         | 3.27%   |
| Xfs     | 1         | 0.47%   |
| Ext3    | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 132       | 61.97%  |
| GPT     | 59        | 27.7%   |
| MBR     | 22        | 10.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 81.13%  |
| Yes       | 40        | 18.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 67.14%  |
| Yes       | 70        | 32.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 34        | 16.11%  |
| Lenovo              | 25        | 11.85%  |
| ASUSTek Computer    | 25        | 11.85%  |
| Dell                | 17        | 8.06%   |
| ASRock              | 16        | 7.58%   |
| Gigabyte Technology | 15        | 7.11%   |
| ECS                 | 15        | 7.11%   |
| MSI                 | 13        | 6.16%   |
| Acer                | 11        | 5.21%   |
| Toshiba             | 8         | 3.79%   |
| Samsung Electronics | 4         | 1.9%    |
| Standard            | 3         | 1.42%   |
| Intel               | 3         | 1.42%   |
| Biostar             | 3         | 1.42%   |
| GPU Company         | 2         | 0.95%   |
| Gateway             | 2         | 0.95%   |
| Apple               | 2         | 0.95%   |
| Unknown             | 2         | 0.95%   |
| Supermicro          | 1         | 0.47%   |
| Sony                | 1         | 0.47%   |
| Positivo            | 1         | 0.47%   |
| Panasonic           | 1         | 0.47%   |
| OEM                 | 1         | 0.47%   |
| MACHINIST           | 1         | 0.47%   |
| iClever             | 1         | 0.47%   |
| Huanan              | 1         | 0.47%   |
| Haitech             | 1         | 0.47%   |
| Fujitsu             | 1         | 0.47%   |
| Foxconn             | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ECS SF20PA2                                | 14        | 6.64%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 3         | 1.42%   |
| Toshiba Satellite L55t-B                   | 2         | 0.95%   |
| Standard SF20BA2                           | 2         | 0.95%   |
| MSI MS-7C37                                | 2         | 0.95%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL0014LD | 2         | 0.95%   |
| HP Pavilion 15                             | 2         | 0.95%   |
| HP Laptop 15-bs0xx                         | 2         | 0.95%   |
| Gigabyte Z390 AORUS ELITE                  | 2         | 0.95%   |
| ASRock N68-S                               | 2         | 0.95%   |
| ASRock H310CM-HDV                          | 2         | 0.95%   |
| ASRock FM2A58M-VG3+ R2.0                   | 2         | 0.95%   |
| ASRock ALiveNF6P-VSTA                      | 2         | 0.95%   |
| Unknown                                    | 2         | 0.95%   |
| Toshiba Satellite L45-B                    | 1         | 0.47%   |
| Toshiba Satellite C855                     | 1         | 0.47%   |
| Toshiba Satellite C75D-C                   | 1         | 0.47%   |
| Toshiba Satellite C645D                    | 1         | 0.47%   |
| Toshiba Satellite C55-B                    | 1         | 0.47%   |
| Toshiba Satellite C45-A                    | 1         | 0.47%   |
| Supermicro P4DMS                           | 1         | 0.47%   |
| Standard EF20EA                            | 1         | 0.47%   |
| Sony SVF14211CLB                           | 1         | 0.47%   |
| Samsung NC208/NC108                        | 1         | 0.47%   |
| Samsung N102SP/N100SP/N101SP               | 1         | 0.47%   |
| Samsung 700T                               | 1         | 0.47%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.47%   |
| Positivo Serie AT300                       | 1         | 0.47%   |
| Panasonic CF-31JEGAX1M                     | 1         | 0.47%   |
| OEM V40SI2                                 | 1         | 0.47%   |
| MSI Pro 3130 Microtower PC                 | 1         | 0.47%   |
| MSI MS-7817                                | 1         | 0.47%   |
| MSI MS-7816                                | 1         | 0.47%   |
| MSI MS-7786                                | 1         | 0.47%   |
| MSI MS-7721                                | 1         | 0.47%   |
| MSI MS-7592                                | 1         | 0.47%   |
| MSI MS-7383                                | 1         | 0.47%   |
| MSI GS63VR 6RF                             | 1         | 0.47%   |
| MSI GL65 Leopard 10SCXR                    | 1         | 0.47%   |
| MSI GL63 8RD                               | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 14        | 6.64%   |
| Lenovo ThinkPad        | 9         | 4.27%   |
| Toshiba Satellite      | 8         | 3.79%   |
| HP Laptop              | 8         | 3.79%   |
| HP Pavilion            | 7         | 3.32%   |
| Dell Inspiron          | 7         | 3.32%   |
| Acer Aspire            | 7         | 3.32%   |
| Lenovo IdeaPad         | 6         | 2.84%   |
| ASUS ROG               | 5         | 2.37%   |
| HP Compaq              | 4         | 1.9%    |
| Dell OptiPlex          | 3         | 1.42%   |
| Dell Latitude          | 3         | 1.42%   |
| Standard SF20BA2       | 2         | 0.95%   |
| MSI MS-7C37            | 2         | 0.95%   |
| Lenovo ThinkCentre     | 2         | 0.95%   |
| Lenovo IdeaCentre      | 2         | 0.95%   |
| HP ENVY                | 2         | 0.95%   |
| HP EliteDesk           | 2         | 0.95%   |
| Gigabyte Z390          | 2         | 0.95%   |
| Dell XPS               | 2         | 0.95%   |
| ASUS VivoBook          | 2         | 0.95%   |
| ASUS TUF               | 2         | 0.95%   |
| ASUS PRIME             | 2         | 0.95%   |
| ASRock N68-S           | 2         | 0.95%   |
| ASRock H310CM-HDV      | 2         | 0.95%   |
| ASRock FM2A58M-VG3+    | 2         | 0.95%   |
| ASRock ALiveNF6P-VSTA  | 2         | 0.95%   |
| ASRock A320M-HDV       | 2         | 0.95%   |
| Acer TravelMate        | 2         | 0.95%   |
| Unknown                | 2         | 0.95%   |
| Supermicro P4DMS       | 1         | 0.47%   |
| Standard EF20EA        | 1         | 0.47%   |
| Sony SVF14211CLB       | 1         | 0.47%   |
| Samsung NC208          | 1         | 0.47%   |
| Samsung N102SP         | 1         | 0.47%   |
| Samsung 700T           | 1         | 0.47%   |
| Samsung 300E4C         | 1         | 0.47%   |
| Positivo Serie         | 1         | 0.47%   |
| Panasonic CF-31JEGAX1M | 1         | 0.47%   |
| OEM V40SI2             | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 27        | 12.8%   |
| 2019    | 25        | 11.85%  |
| 2013    | 21        | 9.95%   |
| 2011    | 21        | 9.95%   |
| 2020    | 15        | 7.11%   |
| 2018    | 15        | 7.11%   |
| 2016    | 13        | 6.16%   |
| 2014    | 13        | 6.16%   |
| 2015    | 12        | 5.69%   |
| 2012    | 12        | 5.69%   |
| 2010    | 7         | 3.32%   |
| 2009    | 7         | 3.32%   |
| 2021    | 6         | 2.84%   |
| 2007    | 6         | 2.84%   |
| 2008    | 4         | 1.9%    |
| 2022    | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |
| 2005    | 1         | 0.47%   |
| 2004    | 1         | 0.47%   |
| 2003    | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 123       | 58.29%  |
| Desktop     | 78        | 36.97%  |
| Mini pc     | 3         | 1.42%   |
| Phone       | 2         | 0.95%   |
| Convertible | 2         | 0.95%   |
| All in one  | 2         | 0.95%   |
| Tablet      | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 197       | 92.92%  |
| Enabled  | 15        | 7.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 211       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 24.07%  |
| 3.01-4.0    | 50        | 23.15%  |
| 8.01-16.0   | 34        | 15.74%  |
| 16.01-24.0  | 27        | 12.5%   |
| 1.01-2.0    | 25        | 11.57%  |
| 32.01-64.0  | 13        | 6.02%   |
| 24.01-32.0  | 7         | 3.24%   |
| 64.01-256.0 | 4         | 1.85%   |
| 2.01-3.0    | 2         | 0.93%   |
| 0.51-1.0    | 1         | 0.46%   |
| 0.01-0.5    | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 95        | 42.22%  |
| 2.01-3.0  | 49        | 21.78%  |
| 3.01-4.0  | 25        | 11.11%  |
| 4.01-8.0  | 23        | 10.22%  |
| 0.51-1.0  | 20        | 8.89%   |
| 8.01-16.0 | 9         | 4%      |
| 0.01-0.5  | 4         | 1.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 68.37%  |
| 2      | 44        | 20.47%  |
| 4      | 10        | 4.65%   |
| 3      | 10        | 4.65%   |
| 5      | 2         | 0.93%   |
| 0      | 2         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 130       | 61.32%  |
| Yes       | 82        | 38.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 77.73%  |
| No        | 47        | 22.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 75.59%  |
| No        | 52        | 24.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 56.4%   |
| No        | 92        | 43.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Uruguay | 211       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Montevideo             | 155       | 69.82%  |
| Maldonado              | 10        | 4.5%    |
| Canelones              | 8         | 3.6%    |
| San Jose de Mayo       | 4         | 1.8%    |
| Las Piedras            | 4         | 1.8%    |
| Punta del Este         | 3         | 1.35%   |
| Florida                | 3         | 1.35%   |
| Ciudad del Plata       | 3         | 1.35%   |
| Buceo                  | 3         | 1.35%   |
| Salto                  | 2         | 0.9%    |
| Rocha                  | 2         | 0.9%    |
| Punta Gorda            | 2         | 0.9%    |
| Parque Rodo            | 2         | 0.9%    |
| La Paz                 | 2         | 0.9%    |
| Durazno                | 2         | 0.9%    |
| Solymar                | 1         | 0.45%   |
| Pinamar                | 1         | 0.45%   |
| Paysandú              | 1         | 0.45%   |
| Nuevo Paris            | 1         | 0.45%   |
| Melo                   | 1         | 0.45%   |
| Melilla                | 1         | 0.45%   |
| Maronas                | 1         | 0.45%   |
| Malvin Norte           | 1         | 0.45%   |
| Las Flores             | 1         | 0.45%   |
| La Barra               | 1         | 0.45%   |
| Joaquin Suarez         | 1         | 0.45%   |
| El Tesoro              | 1         | 0.45%   |
| El Pinar               | 1         | 0.45%   |
| Centro                 | 1         | 0.45%   |
| Barrancas Coloradas    | 1         | 0.45%   |
| Arenas de Jose Ignacio | 1         | 0.45%   |
| Unknown                | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 63        | 78     | 22.26%  |
| Seagate                   | 38        | 48     | 13.43%  |
| Kingston                  | 35        | 43     | 12.37%  |
| Toshiba                   | 31        | 37     | 10.95%  |
| Samsung Electronics       | 29        | 30     | 10.25%  |
| Unknown                   | 20        | 26     | 7.07%   |
| SanDisk                   | 13        | 16     | 4.59%   |
| Hitachi                   | 9         | 14     | 3.18%   |
| Crucial                   | 7         | 9      | 2.47%   |
| SK hynix                  | 5         | 5      | 1.77%   |
| Intel                     | 4         | 4      | 1.41%   |
| HGST                      | 4         | 4      | 1.41%   |
| Hewlett-Packard           | 4         | 4      | 1.41%   |
| Netac                     | 2         | 2      | 0.71%   |
| Micron/Crucial Technology | 2         | 3      | 0.71%   |
| Maxtor                    | 2         | 3      | 0.71%   |
| W800SH                    | 1         | 1      | 0.35%   |
| Silicon Motion            | 1         | 1      | 0.35%   |
| Phison                    | 1         | 1      | 0.35%   |
| Patriot                   | 1         | 1      | 0.35%   |
| Micron Technology         | 1         | 1      | 0.35%   |
| LITEON                    | 1         | 2      | 0.35%   |
| IBM-ESXS                  | 1         | 1      | 0.35%   |
| Gigabyte Technology       | 1         | 1      | 0.35%   |
| ExcelStor                 | 1         | 1      | 0.35%   |
| China                     | 1         | 1      | 0.35%   |
| BIWIN                     | 1         | 1      | 0.35%   |
| Biostar                   | 1         | 1      | 0.35%   |
| BHT                       | 1         | 1      | 0.35%   |
| Apple                     | 1         | 1      | 0.35%   |
| A-DATA Technology         | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 11        | 3.65%   |
| Unknown MMC Card  32GB              | 10        | 3.32%   |
| Unknown DA4032  32GB                | 5         | 1.66%   |
| Toshiba DT01ACA100 1TB              | 5         | 1.66%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 1.66%   |
| Samsung HD161HJ 160GB               | 5         | 1.66%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 1.66%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 1.33%   |
| Toshiba MQ01ABD075 752GB            | 4         | 1.33%   |
| Toshiba DT01ACA300 3TB              | 4         | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.33%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 1.33%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 1%      |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 1%      |
| Toshiba MQ01ABF050 500GB            | 3         | 1%      |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1%      |
| SanDisk DF4032  32GB                | 3         | 1%      |
| Kingston SV300S37A120G 120GB SSD    | 3         | 1%      |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.66%   |
| WDC WD5000LPVT-24G33T1 500GB        | 2         | 0.66%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.66%   |
| WDC WD10EFRX-68FYTN0 1TB            | 2         | 0.66%   |
| Unknown SD/MMC/MS PRO 1TB           | 2         | 0.66%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.66%   |
| Toshiba MK5059GSXP 500GB            | 2         | 0.66%   |
| Toshiba HDWK105 500GB               | 2         | 0.66%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.66%   |
| Seagate ST3250312AS 250GB           | 2         | 0.66%   |
| Seagate ST3160318AS 160GB           | 2         | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 1024GB       | 2         | 0.66%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.66%   |
| Samsung HD103SJ 1TB                 | 2         | 0.66%   |
| Kingston SNVS1000G 1TB              | 2         | 0.66%   |
| Kingston SA2000M81000G 1TB          | 2         | 0.66%   |
| HP SSD S700 500GB                   | 2         | 0.66%   |
| Crucial CT500P2SSD8 500GB           | 2         | 0.66%   |
| Crucial CT1000BX500SSD1 1TB         | 2         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 53        | 66     | 35.33%  |
| Seagate             | 38        | 48     | 25.33%  |
| Toshiba             | 27        | 33     | 18%     |
| Samsung Electronics | 14        | 14     | 9.33%   |
| Hitachi             | 9         | 14     | 6%      |
| HGST                | 4         | 4      | 2.67%   |
| Unknown             | 2         | 2      | 1.33%   |
| Maxtor              | 2         | 3      | 1.33%   |
| ExcelStor           | 1         | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 28        | 32     | 40.58%  |
| Samsung Electronics | 8         | 9      | 11.59%  |
| WDC                 | 7         | 7      | 10.14%  |
| Crucial             | 5         | 6      | 7.25%   |
| SanDisk             | 4         | 4      | 5.8%    |
| Hewlett-Packard     | 3         | 3      | 4.35%   |
| SK hynix            | 2         | 2      | 2.9%    |
| Netac               | 2         | 2      | 2.9%    |
| Intel               | 2         | 2      | 2.9%    |
| W800SH              | 1         | 1      | 1.45%   |
| Toshiba             | 1         | 1      | 1.45%   |
| Micron Technology   | 1         | 1      | 1.45%   |
| Gigabyte Technology | 1         | 1      | 1.45%   |
| China               | 1         | 1      | 1.45%   |
| BIWIN               | 1         | 1      | 1.45%   |
| BHT                 | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 121       | 185    | 48.21%  |
| SSD     | 67        | 75     | 26.69%  |
| NVMe    | 40        | 52     | 15.94%  |
| MMC     | 21        | 28     | 8.37%   |
| Unknown | 2         | 2      | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 163       | 257    | 71.18%  |
| NVMe | 40        | 52     | 17.47%  |
| MMC  | 21        | 28     | 9.17%   |
| SAS  | 5         | 5      | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 157    | 62.94%  |
| 0.51-1.0   | 62        | 92     | 31.47%  |
| 2.01-3.0   | 5         | 5      | 2.54%   |
| 1.01-2.0   | 4         | 4      | 2.03%   |
| 3.01-4.0   | 2         | 2      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 24.77%  |
| 251-500        | 49        | 22.48%  |
| 501-1000       | 33        | 15.14%  |
| 1-20           | 24        | 11.01%  |
| 21-50          | 22        | 10.09%  |
| 1001-2000      | 13        | 5.96%   |
| 51-100         | 9         | 4.13%   |
| Unknown        | 9         | 4.13%   |
| More than 3000 | 3         | 1.38%   |
| 2001-3000      | 2         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 100       | 44.64%  |
| 21-50          | 40        | 17.86%  |
| 101-250        | 19        | 8.48%   |
| 251-500        | 18        | 8.04%   |
| 51-100         | 18        | 8.04%   |
| 501-1000       | 14        | 6.25%   |
| Unknown        | 9         | 4.02%   |
| 1001-2000      | 3         | 1.34%   |
| More than 3000 | 2         | 0.89%   |
| 2001-3000      | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 3      | 11.54%  |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 7.69%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 3.85%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 1      | 3.85%   |
| WDC WD5000AAJS-00A8B0 500GB         | 1         | 1      | 3.85%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 3.85%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 3.85%   |
| Toshiba MK3276GSX 320GB             | 1         | 1      | 3.85%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 3.85%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 3.85%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 3.85%   |
| Seagate ST500DM005 HD502HJ 500GB    | 1         | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 3.85%   |
| Seagate ST3750640NS 752GB           | 1         | 6      | 3.85%   |
| Seagate ST3250310CS 250GB           | 1         | 1      | 3.85%   |
| Seagate ST3200827AS 200GB           | 1         | 1      | 3.85%   |
| Seagate ST250DM000-1BD141 250GB     | 1         | 1      | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 3.85%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1      | 3.85%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 3.85%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 32%     |
| Seagate | 8         | 14     | 32%     |
| Toshiba | 7         | 8      | 28%     |
| SanDisk | 1         | 1      | 4%      |
| Hitachi | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 33.33%  |
| Seagate | 8         | 14     | 33.33%  |
| Toshiba | 7         | 8      | 29.17%  |
| Hitachi | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 31     | 96%     |
| SSD  | 1         | 1      | 4%      |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 133       | 212    | 59.91%  |
| Works    | 64        | 98     | 28.83%  |
| Malfunc  | 25        | 32     | 11.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 138       | 56.56%  |
| AMD                              | 50        | 20.49%  |
| SanDisk                          | 11        | 4.51%   |
| Samsung Electronics              | 7         | 2.87%   |
| Kingston Technology Company      | 7         | 2.87%   |
| Nvidia                           | 5         | 2.05%   |
| ASMedia Technology               | 5         | 2.05%   |
| Micron/Crucial Technology        | 4         | 1.64%   |
| Toshiba America Info Systems     | 3         | 1.23%   |
| SK hynix                         | 3         | 1.23%   |
| Silicon Motion                   | 3         | 1.23%   |
| Marvell Technology Group         | 2         | 0.82%   |
| VIA Technologies                 | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Phison Electronics               | 1         | 0.41%   |
| Lite-On Technology               | 1         | 0.41%   |
| Apple                            | 1         | 0.41%   |
| Adaptec                          | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36        | 12.68%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 5.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 3.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 2.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 2.11%   |
| Nvidia MCP61 SATA Controller                                                            | 5         | 1.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.76%   |
| AMD FCH IDE Controller                                                                  | 5         | 1.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.41%   |
| Nvidia MCP61 IDE                                                                        | 4         | 1.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.06%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.06%   |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.06%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.7%    |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 166       | 65.61%  |
| NVMe | 40        | 15.81%  |
| IDE  | 36        | 14.23%  |
| RAID | 10        | 3.95%   |
| SCSI | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 149       | 70.62%  |
| AMD      | 60        | 28.44%  |
| QUALCOMM | 1         | 0.47%   |
| ARM      | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz               | 15        | 7.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 3         | 1.42%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 3         | 1.42%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3         | 1.42%   |
| AMD Ryzen 9 4900HS with Radeon Graphics         | 3         | 1.42%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 3         | 1.42%   |
| Intel Pentium CPU N3710 @ 1.60GHz               | 2         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 0.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2         | 0.95%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 2         | 0.95%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 2         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 0.95%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2         | 0.95%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 0.95%   |
| Intel Celeron CPU N3160 @ 1.60GHz               | 2         | 0.95%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 2         | 0.95%   |
| Intel Celeron CPU J3355 @ 2.00GHz               | 2         | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 0.95%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2         | 0.95%   |
| AMD E-300 APU with Radeon HD Graphics           | 2         | 0.95%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 2         | 0.95%   |
| AMD A6-5200 APU with Radeon HD Graphics         | 2         | 0.95%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 2         | 0.95%   |
| QUALCOMM AArch64 Processor rev 1 (aarch64)      | 1         | 0.47%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz              | 1         | 0.47%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1         | 0.47%   |
| Intel Xeon CPU 2.40GHz                          | 1         | 0.47%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz          | 1         | 0.47%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.47%   |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1         | 0.47%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.47%   |
| Intel Pentium CPU B970 @ 2.30GHz                | 1         | 0.47%   |
| Intel Pentium CPU 2117U @ 1.80GHz               | 1         | 0.47%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 38        | 18.01%  |
| Intel Core i7      | 33        | 15.64%  |
| Intel Celeron      | 26        | 12.32%  |
| Intel Core i3      | 19        | 9%      |
| AMD Ryzen 5        | 8         | 3.79%   |
| Intel Pentium      | 7         | 3.32%   |
| Intel Core 2 Duo   | 7         | 3.32%   |
| AMD Ryzen 7        | 7         | 3.32%   |
| Intel Atom         | 6         | 2.84%   |
| AMD A6             | 5         | 2.37%   |
| Other              | 4         | 1.9%    |
| AMD Ryzen 9        | 4         | 1.9%    |
| AMD FX             | 4         | 1.9%    |
| AMD Athlon II X2   | 4         | 1.9%    |
| Intel Xeon         | 3         | 1.42%   |
| Intel Core 2 Quad  | 3         | 1.42%   |
| AMD Ryzen 3        | 3         | 1.42%   |
| AMD A4             | 3         | 1.42%   |
| AMD A10            | 3         | 1.42%   |
| Intel Genuine      | 2         | 0.95%   |
| AMD Phenom II X6   | 2         | 0.95%   |
| AMD E1             | 2         | 0.95%   |
| AMD E              | 2         | 0.95%   |
| AMD Athlon         | 2         | 0.95%   |
| AMD A8             | 2         | 0.95%   |
| QUALCOMM AArch64   | 1         | 0.47%   |
| Intel Pentium Dual | 1         | 0.47%   |
| Intel Pentium 4    | 1         | 0.47%   |
| Intel Core i9      | 1         | 0.47%   |
| ARM AArch64        | 1         | 0.47%   |
| AMD PRO A10        | 1         | 0.47%   |
| AMD Phenom II      | 1         | 0.47%   |
| AMD Phenom         | 1         | 0.47%   |
| AMD E2             | 1         | 0.47%   |
| AMD Athlon II      | 1         | 0.47%   |
| AMD Athlon 64 X2   | 1         | 0.47%   |
| AMD Athlon 64      | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 105       | 49.76%  |
| 4      | 62        | 29.38%  |
| 6      | 22        | 10.43%  |
| 8      | 15        | 7.11%   |
| 1      | 7         | 3.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 208       | 98.58%  |
| 2      | 3         | 1.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 120       | 56.87%  |
| 1      | 91        | 43.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 204       | 96.68%  |
| Unknown        | 5         | 2.37%   |
| 32-bit         | 2         | 0.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 21.6%   |
| 0x206a7    | 12        | 5.63%   |
| 0x906ea    | 7         | 3.29%   |
| 0x406c4    | 7         | 3.29%   |
| 0x306c3    | 7         | 3.29%   |
| 0x20655    | 7         | 3.29%   |
| 0x506c9    | 6         | 2.82%   |
| 0x40651    | 6         | 2.82%   |
| 0x1067a    | 6         | 2.82%   |
| 0x806e9    | 5         | 2.35%   |
| 0x306d4    | 5         | 2.35%   |
| 0x306a9    | 5         | 2.35%   |
| 0x806ec    | 4         | 1.88%   |
| 0x806ea    | 4         | 1.88%   |
| 0x406e3    | 4         | 1.88%   |
| 0x30678    | 4         | 1.88%   |
| 0x08701021 | 4         | 1.88%   |
| 0x08108109 | 4         | 1.88%   |
| 0x6fd      | 3         | 1.41%   |
| 0x06001119 | 3         | 1.41%   |
| 0x06000852 | 3         | 1.41%   |
| 0xa0655    | 2         | 0.94%   |
| 0xa0653    | 2         | 0.94%   |
| 0x906eb    | 2         | 0.94%   |
| 0x806c1    | 2         | 0.94%   |
| 0x706e5    | 2         | 0.94%   |
| 0x406c3    | 2         | 0.94%   |
| 0x206d7    | 2         | 0.94%   |
| 0x10676    | 2         | 0.94%   |
| 0x08600104 | 2         | 0.94%   |
| 0x0810100b | 2         | 0.94%   |
| 0x08001138 | 2         | 0.94%   |
| 0x07030104 | 2         | 0.94%   |
| 0x0700010f | 2         | 0.94%   |
| 0x06006705 | 2         | 0.94%   |
| 0x010000dc | 2         | 0.94%   |
| 0x010000c8 | 2         | 0.94%   |
| 0x010000b6 | 2         | 0.94%   |
| 0xf33      | 1         | 0.47%   |
| 0xf27      | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 12.32%  |
| Goldmont      | 17        | 8.06%   |
| SandyBridge   | 16        | 7.58%   |
| Silvermont    | 14        | 6.64%   |
| Haswell       | 13        | 6.16%   |
| IvyBridge     | 11        | 5.21%   |
| Skylake       | 9         | 4.27%   |
| Penryn        | 9         | 4.27%   |
| K10           | 9         | 4.27%   |
| Zen 2         | 8         | 3.79%   |
| Zen+          | 7         | 3.32%   |
| Westmere      | 7         | 3.32%   |
| CometLake     | 7         | 3.32%   |
| Piledriver    | 6         | 2.84%   |
| Excavator     | 6         | 2.84%   |
| Broadwell     | 6         | 2.84%   |
| Zen           | 5         | 2.37%   |
| Zen 3         | 4         | 1.9%    |
| Puma          | 4         | 1.9%    |
| Core          | 4         | 1.9%    |
| Steamroller   | 3         | 1.42%   |
| Jaguar        | 3         | 1.42%   |
| TigerLake     | 2         | 0.95%   |
| NetBurst      | 2         | 0.95%   |
| K8 Hammer     | 2         | 0.95%   |
| IceLake       | 2         | 0.95%   |
| Bonnell       | 2         | 0.95%   |
| Bobcat        | 2         | 0.95%   |
| Unknown       | 2         | 0.95%   |
| Nehalem       | 1         | 0.47%   |
| K10 Llano     | 1         | 0.47%   |
| Goldmont plus | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 123       | 52.12%  |
| AMD                              | 60        | 25.42%  |
| Nvidia                           | 52        | 22.03%  |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 7.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 4.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.48%   |
| Intel HD Graphics 620                                                                    | 5         | 2.07%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.07%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.65%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.65%   |
| Intel HD Graphics 530                                                                    | 4         | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.65%   |
| AMD Renoir                                                                               | 4         | 1.65%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.24%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 1.24%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.24%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.24%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.24%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.24%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.24%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 1.24%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.83%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.83%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.83%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 102       | 48.34%  |
| 1 x AMD        | 42        | 19.91%  |
| 1 x Nvidia     | 36        | 17.06%  |
| Intel + Nvidia | 10        | 4.74%   |
| Intel + AMD    | 8         | 3.79%   |
| AMD + Nvidia   | 6         | 2.84%   |
| 2 x AMD        | 4         | 1.9%    |
| Other          | 2         | 0.95%   |
| 1 x SiS        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 181       | 85.38%  |
| Proprietary | 23        | 10.85%  |
| Unknown     | 8         | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 58.14%  |
| 1.01-2.0   | 23        | 10.7%   |
| 0.51-1.0   | 22        | 10.23%  |
| 0.01-0.5   | 21        | 9.77%   |
| 3.01-4.0   | 15        | 6.98%   |
| 5.01-6.0   | 5         | 2.33%   |
| 7.01-8.0   | 3         | 1.4%    |
| 8.01-16.0  | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 11.21%  |
| LG Display              | 20        | 9.35%   |
| AU Optronics            | 20        | 9.35%   |
| Chimei Innolux          | 19        | 8.88%   |
| BOE                     | 18        | 8.41%   |
| ViewSonic               | 16        | 7.48%   |
| AOC                     | 15        | 7.01%   |
| KTC                     | 8         | 3.74%   |
| Goldstar                | 7         | 3.27%   |
| Acer                    | 7         | 3.27%   |
| KDC                     | 6         | 2.8%    |
| InfoVision              | 6         | 2.8%    |
| Lenovo                  | 5         | 2.34%   |
| Chi Mei Optoelectronics | 5         | 2.34%   |
| Sharp                   | 4         | 1.87%   |
| PANDA                   | 4         | 1.87%   |
| Hewlett-Packard         | 4         | 1.87%   |
| Dell                    | 3         | 1.4%    |
| Unknown                 | 2         | 0.93%   |
| HKC                     | 2         | 0.93%   |
| Sun                     | 1         | 0.47%   |
| Sony                    | 1         | 0.47%   |
| RIS                     | 1         | 0.47%   |
| Panasonic               | 1         | 0.47%   |
| LG Philips              | 1         | 0.47%   |
| LG Electronics          | 1         | 0.47%   |
| Lenovo Group Limited    | 1         | 0.47%   |
| KVM                     | 1         | 0.47%   |
| KOA                     | 1         | 0.47%   |
| JDI                     | 1         | 0.47%   |
| InnoLux Display         | 1         | 0.47%   |
| HSI                     | 1         | 0.47%   |
| Hitachi                 | 1         | 0.47%   |
| Envision                | 1         | 0.47%   |
| CVT                     | 1         | 0.47%   |
| CPT                     | 1         | 0.47%   |
| BenQ                    | 1         | 0.47%   |
| Apple                   | 1         | 0.47%   |
| Ancor Communications    | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 5         | 2.27%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch            | 4         | 1.82%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 4         | 1.82%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.36%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch               | 2         | 0.91%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                  | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.91%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.91%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 2         | 0.91%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 2         | 0.91%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.91%   |
| Lenovo LEN-A3/V1-E LEN0017 1440x900 420x270mm 19.7-inch                  | 2         | 0.91%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch                 | 2         | 0.91%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                     | 2         | 0.91%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.91%   |
| HKC Monitor HKC1850 1360x768 409x230mm 18.5-inch                         | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 0.91%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.91%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.91%   |
| AOC 2461W AOC2461 1920x1080 521x293mm 23.5-inch                          | 2         | 0.91%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.91%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.91%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.91%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                           | 2         | 0.91%   |
| ViewSonic XG2405 VSC0D39 1920x1080 530x300mm 24.0-inch                   | 1         | 0.45%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch            | 1         | 0.45%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch            | 1         | 0.45%   |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch                  | 1         | 0.45%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch                  | 1         | 0.45%   |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch                   | 1         | 0.45%   |
| ViewSonic VA2415-FHD VSC533C 1920x1080 527x296mm 23.8-inch               | 1         | 0.45%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch            | 1         | 0.45%   |
| ViewSonic VA1903a VSC8A31 1366x768 410x230mm 18.5-inch                   | 1         | 0.45%   |
| ViewSonic LCD Monitor VX2240w 3600x1080                                  | 1         | 0.45%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch              | 1         | 0.45%   |
| ViewSonic LCD Monitor VA2261                                             | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 78        | 39.39%  |
| 1920x1080 (FHD)    | 62        | 31.31%  |
| 1600x900 (HD+)     | 12        | 6.06%   |
| 3840x2160 (4K)     | 6         | 3.03%   |
| 2560x1440 (QHD)    | 6         | 3.03%   |
| 1920x1200 (WUXGA)  | 5         | 2.53%   |
| 1440x900 (WXGA+)   | 5         | 2.53%   |
| 1360x768           | 4         | 2.02%   |
| 1280x1024 (SXGA)   | 4         | 2.02%   |
| 1680x1050 (WSXGA+) | 3         | 1.52%   |
| 1280x800 (WXGA)    | 3         | 1.52%   |
| Unknown            | 3         | 1.52%   |
| 1280x720 (HD)      | 2         | 1.01%   |
| 3600x1080          | 1         | 0.51%   |
| 2944x1080          | 1         | 0.51%   |
| 2560x1080          | 1         | 0.51%   |
| 1280x768           | 1         | 0.51%   |
| 1024x600           | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 71        | 33.33%  |
| 13      | 21        | 9.86%   |
| 23      | 19        | 8.92%   |
| 14      | 17        | 7.98%   |
| 21      | 12        | 5.63%   |
| 18      | 12        | 5.63%   |
| 24      | 8         | 3.76%   |
| 17      | 7         | 3.29%   |
| Unknown | 7         | 3.29%   |
| 19      | 6         | 2.82%   |
| 11      | 6         | 2.82%   |
| 27      | 5         | 2.35%   |
| 31      | 3         | 1.41%   |
| 20      | 3         | 1.41%   |
| 84      | 2         | 0.94%   |
| 44      | 2         | 0.94%   |
| 34      | 2         | 0.94%   |
| 32      | 2         | 0.94%   |
| 22      | 2         | 0.94%   |
| 12      | 2         | 0.94%   |
| 57      | 1         | 0.47%   |
| 40      | 1         | 0.47%   |
| 16      | 1         | 0.47%   |
| 10      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 103       | 49.05%  |
| 401-500     | 32        | 15.24%  |
| 501-600     | 30        | 14.29%  |
| 201-300     | 14        | 6.67%   |
| 351-400     | 11        | 5.24%   |
| Unknown     | 7         | 3.33%   |
| 701-800     | 4         | 1.9%    |
| 601-700     | 3         | 1.43%   |
| 1501-2000   | 2         | 0.95%   |
| 901-1000    | 2         | 0.95%   |
| 801-900     | 1         | 0.48%   |
| 1001-1500   | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 163       | 86.7%   |
| 16/10   | 12        | 6.38%   |
| Unknown | 7         | 3.72%   |
| 5/4     | 4         | 2.13%   |
| 21/9    | 2         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 33.49%  |
| 81-90          | 33        | 15.79%  |
| 201-250        | 30        | 14.35%  |
| 151-200        | 18        | 8.61%   |
| 141-150        | 10        | 4.78%   |
| Unknown        | 7         | 3.35%   |
| 51-60          | 6         | 2.87%   |
| 351-500        | 6         | 2.87%   |
| 121-130        | 6         | 2.87%   |
| 71-80          | 5         | 2.39%   |
| 301-350        | 5         | 2.39%   |
| More than 1000 | 3         | 1.44%   |
| 501-1000       | 3         | 1.44%   |
| 61-70          | 2         | 0.96%   |
| 251-300        | 2         | 0.96%   |
| 41-50          | 1         | 0.48%   |
| 131-140        | 1         | 0.48%   |
| 91-100         | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 76        | 37.07%  |
| 51-100        | 74        | 36.1%   |
| 121-160       | 38        | 18.54%  |
| Unknown       | 7         | 3.41%   |
| 161-240       | 5         | 2.44%   |
| 1-50          | 4         | 1.95%   |
| More than 240 | 1         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 169       | 78.6%   |
| 2     | 31        | 14.42%  |
| 0     | 12        | 5.58%   |
| 3     | 2         | 0.93%   |
| 4     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 111       | 35.81%  |
| Intel                            | 87        | 28.06%  |
| Qualcomm Atheros                 | 43        | 13.87%  |
| Broadcom                         | 19        | 6.13%   |
| Ralink Technology                | 9         | 2.9%    |
| TP-Link                          | 7         | 2.26%   |
| Nvidia                           | 5         | 1.61%   |
| Ralink                           | 4         | 1.29%   |
| Xiaomi                           | 3         | 0.97%   |
| MediaTek                         | 3         | 0.97%   |
| Broadcom Limited                 | 3         | 0.97%   |
| Samsung Electronics              | 2         | 0.65%   |
| Mercucys                         | 2         | 0.65%   |
| Huawei Technologies              | 2         | 0.65%   |
| VIA Technologies                 | 1         | 0.32%   |
| Texas Instruments                | 1         | 0.32%   |
| T & A Mobile Phones              | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Sierra Wireless                  | 1         | 0.32%   |
| Qualcomm Atheros Communications  | 1         | 0.32%   |
| Qualcomm                         | 1         | 0.32%   |
| Lenovo                           | 1         | 0.32%   |
| DisplayLink                      | 1         | 0.32%   |
| ASIX Electronics                 | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 21.13%  |
| Intel Wireless 3165                                               | 21        | 5.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 5.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.97%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.69%   |
| Intel Wireless 7265                                               | 6         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 1.41%   |
| Nvidia MCP61 Ethernet                                             | 5         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.41%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.13%   |
| Intel Wireless 7260                                               | 4         | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.85%   |
| Intel Wireless 8260                                               | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.56%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.56%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 2         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.56%   |
| Realtek 802.11ac NIC                                              | 2         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 37.06%  |
| Realtek Semiconductor           | 38        | 22.35%  |
| Qualcomm Atheros                | 30        | 17.65%  |
| Broadcom                        | 12        | 7.06%   |
| Ralink Technology               | 9         | 5.29%   |
| TP-Link                         | 6         | 3.53%   |
| Ralink                          | 4         | 2.35%   |
| Mercucys                        | 2         | 1.18%   |
| MediaTek                        | 2         | 1.18%   |
| Broadcom Limited                | 2         | 1.18%   |
| Sierra Wireless                 | 1         | 0.59%   |
| Qualcomm Atheros Communications | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 21        | 12.28%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.09%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.51%   |
| Intel Wireless 7265                                                     | 6         | 3.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.92%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.34%   |
| Intel Wireless 7260                                                     | 4         | 2.34%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.75%   |
| Intel Wireless 8260                                                     | 3         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.17%   |
| TP-Link 802.11ac NIC                                                    | 2         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 1.17%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.17%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 1.17%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 1.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.17%   |
| Mercucys 802.11n NIC                                                    | 2         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.17%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.17%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.58%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 100       | 55.56%  |
| Intel                            | 36        | 20%     |
| Qualcomm Atheros                 | 14        | 7.78%   |
| Broadcom                         | 9         | 5%      |
| Nvidia                           | 5         | 2.78%   |
| Xiaomi                           | 3         | 1.67%   |
| Samsung Electronics              | 2         | 1.11%   |
| Huawei Technologies              | 2         | 1.11%   |
| VIA Technologies                 | 1         | 0.56%   |
| TP-Link                          | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Qualcomm                         | 1         | 0.56%   |
| MediaTek                         | 1         | 0.56%   |
| Lenovo                           | 1         | 0.56%   |
| DisplayLink                      | 1         | 0.56%   |
| Broadcom Limited                 | 1         | 0.56%   |
| ASIX Electronics                 | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 41.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 11.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.31%   |
| Nvidia MCP61 Ethernet                                             | 5         | 2.76%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.1%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 2         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.1%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.1%    |
| Huawei E353/E3131                                                 | 2         | 1.1%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.1%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.55%   |
| Samsung Kiera                                                     | 1         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.55%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.55%   |
| Qualcomm Mobile Router                                            | 1         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.55%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1         | 0.55%   |
| Lenovo USB-C to LAN                                               | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 164       | 50%     |
| WiFi     | 161       | 49.09%  |
| Modem    | 2         | 0.61%   |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 63.68%  |
| Ethernet | 77        | 36.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 105       | 49.76%  |
| 2     | 96        | 45.5%   |
| 0     | 8         | 3.79%   |
| 3     | 2         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 166       | 77.93%  |
| Yes  | 47        | 22.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 45.83%  |
| Realtek Semiconductor           | 15        | 12.5%   |
| Qualcomm Atheros Communications | 12        | 10%     |
| Cambridge Silicon Radio         | 10        | 8.33%   |
| Toshiba                         | 6         | 5%      |
| IMC Networks                    | 6         | 5%      |
| Foxconn / Hon Hai               | 3         | 2.5%    |
| Broadcom                        | 3         | 2.5%    |
| Ralink                          | 2         | 1.67%   |
| Lite-On Technology              | 2         | 1.67%   |
| Apple                           | 2         | 1.67%   |
| TP-Link                         | 1         | 0.83%   |
| Ralink Technology               | 1         | 0.83%   |
| Foxconn International           | 1         | 0.83%   |
| Alps Electric                   | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 29.17%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 6.67%   |
| Intel AX200 Bluetooth                               | 7         | 5.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5%      |
| Realtek Bluetooth Radio                             | 5         | 4.17%   |
| Toshiba Bluetooth Device                            | 3         | 2.5%    |
| Toshiba BCM43142A0                                  | 2         | 1.67%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.67%   |
| Intel AX201 Bluetooth                               | 2         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.67%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.67%   |
| TP-Link TPuLink UB500 Adapter                       | 1         | 0.83%   |
| Toshiba Bluetooth Radio                             | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.83%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.83%   |
| Lite-On Bluetooth Device                            | 1         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.83%   |
| IMC Networks Wireless_Device                        | 1         | 0.83%   |
| IMC Networks Bluetooth Device                       | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.83%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.83%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.83%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.83%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 143       | 53.36%  |
| AMD                                  | 57        | 21.27%  |
| Nvidia                               | 43        | 16.04%  |
| Logitech                             | 6         | 2.24%   |
| VIA Technologies                     | 2         | 0.75%   |
| Texas Instruments                    | 2         | 0.75%   |
| Samson Technologies                  | 2         | 0.75%   |
| Generalplus Technology               | 2         | 0.75%   |
| Creative Labs                        | 2         | 0.75%   |
| C-Media Electronics                  | 2         | 0.75%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.37%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.37%   |
| Rockwell International               | 1         | 0.37%   |
| Kingston Technology                  | 1         | 0.37%   |
| Focusrite-Novation                   | 1         | 0.37%   |
| Elgato Systems                       | 1         | 0.37%   |
| Creative Technology                  | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 5.12%   |
| AMD FCH Azalia Controller                                                                         | 15        | 4.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 4.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 3.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.41%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.81%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.81%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.81%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.51%   |
| Nvidia MCP61 High Definition Audio                                                                | 5         | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.9%    |
| Logitech H390 headset with microphone                                                             | 3         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 3         | 0.9%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 20.77%  |
| Kingston            | 17        | 13.08%  |
| SK hynix            | 16        | 12.31%  |
| Micron Technology   | 14        | 10.77%  |
| Unknown             | 13        | 10%     |
| Crucial             | 10        | 7.69%   |
| Ramaxel Technology  | 6         | 4.62%   |
| Elpida              | 4         | 3.08%   |
| A-DATA Technology   | 4         | 3.08%   |
| Nanya Technology    | 3         | 2.31%   |
| Goldkey             | 3         | 2.31%   |
| Team                | 2         | 1.54%   |
| Hikvision           | 2         | 1.54%   |
| Corsair             | 2         | 1.54%   |
| Unknown (2C0B)      | 1         | 0.77%   |
| Smart               | 1         | 0.77%   |
| Patriot             | 1         | 0.77%   |
| Netac               | 1         | 0.77%   |
| KLEVV               | 1         | 0.77%   |
| Infineon            | 1         | 0.77%   |
| Avant               | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 2.17%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 3         | 2.17%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s             | 2         | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 2         | 1.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.45%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s   | 2         | 1.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 2         | 1.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 2         | 1.45%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s    | 2         | 1.45%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s        | 2         | 1.45%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 1.45%   |
| Goldkey RAM GKH200SO25608-1600 2048MB SODIMM DDR3 1600MT/s | 2         | 1.45%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2048MB SODIMM DDR3 1334MT/s   | 2         | 1.45%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                  | 1         | 0.72%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s               | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s             | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                   | 1         | 0.72%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s     | 1         | 0.72%   |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s           | 1         | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s        | 1         | 0.72%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                 | 1         | 0.72%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s        | 1         | 0.72%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                 | 1         | 0.72%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                | 1         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1         | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s  | 1         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 0.72%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s     | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 50        | 48.08%  |
| DDR4    | 40        | 38.46%  |
| SDRAM   | 3         | 2.88%   |
| LPDDR3  | 3         | 2.88%   |
| DDR2    | 3         | 2.88%   |
| Unknown | 3         | 2.88%   |
| LPDDR4  | 1         | 0.96%   |
| DDR     | 1         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 54.46%  |
| DIMM         | 42        | 41.58%  |
| Row Of Chips | 4         | 3.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 36        | 29.51%  |
| 8192  | 35        | 28.69%  |
| 2048  | 23        | 18.85%  |
| 16384 | 20        | 16.39%  |
| 32768 | 4         | 3.28%   |
| 1024  | 3         | 2.46%   |
| 256   | 1         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 36        | 29.51%  |
| 2667  | 18        | 14.75%  |
| 1333  | 13        | 10.66%  |
| 2400  | 10        | 8.2%    |
| 3200  | 6         | 4.92%   |
| 2133  | 5         | 4.1%    |
| 1334  | 5         | 4.1%    |
| 3600  | 4         | 3.28%   |
| 1867  | 3         | 2.46%   |
| 533   | 3         | 2.46%   |
| 4199  | 2         | 1.64%   |
| 3400  | 2         | 1.64%   |
| 3266  | 2         | 1.64%   |
| 3000  | 2         | 1.64%   |
| 1067  | 2         | 1.64%   |
| 3800  | 1         | 0.82%   |
| 3733  | 1         | 0.82%   |
| 3500  | 1         | 0.82%   |
| 2666  | 1         | 0.82%   |
| 2176  | 1         | 0.82%   |
| 1866  | 1         | 0.82%   |
| 1066  | 1         | 0.82%   |
| 333   | 1         | 0.82%   |
| 266   | 1         | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Xerox Phaser 3040    | 1         | 25%     |
| Samsung M288x Series | 1         | 25%     |
| Brother DCP-T500W    | 1         | 25%     |
| Brother DCP-T420W    | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 25.19%  |
| Realtek Semiconductor                  | 14        | 10.37%  |
| Acer                                   | 11        | 8.15%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 6.67%   |
| Microdia                               | 8         | 5.93%   |
| Logitech                               | 8         | 5.93%   |
| Sunplus Innovation Technology          | 7         | 5.19%   |
| Unknown                                | 6         | 4.44%   |
| Suyin                                  | 5         | 3.7%    |
| Silicon Motion                         | 4         | 2.96%   |
| IMC Networks                           | 4         | 2.96%   |
| Syntek                                 | 3         | 2.22%   |
| Quanta                                 | 3         | 2.22%   |
| Importek                               | 3         | 2.22%   |
| Alcor Micro                            | 3         | 2.22%   |
| Samsung Electronics                    | 2         | 1.48%   |
| Lite-On Technology                     | 2         | 1.48%   |
| Apple                                  | 2         | 1.48%   |
| Sony                                   | 1         | 0.74%   |
| Primax Electronics                     | 1         | 0.74%   |
| Luxvisions Innotech Limited            | 1         | 0.74%   |
| GEMBIRD                                | 1         | 0.74%   |
| DigiTech                               | 1         | 0.74%   |
| Aveo Technology                        | 1         | 0.74%   |
| A4Tech                                 | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 12        | 8.89%   |
| Unknown USB Camera                                             | 5         | 3.7%    |
| Chicony HP Truevision HD                                       | 5         | 3.7%    |
| Acer Integrated Camera                                         | 5         | 3.7%    |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.96%   |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 2.96%   |
| Chicony Integrated Camera                                      | 4         | 2.96%   |
| Realtek Lenovo EasyCamera                                      | 3         | 2.22%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 2.22%   |
| Logitech Webcam C270                                           | 3         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 2.22%   |
| Syntek Integrated Camera                                       | 2         | 1.48%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.48%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 1.48%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.48%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.48%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.48%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.48%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.48%   |
| Chicony HD WebCam                                              | 2         | 1.48%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 2         | 1.48%   |
| Acer Lenovo EasyCamera                                         | 2         | 1.48%   |
| Acer HD Webcam                                                 | 2         | 1.48%   |
| Unknown HD camera                                              | 1         | 0.74%   |
| Syntek EasyCamera                                              | 1         | 0.74%   |
| Suyin HP Truevision HD                                         | 1         | 0.74%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.74%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.74%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.74%   |
| Sunplus SPCA2082 PC Camera                                     | 1         | 0.74%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.74%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.74%   |
| Sunplus HP TrueVision HD Camera                                | 1         | 0.74%   |
| Sunplus HD WebCam                                              | 1         | 0.74%   |
| Sunplus Asus Webcam                                            | 1         | 0.74%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.74%   |
| Sony CEVCECM                                                   | 1         | 0.74%   |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.74%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Elan Microelectronics      | 2         | 13.33%  |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 13.33%  |
| Elan ELAN:Fingerprint                                  | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 168       | 78.14%  |
| 1     | 43        | 20%     |
| 2     | 3         | 1.4%    |
| 3     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 27.45%  |
| Net/wireless             | 13        | 25.49%  |
| Graphics card            | 9         | 17.65%  |
| Multimedia controller    | 6         | 11.76%  |
| Chipcard                 | 2         | 3.92%   |
| Bluetooth                | 2         | 3.92%   |
| Unassigned class         | 1         | 1.96%   |
| Storage                  | 1         | 1.96%   |
| Sound                    | 1         | 1.96%   |
| Modem                    | 1         | 1.96%   |
| Communication controller | 1         | 1.96%   |


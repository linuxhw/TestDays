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

Total: 366

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| HP            | 0A60h                       | Desktop     | [f0498c1a54](https://linux-hardware.org/?probe=f0498c1a54) | Jun 07, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [624a84a2fc](https://linux-hardware.org/?probe=624a84a2fc) | Jun 06, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| HP            | Stream Notebook             | Notebook    | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| HP            | Notebook                    | Notebook    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| Dell          | Latitude 5530               | Notebook    | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [97cc4e0a84](https://linux-hardware.org/?probe=97cc4e0a84) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| HP            | 240 G4                      | Notebook    | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | 240 G4                      | Notebook    | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Standard      | SF20BA2                     | Notebook    | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| Intel         | EF20                        | Notebook    | [120257faca](https://linux-hardware.org/?probe=120257faca) | Apr 04, 2023 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [5d5eb8d675](https://linux-hardware.org/?probe=5d5eb8d675) | Apr 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [9af85c78cb](https://linux-hardware.org/?probe=9af85c78cb) | Mar 28, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [1531761af6](https://linux-hardware.org/?probe=1531761af6) | Mar 26, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Dell          | Latitude 7310               | Notebook    | [6b5de5fe3c](https://linux-hardware.org/?probe=6b5de5fe3c) | Mar 17, 2023 |
| Standard      | SF20BA                      | Notebook    | [e85dc022b5](https://linux-hardware.org/?probe=e85dc022b5) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [41bf4fb877](https://linux-hardware.org/?probe=41bf4fb877) | Mar 10, 2023 |
| AZW           | MINI S                      | Desktop     | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| Dell          | Latitude 3150               | Notebook    | [f1554a5df0](https://linux-hardware.org/?probe=f1554a5df0) | Mar 05, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| ECS           | SF20PA2                     | Notebook    | [f0ad83686f](https://linux-hardware.org/?probe=f0ad83686f) | Feb 21, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [c5256638eb](https://linux-hardware.org/?probe=c5256638eb) | Feb 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS14H00     | Notebook    | [de5c7ac3f6](https://linux-hardware.org/?probe=de5c7ac3f6) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8183bc042](https://linux-hardware.org/?probe=e8183bc042) | Feb 16, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Gateway       | LT41P                       | Notebook    | [1684d937e7](https://linux-hardware.org/?probe=1684d937e7) | Feb 02, 2023 |
| HP            | 3115-AEC13432GR1            | Notebook    | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [5d86fd4411](https://linux-hardware.org/?probe=5d86fd4411) | Jan 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [4bda80131d](https://linux-hardware.org/?probe=4bda80131d) | Jan 15, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [dc137d0d08](https://linux-hardware.org/?probe=dc137d0d08) | Jan 09, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [57c14b82bd](https://linux-hardware.org/?probe=57c14b82bd) | Nov 23, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| ECS           | SF20PA2                     | Notebook    | [2e0892ec48](https://linux-hardware.org/?probe=2e0892ec48) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e974c2ceff](https://linux-hardware.org/?probe=e974c2ceff) | Nov 12, 2022 |
| Alienware     | 14                          | Notebook    | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
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


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 37        | 13.55%  |
| Ubuntu 18.04       | 29        | 10.62%  |
| OpenMandriva 4.3   | 16        | 5.86%   |
| Manjaro            | 14        | 5.13%   |
| Ubuntu 22.04       | 9         | 3.3%    |
| KDE neon 20.04     | 8         | 2.93%   |
| OpenMandriva 4.2   | 7         | 2.56%   |
| Linux Mint 19.3    | 6         | 2.2%    |
| Arch Rolling       | 6         | 2.2%    |
| Zorin 16           | 5         | 1.83%   |
| Xubuntu 20.04      | 5         | 1.83%   |
| Ubuntu 19.04       | 5         | 1.83%   |
| OpenMandriva 23.03 | 5         | 1.83%   |
| OpenMandriva 23.01 | 5         | 1.83%   |
| Debian 11          | 5         | 1.83%   |
| Ubuntu 21.10       | 4         | 1.47%   |
| Ubuntu 18.10       | 4         | 1.47%   |
| Linux Mint 19.1    | 4         | 1.47%   |
| Fedora 36          | 4         | 1.47%   |
| Xubuntu 18.04      | 3         | 1.1%    |
| ROSA R11.1         | 3         | 1.1%    |
| Pop!_OS 22.04      | 3         | 1.1%    |
| Linux Mint 20      | 3         | 1.1%    |
| BlackPanther 18.1  | 3         | 1.1%    |
| ArcoLinux Rolling  | 3         | 1.1%    |
| Arch               | 3         | 1.1%    |
| Zorin 15           | 2         | 0.73%   |
| Ubuntu 21.04       | 2         | 0.73%   |
| Ubuntu 19.10       | 2         | 0.73%   |
| Pop!_OS 20.04      | 2         | 0.73%   |
| OpenMandriva 4.50  | 2         | 0.73%   |
| Linux Mint 21.1    | 2         | 0.73%   |
| Linux Mint 21      | 2         | 0.73%   |
| Linux Mint 20.3    | 2         | 0.73%   |
| Linux Mint 20.2    | 2         | 0.73%   |
| Linux Mint 20.1    | 2         | 0.73%   |
| Linux Mint 19.2    | 2         | 0.73%   |
| Kubuntu 18.04      | 2         | 0.73%   |
| Fedora 37          | 2         | 0.73%   |
| Fedora 35          | 2         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 92        | 34.72%  |
| OpenMandriva | 33        | 12.45%  |
| Linux Mint   | 26        | 9.81%   |
| Manjaro      | 15        | 5.66%   |
| Fedora       | 13        | 4.91%   |
| Xubuntu      | 9         | 3.4%    |
| KDE neon     | 9         | 3.4%    |
| Arch         | 8         | 3.02%   |
| Zorin        | 7         | 2.64%   |
| Debian       | 7         | 2.64%   |
| Pop!_OS      | 6         | 2.26%   |
| Endless      | 5         | 1.89%   |
| Lubuntu      | 4         | 1.51%   |
| Kubuntu      | 4         | 1.51%   |
| ArcoLinux    | 4         | 1.51%   |
| ROSA         | 3         | 1.13%   |
| BlackPanther | 3         | 1.13%   |
| openSUSE     | 2         | 0.75%   |
| Elementary   | 2         | 0.75%   |
| Android      | 2         | 0.75%   |
| Void Linux   | 1         | 0.38%   |
| Ubuntu MATE  | 1         | 0.38%   |
| SteamOS      | 1         | 0.38%   |
| NixOS        | 1         | 0.38%   |
| MX           | 1         | 0.38%   |
| LMDE         | 1         | 0.38%   |
| LinuxFX      | 1         | 0.38%   |
| Gentoo       | 1         | 0.38%   |
| Feren OS     | 1         | 0.38%   |
| EndeavourOS  | 1         | 0.38%   |
| antiX        | 1         | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003     | 15        | 5.15%   |
| 5.10.14-desktop-1omv4002    | 7         | 2.41%   |
| 5.4.0-42-generic            | 6         | 2.06%   |
| 4.16.18-pa2-2bp1            | 6         | 2.06%   |
| 6.2.6-desktop-1omv2390      | 5         | 1.72%   |
| 6.1.1-desktop-1omv2290      | 5         | 1.72%   |
| 5.11.0-38-generic           | 5         | 1.72%   |
| 4.16.18-pa2-1bp5            | 5         | 1.72%   |
| 5.8.0-53-generic            | 4         | 1.37%   |
| 5.5.19-bp0                  | 4         | 1.37%   |
| 5.4.0-52-generic            | 4         | 1.37%   |
| 5.3.0-46-generic            | 4         | 1.37%   |
| 5.13.0-39-generic           | 4         | 1.37%   |
| 5.4.0-73-generic            | 3         | 1.03%   |
| 5.4.0-72-generic            | 3         | 1.03%   |
| 5.4.0-65-generic            | 3         | 1.03%   |
| 5.4.0-58-generic            | 3         | 1.03%   |
| 5.15.0-67-generic           | 3         | 1.03%   |
| 5.15.0-46-generic           | 3         | 1.03%   |
| 5.10.0-21-amd64             | 3         | 1.03%   |
| 5.0.0-32-generic            | 3         | 1.03%   |
| 4.18.16-desktop-1bP         | 3         | 1.03%   |
| 6.1.26-1-MANJARO            | 2         | 0.69%   |
| 5.8.0-50-generic            | 2         | 0.69%   |
| 5.8.0-43-generic            | 2         | 0.69%   |
| 5.4.83-generic-2rosa-x86_64 | 2         | 0.69%   |
| 5.4.0-62-generic            | 2         | 0.69%   |
| 5.4.0-39-generic            | 2         | 0.69%   |
| 5.3.0-51-generic            | 2         | 0.69%   |
| 5.3.0-28-generic            | 2         | 0.69%   |
| 5.19.0-41-generic           | 2         | 0.69%   |
| 5.19.0-35-generic           | 2         | 0.69%   |
| 5.17.5-76051705-generic     | 2         | 0.69%   |
| 5.16.13-desktop-1omv4003    | 2         | 0.69%   |
| 5.15.60-1-MANJARO           | 2         | 0.69%   |
| 5.15.0-48-generic           | 2         | 0.69%   |
| 5.15.0-41-generic           | 2         | 0.69%   |
| 5.13.0-44-generic           | 2         | 0.69%   |
| 5.13.0-40-generic           | 2         | 0.69%   |
| 5.13.0-37-generic           | 2         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 14.13%  |
| 4.15.0  | 20        | 7.07%   |
| 5.15.0  | 16        | 5.65%   |
| 5.16.7  | 15        | 5.3%    |
| 5.13.0  | 15        | 5.3%    |
| 5.8.0   | 12        | 4.24%   |
| 5.11.0  | 12        | 4.24%   |
| 5.3.0   | 11        | 3.89%   |
| 4.16.18 | 11        | 3.89%   |
| 5.0.0   | 10        | 3.53%   |
| 4.18.0  | 8         | 2.83%   |
| 5.10.14 | 7         | 2.47%   |
| 5.10.0  | 6         | 2.12%   |
| 6.2.6   | 5         | 1.77%   |
| 6.1.1   | 5         | 1.77%   |
| 5.19.0  | 5         | 1.77%   |
| 5.5.19  | 4         | 1.41%   |
| 5.17.5  | 3         | 1.06%   |
| 4.18.16 | 3         | 1.06%   |
| 6.3.4   | 2         | 0.71%   |
| 6.2.12  | 2         | 0.71%   |
| 6.1.26  | 2         | 0.71%   |
| 6.1.11  | 2         | 0.71%   |
| 5.4.83  | 2         | 0.71%   |
| 5.19.12 | 2         | 0.71%   |
| 5.18.12 | 2         | 0.71%   |
| 5.16.13 | 2         | 0.71%   |
| 5.15.60 | 2         | 0.71%   |
| 5.11.12 | 2         | 0.71%   |
| 6.2.0   | 1         | 0.35%   |
| 6.1.31  | 1         | 0.35%   |
| 6.1.29  | 1         | 0.35%   |
| 6.1.18  | 1         | 0.35%   |
| 6.1.0   | 1         | 0.35%   |
| 6.0.6   | 1         | 0.35%   |
| 6.0.18  | 1         | 0.35%   |
| 6.0.15  | 1         | 0.35%   |
| 6.0.12  | 1         | 0.35%   |
| 6.0.0   | 1         | 0.35%   |
| 5.8.11  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 44        | 15.66%  |
| 5.15    | 22        | 7.83%   |
| 4.15    | 20        | 7.12%   |
| 5.16    | 19        | 6.76%   |
| 5.11    | 18        | 6.41%   |
| 5.10    | 17        | 6.05%   |
| 5.13    | 16        | 5.69%   |
| 5.8     | 14        | 4.98%   |
| 6.1     | 13        | 4.63%   |
| 5.3     | 12        | 4.27%   |
| 4.16    | 12        | 4.27%   |
| 4.18    | 11        | 3.91%   |
| 5.0     | 10        | 3.56%   |
| 6.2     | 8         | 2.85%   |
| 5.19    | 8         | 2.85%   |
| 5.17    | 6         | 2.14%   |
| 5.18    | 5         | 1.78%   |
| 6.0     | 4         | 1.42%   |
| 5.5     | 4         | 1.42%   |
| 5.12    | 4         | 1.42%   |
| 6.3     | 2         | 0.71%   |
| 5.6     | 2         | 0.71%   |
| 5.14    | 2         | 0.71%   |
| 4.9     | 2         | 0.71%   |
| 5.2     | 1         | 0.36%   |
| 4.8     | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |
| 4.17    | 1         | 0.36%   |
| 4.13    | 1         | 0.36%   |
| 4.12    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 249       | 97.27%  |
| i686   | 5         | 1.95%   |
| armv8l | 2         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 86        | 32.58%  |
| KDE5            | 59        | 22.35%  |
| Unknown         | 36        | 13.64%  |
| XFCE            | 23        | 8.71%   |
| X-Cinnamon      | 18        | 6.82%   |
| GNOME Flashback | 13        | 4.92%   |
| KDE             | 7         | 2.65%   |
| MATE            | 5         | 1.89%   |
| LXQt            | 3         | 1.14%   |
| LXDE            | 3         | 1.14%   |
| Cinnamon        | 3         | 1.14%   |
| Pantheon        | 2         | 0.76%   |
| KDE4            | 2         | 0.76%   |
| sway            | 1         | 0.38%   |
| qtile           | 1         | 0.38%   |
| LeftWM          | 1         | 0.38%   |
| ICEWM           | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 209       | 80.08%  |
| Wayland | 32        | 12.26%  |
| Unknown | 17        | 6.51%   |
| Tty     | 3         | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 133       | 50.76%  |
| SDDM    | 53        | 20.23%  |
| GDM     | 29        | 11.07%  |
| LightDM | 21        | 8.02%   |
| GDM3    | 18        | 6.87%   |
| TDM     | 4         | 1.53%   |
| KDM     | 2         | 0.76%   |
| XDM     | 1         | 0.38%   |
| GREETD  | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_UY      | 133       | 49.81%  |
| en_US      | 55        | 20.6%   |
| Unknown    | 31        | 11.61%  |
| es_ES      | 26        | 9.74%   |
| es_AR      | 6         | 2.25%   |
| C          | 6         | 2.25%   |
| es_MX      | 5         | 1.87%   |
| pt_BR      | 1         | 0.37%   |
| POSIX      | 1         | 0.37%   |
| es_UY.UTF8 | 1         | 0.37%   |
| en_GB      | 1         | 0.37%   |
| en_CA      | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 138       | 52.87%  |
| EFI  | 123       | 47.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 202       | 77.1%   |
| Overlay | 34        | 12.98%  |
| Btrfs   | 11        | 4.2%    |
| Unknown | 8         | 3.05%   |
| Tmpfs   | 4         | 1.53%   |
| Xfs     | 2         | 0.76%   |
| Ext3    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 56.7%   |
| GPT     | 82        | 31.42%  |
| MBR     | 31        | 11.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 79.77%  |
| Yes       | 52        | 20.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 182       | 70.27%  |
| Yes       | 77        | 29.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 43        | 16.8%   |
| Lenovo              | 32        | 12.5%   |
| ASUSTek Computer    | 28        | 10.94%  |
| Dell                | 19        | 7.42%   |
| Gigabyte Technology | 18        | 7.03%   |
| ASRock              | 18        | 7.03%   |
| MSI                 | 17        | 6.64%   |
| ECS                 | 17        | 6.64%   |
| Acer                | 13        | 5.08%   |
| Toshiba             | 9         | 3.52%   |
| Standard            | 5         | 1.95%   |
| Samsung Electronics | 4         | 1.56%   |
| Intel               | 4         | 1.56%   |
| Gateway             | 3         | 1.17%   |
| Biostar             | 3         | 1.17%   |
| Apple               | 3         | 1.17%   |
| Unknown             | 3         | 1.17%   |
| GPU Company         | 2         | 0.78%   |
| Fujitsu             | 2         | 0.78%   |
| Valve               | 1         | 0.39%   |
| Supermicro          | 1         | 0.39%   |
| Sony                | 1         | 0.39%   |
| Positivo            | 1         | 0.39%   |
| Panasonic           | 1         | 0.39%   |
| OEM                 | 1         | 0.39%   |
| MACHINIST           | 1         | 0.39%   |
| iClever             | 1         | 0.39%   |
| Huanan              | 1         | 0.39%   |
| Haitech             | 1         | 0.39%   |
| Foxconn             | 1         | 0.39%   |
| AZW                 | 1         | 0.39%   |
| Alienware           | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ECS SF20PA2                                | 16        | 6.25%   |
| Standard SF20BA2                           | 3         | 1.17%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL0014LD | 3         | 1.17%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 3         | 1.17%   |
| Unknown                                    | 3         | 1.17%   |
| Toshiba Satellite L55t-B                   | 2         | 0.78%   |
| MSI MS-7C37                                | 2         | 0.78%   |
| MSI MS-7721                                | 2         | 0.78%   |
| HP Pavilion 15                             | 2         | 0.78%   |
| HP Notebook                                | 2         | 0.78%   |
| HP Laptop 15-bs0xx                         | 2         | 0.78%   |
| Gigabyte Z390 AORUS ELITE                  | 2         | 0.78%   |
| Gigabyte H61M-S1                           | 2         | 0.78%   |
| ASRock N68-S                               | 2         | 0.78%   |
| ASRock H310CM-HDV                          | 2         | 0.78%   |
| ASRock FM2A58M-VG3+ R2.0                   | 2         | 0.78%   |
| ASRock ALiveNF6P-VSTA                      | 2         | 0.78%   |
| Valve Jupiter                              | 1         | 0.39%   |
| Toshiba Satellite L45-B                    | 1         | 0.39%   |
| Toshiba Satellite C855                     | 1         | 0.39%   |
| Toshiba Satellite C75D-C                   | 1         | 0.39%   |
| Toshiba Satellite C75D-B                   | 1         | 0.39%   |
| Toshiba Satellite C645D                    | 1         | 0.39%   |
| Toshiba Satellite C55-B                    | 1         | 0.39%   |
| Toshiba Satellite C45-A                    | 1         | 0.39%   |
| Supermicro P4DMS                           | 1         | 0.39%   |
| Standard SF20BA                            | 1         | 0.39%   |
| Standard EF20EA                            | 1         | 0.39%   |
| Sony SVF14211CLB                           | 1         | 0.39%   |
| Samsung NC208/NC108                        | 1         | 0.39%   |
| Samsung N102SP/N100SP/N101SP               | 1         | 0.39%   |
| Samsung 700T                               | 1         | 0.39%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.39%   |
| Positivo Serie AT300                       | 1         | 0.39%   |
| Panasonic CF-31JEGAX1M                     | 1         | 0.39%   |
| OEM V40SI2                                 | 1         | 0.39%   |
| MSI Pro 3130 Microtower PC                 | 1         | 0.39%   |
| MSI MS-7C09                                | 1         | 0.39%   |
| MSI MS-7817                                | 1         | 0.39%   |
| MSI MS-7816                                | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ECS SF20PA2           | 16        | 6.25%   |
| Lenovo ThinkPad       | 12        | 4.69%   |
| Toshiba Satellite     | 9         | 3.52%   |
| Acer Aspire           | 9         | 3.52%   |
| HP Pavilion           | 8         | 3.13%   |
| HP Laptop             | 8         | 3.13%   |
| Dell Inspiron         | 7         | 2.73%   |
| Lenovo IdeaPad        | 6         | 2.34%   |
| HP Compaq             | 6         | 2.34%   |
| Dell Latitude         | 5         | 1.95%   |
| ASUS ROG              | 5         | 1.95%   |
| Lenovo ThinkCentre    | 4         | 1.56%   |
| Standard SF20BA2      | 3         | 1.17%   |
| Lenovo IdeaCentre     | 3         | 1.17%   |
| Dell OptiPlex         | 3         | 1.17%   |
| ASUS VivoBook         | 3         | 1.17%   |
| ASUS PRIME            | 3         | 1.17%   |
| Unknown               | 3         | 1.17%   |
| MSI MS-7C37           | 2         | 0.78%   |
| MSI MS-7721           | 2         | 0.78%   |
| HP Stream             | 2         | 0.78%   |
| HP Notebook           | 2         | 0.78%   |
| HP ENVY               | 2         | 0.78%   |
| HP EliteDesk          | 2         | 0.78%   |
| HP EliteBook          | 2         | 0.78%   |
| HP 240                | 2         | 0.78%   |
| Gigabyte Z390         | 2         | 0.78%   |
| Gigabyte H61M-S1      | 2         | 0.78%   |
| Dell XPS              | 2         | 0.78%   |
| ASUS TUF              | 2         | 0.78%   |
| ASRock N68-S          | 2         | 0.78%   |
| ASRock H310CM-HDV     | 2         | 0.78%   |
| ASRock FM2A58M-VG3+   | 2         | 0.78%   |
| ASRock ALiveNF6P-VSTA | 2         | 0.78%   |
| ASRock A320M-HDV      | 2         | 0.78%   |
| Acer TravelMate       | 2         | 0.78%   |
| Valve Jupiter         | 1         | 0.39%   |
| Supermicro P4DMS      | 1         | 0.39%   |
| Standard SF20BA       | 1         | 0.39%   |
| Standard EF20EA       | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 32        | 12.5%   |
| 2019    | 26        | 10.16%  |
| 2013    | 23        | 8.98%   |
| 2011    | 23        | 8.98%   |
| 2015    | 19        | 7.42%   |
| 2018    | 18        | 7.03%   |
| 2012    | 18        | 7.03%   |
| 2020    | 17        | 6.64%   |
| 2014    | 17        | 6.64%   |
| 2016    | 16        | 6.25%   |
| 2021    | 8         | 3.13%   |
| 2010    | 8         | 3.13%   |
| 2022    | 7         | 2.73%   |
| 2009    | 7         | 2.73%   |
| 2007    | 7         | 2.73%   |
| 2008    | 4         | 1.56%   |
| Unknown | 2         | 0.78%   |
| 2006    | 1         | 0.39%   |
| 2005    | 1         | 0.39%   |
| 2004    | 1         | 0.39%   |
| 2003    | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 151       | 58.98%  |
| Desktop     | 94        | 36.72%  |
| Mini pc     | 3         | 1.17%   |
| All in one  | 3         | 1.17%   |
| Phone       | 2         | 0.78%   |
| Convertible | 2         | 0.78%   |
| Tablet      | 1         | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 241       | 93.77%  |
| Enabled  | 16        | 6.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 256       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 24.14%  |
| 3.01-4.0    | 57        | 21.84%  |
| 8.01-16.0   | 42        | 16.09%  |
| 16.01-24.0  | 34        | 13.03%  |
| 1.01-2.0    | 33        | 12.64%  |
| 32.01-64.0  | 15        | 5.75%   |
| 24.01-32.0  | 8         | 3.07%   |
| 64.01-256.0 | 4         | 1.53%   |
| 2.01-3.0    | 2         | 0.77%   |
| 0.01-0.5    | 2         | 0.77%   |
| 0.51-1.0    | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 117       | 42.24%  |
| 2.01-3.0  | 66        | 23.83%  |
| 3.01-4.0  | 31        | 11.19%  |
| 4.01-8.0  | 27        | 9.75%   |
| 0.51-1.0  | 20        | 7.22%   |
| 8.01-16.0 | 10        | 3.61%   |
| 0.01-0.5  | 6         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 179       | 68.85%  |
| 2      | 54        | 20.77%  |
| 3      | 13        | 5%      |
| 4      | 10        | 3.85%   |
| 5      | 2         | 0.77%   |
| 0      | 2         | 0.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 63.18%  |
| Yes       | 95        | 36.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 76.56%  |
| No        | 60        | 23.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 75.19%  |
| No        | 64        | 24.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 56.64%  |
| No        | 111       | 43.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Uruguay | 256       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Montevideo             | 195       | 72.49%  |
| Maldonado              | 13        | 4.83%   |
| Canelones              | 8         | 2.97%   |
| San Jose de Mayo       | 4         | 1.49%   |
| Punta del Este         | 4         | 1.49%   |
| Las Piedras            | 4         | 1.49%   |
| Florida                | 3         | 1.12%   |
| Ciudad del Plata       | 3         | 1.12%   |
| Buceo                  | 3         | 1.12%   |
| Salto                  | 2         | 0.74%   |
| Rocha                  | 2         | 0.74%   |
| Punta Gorda            | 2         | 0.74%   |
| Parque Rodo            | 2         | 0.74%   |
| Nueva Helvecia         | 2         | 0.74%   |
| La Paz                 | 2         | 0.74%   |
| Durazno                | 2         | 0.74%   |
| Centro                 | 2         | 0.74%   |
| Solymar                | 1         | 0.37%   |
| Pinamar                | 1         | 0.37%   |
| Paysandú              | 1         | 0.37%   |
| Nuevo Paris            | 1         | 0.37%   |
| Melo                   | 1         | 0.37%   |
| Melilla                | 1         | 0.37%   |
| Maronas                | 1         | 0.37%   |
| Malvin Norte           | 1         | 0.37%   |
| Las Flores             | 1         | 0.37%   |
| La Barra               | 1         | 0.37%   |
| Joaquin Suarez         | 1         | 0.37%   |
| El Tesoro              | 1         | 0.37%   |
| El Pinar               | 1         | 0.37%   |
| Barrancas Coloradas    | 1         | 0.37%   |
| Arenas de Jose Ignacio | 1         | 0.37%   |
| Unknown                | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 72        | 91     | 20.99%  |
| Seagate                     | 47        | 60     | 13.7%   |
| Kingston                    | 44        | 54     | 12.83%  |
| Toshiba                     | 37        | 47     | 10.79%  |
| Samsung Electronics         | 30        | 31     | 8.75%   |
| Unknown                     | 27        | 34     | 7.87%   |
| SanDisk                     | 14        | 17     | 4.08%   |
| Hitachi                     | 9         | 14     | 2.62%   |
| Crucial                     | 8         | 12     | 2.33%   |
| SK hynix                    | 7         | 7      | 2.04%   |
| HGST                        | 7         | 7      | 2.04%   |
| Hewlett-Packard             | 5         | 5      | 1.46%   |
| Intel                       | 4         | 4      | 1.17%   |
| Netac                       | 3         | 4      | 0.87%   |
| Micron/Crucial Technology   | 2         | 3      | 0.58%   |
| Micron Technology           | 2         | 2      | 0.58%   |
| Maxtor                      | 2         | 3      | 0.58%   |
| Kingston Technology Company | 2         | 2      | 0.58%   |
| Biostar                     | 2         | 3      | 0.58%   |
| W800SH                      | 1         | 1      | 0.29%   |
| Silicon Motion              | 1         | 1      | 0.29%   |
| SAGE                        | 1         | 1      | 0.29%   |
| Phison                      | 1         | 1      | 0.29%   |
| Patriot                     | 1         | 1      | 0.29%   |
| NGFF                        | 1         | 1      | 0.29%   |
| LITEON                      | 1         | 2      | 0.29%   |
| KIOXIA                      | 1         | 1      | 0.29%   |
| KingFast                    | 1         | 1      | 0.29%   |
| IBM-ESXS                    | 1         | 1      | 0.29%   |
| HS-SSD-C100                 | 1         | 1      | 0.29%   |
| Gigabyte Technology         | 1         | 1      | 0.29%   |
| ExcelStor                   | 1         | 1      | 0.29%   |
| Dahua                       | 1         | 2      | 0.29%   |
| China                       | 1         | 1      | 0.29%   |
| BIWIN                       | 1         | 1      | 0.29%   |
| BHT                         | 1         | 1      | 0.29%   |
| Apple                       | 1         | 1      | 0.29%   |
| A-DATA Technology           | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 14        | 3.85%   |
| Kingston SA400S37240G 240GB SSD     | 14        | 3.85%   |
| Kingston SA400S37480G 480GB SSD     | 7         | 1.92%   |
| Toshiba DT01ACA300 3TB              | 6         | 1.65%   |
| Seagate ST1000LM035-1RK172 1TB      | 6         | 1.65%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 1.37%   |
| Unknown DA4032  32GB                | 5         | 1.37%   |
| Toshiba MQ01ABD075 752GB            | 5         | 1.37%   |
| Toshiba DT01ACA100 1TB              | 5         | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 1.37%   |
| Samsung HD161HJ 160GB               | 5         | 1.37%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 1.1%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 1.1%    |
| Kingston SV300S37A120G 120GB SSD    | 4         | 1.1%    |
| Kingston SA400S37120G 120GB SSD     | 4         | 1.1%    |
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 0.82%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.82%   |
| Toshiba HDWK105 500GB               | 3         | 0.82%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.82%   |
| SanDisk DF4032  32GB                | 3         | 0.82%   |
| Kingston SV300S37A480G 480GB SSD    | 3         | 0.82%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2         | 0.55%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.55%   |
| WDC WD5000LPVT-24G33T1 500GB        | 2         | 0.55%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.55%   |
| WDC WD10EFRX-68FYTN0 1TB            | 2         | 0.55%   |
| Unknown SD/MMC/MS PRO 64GB          | 2         | 0.55%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.55%   |
| Toshiba MK5059GSXP 500GB            | 2         | 0.55%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 0.55%   |
| Seagate ST3750640NS 752GB           | 2         | 0.55%   |
| Seagate ST3250312AS 250GB           | 2         | 0.55%   |
| Seagate ST3160318AS 160GB           | 2         | 0.55%   |
| Seagate ST250DM000-1BD141 250GB     | 2         | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 0.55%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.55%   |
| SanDisk NVMe SSD Drive 1024GB       | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 60        | 76     | 33.9%   |
| Seagate             | 47        | 60     | 26.55%  |
| Toshiba             | 33        | 43     | 18.64%  |
| Samsung Electronics | 15        | 15     | 8.47%   |
| Hitachi             | 9         | 14     | 5.08%   |
| HGST                | 7         | 7      | 3.95%   |
| Unknown             | 2         | 2      | 1.13%   |
| Maxtor              | 2         | 3      | 1.13%   |
| SAGE                | 1         | 1      | 0.56%   |
| ExcelStor           | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 36        | 42     | 42.35%  |
| WDC                 | 9         | 9      | 10.59%  |
| Samsung Electronics | 8         | 9      | 9.41%   |
| Crucial             | 6         | 8      | 7.06%   |
| SanDisk             | 4         | 4      | 4.71%   |
| Hewlett-Packard     | 4         | 4      | 4.71%   |
| Netac               | 3         | 4      | 3.53%   |
| SK hynix            | 2         | 2      | 2.35%   |
| Intel               | 2         | 2      | 2.35%   |
| W800SH              | 1         | 1      | 1.18%   |
| Toshiba             | 1         | 1      | 1.18%   |
| NGFF                | 1         | 1      | 1.18%   |
| Micron Technology   | 1         | 1      | 1.18%   |
| Gigabyte Technology | 1         | 1      | 1.18%   |
| Dahua               | 1         | 2      | 1.18%   |
| China               | 1         | 1      | 1.18%   |
| BIWIN               | 1         | 1      | 1.18%   |
| Biostar             | 1         | 2      | 1.18%   |
| BHT                 | 1         | 1      | 1.18%   |
| A-DATA Technology   | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 146       | 222    | 47.25%  |
| SSD     | 83        | 97     | 26.86%  |
| NVMe    | 47        | 61     | 15.21%  |
| MMC     | 29        | 37     | 9.39%   |
| Unknown | 4         | 4      | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 195       | 317    | 70.4%   |
| NVMe | 47        | 61     | 16.97%  |
| MMC  | 29        | 37     | 10.47%  |
| SAS  | 6         | 6      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 148       | 196    | 64.07%  |
| 0.51-1.0   | 68        | 106    | 29.44%  |
| 2.01-3.0   | 7         | 8      | 3.03%   |
| 1.01-2.0   | 6         | 6      | 2.6%    |
| 3.01-4.0   | 2         | 3      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 23.22%  |
| 251-500        | 61        | 22.85%  |
| 501-1000       | 37        | 13.86%  |
| 1-20           | 32        | 11.99%  |
| 21-50          | 28        | 10.49%  |
| 1001-2000      | 16        | 5.99%   |
| 51-100         | 12        | 4.49%   |
| Unknown        | 11        | 4.12%   |
| More than 3000 | 4         | 1.5%    |
| 2001-3000      | 4         | 1.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 122       | 44.36%  |
| 21-50          | 47        | 17.09%  |
| 51-100         | 28        | 10.18%  |
| 251-500        | 23        | 8.36%   |
| 101-250        | 21        | 7.64%   |
| 501-1000       | 14        | 5.09%   |
| Unknown        | 11        | 4%      |
| 1001-2000      | 5         | 1.82%   |
| More than 3000 | 2         | 0.73%   |
| 2001-3000      | 2         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 3      | 9.09%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 6.06%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 6.06%   |
| Seagate ST3750640NS 752GB           | 2         | 7      | 6.06%   |
| Seagate ST250DM000-1BD141 250GB     | 2         | 2      | 6.06%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 3.03%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 1      | 3.03%   |
| WDC WD5000AAJS-00A8B0 500GB         | 1         | 1      | 3.03%   |
| WDC WD3200BEVT-26ZCT0 320GB         | 1         | 1      | 3.03%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 3.03%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 3.03%   |
| Toshiba MK3276GSX 320GB             | 1         | 1      | 3.03%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 3.03%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 3.03%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 3.03%   |
| Seagate ST980811AS 80GB             | 1         | 2      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 3.03%   |
| Seagate ST500DM005 HD502HJ 500GB    | 1         | 1      | 3.03%   |
| Seagate ST3250310CS 250GB           | 1         | 1      | 3.03%   |
| Seagate ST3200827AS 200GB           | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 3.03%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1      | 3.03%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 3.03%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 3.03%   |
| HGST HTS545032A7E380 320GB          | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 20     | 41.94%  |
| WDC     | 8         | 9      | 25.81%  |
| Toshiba | 7         | 8      | 22.58%  |
| SanDisk | 1         | 1      | 3.23%   |
| Hitachi | 1         | 1      | 3.23%   |
| HGST    | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 20     | 43.33%  |
| WDC     | 8         | 9      | 26.67%  |
| Toshiba | 7         | 8      | 23.33%  |
| Hitachi | 1         | 1      | 3.33%   |
| HGST    | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 39     | 96.77%  |
| SSD  | 1         | 1      | 3.23%   |

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
| Detected | 162       | 253    | 60%     |
| Works    | 77        | 128    | 28.52%  |
| Malfunc  | 31        | 40     | 11.48%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 163       | 56.79%  |
| AMD                              | 60        | 20.91%  |
| SanDisk                          | 13        | 4.53%   |
| Kingston Technology Company      | 9         | 3.14%   |
| Samsung Electronics              | 7         | 2.44%   |
| Nvidia                           | 6         | 2.09%   |
| ASMedia Technology               | 5         | 1.74%   |
| Toshiba America Info Systems     | 4         | 1.39%   |
| SK hynix                         | 4         | 1.39%   |
| Micron/Crucial Technology        | 4         | 1.39%   |
| Silicon Motion                   | 3         | 1.05%   |
| Marvell Technology Group         | 2         | 0.7%    |
| VIA Technologies                 | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Phison Electronics               | 1         | 0.35%   |
| Micron Technology                | 1         | 0.35%   |
| Lite-On Technology               | 1         | 0.35%   |
| Apple                            | 1         | 0.35%   |
| Adaptec                          | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43        | 12.87%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 20        | 5.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 2.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8         | 2.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 2.4%    |
| Nvidia MCP61 SATA Controller                                                            | 6         | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.8%    |
| Nvidia MCP61 IDE                                                                        | 5         | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.5%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.5%    |
| AMD FCH IDE Controller                                                                  | 5         | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.2%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.9%    |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.9%    |
| AMD FCH SATA Controller D                                                               | 3         | 0.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 196       | 65.99%  |
| NVMe | 47        | 15.82%  |
| IDE  | 42        | 14.14%  |
| RAID | 11        | 3.7%    |
| SCSI | 1         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 180       | 70.31%  |
| AMD      | 74        | 28.91%  |
| QUALCOMM | 1         | 0.39%   |
| ARM      | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 6.64%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 4         | 1.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 1.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 1.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 3         | 1.17%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 3         | 1.17%   |
| Intel Celeron CPU J3355 @ 2.00GHz            | 3         | 1.17%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 3         | 1.17%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 1.17%   |
| AMD Ryzen 5 1600 Six-Core Processor          | 3         | 1.17%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 1.17%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 2         | 0.78%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 0.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 2         | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 2         | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 0.78%   |
| Intel Core i5-8400 CPU @ 2.80GHz             | 2         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 0.78%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 0.78%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 2         | 0.78%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 2         | 0.78%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 0.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 0.78%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 0.78%   |
| Intel 12th Gen Core i7-1255U                 | 2         | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics       | 2         | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2         | 0.78%   |
| AMD Phenom II X6 1055T Processor             | 2         | 0.78%   |
| AMD Athlon II X2 250 Processor               | 2         | 0.78%   |
| AMD Athlon 3000G with Radeon Vega Graphics   | 2         | 0.78%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 0.78%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 42        | 16.41%  |
| Intel Celeron      | 39        | 15.23%  |
| Intel Core i7      | 37        | 14.45%  |
| Intel Core i3      | 24        | 9.38%   |
| AMD Ryzen 5        | 9         | 3.52%   |
| Intel Pentium      | 8         | 3.13%   |
| Intel Core 2 Duo   | 8         | 3.13%   |
| AMD Ryzen 7        | 8         | 3.13%   |
| AMD A6             | 8         | 3.13%   |
| Other              | 7         | 2.73%   |
| Intel Atom         | 7         | 2.73%   |
| AMD Athlon II X2   | 5         | 1.95%   |
| AMD Ryzen 9        | 4         | 1.56%   |
| AMD Ryzen 3        | 4         | 1.56%   |
| AMD FX             | 4         | 1.56%   |
| AMD A10            | 4         | 1.56%   |
| Intel Xeon         | 3         | 1.17%   |
| Intel Core 2 Quad  | 3         | 1.17%   |
| AMD Phenom II X6   | 3         | 1.17%   |
| AMD E              | 3         | 1.17%   |
| AMD Athlon         | 3         | 1.17%   |
| AMD A8             | 3         | 1.17%   |
| AMD A4             | 3         | 1.17%   |
| Intel Genuine      | 2         | 0.78%   |
| AMD E1             | 2         | 0.78%   |
| QUALCOMM AArch64   | 1         | 0.39%   |
| Intel Pentium Dual | 1         | 0.39%   |
| Intel Pentium 4    | 1         | 0.39%   |
| Intel Core i9      | 1         | 0.39%   |
| ARM AArch64        | 1         | 0.39%   |
| AMD Ryzen 5 PRO    | 1         | 0.39%   |
| AMD PRO A10        | 1         | 0.39%   |
| AMD Phenom II      | 1         | 0.39%   |
| AMD Phenom         | 1         | 0.39%   |
| AMD E2             | 1         | 0.39%   |
| AMD Athlon II      | 1         | 0.39%   |
| AMD Athlon 64 X2   | 1         | 0.39%   |
| AMD Athlon 64      | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 132       | 51.56%  |
| 4      | 72        | 28.13%  |
| 6      | 25        | 9.77%   |
| 8      | 17        | 6.64%   |
| 1      | 8         | 3.13%   |
| 10     | 2         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 253       | 98.83%  |
| 2      | 3         | 1.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 140       | 54.69%  |
| 1      | 116       | 45.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 249       | 97.27%  |
| Unknown        | 5         | 1.95%   |
| 32-bit         | 2         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 25%     |
| 0x206a7    | 13        | 4.92%   |
| 0x306c3    | 9         | 3.41%   |
| 0x506c9    | 8         | 3.03%   |
| 0x406c4    | 8         | 3.03%   |
| 0x306a9    | 8         | 3.03%   |
| 0x906ea    | 7         | 2.65%   |
| 0x20655    | 7         | 2.65%   |
| 0x40651    | 6         | 2.27%   |
| 0x1067a    | 6         | 2.27%   |
| 0x806ec    | 5         | 1.89%   |
| 0x806e9    | 5         | 1.89%   |
| 0x406e3    | 5         | 1.89%   |
| 0x406c3    | 5         | 1.89%   |
| 0x306d4    | 5         | 1.89%   |
| 0x08108109 | 5         | 1.89%   |
| 0x806ea    | 4         | 1.52%   |
| 0x6fd      | 4         | 1.52%   |
| 0x506e3    | 4         | 1.52%   |
| 0x30678    | 4         | 1.52%   |
| 0x08701021 | 4         | 1.52%   |
| 0x0a50000c | 3         | 1.14%   |
| 0x06006705 | 3         | 1.14%   |
| 0x06001119 | 3         | 1.14%   |
| 0x06000852 | 3         | 1.14%   |
| 0xa0655    | 2         | 0.76%   |
| 0xa0653    | 2         | 0.76%   |
| 0x906eb    | 2         | 0.76%   |
| 0x806c1    | 2         | 0.76%   |
| 0x706e5    | 2         | 0.76%   |
| 0x206d7    | 2         | 0.76%   |
| 0x10676    | 2         | 0.76%   |
| 0x08600104 | 2         | 0.76%   |
| 0x0810100b | 2         | 0.76%   |
| 0x08001138 | 2         | 0.76%   |
| 0x07030105 | 2         | 0.76%   |
| 0x07030104 | 2         | 0.76%   |
| 0x0700010f | 2         | 0.76%   |
| 0x0600611a | 2         | 0.76%   |
| 0x06003106 | 2         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 10.94%  |
| Silvermont    | 21        | 8.2%    |
| Goldmont      | 20        | 7.81%   |
| SandyBridge   | 17        | 6.64%   |
| Haswell       | 17        | 6.64%   |
| IvyBridge     | 16        | 6.25%   |
| Skylake       | 12        | 4.69%   |
| K10           | 11        | 4.3%    |
| Zen+          | 9         | 3.52%   |
| Zen 2         | 9         | 3.52%   |
| Penryn        | 9         | 3.52%   |
| Westmere      | 7         | 2.73%   |
| Piledriver    | 7         | 2.73%   |
| Excavator     | 7         | 2.73%   |
| CometLake     | 7         | 2.73%   |
| Broadwell     | 7         | 2.73%   |
| Zen 3         | 6         | 2.34%   |
| Puma          | 6         | 2.34%   |
| Core          | 6         | 2.34%   |
| Zen           | 5         | 1.95%   |
| Unknown       | 5         | 1.95%   |
| Steamroller   | 4         | 1.56%   |
| Jaguar        | 3         | 1.17%   |
| Bobcat        | 3         | 1.17%   |
| TigerLake     | 2         | 0.78%   |
| NetBurst      | 2         | 0.78%   |
| K8 Hammer     | 2         | 0.78%   |
| IceLake       | 2         | 0.78%   |
| Bonnell       | 2         | 0.78%   |
| Tremont       | 1         | 0.39%   |
| Nehalem       | 1         | 0.39%   |
| K10 Llano     | 1         | 0.39%   |
| Goldmont plus | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153       | 53.87%  |
| AMD                              | 71        | 25%     |
| Nvidia                           | 59        | 20.77%  |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 20        | 6.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 5.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 3.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 2.06%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.06%   |
| Intel HD Graphics 530                                                                    | 6         | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.72%   |
| Intel HD Graphics 620                                                                    | 5         | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.72%   |
| AMD Renoir                                                                               | 5         | 1.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.37%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.37%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.37%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.37%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.03%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 1.03%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.03%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.03%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.03%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.69%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.69%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 129       | 50.39%  |
| 1 x AMD        | 53        | 20.7%   |
| 1 x Nvidia     | 41        | 16.02%  |
| Intel + Nvidia | 12        | 4.69%   |
| Intel + AMD    | 8         | 3.13%   |
| AMD + Nvidia   | 6         | 2.34%   |
| 2 x AMD        | 4         | 1.56%   |
| Other          | 2         | 0.78%   |
| 1 x SiS        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 221       | 85.66%  |
| Proprietary | 27        | 10.47%  |
| Unknown     | 10        | 3.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 59.54%  |
| 1.01-2.0   | 27        | 10.31%  |
| 0.01-0.5   | 27        | 10.31%  |
| 0.51-1.0   | 26        | 9.92%   |
| 3.01-4.0   | 16        | 6.11%   |
| 5.01-6.0   | 5         | 1.91%   |
| 7.01-8.0   | 3         | 1.15%   |
| 2.01-3.0   | 1         | 0.38%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 27        | 10.51%  |
| LG Display              | 26        | 10.12%  |
| Chimei Innolux          | 24        | 9.34%   |
| AU Optronics            | 24        | 9.34%   |
| BOE                     | 21        | 8.17%   |
| AOC                     | 18        | 7%      |
| ViewSonic               | 17        | 6.61%   |
| KTC                     | 10        | 3.89%   |
| InfoVision              | 8         | 3.11%   |
| Acer                    | 8         | 3.11%   |
| KDC                     | 7         | 2.72%   |
| Goldstar                | 7         | 2.72%   |
| Lenovo                  | 6         | 2.33%   |
| Dell                    | 5         | 1.95%   |
| Chi Mei Optoelectronics | 5         | 1.95%   |
| Sharp                   | 4         | 1.56%   |
| PANDA                   | 4         | 1.56%   |
| Hewlett-Packard         | 4         | 1.56%   |
| Unknown                 | 3         | 1.17%   |
| LG Philips              | 2         | 0.78%   |
| HSI                     | 2         | 0.78%   |
| HKC                     | 2         | 0.78%   |
| Apple                   | 2         | 0.78%   |
| Ancor Communications    | 2         | 0.78%   |
| Valve                   | 1         | 0.39%   |
| Sun                     | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| RIS                     | 1         | 0.39%   |
| Philips                 | 1         | 0.39%   |
| Panasonic               | 1         | 0.39%   |
| Mi                      | 1         | 0.39%   |
| LG Electronics          | 1         | 0.39%   |
| Lenovo Group Limited    | 1         | 0.39%   |
| KVM                     | 1         | 0.39%   |
| Konka                   | 1         | 0.39%   |
| KOA                     | 1         | 0.39%   |
| JDI                     | 1         | 0.39%   |
| InnoLux Display         | 1         | 0.39%   |
| Hitachi                 | 1         | 0.39%   |
| Envision                | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 2.26%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 5         | 1.89%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                   | 4         | 1.51%   |
| Lenovo LEN-AIO310-E LEN0017 1440x900 520x320mm 24.0-inch                 | 3         | 1.13%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                     | 3         | 1.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.13%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch               | 2         | 0.75%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                  | 2         | 0.75%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch      | 2         | 0.75%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch        | 2         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.75%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.75%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.75%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 2         | 0.75%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch              | 2         | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.75%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch                 | 2         | 0.75%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.75%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.75%   |
| HSI LED-TV HSI0001 1920x1080 708x398mm 32.0-inch                         | 2         | 0.75%   |
| HKC LCD Monitor HKC1850 1360x768 304x228mm 15.0-inch                     | 2         | 0.75%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 2         | 0.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.75%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 0.75%   |
| AOC 2461W AOC2461 1920x1080 521x293mm 23.5-inch                          | 2         | 0.75%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.75%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.75%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.75%   |
| AOC 1621Wb AOC1621 1366x768 344x194mm 15.5-inch                          | 2         | 0.75%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                   | 1         | 0.38%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch            | 1         | 0.38%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch            | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 89        | 37.39%  |
| 1920x1080 (FHD)    | 76        | 31.93%  |
| 1600x900 (HD+)     | 14        | 5.88%   |
| 3840x2160 (4K)     | 7         | 2.94%   |
| 1920x1200 (WUXGA)  | 7         | 2.94%   |
| 1440x900 (WXGA+)   | 7         | 2.94%   |
| 2560x1440 (QHD)    | 6         | 2.52%   |
| 1360x768           | 5         | 2.1%    |
| Unknown            | 5         | 2.1%    |
| 1280x800 (WXGA)    | 4         | 1.68%   |
| 1280x1024 (SXGA)   | 4         | 1.68%   |
| 1680x1050 (WSXGA+) | 3         | 1.26%   |
| 2960x900           | 2         | 0.84%   |
| 1280x720 (HD)      | 2         | 0.84%   |
| 800x1280           | 1         | 0.42%   |
| 3600x1080          | 1         | 0.42%   |
| 2944x1080          | 1         | 0.42%   |
| 2560x1080          | 1         | 0.42%   |
| 2288x1287          | 1         | 0.42%   |
| 1280x768           | 1         | 0.42%   |
| 1024x600           | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 79        | 30.86%  |
| 13      | 26        | 10.16%  |
| 14      | 23        | 8.98%   |
| 23      | 21        | 8.2%    |
| 21      | 18        | 7.03%   |
| 18      | 12        | 4.69%   |
| 24      | 11        | 4.3%    |
| 17      | 10        | 3.91%   |
| Unknown | 10        | 3.91%   |
| 11      | 8         | 3.13%   |
| 19      | 6         | 2.34%   |
| 27      | 4         | 1.56%   |
| 40      | 3         | 1.17%   |
| 34      | 3         | 1.17%   |
| 31      | 3         | 1.17%   |
| 20      | 3         | 1.17%   |
| 84      | 2         | 0.78%   |
| 44      | 2         | 0.78%   |
| 32      | 2         | 0.78%   |
| 22      | 2         | 0.78%   |
| 12      | 2         | 0.78%   |
| 10      | 2         | 0.78%   |
| 57      | 1         | 0.39%   |
| 52      | 1         | 0.39%   |
| 16      | 1         | 0.39%   |
| 7       | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 47.22%  |
| 401-500     | 38        | 15.08%  |
| 501-600     | 34        | 13.49%  |
| 201-300     | 19        | 7.54%   |
| 351-400     | 14        | 5.56%   |
| Unknown     | 10        | 3.97%   |
| 701-800     | 5         | 1.98%   |
| 801-900     | 3         | 1.19%   |
| 601-700     | 3         | 1.19%   |
| 1501-2000   | 2         | 0.79%   |
| 1001-1500   | 2         | 0.79%   |
| 901-1000    | 2         | 0.79%   |
| 1-100       | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 190       | 84.44%  |
| 16/10   | 17        | 7.56%   |
| Unknown | 10        | 4.44%   |
| 5/4     | 4         | 1.78%   |
| 21/9    | 3         | 1.33%   |
| 0.67    | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 30.83%  |
| 81-90          | 43        | 17%     |
| 201-250        | 40        | 15.81%  |
| 151-200        | 18        | 7.11%   |
| 141-150        | 10        | 3.95%   |
| Unknown        | 10        | 3.95%   |
| 51-60          | 8         | 3.16%   |
| 121-130        | 8         | 3.16%   |
| 351-500        | 7         | 2.77%   |
| 71-80          | 6         | 2.37%   |
| 501-1000       | 5         | 1.98%   |
| More than 1000 | 4         | 1.58%   |
| 301-350        | 4         | 1.58%   |
| 251-300        | 4         | 1.58%   |
| 61-70          | 2         | 0.79%   |
| 41-50          | 2         | 0.79%   |
| 131-140        | 2         | 0.79%   |
| 1-40           | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 94        | 38.06%  |
| 51-100        | 83        | 33.6%   |
| 121-160       | 46        | 18.62%  |
| Unknown       | 10        | 4.05%   |
| 161-240       | 8         | 3.24%   |
| 1-50          | 5         | 2.02%   |
| More than 240 | 1         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 205       | 77.95%  |
| 2     | 40        | 15.21%  |
| 0     | 14        | 5.32%   |
| 3     | 3         | 1.14%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 133       | 35.75%  |
| Intel                            | 104       | 27.96%  |
| Qualcomm Atheros                 | 49        | 13.17%  |
| Broadcom                         | 25        | 6.72%   |
| Ralink Technology                | 12        | 3.23%   |
| TP-Link                          | 8         | 2.15%   |
| Nvidia                           | 6         | 1.61%   |
| MediaTek                         | 5         | 1.34%   |
| Ralink                           | 4         | 1.08%   |
| Broadcom Limited                 | 4         | 1.08%   |
| Xiaomi                           | 3         | 0.81%   |
| Huawei Technologies              | 3         | 0.81%   |
| Samsung Electronics              | 2         | 0.54%   |
| Mercucys                         | 2         | 0.54%   |
| ASIX Electronics                 | 2         | 0.54%   |
| VIA Technologies                 | 1         | 0.27%   |
| Texas Instruments                | 1         | 0.27%   |
| T & A Mobile Phones              | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Sierra Wireless                  | 1         | 0.27%   |
| Qualcomm Atheros Communications  | 1         | 0.27%   |
| Qualcomm                         | 1         | 0.27%   |
| Marvell Technology Group         | 1         | 0.27%   |
| Lenovo                           | 1         | 0.27%   |
| DisplayLink                      | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 20.79%  |
| Intel Wireless 3165                                               | 26        | 6.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 5.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 1.4%    |
| Nvidia MCP61 Ethernet                                             | 6         | 1.4%    |
| Intel Wireless 8260                                               | 6         | 1.4%    |
| Intel Wireless 7265                                               | 6         | 1.4%    |
| Intel Wireless 7260                                               | 5         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.17%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.7%    |
| TP-Link 802.11ac NIC                                              | 3         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.7%    |
| Huawei E353/E3131                                                 | 3         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.47%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 2         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.47%   |
| Realtek 802.11ac NIC                                              | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 37.02%  |
| Realtek Semiconductor           | 45        | 21.63%  |
| Qualcomm Atheros                | 35        | 16.83%  |
| Broadcom                        | 18        | 8.65%   |
| Ralink Technology               | 12        | 5.77%   |
| TP-Link                         | 7         | 3.37%   |
| Ralink                          | 4         | 1.92%   |
| MediaTek                        | 4         | 1.92%   |
| Mercucys                        | 2         | 0.96%   |
| Broadcom Limited                | 2         | 0.96%   |
| Sierra Wireless                 | 1         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 26        | 12.44%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 4.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.35%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 3.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.35%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 2.87%   |
| Intel Wireless 8260                                                     | 6         | 2.87%   |
| Intel Wireless 7265                                                     | 6         | 2.87%   |
| Intel Wireless 7260                                                     | 5         | 2.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.39%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.91%   |
| TP-Link 802.11ac NIC                                                    | 3         | 1.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 3         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.96%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.96%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| Mercucys 802.11n NIC                                                    | 2         | 0.96%   |
| Intel Wireless 3160                                                     | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 119       | 55.35%  |
| Intel                            | 44        | 20.47%  |
| Qualcomm Atheros                 | 16        | 7.44%   |
| Broadcom                         | 10        | 4.65%   |
| Nvidia                           | 6         | 2.79%   |
| Xiaomi                           | 3         | 1.4%    |
| Huawei Technologies              | 3         | 1.4%    |
| Samsung Electronics              | 2         | 0.93%   |
| Broadcom Limited                 | 2         | 0.93%   |
| ASIX Electronics                 | 2         | 0.93%   |
| VIA Technologies                 | 1         | 0.47%   |
| TP-Link                          | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Qualcomm                         | 1         | 0.47%   |
| MediaTek                         | 1         | 0.47%   |
| Marvell Technology Group         | 1         | 0.47%   |
| Lenovo                           | 1         | 0.47%   |
| DisplayLink                      | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 41.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 11.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.7%    |
| Nvidia MCP61 Ethernet                                             | 6         | 2.78%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.39%   |
| Huawei E353/E3131                                                 | 3         | 1.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.93%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 0.93%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.93%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.46%   |
| Samsung Kiera                                                     | 1         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.46%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.46%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.46%   |
| MediaTek TECNO SPARK 9T                                           | 1         | 0.46%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.46%   |
| Lenovo USB-C to LAN                                               | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 196       | 49.87%  |
| WiFi     | 194       | 49.36%  |
| Modem    | 2         | 0.51%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 64.84%  |
| Ethernet | 90        | 35.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 129       | 50.39%  |
| 2     | 115       | 44.92%  |
| 0     | 9         | 3.52%   |
| 3     | 3         | 1.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 182       | 70.27%  |
| Yes  | 77        | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 47.26%  |
| Realtek Semiconductor           | 15        | 10.27%  |
| Qualcomm Atheros Communications | 15        | 10.27%  |
| Cambridge Silicon Radio         | 10        | 6.85%   |
| IMC Networks                    | 9         | 6.16%   |
| Toshiba                         | 7         | 4.79%   |
| Broadcom                        | 5         | 3.42%   |
| Foxconn / Hon Hai               | 4         | 2.74%   |
| Lite-On Technology              | 3         | 2.05%   |
| Apple                           | 3         | 2.05%   |
| Ralink                          | 2         | 1.37%   |
| TP-Link                         | 1         | 0.68%   |
| Ralink Technology               | 1         | 0.68%   |
| Foxconn International           | 1         | 0.68%   |
| Alps Electric                   | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 30.82%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 6.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 6.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 5.48%   |
| Intel AX200 Bluetooth                               | 7         | 4.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 4.11%   |
| Realtek Bluetooth Radio                             | 5         | 3.42%   |
| Intel Bluetooth Device                              | 4         | 2.74%   |
| Toshiba Bluetooth Device                            | 3         | 2.05%   |
| Toshiba BCM43142A0                                  | 3         | 2.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.05%   |
| Intel AX201 Bluetooth                               | 3         | 2.05%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.05%   |
| Apple Bluetooth USB Host Controller                 | 3         | 2.05%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.37%   |
| IMC Networks Wireless_Device                        | 2         | 1.37%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.37%   |
| TP-Link UB500 Adapter                               | 1         | 0.68%   |
| Toshiba Bluetooth Radio                             | 1         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.68%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.68%   |
| Lite-On Bluetooth Device                            | 1         | 0.68%   |
| IMC Networks Bluetooth Device                       | 1         | 0.68%   |
| IMC Networks Bluetooth                              | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.68%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.68%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.68%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.68%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.68%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 173       | 53.4%   |
| AMD                                  | 70        | 21.6%   |
| Nvidia                               | 50        | 15.43%  |
| Logitech                             | 8         | 2.47%   |
| C-Media Electronics                  | 3         | 0.93%   |
| VIA Technologies                     | 2         | 0.62%   |
| Texas Instruments                    | 2         | 0.62%   |
| Samson Technologies                  | 2         | 0.62%   |
| Kingston Technology                  | 2         | 0.62%   |
| Generalplus Technology               | 2         | 0.62%   |
| Creative Labs                        | 2         | 0.62%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.31%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.31%   |
| Rockwell International               | 1         | 0.31%   |
| KTMicro                              | 1         | 0.31%   |
| JMTek                                | 1         | 0.31%   |
| Focusrite-Novation                   | 1         | 0.31%   |
| Elgato Systems                       | 1         | 0.31%   |
| Creative Technology                  | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 4.96%   |
| AMD FCH Azalia Controller                                                                         | 20        | 4.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 3.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 3.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 2.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.99%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 1.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.74%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.74%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.49%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.99%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.99%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.74%   |
| Logitech H390 headset with microphone                                                             | 3         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 21.02%  |
| Kingston            | 20        | 12.74%  |
| SK hynix            | 18        | 11.46%  |
| Micron Technology   | 16        | 10.19%  |
| Unknown             | 15        | 9.55%   |
| Crucial             | 13        | 8.28%   |
| Ramaxel Technology  | 7         | 4.46%   |
| Goldkey             | 6         | 3.82%   |
| Elpida              | 4         | 2.55%   |
| A-DATA Technology   | 4         | 2.55%   |
| Patriot             | 3         | 1.91%   |
| Nanya Technology    | 3         | 1.91%   |
| Hikvision           | 3         | 1.91%   |
| Team                | 2         | 1.27%   |
| Corsair             | 2         | 1.27%   |
| Unknown (2C0B)      | 1         | 0.64%   |
| Unknown (0x5846)    | 1         | 0.64%   |
| Smart               | 1         | 0.64%   |
| Netac               | 1         | 0.64%   |
| KLEVV               | 1         | 0.64%   |
| Infineon            | 1         | 0.64%   |
| GeIL                | 1         | 0.64%   |
| Avant               | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 4         | 2.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 1.81%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 1.81%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s        | 3         | 1.81%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 2         | 1.2%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 1.2%    |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s      | 2         | 1.2%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 1.2%    |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.2%    |
| Micron RAM 8JTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s        | 2         | 1.2%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 1.2%    |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.2%    |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 1.2%    |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s         | 2         | 1.2%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1         | 0.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1         | 0.6%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                          | 1         | 0.6%    |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.6%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1         | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 0.6%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.6%    |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s        | 1         | 0.6%    |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s              | 1         | 0.6%    |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1         | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s           | 1         | 0.6%    |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                    | 1         | 0.6%    |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s           | 1         | 0.6%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.6%    |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.6%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.6%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.6%    |
| SK hynix RAM HMT325U6CFR8C-PB 2048MB DIMM DDR3 1600MT/s       | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 63        | 50%     |
| DDR4    | 48        | 38.1%   |
| DDR2    | 4         | 3.17%   |
| SDRAM   | 3         | 2.38%   |
| LPDDR3  | 3         | 2.38%   |
| Unknown | 3         | 2.38%   |
| LPDDR4  | 1         | 0.79%   |
| DDR     | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 56.1%   |
| DIMM         | 49        | 39.84%  |
| Row Of Chips | 5         | 4.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 30.2%   |
| 4096  | 44        | 29.53%  |
| 2048  | 27        | 18.12%  |
| 16384 | 23        | 15.44%  |
| 32768 | 5         | 3.36%   |
| 1024  | 3         | 2.01%   |
| 512   | 1         | 0.67%   |
| 256   | 1         | 0.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 47        | 32.41%  |
| 2667  | 22        | 15.17%  |
| 1333  | 15        | 10.34%  |
| 3200  | 10        | 6.9%    |
| 2400  | 8         | 5.52%   |
| 2133  | 6         | 4.14%   |
| 1334  | 5         | 3.45%   |
| 3600  | 4         | 2.76%   |
| 533   | 4         | 2.76%   |
| 3266  | 3         | 2.07%   |
| 1867  | 3         | 2.07%   |
| 4199  | 2         | 1.38%   |
| 3800  | 2         | 1.38%   |
| 3000  | 2         | 1.38%   |
| 1067  | 2         | 1.38%   |
| 3733  | 1         | 0.69%   |
| 3500  | 1         | 0.69%   |
| 3466  | 1         | 0.69%   |
| 3400  | 1         | 0.69%   |
| 2666  | 1         | 0.69%   |
| 2176  | 1         | 0.69%   |
| 1866  | 1         | 0.69%   |
| 1066  | 1         | 0.69%   |
| 333   | 1         | 0.69%   |
| 266   | 1         | 0.69%   |

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
| Chicony Electronics                    | 40        | 25%     |
| Realtek Semiconductor                  | 16        | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 15        | 9.38%   |
| Sunplus Innovation Technology          | 9         | 5.63%   |
| Bison Electronics                      | 9         | 5.63%   |
| Microdia                               | 8         | 5%      |
| Logitech                               | 8         | 5%      |
| Suyin                                  | 7         | 4.38%   |
| Unknown                                | 6         | 3.75%   |
| Acer                                   | 5         | 3.13%   |
| Silicon Motion                         | 4         | 2.5%    |
| IMC Networks                           | 4         | 2.5%    |
| Syntek                                 | 3         | 1.88%   |
| Quanta                                 | 3         | 1.88%   |
| Importek                               | 3         | 1.88%   |
| Apple                                  | 3         | 1.88%   |
| Alcor Micro                            | 3         | 1.88%   |
| Samsung Electronics                    | 2         | 1.25%   |
| Luxvisions Innotech Limited            | 2         | 1.25%   |
| Lite-On Technology                     | 2         | 1.25%   |
| Sony                                   | 1         | 0.63%   |
| Sonix Technology                       | 1         | 0.63%   |
| Primax Electronics                     | 1         | 0.63%   |
| Novatek Microelectronics               | 1         | 0.63%   |
| GEMBIRD                                | 1         | 0.63%   |
| DigiTech                               | 1         | 0.63%   |
| Aveo Technology                        | 1         | 0.63%   |
| A4Tech                                 | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 16        | 10%     |
| Unknown USB Camera                                             | 5         | 3.13%   |
| Chicony Integrated Camera                                      | 5         | 3.13%   |
| Chicony HP Truevision HD                                       | 5         | 3.13%   |
| Bison Integrated Camera                                        | 5         | 3.13%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.5%    |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.5%    |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.5%    |
| Realtek Lenovo EasyCamera                                      | 3         | 1.88%   |
| Logitech Webcam C270                                           | 3         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.88%   |
| Acer Integrated Camera                                         | 3         | 1.88%   |
| Syntek Integrated Camera                                       | 2         | 1.25%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.25%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 1.25%   |
| Realtek USB Camera                                             | 2         | 1.25%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.25%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.25%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 1.25%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.25%   |
| Chicony HD WebCam                                              | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.25%   |
| Bison Lenovo EasyCamera                                        | 2         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 1.25%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.25%   |
| Acer HD Webcam                                                 | 2         | 1.25%   |
| Unknown HD camera                                              | 1         | 0.63%   |
| Syntek EasyCamera                                              | 1         | 0.63%   |
| Suyin VGA Webcam                                               | 1         | 0.63%   |
| Suyin HP Truevision HD                                         | 1         | 0.63%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.63%   |
| Suyin HD WebCam                                                | 1         | 0.63%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.63%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.63%   |
| Sunplus MTD camera                                             | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 36.84%  |
| Synaptics                  | 3         | 15.79%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Elan Microelectronics      | 2         | 10.53%  |
| Upek                       | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Focal-systems.Corp         | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 15.79%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 15.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 10.53%  |
| Elan ELAN:Fingerprint                                  | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| Synaptics UWP WBDI Device                              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 33.33%  |
| Broadcom 58200                      | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 206       | 78.93%  |
| 1     | 51        | 19.54%  |
| 2     | 3         | 1.15%   |
| 3     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 30.51%  |
| Net/wireless             | 14        | 23.73%  |
| Graphics card            | 11        | 18.64%  |
| Multimedia controller    | 6         | 10.17%  |
| Chipcard                 | 3         | 5.08%   |
| Bluetooth                | 2         | 3.39%   |
| Unassigned class         | 1         | 1.69%   |
| Storage                  | 1         | 1.69%   |
| Sound                    | 1         | 1.69%   |
| Modem                    | 1         | 1.69%   |
| Communication controller | 1         | 1.69%   |


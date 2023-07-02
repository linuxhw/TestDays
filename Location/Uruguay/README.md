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

Total: 369

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | One S1002                   | Notebook    | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Intel         | H61                         | Desktop     | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Dell          | 0V8WGR A02                  | Desktop     | [448fd1711d](https://linux-hardware.org/?probe=448fd1711d) | Jun 12, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 37        | 13.41%  |
| Ubuntu 18.04       | 29        | 10.51%  |
| OpenMandriva 4.3   | 16        | 5.8%    |
| Manjaro            | 14        | 5.07%   |
| Ubuntu 22.04       | 9         | 3.26%   |
| KDE neon 20.04     | 8         | 2.9%    |
| OpenMandriva 4.2   | 7         | 2.54%   |
| OpenMandriva 23.03 | 6         | 2.17%   |
| Linux Mint 19.3    | 6         | 2.17%   |
| Arch Rolling       | 6         | 2.17%   |
| Zorin 16           | 5         | 1.81%   |
| Xubuntu 20.04      | 5         | 1.81%   |
| Ubuntu 19.04       | 5         | 1.81%   |
| OpenMandriva 23.01 | 5         | 1.81%   |
| Debian 11          | 5         | 1.81%   |
| Ubuntu 21.10       | 4         | 1.45%   |
| Ubuntu 18.10       | 4         | 1.45%   |
| Linux Mint 19.1    | 4         | 1.45%   |
| Fedora 36          | 4         | 1.45%   |
| ArcoLinux Rolling  | 4         | 1.45%   |
| Xubuntu 18.04      | 3         | 1.09%   |
| ROSA R11.1         | 3         | 1.09%   |
| Pop!_OS 22.04      | 3         | 1.09%   |
| Linux Mint 20      | 3         | 1.09%   |
| BlackPanther 18.1  | 3         | 1.09%   |
| Arch               | 3         | 1.09%   |
| Zorin 15           | 2         | 0.72%   |
| Ubuntu 21.04       | 2         | 0.72%   |
| Ubuntu 19.10       | 2         | 0.72%   |
| Pop!_OS 20.04      | 2         | 0.72%   |
| OpenMandriva 4.50  | 2         | 0.72%   |
| Linux Mint 21.1    | 2         | 0.72%   |
| Linux Mint 21      | 2         | 0.72%   |
| Linux Mint 20.3    | 2         | 0.72%   |
| Linux Mint 20.2    | 2         | 0.72%   |
| Linux Mint 20.1    | 2         | 0.72%   |
| Linux Mint 19.2    | 2         | 0.72%   |
| Kubuntu 18.04      | 2         | 0.72%   |
| Fedora 37          | 2         | 0.72%   |
| Fedora 35          | 2         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 92        | 34.33%  |
| OpenMandriva | 34        | 12.69%  |
| Linux Mint   | 26        | 9.7%    |
| Manjaro      | 15        | 5.6%    |
| Fedora       | 13        | 4.85%   |
| Xubuntu      | 9         | 3.36%   |
| KDE neon     | 9         | 3.36%   |
| Arch         | 8         | 2.99%   |
| Zorin        | 7         | 2.61%   |
| Debian       | 7         | 2.61%   |
| Pop!_OS      | 6         | 2.24%   |
| Endless      | 5         | 1.87%   |
| ArcoLinux    | 5         | 1.87%   |
| ROSA         | 4         | 1.49%   |
| Lubuntu      | 4         | 1.49%   |
| Kubuntu      | 4         | 1.49%   |
| BlackPanther | 3         | 1.12%   |
| openSUSE     | 2         | 0.75%   |
| Elementary   | 2         | 0.75%   |
| Android      | 2         | 0.75%   |
| Void Linux   | 1         | 0.37%   |
| Ubuntu MATE  | 1         | 0.37%   |
| SteamOS      | 1         | 0.37%   |
| NixOS        | 1         | 0.37%   |
| MX           | 1         | 0.37%   |
| LMDE         | 1         | 0.37%   |
| LinuxFX      | 1         | 0.37%   |
| Gentoo       | 1         | 0.37%   |
| Feren OS     | 1         | 0.37%   |
| EndeavourOS  | 1         | 0.37%   |
| antiX        | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003     | 15        | 5.1%    |
| 5.10.14-desktop-1omv4002    | 7         | 2.38%   |
| 6.2.6-desktop-1omv2390      | 6         | 2.04%   |
| 5.4.0-42-generic            | 6         | 2.04%   |
| 4.16.18-pa2-2bp1            | 6         | 2.04%   |
| 6.1.1-desktop-1omv2290      | 5         | 1.7%    |
| 5.11.0-38-generic           | 5         | 1.7%    |
| 4.16.18-pa2-1bp5            | 5         | 1.7%    |
| 5.8.0-53-generic            | 4         | 1.36%   |
| 5.5.19-bp0                  | 4         | 1.36%   |
| 5.4.0-52-generic            | 4         | 1.36%   |
| 5.3.0-46-generic            | 4         | 1.36%   |
| 5.13.0-39-generic           | 4         | 1.36%   |
| 5.4.0-73-generic            | 3         | 1.02%   |
| 5.4.0-72-generic            | 3         | 1.02%   |
| 5.4.0-65-generic            | 3         | 1.02%   |
| 5.4.0-58-generic            | 3         | 1.02%   |
| 5.15.0-67-generic           | 3         | 1.02%   |
| 5.15.0-46-generic           | 3         | 1.02%   |
| 5.10.0-21-amd64             | 3         | 1.02%   |
| 5.0.0-32-generic            | 3         | 1.02%   |
| 4.18.16-desktop-1bP         | 3         | 1.02%   |
| 6.1.26-1-MANJARO            | 2         | 0.68%   |
| 5.8.0-50-generic            | 2         | 0.68%   |
| 5.8.0-43-generic            | 2         | 0.68%   |
| 5.4.83-generic-2rosa-x86_64 | 2         | 0.68%   |
| 5.4.0-62-generic            | 2         | 0.68%   |
| 5.4.0-39-generic            | 2         | 0.68%   |
| 5.3.0-51-generic            | 2         | 0.68%   |
| 5.3.0-28-generic            | 2         | 0.68%   |
| 5.19.0-41-generic           | 2         | 0.68%   |
| 5.19.0-35-generic           | 2         | 0.68%   |
| 5.17.5-76051705-generic     | 2         | 0.68%   |
| 5.16.13-desktop-1omv4003    | 2         | 0.68%   |
| 5.15.60-1-MANJARO           | 2         | 0.68%   |
| 5.15.0-48-generic           | 2         | 0.68%   |
| 5.15.0-41-generic           | 2         | 0.68%   |
| 5.13.0-44-generic           | 2         | 0.68%   |
| 5.13.0-40-generic           | 2         | 0.68%   |
| 5.13.0-37-generic           | 2         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 13.99%  |
| 4.15.0  | 20        | 6.99%   |
| 5.15.0  | 16        | 5.59%   |
| 5.16.7  | 15        | 5.24%   |
| 5.13.0  | 15        | 5.24%   |
| 5.8.0   | 12        | 4.2%    |
| 5.11.0  | 12        | 4.2%    |
| 5.3.0   | 11        | 3.85%   |
| 4.16.18 | 11        | 3.85%   |
| 5.0.0   | 10        | 3.5%    |
| 4.18.0  | 8         | 2.8%    |
| 5.10.14 | 7         | 2.45%   |
| 6.2.6   | 6         | 2.1%    |
| 5.10.0  | 6         | 2.1%    |
| 6.1.1   | 5         | 1.75%   |
| 5.19.0  | 5         | 1.75%   |
| 5.5.19  | 4         | 1.4%    |
| 5.17.5  | 3         | 1.05%   |
| 4.18.16 | 3         | 1.05%   |
| 6.3.4   | 2         | 0.7%    |
| 6.2.12  | 2         | 0.7%    |
| 6.1.26  | 2         | 0.7%    |
| 6.1.11  | 2         | 0.7%    |
| 5.4.83  | 2         | 0.7%    |
| 5.19.12 | 2         | 0.7%    |
| 5.18.12 | 2         | 0.7%    |
| 5.16.13 | 2         | 0.7%    |
| 5.15.60 | 2         | 0.7%    |
| 5.11.12 | 2         | 0.7%    |
| 6.3.7   | 1         | 0.35%   |
| 6.2.0   | 1         | 0.35%   |
| 6.1.31  | 1         | 0.35%   |
| 6.1.29  | 1         | 0.35%   |
| 6.1.20  | 1         | 0.35%   |
| 6.1.18  | 1         | 0.35%   |
| 6.1.0   | 1         | 0.35%   |
| 6.0.6   | 1         | 0.35%   |
| 6.0.18  | 1         | 0.35%   |
| 6.0.15  | 1         | 0.35%   |
| 6.0.12  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 44        | 15.49%  |
| 5.15    | 22        | 7.75%   |
| 4.15    | 20        | 7.04%   |
| 5.16    | 19        | 6.69%   |
| 5.11    | 18        | 6.34%   |
| 5.10    | 17        | 5.99%   |
| 5.13    | 16        | 5.63%   |
| 6.1     | 14        | 4.93%   |
| 5.8     | 14        | 4.93%   |
| 5.3     | 12        | 4.23%   |
| 4.16    | 12        | 4.23%   |
| 4.18    | 11        | 3.87%   |
| 5.0     | 10        | 3.52%   |
| 6.2     | 9         | 3.17%   |
| 5.19    | 8         | 2.82%   |
| 5.17    | 6         | 2.11%   |
| 5.18    | 5         | 1.76%   |
| 6.0     | 4         | 1.41%   |
| 5.5     | 4         | 1.41%   |
| 5.12    | 4         | 1.41%   |
| 6.3     | 3         | 1.06%   |
| 5.6     | 2         | 0.7%    |
| 5.14    | 2         | 0.7%    |
| 4.9     | 2         | 0.7%    |
| 5.2     | 1         | 0.35%   |
| 4.8     | 1         | 0.35%   |
| 4.4     | 1         | 0.35%   |
| 4.17    | 1         | 0.35%   |
| 4.13    | 1         | 0.35%   |
| 4.12    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 252       | 97.3%   |
| i686   | 5         | 1.93%   |
| armv8l | 2         | 0.77%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 86        | 32.21%  |
| KDE5            | 61        | 22.85%  |
| Unknown         | 36        | 13.48%  |
| XFCE            | 24        | 8.99%   |
| X-Cinnamon      | 18        | 6.74%   |
| GNOME Flashback | 13        | 4.87%   |
| KDE             | 7         | 2.62%   |
| MATE            | 5         | 1.87%   |
| LXQt            | 3         | 1.12%   |
| LXDE            | 3         | 1.12%   |
| Cinnamon        | 3         | 1.12%   |
| Pantheon        | 2         | 0.75%   |
| KDE4            | 2         | 0.75%   |
| sway            | 1         | 0.37%   |
| qtile           | 1         | 0.37%   |
| LeftWM          | 1         | 0.37%   |
| ICEWM           | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 211       | 79.92%  |
| Wayland | 33        | 12.5%   |
| Unknown | 17        | 6.44%   |
| Tty     | 3         | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 133       | 50.19%  |
| SDDM    | 55        | 20.75%  |
| GDM     | 29        | 10.94%  |
| LightDM | 22        | 8.3%    |
| GDM3    | 18        | 6.79%   |
| TDM     | 4         | 1.51%   |
| KDM     | 2         | 0.75%   |
| XDM     | 1         | 0.38%   |
| GREETD  | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_UY      | 133       | 49.26%  |
| en_US      | 56        | 20.74%  |
| Unknown    | 31        | 11.48%  |
| es_ES      | 27        | 10%     |
| es_AR      | 6         | 2.22%   |
| C          | 6         | 2.22%   |
| es_MX      | 5         | 1.85%   |
| es_UY.UTF8 | 2         | 0.74%   |
| pt_BR      | 1         | 0.37%   |
| POSIX      | 1         | 0.37%   |
| en_GB      | 1         | 0.37%   |
| en_CA      | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 139       | 52.65%  |
| EFI  | 125       | 47.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 204       | 76.98%  |
| Overlay | 35        | 13.21%  |
| Btrfs   | 11        | 4.15%   |
| Unknown | 8         | 3.02%   |
| Tmpfs   | 4         | 1.51%   |
| Xfs     | 2         | 0.75%   |
| Ext3    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 56.06%  |
| GPT     | 84        | 31.82%  |
| MBR     | 32        | 12.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 78.85%  |
| Yes       | 55        | 21.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 185       | 70.61%  |
| Yes       | 77        | 29.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 43        | 16.6%   |
| Lenovo              | 32        | 12.36%  |
| ASUSTek Computer    | 28        | 10.81%  |
| Dell                | 20        | 7.72%   |
| Gigabyte Technology | 18        | 6.95%   |
| ASRock              | 18        | 6.95%   |
| MSI                 | 17        | 6.56%   |
| ECS                 | 17        | 6.56%   |
| Acer                | 14        | 5.41%   |
| Toshiba             | 9         | 3.47%   |
| Standard            | 5         | 1.93%   |
| Intel               | 5         | 1.93%   |
| Samsung Electronics | 4         | 1.54%   |
| Gateway             | 3         | 1.16%   |
| Biostar             | 3         | 1.16%   |
| Apple               | 3         | 1.16%   |
| Unknown             | 3         | 1.16%   |
| GPU Company         | 2         | 0.77%   |
| Fujitsu             | 2         | 0.77%   |
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

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ECS SF20PA2                                | 16        | 6.18%   |
| Standard SF20BA2                           | 3         | 1.16%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL0014LD | 3         | 1.16%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 3         | 1.16%   |
| Unknown                                    | 3         | 1.16%   |
| Toshiba Satellite L55t-B                   | 2         | 0.77%   |
| MSI MS-7C37                                | 2         | 0.77%   |
| MSI MS-7721                                | 2         | 0.77%   |
| HP Pavilion 15                             | 2         | 0.77%   |
| HP Notebook                                | 2         | 0.77%   |
| HP Laptop 15-bs0xx                         | 2         | 0.77%   |
| Gigabyte Z390 AORUS ELITE                  | 2         | 0.77%   |
| Gigabyte H61M-S1                           | 2         | 0.77%   |
| ASRock N68-S                               | 2         | 0.77%   |
| ASRock H310CM-HDV                          | 2         | 0.77%   |
| ASRock FM2A58M-VG3+ R2.0                   | 2         | 0.77%   |
| ASRock ALiveNF6P-VSTA                      | 2         | 0.77%   |
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

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ECS SF20PA2           | 16        | 6.18%   |
| Lenovo ThinkPad       | 12        | 4.63%   |
| Toshiba Satellite     | 9         | 3.47%   |
| Acer Aspire           | 9         | 3.47%   |
| HP Pavilion           | 8         | 3.09%   |
| HP Laptop             | 8         | 3.09%   |
| Dell Inspiron         | 7         | 2.7%    |
| Lenovo IdeaPad        | 6         | 2.32%   |
| HP Compaq             | 6         | 2.32%   |
| Dell Latitude         | 5         | 1.93%   |
| ASUS ROG              | 5         | 1.93%   |
| Lenovo ThinkCentre    | 4         | 1.54%   |
| Dell OptiPlex         | 4         | 1.54%   |
| Standard SF20BA2      | 3         | 1.16%   |
| Lenovo IdeaCentre     | 3         | 1.16%   |
| ASUS VivoBook         | 3         | 1.16%   |
| ASUS PRIME            | 3         | 1.16%   |
| Unknown               | 3         | 1.16%   |
| MSI MS-7C37           | 2         | 0.77%   |
| MSI MS-7721           | 2         | 0.77%   |
| HP Stream             | 2         | 0.77%   |
| HP Notebook           | 2         | 0.77%   |
| HP ENVY               | 2         | 0.77%   |
| HP EliteDesk          | 2         | 0.77%   |
| HP EliteBook          | 2         | 0.77%   |
| HP 240                | 2         | 0.77%   |
| Gigabyte Z390         | 2         | 0.77%   |
| Gigabyte H61M-S1      | 2         | 0.77%   |
| Dell XPS              | 2         | 0.77%   |
| ASUS TUF              | 2         | 0.77%   |
| ASRock N68-S          | 2         | 0.77%   |
| ASRock H310CM-HDV     | 2         | 0.77%   |
| ASRock FM2A58M-VG3+   | 2         | 0.77%   |
| ASRock ALiveNF6P-VSTA | 2         | 0.77%   |
| ASRock A320M-HDV      | 2         | 0.77%   |
| Acer TravelMate       | 2         | 0.77%   |
| Acer One              | 2         | 0.77%   |
| Valve Jupiter         | 1         | 0.39%   |
| Supermicro P4DMS      | 1         | 0.39%   |
| Standard SF20BA       | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 33        | 12.74%  |
| 2019    | 26        | 10.04%  |
| 2013    | 24        | 9.27%   |
| 2011    | 23        | 8.88%   |
| 2015    | 19        | 7.34%   |
| 2018    | 18        | 6.95%   |
| 2014    | 18        | 6.95%   |
| 2012    | 18        | 6.95%   |
| 2020    | 17        | 6.56%   |
| 2016    | 16        | 6.18%   |
| 2021    | 8         | 3.09%   |
| 2010    | 8         | 3.09%   |
| 2022    | 7         | 2.7%    |
| 2009    | 7         | 2.7%    |
| 2007    | 7         | 2.7%    |
| 2008    | 4         | 1.54%   |
| Unknown | 2         | 0.77%   |
| 2006    | 1         | 0.39%   |
| 2005    | 1         | 0.39%   |
| 2004    | 1         | 0.39%   |
| 2003    | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 152       | 58.69%  |
| Desktop     | 96        | 37.07%  |
| Mini pc     | 3         | 1.16%   |
| All in one  | 3         | 1.16%   |
| Phone       | 2         | 0.77%   |
| Convertible | 2         | 0.77%   |
| Tablet      | 1         | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 244       | 93.85%  |
| Enabled  | 16        | 6.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 259       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 24.24%  |
| 3.01-4.0    | 57        | 21.59%  |
| 8.01-16.0   | 43        | 16.29%  |
| 16.01-24.0  | 34        | 12.88%  |
| 1.01-2.0    | 34        | 12.88%  |
| 32.01-64.0  | 15        | 5.68%   |
| 24.01-32.0  | 8         | 3.03%   |
| 64.01-256.0 | 4         | 1.52%   |
| 2.01-3.0    | 2         | 0.76%   |
| 0.01-0.5    | 2         | 0.76%   |
| 0.51-1.0    | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 120       | 42.86%  |
| 2.01-3.0  | 66        | 23.57%  |
| 3.01-4.0  | 31        | 11.07%  |
| 4.01-8.0  | 27        | 9.64%   |
| 0.51-1.0  | 20        | 7.14%   |
| 8.01-16.0 | 10        | 3.57%   |
| 0.01-0.5  | 6         | 2.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 181       | 68.82%  |
| 2      | 55        | 20.91%  |
| 3      | 13        | 4.94%   |
| 4      | 10        | 3.8%    |
| 5      | 2         | 0.76%   |
| 0      | 2         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 63.22%  |
| Yes       | 96        | 36.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 76.45%  |
| No        | 61        | 23.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 74.71%  |
| No        | 66        | 25.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 55.98%  |
| No        | 114       | 44.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Uruguay | 259       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Montevideo             | 196       | 72.06%  |
| Maldonado              | 13        | 4.78%   |
| Canelones              | 8         | 2.94%   |
| San Jose de Mayo       | 4         | 1.47%   |
| Punta del Este         | 4         | 1.47%   |
| Las Piedras            | 4         | 1.47%   |
| Florida                | 3         | 1.1%    |
| Ciudad del Plata       | 3         | 1.1%    |
| Buceo                  | 3         | 1.1%    |
| Salto                  | 2         | 0.74%   |
| Rocha                  | 2         | 0.74%   |
| Punta Gorda            | 2         | 0.74%   |
| Paysandú              | 2         | 0.74%   |
| Parque Rodo            | 2         | 0.74%   |
| Nueva Helvecia         | 2         | 0.74%   |
| La Paz                 | 2         | 0.74%   |
| Durazno                | 2         | 0.74%   |
| Centro                 | 2         | 0.74%   |
| Solymar                | 1         | 0.37%   |
| Pinamar                | 1         | 0.37%   |
| Nuevo Paris            | 1         | 0.37%   |
| Minas                  | 1         | 0.37%   |
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

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 73        | 92     | 21.04%  |
| Seagate                     | 48        | 61     | 13.83%  |
| Kingston                    | 44        | 54     | 12.68%  |
| Toshiba                     | 37        | 47     | 10.66%  |
| Samsung Electronics         | 30        | 31     | 8.65%   |
| Unknown                     | 28        | 35     | 8.07%   |
| SanDisk                     | 14        | 17     | 4.03%   |
| Hitachi                     | 9         | 14     | 2.59%   |
| Crucial                     | 8         | 12     | 2.31%   |
| SK hynix                    | 7         | 7      | 2.02%   |
| HGST                        | 7         | 7      | 2.02%   |
| Hewlett-Packard             | 5         | 5      | 1.44%   |
| Intel                       | 4         | 4      | 1.15%   |
| Netac                       | 3         | 4      | 0.86%   |
| Micron/Crucial Technology   | 2         | 3      | 0.58%   |
| Micron Technology           | 2         | 2      | 0.58%   |
| Maxtor                      | 2         | 3      | 0.58%   |
| Kingston Technology Company | 2         | 2      | 0.58%   |
| HS-SSD-C100                 | 2         | 2      | 0.58%   |
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

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 14        | 3.8%    |
| Kingston SA400S37240G 240GB SSD     | 14        | 3.8%    |
| Kingston SA400S37480G 480GB SSD     | 7         | 1.9%    |
| Toshiba DT01ACA300 3TB              | 6         | 1.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 6         | 1.63%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 1.36%   |
| Unknown DA4032  32GB                | 5         | 1.36%   |
| Toshiba MQ01ABD075 752GB            | 5         | 1.36%   |
| Toshiba DT01ACA100 1TB              | 5         | 1.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 1.36%   |
| Samsung HD161HJ 160GB               | 5         | 1.36%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 1.09%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 1.09%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 1.09%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 0.82%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.82%   |
| Toshiba HDWK105 500GB               | 3         | 0.82%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.82%   |
| SanDisk DF4032  32GB                | 3         | 0.82%   |
| Kingston SV300S37A480G 480GB SSD    | 3         | 0.82%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2         | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.54%   |
| WDC WDS120G2G0A-00JH30 128GB SSD    | 2         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.54%   |
| WDC WD5000LPVT-24G33T1 500GB        | 2         | 0.54%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.54%   |
| WDC WD10EFRX-68FYTN0 1TB            | 2         | 0.54%   |
| Unknown SD/MMC/MS PRO 250GB         | 2         | 0.54%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.54%   |
| Toshiba MK5059GSXP 500GB            | 2         | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 0.54%   |
| Seagate ST500DM005 HD502HJ 500GB    | 2         | 0.54%   |
| Seagate ST3750640NS 752GB           | 2         | 0.54%   |
| Seagate ST3250312AS 250GB           | 2         | 0.54%   |
| Seagate ST3160318AS 160GB           | 2         | 0.54%   |
| Seagate ST250DM000-1BD141 250GB     | 2         | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 0.54%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 61        | 77     | 34.08%  |
| Seagate             | 48        | 61     | 26.82%  |
| Toshiba             | 33        | 43     | 18.44%  |
| Samsung Electronics | 15        | 15     | 8.38%   |
| Hitachi             | 9         | 14     | 5.03%   |
| HGST                | 7         | 7      | 3.91%   |
| Unknown             | 2         | 2      | 1.12%   |
| Maxtor              | 2         | 3      | 1.12%   |
| SAGE                | 1         | 1      | 0.56%   |
| ExcelStor           | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 36        | 42     | 41.86%  |
| WDC                 | 9         | 9      | 10.47%  |
| Samsung Electronics | 8         | 9      | 9.3%    |
| Crucial             | 6         | 8      | 6.98%   |
| SanDisk             | 4         | 4      | 4.65%   |
| Hewlett-Packard     | 4         | 4      | 4.65%   |
| Netac               | 3         | 4      | 3.49%   |
| SK hynix            | 2         | 2      | 2.33%   |
| Intel               | 2         | 2      | 2.33%   |
| W800SH              | 1         | 1      | 1.16%   |
| Toshiba             | 1         | 1      | 1.16%   |
| NGFF                | 1         | 1      | 1.16%   |
| Micron Technology   | 1         | 1      | 1.16%   |
| HS-SSD-C100         | 1         | 1      | 1.16%   |
| Gigabyte Technology | 1         | 1      | 1.16%   |
| Dahua               | 1         | 2      | 1.16%   |
| China               | 1         | 1      | 1.16%   |
| BIWIN               | 1         | 1      | 1.16%   |
| Biostar             | 1         | 2      | 1.16%   |
| BHT                 | 1         | 1      | 1.16%   |
| A-DATA Technology   | 1         | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 148       | 224    | 47.28%  |
| SSD     | 84        | 98     | 26.84%  |
| NVMe    | 47        | 61     | 15.02%  |
| MMC     | 30        | 38     | 9.58%   |
| Unknown | 4         | 4      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 197       | 320    | 70.36%  |
| NVMe | 47        | 61     | 16.79%  |
| MMC  | 30        | 38     | 10.71%  |
| SAS  | 6         | 6      | 2.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 150       | 199    | 64.38%  |
| 0.51-1.0   | 69        | 107    | 29.61%  |
| 2.01-3.0   | 7         | 8      | 3%      |
| 1.01-2.0   | 5         | 5      | 2.15%   |
| 3.01-4.0   | 2         | 3      | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 63        | 23.33%  |
| 251-500        | 61        | 22.59%  |
| 501-1000       | 37        | 13.7%   |
| 1-20           | 34        | 12.59%  |
| 21-50          | 28        | 10.37%  |
| 1001-2000      | 16        | 5.93%   |
| 51-100         | 12        | 4.44%   |
| Unknown        | 11        | 4.07%   |
| More than 3000 | 4         | 1.48%   |
| 2001-3000      | 4         | 1.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 124       | 44.6%   |
| 21-50          | 47        | 16.91%  |
| 51-100         | 28        | 10.07%  |
| 251-500        | 23        | 8.27%   |
| 101-250        | 22        | 7.91%   |
| 501-1000       | 14        | 5.04%   |
| Unknown        | 11        | 3.96%   |
| 1001-2000      | 5         | 1.8%    |
| More than 3000 | 2         | 0.72%   |
| 2001-3000      | 2         | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 3      | 8.82%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 5.88%   |
| Seagate ST3750640NS 752GB           | 2         | 7      | 5.88%   |
| Seagate ST250DM000-1BD141 250GB     | 2         | 2      | 5.88%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 2.94%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 1      | 2.94%   |
| WDC WD5000AAJS-00A8B0 500GB         | 1         | 1      | 2.94%   |
| WDC WD3200BEVT-26ZCT0 320GB         | 1         | 1      | 2.94%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 2.94%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 2.94%   |
| Toshiba MK3276GSX 320GB             | 1         | 1      | 2.94%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 2.94%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 2.94%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 2.94%   |
| Seagate ST980811AS 80GB             | 1         | 2      | 2.94%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 2.94%   |
| Seagate ST500DM005 HD502HJ 500GB    | 1         | 1      | 2.94%   |
| Seagate ST3250310CS 250GB           | 1         | 1      | 2.94%   |
| Seagate ST3200827AS 200GB           | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1      | 2.94%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 2.94%   |
| HS-SSD-C100 SSD 240G                | 1         | 1      | 2.94%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 2.94%   |
| HGST HTS545032A7E380 320GB          | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 13        | 20     | 40.63%  |
| WDC         | 8         | 9      | 25%     |
| Toshiba     | 7         | 8      | 21.88%  |
| SanDisk     | 1         | 1      | 3.13%   |
| HS-SSD-C100 | 1         | 1      | 3.13%   |
| Hitachi     | 1         | 1      | 3.13%   |
| HGST        | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 39     | 93.75%  |
| SSD  | 2         | 2      | 6.25%   |

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
| Detected | 163       | 254    | 59.49%  |
| Works    | 79        | 130    | 28.83%  |
| Malfunc  | 32        | 41     | 11.68%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 165       | 57.09%  |
| AMD                              | 60        | 20.76%  |
| Sandisk                          | 13        | 4.5%    |
| Kingston Technology Company      | 9         | 3.11%   |
| Samsung Electronics              | 7         | 2.42%   |
| Nvidia                           | 6         | 2.08%   |
| ASMedia Technology               | 5         | 1.73%   |
| Toshiba America Info Systems     | 4         | 1.38%   |
| SK hynix                         | 4         | 1.38%   |
| Micron/Crucial Technology        | 4         | 1.38%   |
| Silicon Motion                   | 3         | 1.04%   |
| Marvell Technology Group         | 2         | 0.69%   |
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

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43        | 12.8%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 20        | 5.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 2.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8         | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 2.08%   |
| Nvidia MCP61 SATA Controller                                                            | 6         | 1.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.79%   |
| Nvidia MCP61 IDE                                                                        | 5         | 1.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.49%   |
| AMD FCH IDE Controller                                                                  | 5         | 1.49%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.19%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.89%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.89%   |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.89%   |
| AMD FCH SATA Controller D                                                               | 3         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 198       | 66.22%  |
| NVMe | 47        | 15.72%  |
| IDE  | 42        | 14.05%  |
| RAID | 11        | 3.68%   |
| SCSI | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 183       | 70.66%  |
| AMD      | 74        | 28.57%  |
| QUALCOMM | 1         | 0.39%   |
| ARM      | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz          | 17        | 6.56%   |
| Intel Celeron CPU N3050 @ 1.60GHz          | 4         | 1.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 3         | 1.16%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz       | 3         | 1.16%   |
| Intel Celeron CPU N3160 @ 1.60GHz          | 3         | 1.16%   |
| Intel Celeron CPU J3355 @ 2.00GHz          | 3         | 1.16%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 3         | 1.16%   |
| AMD Ryzen 9 4900HS with Radeon Graphics    | 3         | 1.16%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 3         | 1.16%   |
| AMD E-300 APU with Radeon HD Graphics      | 3         | 1.16%   |
| Intel Pentium CPU N3710 @ 1.60GHz          | 2         | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 0.77%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 2         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 0.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 2         | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 2         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 2         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.77%   |
| Intel Core i5-8400 CPU @ 2.80GHz           | 2         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 2         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 2         | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 2         | 0.77%   |
| Intel Core i5-4200M CPU @ 2.50GHz          | 2         | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 2         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 0.77%   |
| Intel Core i5-10400 CPU @ 2.90GHz          | 2         | 0.77%   |
| Intel Core i3-2120 CPU @ 3.30GHz           | 2         | 0.77%   |
| Intel Core i3 CPU M 380 @ 2.53GHz          | 2         | 0.77%   |
| Intel Celeron CPU N3060 @ 1.60GHz          | 2         | 0.77%   |
| Intel Celeron CPU N2830 @ 2.16GHz          | 2         | 0.77%   |
| Intel Atom CPU Z3735F @ 1.33GHz            | 2         | 0.77%   |
| Intel 12th Gen Core i7-1255U               | 2         | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 2         | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 2         | 0.77%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 2         | 0.77%   |
| AMD Phenom II X6 1055T Processor           | 2         | 0.77%   |
| AMD Athlon II X2 250 Processor             | 2         | 0.77%   |
| AMD Athlon 3000G with Radeon Vega Graphics | 2         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 44        | 16.99%  |
| Intel Celeron      | 39        | 15.06%  |
| Intel Core i7      | 37        | 14.29%  |
| Intel Core i3      | 24        | 9.27%   |
| AMD Ryzen 5        | 9         | 3.47%   |
| Intel Pentium      | 8         | 3.09%   |
| Intel Core 2 Duo   | 8         | 3.09%   |
| Intel Atom         | 8         | 3.09%   |
| AMD Ryzen 7        | 8         | 3.09%   |
| AMD A6             | 8         | 3.09%   |
| Other              | 7         | 2.7%    |
| AMD Athlon II X2   | 5         | 1.93%   |
| AMD Ryzen 9        | 4         | 1.54%   |
| AMD Ryzen 3        | 4         | 1.54%   |
| AMD FX             | 4         | 1.54%   |
| AMD A10            | 4         | 1.54%   |
| Intel Xeon         | 3         | 1.16%   |
| Intel Core 2 Quad  | 3         | 1.16%   |
| AMD Phenom II X6   | 3         | 1.16%   |
| AMD E              | 3         | 1.16%   |
| AMD Athlon         | 3         | 1.16%   |
| AMD A8             | 3         | 1.16%   |
| AMD A4             | 3         | 1.16%   |
| Intel Genuine      | 2         | 0.77%   |
| AMD E1             | 2         | 0.77%   |
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

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 132       | 50.97%  |
| 4      | 75        | 28.96%  |
| 6      | 25        | 9.65%   |
| 8      | 17        | 6.56%   |
| 1      | 8         | 3.09%   |
| 10     | 2         | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 256       | 98.84%  |
| 2      | 3         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 140       | 54.05%  |
| 1      | 119       | 45.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 252       | 97.3%   |
| Unknown        | 5         | 1.93%   |
| 32-bit         | 2         | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 25.47%  |
| 0x206a7    | 13        | 4.87%   |
| 0x306c3    | 9         | 3.37%   |
| 0x306a9    | 9         | 3.37%   |
| 0x506c9    | 8         | 3%      |
| 0x406c4    | 8         | 3%      |
| 0x906ea    | 7         | 2.62%   |
| 0x20655    | 7         | 2.62%   |
| 0x40651    | 6         | 2.25%   |
| 0x1067a    | 6         | 2.25%   |
| 0x806ec    | 5         | 1.87%   |
| 0x806e9    | 5         | 1.87%   |
| 0x406e3    | 5         | 1.87%   |
| 0x406c3    | 5         | 1.87%   |
| 0x306d4    | 5         | 1.87%   |
| 0x08108109 | 5         | 1.87%   |
| 0x806ea    | 4         | 1.5%    |
| 0x6fd      | 4         | 1.5%    |
| 0x506e3    | 4         | 1.5%    |
| 0x30678    | 4         | 1.5%    |
| 0x08701021 | 4         | 1.5%    |
| 0x0a50000c | 3         | 1.12%   |
| 0x06006705 | 3         | 1.12%   |
| 0x06001119 | 3         | 1.12%   |
| 0x06000852 | 3         | 1.12%   |
| 0xa0655    | 2         | 0.75%   |
| 0xa0653    | 2         | 0.75%   |
| 0x906eb    | 2         | 0.75%   |
| 0x806c1    | 2         | 0.75%   |
| 0x706e5    | 2         | 0.75%   |
| 0x206d7    | 2         | 0.75%   |
| 0x10676    | 2         | 0.75%   |
| 0x08600104 | 2         | 0.75%   |
| 0x0810100b | 2         | 0.75%   |
| 0x08001138 | 2         | 0.75%   |
| 0x07030105 | 2         | 0.75%   |
| 0x07030104 | 2         | 0.75%   |
| 0x0700010f | 2         | 0.75%   |
| 0x0600611a | 2         | 0.75%   |
| 0x06003106 | 2         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 10.81%  |
| Silvermont    | 22        | 8.49%   |
| Goldmont      | 20        | 7.72%   |
| IvyBridge     | 18        | 6.95%   |
| SandyBridge   | 17        | 6.56%   |
| Haswell       | 17        | 6.56%   |
| Skylake       | 12        | 4.63%   |
| K10           | 11        | 4.25%   |
| Zen+          | 9         | 3.47%   |
| Zen 2         | 9         | 3.47%   |
| Penryn        | 9         | 3.47%   |
| Westmere      | 7         | 2.7%    |
| Piledriver    | 7         | 2.7%    |
| Excavator     | 7         | 2.7%    |
| CometLake     | 7         | 2.7%    |
| Broadwell     | 7         | 2.7%    |
| Zen 3         | 6         | 2.32%   |
| Puma          | 6         | 2.32%   |
| Core          | 6         | 2.32%   |
| Zen           | 5         | 1.93%   |
| Unknown       | 5         | 1.93%   |
| Steamroller   | 4         | 1.54%   |
| Jaguar        | 3         | 1.16%   |
| Bobcat        | 3         | 1.16%   |
| TigerLake     | 2         | 0.77%   |
| NetBurst      | 2         | 0.77%   |
| K8 Hammer     | 2         | 0.77%   |
| IceLake       | 2         | 0.77%   |
| Bonnell       | 2         | 0.77%   |
| Tremont       | 1         | 0.39%   |
| Nehalem       | 1         | 0.39%   |
| K10 Llano     | 1         | 0.39%   |
| Goldmont plus | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 156       | 54.36%  |
| AMD                              | 71        | 24.74%  |
| Nvidia                           | 59        | 20.56%  |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 20        | 6.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 5.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 3.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 2.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.38%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.04%   |
| Intel HD Graphics 530                                                                    | 6         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.7%    |
| Intel HD Graphics 620                                                                    | 5         | 1.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.7%    |
| AMD Renoir                                                                               | 5         | 1.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.36%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.36%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.36%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 1.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.36%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.02%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 1.02%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.02%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.02%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.02%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.02%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.68%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.68%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 132       | 50.97%  |
| 1 x AMD        | 53        | 20.46%  |
| 1 x Nvidia     | 41        | 15.83%  |
| Intel + Nvidia | 12        | 4.63%   |
| Intel + AMD    | 8         | 3.09%   |
| AMD + Nvidia   | 6         | 2.32%   |
| 2 x AMD        | 4         | 1.54%   |
| Other          | 2         | 0.77%   |
| 1 x SiS        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 224       | 85.82%  |
| Proprietary | 27        | 10.34%  |
| Unknown     | 10        | 3.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 159       | 60%     |
| 1.01-2.0   | 27        | 10.19%  |
| 0.01-0.5   | 27        | 10.19%  |
| 0.51-1.0   | 26        | 9.81%   |
| 3.01-4.0   | 16        | 6.04%   |
| 5.01-6.0   | 5         | 1.89%   |
| 7.01-8.0   | 3         | 1.13%   |
| 2.01-3.0   | 1         | 0.38%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 27        | 10.42%  |
| LG Display              | 26        | 10.04%  |
| Chimei Innolux          | 24        | 9.27%   |
| AU Optronics            | 24        | 9.27%   |
| BOE                     | 21        | 8.11%   |
| AOC                     | 19        | 7.34%   |
| ViewSonic               | 17        | 6.56%   |
| KTC                     | 10        | 3.86%   |
| InfoVision              | 8         | 3.09%   |
| Acer                    | 8         | 3.09%   |
| KDC                     | 7         | 2.7%    |
| Goldstar                | 7         | 2.7%    |
| Lenovo                  | 6         | 2.32%   |
| Dell                    | 5         | 1.93%   |
| Chi Mei Optoelectronics | 5         | 1.93%   |
| Unknown                 | 4         | 1.54%   |
| Sharp                   | 4         | 1.54%   |
| PANDA                   | 4         | 1.54%   |
| Hewlett-Packard         | 4         | 1.54%   |
| LG Philips              | 2         | 0.77%   |
| HSI                     | 2         | 0.77%   |
| HKC                     | 2         | 0.77%   |
| Apple                   | 2         | 0.77%   |
| Ancor Communications    | 2         | 0.77%   |
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

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 6         | 2.25%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 5         | 1.87%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch            | 4         | 1.5%    |
| Lenovo LEN-AIO310-E LEN0017 1440x900 520x320mm 24.0-inch                 | 3         | 1.12%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                     | 3         | 1.12%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.12%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch               | 2         | 0.75%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                         | 2         | 0.75%   |
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
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                         | 2         | 0.75%   |
| HKC LCD Monitor HKC1850 1360x768 304x228mm 15.0-inch                     | 2         | 0.75%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.75%   |
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
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                           | 2         | 0.75%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                   | 1         | 0.37%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch            | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 90        | 37.5%   |
| 1920x1080 (FHD)    | 77        | 32.08%  |
| 1600x900 (HD+)     | 14        | 5.83%   |
| 3840x2160 (4K)     | 7         | 2.92%   |
| 1920x1200 (WUXGA)  | 7         | 2.92%   |
| 1440x900 (WXGA+)   | 7         | 2.92%   |
| 2560x1440 (QHD)    | 6         | 2.5%    |
| 1360x768           | 5         | 2.08%   |
| Unknown            | 5         | 2.08%   |
| 1280x800 (WXGA)    | 4         | 1.67%   |
| 1280x1024 (SXGA)   | 4         | 1.67%   |
| 1680x1050 (WSXGA+) | 3         | 1.25%   |
| 2960x900           | 2         | 0.83%   |
| 1280x720 (HD)      | 2         | 0.83%   |
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

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 79        | 30.62%  |
| 13      | 26        | 10.08%  |
| 14      | 23        | 8.91%   |
| 23      | 21        | 8.14%   |
| 21      | 18        | 6.98%   |
| 18      | 13        | 5.04%   |
| 24      | 11        | 4.26%   |
| 17      | 10        | 3.88%   |
| Unknown | 10        | 3.88%   |
| 11      | 8         | 3.1%    |
| 19      | 6         | 2.33%   |
| 27      | 4         | 1.55%   |
| 40      | 3         | 1.16%   |
| 34      | 3         | 1.16%   |
| 32      | 3         | 1.16%   |
| 31      | 3         | 1.16%   |
| 20      | 3         | 1.16%   |
| 84      | 2         | 0.78%   |
| 44      | 2         | 0.78%   |
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

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 46.85%  |
| 401-500     | 39        | 15.35%  |
| 501-600     | 34        | 13.39%  |
| 201-300     | 19        | 7.48%   |
| 351-400     | 14        | 5.51%   |
| Unknown     | 10        | 3.94%   |
| 701-800     | 6         | 2.36%   |
| 801-900     | 3         | 1.18%   |
| 601-700     | 3         | 1.18%   |
| 1501-2000   | 2         | 0.79%   |
| 1001-1500   | 2         | 0.79%   |
| 901-1000    | 2         | 0.79%   |
| 1-100       | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 192       | 84.58%  |
| 16/10   | 17        | 7.49%   |
| Unknown | 10        | 4.41%   |
| 5/4     | 4         | 1.76%   |
| 21/9    | 3         | 1.32%   |
| 0.67    | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 30.59%  |
| 81-90          | 43        | 16.86%  |
| 201-250        | 40        | 15.69%  |
| 151-200        | 18        | 7.06%   |
| 141-150        | 11        | 4.31%   |
| Unknown        | 10        | 3.92%   |
| 51-60          | 8         | 3.14%   |
| 351-500        | 8         | 3.14%   |
| 121-130        | 8         | 3.14%   |
| 71-80          | 6         | 2.35%   |
| 501-1000       | 5         | 1.96%   |
| More than 1000 | 4         | 1.57%   |
| 301-350        | 4         | 1.57%   |
| 251-300        | 4         | 1.57%   |
| 61-70          | 2         | 0.78%   |
| 41-50          | 2         | 0.78%   |
| 131-140        | 2         | 0.78%   |
| 1-40           | 1         | 0.39%   |
| 91-100         | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 94        | 37.75%  |
| 51-100        | 85        | 34.14%  |
| 121-160       | 46        | 18.47%  |
| Unknown       | 10        | 4.02%   |
| 161-240       | 8         | 3.21%   |
| 1-50          | 5         | 2.01%   |
| More than 240 | 1         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 208       | 78.2%   |
| 2     | 40        | 15.04%  |
| 0     | 14        | 5.26%   |
| 3     | 3         | 1.13%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 134       | 35.83%  |
| Intel                            | 105       | 28.07%  |
| Qualcomm Atheros                 | 49        | 13.1%   |
| Broadcom                         | 25        | 6.68%   |
| Ralink Technology                | 12        | 3.21%   |
| TP-Link                          | 8         | 2.14%   |
| Nvidia                           | 6         | 1.6%    |
| MediaTek                         | 5         | 1.34%   |
| Ralink                           | 4         | 1.07%   |
| Broadcom Limited                 | 4         | 1.07%   |
| Xiaomi                           | 3         | 0.8%    |
| Huawei Technologies              | 3         | 0.8%    |
| Samsung Electronics              | 2         | 0.53%   |
| Mercucys                         | 2         | 0.53%   |
| ASIX Electronics                 | 2         | 0.53%   |
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

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 20.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 6.03%   |
| Intel Wireless 3165                                               | 26        | 6.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.09%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.62%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.62%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 1.39%   |
| Nvidia MCP61 Ethernet                                             | 6         | 1.39%   |
| Intel Wireless 8260                                               | 6         | 1.39%   |
| Intel Wireless 7265                                               | 6         | 1.39%   |
| Intel Wireless 7260                                               | 5         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.16%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.7%    |
| TP-Link 802.11ac NIC                                              | 3         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.7%    |
| Huawei E353/E3131                                                 | 3         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.46%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 2         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.46%   |
| Realtek 802.11ac NIC                                              | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 36.84%  |
| Realtek Semiconductor           | 46        | 22.01%  |
| Qualcomm Atheros                | 35        | 16.75%  |
| Broadcom                        | 18        | 8.61%   |
| Ralink Technology               | 12        | 5.74%   |
| TP-Link                         | 7         | 3.35%   |
| Ralink                          | 4         | 1.91%   |
| MediaTek                        | 4         | 1.91%   |
| Mercucys                        | 2         | 0.96%   |
| Broadcom Limited                | 2         | 0.96%   |
| Sierra Wireless                 | 1         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 26        | 12.38%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 4.29%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.33%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.33%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 2.86%   |
| Intel Wireless 8260                                                     | 6         | 2.86%   |
| Intel Wireless 7265                                                     | 6         | 2.86%   |
| Intel Wireless 7260                                                     | 5         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 4         | 1.9%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.9%    |
| TP-Link 802.11ac NIC                                                    | 3         | 1.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.95%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.95%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.95%   |
| Mercucys 802.11n NIC                                                    | 2         | 0.95%   |
| Intel Wireless 3160                                                     | 2         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.95%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 120       | 55.3%   |
| Intel                            | 45        | 20.74%  |
| Qualcomm Atheros                 | 16        | 7.37%   |
| Broadcom                         | 10        | 4.61%   |
| Nvidia                           | 6         | 2.76%   |
| Xiaomi                           | 3         | 1.38%   |
| Huawei Technologies              | 3         | 1.38%   |
| Samsung Electronics              | 2         | 0.92%   |
| Broadcom Limited                 | 2         | 0.92%   |
| ASIX Electronics                 | 2         | 0.92%   |
| VIA Technologies                 | 1         | 0.46%   |
| TP-Link                          | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Qualcomm                         | 1         | 0.46%   |
| MediaTek                         | 1         | 0.46%   |
| Marvell Technology Group         | 1         | 0.46%   |
| Lenovo                           | 1         | 0.46%   |
| DisplayLink                      | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 40.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 11.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 4.13%   |
| Nvidia MCP61 Ethernet                                             | 6         | 2.75%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.38%   |
| Huawei E353/E3131                                                 | 3         | 1.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.92%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 0.92%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.92%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.46%   |
| Samsung Kiera                                                     | 1         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.46%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.46%   |
| Qualcomm Nokia G400 5G                                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.46%   |
| MediaTek Armor X10 Pro                                            | 1         | 0.46%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.46%   |
| Lenovo USB-C to LAN                                               | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 198       | 50%     |
| WiFi     | 195       | 49.24%  |
| Modem    | 2         | 0.51%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 64.73%  |
| Ethernet | 91        | 35.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 131       | 50.58%  |
| 2     | 115       | 44.4%   |
| 0     | 10        | 3.86%   |
| 3     | 3         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 70.23%  |
| Yes  | 78        | 29.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 30.82%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 6.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 6.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 5.48%   |
| Intel AX200 Bluetooth                               | 7         | 4.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 4.11%   |
| Realtek Bluetooth Radio                             | 5         | 3.42%   |
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
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.37%   |
| Intel Bluetooth Device                              | 2         | 1.37%   |
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

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 175       | 53.68%  |
| AMD                                  | 70        | 21.47%  |
| Nvidia                               | 50        | 15.34%  |
| Logitech                             | 8         | 2.45%   |
| C-Media Electronics                  | 3         | 0.92%   |
| VIA Technologies                     | 2         | 0.61%   |
| Texas Instruments                    | 2         | 0.61%   |
| Samson Technologies                  | 2         | 0.61%   |
| Kingston Technology                  | 2         | 0.61%   |
| Generalplus Technology               | 2         | 0.61%   |
| Creative Labs                        | 2         | 0.61%   |
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

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 4.94%   |
| AMD FCH Azalia Controller                                                                         | 20        | 4.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 4.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 3.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 3.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 2.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.98%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.73%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.73%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.23%   |
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

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 20.37%  |
| Kingston            | 20        | 12.35%  |
| SK hynix            | 18        | 11.11%  |
| Unknown             | 16        | 9.88%   |
| Micron Technology   | 16        | 9.88%   |
| Crucial             | 15        | 9.26%   |
| Ramaxel Technology  | 7         | 4.32%   |
| Goldkey             | 6         | 3.7%    |
| Nanya Technology    | 4         | 2.47%   |
| Hikvision           | 4         | 2.47%   |
| Elpida              | 4         | 2.47%   |
| A-DATA Technology   | 4         | 2.47%   |
| Patriot             | 3         | 1.85%   |
| Team                | 2         | 1.23%   |
| Corsair             | 2         | 1.23%   |
| Unknown (2C0B)      | 1         | 0.62%   |
| Unknown (0x5846)    | 1         | 0.62%   |
| Smart               | 1         | 0.62%   |
| Netac               | 1         | 0.62%   |
| KLEVV               | 1         | 0.62%   |
| Infineon            | 1         | 0.62%   |
| GeIL                | 1         | 0.62%   |
| Avant               | 1         | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 4         | 2.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 1.75%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 3         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 1.75%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s        | 3         | 1.75%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3                  | 3         | 1.75%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 1.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 1.17%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 2         | 1.17%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 1.17%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 1.17%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 1.17%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.17%   |
| Micron RAM 8JTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s        | 2         | 1.17%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 1.17%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.17%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 1.17%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1         | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1         | 0.58%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                          | 1         | 0.58%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.58%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1         | 0.58%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 0.58%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 0.58%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.58%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s        | 1         | 0.58%   |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s              | 1         | 0.58%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1         | 0.58%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s            | 1         | 0.58%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                         | 1         | 0.58%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s           | 1         | 0.58%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.58%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s          | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 66        | 51.16%  |
| DDR4    | 48        | 37.21%  |
| DDR2    | 4         | 3.1%    |
| SDRAM   | 3         | 2.33%   |
| LPDDR3  | 3         | 2.33%   |
| Unknown | 3         | 2.33%   |
| LPDDR4  | 1         | 0.78%   |
| DDR     | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 55.56%  |
| DIMM         | 51        | 40.48%  |
| Row Of Chips | 5         | 3.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 46        | 30.07%  |
| 4096  | 46        | 30.07%  |
| 2048  | 28        | 18.3%   |
| 16384 | 23        | 15.03%  |
| 32768 | 5         | 3.27%   |
| 1024  | 3         | 1.96%   |
| 512   | 1         | 0.65%   |
| 256   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 49        | 33.11%  |
| 2667  | 22        | 14.86%  |
| 1333  | 16        | 10.81%  |
| 3200  | 10        | 6.76%   |
| 2400  | 8         | 5.41%   |
| 2133  | 6         | 4.05%   |
| 1334  | 5         | 3.38%   |
| 3600  | 4         | 2.7%    |
| 533   | 4         | 2.7%    |
| 3266  | 3         | 2.03%   |
| 1867  | 3         | 2.03%   |
| 4199  | 2         | 1.35%   |
| 3800  | 2         | 1.35%   |
| 3000  | 2         | 1.35%   |
| 1067  | 2         | 1.35%   |
| 3733  | 1         | 0.68%   |
| 3500  | 1         | 0.68%   |
| 3466  | 1         | 0.68%   |
| 3400  | 1         | 0.68%   |
| 2666  | 1         | 0.68%   |
| 2176  | 1         | 0.68%   |
| 1866  | 1         | 0.68%   |
| 1066  | 1         | 0.68%   |
| 333   | 1         | 0.68%   |
| 266   | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Xerox Phaser 3040    | 1         | 25%     |
| Samsung M288x Series | 1         | 25%     |
| Brother DCP-T500W    | 1         | 25%     |
| Brother DCP-T420W    | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 25%     |
| Realtek Semiconductor                  | 16        | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 15        | 9.38%   |
| Sunplus Innovation Technology          | 9         | 5.63%   |
| Microdia                               | 8         | 5%      |
| Logitech                               | 8         | 5%      |
| Suyin                                  | 7         | 4.38%   |
| Bison Electronics                      | 7         | 4.38%   |
| Acer                                   | 7         | 4.38%   |
| Unknown                                | 6         | 3.75%   |
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

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 16        | 10%     |
| Unknown USB Camera                                             | 5         | 3.13%   |
| Chicony Integrated Camera                                      | 5         | 3.13%   |
| Chicony HP Truevision HD                                       | 5         | 3.13%   |
| Acer Integrated Camera                                         | 5         | 3.13%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.5%    |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.5%    |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.5%    |
| Realtek Lenovo EasyCamera                                      | 3         | 1.88%   |
| Logitech Webcam C270                                           | 3         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.88%   |
| Bison Integrated Camera                                        | 3         | 1.88%   |
| Syntek Integrated Camera                                       | 2         | 1.25%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.25%   |
| Samsung Galaxy A5 (MTP)                                        | 2         | 1.25%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.25%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.25%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 1.25%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.25%   |
| Chicony HD WebCam                                              | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 1.25%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.25%   |
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
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.63%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.63%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 209       | 79.17%  |
| 1     | 51        | 19.32%  |
| 2     | 3         | 1.14%   |
| 3     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


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


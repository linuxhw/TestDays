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

Total: 401

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Razer         | Blade                       | Notebook    | [e9ad529ed4](https://linux-hardware.org/?probe=e9ad529ed4) | Nov 01, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ef0f47332](https://linux-hardware.org/?probe=8ef0f47332) | Oct 20, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [f4eec82fb9](https://linux-hardware.org/?probe=f4eec82fb9) | Oct 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [a775bc4b08](https://linux-hardware.org/?probe=a775bc4b08) | Oct 05, 2023 |
| Razer         | Blade                       | Notebook    | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4398558915](https://linux-hardware.org/?probe=4398558915) | Sep 19, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [6793d8c052](https://linux-hardware.org/?probe=6793d8c052) | Sep 16, 2023 |
| MSI           | B85M-E45                    | Desktop     | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| GPU Compan... | GWTN156-9                   | Notebook    | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [a435538cb2](https://linux-hardware.org/?probe=a435538cb2) | Aug 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [0dc75dae26](https://linux-hardware.org/?probe=0dc75dae26) | Aug 18, 2023 |
| HP            | 14                          | Notebook    | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [025bd1edae](https://linux-hardware.org/?probe=025bd1edae) | Aug 04, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a4d7919584](https://linux-hardware.org/?probe=a4d7919584) | Jul 29, 2023 |
| HP            | 1497                        | Desktop     | [370799b635](https://linux-hardware.org/?probe=370799b635) | Jul 26, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [01cfac81b4](https://linux-hardware.org/?probe=01cfac81b4) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Dell          | Latitude E5420              | Notebook    | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [cacf2d88c9](https://linux-hardware.org/?probe=cacf2d88c9) | Jul 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6776e11ac9](https://linux-hardware.org/?probe=6776e11ac9) | Jul 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [ad76ecf5a9](https://linux-hardware.org/?probe=ad76ecf5a9) | Jul 01, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [b8bab5a2e6](https://linux-hardware.org/?probe=b8bab5a2e6) | Jul 01, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 37        | 12.21%  |
| Ubuntu 18.04                 | 30        | 9.9%    |
| OpenMandriva 4.3             | 16        | 5.28%   |
| Manjaro                      | 15        | 4.95%   |
| Ubuntu 22.04                 | 13        | 4.29%   |
| KDE neon 20.04               | 8         | 2.64%   |
| OpenMandriva 4.2             | 7         | 2.31%   |
| OpenMandriva 23.03           | 7         | 2.31%   |
| ArcoLinux Rolling            | 7         | 2.31%   |
| Linux Mint 19.3              | 6         | 1.98%   |
| Arch Rolling                 | 6         | 1.98%   |
| Zorin 16                     | 5         | 1.65%   |
| Xubuntu 20.04                | 5         | 1.65%   |
| Ubuntu 19.04                 | 5         | 1.65%   |
| OpenMandriva 23.01           | 5         | 1.65%   |
| Debian 11                    | 5         | 1.65%   |
| Ubuntu 21.10                 | 4         | 1.32%   |
| Ubuntu 18.10                 | 4         | 1.32%   |
| Linux Mint 21.2              | 4         | 1.32%   |
| Linux Mint 19.1              | 4         | 1.32%   |
| Fedora 38                    | 4         | 1.32%   |
| Fedora 36                    | 4         | 1.32%   |
| Xubuntu 18.04                | 3         | 0.99%   |
| ROSA R11.1                   | 3         | 0.99%   |
| Pop!_OS 22.04                | 3         | 0.99%   |
| Linux Mint 20                | 3         | 0.99%   |
| Debian 12                    | 3         | 0.99%   |
| BlackPanther 18.1            | 3         | 0.99%   |
| Arch                         | 3         | 0.99%   |
| Zorin 15                     | 2         | 0.66%   |
| Ubuntu 21.04                 | 2         | 0.66%   |
| Ubuntu 19.10                 | 2         | 0.66%   |
| Pop!_OS 20.04                | 2         | 0.66%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.66%   |
| OpenMandriva 4.50            | 2         | 0.66%   |
| OpenMandriva 23.08           | 2         | 0.66%   |
| Linux Mint 21.1              | 2         | 0.66%   |
| Linux Mint 21                | 2         | 0.66%   |
| Linux Mint 20.3              | 2         | 0.66%   |
| Linux Mint 20.2              | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 97        | 33.11%  |
| OpenMandriva | 37        | 12.63%  |
| Linux Mint   | 30        | 10.24%  |
| Manjaro      | 16        | 5.46%   |
| Fedora       | 16        | 5.46%   |
| Xubuntu      | 10        | 3.41%   |
| KDE neon     | 10        | 3.41%   |
| ArcoLinux    | 8         | 2.73%   |
| Arch         | 8         | 2.73%   |
| Zorin        | 7         | 2.39%   |
| Debian       | 7         | 2.39%   |
| Pop!_OS      | 6         | 2.05%   |
| Endless      | 5         | 1.71%   |
| ROSA         | 4         | 1.37%   |
| Lubuntu      | 4         | 1.37%   |
| Kubuntu      | 4         | 1.37%   |
| openSUSE     | 3         | 1.02%   |
| BlackPanther | 3         | 1.02%   |
| EndeavourOS  | 2         | 0.68%   |
| Elementary   | 2         | 0.68%   |
| Archcraft    | 2         | 0.68%   |
| Android      | 2         | 0.68%   |
| Void Linux   | 1         | 0.34%   |
| Ubuntu MATE  | 1         | 0.34%   |
| SteamOS      | 1         | 0.34%   |
| NixOS        | 1         | 0.34%   |
| MX           | 1         | 0.34%   |
| LMDE         | 1         | 0.34%   |
| LinuxFX      | 1         | 0.34%   |
| Gentoo       | 1         | 0.34%   |
| Feren OS     | 1         | 0.34%   |
| antiX        | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003     | 15        | 4.64%   |
| 6.2.6-desktop-1omv2390      | 7         | 2.17%   |
| 5.10.14-desktop-1omv4002    | 7         | 2.17%   |
| 5.4.0-42-generic            | 6         | 1.86%   |
| 4.16.18-pa2-2bp1            | 6         | 1.86%   |
| 6.1.1-desktop-1omv2290      | 5         | 1.55%   |
| 5.11.0-38-generic           | 5         | 1.55%   |
| 4.16.18-pa2-1bp5            | 5         | 1.55%   |
| 5.8.0-53-generic            | 4         | 1.24%   |
| 5.5.19-bp0                  | 4         | 1.24%   |
| 5.4.0-52-generic            | 4         | 1.24%   |
| 5.3.0-46-generic            | 4         | 1.24%   |
| 5.13.0-39-generic           | 4         | 1.24%   |
| 5.4.0-73-generic            | 3         | 0.93%   |
| 5.4.0-72-generic            | 3         | 0.93%   |
| 5.4.0-65-generic            | 3         | 0.93%   |
| 5.4.0-58-generic            | 3         | 0.93%   |
| 5.15.0-67-generic           | 3         | 0.93%   |
| 5.15.0-46-generic           | 3         | 0.93%   |
| 5.10.0-21-amd64             | 3         | 0.93%   |
| 5.0.0-32-generic            | 3         | 0.93%   |
| 4.18.16-desktop-1bP         | 3         | 0.93%   |
| 6.4.7-arch1-1               | 2         | 0.62%   |
| 6.2.0-34-generic            | 2         | 0.62%   |
| 6.1.26-1-MANJARO            | 2         | 0.62%   |
| 5.8.0-50-generic            | 2         | 0.62%   |
| 5.8.0-43-generic            | 2         | 0.62%   |
| 5.4.83-generic-2rosa-x86_64 | 2         | 0.62%   |
| 5.4.0-62-generic            | 2         | 0.62%   |
| 5.4.0-39-generic            | 2         | 0.62%   |
| 5.3.0-51-generic            | 2         | 0.62%   |
| 5.3.0-28-generic            | 2         | 0.62%   |
| 5.19.0-41-generic           | 2         | 0.62%   |
| 5.19.0-35-generic           | 2         | 0.62%   |
| 5.17.5-76051705-generic     | 2         | 0.62%   |
| 5.16.13-desktop-1omv4003    | 2         | 0.62%   |
| 5.15.60-1-MANJARO           | 2         | 0.62%   |
| 5.15.0-48-generic           | 2         | 0.62%   |
| 5.15.0-41-generic           | 2         | 0.62%   |
| 5.13.0-44-generic           | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 13.02%  |
| 5.15.0  | 20        | 6.35%   |
| 4.15.0  | 20        | 6.35%   |
| 5.16.7  | 15        | 4.76%   |
| 5.13.0  | 15        | 4.76%   |
| 5.8.0   | 12        | 3.81%   |
| 5.11.0  | 12        | 3.81%   |
| 5.3.0   | 11        | 3.49%   |
| 4.16.18 | 11        | 3.49%   |
| 5.0.0   | 10        | 3.17%   |
| 4.18.0  | 8         | 2.54%   |
| 6.2.6   | 7         | 2.22%   |
| 5.19.0  | 7         | 2.22%   |
| 5.10.14 | 7         | 2.22%   |
| 5.10.0  | 6         | 1.9%    |
| 6.1.1   | 5         | 1.59%   |
| 6.2.0   | 4         | 1.27%   |
| 5.5.19  | 4         | 1.27%   |
| 5.17.5  | 3         | 0.95%   |
| 4.18.16 | 3         | 0.95%   |
| 6.4.7   | 2         | 0.63%   |
| 6.4.11  | 2         | 0.63%   |
| 6.3.4   | 2         | 0.63%   |
| 6.2.12  | 2         | 0.63%   |
| 6.1.26  | 2         | 0.63%   |
| 6.1.11  | 2         | 0.63%   |
| 6.1.0   | 2         | 0.63%   |
| 5.4.83  | 2         | 0.63%   |
| 5.19.12 | 2         | 0.63%   |
| 5.18.12 | 2         | 0.63%   |
| 5.16.13 | 2         | 0.63%   |
| 5.15.60 | 2         | 0.63%   |
| 5.11.12 | 2         | 0.63%   |
| 6.5.9   | 1         | 0.32%   |
| 6.5.5   | 1         | 0.32%   |
| 6.5.4   | 1         | 0.32%   |
| 6.5.3   | 1         | 0.32%   |
| 6.4.8   | 1         | 0.32%   |
| 6.4.6   | 1         | 0.32%   |
| 6.4.1   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 14.47%  |
| 5.15    | 26        | 8.36%   |
| 4.15    | 20        | 6.43%   |
| 5.16    | 19        | 6.11%   |
| 5.11    | 18        | 5.79%   |
| 5.10    | 17        | 5.47%   |
| 5.13    | 16        | 5.14%   |
| 6.2     | 15        | 4.82%   |
| 6.1     | 15        | 4.82%   |
| 5.8     | 14        | 4.5%    |
| 5.3     | 12        | 3.86%   |
| 4.16    | 12        | 3.86%   |
| 4.18    | 11        | 3.54%   |
| 5.19    | 10        | 3.22%   |
| 5.0     | 10        | 3.22%   |
| 6.4     | 8         | 2.57%   |
| 5.17    | 6         | 1.93%   |
| 6.0     | 5         | 1.61%   |
| 5.18    | 5         | 1.61%   |
| 6.3     | 4         | 1.29%   |
| 5.5     | 4         | 1.29%   |
| 5.12    | 4         | 1.29%   |
| 6.5     | 3         | 0.96%   |
| 5.6     | 2         | 0.64%   |
| 5.14    | 2         | 0.64%   |
| 4.9     | 2         | 0.64%   |
| 5.2     | 1         | 0.32%   |
| 4.8     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.17    | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |
| 4.12    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 276       | 97.53%  |
| i686   | 5         | 1.77%   |
| armv8l | 2         | 0.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 92        | 31.4%   |
| KDE5            | 67        | 22.87%  |
| Unknown         | 36        | 12.29%  |
| XFCE            | 28        | 9.56%   |
| X-Cinnamon      | 23        | 7.85%   |
| GNOME Flashback | 13        | 4.44%   |
| KDE             | 7         | 2.39%   |
| MATE            | 5         | 1.71%   |
| Cinnamon        | 5         | 1.71%   |
| LXQt            | 3         | 1.02%   |
| LXDE            | 3         | 1.02%   |
| Pantheon        | 2         | 0.68%   |
| openbox         | 2         | 0.68%   |
| KDE4            | 2         | 0.68%   |
| sway            | 1         | 0.34%   |
| qtile           | 1         | 0.34%   |
| LeftWM          | 1         | 0.34%   |
| ICEWM           | 1         | 0.34%   |
| i3              | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 229       | 79.24%  |
| Wayland | 40        | 13.84%  |
| Unknown | 17        | 5.88%   |
| Tty     | 3         | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 141       | 48.45%  |
| SDDM    | 60        | 20.62%  |
| LightDM | 30        | 10.31%  |
| GDM     | 30        | 10.31%  |
| GDM3    | 22        | 7.56%   |
| TDM     | 4         | 1.37%   |
| KDM     | 2         | 0.69%   |
| XDM     | 1         | 0.34%   |
| GREETD  | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_UY      | 147       | 49.66%  |
| en_US      | 65        | 21.96%  |
| Unknown    | 31        | 10.47%  |
| es_ES      | 28        | 9.46%   |
| es_MX      | 7         | 2.36%   |
| es_AR      | 6         | 2.03%   |
| C          | 6         | 2.03%   |
| es_UY.UTF8 | 2         | 0.68%   |
| pt_BR      | 1         | 0.34%   |
| POSIX      | 1         | 0.34%   |
| en_GB      | 1         | 0.34%   |
| en_CA      | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 146       | 50.34%  |
| EFI  | 144       | 49.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 218       | 74.66%  |
| Overlay | 38        | 13.01%  |
| Btrfs   | 17        | 5.82%   |
| Tmpfs   | 8         | 2.74%   |
| Unknown | 8         | 2.74%   |
| Xfs     | 2         | 0.68%   |
| Ext3    | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 156       | 53.79%  |
| GPT     | 102       | 35.17%  |
| MBR     | 32        | 11.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 227       | 79.93%  |
| Yes       | 57        | 20.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 203       | 70.49%  |
| Yes       | 85        | 29.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 47        | 16.61%  |
| Lenovo              | 35        | 12.37%  |
| ASUSTek Computer    | 33        | 11.66%  |
| Dell                | 23        | 8.13%   |
| Gigabyte Technology | 21        | 7.42%   |
| ASRock              | 19        | 6.71%   |
| MSI                 | 18        | 6.36%   |
| ECS                 | 17        | 6.01%   |
| Acer                | 15        | 5.3%    |
| Toshiba             | 9         | 3.18%   |
| Standard            | 5         | 1.77%   |
| Intel               | 5         | 1.77%   |
| Samsung Electronics | 4         | 1.41%   |
| GPU Company         | 3         | 1.06%   |
| Gateway             | 3         | 1.06%   |
| Biostar             | 3         | 1.06%   |
| Apple               | 3         | 1.06%   |
| Unknown             | 3         | 1.06%   |
| Fujitsu             | 2         | 0.71%   |
| Valve               | 1         | 0.35%   |
| Supermicro          | 1         | 0.35%   |
| Sony                | 1         | 0.35%   |
| Razer               | 1         | 0.35%   |
| Positivo            | 1         | 0.35%   |
| Panasonic           | 1         | 0.35%   |
| OEM                 | 1         | 0.35%   |
| MACHINIST           | 1         | 0.35%   |
| iClever             | 1         | 0.35%   |
| Huanan              | 1         | 0.35%   |
| Haitech             | 1         | 0.35%   |
| Foxconn             | 1         | 0.35%   |
| Chuwi               | 1         | 0.35%   |
| AZW                 | 1         | 0.35%   |
| Alienware           | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ECS SF20PA2                                | 16        | 5.65%   |
| Standard SF20BA2                           | 3         | 1.06%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL0014LD | 3         | 1.06%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 3         | 1.06%   |
| Unknown                                    | 3         | 1.06%   |
| Toshiba Satellite L55t-B                   | 2         | 0.71%   |
| MSI MS-7C37                                | 2         | 0.71%   |
| MSI MS-7817                                | 2         | 0.71%   |
| MSI MS-7721                                | 2         | 0.71%   |
| HP Pavilion 15                             | 2         | 0.71%   |
| HP Notebook                                | 2         | 0.71%   |
| HP Laptop 15-bs0xx                         | 2         | 0.71%   |
| HP Compaq 6200 Pro SFF PC                  | 2         | 0.71%   |
| Gigabyte Z390 AORUS ELITE                  | 2         | 0.71%   |
| Gigabyte Z370 AORUS Gaming 7               | 2         | 0.71%   |
| Gigabyte H61M-S1                           | 2         | 0.71%   |
| Dell OptiPlex 7010                         | 2         | 0.71%   |
| ASRock N68-S                               | 2         | 0.71%   |
| ASRock H310CM-HDV                          | 2         | 0.71%   |
| ASRock FM2A58M-VG3+ R2.0                   | 2         | 0.71%   |
| ASRock ALiveNF6P-VSTA                      | 2         | 0.71%   |
| Valve Jupiter                              | 1         | 0.35%   |
| Toshiba Satellite L45-B                    | 1         | 0.35%   |
| Toshiba Satellite C855                     | 1         | 0.35%   |
| Toshiba Satellite C75D-C                   | 1         | 0.35%   |
| Toshiba Satellite C75D-B                   | 1         | 0.35%   |
| Toshiba Satellite C645D                    | 1         | 0.35%   |
| Toshiba Satellite C55-B                    | 1         | 0.35%   |
| Toshiba Satellite C45-A                    | 1         | 0.35%   |
| Supermicro P4DMS                           | 1         | 0.35%   |
| Standard SF20BA                            | 1         | 0.35%   |
| Standard EF20EA                            | 1         | 0.35%   |
| Sony SVF14211CLB                           | 1         | 0.35%   |
| Samsung NC208/NC108                        | 1         | 0.35%   |
| Samsung N102SP/N100SP/N101SP               | 1         | 0.35%   |
| Samsung 700T                               | 1         | 0.35%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.35%   |
| Razer Blade                                | 1         | 0.35%   |
| Positivo Serie AT300                       | 1         | 0.35%   |
| Panasonic CF-31JEGAX1M                     | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ECS SF20PA2           | 16        | 5.65%   |
| Lenovo ThinkPad       | 13        | 4.59%   |
| HP Laptop             | 10        | 3.53%   |
| Acer Aspire           | 10        | 3.53%   |
| Toshiba Satellite     | 9         | 3.18%   |
| HP Pavilion           | 8         | 2.83%   |
| Lenovo IdeaPad        | 7         | 2.47%   |
| HP Compaq             | 7         | 2.47%   |
| Dell Inspiron         | 7         | 2.47%   |
| Dell Latitude         | 6         | 2.12%   |
| ASUS ROG              | 6         | 2.12%   |
| Dell OptiPlex         | 5         | 1.77%   |
| Lenovo ThinkCentre    | 4         | 1.41%   |
| ASUS VivoBook         | 4         | 1.41%   |
| Standard SF20BA2      | 3         | 1.06%   |
| Lenovo IdeaCentre     | 3         | 1.06%   |
| ASUS ZenBook          | 3         | 1.06%   |
| ASUS PRIME            | 3         | 1.06%   |
| Unknown               | 3         | 1.06%   |
| MSI MS-7C37           | 2         | 0.71%   |
| MSI MS-7817           | 2         | 0.71%   |
| MSI MS-7721           | 2         | 0.71%   |
| HP Stream             | 2         | 0.71%   |
| HP Notebook           | 2         | 0.71%   |
| HP ENVY               | 2         | 0.71%   |
| HP EliteDesk          | 2         | 0.71%   |
| HP EliteBook          | 2         | 0.71%   |
| HP 240                | 2         | 0.71%   |
| Gigabyte Z390         | 2         | 0.71%   |
| Gigabyte Z370         | 2         | 0.71%   |
| Gigabyte H61M-S1      | 2         | 0.71%   |
| Dell XPS              | 2         | 0.71%   |
| Dell Precision        | 2         | 0.71%   |
| ASUS TUF              | 2         | 0.71%   |
| ASRock N68-S          | 2         | 0.71%   |
| ASRock H310CM-HDV     | 2         | 0.71%   |
| ASRock FM2A58M-VG3+   | 2         | 0.71%   |
| ASRock ALiveNF6P-VSTA | 2         | 0.71%   |
| ASRock A320M-HDV      | 2         | 0.71%   |
| Acer TravelMate       | 2         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 35        | 12.37%  |
| 2019    | 29        | 10.25%  |
| 2013    | 27        | 9.54%   |
| 2011    | 25        | 8.83%   |
| 2020    | 21        | 7.42%   |
| 2015    | 21        | 7.42%   |
| 2012    | 20        | 7.07%   |
| 2018    | 19        | 6.71%   |
| 2014    | 18        | 6.36%   |
| 2016    | 16        | 5.65%   |
| 2021    | 11        | 3.89%   |
| 2010    | 8         | 2.83%   |
| 2022    | 7         | 2.47%   |
| 2009    | 7         | 2.47%   |
| 2007    | 7         | 2.47%   |
| 2008    | 4         | 1.41%   |
| 2023    | 2         | 0.71%   |
| Unknown | 2         | 0.71%   |
| 2006    | 1         | 0.35%   |
| 2005    | 1         | 0.35%   |
| 2004    | 1         | 0.35%   |
| 2003    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 168       | 59.36%  |
| Desktop     | 104       | 36.75%  |
| Mini pc     | 3         | 1.06%   |
| All in one  | 3         | 1.06%   |
| Phone       | 2         | 0.71%   |
| Convertible | 2         | 0.71%   |
| Tablet      | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 266       | 93.66%  |
| Enabled  | 18        | 6.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 283       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 72        | 25%     |
| 3.01-4.0    | 60        | 20.83%  |
| 8.01-16.0   | 43        | 14.93%  |
| 16.01-24.0  | 42        | 14.58%  |
| 1.01-2.0    | 34        | 11.81%  |
| 32.01-64.0  | 19        | 6.6%    |
| 24.01-32.0  | 9         | 3.13%   |
| 64.01-256.0 | 4         | 1.39%   |
| 2.01-3.0    | 2         | 0.69%   |
| 0.01-0.5    | 2         | 0.69%   |
| 0.51-1.0    | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 130       | 42.21%  |
| 2.01-3.0  | 75        | 24.35%  |
| 3.01-4.0  | 34        | 11.04%  |
| 4.01-8.0  | 31        | 10.06%  |
| 0.51-1.0  | 20        | 6.49%   |
| 8.01-16.0 | 12        | 3.9%    |
| 0.01-0.5  | 6         | 1.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 199       | 69.34%  |
| 2      | 59        | 20.56%  |
| 3      | 13        | 4.53%   |
| 4      | 10        | 3.48%   |
| 5      | 3         | 1.05%   |
| 0      | 2         | 0.7%    |
| 7      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 184       | 64.34%  |
| Yes       | 102       | 35.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 76.33%  |
| No        | 67        | 23.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 74.39%  |
| No        | 73        | 25.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 56.18%  |
| No        | 124       | 43.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Uruguay | 283       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Montevideo             | 216       | 72.73%  |
| Maldonado              | 14        | 4.71%   |
| Canelones              | 8         | 2.69%   |
| San Jose de Mayo       | 4         | 1.35%   |
| Punta del Este         | 4         | 1.35%   |
| Las Piedras            | 4         | 1.35%   |
| Florida                | 3         | 1.01%   |
| Ciudad del Plata       | 3         | 1.01%   |
| Buceo                  | 3         | 1.01%   |
| Salto                  | 2         | 0.67%   |
| Rocha                  | 2         | 0.67%   |
| Punta Gorda            | 2         | 0.67%   |
| Paysandú              | 2         | 0.67%   |
| Parque Rodo            | 2         | 0.67%   |
| Nueva Helvecia         | 2         | 0.67%   |
| Minas                  | 2         | 0.67%   |
| La Paz                 | 2         | 0.67%   |
| El Pinar               | 2         | 0.67%   |
| Durazno                | 2         | 0.67%   |
| Centro                 | 2         | 0.67%   |
| Solymar                | 1         | 0.34%   |
| Pocitos                | 1         | 0.34%   |
| Pinamar                | 1         | 0.34%   |
| Nuevo Paris            | 1         | 0.34%   |
| Melo                   | 1         | 0.34%   |
| Melilla                | 1         | 0.34%   |
| Maronas                | 1         | 0.34%   |
| Malvin Norte           | 1         | 0.34%   |
| Las Flores             | 1         | 0.34%   |
| La Barra               | 1         | 0.34%   |
| Joaquin Suarez         | 1         | 0.34%   |
| El Tesoro              | 1         | 0.34%   |
| Chui                   | 1         | 0.34%   |
| Barrancas Coloradas    | 1         | 0.34%   |
| Arenas de Jose Ignacio | 1         | 0.34%   |
| Unknown                | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 74        | 94     | 19.53%  |
| Seagate                     | 49        | 65     | 12.93%  |
| Kingston                    | 49        | 60     | 12.93%  |
| Toshiba                     | 39        | 49     | 10.29%  |
| Samsung Electronics         | 35        | 37     | 9.23%   |
| Unknown                     | 29        | 37     | 7.65%   |
| SanDisk                     | 16        | 19     | 4.22%   |
| Hitachi                     | 10        | 15     | 2.64%   |
| Crucial                     | 9         | 13     | 2.37%   |
| SK hynix                    | 7         | 7      | 1.85%   |
| HGST                        | 7         | 7      | 1.85%   |
| Intel                       | 5         | 5      | 1.32%   |
| Hewlett-Packard             | 5         | 5      | 1.32%   |
| Netac                       | 4         | 6      | 1.06%   |
| Maxtor                      | 3         | 4      | 0.79%   |
| Biostar                     | 3         | 4      | 0.79%   |
| Phison Electronics          | 2         | 2      | 0.53%   |
| Patriot                     | 2         | 2      | 0.53%   |
| Micron/Crucial Technology   | 2         | 3      | 0.53%   |
| Micron Technology           | 2         | 2      | 0.53%   |
| KIOXIA                      | 2         | 2      | 0.53%   |
| Kingston Technology Company | 2         | 2      | 0.53%   |
| HS-SSD-C100                 | 2         | 3      | 0.53%   |
| W800SH                      | 1         | 1      | 0.26%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.26%   |
| Silicon Motion              | 1         | 1      | 0.26%   |
| SAGE                        | 1         | 2      | 0.26%   |
| Realtek Semiconductor       | 1         | 1      | 0.26%   |
| Phison                      | 1         | 1      | 0.26%   |
| NGFF                        | 1         | 1      | 0.26%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.26%   |
| LITEON                      | 1         | 2      | 0.26%   |
| KingFast                    | 1         | 1      | 0.26%   |
| IBM-ESXS                    | 1         | 1      | 0.26%   |
| Hikvision                   | 1         | 1      | 0.26%   |
| Gigabyte Technology         | 1         | 1      | 0.26%   |
| Gateway                     | 1         | 1      | 0.26%   |
| ExcelStor                   | 1         | 1      | 0.26%   |
| Dahua                       | 1         | 2      | 0.26%   |
| China                       | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 15        | 3.72%   |
| Unknown MMC Card  32GB              | 14        | 3.47%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 2.23%   |
| Toshiba DT01ACA300 3TB              | 6         | 1.49%   |
| Toshiba DT01ACA100 1TB              | 6         | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB      | 6         | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 1.24%   |
| Unknown DA4032  32GB                | 5         | 1.24%   |
| Toshiba MQ01ABD075 752GB            | 5         | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 1.24%   |
| Samsung HD161HJ 160GB               | 5         | 1.24%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 0.99%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.99%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 0.99%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 0.99%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 0.74%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.74%   |
| Toshiba MQ01ABD100 1TB              | 3         | 0.74%   |
| Toshiba HDWK105 500GB               | 3         | 0.74%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.74%   |
| SanDisk DF4032  32GB                | 3         | 0.74%   |
| Samsung SSD 860 EVO 500GB           | 3         | 0.74%   |
| Kingston SV300S37A480G 480GB SSD    | 3         | 0.74%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2         | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.5%    |
| WDC WD5000LPVT-24G33T1 500GB        | 2         | 0.5%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.5%    |
| WDC WD10EFRX-68FYTN0 1TB            | 2         | 0.5%    |
| Unknown SD/MMC/MS PRO 16GB          | 2         | 0.5%    |
| Toshiba MK5059GSXP 500GB            | 2         | 0.5%    |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 0.5%    |
| Seagate ST500DM005 HD502HJ 500GB    | 2         | 0.5%    |
| Seagate ST3750640NS 752GB           | 2         | 0.5%    |
| Seagate ST3250312AS 250GB           | 2         | 0.5%    |
| Seagate ST3160318AS 160GB           | 2         | 0.5%    |
| Seagate ST250DM000-1BD141 250GB     | 2         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 61        | 77     | 33.15%  |
| Seagate             | 49        | 65     | 26.63%  |
| Toshiba             | 35        | 45     | 19.02%  |
| Samsung Electronics | 15        | 15     | 8.15%   |
| Hitachi             | 10        | 15     | 5.43%   |
| HGST                | 7         | 7      | 3.8%    |
| Maxtor              | 3         | 4      | 1.63%   |
| Unknown             | 2         | 2      | 1.09%   |
| SAGE                | 1         | 2      | 0.54%   |
| ExcelStor           | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 40        | 46     | 40%     |
| WDC                 | 10        | 11     | 10%     |
| Samsung Electronics | 10        | 11     | 10%     |
| Crucial             | 7         | 9      | 7%      |
| SanDisk             | 5         | 5      | 5%      |
| Netac               | 4         | 6      | 4%      |
| Hewlett-Packard     | 4         | 4      | 4%      |
| SK hynix            | 2         | 2      | 2%      |
| Intel               | 2         | 2      | 2%      |
| Biostar             | 2         | 3      | 2%      |
| W800SH              | 1         | 1      | 1%      |
| Toshiba             | 1         | 1      | 1%      |
| Patriot             | 1         | 1      | 1%      |
| NGFF                | 1         | 1      | 1%      |
| Micron Technology   | 1         | 1      | 1%      |
| HS-SSD-C100         | 1         | 1      | 1%      |
| Hikvision           | 1         | 1      | 1%      |
| Gigabyte Technology | 1         | 1      | 1%      |
| Gateway             | 1         | 1      | 1%      |
| Dahua               | 1         | 2      | 1%      |
| China               | 1         | 1      | 1%      |
| BIWIN               | 1         | 1      | 1%      |
| BHT                 | 1         | 1      | 1%      |
| A-DATA Technology   | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 152       | 233    | 44.44%  |
| SSD     | 97        | 114    | 28.36%  |
| NVMe    | 58        | 76     | 16.96%  |
| MMC     | 30        | 38     | 8.77%   |
| Unknown | 5         | 7      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 212       | 345    | 69.06%  |
| NVMe | 58        | 76     | 18.89%  |
| MMC  | 30        | 38     | 9.77%   |
| SAS  | 7         | 9      | 2.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 160       | 213    | 63.75%  |
| 0.51-1.0   | 73        | 112    | 29.08%  |
| 2.01-3.0   | 8         | 10     | 3.19%   |
| 1.01-2.0   | 7         | 8      | 2.79%   |
| 3.01-4.0   | 3         | 4      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 24.24%  |
| 251-500        | 65        | 21.89%  |
| 501-1000       | 40        | 13.47%  |
| 1-20           | 36        | 12.12%  |
| 21-50          | 29        | 9.76%   |
| 1001-2000      | 21        | 7.07%   |
| 51-100         | 13        | 4.38%   |
| Unknown        | 11        | 3.7%    |
| More than 3000 | 5         | 1.68%   |
| 2001-3000      | 5         | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 42.67%  |
| 21-50          | 54        | 17.59%  |
| 51-100         | 32        | 10.42%  |
| 101-250        | 26        | 8.47%   |
| 251-500        | 25        | 8.14%   |
| 501-1000       | 16        | 5.21%   |
| Unknown        | 11        | 3.58%   |
| 1001-2000      | 7         | 2.28%   |
| 2001-3000      | 3         | 0.98%   |
| More than 3000 | 2         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB                                  | 3         | 3      | 8.33%   |
| Toshiba MK5059GSXP 500GB                                      | 2         | 3      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB                               | 2         | 2      | 5.56%   |
| Seagate ST3750640NS 752GB                                     | 2         | 7      | 5.56%   |
| Seagate ST250DM000-1BD141 250GB                               | 2         | 2      | 5.56%   |
| WDC WD5000LPCX-24C6HT0 500GB                                  | 1         | 1      | 2.78%   |
| WDC WD5000AAKX-75U6AA0 500GB                                  | 1         | 1      | 2.78%   |
| WDC WD5000AAJS-00A8B0 500GB                                   | 1         | 1      | 2.78%   |
| WDC WD3200BEVT-26ZCT0 320GB                                   | 1         | 1      | 2.78%   |
| WDC WD10SPCX-24HWST1 1TB                                      | 1         | 1      | 2.78%   |
| WDC WD10EARS-22Y5B1 1TB                                       | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD075 752GB                                      | 1         | 1      | 2.78%   |
| Toshiba MK3276GSX 320GB                                       | 1         | 1      | 2.78%   |
| Toshiba MK3265GSX 320GB                                       | 1         | 1      | 2.78%   |
| Toshiba MK3259GSXP 320GB                                      | 1         | 1      | 2.78%   |
| Toshiba DT01ACA100 1TB                                        | 1         | 1      | 2.78%   |
| Seagate ST980811AS 80GB                                       | 1         | 2      | 2.78%   |
| Seagate ST500LM021-1KJ152 500GB                               | 1         | 1      | 2.78%   |
| Seagate ST500DM005 HD502HJ 500GB                              | 1         | 1      | 2.78%   |
| Seagate ST3250310CS 250GB                                     | 1         | 1      | 2.78%   |
| Seagate ST3200827AS 200GB                                     | 1         | 1      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                                | 1         | 1      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 1         | 1      | 2.78%   |
| Seagate ST1000DM010-2EP102 1TB                                | 1         | 1      | 2.78%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                           | 1         | 1      | 2.78%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 2      | 2.78%   |
| Kingston SA400S37480G 480GB SSD                               | 1         | 1      | 2.78%   |
| HS-SSD-C100 SSD 240G                                          | 1         | 1      | 2.78%   |
| Hitachi HTS547564A9E384 640GB                                 | 1         | 1      | 2.78%   |
| HGST HTS545032A7E380 320GB                                    | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 20     | 38.24%  |
| WDC                 | 8         | 9      | 23.53%  |
| Toshiba             | 7         | 8      | 20.59%  |
| SanDisk             | 1         | 1      | 2.94%   |
| Samsung Electronics | 1         | 2      | 2.94%   |
| Kingston            | 1         | 1      | 2.94%   |
| HS-SSD-C100         | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |

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
| HDD  | 30        | 39     | 88.24%  |
| SSD  | 3         | 3      | 8.82%   |
| NVMe | 1         | 2      | 2.94%   |

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
| Detected | 175       | 278    | 58.14%  |
| Works    | 92        | 146    | 30.56%  |
| Malfunc  | 34        | 44     | 11.3%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 186       | 57.94%  |
| AMD                              | 60        | 18.69%  |
| Sandisk                          | 14        | 4.36%   |
| Samsung Electronics              | 10        | 3.12%   |
| Kingston Technology Company      | 10        | 3.12%   |
| Nvidia                           | 6         | 1.87%   |
| ASMedia Technology               | 5         | 1.56%   |
| Toshiba America Info Systems     | 4         | 1.25%   |
| SK hynix                         | 4         | 1.25%   |
| Micron/Crucial Technology        | 4         | 1.25%   |
| Silicon Motion                   | 3         | 0.93%   |
| Phison Electronics               | 3         | 0.93%   |
| Marvell Technology Group         | 2         | 0.62%   |
| VIA Technologies                 | 1         | 0.31%   |
| Union Memory (Shenzhen)          | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Realtek Semiconductor            | 1         | 0.31%   |
| Micron Technology                | 1         | 0.31%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.31%   |
| Lite-On Technology               | 1         | 0.31%   |
| KIOXIA                           | 1         | 0.31%   |
| Apple                            | 1         | 0.31%   |
| Adaptec                          | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43        | 11.65%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 20        | 5.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 3.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 3.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 2.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8         | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.9%    |
| Nvidia MCP61 SATA Controller                                                            | 6         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.63%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 5         | 1.36%   |
| Nvidia MCP61 IDE                                                                        | 5         | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.36%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.36%   |
| AMD FCH IDE Controller                                                                  | 5         | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.08%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 3         | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3         | 0.81%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3         | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.81%   |
| Intel SSD 660P Series                                                                   | 3         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 214       | 64.85%  |
| NVMe | 58        | 17.58%  |
| IDE  | 42        | 12.73%  |
| RAID | 15        | 4.55%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 205       | 72.44%  |
| AMD      | 76        | 26.86%  |
| QUALCOMM | 1         | 0.35%   |
| ARM      | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz       | 17        | 6.01%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 4         | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.06%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 3         | 1.06%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 3         | 1.06%   |
| Intel Celeron CPU J3355 @ 2.00GHz       | 3         | 1.06%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 3         | 1.06%   |
| AMD Ryzen 9 4900HS with Radeon Graphics | 3         | 1.06%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 3         | 1.06%   |
| AMD E-300 APU with Radeon HD Graphics   | 3         | 1.06%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 2         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.71%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.71%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.71%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.71%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 2         | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 0.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.71%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 2         | 0.71%   |
| Intel Core i3-4170 CPU @ 3.70GHz        | 2         | 0.71%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 2         | 0.71%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 0.71%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 2         | 0.71%   |
| Intel Celeron CPU N2830 @ 2.16GHz       | 2         | 0.71%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 2         | 0.71%   |
| Intel 12th Gen Core i7-1255U            | 2         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 50        | 17.67%  |
| Intel Celeron      | 42        | 14.84%  |
| Intel Core i7      | 41        | 14.49%  |
| Intel Core i3      | 28        | 9.89%   |
| Other              | 10        | 3.53%   |
| AMD Ryzen 5        | 10        | 3.53%   |
| Intel Pentium      | 9         | 3.18%   |
| Intel Core 2 Duo   | 8         | 2.83%   |
| Intel Atom         | 8         | 2.83%   |
| AMD Ryzen 7        | 8         | 2.83%   |
| AMD A6             | 8         | 2.83%   |
| AMD Ryzen 9        | 5         | 1.77%   |
| AMD Athlon II X2   | 5         | 1.77%   |
| Intel Xeon         | 4         | 1.41%   |
| AMD Ryzen 3        | 4         | 1.41%   |
| AMD FX             | 4         | 1.41%   |
| AMD A10            | 4         | 1.41%   |
| Intel Core 2 Quad  | 3         | 1.06%   |
| AMD Phenom II X6   | 3         | 1.06%   |
| AMD E              | 3         | 1.06%   |
| AMD Athlon         | 3         | 1.06%   |
| AMD A8             | 3         | 1.06%   |
| AMD A4             | 3         | 1.06%   |
| Intel Genuine      | 2         | 0.71%   |
| AMD E1             | 2         | 0.71%   |
| QUALCOMM AArch64   | 1         | 0.35%   |
| Intel Pentium Dual | 1         | 0.35%   |
| Intel Pentium 4    | 1         | 0.35%   |
| Intel Core i9      | 1         | 0.35%   |
| ARM AArch64        | 1         | 0.35%   |
| AMD Ryzen 5 PRO    | 1         | 0.35%   |
| AMD PRO A10        | 1         | 0.35%   |
| AMD Phenom II      | 1         | 0.35%   |
| AMD Phenom         | 1         | 0.35%   |
| AMD E2             | 1         | 0.35%   |
| AMD Athlon II      | 1         | 0.35%   |
| AMD Athlon 64 X2   | 1         | 0.35%   |
| AMD Athlon 64      | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 143       | 50.53%  |
| 4      | 82        | 28.98%  |
| 6      | 29        | 10.25%  |
| 8      | 18        | 6.36%   |
| 1      | 8         | 2.83%   |
| 10     | 2         | 0.71%   |
| 14     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 280       | 98.94%  |
| 2      | 3         | 1.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 159       | 56.18%  |
| 1      | 124       | 43.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 276       | 97.53%  |
| Unknown        | 5         | 1.77%   |
| 32-bit         | 2         | 0.71%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 30.03%  |
| 0x206a7    | 14        | 4.78%   |
| 0x306c3    | 9         | 3.07%   |
| 0x306a9    | 9         | 3.07%   |
| 0x906ea    | 8         | 2.73%   |
| 0x506c9    | 8         | 2.73%   |
| 0x406c4    | 8         | 2.73%   |
| 0x20655    | 7         | 2.39%   |
| 0x806e9    | 6         | 2.05%   |
| 0x40651    | 6         | 2.05%   |
| 0x1067a    | 6         | 2.05%   |
| 0x806ec    | 5         | 1.71%   |
| 0x406e3    | 5         | 1.71%   |
| 0x406c3    | 5         | 1.71%   |
| 0x306d4    | 5         | 1.71%   |
| 0x08108109 | 5         | 1.71%   |
| 0x806ea    | 4         | 1.37%   |
| 0x6fd      | 4         | 1.37%   |
| 0x506e3    | 4         | 1.37%   |
| 0x30678    | 4         | 1.37%   |
| 0x08701021 | 4         | 1.37%   |
| 0x806c1    | 3         | 1.02%   |
| 0x0a50000c | 3         | 1.02%   |
| 0x06006705 | 3         | 1.02%   |
| 0x06001119 | 3         | 1.02%   |
| 0x06000852 | 3         | 1.02%   |
| 0xa0655    | 2         | 0.68%   |
| 0xa0653    | 2         | 0.68%   |
| 0x906eb    | 2         | 0.68%   |
| 0x706e5    | 2         | 0.68%   |
| 0x706a1    | 2         | 0.68%   |
| 0x206d7    | 2         | 0.68%   |
| 0x10676    | 2         | 0.68%   |
| 0x08600104 | 2         | 0.68%   |
| 0x0810100b | 2         | 0.68%   |
| 0x08001138 | 2         | 0.68%   |
| 0x07030105 | 2         | 0.68%   |
| 0x07030104 | 2         | 0.68%   |
| 0x0700010f | 2         | 0.68%   |
| 0x0600611a | 2         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 33        | 11.66%  |
| Silvermont    | 22        | 7.77%   |
| SandyBridge   | 20        | 7.07%   |
| IvyBridge     | 20        | 7.07%   |
| Haswell       | 20        | 7.07%   |
| Goldmont      | 20        | 7.07%   |
| Skylake       | 12        | 4.24%   |
| K10           | 11        | 3.89%   |
| Zen 2         | 10        | 3.53%   |
| Zen+          | 9         | 3.18%   |
| Penryn        | 9         | 3.18%   |
| CometLake     | 9         | 3.18%   |
| Broadwell     | 8         | 2.83%   |
| Westmere      | 7         | 2.47%   |
| Piledriver    | 7         | 2.47%   |
| Excavator     | 7         | 2.47%   |
| Unknown       | 7         | 2.47%   |
| Zen 3         | 6         | 2.12%   |
| Puma          | 6         | 2.12%   |
| Core          | 6         | 2.12%   |
| Zen           | 5         | 1.77%   |
| TigerLake     | 4         | 1.41%   |
| Steamroller   | 4         | 1.41%   |
| Jaguar        | 3         | 1.06%   |
| IceLake       | 3         | 1.06%   |
| Bobcat        | 3         | 1.06%   |
| Tremont       | 2         | 0.71%   |
| NetBurst      | 2         | 0.71%   |
| K8 Hammer     | 2         | 0.71%   |
| Goldmont plus | 2         | 0.71%   |
| Bonnell       | 2         | 0.71%   |
| Nehalem       | 1         | 0.35%   |
| K10 Llano     | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 175       | 55.21%  |
| AMD                              | 73        | 23.03%  |
| Nvidia                           | 68        | 21.45%  |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 20        | 6.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 4.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 4.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.47%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.16%   |
| Intel HD Graphics 620                                                                    | 6         | 1.85%   |
| Intel HD Graphics 530                                                                    | 6         | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.85%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 1.85%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.23%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.23%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 0.93%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 0.93%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.93%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 0.93%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.93%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 147       | 51.76%  |
| 1 x AMD        | 53        | 18.66%  |
| 1 x Nvidia     | 44        | 15.49%  |
| Intel + Nvidia | 16        | 5.63%   |
| Intel + AMD    | 8         | 2.82%   |
| AMD + Nvidia   | 8         | 2.82%   |
| 2 x AMD        | 4         | 1.41%   |
| Other          | 3         | 1.06%   |
| 1 x SiS        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 242       | 84.62%  |
| Proprietary | 32        | 11.19%  |
| Unknown     | 12        | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 180       | 61.86%  |
| 1.01-2.0   | 29        | 9.97%   |
| 0.01-0.5   | 28        | 9.62%   |
| 0.51-1.0   | 26        | 8.93%   |
| 3.01-4.0   | 17        | 5.84%   |
| 5.01-6.0   | 5         | 1.72%   |
| 7.01-8.0   | 4         | 1.37%   |
| 2.01-3.0   | 1         | 0.34%   |
| 8.01-16.0  | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 33        | 11.5%   |
| LG Display              | 30        | 10.45%  |
| Chimei Innolux          | 27        | 9.41%   |
| AU Optronics            | 26        | 9.06%   |
| BOE                     | 24        | 8.36%   |
| AOC                     | 20        | 6.97%   |
| ViewSonic               | 18        | 6.27%   |
| KTC                     | 10        | 3.48%   |
| Goldstar                | 9         | 3.14%   |
| InfoVision              | 8         | 2.79%   |
| Acer                    | 8         | 2.79%   |
| KDC                     | 7         | 2.44%   |
| Lenovo                  | 6         | 2.09%   |
| Dell                    | 6         | 2.09%   |
| PANDA                   | 5         | 1.74%   |
| Hewlett-Packard         | 5         | 1.74%   |
| Chi Mei Optoelectronics | 5         | 1.74%   |
| Unknown                 | 4         | 1.39%   |
| Sharp                   | 4         | 1.39%   |
| Ancor Communications    | 3         | 1.05%   |
| LG Philips              | 2         | 0.7%    |
| HSI                     | 2         | 0.7%    |
| HKC                     | 2         | 0.7%    |
| Apple                   | 2         | 0.7%    |
| Valve                   | 1         | 0.35%   |
| Toshiba                 | 1         | 0.35%   |
| TMX                     | 1         | 0.35%   |
| Sun                     | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| RIS                     | 1         | 0.35%   |
| Philips                 | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| Mi                      | 1         | 0.35%   |
| LG Electronics          | 1         | 0.35%   |
| Lenovo Group Limited    | 1         | 0.35%   |
| KVM                     | 1         | 0.35%   |
| Konka                   | 1         | 0.35%   |
| KOA                     | 1         | 0.35%   |
| JDI                     | 1         | 0.35%   |
| InnoLux Display         | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 2.02%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 5         | 1.68%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch            | 4         | 1.35%   |
| Lenovo LEN-AIO-330-E LEN0017 1440x900 420x270mm 19.7-inch                | 3         | 1.01%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                     | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.01%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 1.01%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.01%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch               | 2         | 0.67%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                         | 2         | 0.67%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                  | 2         | 0.67%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch      | 2         | 0.67%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch        | 2         | 0.67%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.67%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.67%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.67%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 2         | 0.67%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch              | 2         | 0.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.67%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch                 | 2         | 0.67%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.67%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.67%   |
| HSI LED-TV HSI0001 1920x1080 708x398mm 32.0-inch                         | 2         | 0.67%   |
| HKC '' HKC1850 1360x768 409x230mm 18.5-inch                              | 2         | 0.67%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                         | 2         | 0.67%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 2         | 0.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 0.67%   |
| AOC 2461W AOC2461 1920x1080 521x293mm 23.5-inch                          | 2         | 0.67%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.67%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.67%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.67%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                           | 2         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 98        | 36.7%   |
| 1920x1080 (FHD)    | 84        | 31.46%  |
| 1600x900 (HD+)     | 14        | 5.24%   |
| 3840x2160 (4K)     | 9         | 3.37%   |
| 2560x1440 (QHD)    | 8         | 3%      |
| 1920x1200 (WUXGA)  | 8         | 3%      |
| 1440x900 (WXGA+)   | 7         | 2.62%   |
| 1280x1024 (SXGA)   | 6         | 2.25%   |
| 1360x768           | 5         | 1.87%   |
| Unknown            | 5         | 1.87%   |
| 1680x1050 (WSXGA+) | 4         | 1.5%    |
| 1280x800 (WXGA)    | 4         | 1.5%    |
| 2960x900           | 2         | 0.75%   |
| 2560x1600          | 2         | 0.75%   |
| 1280x720 (HD)      | 2         | 0.75%   |
| 800x1280           | 1         | 0.37%   |
| 3600x1080          | 1         | 0.37%   |
| 3440x1440          | 1         | 0.37%   |
| 2944x1080          | 1         | 0.37%   |
| 2560x1080          | 1         | 0.37%   |
| 2288x1287          | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 1280x768           | 1         | 0.37%   |
| 1024x600           | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 87        | 30.31%  |
| 14      | 29        | 10.1%   |
| 13      | 27        | 9.41%   |
| 21      | 21        | 7.32%   |
| 23      | 20        | 6.97%   |
| 18      | 14        | 4.88%   |
| 24      | 13        | 4.53%   |
| 17      | 12        | 4.18%   |
| Unknown | 10        | 3.48%   |
| 11      | 8         | 2.79%   |
| 19      | 6         | 2.09%   |
| 27      | 5         | 1.74%   |
| 34      | 4         | 1.39%   |
| 20      | 4         | 1.39%   |
| 40      | 3         | 1.05%   |
| 32      | 3         | 1.05%   |
| 31      | 3         | 1.05%   |
| 84      | 2         | 0.7%    |
| 44      | 2         | 0.7%    |
| 22      | 2         | 0.7%    |
| 12      | 2         | 0.7%    |
| 10      | 2         | 0.7%    |
| 86      | 1         | 0.35%   |
| 57      | 1         | 0.35%   |
| 52      | 1         | 0.35%   |
| 48      | 1         | 0.35%   |
| 29      | 1         | 0.35%   |
| 26      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 7       | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 135       | 47.7%   |
| 401-500     | 44        | 15.55%  |
| 501-600     | 37        | 13.07%  |
| 201-300     | 20        | 7.07%   |
| 351-400     | 14        | 4.95%   |
| Unknown     | 10        | 3.53%   |
| 701-800     | 7         | 2.47%   |
| 601-700     | 4         | 1.41%   |
| 1001-1500   | 4         | 1.41%   |
| 801-900     | 3         | 1.06%   |
| 1501-2000   | 2         | 0.71%   |
| 901-1000    | 2         | 0.71%   |
| 1-100       | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 208       | 82.87%  |
| 16/10   | 20        | 7.97%   |
| Unknown | 10        | 3.98%   |
| 5/4     | 6         | 2.39%   |
| 21/9    | 4         | 1.59%   |
| 3/2     | 1         | 0.4%    |
| 0.67    | 1         | 0.4%    |
| 0.56    | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 30.28%  |
| 81-90          | 50        | 17.61%  |
| 201-250        | 44        | 15.49%  |
| 151-200        | 19        | 6.69%   |
| 141-150        | 14        | 4.93%   |
| 351-500        | 10        | 3.52%   |
| Unknown        | 10        | 3.52%   |
| 51-60          | 8         | 2.82%   |
| 121-130        | 8         | 2.82%   |
| More than 1000 | 6         | 2.11%   |
| 71-80          | 6         | 2.11%   |
| 301-350        | 6         | 2.11%   |
| 501-1000       | 5         | 1.76%   |
| 251-300        | 4         | 1.41%   |
| 61-70          | 2         | 0.7%    |
| 41-50          | 2         | 0.7%    |
| 131-140        | 2         | 0.7%    |
| 1-40           | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 106       | 38.27%  |
| 51-100        | 91        | 32.85%  |
| 121-160       | 49        | 17.69%  |
| 161-240       | 12        | 4.33%   |
| Unknown       | 10        | 3.61%   |
| 1-50          | 7         | 2.53%   |
| More than 240 | 2         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 225       | 77.05%  |
| 2     | 46        | 15.75%  |
| 0     | 16        | 5.48%   |
| 3     | 4         | 1.37%   |
| 4     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 147       | 36.03%  |
| Intel                            | 119       | 29.17%  |
| Qualcomm Atheros                 | 51        | 12.5%   |
| Broadcom                         | 26        | 6.37%   |
| Ralink Technology                | 12        | 2.94%   |
| TP-Link                          | 9         | 2.21%   |
| Nvidia                           | 6         | 1.47%   |
| MediaTek                         | 6         | 1.47%   |
| Broadcom Limited                 | 5         | 1.23%   |
| Ralink                           | 4         | 0.98%   |
| Xiaomi                           | 3         | 0.74%   |
| Samsung Electronics              | 3         | 0.74%   |
| Huawei Technologies              | 3         | 0.74%   |
| Mercucys                         | 2         | 0.49%   |
| ASIX Electronics                 | 2         | 0.49%   |
| VIA Technologies                 | 1         | 0.25%   |
| Texas Instruments                | 1         | 0.25%   |
| T & A Mobile Phones              | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Sierra Wireless                  | 1         | 0.25%   |
| Qualcomm Atheros Communications  | 1         | 0.25%   |
| Qualcomm                         | 1         | 0.25%   |
| Marvell Technology Group         | 1         | 0.25%   |
| Lenovo                           | 1         | 0.25%   |
| DisplayLink                      | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 20.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 5.76%   |
| Intel Wireless 3165                                               | 27        | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.92%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 1.49%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.49%   |
| Intel Wireless 7265                                               | 7         | 1.49%   |
| Nvidia MCP61 Ethernet                                             | 6         | 1.28%   |
| Intel Wireless 8260                                               | 6         | 1.28%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 1.07%   |
| Intel Wireless 7260                                               | 5         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.07%   |
| TP-Link 802.11ac NIC                                              | 4         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.64%   |
| Huawei E353/E3131                                                 | 3         | 0.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 38.33%  |
| Realtek Semiconductor           | 51        | 22.47%  |
| Qualcomm Atheros                | 36        | 15.86%  |
| Broadcom                        | 18        | 7.93%   |
| Ralink Technology               | 12        | 5.29%   |
| TP-Link                         | 8         | 3.52%   |
| MediaTek                        | 5         | 2.2%    |
| Ralink                          | 4         | 1.76%   |
| Mercucys                        | 2         | 0.88%   |
| Broadcom Limited                | 2         | 0.88%   |
| Sierra Wireless                 | 1         | 0.44%   |
| Qualcomm Atheros Communications | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 27        | 11.84%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.95%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 3.07%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.07%   |
| Intel Wireless 7265                                                     | 7         | 3.07%   |
| Intel Wireless 8260                                                     | 6         | 2.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 2.19%   |
| Intel Wireless 7260                                                     | 5         | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.19%   |
| TP-Link 802.11ac NIC                                                    | 4         | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 4         | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.88%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.88%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.88%   |
| Mercucys 802.11n NIC                                                    | 2         | 0.88%   |
| Intel Wireless 3160                                                     | 2         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 130       | 54.85%  |
| Intel                            | 50        | 21.1%   |
| Qualcomm Atheros                 | 17        | 7.17%   |
| Broadcom                         | 11        | 4.64%   |
| Nvidia                           | 6         | 2.53%   |
| Xiaomi                           | 3         | 1.27%   |
| Samsung Electronics              | 3         | 1.27%   |
| Huawei Technologies              | 3         | 1.27%   |
| Broadcom Limited                 | 3         | 1.27%   |
| ASIX Electronics                 | 2         | 0.84%   |
| VIA Technologies                 | 1         | 0.42%   |
| TP-Link                          | 1         | 0.42%   |
| T & A Mobile Phones              | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Qualcomm                         | 1         | 0.42%   |
| MediaTek                         | 1         | 0.42%   |
| Marvell Technology Group         | 1         | 0.42%   |
| Lenovo                           | 1         | 0.42%   |
| DisplayLink                      | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 40.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 11.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 4.6%    |
| Nvidia MCP61 Ethernet                                             | 6         | 2.51%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.67%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.26%   |
| Huawei E353/E3131                                                 | 3         | 1.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.84%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 0.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.84%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.42%   |
| T & A Mobile Phones TCL 20E                                       | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.42%   |
| Samsung Kiera                                                     | 1         | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.42%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.42%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 216       | 50.23%  |
| WiFi     | 212       | 49.3%   |
| Modem    | 2         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 64.54%  |
| Ethernet | 100       | 35.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 146       | 51.59%  |
| 2     | 124       | 43.82%  |
| 0     | 10        | 3.53%   |
| 3     | 3         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 68.18%  |
| Yes  | 91        | 31.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 48.75%  |
| Realtek Semiconductor           | 18        | 11.25%  |
| Qualcomm Atheros Communications | 15        | 9.38%   |
| Cambridge Silicon Radio         | 10        | 6.25%   |
| IMC Networks                    | 9         | 5.63%   |
| Toshiba                         | 7         | 4.38%   |
| Foxconn / Hon Hai               | 5         | 3.13%   |
| Broadcom                        | 5         | 3.13%   |
| Lite-On Technology              | 4         | 2.5%    |
| Apple                           | 3         | 1.88%   |
| Ralink                          | 2         | 1.25%   |
| TP-Link                         | 1         | 0.63%   |
| Ralink Technology               | 1         | 0.63%   |
| Foxconn International           | 1         | 0.63%   |
| Alps Electric                   | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 47        | 29.38%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 5.63%   |
| Intel AX200 Bluetooth                               | 9         | 5.63%   |
| Realtek Bluetooth Radio                             | 7         | 4.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4.38%   |
| Intel AX201 Bluetooth                               | 6         | 3.75%   |
| Intel Bluetooth Device                              | 5         | 3.13%   |
| Toshiba Bluetooth Device                            | 3         | 1.88%   |
| Toshiba BCM43142A0                                  | 3         | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.88%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.88%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.88%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.25%   |
| Lite-On Bluetooth Device                            | 2         | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.25%   |
| IMC Networks Wireless_Device                        | 2         | 1.25%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.25%   |
| TP-Link UB500 Adapter                               | 1         | 0.63%   |
| Toshiba Bluetooth Radio                             | 1         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.63%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.63%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.63%   |
| IMC Networks Bluetooth Device                       | 1         | 0.63%   |
| IMC Networks Bluetooth                              | 1         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.63%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.63%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.63%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.63%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 197       | 54.57%  |
| AMD                                  | 72        | 19.94%  |
| Nvidia                               | 58        | 16.07%  |
| Logitech                             | 8         | 2.22%   |
| C-Media Electronics                  | 3         | 0.83%   |
| VIA Technologies                     | 2         | 0.55%   |
| Texas Instruments                    | 2         | 0.55%   |
| Samson Technologies                  | 2         | 0.55%   |
| Kingston Technology                  | 2         | 0.55%   |
| Generalplus Technology               | 2         | 0.55%   |
| Focusrite-Novation                   | 2         | 0.55%   |
| Creative Labs                        | 2         | 0.55%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.28%   |
| Rockwell International               | 1         | 0.28%   |
| KTMicro                              | 1         | 0.28%   |
| JMTek                                | 1         | 0.28%   |
| Elgato Systems                       | 1         | 0.28%   |
| DSEA A/S                             | 1         | 0.28%   |
| Creative Technology                  | 1         | 0.28%   |
| ASUSTek Computer                     | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 4.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 4.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 4.51%   |
| AMD FCH Azalia Controller                                                                         | 20        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 4.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 3.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.81%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.81%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.58%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.13%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.13%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 4         | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 34        | 18.99%  |
| Micron Technology            | 21        | 11.73%  |
| Kingston                     | 21        | 11.73%  |
| SK hynix                     | 19        | 10.61%  |
| Crucial                      | 19        | 10.61%  |
| Unknown                      | 16        | 8.94%   |
| Ramaxel Technology           | 7         | 3.91%   |
| Goldkey                      | 6         | 3.35%   |
| A-DATA Technology            | 5         | 2.79%   |
| Nanya Technology             | 4         | 2.23%   |
| Hikvision                    | 4         | 2.23%   |
| Elpida                       | 4         | 2.23%   |
| Team                         | 3         | 1.68%   |
| Patriot                      | 3         | 1.68%   |
| Corsair                      | 2         | 1.12%   |
| Unknown (89F7)               | 1         | 0.56%   |
| Unknown (2C0B)               | 1         | 0.56%   |
| Unknown (0x5846)             | 1         | 0.56%   |
| Smart                        | 1         | 0.56%   |
| Patriot Memory (PDP Systems) | 1         | 0.56%   |
| Netac                        | 1         | 0.56%   |
| KLEVV                        | 1         | 0.56%   |
| Infineon                     | 1         | 0.56%   |
| GeIL                         | 1         | 0.56%   |
| Avant                        | 1         | 0.56%   |
| Unknown                      | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 4         | 2.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 1.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 1.6%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s        | 3         | 1.6%    |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s         | 3         | 1.6%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 2         | 1.06%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 1.06%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 1.06%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s              | 2         | 1.06%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.06%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.06%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s           | 2         | 1.06%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 1.06%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.06%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 1.06%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1         | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1         | 0.53%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.53%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s        | 1         | 0.53%   |
| Unknown (89F7) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 0.53%   |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s              | 1         | 0.53%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1         | 0.53%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s         | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s         | 1         | 0.53%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                    | 1         | 0.53%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s           | 1         | 0.53%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.53%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.53%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 48.25%  |
| DDR4    | 55        | 38.46%  |
| LPDDR3  | 4         | 2.8%    |
| DDR2    | 4         | 2.8%    |
| SDRAM   | 3         | 2.1%    |
| LPDDR4  | 3         | 2.1%    |
| Unknown | 3         | 2.1%    |
| DDR5    | 1         | 0.7%    |
| DDR     | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 53.57%  |
| DIMM         | 56        | 40%     |
| Row Of Chips | 8         | 5.71%   |
| RIMM         | 1         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 31.58%  |
| 4096  | 48        | 28.07%  |
| 2048  | 29        | 16.96%  |
| 16384 | 27        | 15.79%  |
| 32768 | 8         | 4.68%   |
| 1024  | 3         | 1.75%   |
| 512   | 1         | 0.58%   |
| 256   | 1         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 50        | 30.86%  |
| 2667  | 25        | 15.43%  |
| 1333  | 17        | 10.49%  |
| 3200  | 13        | 8.02%   |
| 2400  | 8         | 4.94%   |
| 2133  | 8         | 4.94%   |
| 1334  | 5         | 3.09%   |
| 3600  | 4         | 2.47%   |
| 533   | 4         | 2.47%   |
| 3266  | 3         | 1.85%   |
| 1867  | 3         | 1.85%   |
| 4199  | 2         | 1.23%   |
| 3800  | 2         | 1.23%   |
| 3000  | 2         | 1.23%   |
| 1067  | 2         | 1.23%   |
| 4800  | 1         | 0.62%   |
| 4267  | 1         | 0.62%   |
| 3733  | 1         | 0.62%   |
| 3500  | 1         | 0.62%   |
| 3466  | 1         | 0.62%   |
| 3400  | 1         | 0.62%   |
| 2666  | 1         | 0.62%   |
| 2473  | 1         | 0.62%   |
| 2176  | 1         | 0.62%   |
| 1866  | 1         | 0.62%   |
| 1800  | 1         | 0.62%   |
| 1066  | 1         | 0.62%   |
| 333   | 1         | 0.62%   |
| 266   | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Xerox Phaser 3040    | 1         | 20%     |
| Samsung M288x Series | 1         | 20%     |
| HP Laser 107a        | 1         | 20%     |
| Brother DCP-T500W    | 1         | 20%     |
| Brother DCP-T420W    | 1         | 20%     |

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
| Chicony Electronics                    | 43        | 24.16%  |
| Realtek Semiconductor                  | 16        | 8.99%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 8.43%   |
| Microdia                               | 10        | 5.62%   |
| Sunplus Innovation Technology          | 9         | 5.06%   |
| Logitech                               | 9         | 5.06%   |
| Bison Electronics                      | 9         | 5.06%   |
| Suyin                                  | 7         | 3.93%   |
| IMC Networks                           | 7         | 3.93%   |
| Unknown                                | 6         | 3.37%   |
| Acer                                   | 6         | 3.37%   |
| Silicon Motion                         | 4         | 2.25%   |
| Samsung Electronics                    | 4         | 2.25%   |
| Quanta                                 | 4         | 2.25%   |
| Lite-On Technology                     | 4         | 2.25%   |
| Syntek                                 | 3         | 1.69%   |
| Sonix Technology                       | 3         | 1.69%   |
| Importek                               | 3         | 1.69%   |
| Apple                                  | 3         | 1.69%   |
| Alcor Micro                            | 3         | 1.69%   |
| Luxvisions Innotech Limited            | 2         | 1.12%   |
| Sony                                   | 1         | 0.56%   |
| Primax Electronics                     | 1         | 0.56%   |
| Novatek Microelectronics               | 1         | 0.56%   |
| GEMBIRD                                | 1         | 0.56%   |
| DigiTech                               | 1         | 0.56%   |
| Aveo Technology                        | 1         | 0.56%   |
| A4Tech                                 | 1         | 0.56%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 16        | 8.99%   |
| Chicony Integrated Camera                                      | 7         | 3.93%   |
| Acer Integrated Camera                                         | 6         | 3.37%   |
| Unknown USB Camera                                             | 5         | 2.81%   |
| Chicony HP Truevision HD                                       | 5         | 2.81%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 4         | 2.25%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.25%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.25%   |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 2.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.25%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.69%   |
| Logitech Webcam C270                                           | 3         | 1.69%   |
| Chicony HD WebCam                                              | 3         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.69%   |
| Bison HD Webcam                                                | 3         | 1.69%   |
| Syntek Integrated Camera                                       | 2         | 1.12%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 1.12%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.12%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.12%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.12%   |
| Microdia USB 2.0 Camera                                        | 2         | 1.12%   |
| Lite-On Integrated Camera                                      | 2         | 1.12%   |
| Lite-On HP Webcam                                              | 2         | 1.12%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.12%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.12%   |
| IMC Networks Integrated Camera                                 | 2         | 1.12%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.12%   |
| Bison Lenovo EasyCamera                                        | 2         | 1.12%   |
| Bison Integrated Camera                                        | 2         | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 1.12%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.12%   |
| Unknown HD camera                                              | 1         | 0.56%   |
| Syntek EasyCamera                                              | 1         | 0.56%   |
| Suyin VGA Webcam                                               | 1         | 0.56%   |
| Suyin HP Truevision HD                                         | 1         | 0.56%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.56%   |
| Suyin HD WebCam                                                | 1         | 0.56%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 40%     |
| Synaptics                  | 3         | 15%     |
| Shenzhen Goodix Technology | 3         | 15%     |
| Elan Microelectronics      | 2         | 10%     |
| Upek                       | 1         | 5%      |
| LighTuning Technology      | 1         | 5%      |
| Focal-systems.Corp         | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 15%     |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 15%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 10%     |
| Elan ELAN:Fingerprint                                  | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5%      |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5%      |
| Validity Sensors Fingerprint scanner                   | 1         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5%      |
| Synaptics UWP WBDI Device                              | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5%      |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5%      |
| AuthenTec Fingerprint Sensor                           | 1         | 5%      |

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
| 0     | 229       | 79.24%  |
| 1     | 54        | 18.69%  |
| 2     | 5         | 1.73%   |
| 3     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 29.23%  |
| Net/wireless             | 14        | 21.54%  |
| Graphics card            | 13        | 20%     |
| Multimedia controller    | 6         | 9.23%   |
| Chipcard                 | 3         | 4.62%   |
| Unassigned class         | 2         | 3.08%   |
| Storage                  | 2         | 3.08%   |
| Sound                    | 2         | 3.08%   |
| Bluetooth                | 2         | 3.08%   |
| Modem                    | 1         | 1.54%   |
| Communication controller | 1         | 1.54%   |


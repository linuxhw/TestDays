Linux in Uruguay - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 214

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | One S1002                   | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Fujitsu       | LIFEBOOK E734               | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | Pavilion g6                 | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| Toshiba       | Satellite C645D             | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Apple         | MacBookPro9,2               | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| Acer          | Aspire 4315                 | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| HP            | Notebook                    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| HP            | Notebook                    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| Dell          | Latitude 5530               | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| Toshiba       | Satellite L45-B             | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | 240 G4                      | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| Standard      | SF20BA2                     | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| Intel         | EF20                        | [120257faca](https://linux-hardware.org/?probe=120257faca) | Apr 04, 2023 |
| Acer          | Aspire 4315                 | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| Toshiba       | Satellite C75D-B            | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| Dell          | Latitude 7310               | [6b5de5fe3c](https://linux-hardware.org/?probe=6b5de5fe3c) | Mar 17, 2023 |
| Standard      | SF20BA                      | [e85dc022b5](https://linux-hardware.org/?probe=e85dc022b5) | Mar 15, 2023 |
| HP            | Laptop 17-ak0xx             | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| HP            | EliteBook 840 G3            | [41bf4fb877](https://linux-hardware.org/?probe=41bf4fb877) | Mar 10, 2023 |
| Dell          | Latitude 3150               | [f1554a5df0](https://linux-hardware.org/?probe=f1554a5df0) | Mar 05, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| ECS           | SF20PA2                     | [f0ad83686f](https://linux-hardware.org/?probe=f0ad83686f) | Feb 21, 2023 |
| HP            | 15 Notebook PC              | [c5256638eb](https://linux-hardware.org/?probe=c5256638eb) | Feb 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS14H00     | [de5c7ac3f6](https://linux-hardware.org/?probe=de5c7ac3f6) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e8183bc042](https://linux-hardware.org/?probe=e8183bc042) | Feb 16, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Gateway       | LT41P                       | [1684d937e7](https://linux-hardware.org/?probe=1684d937e7) | Feb 02, 2023 |
| HP            | 3115-AEC13432GR1            | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Valve         | Jupiter                     | [4bda80131d](https://linux-hardware.org/?probe=4bda80131d) | Jan 15, 2023 |
| Valve         | Jupiter                     | [dc137d0d08](https://linux-hardware.org/?probe=dc137d0d08) | Jan 09, 2023 |
| Toshiba       | Satellite C75D-B            | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Toshiba       | Satellite C75D-B            | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| ECS           | SF20PA2                     | [2e0892ec48](https://linux-hardware.org/?probe=2e0892ec48) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Apple         | MacBookPro9,2               | [e974c2ceff](https://linux-hardware.org/?probe=e974c2ceff) | Nov 12, 2022 |
| Alienware     | 14                          | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| Toshiba       | Satellite L45-B             | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| HP            | Laptop 17-ak0xx             | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Acer          | Aspire ES1-572              | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| Dell          | Latitude 3150               | [6bc88c696c](https://linux-hardware.org/?probe=6bc88c696c) | Sep 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| ECS           | SF20PA2                     | [67dd8af18f](https://linux-hardware.org/?probe=67dd8af18f) | Aug 23, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| Dell          | Latitude 3150               | [aecf1fe543](https://linux-hardware.org/?probe=aecf1fe543) | Aug 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [4eb7e0d085](https://linux-hardware.org/?probe=4eb7e0d085) | Jul 22, 2022 |
| GPU Compan... | GWTN156-9                   | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| iClever       | IC-T01                      | [f82c34c612](https://linux-hardware.org/?probe=f82c34c612) | Jun 17, 2022 |
| HP            | Pavilion g4                 | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | XPS 15 7590                 | [482ed9f535](https://linux-hardware.org/?probe=482ed9f535) | May 29, 2022 |
| Acer          | Swift SF314-54              | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Acer          | Swift SF314-54              | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Acer          | Swift SF314-54              | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Acer          | Swift SF314-54              | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| HP            | Laptop 14-dk1xxx            | [fa6da4906f](https://linux-hardware.org/?probe=fa6da4906f) | May 07, 2022 |
| Toshiba       | Satellite C645D             | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire ES1-572              | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| Lenovo        | B50-45 20388                | [7ad45f257f](https://linux-hardware.org/?probe=7ad45f257f) | Apr 20, 2022 |
| HP            | EliteBook 840 G1            | [d2e2811388](https://linux-hardware.org/?probe=d2e2811388) | Apr 20, 2022 |
| Dell          | Inspiron 5585               | [2c6e96d91f](https://linux-hardware.org/?probe=2c6e96d91f) | Apr 18, 2022 |
| Dell          | Inspiron 15-3567            | [73be944f6c](https://linux-hardware.org/?probe=73be944f6c) | Apr 14, 2022 |
| Dell          | Precision 7550              | [4619da9502](https://linux-hardware.org/?probe=4619da9502) | Apr 14, 2022 |
| Lenovo        | G405 20239                  | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| HP            | Laptop 14-dq1xxx            | [7d203f8bc0](https://linux-hardware.org/?probe=7d203f8bc0) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| HP            | Laptop 14-dq1xxx            | [9bf7ed495b](https://linux-hardware.org/?probe=9bf7ed495b) | Mar 28, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [d9afd858b4](https://linux-hardware.org/?probe=d9afd858b4) | Mar 23, 2022 |
| HP            | ZBook 14u G4                | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| HP            | Pavilion dv5                | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| GPU Compan... | GWTN156-4                   | [89e7b9fa39](https://linux-hardware.org/?probe=89e7b9fa39) | Mar 02, 2022 |
| ECS           | SF20PA2                     | [3bddc7e08a](https://linux-hardware.org/?probe=3bddc7e08a) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Sony          | SVF14211CLB                 | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| Acer          | Aspire 5733Z                | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [4e606c817f](https://linux-hardware.org/?probe=4e606c817f) | Nov 04, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | [c04d448530](https://linux-hardware.org/?probe=c04d448530) | Oct 21, 2021 |
| Lenovo        | B51-30 80LK                 | [dea10156c6](https://linux-hardware.org/?probe=dea10156c6) | Sep 20, 2021 |
| Haitech       | H7141A                      | [496c0eb316](https://linux-hardware.org/?probe=496c0eb316) | Sep 18, 2021 |
| ECS           | SF20PA2                     | [6d17cf08ad](https://linux-hardware.org/?probe=6d17cf08ad) | Sep 12, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| Lenovo        | ThinkPad L490 20Q6S0NF00    | [a8f222614b](https://linux-hardware.org/?probe=a8f222614b) | Aug 11, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | [4781e962e7](https://linux-hardware.org/?probe=4781e962e7) | Aug 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| HP            | Pavilion 15                 | [ec0019224a](https://linux-hardware.org/?probe=ec0019224a) | Jul 28, 2021 |
| ECS           | SF20PA2                     | [2016dfe42c](https://linux-hardware.org/?probe=2016dfe42c) | Jul 26, 2021 |
| HP            | Laptop 15-bs0xx             | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | [27582e9e17](https://linux-hardware.org/?probe=27582e9e17) | Jun 21, 2021 |
| Acer          | TravelMate 5730             | [4a21735ce1](https://linux-hardware.org/?probe=4a21735ce1) | Jun 17, 2021 |
| Acer          | Acadia V1.45                | [9357025bc9](https://linux-hardware.org/?probe=9357025bc9) | Jun 01, 2021 |
| HP            | ENVY TS 15                  | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| Positivo      | Serie AT300                 | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| HP            | Pavilion 17                 | [f12450cc62](https://linux-hardware.org/?probe=f12450cc62) | May 28, 2021 |
| Lenovo        | ThinkPad T590 20N5S2GP05    | [2444839350](https://linux-hardware.org/?probe=2444839350) | May 25, 2021 |
| Dell          | Latitude E5470              | [212d434e24](https://linux-hardware.org/?probe=212d434e24) | May 25, 2021 |
| Positivo      | Serie AT300                 | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Toshiba       | Satellite C45-A             | [cb57bbefd0](https://linux-hardware.org/?probe=cb57bbefd0) | May 22, 2021 |
| Toshiba       | Satellite C45-A             | [297e5b458a](https://linux-hardware.org/?probe=297e5b458a) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| Standard      | SF20BA2                     | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| Acer          | Acadia V1.45                | [321e5159ac](https://linux-hardware.org/?probe=321e5159ac) | May 15, 2021 |
| ECS           | SF20PA2                     | [f3cc58b0e4](https://linux-hardware.org/?probe=f3cc58b0e4) | May 13, 2021 |
| Dell          | Inspiron N5110              | [6f67fbb9d4](https://linux-hardware.org/?probe=6f67fbb9d4) | May 08, 2021 |
| ECS           | SF20PA2                     | [cfbd36f40b](https://linux-hardware.org/?probe=cfbd36f40b) | May 07, 2021 |
| Acer          | Aspire E5-521               | [d1c6c7309a](https://linux-hardware.org/?probe=d1c6c7309a) | May 03, 2021 |
| ASUSTek       | N46VJ                       | [0d6e007969](https://linux-hardware.org/?probe=0d6e007969) | Apr 28, 2021 |
| Standard      | SF20BA2                     | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| Standard      | SF20BA2                     | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Dell          | Inspiron 5565               | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | 240 G7                      | [721c4c3dbd](https://linux-hardware.org/?probe=721c4c3dbd) | Apr 14, 2021 |
| Apple         | MacBookAir7,1               | [2296b37506](https://linux-hardware.org/?probe=2296b37506) | Apr 12, 2021 |
| Acer          | Aspire 5715Z                | [9a7aa83895](https://linux-hardware.org/?probe=9a7aa83895) | Apr 07, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [118abf533e](https://linux-hardware.org/?probe=118abf533e) | Mar 28, 2021 |
| Panasonic     | CF-31JEGAX1M                | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| MSI           | GL65 Leopard 10SCXR         | [8497db47ab](https://linux-hardware.org/?probe=8497db47ab) | Mar 09, 2021 |
| HP            | Laptop 14-df0xxx            | [c1d21b6940](https://linux-hardware.org/?probe=c1d21b6940) | Mar 01, 2021 |
| Dell          | XPS 13 9370                 | [f51dac04a1](https://linux-hardware.org/?probe=f51dac04a1) | Feb 17, 2021 |
| Dell          | XPS 13 9370                 | [bea8cc11d5](https://linux-hardware.org/?probe=bea8cc11d5) | Feb 17, 2021 |
| MSI           | GL65 Leopard 10SCXR         | [ac71737361](https://linux-hardware.org/?probe=ac71737361) | Jan 16, 2021 |
| Acer          | Aspire 5733                 | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Toshiba       | Satellite L55t-B            | [ab3b576bd1](https://linux-hardware.org/?probe=ab3b576bd1) | Jan 07, 2021 |
| Toshiba       | Satellite L55t-B            | [6fc9533a15](https://linux-hardware.org/?probe=6fc9533a15) | Jan 06, 2021 |
| ECS           | SF20PA2                     | [f26e0bf23f](https://linux-hardware.org/?probe=f26e0bf23f) | Jan 04, 2021 |
| HP            | 2000                        | [99481f08e3](https://linux-hardware.org/?probe=99481f08e3) | Dec 31, 2020 |
| Panasonic     | CF-31JEGAX1M                | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | Notebook                    | [213a94eab7](https://linux-hardware.org/?probe=213a94eab7) | Dec 28, 2020 |
| HP            | Notebook                    | [bb3749dd61](https://linux-hardware.org/?probe=bb3749dd61) | Dec 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f55e2642ef](https://linux-hardware.org/?probe=f55e2642ef) | Dec 15, 2020 |
| Toshiba       | Satellite C75D-C            | [f158fc821a](https://linux-hardware.org/?probe=f158fc821a) | Nov 10, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19081a3c58](https://linux-hardware.org/?probe=19081a3c58) | Oct 27, 2020 |
| Dell          | Latitude E6430              | [8ea63ec090](https://linux-hardware.org/?probe=8ea63ec090) | Oct 23, 2020 |
| HP            | Pavilion dm4                | [21a3ef42e0](https://linux-hardware.org/?probe=21a3ef42e0) | Oct 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [64e95b4174](https://linux-hardware.org/?probe=64e95b4174) | Oct 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffffb855b](https://linux-hardware.org/?probe=0ffffb855b) | Oct 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7ddfb80220](https://linux-hardware.org/?probe=7ddfb80220) | Oct 04, 2020 |
| Toshiba       | Satellite C75D-C            | [12c65e3222](https://linux-hardware.org/?probe=12c65e3222) | Sep 25, 2020 |
| MSI           | GE62 6QD                    | [cf444064fc](https://linux-hardware.org/?probe=cf444064fc) | Sep 03, 2020 |
| HP            | Casablanca H710             | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Samsung       | NC208/NC108                 | [f425b1dc48](https://linux-hardware.org/?probe=f425b1dc48) | Aug 17, 2020 |
| Samsung       | NC208/NC108                 | [759ee832fb](https://linux-hardware.org/?probe=759ee832fb) | Aug 17, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3c55f58986](https://linux-hardware.org/?probe=3c55f58986) | Jul 03, 2020 |
| HP            | Presario CQ43               | [bba4f49ed1](https://linux-hardware.org/?probe=bba4f49ed1) | Jun 23, 2020 |
| Acer          | Aspire A715-72G             | [70acf4ea22](https://linux-hardware.org/?probe=70acf4ea22) | Jun 18, 2020 |
| HP            | Presario CQ43               | [3af51e5df2](https://linux-hardware.org/?probe=3af51e5df2) | Jun 13, 2020 |
| ECS           | SF20PA2                     | [fc1653c118](https://linux-hardware.org/?probe=fc1653c118) | Jun 10, 2020 |
| Dell          | Inspiron 5748               | [d7010adabe](https://linux-hardware.org/?probe=d7010adabe) | Jun 09, 2020 |
| OEM           | V40SI2                      | [e2ad8d9479](https://linux-hardware.org/?probe=e2ad8d9479) | Jun 06, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [13b3a46069](https://linux-hardware.org/?probe=13b3a46069) | May 27, 2020 |
| ASUSTek       | X555LAB                     | [7e4107b1b4](https://linux-hardware.org/?probe=7e4107b1b4) | May 26, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7e4e3c078f](https://linux-hardware.org/?probe=7e4e3c078f) | May 20, 2020 |
| MSI           | GL63 8RD                    | [7e41ab8d71](https://linux-hardware.org/?probe=7e41ab8d71) | May 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [3b397b64f7](https://linux-hardware.org/?probe=3b397b64f7) | May 06, 2020 |
| HP            | Laptop 15-bs0xx             | [a9832cd92e](https://linux-hardware.org/?probe=a9832cd92e) | May 05, 2020 |
| HP            | Laptop 15-bs0xx             | [a8857822b2](https://linux-hardware.org/?probe=a8857822b2) | May 03, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [8609a3503d](https://linux-hardware.org/?probe=8609a3503d) | May 02, 2020 |
| HP            | Laptop 15-bs0xx             | [7fdc3c7af9](https://linux-hardware.org/?probe=7fdc3c7af9) | May 02, 2020 |
| Lenovo        | ThinkPad X240 20AMS72901    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Standard      | EF20EA                      | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| Dell          | Inspiron N5110              | [3be039900b](https://linux-hardware.org/?probe=3be039900b) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [cf6e400de0](https://linux-hardware.org/?probe=cf6e400de0) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [bb8bd669f6](https://linux-hardware.org/?probe=bb8bd669f6) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [f1caefcea5](https://linux-hardware.org/?probe=f1caefcea5) | Apr 17, 2020 |
| HP            | 620                         | [812b274fd4](https://linux-hardware.org/?probe=812b274fd4) | Apr 13, 2020 |
| HP            | 620                         | [ca26b96168](https://linux-hardware.org/?probe=ca26b96168) | Apr 13, 2020 |
| ECS           | SF20PA2                     | [d685560200](https://linux-hardware.org/?probe=d685560200) | Feb 01, 2020 |
| ECS           | SF20PA2                     | [e6212ece14](https://linux-hardware.org/?probe=e6212ece14) | Nov 27, 2019 |
| ECS           | SF20PA2                     | [1d4a07f181](https://linux-hardware.org/?probe=1d4a07f181) | Nov 19, 2019 |
| Toshiba       | Satellite C55-B             | [1fab0cb871](https://linux-hardware.org/?probe=1fab0cb871) | Nov 16, 2019 |
| ECS           | SF20PA2                     | [063490d972](https://linux-hardware.org/?probe=063490d972) | Nov 03, 2019 |
| HP            | Laptop 14-dk0xxx            | [623c96ec6e](https://linux-hardware.org/?probe=623c96ec6e) | Oct 07, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [0925f5642c](https://linux-hardware.org/?probe=0925f5642c) | Sep 24, 2019 |
| ECS           | SF20PA2                     | [3c9b29c0c7](https://linux-hardware.org/?probe=3c9b29c0c7) | Sep 20, 2019 |
| ECS           | SF20PA2                     | [6d35e092fa](https://linux-hardware.org/?probe=6d35e092fa) | Sep 16, 2019 |
| Dell          | Inspiron 13-5368            | [0dab5b3510](https://linux-hardware.org/?probe=0dab5b3510) | Sep 15, 2019 |
| ECS           | SF20PA2                     | [80d3b6b8cf](https://linux-hardware.org/?probe=80d3b6b8cf) | Aug 04, 2019 |
| ECS           | SF20PA2                     | [a7b095e2f0](https://linux-hardware.org/?probe=a7b095e2f0) | Jul 30, 2019 |
| ECS           | SF20PA2                     | [01cad0b14a](https://linux-hardware.org/?probe=01cad0b14a) | Jul 10, 2019 |
| Acer          | TravelMate P249-G2-M        | [0e1338db33](https://linux-hardware.org/?probe=0e1338db33) | Jul 01, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [08c0f291e9](https://linux-hardware.org/?probe=08c0f291e9) | Jun 13, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [5619d594fa](https://linux-hardware.org/?probe=5619d594fa) | Jun 10, 2019 |
| Dell          | Inspiron N5040              | [b8f0a4691d](https://linux-hardware.org/?probe=b8f0a4691d) | May 17, 2019 |
| Samsung       | 700T                        | [dcf693f16f](https://linux-hardware.org/?probe=dcf693f16f) | May 11, 2019 |
| HP            | Pavilion dv6                | [36299cef92](https://linux-hardware.org/?probe=36299cef92) | Apr 17, 2019 |
| HP            | Laptop 15-db0xxx            | [b26531074c](https://linux-hardware.org/?probe=b26531074c) | Apr 16, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [7d9905cfe7](https://linux-hardware.org/?probe=7d9905cfe7) | Mar 27, 2019 |
| ASUSTek       | TP300LAB                    | [538b5e5d24](https://linux-hardware.org/?probe=538b5e5d24) | Mar 26, 2019 |
| HP            | Pavilion 15                 | [7376903dca](https://linux-hardware.org/?probe=7376903dca) | May 13, 2018 |
| HP            | Pavilion 15                 | [2cc0124d5d](https://linux-hardware.org/?probe=2cc0124d5d) | May 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 25        | 15.34%  |
| Ubuntu 18.04                 | 20        | 12.27%  |
| Ubuntu 22.04                 | 7         | 4.29%   |
| OpenMandriva 4.2             | 6         | 3.68%   |
| Manjaro                      | 6         | 3.68%   |
| KDE neon 20.04               | 6         | 3.68%   |
| OpenMandriva 4.3             | 5         | 3.07%   |
| Arch Rolling                 | 5         | 3.07%   |
| Zorin 16                     | 4         | 2.45%   |
| OpenMandriva 23.03           | 4         | 2.45%   |
| Ubuntu 21.10                 | 3         | 1.84%   |
| Ubuntu 19.04                 | 3         | 1.84%   |
| Linux Mint 19.3              | 3         | 1.84%   |
| Fedora 36                    | 3         | 1.84%   |
| Xubuntu 18.04                | 2         | 1.23%   |
| Ubuntu 21.04                 | 2         | 1.23%   |
| Ubuntu 18.10                 | 2         | 1.23%   |
| OpenMandriva 23.01           | 2         | 1.23%   |
| Linux Mint 20.1              | 2         | 1.23%   |
| Linux Mint 19.1              | 2         | 1.23%   |
| Kubuntu 18.04                | 2         | 1.23%   |
| Debian 11                    | 2         | 1.23%   |
| Zorin 15                     | 1         | 0.61%   |
| Xubuntu 20.04                | 1         | 0.61%   |
| Void Linux Rolling           | 1         | 0.61%   |
| Ubuntu MATE 20.04            | 1         | 0.61%   |
| Ubuntu 23.04                 | 1         | 0.61%   |
| Ubuntu 20.10                 | 1         | 0.61%   |
| Ubuntu 19.10                 | 1         | 0.61%   |
| Ubuntu 17.10                 | 1         | 0.61%   |
| SteamOS 3.4.4                | 1         | 0.61%   |
| ROSA R11.1                   | 1         | 0.61%   |
| Pop!_OS 22.04                | 1         | 0.61%   |
| openSUSE Leap-15.1           | 1         | 0.61%   |
| OpenMandriva 4.50            | 1         | 0.61%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.61%   |
| MX 21                        | 1         | 0.61%   |
| Manjaro 21.2.0               | 1         | 0.61%   |
| Lubuntu 20.04                | 1         | 0.61%   |
| Lubuntu 19.10                | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 64        | 40.76%  |
| OpenMandriva | 16        | 10.19%  |
| Linux Mint   | 14        | 8.92%   |
| Manjaro      | 7         | 4.46%   |
| Fedora       | 7         | 4.46%   |
| KDE neon     | 6         | 3.82%   |
| Zorin        | 5         | 3.18%   |
| Arch         | 5         | 3.18%   |
| Kubuntu      | 4         | 2.55%   |
| Endless      | 4         | 2.55%   |
| Xubuntu      | 3         | 1.91%   |
| Debian       | 3         | 1.91%   |
| Lubuntu      | 2         | 1.27%   |
| Elementary   | 2         | 1.27%   |
| ArcoLinux    | 2         | 1.27%   |
| Void Linux   | 1         | 0.64%   |
| Ubuntu MATE  | 1         | 0.64%   |
| SteamOS      | 1         | 0.64%   |
| ROSA         | 1         | 0.64%   |
| Pop!_OS      | 1         | 0.64%   |
| openSUSE     | 1         | 0.64%   |
| NixOS        | 1         | 0.64%   |
| MX           | 1         | 0.64%   |
| Gentoo       | 1         | 0.64%   |
| Feren OS     | 1         | 0.64%   |
| EndeavourOS  | 1         | 0.64%   |
| BlackPanther | 1         | 0.64%   |
| antiX        | 1         | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 6         | 3.43%   |
| 4.16.18-pa2-2bp1         | 6         | 3.43%   |
| 4.16.18-pa2-1bp5         | 5         | 2.86%   |
| 6.2.6-desktop-1omv2390   | 4         | 2.29%   |
| 5.8.0-53-generic         | 4         | 2.29%   |
| 5.5.19-bp0               | 4         | 2.29%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.29%   |
| 5.13.0-39-generic        | 4         | 2.29%   |
| 5.4.0-73-generic         | 3         | 1.71%   |
| 5.4.0-58-generic         | 3         | 1.71%   |
| 5.4.0-52-generic         | 3         | 1.71%   |
| 5.11.0-38-generic        | 3         | 1.71%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.14%   |
| 5.8.0-50-generic         | 2         | 1.14%   |
| 5.8.0-43-generic         | 2         | 1.14%   |
| 5.4.0-72-generic         | 2         | 1.14%   |
| 5.4.0-42-generic         | 2         | 1.14%   |
| 5.3.0-28-generic         | 2         | 1.14%   |
| 5.19.0-41-generic        | 2         | 1.14%   |
| 5.19.0-35-generic        | 2         | 1.14%   |
| 5.16.13-desktop-1omv4003 | 2         | 1.14%   |
| 5.15.0-46-generic        | 2         | 1.14%   |
| 5.15.0-41-generic        | 2         | 1.14%   |
| 5.13.0-40-generic        | 2         | 1.14%   |
| 5.13.0-37-generic        | 2         | 1.14%   |
| 5.13.0-30-generic        | 2         | 1.14%   |
| 5.11.12-desktop-1omv4002 | 2         | 1.14%   |
| 5.0.0-13-generic         | 2         | 1.14%   |
| 4.15.0-51-generic        | 2         | 1.14%   |
| 4.15.0-20-generic        | 2         | 1.14%   |
| 4.15.0-101-generic       | 2         | 1.14%   |
| 6.3.4-zen1-1-zen         | 1         | 0.57%   |
| 6.3.4-201.fc38.x86_64    | 1         | 0.57%   |
| 6.2.12-arch1-1           | 1         | 0.57%   |
| 6.2.0-20-generic         | 1         | 0.57%   |
| 6.1.31-2-MANJARO         | 1         | 0.57%   |
| 6.1.29_1                 | 1         | 0.57%   |
| 6.1.18-200.fc37.x86_64   | 1         | 0.57%   |
| 6.1.11-76060111-generic  | 1         | 0.57%   |
| 6.1.0-9-amd64            | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 13.53%  |
| 5.8.0   | 12        | 7.06%   |
| 5.13.0  | 12        | 7.06%   |
| 4.16.18 | 11        | 6.47%   |
| 4.15.0  | 9         | 5.29%   |
| 5.15.0  | 8         | 4.71%   |
| 5.11.0  | 6         | 3.53%   |
| 5.10.14 | 6         | 3.53%   |
| 5.0.0   | 6         | 3.53%   |
| 5.3.0   | 5         | 2.94%   |
| 5.19.0  | 5         | 2.94%   |
| 6.2.6   | 4         | 2.35%   |
| 5.5.19  | 4         | 2.35%   |
| 5.16.7  | 4         | 2.35%   |
| 4.18.0  | 4         | 2.35%   |
| 5.10.0  | 3         | 1.76%   |
| 6.3.4   | 2         | 1.18%   |
| 6.1.1   | 2         | 1.18%   |
| 5.19.12 | 2         | 1.18%   |
| 5.16.13 | 2         | 1.18%   |
| 5.11.12 | 2         | 1.18%   |
| 6.2.12  | 1         | 0.59%   |
| 6.2.0   | 1         | 0.59%   |
| 6.1.31  | 1         | 0.59%   |
| 6.1.29  | 1         | 0.59%   |
| 6.1.18  | 1         | 0.59%   |
| 6.1.11  | 1         | 0.59%   |
| 6.1.0   | 1         | 0.59%   |
| 6.0.6   | 1         | 0.59%   |
| 6.0.15  | 1         | 0.59%   |
| 6.0.12  | 1         | 0.59%   |
| 5.8.11  | 1         | 0.59%   |
| 5.8.1   | 1         | 0.59%   |
| 5.6.8   | 1         | 0.59%   |
| 5.4.60  | 1         | 0.59%   |
| 5.4.32  | 1         | 0.59%   |
| 5.2.13  | 1         | 0.59%   |
| 5.18.18 | 1         | 0.59%   |
| 5.18.13 | 1         | 0.59%   |
| 5.17.5  | 1         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 25        | 14.88%  |
| 5.8     | 14        | 8.33%   |
| 5.13    | 12        | 7.14%   |
| 5.10    | 12        | 7.14%   |
| 4.16    | 12        | 7.14%   |
| 5.15    | 10        | 5.95%   |
| 5.11    | 10        | 5.95%   |
| 4.15    | 9         | 5.36%   |
| 5.16    | 8         | 4.76%   |
| 6.1     | 7         | 4.17%   |
| 5.19    | 7         | 4.17%   |
| 6.2     | 6         | 3.57%   |
| 5.0     | 6         | 3.57%   |
| 5.3     | 5         | 2.98%   |
| 4.18    | 5         | 2.98%   |
| 5.5     | 4         | 2.38%   |
| 5.17    | 3         | 1.79%   |
| 6.3     | 2         | 1.19%   |
| 6.0     | 2         | 1.19%   |
| 5.18    | 2         | 1.19%   |
| 5.6     | 1         | 0.6%    |
| 5.2     | 1         | 0.6%    |
| 5.14    | 1         | 0.6%    |
| 4.9     | 1         | 0.6%    |
| 4.17    | 1         | 0.6%    |
| 4.13    | 1         | 0.6%    |
| 4.12    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 150       | 98.68%  |
| i686   | 2         | 1.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 53        | 33.97%  |
| KDE5            | 29        | 18.59%  |
| Unknown         | 22        | 14.1%   |
| XFCE            | 13        | 8.33%   |
| GNOME Flashback | 13        | 8.33%   |
| X-Cinnamon      | 9         | 5.77%   |
| KDE             | 5         | 3.21%   |
| MATE            | 3         | 1.92%   |
| LXQt            | 3         | 1.92%   |
| Pantheon        | 2         | 1.28%   |
| Cinnamon        | 2         | 1.28%   |
| sway            | 1         | 0.64%   |
| LeftWM          | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 119       | 77.78%  |
| Wayland | 24        | 15.69%  |
| Unknown | 9         | 5.88%   |
| Tty     | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 75        | 48.08%  |
| SDDM    | 28        | 17.95%  |
| GDM     | 23        | 14.74%  |
| GDM3    | 15        | 9.62%   |
| LightDM | 10        | 6.41%   |
| TDM     | 3         | 1.92%   |
| XDM     | 1         | 0.64%   |
| GREETD  | 1         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_UY      | 78        | 49.06%  |
| en_US      | 35        | 22.01%  |
| Unknown    | 18        | 11.32%  |
| es_ES      | 16        | 10.06%  |
| es_MX      | 5         | 3.14%   |
| es_AR      | 2         | 1.26%   |
| C          | 2         | 1.26%   |
| pt_BR      | 1         | 0.63%   |
| es_UY.UTF8 | 1         | 0.63%   |
| en_CA      | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 53.55%  |
| BIOS | 72        | 46.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 125       | 80.13%  |
| Overlay | 15        | 9.62%   |
| Btrfs   | 7         | 4.49%   |
| Unknown | 4         | 2.56%   |
| Tmpfs   | 3         | 1.92%   |
| Xfs     | 1         | 0.64%   |
| Ext3    | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 88        | 56.77%  |
| GPT     | 50        | 32.26%  |
| MBR     | 17        | 10.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 80.92%  |
| Yes       | 29        | 19.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 117       | 75.97%  |
| Yes       | 37        | 24.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 32        | 21.05%  |
| Lenovo              | 25        | 16.45%  |
| ECS                 | 16        | 10.53%  |
| Dell                | 15        | 9.87%   |
| Acer                | 13        | 8.55%   |
| ASUSTek Computer    | 12        | 7.89%   |
| Toshiba             | 9         | 5.92%   |
| Standard            | 5         | 3.29%   |
| Samsung Electronics | 4         | 2.63%   |
| MSI                 | 4         | 2.63%   |
| GPU Company         | 2         | 1.32%   |
| Gateway             | 2         | 1.32%   |
| Apple               | 2         | 1.32%   |
| Valve               | 1         | 0.66%   |
| Sony                | 1         | 0.66%   |
| Positivo            | 1         | 0.66%   |
| Panasonic           | 1         | 0.66%   |
| OEM                 | 1         | 0.66%   |
| Intel               | 1         | 0.66%   |
| iClever             | 1         | 0.66%   |
| Haitech             | 1         | 0.66%   |
| Fujitsu             | 1         | 0.66%   |
| Alienware           | 1         | 0.66%   |
| Unknown             | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 16        | 10.53%  |
| Standard SF20BA2                      | 3         | 1.97%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 1.97%   |
| Toshiba Satellite L55t-B              | 2         | 1.32%   |
| HP Pavilion 15                        | 2         | 1.32%   |
| HP Notebook                           | 2         | 1.32%   |
| HP Laptop 15-bs0xx                    | 2         | 1.32%   |
| Valve Jupiter                         | 1         | 0.66%   |
| Toshiba Satellite L45-B               | 1         | 0.66%   |
| Toshiba Satellite C855                | 1         | 0.66%   |
| Toshiba Satellite C75D-C              | 1         | 0.66%   |
| Toshiba Satellite C75D-B              | 1         | 0.66%   |
| Toshiba Satellite C645D               | 1         | 0.66%   |
| Toshiba Satellite C55-B               | 1         | 0.66%   |
| Toshiba Satellite C45-A               | 1         | 0.66%   |
| Standard SF20BA                       | 1         | 0.66%   |
| Standard EF20EA                       | 1         | 0.66%   |
| Sony SVF14211CLB                      | 1         | 0.66%   |
| Samsung NC208/NC108                   | 1         | 0.66%   |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.66%   |
| Samsung 700T                          | 1         | 0.66%   |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.66%   |
| Positivo Serie AT300                  | 1         | 0.66%   |
| Panasonic CF-31JEGAX1M                | 1         | 0.66%   |
| OEM V40SI2                            | 1         | 0.66%   |
| MSI GS63VR 6RF                        | 1         | 0.66%   |
| MSI GL65 Leopard 10SCXR               | 1         | 0.66%   |
| MSI GL63 8RD                          | 1         | 0.66%   |
| MSI GE62 6QD                          | 1         | 0.66%   |
| Lenovo V15-ADA 82C7                   | 1         | 0.66%   |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.66%   |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.66%   |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.66%   |
| Lenovo ThinkPad T14s Gen 3 21BSS37200 | 1         | 0.66%   |
| Lenovo ThinkPad T14 Gen 2a 20XLS23K00 | 1         | 0.66%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.66%   |
| Lenovo ThinkPad P50 20EQS14H00        | 1         | 0.66%   |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.66%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.66%   |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 16        | 10.53%  |
| Lenovo ThinkPad        | 12        | 7.89%   |
| Toshiba Satellite      | 9         | 5.92%   |
| Acer Aspire            | 9         | 5.92%   |
| HP Pavilion            | 8         | 5.26%   |
| HP Laptop              | 8         | 5.26%   |
| Dell Inspiron          | 7         | 4.61%   |
| Lenovo IdeaPad         | 6         | 3.95%   |
| Dell Latitude          | 5         | 3.29%   |
| ASUS ROG               | 4         | 2.63%   |
| Standard SF20BA2       | 3         | 1.97%   |
| ASUS VivoBook          | 3         | 1.97%   |
| HP Stream              | 2         | 1.32%   |
| HP Notebook            | 2         | 1.32%   |
| HP EliteBook           | 2         | 1.32%   |
| HP 240                 | 2         | 1.32%   |
| Dell XPS               | 2         | 1.32%   |
| Acer TravelMate        | 2         | 1.32%   |
| Valve Jupiter          | 1         | 0.66%   |
| Standard SF20BA        | 1         | 0.66%   |
| Standard EF20EA        | 1         | 0.66%   |
| Sony SVF14211CLB       | 1         | 0.66%   |
| Samsung NC208          | 1         | 0.66%   |
| Samsung N102SP         | 1         | 0.66%   |
| Samsung 700T           | 1         | 0.66%   |
| Samsung 300E4C         | 1         | 0.66%   |
| Positivo Serie         | 1         | 0.66%   |
| Panasonic CF-31JEGAX1M | 1         | 0.66%   |
| OEM V40SI2             | 1         | 0.66%   |
| MSI GS63VR             | 1         | 0.66%   |
| MSI GL65               | 1         | 0.66%   |
| MSI GL63               | 1         | 0.66%   |
| MSI GE62               | 1         | 0.66%   |
| Lenovo V15-ADA         | 1         | 0.66%   |
| Lenovo ThinkBook       | 1         | 0.66%   |
| Lenovo G50-70          | 1         | 0.66%   |
| Lenovo G405            | 1         | 0.66%   |
| Lenovo B51-30          | 1         | 0.66%   |
| Lenovo B50-45          | 1         | 0.66%   |
| Lenovo 14w             | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 25        | 16.45%  |
| 2019 | 14        | 9.21%   |
| 2014 | 14        | 9.21%   |
| 2013 | 14        | 9.21%   |
| 2020 | 13        | 8.55%   |
| 2018 | 12        | 7.89%   |
| 2016 | 12        | 7.89%   |
| 2015 | 12        | 7.89%   |
| 2011 | 11        | 7.24%   |
| 2012 | 7         | 4.61%   |
| 2022 | 4         | 2.63%   |
| 2010 | 4         | 2.63%   |
| 2021 | 3         | 1.97%   |
| 2008 | 3         | 1.97%   |
| 2007 | 3         | 1.97%   |
| 2009 | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 152       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 138       | 90.2%   |
| Enabled  | 15        | 9.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 39        | 25.32%  |
| 4.01-8.0    | 35        | 22.73%  |
| 1.01-2.0    | 28        | 18.18%  |
| 8.01-16.0   | 23        | 14.94%  |
| 16.01-24.0  | 15        | 9.74%   |
| 32.01-64.0  | 8         | 5.19%   |
| 24.01-32.0  | 3         | 1.95%   |
| 2.01-3.0    | 1         | 0.65%   |
| 64.01-256.0 | 1         | 0.65%   |
| 0.01-0.5    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 73        | 43.98%  |
| 2.01-3.0  | 39        | 23.49%  |
| 4.01-8.0  | 18        | 10.84%  |
| 3.01-4.0  | 16        | 9.64%   |
| 0.51-1.0  | 12        | 7.23%   |
| 8.01-16.0 | 6         | 3.61%   |
| 0.01-0.5  | 2         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 124       | 81.58%  |
| 2      | 27        | 17.76%  |
| 0      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 67.97%  |
| Yes       | 49        | 32.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 64.47%  |
| No        | 54        | 35.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 96.05%  |
| No        | 6         | 3.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 78.95%  |
| No        | 32        | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 152       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 110       | 67.9%   |
| Maldonado              | 9         | 5.56%   |
| Canelones              | 8         | 4.94%   |
| Punta del Este         | 4         | 2.47%   |
| Buceo                  | 3         | 1.85%   |
| Salto                  | 2         | 1.23%   |
| Rocha                  | 2         | 1.23%   |
| Punta Gorda            | 2         | 1.23%   |
| Paysandú              | 2         | 1.23%   |
| Las Piedras            | 2         | 1.23%   |
| Ciudad del Plata       | 2         | 1.23%   |
| Solymar                | 1         | 0.62%   |
| San Jose de Mayo       | 1         | 0.62%   |
| Pinamar                | 1         | 0.62%   |
| Parque Rodo            | 1         | 0.62%   |
| Nueva Helvecia         | 1         | 0.62%   |
| Melilla                | 1         | 0.62%   |
| Maronas                | 1         | 0.62%   |
| Las Flores             | 1         | 0.62%   |
| La Paz                 | 1         | 0.62%   |
| Joaquin Suarez         | 1         | 0.62%   |
| El Tesoro              | 1         | 0.62%   |
| El Pinar               | 1         | 0.62%   |
| Durazno                | 1         | 0.62%   |
| Centro                 | 1         | 0.62%   |
| Barrancas Coloradas    | 1         | 0.62%   |
| Arenas de Jose Ignacio | 1         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 26        | 32     | 15.29%  |
| WDC                         | 24        | 29     | 14.12%  |
| Toshiba                     | 21        | 25     | 12.35%  |
| Kingston                    | 21        | 28     | 12.35%  |
| Seagate                     | 16        | 20     | 9.41%   |
| SanDisk                     | 12        | 14     | 7.06%   |
| Samsung Electronics         | 9         | 9      | 5.29%   |
| SK hynix                    | 6         | 6      | 3.53%   |
| Hitachi                     | 6         | 8      | 3.53%   |
| HGST                        | 6         | 6      | 3.53%   |
| Intel                       | 4         | 4      | 2.35%   |
| Hewlett-Packard             | 3         | 3      | 1.76%   |
| Kingston Technology Company | 2         | 2      | 1.18%   |
| Crucial                     | 2         | 3      | 1.18%   |
| W800SH                      | 1         | 1      | 0.59%   |
| SAGE                        | 1         | 1      | 0.59%   |
| Netac                       | 1         | 1      | 0.59%   |
| Micron Technology           | 1         | 1      | 0.59%   |
| LITEON                      | 1         | 2      | 0.59%   |
| KIOXIA                      | 1         | 1      | 0.59%   |
| KingFast                    | 1         | 1      | 0.59%   |
| Dahua                       | 1         | 2      | 0.59%   |
| China                       | 1         | 1      | 0.59%   |
| BIWIN                       | 1         | 1      | 0.59%   |
| BHT                         | 1         | 1      | 0.59%   |
| Apple                       | 1         | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 13        | 7.43%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 4.57%   |
| Unknown DA4032  32GB                 | 5         | 2.86%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 2.86%   |
| Toshiba MQ01ABD075 752GB             | 4         | 2.29%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 2.29%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.71%   |
| Toshiba HDWK105 500GB                | 3         | 1.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.71%   |
| SanDisk DF4032  32GB                 | 3         | 1.71%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 2         | 1.14%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 2         | 1.14%   |
| Unknown SD/MMC/MS PRO 250GB          | 2         | 1.14%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 1.14%   |
| SanDisk NVMe SSD Drive 1024GB        | 2         | 1.14%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.14%   |
| WDC WDS250G2X0C-00L350 250GB         | 1         | 0.57%   |
| WDC WDS120G2G0A-00JH30 128GB SSD     | 1         | 0.57%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.57%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.57%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.57%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.57%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.57%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.57%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.57%   |
| WDC WD3200LPCX-24C6HT0 320GB         | 1         | 0.57%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 1         | 0.57%   |
| WDC WD3200BEVT-26ZCT0 320GB          | 1         | 0.57%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.57%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.57%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.57%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.57%   |
| W800SH 512GB SSD                     | 1         | 0.57%   |
| Unknown SD64G  64GB                  | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 18        | 23     | 27.27%  |
| Toshiba | 17        | 21     | 25.76%  |
| Seagate | 16        | 20     | 24.24%  |
| Hitachi | 6         | 8      | 9.09%   |
| HGST    | 6         | 6      | 9.09%   |
| Unknown | 2         | 2      | 3.03%   |
| SAGE    | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 21     | 39.53%  |
| Samsung Electronics | 5         | 5      | 11.63%  |
| WDC                 | 3         | 3      | 6.98%   |
| SanDisk             | 3         | 3      | 6.98%   |
| Hewlett-Packard     | 3         | 3      | 6.98%   |
| SK hynix            | 2         | 2      | 4.65%   |
| Intel               | 2         | 2      | 4.65%   |
| W800SH              | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Netac               | 1         | 1      | 2.33%   |
| Dahua               | 1         | 2      | 2.33%   |
| Crucial             | 1         | 2      | 2.33%   |
| China               | 1         | 1      | 2.33%   |
| BIWIN               | 1         | 1      | 2.33%   |
| BHT                 | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 81     | 38.55%  |
| SSD     | 42        | 49     | 25.3%   |
| NVMe    | 31        | 37     | 18.67%  |
| MMC     | 28        | 35     | 16.87%  |
| Unknown | 1         | 1      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 97        | 127    | 60.63%  |
| NVMe | 31        | 37     | 19.38%  |
| MMC  | 28        | 35     | 17.5%   |
| SAS  | 4         | 4      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 72        | 90     | 69.9%   |
| 0.51-1.0   | 30        | 39     | 29.13%  |
| 1.01-2.0   | 1         | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 39        | 24.53%  |
| 101-250        | 35        | 22.01%  |
| 21-50          | 23        | 14.47%  |
| 501-1000       | 23        | 14.47%  |
| 1-20           | 20        | 12.58%  |
| 51-100         | 9         | 5.66%   |
| 1001-2000      | 5         | 3.14%   |
| Unknown        | 4         | 2.52%   |
| More than 3000 | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 80        | 48.19%  |
| 21-50          | 30        | 18.07%  |
| 51-100         | 17        | 10.24%  |
| 251-500        | 16        | 9.64%   |
| 101-250        | 12        | 7.23%   |
| 501-1000       | 5         | 3.01%   |
| Unknown        | 4         | 2.41%   |
| More than 3000 | 1         | 0.6%    |
| 1001-2000      | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 2      | 14.29%  |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 7.14%   |
| WDC WD3200BEVT-26ZCT0 320GB         | 1         | 1      | 7.14%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 7.14%   |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 7.14%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 7.14%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 7.14%   |
| Seagate ST980811AS 80GB             | 1         | 2      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 7.14%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 7.14%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 7.14%   |
| HGST HTS545032A7E380 320GB          | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 30.77%  |
| Toshiba | 3         | 4      | 23.08%  |
| Seagate | 3         | 4      | 23.08%  |
| SanDisk | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 33.33%  |
| Toshiba | 3         | 4      | 25%     |
| Seagate | 3         | 4      | 25%     |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 15     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Detected | 99        | 130    | 64.29%  |
| Works    | 42        | 57     | 27.27%  |
| Malfunc  | 13        | 16     | 8.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 100       | 63.29%  |
| AMD                              | 28        | 17.72%  |
| SanDisk                          | 9         | 5.7%    |
| Kingston Technology Company      | 5         | 3.16%   |
| Toshiba America Info Systems     | 4         | 2.53%   |
| Samsung Electronics              | 4         | 2.53%   |
| SK hynix                         | 3         | 1.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| Micron/Crucial Technology        | 1         | 0.63%   |
| Micron Technology                | 1         | 0.63%   |
| Lite-On Technology               | 1         | 0.63%   |
| Apple                            | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 15.15%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 10.3%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 4.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 3.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 2.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.82%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.21%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 1.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 1.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.21%   |
| Intel SSD 660P Series                                                            | 2         | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.21%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.61%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.61%   |
| Sandisk PC SN740 NVMe SSD                                                        | 1         | 0.61%   |
| SanDisk PC SN530 NVMe SSD                                                        | 1         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.61%   |
| Micron NVMe Storage Controller                                                   | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 117       | 72.22%  |
| NVMe | 31        | 19.14%  |
| RAID | 7         | 4.32%   |
| IDE  | 7         | 4.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 76.97%  |
| AMD    | 35        | 23.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 11.18%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 1.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 1.97%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 3         | 1.97%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 3         | 1.97%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 1.97%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 1.97%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.32%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.32%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.32%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.32%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.32%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.32%   |
| Intel Atom CPU Z3735F @ 1.33GHz              | 2         | 1.32%   |
| Intel 12th Gen Core i7-1255U                 | 2         | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics       | 2         | 1.32%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.32%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 2         | 1.32%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.66%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.66%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.66%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.66%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.66%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.66%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.66%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 32        | 21.05%  |
| Intel Core i5      | 27        | 17.76%  |
| Intel Core i7      | 23        | 15.13%  |
| Intel Core i3      | 12        | 7.89%   |
| Other              | 7         | 4.61%   |
| Intel Pentium      | 7         | 4.61%   |
| Intel Atom         | 7         | 4.61%   |
| AMD A6             | 6         | 3.95%   |
| AMD Ryzen 9        | 4         | 2.63%   |
| AMD Ryzen 7        | 3         | 1.97%   |
| AMD E              | 3         | 1.97%   |
| Intel Genuine      | 2         | 1.32%   |
| Intel Core 2 Duo   | 2         | 1.32%   |
| AMD Ryzen 5        | 2         | 1.32%   |
| AMD Ryzen 3        | 2         | 1.32%   |
| AMD E1             | 2         | 1.32%   |
| AMD A8             | 2         | 1.32%   |
| Intel Pentium Dual | 1         | 0.66%   |
| AMD Ryzen 5 PRO    | 1         | 0.66%   |
| AMD Phenom II      | 1         | 0.66%   |
| AMD FX             | 1         | 0.66%   |
| AMD E2             | 1         | 0.66%   |
| AMD Athlon II      | 1         | 0.66%   |
| AMD Athlon         | 1         | 0.66%   |
| AMD A4             | 1         | 0.66%   |
| AMD A10            | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 59.21%  |
| 4      | 44        | 28.95%  |
| 8      | 6         | 3.95%   |
| 6      | 6         | 3.95%   |
| 1      | 4         | 2.63%   |
| 10     | 2         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 152       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 83        | 54.61%  |
| 1      | 69        | 45.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 149       | 98.03%  |
| Unknown        | 3         | 1.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 24.84%  |
| 0x406c4    | 7         | 4.46%   |
| 0x206a7    | 7         | 4.46%   |
| 0x506c9    | 6         | 3.82%   |
| 0x40651    | 6         | 3.82%   |
| 0x806ec    | 5         | 3.18%   |
| 0x406e3    | 5         | 3.18%   |
| 0x306d4    | 5         | 3.18%   |
| 0x20655    | 5         | 3.18%   |
| 0x806ea    | 4         | 2.55%   |
| 0x406c3    | 4         | 2.55%   |
| 0x30678    | 4         | 2.55%   |
| 0x906ea    | 3         | 1.91%   |
| 0x806e9    | 3         | 1.91%   |
| 0x6fd      | 3         | 1.91%   |
| 0x306c3    | 3         | 1.91%   |
| 0x306a9    | 3         | 1.91%   |
| 0x08108109 | 3         | 1.91%   |
| 0x06006705 | 3         | 1.91%   |
| 0x806c1    | 2         | 1.27%   |
| 0x706e5    | 2         | 1.27%   |
| 0x506e3    | 2         | 1.27%   |
| 0x0a50000c | 2         | 1.27%   |
| 0x08600104 | 2         | 1.27%   |
| 0x0810100b | 2         | 1.27%   |
| 0x07030105 | 2         | 1.27%   |
| 0x07030104 | 2         | 1.27%   |
| 0x0700010f | 2         | 1.27%   |
| 0xa0652    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x706a1    | 1         | 0.64%   |
| 0x30673    | 1         | 0.64%   |
| 0x30661    | 1         | 0.64%   |
| 0x106e5    | 1         | 0.64%   |
| 0x106ca    | 1         | 0.64%   |
| 0x1067a    | 1         | 0.64%   |
| 0x10676    | 1         | 0.64%   |
| 0x10661    | 1         | 0.64%   |
| 0x08600102 | 1         | 0.64%   |
| 0x07030106 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 20        | 13.16%  |
| KabyLake      | 17        | 11.18%  |
| Goldmont      | 17        | 11.18%  |
| Haswell       | 11        | 7.24%   |
| Skylake       | 9         | 5.92%   |
| SandyBridge   | 7         | 4.61%   |
| Broadwell     | 7         | 4.61%   |
| Puma          | 6         | 3.95%   |
| IvyBridge     | 6         | 3.95%   |
| Excavator     | 6         | 3.95%   |
| Zen 2         | 5         | 3.29%   |
| Westmere      | 5         | 3.29%   |
| Zen+          | 4         | 2.63%   |
| Core          | 4         | 2.63%   |
| Bobcat        | 3         | 1.97%   |
| Unknown       | 3         | 1.97%   |
| Zen 3         | 2         | 1.32%   |
| Zen           | 2         | 1.32%   |
| TigerLake     | 2         | 1.32%   |
| Piledriver    | 2         | 1.32%   |
| Penryn        | 2         | 1.32%   |
| K10           | 2         | 1.32%   |
| Jaguar        | 2         | 1.32%   |
| IceLake       | 2         | 1.32%   |
| CometLake     | 2         | 1.32%   |
| Bonnell       | 2         | 1.32%   |
| Nehalem       | 1         | 0.66%   |
| Goldmont plus | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 115       | 65.34%  |
| AMD                              | 43        | 24.43%  |
| Nvidia                           | 17        | 9.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 9.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 7.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.87%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.76%   |
| AMD Renoir                                                                               | 5         | 2.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.21%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.21%   |
| Intel HD Graphics 530                                                                    | 4         | 2.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.21%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.21%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.21%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.66%   |
| Intel HD Graphics 620                                                                    | 3         | 1.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.66%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.1%    |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 2         | 1.1%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.1%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.1%    |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.1%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.55%   |
| Nvidia TU117M                                                                            | 1         | 0.55%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 63.16%  |
| 1 x AMD        | 28        | 18.42%  |
| Intel + Nvidia | 11        | 7.24%   |
| Intel + AMD    | 8         | 5.26%   |
| AMD + Nvidia   | 5         | 3.29%   |
| 2 x AMD        | 2         | 1.32%   |
| 1 x SiS        | 1         | 0.66%   |
| 1 x Nvidia     | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 140       | 91.5%   |
| Proprietary | 11        | 7.19%   |
| Unknown     | 2         | 1.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 71.43%  |
| 0.01-0.5   | 16        | 10.39%  |
| 0.51-1.0   | 11        | 7.14%   |
| 1.01-2.0   | 9         | 5.84%   |
| 3.01-4.0   | 6         | 3.9%    |
| 5.01-6.0   | 2         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 26        | 15.95%  |
| Chimei Innolux          | 24        | 14.72%  |
| AU Optronics            | 22        | 13.5%   |
| BOE                     | 21        | 12.88%  |
| Samsung Electronics     | 14        | 8.59%   |
| InfoVision              | 8         | 4.91%   |
| KDC                     | 7         | 4.29%   |
| ViewSonic               | 4         | 2.45%   |
| Sharp                   | 4         | 2.45%   |
| PANDA                   | 4         | 2.45%   |
| Chi Mei Optoelectronics | 4         | 2.45%   |
| Dell                    | 3         | 1.84%   |
| Acer                    | 3         | 1.84%   |
| LG Philips              | 2         | 1.23%   |
| KTC                     | 2         | 1.23%   |
| HSI                     | 2         | 1.23%   |
| Apple                   | 2         | 1.23%   |
| Valve                   | 1         | 0.61%   |
| Sun                     | 1         | 0.61%   |
| Mi                      | 1         | 0.61%   |
| Konka                   | 1         | 0.61%   |
| JDI                     | 1         | 0.61%   |
| InnoLux Display         | 1         | 0.61%   |
| HKC                     | 1         | 0.61%   |
| Hewlett-Packard         | 1         | 0.61%   |
| CPT                     | 1         | 0.61%   |
| AOC                     | 1         | 0.61%   |
| Ancor Communications    | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch          | 6         | 3.64%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 5         | 3.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 1.82%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.21%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.21%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.21%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.21%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 1.21%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.21%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 2         | 1.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.21%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.21%   |
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                      | 2         | 1.21%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch       | 2         | 1.21%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.21%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch         | 1         | 0.61%   |
| ViewSonic VSD220 VSC2CB2 1920x1080 477x268mm 21.5-inch                | 1         | 0.61%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.61%   |
| Sun 48FHD_LCD_TV SCE0301 1920x1080 1280x720mm 57.8-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.61%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.61%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.61%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 78        | 53.42%  |
| 1920x1080 (FHD)   | 40        | 27.4%   |
| 1600x900 (HD+)    | 8         | 5.48%   |
| 1920x1200 (WUXGA) | 7         | 4.79%   |
| 1280x800 (WXGA)   | 4         | 2.74%   |
| 3840x2160 (4K)    | 3         | 2.05%   |
| 2560x1440 (QHD)   | 2         | 1.37%   |
| 800x1280          | 1         | 0.68%   |
| 2288x1287         | 1         | 0.68%   |
| 1360x768          | 1         | 0.68%   |
| 1024x600          | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 72        | 44.17%  |
| 13     | 25        | 15.34%  |
| 14     | 23        | 14.11%  |
| 11     | 8         | 4.91%   |
| 17     | 7         | 4.29%   |
| 23     | 5         | 3.07%   |
| 21     | 5         | 3.07%   |
| 24     | 4         | 2.45%   |
| 40     | 2         | 1.23%   |
| 34     | 2         | 1.23%   |
| 18     | 2         | 1.23%   |
| 12     | 2         | 1.23%   |
| 10     | 2         | 1.23%   |
| 57     | 1         | 0.61%   |
| 52     | 1         | 0.61%   |
| 27     | 1         | 0.61%   |
| 7      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 68.94%  |
| 201-300     | 18        | 11.18%  |
| 501-600     | 10        | 6.21%   |
| 351-400     | 8         | 4.97%   |
| 401-500     | 7         | 4.35%   |
| 801-900     | 2         | 1.24%   |
| 701-800     | 2         | 1.24%   |
| 1001-1500   | 2         | 1.24%   |
| 1-100       | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 129       | 92.81%  |
| 16/10 | 7         | 5.04%   |
| 21/9  | 2         | 1.44%   |
| 0.67  | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 43.9%   |
| 81-90          | 43        | 26.22%  |
| 201-250        | 13        | 7.93%   |
| 51-60          | 8         | 4.88%   |
| 121-130        | 7         | 4.27%   |
| 71-80          | 5         | 3.05%   |
| More than 1000 | 2         | 1.22%   |
| 61-70          | 2         | 1.22%   |
| 351-500        | 2         | 1.22%   |
| 41-50          | 2         | 1.22%   |
| 151-200        | 2         | 1.22%   |
| 141-150        | 2         | 1.22%   |
| 501-1000       | 2         | 1.22%   |
| 1-40           | 1         | 0.61%   |
| 301-350        | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 82        | 51.25%  |
| 121-160       | 43        | 26.88%  |
| 51-100        | 26        | 16.25%  |
| 161-240       | 6         | 3.75%   |
| 1-50          | 2         | 1.25%   |
| More than 240 | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 126       | 80.77%  |
| 2     | 24        | 15.38%  |
| 3     | 3         | 1.92%   |
| 0     | 3         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 73        | 32.3%   |
| Intel                            | 69        | 30.53%  |
| Qualcomm Atheros                 | 35        | 15.49%  |
| Broadcom                         | 20        | 8.85%   |
| Ralink Technology                | 5         | 2.21%   |
| MediaTek                         | 5         | 2.21%   |
| Ralink                           | 3         | 1.33%   |
| TP-Link                          | 2         | 0.88%   |
| Broadcom Limited                 | 2         | 0.88%   |
| ASIX Electronics                 | 2         | 0.88%   |
| Xiaomi                           | 1         | 0.44%   |
| T & A Mobile Phones              | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| Sierra Wireless                  | 1         | 0.44%   |
| Samsung Electronics              | 1         | 0.44%   |
| Qualcomm Atheros Communications  | 1         | 0.44%   |
| Marvell Technology Group         | 1         | 0.44%   |
| Lenovo                           | 1         | 0.44%   |
| Huawei Technologies              | 1         | 0.44%   |
| DisplayLink                      | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 36        | 13.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 9.54%   |
| Intel Wireless 3165                                                     | 24        | 9.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.29%   |
| Intel Wireless 7265                                                     | 5         | 1.91%   |
| Intel Wireless 7260                                                     | 5         | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.91%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.53%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.53%   |
| Intel Wireless 8260                                                     | 4         | 1.53%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |
| Intel Wireless 3160                                                     | 2         | 0.76%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.76%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 43.23%  |
| Realtek Semiconductor           | 28        | 18.06%  |
| Qualcomm Atheros                | 28        | 18.06%  |
| Broadcom                        | 15        | 9.68%   |
| Ralink Technology               | 5         | 3.23%   |
| MediaTek                        | 4         | 2.58%   |
| Ralink                          | 3         | 1.94%   |
| Broadcom Limited                | 2         | 1.29%   |
| TP-Link                         | 1         | 0.65%   |
| Sierra Wireless                 | 1         | 0.65%   |
| Qualcomm Atheros Communications | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 24        | 15.38%  |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.85%   |
| Intel Wireless 7265                                                     | 5         | 3.21%   |
| Intel Wireless 7260                                                     | 5         | 3.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.21%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 2.56%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.56%   |
| Intel Wireless 8260                                                     | 4         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.56%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.28%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.28%   |
| Intel Wireless 3160                                                     | 2         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.28%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.28%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.64%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.64%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.64%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.64%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.64%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 63        | 60%     |
| Intel                            | 15        | 14.29%  |
| Qualcomm Atheros                 | 9         | 8.57%   |
| Broadcom                         | 7         | 6.67%   |
| ASIX Electronics                 | 2         | 1.9%    |
| Xiaomi                           | 1         | 0.95%   |
| TP-Link                          | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] | 1         | 0.95%   |
| Samsung Electronics              | 1         | 0.95%   |
| MediaTek                         | 1         | 0.95%   |
| Marvell Technology Group         | 1         | 0.95%   |
| Lenovo                           | 1         | 0.95%   |
| Huawei Technologies              | 1         | 0.95%   |
| DisplayLink                      | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 34.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 23.81%  |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 2.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.9%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.9%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.9%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.95%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.95%   |
| Samsung Kiera                                                     | 1         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.95%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.95%   |
| MediaTek Armor X10 Pro                                            | 1         | 0.95%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.95%   |
| Lenovo USB-C to LAN                                               | 1         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.95%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.95%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.95%   |
| Huawei E353/E3131                                                 | 1         | 0.95%   |
| DisplayLink Plugable UD-3900                                      | 1         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.95%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.95%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 59.59%  |
| Ethernet | 98        | 40%     |
| Unknown  | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 87.66%  |
| Ethernet | 19        | 12.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 91        | 59.87%  |
| 1     | 55        | 36.18%  |
| 0     | 5         | 3.29%   |
| 3     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 73.2%   |
| Yes  | 41        | 26.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 48.76%  |
| Realtek Semiconductor           | 13        | 10.74%  |
| Qualcomm Atheros Communications | 11        | 9.09%   |
| IMC Networks                    | 9         | 7.44%   |
| Toshiba                         | 7         | 5.79%   |
| Broadcom                        | 5         | 4.13%   |
| Foxconn / Hon Hai               | 4         | 3.31%   |
| Lite-On Technology              | 3         | 2.48%   |
| Cambridge Silicon Radio         | 3         | 2.48%   |
| Ralink                          | 2         | 1.65%   |
| Apple                           | 2         | 1.65%   |
| Ralink Technology               | 1         | 0.83%   |
| Foxconn International           | 1         | 0.83%   |
| Alps Electric                   | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 32.23%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 4.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 4.96%   |
| Intel AX200 Bluetooth                               | 4         | 3.31%   |
| Toshiba Bluetooth Device                            | 3         | 2.48%   |
| Toshiba BCM43142A0                                  | 3         | 2.48%   |
| Realtek Bluetooth Radio                             | 3         | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.48%   |
| Intel AX201 Bluetooth                               | 3         | 2.48%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.48%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.65%   |
| Intel Bluetooth Device                              | 2         | 1.65%   |
| IMC Networks Wireless_Device                        | 2         | 1.65%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.65%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.65%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.65%   |
| Toshiba Bluetooth Radio                             | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.83%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.83%   |
| Lite-On Bluetooth Device                            | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.83%   |
| IMC Networks Bluetooth Device                       | 1         | 0.83%   |
| IMC Networks Bluetooth                              | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.83%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.83%   |
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


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 111       | 66.07%  |
| AMD                                  | 35        | 20.83%  |
| Nvidia                               | 11        | 6.55%   |
| Logitech                             | 4         | 2.38%   |
| Generalplus Technology               | 2         | 1.19%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.6%    |
| Texas Instruments                    | 1         | 0.6%    |
| Silicon Integrated Systems [SiS]     | 1         | 0.6%    |
| Kingston Technology                  | 1         | 0.6%    |
| C-Media Electronics                  | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 7.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 5.48%   |
| AMD FCH Azalia Controller                                                                         | 12        | 5.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 5.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.2%    |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.83%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.37%   |
| Logitech H390 headset with microphone                                                             | 2         | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.91%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.91%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.91%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.91%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.91%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.91%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.91%   |
| Thesycon Systemsoftware & Consulting D50s                                                         | 1         | 0.46%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 29.55%  |
| SK hynix            | 15        | 17.05%  |
| Micron Technology   | 11        | 12.5%   |
| Ramaxel Technology  | 7         | 7.95%   |
| Unknown             | 6         | 6.82%   |
| Goldkey             | 6         | 6.82%   |
| Kingston            | 5         | 5.68%   |
| Crucial             | 4         | 4.55%   |
| Elpida              | 3         | 3.41%   |
| Nanya Technology    | 2         | 2.27%   |
| A-DATA Technology   | 2         | 2.27%   |
| Patriot             | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s  | 4         | 4.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 3.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 3         | 3.26%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s           | 2         | 2.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 2         | 2.17%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 2         | 2.17%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s    | 2         | 2.17%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 2         | 2.17%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s | 2         | 2.17%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s  | 2         | 2.17%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s     | 2         | 2.17%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s  | 2         | 2.17%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s    | 2         | 2.17%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 1.09%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1         | 1.09%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s              | 1         | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.09%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 1.09%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 1.09%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 1.09%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1         | 1.09%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 1         | 1.09%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s   | 1         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 1.09%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s   | 1         | 1.09%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s    | 1         | 1.09%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                 | 1         | 1.09%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                 | 1         | 1.09%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s    | 1         | 1.09%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.09%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.09%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 1.09%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s   | 1         | 1.09%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s   | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 38        | 52.78%  |
| DDR4   | 26        | 36.11%  |
| DDR2   | 3         | 4.17%   |
| SDRAM  | 2         | 2.78%   |
| LPDDR3 | 2         | 2.78%   |
| LPDDR4 | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 91.43%  |
| Row Of Chips | 4         | 5.71%   |
| DIMM         | 2         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 34.15%  |
| 8192  | 22        | 26.83%  |
| 2048  | 17        | 20.73%  |
| 16384 | 10        | 12.2%   |
| 32768 | 2         | 2.44%   |
| 1024  | 2         | 2.44%   |
| 512   | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 33        | 40.74%  |
| 2667  | 14        | 17.28%  |
| 3200  | 7         | 8.64%   |
| 2400  | 6         | 7.41%   |
| 1334  | 5         | 6.17%   |
| 3266  | 3         | 3.7%    |
| 2133  | 3         | 3.7%    |
| 1333  | 3         | 3.7%    |
| 533   | 3         | 3.7%    |
| 4199  | 2         | 2.47%   |
| 1867  | 1         | 1.23%   |
| 1067  | 1         | 1.23%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 28.06%  |
| Realtek Semiconductor                  | 16        | 11.51%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 10.07%  |
| Sunplus Innovation Technology          | 8         | 5.76%   |
| Microdia                               | 8         | 5.76%   |
| Suyin                                  | 7         | 5.04%   |
| Bison Electronics                      | 7         | 5.04%   |
| Unknown                                | 5         | 3.6%    |
| Acer                                   | 5         | 3.6%    |
| Silicon Motion                         | 4         | 2.88%   |
| IMC Networks                           | 4         | 2.88%   |
| Quanta                                 | 3         | 2.16%   |
| Importek                               | 3         | 2.16%   |
| Alcor Micro                            | 3         | 2.16%   |
| Syntek                                 | 2         | 1.44%   |
| Luxvisions Innotech Limited            | 2         | 1.44%   |
| Lite-On Technology                     | 2         | 1.44%   |
| Sonix Technology                       | 1         | 0.72%   |
| Samsung Electronics                    | 1         | 0.72%   |
| Primax Electronics                     | 1         | 0.72%   |
| Novatek Microelectronics               | 1         | 0.72%   |
| Logitech                               | 1         | 0.72%   |
| DigiTech                               | 1         | 0.72%   |
| Apple                                  | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 16        | 11.51%  |
| Unknown USB Camera                                             | 5         | 3.6%    |
| Chicony Integrated Camera                                      | 5         | 3.6%    |
| Chicony HP Truevision HD                                       | 5         | 3.6%    |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.88%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.88%   |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 2.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.88%   |
| Realtek Lenovo EasyCamera                                      | 3         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 2.16%   |
| Bison Integrated Camera                                        | 3         | 2.16%   |
| Acer Integrated Camera                                         | 3         | 2.16%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.44%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.44%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.44%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 1.44%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.44%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.44%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.44%   |
| Chicony HD WebCam                                              | 2         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.44%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.44%   |
| Syntek Integrated Camera                                       | 1         | 0.72%   |
| Syntek EasyCamera                                              | 1         | 0.72%   |
| Suyin VGA Webcam                                               | 1         | 0.72%   |
| Suyin HP Truevision HD                                         | 1         | 0.72%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.72%   |
| Suyin HD WebCam                                                | 1         | 0.72%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.72%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.72%   |
| Sunplus MTD camera                                             | 1         | 0.72%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.72%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.72%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 0.72%   |
| Sunplus HP TrueVision HD Camera                                | 1         | 0.72%   |
| Sunplus HD WebCam                                              | 1         | 0.72%   |
| Sunplus Asus Webcam                                            | 1         | 0.72%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 38.89%  |
| Synaptics                  | 3         | 16.67%  |
| Shenzhen Goodix Technology | 3         | 16.67%  |
| Upek                       | 1         | 5.56%   |
| LighTuning Technology      | 1         | 5.56%   |
| Focal-systems.Corp         | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.56%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.56%   |
| Synaptics UWP WBDI Device                              | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.56%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5.56%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.56%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 118       | 76.62%  |
| 1     | 34        | 22.08%  |
| 2     | 2         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 44.74%  |
| Net/wireless          | 6         | 15.79%  |
| Multimedia controller | 5         | 13.16%  |
| Graphics card         | 3         | 7.89%   |
| Chipcard              | 3         | 7.89%   |
| Bluetooth             | 2         | 5.26%   |
| Storage               | 1         | 2.63%   |
| Modem                 | 1         | 2.63%   |


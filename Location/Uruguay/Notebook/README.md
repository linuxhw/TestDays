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

Total: 162

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 14-dk1xxx            | [4eb7e0d085](https://linux-hardware.org/?probe=4eb7e0d085) | Jul 22, 2022 |
| HP            | Laptop 14-dk1xxx            | [c4637b4ecd](https://linux-hardware.org/?probe=c4637b4ecd) | Jul 22, 2022 |
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
| Ubuntu 20.04                 | 22        | 18.33%  |
| Ubuntu 18.04                 | 19        | 15.83%  |
| OpenMandriva 4.2             | 6         | 5%      |
| KDE neon 20.04               | 6         | 5%      |
| Manjaro                      | 4         | 3.33%   |
| Ubuntu 21.10                 | 3         | 2.5%    |
| Ubuntu 19.04                 | 3         | 2.5%    |
| Linux Mint 19.3              | 3         | 2.5%    |
| Xubuntu 18.04                | 2         | 1.67%   |
| Ubuntu 21.04                 | 2         | 1.67%   |
| Ubuntu 18.10                 | 2         | 1.67%   |
| Linux Mint 20.1              | 2         | 1.67%   |
| Linux Mint 19.1              | 2         | 1.67%   |
| Kubuntu 18.04                | 2         | 1.67%   |
| Debian 11                    | 2         | 1.67%   |
| Arch Rolling                 | 2         | 1.67%   |
| Zorin 16                     | 1         | 0.83%   |
| Zorin 15                     | 1         | 0.83%   |
| Xubuntu 20.04                | 1         | 0.83%   |
| Ubuntu MATE 20.04            | 1         | 0.83%   |
| Ubuntu 22.04                 | 1         | 0.83%   |
| Ubuntu 20.10                 | 1         | 0.83%   |
| Ubuntu 19.10                 | 1         | 0.83%   |
| Ubuntu 17.10                 | 1         | 0.83%   |
| ROSA R11.1                   | 1         | 0.83%   |
| Pop!_OS 22.04                | 1         | 0.83%   |
| openSUSE Leap-15.1           | 1         | 0.83%   |
| OpenMandriva 4.3             | 1         | 0.83%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.83%   |
| Manjaro 21.2.0               | 1         | 0.83%   |
| Lubuntu 20.04                | 1         | 0.83%   |
| Lubuntu 19.10                | 1         | 0.83%   |
| Linux Mint 20.3              | 1         | 0.83%   |
| Linux Mint 20.2              | 1         | 0.83%   |
| Linux Mint 20                | 1         | 0.83%   |
| Linux Mint 19.2              | 1         | 0.83%   |
| Linux Mint 19                | 1         | 0.83%   |
| Kubuntu 20.10                | 1         | 0.83%   |
| Kubuntu 20.04                | 1         | 0.83%   |
| Gentoo 2.8                   | 1         | 0.83%   |
| Feren OS 18.04               | 1         | 0.83%   |
| Fedora 35                    | 1         | 0.83%   |
| Fedora 34                    | 1         | 0.83%   |
| Fedora 30                    | 1         | 0.83%   |
| Endless 3.8.7                | 1         | 0.83%   |
| Endless 3.7.8                | 1         | 0.83%   |
| Endless 3.6.2                | 1         | 0.83%   |
| Endless 3.4.2-nexthw1        | 1         | 0.83%   |
| EndeavourOS                  | 1         | 0.83%   |
| Elementary 6                 | 1         | 0.83%   |
| Elementary 5.1.7             | 1         | 0.83%   |
| BlackPanther 18.1            | 1         | 0.83%   |
| ArcoLinux Rolling            | 1         | 0.83%   |
| Arch                         | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 53        | 44.92%  |
| Linux Mint   | 12        | 10.17%  |
| OpenMandriva | 7         | 5.93%   |
| KDE neon     | 6         | 5.08%   |
| Manjaro      | 5         | 4.24%   |
| Kubuntu      | 4         | 3.39%   |
| Endless      | 4         | 3.39%   |
| Xubuntu      | 3         | 2.54%   |
| Fedora       | 3         | 2.54%   |
| Arch         | 3         | 2.54%   |
| Zorin        | 2         | 1.69%   |
| Lubuntu      | 2         | 1.69%   |
| Elementary   | 2         | 1.69%   |
| Debian       | 2         | 1.69%   |
| Ubuntu MATE  | 1         | 0.85%   |
| ROSA         | 1         | 0.85%   |
| Pop!_OS      | 1         | 0.85%   |
| openSUSE     | 1         | 0.85%   |
| NixOS        | 1         | 0.85%   |
| Gentoo       | 1         | 0.85%   |
| Feren OS     | 1         | 0.85%   |
| EndeavourOS  | 1         | 0.85%   |
| BlackPanther | 1         | 0.85%   |
| ArcoLinux    | 1         | 0.85%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 6         | 4.76%   |
| 4.16.18-pa2-2bp1            | 6         | 4.76%   |
| 4.16.18-pa2-1bp5            | 5         | 3.97%   |
| 5.8.0-53-generic            | 4         | 3.17%   |
| 5.13.0-39-generic           | 4         | 3.17%   |
| 5.4.0-73-generic            | 3         | 2.38%   |
| 5.4.0-58-generic            | 3         | 2.38%   |
| 5.4.0-52-generic            | 3         | 2.38%   |
| 5.11.0-38-generic           | 3         | 2.38%   |
| 5.8.0-50-generic            | 2         | 1.59%   |
| 5.8.0-43-generic            | 2         | 1.59%   |
| 5.5.19-bp0                  | 2         | 1.59%   |
| 5.4.0-72-generic            | 2         | 1.59%   |
| 5.4.0-42-generic            | 2         | 1.59%   |
| 5.3.0-28-generic            | 2         | 1.59%   |
| 5.13.0-40-generic           | 2         | 1.59%   |
| 5.13.0-37-generic           | 2         | 1.59%   |
| 5.13.0-30-generic           | 2         | 1.59%   |
| 5.11.12-desktop-1omv4002    | 2         | 1.59%   |
| 5.0.0-13-generic            | 2         | 1.59%   |
| 4.15.0-51-generic           | 2         | 1.59%   |
| 4.15.0-20-generic           | 2         | 1.59%   |
| 4.15.0-101-generic          | 2         | 1.59%   |
| 5.8.11-1-MANJARO            | 1         | 0.79%   |
| 5.8.1-3-MANJARO             | 1         | 0.79%   |
| 5.8.0-49-generic            | 1         | 0.79%   |
| 5.8.0-48-generic            | 1         | 0.79%   |
| 5.8.0-44-generic            | 1         | 0.79%   |
| 5.8.0-34-generic            | 1         | 0.79%   |
| 5.6.8-1-MANJARO             | 1         | 0.79%   |
| 5.4.60-1-lts                | 1         | 0.79%   |
| 5.4.32-generic-2rosa-x86_64 | 1         | 0.79%   |
| 5.4.0-80-generic            | 1         | 0.79%   |
| 5.4.0-70-generic            | 1         | 0.79%   |
| 5.4.0-65-generic            | 1         | 0.79%   |
| 5.4.0-62-generic            | 1         | 0.79%   |
| 5.4.0-59-generic            | 1         | 0.79%   |
| 5.4.0-39-generic            | 1         | 0.79%   |
| 5.4.0-37-generic            | 1         | 0.79%   |
| 5.4.0-28-generic            | 1         | 0.79%   |
| 5.4.0-120-generic           | 1         | 0.79%   |
| 5.3.0-51-generic            | 1         | 0.79%   |
| 5.3.0-46-generic            | 1         | 0.79%   |
| 5.3.0-10-generic            | 1         | 0.79%   |
| 5.2.13-200.fc30.x86_64      | 1         | 0.79%   |
| 5.17.5-76051705-generic     | 1         | 0.79%   |
| 5.17.4-arch1-1              | 1         | 0.79%   |
| 5.16.16-arch1-1             | 1         | 0.79%   |
| 5.16.13-desktop-1omv4003    | 1         | 0.79%   |
| 5.16.12-200.fc35.x86_64     | 1         | 0.79%   |
| 5.16.0-gentoo-gentoo-dist   | 1         | 0.79%   |
| 5.15.3                      | 1         | 0.79%   |
| 5.15.0-41-generic           | 1         | 0.79%   |
| 5.15.0-30-generic           | 1         | 0.79%   |
| 5.14.18-1-MANJARO           | 1         | 0.79%   |
| 5.13.0-44-generic           | 1         | 0.79%   |
| 5.13.0-22-generic           | 1         | 0.79%   |
| 5.11.20-300.fc34.x86_64     | 1         | 0.79%   |
| 5.11.11-051111-generic      | 1         | 0.79%   |
| 5.11.0-34-generic           | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 17.74%  |
| 5.8.0   | 12        | 9.68%   |
| 5.13.0  | 11        | 8.87%   |
| 4.16.18 | 11        | 8.87%   |
| 4.15.0  | 9         | 7.26%   |
| 5.11.0  | 6         | 4.84%   |
| 5.10.14 | 6         | 4.84%   |
| 5.0.0   | 6         | 4.84%   |
| 5.3.0   | 5         | 4.03%   |
| 4.18.0  | 4         | 3.23%   |
| 5.5.19  | 2         | 1.61%   |
| 5.15.0  | 2         | 1.61%   |
| 5.11.12 | 2         | 1.61%   |
| 5.10.0  | 2         | 1.61%   |
| 5.8.11  | 1         | 0.81%   |
| 5.8.1   | 1         | 0.81%   |
| 5.6.8   | 1         | 0.81%   |
| 5.4.60  | 1         | 0.81%   |
| 5.4.32  | 1         | 0.81%   |
| 5.2.13  | 1         | 0.81%   |
| 5.17.5  | 1         | 0.81%   |
| 5.17.4  | 1         | 0.81%   |
| 5.16.16 | 1         | 0.81%   |
| 5.16.13 | 1         | 0.81%   |
| 5.16.12 | 1         | 0.81%   |
| 5.16.0  | 1         | 0.81%   |
| 5.15.3  | 1         | 0.81%   |
| 5.14.18 | 1         | 0.81%   |
| 5.11.20 | 1         | 0.81%   |
| 5.11.11 | 1         | 0.81%   |
| 5.10.4  | 1         | 0.81%   |
| 5.10.31 | 1         | 0.81%   |
| 5.10.30 | 1         | 0.81%   |
| 4.18.16 | 1         | 0.81%   |
| 4.17.19 | 1         | 0.81%   |
| 4.16.0  | 1         | 0.81%   |
| 4.13.0  | 1         | 0.81%   |
| 4.12.14 | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 19.35%  |
| 5.8     | 14        | 11.29%  |
| 4.16    | 12        | 9.68%   |
| 5.13    | 11        | 8.87%   |
| 5.10    | 11        | 8.87%   |
| 5.11    | 10        | 8.06%   |
| 4.15    | 9         | 7.26%   |
| 5.0     | 6         | 4.84%   |
| 5.3     | 5         | 4.03%   |
| 4.18    | 5         | 4.03%   |
| 5.16    | 4         | 3.23%   |
| 5.15    | 3         | 2.42%   |
| 5.5     | 2         | 1.61%   |
| 5.17    | 2         | 1.61%   |
| 5.6     | 1         | 0.81%   |
| 5.2     | 1         | 0.81%   |
| 5.14    | 1         | 0.81%   |
| 4.17    | 1         | 0.81%   |
| 4.13    | 1         | 0.81%   |
| 4.12    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 112       | 98.25%  |
| i686   | 2         | 1.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 36        | 30.77%  |
| Unknown         | 21        | 17.95%  |
| KDE5            | 18        | 15.38%  |
| GNOME Flashback | 11        | 9.4%    |
| XFCE            | 8         | 6.84%   |
| X-Cinnamon      | 7         | 5.98%   |
| KDE             | 5         | 4.27%   |
| MATE            | 3         | 2.56%   |
| LXQt            | 3         | 2.56%   |
| Pantheon        | 2         | 1.71%   |
| Cinnamon        | 2         | 1.71%   |
| sway            | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 92        | 80.7%   |
| Wayland | 12        | 10.53%  |
| Unknown | 9         | 7.89%   |
| Tty     | 1         | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 59        | 51.3%   |
| GDM     | 22        | 19.13%  |
| SDDM    | 19        | 16.52%  |
| GDM3    | 6         | 5.22%   |
| LightDM | 5         | 4.35%   |
| TDM     | 3         | 2.61%   |
| GREETD  | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_UY   | 59        | 50%     |
| en_US   | 22        | 18.64%  |
| Unknown | 18        | 15.25%  |
| es_ES   | 12        | 10.17%  |
| es_MX   | 3         | 2.54%   |
| es_AR   | 2         | 1.69%   |
| en_CA   | 1         | 0.85%   |
| C       | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 63        | 54.31%  |
| BIOS | 53        | 45.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 87.93%  |
| Overlay | 7         | 6.03%   |
| Unknown | 4         | 3.45%   |
| Btrfs   | 2         | 1.72%   |
| Ext3    | 1         | 0.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 63.16%  |
| GPT     | 31        | 27.19%  |
| MBR     | 11        | 9.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 83.33%  |
| Yes       | 19        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 71.3%   |
| Yes       | 33        | 28.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 21.05%  |
| Lenovo              | 19        | 16.67%  |
| ECS                 | 13        | 11.4%   |
| Dell                | 12        | 10.53%  |
| ASUSTek Computer    | 10        | 8.77%   |
| Acer                | 10        | 8.77%   |
| Toshiba             | 6         | 5.26%   |
| Samsung Electronics | 4         | 3.51%   |
| MSI                 | 4         | 3.51%   |
| Standard            | 3         | 2.63%   |
| GPU Company         | 2         | 1.75%   |
| Sony                | 1         | 0.88%   |
| Positivo            | 1         | 0.88%   |
| Panasonic           | 1         | 0.88%   |
| OEM                 | 1         | 0.88%   |
| iClever             | 1         | 0.88%   |
| Haitech             | 1         | 0.88%   |
| Apple               | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 13        | 11.4%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.63%   |
| Toshiba Satellite L55t-B              | 2         | 1.75%   |
| Standard SF20BA2                      | 2         | 1.75%   |
| HP Pavilion 15                        | 2         | 1.75%   |
| HP Laptop 15-bs0xx                    | 2         | 1.75%   |
| Toshiba Satellite C75D-C              | 1         | 0.88%   |
| Toshiba Satellite C645D               | 1         | 0.88%   |
| Toshiba Satellite C55-B               | 1         | 0.88%   |
| Toshiba Satellite C45-A               | 1         | 0.88%   |
| Standard EF20EA                       | 1         | 0.88%   |
| Sony SVF14211CLB                      | 1         | 0.88%   |
| Samsung NC208/NC108                   | 1         | 0.88%   |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.88%   |
| Samsung 700T                          | 1         | 0.88%   |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.88%   |
| Positivo Serie AT300                  | 1         | 0.88%   |
| Panasonic CF-31JEGAX1M                | 1         | 0.88%   |
| OEM V40SI2                            | 1         | 0.88%   |
| MSI GS63VR 6RF                        | 1         | 0.88%   |
| MSI GL65 Leopard 10SCXR               | 1         | 0.88%   |
| MSI GL63 8RD                          | 1         | 0.88%   |
| MSI GE62 6QD                          | 1         | 0.88%   |
| Lenovo V15-ADA 82C7                   | 1         | 0.88%   |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.88%   |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.88%   |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.88%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.88%   |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.88%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.88%   |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.88%   |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.88%   |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.88%   |
| Lenovo IdeaPad S340-15IWL 81N8        | 1         | 0.88%   |
| Lenovo IdeaPad S145-15AST 81N3        | 1         | 0.88%   |
| Lenovo IdeaPad 330S-15ARR 81FB        | 1         | 0.88%   |
| Lenovo IdeaPad 320-17IKB 81BJ         | 1         | 0.88%   |
| Lenovo IdeaPad 300-15ISK 80RS         | 1         | 0.88%   |
| Lenovo G50-70 20351                   | 1         | 0.88%   |
| Lenovo G405 20239                     | 1         | 0.88%   |
| Lenovo B51-30 80LK                    | 1         | 0.88%   |
| Lenovo B50-45 20388                   | 1         | 0.88%   |
| iClever IC-T01                        | 1         | 0.88%   |
| HP ZBook 14u G4                       | 1         | 0.88%   |
| HP Stream Laptop 14-ax0XX             | 1         | 0.88%   |
| HP Presario CQ43                      | 1         | 0.88%   |
| HP Pavilion g4                        | 1         | 0.88%   |
| HP Pavilion dv6                       | 1         | 0.88%   |
| HP Pavilion dv5                       | 1         | 0.88%   |
| HP Pavilion dm4                       | 1         | 0.88%   |
| HP Pavilion 17                        | 1         | 0.88%   |
| HP Notebook                           | 1         | 0.88%   |
| HP Laptop 15-db0xxx                   | 1         | 0.88%   |
| HP Laptop 14-dq1xxx                   | 1         | 0.88%   |
| HP Laptop 14-dk1xxx                   | 1         | 0.88%   |
| HP Laptop 14-dk0xxx                   | 1         | 0.88%   |
| HP Laptop 14-df0xxx                   | 1         | 0.88%   |
| HP ENVY TS 15                         | 1         | 0.88%   |
| HP EliteBook 840 G1                   | 1         | 0.88%   |
| HP Casablanca H710                    | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 13        | 11.4%   |
| Lenovo ThinkPad        | 8         | 7.02%   |
| HP Pavilion            | 7         | 6.14%   |
| HP Laptop              | 7         | 6.14%   |
| Dell Inspiron          | 7         | 6.14%   |
| Acer Aspire            | 7         | 6.14%   |
| Toshiba Satellite      | 6         | 5.26%   |
| Lenovo IdeaPad         | 5         | 4.39%   |
| ASUS ROG               | 3         | 2.63%   |
| Standard SF20BA2       | 2         | 1.75%   |
| Dell XPS               | 2         | 1.75%   |
| Dell Latitude          | 2         | 1.75%   |
| ASUS VivoBook          | 2         | 1.75%   |
| Acer TravelMate        | 2         | 1.75%   |
| Standard EF20EA        | 1         | 0.88%   |
| Sony SVF14211CLB       | 1         | 0.88%   |
| Samsung NC208          | 1         | 0.88%   |
| Samsung N102SP         | 1         | 0.88%   |
| Samsung 700T           | 1         | 0.88%   |
| Samsung 300E4C         | 1         | 0.88%   |
| Positivo Serie         | 1         | 0.88%   |
| Panasonic CF-31JEGAX1M | 1         | 0.88%   |
| OEM V40SI2             | 1         | 0.88%   |
| MSI GS63VR             | 1         | 0.88%   |
| MSI GL65               | 1         | 0.88%   |
| MSI GL63               | 1         | 0.88%   |
| MSI GE62               | 1         | 0.88%   |
| Lenovo V15-ADA         | 1         | 0.88%   |
| Lenovo ThinkBook       | 1         | 0.88%   |
| Lenovo G50-70          | 1         | 0.88%   |
| Lenovo G405            | 1         | 0.88%   |
| Lenovo B51-30          | 1         | 0.88%   |
| Lenovo B50-45          | 1         | 0.88%   |
| iClever IC-T01         | 1         | 0.88%   |
| HP ZBook               | 1         | 0.88%   |
| HP Stream              | 1         | 0.88%   |
| HP Presario            | 1         | 0.88%   |
| HP Notebook            | 1         | 0.88%   |
| HP ENVY                | 1         | 0.88%   |
| HP EliteBook           | 1         | 0.88%   |
| HP Casablanca          | 1         | 0.88%   |
| HP 620                 | 1         | 0.88%   |
| HP 240                 | 1         | 0.88%   |
| HP 2000                | 1         | 0.88%   |
| Haitech H7141A         | 1         | 0.88%   |
| GPU Company GWTN156-9  | 1         | 0.88%   |
| GPU Company GWTN156-4  | 1         | 0.88%   |
| Dell Precision         | 1         | 0.88%   |
| ASUS ZenBook           | 1         | 0.88%   |
| ASUS X555LAB           | 1         | 0.88%   |
| ASUS TP300LAB          | 1         | 0.88%   |
| ASUS N46VJ             | 1         | 0.88%   |
| ASUS ASUS              | 1         | 0.88%   |
| Apple MacBookAir7      | 1         | 0.88%   |
| Acer Swift             | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 20        | 17.54%  |
| 2019 | 14        | 12.28%  |
| 2020 | 11        | 9.65%   |
| 2018 | 11        | 9.65%   |
| 2013 | 11        | 9.65%   |
| 2011 | 10        | 8.77%   |
| 2014 | 9         | 7.89%   |
| 2016 | 8         | 7.02%   |
| 2015 | 5         | 4.39%   |
| 2012 | 5         | 4.39%   |
| 2010 | 3         | 2.63%   |
| 2008 | 3         | 2.63%   |
| 2007 | 2         | 1.75%   |
| 2021 | 1         | 0.88%   |
| 2009 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 114       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 101       | 87.83%  |
| Enabled  | 14        | 12.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 31        | 26.72%  |
| 4.01-8.0    | 29        | 25%     |
| 1.01-2.0    | 19        | 16.38%  |
| 8.01-16.0   | 17        | 14.66%  |
| 16.01-24.0  | 10        | 8.62%   |
| 32.01-64.0  | 5         | 4.31%   |
| 24.01-32.0  | 3         | 2.59%   |
| 2.01-3.0    | 1         | 0.86%   |
| 64.01-256.0 | 1         | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 52        | 42.62%  |
| 2.01-3.0  | 27        | 22.13%  |
| 4.01-8.0  | 14        | 11.48%  |
| 0.51-1.0  | 12        | 9.84%   |
| 3.01-4.0  | 11        | 9.02%   |
| 8.01-16.0 | 5         | 4.1%    |
| 0.01-0.5  | 1         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 81.58%  |
| 2      | 20        | 17.54%  |
| 0      | 1         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 69.3%   |
| Yes       | 35        | 30.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 65.79%  |
| No        | 39        | 34.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 97.37%  |
| No        | 3         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 80.7%   |
| No        | 22        | 19.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 114       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 77        | 63.64%  |
| Canelones              | 8         | 6.61%   |
| Maldonado              | 6         | 4.96%   |
| Punta del Este         | 3         | 2.48%   |
| Buceo                  | 3         | 2.48%   |
| Salto                  | 2         | 1.65%   |
| Rocha                  | 2         | 1.65%   |
| Punta Gorda            | 2         | 1.65%   |
| Las Piedras            | 2         | 1.65%   |
| Ciudad del Plata       | 2         | 1.65%   |
| Solymar                | 1         | 0.83%   |
| San Jose de Mayo       | 1         | 0.83%   |
| Paysandú              | 1         | 0.83%   |
| Parque Rodo            | 1         | 0.83%   |
| Melilla                | 1         | 0.83%   |
| Maronas                | 1         | 0.83%   |
| Las Flores             | 1         | 0.83%   |
| La Paz                 | 1         | 0.83%   |
| Joaquin Suarez         | 1         | 0.83%   |
| El Tesoro              | 1         | 0.83%   |
| El Pinar               | 1         | 0.83%   |
| Durazno                | 1         | 0.83%   |
| Barrancas Coloradas    | 1         | 0.83%   |
| Arenas de Jose Ignacio | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 23     | 15.87%  |
| Unknown             | 17        | 22     | 13.49%  |
| Toshiba             | 16        | 18     | 12.7%   |
| Kingston            | 14        | 20     | 11.11%  |
| Seagate             | 13        | 14     | 10.32%  |
| SanDisk             | 10        | 12     | 7.94%   |
| Samsung Electronics | 9         | 9      | 7.14%   |
| Hitachi             | 6         | 8      | 4.76%   |
| Intel               | 4         | 4      | 3.17%   |
| SK hynix            | 3         | 3      | 2.38%   |
| HGST                | 3         | 3      | 2.38%   |
| Hewlett-Packard     | 2         | 2      | 1.59%   |
| Crucial             | 2         | 3      | 1.59%   |
| W800SH              | 1         | 1      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| LITEON              | 1         | 2      | 0.79%   |
| China               | 1         | 1      | 0.79%   |
| BIWIN               | 1         | 1      | 0.79%   |
| BHT                 | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 9         | 6.98%   |
| Kingston SA400S37240G 240GB SSD       | 6         | 4.65%   |
| Unknown DA4032  32GB                  | 5         | 3.88%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 3.1%    |
| Toshiba MQ01ABD075 752GB              | 3         | 2.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 2.33%   |
| WDC WD5000BEKT-60KA9T0 500GB          | 2         | 1.55%   |
| Unknown SD/MMC/MS PRO 64GB            | 2         | 1.55%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.55%   |
| Toshiba HDWK105 500GB                 | 2         | 1.55%   |
| SanDisk NVMe SSD Drive 256GB          | 2         | 1.55%   |
| SanDisk NVMe SSD Drive 1024GB         | 2         | 1.55%   |
| SanDisk DF4032  32GB                  | 2         | 1.55%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.55%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 1         | 0.78%   |
| WDC WDS250G2X0C-00L350 250GB          | 1         | 0.78%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.78%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 0.78%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.78%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.78%   |
| WDC WD5000LPVT-24G33T1 500GB          | 1         | 0.78%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.78%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.78%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 0.78%   |
| WDC WD3200LPCX-24C6HT0 320GB          | 1         | 0.78%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.78%   |
| WDC WD10SPZX-08Z10 1TB                | 1         | 0.78%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.78%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 0.78%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 0.78%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 0.78%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.78%   |
| W800SH 512GB SSD                      | 1         | 0.78%   |
| Unknown SD64G  64GB                   | 1         | 0.78%   |
| Unknown NCard  32GB                   | 1         | 0.78%   |
| Unknown MMC Card  64GB                | 1         | 0.78%   |
| Unknown MMC Card  4GB                 | 1         | 0.78%   |
| Toshiba THNSNJ256G8NY 256GB SSD       | 1         | 0.78%   |
| Toshiba NVMe SSD Drive 256GB          | 1         | 0.78%   |
| Toshiba MQ04ABF100 1TB                | 1         | 0.78%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.78%   |
| Toshiba MK5059GSXP 500GB              | 1         | 0.78%   |
| Toshiba MK3265GSX 320GB               | 1         | 0.78%   |
| Toshiba MK3259GSXP 320GB              | 1         | 0.78%   |
| Toshiba KXG6AZNV512G 512GB            | 1         | 0.78%   |
| Toshiba KXG50ZNV256G 256GB            | 1         | 0.78%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.78%   |
| SK hynix HFS256G32TNH-73A0A 256GB SSD | 1         | 0.78%   |
| SK hynix HFM256GDHTNG-8310A 256GB     | 1         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.78%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.78%   |
| Seagate Expansion 1TB                 | 1         | 0.78%   |
| SanDisk SSD U100 8GB                  | 1         | 0.78%   |
| SanDisk SDSSDP128G 128GB              | 1         | 0.78%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 0.78%   |
| SanDisk NVMe SSD Drive 1TB            | 1         | 0.78%   |
| Samsung SSD SM841 2.5 7mm 128GB       | 1         | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB          | 1         | 0.78%   |
| Samsung SSD 860 EVO 500GB             | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 18     | 29.41%  |
| Seagate | 13        | 14     | 25.49%  |
| Toshiba | 12        | 14     | 23.53%  |
| Hitachi | 6         | 8      | 11.76%  |
| HGST    | 3         | 3      | 5.88%   |
| Unknown | 2         | 2      | 3.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 14     | 32.35%  |
| Samsung Electronics | 5         | 5      | 14.71%  |
| SanDisk             | 3         | 3      | 8.82%   |
| WDC                 | 2         | 2      | 5.88%   |
| SK hynix            | 2         | 2      | 5.88%   |
| Intel               | 2         | 2      | 5.88%   |
| Hewlett-Packard     | 2         | 2      | 5.88%   |
| W800SH              | 1         | 1      | 2.94%   |
| Toshiba             | 1         | 1      | 2.94%   |
| Netac               | 1         | 1      | 2.94%   |
| Crucial             | 1         | 2      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| BIWIN               | 1         | 1      | 2.94%   |
| BHT                 | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 59     | 39.84%  |
| SSD  | 33        | 38     | 26.83%  |
| NVMe | 24        | 29     | 19.51%  |
| MMC  | 17        | 23     | 13.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 75        | 94     | 63.03%  |
| NVMe | 24        | 29     | 20.17%  |
| MMC  | 17        | 23     | 14.29%  |
| SAS  | 3         | 3      | 2.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 64     | 67.5%   |
| 0.51-1.0   | 25        | 32     | 31.25%  |
| 1.01-2.0   | 1         | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 25.42%  |
| 251-500        | 27        | 22.88%  |
| 501-1000       | 19        | 16.1%   |
| 21-50          | 16        | 13.56%  |
| 1-20           | 13        | 11.02%  |
| 51-100         | 7         | 5.93%   |
| Unknown        | 3         | 2.54%   |
| 1001-2000      | 2         | 1.69%   |
| More than 3000 | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 60        | 48.78%  |
| 21-50          | 22        | 17.89%  |
| 251-500        | 12        | 9.76%   |
| 51-100         | 11        | 8.94%   |
| 101-250        | 10        | 8.13%   |
| 501-1000       | 4         | 3.25%   |
| Unknown        | 3         | 2.44%   |
| More than 3000 | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 2      | 20%     |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 10%     |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 10%     |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 10%     |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 10%     |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 10%     |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 10%     |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 10%     |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 30%     |
| Toshiba | 3         | 4      | 30%     |
| Seagate | 2         | 2      | 20%     |
| SanDisk | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 33.33%  |
| Toshiba | 3         | 4      | 33.33%  |
| Seagate | 2         | 2      | 22.22%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 90%     |
| SSD  | 1         | 1      | 10%     |

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
| Detected | 71        | 94     | 61.74%  |
| Works    | 34        | 44     | 29.57%  |
| Malfunc  | 10        | 11     | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 79        | 63.71%  |
| AMD                              | 22        | 17.74%  |
| SanDisk                          | 8         | 6.45%   |
| Samsung Electronics              | 4         | 3.23%   |
| Toshiba America Info Systems     | 3         | 2.42%   |
| Kingston Technology Company      | 3         | 2.42%   |
| SK hynix                         | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |
| Micron/Crucial Technology        | 1         | 0.81%   |
| Lite-On Technology               | 1         | 0.81%   |
| Apple                            | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 19        | 14.73%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 14        | 10.85%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 6.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 4.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 3.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 3.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 3.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 4         | 3.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 3.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 2.33%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 1.55%   |
| Intel SSD 660P Series                                                                  | 2         | 1.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.55%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.78%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.78%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.78%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.78%   |
| Lite-On NVMe Controller                                                                | 1         | 0.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.78%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 0.78%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.78%   |
| Apple S1X NVMe Controller                                                              | 1         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 93        | 72.66%  |
| NVMe | 24        | 18.75%  |
| RAID | 6         | 4.69%   |
| IDE  | 5         | 3.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 89        | 78.07%  |
| AMD    | 25        | 21.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 14        | 12.28%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.63%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.63%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.75%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.75%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.75%   |
| AMD E-300 APU with Radeon HD Graphics        | 2         | 1.75%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.75%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.88%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.88%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.88%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.88%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.88%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.88%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.88%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 1         | 0.88%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.88%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.88%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.88%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.88%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 1         | 0.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 0.88%   |
| Intel Core i5-5250U CPU @ 1.60GHz            | 1         | 0.88%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.88%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 0.88%   |
| Intel Core i5-3340M CPU @ 2.70GHz            | 1         | 0.88%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.88%   |
| Intel Core i5-2467M CPU @ 1.60GHz            | 1         | 0.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 0.88%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.88%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz           | 1         | 0.88%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 1         | 0.88%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.88%   |
| Intel Core i3-6100U CPU @ 2.30GHz            | 1         | 0.88%   |
| Intel Core i3-5020U CPU @ 2.20GHz            | 1         | 0.88%   |
| Intel Core i3-4030U CPU @ 1.90GHz            | 1         | 0.88%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.88%   |
| Intel Core i3 CPU M 390 @ 2.67GHz            | 1         | 0.88%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 0.88%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz         | 1         | 0.88%   |
| Intel Celeron N4100 CPU @ 1.10GHz            | 1         | 0.88%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 1         | 0.88%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 1         | 0.88%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 22        | 19.3%   |
| Intel Core i7      | 20        | 17.54%  |
| Intel Celeron      | 20        | 17.54%  |
| Intel Core i3      | 9         | 7.89%   |
| Intel Pentium      | 6         | 5.26%   |
| Intel Atom         | 5         | 4.39%   |
| Other              | 4         | 3.51%   |
| AMD Ryzen 9        | 3         | 2.63%   |
| AMD A6             | 3         | 2.63%   |
| Intel Genuine      | 2         | 1.75%   |
| Intel Core 2 Duo   | 2         | 1.75%   |
| AMD Ryzen 7        | 2         | 1.75%   |
| AMD Ryzen 5        | 2         | 1.75%   |
| AMD Ryzen 3        | 2         | 1.75%   |
| AMD E1             | 2         | 1.75%   |
| AMD E              | 2         | 1.75%   |
| Intel Pentium Dual | 1         | 0.88%   |
| AMD Phenom II      | 1         | 0.88%   |
| AMD FX             | 1         | 0.88%   |
| AMD E2             | 1         | 0.88%   |
| AMD Athlon II      | 1         | 0.88%   |
| AMD Athlon         | 1         | 0.88%   |
| AMD A8             | 1         | 0.88%   |
| AMD A4             | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 58.77%  |
| 4      | 35        | 30.7%   |
| 6      | 5         | 4.39%   |
| 8      | 4         | 3.51%   |
| 1      | 3         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 65        | 57.02%  |
| 1      | 49        | 42.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 111       | 97.37%  |
| Unknown        | 3         | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 20%     |
| 0x406c4    | 6         | 5.22%   |
| 0x40651    | 6         | 5.22%   |
| 0x206a7    | 6         | 5.22%   |
| 0x306d4    | 5         | 4.35%   |
| 0x806ec    | 4         | 3.48%   |
| 0x806ea    | 4         | 3.48%   |
| 0x20655    | 4         | 3.48%   |
| 0x906ea    | 3         | 2.61%   |
| 0x806e9    | 3         | 2.61%   |
| 0x6fd      | 3         | 2.61%   |
| 0x506c9    | 3         | 2.61%   |
| 0x406e3    | 3         | 2.61%   |
| 0x08108109 | 3         | 2.61%   |
| 0x806c1    | 2         | 1.74%   |
| 0x706e5    | 2         | 1.74%   |
| 0x306c3    | 2         | 1.74%   |
| 0x306a9    | 2         | 1.74%   |
| 0x30678    | 2         | 1.74%   |
| 0x08600104 | 2         | 1.74%   |
| 0x0810100b | 2         | 1.74%   |
| 0x07030104 | 2         | 1.74%   |
| 0x0700010f | 2         | 1.74%   |
| 0x06006705 | 2         | 1.74%   |
| 0xa0652    | 1         | 0.87%   |
| 0x806eb    | 1         | 0.87%   |
| 0x706a1    | 1         | 0.87%   |
| 0x506e3    | 1         | 0.87%   |
| 0x406c3    | 1         | 0.87%   |
| 0x30661    | 1         | 0.87%   |
| 0x106e5    | 1         | 0.87%   |
| 0x106ca    | 1         | 0.87%   |
| 0x1067a    | 1         | 0.87%   |
| 0x10676    | 1         | 0.87%   |
| 0x08600102 | 1         | 0.87%   |
| 0x07030106 | 1         | 0.87%   |
| 0x07030105 | 1         | 0.87%   |
| 0x06006118 | 1         | 0.87%   |
| 0x06001119 | 1         | 0.87%   |
| 0x05000119 | 1         | 0.87%   |
| 0x05000101 | 1         | 0.87%   |
| 0x010000c8 | 1         | 0.87%   |
| 0x010000b6 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 14.04%  |
| Goldmont      | 14        | 12.28%  |
| Silvermont    | 10        | 8.77%   |
| Haswell       | 8         | 7.02%   |
| Skylake       | 6         | 5.26%   |
| SandyBridge   | 6         | 5.26%   |
| Broadwell     | 6         | 5.26%   |
| Zen+          | 4         | 3.51%   |
| Zen 2         | 4         | 3.51%   |
| Westmere      | 4         | 3.51%   |
| Puma          | 4         | 3.51%   |
| IvyBridge     | 4         | 3.51%   |
| Excavator     | 4         | 3.51%   |
| Core          | 3         | 2.63%   |
| Zen           | 2         | 1.75%   |
| TigerLake     | 2         | 1.75%   |
| Penryn        | 2         | 1.75%   |
| K10           | 2         | 1.75%   |
| Jaguar        | 2         | 1.75%   |
| IceLake       | 2         | 1.75%   |
| CometLake     | 2         | 1.75%   |
| Bonnell       | 2         | 1.75%   |
| Bobcat        | 2         | 1.75%   |
| Piledriver    | 1         | 0.88%   |
| Nehalem       | 1         | 0.88%   |
| Goldmont plus | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 87        | 64.44%  |
| AMD                              | 33        | 24.44%  |
| Nvidia                           | 14        | 10.37%  |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 14        | 10.14%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 5.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.35%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.9%    |
| Intel UHD Graphics 620                                                                   | 4         | 2.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.9%    |
| AMD Renoir                                                                               | 4         | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.9%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.17%   |
| Intel HD Graphics 620                                                                    | 3         | 2.17%   |
| Intel HD Graphics 530                                                                    | 3         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.17%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 2.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.45%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.45%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.45%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.72%   |
| Nvidia TU117M                                                                            | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.72%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.72%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.72%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.72%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.72%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.72%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.72%   |
| AMD Richland [Radeon HD 8450G]                                                           | 1         | 0.72%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 0.72%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 0.72%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 0.72%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 70        | 61.4%   |
| 1 x AMD        | 20        | 17.54%  |
| Intel + Nvidia | 9         | 7.89%   |
| Intel + AMD    | 8         | 7.02%   |
| AMD + Nvidia   | 4         | 3.51%   |
| 2 x AMD        | 1         | 0.88%   |
| 1 x SiS        | 1         | 0.88%   |
| 1 x Nvidia     | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 104       | 91.23%  |
| Proprietary | 9         | 7.89%   |
| Unknown     | 1         | 0.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 67.83%  |
| 0.01-0.5   | 11        | 9.57%   |
| 0.51-1.0   | 10        | 8.7%    |
| 1.01-2.0   | 9         | 7.83%   |
| 3.01-4.0   | 5         | 4.35%   |
| 5.01-6.0   | 2         | 1.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 18        | 14.52%  |
| Chimei Innolux          | 17        | 13.71%  |
| BOE                     | 17        | 13.71%  |
| AU Optronics            | 16        | 12.9%   |
| Samsung Electronics     | 14        | 11.29%  |
| KDC                     | 6         | 4.84%   |
| InfoVision              | 6         | 4.84%   |
| Sharp                   | 4         | 3.23%   |
| PANDA                   | 4         | 3.23%   |
| ViewSonic               | 3         | 2.42%   |
| Chi Mei Optoelectronics | 3         | 2.42%   |
| Acer                    | 3         | 2.42%   |
| KTC                     | 2         | 1.61%   |
| Sun                     | 1         | 0.81%   |
| LG Philips              | 1         | 0.81%   |
| JDI                     | 1         | 0.81%   |
| InnoLux Display         | 1         | 0.81%   |
| HSI                     | 1         | 0.81%   |
| HKC                     | 1         | 0.81%   |
| Hewlett-Packard         | 1         | 0.81%   |
| Dell                    | 1         | 0.81%   |
| CPT                     | 1         | 0.81%   |
| Apple                   | 1         | 0.81%   |
| AOC                     | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 5         | 3.97%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 4         | 3.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 2.38%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.59%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.59%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.59%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.59%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.59%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch           | 1         | 0.79%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.79%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.79%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1         | 0.79%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.79%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.79%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch           | 1         | 0.79%   |
| KTC 23L13-H-AN KTC2304 1920x1080 510x287mm 23.0-inch                  | 1         | 0.79%   |
| KTC 23'TV KTC2300 1920x1080 510x290mm 23.1-inch                       | 1         | 0.79%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 0.79%   |
| InnoLux Display LCD Monitor INL0015 1366x768 309x174mm 14.0-inch      | 1         | 0.79%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch           | 1         | 0.79%   |
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                      | 1         | 0.79%   |
| HKC Checksum: 0x8a (valid) HKC1850 1360x768 304x228mm 15.0-inch       | 1         | 0.79%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 509x286mm 23.0-inch          | 1         | 0.79%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                     | 1         | 0.79%   |
| CPT LCD Monitor CPT1BC7 1024x600 223x125mm 10.1-inch                  | 1         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch       | 1         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 62        | 55.36%  |
| 1920x1080 (FHD)   | 31        | 27.68%  |
| 1600x900 (HD+)    | 6         | 5.36%   |
| 1920x1200 (WUXGA) | 5         | 4.46%   |
| 1280x800 (WXGA)   | 3         | 2.68%   |
| 3840x2160 (4K)    | 2         | 1.79%   |
| 2560x1440 (QHD)   | 1         | 0.89%   |
| 1360x768          | 1         | 0.89%   |
| 1024x600          | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 60        | 48.39%  |
| 13     | 19        | 15.32%  |
| 14     | 16        | 12.9%   |
| 11     | 5         | 4.03%   |
| 24     | 4         | 3.23%   |
| 23     | 4         | 3.23%   |
| 17     | 4         | 3.23%   |
| 27     | 3         | 2.42%   |
| 21     | 2         | 1.61%   |
| 18     | 2         | 1.61%   |
| 12     | 2         | 1.61%   |
| 57     | 1         | 0.81%   |
| 34     | 1         | 0.81%   |
| 10     | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 89        | 72.36%  |
| 201-300     | 12        | 9.76%   |
| 501-600     | 11        | 8.94%   |
| 351-400     | 5         | 4.07%   |
| 401-500     | 4         | 3.25%   |
| 701-800     | 1         | 0.81%   |
| 1001-1500   | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 101       | 95.28%  |
| 16/10 | 4         | 3.77%   |
| 21/9  | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 48.39%  |
| 81-90          | 31        | 25%     |
| 201-250        | 8         | 6.45%   |
| 51-60          | 5         | 4.03%   |
| 71-80          | 4         | 3.23%   |
| 121-130        | 4         | 3.23%   |
| 301-350        | 3         | 2.42%   |
| 61-70          | 2         | 1.61%   |
| 151-200        | 2         | 1.61%   |
| 141-150        | 2         | 1.61%   |
| More than 1000 | 1         | 0.81%   |
| 351-500        | 1         | 0.81%   |
| 41-50          | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 62        | 50.82%  |
| 121-160       | 33        | 27.05%  |
| 51-100        | 23        | 18.85%  |
| 161-240       | 2         | 1.64%   |
| More than 240 | 1         | 0.82%   |
| 1-50          | 1         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 94        | 81.03%  |
| 2     | 18        | 15.52%  |
| 3     | 2         | 1.72%   |
| 0     | 2         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 56        | 32.56%  |
| Intel                            | 53        | 30.81%  |
| Qualcomm Atheros                 | 27        | 15.7%   |
| Broadcom                         | 14        | 8.14%   |
| Ralink Technology                | 3         | 1.74%   |
| Ralink                           | 3         | 1.74%   |
| TP-Link                          | 2         | 1.16%   |
| MediaTek                         | 2         | 1.16%   |
| Broadcom Limited                 | 2         | 1.16%   |
| Xiaomi                           | 1         | 0.58%   |
| T & A Mobile Phones              | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Sierra Wireless                  | 1         | 0.58%   |
| Samsung Electronics              | 1         | 0.58%   |
| Qualcomm Atheros Communications  | 1         | 0.58%   |
| Lenovo                           | 1         | 0.58%   |
| Huawei Technologies              | 1         | 0.58%   |
| DisplayLink                      | 1         | 0.58%   |
| ASIX Electronics                 | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 30        | 15%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 9.5%    |
| Intel Wireless 3165                                                     | 19        | 9.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.5%    |
| Intel Wireless 7265                                                     | 4         | 2%      |
| Intel Wireless 7260                                                     | 4         | 2%      |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2%      |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1%      |
| Intel Wireless 8260                                                     | 2         | 1%      |
| Intel Ethernet Connection I218-LM                                       | 2         | 1%      |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1%      |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.5%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.5%    |
| T & A Mobile Phones 5087Z                                               | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.5%    |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.5%    |
| Samsung Kiera                                                           | 1         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.5%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.5%    |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.5%    |
| MediaTek moto e(6) plus                                                 | 1         | 0.5%    |
| Lenovo USB-C to LAN                                                     | 1         | 0.5%    |
| Intel Wireless 8265 / 8275                                              | 1         | 0.5%    |
| Intel Wireless 3160                                                     | 1         | 0.5%    |
| Intel WiFi Link 5100                                                    | 1         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 43.59%  |
| Realtek Semiconductor           | 22        | 18.8%   |
| Qualcomm Atheros                | 22        | 18.8%   |
| Broadcom                        | 10        | 8.55%   |
| Ralink Technology               | 3         | 2.56%   |
| Ralink                          | 3         | 2.56%   |
| Broadcom Limited                | 2         | 1.71%   |
| TP-Link                         | 1         | 0.85%   |
| Sierra Wireless                 | 1         | 0.85%   |
| Qualcomm Atheros Communications | 1         | 0.85%   |
| MediaTek                        | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 19        | 16.1%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 5.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 5.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.24%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 4.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 4.24%   |
| Intel Wireless 7265                                                     | 4         | 3.39%   |
| Intel Wireless 7260                                                     | 4         | 3.39%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.39%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.69%   |
| Intel Wireless 8260                                                     | 2         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.85%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.85%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.85%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.85%   |
| Intel Wireless 3160                                                     | 1         | 0.85%   |
| Intel WiFi Link 5100                                                    | 1         | 0.85%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.85%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.85%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.85%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.85%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.85%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.85%   |
| Broadcom Limited BCM43225 802.11b/g/n                                   | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 50        | 61.73%  |
| Intel                            | 11        | 13.58%  |
| Qualcomm Atheros                 | 6         | 7.41%   |
| Broadcom                         | 5         | 6.17%   |
| Xiaomi                           | 1         | 1.23%   |
| TP-Link                          | 1         | 1.23%   |
| Silicon Integrated Systems [SiS] | 1         | 1.23%   |
| Samsung Electronics              | 1         | 1.23%   |
| MediaTek                         | 1         | 1.23%   |
| Lenovo                           | 1         | 1.23%   |
| Huawei Technologies              | 1         | 1.23%   |
| DisplayLink                      | 1         | 1.23%   |
| ASIX Electronics                 | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 37.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 23.46%  |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.47%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.47%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.47%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.23%   |
| Samsung Kiera                                                     | 1         | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.23%   |
| MediaTek moto e(6) plus                                           | 1         | 1.23%   |
| Lenovo USB-C to LAN                                               | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.23%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.23%   |
| Huawei E353/E3131                                                 | 1         | 1.23%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 59.36%  |
| Ethernet | 75        | 40.11%  |
| Unknown  | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 86.21%  |
| Ethernet | 16        | 13.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 70        | 61.4%   |
| 1     | 41        | 35.96%  |
| 0     | 3         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 85.96%  |
| Yes  | 16        | 14.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 47.31%  |
| Realtek Semiconductor           | 13        | 13.98%  |
| Qualcomm Atheros Communications | 9         | 9.68%   |
| Toshiba                         | 5         | 5.38%   |
| IMC Networks                    | 5         | 5.38%   |
| Foxconn / Hon Hai               | 3         | 3.23%   |
| Cambridge Silicon Radio         | 3         | 3.23%   |
| Broadcom                        | 3         | 3.23%   |
| Ralink                          | 2         | 2.15%   |
| Lite-On Technology              | 2         | 2.15%   |
| Ralink Technology               | 1         | 1.08%   |
| Foxconn International           | 1         | 1.08%   |
| Apple                           | 1         | 1.08%   |
| Alps Electric                   | 1         | 1.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 29        | 31.18%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 8.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 7.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.45%   |
| Intel AX200 Bluetooth                               | 4         | 4.3%    |
| Realtek Bluetooth Radio                             | 3         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.23%   |
| Toshiba Bluetooth Device                            | 2         | 2.15%   |
| Toshiba BCM43142A0                                  | 2         | 2.15%   |
| Ralink RT3290 Bluetooth                             | 2         | 2.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.15%   |
| Intel Bluetooth Device                              | 2         | 2.15%   |
| Intel AX201 Bluetooth                               | 2         | 2.15%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.15%   |
| Toshiba Bluetooth Radio                             | 1         | 1.08%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.08%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.08%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.08%   |
| Lite-On Bluetooth Device                            | 1         | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.08%   |
| IMC Networks Bluetooth Device                       | 1         | 1.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.08%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 1.08%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.08%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.08%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.08%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.08%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.08%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.08%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.08%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 85        | 67.46%  |
| AMD                                  | 25        | 19.84%  |
| Nvidia                               | 8         | 6.35%   |
| Logitech                             | 3         | 2.38%   |
| Generalplus Technology               | 2         | 1.59%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.79%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.79%   |
| C-Media Electronics                  | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 8.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 6.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 6.1%    |
| AMD FCH Azalia Controller                                                                         | 8         | 4.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 4.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.66%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 3.66%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.83%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.83%   |
| Logitech USB Headset                                                                              | 2         | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.22%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 1.22%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.22%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                                                      | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Logitech Headset H390                                                                             | 1         | 0.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.61%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.61%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 29.41%  |
| SK hynix            | 13        | 19.12%  |
| Micron Technology   | 9         | 13.24%  |
| Ramaxel Technology  | 5         | 7.35%   |
| Kingston            | 5         | 7.35%   |
| Unknown             | 4         | 5.88%   |
| Elpida              | 3         | 4.41%   |
| Crucial             | 3         | 4.41%   |
| Nanya Technology    | 2         | 2.94%   |
| Goldkey             | 2         | 2.94%   |
| A-DATA Technology   | 2         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 4.23%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 2.82%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 2.82%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 2.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s      | 2         | 2.82%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 2.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 2.82%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 2.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.41%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1         | 1.41%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 1.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s     | 1         | 1.41%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.41%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.41%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.41%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                      | 1         | 1.41%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 1.41%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.41%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.41%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.41%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.41%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s    | 1         | 1.41%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 1.41%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| Nanya RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.41%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.41%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s            | 1         | 1.41%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s          | 1         | 1.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s         | 1         | 1.41%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s         | 1         | 1.41%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Micron RAM 16ATF4G64HZ-2G6B2 32GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.41%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.41%   |
| Kingston RAM ACR16D3LS1KBGR/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.41%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| Goldkey RAM GKH200SO25608-1600 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.41%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.41%   |
| Crucial RAM CT16G4SFD8266.C16FE 16384MB SODIMM DDR4 2667MT/s  | 1         | 1.41%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s    | 1         | 1.41%   |
| Crucial RAM BLS8G4S240FSDK.8FD 8192MB SODIMM DDR4 2400MT/s    | 1         | 1.41%   |
| A-DATA RAM Module 32GB SODIMM DDR4 2667MT/s                   | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 27        | 49.09%  |
| DDR4   | 21        | 38.18%  |
| SDRAM  | 2         | 3.64%   |
| LPDDR3 | 2         | 3.64%   |
| DDR2   | 2         | 3.64%   |
| LPDDR4 | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 90.57%  |
| Row Of Chips | 3         | 5.66%   |
| DIMM         | 2         | 3.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 37.1%   |
| 8192  | 18        | 29.03%  |
| 2048  | 11        | 17.74%  |
| 16384 | 6         | 9.68%   |
| 32768 | 2         | 3.23%   |
| 1024  | 2         | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 23        | 35.94%  |
| 2667  | 13        | 20.31%  |
| 3200  | 6         | 9.38%   |
| 2400  | 5         | 7.81%   |
| 1334  | 5         | 7.81%   |
| 4199  | 2         | 3.13%   |
| 3266  | 2         | 3.13%   |
| 2133  | 2         | 3.13%   |
| 1333  | 2         | 3.13%   |
| 533   | 2         | 3.13%   |
| 1867  | 1         | 1.56%   |
| 1067  | 1         | 1.56%   |

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
| Chicony Electronics                    | 31        | 28.7%   |
| Realtek Semiconductor                  | 14        | 12.96%  |
| Microdia                               | 8         | 7.41%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 7.41%   |
| Acer                                   | 8         | 7.41%   |
| Unknown                                | 5         | 4.63%   |
| Sunplus Innovation Technology          | 5         | 4.63%   |
| Suyin                                  | 4         | 3.7%    |
| Silicon Motion                         | 4         | 3.7%    |
| IMC Networks                           | 4         | 3.7%    |
| Quanta                                 | 3         | 2.78%   |
| Alcor Micro                            | 3         | 2.78%   |
| Syntek                                 | 2         | 1.85%   |
| Lite-On Technology                     | 2         | 1.85%   |
| Importek                               | 2         | 1.85%   |
| Samsung Electronics                    | 1         | 0.93%   |
| Primax Electronics                     | 1         | 0.93%   |
| Luxvisions Innotech Limited            | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| DigiTech                               | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                                     | 11        | 10.19%  |
| Unknown USB Camera                                                    | 5         | 4.63%   |
| Chicony HP Truevision HD                                              | 5         | 4.63%   |
| Microdia Integrated_Webcam_HD                                         | 4         | 3.7%    |
| Chicony Integrated Camera                                             | 4         | 3.7%    |
| Realtek Lenovo EasyCamera                                             | 3         | 2.78%   |
| Realtek Integrated_Webcam_HD                                          | 3         | 2.78%   |
| Chicony TOSHIBA Web Camera - HD                                       | 3         | 2.78%   |
| Acer Integrated Camera                                                | 3         | 2.78%   |
| Sunplus HP TrueVision HD Camera                                       | 2         | 1.85%   |
| Silicon Motion WebCam SC-0311139N                                     | 2         | 1.85%   |
| Realtek Integrated Webcam HD                                          | 2         | 1.85%   |
| Quanta HP TrueVision HD Camera                                        | 2         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 2         | 1.85%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 2         | 1.85%   |
| Chicony HD WebCam                                                     | 2         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera        | 2         | 1.85%   |
| Acer HD Webcam                                                        | 2         | 1.85%   |
| Syntek Integrated Camera                                              | 1         | 0.93%   |
| Syntek EasyCamera                                                     | 1         | 0.93%   |
| Suyin HP Truevision HD                                                | 1         | 0.93%   |
| Suyin HP Integrated Webcam                                            | 1         | 0.93%   |
| Suyin Asus Integrated Webcam                                          | 1         | 0.93%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 1         | 0.93%   |
| Sunplus HD Webcam                                                     | 1         | 0.93%   |
| Sunplus ASUS USB2.0 Webcam                                            | 1         | 0.93%   |
| Sunplus 1.3M HD WebCam                                                | 1         | 0.93%   |
| Silicon Motion WebCam SC-20FHM11347N                                  | 1         | 0.93%   |
| Silicon Motion WebCam SC-13HDL11939N                                  | 1         | 0.93%   |
| Samsung Galaxy A5 (MTP)                                               | 1         | 0.93%   |
| Realtek USB Camera                                                    | 1         | 0.93%   |
| Realtek MTD camera                                                    | 1         | 0.93%   |
| Realtek Integrated Camera                                             | 1         | 0.93%   |
| Realtek HD WebCam                                                     | 1         | 0.93%   |
| Realtek Front Camera                                                  | 1         | 0.93%   |
| Realtek Acer 640 x 480 laptop camera                                  | 1         | 0.93%   |
| Quanta HD Webcam                                                      | 1         | 0.93%   |
| Primax webcam                                                         | 1         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                                  | 1         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 0.93%   |
| Microdia HP Webcam                                                    | 1         | 0.93%   |
| Microdia HDP Webcam USB                                               | 1         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera                         | 1         | 0.93%   |
| Logitech Webcam C270                                                  | 1         | 0.93%   |
| Lite-On Integrated Camera                                             | 1         | 0.93%   |
| Lite-On HP Webcam                                                     | 1         | 0.93%   |
| Importek TOSHIBA Web Camera                                           | 1         | 0.93%   |
| Importek HP Webcam                                                    | 1         | 0.93%   |
| IMC Networks TOSHIBA Web Camera - HD                                  | 1         | 0.93%   |
| IMC Networks Integrated Camera                                        | 1         | 0.93%   |
| DigiTech WebCam SC-30AFL11449M                                        | 1         | 0.93%   |
| Chicony USB2.0 HD Camera                                              | 1         | 0.93%   |
| Chicony Lenovo EasyCamera                                             | 1         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                               | 1         | 0.93%   |
| Chicony HP Webcam                                                     | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101                  | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam [2 MP Fixed]         | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                      | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD               | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                   | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 35.71%  |
| Shenzhen Goodix Technology | 3         | 21.43%  |
| Upek                       | 1         | 7.14%   |
| Synaptics                  | 1         | 7.14%   |
| LighTuning Technology      | 1         | 7.14%   |
| Focal-systems.Corp         | 1         | 7.14%   |
| Elan Microelectronics      | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 21.43%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.14%   |
| AuthenTec Fingerprint Sensor                           | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 86        | 74.78%  |
| 1     | 27        | 23.48%  |
| 2     | 2         | 1.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 41.94%  |
| Net/wireless          | 6         | 19.35%  |
| Multimedia controller | 4         | 12.9%   |
| Graphics card         | 2         | 6.45%   |
| Chipcard              | 2         | 6.45%   |
| Bluetooth             | 2         | 6.45%   |
| Storage               | 1         | 3.23%   |
| Modem                 | 1         | 3.23%   |


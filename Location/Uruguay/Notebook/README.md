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

Total: 167

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| ECS           | SF20PA2                     | [67dd8af18f](https://linux-hardware.org/?probe=67dd8af18f) | Aug 23, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| Dell          | Latitude 3150               | [aecf1fe543](https://linux-hardware.org/?probe=aecf1fe543) | Aug 01, 2022 |
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
| Ubuntu 20.04                 | 24        | 19.2%   |
| Ubuntu 18.04                 | 19        | 15.2%   |
| OpenMandriva 4.2             | 6         | 4.8%    |
| KDE neon 20.04               | 6         | 4.8%    |
| Manjaro                      | 4         | 3.2%    |
| Ubuntu 21.10                 | 3         | 2.4%    |
| Ubuntu 19.04                 | 3         | 2.4%    |
| Linux Mint 19.3              | 3         | 2.4%    |
| Xubuntu 18.04                | 2         | 1.6%    |
| Ubuntu 21.04                 | 2         | 1.6%    |
| Ubuntu 18.10                 | 2         | 1.6%    |
| OpenMandriva 4.3             | 2         | 1.6%    |
| Linux Mint 20.1              | 2         | 1.6%    |
| Linux Mint 19.1              | 2         | 1.6%    |
| Kubuntu 18.04                | 2         | 1.6%    |
| Fedora 36                    | 2         | 1.6%    |
| Debian 11                    | 2         | 1.6%    |
| Arch Rolling                 | 2         | 1.6%    |
| Zorin 16                     | 1         | 0.8%    |
| Zorin 15                     | 1         | 0.8%    |
| Xubuntu 20.04                | 1         | 0.8%    |
| Ubuntu MATE 20.04            | 1         | 0.8%    |
| Ubuntu 22.04                 | 1         | 0.8%    |
| Ubuntu 20.10                 | 1         | 0.8%    |
| Ubuntu 19.10                 | 1         | 0.8%    |
| Ubuntu 17.10                 | 1         | 0.8%    |
| ROSA R11.1                   | 1         | 0.8%    |
| Pop!_OS 22.04                | 1         | 0.8%    |
| openSUSE Leap-15.1           | 1         | 0.8%    |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.8%    |
| Manjaro 21.2.0               | 1         | 0.8%    |
| Lubuntu 20.04                | 1         | 0.8%    |
| Lubuntu 19.10                | 1         | 0.8%    |
| Linux Mint 20.3              | 1         | 0.8%    |
| Linux Mint 20.2              | 1         | 0.8%    |
| Linux Mint 20                | 1         | 0.8%    |
| Linux Mint 19.2              | 1         | 0.8%    |
| Linux Mint 19                | 1         | 0.8%    |
| Kubuntu 20.10                | 1         | 0.8%    |
| Kubuntu 20.04                | 1         | 0.8%    |
| Gentoo 2.8                   | 1         | 0.8%    |
| Feren OS 18.04               | 1         | 0.8%    |
| Fedora 35                    | 1         | 0.8%    |
| Fedora 34                    | 1         | 0.8%    |
| Fedora 30                    | 1         | 0.8%    |
| Endless 3.8.7                | 1         | 0.8%    |
| Endless 3.7.8                | 1         | 0.8%    |
| Endless 3.6.2                | 1         | 0.8%    |
| Endless 3.4.2-nexthw1        | 1         | 0.8%    |
| EndeavourOS                  | 1         | 0.8%    |
| Elementary 6                 | 1         | 0.8%    |
| Elementary 5.1.7             | 1         | 0.8%    |
| BlackPanther 18.1            | 1         | 0.8%    |
| ArcoLinux Rolling            | 1         | 0.8%    |
| Arch                         | 1         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 55        | 44.72%  |
| Linux Mint   | 12        | 9.76%   |
| OpenMandriva | 8         | 6.5%    |
| KDE neon     | 6         | 4.88%   |
| Manjaro      | 5         | 4.07%   |
| Fedora       | 5         | 4.07%   |
| Kubuntu      | 4         | 3.25%   |
| Endless      | 4         | 3.25%   |
| Xubuntu      | 3         | 2.44%   |
| Arch         | 3         | 2.44%   |
| Zorin        | 2         | 1.63%   |
| Lubuntu      | 2         | 1.63%   |
| Elementary   | 2         | 1.63%   |
| Debian       | 2         | 1.63%   |
| Ubuntu MATE  | 1         | 0.81%   |
| ROSA         | 1         | 0.81%   |
| Pop!_OS      | 1         | 0.81%   |
| openSUSE     | 1         | 0.81%   |
| NixOS        | 1         | 0.81%   |
| Gentoo       | 1         | 0.81%   |
| Feren OS     | 1         | 0.81%   |
| EndeavourOS  | 1         | 0.81%   |
| BlackPanther | 1         | 0.81%   |
| ArcoLinux    | 1         | 0.81%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 6         | 4.58%   |
| 4.16.18-pa2-2bp1            | 6         | 4.58%   |
| 4.16.18-pa2-1bp5            | 5         | 3.82%   |
| 5.8.0-53-generic            | 4         | 3.05%   |
| 5.13.0-39-generic           | 4         | 3.05%   |
| 5.5.19-bp0                  | 3         | 2.29%   |
| 5.4.0-73-generic            | 3         | 2.29%   |
| 5.4.0-58-generic            | 3         | 2.29%   |
| 5.4.0-52-generic            | 3         | 2.29%   |
| 5.11.0-38-generic           | 3         | 2.29%   |
| 5.8.0-50-generic            | 2         | 1.53%   |
| 5.8.0-43-generic            | 2         | 1.53%   |
| 5.4.0-72-generic            | 2         | 1.53%   |
| 5.4.0-42-generic            | 2         | 1.53%   |
| 5.3.0-28-generic            | 2         | 1.53%   |
| 5.15.0-41-generic           | 2         | 1.53%   |
| 5.13.0-40-generic           | 2         | 1.53%   |
| 5.13.0-37-generic           | 2         | 1.53%   |
| 5.13.0-30-generic           | 2         | 1.53%   |
| 5.11.12-desktop-1omv4002    | 2         | 1.53%   |
| 5.0.0-13-generic            | 2         | 1.53%   |
| 4.15.0-51-generic           | 2         | 1.53%   |
| 4.15.0-20-generic           | 2         | 1.53%   |
| 4.15.0-101-generic          | 2         | 1.53%   |
| 5.8.11-1-MANJARO            | 1         | 0.76%   |
| 5.8.1-3-MANJARO             | 1         | 0.76%   |
| 5.8.0-49-generic            | 1         | 0.76%   |
| 5.8.0-48-generic            | 1         | 0.76%   |
| 5.8.0-44-generic            | 1         | 0.76%   |
| 5.8.0-34-generic            | 1         | 0.76%   |
| 5.6.8-1-MANJARO             | 1         | 0.76%   |
| 5.4.60-1-lts                | 1         | 0.76%   |
| 5.4.32-generic-2rosa-x86_64 | 1         | 0.76%   |
| 5.4.0-80-generic            | 1         | 0.76%   |
| 5.4.0-70-generic            | 1         | 0.76%   |
| 5.4.0-65-generic            | 1         | 0.76%   |
| 5.4.0-62-generic            | 1         | 0.76%   |
| 5.4.0-59-generic            | 1         | 0.76%   |
| 5.4.0-39-generic            | 1         | 0.76%   |
| 5.4.0-37-generic            | 1         | 0.76%   |
| 5.4.0-28-generic            | 1         | 0.76%   |
| 5.4.0-120-generic           | 1         | 0.76%   |
| 5.3.0-51-generic            | 1         | 0.76%   |
| 5.3.0-46-generic            | 1         | 0.76%   |
| 5.3.0-10-generic            | 1         | 0.76%   |
| 5.2.13-200.fc30.x86_64      | 1         | 0.76%   |
| 5.18.18-200.rog.fc36.x86_64 | 1         | 0.76%   |
| 5.18.13-200.fc36.x86_64     | 1         | 0.76%   |
| 5.17.5-76051705-generic     | 1         | 0.76%   |
| 5.17.4-arch1-1              | 1         | 0.76%   |
| 5.16.7-desktop-1omv4003     | 1         | 0.76%   |
| 5.16.16-arch1-1             | 1         | 0.76%   |
| 5.16.13-desktop-1omv4003    | 1         | 0.76%   |
| 5.16.12-200.fc35.x86_64     | 1         | 0.76%   |
| 5.16.0-gentoo-gentoo-dist   | 1         | 0.76%   |
| 5.15.3                      | 1         | 0.76%   |
| 5.15.0-30-generic           | 1         | 0.76%   |
| 5.14.18-1-MANJARO           | 1         | 0.76%   |
| 5.13.0-44-generic           | 1         | 0.76%   |
| 5.13.0-22-generic           | 1         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 17.05%  |
| 5.8.0   | 12        | 9.3%    |
| 5.13.0  | 11        | 8.53%   |
| 4.16.18 | 11        | 8.53%   |
| 4.15.0  | 9         | 6.98%   |
| 5.11.0  | 6         | 4.65%   |
| 5.10.14 | 6         | 4.65%   |
| 5.0.0   | 6         | 4.65%   |
| 5.3.0   | 5         | 3.88%   |
| 4.18.0  | 4         | 3.1%    |
| 5.5.19  | 3         | 2.33%   |
| 5.15.0  | 3         | 2.33%   |
| 5.11.12 | 2         | 1.55%   |
| 5.10.0  | 2         | 1.55%   |
| 5.8.11  | 1         | 0.78%   |
| 5.8.1   | 1         | 0.78%   |
| 5.6.8   | 1         | 0.78%   |
| 5.4.60  | 1         | 0.78%   |
| 5.4.32  | 1         | 0.78%   |
| 5.2.13  | 1         | 0.78%   |
| 5.18.18 | 1         | 0.78%   |
| 5.18.13 | 1         | 0.78%   |
| 5.17.5  | 1         | 0.78%   |
| 5.17.4  | 1         | 0.78%   |
| 5.16.7  | 1         | 0.78%   |
| 5.16.16 | 1         | 0.78%   |
| 5.16.13 | 1         | 0.78%   |
| 5.16.12 | 1         | 0.78%   |
| 5.16.0  | 1         | 0.78%   |
| 5.15.3  | 1         | 0.78%   |
| 5.14.18 | 1         | 0.78%   |
| 5.11.20 | 1         | 0.78%   |
| 5.11.11 | 1         | 0.78%   |
| 5.10.4  | 1         | 0.78%   |
| 5.10.31 | 1         | 0.78%   |
| 5.10.30 | 1         | 0.78%   |
| 4.18.16 | 1         | 0.78%   |
| 4.17.19 | 1         | 0.78%   |
| 4.16.0  | 1         | 0.78%   |
| 4.13.0  | 1         | 0.78%   |
| 4.12.14 | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 18.6%   |
| 5.8     | 14        | 10.85%  |
| 4.16    | 12        | 9.3%    |
| 5.13    | 11        | 8.53%   |
| 5.10    | 11        | 8.53%   |
| 5.11    | 10        | 7.75%   |
| 4.15    | 9         | 6.98%   |
| 5.0     | 6         | 4.65%   |
| 5.3     | 5         | 3.88%   |
| 5.16    | 5         | 3.88%   |
| 4.18    | 5         | 3.88%   |
| 5.15    | 4         | 3.1%    |
| 5.5     | 3         | 2.33%   |
| 5.18    | 2         | 1.55%   |
| 5.17    | 2         | 1.55%   |
| 5.6     | 1         | 0.78%   |
| 5.2     | 1         | 0.78%   |
| 5.14    | 1         | 0.78%   |
| 4.17    | 1         | 0.78%   |
| 4.13    | 1         | 0.78%   |
| 4.12    | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 98.32%  |
| i686   | 2         | 1.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 39        | 31.97%  |
| Unknown         | 21        | 17.21%  |
| KDE5            | 19        | 15.57%  |
| GNOME Flashback | 12        | 9.84%   |
| XFCE            | 8         | 6.56%   |
| X-Cinnamon      | 7         | 5.74%   |
| KDE             | 5         | 4.1%    |
| MATE            | 3         | 2.46%   |
| LXQt            | 3         | 2.46%   |
| Pantheon        | 2         | 1.64%   |
| Cinnamon        | 2         | 1.64%   |
| sway            | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 96        | 80.67%  |
| Wayland | 13        | 10.92%  |
| Unknown | 9         | 7.56%   |
| Tty     | 1         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 50.83%  |
| GDM     | 22        | 18.33%  |
| SDDM    | 20        | 16.67%  |
| GDM3    | 7         | 5.83%   |
| LightDM | 6         | 5%      |
| TDM     | 3         | 2.5%    |
| GREETD  | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_UY   | 59        | 47.97%  |
| en_US   | 25        | 20.33%  |
| Unknown | 18        | 14.63%  |
| es_ES   | 13        | 10.57%  |
| es_MX   | 3         | 2.44%   |
| es_AR   | 2         | 1.63%   |
| pt_BR   | 1         | 0.81%   |
| en_CA   | 1         | 0.81%   |
| C       | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 66        | 54.55%  |
| BIOS | 55        | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 104       | 85.95%  |
| Overlay | 8         | 6.61%   |
| Btrfs   | 4         | 3.31%   |
| Unknown | 4         | 3.31%   |
| Ext3    | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 75        | 63.03%  |
| GPT     | 33        | 27.73%  |
| MBR     | 11        | 9.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 82.35%  |
| Yes       | 21        | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 72.5%   |
| Yes       | 33        | 27.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 20.17%  |
| Lenovo              | 20        | 16.81%  |
| ECS                 | 14        | 11.76%  |
| Dell                | 13        | 10.92%  |
| ASUSTek Computer    | 11        | 9.24%   |
| Acer                | 10        | 8.4%    |
| Toshiba             | 6         | 5.04%   |
| Samsung Electronics | 4         | 3.36%   |
| MSI                 | 4         | 3.36%   |
| Standard            | 3         | 2.52%   |
| GPU Company         | 2         | 1.68%   |
| Sony                | 1         | 0.84%   |
| Positivo            | 1         | 0.84%   |
| Panasonic           | 1         | 0.84%   |
| OEM                 | 1         | 0.84%   |
| iClever             | 1         | 0.84%   |
| Haitech             | 1         | 0.84%   |
| Gateway             | 1         | 0.84%   |
| Apple               | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 14        | 11.76%  |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.52%   |
| Toshiba Satellite L55t-B              | 2         | 1.68%   |
| Standard SF20BA2                      | 2         | 1.68%   |
| HP Pavilion 15                        | 2         | 1.68%   |
| HP Laptop 15-bs0xx                    | 2         | 1.68%   |
| Toshiba Satellite C75D-C              | 1         | 0.84%   |
| Toshiba Satellite C645D               | 1         | 0.84%   |
| Toshiba Satellite C55-B               | 1         | 0.84%   |
| Toshiba Satellite C45-A               | 1         | 0.84%   |
| Standard EF20EA                       | 1         | 0.84%   |
| Sony SVF14211CLB                      | 1         | 0.84%   |
| Samsung NC208/NC108                   | 1         | 0.84%   |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.84%   |
| Samsung 700T                          | 1         | 0.84%   |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.84%   |
| Positivo Serie AT300                  | 1         | 0.84%   |
| Panasonic CF-31JEGAX1M                | 1         | 0.84%   |
| OEM V40SI2                            | 1         | 0.84%   |
| MSI GS63VR 6RF                        | 1         | 0.84%   |
| MSI GL65 Leopard 10SCXR               | 1         | 0.84%   |
| MSI GL63 8RD                          | 1         | 0.84%   |
| MSI GE62 6QD                          | 1         | 0.84%   |
| Lenovo V15-ADA 82C7                   | 1         | 0.84%   |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.84%   |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.84%   |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.84%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.84%   |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.84%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.84%   |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.84%   |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.84%   |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.84%   |
| Lenovo IdeaPad S340-15IWL 81N8        | 1         | 0.84%   |
| Lenovo IdeaPad S145-15AST 81N3        | 1         | 0.84%   |
| Lenovo IdeaPad 500S-14ISK 80Q3        | 1         | 0.84%   |
| Lenovo IdeaPad 330S-15ARR 81FB        | 1         | 0.84%   |
| Lenovo IdeaPad 320-17IKB 81BJ         | 1         | 0.84%   |
| Lenovo IdeaPad 300-15ISK 80RS         | 1         | 0.84%   |
| Lenovo G50-70 20351                   | 1         | 0.84%   |
| Lenovo G405 20239                     | 1         | 0.84%   |
| Lenovo B51-30 80LK                    | 1         | 0.84%   |
| Lenovo B50-45 20388                   | 1         | 0.84%   |
| iClever IC-T01                        | 1         | 0.84%   |
| HP ZBook 14u G4                       | 1         | 0.84%   |
| HP Stream Laptop 14-ax0XX             | 1         | 0.84%   |
| HP Presario CQ43                      | 1         | 0.84%   |
| HP Pavilion g4                        | 1         | 0.84%   |
| HP Pavilion dv6                       | 1         | 0.84%   |
| HP Pavilion dv5                       | 1         | 0.84%   |
| HP Pavilion dm4                       | 1         | 0.84%   |
| HP Pavilion 17                        | 1         | 0.84%   |
| HP Notebook                           | 1         | 0.84%   |
| HP Laptop 15-db0xxx                   | 1         | 0.84%   |
| HP Laptop 14-dq1xxx                   | 1         | 0.84%   |
| HP Laptop 14-dk1xxx                   | 1         | 0.84%   |
| HP Laptop 14-dk0xxx                   | 1         | 0.84%   |
| HP Laptop 14-df0xxx                   | 1         | 0.84%   |
| HP ENVY TS 15                         | 1         | 0.84%   |
| HP EliteBook 840 G1                   | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 14        | 11.76%  |
| Lenovo ThinkPad        | 8         | 6.72%   |
| HP Pavilion            | 7         | 5.88%   |
| HP Laptop              | 7         | 5.88%   |
| Dell Inspiron          | 7         | 5.88%   |
| Acer Aspire            | 7         | 5.88%   |
| Toshiba Satellite      | 6         | 5.04%   |
| Lenovo IdeaPad         | 6         | 5.04%   |
| ASUS ROG               | 4         | 3.36%   |
| Dell Latitude          | 3         | 2.52%   |
| Standard SF20BA2       | 2         | 1.68%   |
| Dell XPS               | 2         | 1.68%   |
| ASUS VivoBook          | 2         | 1.68%   |
| Acer TravelMate        | 2         | 1.68%   |
| Standard EF20EA        | 1         | 0.84%   |
| Sony SVF14211CLB       | 1         | 0.84%   |
| Samsung NC208          | 1         | 0.84%   |
| Samsung N102SP         | 1         | 0.84%   |
| Samsung 700T           | 1         | 0.84%   |
| Samsung 300E4C         | 1         | 0.84%   |
| Positivo Serie         | 1         | 0.84%   |
| Panasonic CF-31JEGAX1M | 1         | 0.84%   |
| OEM V40SI2             | 1         | 0.84%   |
| MSI GS63VR             | 1         | 0.84%   |
| MSI GL65               | 1         | 0.84%   |
| MSI GL63               | 1         | 0.84%   |
| MSI GE62               | 1         | 0.84%   |
| Lenovo V15-ADA         | 1         | 0.84%   |
| Lenovo ThinkBook       | 1         | 0.84%   |
| Lenovo G50-70          | 1         | 0.84%   |
| Lenovo G405            | 1         | 0.84%   |
| Lenovo B51-30          | 1         | 0.84%   |
| Lenovo B50-45          | 1         | 0.84%   |
| iClever IC-T01         | 1         | 0.84%   |
| HP ZBook               | 1         | 0.84%   |
| HP Stream              | 1         | 0.84%   |
| HP Presario            | 1         | 0.84%   |
| HP Notebook            | 1         | 0.84%   |
| HP ENVY                | 1         | 0.84%   |
| HP EliteBook           | 1         | 0.84%   |
| HP Casablanca          | 1         | 0.84%   |
| HP 620                 | 1         | 0.84%   |
| HP 240                 | 1         | 0.84%   |
| HP 2000                | 1         | 0.84%   |
| Haitech H7141A         | 1         | 0.84%   |
| GPU Company GWTN156-9  | 1         | 0.84%   |
| GPU Company GWTN156-4  | 1         | 0.84%   |
| Gateway NV55C          | 1         | 0.84%   |
| Dell Precision         | 1         | 0.84%   |
| ASUS ZenBook           | 1         | 0.84%   |
| ASUS X555LAB           | 1         | 0.84%   |
| ASUS TP300LAB          | 1         | 0.84%   |
| ASUS N46VJ             | 1         | 0.84%   |
| ASUS ASUS              | 1         | 0.84%   |
| Apple MacBookAir7      | 1         | 0.84%   |
| Acer Swift             | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 21        | 17.65%  |
| 2019 | 14        | 11.76%  |
| 2020 | 11        | 9.24%   |
| 2018 | 11        | 9.24%   |
| 2013 | 11        | 9.24%   |
| 2011 | 10        | 8.4%    |
| 2016 | 9         | 7.56%   |
| 2014 | 9         | 7.56%   |
| 2015 | 6         | 5.04%   |
| 2012 | 5         | 4.2%    |
| 2010 | 4         | 3.36%   |
| 2008 | 3         | 2.52%   |
| 2021 | 2         | 1.68%   |
| 2007 | 2         | 1.68%   |
| 2009 | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 119       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 106       | 88.33%  |
| Enabled  | 14        | 11.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 33        | 27.27%  |
| 4.01-8.0    | 30        | 24.79%  |
| 1.01-2.0    | 20        | 16.53%  |
| 8.01-16.0   | 18        | 14.88%  |
| 16.01-24.0  | 10        | 8.26%   |
| 32.01-64.0  | 5         | 4.13%   |
| 24.01-32.0  | 3         | 2.48%   |
| 2.01-3.0    | 1         | 0.83%   |
| 64.01-256.0 | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 55        | 43.31%  |
| 2.01-3.0  | 28        | 22.05%  |
| 4.01-8.0  | 15        | 11.81%  |
| 0.51-1.0  | 12        | 9.45%   |
| 3.01-4.0  | 11        | 8.66%   |
| 8.01-16.0 | 5         | 3.94%   |
| 0.01-0.5  | 1         | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 96        | 80.67%  |
| 2      | 22        | 18.49%  |
| 0      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 69.75%  |
| Yes       | 36        | 30.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 66.39%  |
| No        | 40        | 33.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 97.48%  |
| No        | 3         | 2.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 79.83%  |
| No        | 24        | 20.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 119       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 82        | 65.08%  |
| Canelones              | 8         | 6.35%   |
| Maldonado              | 6         | 4.76%   |
| Punta del Este         | 3         | 2.38%   |
| Buceo                  | 3         | 2.38%   |
| Salto                  | 2         | 1.59%   |
| Rocha                  | 2         | 1.59%   |
| Punta Gorda            | 2         | 1.59%   |
| Las Piedras            | 2         | 1.59%   |
| Ciudad del Plata       | 2         | 1.59%   |
| Solymar                | 1         | 0.79%   |
| San Jose de Mayo       | 1         | 0.79%   |
| Paysandú              | 1         | 0.79%   |
| Parque Rodo            | 1         | 0.79%   |
| Melilla                | 1         | 0.79%   |
| Maronas                | 1         | 0.79%   |
| Las Flores             | 1         | 0.79%   |
| La Paz                 | 1         | 0.79%   |
| Joaquin Suarez         | 1         | 0.79%   |
| El Tesoro              | 1         | 0.79%   |
| El Pinar               | 1         | 0.79%   |
| Durazno                | 1         | 0.79%   |
| Barrancas Coloradas    | 1         | 0.79%   |
| Arenas de Jose Ignacio | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 25     | 16.67%  |
| Unknown             | 18        | 23     | 13.64%  |
| Toshiba             | 16        | 18     | 12.12%  |
| Seagate             | 14        | 15     | 10.61%  |
| Kingston            | 14        | 20     | 10.61%  |
| SanDisk             | 11        | 13     | 8.33%   |
| Samsung Electronics | 9         | 9      | 6.82%   |
| Hitachi             | 6         | 8      | 4.55%   |
| SK hynix            | 4         | 4      | 3.03%   |
| Intel               | 4         | 4      | 3.03%   |
| HGST                | 3         | 3      | 2.27%   |
| Hewlett-Packard     | 2         | 2      | 1.52%   |
| Crucial             | 2         | 3      | 1.52%   |
| W800SH              | 1         | 1      | 0.76%   |
| Netac               | 1         | 1      | 0.76%   |
| LITEON              | 1         | 2      | 0.76%   |
| China               | 1         | 1      | 0.76%   |
| BIWIN               | 1         | 1      | 0.76%   |
| BHT                 | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 9         | 6.67%   |
| Kingston SA400S37240G 240GB SSD       | 6         | 4.44%   |
| Unknown DA4032  32GB                  | 5         | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 2.96%   |
| Toshiba MQ01ABD075 752GB              | 3         | 2.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 2.22%   |
| SanDisk DF4032  32GB                  | 3         | 2.22%   |
| WDC WD5000BEKT-60KA9T0 500GB          | 2         | 1.48%   |
| Unknown SD/MMC/MS PRO 128GB           | 2         | 1.48%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.48%   |
| Toshiba HDWK105 500GB                 | 2         | 1.48%   |
| SanDisk NVMe SSD Drive 256GB          | 2         | 1.48%   |
| SanDisk NVMe SSD Drive 1024GB         | 2         | 1.48%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.48%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 1         | 0.74%   |
| WDC WDS250G2X0C-00L350 250GB          | 1         | 0.74%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.74%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 0.74%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.74%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.74%   |
| WDC WD5000LPVT-24G33T1 500GB          | 1         | 0.74%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.74%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.74%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 0.74%   |
| WDC WD3200LPCX-24C6HT0 320GB          | 1         | 0.74%   |
| WDC WD3200BPVT-22ZEST0 320GB          | 1         | 0.74%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.74%   |
| WDC WD10SPZX-08Z10 1TB                | 1         | 0.74%   |
| WDC WD10SPCX-24HWST1 1TB              | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 0.74%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 0.74%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 0.74%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.74%   |
| W800SH 512GB SSD                      | 1         | 0.74%   |
| Unknown SD64G  64GB                   | 1         | 0.74%   |
| Unknown NCard  32GB                   | 1         | 0.74%   |
| Unknown MMC Card  64GB                | 1         | 0.74%   |
| Unknown MMC Card  4GB                 | 1         | 0.74%   |
| Unknown MMC Card  16GB                | 1         | 0.74%   |
| Toshiba THNSNJ256G8NY 256GB SSD       | 1         | 0.74%   |
| Toshiba MQ04ABF100 1TB                | 1         | 0.74%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.74%   |
| Toshiba MK5059GSXP 500GB              | 1         | 0.74%   |
| Toshiba MK3265GSX 320GB               | 1         | 0.74%   |
| Toshiba MK3259GSXP 320GB              | 1         | 0.74%   |
| Toshiba KXG6AZNV512G 512GB            | 1         | 0.74%   |
| Toshiba KXG50ZNV256G 256GB            | 1         | 0.74%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 1         | 0.74%   |
| SK hynix NVMe SSD Drive 1024GB        | 1         | 0.74%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.74%   |
| SK hynix HFS256G32TNH-73A0A 256GB SSD | 1         | 0.74%   |
| SK hynix HFM256GDHTNG-8310A 256GB     | 1         | 0.74%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 0.74%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.74%   |
| Seagate Expansion 500GB               | 1         | 0.74%   |
| SanDisk SSD U100 8GB                  | 1         | 0.74%   |
| SanDisk SDSSDP128G 128GB              | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 17        | 20     | 31.48%  |
| Seagate | 14        | 15     | 25.93%  |
| Toshiba | 12        | 14     | 22.22%  |
| Hitachi | 6         | 8      | 11.11%  |
| HGST    | 3         | 3      | 5.56%   |
| Unknown | 2         | 2      | 3.7%    |

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
| HDD  | 52        | 62     | 40.31%  |
| SSD  | 33        | 38     | 25.58%  |
| NVMe | 25        | 30     | 19.38%  |
| MMC  | 19        | 25     | 14.73%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 97     | 62.4%   |
| NVMe | 25        | 30     | 20%     |
| MMC  | 19        | 25     | 15.2%   |
| SAS  | 3         | 3      | 2.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 67     | 67.86%  |
| 0.51-1.0   | 26        | 32     | 30.95%  |
| 1.01-2.0   | 1         | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 24.39%  |
| 251-500        | 28        | 22.76%  |
| 501-1000       | 20        | 16.26%  |
| 21-50          | 17        | 13.82%  |
| 1-20           | 14        | 11.38%  |
| 51-100         | 7         | 5.69%   |
| 1001-2000      | 3         | 2.44%   |
| Unknown        | 3         | 2.44%   |
| More than 3000 | 1         | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 63        | 49.22%  |
| 21-50          | 23        | 17.97%  |
| 251-500        | 12        | 9.38%   |
| 51-100         | 11        | 8.59%   |
| 101-250        | 10        | 7.81%   |
| 501-1000       | 5         | 3.91%   |
| Unknown        | 3         | 2.34%   |
| More than 3000 | 1         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 2      | 18.18%  |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 9.09%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 9.09%   |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 9.09%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 9.09%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 9.09%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 36.36%  |
| Toshiba | 3         | 4      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| SanDisk | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Toshiba | 3         | 4      | 30%     |
| Seagate | 2         | 2      | 20%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Detected | 75        | 99     | 62.5%   |
| Works    | 34        | 44     | 28.33%  |
| Malfunc  | 11        | 12     | 9.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 83        | 64.34%  |
| AMD                              | 22        | 17.05%  |
| SanDisk                          | 8         | 6.2%    |
| Samsung Electronics              | 4         | 3.1%    |
| Toshiba America Info Systems     | 3         | 2.33%   |
| Kingston Technology Company      | 3         | 2.33%   |
| SK hynix                         | 2         | 1.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Micron/Crucial Technology        | 1         | 0.78%   |
| Lite-On Technology               | 1         | 0.78%   |
| Apple                            | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 19        | 14.18%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 15        | 11.19%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 6.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 4.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 3.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 3.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 3.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 4         | 2.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 2.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 2.24%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 1.49%   |
| Intel SSD 660P Series                                                                  | 2         | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.49%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.75%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.75%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.75%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.75%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.75%   |
| Lite-On NVMe Controller                                                                | 1         | 0.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.75%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.75%   |
| Apple S1X NVMe Controller                                                              | 1         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 97        | 72.93%  |
| NVMe | 25        | 18.8%   |
| RAID | 6         | 4.51%   |
| IDE  | 5         | 3.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 93        | 78.15%  |
| AMD    | 26        | 21.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 15        | 12.61%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.52%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.68%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.68%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.68%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.68%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.68%   |
| AMD E-300 APU with Radeon HD Graphics        | 2         | 1.68%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.68%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.84%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.84%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.84%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.84%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.84%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.84%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.84%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.84%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 1         | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.84%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.84%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.84%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.84%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.84%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 1         | 0.84%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 0.84%   |
| Intel Core i5-5250U CPU @ 1.60GHz            | 1         | 0.84%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.84%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 0.84%   |
| Intel Core i5-3340M CPU @ 2.70GHz            | 1         | 0.84%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.84%   |
| Intel Core i5-2467M CPU @ 1.60GHz            | 1         | 0.84%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 0.84%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.84%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz           | 1         | 0.84%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 1         | 0.84%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.84%   |
| Intel Core i3-6100U CPU @ 2.30GHz            | 1         | 0.84%   |
| Intel Core i3-5020U CPU @ 2.20GHz            | 1         | 0.84%   |
| Intel Core i3-4030U CPU @ 1.90GHz            | 1         | 0.84%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.84%   |
| Intel Core i3 CPU M 390 @ 2.67GHz            | 1         | 0.84%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 1         | 0.84%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 0.84%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz         | 1         | 0.84%   |
| Intel Celeron N4100 CPU @ 1.10GHz            | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 22        | 18.49%  |
| Intel Core i7      | 21        | 17.65%  |
| Intel Celeron      | 21        | 17.65%  |
| Intel Core i3      | 10        | 8.4%    |
| Intel Pentium      | 7         | 5.88%   |
| Intel Atom         | 5         | 4.2%    |
| Other              | 4         | 3.36%   |
| AMD Ryzen 9        | 4         | 3.36%   |
| AMD A6             | 3         | 2.52%   |
| Intel Genuine      | 2         | 1.68%   |
| Intel Core 2 Duo   | 2         | 1.68%   |
| AMD Ryzen 7        | 2         | 1.68%   |
| AMD Ryzen 5        | 2         | 1.68%   |
| AMD Ryzen 3        | 2         | 1.68%   |
| AMD E1             | 2         | 1.68%   |
| AMD E              | 2         | 1.68%   |
| Intel Pentium Dual | 1         | 0.84%   |
| AMD Phenom II      | 1         | 0.84%   |
| AMD FX             | 1         | 0.84%   |
| AMD E2             | 1         | 0.84%   |
| AMD Athlon II      | 1         | 0.84%   |
| AMD Athlon         | 1         | 0.84%   |
| AMD A8             | 1         | 0.84%   |
| AMD A4             | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 70        | 58.82%  |
| 4      | 36        | 30.25%  |
| 8      | 5         | 4.2%    |
| 6      | 5         | 4.2%    |
| 1      | 3         | 2.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 68        | 57.14%  |
| 1      | 51        | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 116       | 97.48%  |
| Unknown        | 3         | 2.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 19.17%  |
| 0x406c4    | 6         | 5%      |
| 0x40651    | 6         | 5%      |
| 0x206a7    | 6         | 5%      |
| 0x306d4    | 5         | 4.17%   |
| 0x20655    | 5         | 4.17%   |
| 0x806ec    | 4         | 3.33%   |
| 0x806ea    | 4         | 3.33%   |
| 0x506c9    | 4         | 3.33%   |
| 0x406e3    | 4         | 3.33%   |
| 0x906ea    | 3         | 2.5%    |
| 0x806e9    | 3         | 2.5%    |
| 0x6fd      | 3         | 2.5%    |
| 0x30678    | 3         | 2.5%    |
| 0x08108109 | 3         | 2.5%    |
| 0x806c1    | 2         | 1.67%   |
| 0x706e5    | 2         | 1.67%   |
| 0x306c3    | 2         | 1.67%   |
| 0x306a9    | 2         | 1.67%   |
| 0x08600104 | 2         | 1.67%   |
| 0x0810100b | 2         | 1.67%   |
| 0x07030104 | 2         | 1.67%   |
| 0x0700010f | 2         | 1.67%   |
| 0x06006705 | 2         | 1.67%   |
| 0xa0652    | 1         | 0.83%   |
| 0x806eb    | 1         | 0.83%   |
| 0x706a1    | 1         | 0.83%   |
| 0x506e3    | 1         | 0.83%   |
| 0x406c3    | 1         | 0.83%   |
| 0x30661    | 1         | 0.83%   |
| 0x106e5    | 1         | 0.83%   |
| 0x106ca    | 1         | 0.83%   |
| 0x1067a    | 1         | 0.83%   |
| 0x10676    | 1         | 0.83%   |
| 0x0a50000c | 1         | 0.83%   |
| 0x08600102 | 1         | 0.83%   |
| 0x07030106 | 1         | 0.83%   |
| 0x07030105 | 1         | 0.83%   |
| 0x06006118 | 1         | 0.83%   |
| 0x06001119 | 1         | 0.83%   |
| 0x05000119 | 1         | 0.83%   |
| 0x05000101 | 1         | 0.83%   |
| 0x010000c8 | 1         | 0.83%   |
| 0x010000b6 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 13.45%  |
| Goldmont      | 15        | 12.61%  |
| Silvermont    | 11        | 9.24%   |
| Haswell       | 8         | 6.72%   |
| Skylake       | 7         | 5.88%   |
| SandyBridge   | 6         | 5.04%   |
| Broadwell     | 6         | 5.04%   |
| Westmere      | 5         | 4.2%    |
| Zen+          | 4         | 3.36%   |
| Zen 2         | 4         | 3.36%   |
| Puma          | 4         | 3.36%   |
| IvyBridge     | 4         | 3.36%   |
| Excavator     | 4         | 3.36%   |
| Core          | 3         | 2.52%   |
| Zen           | 2         | 1.68%   |
| TigerLake     | 2         | 1.68%   |
| Penryn        | 2         | 1.68%   |
| K10           | 2         | 1.68%   |
| Jaguar        | 2         | 1.68%   |
| IceLake       | 2         | 1.68%   |
| CometLake     | 2         | 1.68%   |
| Bonnell       | 2         | 1.68%   |
| Bobcat        | 2         | 1.68%   |
| Zen 3         | 1         | 0.84%   |
| Piledriver    | 1         | 0.84%   |
| Nehalem       | 1         | 0.84%   |
| Goldmont plus | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 91        | 64.54%  |
| AMD                              | 34        | 24.11%  |
| Nvidia                           | 15        | 10.64%  |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 15        | 10.42%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 5.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.17%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.78%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.78%   |
| AMD Renoir                                                                               | 4         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.78%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 2.08%   |
| Intel HD Graphics 620                                                                    | 3         | 2.08%   |
| Intel HD Graphics 530                                                                    | 3         | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 2.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.39%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.39%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.39%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.39%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.39%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.39%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.69%   |
| Nvidia TU117M                                                                            | 1         | 0.69%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.69%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.69%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.69%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.69%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.69%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.69%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.69%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.69%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.69%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.69%   |
| AMD Richland [Radeon HD 8450G]                                                           | 1         | 0.69%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 0.69%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 0.69%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 0.69%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.69%   |
| AMD Cezanne                                                                              | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 62.18%  |
| 1 x AMD        | 20        | 16.81%  |
| Intel + Nvidia | 9         | 7.56%   |
| Intel + AMD    | 8         | 6.72%   |
| AMD + Nvidia   | 5         | 4.2%    |
| 2 x AMD        | 1         | 0.84%   |
| 1 x SiS        | 1         | 0.84%   |
| 1 x Nvidia     | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 90.76%  |
| Proprietary | 10        | 8.4%    |
| Unknown     | 1         | 0.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 68.33%  |
| 0.01-0.5   | 12        | 10%     |
| 0.51-1.0   | 10        | 8.33%   |
| 1.01-2.0   | 9         | 7.5%    |
| 3.01-4.0   | 5         | 4.17%   |
| 5.01-6.0   | 2         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 19        | 14.84%  |
| Chimei Innolux          | 19        | 14.84%  |
| BOE                     | 18        | 14.06%  |
| AU Optronics            | 16        | 12.5%   |
| Samsung Electronics     | 14        | 10.94%  |
| KDC                     | 6         | 4.69%   |
| InfoVision              | 6         | 4.69%   |
| Sharp                   | 4         | 3.13%   |
| PANDA                   | 4         | 3.13%   |
| ViewSonic               | 3         | 2.34%   |
| Chi Mei Optoelectronics | 3         | 2.34%   |
| Acer                    | 3         | 2.34%   |
| KTC                     | 2         | 1.56%   |
| Sun                     | 1         | 0.78%   |
| LG Philips              | 1         | 0.78%   |
| JDI                     | 1         | 0.78%   |
| InnoLux Display         | 1         | 0.78%   |
| HSI                     | 1         | 0.78%   |
| HKC                     | 1         | 0.78%   |
| Hewlett-Packard         | 1         | 0.78%   |
| Dell                    | 1         | 0.78%   |
| CPT                     | 1         | 0.78%   |
| Apple                   | 1         | 0.78%   |
| AOC                     | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 5         | 3.85%   |
| KDC LCD Monitor KDC05F1 1366x768 256x144mm 11.6-inch                  | 4         | 3.08%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 2.31%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.54%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.54%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 1.54%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.54%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.54%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.54%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch           | 1         | 0.77%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.77%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.77%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.77%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1         | 0.77%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.77%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.77%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.77%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.77%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.77%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.77%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch           | 1         | 0.77%   |
| KTC 23L13-H-AN KTC2304 1920x1080 510x287mm 23.0-inch                  | 1         | 0.77%   |
| KTC 23'TV KTC2300 1920x1080 510x290mm 23.1-inch                       | 1         | 0.77%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 0.77%   |
| InnoLux Display LCD Monitor INL0015 1366x768 309x174mm 14.0-inch      | 1         | 0.77%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch           | 1         | 0.77%   |
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                      | 1         | 0.77%   |
| HKC Monitor HKC1850 1360x768 409x230mm 18.5-inch                      | 1         | 0.77%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x287mm 23.0-inch          | 1         | 0.77%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                     | 1         | 0.77%   |
| CPT LCD Monitor CPT1BC7 1024x600 223x125mm 10.1-inch                  | 1         | 0.77%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch       | 1         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.77%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 64        | 55.17%  |
| 1920x1080 (FHD)   | 32        | 27.59%  |
| 1600x900 (HD+)    | 6         | 5.17%   |
| 1920x1200 (WUXGA) | 5         | 4.31%   |
| 1280x800 (WXGA)   | 3         | 2.59%   |
| 3840x2160 (4K)    | 2         | 1.72%   |
| 2560x1440 (QHD)   | 2         | 1.72%   |
| 1360x768          | 1         | 0.86%   |
| 1024x600          | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 62        | 48.44%  |
| 13     | 20        | 15.63%  |
| 14     | 16        | 12.5%   |
| 11     | 6         | 4.69%   |
| 24     | 4         | 3.13%   |
| 23     | 4         | 3.13%   |
| 17     | 4         | 3.13%   |
| 27     | 3         | 2.34%   |
| 21     | 2         | 1.56%   |
| 18     | 2         | 1.56%   |
| 12     | 2         | 1.56%   |
| 57     | 1         | 0.78%   |
| 34     | 1         | 0.78%   |
| 10     | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 72.44%  |
| 201-300     | 13        | 10.24%  |
| 501-600     | 11        | 8.66%   |
| 351-400     | 5         | 3.94%   |
| 401-500     | 4         | 3.15%   |
| 701-800     | 1         | 0.79%   |
| 1001-1500   | 1         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 105       | 95.45%  |
| 16/10 | 4         | 3.64%   |
| 21/9  | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 48.44%  |
| 81-90          | 32        | 25%     |
| 201-250        | 8         | 6.25%   |
| 51-60          | 6         | 4.69%   |
| 71-80          | 4         | 3.13%   |
| 121-130        | 4         | 3.13%   |
| 301-350        | 3         | 2.34%   |
| 61-70          | 2         | 1.56%   |
| 151-200        | 2         | 1.56%   |
| 141-150        | 2         | 1.56%   |
| More than 1000 | 1         | 0.78%   |
| 351-500        | 1         | 0.78%   |
| 41-50          | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 63        | 50%     |
| 121-160       | 35        | 27.78%  |
| 51-100        | 23        | 18.25%  |
| 161-240       | 3         | 2.38%   |
| More than 240 | 1         | 0.79%   |
| 1-50          | 1         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 99        | 81.82%  |
| 2     | 18        | 14.88%  |
| 3     | 2         | 1.65%   |
| 0     | 2         | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 32.6%   |
| Intel                            | 56        | 30.94%  |
| Qualcomm Atheros                 | 28        | 15.47%  |
| Broadcom                         | 15        | 8.29%   |
| Ralink Technology                | 3         | 1.66%   |
| Ralink                           | 3         | 1.66%   |
| MediaTek                         | 3         | 1.66%   |
| TP-Link                          | 2         | 1.1%    |
| Broadcom Limited                 | 2         | 1.1%    |
| Xiaomi                           | 1         | 0.55%   |
| T & A Mobile Phones              | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Sierra Wireless                  | 1         | 0.55%   |
| Samsung Electronics              | 1         | 0.55%   |
| Qualcomm Atheros Communications  | 1         | 0.55%   |
| Lenovo                           | 1         | 0.55%   |
| Huawei Technologies              | 1         | 0.55%   |
| DisplayLink                      | 1         | 0.55%   |
| ASIX Electronics                 | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32        | 15.31%  |
| Intel Wireless 3165                                                     | 20        | 9.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.39%   |
| Intel Wireless 7265                                                     | 5         | 2.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.39%   |
| Intel Wireless 7260                                                     | 4         | 1.91%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.96%   |
| Intel Wireless 8260                                                     | 2         | 0.96%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.96%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.48%   |
| T & A Mobile Phones 5087Z                                               | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.48%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.48%   |
| Samsung Kiera                                                           | 1         | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.48%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.48%   |
| Realtek Realtek Ethernet controller                                     | 1         | 0.48%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.48%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.48%   |
| MediaTek moto e6s                                                       | 1         | 0.48%   |
| Lenovo USB-C to LAN                                                     | 1         | 0.48%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.48%   |
| Intel Wireless 3160                                                     | 1         | 0.48%   |
| Intel WiFi Link 5100                                                    | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 44.63%  |
| Qualcomm Atheros                | 23        | 19.01%  |
| Realtek Semiconductor           | 22        | 18.18%  |
| Broadcom                        | 10        | 8.26%   |
| Ralink Technology               | 3         | 2.48%   |
| Ralink                          | 3         | 2.48%   |
| MediaTek                        | 2         | 1.65%   |
| Broadcom Limited                | 2         | 1.65%   |
| TP-Link                         | 1         | 0.83%   |
| Qualcomm Atheros Communications | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 20        | 16.39%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 5.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.1%    |
| Intel Wireless 7265                                                     | 5         | 4.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 4.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 4.1%    |
| Intel Wireless 7260                                                     | 4         | 3.28%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.28%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.64%   |
| Intel Wireless 8260                                                     | 2         | 1.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.82%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.82%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.82%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.82%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.82%   |
| Intel Wireless 3160                                                     | 1         | 0.82%   |
| Intel WiFi Link 5100                                                    | 1         | 0.82%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.82%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.82%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.82%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.82%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.82%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.82%   |
| Broadcom Limited BCM43225 802.11b/g/n                                   | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 53        | 61.63%  |
| Intel                            | 11        | 12.79%  |
| Qualcomm Atheros                 | 6         | 6.98%   |
| Broadcom                         | 6         | 6.98%   |
| Xiaomi                           | 1         | 1.16%   |
| TP-Link                          | 1         | 1.16%   |
| Silicon Integrated Systems [SiS] | 1         | 1.16%   |
| Sierra Wireless                  | 1         | 1.16%   |
| Samsung Electronics              | 1         | 1.16%   |
| MediaTek                         | 1         | 1.16%   |
| Lenovo                           | 1         | 1.16%   |
| Huawei Technologies              | 1         | 1.16%   |
| DisplayLink                      | 1         | 1.16%   |
| ASIX Electronics                 | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 37.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 22.09%  |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 3.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.33%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.33%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.16%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.16%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.16%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.16%   |
| Samsung Kiera                                                     | 1         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.16%   |
| Realtek Realtek Ethernet controller                               | 1         | 1.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.16%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.16%   |
| MediaTek moto e6s                                                 | 1         | 1.16%   |
| Lenovo USB-C to LAN                                               | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.16%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.16%   |
| Huawei E353/E3131                                                 | 1         | 1.16%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.16%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 116       | 59.18%  |
| Ethernet | 79        | 40.31%  |
| Unknown  | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 86.78%  |
| Ethernet | 16        | 13.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 62.18%  |
| 1     | 42        | 35.29%  |
| 0     | 3         | 2.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 83.19%  |
| Yes  | 20        | 16.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 47.92%  |
| Realtek Semiconductor           | 13        | 13.54%  |
| Qualcomm Atheros Communications | 9         | 9.38%   |
| IMC Networks                    | 6         | 6.25%   |
| Toshiba                         | 5         | 5.21%   |
| Foxconn / Hon Hai               | 3         | 3.13%   |
| Cambridge Silicon Radio         | 3         | 3.13%   |
| Broadcom                        | 3         | 3.13%   |
| Ralink                          | 2         | 2.08%   |
| Lite-On Technology              | 2         | 2.08%   |
| Ralink Technology               | 1         | 1.04%   |
| Foxconn International           | 1         | 1.04%   |
| Apple                           | 1         | 1.04%   |
| Alps Electric                   | 1         | 1.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 31        | 32.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.25%   |
| Intel AX200 Bluetooth                               | 4         | 4.17%   |
| Realtek Bluetooth Radio                             | 3         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.13%   |
| Toshiba Bluetooth Device                            | 2         | 2.08%   |
| Toshiba BCM43142A0                                  | 2         | 2.08%   |
| Ralink RT3290 Bluetooth                             | 2         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 2.08%   |
| Intel AX201 Bluetooth                               | 2         | 2.08%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.08%   |
| Toshiba Bluetooth Radio                             | 1         | 1.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.04%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.04%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.04%   |
| Lite-On Bluetooth Device                            | 1         | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.04%   |
| IMC Networks Wireless_Device                        | 1         | 1.04%   |
| IMC Networks Bluetooth Device                       | 1         | 1.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.04%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 1.04%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.04%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.04%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.04%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.04%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.04%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.04%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 89        | 67.42%  |
| AMD                                  | 26        | 19.7%   |
| Nvidia                               | 9         | 6.82%   |
| Logitech                             | 3         | 2.27%   |
| Generalplus Technology               | 2         | 1.52%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.76%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.76%   |
| C-Media Electronics                  | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 8.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 6.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 6.43%   |
| AMD FCH Azalia Controller                                                                         | 8         | 4.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 4.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.51%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 3.51%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 2.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.75%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.75%   |
| Logitech H390 headset with microphone                                                             | 2         | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.17%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 1.17%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.17%   |
| Thesycon Systemsoftware & Consulting U90                                                          | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.58%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Logitech Headset H390                                                                             | 1         | 0.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.58%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.58%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.58%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 28.57%  |
| SK hynix            | 13        | 18.57%  |
| Micron Technology   | 9         | 12.86%  |
| Ramaxel Technology  | 6         | 8.57%   |
| Kingston            | 5         | 7.14%   |
| Unknown             | 4         | 5.71%   |
| Goldkey             | 3         | 4.29%   |
| Elpida              | 3         | 4.29%   |
| Crucial             | 3         | 4.29%   |
| Nanya Technology    | 2         | 2.86%   |
| A-DATA Technology   | 2         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 4.11%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 2.74%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 2.74%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 2.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.74%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s      | 2         | 2.74%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s    | 2         | 2.74%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 2.74%   |
| Goldkey RAM GKH200SO25608-1600 2048MB SODIMM DDR3 1600MT/s    | 2         | 2.74%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 2.74%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.37%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1         | 1.37%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.37%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.37%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.37%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.37%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                      | 1         | 1.37%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 1.37%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.37%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.37%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.37%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.37%   |
| Ramaxel RAM RMT3160ME68FAF1600 8GB SODIMM DDR3 1600MT/s       | 1         | 1.37%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s    | 1         | 1.37%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 1.37%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Nanya RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.37%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.37%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s            | 1         | 1.37%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s          | 1         | 1.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s         | 1         | 1.37%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.37%   |
| Micron RAM 16ATF4G64HZ-2G6B2 32GB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.37%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.37%   |
| Kingston RAM ACR16D3LS1KBGR/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.37%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s       | 1         | 1.37%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.37%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.37%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.37%   |
| Crucial RAM CT16G4SFD8266.C16FE 16384MB SODIMM DDR4 2667MT/s  | 1         | 1.37%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s    | 1         | 1.37%   |
| Crucial RAM BLS8G4S240FSDK.8FD 8192MB SODIMM DDR4 2400MT/s    | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 29        | 50.88%  |
| DDR4   | 21        | 36.84%  |
| SDRAM  | 2         | 3.51%   |
| LPDDR3 | 2         | 3.51%   |
| DDR2   | 2         | 3.51%   |
| LPDDR4 | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 90.91%  |
| Row Of Chips | 3         | 5.45%   |
| DIMM         | 2         | 3.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 35.94%  |
| 8192  | 19        | 29.69%  |
| 2048  | 12        | 18.75%  |
| 16384 | 6         | 9.38%   |
| 32768 | 2         | 3.13%   |
| 1024  | 2         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 25        | 37.88%  |
| 2667  | 13        | 19.7%   |
| 3200  | 6         | 9.09%   |
| 2400  | 5         | 7.58%   |
| 1334  | 5         | 7.58%   |
| 4199  | 2         | 3.03%   |
| 3266  | 2         | 3.03%   |
| 2133  | 2         | 3.03%   |
| 1333  | 2         | 3.03%   |
| 533   | 2         | 3.03%   |
| 1867  | 1         | 1.52%   |
| 1067  | 1         | 1.52%   |

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
| Chicony Electronics                    | 32        | 28.57%  |
| Realtek Semiconductor                  | 14        | 12.5%   |
| Acer                                   | 9         | 8.04%   |
| Microdia                               | 8         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 7.14%   |
| Sunplus Innovation Technology          | 6         | 5.36%   |
| Unknown                                | 5         | 4.46%   |
| Suyin                                  | 5         | 4.46%   |
| Silicon Motion                         | 4         | 3.57%   |
| IMC Networks                           | 4         | 3.57%   |
| Quanta                                 | 3         | 2.68%   |
| Alcor Micro                            | 3         | 2.68%   |
| Syntek                                 | 2         | 1.79%   |
| Lite-On Technology                     | 2         | 1.79%   |
| Importek                               | 2         | 1.79%   |
| Samsung Electronics                    | 1         | 0.89%   |
| Primax Electronics                     | 1         | 0.89%   |
| Luxvisions Innotech Limited            | 1         | 0.89%   |
| Logitech                               | 1         | 0.89%   |
| DigiTech                               | 1         | 0.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                                     | 12        | 10.71%  |
| Unknown USB Camera                                                    | 5         | 4.46%   |
| Chicony HP Truevision HD                                              | 5         | 4.46%   |
| Microdia Integrated_Webcam_HD                                         | 4         | 3.57%   |
| Chicony Integrated Camera                                             | 4         | 3.57%   |
| Realtek Lenovo EasyCamera                                             | 3         | 2.68%   |
| Realtek Integrated_Webcam_HD                                          | 3         | 2.68%   |
| Chicony TOSHIBA Web Camera - HD                                       | 3         | 2.68%   |
| Acer Integrated Camera                                                | 3         | 2.68%   |
| Silicon Motion WebCam SC-0311139N                                     | 2         | 1.79%   |
| Realtek Integrated Webcam HD                                          | 2         | 1.79%   |
| Quanta HP TrueVision HD Camera                                        | 2         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 2         | 1.79%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 2         | 1.79%   |
| Chicony HD WebCam                                                     | 2         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera        | 2         | 1.79%   |
| Alcor Micro USB 2.0 Camera                                            | 2         | 1.79%   |
| Acer Lenovo EasyCamera                                                | 2         | 1.79%   |
| Acer HD Webcam                                                        | 2         | 1.79%   |
| Syntek Integrated Camera                                              | 1         | 0.89%   |
| Syntek EasyCamera                                                     | 1         | 0.89%   |
| Suyin HP Truevision HD                                                | 1         | 0.89%   |
| Suyin HP Integrated Webcam                                            | 1         | 0.89%   |
| Suyin Asus Integrated Webcam                                          | 1         | 0.89%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 1         | 0.89%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)           | 1         | 0.89%   |
| Sunplus Laptop Integrated Webcam HD                                   | 1         | 0.89%   |
| Sunplus Integrated Camera                                             | 1         | 0.89%   |
| Sunplus HP TrueVision HD Camera                                       | 1         | 0.89%   |
| Sunplus HD WebCam                                                     | 1         | 0.89%   |
| Sunplus ASUS USB2.0 Webcam                                            | 1         | 0.89%   |
| Sunplus 1.3M HD WebCam                                                | 1         | 0.89%   |
| Silicon Motion WebCam SC-20FHM11347N                                  | 1         | 0.89%   |
| Silicon Motion WebCam SC-13HDL11939N                                  | 1         | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)                               | 1         | 0.89%   |
| Realtek USB2.0 camera                                                 | 1         | 0.89%   |
| Realtek USB Camera                                                    | 1         | 0.89%   |
| Realtek Integrated Camera                                             | 1         | 0.89%   |
| Realtek HD WebCam                                                     | 1         | 0.89%   |
| Realtek Front Camera                                                  | 1         | 0.89%   |
| Realtek Acer 640 x 480 laptop camera                                  | 1         | 0.89%   |
| Quanta HD Webcam                                                      | 1         | 0.89%   |
| Primax webcam                                                         | 1         | 0.89%   |
| Microdia USB 2.0 Camera                                               | 1         | 0.89%   |
| Microdia Laptop_Integrated_Webcam_HD                                  | 1         | 0.89%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 0.89%   |
| Microdia HP Webcam                                                    | 1         | 0.89%   |
| Luxvisions Innotech Limited Integrated Camera                         | 1         | 0.89%   |
| Logitech Webcam C270                                                  | 1         | 0.89%   |
| Lite-On Integrated Camera                                             | 1         | 0.89%   |
| Lite-On HP Webcam                                                     | 1         | 0.89%   |
| Importek TOSHIBA Web Camera                                           | 1         | 0.89%   |
| Importek HP Webcam                                                    | 1         | 0.89%   |
| IMC Networks TOSHIBA Web Camera - HD                                  | 1         | 0.89%   |
| IMC Networks Integrated Camera                                        | 1         | 0.89%   |
| DigiTech WebCam SC-30AFL11449M                                        | 1         | 0.89%   |
| Chicony USB2.0 HD Camera                                              | 1         | 0.89%   |
| Chicony Lenovo EasyCamera                                             | 1         | 0.89%   |
| Chicony Integrated Camera (1280x720@30)                               | 1         | 0.89%   |
| Chicony HP Webcam                                                     | 1         | 0.89%   |

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
| 0     | 89        | 74.17%  |
| 1     | 29        | 24.17%  |
| 2     | 2         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 39.39%  |
| Net/wireless          | 6         | 18.18%  |
| Multimedia controller | 5         | 15.15%  |
| Graphics card         | 3         | 9.09%   |
| Chipcard              | 2         | 6.06%   |
| Bluetooth             | 2         | 6.06%   |
| Storage               | 1         | 3.03%   |
| Modem                 | 1         | 3.03%   |


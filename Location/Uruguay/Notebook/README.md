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

Total: 155

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 22        | 18.97%  |
| Ubuntu 18.04                 | 19        | 16.38%  |
| KDE neon 20.04               | 6         | 5.17%   |
| OpenMandriva 4.2             | 5         | 4.31%   |
| Manjaro                      | 4         | 3.45%   |
| Ubuntu 21.10                 | 3         | 2.59%   |
| Ubuntu 19.04                 | 3         | 2.59%   |
| Linux Mint 19.3              | 3         | 2.59%   |
| Xubuntu 18.04                | 2         | 1.72%   |
| Ubuntu 21.04                 | 2         | 1.72%   |
| Ubuntu 18.10                 | 2         | 1.72%   |
| Linux Mint 20.1              | 2         | 1.72%   |
| Linux Mint 19.1              | 2         | 1.72%   |
| Kubuntu 18.04                | 2         | 1.72%   |
| Arch Rolling                 | 2         | 1.72%   |
| Zorin 16                     | 1         | 0.86%   |
| Zorin 15                     | 1         | 0.86%   |
| Xubuntu 20.04                | 1         | 0.86%   |
| Ubuntu MATE 20.04            | 1         | 0.86%   |
| Ubuntu 22.04                 | 1         | 0.86%   |
| Ubuntu 20.10                 | 1         | 0.86%   |
| Ubuntu 19.10                 | 1         | 0.86%   |
| Ubuntu 17.10                 | 1         | 0.86%   |
| ROSA R11.1                   | 1         | 0.86%   |
| openSUSE Leap-15.1           | 1         | 0.86%   |
| OpenMandriva 4.3             | 1         | 0.86%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.86%   |
| Manjaro 21.2.0               | 1         | 0.86%   |
| Lubuntu 20.04                | 1         | 0.86%   |
| Lubuntu 19.10                | 1         | 0.86%   |
| Linux Mint 20.2              | 1         | 0.86%   |
| Linux Mint 20                | 1         | 0.86%   |
| Linux Mint 19.2              | 1         | 0.86%   |
| Linux Mint 19                | 1         | 0.86%   |
| Kubuntu 20.10                | 1         | 0.86%   |
| Kubuntu 20.04                | 1         | 0.86%   |
| Gentoo 2.8                   | 1         | 0.86%   |
| Feren OS 18.04               | 1         | 0.86%   |
| Fedora 35                    | 1         | 0.86%   |
| Fedora 34                    | 1         | 0.86%   |
| Fedora 30                    | 1         | 0.86%   |
| Endless 3.8.7                | 1         | 0.86%   |
| Endless 3.7.8                | 1         | 0.86%   |
| Endless 3.6.2                | 1         | 0.86%   |
| Endless 3.4.2-nexthw1        | 1         | 0.86%   |
| EndeavourOS                  | 1         | 0.86%   |
| Elementary 6                 | 1         | 0.86%   |
| Elementary 5.1.7             | 1         | 0.86%   |
| Debian 11                    | 1         | 0.86%   |
| BlackPanther 18.1            | 1         | 0.86%   |
| ArcoLinux Rolling            | 1         | 0.86%   |
| Arch                         | 1         | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 53        | 46.49%  |
| Linux Mint   | 11        | 9.65%   |
| OpenMandriva | 6         | 5.26%   |
| KDE neon     | 6         | 5.26%   |
| Manjaro      | 5         | 4.39%   |
| Kubuntu      | 4         | 3.51%   |
| Endless      | 4         | 3.51%   |
| Xubuntu      | 3         | 2.63%   |
| Fedora       | 3         | 2.63%   |
| Arch         | 3         | 2.63%   |
| Zorin        | 2         | 1.75%   |
| Lubuntu      | 2         | 1.75%   |
| Elementary   | 2         | 1.75%   |
| Ubuntu MATE  | 1         | 0.88%   |
| ROSA         | 1         | 0.88%   |
| openSUSE     | 1         | 0.88%   |
| NixOS        | 1         | 0.88%   |
| Gentoo       | 1         | 0.88%   |
| Feren OS     | 1         | 0.88%   |
| EndeavourOS  | 1         | 0.88%   |
| Debian       | 1         | 0.88%   |
| BlackPanther | 1         | 0.88%   |
| ArcoLinux    | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 4.16.18-pa2-2bp1            | 6         | 4.96%   |
| 5.10.14-desktop-1omv4002    | 5         | 4.13%   |
| 4.16.18-pa2-1bp5            | 5         | 4.13%   |
| 5.8.0-53-generic            | 4         | 3.31%   |
| 5.13.0-39-generic           | 4         | 3.31%   |
| 5.4.0-73-generic            | 3         | 2.48%   |
| 5.4.0-58-generic            | 3         | 2.48%   |
| 5.4.0-52-generic            | 3         | 2.48%   |
| 5.11.0-38-generic           | 3         | 2.48%   |
| 5.8.0-50-generic            | 2         | 1.65%   |
| 5.8.0-43-generic            | 2         | 1.65%   |
| 5.5.19-bp0                  | 2         | 1.65%   |
| 5.4.0-72-generic            | 2         | 1.65%   |
| 5.4.0-42-generic            | 2         | 1.65%   |
| 5.3.0-28-generic            | 2         | 1.65%   |
| 5.13.0-40-generic           | 2         | 1.65%   |
| 5.13.0-37-generic           | 2         | 1.65%   |
| 5.13.0-30-generic           | 2         | 1.65%   |
| 5.11.12-desktop-1omv4002    | 2         | 1.65%   |
| 5.0.0-13-generic            | 2         | 1.65%   |
| 4.15.0-51-generic           | 2         | 1.65%   |
| 4.15.0-20-generic           | 2         | 1.65%   |
| 4.15.0-101-generic          | 2         | 1.65%   |
| 5.8.11-1-MANJARO            | 1         | 0.83%   |
| 5.8.1-3-MANJARO             | 1         | 0.83%   |
| 5.8.0-49-generic            | 1         | 0.83%   |
| 5.8.0-48-generic            | 1         | 0.83%   |
| 5.8.0-44-generic            | 1         | 0.83%   |
| 5.8.0-34-generic            | 1         | 0.83%   |
| 5.6.8-1-MANJARO             | 1         | 0.83%   |
| 5.4.60-1-lts                | 1         | 0.83%   |
| 5.4.32-generic-2rosa-x86_64 | 1         | 0.83%   |
| 5.4.0-80-generic            | 1         | 0.83%   |
| 5.4.0-70-generic            | 1         | 0.83%   |
| 5.4.0-65-generic            | 1         | 0.83%   |
| 5.4.0-62-generic            | 1         | 0.83%   |
| 5.4.0-59-generic            | 1         | 0.83%   |
| 5.4.0-39-generic            | 1         | 0.83%   |
| 5.4.0-37-generic            | 1         | 0.83%   |
| 5.4.0-28-generic            | 1         | 0.83%   |
| 5.3.0-51-generic            | 1         | 0.83%   |
| 5.3.0-46-generic            | 1         | 0.83%   |
| 5.3.0-10-generic            | 1         | 0.83%   |
| 5.2.13-200.fc30.x86_64      | 1         | 0.83%   |
| 5.17.4-arch1-1              | 1         | 0.83%   |
| 5.16.16-arch1-1             | 1         | 0.83%   |
| 5.16.13-desktop-1omv4003    | 1         | 0.83%   |
| 5.16.12-200.fc35.x86_64     | 1         | 0.83%   |
| 5.16.0-gentoo-gentoo-dist   | 1         | 0.83%   |
| 5.15.3                      | 1         | 0.83%   |
| 5.15.0-30-generic           | 1         | 0.83%   |
| 5.14.18-1-MANJARO           | 1         | 0.83%   |
| 5.13.0-44-generic           | 1         | 0.83%   |
| 5.13.0-22-generic           | 1         | 0.83%   |
| 5.11.20-300.fc34.x86_64     | 1         | 0.83%   |
| 5.11.11-051111-generic      | 1         | 0.83%   |
| 5.11.0-34-generic           | 1         | 0.83%   |
| 5.11.0-25-generic           | 1         | 0.83%   |
| 5.11.0-14-generic           | 1         | 0.83%   |
| 5.10.4-arch2-1              | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 17.65%  |
| 5.8.0   | 12        | 10.08%  |
| 5.13.0  | 11        | 9.24%   |
| 4.16.18 | 11        | 9.24%   |
| 4.15.0  | 9         | 7.56%   |
| 5.11.0  | 6         | 5.04%   |
| 5.0.0   | 6         | 5.04%   |
| 5.3.0   | 5         | 4.2%    |
| 5.10.14 | 5         | 4.2%    |
| 4.18.0  | 4         | 3.36%   |
| 5.5.19  | 2         | 1.68%   |
| 5.11.12 | 2         | 1.68%   |
| 5.8.11  | 1         | 0.84%   |
| 5.8.1   | 1         | 0.84%   |
| 5.6.8   | 1         | 0.84%   |
| 5.4.60  | 1         | 0.84%   |
| 5.4.32  | 1         | 0.84%   |
| 5.2.13  | 1         | 0.84%   |
| 5.17.4  | 1         | 0.84%   |
| 5.16.16 | 1         | 0.84%   |
| 5.16.13 | 1         | 0.84%   |
| 5.16.12 | 1         | 0.84%   |
| 5.16.0  | 1         | 0.84%   |
| 5.15.3  | 1         | 0.84%   |
| 5.15.0  | 1         | 0.84%   |
| 5.14.18 | 1         | 0.84%   |
| 5.11.20 | 1         | 0.84%   |
| 5.11.11 | 1         | 0.84%   |
| 5.10.4  | 1         | 0.84%   |
| 5.10.31 | 1         | 0.84%   |
| 5.10.30 | 1         | 0.84%   |
| 5.10.0  | 1         | 0.84%   |
| 4.18.16 | 1         | 0.84%   |
| 4.17.19 | 1         | 0.84%   |
| 4.16.0  | 1         | 0.84%   |
| 4.13.0  | 1         | 0.84%   |
| 4.12.14 | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 19.33%  |
| 5.8     | 14        | 11.76%  |
| 4.16    | 12        | 10.08%  |
| 5.13    | 11        | 9.24%   |
| 5.11    | 10        | 8.4%    |
| 5.10    | 9         | 7.56%   |
| 4.15    | 9         | 7.56%   |
| 5.0     | 6         | 5.04%   |
| 5.3     | 5         | 4.2%    |
| 4.18    | 5         | 4.2%    |
| 5.16    | 4         | 3.36%   |
| 5.5     | 2         | 1.68%   |
| 5.15    | 2         | 1.68%   |
| 5.6     | 1         | 0.84%   |
| 5.2     | 1         | 0.84%   |
| 5.17    | 1         | 0.84%   |
| 5.14    | 1         | 0.84%   |
| 4.17    | 1         | 0.84%   |
| 4.13    | 1         | 0.84%   |
| 4.12    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 98.2%   |
| i686   | 2         | 1.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 36        | 31.58%  |
| Unknown         | 21        | 18.42%  |
| KDE5            | 16        | 14.04%  |
| GNOME Flashback | 11        | 9.65%   |
| XFCE            | 8         | 7.02%   |
| X-Cinnamon      | 6         | 5.26%   |
| KDE             | 5         | 4.39%   |
| MATE            | 3         | 2.63%   |
| LXQt            | 3         | 2.63%   |
| Pantheon        | 2         | 1.75%   |
| Cinnamon        | 2         | 1.75%   |
| sway            | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 89        | 80.18%  |
| Wayland | 12        | 10.81%  |
| Unknown | 9         | 8.11%   |
| Tty     | 1         | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 59        | 52.68%  |
| GDM     | 22        | 19.64%  |
| SDDM    | 17        | 15.18%  |
| GDM3    | 6         | 5.36%   |
| LightDM | 4         | 3.57%   |
| TDM     | 3         | 2.68%   |
| GREETD  | 1         | 0.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_UY   | 57        | 49.57%  |
| en_US   | 21        | 18.26%  |
| Unknown | 18        | 15.65%  |
| es_ES   | 12        | 10.43%  |
| es_MX   | 3         | 2.61%   |
| es_AR   | 2         | 1.74%   |
| en_CA   | 1         | 0.87%   |
| C       | 1         | 0.87%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 54.46%  |
| BIOS | 51        | 45.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 88.5%   |
| Overlay | 6         | 5.31%   |
| Unknown | 4         | 3.54%   |
| Btrfs   | 2         | 1.77%   |
| Ext3    | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 64.86%  |
| GPT     | 29        | 26.13%  |
| MBR     | 10        | 9.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 83.78%  |
| Yes       | 18        | 16.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 71.43%  |
| Yes       | 32        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 20.72%  |
| Lenovo              | 19        | 17.12%  |
| ECS                 | 13        | 11.71%  |
| Dell                | 12        | 10.81%  |
| ASUSTek Computer    | 10        | 9.01%   |
| Acer                | 10        | 9.01%   |
| Toshiba             | 6         | 5.41%   |
| Samsung Electronics | 4         | 3.6%    |
| MSI                 | 4         | 3.6%    |
| Standard            | 3         | 2.7%    |
| Sony                | 1         | 0.9%    |
| Positivo            | 1         | 0.9%    |
| Panasonic           | 1         | 0.9%    |
| OEM                 | 1         | 0.9%    |
| Haitech             | 1         | 0.9%    |
| GPU Company         | 1         | 0.9%    |
| Apple               | 1         | 0.9%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 13        | 11.71%  |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.7%    |
| Toshiba Satellite L55t-B              | 2         | 1.8%    |
| Standard SF20BA2                      | 2         | 1.8%    |
| HP Pavilion 15                        | 2         | 1.8%    |
| HP Laptop 15-bs0xx                    | 2         | 1.8%    |
| Toshiba Satellite C75D-C              | 1         | 0.9%    |
| Toshiba Satellite C645D               | 1         | 0.9%    |
| Toshiba Satellite C55-B               | 1         | 0.9%    |
| Toshiba Satellite C45-A               | 1         | 0.9%    |
| Standard EF20EA                       | 1         | 0.9%    |
| Sony SVF14211CLB                      | 1         | 0.9%    |
| Samsung NC208/NC108                   | 1         | 0.9%    |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.9%    |
| Samsung 700T                          | 1         | 0.9%    |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.9%    |
| Positivo Serie AT300                  | 1         | 0.9%    |
| Panasonic CF-31JEGAX1M                | 1         | 0.9%    |
| OEM V40SI2                            | 1         | 0.9%    |
| MSI GS63VR 6RF                        | 1         | 0.9%    |
| MSI GL65 Leopard 10SCXR               | 1         | 0.9%    |
| MSI GL63 8RD                          | 1         | 0.9%    |
| MSI GE62 6QD                          | 1         | 0.9%    |
| Lenovo V15-ADA 82C7                   | 1         | 0.9%    |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.9%    |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.9%    |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.9%    |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.9%    |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.9%    |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.9%    |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.9%    |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.9%    |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.9%    |
| Lenovo IdeaPad S340-15IWL 81N8        | 1         | 0.9%    |
| Lenovo IdeaPad S145-15AST 81N3        | 1         | 0.9%    |
| Lenovo IdeaPad 330S-15ARR 81FB        | 1         | 0.9%    |
| Lenovo IdeaPad 320-17IKB 81BJ         | 1         | 0.9%    |
| Lenovo IdeaPad 300-15ISK 80RS         | 1         | 0.9%    |
| Lenovo G50-70 20351                   | 1         | 0.9%    |
| Lenovo G405 20239                     | 1         | 0.9%    |
| Lenovo B51-30 80LK                    | 1         | 0.9%    |
| Lenovo B50-45 20388                   | 1         | 0.9%    |
| HP ZBook 14u G4                       | 1         | 0.9%    |
| HP Stream Laptop 14-ax0XX             | 1         | 0.9%    |
| HP Presario CQ43                      | 1         | 0.9%    |
| HP Pavilion dv6                       | 1         | 0.9%    |
| HP Pavilion dv5                       | 1         | 0.9%    |
| HP Pavilion dm4                       | 1         | 0.9%    |
| HP Pavilion 17                        | 1         | 0.9%    |
| HP Notebook                           | 1         | 0.9%    |
| HP Laptop 15-db0xxx                   | 1         | 0.9%    |
| HP Laptop 14-dq1xxx                   | 1         | 0.9%    |
| HP Laptop 14-dk1xxx                   | 1         | 0.9%    |
| HP Laptop 14-dk0xxx                   | 1         | 0.9%    |
| HP Laptop 14-df0xxx                   | 1         | 0.9%    |
| HP ENVY TS 15                         | 1         | 0.9%    |
| HP EliteBook 840 G1                   | 1         | 0.9%    |
| HP Casablanca H710                    | 1         | 0.9%    |
| HP 620                                | 1         | 0.9%    |
| HP 240 G7                             | 1         | 0.9%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 13        | 11.71%  |
| Lenovo ThinkPad        | 8         | 7.21%   |
| HP Laptop              | 7         | 6.31%   |
| Dell Inspiron          | 7         | 6.31%   |
| Acer Aspire            | 7         | 6.31%   |
| Toshiba Satellite      | 6         | 5.41%   |
| HP Pavilion            | 6         | 5.41%   |
| Lenovo IdeaPad         | 5         | 4.5%    |
| ASUS ROG               | 3         | 2.7%    |
| Standard SF20BA2       | 2         | 1.8%    |
| Dell XPS               | 2         | 1.8%    |
| Dell Latitude          | 2         | 1.8%    |
| ASUS VivoBook          | 2         | 1.8%    |
| Acer TravelMate        | 2         | 1.8%    |
| Standard EF20EA        | 1         | 0.9%    |
| Sony SVF14211CLB       | 1         | 0.9%    |
| Samsung NC208          | 1         | 0.9%    |
| Samsung N102SP         | 1         | 0.9%    |
| Samsung 700T           | 1         | 0.9%    |
| Samsung 300E4C         | 1         | 0.9%    |
| Positivo Serie         | 1         | 0.9%    |
| Panasonic CF-31JEGAX1M | 1         | 0.9%    |
| OEM V40SI2             | 1         | 0.9%    |
| MSI GS63VR             | 1         | 0.9%    |
| MSI GL65               | 1         | 0.9%    |
| MSI GL63               | 1         | 0.9%    |
| MSI GE62               | 1         | 0.9%    |
| Lenovo V15-ADA         | 1         | 0.9%    |
| Lenovo ThinkBook       | 1         | 0.9%    |
| Lenovo G50-70          | 1         | 0.9%    |
| Lenovo G405            | 1         | 0.9%    |
| Lenovo B51-30          | 1         | 0.9%    |
| Lenovo B50-45          | 1         | 0.9%    |
| HP ZBook               | 1         | 0.9%    |
| HP Stream              | 1         | 0.9%    |
| HP Presario            | 1         | 0.9%    |
| HP Notebook            | 1         | 0.9%    |
| HP ENVY                | 1         | 0.9%    |
| HP EliteBook           | 1         | 0.9%    |
| HP Casablanca          | 1         | 0.9%    |
| HP 620                 | 1         | 0.9%    |
| HP 240                 | 1         | 0.9%    |
| HP 2000                | 1         | 0.9%    |
| Haitech H7141A         | 1         | 0.9%    |
| GPU Company GWTN156-4  | 1         | 0.9%    |
| Dell Precision         | 1         | 0.9%    |
| ASUS ZenBook           | 1         | 0.9%    |
| ASUS X555LAB           | 1         | 0.9%    |
| ASUS TP300LAB          | 1         | 0.9%    |
| ASUS N46VJ             | 1         | 0.9%    |
| ASUS ASUS              | 1         | 0.9%    |
| Apple MacBookAir7      | 1         | 0.9%    |
| Acer Swift             | 1         | 0.9%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 20        | 18.02%  |
| 2019 | 14        | 12.61%  |
| 2020 | 11        | 9.91%   |
| 2018 | 11        | 9.91%   |
| 2013 | 11        | 9.91%   |
| 2014 | 9         | 8.11%   |
| 2011 | 9         | 8.11%   |
| 2016 | 8         | 7.21%   |
| 2012 | 5         | 4.5%    |
| 2015 | 4         | 3.6%    |
| 2010 | 3         | 2.7%    |
| 2008 | 3         | 2.7%    |
| 2007 | 2         | 1.8%    |
| 2009 | 1         | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 111       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 98        | 88.29%  |
| Enabled  | 13        | 11.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 111       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 30        | 26.55%  |
| 4.01-8.0    | 29        | 25.66%  |
| 1.01-2.0    | 18        | 15.93%  |
| 8.01-16.0   | 17        | 15.04%  |
| 16.01-24.0  | 9         | 7.96%   |
| 32.01-64.0  | 5         | 4.42%   |
| 24.01-32.0  | 3         | 2.65%   |
| 2.01-3.0    | 1         | 0.88%   |
| 64.01-256.0 | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 51        | 43.59%  |
| 2.01-3.0  | 25        | 21.37%  |
| 4.01-8.0  | 13        | 11.11%  |
| 3.01-4.0  | 11        | 9.4%    |
| 0.51-1.0  | 11        | 9.4%    |
| 8.01-16.0 | 5         | 4.27%   |
| 0.01-0.5  | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 81.98%  |
| 2      | 19        | 17.12%  |
| 0      | 1         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 69.37%  |
| Yes       | 34        | 30.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 66.67%  |
| No        | 37        | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 98.2%   |
| No        | 2         | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 81.08%  |
| No        | 21        | 18.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 111       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 75        | 64.1%   |
| Canelones              | 8         | 6.84%   |
| Maldonado              | 6         | 5.13%   |
| Salto                  | 2         | 1.71%   |
| Rocha                  | 2         | 1.71%   |
| Punta Gorda            | 2         | 1.71%   |
| Punta del Este         | 2         | 1.71%   |
| Las Piedras            | 2         | 1.71%   |
| Ciudad del Plata       | 2         | 1.71%   |
| Buceo                  | 2         | 1.71%   |
| Solymar                | 1         | 0.85%   |
| San Jose de Mayo       | 1         | 0.85%   |
| Paysandú              | 1         | 0.85%   |
| Parque Rodo            | 1         | 0.85%   |
| Melilla                | 1         | 0.85%   |
| Maronas                | 1         | 0.85%   |
| Las Flores             | 1         | 0.85%   |
| La Paz                 | 1         | 0.85%   |
| Joaquin Suarez         | 1         | 0.85%   |
| El Tesoro              | 1         | 0.85%   |
| El Pinar               | 1         | 0.85%   |
| Durazno                | 1         | 0.85%   |
| Barrancas Coloradas    | 1         | 0.85%   |
| Arenas de Jose Ignacio | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 23     | 16.26%  |
| Unknown             | 16        | 20     | 13.01%  |
| Toshiba             | 15        | 17     | 12.2%   |
| Kingston            | 14        | 19     | 11.38%  |
| Seagate             | 13        | 14     | 10.57%  |
| SanDisk             | 10        | 11     | 8.13%   |
| Samsung Electronics | 9         | 9      | 7.32%   |
| Hitachi             | 6         | 8      | 4.88%   |
| Intel               | 4         | 4      | 3.25%   |
| SK Hynix            | 3         | 3      | 2.44%   |
| HGST                | 3         | 3      | 2.44%   |
| Hewlett-Packard     | 2         | 2      | 1.63%   |
| Crucial             | 2         | 3      | 1.63%   |
| Netac               | 1         | 1      | 0.81%   |
| LITEON              | 1         | 2      | 0.81%   |
| China               | 1         | 1      | 0.81%   |
| BIWIN               | 1         | 1      | 0.81%   |
| BHT                 | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 9         | 7.2%    |
| Kingston SA400S37240G 240GB SSD       | 6         | 4.8%    |
| Unknown DA4032  32GB                  | 5         | 4%      |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 3.2%    |
| Toshiba MQ01ABD075 752GB              | 3         | 2.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 2.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 2.4%    |
| WDC WD5000BEKT-60KA9T0 500GB          | 2         | 1.6%    |
| Unknown SD/MMC/MS PRO 999GB           | 2         | 1.6%    |
| Toshiba MQ01ABF050 500GB              | 2         | 1.6%    |
| Toshiba HDWK105 500GB                 | 2         | 1.6%    |
| Sandisk NVMe SSD Drive 256GB          | 2         | 1.6%    |
| Sandisk NVMe SSD Drive 1024GB         | 2         | 1.6%    |
| SanDisk DF4032  32GB                  | 2         | 1.6%    |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.6%    |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 1         | 0.8%    |
| WDC WDS250G2X0C-00L350 250GB          | 1         | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.8%    |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 0.8%    |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.8%    |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.8%    |
| WDC WD5000LPVT-24G33T1 500GB          | 1         | 0.8%    |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.8%    |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.8%    |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 0.8%    |
| WDC WD3200LPCX-24C6HT0 320GB          | 1         | 0.8%    |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.8%    |
| WDC WD10SPZX-08Z10 1TB                | 1         | 0.8%    |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.8%    |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 0.8%    |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 0.8%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 0.8%    |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.8%    |
| Unknown MMC Card  64GB                | 1         | 0.8%    |
| Unknown MMC Card  4GB                 | 1         | 0.8%    |
| Toshiba THNSNJ256G8NY 256GB SSD       | 1         | 0.8%    |
| Toshiba MQ04ABF100 1TB                | 1         | 0.8%    |
| Toshiba MQ01ABD100 1TB                | 1         | 0.8%    |
| Toshiba MK5059GSXP 500GB              | 1         | 0.8%    |
| Toshiba MK3259GSXP 320GB              | 1         | 0.8%    |
| Toshiba KXG6AZNV512G 512GB            | 1         | 0.8%    |
| Toshiba KXG50ZNV256G 256GB            | 1         | 0.8%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 1         | 0.8%    |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.8%    |
| SK Hynix HFS256G32TNH-73A0A 256GB SSD | 1         | 0.8%    |
| SK Hynix HFM256GDHTNG-8310A 256GB     | 1         | 0.8%    |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.8%    |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.8%    |
| Seagate Expansion 4TB                 | 1         | 0.8%    |
| SanDisk SSD U100 8GB                  | 1         | 0.8%    |
| SanDisk SDSSDP128G 128GB              | 1         | 0.8%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 0.8%    |
| Sandisk NVMe SSD Drive 1TB            | 1         | 0.8%    |
| Samsung SSD SM841 2.5 7mm 128GB       | 1         | 0.8%    |
| Samsung SSD 970 EVO Plus 1TB          | 1         | 0.8%    |
| Samsung SSD 860 EVO 500GB             | 1         | 0.8%    |
| Samsung SSD 860 EVO 250GB             | 1         | 0.8%    |
| Samsung SSD 850 EVO 500GB             | 1         | 0.8%    |
| Samsung PM951 NVMe 256GB              | 1         | 0.8%    |
| Samsung NVMe SSD Drive 1024GB         | 1         | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 18     | 30%     |
| Seagate | 13        | 14     | 26%     |
| Toshiba | 11        | 13     | 22%     |
| Hitachi | 6         | 8      | 12%     |
| HGST    | 3         | 3      | 6%      |
| Unknown | 2         | 2      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 14     | 33.33%  |
| Samsung Electronics | 5         | 5      | 15.15%  |
| SanDisk             | 3         | 3      | 9.09%   |
| WDC                 | 2         | 2      | 6.06%   |
| SK Hynix            | 2         | 2      | 6.06%   |
| Intel               | 2         | 2      | 6.06%   |
| Hewlett-Packard     | 2         | 2      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| Crucial             | 1         | 2      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| BIWIN               | 1         | 1      | 3.03%   |
| BHT                 | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 58     | 40%     |
| SSD  | 32        | 37     | 26.67%  |
| NVMe | 24        | 27     | 20%     |
| MMC  | 16        | 21     | 13.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 92     | 62.93%  |
| NVMe | 24        | 27     | 20.69%  |
| MMC  | 16        | 21     | 13.79%  |
| SAS  | 3         | 3      | 2.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 61     | 65.43%  |
| 0.51-1.0   | 26        | 32     | 32.1%   |
| 3.01-4.0   | 1         | 1      | 1.23%   |
| 1.01-2.0   | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 26.09%  |
| 251-500        | 26        | 22.61%  |
| 501-1000       | 19        | 16.52%  |
| 21-50          | 16        | 13.91%  |
| 1-20           | 12        | 10.43%  |
| 51-100         | 6         | 5.22%   |
| Unknown        | 3         | 2.61%   |
| 1001-2000      | 2         | 1.74%   |
| More than 3000 | 1         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 58        | 48.74%  |
| 21-50          | 21        | 17.65%  |
| 251-500        | 12        | 10.08%  |
| 51-100         | 11        | 9.24%   |
| 101-250        | 9         | 7.56%   |
| 501-1000       | 4         | 3.36%   |
| Unknown        | 3         | 2.52%   |
| More than 3000 | 1         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 2      | 22.22%  |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 11.11%  |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 11.11%  |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 11.11%  |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 11.11%  |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 33.33%  |
| Toshiba | 2         | 3      | 22.22%  |
| Seagate | 2         | 2      | 22.22%  |
| SanDisk | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 37.5%   |
| Toshiba | 2         | 3      | 25%     |
| Seagate | 2         | 2      | 25%     |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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
| Detected | 70        | 91     | 62.5%   |
| Works    | 33        | 42     | 29.46%  |
| Malfunc  | 9         | 10     | 8.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 78        | 63.93%  |
| AMD                              | 21        | 17.21%  |
| Sandisk                          | 8         | 6.56%   |
| Samsung Electronics              | 4         | 3.28%   |
| Toshiba America Info Systems     | 3         | 2.46%   |
| Kingston Technology Company      | 3         | 2.46%   |
| SK Hynix                         | 1         | 0.82%   |
| Silicon Integrated Systems [SiS] | 1         | 0.82%   |
| Micron/Crucial Technology        | 1         | 0.82%   |
| Lite-On Technology               | 1         | 0.82%   |
| Apple                            | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 19        | 14.96%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 14        | 11.02%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 6.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 4.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 3.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 3.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 3.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 4         | 3.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 3.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.36%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 1.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 1.57%   |
| Intel SSD 660P Series                                                                  | 2         | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.79%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.79%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.79%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.79%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.79%   |
| Lite-On NVMe Controller                                                                | 1         | 0.79%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.79%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.79%   |
| Apple S1X NVMe Controller                                                              | 1         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 91        | 72.22%  |
| NVMe | 24        | 19.05%  |
| RAID | 6         | 4.76%   |
| IDE  | 5         | 3.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 78.38%  |
| AMD    | 24        | 21.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 14        | 12.61%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.7%    |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.8%    |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.8%    |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.8%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.8%    |
| AMD E-300 APU with Radeon HD Graphics        | 2         | 1.8%    |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.8%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.9%    |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.9%    |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.9%    |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.9%    |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.9%    |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.9%    |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 1         | 0.9%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.9%    |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.9%    |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.9%    |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.9%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz            | 1         | 0.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 0.9%    |
| Intel Core i5-5250U CPU @ 1.60GHz            | 1         | 0.9%    |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.9%    |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 0.9%    |
| Intel Core i5-3340M CPU @ 2.70GHz            | 1         | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.9%    |
| Intel Core i5-2467M CPU @ 1.60GHz            | 1         | 0.9%    |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 0.9%    |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.9%    |
| Intel Core i5-1035G4 CPU @ 1.10GHz           | 1         | 0.9%    |
| Intel Core i3-8130U CPU @ 2.20GHz            | 1         | 0.9%    |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.9%    |
| Intel Core i3-6100U CPU @ 2.30GHz            | 1         | 0.9%    |
| Intel Core i3-5020U CPU @ 2.20GHz            | 1         | 0.9%    |
| Intel Core i3-4030U CPU @ 1.90GHz            | 1         | 0.9%    |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.9%    |
| Intel Core i3 CPU M 390 @ 2.67GHz            | 1         | 0.9%    |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 0.9%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz         | 1         | 0.9%    |
| Intel Celeron N4100 CPU @ 1.10GHz            | 1         | 0.9%    |
| Intel Celeron CPU N3060 @ 1.60GHz            | 1         | 0.9%    |
| Intel Celeron CPU N2830 @ 2.16GHz            | 1         | 0.9%    |
| Intel Celeron CPU 847 @ 1.10GHz              | 1         | 0.9%    |
| Intel Atom CPU N455 @ 1.66GHz                | 1         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 22        | 19.82%  |
| Intel Core i7      | 20        | 18.02%  |
| Intel Celeron      | 20        | 18.02%  |
| Intel Core i3      | 9         | 8.11%   |
| Intel Pentium      | 6         | 5.41%   |
| Intel Atom         | 4         | 3.6%    |
| Other              | 3         | 2.7%    |
| AMD Ryzen 9        | 3         | 2.7%    |
| AMD A6             | 3         | 2.7%    |
| Intel Genuine      | 2         | 1.8%    |
| Intel Core 2 Duo   | 2         | 1.8%    |
| AMD Ryzen 7        | 2         | 1.8%    |
| AMD Ryzen 5        | 2         | 1.8%    |
| AMD Ryzen 3        | 2         | 1.8%    |
| AMD E1             | 2         | 1.8%    |
| AMD E              | 2         | 1.8%    |
| Intel Pentium Dual | 1         | 0.9%    |
| AMD Phenom II      | 1         | 0.9%    |
| AMD FX             | 1         | 0.9%    |
| AMD E2             | 1         | 0.9%    |
| AMD Athlon         | 1         | 0.9%    |
| AMD A8             | 1         | 0.9%    |
| AMD A4             | 1         | 0.9%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 59.46%  |
| 4      | 33        | 29.73%  |
| 6      | 5         | 4.5%    |
| 8      | 4         | 3.6%    |
| 1      | 3         | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 111       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 57.66%  |
| 1      | 47        | 42.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 97.3%   |
| Unknown        | 3         | 2.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 19.82%  |
| 0x406c4    | 6         | 5.41%   |
| 0x40651    | 6         | 5.41%   |
| 0x206a7    | 6         | 5.41%   |
| 0x306d4    | 5         | 4.5%    |
| 0x806ec    | 4         | 3.6%    |
| 0x806ea    | 4         | 3.6%    |
| 0x20655    | 4         | 3.6%    |
| 0x906ea    | 3         | 2.7%    |
| 0x806e9    | 3         | 2.7%    |
| 0x6fd      | 3         | 2.7%    |
| 0x506c9    | 3         | 2.7%    |
| 0x406e3    | 3         | 2.7%    |
| 0x08108109 | 3         | 2.7%    |
| 0x706e5    | 2         | 1.8%    |
| 0x306c3    | 2         | 1.8%    |
| 0x306a9    | 2         | 1.8%    |
| 0x08600104 | 2         | 1.8%    |
| 0x0810100b | 2         | 1.8%    |
| 0x07030104 | 2         | 1.8%    |
| 0x0700010f | 2         | 1.8%    |
| 0x06006705 | 2         | 1.8%    |
| 0xa0652    | 1         | 0.9%    |
| 0x806eb    | 1         | 0.9%    |
| 0x806c1    | 1         | 0.9%    |
| 0x706a1    | 1         | 0.9%    |
| 0x506e3    | 1         | 0.9%    |
| 0x406c3    | 1         | 0.9%    |
| 0x30678    | 1         | 0.9%    |
| 0x30661    | 1         | 0.9%    |
| 0x106e5    | 1         | 0.9%    |
| 0x106ca    | 1         | 0.9%    |
| 0x1067a    | 1         | 0.9%    |
| 0x10676    | 1         | 0.9%    |
| 0x08600102 | 1         | 0.9%    |
| 0x07030106 | 1         | 0.9%    |
| 0x07030105 | 1         | 0.9%    |
| 0x06006118 | 1         | 0.9%    |
| 0x06001119 | 1         | 0.9%    |
| 0x05000119 | 1         | 0.9%    |
| 0x05000101 | 1         | 0.9%    |
| 0x010000b6 | 1         | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 14.41%  |
| Goldmont      | 14        | 12.61%  |
| Silvermont    | 9         | 8.11%   |
| Haswell       | 8         | 7.21%   |
| Skylake       | 6         | 5.41%   |
| SandyBridge   | 6         | 5.41%   |
| Broadwell     | 6         | 5.41%   |
| Zen+          | 4         | 3.6%    |
| Zen 2         | 4         | 3.6%    |
| Westmere      | 4         | 3.6%    |
| Puma          | 4         | 3.6%    |
| IvyBridge     | 4         | 3.6%    |
| Excavator     | 4         | 3.6%    |
| Core          | 3         | 2.7%    |
| Zen           | 2         | 1.8%    |
| Penryn        | 2         | 1.8%    |
| Jaguar        | 2         | 1.8%    |
| IceLake       | 2         | 1.8%    |
| CometLake     | 2         | 1.8%    |
| Bonnell       | 2         | 1.8%    |
| Bobcat        | 2         | 1.8%    |
| TigerLake     | 1         | 0.9%    |
| Piledriver    | 1         | 0.9%    |
| Nehalem       | 1         | 0.9%    |
| K10           | 1         | 0.9%    |
| Goldmont plus | 1         | 0.9%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 85        | 64.39%  |
| AMD                              | 32        | 24.24%  |
| Nvidia                           | 14        | 10.61%  |
| Silicon Integrated Systems [SiS] | 1         | 0.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 14        | 10.37%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 5.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.44%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.96%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.96%   |
| AMD Renoir                                                                               | 4         | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.96%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.22%   |
| Intel HD Graphics 620                                                                    | 3         | 2.22%   |
| Intel HD Graphics 530                                                                    | 3         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 2.22%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.48%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.48%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.48%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.48%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.48%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.74%   |
| Nvidia TU117M                                                                            | 1         | 0.74%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.74%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.74%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.74%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.74%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.74%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.74%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.74%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.74%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.74%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.74%   |
| AMD Richland [Radeon HD 8450G]                                                           | 1         | 0.74%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 0.74%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 0.74%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 0.74%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 61.26%  |
| 1 x AMD        | 19        | 17.12%  |
| Intel + Nvidia | 9         | 8.11%   |
| Intel + AMD    | 8         | 7.21%   |
| AMD + Nvidia   | 4         | 3.6%    |
| 2 x AMD        | 1         | 0.9%    |
| 1 x SiS        | 1         | 0.9%    |
| 1 x Nvidia     | 1         | 0.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 101       | 90.99%  |
| Proprietary | 9         | 8.11%   |
| Unknown     | 1         | 0.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 67.57%  |
| 0.51-1.0   | 10        | 9.01%   |
| 0.01-0.5   | 10        | 9.01%   |
| 1.01-2.0   | 9         | 8.11%   |
| 3.01-4.0   | 5         | 4.5%    |
| 5.01-6.0   | 2         | 1.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 18        | 14.88%  |
| Chimei Innolux          | 17        | 14.05%  |
| BOE                     | 17        | 14.05%  |
| AU Optronics            | 15        | 12.4%   |
| Samsung Electronics     | 13        | 10.74%  |
| KDC                     | 6         | 4.96%   |
| InfoVision              | 6         | 4.96%   |
| Sharp                   | 4         | 3.31%   |
| ViewSonic               | 3         | 2.48%   |
| PANDA                   | 3         | 2.48%   |
| Chi Mei Optoelectronics | 3         | 2.48%   |
| Acer                    | 3         | 2.48%   |
| KTC                     | 2         | 1.65%   |
| Sun                     | 1         | 0.83%   |
| LG Philips              | 1         | 0.83%   |
| JDI                     | 1         | 0.83%   |
| InnoLux Display         | 1         | 0.83%   |
| HSI                     | 1         | 0.83%   |
| HKC                     | 1         | 0.83%   |
| Hewlett-Packard         | 1         | 0.83%   |
| Dell                    | 1         | 0.83%   |
| CPT                     | 1         | 0.83%   |
| Apple                   | 1         | 0.83%   |
| AOC                     | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 5         | 4.07%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 4         | 3.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 2.44%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.63%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.63%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.63%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.63%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.63%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.63%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.63%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch           | 1         | 0.81%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.81%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.81%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 286x179mm 13.3-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0396 1600x900 380x210mm 17.1-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch           | 1         | 0.81%   |
| KTC 23L13-H-AN KTC2304 1920x1080 510x287mm 23.0-inch                  | 1         | 0.81%   |
| KTC 23'TV KTC2300 1920x1080 510x290mm 23.1-inch                       | 1         | 0.81%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 0.81%   |
| InnoLux Display LCD Monitor INL0015 1366x768 309x174mm 14.0-inch      | 1         | 0.81%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch           | 1         | 0.81%   |
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                      | 1         | 0.81%   |
| HKC Checksum: 0x8a (valid) HKC1850 1360x768 304x228mm 15.0-inch       | 1         | 0.81%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x287mm 23.0-inch          | 1         | 0.81%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 1         | 0.81%   |
| CPT LCD Monitor CPT1BC7 1024x600 223x125mm 10.1-inch                  | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch       | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 61        | 55.45%  |
| 1920x1080 (FHD)   | 30        | 27.27%  |
| 1600x900 (HD+)    | 6         | 5.45%   |
| 1920x1200 (WUXGA) | 5         | 4.55%   |
| 1280x800 (WXGA)   | 3         | 2.73%   |
| 3840x2160 (4K)    | 2         | 1.82%   |
| 2560x1440 (QHD)   | 1         | 0.91%   |
| 1360x768          | 1         | 0.91%   |
| 1024x600          | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 59        | 48.76%  |
| 13     | 18        | 14.88%  |
| 14     | 15        | 12.4%   |
| 11     | 5         | 4.13%   |
| 24     | 4         | 3.31%   |
| 17     | 4         | 3.31%   |
| 27     | 3         | 2.48%   |
| 23     | 3         | 2.48%   |
| 21     | 2         | 1.65%   |
| 18     | 2         | 1.65%   |
| 12     | 2         | 1.65%   |
| 10     | 2         | 1.65%   |
| 57     | 1         | 0.83%   |
| 34     | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 71.67%  |
| 201-300     | 13        | 10.83%  |
| 501-600     | 10        | 8.33%   |
| 351-400     | 5         | 4.17%   |
| 401-500     | 4         | 3.33%   |
| 701-800     | 1         | 0.83%   |
| 1001-1500   | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 99        | 95.19%  |
| 16/10 | 4         | 3.85%   |
| 21/9  | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 48.76%  |
| 81-90          | 29        | 23.97%  |
| 201-250        | 7         | 5.79%   |
| 51-60          | 5         | 4.13%   |
| 71-80          | 4         | 3.31%   |
| 121-130        | 4         | 3.31%   |
| 301-350        | 3         | 2.48%   |
| 61-70          | 2         | 1.65%   |
| 41-50          | 2         | 1.65%   |
| 151-200        | 2         | 1.65%   |
| 141-150        | 2         | 1.65%   |
| More than 1000 | 1         | 0.83%   |
| 351-500        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 60        | 50.42%  |
| 121-160       | 32        | 26.89%  |
| 51-100        | 22        | 18.49%  |
| 161-240       | 3         | 2.52%   |
| More than 240 | 1         | 0.84%   |
| 1-50          | 1         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 92        | 81.42%  |
| 2     | 17        | 15.04%  |
| 3     | 2         | 1.77%   |
| 0     | 2         | 1.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 55        | 32.54%  |
| Intel                            | 52        | 30.77%  |
| Qualcomm Atheros                 | 27        | 15.98%  |
| Broadcom                         | 13        | 7.69%   |
| Ralink Technology                | 3         | 1.78%   |
| Ralink                           | 3         | 1.78%   |
| TP-Link                          | 2         | 1.18%   |
| MEDIATEK                         | 2         | 1.18%   |
| Broadcom Limited                 | 2         | 1.18%   |
| Xiaomi                           | 1         | 0.59%   |
| T & A Mobile Phones              | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |
| Sierra Wireless                  | 1         | 0.59%   |
| Samsung Electronics              | 1         | 0.59%   |
| Qualcomm Atheros Communications  | 1         | 0.59%   |
| Lenovo                           | 1         | 0.59%   |
| Huawei Technologies              | 1         | 0.59%   |
| DisplayLink                      | 1         | 0.59%   |
| ASIX Electronics                 | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 30        | 15.23%  |
| Intel Wireless 3165                                                     | 19        | 9.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 9.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.54%   |
| Intel Wireless 7265                                                     | 4         | 2.03%   |
| Intel Wireless 7260                                                     | 4         | 2.03%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.03%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.02%   |
| Intel Wireless 8260                                                     | 2         | 1.02%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.02%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.51%   |
| TP-Link USB 10/100/1000 LAN                                             | 1         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.51%   |
| T & A Mobile Phones MT65xx Android Phone                                | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.51%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.51%   |
| Samsung Kiera                                                           | 1         | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.51%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.51%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.51%   |
| MediaTek Vodafone Smart N10                                             | 1         | 0.51%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.51%   |
| Lenovo USB-C to LAN                                                     | 1         | 0.51%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.51%   |
| Intel Wireless 3160                                                     | 1         | 0.51%   |
| Intel WiFi Link 5100                                                    | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 43.48%  |
| Realtek Semiconductor           | 22        | 19.13%  |
| Qualcomm Atheros                | 22        | 19.13%  |
| Broadcom                        | 9         | 7.83%   |
| Ralink Technology               | 3         | 2.61%   |
| Ralink                          | 3         | 2.61%   |
| Broadcom Limited                | 2         | 1.74%   |
| TP-Link                         | 1         | 0.87%   |
| Sierra Wireless                 | 1         | 0.87%   |
| Qualcomm Atheros Communications | 1         | 0.87%   |
| MEDIATEK                        | 1         | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 19        | 16.38%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 6.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 5.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 4.31%   |
| Intel Wireless 7265                                                     | 4         | 3.45%   |
| Intel Wireless 7260                                                     | 4         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.72%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.72%   |
| Intel Wireless 8260                                                     | 2         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.86%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.86%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.86%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.86%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.86%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.86%   |
| Intel Wireless 3160                                                     | 1         | 0.86%   |
| Intel WiFi Link 5100                                                    | 1         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.86%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.86%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.86%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.86%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.86%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.86%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.86%   |
| Broadcom Limited BCM43225 802.11b/g/n                                   | 1         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 49        | 62.03%  |
| Intel                            | 11        | 13.92%  |
| Qualcomm Atheros                 | 6         | 7.59%   |
| Broadcom                         | 5         | 6.33%   |
| Xiaomi                           | 1         | 1.27%   |
| TP-Link                          | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| MediaTek                         | 1         | 1.27%   |
| Lenovo                           | 1         | 1.27%   |
| Huawei Technologies              | 1         | 1.27%   |
| DisplayLink                      | 1         | 1.27%   |
| ASIX Electronics                 | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 37.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 22.78%  |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.53%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.27%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.27%   |
| MediaTek Vodafone Smart N10                                       | 1         | 1.27%   |
| Lenovo USB-C to LAN                                               | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.27%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.27%   |
| Huawei E353/E3131                                                 | 1         | 1.27%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.27%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 58.92%  |
| Ethernet | 74        | 40%     |
| Modem    | 1         | 0.54%   |
| Unknown  | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 85.84%  |
| Ethernet | 16        | 14.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 62.16%  |
| 1     | 40        | 36.04%  |
| 0     | 2         | 1.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 96        | 86.49%  |
| Yes  | 15        | 13.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 47.25%  |
| Realtek Semiconductor           | 13        | 14.29%  |
| Qualcomm Atheros Communications | 9         | 9.89%   |
| Toshiba                         | 5         | 5.49%   |
| IMC Networks                    | 5         | 5.49%   |
| Foxconn / Hon Hai               | 3         | 3.3%    |
| Cambridge Silicon Radio         | 3         | 3.3%    |
| Ralink                          | 2         | 2.2%    |
| Lite-On Technology              | 2         | 2.2%    |
| Broadcom                        | 2         | 2.2%    |
| Ralink Technology               | 1         | 1.1%    |
| Foxconn International           | 1         | 1.1%    |
| Apple                           | 1         | 1.1%    |
| Alps Electric                   | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 29        | 31.87%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 8.79%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 6.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 5.49%   |
| Intel AX200 Bluetooth                               | 4         | 4.4%    |
| Realtek Bluetooth Radio                             | 3         | 3.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.3%    |
| Toshiba Bluetooth Device                            | 2         | 2.2%    |
| Toshiba BCM43142A0                                  | 2         | 2.2%    |
| Ralink RT3290 Bluetooth                             | 2         | 2.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 2.2%    |
| Intel AX201 Bluetooth                               | 2         | 2.2%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.2%    |
| Toshiba Bluetooth Radio                             | 1         | 1.1%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.1%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.1%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.1%    |
| Lite-On Bluetooth Device                            | 1         | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.1%    |
| IMC Networks Bluetooth Device                       | 1         | 1.1%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.1%    |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 1.1%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.1%    |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.1%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.1%    |
| Apple Bluetooth USB Host Controller                 | 1         | 1.1%    |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 84        | 67.74%  |
| AMD                                  | 24        | 19.35%  |
| Nvidia                               | 8         | 6.45%   |
| Logitech                             | 3         | 2.42%   |
| Generalplus Technology               | 2         | 1.61%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.81%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.81%   |
| C-Media Electronics                  | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 8.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 6.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 6.21%   |
| AMD FCH Azalia Controller                                                                         | 8         | 4.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 4.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.73%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 3.73%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.11%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.86%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.86%   |
| Logitech H390 headset with microphone                                                             | 2         | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.24%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.24%   |
| Generalplus Technology Usb Audio Device                                                           | 2         | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.24%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Logitech Headset H390                                                                             | 1         | 0.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.62%   |
| C-Media Electronics SADES Luna                                                                    | 1         | 0.62%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.62%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.62%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 30.65%  |
| SK Hynix            | 13        | 20.97%  |
| Micron Technology   | 8         | 12.9%   |
| Ramaxel Technology  | 5         | 8.06%   |
| Kingston            | 5         | 8.06%   |
| Unknown             | 3         | 4.84%   |
| Goldkey             | 2         | 3.23%   |
| Elpida              | 2         | 3.23%   |
| Crucial             | 2         | 3.23%   |
| A-DATA Technology   | 2         | 3.23%   |
| Nanya Technology    | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 4.62%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 3.08%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 3.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 3.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 3.08%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 3.08%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 3.08%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.54%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 1.54%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.54%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s     | 1         | 1.54%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s    | 1         | 1.54%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.54%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.54%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2400MT/s     | 1         | 1.54%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.54%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.54%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                      | 1         | 1.54%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 1.54%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.54%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 1         | 1.54%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.54%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.54%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.54%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s    | 1         | 1.54%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 1.54%   |
| Nanya RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.54%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.54%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8192MB SODIMM DDR4 2400MT/s       | 1         | 1.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s         | 1         | 1.54%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s         | 1         | 1.54%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.54%   |
| Micron RAM 16ATF4G64HZ-2G6B2 32GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.54%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.54%   |
| Kingston RAM ACR16D3LS1KBGR/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |
| Goldkey RAM GKH200SO25608-1600 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.54%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.54%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 1         | 1.54%   |
| Crucial RAM CT16G4SFD8266.C16FE 16384MB SODIMM DDR4 2667MT/s  | 1         | 1.54%   |
| Crucial RAM BLS8G4S240FSDK.8FD 8192MB SODIMM DDR4 2400MT/s    | 1         | 1.54%   |
| A-DATA RAM Module 32GB SODIMM DDR4 2667MT/s                   | 1         | 1.54%   |
| A-DATA RAM AM1L16BC4R1-B1HS 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 25        | 49.02%  |
| DDR4   | 20        | 39.22%  |
| SDRAM  | 2         | 3.92%   |
| LPDDR3 | 2         | 3.92%   |
| DDR2   | 2         | 3.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 93.88%  |
| Row Of Chips | 2         | 4.08%   |
| DIMM         | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 36.84%  |
| 8192  | 18        | 31.58%  |
| 2048  | 9         | 15.79%  |
| 16384 | 5         | 8.77%   |
| 32768 | 2         | 3.51%   |
| 1024  | 2         | 3.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 22        | 37.93%  |
| 2667  | 13        | 22.41%  |
| 3200  | 5         | 8.62%   |
| 2400  | 4         | 6.9%    |
| 1334  | 4         | 6.9%    |
| 4199  | 2         | 3.45%   |
| 2133  | 2         | 3.45%   |
| 533   | 2         | 3.45%   |
| 3266  | 1         | 1.72%   |
| 1867  | 1         | 1.72%   |
| 1333  | 1         | 1.72%   |
| 1067  | 1         | 1.72%   |

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
| Chicony Electronics                    | 31        | 29.25%  |
| Realtek Semiconductor                  | 13        | 12.26%  |
| Microdia                               | 8         | 7.55%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 7.55%   |
| Acer                                   | 8         | 7.55%   |
| Unknown                                | 5         | 4.72%   |
| Sunplus Innovation Technology          | 5         | 4.72%   |
| Suyin                                  | 4         | 3.77%   |
| Silicon Motion                         | 4         | 3.77%   |
| IMC Networks                           | 4         | 3.77%   |
| Quanta                                 | 3         | 2.83%   |
| Alcor Micro                            | 3         | 2.83%   |
| Syntek                                 | 2         | 1.89%   |
| Lite-On Technology                     | 2         | 1.89%   |
| Importek                               | 2         | 1.89%   |
| Samsung Electronics                    | 1         | 0.94%   |
| Luxvisions Innotech Limited            | 1         | 0.94%   |
| Logitech                               | 1         | 0.94%   |
| DigiTech                               | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 11        | 10.38%  |
| Unknown USB Camera                                             | 5         | 4.72%   |
| Chicony HP Truevision HD                                       | 5         | 4.72%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 3.77%   |
| Chicony Integrated Camera                                      | 4         | 3.77%   |
| Realtek Lenovo EasyCamera                                      | 3         | 2.83%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 2.83%   |
| Chicony TOSHIBA Web Camera - HD                                | 3         | 2.83%   |
| Acer Integrated Camera                                         | 3         | 2.83%   |
| Sunplus HP TrueVision HD Camera                                | 2         | 1.89%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.89%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.89%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.89%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.89%   |
| Chicony HD WebCam                                              | 2         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.89%   |
| Acer HD Webcam                                                 | 2         | 1.89%   |
| Syntek Integrated Camera                                       | 1         | 0.94%   |
| Syntek EasyCamera                                              | 1         | 0.94%   |
| Suyin HP Truevision HD                                         | 1         | 0.94%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.94%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.94%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.94%   |
| Sunplus HD WebCam                                              | 1         | 0.94%   |
| Sunplus Asus Webcam                                            | 1         | 0.94%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.94%   |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.94%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.94%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 0.94%   |
| Realtek USB Camera                                             | 1         | 0.94%   |
| Realtek Integrated Camera                                      | 1         | 0.94%   |
| Realtek HD WebCam                                              | 1         | 0.94%   |
| Realtek Front Camera                                           | 1         | 0.94%   |
| Realtek Acer 640 x 480 laptop camera                           | 1         | 0.94%   |
| Quanta HD Webcam                                               | 1         | 0.94%   |
| Microdia USB Camera                                            | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_0.3M                         | 1         | 0.94%   |
| Microdia HP Webcam                                             | 1         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera                  | 1         | 0.94%   |
| Logitech Webcam C270                                           | 1         | 0.94%   |
| Lite-On Integrated Camera                                      | 1         | 0.94%   |
| Lite-On HP Webcam                                              | 1         | 0.94%   |
| Importek TOSHIBA Web Camera                                    | 1         | 0.94%   |
| Importek HP Webcam                                             | 1         | 0.94%   |
| IMC Networks TOSHIBA Web Camera - HD                           | 1         | 0.94%   |
| IMC Networks Integrated Camera                                 | 1         | 0.94%   |
| DigiTech WebCam SC-30AFL11449M                                 | 1         | 0.94%   |
| Chicony USB2.0 HD Camera                                       | 1         | 0.94%   |
| Chicony Lenovo EasyCamera                                      | 1         | 0.94%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 0.94%   |
| Chicony HP Webcam                                              | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam [2 MP Fixed]  | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 0.94%   |
| Alcor Micro USB 2.0 PC Camera                                  | 1         | 0.94%   |

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
| 0     | 82        | 73.87%  |
| 1     | 27        | 24.32%  |
| 2     | 2         | 1.8%    |

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


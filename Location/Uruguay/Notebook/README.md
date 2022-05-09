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

Total: 153

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Acer          | Aspire 5715Z                | [aa3fceee37](https://linux-hardware.org/?probe=aa3fceee37) | May 17, 2021 |
| Standard      | SF20BA2                     | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| Acer          | Acadia V1.45                | [8495a627b6](https://linux-hardware.org/?probe=8495a627b6) | May 15, 2021 |
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
| MSI           | GL65 Leopard 10SCXR         | [4b122af9f4](https://linux-hardware.org/?probe=4b122af9f4) | Mar 09, 2021 |
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
| HP            | 620                         | [84286295bf](https://linux-hardware.org/?probe=84286295bf) | Apr 13, 2020 |
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
| ECS           | SF20PA2                     | [828b068f68](https://linux-hardware.org/?probe=828b068f68) | Jul 20, 2019 |
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
| Ubuntu 20.04                 | 21        | 18.58%  |
| Ubuntu 18.04                 | 20        | 17.7%   |
| OpenMandriva 4.2             | 5         | 4.42%   |
| KDE neon 20.04               | 5         | 4.42%   |
| Manjaro                      | 4         | 3.54%   |
| Ubuntu 21.10                 | 3         | 2.65%   |
| Ubuntu 19.04                 | 3         | 2.65%   |
| Linux Mint 19.3              | 3         | 2.65%   |
| Xubuntu 18.04                | 2         | 1.77%   |
| Ubuntu 21.04                 | 2         | 1.77%   |
| Ubuntu 18.10                 | 2         | 1.77%   |
| Linux Mint 20.1              | 2         | 1.77%   |
| Linux Mint 19.1              | 2         | 1.77%   |
| Kubuntu 18.04                | 2         | 1.77%   |
| Arch Rolling                 | 2         | 1.77%   |
| Zorin 16                     | 1         | 0.88%   |
| Zorin 15                     | 1         | 0.88%   |
| Xubuntu 20.04                | 1         | 0.88%   |
| Ubuntu MATE 20.04            | 1         | 0.88%   |
| Ubuntu 20.10                 | 1         | 0.88%   |
| Ubuntu 19.10                 | 1         | 0.88%   |
| Ubuntu 17.10                 | 1         | 0.88%   |
| ROSA R11.1                   | 1         | 0.88%   |
| openSUSE Leap-15.1           | 1         | 0.88%   |
| OpenMandriva 4.3             | 1         | 0.88%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.88%   |
| Manjaro 21.2.0               | 1         | 0.88%   |
| Lubuntu 20.04                | 1         | 0.88%   |
| Lubuntu 19.10                | 1         | 0.88%   |
| Linux Mint 20.2              | 1         | 0.88%   |
| Linux Mint 20                | 1         | 0.88%   |
| Linux Mint 19.2              | 1         | 0.88%   |
| Linux Mint 19                | 1         | 0.88%   |
| Kubuntu 20.10                | 1         | 0.88%   |
| Kubuntu 20.04                | 1         | 0.88%   |
| Gentoo 2.8                   | 1         | 0.88%   |
| Fedora 35                    | 1         | 0.88%   |
| Fedora 34                    | 1         | 0.88%   |
| Fedora 30                    | 1         | 0.88%   |
| Endless 3.8.7                | 1         | 0.88%   |
| Endless 3.7.8                | 1         | 0.88%   |
| Endless 3.6.2                | 1         | 0.88%   |
| Endless 3.4.2-nexthw1        | 1         | 0.88%   |
| EndeavourOS                  | 1         | 0.88%   |
| Elementary 6                 | 1         | 0.88%   |
| Elementary 5.1.7             | 1         | 0.88%   |
| Debian 11                    | 1         | 0.88%   |
| BlackPanther 18.1            | 1         | 0.88%   |
| ArcoLinux Rolling            | 1         | 0.88%   |
| Arch                         | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 52        | 46.85%  |
| Linux Mint   | 11        | 9.91%   |
| OpenMandriva | 6         | 5.41%   |
| Manjaro      | 5         | 4.5%    |
| KDE neon     | 5         | 4.5%    |
| Kubuntu      | 4         | 3.6%    |
| Endless      | 4         | 3.6%    |
| Xubuntu      | 3         | 2.7%    |
| Fedora       | 3         | 2.7%    |
| Arch         | 3         | 2.7%    |
| Zorin        | 2         | 1.8%    |
| Lubuntu      | 2         | 1.8%    |
| Elementary   | 2         | 1.8%    |
| Ubuntu MATE  | 1         | 0.9%    |
| ROSA         | 1         | 0.9%    |
| openSUSE     | 1         | 0.9%    |
| NixOS        | 1         | 0.9%    |
| Gentoo       | 1         | 0.9%    |
| EndeavourOS  | 1         | 0.9%    |
| Debian       | 1         | 0.9%    |
| BlackPanther | 1         | 0.9%    |
| ArcoLinux    | 1         | 0.9%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 4.16.18-pa2-2bp1            | 6         | 5.08%   |
| 5.10.14-desktop-1omv4002    | 5         | 4.24%   |
| 4.16.18-pa2-1bp5            | 5         | 4.24%   |
| 5.8.0-53-generic            | 4         | 3.39%   |
| 5.13.0-39-generic           | 4         | 3.39%   |
| 5.4.0-73-generic            | 3         | 2.54%   |
| 5.4.0-58-generic            | 3         | 2.54%   |
| 5.4.0-52-generic            | 3         | 2.54%   |
| 5.11.0-38-generic           | 3         | 2.54%   |
| 5.8.0-50-generic            | 2         | 1.69%   |
| 5.8.0-43-generic            | 2         | 1.69%   |
| 5.5.19-bp0                  | 2         | 1.69%   |
| 5.4.0-72-generic            | 2         | 1.69%   |
| 5.4.0-42-generic            | 2         | 1.69%   |
| 5.3.0-28-generic            | 2         | 1.69%   |
| 5.13.0-37-generic           | 2         | 1.69%   |
| 5.13.0-30-generic           | 2         | 1.69%   |
| 5.11.12-desktop-1omv4002    | 2         | 1.69%   |
| 5.0.0-13-generic            | 2         | 1.69%   |
| 4.15.0-51-generic           | 2         | 1.69%   |
| 4.15.0-20-generic           | 2         | 1.69%   |
| 4.15.0-101-generic          | 2         | 1.69%   |
| 5.8.11-1-MANJARO            | 1         | 0.85%   |
| 5.8.1-3-MANJARO             | 1         | 0.85%   |
| 5.8.0-49-generic            | 1         | 0.85%   |
| 5.8.0-48-generic            | 1         | 0.85%   |
| 5.8.0-44-generic            | 1         | 0.85%   |
| 5.8.0-34-generic            | 1         | 0.85%   |
| 5.6.8-1-MANJARO             | 1         | 0.85%   |
| 5.4.60-1-lts                | 1         | 0.85%   |
| 5.4.32-generic-2rosa-x86_64 | 1         | 0.85%   |
| 5.4.0-80-generic            | 1         | 0.85%   |
| 5.4.0-70-generic            | 1         | 0.85%   |
| 5.4.0-65-generic            | 1         | 0.85%   |
| 5.4.0-62-generic            | 1         | 0.85%   |
| 5.4.0-59-generic            | 1         | 0.85%   |
| 5.4.0-39-generic            | 1         | 0.85%   |
| 5.4.0-37-generic            | 1         | 0.85%   |
| 5.4.0-28-generic            | 1         | 0.85%   |
| 5.3.0-51-generic            | 1         | 0.85%   |
| 5.3.0-46-generic            | 1         | 0.85%   |
| 5.3.0-10-generic            | 1         | 0.85%   |
| 5.2.13-200.fc30.x86_64      | 1         | 0.85%   |
| 5.17.4-arch1-1              | 1         | 0.85%   |
| 5.16.16-arch1-1             | 1         | 0.85%   |
| 5.16.13-desktop-1omv4003    | 1         | 0.85%   |
| 5.16.12-200.fc35.x86_64     | 1         | 0.85%   |
| 5.16.0-gentoo-gentoo-dist   | 1         | 0.85%   |
| 5.15.3                      | 1         | 0.85%   |
| 5.14.18-1-MANJARO           | 1         | 0.85%   |
| 5.13.0-40-generic           | 1         | 0.85%   |
| 5.13.0-22-generic           | 1         | 0.85%   |
| 5.11.20-300.fc34.x86_64     | 1         | 0.85%   |
| 5.11.11-051111-generic      | 1         | 0.85%   |
| 5.11.0-34-generic           | 1         | 0.85%   |
| 5.11.0-25-generic           | 1         | 0.85%   |
| 5.11.0-14-generic           | 1         | 0.85%   |
| 5.10.4-arch2-1              | 1         | 0.85%   |
| 5.10.31-1-lts               | 1         | 0.85%   |
| 5.10.30-1-MANJARO           | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 18.1%   |
| 5.8.0   | 12        | 10.34%  |
| 4.16.18 | 11        | 9.48%   |
| 5.13.0  | 9         | 7.76%   |
| 4.15.0  | 9         | 7.76%   |
| 5.11.0  | 6         | 5.17%   |
| 5.0.0   | 6         | 5.17%   |
| 5.3.0   | 5         | 4.31%   |
| 5.10.14 | 5         | 4.31%   |
| 4.18.0  | 4         | 3.45%   |
| 5.5.19  | 2         | 1.72%   |
| 5.11.12 | 2         | 1.72%   |
| 5.8.11  | 1         | 0.86%   |
| 5.8.1   | 1         | 0.86%   |
| 5.6.8   | 1         | 0.86%   |
| 5.4.60  | 1         | 0.86%   |
| 5.4.32  | 1         | 0.86%   |
| 5.2.13  | 1         | 0.86%   |
| 5.17.4  | 1         | 0.86%   |
| 5.16.16 | 1         | 0.86%   |
| 5.16.13 | 1         | 0.86%   |
| 5.16.12 | 1         | 0.86%   |
| 5.16.0  | 1         | 0.86%   |
| 5.15.3  | 1         | 0.86%   |
| 5.14.18 | 1         | 0.86%   |
| 5.11.20 | 1         | 0.86%   |
| 5.11.11 | 1         | 0.86%   |
| 5.10.4  | 1         | 0.86%   |
| 5.10.31 | 1         | 0.86%   |
| 5.10.30 | 1         | 0.86%   |
| 5.10.0  | 1         | 0.86%   |
| 4.18.16 | 1         | 0.86%   |
| 4.17.19 | 1         | 0.86%   |
| 4.16.0  | 1         | 0.86%   |
| 4.13.0  | 1         | 0.86%   |
| 4.12.14 | 1         | 0.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 19.83%  |
| 5.8     | 14        | 12.07%  |
| 4.16    | 12        | 10.34%  |
| 5.11    | 10        | 8.62%   |
| 5.13    | 9         | 7.76%   |
| 5.10    | 9         | 7.76%   |
| 4.15    | 9         | 7.76%   |
| 5.0     | 6         | 5.17%   |
| 5.3     | 5         | 4.31%   |
| 4.18    | 5         | 4.31%   |
| 5.16    | 4         | 3.45%   |
| 5.5     | 2         | 1.72%   |
| 5.6     | 1         | 0.86%   |
| 5.2     | 1         | 0.86%   |
| 5.17    | 1         | 0.86%   |
| 5.15    | 1         | 0.86%   |
| 5.14    | 1         | 0.86%   |
| 4.17    | 1         | 0.86%   |
| 4.13    | 1         | 0.86%   |
| 4.12    | 1         | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 98.17%  |
| i686   | 2         | 1.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 35        | 31.25%  |
| Unknown         | 21        | 18.75%  |
| KDE5            | 15        | 13.39%  |
| GNOME Flashback | 11        | 9.82%   |
| XFCE            | 8         | 7.14%   |
| X-Cinnamon      | 6         | 5.36%   |
| KDE             | 5         | 4.46%   |
| MATE            | 3         | 2.68%   |
| LXQt            | 3         | 2.68%   |
| Pantheon        | 2         | 1.79%   |
| Cinnamon        | 2         | 1.79%   |
| sway            | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 87        | 79.82%  |
| Wayland | 12        | 11.01%  |
| Unknown | 9         | 8.26%   |
| Tty     | 1         | 0.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 59        | 54.13%  |
| GDM     | 22        | 20.18%  |
| SDDM    | 16        | 14.68%  |
| LightDM | 4         | 3.67%   |
| GDM3    | 4         | 3.67%   |
| TDM     | 3         | 2.75%   |
| GREETD  | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_UY   | 57        | 50.89%  |
| en_US   | 20        | 17.86%  |
| Unknown | 18        | 16.07%  |
| es_ES   | 10        | 8.93%   |
| es_MX   | 3         | 2.68%   |
| es_AR   | 2         | 1.79%   |
| en_CA   | 1         | 0.89%   |
| C       | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 59        | 54.13%  |
| BIOS | 50        | 45.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 88.29%  |
| Overlay | 6         | 5.41%   |
| Unknown | 4         | 3.6%    |
| Btrfs   | 2         | 1.8%    |
| Ext3    | 1         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 65.14%  |
| GPT     | 28        | 25.69%  |
| MBR     | 10        | 9.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 83.49%  |
| Yes       | 18        | 16.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 72.48%  |
| Yes       | 30        | 27.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 20.18%  |
| Lenovo              | 19        | 17.43%  |
| ECS                 | 13        | 11.93%  |
| Dell                | 11        | 10.09%  |
| ASUSTek Computer    | 10        | 9.17%   |
| Acer                | 10        | 9.17%   |
| Toshiba             | 6         | 5.5%    |
| Samsung Electronics | 4         | 3.67%   |
| MSI                 | 4         | 3.67%   |
| Standard            | 3         | 2.75%   |
| Sony                | 1         | 0.92%   |
| Positivo            | 1         | 0.92%   |
| Panasonic           | 1         | 0.92%   |
| OEM                 | 1         | 0.92%   |
| Haitech             | 1         | 0.92%   |
| GPU Company         | 1         | 0.92%   |
| Apple               | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 13        | 11.93%  |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.75%   |
| Toshiba Satellite L55t-B              | 2         | 1.83%   |
| Standard SF20BA2                      | 2         | 1.83%   |
| HP Pavilion 15                        | 2         | 1.83%   |
| HP Laptop 15-bs0xx                    | 2         | 1.83%   |
| Toshiba Satellite C75D-C              | 1         | 0.92%   |
| Toshiba Satellite C645D               | 1         | 0.92%   |
| Toshiba Satellite C55-B               | 1         | 0.92%   |
| Toshiba Satellite C45-A               | 1         | 0.92%   |
| Standard EF20EA                       | 1         | 0.92%   |
| Sony SVF14211CLB                      | 1         | 0.92%   |
| Samsung NC208/NC108                   | 1         | 0.92%   |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.92%   |
| Samsung 700T                          | 1         | 0.92%   |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.92%   |
| Positivo Serie AT300                  | 1         | 0.92%   |
| Panasonic CF-31JEGAX1M                | 1         | 0.92%   |
| OEM V40SI2                            | 1         | 0.92%   |
| MSI GS63VR 6RF                        | 1         | 0.92%   |
| MSI GL65 Leopard 10SCXR               | 1         | 0.92%   |
| MSI GL63 8RD                          | 1         | 0.92%   |
| MSI GE62 6QD                          | 1         | 0.92%   |
| Lenovo V15-ADA 82C7                   | 1         | 0.92%   |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.92%   |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.92%   |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.92%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.92%   |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.92%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.92%   |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.92%   |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.92%   |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.92%   |
| Lenovo IdeaPad S340-15IWL 81N8        | 1         | 0.92%   |
| Lenovo IdeaPad S145-15AST 81N3        | 1         | 0.92%   |
| Lenovo IdeaPad 330S-15ARR 81FB        | 1         | 0.92%   |
| Lenovo IdeaPad 320-17IKB 81BJ         | 1         | 0.92%   |
| Lenovo IdeaPad 300-15ISK 80RS         | 1         | 0.92%   |
| Lenovo G50-70 20351                   | 1         | 0.92%   |
| Lenovo G405 20239                     | 1         | 0.92%   |
| Lenovo B51-30 80LK                    | 1         | 0.92%   |
| Lenovo B50-45 20388                   | 1         | 0.92%   |
| HP ZBook 14u G4                       | 1         | 0.92%   |
| HP Stream Laptop 14-ax0XX             | 1         | 0.92%   |
| HP Presario CQ43                      | 1         | 0.92%   |
| HP Pavilion dv6                       | 1         | 0.92%   |
| HP Pavilion dv5                       | 1         | 0.92%   |
| HP Pavilion dm4                       | 1         | 0.92%   |
| HP Pavilion 17                        | 1         | 0.92%   |
| HP Notebook                           | 1         | 0.92%   |
| HP Laptop 15-db0xxx                   | 1         | 0.92%   |
| HP Laptop 14-dq1xxx                   | 1         | 0.92%   |
| HP Laptop 14-dk0xxx                   | 1         | 0.92%   |
| HP Laptop 14-df0xxx                   | 1         | 0.92%   |
| HP ENVY TS 15                         | 1         | 0.92%   |
| HP EliteBook 840 G1                   | 1         | 0.92%   |
| HP Casablanca H710                    | 1         | 0.92%   |
| HP 620                                | 1         | 0.92%   |
| HP 240 G7                             | 1         | 0.92%   |
| HP 2000                               | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 13        | 11.93%  |
| Lenovo ThinkPad        | 8         | 7.34%   |
| Dell Inspiron          | 7         | 6.42%   |
| Acer Aspire            | 7         | 6.42%   |
| Toshiba Satellite      | 6         | 5.5%    |
| HP Pavilion            | 6         | 5.5%    |
| HP Laptop              | 6         | 5.5%    |
| Lenovo IdeaPad         | 5         | 4.59%   |
| ASUS ROG               | 3         | 2.75%   |
| Standard SF20BA2       | 2         | 1.83%   |
| Dell Latitude          | 2         | 1.83%   |
| ASUS VivoBook          | 2         | 1.83%   |
| Acer TravelMate        | 2         | 1.83%   |
| Standard EF20EA        | 1         | 0.92%   |
| Sony SVF14211CLB       | 1         | 0.92%   |
| Samsung NC208          | 1         | 0.92%   |
| Samsung N102SP         | 1         | 0.92%   |
| Samsung 700T           | 1         | 0.92%   |
| Samsung 300E4C         | 1         | 0.92%   |
| Positivo Serie         | 1         | 0.92%   |
| Panasonic CF-31JEGAX1M | 1         | 0.92%   |
| OEM V40SI2             | 1         | 0.92%   |
| MSI GS63VR             | 1         | 0.92%   |
| MSI GL65               | 1         | 0.92%   |
| MSI GL63               | 1         | 0.92%   |
| MSI GE62               | 1         | 0.92%   |
| Lenovo V15-ADA         | 1         | 0.92%   |
| Lenovo ThinkBook       | 1         | 0.92%   |
| Lenovo G50-70          | 1         | 0.92%   |
| Lenovo G405            | 1         | 0.92%   |
| Lenovo B51-30          | 1         | 0.92%   |
| Lenovo B50-45          | 1         | 0.92%   |
| HP ZBook               | 1         | 0.92%   |
| HP Stream              | 1         | 0.92%   |
| HP Presario            | 1         | 0.92%   |
| HP Notebook            | 1         | 0.92%   |
| HP ENVY                | 1         | 0.92%   |
| HP EliteBook           | 1         | 0.92%   |
| HP Casablanca          | 1         | 0.92%   |
| HP 620                 | 1         | 0.92%   |
| HP 240                 | 1         | 0.92%   |
| HP 2000                | 1         | 0.92%   |
| Haitech H7141A         | 1         | 0.92%   |
| GPU Company GWTN156-4  | 1         | 0.92%   |
| Dell XPS               | 1         | 0.92%   |
| Dell Precision         | 1         | 0.92%   |
| ASUS ZenBook           | 1         | 0.92%   |
| ASUS X555LAB           | 1         | 0.92%   |
| ASUS TP300LAB          | 1         | 0.92%   |
| ASUS N46VJ             | 1         | 0.92%   |
| ASUS ASUS              | 1         | 0.92%   |
| Apple MacBookAir7      | 1         | 0.92%   |
| Acer Swift             | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 20        | 18.35%  |
| 2019 | 12        | 11.01%  |
| 2020 | 11        | 10.09%  |
| 2018 | 11        | 10.09%  |
| 2013 | 11        | 10.09%  |
| 2014 | 9         | 8.26%   |
| 2011 | 9         | 8.26%   |
| 2016 | 8         | 7.34%   |
| 2012 | 5         | 4.59%   |
| 2015 | 4         | 3.67%   |
| 2008 | 4         | 3.67%   |
| 2010 | 3         | 2.75%   |
| 2009 | 1         | 0.92%   |
| 2007 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 109       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 96        | 88.07%  |
| Enabled  | 13        | 11.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 30        | 27.03%  |
| 4.01-8.0    | 29        | 26.13%  |
| 1.01-2.0    | 18        | 16.22%  |
| 8.01-16.0   | 17        | 15.32%  |
| 16.01-24.0  | 8         | 7.21%   |
| 32.01-64.0  | 4         | 3.6%    |
| 24.01-32.0  | 3         | 2.7%    |
| 2.01-3.0    | 1         | 0.9%    |
| 64.01-256.0 | 1         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 50        | 43.86%  |
| 2.01-3.0  | 25        | 21.93%  |
| 4.01-8.0  | 13        | 11.4%   |
| 0.51-1.0  | 11        | 9.65%   |
| 3.01-4.0  | 9         | 7.89%   |
| 8.01-16.0 | 5         | 4.39%   |
| 0.01-0.5  | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 89        | 81.65%  |
| 2      | 19        | 17.43%  |
| 0      | 1         | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 68.81%  |
| Yes       | 34        | 31.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 66.97%  |
| No        | 36        | 33.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 98.17%  |
| No        | 2         | 1.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 80.73%  |
| No        | 21        | 19.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 109       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 72        | 61.54%  |
| Maldonado              | 7         | 5.98%   |
| Canelones              | 4         | 3.42%   |
| Solymar                | 3         | 2.56%   |
| Rocha                  | 2         | 1.71%   |
| Piriapolis             | 2         | 1.71%   |
| Libertad               | 2         | 1.71%   |
| Cordon                 | 2         | 1.71%   |
| Ciudad del Plata       | 2         | 1.71%   |
| Bella Vista            | 2         | 1.71%   |
| Shangrila              | 1         | 0.85%   |
| Punta Carretas         | 1         | 0.85%   |
| Pocitos                | 1         | 0.85%   |
| Paysandú              | 1         | 0.85%   |
| Pando                  | 1         | 0.85%   |
| Manga                  | 1         | 0.85%   |
| Las Piedras            | 1         | 0.85%   |
| La Paloma              | 1         | 0.85%   |
| La Blanqueada          | 1         | 0.85%   |
| Joaquin Suarez         | 1         | 0.85%   |
| Fray Bentos            | 1         | 0.85%   |
| Florida                | 1         | 0.85%   |
| El Tesoro              | 1         | 0.85%   |
| Ciudad Vieja           | 1         | 0.85%   |
| Centro                 | 1         | 0.85%   |
| Barrio Sur             | 1         | 0.85%   |
| Arroyo de la Virgen    | 1         | 0.85%   |
| Arenas de Jose Ignacio | 1         | 0.85%   |
| Aguada                 | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 23     | 16.53%  |
| Unknown             | 16        | 20     | 13.22%  |
| Toshiba             | 15        | 17     | 12.4%   |
| Kingston            | 14        | 18     | 11.57%  |
| Seagate             | 13        | 14     | 10.74%  |
| SanDisk             | 9         | 10     | 7.44%   |
| Samsung Electronics | 8         | 8      | 6.61%   |
| Hitachi             | 6         | 8      | 4.96%   |
| Intel               | 4         | 4      | 3.31%   |
| SK Hynix            | 3         | 3      | 2.48%   |
| HGST                | 3         | 3      | 2.48%   |
| Hewlett-Packard     | 2         | 2      | 1.65%   |
| Crucial             | 2         | 3      | 1.65%   |
| Netac               | 1         | 1      | 0.83%   |
| LITEON              | 1         | 2      | 0.83%   |
| China               | 1         | 1      | 0.83%   |
| BIWIN               | 1         | 1      | 0.83%   |
| BHT                 | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 9         | 7.32%   |
| Kingston SA400S37240G 240GB SSD       | 6         | 4.88%   |
| Unknown DA4032  32GB                  | 5         | 4.07%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 3.25%   |
| Toshiba MQ01ABD075 752GB              | 3         | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 2.44%   |
| WDC WD5000BEKT-60KA9T0 500GB          | 2         | 1.63%   |
| Unknown SD/MMC/MS PRO 128GB           | 2         | 1.63%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.63%   |
| Toshiba HDWK105 500GB                 | 2         | 1.63%   |
| Sandisk NVMe SSD Drive 256GB          | 2         | 1.63%   |
| Sandisk NVMe SSD Drive 1024GB         | 2         | 1.63%   |
| SanDisk DF4032  32GB                  | 2         | 1.63%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.63%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 1         | 0.81%   |
| WDC WDS250G2X0C-00L350 250GB          | 1         | 0.81%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.81%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 0.81%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.81%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.81%   |
| WDC WD5000LPVT-24G33T1 500GB          | 1         | 0.81%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.81%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.81%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 0.81%   |
| WDC WD3200LPCX-24C6HT0 320GB          | 1         | 0.81%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.81%   |
| WDC WD10SPZX-08Z10 1TB                | 1         | 0.81%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.81%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 0.81%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 0.81%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 0.81%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.81%   |
| Unknown MMC Card  64GB                | 1         | 0.81%   |
| Unknown MMC Card  4GB                 | 1         | 0.81%   |
| Toshiba THNSNJ256G8NY 256GB SSD       | 1         | 0.81%   |
| Toshiba NVMe SSD Drive 256GB          | 1         | 0.81%   |
| Toshiba MQ04ABF100 1TB                | 1         | 0.81%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.81%   |
| Toshiba MK5059GSXP 500GB              | 1         | 0.81%   |
| Toshiba MK3259GSXP 320GB              | 1         | 0.81%   |
| Toshiba KXG6AZNV512G 512GB            | 1         | 0.81%   |
| Toshiba KXG50ZNV256G 256GB            | 1         | 0.81%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.81%   |
| SK Hynix HFS256G32TNH-73A0A 256GB SSD | 1         | 0.81%   |
| SK Hynix HFM256GDHTNG-8310A 256GB     | 1         | 0.81%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.81%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.81%   |
| Seagate Expansion+ 2TB                | 1         | 0.81%   |
| SanDisk SSD U100 8GB                  | 1         | 0.81%   |
| SanDisk SDSSDP128G 128GB              | 1         | 0.81%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 0.81%   |
| Samsung SSD SM841 2.5 7mm 128GB       | 1         | 0.81%   |
| Samsung SSD 860 EVO 500GB             | 1         | 0.81%   |
| Samsung SSD 860 EVO 250GB             | 1         | 0.81%   |
| Samsung SSD 850 EVO 500GB             | 1         | 0.81%   |
| Samsung PM951 NVMe 256GB              | 1         | 0.81%   |
| Samsung NVMe SSD Drive 1024GB         | 1         | 0.81%   |
| Samsung MZVLB512HAJQ-00000 512GB      | 1         | 0.81%   |
| Samsung MZMPA128HMFU-00000 128GB SSD  | 1         | 0.81%   |

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
| HDD  | 48        | 58     | 40.68%  |
| SSD  | 32        | 37     | 27.12%  |
| NVMe | 22        | 24     | 18.64%  |
| MMC  | 16        | 21     | 13.56%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 92     | 64.04%  |
| NVMe | 22        | 24     | 19.3%   |
| MMC  | 16        | 21     | 14.04%  |
| SAS  | 3         | 3      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 63     | 67.09%  |
| 0.51-1.0   | 24        | 30     | 30.38%  |
| 1.01-2.0   | 2         | 2      | 2.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 25.89%  |
| 251-500        | 26        | 23.21%  |
| 501-1000       | 17        | 15.18%  |
| 21-50          | 16        | 14.29%  |
| 1-20           | 12        | 10.71%  |
| 51-100         | 6         | 5.36%   |
| Unknown        | 3         | 2.68%   |
| 1001-2000      | 2         | 1.79%   |
| More than 3000 | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 58        | 50%     |
| 21-50          | 21        | 18.1%   |
| 251-500        | 11        | 9.48%   |
| 51-100         | 10        | 8.62%   |
| 101-250        | 8         | 6.9%    |
| 501-1000       | 4         | 3.45%   |
| Unknown        | 3         | 2.59%   |
| More than 3000 | 1         | 0.86%   |

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
| Detected | 69        | 90     | 62.73%  |
| Works    | 32        | 40     | 29.09%  |
| Malfunc  | 9         | 10     | 8.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 77        | 64.71%  |
| AMD                              | 21        | 17.65%  |
| Sandisk                          | 7         | 5.88%   |
| Toshiba America Info Systems     | 3         | 2.52%   |
| Samsung Electronics              | 3         | 2.52%   |
| Kingston Technology Company      | 3         | 2.52%   |
| SK Hynix                         | 1         | 0.84%   |
| Silicon Integrated Systems [SiS] | 1         | 0.84%   |
| Micron/Crucial Technology        | 1         | 0.84%   |
| Lite-On Technology               | 1         | 0.84%   |
| Apple                            | 1         | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 19        | 15.32%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 14        | 11.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 4.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 4.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 4.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 4.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 3.23%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 3         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.42%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 1.61%   |
| Intel SSD 660P Series                                                                  | 2         | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.81%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.81%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.81%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.81%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.81%   |
| Lite-On NVMe Controller                                                                | 1         | 0.81%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.81%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 0.81%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.81%   |
| Apple S1X NVMe Controller                                                              | 1         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 90        | 73.17%  |
| NVMe | 22        | 17.89%  |
| RAID | 6         | 4.88%   |
| IDE  | 5         | 4.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 78.9%   |
| AMD    | 23        | 21.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 14        | 12.84%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.75%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.75%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.83%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.83%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.83%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.83%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.83%   |
| AMD E-300 APU with Radeon HD Graphics        | 2         | 1.83%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.83%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.92%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.92%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.92%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.92%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.92%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.92%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.92%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 1         | 0.92%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.92%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.92%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.92%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i5-5250U CPU @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i5-3340M CPU @ 2.70GHz            | 1         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i5-2467M CPU @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 0.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz           | 1         | 0.92%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 1         | 0.92%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.92%   |
| Intel Core i3-6100U CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i3-5020U CPU @ 2.20GHz            | 1         | 0.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz            | 1         | 0.92%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.92%   |
| Intel Core i3 CPU M 390 @ 2.67GHz            | 1         | 0.92%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 0.92%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz         | 1         | 0.92%   |
| Intel Celeron N4100 CPU @ 1.10GHz            | 1         | 0.92%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 1         | 0.92%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 1         | 0.92%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 1         | 0.92%   |
| Intel Atom CPU N455 @ 1.66GHz                | 1         | 0.92%   |
| Intel Atom CPU N2100 @ 1.60GHz               | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 22        | 20.18%  |
| Intel Celeron      | 20        | 18.35%  |
| Intel Core i7      | 19        | 17.43%  |
| Intel Core i3      | 9         | 8.26%   |
| Intel Pentium      | 6         | 5.5%    |
| Intel Atom         | 4         | 3.67%   |
| Other              | 3         | 2.75%   |
| AMD Ryzen 9        | 3         | 2.75%   |
| AMD A6             | 3         | 2.75%   |
| Intel Genuine      | 2         | 1.83%   |
| Intel Core 2 Duo   | 2         | 1.83%   |
| AMD Ryzen 7        | 2         | 1.83%   |
| AMD Ryzen 5        | 2         | 1.83%   |
| AMD Ryzen 3        | 2         | 1.83%   |
| AMD E1             | 2         | 1.83%   |
| AMD E              | 2         | 1.83%   |
| Intel Pentium Dual | 1         | 0.92%   |
| AMD Phenom II      | 1         | 0.92%   |
| AMD FX             | 1         | 0.92%   |
| AMD E2             | 1         | 0.92%   |
| AMD A8             | 1         | 0.92%   |
| AMD A4             | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 65        | 59.63%  |
| 4      | 33        | 30.28%  |
| 8      | 4         | 3.67%   |
| 6      | 4         | 3.67%   |
| 1      | 3         | 2.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 57.8%   |
| 1      | 46        | 42.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 97.25%  |
| Unknown        | 3         | 2.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 20.18%  |
| 0x406c4    | 6         | 5.5%    |
| 0x40651    | 6         | 5.5%    |
| 0x206a7    | 6         | 5.5%    |
| 0x306d4    | 5         | 4.59%   |
| 0x806ec    | 4         | 3.67%   |
| 0x806ea    | 4         | 3.67%   |
| 0x20655    | 4         | 3.67%   |
| 0x806e9    | 3         | 2.75%   |
| 0x6fd      | 3         | 2.75%   |
| 0x506c9    | 3         | 2.75%   |
| 0x406e3    | 3         | 2.75%   |
| 0x906ea    | 2         | 1.83%   |
| 0x706e5    | 2         | 1.83%   |
| 0x306c3    | 2         | 1.83%   |
| 0x306a9    | 2         | 1.83%   |
| 0x08600104 | 2         | 1.83%   |
| 0x08108109 | 2         | 1.83%   |
| 0x0810100b | 2         | 1.83%   |
| 0x07030104 | 2         | 1.83%   |
| 0x0700010f | 2         | 1.83%   |
| 0x06006705 | 2         | 1.83%   |
| 0xa0652    | 1         | 0.92%   |
| 0x806eb    | 1         | 0.92%   |
| 0x806c1    | 1         | 0.92%   |
| 0x706a1    | 1         | 0.92%   |
| 0x506e3    | 1         | 0.92%   |
| 0x406c3    | 1         | 0.92%   |
| 0x30678    | 1         | 0.92%   |
| 0x30661    | 1         | 0.92%   |
| 0x106e5    | 1         | 0.92%   |
| 0x106ca    | 1         | 0.92%   |
| 0x1067a    | 1         | 0.92%   |
| 0x10676    | 1         | 0.92%   |
| 0x08600102 | 1         | 0.92%   |
| 0x07030106 | 1         | 0.92%   |
| 0x07030105 | 1         | 0.92%   |
| 0x06006118 | 1         | 0.92%   |
| 0x06001119 | 1         | 0.92%   |
| 0x05000119 | 1         | 0.92%   |
| 0x05000101 | 1         | 0.92%   |
| 0x010000b6 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 13.76%  |
| Goldmont      | 14        | 12.84%  |
| Silvermont    | 9         | 8.26%   |
| Haswell       | 8         | 7.34%   |
| Skylake       | 6         | 5.5%    |
| SandyBridge   | 6         | 5.5%    |
| Broadwell     | 6         | 5.5%    |
| Zen 2         | 4         | 3.67%   |
| Westmere      | 4         | 3.67%   |
| Puma          | 4         | 3.67%   |
| IvyBridge     | 4         | 3.67%   |
| Excavator     | 4         | 3.67%   |
| Zen+          | 3         | 2.75%   |
| Core          | 3         | 2.75%   |
| Zen           | 2         | 1.83%   |
| Penryn        | 2         | 1.83%   |
| Jaguar        | 2         | 1.83%   |
| IceLake       | 2         | 1.83%   |
| CometLake     | 2         | 1.83%   |
| Bonnell       | 2         | 1.83%   |
| Bobcat        | 2         | 1.83%   |
| TigerLake     | 1         | 0.92%   |
| Piledriver    | 1         | 0.92%   |
| Nehalem       | 1         | 0.92%   |
| K10           | 1         | 0.92%   |
| Goldmont plus | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 65.12%  |
| AMD                              | 31        | 24.03%  |
| Nvidia                           | 13        | 10.08%  |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 14        | 10.61%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 6.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.55%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.03%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.03%   |
| AMD Renoir                                                                               | 4         | 3.03%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.27%   |
| Intel HD Graphics 620                                                                    | 3         | 2.27%   |
| Intel HD Graphics 530                                                                    | 3         | 2.27%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 2.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.52%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.52%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.52%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.76%   |
| Nvidia TU117M                                                                            | 1         | 0.76%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.76%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.76%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.76%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.76%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.76%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.76%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.76%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.76%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.76%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.76%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.76%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.76%   |
| AMD Richland [Radeon HD 8450G]                                                           | 1         | 0.76%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 0.76%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 0.76%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 0.76%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 62.39%  |
| 1 x AMD        | 18        | 16.51%  |
| Intel + Nvidia | 8         | 7.34%   |
| Intel + AMD    | 8         | 7.34%   |
| AMD + Nvidia   | 4         | 3.67%   |
| 2 x AMD        | 1         | 0.92%   |
| 1 x SiS        | 1         | 0.92%   |
| 1 x Nvidia     | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 100       | 91.74%  |
| Proprietary | 8         | 7.34%   |
| Unknown     | 1         | 0.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 67.89%  |
| 0.51-1.0   | 10        | 9.17%   |
| 0.01-0.5   | 10        | 9.17%   |
| 1.01-2.0   | 8         | 7.34%   |
| 3.01-4.0   | 5         | 4.59%   |
| 5.01-6.0   | 2         | 1.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 18        | 15.25%  |
| Chimei Innolux          | 17        | 14.41%  |
| BOE                     | 16        | 13.56%  |
| AU Optronics            | 15        | 12.71%  |
| Samsung Electronics     | 13        | 11.02%  |
| KDC                     | 6         | 5.08%   |
| InfoVision              | 6         | 5.08%   |
| ViewSonic               | 3         | 2.54%   |
| Sharp                   | 3         | 2.54%   |
| PANDA                   | 3         | 2.54%   |
| Chi Mei Optoelectronics | 3         | 2.54%   |
| Acer                    | 3         | 2.54%   |
| KTC                     | 2         | 1.69%   |
| LG Philips              | 1         | 0.85%   |
| JDI                     | 1         | 0.85%   |
| InnoLux Display         | 1         | 0.85%   |
| HSI                     | 1         | 0.85%   |
| HKC                     | 1         | 0.85%   |
| Hewlett-Packard         | 1         | 0.85%   |
| Dell                    | 1         | 0.85%   |
| CPT                     | 1         | 0.85%   |
| Apple                   | 1         | 0.85%   |
| AOC                     | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 5         | 4.17%   |
| KDC LCD Monitor KDC05F1 1366x768 256x144mm 11.6-inch                  | 4         | 3.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 2.5%    |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.67%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.67%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 1.67%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.67%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 2         | 1.67%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.67%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch         | 1         | 0.83%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.83%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.83%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 310x170mm 13.9-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.83%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0396 1600x900 380x210mm 17.1-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch           | 1         | 0.83%   |
| KTC 23L13-H-AN KTC2304 1920x1080 510x287mm 23.0-inch                  | 1         | 0.83%   |
| KTC 23'TV KTC2300 1920x1080 510x290mm 23.1-inch                       | 1         | 0.83%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 0.83%   |
| InnoLux Display LCD Monitor INL0015 1366x768 309x174mm 14.0-inch      | 1         | 0.83%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch           | 1         | 0.83%   |
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                      | 1         | 0.83%   |
| HKC Checksum: 0x8a (valid) HKC1850 1360x768 304x228mm 15.0-inch       | 1         | 0.83%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x287mm 23.0-inch          | 1         | 0.83%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 1         | 0.83%   |
| CPT LCD Monitor CPT1BC7 1024x600 223x125mm 10.1-inch                  | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch       | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 60        | 56.07%  |
| 1920x1080 (FHD)   | 28        | 26.17%  |
| 1600x900 (HD+)    | 6         | 5.61%   |
| 1920x1200 (WUXGA) | 5         | 4.67%   |
| 1280x800 (WXGA)   | 3         | 2.8%    |
| 3840x2160 (4K)    | 2         | 1.87%   |
| 2560x1440 (QHD)   | 1         | 0.93%   |
| 1360x768          | 1         | 0.93%   |
| 1024x600          | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 58        | 49.15%  |
| 13     | 17        | 14.41%  |
| 14     | 15        | 12.71%  |
| 11     | 5         | 4.24%   |
| 24     | 4         | 3.39%   |
| 17     | 4         | 3.39%   |
| 27     | 3         | 2.54%   |
| 23     | 3         | 2.54%   |
| 21     | 2         | 1.69%   |
| 18     | 2         | 1.69%   |
| 12     | 2         | 1.69%   |
| 10     | 2         | 1.69%   |
| 34     | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 71.79%  |
| 201-300     | 13        | 11.11%  |
| 501-600     | 10        | 8.55%   |
| 351-400     | 5         | 4.27%   |
| 401-500     | 4         | 3.42%   |
| 701-800     | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 97        | 95.1%   |
| 16/10 | 4         | 3.92%   |
| 21/9  | 1         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 49.15%  |
| 81-90          | 28        | 23.73%  |
| 201-250        | 7         | 5.93%   |
| 51-60          | 5         | 4.24%   |
| 71-80          | 4         | 3.39%   |
| 121-130        | 4         | 3.39%   |
| 301-350        | 3         | 2.54%   |
| 61-70          | 2         | 1.69%   |
| 41-50          | 2         | 1.69%   |
| 151-200        | 2         | 1.69%   |
| 141-150        | 2         | 1.69%   |
| 351-500        | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 59        | 50.86%  |
| 121-160       | 31        | 26.72%  |
| 51-100        | 22        | 18.97%  |
| 161-240       | 3         | 2.59%   |
| More than 240 | 1         | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 91        | 81.98%  |
| 2     | 16        | 14.41%  |
| 3     | 2         | 1.8%    |
| 0     | 2         | 1.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 54        | 32.34%  |
| Intel                            | 51        | 30.54%  |
| Qualcomm Atheros                 | 27        | 16.17%  |
| Broadcom                         | 13        | 7.78%   |
| Ralink Technology                | 3         | 1.8%    |
| Ralink                           | 3         | 1.8%    |
| TP-Link                          | 2         | 1.2%    |
| MediaTek                         | 2         | 1.2%    |
| Broadcom Limited                 | 2         | 1.2%    |
| Xiaomi                           | 1         | 0.6%    |
| T & A Mobile Phones              | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Sierra Wireless                  | 1         | 0.6%    |
| Samsung Electronics              | 1         | 0.6%    |
| Qualcomm Atheros Communications  | 1         | 0.6%    |
| Lenovo                           | 1         | 0.6%    |
| Huawei Technologies              | 1         | 0.6%    |
| DisplayLink                      | 1         | 0.6%    |
| ASIX Electronics                 | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 29        | 14.95%  |
| Intel Wireless 3165                                                     | 19        | 9.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 9.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.58%   |
| Intel Wireless 7265                                                     | 4         | 2.06%   |
| Intel Wireless 7260                                                     | 4         | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.06%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.55%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.03%   |
| Intel Wireless 8260                                                     | 2         | 1.03%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.03%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.03%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.52%   |
| T & A Mobile Phones MT65xx Android Phone                                | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.52%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.52%   |
| Samsung Kiera                                                           | 1         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.52%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.52%   |
| MediaTek NOA N2                                                         | 1         | 0.52%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.52%   |
| Lenovo USB-C to LAN                                                     | 1         | 0.52%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.52%   |
| Intel Wireless 3160                                                     | 1         | 0.52%   |
| Intel WiFi Link 5100                                                    | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 43.75%  |
| Qualcomm Atheros                | 22        | 19.64%  |
| Realtek Semiconductor           | 21        | 18.75%  |
| Broadcom                        | 9         | 8.04%   |
| Ralink Technology               | 3         | 2.68%   |
| Ralink                          | 3         | 2.68%   |
| Broadcom Limited                | 2         | 1.79%   |
| TP-Link                         | 1         | 0.89%   |
| Qualcomm Atheros Communications | 1         | 0.89%   |
| MEDIATEK                        | 1         | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 19        | 16.81%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 5.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 5.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.42%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 4.42%   |
| Intel Wireless 7265                                                     | 4         | 3.54%   |
| Intel Wireless 7260                                                     | 4         | 3.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.65%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.77%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.77%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.77%   |
| Intel Wireless 8260                                                     | 2         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.88%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.88%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.88%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.88%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.88%   |
| Intel Wireless 3160                                                     | 1         | 0.88%   |
| Intel WiFi Link 5100                                                    | 1         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.88%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.88%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.88%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.88%   |
| Broadcom Limited BCM43225 802.11b/g/n                                   | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 48        | 60.76%  |
| Intel                            | 11        | 13.92%  |
| Qualcomm Atheros                 | 6         | 7.59%   |
| Broadcom                         | 5         | 6.33%   |
| Xiaomi                           | 1         | 1.27%   |
| TP-Link                          | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| Sierra Wireless                  | 1         | 1.27%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 36.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 22.78%  |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.53%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.27%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.27%   |
| MediaTek NOA N2                                                   | 1         | 1.27%   |
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
| WiFi     | 107       | 58.79%  |
| Ethernet | 73        | 40.11%  |
| Modem    | 1         | 0.55%   |
| Unknown  | 1         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 76.52%  |
| Ethernet | 31        | 23.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 68        | 62.39%  |
| 1     | 39        | 35.78%  |
| 0     | 2         | 1.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 87.16%  |
| Yes  | 14        | 12.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 47.19%  |
| Realtek Semiconductor           | 12        | 13.48%  |
| Qualcomm Atheros Communications | 9         | 10.11%  |
| Toshiba                         | 5         | 5.62%   |
| IMC Networks                    | 5         | 5.62%   |
| Foxconn / Hon Hai               | 3         | 3.37%   |
| Cambridge Silicon Radio         | 3         | 3.37%   |
| Ralink                          | 2         | 2.25%   |
| Lite-On Technology              | 2         | 2.25%   |
| Broadcom                        | 2         | 2.25%   |
| Ralink Technology               | 1         | 1.12%   |
| Foxconn International           | 1         | 1.12%   |
| Apple                           | 1         | 1.12%   |
| Alps Electric                   | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 29        | 32.58%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 6.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 5.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.49%   |
| Realtek Bluetooth Radio                             | 4         | 4.49%   |
| Realtek 802.11n WLAN Adapter                        | 3         | 3.37%   |
| Intel AX200 Bluetooth                               | 3         | 3.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.37%   |
| Toshiba Bluetooth Device                            | 2         | 2.25%   |
| Toshiba BCM43142A0                                  | 2         | 2.25%   |
| Ralink RT3290 Bluetooth                             | 2         | 2.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.25%   |
| Intel Bluetooth Device                              | 2         | 2.25%   |
| Intel AX201 Bluetooth                               | 2         | 2.25%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.25%   |
| Toshiba Bluetooth Radio                             | 1         | 1.12%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.12%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.12%   |
| Lite-On Bluetooth Device                            | 1         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.12%   |
| IMC Networks Bluetooth Device                       | 1         | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 1.12%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.12%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.12%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.12%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.12%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.12%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 83        | 68.03%  |
| AMD                                  | 23        | 18.85%  |
| Nvidia                               | 8         | 6.56%   |
| Logitech                             | 3         | 2.46%   |
| Generalplus Technology               | 2         | 1.64%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.82%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.82%   |
| C-Media Electronics                  | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 8.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 6.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.7%    |
| AMD FCH Azalia Controller                                                                         | 8         | 5.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 4.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.8%    |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 3.8%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.9%    |
| AMD High Definition Audio Controller                                                              | 3         | 1.9%    |
| Logitech USB Headset                                                                              | 2         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.27%   |
| Generalplus Technology Usb Audio Device                                                           | 2         | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.27%   |
| Thesycon Systemsoftware & Consulting D10s                                                         | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Logitech Headset H390                                                                             | 1         | 0.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.63%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 1         | 0.63%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.63%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 31.15%  |
| SK Hynix            | 13        | 21.31%  |
| Micron Technology   | 8         | 13.11%  |
| Ramaxel Technology  | 5         | 8.2%    |
| Kingston            | 5         | 8.2%    |
| Unknown             | 3         | 4.92%   |
| Goldkey             | 2         | 3.28%   |
| Elpida              | 2         | 3.28%   |
| A-DATA Technology   | 2         | 3.28%   |
| Nanya Technology    | 1         | 1.64%   |
| Crucial             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 3.13%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 3.13%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 3.13%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 3.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 3.13%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 3.13%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s       | 2         | 3.13%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.56%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 1.56%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.56%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.56%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.56%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.56%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s    | 1         | 1.56%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.56%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2400MT/s     | 1         | 1.56%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.56%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.56%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                      | 1         | 1.56%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 1.56%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.56%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 1         | 1.56%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.56%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.56%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.56%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s    | 1         | 1.56%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 1.56%   |
| Nanya RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.56%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.56%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s          | 1         | 1.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s      | 1         | 1.56%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s         | 1         | 1.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.56%   |
| Micron RAM 16ATF4G64HZ-2G6B2 32GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.56%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.56%   |
| Kingston RAM ACR16D3LS1KBGR/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Goldkey RAM GKH200SO25608-1600 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.56%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.56%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 1         | 1.56%   |
| Crucial RAM BLS8G4S240FSDK.8FD 8192MB SODIMM DDR4 2400MT/s    | 1         | 1.56%   |
| A-DATA RAM Module 32GB SODIMM DDR4 2667MT/s                   | 1         | 1.56%   |
| A-DATA RAM AM1L16BC4R1-B1HS 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 25        | 50%     |
| DDR4   | 19        | 38%     |
| SDRAM  | 2         | 4%      |
| LPDDR3 | 2         | 4%      |
| DDR2   | 2         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 93.75%  |
| Row Of Chips | 2         | 4.17%   |
| DIMM         | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 37.5%   |
| 8192  | 18        | 32.14%  |
| 2048  | 9         | 16.07%  |
| 16384 | 4         | 7.14%   |
| 32768 | 2         | 3.57%   |
| 1024  | 2         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 22        | 38.6%   |
| 2667  | 12        | 21.05%  |
| 3200  | 5         | 8.77%   |
| 2400  | 4         | 7.02%   |
| 1334  | 4         | 7.02%   |
| 4199  | 2         | 3.51%   |
| 2133  | 2         | 3.51%   |
| 533   | 2         | 3.51%   |
| 3266  | 1         | 1.75%   |
| 1867  | 1         | 1.75%   |
| 1333  | 1         | 1.75%   |
| 1067  | 1         | 1.75%   |

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
| Chicony Electronics                    | 31        | 29.81%  |
| Realtek Semiconductor                  | 13        | 12.5%   |
| Acer                                   | 8         | 7.69%   |
| Microdia                               | 7         | 6.73%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 6.73%   |
| Unknown                                | 5         | 4.81%   |
| Sunplus Innovation Technology          | 5         | 4.81%   |
| Suyin                                  | 4         | 3.85%   |
| Silicon Motion                         | 4         | 3.85%   |
| IMC Networks                           | 4         | 3.85%   |
| Quanta                                 | 3         | 2.88%   |
| Alcor Micro                            | 3         | 2.88%   |
| Syntek                                 | 2         | 1.92%   |
| Lite-On Technology                     | 2         | 1.92%   |
| Importek                               | 2         | 1.92%   |
| Samsung Electronics                    | 1         | 0.96%   |
| Logitech                               | 1         | 0.96%   |
| DigiTech                               | 1         | 0.96%   |
| 8SSC20F27114V1GZ07N14V2                | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 11        | 10.58%  |
| Unknown USB Camera                                             | 5         | 4.81%   |
| Chicony HP Truevision HD                                       | 5         | 4.81%   |
| Chicony Integrated Camera                                      | 4         | 3.85%   |
| Realtek Lenovo EasyCamera                                      | 3         | 2.88%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 2.88%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 2.88%   |
| Chicony TOSHIBA Web Camera - HD                                | 3         | 2.88%   |
| Acer Integrated Camera                                         | 3         | 2.88%   |
| Sunplus HP TrueVision HD Camera                                | 2         | 1.92%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.92%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.92%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.92%   |
| Chicony HD WebCam                                              | 2         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.92%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.92%   |
| Acer HD Webcam                                                 | 2         | 1.92%   |
| Syntek Integrated Camera                                       | 1         | 0.96%   |
| Syntek EasyCamera                                              | 1         | 0.96%   |
| Suyin HP Truevision HD                                         | 1         | 0.96%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.96%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.96%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.96%   |
| Sunplus HD Webcam                                              | 1         | 0.96%   |
| Sunplus ASUS USB2.0 Webcam                                     | 1         | 0.96%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.96%   |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.96%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.96%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 0.96%   |
| Realtek USB Camera                                             | 1         | 0.96%   |
| Realtek Integrated Camera                                      | 1         | 0.96%   |
| Realtek HD WebCam                                              | 1         | 0.96%   |
| Realtek Front Camera                                           | 1         | 0.96%   |
| Realtek Acer 640 x 480 laptop camera                           | 1         | 0.96%   |
| Quanta HD Webcam                                               | 1         | 0.96%   |
| Microdia USB 2.0 Camera                                        | 1         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_0.3M                         | 1         | 0.96%   |
| Microdia HP Webcam                                             | 1         | 0.96%   |
| Logitech Webcam C270                                           | 1         | 0.96%   |
| Lite-On Integrated Camera                                      | 1         | 0.96%   |
| Lite-On HP Webcam                                              | 1         | 0.96%   |
| Importek TOSHIBA Web Camera                                    | 1         | 0.96%   |
| Importek HP Webcam                                             | 1         | 0.96%   |
| IMC Networks TOSHIBA Web Camera - HD                           | 1         | 0.96%   |
| IMC Networks Integrated Camera                                 | 1         | 0.96%   |
| DigiTech WebCam SC-30AFL11449M                                 | 1         | 0.96%   |
| Chicony USB2.0 HD Camera                                       | 1         | 0.96%   |
| Chicony Lenovo EasyCamera                                      | 1         | 0.96%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 0.96%   |
| Chicony HP Webcam                                              | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam [2 MP Fixed]  | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 0.96%   |
| Alcor Micro USB 2.0 PC Camera                                  | 1         | 0.96%   |
| Acer NEC HD WebCam                                             | 1         | 0.96%   |

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


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 82        | 75.23%  |
| 1     | 25        | 22.94%  |
| 2     | 2         | 1.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 44.83%  |
| Net/wireless          | 6         | 20.69%  |
| Multimedia controller | 4         | 13.79%  |
| Graphics card         | 2         | 6.9%    |
| Bluetooth             | 2         | 6.9%    |
| Storage               | 1         | 3.45%   |
| Chipcard              | 1         | 3.45%   |


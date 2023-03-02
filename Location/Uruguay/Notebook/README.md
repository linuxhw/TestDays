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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 25        | 17.48%  |
| Ubuntu 18.04                 | 19        | 13.29%  |
| OpenMandriva 4.2             | 6         | 4.2%    |
| KDE neon 20.04               | 6         | 4.2%    |
| OpenMandriva 4.3             | 5         | 3.5%    |
| Manjaro                      | 5         | 3.5%    |
| Zorin 16                     | 3         | 2.1%    |
| Ubuntu 22.04                 | 3         | 2.1%    |
| Ubuntu 21.10                 | 3         | 2.1%    |
| Ubuntu 19.04                 | 3         | 2.1%    |
| Linux Mint 19.3              | 3         | 2.1%    |
| Fedora 36                    | 3         | 2.1%    |
| Arch Rolling                 | 3         | 2.1%    |
| Xubuntu 18.04                | 2         | 1.4%    |
| Ubuntu 21.04                 | 2         | 1.4%    |
| Ubuntu 18.10                 | 2         | 1.4%    |
| OpenMandriva 23.01           | 2         | 1.4%    |
| Linux Mint 20.1              | 2         | 1.4%    |
| Linux Mint 19.1              | 2         | 1.4%    |
| Kubuntu 18.04                | 2         | 1.4%    |
| Debian 11                    | 2         | 1.4%    |
| Zorin 15                     | 1         | 0.7%    |
| Xubuntu 20.04                | 1         | 0.7%    |
| Ubuntu MATE 20.04            | 1         | 0.7%    |
| Ubuntu 20.10                 | 1         | 0.7%    |
| Ubuntu 19.10                 | 1         | 0.7%    |
| Ubuntu 17.10                 | 1         | 0.7%    |
| SteamOS 3.4.4                | 1         | 0.7%    |
| ROSA R11.1                   | 1         | 0.7%    |
| Pop!_OS 22.04                | 1         | 0.7%    |
| openSUSE Leap-15.1           | 1         | 0.7%    |
| OpenMandriva 4.50            | 1         | 0.7%    |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.7%    |
| MX 21                        | 1         | 0.7%    |
| Manjaro 21.2.0               | 1         | 0.7%    |
| Lubuntu 20.04                | 1         | 0.7%    |
| Lubuntu 19.10                | 1         | 0.7%    |
| Linux Mint 21.1              | 1         | 0.7%    |
| Linux Mint 20.3              | 1         | 0.7%    |
| Linux Mint 20.2              | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 41.43%  |
| OpenMandriva | 14        | 10%     |
| Linux Mint   | 13        | 9.29%   |
| Manjaro      | 6         | 4.29%   |
| KDE neon     | 6         | 4.29%   |
| Fedora       | 6         | 4.29%   |
| Zorin        | 4         | 2.86%   |
| Kubuntu      | 4         | 2.86%   |
| Endless      | 4         | 2.86%   |
| Xubuntu      | 3         | 2.14%   |
| Arch         | 3         | 2.14%   |
| Lubuntu      | 2         | 1.43%   |
| Elementary   | 2         | 1.43%   |
| Debian       | 2         | 1.43%   |
| ArcoLinux    | 2         | 1.43%   |
| Ubuntu MATE  | 1         | 0.71%   |
| SteamOS      | 1         | 0.71%   |
| ROSA         | 1         | 0.71%   |
| Pop!_OS      | 1         | 0.71%   |
| openSUSE     | 1         | 0.71%   |
| NixOS        | 1         | 0.71%   |
| MX           | 1         | 0.71%   |
| Gentoo       | 1         | 0.71%   |
| Feren OS     | 1         | 0.71%   |
| EndeavourOS  | 1         | 0.71%   |
| BlackPanther | 1         | 0.71%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 6         | 3.97%   |
| 4.16.18-pa2-2bp1            | 6         | 3.97%   |
| 4.16.18-pa2-1bp5            | 5         | 3.31%   |
| 5.8.0-53-generic            | 4         | 2.65%   |
| 5.5.19-bp0                  | 4         | 2.65%   |
| 5.16.7-desktop-1omv4003     | 4         | 2.65%   |
| 5.13.0-39-generic           | 4         | 2.65%   |
| 5.4.0-73-generic            | 3         | 1.99%   |
| 5.4.0-58-generic            | 3         | 1.99%   |
| 5.4.0-52-generic            | 3         | 1.99%   |
| 5.11.0-38-generic           | 3         | 1.99%   |
| 6.1.1-desktop-1omv2290      | 2         | 1.32%   |
| 5.8.0-50-generic            | 2         | 1.32%   |
| 5.8.0-43-generic            | 2         | 1.32%   |
| 5.4.0-72-generic            | 2         | 1.32%   |
| 5.4.0-42-generic            | 2         | 1.32%   |
| 5.3.0-28-generic            | 2         | 1.32%   |
| 5.15.0-46-generic           | 2         | 1.32%   |
| 5.15.0-41-generic           | 2         | 1.32%   |
| 5.13.0-40-generic           | 2         | 1.32%   |
| 5.13.0-37-generic           | 2         | 1.32%   |
| 5.13.0-30-generic           | 2         | 1.32%   |
| 5.11.12-desktop-1omv4002    | 2         | 1.32%   |
| 5.0.0-13-generic            | 2         | 1.32%   |
| 4.15.0-51-generic           | 2         | 1.32%   |
| 4.15.0-20-generic           | 2         | 1.32%   |
| 4.15.0-101-generic          | 2         | 1.32%   |
| 6.0.6-arch1-1               | 1         | 0.66%   |
| 6.0.15-200.fc36.x86_64      | 1         | 0.66%   |
| 6.0.12-200.fc36.x86_64      | 1         | 0.66%   |
| 5.8.11-1-MANJARO            | 1         | 0.66%   |
| 5.8.1-3-MANJARO             | 1         | 0.66%   |
| 5.8.0-49-generic            | 1         | 0.66%   |
| 5.8.0-48-generic            | 1         | 0.66%   |
| 5.8.0-44-generic            | 1         | 0.66%   |
| 5.8.0-34-generic            | 1         | 0.66%   |
| 5.6.8-1-MANJARO             | 1         | 0.66%   |
| 5.4.60-1-lts                | 1         | 0.66%   |
| 5.4.32-generic-2rosa-x86_64 | 1         | 0.66%   |
| 5.4.0-80-generic            | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 14.86%  |
| 5.8.0   | 12        | 8.11%   |
| 5.13.0  | 12        | 8.11%   |
| 4.16.18 | 11        | 7.43%   |
| 4.15.0  | 9         | 6.08%   |
| 5.15.0  | 6         | 4.05%   |
| 5.11.0  | 6         | 4.05%   |
| 5.10.14 | 6         | 4.05%   |
| 5.0.0   | 6         | 4.05%   |
| 5.3.0   | 5         | 3.38%   |
| 5.5.19  | 4         | 2.7%    |
| 5.16.7  | 4         | 2.7%    |
| 4.18.0  | 4         | 2.7%    |
| 5.10.0  | 3         | 2.03%   |
| 6.1.1   | 2         | 1.35%   |
| 5.19.12 | 2         | 1.35%   |
| 5.11.12 | 2         | 1.35%   |
| 6.0.6   | 1         | 0.68%   |
| 6.0.15  | 1         | 0.68%   |
| 6.0.12  | 1         | 0.68%   |
| 5.8.11  | 1         | 0.68%   |
| 5.8.1   | 1         | 0.68%   |
| 5.6.8   | 1         | 0.68%   |
| 5.4.60  | 1         | 0.68%   |
| 5.4.32  | 1         | 0.68%   |
| 5.2.13  | 1         | 0.68%   |
| 5.19.0  | 1         | 0.68%   |
| 5.18.18 | 1         | 0.68%   |
| 5.18.13 | 1         | 0.68%   |
| 5.17.5  | 1         | 0.68%   |
| 5.17.4  | 1         | 0.68%   |
| 5.17.0  | 1         | 0.68%   |
| 5.16.16 | 1         | 0.68%   |
| 5.16.13 | 1         | 0.68%   |
| 5.16.12 | 1         | 0.68%   |
| 5.16.0  | 1         | 0.68%   |
| 5.15.65 | 1         | 0.68%   |
| 5.15.3  | 1         | 0.68%   |
| 5.14.18 | 1         | 0.68%   |
| 5.11.20 | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 16.33%  |
| 5.8     | 14        | 9.52%   |
| 5.13    | 12        | 8.16%   |
| 5.10    | 12        | 8.16%   |
| 4.16    | 12        | 8.16%   |
| 5.11    | 10        | 6.8%    |
| 4.15    | 9         | 6.12%   |
| 5.16    | 8         | 5.44%   |
| 5.15    | 8         | 5.44%   |
| 5.0     | 6         | 4.08%   |
| 5.3     | 5         | 3.4%    |
| 4.18    | 5         | 3.4%    |
| 5.5     | 4         | 2.72%   |
| 5.19    | 3         | 2.04%   |
| 5.17    | 3         | 2.04%   |
| 6.1     | 2         | 1.36%   |
| 6.0     | 2         | 1.36%   |
| 5.18    | 2         | 1.36%   |
| 5.6     | 1         | 0.68%   |
| 5.2     | 1         | 0.68%   |
| 5.14    | 1         | 0.68%   |
| 4.17    | 1         | 0.68%   |
| 4.13    | 1         | 0.68%   |
| 4.12    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 134       | 98.53%  |
| i686   | 2         | 1.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 43        | 30.94%  |
| KDE5            | 27        | 19.42%  |
| Unknown         | 21        | 15.11%  |
| GNOME Flashback | 13        | 9.35%   |
| XFCE            | 11        | 7.91%   |
| X-Cinnamon      | 8         | 5.76%   |
| KDE             | 5         | 3.6%    |
| MATE            | 3         | 2.16%   |
| LXQt            | 3         | 2.16%   |
| Pantheon        | 2         | 1.44%   |
| Cinnamon        | 2         | 1.44%   |
| sway            | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 110       | 80.88%  |
| Wayland | 16        | 11.76%  |
| Unknown | 9         | 6.62%   |
| Tty     | 1         | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 67        | 48.91%  |
| SDDM    | 26        | 18.98%  |
| GDM     | 22        | 16.06%  |
| LightDM | 9         | 6.57%   |
| GDM3    | 9         | 6.57%   |
| TDM     | 3         | 2.19%   |
| GREETD  | 1         | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_UY   | 72        | 51.06%  |
| en_US   | 28        | 19.86%  |
| Unknown | 18        | 12.77%  |
| es_ES   | 15        | 10.64%  |
| es_MX   | 3         | 2.13%   |
| es_AR   | 2         | 1.42%   |
| pt_BR   | 1         | 0.71%   |
| en_CA   | 1         | 0.71%   |
| C       | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 74        | 53.62%  |
| BIOS | 64        | 46.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 114       | 82.61%  |
| Overlay | 13        | 9.42%   |
| Btrfs   | 6         | 4.35%   |
| Unknown | 4         | 2.9%    |
| Ext3    | 1         | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 59.56%  |
| GPT     | 40        | 29.41%  |
| MBR     | 15        | 11.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 81.62%  |
| Yes       | 25        | 18.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 74.45%  |
| Yes       | 35        | 25.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 19.85%  |
| Lenovo              | 23        | 16.91%  |
| ECS                 | 16        | 11.76%  |
| Dell                | 13        | 9.56%   |
| ASUSTek Computer    | 11        | 8.09%   |
| Acer                | 11        | 8.09%   |
| Toshiba             | 9         | 6.62%   |
| Samsung Electronics | 4         | 2.94%   |
| MSI                 | 4         | 2.94%   |
| Standard            | 3         | 2.21%   |
| GPU Company         | 2         | 1.47%   |
| Gateway             | 2         | 1.47%   |
| Apple               | 2         | 1.47%   |
| Valve               | 1         | 0.74%   |
| Sony                | 1         | 0.74%   |
| Positivo            | 1         | 0.74%   |
| Panasonic           | 1         | 0.74%   |
| OEM                 | 1         | 0.74%   |
| iClever             | 1         | 0.74%   |
| Haitech             | 1         | 0.74%   |
| Alienware           | 1         | 0.74%   |
| Unknown             | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 16        | 11.76%  |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.21%   |
| Toshiba Satellite L55t-B              | 2         | 1.47%   |
| Standard SF20BA2                      | 2         | 1.47%   |
| HP Pavilion 15                        | 2         | 1.47%   |
| HP Laptop 15-bs0xx                    | 2         | 1.47%   |
| Valve Jupiter                         | 1         | 0.74%   |
| Toshiba Satellite L45-B               | 1         | 0.74%   |
| Toshiba Satellite C855                | 1         | 0.74%   |
| Toshiba Satellite C75D-C              | 1         | 0.74%   |
| Toshiba Satellite C75D-B              | 1         | 0.74%   |
| Toshiba Satellite C645D               | 1         | 0.74%   |
| Toshiba Satellite C55-B               | 1         | 0.74%   |
| Toshiba Satellite C45-A               | 1         | 0.74%   |
| Standard EF20EA                       | 1         | 0.74%   |
| Sony SVF14211CLB                      | 1         | 0.74%   |
| Samsung NC208/NC108                   | 1         | 0.74%   |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.74%   |
| Samsung 700T                          | 1         | 0.74%   |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.74%   |
| Positivo Serie AT300                  | 1         | 0.74%   |
| Panasonic CF-31JEGAX1M                | 1         | 0.74%   |
| OEM V40SI2                            | 1         | 0.74%   |
| MSI GS63VR 6RF                        | 1         | 0.74%   |
| MSI GL65 Leopard 10SCXR               | 1         | 0.74%   |
| MSI GL63 8RD                          | 1         | 0.74%   |
| MSI GE62 6QD                          | 1         | 0.74%   |
| Lenovo V15-ADA 82C7                   | 1         | 0.74%   |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.74%   |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.74%   |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.74%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.74%   |
| Lenovo ThinkPad P50 20EQS14H00        | 1         | 0.74%   |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.74%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.74%   |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.74%   |
| Lenovo ThinkPad Edge E531 68852BS     | 1         | 0.74%   |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.74%   |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.74%   |
| Lenovo IdeaPad S340-15IWL 81N8        | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 16        | 11.76%  |
| Lenovo ThinkPad        | 10        | 7.35%   |
| Toshiba Satellite      | 9         | 6.62%   |
| HP Laptop              | 8         | 5.88%   |
| Acer Aspire            | 8         | 5.88%   |
| HP Pavilion            | 7         | 5.15%   |
| Dell Inspiron          | 7         | 5.15%   |
| Lenovo IdeaPad         | 6         | 4.41%   |
| ASUS ROG               | 4         | 2.94%   |
| Dell Latitude          | 3         | 2.21%   |
| Standard SF20BA2       | 2         | 1.47%   |
| Dell XPS               | 2         | 1.47%   |
| ASUS VivoBook          | 2         | 1.47%   |
| Acer TravelMate        | 2         | 1.47%   |
| Valve Jupiter          | 1         | 0.74%   |
| Standard EF20EA        | 1         | 0.74%   |
| Sony SVF14211CLB       | 1         | 0.74%   |
| Samsung NC208          | 1         | 0.74%   |
| Samsung N102SP         | 1         | 0.74%   |
| Samsung 700T           | 1         | 0.74%   |
| Samsung 300E4C         | 1         | 0.74%   |
| Positivo Serie         | 1         | 0.74%   |
| Panasonic CF-31JEGAX1M | 1         | 0.74%   |
| OEM V40SI2             | 1         | 0.74%   |
| MSI GS63VR             | 1         | 0.74%   |
| MSI GL65               | 1         | 0.74%   |
| MSI GL63               | 1         | 0.74%   |
| MSI GE62               | 1         | 0.74%   |
| Lenovo V15-ADA         | 1         | 0.74%   |
| Lenovo ThinkBook       | 1         | 0.74%   |
| Lenovo G50-70          | 1         | 0.74%   |
| Lenovo G405            | 1         | 0.74%   |
| Lenovo B51-30          | 1         | 0.74%   |
| Lenovo B50-45          | 1         | 0.74%   |
| Lenovo 14w             | 1         | 0.74%   |
| iClever IC-T01         | 1         | 0.74%   |
| HP ZBook               | 1         | 0.74%   |
| HP Stream              | 1         | 0.74%   |
| HP Presario            | 1         | 0.74%   |
| HP Notebook            | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 24        | 17.65%  |
| 2019 | 14        | 10.29%  |
| 2013 | 14        | 10.29%  |
| 2020 | 12        | 8.82%   |
| 2014 | 12        | 8.82%   |
| 2018 | 11        | 8.09%   |
| 2015 | 10        | 7.35%   |
| 2011 | 10        | 7.35%   |
| 2016 | 9         | 6.62%   |
| 2012 | 7         | 5.15%   |
| 2010 | 4         | 2.94%   |
| 2008 | 3         | 2.21%   |
| 2021 | 2         | 1.47%   |
| 2007 | 2         | 1.47%   |
| 2022 | 1         | 0.74%   |
| 2009 | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 136       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 123       | 89.78%  |
| Enabled  | 14        | 10.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 136       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 26.81%  |
| 4.01-8.0    | 33        | 23.91%  |
| 1.01-2.0    | 24        | 17.39%  |
| 8.01-16.0   | 21        | 15.22%  |
| 16.01-24.0  | 12        | 8.7%    |
| 32.01-64.0  | 6         | 4.35%   |
| 24.01-32.0  | 3         | 2.17%   |
| 2.01-3.0    | 1         | 0.72%   |
| 64.01-256.0 | 1         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 67        | 45.89%  |
| 2.01-3.0  | 32        | 21.92%  |
| 4.01-8.0  | 16        | 10.96%  |
| 3.01-4.0  | 13        | 8.9%    |
| 0.51-1.0  | 12        | 8.22%   |
| 8.01-16.0 | 5         | 3.42%   |
| 0.01-0.5  | 1         | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 80.88%  |
| 2      | 25        | 18.38%  |
| 0      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 66.42%  |
| Yes       | 46        | 33.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 66.18%  |
| No        | 46        | 33.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 97.06%  |
| No        | 4         | 2.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 80.15%  |
| No        | 27        | 19.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 136       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 96        | 66.67%  |
| Maldonado              | 8         | 5.56%   |
| Canelones              | 8         | 5.56%   |
| Punta del Este         | 3         | 2.08%   |
| Las Piedras            | 3         | 2.08%   |
| Buceo                  | 3         | 2.08%   |
| Salto                  | 2         | 1.39%   |
| Rocha                  | 2         | 1.39%   |
| Punta Gorda            | 2         | 1.39%   |
| Ciudad del Plata       | 2         | 1.39%   |
| Solymar                | 1         | 0.69%   |
| San Jose de Mayo       | 1         | 0.69%   |
| Pinamar                | 1         | 0.69%   |
| Paysandú              | 1         | 0.69%   |
| Parque Rodo            | 1         | 0.69%   |
| Melilla                | 1         | 0.69%   |
| Maronas                | 1         | 0.69%   |
| Las Flores             | 1         | 0.69%   |
| La Paz                 | 1         | 0.69%   |
| Joaquin Suarez         | 1         | 0.69%   |
| El Tesoro              | 1         | 0.69%   |
| El Pinar               | 1         | 0.69%   |
| Durazno                | 1         | 0.69%   |
| Barrancas Coloradas    | 1         | 0.69%   |
| Arenas de Jose Ignacio | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 23        | 27     | 15.33%  |
| Unknown                     | 22        | 28     | 14.67%  |
| Toshiba                     | 19        | 22     | 12.67%  |
| Kingston                    | 17        | 23     | 11.33%  |
| Seagate                     | 15        | 17     | 10%     |
| SanDisk                     | 11        | 13     | 7.33%   |
| Samsung Electronics         | 9         | 9      | 6%      |
| Hitachi                     | 6         | 8      | 4%      |
| SK hynix                    | 5         | 5      | 3.33%   |
| HGST                        | 5         | 5      | 3.33%   |
| Intel                       | 4         | 4      | 2.67%   |
| Hewlett-Packard             | 3         | 3      | 2%      |
| Crucial                     | 2         | 3      | 1.33%   |
| W800SH                      | 1         | 1      | 0.67%   |
| Netac                       | 1         | 1      | 0.67%   |
| LITEON                      | 1         | 2      | 0.67%   |
| Kingston Technology Company | 1         | 1      | 0.67%   |
| Dahua                       | 1         | 1      | 0.67%   |
| China                       | 1         | 1      | 0.67%   |
| BIWIN                       | 1         | 1      | 0.67%   |
| BHT                         | 1         | 1      | 0.67%   |
| Apple                       | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 10        | 6.49%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 4.55%   |
| Unknown DA4032  32GB                 | 5         | 3.25%   |
| Toshiba MQ01ABD075 752GB             | 4         | 2.6%    |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 2.6%    |
| Kingston SA400S37480G 480GB SSD      | 4         | 2.6%    |
| Toshiba MQ01ABF050 500GB             | 3         | 1.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.95%   |
| SanDisk DF4032  32GB                 | 3         | 1.95%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 2         | 1.3%    |
| Unknown SD/MMC/MS PRO 16GB           | 2         | 1.3%    |
| Toshiba HDWK105 500GB                | 2         | 1.3%    |
| SanDisk NVMe SSD Drive 256GB         | 2         | 1.3%    |
| SanDisk NVMe SSD Drive 1024GB        | 2         | 1.3%    |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.65%   |
| WDC WDS250G2X0C-00L350 250GB         | 1         | 0.65%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.65%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.65%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.65%   |
| WDC WD3200LPCX-24C6HT0 320GB         | 1         | 0.65%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 1         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.65%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.65%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.65%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.65%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.65%   |
| W800SH 512GB SSD                     | 1         | 0.65%   |
| Unknown SD64G  64GB                  | 1         | 0.65%   |
| Unknown SD16G  32GB                  | 1         | 0.65%   |
| Unknown NCard  32GB                  | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 18        | 22     | 29.51%  |
| Toshiba | 15        | 18     | 24.59%  |
| Seagate | 15        | 17     | 24.59%  |
| Hitachi | 6         | 8      | 9.84%   |
| HGST    | 5         | 5      | 8.2%    |
| Unknown | 2         | 2      | 3.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 17     | 35.9%   |
| Samsung Electronics | 5         | 5      | 12.82%  |
| SanDisk             | 3         | 3      | 7.69%   |
| Hewlett-Packard     | 3         | 3      | 7.69%   |
| WDC                 | 2         | 2      | 5.13%   |
| SK hynix            | 2         | 2      | 5.13%   |
| Intel               | 2         | 2      | 5.13%   |
| W800SH              | 1         | 1      | 2.56%   |
| Toshiba             | 1         | 1      | 2.56%   |
| Netac               | 1         | 1      | 2.56%   |
| Dahua               | 1         | 1      | 2.56%   |
| Crucial             | 1         | 2      | 2.56%   |
| China               | 1         | 1      | 2.56%   |
| BIWIN               | 1         | 1      | 2.56%   |
| BHT                 | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 72     | 40.14%  |
| SSD  | 38        | 43     | 25.85%  |
| NVMe | 26        | 31     | 17.69%  |
| MMC  | 24        | 31     | 16.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 112    | 62.94%  |
| NVMe | 26        | 31     | 18.18%  |
| MMC  | 24        | 31     | 16.78%  |
| SAS  | 3         | 3      | 2.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 65        | 76     | 68.42%  |
| 0.51-1.0   | 29        | 38     | 30.53%  |
| 1.01-2.0   | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 33        | 23.57%  |
| 101-250        | 32        | 22.86%  |
| 21-50          | 20        | 14.29%  |
| 501-1000       | 20        | 14.29%  |
| 1-20           | 18        | 12.86%  |
| 51-100         | 8         | 5.71%   |
| 1001-2000      | 5         | 3.57%   |
| Unknown        | 3         | 2.14%   |
| More than 3000 | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 72        | 49.32%  |
| 21-50          | 26        | 17.81%  |
| 251-500        | 14        | 9.59%   |
| 51-100         | 13        | 8.9%    |
| 101-250        | 11        | 7.53%   |
| 501-1000       | 5         | 3.42%   |
| Unknown        | 3         | 2.05%   |
| More than 3000 | 1         | 0.68%   |
| 1001-2000      | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 2      | 16.67%  |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 8.33%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 8.33%   |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 8.33%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 8.33%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 8.33%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 8.33%   |
| HGST HTS545032A7E380 320GB          | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 33.33%  |
| Toshiba | 3         | 4      | 25%     |
| Seagate | 2         | 2      | 16.67%  |
| SanDisk | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 36.36%  |
| Toshiba | 3         | 4      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 12     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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
| Detected | 86        | 114    | 62.77%  |
| Works    | 39        | 50     | 28.47%  |
| Malfunc  | 12        | 13     | 8.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 94        | 64.83%  |
| AMD                              | 26        | 17.93%  |
| SanDisk                          | 8         | 5.52%   |
| Samsung Electronics              | 4         | 2.76%   |
| Kingston Technology Company      | 4         | 2.76%   |
| Toshiba America Info Systems     | 3         | 2.07%   |
| SK hynix                         | 2         | 1.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |
| Micron/Crucial Technology        | 1         | 0.69%   |
| Lite-On Technology               | 1         | 0.69%   |
| Apple                            | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 15.23%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 11.26%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 5.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 3.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 3.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 2.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.99%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.32%   |
| Intel SSD 660P Series                                                            | 2         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.32%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.66%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.66%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.66%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.66%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.66%   |
| Lite-On NVMe Controller                                                          | 1         | 0.66%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 111       | 74.5%   |
| NVMe | 26        | 17.45%  |
| RAID | 6         | 4.03%   |
| IDE  | 6         | 4.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 77.21%  |
| AMD    | 31        | 22.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 12.5%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.21%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.21%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 2.21%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.47%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 1.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.47%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.47%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.47%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.47%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 2         | 1.47%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.47%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.47%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.47%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.74%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.74%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.74%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.74%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.74%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.74%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.74%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.74%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.74%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.74%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.74%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 28        | 20.59%  |
| Intel Core i5      | 25        | 18.38%  |
| Intel Core i7      | 22        | 16.18%  |
| Intel Core i3      | 11        | 8.09%   |
| Intel Pentium      | 7         | 5.15%   |
| Other              | 5         | 3.68%   |
| Intel Atom         | 5         | 3.68%   |
| AMD A6             | 5         | 3.68%   |
| AMD Ryzen 9        | 4         | 2.94%   |
| AMD E              | 3         | 2.21%   |
| Intel Genuine      | 2         | 1.47%   |
| Intel Core 2 Duo   | 2         | 1.47%   |
| AMD Ryzen 7        | 2         | 1.47%   |
| AMD Ryzen 5        | 2         | 1.47%   |
| AMD Ryzen 3        | 2         | 1.47%   |
| AMD E1             | 2         | 1.47%   |
| Intel Pentium Dual | 1         | 0.74%   |
| AMD Phenom II      | 1         | 0.74%   |
| AMD FX             | 1         | 0.74%   |
| AMD E2             | 1         | 0.74%   |
| AMD Athlon II      | 1         | 0.74%   |
| AMD Athlon         | 1         | 0.74%   |
| AMD A8             | 1         | 0.74%   |
| AMD A4             | 1         | 0.74%   |
| AMD A10            | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 84        | 61.76%  |
| 4      | 39        | 28.68%  |
| 8      | 5         | 3.68%   |
| 6      | 5         | 3.68%   |
| 1      | 3         | 2.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 136       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 55.15%  |
| 1      | 61        | 44.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 133       | 97.79%  |
| Unknown        | 3         | 2.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 21.01%  |
| 0x206a7    | 7         | 5.07%   |
| 0x506c9    | 6         | 4.35%   |
| 0x406c4    | 6         | 4.35%   |
| 0x40651    | 6         | 4.35%   |
| 0x306d4    | 5         | 3.62%   |
| 0x20655    | 5         | 3.62%   |
| 0x806ec    | 4         | 2.9%    |
| 0x806ea    | 4         | 2.9%    |
| 0x406e3    | 4         | 2.9%    |
| 0x30678    | 4         | 2.9%    |
| 0x906ea    | 3         | 2.17%   |
| 0x806e9    | 3         | 2.17%   |
| 0x6fd      | 3         | 2.17%   |
| 0x306c3    | 3         | 2.17%   |
| 0x306a9    | 3         | 2.17%   |
| 0x08108109 | 3         | 2.17%   |
| 0x06006705 | 3         | 2.17%   |
| 0x806c1    | 2         | 1.45%   |
| 0x706e5    | 2         | 1.45%   |
| 0x506e3    | 2         | 1.45%   |
| 0x406c3    | 2         | 1.45%   |
| 0x08600104 | 2         | 1.45%   |
| 0x0810100b | 2         | 1.45%   |
| 0x07030105 | 2         | 1.45%   |
| 0x07030104 | 2         | 1.45%   |
| 0x0700010f | 2         | 1.45%   |
| 0xa0652    | 1         | 0.72%   |
| 0x806eb    | 1         | 0.72%   |
| 0x706a1    | 1         | 0.72%   |
| 0x30673    | 1         | 0.72%   |
| 0x30661    | 1         | 0.72%   |
| 0x106e5    | 1         | 0.72%   |
| 0x106ca    | 1         | 0.72%   |
| 0x1067a    | 1         | 0.72%   |
| 0x10676    | 1         | 0.72%   |
| 0x0a50000c | 1         | 0.72%   |
| 0x08600102 | 1         | 0.72%   |
| 0x07030106 | 1         | 0.72%   |
| 0x06006118 | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Goldmont      | 17        | 12.5%   |
| KabyLake      | 16        | 11.76%  |
| Silvermont    | 15        | 11.03%  |
| Haswell       | 10        | 7.35%   |
| Skylake       | 8         | 5.88%   |
| SandyBridge   | 7         | 5.15%   |
| IvyBridge     | 6         | 4.41%   |
| Excavator     | 6         | 4.41%   |
| Broadwell     | 6         | 4.41%   |
| Westmere      | 5         | 3.68%   |
| Puma          | 5         | 3.68%   |
| Zen+          | 4         | 2.94%   |
| Zen 2         | 4         | 2.94%   |
| Core          | 3         | 2.21%   |
| Bobcat        | 3         | 2.21%   |
| Zen           | 2         | 1.47%   |
| TigerLake     | 2         | 1.47%   |
| Penryn        | 2         | 1.47%   |
| K10           | 2         | 1.47%   |
| Jaguar        | 2         | 1.47%   |
| IceLake       | 2         | 1.47%   |
| CometLake     | 2         | 1.47%   |
| Bonnell       | 2         | 1.47%   |
| Zen 3         | 1         | 0.74%   |
| Piledriver    | 1         | 0.74%   |
| Nehalem       | 1         | 0.74%   |
| Goldmont plus | 1         | 0.74%   |
| Unknown       | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 64.38%  |
| AMD                              | 39        | 24.38%  |
| Nvidia                           | 17        | 10.63%  |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 10.37%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 6.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.66%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.44%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.44%   |
| Intel HD Graphics 530                                                                    | 4         | 2.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.44%   |
| AMD Renoir                                                                               | 4         | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.44%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.83%   |
| Intel HD Graphics 620                                                                    | 3         | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.83%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.83%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.22%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.22%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.22%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.22%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia TU117M                                                                            | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.61%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 84        | 61.76%  |
| 1 x AMD        | 24        | 17.65%  |
| Intel + Nvidia | 11        | 8.09%   |
| Intel + AMD    | 8         | 5.88%   |
| AMD + Nvidia   | 5         | 3.68%   |
| 2 x AMD        | 2         | 1.47%   |
| 1 x SiS        | 1         | 0.74%   |
| 1 x Nvidia     | 1         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 124       | 91.18%  |
| Proprietary | 11        | 8.09%   |
| Unknown     | 1         | 0.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 70.07%  |
| 0.01-0.5   | 14        | 10.22%  |
| 0.51-1.0   | 11        | 8.03%   |
| 1.01-2.0   | 9         | 6.57%   |
| 3.01-4.0   | 5         | 3.65%   |
| 5.01-6.0   | 2         | 1.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 25        | 17.24%  |
| AU Optronics            | 21        | 14.48%  |
| Chimei Innolux          | 20        | 13.79%  |
| BOE                     | 18        | 12.41%  |
| Samsung Electronics     | 14        | 9.66%   |
| InfoVision              | 7         | 4.83%   |
| KDC                     | 6         | 4.14%   |
| Sharp                   | 4         | 2.76%   |
| PANDA                   | 4         | 2.76%   |
| Chi Mei Optoelectronics | 4         | 2.76%   |
| ViewSonic               | 3         | 2.07%   |
| Acer                    | 3         | 2.07%   |
| KTC                     | 2         | 1.38%   |
| HSI                     | 2         | 1.38%   |
| Apple                   | 2         | 1.38%   |
| Valve                   | 1         | 0.69%   |
| Sun                     | 1         | 0.69%   |
| LG Philips              | 1         | 0.69%   |
| JDI                     | 1         | 0.69%   |
| InnoLux Display         | 1         | 0.69%   |
| HKC                     | 1         | 0.69%   |
| Hewlett-Packard         | 1         | 0.69%   |
| Dell                    | 1         | 0.69%   |
| CPT                     | 1         | 0.69%   |
| AOC                     | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 6         | 4.08%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 4         | 2.72%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 2.04%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                | 2         | 1.36%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.36%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.36%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.36%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 1.36%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.36%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 2         | 1.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.36%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.36%   |
| HSI HiTV HSI0001 3840x2160 708x398mm 32.0-inch                        | 2         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 2         | 1.36%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.36%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 1.36%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.36%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch         | 1         | 0.68%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.68%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.68%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.68%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.68%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.68%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.68%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.68%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.68%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.68%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.68%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 73        | 54.89%  |
| 1920x1080 (FHD)   | 35        | 26.32%  |
| 1600x900 (HD+)    | 7         | 5.26%   |
| 1920x1200 (WUXGA) | 6         | 4.51%   |
| 1280x800 (WXGA)   | 4         | 3.01%   |
| 3840x2160 (4K)    | 3         | 2.26%   |
| 2560x1440 (QHD)   | 2         | 1.5%    |
| 800x1280          | 1         | 0.75%   |
| 1360x768          | 1         | 0.75%   |
| 1024x600          | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 69        | 47.59%  |
| 13     | 23        | 15.86%  |
| 14     | 18        | 12.41%  |
| 17     | 6         | 4.14%   |
| 11     | 6         | 4.14%   |
| 24     | 4         | 2.76%   |
| 23     | 4         | 2.76%   |
| 40     | 2         | 1.38%   |
| 34     | 2         | 1.38%   |
| 21     | 2         | 1.38%   |
| 18     | 2         | 1.38%   |
| 12     | 2         | 1.38%   |
| 10     | 2         | 1.38%   |
| 57     | 1         | 0.69%   |
| 27     | 1         | 0.69%   |
| 7      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 103       | 71.53%  |
| 201-300     | 15        | 10.42%  |
| 501-600     | 9         | 6.25%   |
| 351-400     | 7         | 4.86%   |
| 401-500     | 4         | 2.78%   |
| 801-900     | 2         | 1.39%   |
| 701-800     | 2         | 1.39%   |
| 1001-1500   | 1         | 0.69%   |
| 1-100       | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 119       | 93.7%   |
| 16/10 | 5         | 3.94%   |
| 21/9  | 2         | 1.57%   |
| 0.67  | 1         | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 47.59%  |
| 81-90          | 37        | 25.52%  |
| 201-250        | 8         | 5.52%   |
| 51-60          | 6         | 4.14%   |
| 121-130        | 6         | 4.14%   |
| 71-80          | 4         | 2.76%   |
| 61-70          | 2         | 1.38%   |
| 351-500        | 2         | 1.38%   |
| 41-50          | 2         | 1.38%   |
| 151-200        | 2         | 1.38%   |
| 141-150        | 2         | 1.38%   |
| 501-1000       | 2         | 1.38%   |
| More than 1000 | 1         | 0.69%   |
| 1-40           | 1         | 0.69%   |
| 301-350        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 74        | 51.75%  |
| 121-160       | 38        | 26.57%  |
| 51-100        | 25        | 17.48%  |
| 161-240       | 4         | 2.8%    |
| More than 240 | 1         | 0.7%    |
| 1-50          | 1         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 83.45%  |
| 2     | 19        | 13.67%  |
| 3     | 2         | 1.44%   |
| 0     | 2         | 1.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 68        | 33.17%  |
| Intel                            | 62        | 30.24%  |
| Qualcomm Atheros                 | 35        | 17.07%  |
| Broadcom                         | 17        | 8.29%   |
| Ralink Technology                | 3         | 1.46%   |
| Ralink                           | 3         | 1.46%   |
| MediaTek                         | 3         | 1.46%   |
| TP-Link                          | 2         | 0.98%   |
| Broadcom Limited                 | 2         | 0.98%   |
| Xiaomi                           | 1         | 0.49%   |
| T & A Mobile Phones              | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Sierra Wireless                  | 1         | 0.49%   |
| Samsung Electronics              | 1         | 0.49%   |
| Qualcomm Atheros Communications  | 1         | 0.49%   |
| Lenovo                           | 1         | 0.49%   |
| Huawei Technologies              | 1         | 0.49%   |
| DisplayLink                      | 1         | 0.49%   |
| ASIX Electronics                 | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 34        | 14.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 23        | 9.7%    |
| Intel Wireless 3165                                                     | 22        | 9.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.53%   |
| Intel Wireless 7265                                                     | 5         | 2.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.69%   |
| Intel Wireless 7260                                                     | 4         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.69%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.27%   |
| Intel Wireless 8260                                                     | 3         | 1.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.84%   |
| Intel Wireless 3160                                                     | 2         | 0.84%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.84%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 43.48%  |
| Qualcomm Atheros                | 28        | 20.29%  |
| Realtek Semiconductor           | 26        | 18.84%  |
| Broadcom                        | 12        | 8.7%    |
| Ralink Technology               | 3         | 2.17%   |
| Ralink                          | 3         | 2.17%   |
| Broadcom Limited                | 2         | 1.45%   |
| TP-Link                         | 1         | 0.72%   |
| Sierra Wireless                 | 1         | 0.72%   |
| Qualcomm Atheros Communications | 1         | 0.72%   |
| MediaTek                        | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 22        | 15.83%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 5.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 5.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.32%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 4.32%   |
| Intel Wireless 7265                                                     | 5         | 3.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.88%   |
| Intel Wireless 7260                                                     | 4         | 2.88%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.16%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 2.16%   |
| Intel Wireless 8260                                                     | 3         | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.44%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.44%   |
| Intel Wireless 3160                                                     | 2         | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.44%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.72%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.72%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.72%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.72%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.72%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 60.82%  |
| Intel                            | 12        | 12.37%  |
| Qualcomm Atheros                 | 9         | 9.28%   |
| Broadcom                         | 7         | 7.22%   |
| MediaTek                         | 2         | 2.06%   |
| Xiaomi                           | 1         | 1.03%   |
| TP-Link                          | 1         | 1.03%   |
| Silicon Integrated Systems [SiS] | 1         | 1.03%   |
| Samsung Electronics              | 1         | 1.03%   |
| Lenovo                           | 1         | 1.03%   |
| Huawei Technologies              | 1         | 1.03%   |
| DisplayLink                      | 1         | 1.03%   |
| ASIX Electronics                 | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 35.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 23.71%  |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 3.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.06%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.06%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.06%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.06%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.03%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.03%   |
| Samsung Kiera                                                     | 1         | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.03%   |
| Realtek Realtek Ethernet controller                               | 1         | 1.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.03%   |
| MediaTek moto e(6) plus                                           | 1         | 1.03%   |
| Lenovo USB-C to LAN                                               | 1         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.03%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.03%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.03%   |
| Huawei E353/E3131                                                 | 1         | 1.03%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.03%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 59.19%  |
| Ethernet | 90        | 40.36%  |
| Unknown  | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 86.33%  |
| Ethernet | 19        | 13.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 62.5%   |
| 1     | 48        | 35.29%  |
| 0     | 3         | 2.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 77.21%  |
| Yes  | 31        | 22.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 47.27%  |
| Realtek Semiconductor           | 13        | 11.82%  |
| Qualcomm Atheros Communications | 11        | 10%     |
| IMC Networks                    | 8         | 7.27%   |
| Toshiba                         | 7         | 6.36%   |
| Lite-On Technology              | 3         | 2.73%   |
| Foxconn / Hon Hai               | 3         | 2.73%   |
| Cambridge Silicon Radio         | 3         | 2.73%   |
| Broadcom                        | 3         | 2.73%   |
| Ralink                          | 2         | 1.82%   |
| Apple                           | 2         | 1.82%   |
| Ralink Technology               | 1         | 0.91%   |
| Foxconn International           | 1         | 0.91%   |
| Alps Electric                   | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 31.82%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 7.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 5.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.45%   |
| Intel AX200 Bluetooth                               | 4         | 3.64%   |
| Toshiba Bluetooth Device                            | 3         | 2.73%   |
| Toshiba BCM43142A0                                  | 3         | 2.73%   |
| Realtek Bluetooth Radio                             | 3         | 2.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.73%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.73%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.82%   |
| Intel AX201 Bluetooth                               | 2         | 1.82%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.82%   |
| Toshiba Bluetooth Radio                             | 1         | 0.91%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.91%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.91%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.91%   |
| Lite-On Bluetooth Device                            | 1         | 0.91%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.91%   |
| IMC Networks Wireless_Device                        | 1         | 0.91%   |
| IMC Networks Bluetooth Device                       | 1         | 0.91%   |
| IMC Networks Bluetooth                              | 1         | 0.91%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.91%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.91%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.91%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.91%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.91%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.91%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.91%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.91%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 101       | 66.45%  |
| AMD                                  | 31        | 20.39%  |
| Nvidia                               | 11        | 7.24%   |
| Logitech                             | 3         | 1.97%   |
| Generalplus Technology               | 2         | 1.32%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.66%   |
| Texas Instruments                    | 1         | 0.66%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.66%   |
| C-Media Electronics                  | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 8.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 5.58%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5.58%   |
| AMD FCH Azalia Controller                                                                         | 10        | 5.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 4.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 4.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.05%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.05%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 3.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.54%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 2.03%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.52%   |
| Logitech H390 headset with microphone                                                             | 2         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.02%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 1.02%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.02%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.02%   |
| Thesycon Systemsoftware & Consulting D10 Balanced                                                 | 1         | 0.51%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 28.4%   |
| SK hynix            | 15        | 18.52%  |
| Micron Technology   | 10        | 12.35%  |
| Ramaxel Technology  | 7         | 8.64%   |
| Kingston            | 5         | 6.17%   |
| Goldkey             | 5         | 6.17%   |
| Unknown             | 4         | 4.94%   |
| Crucial             | 4         | 4.94%   |
| Elpida              | 3         | 3.7%    |
| Nanya Technology    | 2         | 2.47%   |
| A-DATA Technology   | 2         | 2.47%   |
| Patriot             | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s    | 4         | 4.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 3         | 3.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 3         | 3.57%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s             | 2         | 2.38%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s      | 2         | 2.38%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 2         | 2.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 2.38%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s    | 2         | 2.38%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 2.38%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s      | 2         | 2.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                | 1         | 1.19%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 1         | 1.19%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                | 1         | 1.19%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.19%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.19%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.19%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 1.19%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s | 1         | 1.19%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s     | 1         | 1.19%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s      | 1         | 1.19%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                | 1         | 1.19%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 1.19%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                   | 1         | 1.19%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                   | 1         | 1.19%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s      | 1         | 1.19%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 1         | 1.19%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 1         | 1.19%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.19%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s   | 1         | 1.19%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 1.19%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 1.19%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 1.19%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 1.19%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s      | 1         | 1.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 54.55%  |
| DDR4   | 23        | 34.85%  |
| SDRAM  | 2         | 3.03%   |
| LPDDR3 | 2         | 3.03%   |
| DDR2   | 2         | 3.03%   |
| LPDDR4 | 1         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 92.19%  |
| Row Of Chips | 3         | 4.69%   |
| DIMM         | 2         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 27        | 36%     |
| 8192  | 20        | 26.67%  |
| 2048  | 16        | 21.33%  |
| 16384 | 8         | 10.67%  |
| 32768 | 2         | 2.67%   |
| 1024  | 2         | 2.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 32        | 42.67%  |
| 2667  | 13        | 17.33%  |
| 3200  | 6         | 8%      |
| 2400  | 6         | 8%      |
| 1334  | 5         | 6.67%   |
| 3266  | 3         | 4%      |
| 4199  | 2         | 2.67%   |
| 2133  | 2         | 2.67%   |
| 1333  | 2         | 2.67%   |
| 533   | 2         | 2.67%   |
| 1867  | 1         | 1.33%   |
| 1067  | 1         | 1.33%   |

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
| Chicony Electronics                    | 35        | 28%     |
| Realtek Semiconductor                  | 14        | 11.2%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 8.8%    |
| Acer                                   | 11        | 8.8%    |
| Microdia                               | 8         | 6.4%    |
| Suyin                                  | 7         | 5.6%    |
| Sunplus Innovation Technology          | 7         | 5.6%    |
| Unknown                                | 5         | 4%      |
| Silicon Motion                         | 4         | 3.2%    |
| IMC Networks                           | 4         | 3.2%    |
| Quanta                                 | 3         | 2.4%    |
| Importek                               | 3         | 2.4%    |
| Alcor Micro                            | 3         | 2.4%    |
| Syntek                                 | 2         | 1.6%    |
| Lite-On Technology                     | 2         | 1.6%    |
| Samsung Electronics                    | 1         | 0.8%    |
| Primax Electronics                     | 1         | 0.8%    |
| Luxvisions Innotech Limited            | 1         | 0.8%    |
| Logitech                               | 1         | 0.8%    |
| DigiTech                               | 1         | 0.8%    |
| Apple                                  | 1         | 0.8%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 13        | 10.4%   |
| Unknown USB Camera                                             | 5         | 4%      |
| Chicony Integrated Camera                                      | 5         | 4%      |
| Chicony HP Truevision HD                                       | 5         | 4%      |
| Acer Integrated Camera                                         | 5         | 4%      |
| Microdia Integrated_Webcam_HD                                  | 4         | 3.2%    |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 3.2%    |
| Realtek Lenovo EasyCamera                                      | 3         | 2.4%    |
| Realtek Integrated_Webcam_HD                                   | 3         | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 2.4%    |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.6%    |
| Realtek Integrated Webcam HD                                   | 2         | 1.6%    |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.6%    |
| Importek TOSHIBA Web Camera                                    | 2         | 1.6%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.6%    |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.6%    |
| Chicony HD WebCam                                              | 2         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.6%    |
| Acer Lenovo EasyCamera                                         | 2         | 1.6%    |
| Acer HD Webcam                                                 | 2         | 1.6%    |
| Syntek Integrated Camera                                       | 1         | 0.8%    |
| Syntek EasyCamera                                              | 1         | 0.8%    |
| Suyin VGA Webcam                                               | 1         | 0.8%    |
| Suyin HP Truevision HD                                         | 1         | 0.8%    |
| Suyin HP Integrated Webcam                                     | 1         | 0.8%    |
| Suyin HD WebCam                                                | 1         | 0.8%    |
| Suyin Asus Integrated Webcam                                   | 1         | 0.8%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.8%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.8%    |
| Sunplus MTD camera                                             | 1         | 0.8%    |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.8%    |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.8%    |
| Sunplus HP TrueVision HD Camera                                | 1         | 0.8%    |
| Sunplus HD WebCam                                              | 1         | 0.8%    |
| Sunplus Asus Webcam                                            | 1         | 0.8%    |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.8%    |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.8%    |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.8%    |
| Samsung Galaxy A5 (MTP)                                        | 1         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 40%     |
| Shenzhen Goodix Technology | 3         | 20%     |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 6.67%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.67%   |

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
| 0     | 104       | 75.91%  |
| 1     | 31        | 22.63%  |
| 2     | 2         | 1.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 40%     |
| Net/wireless          | 6         | 17.14%  |
| Multimedia controller | 5         | 14.29%  |
| Graphics card         | 4         | 11.43%  |
| Chipcard              | 2         | 5.71%   |
| Bluetooth             | 2         | 5.71%   |
| Storage               | 1         | 2.86%   |
| Modem                 | 1         | 2.86%   |


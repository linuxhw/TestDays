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

Total: 196

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 25        | 16.89%  |
| Ubuntu 18.04                 | 19        | 12.84%  |
| OpenMandriva 4.2             | 6         | 4.05%   |
| KDE neon 20.04               | 6         | 4.05%   |
| Ubuntu 22.04                 | 5         | 3.38%   |
| OpenMandriva 4.3             | 5         | 3.38%   |
| Manjaro                      | 5         | 3.38%   |
| Zorin 16                     | 3         | 2.03%   |
| Ubuntu 21.10                 | 3         | 2.03%   |
| Ubuntu 19.04                 | 3         | 2.03%   |
| Linux Mint 19.3              | 3         | 2.03%   |
| Fedora 36                    | 3         | 2.03%   |
| Arch Rolling                 | 3         | 2.03%   |
| Xubuntu 18.04                | 2         | 1.35%   |
| Ubuntu 21.04                 | 2         | 1.35%   |
| Ubuntu 18.10                 | 2         | 1.35%   |
| OpenMandriva 23.01           | 2         | 1.35%   |
| Linux Mint 20.1              | 2         | 1.35%   |
| Linux Mint 19.1              | 2         | 1.35%   |
| Kubuntu 18.04                | 2         | 1.35%   |
| Debian 11                    | 2         | 1.35%   |
| Zorin 15                     | 1         | 0.68%   |
| Xubuntu 20.04                | 1         | 0.68%   |
| Ubuntu MATE 20.04            | 1         | 0.68%   |
| Ubuntu 20.10                 | 1         | 0.68%   |
| Ubuntu 19.10                 | 1         | 0.68%   |
| Ubuntu 17.10                 | 1         | 0.68%   |
| SteamOS 3.4.4                | 1         | 0.68%   |
| ROSA R11.1                   | 1         | 0.68%   |
| Pop!_OS 22.04                | 1         | 0.68%   |
| openSUSE Leap-15.1           | 1         | 0.68%   |
| OpenMandriva 4.50            | 1         | 0.68%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.68%   |
| MX 21                        | 1         | 0.68%   |
| Manjaro 21.2.0               | 1         | 0.68%   |
| Lubuntu 20.04                | 1         | 0.68%   |
| Lubuntu 19.10                | 1         | 0.68%   |
| Linux Mint 21.1              | 1         | 0.68%   |
| Linux Mint 21                | 1         | 0.68%   |
| Linux Mint 20.3              | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 60        | 41.67%  |
| OpenMandriva | 14        | 9.72%   |
| Linux Mint   | 14        | 9.72%   |
| Manjaro      | 6         | 4.17%   |
| KDE neon     | 6         | 4.17%   |
| Fedora       | 6         | 4.17%   |
| Zorin        | 4         | 2.78%   |
| Kubuntu      | 4         | 2.78%   |
| Endless      | 4         | 2.78%   |
| Xubuntu      | 3         | 2.08%   |
| Arch         | 3         | 2.08%   |
| Lubuntu      | 2         | 1.39%   |
| Elementary   | 2         | 1.39%   |
| Debian       | 2         | 1.39%   |
| ArcoLinux    | 2         | 1.39%   |
| Ubuntu MATE  | 1         | 0.69%   |
| SteamOS      | 1         | 0.69%   |
| ROSA         | 1         | 0.69%   |
| Pop!_OS      | 1         | 0.69%   |
| openSUSE     | 1         | 0.69%   |
| NixOS        | 1         | 0.69%   |
| MX           | 1         | 0.69%   |
| Gentoo       | 1         | 0.69%   |
| Feren OS     | 1         | 0.69%   |
| EndeavourOS  | 1         | 0.69%   |
| BlackPanther | 1         | 0.69%   |
| antiX        | 1         | 0.69%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 6         | 3.77%   |
| 4.16.18-pa2-2bp1         | 6         | 3.77%   |
| 4.16.18-pa2-1bp5         | 5         | 3.14%   |
| 5.8.0-53-generic         | 4         | 2.52%   |
| 5.5.19-bp0               | 4         | 2.52%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.52%   |
| 5.13.0-39-generic        | 4         | 2.52%   |
| 5.4.0-73-generic         | 3         | 1.89%   |
| 5.4.0-58-generic         | 3         | 1.89%   |
| 5.4.0-52-generic         | 3         | 1.89%   |
| 5.11.0-38-generic        | 3         | 1.89%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.26%   |
| 5.8.0-50-generic         | 2         | 1.26%   |
| 5.8.0-43-generic         | 2         | 1.26%   |
| 5.4.0-72-generic         | 2         | 1.26%   |
| 5.4.0-42-generic         | 2         | 1.26%   |
| 5.3.0-28-generic         | 2         | 1.26%   |
| 5.19.0-35-generic        | 2         | 1.26%   |
| 5.15.0-46-generic        | 2         | 1.26%   |
| 5.15.0-41-generic        | 2         | 1.26%   |
| 5.13.0-40-generic        | 2         | 1.26%   |
| 5.13.0-37-generic        | 2         | 1.26%   |
| 5.13.0-30-generic        | 2         | 1.26%   |
| 5.11.12-desktop-1omv4002 | 2         | 1.26%   |
| 5.0.0-13-generic         | 2         | 1.26%   |
| 4.15.0-51-generic        | 2         | 1.26%   |
| 4.15.0-20-generic        | 2         | 1.26%   |
| 4.15.0-101-generic       | 2         | 1.26%   |
| 6.1.18-200.fc37.x86_64   | 1         | 0.63%   |
| 6.1.11-76060111-generic  | 1         | 0.63%   |
| 6.0.6-arch1-1            | 1         | 0.63%   |
| 6.0.15-200.fc36.x86_64   | 1         | 0.63%   |
| 6.0.12-200.fc36.x86_64   | 1         | 0.63%   |
| 5.8.11-1-MANJARO         | 1         | 0.63%   |
| 5.8.1-3-MANJARO          | 1         | 0.63%   |
| 5.8.0-49-generic         | 1         | 0.63%   |
| 5.8.0-48-generic         | 1         | 0.63%   |
| 5.8.0-44-generic         | 1         | 0.63%   |
| 5.8.0-34-generic         | 1         | 0.63%   |
| 5.6.8-1-MANJARO          | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 14.29%  |
| 5.8.0   | 12        | 7.79%   |
| 5.13.0  | 12        | 7.79%   |
| 4.16.18 | 11        | 7.14%   |
| 4.15.0  | 9         | 5.84%   |
| 5.15.0  | 7         | 4.55%   |
| 5.11.0  | 6         | 3.9%    |
| 5.10.14 | 6         | 3.9%    |
| 5.0.0   | 6         | 3.9%    |
| 5.3.0   | 5         | 3.25%   |
| 5.5.19  | 4         | 2.6%    |
| 5.16.7  | 4         | 2.6%    |
| 4.18.0  | 4         | 2.6%    |
| 5.19.0  | 3         | 1.95%   |
| 5.10.0  | 3         | 1.95%   |
| 6.1.1   | 2         | 1.3%    |
| 5.19.12 | 2         | 1.3%    |
| 5.11.12 | 2         | 1.3%    |
| 6.1.18  | 1         | 0.65%   |
| 6.1.11  | 1         | 0.65%   |
| 6.0.6   | 1         | 0.65%   |
| 6.0.15  | 1         | 0.65%   |
| 6.0.12  | 1         | 0.65%   |
| 5.8.11  | 1         | 0.65%   |
| 5.8.1   | 1         | 0.65%   |
| 5.6.8   | 1         | 0.65%   |
| 5.4.60  | 1         | 0.65%   |
| 5.4.32  | 1         | 0.65%   |
| 5.2.13  | 1         | 0.65%   |
| 5.18.18 | 1         | 0.65%   |
| 5.18.13 | 1         | 0.65%   |
| 5.17.5  | 1         | 0.65%   |
| 5.17.4  | 1         | 0.65%   |
| 5.17.0  | 1         | 0.65%   |
| 5.16.16 | 1         | 0.65%   |
| 5.16.13 | 1         | 0.65%   |
| 5.16.12 | 1         | 0.65%   |
| 5.16.0  | 1         | 0.65%   |
| 5.15.65 | 1         | 0.65%   |
| 5.15.3  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 15.69%  |
| 5.8     | 14        | 9.15%   |
| 5.13    | 12        | 7.84%   |
| 5.10    | 12        | 7.84%   |
| 4.16    | 12        | 7.84%   |
| 5.11    | 10        | 6.54%   |
| 5.15    | 9         | 5.88%   |
| 4.15    | 9         | 5.88%   |
| 5.16    | 8         | 5.23%   |
| 5.0     | 6         | 3.92%   |
| 5.3     | 5         | 3.27%   |
| 5.19    | 5         | 3.27%   |
| 4.18    | 5         | 3.27%   |
| 6.1     | 4         | 2.61%   |
| 5.5     | 4         | 2.61%   |
| 5.17    | 3         | 1.96%   |
| 6.0     | 2         | 1.31%   |
| 5.18    | 2         | 1.31%   |
| 5.6     | 1         | 0.65%   |
| 5.2     | 1         | 0.65%   |
| 5.14    | 1         | 0.65%   |
| 4.9     | 1         | 0.65%   |
| 4.17    | 1         | 0.65%   |
| 4.13    | 1         | 0.65%   |
| 4.12    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 98.57%  |
| i686   | 2         | 1.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 45        | 31.47%  |
| KDE5            | 27        | 18.88%  |
| Unknown         | 22        | 15.38%  |
| GNOME Flashback | 13        | 9.09%   |
| XFCE            | 11        | 7.69%   |
| X-Cinnamon      | 9         | 6.29%   |
| KDE             | 5         | 3.5%    |
| MATE            | 3         | 2.1%    |
| LXQt            | 3         | 2.1%    |
| Pantheon        | 2         | 1.4%    |
| Cinnamon        | 2         | 1.4%    |
| sway            | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 113       | 80.71%  |
| Wayland | 17        | 12.14%  |
| Unknown | 9         | 6.43%   |
| Tty     | 1         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 48.59%  |
| SDDM    | 26        | 18.31%  |
| GDM     | 22        | 15.49%  |
| GDM3    | 11        | 7.75%   |
| LightDM | 9         | 6.34%   |
| TDM     | 3         | 2.11%   |
| XDM     | 1         | 0.7%    |
| GREETD  | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_UY   | 73        | 50.34%  |
| en_US   | 30        | 20.69%  |
| Unknown | 18        | 12.41%  |
| es_ES   | 16        | 11.03%  |
| es_MX   | 3         | 2.07%   |
| es_AR   | 2         | 1.38%   |
| pt_BR   | 1         | 0.69%   |
| en_CA   | 1         | 0.69%   |
| C       | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 53.85%  |
| BIOS | 66        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 118       | 83.1%   |
| Overlay | 13        | 9.15%   |
| Btrfs   | 6         | 4.23%   |
| Unknown | 4         | 2.82%   |
| Ext3    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 58.45%  |
| GPT     | 42        | 29.58%  |
| MBR     | 17        | 11.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 81.43%  |
| Yes       | 26        | 18.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 75.18%  |
| Yes       | 35        | 24.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 28        | 20%     |
| Lenovo              | 23        | 16.43%  |
| ECS                 | 16        | 11.43%  |
| Dell                | 14        | 10%     |
| Acer                | 12        | 8.57%   |
| ASUSTek Computer    | 11        | 7.86%   |
| Toshiba             | 9         | 6.43%   |
| Standard            | 4         | 2.86%   |
| Samsung Electronics | 4         | 2.86%   |
| MSI                 | 4         | 2.86%   |
| GPU Company         | 2         | 1.43%   |
| Gateway             | 2         | 1.43%   |
| Apple               | 2         | 1.43%   |
| Valve               | 1         | 0.71%   |
| Sony                | 1         | 0.71%   |
| Positivo            | 1         | 0.71%   |
| Panasonic           | 1         | 0.71%   |
| OEM                 | 1         | 0.71%   |
| iClever             | 1         | 0.71%   |
| Haitech             | 1         | 0.71%   |
| Alienware           | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 16        | 11.43%  |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.14%   |
| Toshiba Satellite L55t-B              | 2         | 1.43%   |
| Standard SF20BA2                      | 2         | 1.43%   |
| HP Pavilion 15                        | 2         | 1.43%   |
| HP Laptop 15-bs0xx                    | 2         | 1.43%   |
| Valve Jupiter                         | 1         | 0.71%   |
| Toshiba Satellite L45-B               | 1         | 0.71%   |
| Toshiba Satellite C855                | 1         | 0.71%   |
| Toshiba Satellite C75D-C              | 1         | 0.71%   |
| Toshiba Satellite C75D-B              | 1         | 0.71%   |
| Toshiba Satellite C645D               | 1         | 0.71%   |
| Toshiba Satellite C55-B               | 1         | 0.71%   |
| Toshiba Satellite C45-A               | 1         | 0.71%   |
| Standard SF20BA                       | 1         | 0.71%   |
| Standard EF20EA                       | 1         | 0.71%   |
| Sony SVF14211CLB                      | 1         | 0.71%   |
| Samsung NC208/NC108                   | 1         | 0.71%   |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.71%   |
| Samsung 700T                          | 1         | 0.71%   |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.71%   |
| Positivo Serie AT300                  | 1         | 0.71%   |
| Panasonic CF-31JEGAX1M                | 1         | 0.71%   |
| OEM V40SI2                            | 1         | 0.71%   |
| MSI GS63VR 6RF                        | 1         | 0.71%   |
| MSI GL65 Leopard 10SCXR               | 1         | 0.71%   |
| MSI GL63 8RD                          | 1         | 0.71%   |
| MSI GE62 6QD                          | 1         | 0.71%   |
| Lenovo V15-ADA 82C7                   | 1         | 0.71%   |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.71%   |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.71%   |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.71%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.71%   |
| Lenovo ThinkPad P50 20EQS14H00        | 1         | 0.71%   |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.71%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.71%   |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.71%   |
| Lenovo ThinkPad Edge E531 68852BS     | 1         | 0.71%   |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.71%   |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 16        | 11.43%  |
| Lenovo ThinkPad        | 10        | 7.14%   |
| Toshiba Satellite      | 9         | 6.43%   |
| Acer Aspire            | 9         | 6.43%   |
| HP Laptop              | 8         | 5.71%   |
| HP Pavilion            | 7         | 5%      |
| Dell Inspiron          | 7         | 5%      |
| Lenovo IdeaPad         | 6         | 4.29%   |
| Dell Latitude          | 4         | 2.86%   |
| ASUS ROG               | 4         | 2.86%   |
| Standard SF20BA2       | 2         | 1.43%   |
| HP EliteBook           | 2         | 1.43%   |
| Dell XPS               | 2         | 1.43%   |
| ASUS VivoBook          | 2         | 1.43%   |
| Acer TravelMate        | 2         | 1.43%   |
| Valve Jupiter          | 1         | 0.71%   |
| Standard SF20BA        | 1         | 0.71%   |
| Standard EF20EA        | 1         | 0.71%   |
| Sony SVF14211CLB       | 1         | 0.71%   |
| Samsung NC208          | 1         | 0.71%   |
| Samsung N102SP         | 1         | 0.71%   |
| Samsung 700T           | 1         | 0.71%   |
| Samsung 300E4C         | 1         | 0.71%   |
| Positivo Serie         | 1         | 0.71%   |
| Panasonic CF-31JEGAX1M | 1         | 0.71%   |
| OEM V40SI2             | 1         | 0.71%   |
| MSI GS63VR             | 1         | 0.71%   |
| MSI GL65               | 1         | 0.71%   |
| MSI GL63               | 1         | 0.71%   |
| MSI GE62               | 1         | 0.71%   |
| Lenovo V15-ADA         | 1         | 0.71%   |
| Lenovo ThinkBook       | 1         | 0.71%   |
| Lenovo G50-70          | 1         | 0.71%   |
| Lenovo G405            | 1         | 0.71%   |
| Lenovo B51-30          | 1         | 0.71%   |
| Lenovo B50-45          | 1         | 0.71%   |
| Lenovo 14w             | 1         | 0.71%   |
| iClever IC-T01         | 1         | 0.71%   |
| HP ZBook               | 1         | 0.71%   |
| HP Stream              | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 25        | 17.86%  |
| 2019 | 14        | 10%     |
| 2013 | 14        | 10%     |
| 2020 | 13        | 9.29%   |
| 2014 | 12        | 8.57%   |
| 2018 | 11        | 7.86%   |
| 2016 | 10        | 7.14%   |
| 2015 | 10        | 7.14%   |
| 2011 | 10        | 7.14%   |
| 2012 | 7         | 5%      |
| 2010 | 4         | 2.86%   |
| 2008 | 3         | 2.14%   |
| 2007 | 3         | 2.14%   |
| 2021 | 2         | 1.43%   |
| 2022 | 1         | 0.71%   |
| 2009 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 127       | 90.07%  |
| Enabled  | 14        | 9.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 140       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 26.06%  |
| 4.01-8.0    | 34        | 23.94%  |
| 1.01-2.0    | 25        | 17.61%  |
| 8.01-16.0   | 21        | 14.79%  |
| 16.01-24.0  | 12        | 8.45%   |
| 32.01-64.0  | 7         | 4.93%   |
| 24.01-32.0  | 3         | 2.11%   |
| 2.01-3.0    | 1         | 0.7%    |
| 64.01-256.0 | 1         | 0.7%    |
| 0.01-0.5    | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 68        | 44.74%  |
| 2.01-3.0  | 33        | 21.71%  |
| 4.01-8.0  | 17        | 11.18%  |
| 3.01-4.0  | 15        | 9.87%   |
| 0.51-1.0  | 12        | 7.89%   |
| 8.01-16.0 | 5         | 3.29%   |
| 0.01-0.5  | 2         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 80.71%  |
| 2      | 26        | 18.57%  |
| 0      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 66.67%  |
| Yes       | 47        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 65.71%  |
| No        | 48        | 34.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 97.86%  |
| No        | 3         | 2.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 80%     |
| No        | 28        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 140       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 98        | 65.77%  |
| Maldonado              | 8         | 5.37%   |
| Canelones              | 8         | 5.37%   |
| Las Piedras            | 4         | 2.68%   |
| Punta del Este         | 3         | 2.01%   |
| Buceo                  | 3         | 2.01%   |
| Salto                  | 2         | 1.34%   |
| Rocha                  | 2         | 1.34%   |
| Punta Gorda            | 2         | 1.34%   |
| Ciudad del Plata       | 2         | 1.34%   |
| Solymar                | 1         | 0.67%   |
| San Jose de Mayo       | 1         | 0.67%   |
| Pocitos                | 1         | 0.67%   |
| Pinamar                | 1         | 0.67%   |
| Paysandú              | 1         | 0.67%   |
| Parque Rodo            | 1         | 0.67%   |
| Nueva Helvecia         | 1         | 0.67%   |
| Melilla                | 1         | 0.67%   |
| Maronas                | 1         | 0.67%   |
| Las Flores             | 1         | 0.67%   |
| La Paz                 | 1         | 0.67%   |
| Joaquin Suarez         | 1         | 0.67%   |
| El Tesoro              | 1         | 0.67%   |
| El Pinar               | 1         | 0.67%   |
| Durazno                | 1         | 0.67%   |
| Barrancas Coloradas    | 1         | 0.67%   |
| Arenas de Jose Ignacio | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 24        | 28     | 15.29%  |
| Unknown                     | 23        | 29     | 14.65%  |
| Toshiba                     | 20        | 23     | 12.74%  |
| Kingston                    | 18        | 25     | 11.46%  |
| Seagate                     | 16        | 19     | 10.19%  |
| SanDisk                     | 11        | 13     | 7.01%   |
| Samsung Electronics         | 9         | 9      | 5.73%   |
| Hitachi                     | 6         | 8      | 3.82%   |
| SK hynix                    | 5         | 5      | 3.18%   |
| HGST                        | 5         | 5      | 3.18%   |
| Intel                       | 4         | 4      | 2.55%   |
| Hewlett-Packard             | 3         | 3      | 1.91%   |
| Kingston Technology Company | 2         | 2      | 1.27%   |
| Crucial                     | 2         | 3      | 1.27%   |
| W800SH                      | 1         | 1      | 0.64%   |
| Netac                       | 1         | 1      | 0.64%   |
| LITEON                      | 1         | 2      | 0.64%   |
| KIOXIA                      | 1         | 1      | 0.64%   |
| Dahua                       | 1         | 1      | 0.64%   |
| China                       | 1         | 1      | 0.64%   |
| BIWIN                       | 1         | 1      | 0.64%   |
| BHT                         | 1         | 1      | 0.64%   |
| Apple                       | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 11        | 6.83%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 4.35%   |
| Unknown DA4032  32GB                 | 5         | 3.11%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 3.11%   |
| Toshiba MQ01ABD075 752GB             | 4         | 2.48%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 2.48%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.86%   |
| SanDisk DF4032  32GB                 | 3         | 1.86%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 2         | 1.24%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 2         | 1.24%   |
| Unknown SD/MMC/MS PRO 64GB           | 2         | 1.24%   |
| Toshiba HDWK105 500GB                | 2         | 1.24%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 1.24%   |
| SanDisk NVMe SSD Drive 1024GB        | 2         | 1.24%   |
| WDC WDS250G2X0C-00L350 250GB         | 1         | 0.62%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.62%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.62%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.62%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.62%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.62%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.62%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.62%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.62%   |
| WDC WD3200LPCX-24C6HT0 320GB         | 1         | 0.62%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 1         | 0.62%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.62%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.62%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.62%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.62%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.62%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.62%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.62%   |
| W800SH 512GB SSD                     | 1         | 0.62%   |
| Unknown SD64G  64GB                  | 1         | 0.62%   |
| Unknown SD16G  32GB                  | 1         | 0.62%   |
| Unknown NCard  32GB                  | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 18        | 22     | 28.57%  |
| Toshiba | 16        | 19     | 25.4%   |
| Seagate | 16        | 19     | 25.4%   |
| Hitachi | 6         | 8      | 9.52%   |
| HGST    | 5         | 5      | 7.94%   |
| Unknown | 2         | 2      | 3.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 19     | 36.59%  |
| Samsung Electronics | 5         | 5      | 12.2%   |
| WDC                 | 3         | 3      | 7.32%   |
| SanDisk             | 3         | 3      | 7.32%   |
| Hewlett-Packard     | 3         | 3      | 7.32%   |
| SK hynix            | 2         | 2      | 4.88%   |
| Intel               | 2         | 2      | 4.88%   |
| W800SH              | 1         | 1      | 2.44%   |
| Toshiba             | 1         | 1      | 2.44%   |
| Netac               | 1         | 1      | 2.44%   |
| Dahua               | 1         | 1      | 2.44%   |
| Crucial             | 1         | 2      | 2.44%   |
| China               | 1         | 1      | 2.44%   |
| BIWIN               | 1         | 1      | 2.44%   |
| BHT                 | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 75     | 39.87%  |
| SSD  | 40        | 46     | 26.14%  |
| NVMe | 27        | 33     | 17.65%  |
| MMC  | 25        | 32     | 16.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 118    | 62.59%  |
| NVMe | 27        | 33     | 18.37%  |
| MMC  | 25        | 32     | 17.01%  |
| SAS  | 3         | 3      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 82     | 68.69%  |
| 0.51-1.0   | 29        | 37     | 29.29%  |
| 1.01-2.0   | 2         | 2      | 2.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 35        | 24.14%  |
| 101-250        | 32        | 22.07%  |
| 21-50          | 21        | 14.48%  |
| 501-1000       | 21        | 14.48%  |
| 1-20           | 18        | 12.41%  |
| 51-100         | 9         | 6.21%   |
| 1001-2000      | 5         | 3.45%   |
| Unknown        | 3         | 2.07%   |
| More than 3000 | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 74        | 48.37%  |
| 21-50          | 28        | 18.3%   |
| 51-100         | 15        | 9.8%    |
| 251-500        | 14        | 9.15%   |
| 101-250        | 12        | 7.84%   |
| 501-1000       | 5         | 3.27%   |
| Unknown        | 3         | 1.96%   |
| More than 3000 | 1         | 0.65%   |
| 1001-2000      | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 2      | 15.38%  |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 7.69%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 7.69%   |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 7.69%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 7.69%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 7.69%   |
| Seagate ST980811AS 80GB             | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 7.69%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 7.69%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 7.69%   |
| HGST HTS545032A7E380 320GB          | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 30.77%  |
| Toshiba | 3         | 4      | 23.08%  |
| Seagate | 3         | 3      | 23.08%  |
| SanDisk | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 33.33%  |
| Toshiba | 3         | 4      | 25%     |
| Seagate | 3         | 3      | 25%     |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 92.31%  |
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
| Detected | 88        | 118    | 61.97%  |
| Works    | 41        | 54     | 28.87%  |
| Malfunc  | 13        | 14     | 9.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 96        | 64.86%  |
| AMD                              | 26        | 17.57%  |
| SanDisk                          | 8         | 5.41%   |
| Toshiba America Info Systems     | 4         | 2.7%    |
| Samsung Electronics              | 4         | 2.7%    |
| Kingston Technology Company      | 4         | 2.7%    |
| SK hynix                         | 2         | 1.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Micron/Crucial Technology        | 1         | 0.68%   |
| Lite-On Technology               | 1         | 0.68%   |
| Apple                            | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 14.84%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 10.97%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 3.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 2.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.29%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.29%   |
| Intel SSD 660P Series                                                            | 2         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.29%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.29%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.65%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.65%   |
| SanDisk NVMe Controller                                                          | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.65%   |
| Lite-On NVMe Controller                                                          | 1         | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 73.68%  |
| NVMe | 27        | 17.76%  |
| IDE  | 7         | 4.61%   |
| RAID | 6         | 3.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 109       | 77.86%  |
| AMD    | 31        | 22.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 12.14%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.14%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.14%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 2.14%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.43%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 1.43%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.43%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.43%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.43%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.43%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.43%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 2         | 1.43%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.43%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.43%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.43%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.71%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.71%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.71%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.71%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.71%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.71%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.71%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.71%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 30        | 21.43%  |
| Intel Core i5      | 26        | 18.57%  |
| Intel Core i7      | 23        | 16.43%  |
| Intel Core i3      | 11        | 7.86%   |
| Intel Pentium      | 7         | 5%      |
| Other              | 5         | 3.57%   |
| Intel Atom         | 5         | 3.57%   |
| AMD A6             | 5         | 3.57%   |
| AMD Ryzen 9        | 4         | 2.86%   |
| AMD E              | 3         | 2.14%   |
| Intel Genuine      | 2         | 1.43%   |
| Intel Core 2 Duo   | 2         | 1.43%   |
| AMD Ryzen 7        | 2         | 1.43%   |
| AMD Ryzen 5        | 2         | 1.43%   |
| AMD Ryzen 3        | 2         | 1.43%   |
| AMD E1             | 2         | 1.43%   |
| Intel Pentium Dual | 1         | 0.71%   |
| AMD Phenom II      | 1         | 0.71%   |
| AMD FX             | 1         | 0.71%   |
| AMD E2             | 1         | 0.71%   |
| AMD Athlon II      | 1         | 0.71%   |
| AMD Athlon         | 1         | 0.71%   |
| AMD A8             | 1         | 0.71%   |
| AMD A4             | 1         | 0.71%   |
| AMD A10            | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 61.43%  |
| 4      | 40        | 28.57%  |
| 8      | 5         | 3.57%   |
| 6      | 5         | 3.57%   |
| 1      | 4         | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 77        | 55%     |
| 1      | 63        | 45%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 97.86%  |
| Unknown        | 3         | 2.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 20.83%  |
| 0x406c4    | 7         | 4.86%   |
| 0x206a7    | 7         | 4.86%   |
| 0x506c9    | 6         | 4.17%   |
| 0x40651    | 6         | 4.17%   |
| 0x806ec    | 5         | 3.47%   |
| 0x406e3    | 5         | 3.47%   |
| 0x306d4    | 5         | 3.47%   |
| 0x20655    | 5         | 3.47%   |
| 0x806ea    | 4         | 2.78%   |
| 0x30678    | 4         | 2.78%   |
| 0x906ea    | 3         | 2.08%   |
| 0x806e9    | 3         | 2.08%   |
| 0x6fd      | 3         | 2.08%   |
| 0x306c3    | 3         | 2.08%   |
| 0x306a9    | 3         | 2.08%   |
| 0x08108109 | 3         | 2.08%   |
| 0x06006705 | 3         | 2.08%   |
| 0x806c1    | 2         | 1.39%   |
| 0x706e5    | 2         | 1.39%   |
| 0x506e3    | 2         | 1.39%   |
| 0x406c3    | 2         | 1.39%   |
| 0x08600104 | 2         | 1.39%   |
| 0x0810100b | 2         | 1.39%   |
| 0x07030105 | 2         | 1.39%   |
| 0x07030104 | 2         | 1.39%   |
| 0x0700010f | 2         | 1.39%   |
| 0xa0652    | 1         | 0.69%   |
| 0x806eb    | 1         | 0.69%   |
| 0x706a1    | 1         | 0.69%   |
| 0x30673    | 1         | 0.69%   |
| 0x30661    | 1         | 0.69%   |
| 0x106e5    | 1         | 0.69%   |
| 0x106ca    | 1         | 0.69%   |
| 0x1067a    | 1         | 0.69%   |
| 0x10676    | 1         | 0.69%   |
| 0x10661    | 1         | 0.69%   |
| 0x0a50000c | 1         | 0.69%   |
| 0x08600102 | 1         | 0.69%   |
| 0x07030106 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 12.14%  |
| Goldmont      | 17        | 12.14%  |
| Silvermont    | 16        | 11.43%  |
| Haswell       | 10        | 7.14%   |
| Skylake       | 9         | 6.43%   |
| SandyBridge   | 7         | 5%      |
| IvyBridge     | 6         | 4.29%   |
| Excavator     | 6         | 4.29%   |
| Broadwell     | 6         | 4.29%   |
| Westmere      | 5         | 3.57%   |
| Puma          | 5         | 3.57%   |
| Zen+          | 4         | 2.86%   |
| Zen 2         | 4         | 2.86%   |
| Core          | 4         | 2.86%   |
| Bobcat        | 3         | 2.14%   |
| Zen           | 2         | 1.43%   |
| TigerLake     | 2         | 1.43%   |
| Penryn        | 2         | 1.43%   |
| K10           | 2         | 1.43%   |
| Jaguar        | 2         | 1.43%   |
| IceLake       | 2         | 1.43%   |
| CometLake     | 2         | 1.43%   |
| Bonnell       | 2         | 1.43%   |
| Zen 3         | 1         | 0.71%   |
| Piledriver    | 1         | 0.71%   |
| Nehalem       | 1         | 0.71%   |
| Goldmont plus | 1         | 0.71%   |
| Unknown       | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 107       | 65.24%  |
| AMD                              | 39        | 23.78%  |
| Nvidia                           | 17        | 10.37%  |
| Silicon Integrated Systems [SiS] | 1         | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 10.06%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 6.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.96%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.37%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.37%   |
| Intel HD Graphics 530                                                                    | 4         | 2.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.37%   |
| AMD Renoir                                                                               | 4         | 2.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.37%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.78%   |
| Intel HD Graphics 620                                                                    | 3         | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.78%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.18%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.18%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.18%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.59%   |
| Nvidia TU117M                                                                            | 1         | 0.59%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.59%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 62.86%  |
| 1 x AMD        | 24        | 17.14%  |
| Intel + Nvidia | 11        | 7.86%   |
| Intel + AMD    | 8         | 5.71%   |
| AMD + Nvidia   | 5         | 3.57%   |
| 2 x AMD        | 2         | 1.43%   |
| 1 x SiS        | 1         | 0.71%   |
| 1 x Nvidia     | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 127       | 90.71%  |
| Proprietary | 11        | 7.86%   |
| Unknown     | 2         | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 70.42%  |
| 0.01-0.5   | 15        | 10.56%  |
| 0.51-1.0   | 11        | 7.75%   |
| 1.01-2.0   | 9         | 6.34%   |
| 3.01-4.0   | 5         | 3.52%   |
| 5.01-6.0   | 2         | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 25        | 16.78%  |
| Chimei Innolux          | 22        | 14.77%  |
| AU Optronics            | 21        | 14.09%  |
| BOE                     | 18        | 12.08%  |
| Samsung Electronics     | 14        | 9.4%    |
| InfoVision              | 7         | 4.7%    |
| KDC                     | 6         | 4.03%   |
| Sharp                   | 4         | 2.68%   |
| PANDA                   | 4         | 2.68%   |
| Chi Mei Optoelectronics | 4         | 2.68%   |
| ViewSonic               | 3         | 2.01%   |
| Acer                    | 3         | 2.01%   |
| LG Philips              | 2         | 1.34%   |
| KTC                     | 2         | 1.34%   |
| HSI                     | 2         | 1.34%   |
| Dell                    | 2         | 1.34%   |
| Apple                   | 2         | 1.34%   |
| Valve                   | 1         | 0.67%   |
| Sun                     | 1         | 0.67%   |
| JDI                     | 1         | 0.67%   |
| InnoLux Display         | 1         | 0.67%   |
| HKC                     | 1         | 0.67%   |
| Hewlett-Packard         | 1         | 0.67%   |
| CPT                     | 1         | 0.67%   |
| AOC                     | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch          | 6         | 3.97%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 4         | 2.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 1.99%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.32%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.32%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 1.32%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.32%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 2         | 1.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.32%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.32%   |
| HSI LED-TV HSI0001 1920x1080 708x398mm 32.0-inch                      | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 2         | 1.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.32%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch         | 1         | 0.66%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.66%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.66%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.66%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.66%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.66%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.66%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 74        | 54.41%  |
| 1920x1080 (FHD)   | 36        | 26.47%  |
| 1600x900 (HD+)    | 7         | 5.15%   |
| 1920x1200 (WUXGA) | 6         | 4.41%   |
| 1280x800 (WXGA)   | 4         | 2.94%   |
| 3840x2160 (4K)    | 3         | 2.21%   |
| 2560x1440 (QHD)   | 2         | 1.47%   |
| 800x1280          | 1         | 0.74%   |
| 2288x1287         | 1         | 0.74%   |
| 1360x768          | 1         | 0.74%   |
| 1024x600          | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 69        | 46.31%  |
| 13     | 24        | 16.11%  |
| 14     | 20        | 13.42%  |
| 17     | 6         | 4.03%   |
| 11     | 6         | 4.03%   |
| 24     | 4         | 2.68%   |
| 23     | 4         | 2.68%   |
| 21     | 3         | 2.01%   |
| 40     | 2         | 1.34%   |
| 34     | 2         | 1.34%   |
| 18     | 2         | 1.34%   |
| 12     | 2         | 1.34%   |
| 10     | 2         | 1.34%   |
| 57     | 1         | 0.67%   |
| 27     | 1         | 0.67%   |
| 7      | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 70.95%  |
| 201-300     | 16        | 10.81%  |
| 501-600     | 9         | 6.08%   |
| 351-400     | 7         | 4.73%   |
| 401-500     | 5         | 3.38%   |
| 801-900     | 2         | 1.35%   |
| 701-800     | 2         | 1.35%   |
| 1001-1500   | 1         | 0.68%   |
| 1-100       | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 121       | 93.08%  |
| 16/10 | 6         | 4.62%   |
| 21/9  | 2         | 1.54%   |
| 0.67  | 1         | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 46.31%  |
| 81-90          | 39        | 26.17%  |
| 201-250        | 9         | 6.04%   |
| 51-60          | 6         | 4.03%   |
| 121-130        | 6         | 4.03%   |
| 71-80          | 5         | 3.36%   |
| 61-70          | 2         | 1.34%   |
| 351-500        | 2         | 1.34%   |
| 41-50          | 2         | 1.34%   |
| 151-200        | 2         | 1.34%   |
| 141-150        | 2         | 1.34%   |
| 501-1000       | 2         | 1.34%   |
| More than 1000 | 1         | 0.67%   |
| 1-40           | 1         | 0.67%   |
| 301-350        | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 77        | 52.38%  |
| 121-160       | 38        | 25.85%  |
| 51-100        | 25        | 17.01%  |
| 161-240       | 5         | 3.4%    |
| More than 240 | 1         | 0.68%   |
| 1-50          | 1         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 119       | 83.22%  |
| 2     | 20        | 13.99%  |
| 3     | 2         | 1.4%    |
| 0     | 2         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 68        | 32.38%  |
| Intel                            | 65        | 30.95%  |
| Qualcomm Atheros                 | 35        | 16.67%  |
| Broadcom                         | 18        | 8.57%   |
| Ralink Technology                | 3         | 1.43%   |
| Ralink                           | 3         | 1.43%   |
| MediaTek                         | 3         | 1.43%   |
| TP-Link                          | 2         | 0.95%   |
| Broadcom Limited                 | 2         | 0.95%   |
| Xiaomi                           | 1         | 0.48%   |
| T & A Mobile Phones              | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Sierra Wireless                  | 1         | 0.48%   |
| Samsung Electronics              | 1         | 0.48%   |
| Qualcomm Atheros Communications  | 1         | 0.48%   |
| Marvell Technology Group         | 1         | 0.48%   |
| Lenovo                           | 1         | 0.48%   |
| Huawei Technologies              | 1         | 0.48%   |
| DisplayLink                      | 1         | 0.48%   |
| ASIX Electronics                 | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 34        | 13.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 23        | 9.47%   |
| Intel Wireless 3165                                                     | 23        | 9.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.47%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.47%   |
| Intel Wireless 7265                                                     | 5         | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.65%   |
| Intel Wireless 8260                                                     | 4         | 1.65%   |
| Intel Wireless 7260                                                     | 4         | 1.65%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.65%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.82%   |
| Intel Wireless 3160                                                     | 2         | 0.82%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.82%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.82%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 44.06%  |
| Qualcomm Atheros                | 28        | 19.58%  |
| Realtek Semiconductor           | 26        | 18.18%  |
| Broadcom                        | 13        | 9.09%   |
| Ralink Technology               | 3         | 2.1%    |
| Ralink                          | 3         | 2.1%    |
| MediaTek                        | 2         | 1.4%    |
| Broadcom Limited                | 2         | 1.4%    |
| TP-Link                         | 1         | 0.7%    |
| Sierra Wireless                 | 1         | 0.7%    |
| Qualcomm Atheros Communications | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 23        | 15.97%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 4.17%   |
| Intel Wireless 7265                                                     | 5         | 3.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.78%   |
| Intel Wireless 8260                                                     | 4         | 2.78%   |
| Intel Wireless 7260                                                     | 4         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.39%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.39%   |
| Intel Wireless 3160                                                     | 2         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.39%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 60.2%   |
| Intel                            | 13        | 13.27%  |
| Qualcomm Atheros                 | 9         | 9.18%   |
| Broadcom                         | 7         | 7.14%   |
| Xiaomi                           | 1         | 1.02%   |
| TP-Link                          | 1         | 1.02%   |
| Silicon Integrated Systems [SiS] | 1         | 1.02%   |
| Samsung Electronics              | 1         | 1.02%   |
| MediaTek                         | 1         | 1.02%   |
| Marvell Technology Group         | 1         | 1.02%   |
| Lenovo                           | 1         | 1.02%   |
| Huawei Technologies              | 1         | 1.02%   |
| DisplayLink                      | 1         | 1.02%   |
| ASIX Electronics                 | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 34.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 23.47%  |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 3.06%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.04%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.04%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.02%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.02%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.02%   |
| Samsung Kiera                                                     | 1         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.02%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.02%   |
| MediaTek U318AA                                                   | 1         | 1.02%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.02%   |
| Lenovo USB-C to LAN                                               | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.02%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.02%   |
| Huawei E353/E3131                                                 | 1         | 1.02%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.02%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 59.57%  |
| Ethernet | 92        | 40%     |
| Unknown  | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 87.41%  |
| Ethernet | 18        | 12.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 62.14%  |
| 1     | 50        | 35.71%  |
| 0     | 3         | 2.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 77.14%  |
| Yes  | 32        | 22.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 48.67%  |
| Realtek Semiconductor           | 13        | 11.5%   |
| Qualcomm Atheros Communications | 11        | 9.73%   |
| IMC Networks                    | 8         | 7.08%   |
| Toshiba                         | 7         | 6.19%   |
| Lite-On Technology              | 3         | 2.65%   |
| Foxconn / Hon Hai               | 3         | 2.65%   |
| Cambridge Silicon Radio         | 3         | 2.65%   |
| Broadcom                        | 3         | 2.65%   |
| Ralink                          | 2         | 1.77%   |
| Apple                           | 2         | 1.77%   |
| Ralink Technology               | 1         | 0.88%   |
| Foxconn International           | 1         | 0.88%   |
| Alps Electric                   | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 37        | 32.74%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 7.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 5.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.31%   |
| Intel AX200 Bluetooth                               | 4         | 3.54%   |
| Toshiba Bluetooth Device                            | 3         | 2.65%   |
| Toshiba BCM43142A0                                  | 3         | 2.65%   |
| Realtek Bluetooth Radio                             | 3         | 2.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.65%   |
| Intel AX201 Bluetooth                               | 3         | 2.65%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.65%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.77%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.77%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.77%   |
| Toshiba Bluetooth Radio                             | 1         | 0.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.88%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.88%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.88%   |
| Lite-On Bluetooth Device                            | 1         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.88%   |
| IMC Networks Wireless_Device                        | 1         | 0.88%   |
| IMC Networks Bluetooth Device                       | 1         | 0.88%   |
| IMC Networks Bluetooth                              | 1         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.88%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.88%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.88%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.88%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.88%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.88%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 105       | 66.88%  |
| AMD                                  | 31        | 19.75%  |
| Nvidia                               | 11        | 7.01%   |
| Logitech                             | 4         | 2.55%   |
| Generalplus Technology               | 2         | 1.27%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.64%   |
| Texas Instruments                    | 1         | 0.64%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.64%   |
| C-Media Electronics                  | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 8.42%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5.45%   |
| AMD FCH Azalia Controller                                                                         | 10        | 4.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 4.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.97%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.97%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.98%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.49%   |
| Logitech H390 headset with microphone                                                             | 2         | 0.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.99%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.99%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.99%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.99%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.99%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                                                     | 1         | 0.5%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 29.76%  |
| SK hynix            | 15        | 17.86%  |
| Micron Technology   | 10        | 11.9%   |
| Ramaxel Technology  | 7         | 8.33%   |
| Unknown             | 5         | 5.95%   |
| Kingston            | 5         | 5.95%   |
| Goldkey             | 5         | 5.95%   |
| Crucial             | 4         | 4.76%   |
| Elpida              | 3         | 3.57%   |
| Nanya Technology    | 2         | 2.38%   |
| A-DATA Technology   | 2         | 2.38%   |
| Patriot             | 1         | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s      | 4         | 4.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 3.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 3.45%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 2         | 2.3%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 2.3%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 2         | 2.3%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 2.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.3%    |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s      | 2         | 2.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.3%    |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s        | 2         | 2.3%    |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                 | 1         | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 1         | 1.15%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1         | 1.15%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                  | 1         | 1.15%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.15%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.15%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.15%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 1         | 1.15%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                     | 1         | 1.15%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                     | 1         | 1.15%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 1         | 1.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.15%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.15%   |
| Samsung RAM M471A2G44AM0-CTD 16GB Row Of Chips DDR4 2667MT/s | 1         | 1.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 52.17%  |
| DDR4   | 25        | 36.23%  |
| DDR2   | 3         | 4.35%   |
| SDRAM  | 2         | 2.9%    |
| LPDDR3 | 2         | 2.9%    |
| LPDDR4 | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 91.04%  |
| Row Of Chips | 4         | 5.97%   |
| DIMM         | 2         | 2.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 27        | 34.62%  |
| 8192  | 21        | 26.92%  |
| 2048  | 16        | 20.51%  |
| 16384 | 9         | 11.54%  |
| 32768 | 2         | 2.56%   |
| 1024  | 2         | 2.56%   |
| 512   | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 32        | 41.03%  |
| 2667  | 14        | 17.95%  |
| 3200  | 6         | 7.69%   |
| 2400  | 6         | 7.69%   |
| 1334  | 5         | 6.41%   |
| 3266  | 3         | 3.85%   |
| 2133  | 3         | 3.85%   |
| 533   | 3         | 3.85%   |
| 4199  | 2         | 2.56%   |
| 1333  | 2         | 2.56%   |
| 1867  | 1         | 1.28%   |
| 1067  | 1         | 1.28%   |

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
| Chicony Electronics                    | 36        | 27.91%  |
| Realtek Semiconductor                  | 15        | 11.63%  |
| Cheng Uei Precision Industry (Foxlink) | 12        | 9.3%    |
| Microdia                               | 8         | 6.2%    |
| Suyin                                  | 7         | 5.43%   |
| Sunplus Innovation Technology          | 7         | 5.43%   |
| Acer                                   | 6         | 4.65%   |
| Unknown                                | 5         | 3.88%   |
| Bison Electronics                      | 5         | 3.88%   |
| Silicon Motion                         | 4         | 3.1%    |
| IMC Networks                           | 4         | 3.1%    |
| Quanta                                 | 3         | 2.33%   |
| Importek                               | 3         | 2.33%   |
| Alcor Micro                            | 3         | 2.33%   |
| Syntek                                 | 2         | 1.55%   |
| Lite-On Technology                     | 2         | 1.55%   |
| Samsung Electronics                    | 1         | 0.78%   |
| Primax Electronics                     | 1         | 0.78%   |
| Novatek Microelectronics               | 1         | 0.78%   |
| Luxvisions Innotech Limited            | 1         | 0.78%   |
| Logitech                               | 1         | 0.78%   |
| DigiTech                               | 1         | 0.78%   |
| Apple                                  | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 14        | 10.85%  |
| Realtek Integrated_Webcam_HD                                   | 6         | 4.65%   |
| Unknown USB Camera                                             | 5         | 3.88%   |
| Chicony Integrated Camera                                      | 5         | 3.88%   |
| Chicony HP Truevision HD                                       | 5         | 3.88%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 3.1%    |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 3.1%    |
| Realtek Lenovo EasyCamera                                      | 3         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 2.33%   |
| Acer Integrated Camera                                         | 3         | 2.33%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.55%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.55%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.55%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.55%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.55%   |
| Chicony HD WebCam                                              | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.55%   |
| Bison Integrated Camera                                        | 2         | 1.55%   |
| Acer HD Webcam                                                 | 2         | 1.55%   |
| Syntek Integrated Camera                                       | 1         | 0.78%   |
| Syntek EasyCamera                                              | 1         | 0.78%   |
| Suyin VGA Webcam                                               | 1         | 0.78%   |
| Suyin HP Truevision HD                                         | 1         | 0.78%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.78%   |
| Suyin HD WebCam                                                | 1         | 0.78%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.78%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.78%   |
| Sunplus MTD camera                                             | 1         | 0.78%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.78%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.78%   |
| Sunplus HP TrueVision HD Camera                                | 1         | 0.78%   |
| Sunplus HD WebCam                                              | 1         | 0.78%   |
| Sunplus Asus Webcam                                            | 1         | 0.78%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.78%   |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.78%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.78%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 43.75%  |
| Shenzhen Goodix Technology | 3         | 18.75%  |
| Upek                       | 1         | 6.25%   |
| Synaptics                  | 1         | 6.25%   |
| LighTuning Technology      | 1         | 6.25%   |
| Focal-systems.Corp         | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 18.75%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 18.75%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.25%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.25%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.25%   |

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
| 0     | 107       | 75.89%  |
| 1     | 32        | 22.7%   |
| 2     | 2         | 1.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 41.67%  |
| Net/wireless          | 6         | 16.67%  |
| Multimedia controller | 5         | 13.89%  |
| Graphics card         | 3         | 8.33%   |
| Chipcard              | 3         | 8.33%   |
| Bluetooth             | 2         | 5.56%   |
| Storage               | 1         | 2.78%   |
| Modem                 | 1         | 2.78%   |


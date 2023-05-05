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

Total: 201

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 25        | 16.56%  |
| Ubuntu 18.04                 | 20        | 13.25%  |
| OpenMandriva 4.2             | 6         | 3.97%   |
| KDE neon 20.04               | 6         | 3.97%   |
| Ubuntu 22.04                 | 5         | 3.31%   |
| OpenMandriva 4.3             | 5         | 3.31%   |
| Manjaro                      | 5         | 3.31%   |
| Arch Rolling                 | 4         | 2.65%   |
| Zorin 16                     | 3         | 1.99%   |
| Ubuntu 21.10                 | 3         | 1.99%   |
| Ubuntu 19.04                 | 3         | 1.99%   |
| Linux Mint 19.3              | 3         | 1.99%   |
| Fedora 36                    | 3         | 1.99%   |
| Xubuntu 18.04                | 2         | 1.32%   |
| Ubuntu 21.04                 | 2         | 1.32%   |
| Ubuntu 18.10                 | 2         | 1.32%   |
| OpenMandriva 23.01           | 2         | 1.32%   |
| Linux Mint 20.1              | 2         | 1.32%   |
| Linux Mint 19.1              | 2         | 1.32%   |
| Kubuntu 18.04                | 2         | 1.32%   |
| Debian 11                    | 2         | 1.32%   |
| Zorin 15                     | 1         | 0.66%   |
| Xubuntu 20.04                | 1         | 0.66%   |
| Ubuntu MATE 20.04            | 1         | 0.66%   |
| Ubuntu 20.10                 | 1         | 0.66%   |
| Ubuntu 19.10                 | 1         | 0.66%   |
| Ubuntu 17.10                 | 1         | 0.66%   |
| SteamOS 3.4.4                | 1         | 0.66%   |
| ROSA R11.1                   | 1         | 0.66%   |
| Pop!_OS 22.04                | 1         | 0.66%   |
| openSUSE Leap-15.1           | 1         | 0.66%   |
| OpenMandriva 4.50            | 1         | 0.66%   |
| OpenMandriva 23.03           | 1         | 0.66%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.66%   |
| MX 21                        | 1         | 0.66%   |
| Manjaro 21.2.0               | 1         | 0.66%   |
| Lubuntu 20.04                | 1         | 0.66%   |
| Lubuntu 19.10                | 1         | 0.66%   |
| Linux Mint 21.1              | 1         | 0.66%   |
| Linux Mint 21                | 1         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 61        | 41.5%   |
| OpenMandriva | 15        | 10.2%   |
| Linux Mint   | 14        | 9.52%   |
| Manjaro      | 6         | 4.08%   |
| KDE neon     | 6         | 4.08%   |
| Fedora       | 6         | 4.08%   |
| Zorin        | 4         | 2.72%   |
| Kubuntu      | 4         | 2.72%   |
| Endless      | 4         | 2.72%   |
| Arch         | 4         | 2.72%   |
| Xubuntu      | 3         | 2.04%   |
| Lubuntu      | 2         | 1.36%   |
| Elementary   | 2         | 1.36%   |
| Debian       | 2         | 1.36%   |
| ArcoLinux    | 2         | 1.36%   |
| Ubuntu MATE  | 1         | 0.68%   |
| SteamOS      | 1         | 0.68%   |
| ROSA         | 1         | 0.68%   |
| Pop!_OS      | 1         | 0.68%   |
| openSUSE     | 1         | 0.68%   |
| NixOS        | 1         | 0.68%   |
| MX           | 1         | 0.68%   |
| Gentoo       | 1         | 0.68%   |
| Feren OS     | 1         | 0.68%   |
| EndeavourOS  | 1         | 0.68%   |
| BlackPanther | 1         | 0.68%   |
| antiX        | 1         | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 6         | 3.68%   |
| 4.16.18-pa2-2bp1         | 6         | 3.68%   |
| 4.16.18-pa2-1bp5         | 5         | 3.07%   |
| 5.8.0-53-generic         | 4         | 2.45%   |
| 5.5.19-bp0               | 4         | 2.45%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.45%   |
| 5.13.0-39-generic        | 4         | 2.45%   |
| 5.4.0-73-generic         | 3         | 1.84%   |
| 5.4.0-58-generic         | 3         | 1.84%   |
| 5.4.0-52-generic         | 3         | 1.84%   |
| 5.11.0-38-generic        | 3         | 1.84%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.23%   |
| 5.8.0-50-generic         | 2         | 1.23%   |
| 5.8.0-43-generic         | 2         | 1.23%   |
| 5.4.0-72-generic         | 2         | 1.23%   |
| 5.4.0-42-generic         | 2         | 1.23%   |
| 5.3.0-28-generic         | 2         | 1.23%   |
| 5.19.0-35-generic        | 2         | 1.23%   |
| 5.16.13-desktop-1omv4003 | 2         | 1.23%   |
| 5.15.0-46-generic        | 2         | 1.23%   |
| 5.15.0-41-generic        | 2         | 1.23%   |
| 5.13.0-40-generic        | 2         | 1.23%   |
| 5.13.0-37-generic        | 2         | 1.23%   |
| 5.13.0-30-generic        | 2         | 1.23%   |
| 5.11.12-desktop-1omv4002 | 2         | 1.23%   |
| 5.0.0-13-generic         | 2         | 1.23%   |
| 4.15.0-51-generic        | 2         | 1.23%   |
| 4.15.0-20-generic        | 2         | 1.23%   |
| 4.15.0-101-generic       | 2         | 1.23%   |
| 6.2.6-desktop-1omv2390   | 1         | 0.61%   |
| 6.2.12-arch1-1           | 1         | 0.61%   |
| 6.1.18-200.fc37.x86_64   | 1         | 0.61%   |
| 6.1.11-76060111-generic  | 1         | 0.61%   |
| 6.0.6-arch1-1            | 1         | 0.61%   |
| 6.0.15-200.fc36.x86_64   | 1         | 0.61%   |
| 6.0.12-200.fc36.x86_64   | 1         | 0.61%   |
| 5.8.11-1-MANJARO         | 1         | 0.61%   |
| 5.8.1-3-MANJARO          | 1         | 0.61%   |
| 5.8.0-49-generic         | 1         | 0.61%   |
| 5.8.0-48-generic         | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 14.56%  |
| 5.8.0   | 12        | 7.59%   |
| 5.13.0  | 12        | 7.59%   |
| 4.16.18 | 11        | 6.96%   |
| 4.15.0  | 9         | 5.7%    |
| 5.15.0  | 7         | 4.43%   |
| 5.11.0  | 6         | 3.8%    |
| 5.10.14 | 6         | 3.8%    |
| 5.0.0   | 6         | 3.8%    |
| 5.3.0   | 5         | 3.16%   |
| 5.5.19  | 4         | 2.53%   |
| 5.16.7  | 4         | 2.53%   |
| 4.18.0  | 4         | 2.53%   |
| 5.19.0  | 3         | 1.9%    |
| 5.10.0  | 3         | 1.9%    |
| 6.1.1   | 2         | 1.27%   |
| 5.19.12 | 2         | 1.27%   |
| 5.16.13 | 2         | 1.27%   |
| 5.11.12 | 2         | 1.27%   |
| 6.2.6   | 1         | 0.63%   |
| 6.2.12  | 1         | 0.63%   |
| 6.1.18  | 1         | 0.63%   |
| 6.1.11  | 1         | 0.63%   |
| 6.0.6   | 1         | 0.63%   |
| 6.0.15  | 1         | 0.63%   |
| 6.0.12  | 1         | 0.63%   |
| 5.8.11  | 1         | 0.63%   |
| 5.8.1   | 1         | 0.63%   |
| 5.6.8   | 1         | 0.63%   |
| 5.4.60  | 1         | 0.63%   |
| 5.4.32  | 1         | 0.63%   |
| 5.2.13  | 1         | 0.63%   |
| 5.18.18 | 1         | 0.63%   |
| 5.18.13 | 1         | 0.63%   |
| 5.17.5  | 1         | 0.63%   |
| 5.17.4  | 1         | 0.63%   |
| 5.17.0  | 1         | 0.63%   |
| 5.16.16 | 1         | 0.63%   |
| 5.16.12 | 1         | 0.63%   |
| 5.16.0  | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 25        | 16.03%  |
| 5.8     | 14        | 8.97%   |
| 5.13    | 12        | 7.69%   |
| 5.10    | 12        | 7.69%   |
| 4.16    | 12        | 7.69%   |
| 5.11    | 10        | 6.41%   |
| 5.15    | 9         | 5.77%   |
| 4.15    | 9         | 5.77%   |
| 5.16    | 8         | 5.13%   |
| 5.0     | 6         | 3.85%   |
| 5.3     | 5         | 3.21%   |
| 5.19    | 5         | 3.21%   |
| 4.18    | 5         | 3.21%   |
| 6.1     | 4         | 2.56%   |
| 5.5     | 4         | 2.56%   |
| 5.17    | 3         | 1.92%   |
| 6.2     | 2         | 1.28%   |
| 6.0     | 2         | 1.28%   |
| 5.18    | 2         | 1.28%   |
| 5.6     | 1         | 0.64%   |
| 5.2     | 1         | 0.64%   |
| 5.14    | 1         | 0.64%   |
| 4.9     | 1         | 0.64%   |
| 4.17    | 1         | 0.64%   |
| 4.13    | 1         | 0.64%   |
| 4.12    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 141       | 98.6%   |
| i686   | 2         | 1.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 47        | 32.19%  |
| KDE5            | 28        | 19.18%  |
| Unknown         | 22        | 15.07%  |
| GNOME Flashback | 13        | 8.9%    |
| XFCE            | 11        | 7.53%   |
| X-Cinnamon      | 9         | 6.16%   |
| KDE             | 5         | 3.42%   |
| MATE            | 3         | 2.05%   |
| LXQt            | 3         | 2.05%   |
| Pantheon        | 2         | 1.37%   |
| Cinnamon        | 2         | 1.37%   |
| sway            | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 115       | 80.42%  |
| Wayland | 18        | 12.59%  |
| Unknown | 9         | 6.29%   |
| Tty     | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 48.28%  |
| SDDM    | 27        | 18.62%  |
| GDM     | 22        | 15.17%  |
| GDM3    | 12        | 8.28%   |
| LightDM | 9         | 6.21%   |
| TDM     | 3         | 2.07%   |
| XDM     | 1         | 0.69%   |
| GREETD  | 1         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_UY      | 75        | 50.68%  |
| en_US      | 30        | 20.27%  |
| Unknown    | 18        | 12.16%  |
| es_ES      | 16        | 10.81%  |
| es_MX      | 3         | 2.03%   |
| es_AR      | 2         | 1.35%   |
| pt_BR      | 1         | 0.68%   |
| es_UY.UTF8 | 1         | 0.68%   |
| en_CA      | 1         | 0.68%   |
| C          | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 79        | 54.11%  |
| BIOS | 67        | 45.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 120       | 82.76%  |
| Overlay | 14        | 9.66%   |
| Btrfs   | 6         | 4.14%   |
| Unknown | 4         | 2.76%   |
| Ext3    | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 57.93%  |
| GPT     | 44        | 30.34%  |
| MBR     | 17        | 11.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 81.12%  |
| Yes       | 27        | 18.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 75.69%  |
| Yes       | 35        | 24.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 29        | 20.28%  |
| Lenovo              | 23        | 16.08%  |
| ECS                 | 16        | 11.19%  |
| Dell                | 14        | 9.79%   |
| Acer                | 12        | 8.39%   |
| ASUSTek Computer    | 11        | 7.69%   |
| Toshiba             | 9         | 6.29%   |
| Standard            | 5         | 3.5%    |
| Samsung Electronics | 4         | 2.8%    |
| MSI                 | 4         | 2.8%    |
| GPU Company         | 2         | 1.4%    |
| Gateway             | 2         | 1.4%    |
| Apple               | 2         | 1.4%    |
| Valve               | 1         | 0.7%    |
| Sony                | 1         | 0.7%    |
| Positivo            | 1         | 0.7%    |
| Panasonic           | 1         | 0.7%    |
| OEM                 | 1         | 0.7%    |
| Intel               | 1         | 0.7%    |
| iClever             | 1         | 0.7%    |
| Haitech             | 1         | 0.7%    |
| Alienware           | 1         | 0.7%    |
| Unknown             | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ECS SF20PA2                           | 16        | 11.19%  |
| Standard SF20BA2                      | 3         | 2.1%    |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 2.1%    |
| Toshiba Satellite L55t-B              | 2         | 1.4%    |
| HP Pavilion 15                        | 2         | 1.4%    |
| HP Laptop 15-bs0xx                    | 2         | 1.4%    |
| Valve Jupiter                         | 1         | 0.7%    |
| Toshiba Satellite L45-B               | 1         | 0.7%    |
| Toshiba Satellite C855                | 1         | 0.7%    |
| Toshiba Satellite C75D-C              | 1         | 0.7%    |
| Toshiba Satellite C75D-B              | 1         | 0.7%    |
| Toshiba Satellite C645D               | 1         | 0.7%    |
| Toshiba Satellite C55-B               | 1         | 0.7%    |
| Toshiba Satellite C45-A               | 1         | 0.7%    |
| Standard SF20BA                       | 1         | 0.7%    |
| Standard EF20EA                       | 1         | 0.7%    |
| Sony SVF14211CLB                      | 1         | 0.7%    |
| Samsung NC208/NC108                   | 1         | 0.7%    |
| Samsung N102SP/N100SP/N101SP          | 1         | 0.7%    |
| Samsung 700T                          | 1         | 0.7%    |
| Samsung 300E4C/300E5C/300E7C          | 1         | 0.7%    |
| Positivo Serie AT300                  | 1         | 0.7%    |
| Panasonic CF-31JEGAX1M                | 1         | 0.7%    |
| OEM V40SI2                            | 1         | 0.7%    |
| MSI GS63VR 6RF                        | 1         | 0.7%    |
| MSI GL65 Leopard 10SCXR               | 1         | 0.7%    |
| MSI GL63 8RD                          | 1         | 0.7%    |
| MSI GE62 6QD                          | 1         | 0.7%    |
| Lenovo V15-ADA 82C7                   | 1         | 0.7%    |
| Lenovo ThinkPad X240 20AMS72901       | 1         | 0.7%    |
| Lenovo ThinkPad T590 20N5S2GP05       | 1         | 0.7%    |
| Lenovo ThinkPad T450 20BUS0G91F       | 1         | 0.7%    |
| Lenovo ThinkPad S1 Yoga 20CDS02V00    | 1         | 0.7%    |
| Lenovo ThinkPad P50 20EQS14H00        | 1         | 0.7%    |
| Lenovo ThinkPad L490 20Q6S0NF00       | 1         | 0.7%    |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00  | 1         | 0.7%    |
| Lenovo ThinkPad Edge E540 20C6005CLS  | 1         | 0.7%    |
| Lenovo ThinkPad Edge E531 68852BS     | 1         | 0.7%    |
| Lenovo ThinkPad E15 20RES31K00        | 1         | 0.7%    |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 16        | 11.19%  |
| Lenovo ThinkPad        | 10        | 6.99%   |
| Toshiba Satellite      | 9         | 6.29%   |
| Acer Aspire            | 9         | 6.29%   |
| HP Laptop              | 8         | 5.59%   |
| HP Pavilion            | 7         | 4.9%    |
| Dell Inspiron          | 7         | 4.9%    |
| Lenovo IdeaPad         | 6         | 4.2%    |
| Dell Latitude          | 4         | 2.8%    |
| ASUS ROG               | 4         | 2.8%    |
| Standard SF20BA2       | 3         | 2.1%    |
| HP EliteBook           | 2         | 1.4%    |
| HP 240                 | 2         | 1.4%    |
| Dell XPS               | 2         | 1.4%    |
| ASUS VivoBook          | 2         | 1.4%    |
| Acer TravelMate        | 2         | 1.4%    |
| Valve Jupiter          | 1         | 0.7%    |
| Standard SF20BA        | 1         | 0.7%    |
| Standard EF20EA        | 1         | 0.7%    |
| Sony SVF14211CLB       | 1         | 0.7%    |
| Samsung NC208          | 1         | 0.7%    |
| Samsung N102SP         | 1         | 0.7%    |
| Samsung 700T           | 1         | 0.7%    |
| Samsung 300E4C         | 1         | 0.7%    |
| Positivo Serie         | 1         | 0.7%    |
| Panasonic CF-31JEGAX1M | 1         | 0.7%    |
| OEM V40SI2             | 1         | 0.7%    |
| MSI GS63VR             | 1         | 0.7%    |
| MSI GL65               | 1         | 0.7%    |
| MSI GL63               | 1         | 0.7%    |
| MSI GE62               | 1         | 0.7%    |
| Lenovo V15-ADA         | 1         | 0.7%    |
| Lenovo ThinkBook       | 1         | 0.7%    |
| Lenovo G50-70          | 1         | 0.7%    |
| Lenovo G405            | 1         | 0.7%    |
| Lenovo B51-30          | 1         | 0.7%    |
| Lenovo B50-45          | 1         | 0.7%    |
| Lenovo 14w             | 1         | 0.7%    |
| Intel EF20             | 1         | 0.7%    |
| iClever IC-T01         | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 25        | 17.48%  |
| 2019 | 14        | 9.79%   |
| 2013 | 14        | 9.79%   |
| 2020 | 13        | 9.09%   |
| 2018 | 12        | 8.39%   |
| 2014 | 12        | 8.39%   |
| 2016 | 11        | 7.69%   |
| 2015 | 11        | 7.69%   |
| 2011 | 10        | 6.99%   |
| 2012 | 7         | 4.9%    |
| 2010 | 4         | 2.8%    |
| 2008 | 3         | 2.1%    |
| 2007 | 3         | 2.1%    |
| 2021 | 2         | 1.4%    |
| 2022 | 1         | 0.7%    |
| 2009 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 143       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 130       | 90.28%  |
| Enabled  | 14        | 9.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 38        | 26.21%  |
| 4.01-8.0    | 34        | 23.45%  |
| 1.01-2.0    | 26        | 17.93%  |
| 8.01-16.0   | 22        | 15.17%  |
| 16.01-24.0  | 12        | 8.28%   |
| 32.01-64.0  | 7         | 4.83%   |
| 24.01-32.0  | 3         | 2.07%   |
| 2.01-3.0    | 1         | 0.69%   |
| 64.01-256.0 | 1         | 0.69%   |
| 0.01-0.5    | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 70        | 44.87%  |
| 2.01-3.0  | 35        | 22.44%  |
| 4.01-8.0  | 17        | 10.9%   |
| 3.01-4.0  | 15        | 9.62%   |
| 0.51-1.0  | 12        | 7.69%   |
| 8.01-16.0 | 5         | 3.21%   |
| 0.01-0.5  | 2         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 116       | 81.12%  |
| 2      | 26        | 18.18%  |
| 0      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 66.67%  |
| Yes       | 48        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 65.03%  |
| No        | 50        | 34.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 97.2%   |
| No        | 4         | 2.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 79.72%  |
| No        | 29        | 20.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 143       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 100       | 65.36%  |
| Maldonado              | 8         | 5.23%   |
| Canelones              | 8         | 5.23%   |
| Punta del Este         | 4         | 2.61%   |
| Las Piedras            | 4         | 2.61%   |
| Buceo                  | 3         | 1.96%   |
| Salto                  | 2         | 1.31%   |
| Rocha                  | 2         | 1.31%   |
| Punta Gorda            | 2         | 1.31%   |
| Ciudad del Plata       | 2         | 1.31%   |
| Solymar                | 1         | 0.65%   |
| San Jose de Mayo       | 1         | 0.65%   |
| Pocitos                | 1         | 0.65%   |
| Pinamar                | 1         | 0.65%   |
| Paysandú              | 1         | 0.65%   |
| Parque Rodo            | 1         | 0.65%   |
| Nueva Helvecia         | 1         | 0.65%   |
| Melilla                | 1         | 0.65%   |
| Maronas                | 1         | 0.65%   |
| Libertad               | 1         | 0.65%   |
| Las Flores             | 1         | 0.65%   |
| La Paz                 | 1         | 0.65%   |
| Joaquin Suarez         | 1         | 0.65%   |
| El Tesoro              | 1         | 0.65%   |
| El Pinar               | 1         | 0.65%   |
| Durazno                | 1         | 0.65%   |
| Barrancas Coloradas    | 1         | 0.65%   |
| Arenas de Jose Ignacio | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 24        | 28     | 15%     |
| Unknown                     | 24        | 30     | 15%     |
| Toshiba                     | 21        | 25     | 13.13%  |
| Kingston                    | 19        | 26     | 11.88%  |
| Seagate                     | 16        | 19     | 10%     |
| SanDisk                     | 11        | 13     | 6.88%   |
| Samsung Electronics         | 9         | 9      | 5.63%   |
| Hitachi                     | 6         | 8      | 3.75%   |
| SK hynix                    | 5         | 5      | 3.13%   |
| HGST                        | 5         | 5      | 3.13%   |
| Intel                       | 4         | 4      | 2.5%    |
| Hewlett-Packard             | 3         | 3      | 1.88%   |
| Kingston Technology Company | 2         | 2      | 1.25%   |
| Crucial                     | 2         | 3      | 1.25%   |
| W800SH                      | 1         | 1      | 0.63%   |
| Netac                       | 1         | 1      | 0.63%   |
| LITEON                      | 1         | 2      | 0.63%   |
| KIOXIA                      | 1         | 1      | 0.63%   |
| Dahua                       | 1         | 1      | 0.63%   |
| China                       | 1         | 1      | 0.63%   |
| BIWIN                       | 1         | 1      | 0.63%   |
| BHT                         | 1         | 1      | 0.63%   |
| Apple                       | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 12        | 7.32%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 4.88%   |
| Unknown DA4032  32GB                 | 5         | 3.05%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 3.05%   |
| Toshiba MQ01ABD075 752GB             | 4         | 2.44%   |
| Seagate ST1000LM035-1RK172 970GB     | 4         | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 2.44%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.83%   |
| Toshiba HDWK105 500GB                | 3         | 1.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.83%   |
| SanDisk DF4032  32GB                 | 3         | 1.83%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 2         | 1.22%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 2         | 1.22%   |
| Unknown SD/MMC/MS PRO 249GB          | 2         | 1.22%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 1.22%   |
| SanDisk NVMe SSD Drive 1024GB        | 2         | 1.22%   |
| WDC WDS250G2X0C-00L350 250GB         | 1         | 0.61%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.61%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.61%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.61%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.61%   |
| WDC WD3200LPCX-24C6HT0 320GB         | 1         | 0.61%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 1         | 0.61%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.61%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.61%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.61%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.61%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.61%   |
| W800SH 512GB SSD                     | 1         | 0.61%   |
| Unknown SD64G  64GB                  | 1         | 0.61%   |
| Unknown SD16G  32GB                  | 1         | 0.61%   |
| Unknown NCard  32GB                  | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 18        | 22     | 28.13%  |
| Toshiba | 17        | 21     | 26.56%  |
| Seagate | 16        | 19     | 25%     |
| Hitachi | 6         | 8      | 9.38%   |
| HGST    | 5         | 5      | 7.81%   |
| Unknown | 2         | 2      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 20     | 38.1%   |
| Samsung Electronics | 5         | 5      | 11.9%   |
| WDC                 | 3         | 3      | 7.14%   |
| SanDisk             | 3         | 3      | 7.14%   |
| Hewlett-Packard     | 3         | 3      | 7.14%   |
| SK hynix            | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| W800SH              | 1         | 1      | 2.38%   |
| Toshiba             | 1         | 1      | 2.38%   |
| Netac               | 1         | 1      | 2.38%   |
| Dahua               | 1         | 1      | 2.38%   |
| Crucial             | 1         | 2      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| BIWIN               | 1         | 1      | 2.38%   |
| BHT                 | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 77     | 39.74%  |
| SSD  | 41        | 47     | 26.28%  |
| NVMe | 27        | 33     | 17.31%  |
| MMC  | 26        | 33     | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 121    | 62.67%  |
| NVMe | 27        | 33     | 18%     |
| MMC  | 26        | 33     | 17.33%  |
| SAS  | 3         | 3      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 85     | 69.31%  |
| 0.51-1.0   | 29        | 37     | 28.71%  |
| 3.01-4.0   | 1         | 1      | 0.99%   |
| 1.01-2.0   | 1         | 1      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 35        | 23.65%  |
| 101-250        | 33        | 22.3%   |
| 21-50          | 22        | 14.86%  |
| 501-1000       | 21        | 14.19%  |
| 1-20           | 19        | 12.84%  |
| 51-100         | 9         | 6.08%   |
| 1001-2000      | 5         | 3.38%   |
| Unknown        | 3         | 2.03%   |
| More than 3000 | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 77        | 49.36%  |
| 21-50          | 28        | 17.95%  |
| 51-100         | 15        | 9.62%   |
| 251-500        | 14        | 8.97%   |
| 101-250        | 12        | 7.69%   |
| 501-1000       | 5         | 3.21%   |
| Unknown        | 3         | 1.92%   |
| More than 3000 | 1         | 0.64%   |
| 1001-2000      | 1         | 0.64%   |

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
| Seagate ST1000LM035-1RK172 970GB    | 1         | 1      | 7.69%   |
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
| Detected | 90        | 120    | 62.07%  |
| Works    | 42        | 56     | 28.97%  |
| Malfunc  | 13        | 14     | 8.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 98        | 65.33%  |
| AMD                              | 26        | 17.33%  |
| SanDisk                          | 8         | 5.33%   |
| Toshiba America Info Systems     | 4         | 2.67%   |
| Samsung Electronics              | 4         | 2.67%   |
| Kingston Technology Company      | 4         | 2.67%   |
| SK hynix                         | 2         | 1.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.67%   |
| Micron/Crucial Technology        | 1         | 0.67%   |
| Lite-On Technology               | 1         | 0.67%   |
| Apple                            | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 14.65%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 10.83%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 4.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 3.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 2.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.27%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.27%   |
| Intel SSD 660P Series                                                            | 2         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.27%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.64%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.64%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.64%   |
| SanDisk NVMe Controller                                                          | 1         | 0.64%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.64%   |
| Lite-On NVMe Controller                                                          | 1         | 0.64%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 114       | 74.03%  |
| NVMe | 27        | 17.53%  |
| IDE  | 7         | 4.55%   |
| RAID | 6         | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 112       | 78.32%  |
| AMD    | 31        | 21.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 11.89%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 2.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 2.1%    |
| Intel Celeron CPU N3160 @ 1.60GHz            | 3         | 2.1%    |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 2.1%    |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 2.1%    |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.4%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 1.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.4%    |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.4%    |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.4%    |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.4%    |
| Intel Celeron CPU N3050 @ 1.60GHz            | 2         | 1.4%    |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.4%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.4%    |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.4%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.7%    |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.7%    |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.7%    |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.7%    |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.7%    |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.7%    |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.7%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 31        | 21.68%  |
| Intel Core i5      | 26        | 18.18%  |
| Intel Core i7      | 23        | 16.08%  |
| Intel Core i3      | 12        | 8.39%   |
| Intel Pentium      | 7         | 4.9%    |
| Intel Atom         | 6         | 4.2%    |
| Other              | 5         | 3.5%    |
| AMD A6             | 5         | 3.5%    |
| AMD Ryzen 9        | 4         | 2.8%    |
| AMD E              | 3         | 2.1%    |
| Intel Genuine      | 2         | 1.4%    |
| Intel Core 2 Duo   | 2         | 1.4%    |
| AMD Ryzen 7        | 2         | 1.4%    |
| AMD Ryzen 5        | 2         | 1.4%    |
| AMD Ryzen 3        | 2         | 1.4%    |
| AMD E1             | 2         | 1.4%    |
| Intel Pentium Dual | 1         | 0.7%    |
| AMD Phenom II      | 1         | 0.7%    |
| AMD FX             | 1         | 0.7%    |
| AMD E2             | 1         | 0.7%    |
| AMD Athlon II      | 1         | 0.7%    |
| AMD Athlon         | 1         | 0.7%    |
| AMD A8             | 1         | 0.7%    |
| AMD A4             | 1         | 0.7%    |
| AMD A10            | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 87        | 60.84%  |
| 4      | 42        | 29.37%  |
| 8      | 5         | 3.5%    |
| 6      | 5         | 3.5%    |
| 1      | 4         | 2.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 54.55%  |
| 1      | 65        | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 140       | 97.9%   |
| Unknown        | 3         | 2.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 21.77%  |
| 0x406c4    | 7         | 4.76%   |
| 0x206a7    | 7         | 4.76%   |
| 0x506c9    | 6         | 4.08%   |
| 0x40651    | 6         | 4.08%   |
| 0x806ec    | 5         | 3.4%    |
| 0x406e3    | 5         | 3.4%    |
| 0x306d4    | 5         | 3.4%    |
| 0x20655    | 5         | 3.4%    |
| 0x806ea    | 4         | 2.72%   |
| 0x30678    | 4         | 2.72%   |
| 0x906ea    | 3         | 2.04%   |
| 0x806e9    | 3         | 2.04%   |
| 0x6fd      | 3         | 2.04%   |
| 0x406c3    | 3         | 2.04%   |
| 0x306c3    | 3         | 2.04%   |
| 0x306a9    | 3         | 2.04%   |
| 0x08108109 | 3         | 2.04%   |
| 0x06006705 | 3         | 2.04%   |
| 0x806c1    | 2         | 1.36%   |
| 0x706e5    | 2         | 1.36%   |
| 0x506e3    | 2         | 1.36%   |
| 0x08600104 | 2         | 1.36%   |
| 0x0810100b | 2         | 1.36%   |
| 0x07030105 | 2         | 1.36%   |
| 0x07030104 | 2         | 1.36%   |
| 0x0700010f | 2         | 1.36%   |
| 0xa0652    | 1         | 0.68%   |
| 0x806eb    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x30673    | 1         | 0.68%   |
| 0x30661    | 1         | 0.68%   |
| 0x106e5    | 1         | 0.68%   |
| 0x106ca    | 1         | 0.68%   |
| 0x1067a    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x10661    | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x08600102 | 1         | 0.68%   |
| 0x07030106 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 18        | 12.59%  |
| KabyLake      | 17        | 11.89%  |
| Goldmont      | 17        | 11.89%  |
| Haswell       | 10        | 6.99%   |
| Skylake       | 9         | 6.29%   |
| SandyBridge   | 7         | 4.9%    |
| Broadwell     | 7         | 4.9%    |
| IvyBridge     | 6         | 4.2%    |
| Excavator     | 6         | 4.2%    |
| Westmere      | 5         | 3.5%    |
| Puma          | 5         | 3.5%    |
| Zen+          | 4         | 2.8%    |
| Zen 2         | 4         | 2.8%    |
| Core          | 4         | 2.8%    |
| Bobcat        | 3         | 2.1%    |
| Zen           | 2         | 1.4%    |
| TigerLake     | 2         | 1.4%    |
| Penryn        | 2         | 1.4%    |
| K10           | 2         | 1.4%    |
| Jaguar        | 2         | 1.4%    |
| IceLake       | 2         | 1.4%    |
| CometLake     | 2         | 1.4%    |
| Bonnell       | 2         | 1.4%    |
| Zen 3         | 1         | 0.7%    |
| Piledriver    | 1         | 0.7%    |
| Nehalem       | 1         | 0.7%    |
| Goldmont plus | 1         | 0.7%    |
| Unknown       | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 110       | 65.87%  |
| AMD                              | 39        | 23.35%  |
| Nvidia                           | 17        | 10.18%  |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 9.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 7.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.07%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.33%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.33%   |
| Intel HD Graphics 530                                                                    | 4         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.33%   |
| AMD Renoir                                                                               | 4         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.33%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.74%   |
| Intel HD Graphics 620                                                                    | 3         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.74%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.16%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.16%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.16%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.58%   |
| Nvidia TU117M                                                                            | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.58%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 63.64%  |
| 1 x AMD        | 24        | 16.78%  |
| Intel + Nvidia | 11        | 7.69%   |
| Intel + AMD    | 8         | 5.59%   |
| AMD + Nvidia   | 5         | 3.5%    |
| 2 x AMD        | 2         | 1.4%    |
| 1 x SiS        | 1         | 0.7%    |
| 1 x Nvidia     | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 130       | 90.91%  |
| Proprietary | 11        | 7.69%   |
| Unknown     | 2         | 1.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 71.03%  |
| 0.01-0.5   | 15        | 10.34%  |
| 0.51-1.0   | 11        | 7.59%   |
| 1.01-2.0   | 9         | 6.21%   |
| 3.01-4.0   | 5         | 3.45%   |
| 5.01-6.0   | 2         | 1.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 25        | 16.34%  |
| Chimei Innolux          | 23        | 15.03%  |
| AU Optronics            | 22        | 14.38%  |
| BOE                     | 18        | 11.76%  |
| Samsung Electronics     | 14        | 9.15%   |
| KDC                     | 7         | 4.58%   |
| InfoVision              | 7         | 4.58%   |
| Sharp                   | 4         | 2.61%   |
| PANDA                   | 4         | 2.61%   |
| Chi Mei Optoelectronics | 4         | 2.61%   |
| ViewSonic               | 3         | 1.96%   |
| Acer                    | 3         | 1.96%   |
| LG Philips              | 2         | 1.31%   |
| KTC                     | 2         | 1.31%   |
| HSI                     | 2         | 1.31%   |
| Dell                    | 2         | 1.31%   |
| Apple                   | 2         | 1.31%   |
| Valve                   | 1         | 0.65%   |
| Sun                     | 1         | 0.65%   |
| Konka                   | 1         | 0.65%   |
| JDI                     | 1         | 0.65%   |
| InnoLux Display         | 1         | 0.65%   |
| HKC                     | 1         | 0.65%   |
| Hewlett-Packard         | 1         | 0.65%   |
| CPT                     | 1         | 0.65%   |
| AOC                     | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 6         | 3.87%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 5         | 3.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 1.94%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.29%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.29%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.29%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 1.29%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.29%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 2         | 1.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.29%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.29%   |
| HSI LED-TV HSI0001 1920x1080 708x398mm 32.0-inch                      | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch       | 2         | 1.29%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.29%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch         | 1         | 0.65%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.65%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.65%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.65%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.65%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch | 1         | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.65%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 77        | 55%     |
| 1920x1080 (FHD)   | 37        | 26.43%  |
| 1600x900 (HD+)    | 7         | 5%      |
| 1920x1200 (WUXGA) | 6         | 4.29%   |
| 1280x800 (WXGA)   | 4         | 2.86%   |
| 3840x2160 (4K)    | 3         | 2.14%   |
| 2560x1440 (QHD)   | 2         | 1.43%   |
| 800x1280          | 1         | 0.71%   |
| 2288x1287         | 1         | 0.71%   |
| 1360x768          | 1         | 0.71%   |
| 1024x600          | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 70        | 45.75%  |
| 13     | 25        | 16.34%  |
| 14     | 20        | 13.07%  |
| 11     | 7         | 4.58%   |
| 17     | 6         | 3.92%   |
| 24     | 4         | 2.61%   |
| 23     | 4         | 2.61%   |
| 21     | 3         | 1.96%   |
| 40     | 2         | 1.31%   |
| 34     | 2         | 1.31%   |
| 18     | 2         | 1.31%   |
| 12     | 2         | 1.31%   |
| 10     | 2         | 1.31%   |
| 57     | 1         | 0.65%   |
| 52     | 1         | 0.65%   |
| 27     | 1         | 0.65%   |
| 7      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 70.39%  |
| 201-300     | 17        | 11.18%  |
| 501-600     | 9         | 5.92%   |
| 351-400     | 7         | 4.61%   |
| 401-500     | 5         | 3.29%   |
| 801-900     | 2         | 1.32%   |
| 701-800     | 2         | 1.32%   |
| 1001-1500   | 2         | 1.32%   |
| 1-100       | 1         | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 124       | 93.23%  |
| 16/10 | 6         | 4.51%   |
| 21/9  | 2         | 1.5%    |
| 0.67  | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 45.75%  |
| 81-90          | 40        | 26.14%  |
| 201-250        | 9         | 5.88%   |
| 51-60          | 7         | 4.58%   |
| 121-130        | 6         | 3.92%   |
| 71-80          | 5         | 3.27%   |
| More than 1000 | 2         | 1.31%   |
| 61-70          | 2         | 1.31%   |
| 351-500        | 2         | 1.31%   |
| 41-50          | 2         | 1.31%   |
| 151-200        | 2         | 1.31%   |
| 141-150        | 2         | 1.31%   |
| 501-1000       | 2         | 1.31%   |
| 1-40           | 1         | 0.65%   |
| 301-350        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 79        | 52.32%  |
| 121-160       | 39        | 25.83%  |
| 51-100        | 25        | 16.56%  |
| 161-240       | 5         | 3.31%   |
| 1-50          | 2         | 1.32%   |
| More than 240 | 1         | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 121       | 82.31%  |
| 2     | 22        | 14.97%  |
| 3     | 2         | 1.36%   |
| 0     | 2         | 1.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 69        | 32.39%  |
| Intel                            | 66        | 30.99%  |
| Qualcomm Atheros                 | 35        | 16.43%  |
| Broadcom                         | 19        | 8.92%   |
| Ralink Technology                | 3         | 1.41%   |
| Ralink                           | 3         | 1.41%   |
| MediaTek                         | 3         | 1.41%   |
| TP-Link                          | 2         | 0.94%   |
| Broadcom Limited                 | 2         | 0.94%   |
| Xiaomi                           | 1         | 0.47%   |
| T & A Mobile Phones              | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Sierra Wireless                  | 1         | 0.47%   |
| Samsung Electronics              | 1         | 0.47%   |
| Qualcomm Atheros Communications  | 1         | 0.47%   |
| Marvell Technology Group         | 1         | 0.47%   |
| Lenovo                           | 1         | 0.47%   |
| Huawei Technologies              | 1         | 0.47%   |
| DisplayLink                      | 1         | 0.47%   |
| ASIX Electronics                 | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 35        | 14.23%  |
| Intel Wireless 3165                                                     | 24        | 9.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 23        | 9.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 2.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.44%   |
| Intel Wireless 7265                                                     | 5         | 2.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.63%   |
| Intel Wireless 8260                                                     | 4         | 1.63%   |
| Intel Wireless 7260                                                     | 4         | 1.63%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.63%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.81%   |
| Intel Wireless 3160                                                     | 2         | 0.81%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.81%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.81%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 44.44%  |
| Qualcomm Atheros                | 28        | 19.44%  |
| Realtek Semiconductor           | 26        | 18.06%  |
| Broadcom                        | 14        | 9.72%   |
| Ralink Technology               | 3         | 2.08%   |
| Ralink                          | 3         | 2.08%   |
| MediaTek                        | 2         | 1.39%   |
| Broadcom Limited                | 2         | 1.39%   |
| TP-Link                         | 1         | 0.69%   |
| Qualcomm Atheros Communications | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 24        | 16.55%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 4.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.14%   |
| Intel Wireless 7265                                                     | 5         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.76%   |
| Intel Wireless 8260                                                     | 4         | 2.76%   |
| Intel Wireless 7260                                                     | 4         | 2.76%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.07%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.38%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.38%   |
| Intel Wireless 3160                                                     | 2         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.38%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.69%   |
| Intel WiFi Link 5100                                                    | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 60        | 60%     |
| Intel                            | 13        | 13%     |
| Qualcomm Atheros                 | 9         | 9%      |
| Broadcom                         | 7         | 7%      |
| Xiaomi                           | 1         | 1%      |
| TP-Link                          | 1         | 1%      |
| Silicon Integrated Systems [SiS] | 1         | 1%      |
| Sierra Wireless                  | 1         | 1%      |
| Samsung Electronics              | 1         | 1%      |
| MediaTek                         | 1         | 1%      |
| Marvell Technology Group         | 1         | 1%      |
| Lenovo                           | 1         | 1%      |
| Huawei Technologies              | 1         | 1%      |
| DisplayLink                      | 1         | 1%      |
| ASIX Electronics                 | 1         | 1%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 35%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 23%     |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 3%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 2         | 2%      |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2%      |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 2%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1%      |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1%      |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1%      |
| Samsung Kiera                                                     | 1         | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1%      |
| Realtek PCIe GbE Family Controller                                | 1         | 1%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1%      |
| MediaTek PRESIDENT_GOLD_10                                        | 1         | 1%      |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1%      |
| Lenovo USB-C to LAN                                               | 1         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1%      |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1%      |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1%      |
| Huawei E353/E3131                                                 | 1         | 1%      |
| DisplayLink Plugable UD-3900                                      | 1         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1%      |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 139       | 59.66%  |
| Ethernet | 93        | 39.91%  |
| Unknown  | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 87.59%  |
| Ethernet | 18        | 12.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 88        | 61.54%  |
| 1     | 51        | 35.66%  |
| 0     | 4         | 2.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 75.69%  |
| Yes  | 35        | 24.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 48.7%   |
| Realtek Semiconductor           | 13        | 11.3%   |
| Qualcomm Atheros Communications | 11        | 9.57%   |
| IMC Networks                    | 8         | 6.96%   |
| Toshiba                         | 7         | 6.09%   |
| Broadcom                        | 4         | 3.48%   |
| Lite-On Technology              | 3         | 2.61%   |
| Foxconn / Hon Hai               | 3         | 2.61%   |
| Cambridge Silicon Radio         | 3         | 2.61%   |
| Ralink                          | 2         | 1.74%   |
| Apple                           | 2         | 1.74%   |
| Ralink Technology               | 1         | 0.87%   |
| Foxconn International           | 1         | 0.87%   |
| Alps Electric                   | 1         | 0.87%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 33.04%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 6.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.22%   |
| Intel AX200 Bluetooth                               | 4         | 3.48%   |
| Toshiba Bluetooth Device                            | 3         | 2.61%   |
| Toshiba BCM43142A0                                  | 3         | 2.61%   |
| Realtek Bluetooth Radio                             | 3         | 2.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.61%   |
| Intel AX201 Bluetooth                               | 3         | 2.61%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.61%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.74%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.74%   |
| Toshiba Bluetooth Radio                             | 1         | 0.87%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.87%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.87%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.87%   |
| Lite-On Bluetooth Device                            | 1         | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.87%   |
| IMC Networks Wireless_Device                        | 1         | 0.87%   |
| IMC Networks Bluetooth Device                       | 1         | 0.87%   |
| IMC Networks Bluetooth                              | 1         | 0.87%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.87%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.87%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.87%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.87%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.87%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.87%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.87%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.87%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.87%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 107       | 67.3%   |
| AMD                                  | 31        | 19.5%   |
| Nvidia                               | 11        | 6.92%   |
| Logitech                             | 4         | 2.52%   |
| Generalplus Technology               | 2         | 1.26%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.63%   |
| Texas Instruments                    | 1         | 0.63%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.63%   |
| C-Media Electronics                  | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 8.29%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 5.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 4.88%   |
| AMD FCH Azalia Controller                                                                         | 10        | 4.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 4.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.41%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.93%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.44%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.95%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.46%   |
| Logitech H390 headset with microphone                                                             | 2         | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.98%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.98%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.98%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.98%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.98%   |
| Thesycon Systemsoftware & Consulting D50s                                                         | 1         | 0.49%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 29.41%  |
| SK hynix            | 15        | 17.65%  |
| Micron Technology   | 10        | 11.76%  |
| Ramaxel Technology  | 7         | 8.24%   |
| Goldkey             | 6         | 7.06%   |
| Unknown             | 5         | 5.88%   |
| Kingston            | 5         | 5.88%   |
| Crucial             | 4         | 4.71%   |
| Elpida              | 3         | 3.53%   |
| Nanya Technology    | 2         | 2.35%   |
| A-DATA Technology   | 2         | 2.35%   |
| Patriot             | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s      | 4         | 4.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 3.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 3.41%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 2         | 2.27%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 2.27%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 2         | 2.27%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 2.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.27%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s      | 2         | 2.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.27%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s      | 2         | 2.27%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2048MB SODIMM DDR3 1334MT/s     | 2         | 2.27%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                 | 1         | 1.14%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 1         | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1         | 1.14%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                  | 1         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.14%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.14%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 1         | 1.14%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s        | 1         | 1.14%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.14%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                     | 1         | 1.14%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s        | 1         | 1.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 1         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.14%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.14%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.14%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.14%   |
| Samsung RAM M471A2G44AM0-CTD 16GB Row Of Chips DDR4 2667MT/s | 1         | 1.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 37        | 52.86%  |
| DDR4   | 25        | 35.71%  |
| DDR2   | 3         | 4.29%   |
| SDRAM  | 2         | 2.86%   |
| LPDDR3 | 2         | 2.86%   |
| LPDDR4 | 1         | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 62        | 91.18%  |
| Row Of Chips | 4         | 5.88%   |
| DIMM         | 2         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 35.44%  |
| 8192  | 21        | 26.58%  |
| 2048  | 16        | 20.25%  |
| 16384 | 9         | 11.39%  |
| 32768 | 2         | 2.53%   |
| 1024  | 2         | 2.53%   |
| 512   | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 33        | 41.77%  |
| 2667  | 14        | 17.72%  |
| 3200  | 6         | 7.59%   |
| 2400  | 6         | 7.59%   |
| 1334  | 5         | 6.33%   |
| 3266  | 3         | 3.8%    |
| 2133  | 3         | 3.8%    |
| 533   | 3         | 3.8%    |
| 4199  | 2         | 2.53%   |
| 1333  | 2         | 2.53%   |
| 1867  | 1         | 1.27%   |
| 1067  | 1         | 1.27%   |

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
| Chicony Electronics                    | 38        | 28.79%  |
| Realtek Semiconductor                  | 15        | 11.36%  |
| Cheng Uei Precision Industry (Foxlink) | 13        | 9.85%   |
| Microdia                               | 8         | 6.06%   |
| Suyin                                  | 7         | 5.3%    |
| Sunplus Innovation Technology          | 7         | 5.3%    |
| Acer                                   | 7         | 5.3%    |
| Unknown                                | 5         | 3.79%   |
| Silicon Motion                         | 4         | 3.03%   |
| IMC Networks                           | 4         | 3.03%   |
| Bison Electronics                      | 4         | 3.03%   |
| Quanta                                 | 3         | 2.27%   |
| Importek                               | 3         | 2.27%   |
| Alcor Micro                            | 3         | 2.27%   |
| Syntek                                 | 2         | 1.52%   |
| Lite-On Technology                     | 2         | 1.52%   |
| Samsung Electronics                    | 1         | 0.76%   |
| Primax Electronics                     | 1         | 0.76%   |
| Novatek Microelectronics               | 1         | 0.76%   |
| Luxvisions Innotech Limited            | 1         | 0.76%   |
| Logitech                               | 1         | 0.76%   |
| DigiTech                               | 1         | 0.76%   |
| Apple                                  | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 16        | 12.12%  |
| Unknown USB Camera                                             | 5         | 3.79%   |
| Chicony Integrated Camera                                      | 5         | 3.79%   |
| Chicony HP Truevision HD                                       | 5         | 3.79%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 3.03%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 3.03%   |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 3.03%   |
| Acer Integrated Camera                                         | 4         | 3.03%   |
| Realtek Lenovo EasyCamera                                      | 3         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 3         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 2.27%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.52%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.52%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.52%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.52%   |
| Chicony HD WebCam                                              | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.52%   |
| Acer Lenovo EasyCamera                                         | 2         | 1.52%   |
| Syntek Integrated Camera                                       | 1         | 0.76%   |
| Syntek EasyCamera                                              | 1         | 0.76%   |
| Suyin VGA Webcam                                               | 1         | 0.76%   |
| Suyin HP Truevision HD                                         | 1         | 0.76%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.76%   |
| Suyin HD WebCam                                                | 1         | 0.76%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.76%   |
| Sunplus MTD camera                                             | 1         | 0.76%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.76%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.76%   |
| Sunplus HP TrueVision HD Camera                                | 1         | 0.76%   |
| Sunplus HD Webcam                                              | 1         | 0.76%   |
| Sunplus Asus Webcam                                            | 1         | 0.76%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.76%   |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 0.76%   |

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
| 0     | 109       | 75.69%  |
| 1     | 33        | 22.92%  |
| 2     | 2         | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 40.54%  |
| Net/wireless          | 6         | 16.22%  |
| Multimedia controller | 5         | 13.51%  |
| Graphics card         | 4         | 10.81%  |
| Chipcard              | 3         | 8.11%   |
| Bluetooth             | 2         | 5.41%   |
| Storage               | 1         | 2.7%    |
| Modem                 | 1         | 2.7%    |


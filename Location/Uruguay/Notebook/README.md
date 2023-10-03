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

Total: 232

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Razer         | Blade                       | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4398558915](https://linux-hardware.org/?probe=4398558915) | Sep 19, 2023 |
| ASUSTek       | X542UQ                      | [6793d8c052](https://linux-hardware.org/?probe=6793d8c052) | Sep 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| GPU Compan... | GWTN156-9                   | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| Chuwi         | GemiBook Pro                | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [a435538cb2](https://linux-hardware.org/?probe=a435538cb2) | Aug 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [0dc75dae26](https://linux-hardware.org/?probe=0dc75dae26) | Aug 18, 2023 |
| HP            | 14                          | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| HP            | Laptop 15-dy2xxx            | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Dell          | Latitude E5420              | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [ad76ecf5a9](https://linux-hardware.org/?probe=ad76ecf5a9) | Jul 01, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [b8bab5a2e6](https://linux-hardware.org/?probe=b8bab5a2e6) | Jul 01, 2023 |
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
| Ubuntu 20.04                 | 25        | 14.04%  |
| Ubuntu 18.04                 | 20        | 11.24%  |
| Ubuntu 22.04                 | 8         | 4.49%   |
| OpenMandriva 4.2             | 6         | 3.37%   |
| Manjaro                      | 6         | 3.37%   |
| KDE neon 20.04               | 6         | 3.37%   |
| OpenMandriva 4.3             | 5         | 2.81%   |
| Arch Rolling                 | 5         | 2.81%   |
| Zorin 16                     | 4         | 2.25%   |
| OpenMandriva 23.03           | 4         | 2.25%   |
| Fedora 38                    | 4         | 2.25%   |
| Ubuntu 21.10                 | 3         | 1.69%   |
| Ubuntu 19.04                 | 3         | 1.69%   |
| Linux Mint 21.2              | 3         | 1.69%   |
| Linux Mint 19.3              | 3         | 1.69%   |
| Fedora 36                    | 3         | 1.69%   |
| Xubuntu 18.04                | 2         | 1.12%   |
| Ubuntu 21.04                 | 2         | 1.12%   |
| Ubuntu 18.10                 | 2         | 1.12%   |
| OpenMandriva 23.01           | 2         | 1.12%   |
| Linux Mint 20.1              | 2         | 1.12%   |
| Linux Mint 19.1              | 2         | 1.12%   |
| Kubuntu 18.04                | 2         | 1.12%   |
| Debian 12                    | 2         | 1.12%   |
| Debian 11                    | 2         | 1.12%   |
| ArcoLinux Rolling            | 2         | 1.12%   |
| Zorin 15                     | 1         | 0.56%   |
| Xubuntu 22.04                | 1         | 0.56%   |
| Xubuntu 20.04                | 1         | 0.56%   |
| Void Linux Rolling           | 1         | 0.56%   |
| Ubuntu MATE 20.04            | 1         | 0.56%   |
| Ubuntu 23.04                 | 1         | 0.56%   |
| Ubuntu 20.10                 | 1         | 0.56%   |
| Ubuntu 19.10                 | 1         | 0.56%   |
| Ubuntu 17.10                 | 1         | 0.56%   |
| SteamOS 3.4.4                | 1         | 0.56%   |
| ROSA R11.1                   | 1         | 0.56%   |
| Pop!_OS 22.04                | 1         | 0.56%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.56%   |
| openSUSE Leap-15.1           | 1         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 65        | 38.01%  |
| OpenMandriva | 17        | 9.94%   |
| Linux Mint   | 17        | 9.94%   |
| Fedora       | 10        | 5.85%   |
| Manjaro      | 7         | 4.09%   |
| KDE neon     | 6         | 3.51%   |
| Zorin        | 5         | 2.92%   |
| Arch         | 5         | 2.92%   |
| Xubuntu      | 4         | 2.34%   |
| Kubuntu      | 4         | 2.34%   |
| Endless      | 4         | 2.34%   |
| Debian       | 3         | 1.75%   |
| ArcoLinux    | 3         | 1.75%   |
| openSUSE     | 2         | 1.17%   |
| Lubuntu      | 2         | 1.17%   |
| EndeavourOS  | 2         | 1.17%   |
| Elementary   | 2         | 1.17%   |
| Archcraft    | 2         | 1.17%   |
| Void Linux   | 1         | 0.58%   |
| Ubuntu MATE  | 1         | 0.58%   |
| SteamOS      | 1         | 0.58%   |
| ROSA         | 1         | 0.58%   |
| Pop!_OS      | 1         | 0.58%   |
| NixOS        | 1         | 0.58%   |
| MX           | 1         | 0.58%   |
| Gentoo       | 1         | 0.58%   |
| Feren OS     | 1         | 0.58%   |
| BlackPanther | 1         | 0.58%   |
| antiX        | 1         | 0.58%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 6         | 3.14%   |
| 4.16.18-pa2-2bp1         | 6         | 3.14%   |
| 4.16.18-pa2-1bp5         | 5         | 2.62%   |
| 6.2.6-desktop-1omv2390   | 4         | 2.09%   |
| 5.8.0-53-generic         | 4         | 2.09%   |
| 5.5.19-bp0               | 4         | 2.09%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.09%   |
| 5.13.0-39-generic        | 4         | 2.09%   |
| 5.4.0-73-generic         | 3         | 1.57%   |
| 5.4.0-58-generic         | 3         | 1.57%   |
| 5.4.0-52-generic         | 3         | 1.57%   |
| 5.11.0-38-generic        | 3         | 1.57%   |
| 6.4.7-arch1-1            | 2         | 1.05%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.05%   |
| 5.8.0-50-generic         | 2         | 1.05%   |
| 5.8.0-43-generic         | 2         | 1.05%   |
| 5.4.0-72-generic         | 2         | 1.05%   |
| 5.4.0-42-generic         | 2         | 1.05%   |
| 5.3.0-28-generic         | 2         | 1.05%   |
| 5.19.0-41-generic        | 2         | 1.05%   |
| 5.19.0-35-generic        | 2         | 1.05%   |
| 5.16.13-desktop-1omv4003 | 2         | 1.05%   |
| 5.15.0-46-generic        | 2         | 1.05%   |
| 5.15.0-41-generic        | 2         | 1.05%   |
| 5.13.0-40-generic        | 2         | 1.05%   |
| 5.13.0-37-generic        | 2         | 1.05%   |
| 5.13.0-30-generic        | 2         | 1.05%   |
| 5.11.12-desktop-1omv4002 | 2         | 1.05%   |
| 5.0.0-13-generic         | 2         | 1.05%   |
| 4.15.0-51-generic        | 2         | 1.05%   |
| 4.15.0-20-generic        | 2         | 1.05%   |
| 4.15.0-101-generic       | 2         | 1.05%   |
| 6.5.4-arch2-1            | 1         | 0.52%   |
| 6.5.3-1-default          | 1         | 0.52%   |
| 6.4.8-desktop-2omv2390   | 1         | 0.52%   |
| 6.4.6-200.fc38.x86_64    | 1         | 0.52%   |
| 6.4.1-arch2-1            | 1         | 0.52%   |
| 6.4.0-060400-generic     | 1         | 0.52%   |
| 6.3.9-zen1-1-zen         | 1         | 0.52%   |
| 6.3.4-zen1-1-zen         | 1         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 12.37%  |
| 5.8.0   | 12        | 6.45%   |
| 5.13.0  | 12        | 6.45%   |
| 5.15.0  | 11        | 5.91%   |
| 4.16.18 | 11        | 5.91%   |
| 4.15.0  | 9         | 4.84%   |
| 5.11.0  | 6         | 3.23%   |
| 5.10.14 | 6         | 3.23%   |
| 5.0.0   | 6         | 3.23%   |
| 5.3.0   | 5         | 2.69%   |
| 5.19.0  | 5         | 2.69%   |
| 6.2.6   | 4         | 2.15%   |
| 5.5.19  | 4         | 2.15%   |
| 5.16.7  | 4         | 2.15%   |
| 4.18.0  | 4         | 2.15%   |
| 5.10.0  | 3         | 1.61%   |
| 6.4.7   | 2         | 1.08%   |
| 6.3.4   | 2         | 1.08%   |
| 6.2.0   | 2         | 1.08%   |
| 6.1.1   | 2         | 1.08%   |
| 6.1.0   | 2         | 1.08%   |
| 5.19.12 | 2         | 1.08%   |
| 5.16.13 | 2         | 1.08%   |
| 5.11.12 | 2         | 1.08%   |
| 6.5.4   | 1         | 0.54%   |
| 6.5.3   | 1         | 0.54%   |
| 6.4.8   | 1         | 0.54%   |
| 6.4.6   | 1         | 0.54%   |
| 6.4.1   | 1         | 0.54%   |
| 6.4.0   | 1         | 0.54%   |
| 6.3.9   | 1         | 0.54%   |
| 6.2.9   | 1         | 0.54%   |
| 6.2.12  | 1         | 0.54%   |
| 6.1.31  | 1         | 0.54%   |
| 6.1.29  | 1         | 0.54%   |
| 6.1.18  | 1         | 0.54%   |
| 6.1.11  | 1         | 0.54%   |
| 6.0.8   | 1         | 0.54%   |
| 6.0.6   | 1         | 0.54%   |
| 6.0.15  | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 25        | 13.66%  |
| 5.8     | 14        | 7.65%   |
| 5.15    | 13        | 7.1%    |
| 5.13    | 12        | 6.56%   |
| 5.10    | 12        | 6.56%   |
| 4.16    | 12        | 6.56%   |
| 5.11    | 10        | 5.46%   |
| 4.15    | 9         | 4.92%   |
| 6.2     | 8         | 4.37%   |
| 6.1     | 8         | 4.37%   |
| 5.16    | 8         | 4.37%   |
| 5.19    | 7         | 3.83%   |
| 6.4     | 6         | 3.28%   |
| 5.0     | 6         | 3.28%   |
| 5.3     | 5         | 2.73%   |
| 4.18    | 5         | 2.73%   |
| 5.5     | 4         | 2.19%   |
| 6.0     | 3         | 1.64%   |
| 5.17    | 3         | 1.64%   |
| 6.5     | 2         | 1.09%   |
| 6.3     | 2         | 1.09%   |
| 5.18    | 2         | 1.09%   |
| 5.6     | 1         | 0.55%   |
| 5.2     | 1         | 0.55%   |
| 5.14    | 1         | 0.55%   |
| 4.9     | 1         | 0.55%   |
| 4.17    | 1         | 0.55%   |
| 4.13    | 1         | 0.55%   |
| 4.12    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 164       | 98.8%   |
| i686   | 2         | 1.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 56        | 32.75%  |
| KDE5            | 32        | 18.71%  |
| Unknown         | 22        | 12.87%  |
| XFCE            | 16        | 9.36%   |
| X-Cinnamon      | 13        | 7.6%    |
| GNOME Flashback | 13        | 7.6%    |
| KDE             | 5         | 2.92%   |
| MATE            | 3         | 1.75%   |
| LXQt            | 3         | 1.75%   |
| Pantheon        | 2         | 1.17%   |
| openbox         | 2         | 1.17%   |
| Cinnamon        | 2         | 1.17%   |
| sway            | 1         | 0.58%   |
| LeftWM          | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 129       | 77.25%  |
| Wayland | 28        | 16.77%  |
| Unknown | 9         | 5.39%   |
| Tty     | 1         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 47.37%  |
| SDDM    | 30        | 17.54%  |
| GDM     | 23        | 13.45%  |
| LightDM | 16        | 9.36%   |
| GDM3    | 16        | 9.36%   |
| TDM     | 3         | 1.75%   |
| XDM     | 1         | 0.58%   |
| GREETD  | 1         | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_UY      | 83        | 47.7%   |
| en_US      | 43        | 24.71%  |
| Unknown    | 18        | 10.34%  |
| es_ES      | 16        | 9.2%    |
| es_MX      | 7         | 4.02%   |
| es_AR      | 2         | 1.15%   |
| C          | 2         | 1.15%   |
| pt_BR      | 1         | 0.57%   |
| es_UY.UTF8 | 1         | 0.57%   |
| en_CA      | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 95        | 56.21%  |
| BIOS | 74        | 43.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 133       | 77.33%  |
| Overlay | 16        | 9.3%    |
| Btrfs   | 13        | 7.56%   |
| Tmpfs   | 4         | 2.33%   |
| Unknown | 4         | 2.33%   |
| Xfs     | 1         | 0.58%   |
| Ext3    | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 94        | 55.62%  |
| GPT     | 58        | 34.32%  |
| MBR     | 17        | 10.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 137       | 82.53%  |
| Yes       | 29        | 17.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 128       | 75.74%  |
| Yes       | 41        | 24.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 34        | 20.48%  |
| Lenovo              | 28        | 16.87%  |
| ASUSTek Computer    | 17        | 10.24%  |
| ECS                 | 16        | 9.64%   |
| Dell                | 16        | 9.64%   |
| Acer                | 14        | 8.43%   |
| Toshiba             | 9         | 5.42%   |
| Standard            | 5         | 3.01%   |
| Samsung Electronics | 4         | 2.41%   |
| MSI                 | 4         | 2.41%   |
| GPU Company         | 2         | 1.2%    |
| Gateway             | 2         | 1.2%    |
| Apple               | 2         | 1.2%    |
| Valve               | 1         | 0.6%    |
| Sony                | 1         | 0.6%    |
| Razer               | 1         | 0.6%    |
| Positivo            | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| OEM                 | 1         | 0.6%    |
| Intel               | 1         | 0.6%    |
| iClever             | 1         | 0.6%    |
| Haitech             | 1         | 0.6%    |
| Fujitsu             | 1         | 0.6%    |
| Chuwi               | 1         | 0.6%    |
| Alienware           | 1         | 0.6%    |
| Unknown             | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ECS SF20PA2                              | 16        | 9.64%   |
| Standard SF20BA2                         | 3         | 1.81%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 3         | 1.81%   |
| Toshiba Satellite L55t-B                 | 2         | 1.2%    |
| HP Pavilion 15                           | 2         | 1.2%    |
| HP Notebook                              | 2         | 1.2%    |
| HP Laptop 15-bs0xx                       | 2         | 1.2%    |
| Valve Jupiter                            | 1         | 0.6%    |
| Toshiba Satellite L45-B                  | 1         | 0.6%    |
| Toshiba Satellite C855                   | 1         | 0.6%    |
| Toshiba Satellite C75D-C                 | 1         | 0.6%    |
| Toshiba Satellite C75D-B                 | 1         | 0.6%    |
| Toshiba Satellite C645D                  | 1         | 0.6%    |
| Toshiba Satellite C55-B                  | 1         | 0.6%    |
| Toshiba Satellite C45-A                  | 1         | 0.6%    |
| Standard SF20BA                          | 1         | 0.6%    |
| Standard EF20EA                          | 1         | 0.6%    |
| Sony SVF14211CLB                         | 1         | 0.6%    |
| Samsung NC208/NC108                      | 1         | 0.6%    |
| Samsung N102SP/N100SP/N101SP             | 1         | 0.6%    |
| Samsung 700T                             | 1         | 0.6%    |
| Samsung 300E4C/300E5C/300E7C             | 1         | 0.6%    |
| Razer Blade                              | 1         | 0.6%    |
| Positivo Serie AT300                     | 1         | 0.6%    |
| Panasonic CF-31JEGAX1M                   | 1         | 0.6%    |
| OEM V40SI2                               | 1         | 0.6%    |
| MSI GS63VR 6RF                           | 1         | 0.6%    |
| MSI GL65 Leopard 10SCXR                  | 1         | 0.6%    |
| MSI GL63 8RD                             | 1         | 0.6%    |
| MSI GE62 6QD                             | 1         | 0.6%    |
| Lenovo V15-ADA 82C7                      | 1         | 0.6%    |
| Lenovo ThinkPad X240 20AMS72901          | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS36700 | 1         | 0.6%    |
| Lenovo ThinkPad T590 20N5S2GP05          | 1         | 0.6%    |
| Lenovo ThinkPad T450 20BUS0G91F          | 1         | 0.6%    |
| Lenovo ThinkPad T14s Gen 3 21BSS37200    | 1         | 0.6%    |
| Lenovo ThinkPad T14 Gen 2a 20XLS23K00    | 1         | 0.6%    |
| Lenovo ThinkPad S1 Yoga 20CDS02V00       | 1         | 0.6%    |
| Lenovo ThinkPad P50 20EQS14H00           | 1         | 0.6%    |
| Lenovo ThinkPad L490 20Q6S0NF00          | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 16        | 9.64%   |
| Lenovo ThinkPad        | 13        | 7.83%   |
| Acer Aspire            | 10        | 6.02%   |
| Toshiba Satellite      | 9         | 5.42%   |
| HP Laptop              | 9         | 5.42%   |
| HP Pavilion            | 8         | 4.82%   |
| Lenovo IdeaPad         | 7         | 4.22%   |
| Dell Inspiron          | 7         | 4.22%   |
| Dell Latitude          | 6         | 3.61%   |
| ASUS ROG               | 5         | 3.01%   |
| ASUS VivoBook          | 4         | 2.41%   |
| Standard SF20BA2       | 3         | 1.81%   |
| ASUS ZenBook           | 3         | 1.81%   |
| HP Stream              | 2         | 1.2%    |
| HP Notebook            | 2         | 1.2%    |
| HP EliteBook           | 2         | 1.2%    |
| HP 240                 | 2         | 1.2%    |
| Dell XPS               | 2         | 1.2%    |
| Acer TravelMate        | 2         | 1.2%    |
| Valve Jupiter          | 1         | 0.6%    |
| Standard SF20BA        | 1         | 0.6%    |
| Standard EF20EA        | 1         | 0.6%    |
| Sony SVF14211CLB       | 1         | 0.6%    |
| Samsung NC208          | 1         | 0.6%    |
| Samsung N102SP         | 1         | 0.6%    |
| Samsung 700T           | 1         | 0.6%    |
| Samsung 300E4C         | 1         | 0.6%    |
| Razer Blade            | 1         | 0.6%    |
| Positivo Serie         | 1         | 0.6%    |
| Panasonic CF-31JEGAX1M | 1         | 0.6%    |
| OEM V40SI2             | 1         | 0.6%    |
| MSI GS63VR             | 1         | 0.6%    |
| MSI GL65               | 1         | 0.6%    |
| MSI GL63               | 1         | 0.6%    |
| MSI GE62               | 1         | 0.6%    |
| Lenovo V15-ADA         | 1         | 0.6%    |
| Lenovo ThinkBook       | 1         | 0.6%    |
| Lenovo Legion          | 1         | 0.6%    |
| Lenovo G50-70          | 1         | 0.6%    |
| Lenovo G405            | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 26        | 15.66%  |
| 2019 | 17        | 10.24%  |
| 2020 | 16        | 9.64%   |
| 2013 | 15        | 9.04%   |
| 2014 | 14        | 8.43%   |
| 2015 | 13        | 7.83%   |
| 2018 | 12        | 7.23%   |
| 2016 | 12        | 7.23%   |
| 2011 | 12        | 7.23%   |
| 2012 | 8         | 4.82%   |
| 2021 | 5         | 3.01%   |
| 2022 | 4         | 2.41%   |
| 2010 | 4         | 2.41%   |
| 2008 | 3         | 1.81%   |
| 2007 | 3         | 1.81%   |
| 2023 | 1         | 0.6%    |
| 2009 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 166       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 150       | 89.82%  |
| Enabled  | 17        | 10.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 166       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 41        | 24.4%   |
| 4.01-8.0    | 40        | 23.81%  |
| 1.01-2.0    | 28        | 16.67%  |
| 8.01-16.0   | 23        | 13.69%  |
| 16.01-24.0  | 19        | 11.31%  |
| 32.01-64.0  | 11        | 6.55%   |
| 24.01-32.0  | 3         | 1.79%   |
| 2.01-3.0    | 1         | 0.6%    |
| 64.01-256.0 | 1         | 0.6%    |
| 0.01-0.5    | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 77        | 42.54%  |
| 2.01-3.0  | 45        | 24.86%  |
| 4.01-8.0  | 22        | 12.15%  |
| 3.01-4.0  | 17        | 9.39%   |
| 0.51-1.0  | 12        | 6.63%   |
| 8.01-16.0 | 6         | 3.31%   |
| 0.01-0.5  | 2         | 1.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 136       | 81.93%  |
| 2      | 29        | 17.47%  |
| 0      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 68.86%  |
| Yes       | 52        | 31.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 63.86%  |
| No        | 60        | 36.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 95.78%  |
| No        | 7         | 4.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 78.92%  |
| No        | 35        | 21.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 166       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 121       | 68.75%  |
| Maldonado              | 9         | 5.11%   |
| Canelones              | 8         | 4.55%   |
| Punta del Este         | 4         | 2.27%   |
| Buceo                  | 3         | 1.7%    |
| Salto                  | 2         | 1.14%   |
| Rocha                  | 2         | 1.14%   |
| Punta Gorda            | 2         | 1.14%   |
| Paysandú              | 2         | 1.14%   |
| Las Piedras            | 2         | 1.14%   |
| El Pinar               | 2         | 1.14%   |
| Ciudad del Plata       | 2         | 1.14%   |
| Solymar                | 1         | 0.57%   |
| San Jose de Mayo       | 1         | 0.57%   |
| Pocitos                | 1         | 0.57%   |
| Pinamar                | 1         | 0.57%   |
| Parque Rodo            | 1         | 0.57%   |
| Nueva Helvecia         | 1         | 0.57%   |
| Minas                  | 1         | 0.57%   |
| Melilla                | 1         | 0.57%   |
| Maronas                | 1         | 0.57%   |
| Las Flores             | 1         | 0.57%   |
| La Paz                 | 1         | 0.57%   |
| Joaquin Suarez         | 1         | 0.57%   |
| El Tesoro              | 1         | 0.57%   |
| Durazno                | 1         | 0.57%   |
| Centro                 | 1         | 0.57%   |
| Barrancas Coloradas    | 1         | 0.57%   |
| Arenas de Jose Ignacio | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 26        | 32     | 13.98%  |
| WDC                         | 24        | 29     | 12.9%   |
| Kingston                    | 23        | 31     | 12.37%  |
| Toshiba                     | 22        | 26     | 11.83%  |
| Seagate                     | 16        | 20     | 8.6%    |
| SanDisk                     | 14        | 16     | 7.53%   |
| Samsung Electronics         | 13        | 13     | 6.99%   |
| Hitachi                     | 7         | 9      | 3.76%   |
| SK hynix                    | 6         | 6      | 3.23%   |
| HGST                        | 6         | 6      | 3.23%   |
| Intel                       | 5         | 5      | 2.69%   |
| Hewlett-Packard             | 3         | 3      | 1.61%   |
| Netac                       | 2         | 3      | 1.08%   |
| KIOXIA                      | 2         | 2      | 1.08%   |
| Kingston Technology Company | 2         | 2      | 1.08%   |
| Crucial                     | 2         | 3      | 1.08%   |
| W800SH                      | 1         | 1      | 0.54%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.54%   |
| SAGE                        | 1         | 2      | 0.54%   |
| Micron Technology           | 1         | 1      | 0.54%   |
| LITEON                      | 1         | 2      | 0.54%   |
| KingFast                    | 1         | 1      | 0.54%   |
| Hikvision                   | 1         | 1      | 0.54%   |
| Gateway                     | 1         | 1      | 0.54%   |
| Dahua                       | 1         | 2      | 0.54%   |
| China                       | 1         | 1      | 0.54%   |
| BIWIN                       | 1         | 1      | 0.54%   |
| BHT                         | 1         | 1      | 0.54%   |
| Apple                       | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 13        | 6.81%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 4.19%   |
| Kingston SA400S37480G 480GB SSD     | 6         | 3.14%   |
| Unknown DA4032  32GB                | 5         | 2.62%   |
| Toshiba MQ01ABD075 752GB            | 4         | 2.09%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 2.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 2.09%   |
| Toshiba MQ01ABF050 500GB            | 3         | 1.57%   |
| Toshiba HDWK105 500GB               | 3         | 1.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 1.57%   |
| SanDisk DF4032  32GB                | 3         | 1.57%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2         | 1.05%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 2         | 1.05%   |
| Unknown SD/MMC/MS PRO 128GB         | 2         | 1.05%   |
| Toshiba MQ01ABD100 1TB              | 2         | 1.05%   |
| SanDisk SSD U100 8GB                | 2         | 1.05%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 1.05%   |
| SanDisk NVMe SSD Drive 1024GB       | 2         | 1.05%   |
| Netac SSD 256GB                     | 2         | 1.05%   |
| Hitachi HTS547564A9E384 640GB       | 2         | 1.05%   |
| HGST HTS545050A7E680 500GB          | 2         | 1.05%   |
| WDC WDS250G2X0C-00L350 250GB        | 1         | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.52%   |
| WDC WD7500BPVX-22JC3T0 752GB        | 1         | 0.52%   |
| WDC WD6400BPVT-75HXZT1 640GB        | 1         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.52%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 1         | 0.52%   |
| WDC WD5000LPVT-24G33T1 500GB        | 1         | 0.52%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.52%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 0.52%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.52%   |
| WDC WD3200LPCX-24C6HT0 320GB        | 1         | 0.52%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1         | 0.52%   |
| WDC WD3200BEVT-26ZCT0 320GB         | 1         | 0.52%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.52%   |
| WDC WD10SPZX-08Z10 1TB              | 1         | 0.52%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 0.52%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.52%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 0.52%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 18        | 23     | 26.47%  |
| Toshiba | 18        | 22     | 26.47%  |
| Seagate | 16        | 20     | 23.53%  |
| Hitachi | 7         | 9      | 10.29%  |
| HGST    | 6         | 6      | 8.82%   |
| Unknown | 2         | 2      | 2.94%   |
| SAGE    | 1         | 2      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 18        | 22     | 36.73%  |
| Samsung Electronics | 6         | 6      | 12.24%  |
| SanDisk             | 4         | 4      | 8.16%   |
| WDC                 | 3         | 3      | 6.12%   |
| Hewlett-Packard     | 3         | 3      | 6.12%   |
| SK hynix            | 2         | 2      | 4.08%   |
| Netac               | 2         | 3      | 4.08%   |
| Intel               | 2         | 2      | 4.08%   |
| W800SH              | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 1      | 2.04%   |
| Hikvision           | 1         | 1      | 2.04%   |
| Gateway             | 1         | 1      | 2.04%   |
| Dahua               | 1         | 2      | 2.04%   |
| Crucial             | 1         | 2      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| BIWIN               | 1         | 1      | 2.04%   |
| BHT                 | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 66        | 84     | 36.46%  |
| SSD     | 47        | 56     | 25.97%  |
| NVMe    | 39        | 46     | 21.55%  |
| MMC     | 28        | 35     | 15.47%  |
| Unknown | 1         | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 104       | 136    | 59.43%  |
| NVMe | 39        | 46     | 22.29%  |
| MMC  | 28        | 35     | 16%     |
| SAS  | 4         | 5      | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 98     | 70.91%  |
| 0.51-1.0   | 31        | 41     | 28.18%  |
| 1.01-2.0   | 1         | 1      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 42        | 24.14%  |
| 101-250        | 39        | 22.41%  |
| 501-1000       | 26        | 14.94%  |
| 21-50          | 23        | 13.22%  |
| 1-20           | 21        | 12.07%  |
| 1001-2000      | 9         | 5.17%   |
| 51-100         | 9         | 5.17%   |
| Unknown        | 4         | 2.3%    |
| More than 3000 | 1         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 45.05%  |
| 21-50          | 34        | 18.68%  |
| 51-100         | 21        | 11.54%  |
| 251-500        | 17        | 9.34%   |
| 101-250        | 15        | 8.24%   |
| 501-1000       | 7         | 3.85%   |
| Unknown        | 4         | 2.2%    |
| More than 3000 | 1         | 0.55%   |
| 1001-2000      | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB                                    | 2         | 2      | 13.33%  |
| WDC WD5000LPCX-24C6HT0 500GB                                    | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-26ZCT0 320GB                                     | 1         | 1      | 6.67%   |
| WDC WD10SPCX-24HWST1 1TB                                        | 1         | 1      | 6.67%   |
| Toshiba MK5059GSXP 500GB                                        | 1         | 2      | 6.67%   |
| Toshiba MK3265GSX 320GB                                         | 1         | 1      | 6.67%   |
| Toshiba MK3259GSXP 320GB                                        | 1         | 1      | 6.67%   |
| Seagate ST980811AS 80GB                                         | 1         | 2      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1         | 1      | 6.67%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                             | 1         | 1      | 6.67%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 256GB | 1         | 1      | 6.67%   |
| Hitachi HTS547564A9E384 640GB                                   | 1         | 1      | 6.67%   |
| HGST HTS545032A7E380 320GB                                      | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 28.57%  |
| Toshiba             | 3         | 4      | 21.43%  |
| Seagate             | 3         | 4      | 21.43%  |
| SanDisk             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

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
| HDD  | 12        | 15     | 85.71%  |
| NVMe | 1         | 1      | 7.14%   |
| SSD  | 1         | 1      | 7.14%   |

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
| Detected | 106       | 139    | 62.72%  |
| Works    | 49        | 66     | 28.99%  |
| Malfunc  | 14        | 17     | 8.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 112       | 63.28%  |
| AMD                              | 28        | 15.82%  |
| SanDisk                          | 10        | 5.65%   |
| Samsung Electronics              | 7         | 3.95%   |
| Kingston Technology Company      | 6         | 3.39%   |
| Toshiba America Info Systems     | 4         | 2.26%   |
| SK hynix                         | 3         | 1.69%   |
| Union Memory (Shenzhen)          | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Micron/Crucial Technology        | 1         | 0.56%   |
| Micron Technology                | 1         | 0.56%   |
| Lite-On Technology               | 1         | 0.56%   |
| KIOXIA                           | 1         | 0.56%   |
| Apple                            | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 13.59%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 9.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 5.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 4.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 3.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 3.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.63%   |
| Intel SSD 660P Series                                                            | 3         | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.09%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 1.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.09%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                            | 1         | 0.54%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.54%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.54%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                            | 1         | 0.54%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 125       | 69.06%  |
| NVMe | 39        | 21.55%  |
| RAID | 10        | 5.52%   |
| IDE  | 7         | 3.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 130       | 78.31%  |
| AMD    | 36        | 21.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 10.24%  |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 1.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 3         | 1.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 3         | 1.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 1.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 1.81%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 3         | 1.81%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 3         | 1.81%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 1.81%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 1.81%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.2%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 1.2%    |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.2%    |
| Intel Core i5-3230M CPU @ 2.60GHz            | 2         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.2%    |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.2%    |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.2%    |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.2%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.2%    |
| Intel Atom CPU Z3735F @ 1.33GHz              | 2         | 1.2%    |
| Intel 12th Gen Core i7-1255U                 | 2         | 1.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics       | 2         | 1.2%    |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.2%    |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 2         | 1.2%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.6%    |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.6%    |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.6%    |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.6%    |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.6%    |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.6%    |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.6%    |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 34        | 20.48%  |
| Intel Core i5      | 31        | 18.67%  |
| Intel Core i7      | 26        | 15.66%  |
| Intel Core i3      | 14        | 8.43%   |
| Other              | 9         | 5.42%   |
| Intel Pentium      | 7         | 4.22%   |
| Intel Atom         | 7         | 4.22%   |
| AMD A6             | 6         | 3.61%   |
| AMD Ryzen 9        | 5         | 3.01%   |
| AMD Ryzen 7        | 3         | 1.81%   |
| AMD E              | 3         | 1.81%   |
| Intel Genuine      | 2         | 1.2%    |
| Intel Core 2 Duo   | 2         | 1.2%    |
| AMD Ryzen 5        | 2         | 1.2%    |
| AMD Ryzen 3        | 2         | 1.2%    |
| AMD E1             | 2         | 1.2%    |
| AMD A8             | 2         | 1.2%    |
| Intel Pentium Dual | 1         | 0.6%    |
| AMD Ryzen 5 PRO    | 1         | 0.6%    |
| AMD Phenom II      | 1         | 0.6%    |
| AMD FX             | 1         | 0.6%    |
| AMD E2             | 1         | 0.6%    |
| AMD Athlon II      | 1         | 0.6%    |
| AMD Athlon         | 1         | 0.6%    |
| AMD A4             | 1         | 0.6%    |
| AMD A10            | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 97        | 58.43%  |
| 4      | 48        | 28.92%  |
| 6      | 8         | 4.82%   |
| 8      | 7         | 4.22%   |
| 1      | 4         | 2.41%   |
| 10     | 2         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 166       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 95        | 57.23%  |
| 1      | 71        | 42.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 163       | 98.19%  |
| Unknown        | 3         | 1.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 28.65%  |
| 0x406c4    | 7         | 4.09%   |
| 0x206a7    | 7         | 4.09%   |
| 0x506c9    | 6         | 3.51%   |
| 0x40651    | 6         | 3.51%   |
| 0x806ec    | 5         | 2.92%   |
| 0x406e3    | 5         | 2.92%   |
| 0x306d4    | 5         | 2.92%   |
| 0x20655    | 5         | 2.92%   |
| 0x806ea    | 4         | 2.34%   |
| 0x806e9    | 4         | 2.34%   |
| 0x406c3    | 4         | 2.34%   |
| 0x30678    | 4         | 2.34%   |
| 0x906ea    | 3         | 1.75%   |
| 0x806c1    | 3         | 1.75%   |
| 0x6fd      | 3         | 1.75%   |
| 0x306c3    | 3         | 1.75%   |
| 0x306a9    | 3         | 1.75%   |
| 0x08108109 | 3         | 1.75%   |
| 0x06006705 | 3         | 1.75%   |
| 0x706e5    | 2         | 1.17%   |
| 0x706a1    | 2         | 1.17%   |
| 0x506e3    | 2         | 1.17%   |
| 0x0a50000c | 2         | 1.17%   |
| 0x08600104 | 2         | 1.17%   |
| 0x0810100b | 2         | 1.17%   |
| 0x07030105 | 2         | 1.17%   |
| 0x07030104 | 2         | 1.17%   |
| 0x0700010f | 2         | 1.17%   |
| 0xa0652    | 1         | 0.58%   |
| 0x806eb    | 1         | 0.58%   |
| 0x30673    | 1         | 0.58%   |
| 0x30661    | 1         | 0.58%   |
| 0x106e5    | 1         | 0.58%   |
| 0x106ca    | 1         | 0.58%   |
| 0x1067a    | 1         | 0.58%   |
| 0x10676    | 1         | 0.58%   |
| 0x10661    | 1         | 0.58%   |
| 0x0a704103 | 1         | 0.58%   |
| 0x08600102 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 20        | 12.05%  |
| KabyLake      | 20        | 12.05%  |
| Goldmont      | 17        | 10.24%  |
| Haswell       | 11        | 6.63%   |
| Skylake       | 9         | 5.42%   |
| SandyBridge   | 9         | 5.42%   |
| Broadwell     | 8         | 4.82%   |
| IvyBridge     | 7         | 4.22%   |
| Puma          | 6         | 3.61%   |
| Excavator     | 6         | 3.61%   |
| Zen 2         | 5         | 3.01%   |
| Westmere      | 5         | 3.01%   |
| Zen+          | 4         | 2.41%   |
| TigerLake     | 4         | 2.41%   |
| Core          | 4         | 2.41%   |
| Unknown       | 4         | 2.41%   |
| IceLake       | 3         | 1.81%   |
| CometLake     | 3         | 1.81%   |
| Bobcat        | 3         | 1.81%   |
| Zen 3         | 2         | 1.2%    |
| Zen           | 2         | 1.2%    |
| Piledriver    | 2         | 1.2%    |
| Penryn        | 2         | 1.2%    |
| K10           | 2         | 1.2%    |
| Jaguar        | 2         | 1.2%    |
| Goldmont plus | 2         | 1.2%    |
| Bonnell       | 2         | 1.2%    |
| Tremont       | 1         | 0.6%    |
| Nehalem       | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 128       | 65.98%  |
| AMD                              | 44        | 22.68%  |
| Nvidia                           | 21        | 10.82%  |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 8.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 7.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.52%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.51%   |
| AMD Renoir                                                                               | 5         | 2.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.01%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.01%   |
| Intel HD Graphics 620                                                                    | 4         | 2.01%   |
| Intel HD Graphics 530                                                                    | 4         | 2.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.01%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.01%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.51%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.51%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.01%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 2         | 1.01%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.01%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.01%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.01%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.5%    |
| Nvidia TU117M                                                                            | 1         | 0.5%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 106       | 63.86%  |
| 1 x AMD        | 28        | 16.87%  |
| Intel + Nvidia | 14        | 8.43%   |
| Intel + AMD    | 8         | 4.82%   |
| AMD + Nvidia   | 6         | 3.61%   |
| 2 x AMD        | 2         | 1.2%    |
| 1 x SiS        | 1         | 0.6%    |
| 1 x Nvidia     | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 151       | 90.42%  |
| Proprietary | 14        | 8.38%   |
| Unknown     | 2         | 1.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 72.62%  |
| 0.01-0.5   | 17        | 10.12%  |
| 0.51-1.0   | 11        | 6.55%   |
| 1.01-2.0   | 10        | 5.95%   |
| 3.01-4.0   | 6         | 3.57%   |
| 5.01-6.0   | 2         | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 30        | 16.39%  |
| Chimei Innolux          | 27        | 14.75%  |
| AU Optronics            | 24        | 13.11%  |
| BOE                     | 23        | 12.57%  |
| Samsung Electronics     | 19        | 10.38%  |
| InfoVision              | 8         | 4.37%   |
| KDC                     | 7         | 3.83%   |
| ViewSonic               | 4         | 2.19%   |
| Sharp                   | 4         | 2.19%   |
| PANDA                   | 4         | 2.19%   |
| Dell                    | 4         | 2.19%   |
| Chi Mei Optoelectronics | 4         | 2.19%   |
| Acer                    | 3         | 1.64%   |
| LG Philips              | 2         | 1.09%   |
| KTC                     | 2         | 1.09%   |
| HSI                     | 2         | 1.09%   |
| Apple                   | 2         | 1.09%   |
| Valve                   | 1         | 0.55%   |
| Toshiba                 | 1         | 0.55%   |
| TMX                     | 1         | 0.55%   |
| Sun                     | 1         | 0.55%   |
| Mi                      | 1         | 0.55%   |
| Konka                   | 1         | 0.55%   |
| JDI                     | 1         | 0.55%   |
| InnoLux Display         | 1         | 0.55%   |
| HKC                     | 1         | 0.55%   |
| Hewlett-Packard         | 1         | 0.55%   |
| Goldstar                | 1         | 0.55%   |
| CPT                     | 1         | 0.55%   |
| AOC                     | 1         | 0.55%   |
| Ancor Communications    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch           | 6         | 3.23%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 5         | 2.69%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 1.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 1.61%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 1.08%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 1.08%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 1.08%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.08%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 1.08%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 1.08%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 2         | 1.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.08%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.08%   |
| HSI LED-TV HSI0001 1920x1080 708x398mm 32.0-inch                      | 2         | 1.08%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch       | 2         | 1.08%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.08%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch         | 1         | 0.54%   |
| ViewSonic VSD220 VSC2CB2 1920x1080 477x268mm 21.5-inch                | 1         | 0.54%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.54%   |
| Toshiba no-audio-HD TSB8888 1080x1920 1080x1920mm 86.7-inch           | 1         | 0.54%   |
| TMX TL140ADXP02-0 TMX1401 2560x1600 301x188mm 14.0-inch               | 1         | 0.54%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.54%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.54%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.54%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.54%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 85        | 51.83%  |
| 1920x1080 (FHD)   | 44        | 26.83%  |
| 1600x900 (HD+)    | 8         | 4.88%   |
| 1920x1200 (WUXGA) | 7         | 4.27%   |
| 3840x2160 (4K)    | 5         | 3.05%   |
| 2560x1440 (QHD)   | 4         | 2.44%   |
| 1280x800 (WXGA)   | 4         | 2.44%   |
| 2560x1600         | 2         | 1.22%   |
| 800x1280          | 1         | 0.61%   |
| 2288x1287         | 1         | 0.61%   |
| 2160x1440         | 1         | 0.61%   |
| 1360x768          | 1         | 0.61%   |
| 1024x600          | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 79        | 42.93%  |
| 14     | 29        | 15.76%  |
| 13     | 25        | 13.59%  |
| 11     | 8         | 4.35%   |
| 21     | 7         | 3.8%    |
| 17     | 7         | 3.8%    |
| 23     | 6         | 3.26%   |
| 24     | 4         | 2.17%   |
| 18     | 3         | 1.63%   |
| 40     | 2         | 1.09%   |
| 34     | 2         | 1.09%   |
| 27     | 2         | 1.09%   |
| 12     | 2         | 1.09%   |
| 10     | 2         | 1.09%   |
| 86     | 1         | 0.54%   |
| 57     | 1         | 0.54%   |
| 52     | 1         | 0.54%   |
| 29     | 1         | 0.54%   |
| 26     | 1         | 0.54%   |
| 7      | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 123       | 67.58%  |
| 201-300     | 19        | 10.44%  |
| 501-600     | 13        | 7.14%   |
| 401-500     | 10        | 5.49%   |
| 351-400     | 8         | 4.4%    |
| 1001-1500   | 3         | 1.65%   |
| 801-900     | 2         | 1.1%    |
| 701-800     | 2         | 1.1%    |
| 601-700     | 1         | 0.55%   |
| 1-100       | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 141       | 90.97%  |
| 16/10 | 9         | 5.81%   |
| 21/9  | 2         | 1.29%   |
| 3/2   | 1         | 0.65%   |
| 0.67  | 1         | 0.65%   |
| 0.56  | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 79        | 42.7%   |
| 81-90          | 49        | 26.49%  |
| 201-250        | 16        | 8.65%   |
| 51-60          | 8         | 4.32%   |
| 121-130        | 7         | 3.78%   |
| 71-80          | 5         | 2.7%    |
| More than 1000 | 3         | 1.62%   |
| 351-500        | 3         | 1.62%   |
| 301-350        | 3         | 1.62%   |
| 141-150        | 3         | 1.62%   |
| 61-70          | 2         | 1.08%   |
| 41-50          | 2         | 1.08%   |
| 151-200        | 2         | 1.08%   |
| 501-1000       | 2         | 1.08%   |
| 1-40           | 1         | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 91        | 50.84%  |
| 121-160       | 45        | 25.14%  |
| 51-100        | 28        | 15.64%  |
| 161-240       | 10        | 5.59%   |
| 1-50          | 3         | 1.68%   |
| More than 240 | 2         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 135       | 78.95%  |
| 2     | 29        | 16.96%  |
| 3     | 4         | 2.34%   |
| 0     | 3         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 79        | 32.11%  |
| Intel                            | 77        | 31.3%   |
| Qualcomm Atheros                 | 36        | 14.63%  |
| Broadcom                         | 21        | 8.54%   |
| MediaTek                         | 6         | 2.44%   |
| Ralink Technology                | 5         | 2.03%   |
| TP-Link                          | 3         | 1.22%   |
| Ralink                           | 3         | 1.22%   |
| Broadcom Limited                 | 3         | 1.22%   |
| Samsung Electronics              | 2         | 0.81%   |
| ASIX Electronics                 | 2         | 0.81%   |
| Xiaomi                           | 1         | 0.41%   |
| T & A Mobile Phones              | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Sierra Wireless                  | 1         | 0.41%   |
| Qualcomm Atheros Communications  | 1         | 0.41%   |
| Marvell Technology Group         | 1         | 0.41%   |
| Lenovo                           | 1         | 0.41%   |
| Huawei Technologies              | 1         | 0.41%   |
| DisplayLink                      | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 38        | 13.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 9.15%   |
| Intel Wireless 3165                                                     | 25        | 8.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.11%   |
| Intel Wireless 7265                                                     | 6         | 2.11%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 1.76%   |
| Intel Wireless 7260                                                     | 5         | 1.76%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.76%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.41%   |
| Intel Wireless 8260                                                     | 4         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.41%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.06%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.7%    |
| Intel Wireless 3160                                                     | 2         | 0.7%    |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.7%    |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.7%    |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 44.38%  |
| Realtek Semiconductor           | 31        | 18.34%  |
| Qualcomm Atheros                | 29        | 17.16%  |
| Broadcom                        | 15        | 8.88%   |
| Ralink Technology               | 5         | 2.96%   |
| MediaTek                        | 5         | 2.96%   |
| Ralink                          | 3         | 1.78%   |
| TP-Link                         | 2         | 1.18%   |
| Broadcom Limited                | 2         | 1.18%   |
| Sierra Wireless                 | 1         | 0.59%   |
| Qualcomm Atheros Communications | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 25        | 14.71%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 5.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 4.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.53%   |
| Intel Wireless 7265                                                     | 6         | 3.53%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 2.94%   |
| Intel Wireless 7260                                                     | 5         | 2.94%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.94%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.35%   |
| Intel Wireless 8260                                                     | 4         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.35%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| Intel Wireless 3160                                                     | 2         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.18%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.59%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.59%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.59%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.59%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.59%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 67        | 58.77%  |
| Intel                            | 16        | 14.04%  |
| Qualcomm Atheros                 | 9         | 7.89%   |
| Broadcom                         | 8         | 7.02%   |
| Samsung Electronics              | 2         | 1.75%   |
| ASIX Electronics                 | 2         | 1.75%   |
| Xiaomi                           | 1         | 0.88%   |
| TP-Link                          | 1         | 0.88%   |
| T & A Mobile Phones              | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| MediaTek                         | 1         | 0.88%   |
| Marvell Technology Group         | 1         | 0.88%   |
| Lenovo                           | 1         | 0.88%   |
| Huawei Technologies              | 1         | 0.88%   |
| DisplayLink                      | 1         | 0.88%   |
| Broadcom Limited                 | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 22.81%  |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.88%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.88%   |
| T & A Mobile Phones Alcatel 3X                                    | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.88%   |
| Samsung Kiera                                                     | 1         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.88%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.88%   |
| MediaTek Infinix SMART 6 HD                                       | 1         | 0.88%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.88%   |
| Lenovo USB-C to LAN                                               | 1         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.88%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.88%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.88%   |
| Huawei E353/E3131                                                 | 1         | 0.88%   |
| DisplayLink Plugable UD-3900                                      | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.88%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 60%     |
| Ethernet | 106       | 40%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 87.5%   |
| Ethernet | 21        | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 96        | 57.83%  |
| 1     | 64        | 38.55%  |
| 0     | 5         | 3.01%   |
| 3     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 71.26%  |
| Yes  | 48        | 28.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 50%     |
| Realtek Semiconductor           | 15        | 11.36%  |
| Qualcomm Atheros Communications | 11        | 8.33%   |
| IMC Networks                    | 9         | 6.82%   |
| Toshiba                         | 7         | 5.3%    |
| Foxconn / Hon Hai               | 5         | 3.79%   |
| Broadcom                        | 5         | 3.79%   |
| Lite-On Technology              | 4         | 3.03%   |
| Cambridge Silicon Radio         | 3         | 2.27%   |
| Ralink                          | 2         | 1.52%   |
| Apple                           | 2         | 1.52%   |
| Ralink Technology               | 1         | 0.76%   |
| Foxconn International           | 1         | 0.76%   |
| Alps Electric                   | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 41        | 31.06%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 5.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 4.55%   |
| Intel AX201 Bluetooth                               | 6         | 4.55%   |
| Realtek Bluetooth Radio                             | 5         | 3.79%   |
| Intel AX200 Bluetooth                               | 5         | 3.79%   |
| Toshiba Bluetooth Device                            | 3         | 2.27%   |
| Toshiba BCM43142A0                                  | 3         | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.27%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.27%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.52%   |
| Lite-On Bluetooth Device                            | 2         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.52%   |
| Intel Bluetooth Device                              | 2         | 1.52%   |
| IMC Networks Wireless_Device                        | 2         | 1.52%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.52%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.52%   |
| Toshiba Bluetooth Radio                             | 1         | 0.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.76%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.76%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.76%   |
| IMC Networks Bluetooth Device                       | 1         | 0.76%   |
| IMC Networks Bluetooth                              | 1         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.76%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.76%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.76%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.76%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 124       | 66.31%  |
| AMD                                  | 36        | 19.25%  |
| Nvidia                               | 14        | 7.49%   |
| Logitech                             | 4         | 2.14%   |
| Generalplus Technology               | 2         | 1.07%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.53%   |
| Texas Instruments                    | 1         | 0.53%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.53%   |
| Kingston Technology                  | 1         | 0.53%   |
| DSEA A/S                             | 1         | 0.53%   |
| C-Media Electronics                  | 1         | 0.53%   |
| ASUSTek Computer                     | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 7.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 5.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 5.42%   |
| AMD FCH Azalia Controller                                                                         | 12        | 5%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 4.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 4.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 3.33%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.5%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 2.08%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.67%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.25%   |
| Logitech H390 headset with microphone                                                             | 2         | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.83%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.83%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.83%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.83%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 27.84%  |
| SK hynix            | 15        | 15.46%  |
| Micron Technology   | 15        | 15.46%  |
| Ramaxel Technology  | 7         | 7.22%   |
| Unknown             | 6         | 6.19%   |
| Goldkey             | 6         | 6.19%   |
| Crucial             | 6         | 6.19%   |
| Kingston            | 5         | 5.15%   |
| Elpida              | 3         | 3.09%   |
| A-DATA Technology   | 3         | 3.09%   |
| Nanya Technology    | 2         | 2.06%   |
| Team                | 1         | 1.03%   |
| Patriot             | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 4         | 3.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 2.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 2.97%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 1.98%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 1.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 1.98%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 1.98%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 1.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 1.98%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.98%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.98%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 1.98%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.98%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 1.98%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.99%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1         | 0.99%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s          | 1         | 0.99%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.99%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 0.99%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.99%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s     | 1         | 0.99%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s     | 1         | 0.99%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s        | 1         | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 0.99%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 0.99%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s         | 1         | 0.99%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 0.99%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 0.99%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                      | 1         | 0.99%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.99%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s         | 1         | 0.99%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 0.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 38        | 47.5%   |
| DDR4   | 30        | 37.5%   |
| LPDDR4 | 3         | 3.75%   |
| LPDDR3 | 3         | 3.75%   |
| DDR2   | 3         | 3.75%   |
| SDRAM  | 2         | 2.5%    |
| DDR5   | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 88.46%  |
| Row Of Chips | 7         | 8.97%   |
| DIMM         | 2         | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 29        | 31.18%  |
| 8192  | 27        | 29.03%  |
| 2048  | 17        | 18.28%  |
| 16384 | 12        | 12.9%   |
| 32768 | 5         | 5.38%   |
| 1024  | 2         | 2.15%   |
| 512   | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 33        | 37.08%  |
| 2667  | 16        | 17.98%  |
| 3200  | 10        | 11.24%  |
| 2400  | 6         | 6.74%   |
| 1334  | 5         | 5.62%   |
| 2133  | 4         | 4.49%   |
| 3266  | 3         | 3.37%   |
| 1333  | 3         | 3.37%   |
| 533   | 3         | 3.37%   |
| 4199  | 2         | 2.25%   |
| 4800  | 1         | 1.12%   |
| 4267  | 1         | 1.12%   |
| 1867  | 1         | 1.12%   |
| 1067  | 1         | 1.12%   |

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
| Chicony Electronics                    | 42        | 27.45%  |
| Realtek Semiconductor                  | 16        | 10.46%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 9.15%   |
| Microdia                               | 9         | 5.88%   |
| Sunplus Innovation Technology          | 8         | 5.23%   |
| Bison Electronics                      | 8         | 5.23%   |
| Suyin                                  | 7         | 4.58%   |
| IMC Networks                           | 7         | 4.58%   |
| Unknown                                | 5         | 3.27%   |
| Silicon Motion                         | 4         | 2.61%   |
| Quanta                                 | 4         | 2.61%   |
| Acer                                   | 4         | 2.61%   |
| Sonix Technology                       | 3         | 1.96%   |
| Samsung Electronics                    | 3         | 1.96%   |
| Luxvisions Innotech Limited            | 3         | 1.96%   |
| Lite-On Technology                     | 3         | 1.96%   |
| Importek                               | 3         | 1.96%   |
| Alcor Micro                            | 3         | 1.96%   |
| Syntek                                 | 2         | 1.31%   |
| Primax Electronics                     | 1         | 0.65%   |
| Novatek Microelectronics               | 1         | 0.65%   |
| Logitech                               | 1         | 0.65%   |
| DigiTech                               | 1         | 0.65%   |
| Apple                                  | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 16        | 10.46%  |
| Chicony Integrated Camera                                      | 7         | 4.58%   |
| Unknown USB Camera                                             | 5         | 3.27%   |
| Chicony HP Truevision HD                                       | 5         | 3.27%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.61%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.61%   |
| Chicony Web Camera - HD                                        | 4         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.61%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 3         | 1.96%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.96%   |
| Chicony HD WebCam                                              | 3         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.96%   |
| Bison Integrated Camera                                        | 3         | 1.96%   |
| Acer Integrated Camera                                         | 3         | 1.96%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 1.31%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.31%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.31%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.31%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 1.31%   |
| Lite-On Integrated Camera                                      | 2         | 1.31%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.31%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.31%   |
| IMC Networks Integrated Camera                                 | 2         | 1.31%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.31%   |
| Bison HD Webcam                                                | 2         | 1.31%   |
| Syntek Integrated Camera                                       | 1         | 0.65%   |
| Syntek EasyCamera                                              | 1         | 0.65%   |
| Suyin VGA Webcam                                               | 1         | 0.65%   |
| Suyin HP Truevision HD                                         | 1         | 0.65%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.65%   |
| Suyin HD WebCam                                                | 1         | 0.65%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.65%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.65%   |
| Sunplus MTD camera                                             | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.65%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 42.11%  |
| Synaptics                  | 3         | 15.79%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Upek                       | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Focal-systems.Corp         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 15.79%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 15.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| Synaptics UWP WBDI Device                              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5.26%   |
| Elan WBF Fingerprint Sensor                            | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.26%   |

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
| 0     | 130       | 77.38%  |
| 1     | 35        | 20.83%  |
| 2     | 2         | 1.19%   |
| 3     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 42.86%  |
| Net/wireless          | 6         | 14.29%  |
| Multimedia controller | 5         | 11.9%   |
| Graphics card         | 5         | 11.9%   |
| Chipcard              | 3         | 7.14%   |
| Storage               | 2         | 4.76%   |
| Bluetooth             | 2         | 4.76%   |
| Modem                 | 1         | 2.38%   |


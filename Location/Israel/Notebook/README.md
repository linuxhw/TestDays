Linux in Israel - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

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

Total: 382

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Dell          | XPS 15 7590                 | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| Lenovo        | G50-80 80L0                 | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Lenovo        | 3000 G530 4151/200          | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| Dell          | G7 7500                     | [f5e6475121](https://linux-hardware.org/?probe=f5e6475121) | Jul 22, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [8f556b89fc](https://linux-hardware.org/?probe=8f556b89fc) | Jul 16, 2022 |
| ASUSTek       | G53JW                       | [2090800f5c](https://linux-hardware.org/?probe=2090800f5c) | Jul 06, 2022 |
| HP            | ProBook 430 G6              | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [755c2fc534](https://linux-hardware.org/?probe=755c2fc534) | Jun 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9cf3c1f84c](https://linux-hardware.org/?probe=9cf3c1f84c) | Jun 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Purism        | Librem 14                   | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Dell          | XPS 15 9570                 | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| Lenovo        | Unknown                     | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1c8e5b49d3](https://linux-hardware.org/?probe=1c8e5b49d3) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [00d3a71a00](https://linux-hardware.org/?probe=00d3a71a00) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| ASUSTek       | N550JV                      | [8a1f2ffc65](https://linux-hardware.org/?probe=8a1f2ffc65) | May 20, 2022 |
| ASUSTek       | N550JV                      | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| Dell          | Inspiron 5577               | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Lenovo        | V14-IIL 82C4                | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| Dell          | Vostro 5402                 | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| Dell          | Latitude 7400               | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Acer          | Aspire V7-482PG             | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| Acer          | Aspire 5755G                | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Dell          | XPS 15 9570                 | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Acer          | Aspire 5820                 | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | N550JV                      | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| Dell          | Studio 1555                 | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Dell          | Latitude 3350               | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Acer          | Aspire 5755G                | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ba96dd251c](https://linux-hardware.org/?probe=ba96dd251c) | Nov 17, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | BU403UAV                    | [cb7fcf5c15](https://linux-hardware.org/?probe=cb7fcf5c15) | Nov 15, 2021 |
| ASUSTek       | GL502VMK                    | [78bc4b00c0](https://linux-hardware.org/?probe=78bc4b00c0) | Nov 12, 2021 |
| Dell          | XPS 15 9510                 | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| Dell          | Latitude 5410               | [35fd3a8949](https://linux-hardware.org/?probe=35fd3a8949) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [c5e111be13](https://linux-hardware.org/?probe=c5e111be13) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [6cc81555db](https://linux-hardware.org/?probe=6cc81555db) | Nov 04, 2021 |
| Dell          | System Inspiron N7110       | [3f5d6aaab8](https://linux-hardware.org/?probe=3f5d6aaab8) | Oct 26, 2021 |
| Lenovo        | G40-70 20369                | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| Dell          | Inspiron 3593               | [28136dcca0](https://linux-hardware.org/?probe=28136dcca0) | Oct 13, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [267712392b](https://linux-hardware.org/?probe=267712392b) | Oct 11, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Dell          | Inspiron 3521               | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| Dell          | Latitude 5420               | [a31b3507c4](https://linux-hardware.org/?probe=a31b3507c4) | Sep 26, 2021 |
| Dell          | Latitude 5420               | [a077664ed2](https://linux-hardware.org/?probe=a077664ed2) | Sep 26, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| Lenovo        | G40-70 20369                | [e79a9eb09d](https://linux-hardware.org/?probe=e79a9eb09d) | Sep 22, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Dell          | Vostro 7590                 | [8f4e694845](https://linux-hardware.org/?probe=8f4e694845) | Sep 10, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ProBook 4520s               | [4f947f1b22](https://linux-hardware.org/?probe=4f947f1b22) | Sep 06, 2021 |
| HP            | ProBook 4520s               | [fac0dbdf09](https://linux-hardware.org/?probe=fac0dbdf09) | Sep 06, 2021 |
| HP            | Spectre Notebook            | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| Apple         | MacBookPro12,1              | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| HP            | Compaq Presario CQ61        | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [17afc04962](https://linux-hardware.org/?probe=17afc04962) | Aug 16, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [0ca5c5faa2](https://linux-hardware.org/?probe=0ca5c5faa2) | Aug 11, 2021 |
| IP3 Tech      | AP1                         | [b27a94c64c](https://linux-hardware.org/?probe=b27a94c64c) | Aug 08, 2021 |
| Dell          | Latitude 5410               | [4f2e0ccb9f](https://linux-hardware.org/?probe=4f2e0ccb9f) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [37cbdcae11](https://linux-hardware.org/?probe=37cbdcae11) | Aug 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| Dell          | Latitude 5410               | [73c46f7a65](https://linux-hardware.org/?probe=73c46f7a65) | Aug 01, 2021 |
| Dell          | Latitude 5410               | [8357a0ce64](https://linux-hardware.org/?probe=8357a0ce64) | Aug 01, 2021 |
| HP            | Unknown                     | [f048334d4b](https://linux-hardware.org/?probe=f048334d4b) | Jul 21, 2021 |
| Dell          | Latitude E4300              | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| Apple         | MacBookAir4,2               | [d479a6fd61](https://linux-hardware.org/?probe=d479a6fd61) | Jun 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [13ed380099](https://linux-hardware.org/?probe=13ed380099) | Jun 24, 2021 |
| HP            | Notebook                    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| HP            | Notebook                    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Dell          | Vostro 5590                 | [debb5f4ac5](https://linux-hardware.org/?probe=debb5f4ac5) | Jun 07, 2021 |
| Acer          | Aspire 4333                 | [9f3738469d](https://linux-hardware.org/?probe=9f3738469d) | May 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe368312c](https://linux-hardware.org/?probe=6fe368312c) | May 15, 2021 |
| Lenovo        | G510 20238                  | [9497cc9d85](https://linux-hardware.org/?probe=9497cc9d85) | May 15, 2021 |
| Dell          | Latitude E4300              | [7ed9015fd5](https://linux-hardware.org/?probe=7ed9015fd5) | May 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [ab559fd00d](https://linux-hardware.org/?probe=ab559fd00d) | May 09, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c72aec456a](https://linux-hardware.org/?probe=c72aec456a) | May 06, 2021 |
| LG Electro... | 15Z980-A.AAS8U1             | [2a68dcd848](https://linux-hardware.org/?probe=2a68dcd848) | May 03, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [ca15c642d7](https://linux-hardware.org/?probe=ca15c642d7) | Apr 08, 2021 |
| Dell          | Inspiron 5755               | [fefe0c7d71](https://linux-hardware.org/?probe=fefe0c7d71) | Apr 01, 2021 |
| Dell          | Inspiron 3593               | [4cc755d1c2](https://linux-hardware.org/?probe=4cc755d1c2) | Mar 25, 2021 |
| HP            | Compaq Presario CQ61        | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Dell          | XPS 13 9370                 | [f71120521c](https://linux-hardware.org/?probe=f71120521c) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [edf6ab636e](https://linux-hardware.org/?probe=edf6ab636e) | Mar 19, 2021 |
| HP            | ZBook 15 G3                 | [fa7b8613f2](https://linux-hardware.org/?probe=fa7b8613f2) | Mar 16, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a50f9abd26](https://linux-hardware.org/?probe=a50f9abd26) | Mar 11, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a55964d5d9](https://linux-hardware.org/?probe=a55964d5d9) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HUAWEI        | HN-WX9X                     | [fb3d2fc3e9](https://linux-hardware.org/?probe=fb3d2fc3e9) | Mar 03, 2021 |
| HP            | ZBook 15 G6                 | [061392ad81](https://linux-hardware.org/?probe=061392ad81) | Mar 01, 2021 |
| ASUSTek       | GL503VD                     | [d03b00803b](https://linux-hardware.org/?probe=d03b00803b) | Feb 27, 2021 |
| Apple         | MacBookPro9,2               | [618d47c042](https://linux-hardware.org/?probe=618d47c042) | Feb 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2fff8b3674](https://linux-hardware.org/?probe=2fff8b3674) | Feb 24, 2021 |
| HUAWEI        | HN-WX9X                     | [2b4a74a520](https://linux-hardware.org/?probe=2b4a74a520) | Feb 16, 2021 |
| HUAWEI        | HN-WX9X                     | [f4c77fc7dc](https://linux-hardware.org/?probe=f4c77fc7dc) | Feb 16, 2021 |
| HP            | Compaq Presario CQ61        | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [a2ab510560](https://linux-hardware.org/?probe=a2ab510560) | Feb 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8711f89b6b](https://linux-hardware.org/?probe=8711f89b6b) | Feb 13, 2021 |
| HP            | Compaq Presario CQ61        | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [655d6c5817](https://linux-hardware.org/?probe=655d6c5817) | Feb 06, 2021 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [799c676c40](https://linux-hardware.org/?probe=799c676c40) | Feb 04, 2021 |
| Lenovo        | ThinkPad E550 20DF004RIV    | [23140cf3f9](https://linux-hardware.org/?probe=23140cf3f9) | Jan 29, 2021 |
| Lenovo        | G40-70 20369                | [1763668816](https://linux-hardware.org/?probe=1763668816) | Jan 29, 2021 |
| Dell          | Latitude E6420              | [9aa53da922](https://linux-hardware.org/?probe=9aa53da922) | Jan 19, 2021 |
| Dell          | Latitude E6420              | [20a4b3769d](https://linux-hardware.org/?probe=20a4b3769d) | Jan 19, 2021 |
| Dell          | XPS 13 9370                 | [4df2203870](https://linux-hardware.org/?probe=4df2203870) | Jan 19, 2021 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [65724a4aa6](https://linux-hardware.org/?probe=65724a4aa6) | Jan 18, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [23a9e9c5f6](https://linux-hardware.org/?probe=23a9e9c5f6) | Jan 17, 2021 |
| HP            | Pavilion Notebook           | [750413cc61](https://linux-hardware.org/?probe=750413cc61) | Jan 16, 2021 |
| HP            | EliteBook 840 G5            | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Dell          | Inspiron 13-5378            | [94b70d7578](https://linux-hardware.org/?probe=94b70d7578) | Jan 12, 2021 |
| HP            | Pavilion Notebook           | [c1eeffc9d8](https://linux-hardware.org/?probe=c1eeffc9d8) | Jan 08, 2021 |
| Dell          | Inspiron 5567               | [0d62d918c5](https://linux-hardware.org/?probe=0d62d918c5) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | [5a3a67e5c3](https://linux-hardware.org/?probe=5a3a67e5c3) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | [f37800ed52](https://linux-hardware.org/?probe=f37800ed52) | Jan 07, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [b8bab31c57](https://linux-hardware.org/?probe=b8bab31c57) | Jan 06, 2021 |
| Dell          | Inspiron 13-5378            | [d55bf78096](https://linux-hardware.org/?probe=d55bf78096) | Jan 06, 2021 |
| Unknown       | Unknown                     | [b364724e53](https://linux-hardware.org/?probe=b364724e53) | Jan 02, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8d338ea73c](https://linux-hardware.org/?probe=8d338ea73c) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [ef84edb346](https://linux-hardware.org/?probe=ef84edb346) | Dec 31, 2020 |
| HP            | EliteBook 2570p             | [2ed921327b](https://linux-hardware.org/?probe=2ed921327b) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [9448ec4439](https://linux-hardware.org/?probe=9448ec4439) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [7cd92f4564](https://linux-hardware.org/?probe=7cd92f4564) | Dec 30, 2020 |
| Unknown       | Unknown                     | [749c45e229](https://linux-hardware.org/?probe=749c45e229) | Dec 29, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [01024cf86e](https://linux-hardware.org/?probe=01024cf86e) | Dec 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [66fd37cef4](https://linux-hardware.org/?probe=66fd37cef4) | Dec 27, 2020 |
| Dell          | Inspiron 3542               | [c79668f190](https://linux-hardware.org/?probe=c79668f190) | Dec 24, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [56b69fe95e](https://linux-hardware.org/?probe=56b69fe95e) | Dec 23, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [ddc1a4457d](https://linux-hardware.org/?probe=ddc1a4457d) | Dec 22, 2020 |
| HP            | Pavilion g6                 | [8d41f37972](https://linux-hardware.org/?probe=8d41f37972) | Dec 18, 2020 |
| Unknown       | Unknown                     | [e42b0f86e0](https://linux-hardware.org/?probe=e42b0f86e0) | Dec 14, 2020 |
| HUAWEI        | HN-WX9X                     | [5c1982b26c](https://linux-hardware.org/?probe=5c1982b26c) | Dec 08, 2020 |
| HUAWEI        | HN-WX9X                     | [5b58c4ff46](https://linux-hardware.org/?probe=5b58c4ff46) | Dec 08, 2020 |
| HP            | Laptop 15-da1xxx            | [df5f3d5a4d](https://linux-hardware.org/?probe=df5f3d5a4d) | Dec 07, 2020 |
| Dell          | XPS 13 9370                 | [4cbbe5b21a](https://linux-hardware.org/?probe=4cbbe5b21a) | Nov 26, 2020 |
| Lenovo        | Unknown                     | [40c892a262](https://linux-hardware.org/?probe=40c892a262) | Nov 26, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| Toshiba       | Satellite L755              | [a6e2af6e5b](https://linux-hardware.org/?probe=a6e2af6e5b) | Nov 18, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2f9457bf32](https://linux-hardware.org/?probe=2f9457bf32) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f2e24821f4](https://linux-hardware.org/?probe=f2e24821f4) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [e13999e22a](https://linux-hardware.org/?probe=e13999e22a) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | [e04b97eabe](https://linux-hardware.org/?probe=e04b97eabe) | Nov 11, 2020 |
| Acer          | Aspire A715-72G             | [90ef23a01c](https://linux-hardware.org/?probe=90ef23a01c) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | [4572167747](https://linux-hardware.org/?probe=4572167747) | Nov 10, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Lenovo        | Yoga 3 11 80J8              | [b4f083536f](https://linux-hardware.org/?probe=b4f083536f) | Nov 04, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [b94cef8d24](https://linux-hardware.org/?probe=b94cef8d24) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [c872f1d76f](https://linux-hardware.org/?probe=c872f1d76f) | Nov 03, 2020 |
| Dell          | Latitude E6330              | [f7e530a8c2](https://linux-hardware.org/?probe=f7e530a8c2) | Nov 02, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e8426a064f](https://linux-hardware.org/?probe=e8426a064f) | Nov 01, 2020 |
| Lenovo        | ThinkPad E480 20KN0062IV    | [fba2fb0e45](https://linux-hardware.org/?probe=fba2fb0e45) | Oct 30, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [1a691f72dc](https://linux-hardware.org/?probe=1a691f72dc) | Oct 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [990f9bb22f](https://linux-hardware.org/?probe=990f9bb22f) | Oct 29, 2020 |
| Dell          | Latitude 7490               | [2d61d426d5](https://linux-hardware.org/?probe=2d61d426d5) | Oct 28, 2020 |
| Dell          | Latitude 7300               | [ebf99bafc8](https://linux-hardware.org/?probe=ebf99bafc8) | Oct 27, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [36d289ce92](https://linux-hardware.org/?probe=36d289ce92) | Oct 20, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e360fd1fa2](https://linux-hardware.org/?probe=e360fd1fa2) | Oct 18, 2020 |
| Dell          | Vostro 14 5401              | [89826d13da](https://linux-hardware.org/?probe=89826d13da) | Oct 13, 2020 |
| ASUSTek       | UX430UNR                    | [03dd6f184c](https://linux-hardware.org/?probe=03dd6f184c) | Oct 12, 2020 |
| Dell          | Vostro 14 5401              | [d3f66acd1b](https://linux-hardware.org/?probe=d3f66acd1b) | Oct 12, 2020 |
| HP            | Laptop 15-bs1xx             | [cab83dd9ff](https://linux-hardware.org/?probe=cab83dd9ff) | Oct 12, 2020 |
| Dell          | Vostro 5490                 | [b998e489c5](https://linux-hardware.org/?probe=b998e489c5) | Oct 07, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [a9d940dd83](https://linux-hardware.org/?probe=a9d940dd83) | Oct 04, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [c7e2a6001a](https://linux-hardware.org/?probe=c7e2a6001a) | Oct 04, 2020 |
| Dell          | Latitude 7400               | [6eac6cfa15](https://linux-hardware.org/?probe=6eac6cfa15) | Oct 04, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b8c1686e69](https://linux-hardware.org/?probe=b8c1686e69) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [33801ffba1](https://linux-hardware.org/?probe=33801ffba1) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 20RA0036IV     | [d53e57ac10](https://linux-hardware.org/?probe=d53e57ac10) | Sep 25, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [9b2604c2e1](https://linux-hardware.org/?probe=9b2604c2e1) | Sep 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| Dell          | Latitude E5270              | [745e05ba12](https://linux-hardware.org/?probe=745e05ba12) | Aug 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [eee9972fdf](https://linux-hardware.org/?probe=eee9972fdf) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [cb7fda5c3f](https://linux-hardware.org/?probe=cb7fda5c3f) | Aug 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [99c5924655](https://linux-hardware.org/?probe=99c5924655) | Aug 23, 2020 |
| Lenovo        | ThinkPad L390 20NR001LIV    | [9fef5634b2](https://linux-hardware.org/?probe=9fef5634b2) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee5213ce49](https://linux-hardware.org/?probe=ee5213ce49) | Aug 19, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | [5f1ce912be](https://linux-hardware.org/?probe=5f1ce912be) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [635a148f20](https://linux-hardware.org/?probe=635a148f20) | Aug 19, 2020 |
| Toshiba       | Satellite P50t-B-10T        | [0f41a5b6ec](https://linux-hardware.org/?probe=0f41a5b6ec) | Aug 13, 2020 |
| Lenovo        | ThinkPad T490 20N20073IV    | [3878e27014](https://linux-hardware.org/?probe=3878e27014) | Aug 10, 2020 |
| Dell          | Latitude 7390 2-in-1        | [fb785080a3](https://linux-hardware.org/?probe=fb785080a3) | Aug 02, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | [e934fab850](https://linux-hardware.org/?probe=e934fab850) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | [38feef34d4](https://linux-hardware.org/?probe=38feef34d4) | Aug 01, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Dell          | Latitude E6530              | [6e1b2fb388](https://linux-hardware.org/?probe=6e1b2fb388) | Jul 24, 2020 |
| Lenovo        | V510-15IKB 80WQ             | [3944aa1028](https://linux-hardware.org/?probe=3944aa1028) | Jul 20, 2020 |
| HP            | ProBook 640 G2              | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [6e6f80378d](https://linux-hardware.org/?probe=6e6f80378d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | [d0aacf7693](https://linux-hardware.org/?probe=d0aacf7693) | Jul 09, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | [868953dc99](https://linux-hardware.org/?probe=868953dc99) | Jul 09, 2020 |
| Dell          | Latitude 5400               | [ae1c2d9825](https://linux-hardware.org/?probe=ae1c2d9825) | Jul 08, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [52fad4367c](https://linux-hardware.org/?probe=52fad4367c) | Jul 01, 2020 |
| HP            | Pavilion dv6                | [39df31f4c6](https://linux-hardware.org/?probe=39df31f4c6) | Jun 27, 2020 |
| Lenovo        | ThinkPad E14 20RA0016IV     | [2878e88064](https://linux-hardware.org/?probe=2878e88064) | Jun 24, 2020 |
| HP            | Pavilion Notebook           | [866c72927a](https://linux-hardware.org/?probe=866c72927a) | Jun 22, 2020 |
| Dell          | Inspiron 5379               | [f7fe8744d9](https://linux-hardware.org/?probe=f7fe8744d9) | Jun 21, 2020 |
| ASUSTek       | UX331UA                     | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| HP            | EliteBook 840 G5            | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| ASUSTek       | UX331UA                     | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1ce6e06069](https://linux-hardware.org/?probe=1ce6e06069) | May 30, 2020 |
| Dell          | Latitude 5490               | [2afe6adf1b](https://linux-hardware.org/?probe=2afe6adf1b) | May 18, 2020 |
| Dell          | Latitude 5490               | [c2b1c12105](https://linux-hardware.org/?probe=c2b1c12105) | May 17, 2020 |
| ASUSTek       | UX331UA                     | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| HP            | EliteBook 840 G5            | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| HP            | G42                         | [6d45062a76](https://linux-hardware.org/?probe=6d45062a76) | May 14, 2020 |
| Lenovo        | ThinkPad X200 74587DU       | [ba354beaa9](https://linux-hardware.org/?probe=ba354beaa9) | May 10, 2020 |
| ASUSTek       | K54C                        | [c2656ceae6](https://linux-hardware.org/?probe=c2656ceae6) | May 07, 2020 |
| HP            | Pavilion Laptop 14-bf1xx    | [6f86c55589](https://linux-hardware.org/?probe=6f86c55589) | May 04, 2020 |
| Acer          | Swift SF314-54G             | [e93143c6fd](https://linux-hardware.org/?probe=e93143c6fd) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | [4cc7a86795](https://linux-hardware.org/?probe=4cc7a86795) | Apr 26, 2020 |
| Toshiba       | Satellite A200              | [d9a55aeca2](https://linux-hardware.org/?probe=d9a55aeca2) | Apr 25, 2020 |
| Toshiba       | Satellite A200              | [1e6ea00cd0](https://linux-hardware.org/?probe=1e6ea00cd0) | Apr 25, 2020 |
| ASUSTek       | UX331UA                     | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [2516b70573](https://linux-hardware.org/?probe=2516b70573) | Apr 23, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [cdcce3c09c](https://linux-hardware.org/?probe=cdcce3c09c) | Apr 23, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [434a4a46f9](https://linux-hardware.org/?probe=434a4a46f9) | Apr 19, 2020 |
| Dell          | XPS 13 9350                 | [d718b985ec](https://linux-hardware.org/?probe=d718b985ec) | Apr 18, 2020 |
| HP            | Pavilion Notebook           | [cd641ec5c7](https://linux-hardware.org/?probe=cd641ec5c7) | Apr 17, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [28e6c33fec](https://linux-hardware.org/?probe=28e6c33fec) | Apr 17, 2020 |
| HP            | Pavilion Notebook           | [7e17ce97e9](https://linux-hardware.org/?probe=7e17ce97e9) | Apr 17, 2020 |
| ASUSTek       | X550CA                      | [d23cc368bb](https://linux-hardware.org/?probe=d23cc368bb) | Apr 10, 2020 |
| Dell          | Latitude 5490               | [6759b030d2](https://linux-hardware.org/?probe=6759b030d2) | Apr 10, 2020 |
| Dell          | Latitude 7300               | [4c263fc2d0](https://linux-hardware.org/?probe=4c263fc2d0) | Apr 01, 2020 |
| HP            | ZBook 15 G3                 | [254c1f48da](https://linux-hardware.org/?probe=254c1f48da) | Mar 31, 2020 |
| Dell          | Latitude 5490               | [03873fa787](https://linux-hardware.org/?probe=03873fa787) | Mar 30, 2020 |
| Dell          | Latitude 5490               | [d71d69d129](https://linux-hardware.org/?probe=d71d69d129) | Mar 30, 2020 |
| HP            | EliteBook 840 G5            | [2aab729aee](https://linux-hardware.org/?probe=2aab729aee) | Mar 30, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9c1238b041](https://linux-hardware.org/?probe=9c1238b041) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5765e1a9f](https://linux-hardware.org/?probe=b5765e1a9f) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3c36d4bdc9](https://linux-hardware.org/?probe=3c36d4bdc9) | Mar 21, 2020 |
| Lenovo        | ThinkPad T480 20L5A063CD    | [ccd24104da](https://linux-hardware.org/?probe=ccd24104da) | Mar 08, 2020 |
| Dell          | Inspiron N5110              | [d13a02aacb](https://linux-hardware.org/?probe=d13a02aacb) | Mar 08, 2020 |
| Dell          | Inspiron 7548               | [ebce14c87e](https://linux-hardware.org/?probe=ebce14c87e) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | [d4b3df5729](https://linux-hardware.org/?probe=d4b3df5729) | Feb 22, 2020 |
| ASUSTek       | X201EP                      | [75d7523e83](https://linux-hardware.org/?probe=75d7523e83) | Feb 13, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [239b2eba6d](https://linux-hardware.org/?probe=239b2eba6d) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [a3e9ca6d37](https://linux-hardware.org/?probe=a3e9ca6d37) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [60ba0e3d0f](https://linux-hardware.org/?probe=60ba0e3d0f) | Feb 08, 2020 |
| Dell          | Inspiron 13-5378            | [30e38a1812](https://linux-hardware.org/?probe=30e38a1812) | Feb 03, 2020 |
| HP            | Laptop 15-da1xxx            | [b4ef2a52c5](https://linux-hardware.org/?probe=b4ef2a52c5) | Jan 21, 2020 |
| HP            | Laptop 15-da1xxx            | [33d23400b4](https://linux-hardware.org/?probe=33d23400b4) | Jan 20, 2020 |
| LG Electro... | 15Z990-A.AAS7U1             | [afd7d4caf9](https://linux-hardware.org/?probe=afd7d4caf9) | Jan 15, 2020 |
| Lenovo        | G570 4334                   | [7bf153f618](https://linux-hardware.org/?probe=7bf153f618) | Jan 13, 2020 |
| Lenovo        | ThinkPad E595 20NF0018US    | [00d8e5ba33](https://linux-hardware.org/?probe=00d8e5ba33) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | [a423e910c6](https://linux-hardware.org/?probe=a423e910c6) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | [84fcfb4be2](https://linux-hardware.org/?probe=84fcfb4be2) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | [903ab151c8](https://linux-hardware.org/?probe=903ab151c8) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | [495c89d842](https://linux-hardware.org/?probe=495c89d842) | Jan 07, 2020 |
| Dell          | Latitude E7270              | [83f77407ab](https://linux-hardware.org/?probe=83f77407ab) | Jan 06, 2020 |
| Dell          | Latitude E7270              | [dc87d2cdee](https://linux-hardware.org/?probe=dc87d2cdee) | Jan 06, 2020 |
| Dell          | Inspiron MM061              | [3da92e4cab](https://linux-hardware.org/?probe=3da92e4cab) | Jan 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [992e2074ff](https://linux-hardware.org/?probe=992e2074ff) | Dec 25, 2019 |
| ASUSTek       | UL30A                       | [b7f84b8da0](https://linux-hardware.org/?probe=b7f84b8da0) | Dec 20, 2019 |
| ASUSTek       | X501A                       | [ce99670ceb](https://linux-hardware.org/?probe=ce99670ceb) | Dec 20, 2019 |
| ASUSTek       | X501A                       | [f7a367e32c](https://linux-hardware.org/?probe=f7a367e32c) | Dec 20, 2019 |
| LG Electro... | A310                        | [d2599d1470](https://linux-hardware.org/?probe=d2599d1470) | Nov 26, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [52db21c094](https://linux-hardware.org/?probe=52db21c094) | Nov 24, 2019 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [831c001466](https://linux-hardware.org/?probe=831c001466) | Nov 23, 2019 |
| HP            | G7000                       | [cb550f69f7](https://linux-hardware.org/?probe=cb550f69f7) | Nov 12, 2019 |
| HP            | G7000                       | [97ada3d9cf](https://linux-hardware.org/?probe=97ada3d9cf) | Nov 12, 2019 |
| HP            | G7000                       | [ca985e708a](https://linux-hardware.org/?probe=ca985e708a) | Nov 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [39c33a8d85](https://linux-hardware.org/?probe=39c33a8d85) | Oct 21, 2019 |
| Samsung       | 3570R/370R/470R/450R/510... | [a5e61f3a1a](https://linux-hardware.org/?probe=a5e61f3a1a) | Oct 18, 2019 |
| Dell          | Latitude E6320              | [276041713d](https://linux-hardware.org/?probe=276041713d) | Oct 18, 2019 |
| Dell          | Latitude E6320              | [a2002798ac](https://linux-hardware.org/?probe=a2002798ac) | Oct 18, 2019 |
| Lenovo        | E31-80 80MX                 | [4f5d1ae105](https://linux-hardware.org/?probe=4f5d1ae105) | Oct 17, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6bc1a600ee](https://linux-hardware.org/?probe=6bc1a600ee) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [32944602dd](https://linux-hardware.org/?probe=32944602dd) | Oct 06, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [60e8599708](https://linux-hardware.org/?probe=60e8599708) | Sep 30, 2019 |
| Lenovo        | G560 0679                   | [403cb2c831](https://linux-hardware.org/?probe=403cb2c831) | Sep 19, 2019 |
| Lenovo        | G560 0679                   | [0552d32d91](https://linux-hardware.org/?probe=0552d32d91) | Sep 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [77a3bc0e11](https://linux-hardware.org/?probe=77a3bc0e11) | Sep 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eeaadaa0a3](https://linux-hardware.org/?probe=eeaadaa0a3) | Sep 17, 2019 |
| HP            | EliteBook 840 G6            | [4ada1a54ef](https://linux-hardware.org/?probe=4ada1a54ef) | Sep 13, 2019 |
| Lenovo        | Yoga 500-14ISK 80R5         | [b4f1b9249a](https://linux-hardware.org/?probe=b4f1b9249a) | Sep 10, 2019 |
| Dell          | Latitude E7450              | [cb374fcaff](https://linux-hardware.org/?probe=cb374fcaff) | Sep 05, 2019 |
| Dell          | XPS 13 9343                 | [ecb0cffd7b](https://linux-hardware.org/?probe=ecb0cffd7b) | Sep 04, 2019 |
| ASUSTek       | X302UJ                      | [d467007887](https://linux-hardware.org/?probe=d467007887) | Aug 24, 2019 |
| Acer          | Aspire 5730                 | [6e8c846d9b](https://linux-hardware.org/?probe=6e8c846d9b) | Aug 24, 2019 |
| Dell          | Latitude E5470              | [d01c149d9c](https://linux-hardware.org/?probe=d01c149d9c) | Aug 17, 2019 |
| Dell          | Latitude E5470              | [b0b32067b9](https://linux-hardware.org/?probe=b0b32067b9) | Aug 17, 2019 |
| Dell          | Inspiron 13-5378            | [afa245a5c3](https://linux-hardware.org/?probe=afa245a5c3) | Aug 13, 2019 |
| HP            | 255 G5 Notebook PC          | [2043a9b3c9](https://linux-hardware.org/?probe=2043a9b3c9) | Jul 18, 2019 |
| ASUSTek       | K54C                        | [4a89c5d895](https://linux-hardware.org/?probe=4a89c5d895) | Jul 06, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [93c1102eae](https://linux-hardware.org/?probe=93c1102eae) | May 30, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [89e100d874](https://linux-hardware.org/?probe=89e100d874) | May 17, 2019 |
| HP            | Pavilion dv6500             | [b185023357](https://linux-hardware.org/?probe=b185023357) | May 13, 2019 |
| ASUSTek       | K54C                        | [653d157e1a](https://linux-hardware.org/?probe=653d157e1a) | May 04, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | [a803a8593b](https://linux-hardware.org/?probe=a803a8593b) | Apr 11, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | [6be3c466e0](https://linux-hardware.org/?probe=6be3c466e0) | Apr 10, 2019 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f49f4bf7e3](https://linux-hardware.org/?probe=f49f4bf7e3) | Mar 30, 2019 |
| Fujitsu Si... | AMILO Li 2727               | [606743f06e](https://linux-hardware.org/?probe=606743f06e) | Mar 22, 2019 |
| System76      | Gazelle                     | [03387dc427](https://linux-hardware.org/?probe=03387dc427) | Mar 12, 2019 |
| HP            | G70                         | [d4f5ef99c5](https://linux-hardware.org/?probe=d4f5ef99c5) | Feb 14, 2019 |
| ASUSTek       | S551LN                      | [572227fb77](https://linux-hardware.org/?probe=572227fb77) | Jan 19, 2019 |
| ASUSTek       | S551LN                      | [f624b3c2eb](https://linux-hardware.org/?probe=f624b3c2eb) | Jan 18, 2019 |
| ASUSTek       | S551LN                      | [084947886f](https://linux-hardware.org/?probe=084947886f) | Jan 03, 2019 |
| Timi          | TM1701                      | [19f0b77769](https://linux-hardware.org/?probe=19f0b77769) | Dec 21, 2018 |
| Timi          | TM1701                      | [e0c4ee1fcb](https://linux-hardware.org/?probe=e0c4ee1fcb) | Dec 21, 2018 |
| ASUSTek       | S551LN                      | [4fef5b511a](https://linux-hardware.org/?probe=4fef5b511a) | Dec 15, 2018 |
| ASUSTek       | S551LN                      | [735db3cd91](https://linux-hardware.org/?probe=735db3cd91) | Dec 14, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [120d843ed3](https://linux-hardware.org/?probe=120d843ed3) | Nov 07, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d21daddd24](https://linux-hardware.org/?probe=d21daddd24) | Nov 07, 2018 |
| ASUSTek       | 1001PXD                     | [00e7c9c5fc](https://linux-hardware.org/?probe=00e7c9c5fc) | Aug 18, 2018 |
| ASUSTek       | 1001PXD                     | [80227a12a8](https://linux-hardware.org/?probe=80227a12a8) | Aug 18, 2018 |
| Lenovo        | ThinkPad T60 2613CTO        | [35edbff8b9](https://linux-hardware.org/?probe=35edbff8b9) | Feb 25, 2018 |
| Samsung       | N248P                       | [2b7782d6cb](https://linux-hardware.org/?probe=2b7782d6cb) | Aug 10, 2017 |
| HP            | Unknown                     | [551457fd6d](https://linux-hardware.org/?probe=551457fd6d) | Jul 10, 2017 |
| Acer          | Aspire 7520                 | [9132eeefdd](https://linux-hardware.org/?probe=9132eeefdd) | Nov 21, 2016 |
| ASUSTek       | 1001PXD                     | [6de0cbb74c](https://linux-hardware.org/?probe=6de0cbb74c) | Oct 29, 2016 |
| ASUSTek       | 1001PXD                     | [439684c718](https://linux-hardware.org/?probe=439684c718) | Oct 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 69        | 25%     |
| Ubuntu 18.04                 | 30        | 10.87%  |
| Fedora 35                    | 8         | 2.9%    |
| Ubuntu 22.04                 | 7         | 2.54%   |
| Ubuntu 21.04                 | 7         | 2.54%   |
| Arch                         | 6         | 2.17%   |
| Zorin 15                     | 5         | 1.81%   |
| ROSA R11                     | 5         | 1.81%   |
| Pop!_OS 21.04                | 5         | 1.81%   |
| Manjaro                      | 5         | 1.81%   |
| Linux Mint 20.1              | 5         | 1.81%   |
| Ubuntu 19.10                 | 4         | 1.45%   |
| ROSA R10                     | 4         | 1.45%   |
| Fedora 36                    | 4         | 1.45%   |
| Fedora 34                    | 4         | 1.45%   |
| Fedora 33                    | 4         | 1.45%   |
| Zorin 16                     | 3         | 1.09%   |
| Ubuntu 20.10                 | 3         | 1.09%   |
| Ubuntu 19.04                 | 3         | 1.09%   |
| Pop!_OS 21.10                | 3         | 1.09%   |
| Pop!_OS 20.10                | 3         | 1.09%   |
| Manjaro 20.2                 | 3         | 1.09%   |
| Linux Mint 20.3              | 3         | 1.09%   |
| Linux Mint 20                | 3         | 1.09%   |
| Fedora 32                    | 3         | 1.09%   |
| Arch Rolling                 | 3         | 1.09%   |
| ROSA R9                      | 2         | 0.72%   |
| ROSA R8                      | 2         | 0.72%   |
| ROSA R11.1                   | 2         | 0.72%   |
| Pop!_OS 20.04                | 2         | 0.72%   |
| OpenMandriva 4.3             | 2         | 0.72%   |
| OpenMandriva 4.2             | 2         | 0.72%   |
| Linux Mint 20.2              | 2         | 0.72%   |
| Linux Mint 19.2              | 2         | 0.72%   |
| Kubuntu 20.04                | 2         | 0.72%   |
| KDE neon 20.04               | 2         | 0.72%   |
| ArcoLinux Rolling            | 2         | 0.72%   |
| Zorin 12                     | 1         | 0.36%   |
| Xubuntu 20.10                | 1         | 0.36%   |
| Xubuntu 20.04                | 1         | 0.36%   |
| Xubuntu 19.10                | 1         | 0.36%   |
| Xubuntu 18.04                | 1         | 0.36%   |
| Ubuntu MATE 18.04            | 1         | 0.36%   |
| Ubuntu 21.10                 | 1         | 0.36%   |
| Ubuntu 18.10                 | 1         | 0.36%   |
| Ubuntu 16.04                 | 1         | 0.36%   |
| ROSA 12.2                    | 1         | 0.36%   |
| RHEL 8                       | 1         | 0.36%   |
| PureOS 10                    | 1         | 0.36%   |
| Pop!_OS 22.04                | 1         | 0.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.36%   |
| Manjaro 21.3.1               | 1         | 0.36%   |
| Manjaro 21.2pre1             | 1         | 0.36%   |
| Manjaro 21.2.5               | 1         | 0.36%   |
| Manjaro 21.0.7               | 1         | 0.36%   |
| Manjaro 21.0.4               | 1         | 0.36%   |
| Manjaro 21.0                 | 1         | 0.36%   |
| Manjaro 20.2.1               | 1         | 0.36%   |
| Manjaro 20.1.1               | 1         | 0.36%   |
| Manjaro 20.1                 | 1         | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 123       | 48.24%  |
| Fedora       | 21        | 8.24%   |
| Linux Mint   | 18        | 7.06%   |
| ROSA         | 14        | 5.49%   |
| Pop!_OS      | 14        | 5.49%   |
| Manjaro      | 11        | 4.31%   |
| Zorin        | 9         | 3.53%   |
| Arch         | 9         | 3.53%   |
| Endless      | 7         | 2.75%   |
| Xubuntu      | 4         | 1.57%   |
| OpenMandriva | 4         | 1.57%   |
| Kubuntu      | 2         | 0.78%   |
| KDE neon     | 2         | 0.78%   |
| Debian       | 2         | 0.78%   |
| CentOS       | 2         | 0.78%   |
| ArcoLinux    | 2         | 0.78%   |
| Ubuntu MATE  | 1         | 0.39%   |
| RHEL         | 1         | 0.39%   |
| PureOS       | 1         | 0.39%   |
| openSUSE     | 1         | 0.39%   |
| Lubuntu      | 1         | 0.39%   |
| Kali         | 1         | 0.39%   |
| EndeavourOS  | 1         | 0.39%   |
| Elementary   | 1         | 0.39%   |
| Devuan       | 1         | 0.39%   |
| Clear Linux  | 1         | 0.39%   |
| BlackPanther | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 10        | 3.44%   |
| 5.4.0-48-generic                | 8         | 2.75%   |
| 5.4.0-52-generic                | 5         | 1.72%   |
| 5.0.0-23-generic                | 5         | 1.72%   |
| 5.4.0-26-generic                | 4         | 1.37%   |
| 5.8.0-59-generic                | 3         | 1.03%   |
| 5.8.0-44-generic                | 3         | 1.03%   |
| 5.4.0-72-generic                | 3         | 1.03%   |
| 5.4.0-65-generic                | 3         | 1.03%   |
| 5.4.0-58-generic                | 3         | 1.03%   |
| 5.3.0-46-generic                | 3         | 1.03%   |
| 5.3.0-42-generic                | 3         | 1.03%   |
| 5.3.0-26-generic                | 3         | 1.03%   |
| 5.11.0-34-generic               | 3         | 1.03%   |
| 5.9.16-200.fc33.x86_64          | 2         | 0.69%   |
| 5.8.16-300.fc33.x86_64          | 2         | 0.69%   |
| 5.8.0-7642-generic              | 2         | 0.69%   |
| 5.8.0-63-generic                | 2         | 0.69%   |
| 5.8.0-53-generic                | 2         | 0.69%   |
| 5.8.0-41-generic                | 2         | 0.69%   |
| 5.4.2-1-MANJARO                 | 2         | 0.69%   |
| 5.4.0-91-generic                | 2         | 0.69%   |
| 5.4.0-70-generic                | 2         | 0.69%   |
| 5.4.0-62-generic                | 2         | 0.69%   |
| 5.4.0-53-generic                | 2         | 0.69%   |
| 5.4.0-47-generic                | 2         | 0.69%   |
| 5.4.0-40-generic                | 2         | 0.69%   |
| 5.4.0-37-generic                | 2         | 0.69%   |
| 5.4.0-29-generic                | 2         | 0.69%   |
| 5.4.0-122-generic               | 2         | 0.69%   |
| 5.3.0-53-generic                | 2         | 0.69%   |
| 5.3.0-51-generic                | 2         | 0.69%   |
| 5.3.0-28-generic                | 2         | 0.69%   |
| 5.3.0-19-generic                | 2         | 0.69%   |
| 5.19.1-arch2-1                  | 2         | 0.69%   |
| 5.16.7-desktop-1omv4003         | 2         | 0.69%   |
| 5.16.18-200.fc35.x86_64         | 2         | 0.69%   |
| 5.16.15-76051615-generic        | 2         | 0.69%   |
| 5.15.0-41-generic               | 2         | 0.69%   |
| 5.15.0-27-generic               | 2         | 0.69%   |
| 5.13.12-200.fc34.x86_64         | 2         | 0.69%   |
| 5.13.0-7620-generic             | 2         | 0.69%   |
| 5.13.0-40-generic               | 2         | 0.69%   |
| 5.13.0-30-generic               | 2         | 0.69%   |
| 5.11.0-43-generic               | 2         | 0.69%   |
| 5.11.0-40-generic               | 2         | 0.69%   |
| 5.11.0-38-generic               | 2         | 0.69%   |
| 5.11.0-27-generic               | 2         | 0.69%   |
| 5.11.0-22-generic               | 2         | 0.69%   |
| 5.0.0-27-generic                | 2         | 0.69%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.69%   |
| 4.9.20-nrj-desktop-1rosa-i586   | 2         | 0.69%   |
| 4.19.0-10-amd64                 | 2         | 0.69%   |
| 4.15.0-desktop-68.5rosa-x86_64  | 2         | 0.69%   |
| 4.15.0-15-generic               | 2         | 0.69%   |
| 5.9.9-200.fc33.x86_64           | 1         | 0.34%   |
| 5.9.3-arch1-1                   | 1         | 0.34%   |
| 5.9.13-lqx1-1-lqx               | 1         | 0.34%   |
| 5.9.11-3-MANJARO                | 1         | 0.34%   |
| 5.8.5-arch1-1                   | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 66        | 23.4%   |
| 5.8.0   | 23        | 8.16%   |
| 5.11.0  | 21        | 7.45%   |
| 4.15.0  | 20        | 7.09%   |
| 5.3.0   | 18        | 6.38%   |
| 5.13.0  | 12        | 4.26%   |
| 5.0.0   | 12        | 4.26%   |
| 5.15.0  | 8         | 2.84%   |
| 4.18.0  | 6         | 2.13%   |
| 5.10.0  | 3         | 1.06%   |
| 4.9.60  | 3         | 1.06%   |
| 5.9.16  | 2         | 0.71%   |
| 5.8.16  | 2         | 0.71%   |
| 5.7.10  | 2         | 0.71%   |
| 5.6.0   | 2         | 0.71%   |
| 5.4.2   | 2         | 0.71%   |
| 5.19.1  | 2         | 0.71%   |
| 5.16.7  | 2         | 0.71%   |
| 5.16.18 | 2         | 0.71%   |
| 5.16.15 | 2         | 0.71%   |
| 5.15.2  | 2         | 0.71%   |
| 5.13.12 | 2         | 0.71%   |
| 4.9.20  | 2         | 0.71%   |
| 4.19.0  | 2         | 0.71%   |
| 4.1.34  | 2         | 0.71%   |
| 5.9.9   | 1         | 0.35%   |
| 5.9.3   | 1         | 0.35%   |
| 5.9.13  | 1         | 0.35%   |
| 5.9.11  | 1         | 0.35%   |
| 5.8.5   | 1         | 0.35%   |
| 5.8.11  | 1         | 0.35%   |
| 5.8.1   | 1         | 0.35%   |
| 5.7.7   | 1         | 0.35%   |
| 5.7.11  | 1         | 0.35%   |
| 5.7.0   | 1         | 0.35%   |
| 5.6.13  | 1         | 0.35%   |
| 5.5.6   | 1         | 0.35%   |
| 5.4.34  | 1         | 0.35%   |
| 5.3.6   | 1         | 0.35%   |
| 5.3.16  | 1         | 0.35%   |
| 5.19.0  | 1         | 0.35%   |
| 5.18.8  | 1         | 0.35%   |
| 5.18.6  | 1         | 0.35%   |
| 5.18.5  | 1         | 0.35%   |
| 5.18.3  | 1         | 0.35%   |
| 5.18.2  | 1         | 0.35%   |
| 5.18.11 | 1         | 0.35%   |
| 5.18.1  | 1         | 0.35%   |
| 5.18.0  | 1         | 0.35%   |
| 5.17.8  | 1         | 0.35%   |
| 5.17.6  | 1         | 0.35%   |
| 5.17.13 | 1         | 0.35%   |
| 5.16.8  | 1         | 0.35%   |
| 5.16.2  | 1         | 0.35%   |
| 5.16.14 | 1         | 0.35%   |
| 5.16.11 | 1         | 0.35%   |
| 5.16.10 | 1         | 0.35%   |
| 5.15.7  | 1         | 0.35%   |
| 5.15.6  | 1         | 0.35%   |
| 5.15.57 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 69        | 25.18%  |
| 5.8     | 27        | 9.85%   |
| 5.11    | 26        | 9.49%   |
| 5.3     | 20        | 7.3%    |
| 4.15    | 20        | 7.3%    |
| 5.15    | 15        | 5.47%   |
| 5.13    | 15        | 5.47%   |
| 5.0     | 12        | 4.38%   |
| 5.16    | 11        | 4.01%   |
| 5.10    | 10        | 3.65%   |
| 5.18    | 7         | 2.55%   |
| 4.18    | 7         | 2.55%   |
| 4.9     | 6         | 2.19%   |
| 5.9     | 5         | 1.82%   |
| 5.7     | 4         | 1.46%   |
| 5.6     | 3         | 1.09%   |
| 5.19    | 3         | 1.09%   |
| 5.17    | 3         | 1.09%   |
| 5.14    | 3         | 1.09%   |
| 4.19    | 3         | 1.09%   |
| 4.1     | 2         | 0.73%   |
| 5.5     | 1         | 0.36%   |
| 5.12    | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 245       | 96.46%  |
| i686   | 9         | 3.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 147       | 56.76%  |
| Unknown    | 34        | 13.13%  |
| KDE5       | 27        | 10.42%  |
| X-Cinnamon | 13        | 5.02%   |
| XFCE       | 12        | 4.63%   |
| KDE4       | 11        | 4.25%   |
| KDE        | 4         | 1.54%   |
| Cinnamon   | 3         | 1.16%   |
| MATE       | 2         | 0.77%   |
| LXQt       | 2         | 0.77%   |
| Trinity    | 1         | 0.39%   |
| Pantheon   | 1         | 0.39%   |
| LXDE       | 1         | 0.39%   |
| i3         | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 202       | 78.29%  |
| Wayland | 33        | 12.79%  |
| Unknown | 21        | 8.14%   |
| Tty     | 2         | 0.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 146       | 56.59%  |
| GDM     | 49        | 18.99%  |
| SDDM    | 19        | 7.36%   |
| GDM3    | 16        | 6.2%    |
| KDM     | 11        | 4.26%   |
| TDM     | 10        | 3.88%   |
| LightDM | 7         | 2.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IL   | 102       | 39.38%  |
| en_US   | 77        | 29.73%  |
| Unknown | 42        | 16.22%  |
| ru_RU   | 15        | 5.79%   |
| he_IL   | 12        | 4.63%   |
| en_GB   | 3         | 1.16%   |
| fr_FR   | 2         | 0.77%   |
| C       | 2         | 0.77%   |
| es_ES   | 1         | 0.39%   |
| en_NZ   | 1         | 0.39%   |
| en_CA   | 1         | 0.39%   |
| en_AU   | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 145       | 55.56%  |
| BIOS | 116       | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 209       | 82.28%  |
| Btrfs   | 17        | 6.69%   |
| Unknown | 14        | 5.51%   |
| Overlay | 8         | 3.15%   |
| Xfs     | 4         | 1.57%   |
| Ext3    | 1         | 0.39%   |
| Ext2    | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 152       | 58.91%  |
| GPT     | 85        | 32.95%  |
| MBR     | 21        | 8.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 238       | 93.33%  |
| Yes       | 17        | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 189       | 74.41%  |
| Yes       | 65        | 25.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 77        | 30.31%  |
| Dell                | 56        | 22.05%  |
| ASUSTek Computer    | 45        | 17.72%  |
| Hewlett-Packard     | 40        | 15.75%  |
| Acer                | 8         | 3.15%   |
| Samsung Electronics | 5         | 1.97%   |
| Toshiba             | 4         | 1.57%   |
| Apple               | 4         | 1.57%   |
| LG Electronics      | 3         | 1.18%   |
| Fujitsu             | 3         | 1.18%   |
| Fujitsu Siemens     | 2         | 0.79%   |
| Timi                | 1         | 0.39%   |
| System76            | 1         | 0.39%   |
| Purism              | 1         | 0.39%   |
| Notebook            | 1         | 0.39%   |
| IP3 Tech            | 1         | 0.39%   |
| HUAWEI              | 1         | 0.39%   |
| Unknown             | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 5         | 1.97%   |
| HP Compaq Presario CQ61                                                                  | 3         | 1.18%   |
| ASUS UX331UA                                                                             | 3         | 1.18%   |
| Lenovo V14-IIL 82C4                                                                      | 2         | 0.79%   |
| Lenovo IdeaPad Y700-15ISK 80NV                                                           | 2         | 0.79%   |
| Lenovo IdeaPad L340-15IWL 81LG                                                           | 2         | 0.79%   |
| Lenovo IdeaPad 5 14ITL05 82FE                                                            | 2         | 0.79%   |
| Lenovo G50-80 80L0                                                                       | 2         | 0.79%   |
| HP ZBook 15 G3                                                                           | 2         | 0.79%   |
| HP Pavilion Notebook                                                                     | 2         | 0.79%   |
| HP EliteBook 840 G5                                                                      | 2         | 0.79%   |
| Fujitsu LIFEBOOK AH530                                                                   | 2         | 0.79%   |
| Dell XPS 15 9570                                                                         | 2         | 0.79%   |
| Dell Latitude E6330                                                                      | 2         | 0.79%   |
| Dell Latitude 7400                                                                       | 2         | 0.79%   |
| Dell Latitude 5410                                                                       | 2         | 0.79%   |
| Dell Inspiron 3593                                                                       | 2         | 0.79%   |
| Dell Inspiron 3542                                                                       | 2         | 0.79%   |
| Dell Inspiron 13-5378                                                                    | 2         | 0.79%   |
| ASUS ZenBook UX425EA_UX425EA                                                             | 2         | 0.79%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                                                     | 2         | 0.79%   |
| ASUS N550JV                                                                              | 2         | 0.79%   |
| Toshiba Satellite P50t-B-10T                                                             | 1         | 0.39%   |
| Toshiba Satellite L755                                                                   | 1         | 0.39%   |
| Toshiba Satellite A200                                                                   | 1         | 0.39%   |
| Toshiba PORTEGE R700                                                                     | 1         | 0.39%   |
| Timi TM1701                                                                              | 1         | 0.39%   |
| System76 Gazelle                                                                         | 1         | 0.39%   |
| Samsung N248P                                                                            | 1         | 0.39%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV                                                 | 1         | 0.39%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.39%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                                                      | 1         | 0.39%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B                                               | 1         | 0.39%   |
| Purism Librem 14                                                                         | 1         | 0.39%   |
| Notebook N2x0WU                                                                          | 1         | 0.39%   |
| LG A310                                                                                  | 1         | 0.39%   |
| LG 15Z990-A.AAS7U1                                                                       | 1         | 0.39%   |
| LG 15Z980-A.AAS8U1                                                                       | 1         | 0.39%   |
| Lenovo Yoga 500-14ISK 80R5                                                               | 1         | 0.39%   |
| Lenovo Yoga 3 11 80J8                                                                    | 1         | 0.39%   |
| Lenovo V510-15IKB 80WQ                                                                   | 1         | 0.39%   |
| Lenovo ThinkPad X61 Tablet 7767BFG                                                       | 1         | 0.39%   |
| Lenovo ThinkPad X260 20F60041IV                                                          | 1         | 0.39%   |
| Lenovo ThinkPad X250 20CLS3UW00                                                          | 1         | 0.39%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.39%   |
| Lenovo ThinkPad X200 74587DU                                                             | 1         | 0.39%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005PIV                                               | 1         | 0.39%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES0H400                                                 | 1         | 0.39%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S0G                                                 | 1         | 0.39%   |
| Lenovo ThinkPad T60 2613CTO                                                              | 1         | 0.39%   |
| Lenovo ThinkPad T580 20L9001YIV                                                          | 1         | 0.39%   |
| Lenovo ThinkPad T490 20N20073IV                                                          | 1         | 0.39%   |
| Lenovo ThinkPad T480 20L5A063CD                                                          | 1         | 0.39%   |
| Lenovo ThinkPad T440s 20AQ005TUS                                                         | 1         | 0.39%   |
| Lenovo ThinkPad T440p 20AN00E3IV                                                         | 1         | 0.39%   |
| Lenovo ThinkPad T410 2522WZN                                                             | 1         | 0.39%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D3N                                                    | 1         | 0.39%   |
| Lenovo ThinkPad T14 Gen 2i 20W000C9US                                                    | 1         | 0.39%   |
| Lenovo ThinkPad T14 Gen 1 20S00034US                                                     | 1         | 0.39%   |
| Lenovo ThinkPad T14 Gen 1 20S0000BIV                                                     | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 37        | 14.57%  |
| Dell Latitude           | 23        | 9.06%   |
| Lenovo IdeaPad          | 17        | 6.69%   |
| Dell Inspiron           | 16        | 6.3%    |
| ASUS VivoBook           | 9         | 3.54%   |
| HP Pavilion             | 8         | 3.15%   |
| Dell XPS                | 7         | 2.76%   |
| Dell Vostro             | 7         | 2.76%   |
| ASUS ROG                | 7         | 2.76%   |
| Acer Aspire             | 7         | 2.76%   |
| Lenovo Legion           | 6         | 2.36%   |
| HP ProBook              | 5         | 1.97%   |
| HP EliteBook            | 5         | 1.97%   |
| ASUS ZenBook            | 5         | 1.97%   |
| Unknown                 | 5         | 1.97%   |
| HP ZBook                | 4         | 1.57%   |
| Toshiba Satellite       | 3         | 1.18%   |
| Lenovo G50-80           | 3         | 1.18%   |
| HP Compaq               | 3         | 1.18%   |
| Fujitsu LIFEBOOK        | 3         | 1.18%   |
| ASUS UX331UA            | 3         | 1.18%   |
| Lenovo Yoga             | 2         | 0.79%   |
| Lenovo V14-IIL          | 2         | 0.79%   |
| HP Laptop               | 2         | 0.79%   |
| HP ENVY                 | 2         | 0.79%   |
| ASUS N550JV             | 2         | 0.79%   |
| ASUS ASUS               | 2         | 0.79%   |
| Toshiba PORTEGE         | 1         | 0.39%   |
| Timi TM1701             | 1         | 0.39%   |
| System76 Gazelle        | 1         | 0.39%   |
| Samsung N248P           | 1         | 0.39%   |
| Samsung 3570R           | 1         | 0.39%   |
| Samsung 355V4C          | 1         | 0.39%   |
| Samsung 350V5C          | 1         | 0.39%   |
| Samsung 300V3A          | 1         | 0.39%   |
| Purism Librem           | 1         | 0.39%   |
| Notebook N2x0WU         | 1         | 0.39%   |
| LG A310                 | 1         | 0.39%   |
| LG 15Z990-A.AAS7U1      | 1         | 0.39%   |
| LG 15Z980-A.AAS8U1      | 1         | 0.39%   |
| Lenovo V510-15IKB       | 1         | 0.39%   |
| Lenovo ThinkBook        | 1         | 0.39%   |
| Lenovo G570             | 1         | 0.39%   |
| Lenovo G560             | 1         | 0.39%   |
| Lenovo G510             | 1         | 0.39%   |
| Lenovo G40-70           | 1         | 0.39%   |
| Lenovo E31-80           | 1         | 0.39%   |
| Lenovo 3000             | 1         | 0.39%   |
| IP3 Tech Hi13           | 1         | 0.39%   |
| HUAWEI HN-WX9X          | 1         | 0.39%   |
| HP Spectre              | 1         | 0.39%   |
| HP Notebook             | 1         | 0.39%   |
| HP Mini                 | 1         | 0.39%   |
| HP G7000                | 1         | 0.39%   |
| HP G70                  | 1         | 0.39%   |
| HP G42                  | 1         | 0.39%   |
| HP 255                  | 1         | 0.39%   |
| HP 250                  | 1         | 0.39%   |
| HP 240                  | 1         | 0.39%   |
| Fujitsu Siemens ESPRIMO | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 42        | 16.54%  |
| 2020 | 32        | 12.6%   |
| 2018 | 28        | 11.02%  |
| 2016 | 19        | 7.48%   |
| 2017 | 18        | 7.09%   |
| 2015 | 18        | 7.09%   |
| 2012 | 15        | 5.91%   |
| 2011 | 15        | 5.91%   |
| 2021 | 13        | 5.12%   |
| 2010 | 11        | 4.33%   |
| 2014 | 10        | 3.94%   |
| 2013 | 9         | 3.54%   |
| 2008 | 9         | 3.54%   |
| 2009 | 6         | 2.36%   |
| 2007 | 6         | 2.36%   |
| 2006 | 2         | 0.79%   |
| 2022 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 254       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 225       | 87.89%  |
| Enabled  | 31        | 12.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 253       | 99.61%  |
| Yes  | 1         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 65        | 25.59%  |
| 16.01-24.0  | 60        | 23.62%  |
| 32.01-64.0  | 35        | 13.78%  |
| 3.01-4.0    | 34        | 13.39%  |
| 8.01-16.0   | 34        | 13.39%  |
| 1.01-2.0    | 13        | 5.12%   |
| 64.01-256.0 | 5         | 1.97%   |
| 2.01-3.0    | 4         | 1.57%   |
| 24.01-32.0  | 2         | 0.79%   |
| 0.51-1.0    | 2         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 75        | 27.68%  |
| 2.01-3.0   | 65        | 23.99%  |
| 4.01-8.0   | 45        | 16.61%  |
| 3.01-4.0   | 45        | 16.61%  |
| 8.01-16.0  | 23        | 8.49%   |
| 0.51-1.0   | 11        | 4.06%   |
| 16.01-24.0 | 4         | 1.48%   |
| 0.01-0.5   | 3         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 212       | 83.14%  |
| 2      | 39        | 15.29%  |
| 3      | 2         | 0.78%   |
| 0      | 2         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 177       | 69.69%  |
| Yes       | 77        | 30.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 80.39%  |
| No        | 50        | 19.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 98.03%  |
| No        | 5         | 1.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 80.08%  |
| No        | 51        | 19.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Israel  | 254       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Tel Aviv              | 123       | 45.39%  |
| Ramat Gan             | 27        | 9.96%   |
| Jerusalem             | 11        | 4.06%   |
| Petaẖ Tiqwa         | 9         | 3.32%   |
| Herzliya              | 9         | 3.32%   |
| Givatayim             | 8         | 2.95%   |
| Rishon LeZiyyon       | 7         | 2.58%   |
| Haifa                 | 7         | 2.58%   |
| Rehovot               | 5         | 1.85%   |
| Netanya               | 5         | 1.85%   |
| Ramat HaSharon        | 4         | 1.48%   |
| Nahariya              | 4         | 1.48%   |
| Kiryat Ono            | 4         | 1.48%   |
| Holon                 | 4         | 1.48%   |
| Ashquelon             | 4         | 1.48%   |
| Raanana               | 3         | 1.11%   |
| Givat Shmuel          | 3         | 1.11%   |
| Yavne                 | 2         | 0.74%   |
| Rishon LeTsiyyon      | 2         | 0.74%   |
| Kfar Saba             | 2         | 0.74%   |
| Hadera                | 2         | 0.74%   |
| Bet Shemesh           | 2         | 0.74%   |
| Tiberias              | 1         | 0.37%   |
| Shelomi               | 1         | 0.37%   |
| Sha`ar Ha`Amaqim      | 1         | 0.37%   |
| Sde Nehemya           | 1         | 0.37%   |
| Ramla                 | 1         | 0.37%   |
| Qiryat Moẕqin       | 1         | 0.37%   |
| Qiryat Bialik         | 1         | 0.37%   |
| Pardes Hanna Karkur   | 1         | 0.37%   |
| Ofakim                | 1         | 0.37%   |
| Ness Ziona            | 1         | 0.37%   |
| Modiin Makkabbim Reut | 1         | 0.37%   |
| Mazkeret Batya        | 1         | 0.37%   |
| Lod                   | 1         | 0.37%   |
| Kinneret              | 1         | 0.37%   |
| Kfar Yona             | 1         | 0.37%   |
| Karmi’el            | 1         | 0.37%   |
| Hod HaSharon          | 1         | 0.37%   |
| Ganei Tikva           | 1         | 0.37%   |
| Eilat                 | 1         | 0.37%   |
| Dimona                | 1         | 0.37%   |
| Caesarea              | 1         | 0.37%   |
| Bet She’an          | 1         | 0.37%   |
| Beersheba             | 1         | 0.37%   |
| Be'er Ya'aqov         | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 58     | 16.03%  |
| WDC                 | 35        | 36     | 12.2%   |
| Seagate             | 29        | 36     | 10.1%   |
| Toshiba             | 25        | 27     | 8.71%   |
| SK hynix            | 25        | 36     | 8.71%   |
| SanDisk             | 24        | 29     | 8.36%   |
| Intel               | 17        | 20     | 5.92%   |
| Kingston            | 14        | 14     | 4.88%   |
| Micron Technology   | 13        | 16     | 4.53%   |
| HGST                | 13        | 14     | 4.53%   |
| Hitachi             | 8         | 8      | 2.79%   |
| Unknown             | 6         | 6      | 2.09%   |
| Crucial             | 6         | 14     | 2.09%   |
| Transcend           | 3         | 4      | 1.05%   |
| StoreJet            | 3         | 3      | 1.05%   |
| KIOXIA              | 3         | 3      | 1.05%   |
| Fujitsu             | 3         | 3      | 1.05%   |
| A-DATA Technology   | 3         | 4      | 1.05%   |
| LITEON              | 2         | 2      | 0.7%    |
| JMicron Technology  | 2         | 2      | 0.7%    |
| China               | 2         | 3      | 0.7%    |
| Apple               | 2         | 2      | 0.7%    |
| Lexar               | 1         | 1      | 0.35%   |
| Apacer              | 1         | 1      | 0.35%   |
| ADATA Technology    | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 9         | 3.07%   |
| Seagate ST500LT012-1DG142 500GB         | 6         | 2.05%   |
| SK hynix NVMe SSD Drive 256GB           | 5         | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 1.71%   |
| SanDisk NVMe SSD Drive 512GB            | 4         | 1.37%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 1.37%   |
| Intel NVMe SSD Drive 512GB              | 4         | 1.37%   |
| Toshiba NVMe SSD Drive 512GB            | 3         | 1.02%   |
| SK hynix PC401 NVMe 512GB               | 3         | 1.02%   |
| SK hynix NVMe SSD Drive 512GB           | 3         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.02%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 1.02%   |
| Samsung NVMe SSD Drive 256GB            | 3         | 1.02%   |
| Intel NVMe SSD Drive 256GB              | 3         | 1.02%   |
| HGST HTS721010A9E630 1TB                | 3         | 1.02%   |
| HGST HTS541010A9E680 1TB                | 3         | 1.02%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 1.02%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 2         | 0.68%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 2         | 0.68%   |
| WDC PC SN730 NVMe 512GB                 | 2         | 0.68%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 2         | 0.68%   |
| WDC PC SN530 NVMe 256GB                 | 2         | 0.68%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.68%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.68%   |
| Toshiba KXG6AZNV1T02 1TB                | 2         | 0.68%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.68%   |
| StoreJet Transcend 1TB                  | 2         | 0.68%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.68%   |
| SanDisk SD8SN8U512G1002 512GB SSD       | 2         | 0.68%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.68%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.68%   |
| Samsung SSD 850 EVO 500GB               | 2         | 0.68%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 2         | 0.68%   |
| Samsung MZVLB1T0HBLR-000L2 1TB          | 2         | 0.68%   |
| Micron 1300 SATA 256GB SSD              | 2         | 0.68%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 2         | 0.68%   |
| LITEON CV1-8B512 512GB SSD              | 2         | 0.68%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.68%   |
| JMicron Generic 160GB                   | 2         | 0.68%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 0.68%   |
| Hitachi HTS542516K9SA00 160GB           | 2         | 0.68%   |
| HGST HTS545050A7E380 500GB              | 2         | 0.68%   |
| A-DATA SU630 480GB SSD                  | 2         | 0.68%   |
| WDC WDS200T3X0C-00SJG0 2TB              | 1         | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.34%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.34%   |
| WDC WD7500BPKX-75HPJT0 752GB            | 1         | 0.34%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.34%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 1         | 0.34%   |
| WDC WD5000L12X-21UJGT0 516GB            | 1         | 0.34%   |
| WDC WD5000BPVT-22HXZT1 500GB            | 1         | 0.34%   |
| WDC WD2500BJKT-75F4T0 250GB             | 1         | 0.34%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 0.34%   |
| WDC WD2500BEVT-24A23T0 250GB            | 1         | 0.34%   |
| WDC WD20SPZX-22UA7T0 2TB                | 1         | 0.34%   |
| WDC WD1600BJKT-75F4T0 160GB             | 1         | 0.34%   |
| WDC WD1600BEVT-00ZCT0 160GB             | 1         | 0.34%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.34%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.34%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 36     | 33.33%  |
| WDC                 | 17        | 17     | 19.54%  |
| Toshiba             | 15        | 15     | 17.24%  |
| HGST                | 13        | 14     | 14.94%  |
| Hitachi             | 8         | 8      | 9.2%    |
| Fujitsu             | 3         | 3      | 3.45%   |
| Unknown             | 1         | 1      | 1.15%   |
| Samsung Electronics | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 16     | 18.6%   |
| SanDisk             | 14        | 18     | 16.28%  |
| Kingston            | 11        | 11     | 12.79%  |
| SK hynix            | 8         | 18     | 9.3%    |
| Micron Technology   | 7         | 7      | 8.14%   |
| Crucial             | 6         | 14     | 6.98%   |
| WDC                 | 3         | 3      | 3.49%   |
| Transcend           | 3         | 4      | 3.49%   |
| A-DATA Technology   | 3         | 4      | 3.49%   |
| Toshiba             | 2         | 2      | 2.33%   |
| StoreJet            | 2         | 2      | 2.33%   |
| LITEON              | 2         | 2      | 2.33%   |
| JMicron Technology  | 2         | 2      | 2.33%   |
| Intel               | 2         | 2      | 2.33%   |
| China               | 2         | 3      | 2.33%   |
| Apple               | 2         | 2      | 2.33%   |
| Apacer              | 1         | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 108       | 132    | 38.85%  |
| HDD     | 83        | 95     | 29.86%  |
| SSD     | 82        | 111    | 29.5%   |
| MMC     | 4         | 4      | 1.44%   |
| Unknown | 1         | 1      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 151       | 196    | 55.11%  |
| NVMe | 108       | 132    | 39.42%  |
| SAS  | 11        | 11     | 4.01%   |
| MMC  | 4         | 4      | 1.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 111       | 139    | 67.27%  |
| 0.51-1.0   | 50        | 63     | 30.3%   |
| 1.01-2.0   | 4         | 4      | 2.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 33.59%  |
| 251-500        | 75        | 28.96%  |
| 501-1000       | 37        | 14.29%  |
| 51-100         | 17        | 6.56%   |
| 1-20           | 13        | 5.02%   |
| 21-50          | 8         | 3.09%   |
| Unknown        | 8         | 3.09%   |
| 1001-2000      | 7         | 2.7%    |
| 2001-3000      | 5         | 1.93%   |
| More than 3000 | 2         | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 97        | 36.06%  |
| 21-50     | 61        | 22.68%  |
| 101-250   | 43        | 15.99%  |
| 51-100    | 35        | 13.01%  |
| 251-500   | 18        | 6.69%   |
| Unknown   | 8         | 2.97%   |
| 501-1000  | 4         | 1.49%   |
| 1001-2000 | 3         | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB            | 2         | 2      | 9.09%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 4.55%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 4.55%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 4.55%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 4.55%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 4.55%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 4.55%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 4.55%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 4.55%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 4.55%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 4.55%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 2      | 4.55%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 4.55%   |
| Intel SSDSCKKF256H6 SATA 256GB        | 1         | 1      | 4.55%   |
| Hitachi HTS545025B9A300 250GB         | 1         | 1      | 4.55%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 4.55%   |
| HGST HCC545050A7E380 500GB            | 1         | 1      | 4.55%   |
| Fujitsu MHY2160BH 160GB               | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 5         | 5      | 23.81%  |
| WDC      | 3         | 3      | 14.29%  |
| Seagate  | 3         | 5      | 14.29%  |
| HGST     | 3         | 3      | 14.29%  |
| SK hynix | 2         | 6      | 9.52%   |
| Hitachi  | 2         | 2      | 9.52%   |
| SanDisk  | 1         | 1      | 4.76%   |
| Intel    | 1         | 1      | 4.76%   |
| Fujitsu  | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 29.41%  |
| WDC     | 3         | 3      | 17.65%  |
| Seagate | 3         | 5      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Hitachi | 2         | 2      | 11.76%  |
| Fujitsu | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 19     | 77.78%  |
| SSD  | 4         | 8      | 22.22%  |

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
| Detected | 155       | 198    | 57.84%  |
| Works    | 95        | 118    | 35.45%  |
| Malfunc  | 18        | 27     | 6.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 199       | 65.46%  |
| Samsung Electronics          | 30        | 9.87%   |
| SanDisk                      | 24        | 7.89%   |
| SK hynix                     | 17        | 5.59%   |
| Toshiba America Info Systems | 9         | 2.96%   |
| AMD                          | 8         | 2.63%   |
| Micron Technology            | 6         | 1.97%   |
| KIOXIA                       | 3         | 0.99%   |
| Kingston Technology Company  | 3         | 0.99%   |
| VIA Technologies             | 1         | 0.33%   |
| Union Memory (Shenzhen)      | 1         | 0.33%   |
| Shenzhen Longsys Electronics | 1         | 0.33%   |
| Nvidia                       | 1         | 0.33%   |
| ADATA Technology             | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 36        | 11.04%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 5.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 16        | 4.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 14        | 4.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 13        | 3.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 11        | 3.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 10        | 3.07%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 9         | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 9         | 2.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 8         | 2.45%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 8         | 2.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 2.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 8         | 2.45%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 8         | 2.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 7         | 2.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 6         | 1.84%   |
| Micron Non-Volatile memory controller                                                  | 6         | 1.84%   |
| Intel SSD 660P Series                                                                  | 6         | 1.84%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 1.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 1.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 5         | 1.53%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 5         | 1.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 5         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 5         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 1.53%   |
| SK hynix Non-Volatile memory controller                                                | 4         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 4         | 1.23%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 4         | 1.23%   |
| SanDisk Non-Volatile memory controller                                                 | 4         | 1.23%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 3         | 0.92%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 3         | 0.92%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 0.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 3         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 0.92%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.61%   |
| SK hynix BC511                                                                         | 2         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                              | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.61%   |
| Intel SSD 600P Series                                                                  | 2         | 0.61%   |
| Intel PROSet/Wireless WiFi Software extension                                          | 2         | 0.61%   |
| Intel Non-Volatile memory controller                                                   | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.61%   |
| VIA VT8237/8251 Serial ATA Controller                                                  | 1         | 0.31%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.31%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.31%   |
| Shenzhen Longsys Non-Volatile memory controller                                        | 1         | 0.31%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.31%   |
| Samsung Electronics SATA controller                                                    | 1         | 0.31%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 0.31%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 0.31%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.31%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.31%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 0.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 174       | 54.21%  |
| NVMe | 108       | 33.64%  |
| RAID | 26        | 8.1%    |
| IDE  | 13        | 4.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 239       | 94.09%  |
| AMD          | 14        | 5.51%   |
| CentaurHauls | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 5.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 3.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 2.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 2.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 2.76%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 1.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.97%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.97%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 4         | 1.57%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 4         | 1.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.57%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.18%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.18%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 3         | 1.18%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.18%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.79%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.79%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.79%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.79%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.79%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.79%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.79%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 2         | 0.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.79%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.39%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.39%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.39%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz        | 1         | 0.39%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.39%   |
| Intel Genuine CPU U2300 @ 1.20GHz             | 1         | 0.39%   |
| Intel Genuine CPU @ 2.16GHz                   | 1         | 0.39%   |
| Intel Core M-5Y10c CPU @ 0.80GHz              | 1         | 0.39%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.39%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.39%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.39%   |
| Intel Core i7-6560U CPU @ 2.20GHz             | 1         | 0.39%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.39%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.39%   |
| Intel Core i7-4700EQ CPU @ 2.40GHz            | 1         | 0.39%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 92        | 36.22%  |
| Intel Core i5           | 67        | 26.38%  |
| Other                   | 22        | 8.66%   |
| Intel Core i3           | 22        | 8.66%   |
| Intel Core 2 Duo        | 8         | 3.15%   |
| Intel Celeron           | 5         | 1.97%   |
| Intel Pentium Dual-Core | 4         | 1.57%   |
| Intel Core i9           | 4         | 1.57%   |
| Intel Pentium Dual      | 3         | 1.18%   |
| Intel Pentium           | 3         | 1.18%   |
| Intel Atom              | 3         | 1.18%   |
| AMD Ryzen 9             | 3         | 1.18%   |
| AMD Ryzen 5             | 3         | 1.18%   |
| Intel Genuine           | 2         | 0.79%   |
| AMD Ryzen 7             | 2         | 0.79%   |
| AMD A6                  | 2         | 0.79%   |
| Intel Xeon              | 1         | 0.39%   |
| Intel Core M            | 1         | 0.39%   |
| Intel Core 2            | 1         | 0.39%   |
| Intel Celeron Dual-Core | 1         | 0.39%   |
| CentaurHauls VIA C7     | 1         | 0.39%   |
| AMD Turion 64 X2 Mobile | 1         | 0.39%   |
| AMD Ryzen 7 PRO         | 1         | 0.39%   |
| AMD A8                  | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 108       | 42.52%  |
| 4       | 107       | 42.13%  |
| 6       | 19        | 7.48%   |
| 8       | 12        | 4.72%   |
| 1       | 6         | 2.36%   |
| 14      | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 253       | 99.61%  |
| Unknown | 1         | 0.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 219       | 85.88%  |
| 1       | 35        | 13.73%  |
| Unknown | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 247       | 97.24%  |
| Unknown        | 6         | 2.36%   |
| 32-bit         | 1         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 22.81%  |
| 0x806ea    | 19        | 7.22%   |
| 0x806ec    | 16        | 6.08%   |
| 0x806c1    | 16        | 6.08%   |
| 0x406e3    | 12        | 4.56%   |
| 0x206a7    | 12        | 4.56%   |
| 0x306a9    | 11        | 4.18%   |
| 0x306d4    | 10        | 3.8%    |
| 0x806e9    | 9         | 3.42%   |
| 0x706e5    | 9         | 3.42%   |
| 0x20655    | 8         | 3.04%   |
| 0xa0652    | 7         | 2.66%   |
| 0x906ea    | 7         | 2.66%   |
| 0x506e3    | 7         | 2.66%   |
| 0x806eb    | 6         | 2.28%   |
| 0x1067a    | 6         | 2.28%   |
| 0x906ed    | 5         | 1.9%    |
| 0x6fd      | 5         | 1.9%    |
| 0x40651    | 5         | 1.9%    |
| 0x306c3    | 5         | 1.9%    |
| 0x106ca    | 3         | 1.14%   |
| 0x906e9    | 2         | 0.76%   |
| 0x806d1    | 2         | 0.76%   |
| 0x6fa      | 2         | 0.76%   |
| 0x08600104 | 2         | 0.76%   |
| 0x08108109 | 2         | 0.76%   |
| 0x08108102 | 2         | 0.76%   |
| 0xa0660    | 1         | 0.38%   |
| 0x906a3    | 1         | 0.38%   |
| 0x706a1    | 1         | 0.38%   |
| 0x6f6      | 1         | 0.38%   |
| 0x6f4      | 1         | 0.38%   |
| 0x506c9    | 1         | 0.38%   |
| 0x106e5    | 1         | 0.38%   |
| 0x10676    | 1         | 0.38%   |
| 0x0a50000c | 1         | 0.38%   |
| 0x0a404101 | 1         | 0.38%   |
| 0x08600106 | 1         | 0.38%   |
| 0x07030106 | 1         | 0.38%   |
| 0x06001119 | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 84        | 33.07%  |
| Skylake          | 22        | 8.66%   |
| TigerLake        | 19        | 7.48%   |
| SandyBridge      | 15        | 5.91%   |
| IvyBridge        | 15        | 5.91%   |
| Haswell          | 14        | 5.51%   |
| IceLake          | 12        | 4.72%   |
| Broadwell        | 12        | 4.72%   |
| Penryn           | 11        | 4.33%   |
| Westmere         | 9         | 3.54%   |
| Core             | 9         | 3.54%   |
| CometLake        | 9         | 3.54%   |
| Zen+             | 4         | 1.57%   |
| Zen 2            | 3         | 1.18%   |
| Unknown          | 3         | 1.18%   |
| Puma             | 2         | 0.79%   |
| Piledriver       | 2         | 0.79%   |
| Bonnell          | 2         | 0.79%   |
| Zen 3            | 1         | 0.39%   |
| Silvermont       | 1         | 0.39%   |
| Nehalem          | 1         | 0.39%   |
| K8 Hammer        | 1         | 0.39%   |
| Goldmont plus    | 1         | 0.39%   |
| Goldmont         | 1         | 0.39%   |
| Alderlake Hybrid | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 230       | 69.91%  |
| Nvidia           | 76        | 23.1%   |
| AMD              | 22        | 6.69%   |
| VIA Technologies | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 27        | 8.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 18        | 5.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 16        | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 14        | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 14        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 13        | 3.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 12        | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 12        | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 11        | 3.27%   |
| Intel HD Graphics 5500                                                    | 10        | 2.98%   |
| Intel Core Processor Integrated Graphics Controller                       | 9         | 2.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 8         | 2.38%   |
| Intel HD Graphics 530                                                     | 7         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 2.08%   |
| Nvidia GP108M [GeForce MX150]                                             | 6         | 1.79%   |
| Intel HD Graphics 620                                                     | 6         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 6         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 5         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 5         | 1.49%   |
| Intel Iris Plus Graphics G7                                               | 5         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 4         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 4         | 1.19%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 4         | 1.19%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                         | 4         | 1.19%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 1.19%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 3         | 0.89%   |
| Nvidia GP108M [GeForce MX230]                                             | 3         | 0.89%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 3         | 0.89%   |
| Intel Tiger Lake UHD Graphics                                             | 3         | 0.89%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 3         | 0.89%   |
| AMD Renoir                                                                | 3         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.6%    |
| Nvidia GM107GLM [Quadro M2000M]                                           | 2         | 0.6%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 2         | 0.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 0.6%    |
| Intel HD Graphics 630                                                     | 2         | 0.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 0.6%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                         | 1         | 0.3%    |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.3%    |
| Nvidia TU117M                                                             | 1         | 0.3%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                      | 1         | 0.3%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.3%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.3%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.3%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                    | 1         | 0.3%    |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                          | 1         | 0.3%    |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.3%    |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.3%    |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.3%    |
| Nvidia GP108BM [GeForce MX250]                                            | 1         | 0.3%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.3%    |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.3%    |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 160       | 62.99%  |
| Intel + Nvidia | 63        | 24.8%   |
| 1 x AMD        | 10        | 3.94%   |
| 1 x Nvidia     | 8         | 3.15%   |
| Intel + AMD    | 7         | 2.76%   |
| AMD + Nvidia   | 4         | 1.57%   |
| 2 x AMD        | 1         | 0.39%   |
| 1 x VIA        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 213       | 82.88%  |
| Proprietary | 38        | 14.79%  |
| Unknown     | 6         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 186       | 72.09%  |
| 3.01-4.0   | 22        | 8.53%   |
| 1.01-2.0   | 22        | 8.53%   |
| 0.01-0.5   | 11        | 4.26%   |
| 5.01-6.0   | 6         | 2.33%   |
| 0.51-1.0   | 6         | 2.33%   |
| 7.01-8.0   | 4         | 1.55%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 63        | 20.39%  |
| LG Display              | 42        | 13.59%  |
| Chimei Innolux          | 42        | 13.59%  |
| BOE                     | 35        | 11.33%  |
| Samsung Electronics     | 27        | 8.74%   |
| Dell                    | 26        | 8.41%   |
| Lenovo                  | 12        | 3.88%   |
| Sharp                   | 10        | 3.24%   |
| InfoVision              | 7         | 2.27%   |
| Goldstar                | 7         | 2.27%   |
| LG Philips              | 5         | 1.62%   |
| Hewlett-Packard         | 5         | 1.62%   |
| Chi Mei Optoelectronics | 5         | 1.62%   |
| Apple                   | 4         | 1.29%   |
| Philips                 | 3         | 0.97%   |
| CSO                     | 2         | 0.65%   |
| VOR                     | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| STD                     | 1         | 0.32%   |
| Seiko/Epson             | 1         | 0.32%   |
| RIS                     | 1         | 0.32%   |
| PANDA                   | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| LGD                     | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |
| BOE Technology Group    | 1         | 0.32%   |
| ASUSTek Computer        | 1         | 0.32%   |
| AOC                     | 1         | 0.32%   |
| Ancor Communications    | 1         | 0.32%   |
| Acer                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 1.9%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 6         | 1.9%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 1.27%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 4         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.27%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.95%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                        | 3         | 0.95%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch           | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch           | 3         | 0.95%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.63%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch       | 2         | 0.63%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.63%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch             | 2         | 0.63%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.63%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.63%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.63%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch              | 2         | 0.63%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                        | 2         | 0.63%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.63%   |
| BOE LCD Monitor BOE07BC 1920x1080 309x173mm 13.9-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO633D 1920x1080 309x174mm 14.0-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO453D 1920x1080 309x174mm 14.0-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 2         | 0.63%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.63%   |
| VOR A/G2356 VOR2300 1920x1080 473x296mm 22.0-inch                        | 1         | 0.32%   |
| Toshiba LCD Monitor LCD2207 1280x800 287x180mm 13.3-inch                 | 1         | 0.32%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                            | 1         | 0.32%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.32%   |
| Sharp LQ156D1JX01B SHP142A 3840x2160 346x194mm 15.6-inch                 | 1         | 0.32%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch                  | 1         | 0.32%   |
| Seiko/Epson LCD Monitor 1600x900                                         | 1         | 0.32%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch        | 1         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch     | 1         | 0.32%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.32%   |
| Samsung Electronics S24E450 SAM0CA2 1920x1080 531x299mm 24.0-inch        | 1         | 0.32%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch        | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 143       | 51.07%  |
| 1366x768 (WXGA)    | 62        | 22.14%  |
| 3840x2160 (4K)     | 21        | 7.5%    |
| 2560x1440 (QHD)    | 12        | 4.29%   |
| 1280x800 (WXGA)    | 11        | 3.93%   |
| 1920x1200 (WUXGA)  | 5         | 1.79%   |
| 1600x900 (HD+)     | 4         | 1.43%   |
| 3440x1440          | 3         | 1.07%   |
| 1440x900 (WXGA+)   | 3         | 1.07%   |
| 3200x1800 (QHD+)   | 2         | 0.71%   |
| 1680x1050 (WSXGA+) | 2         | 0.71%   |
| 1024x768 (XGA)     | 2         | 0.71%   |
| 3840x1080          | 1         | 0.36%   |
| 3456x2160          | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2560x1600          | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 2160x1440          | 1         | 0.36%   |
| 1280x768           | 1         | 0.36%   |
| 1280x1024 (SXGA)   | 1         | 0.36%   |
| 1024x600           | 1         | 0.36%   |
| Unknown            | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 120       | 38.83%  |
| 13      | 60        | 19.42%  |
| 14      | 41        | 13.27%  |
| 24      | 20        | 6.47%   |
| 27      | 16        | 5.18%   |
| 23      | 9         | 2.91%   |
| 17      | 9         | 2.91%   |
| 21      | 7         | 2.27%   |
| 12      | 7         | 2.27%   |
| 34      | 3         | 0.97%   |
| 31      | 3         | 0.97%   |
| Unknown | 3         | 0.97%   |
| 22      | 2         | 0.65%   |
| 19      | 2         | 0.65%   |
| 11      | 2         | 0.65%   |
| 84      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 25      | 1         | 0.32%   |
| 10      | 1         | 0.32%   |
| 8       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 187       | 61.31%  |
| 201-300     | 42        | 13.77%  |
| 501-600     | 40        | 13.11%  |
| 351-400     | 13        | 4.26%   |
| 401-500     | 9         | 2.95%   |
| 601-700     | 5         | 1.64%   |
| 701-800     | 3         | 0.98%   |
| Unknown     | 3         | 0.98%   |
| 801-900     | 1         | 0.33%   |
| 1501-2000   | 1         | 0.33%   |
| 101-200     | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 222       | 85.71%  |
| 16/10   | 25        | 9.65%   |
| 21/9    | 3         | 1.16%   |
| Unknown | 3         | 1.16%   |
| 5/4     | 2         | 0.77%   |
| 4/3     | 2         | 0.77%   |
| 3/2     | 2         | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 120       | 39.09%  |
| 81-90          | 72        | 23.45%  |
| 201-250        | 31        | 10.1%   |
| 71-80          | 28        | 9.12%   |
| 301-350        | 16        | 5.21%   |
| 61-70          | 7         | 2.28%   |
| 121-130        | 7         | 2.28%   |
| 351-500        | 6         | 1.95%   |
| 251-300        | 5         | 1.63%   |
| 151-200        | 3         | 0.98%   |
| Unknown        | 3         | 0.98%   |
| 51-60          | 2         | 0.65%   |
| 131-140        | 2         | 0.65%   |
| More than 1000 | 1         | 0.33%   |
| 41-50          | 1         | 0.33%   |
| 1-40           | 1         | 0.33%   |
| 501-1000       | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 124       | 41.2%   |
| 101-120       | 78        | 25.91%  |
| 51-100        | 54        | 17.94%  |
| 161-240       | 23        | 7.64%   |
| More than 240 | 19        | 6.31%   |
| Unknown       | 3         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 194       | 74.9%   |
| 2     | 49        | 18.92%  |
| 3     | 10        | 3.86%   |
| 0     | 5         | 1.93%   |
| 4     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 37.59%  |
| Realtek Semiconductor           | 131       | 32.19%  |
| Qualcomm Atheros                | 54        | 13.27%  |
| Broadcom                        | 19        | 4.67%   |
| Lenovo                          | 9         | 2.21%   |
| Broadcom Limited                | 7         | 1.72%   |
| MediaTek                        | 4         | 0.98%   |
| DisplayLink                     | 3         | 0.74%   |
| Xiaomi                          | 2         | 0.49%   |
| Samsung Electronics             | 2         | 0.49%   |
| Qualcomm Atheros Communications | 2         | 0.49%   |
| Marvell Technology Group        | 2         | 0.49%   |
| Edimax Technology               | 2         | 0.49%   |
| ASIX Electronics                | 2         | 0.49%   |
| Toshiba                         | 1         | 0.25%   |
| Ralink Technology               | 1         | 0.25%   |
| PEAK-System Technik             | 1         | 0.25%   |
| Nvidia                          | 1         | 0.25%   |
| Nokia Mobile Phones             | 1         | 0.25%   |
| Linksys                         | 1         | 0.25%   |
| LG Electronics                  | 1         | 0.25%   |
| Huawei Technologies             | 1         | 0.25%   |
| HMD Global                      | 1         | 0.25%   |
| Hewlett-Packard                 | 1         | 0.25%   |
| Google                          | 1         | 0.25%   |
| Dell                            | 1         | 0.25%   |
| Comneon                         | 1         | 0.25%   |
| Attansic Technology             | 1         | 0.25%   |
| ASUSTek Computer                | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 81        | 16.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 5.49%   |
| Intel Wireless 8265 / 8275                                              | 19        | 3.86%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 3.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 2.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 2.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 2.03%   |
| Intel Wireless 8260                                                     | 10        | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.83%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.42%   |
| Intel Wireless 3165                                                     | 7         | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.22%   |
| Intel Wireless 7265                                                     | 6         | 1.22%   |
| Intel Wireless 3160                                                     | 6         | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.02%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.81%   |
| Lenovo USB-C Dock Ethernet                                              | 4         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                                   | 4         | 0.81%   |
| Intel Ethernet Connection (10) I219-V                                   | 4         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.61%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 3         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.41%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.41%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.41%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.41%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.41%   |
| Intel Wireless 7260                                                     | 2         | 0.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.41%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                                   | 2         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                                   | 2         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 145       | 56.42%  |
| Qualcomm Atheros                | 50        | 19.46%  |
| Realtek Semiconductor           | 27        | 10.51%  |
| Broadcom                        | 19        | 7.39%   |
| Broadcom Limited                | 5         | 1.95%   |
| MediaTek                        | 4         | 1.56%   |
| Qualcomm Atheros Communications | 2         | 0.78%   |
| Edimax Technology               | 2         | 0.78%   |
| Ralink Technology               | 1         | 0.39%   |
| Dell                            | 1         | 0.39%   |
| ASUSTek Computer                | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 19        | 7.36%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 6.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 4.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 4.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 4.26%   |
| Intel Wireless 8260                                                     | 10        | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.49%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 3.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 2.71%   |
| Intel Wireless 3165                                                     | 7         | 2.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.33%   |
| Intel Wireless 7265                                                     | 6         | 2.33%   |
| Intel Wireless 3160                                                     | 6         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.78%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.78%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.78%   |
| Intel Wireless 7260                                                     | 2         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.78%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.78%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.78%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.39%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.39%   |
| MediaTek WLAN controller                                                | 1         | 0.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.39%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.39%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.39%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.39%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.39%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 0.39%   |
| Edimax RTL8192S WLAN Adapter                                            | 1         | 0.39%   |
| Edimax 802.11ac WLAN Adapter                                            | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 123       | 54.67%  |
| Intel                    | 59        | 26.22%  |
| Qualcomm Atheros         | 10        | 4.44%   |
| Lenovo                   | 9         | 4%      |
| Broadcom                 | 5         | 2.22%   |
| DisplayLink              | 3         | 1.33%   |
| Broadcom Limited         | 3         | 1.33%   |
| Xiaomi                   | 2         | 0.89%   |
| Samsung Electronics      | 2         | 0.89%   |
| Marvell Technology Group | 2         | 0.89%   |
| ASIX Electronics         | 2         | 0.89%   |
| Nvidia                   | 1         | 0.44%   |
| Linksys                  | 1         | 0.44%   |
| HMD Global               | 1         | 0.44%   |
| Google                   | 1         | 0.44%   |
| Attansic Technology      | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 35.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 11.89%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.52%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.2%    |
| Lenovo USB-C Dock Ethernet                                        | 4         | 1.76%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.76%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 1.76%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.76%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 3         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.88%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.44%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.44%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.44%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.44%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.44%   |
| Lenovo USB-C Hub                                                  | 1         | 0.44%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.44%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.44%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.44%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.44%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.44%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.44%   |
| HMD Global TA-1032                                                | 1         | 0.44%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.44%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 0.44%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 249       | 54.01%  |
| Ethernet | 205       | 44.47%  |
| Modem    | 6         | 1.3%    |
| Unknown  | 1         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 75.75%  |
| Ethernet | 64        | 23.88%  |
| Modem    | 1         | 0.37%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 186       | 73.23%  |
| 1     | 66        | 25.98%  |
| 3     | 2         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 226       | 88.28%  |
| Yes  | 30        | 11.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 60.19%  |
| Qualcomm Atheros Communications | 18        | 8.74%   |
| Realtek Semiconductor           | 15        | 7.28%   |
| IMC Networks                    | 13        | 6.31%   |
| Broadcom                        | 9         | 4.37%   |
| Foxconn / Hon Hai               | 6         | 2.91%   |
| Lite-On Technology              | 5         | 2.43%   |
| Apple                           | 4         | 1.94%   |
| Dell                            | 3         | 1.46%   |
| Hewlett-Packard                 | 2         | 0.97%   |
| Askey Computer                  | 2         | 0.97%   |
| Toshiba                         | 1         | 0.49%   |
| Realtek                         | 1         | 0.49%   |
| MediaTek                        | 1         | 0.49%   |
| Cambridge Silicon Radio         | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 52        | 25.24%  |
| Intel AX201 Bluetooth                               | 35        | 16.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 8.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 4.37%   |
| Intel AX200 Bluetooth                               | 8         | 3.88%   |
| Realtek Bluetooth Radio                             | 6         | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 1.94%   |
| Lite-On Bluetooth Device                            | 4         | 1.94%   |
| IMC Networks Bluetooth Device                       | 4         | 1.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.46%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.97%   |
| IMC Networks Wireless_Device                        | 2         | 0.97%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.97%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.97%   |
| Foxconn / Hon Hai BT                                | 2         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.97%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.97%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.97%   |
| Askey Bluetooth Device                              | 2         | 0.97%   |
| Apple Bluetooth Host Controller                     | 2         | 0.97%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.49%   |
| Realtek Bluetooth Radio                             | 1         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.49%   |
| MediaTek BT                                         | 1         | 0.49%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.49%   |
| Intel Bluetooth Device                              | 1         | 0.49%   |
| Intel AX210 Bluetooth                               | 1         | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.49%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.49%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 0.49%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.49%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.49%   |
| Broadcom BCM20702A0                                 | 1         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.49%   |
| Broadcom BCM2045A0                                  | 1         | 0.49%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 0.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.49%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 239       | 76.85%  |
| Nvidia                     | 32        | 10.29%  |
| AMD                        | 14        | 4.5%    |
| Lenovo                     | 9         | 2.89%   |
| Realtek Semiconductor      | 4         | 1.29%   |
| Microsoft                  | 2         | 0.64%   |
| GN Netcom                  | 2         | 0.64%   |
| XMOS                       | 1         | 0.32%   |
| VIA Technologies           | 1         | 0.32%   |
| Sennheiser Communications  | 1         | 0.32%   |
| PreSonus Audio Electronics | 1         | 0.32%   |
| Plantronics                | 1         | 0.32%   |
| Logitech                   | 1         | 0.32%   |
| FIFINE Microphones         | 1         | 0.32%   |
| Creative Technology        | 1         | 0.32%   |
| C-Media Electronics        | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 51        | 14.61%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 5.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 4.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 3.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 3.44%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 3.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 2.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 2.29%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.43%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.15%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 4         | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.15%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.86%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 3         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.86%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.57%   |
| Microsoft LifeChat LX-3000 Headset                                                                | 2         | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.57%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.57%   |
| XMOS xDuoo USB Audio 2.0                                                                          | 1         | 0.29%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.29%   |
| Sennheiser Communications Sennheiser SC 130 USB                                                   | 1         | 0.29%   |
| PreSonus Audio Electronics Studio 26c                                                             | 1         | 0.29%   |
| Plantronics Audio 628 USB                                                                         | 1         | 0.29%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.29%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.29%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.29%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.29%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.29%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.29%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.29%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 0.29%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 0.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.29%   |
| GN Netcom Jabra SPEAK 510 USB                                                                     | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 28.65%  |
| SK hynix            | 40        | 23.39%  |
| Micron Technology   | 30        | 17.54%  |
| Kingston            | 13        | 7.6%    |
| Unknown             | 11        | 6.43%   |
| Crucial             | 8         | 4.68%   |
| G.Skill             | 4         | 2.34%   |
| Ramaxel Technology  | 3         | 1.75%   |
| Nanya Technology    | 3         | 1.75%   |
| Transcend           | 2         | 1.17%   |
| Elpida              | 2         | 1.17%   |
| V-Color             | 1         | 0.58%   |
| Corsair             | 1         | 0.58%   |
| Avant               | 1         | 0.58%   |
| ASint Technology    | 1         | 0.58%   |
| A-DATA Technology   | 1         | 0.58%   |
| 48spaces            | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 2.27%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 3         | 1.7%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 3         | 1.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 3         | 1.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 3         | 1.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 1.7%    |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s   | 3         | 1.7%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 3         | 1.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 2         | 1.14%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 2         | 1.14%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 2         | 1.14%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s               | 2         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 2         | 1.14%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 2         | 1.14%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 1.14%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 2         | 1.14%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.14%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s       | 2         | 1.14%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 1.14%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s             | 2         | 1.14%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 2         | 1.14%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s       | 2         | 1.14%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s    | 2         | 1.14%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s         | 2         | 1.14%   |
| Kingston RAM 9905711-035.A00G 8GB SODIMM DDR4 3200MT/s         | 2         | 1.14%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s        | 2         | 1.14%   |
| V-Color RAM TF416G26D819 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.57%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s            | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                       | 1         | 0.57%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s              | 1         | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 0.57%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s        | 1         | 0.57%   |
| SK hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR2 667MT/s       | 1         | 0.57%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.57%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.57%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.57%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s         | 1         | 0.57%   |
| SK hynix RAM HMT125S6AFP8C-G7 2GB SODIMM DDR3 1066MT/s         | 1         | 0.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 1         | 0.57%   |
| SK hynix RAM HMA82GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 0.57%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.57%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.57%   |
| SK hynix RAM H9CCNNNCLTMLAR-NUD 8GB Chip LPDDR3 1867MT/s       | 1         | 0.57%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.57%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 79        | 57.25%  |
| DDR3    | 34        | 24.64%  |
| LPDDR3  | 9         | 6.52%   |
| DDR2    | 9         | 6.52%   |
| LPDDR4  | 2         | 1.45%   |
| DDR5    | 2         | 1.45%   |
| DDR     | 2         | 1.45%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 123       | 88.49%  |
| Row Of Chips | 14        | 10.07%  |
| DIMM         | 1         | 0.72%   |
| Chip         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 49        | 32.45%  |
| 4096  | 36        | 23.84%  |
| 16384 | 34        | 22.52%  |
| 2048  | 17        | 11.26%  |
| 1024  | 8         | 5.3%    |
| 32768 | 7         | 4.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 43        | 28.86%  |
| 3200    | 24        | 16.11%  |
| 1600    | 24        | 16.11%  |
| 2133    | 14        | 9.4%    |
| 2400    | 11        | 7.38%   |
| 667     | 6         | 4.03%   |
| 1334    | 5         | 3.36%   |
| 1067    | 4         | 2.68%   |
| Unknown | 3         | 2.01%   |
| 4800    | 2         | 1.34%   |
| 4267    | 2         | 1.34%   |
| 3266    | 2         | 1.34%   |
| 1867    | 2         | 1.34%   |
| 1333    | 2         | 1.34%   |
| 800     | 2         | 1.34%   |
| 8400    | 1         | 0.67%   |
| 1066    | 1         | 0.67%   |
| 533     | 1         | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M288x Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 43        | 17.84%  |
| Chicony Electronics                    | 41        | 17.01%  |
| Realtek Semiconductor                  | 40        | 16.6%   |
| Acer                                   | 20        | 8.3%    |
| Sunplus Innovation Technology          | 19        | 7.88%   |
| Microdia                               | 16        | 6.64%   |
| Lite-On Technology                     | 7         | 2.9%    |
| Apple                                  | 7         | 2.9%    |
| Suyin                                  | 6         | 2.49%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.49%   |
| Logitech                               | 5         | 2.07%   |
| Syntek                                 | 4         | 1.66%   |
| Silicon Motion                         | 4         | 1.66%   |
| Quanta                                 | 4         | 1.66%   |
| Microsoft                              | 4         | 1.66%   |
| Luxvisions Innotech Limited            | 3         | 1.24%   |
| Lenovo                                 | 2         | 0.83%   |
| ALi                                    | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Samsung Electronics                    | 1         | 0.41%   |
| Primax Electronics                     | 1         | 0.41%   |
| Jieli Technology                       | 1         | 0.41%   |
| Generalplus Technology                 | 1         | 0.41%   |
| eMPIA Technology                       | 1         | 0.41%   |
| Cubeternet                             | 1         | 0.41%   |
| Alcor Micro                            | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 20        | 8.26%   |
| Chicony Integrated Camera                     | 14        | 5.79%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 12        | 4.96%   |
| IMC Networks Integrated Camera                | 11        | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam             | 10        | 4.13%   |
| Microdia Integrated_Webcam_HD                 | 7         | 2.89%   |
| Acer Integrated Camera                        | 5         | 2.07%   |
| Chicony HP HD Camera                          | 4         | 1.65%   |
| Apple iPhone 5/5C/5S/6/SE                     | 4         | 1.65%   |
| Acer SunplusIT Integrated Camera              | 4         | 1.65%   |
| Acer Lenovo EasyCamera                        | 4         | 1.65%   |
| Syntek Integrated Camera                      | 3         | 1.24%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 1.24%   |
| Sunplus Depstech webcam MIC                   | 3         | 1.24%   |
| Realtek Lenovo EasyCamera                     | 3         | 1.24%   |
| Realtek Integrated Webcam HD                  | 3         | 1.24%   |
| Lite-On HP HD Camera                          | 3         | 1.24%   |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 1.24%   |
| Chicony Lenovo EasyCamera                     | 3         | 1.24%   |
| Chicony Integrated Camera (1280x720@30)       | 3         | 1.24%   |
| Realtek USB2.0 HD UVC WebCam                  | 2         | 0.83%   |
| Realtek USB Camera                            | 2         | 0.83%   |
| Realtek HP Wide Vision HD Camera              | 2         | 0.83%   |
| Quanta USB Webcam                             | 2         | 0.83%   |
| Microsoft LifeCam NX-6000                     | 2         | 0.83%   |
| Microdia Integrated Webcam                    | 2         | 0.83%   |
| Microdia Dell Integrated HD Webcam            | 2         | 0.83%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.83%   |
| Lite-On Integrated Camera                     | 2         | 0.83%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 2         | 0.83%   |
| IMC Networks Lenovo EasyCamera                | 2         | 0.83%   |
| Chicony HP Webcam                             | 2         | 0.83%   |
| Apple FaceTime HD Camera                      | 2         | 0.83%   |
| ALi Gateway Webcam                            | 2         | 0.83%   |
| Acer BisonCam, NB Pro                         | 2         | 0.83%   |
| Z-Star WebCam SC-03FFL11739P                  | 1         | 0.41%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.41%   |
| Suyin Integrated_Webcam_HD                    | 1         | 0.41%   |
| Suyin HP webcam [dv6-1190en]                  | 1         | 0.41%   |
| Suyin HP Truevision HD                        | 1         | 0.41%   |
| Suyin Asus Integrated Webcam [CN031B]         | 1         | 0.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 0.41%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 0.41%   |
| Sunplus Lenovo EasyCamera                     | 1         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 0.41%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 0.41%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.41%   |
| Sunplus Integrated Camera                     | 1         | 0.41%   |
| Sunplus HD WebCam                             | 1         | 0.41%   |
| Sunplus HD User Facing                        | 1         | 0.41%   |
| Sunplus Dell HD Webcam                        | 1         | 0.41%   |
| Sunplus Dell E5570 integrated webcam          | 1         | 0.41%   |
| Sunplus ASUS Webcam                           | 1         | 0.41%   |
| Sunplus ASUS USB2.0 Webcam                    | 1         | 0.41%   |
| Sunplus 1.3M HD WebCam                        | 1         | 0.41%   |
| Silicon Motion WebCam SCB-1100N               | 1         | 0.41%   |
| Silicon Motion WebCam SCB-0355N               | 1         | 0.41%   |
| Silicon Motion WebCam SC-13HDL11939N          | 1         | 0.41%   |
| Silicon Motion HP Webcam-101                  | 1         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 21        | 40.38%  |
| Validity Sensors           | 16        | 30.77%  |
| Shenzhen Goodix Technology | 7         | 13.46%  |
| STMicroelectronics         | 2         | 3.85%   |
| Elan Microelectronics      | 2         | 3.85%   |
| AuthenTec                  | 2         | 3.85%   |
| Upek                       | 1         | 1.92%   |
| LighTuning Technology      | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 21.15%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 5.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.85%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.85%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.85%   |
| Unknown                                                                    | 2         | 3.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.92%   |
| Validity Sensors VFS491                                                    | 1         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.92%   |
| Synaptics  WBDI                                                            | 1         | 1.92%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.92%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 65.63%  |
| Alcor Micro | 11        | 34.38%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 34.38%  |
| Broadcom 58200                                                               | 8         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 18.75%  |
| Broadcom 5880                                                                | 6         | 18.75%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 150       | 57.25%  |
| 1     | 85        | 32.44%  |
| 2     | 22        | 8.4%    |
| 3     | 3         | 1.15%   |
| 7     | 1         | 0.38%   |
| 4     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 35.17%  |
| Graphics card            | 29        | 20%     |
| Chipcard                 | 29        | 20%     |
| Net/wireless             | 15        | 10.34%  |
| Multimedia controller    | 5         | 3.45%   |
| Camera                   | 4         | 2.76%   |
| Card reader              | 3         | 2.07%   |
| Sound                    | 2         | 1.38%   |
| Bluetooth                | 2         | 1.38%   |
| Unassigned class         | 1         | 0.69%   |
| Storage                  | 1         | 0.69%   |
| Network                  | 1         | 0.69%   |
| Net/ethernet             | 1         | 0.69%   |
| Communication controller | 1         | 0.69%   |


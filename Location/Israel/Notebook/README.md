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

Total: 408

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Dell          | Vostro 15 5510              | [10f4ac5e13](https://linux-hardware.org/?probe=10f4ac5e13) | Dec 24, 2022 |
| Dell          | XPS 15 9520                 | [b9b1f8140b](https://linux-hardware.org/?probe=b9b1f8140b) | Dec 18, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| Dell          | Latitude E6420              | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [dc13dde66a](https://linux-hardware.org/?probe=dc13dde66a) | Nov 29, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| Dell          | Vostro 3300                 | [ae100dd7e2](https://linux-hardware.org/?probe=ae100dd7e2) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| ASUSTek       | UX430UNR                    | [f04bf95806](https://linux-hardware.org/?probe=f04bf95806) | Nov 08, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| HP            | Laptop 15-dw2xxx            | [66b04ff6f8](https://linux-hardware.org/?probe=66b04ff6f8) | Oct 20, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Dell          | Inspiron 5559               | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [bc43cff31b](https://linux-hardware.org/?probe=bc43cff31b) | Sep 23, 2022 |
| Dell          | Inspiron 1545               | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Dell          | Latitude E4300              | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
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


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu 20.04     | 73        | 24.41%  |
| Ubuntu 18.04     | 30        | 10.03%  |
| Ubuntu 22.04     | 9         | 3.01%   |
| Fedora 35        | 8         | 2.68%   |
| Ubuntu 21.04     | 7         | 2.34%   |
| Arch             | 6         | 2.01%   |
| Zorin 15         | 5         | 1.67%   |
| ROSA R11         | 5         | 1.67%   |
| Pop!_OS 21.04    | 5         | 1.67%   |
| Manjaro          | 5         | 1.67%   |
| Linux Mint 20.1  | 5         | 1.67%   |
| Fedora 36        | 5         | 1.67%   |
| Ubuntu 19.10     | 4         | 1.34%   |
| ROSA R10         | 4         | 1.34%   |
| OpenMandriva 4.3 | 4         | 1.34%   |
| Fedora 34        | 4         | 1.34%   |
| Fedora 33        | 4         | 1.34%   |
| Zorin 16         | 3         | 1%      |
| Ubuntu 20.10     | 3         | 1%      |
| Ubuntu 19.04     | 3         | 1%      |
| Pop!_OS 22.04    | 3         | 1%      |
| Pop!_OS 21.10    | 3         | 1%      |
| Pop!_OS 20.10    | 3         | 1%      |
| Manjaro 20.2     | 3         | 1%      |
| Linux Mint 21    | 3         | 1%      |
| Linux Mint 20.3  | 3         | 1%      |
| Linux Mint 20    | 3         | 1%      |
| Fedora 32        | 3         | 1%      |
| Arch Rolling     | 3         | 1%      |
| Xubuntu 22.04    | 2         | 0.67%   |
| ROSA R9          | 2         | 0.67%   |
| ROSA R8          | 2         | 0.67%   |
| ROSA R11.1       | 2         | 0.67%   |
| Pop!_OS 20.04    | 2         | 0.67%   |
| OpenMandriva 4.2 | 2         | 0.67%   |
| Linux Mint 20.2  | 2         | 0.67%   |
| Linux Mint 19.2  | 2         | 0.67%   |
| Kubuntu 20.04    | 2         | 0.67%   |
| KDE neon 20.04   | 2         | 0.67%   |
| Fedora 37        | 2         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 128       | 46.38%  |
| Fedora       | 23        | 8.33%   |
| Linux Mint   | 21        | 7.61%   |
| Pop!_OS      | 16        | 5.8%    |
| ROSA         | 14        | 5.07%   |
| Manjaro      | 12        | 4.35%   |
| Zorin        | 9         | 3.26%   |
| Arch         | 9         | 3.26%   |
| OpenMandriva | 7         | 2.54%   |
| Endless      | 7         | 2.54%   |
| Xubuntu      | 6         | 2.17%   |
| Kubuntu      | 3         | 1.09%   |
| KDE neon     | 2         | 0.72%   |
| Debian       | 2         | 0.72%   |
| CentOS       | 2         | 0.72%   |
| BlackPanther | 2         | 0.72%   |
| ArcoLinux    | 2         | 0.72%   |
| Ubuntu MATE  | 1         | 0.36%   |
| RHEL         | 1         | 0.36%   |
| PureOS       | 1         | 0.36%   |
| openSUSE     | 1         | 0.36%   |
| Lubuntu      | 1         | 0.36%   |
| Kali         | 1         | 0.36%   |
| EndeavourOS  | 1         | 0.36%   |
| Elementary   | 1         | 0.36%   |
| Devuan       | 1         | 0.36%   |
| Clear Linux  | 1         | 0.36%   |
| Artix        | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 10        | 3.18%   |
| 5.4.0-48-generic        | 8         | 2.55%   |
| 5.4.0-52-generic        | 5         | 1.59%   |
| 5.0.0-23-generic        | 5         | 1.59%   |
| 5.4.0-26-generic        | 4         | 1.27%   |
| 5.16.7-desktop-1omv4003 | 4         | 1.27%   |
| 5.8.0-59-generic        | 3         | 0.96%   |
| 5.8.0-44-generic        | 3         | 0.96%   |
| 5.4.0-72-generic        | 3         | 0.96%   |
| 5.4.0-65-generic        | 3         | 0.96%   |
| 5.4.0-58-generic        | 3         | 0.96%   |
| 5.3.0-46-generic        | 3         | 0.96%   |
| 5.3.0-42-generic        | 3         | 0.96%   |
| 5.3.0-26-generic        | 3         | 0.96%   |
| 5.15.0-50-generic       | 3         | 0.96%   |
| 5.15.0-41-generic       | 3         | 0.96%   |
| 5.11.0-34-generic       | 3         | 0.96%   |
| 6.0.8-300.fc37.x86_64   | 2         | 0.64%   |
| 5.9.16-200.fc33.x86_64  | 2         | 0.64%   |
| 5.8.16-300.fc33.x86_64  | 2         | 0.64%   |
| 5.8.0-7642-generic      | 2         | 0.64%   |
| 5.8.0-63-generic        | 2         | 0.64%   |
| 5.8.0-53-generic        | 2         | 0.64%   |
| 5.8.0-41-generic        | 2         | 0.64%   |
| 5.4.2-1-MANJARO         | 2         | 0.64%   |
| 5.4.0-91-generic        | 2         | 0.64%   |
| 5.4.0-70-generic        | 2         | 0.64%   |
| 5.4.0-62-generic        | 2         | 0.64%   |
| 5.4.0-53-generic        | 2         | 0.64%   |
| 5.4.0-47-generic        | 2         | 0.64%   |
| 5.4.0-40-generic        | 2         | 0.64%   |
| 5.4.0-37-generic        | 2         | 0.64%   |
| 5.4.0-29-generic        | 2         | 0.64%   |
| 5.4.0-122-generic       | 2         | 0.64%   |
| 5.3.0-53-generic        | 2         | 0.64%   |
| 5.3.0-51-generic        | 2         | 0.64%   |
| 5.3.0-28-generic        | 2         | 0.64%   |
| 5.3.0-19-generic        | 2         | 0.64%   |
| 5.19.1-arch2-1          | 2         | 0.64%   |
| 5.16.18-200.fc35.x86_64 | 2         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 67        | 22.11%  |
| 5.8.0   | 23        | 7.59%   |
| 5.11.0  | 21        | 6.93%   |
| 4.15.0  | 20        | 6.6%    |
| 5.3.0   | 18        | 5.94%   |
| 5.15.0  | 16        | 5.28%   |
| 5.13.0  | 12        | 3.96%   |
| 5.0.0   | 12        | 3.96%   |
| 4.18.0  | 6         | 1.98%   |
| 5.16.7  | 4         | 1.32%   |
| 5.10.0  | 3         | 0.99%   |
| 4.9.60  | 3         | 0.99%   |
| 6.0.8   | 2         | 0.66%   |
| 6.0.2   | 2         | 0.66%   |
| 5.9.16  | 2         | 0.66%   |
| 5.8.16  | 2         | 0.66%   |
| 5.7.10  | 2         | 0.66%   |
| 5.6.0   | 2         | 0.66%   |
| 5.4.2   | 2         | 0.66%   |
| 5.19.1  | 2         | 0.66%   |
| 5.16.18 | 2         | 0.66%   |
| 5.16.15 | 2         | 0.66%   |
| 5.15.2  | 2         | 0.66%   |
| 5.13.12 | 2         | 0.66%   |
| 4.9.20  | 2         | 0.66%   |
| 4.19.0  | 2         | 0.66%   |
| 4.18.16 | 2         | 0.66%   |
| 4.1.34  | 2         | 0.66%   |
| 6.0.7   | 1         | 0.33%   |
| 6.0.12  | 1         | 0.33%   |
| 5.9.9   | 1         | 0.33%   |
| 5.9.3   | 1         | 0.33%   |
| 5.9.13  | 1         | 0.33%   |
| 5.9.11  | 1         | 0.33%   |
| 5.8.5   | 1         | 0.33%   |
| 5.8.11  | 1         | 0.33%   |
| 5.8.1   | 1         | 0.33%   |
| 5.7.7   | 1         | 0.33%   |
| 5.7.11  | 1         | 0.33%   |
| 5.7.0   | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 70        | 23.65%  |
| 5.8     | 27        | 9.12%   |
| 5.11    | 26        | 8.78%   |
| 5.15    | 24        | 8.11%   |
| 5.3     | 20        | 6.76%   |
| 4.15    | 20        | 6.76%   |
| 5.13    | 15        | 5.07%   |
| 5.16    | 13        | 4.39%   |
| 5.0     | 12        | 4.05%   |
| 5.10    | 10        | 3.38%   |
| 5.18    | 8         | 2.7%    |
| 4.18    | 8         | 2.7%    |
| 6.0     | 6         | 2.03%   |
| 4.9     | 6         | 2.03%   |
| 5.9     | 5         | 1.69%   |
| 5.7     | 4         | 1.35%   |
| 5.19    | 4         | 1.35%   |
| 5.14    | 4         | 1.35%   |
| 5.6     | 3         | 1.01%   |
| 5.17    | 3         | 1.01%   |
| 4.19    | 3         | 1.01%   |
| 4.1     | 2         | 0.68%   |
| 5.5     | 1         | 0.34%   |
| 5.12    | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 264       | 96.7%   |
| i686   | 9         | 3.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 156       | 55.71%  |
| Unknown    | 34        | 12.14%  |
| KDE5       | 33        | 11.79%  |
| X-Cinnamon | 16        | 5.71%   |
| XFCE       | 15        | 5.36%   |
| KDE4       | 11        | 3.93%   |
| KDE        | 4         | 1.43%   |
| Cinnamon   | 3         | 1.07%   |
| MATE       | 2         | 0.71%   |
| LXQt       | 2         | 0.71%   |
| Trinity    | 1         | 0.36%   |
| Pantheon   | 1         | 0.36%   |
| LXDE       | 1         | 0.36%   |
| i3         | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 217       | 78.34%  |
| Wayland | 37        | 13.36%  |
| Unknown | 21        | 7.58%   |
| Tty     | 2         | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 150       | 53.96%  |
| GDM     | 53        | 19.06%  |
| SDDM    | 23        | 8.27%   |
| GDM3    | 20        | 7.19%   |
| LightDM | 11        | 3.96%   |
| KDM     | 11        | 3.96%   |
| TDM     | 10        | 3.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IL   | 111       | 39.64%  |
| en_US   | 83        | 29.64%  |
| Unknown | 43        | 15.36%  |
| ru_RU   | 17        | 6.07%   |
| he_IL   | 12        | 4.29%   |
| en_GB   | 3         | 1.07%   |
| C       | 3         | 1.07%   |
| fr_FR   | 2         | 0.71%   |
| en_AG   | 2         | 0.71%   |
| es_ES   | 1         | 0.36%   |
| en_NZ   | 1         | 0.36%   |
| en_CA   | 1         | 0.36%   |
| en_AU   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 159       | 56.58%  |
| BIOS | 122       | 43.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 224       | 82.05%  |
| Btrfs   | 18        | 6.59%   |
| Unknown | 14        | 5.13%   |
| Overlay | 11        | 4.03%   |
| Xfs     | 4         | 1.47%   |
| Ext3    | 1         | 0.37%   |
| Ext2    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 156       | 55.91%  |
| GPT     | 100       | 35.84%  |
| MBR     | 23        | 8.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 254       | 92.7%   |
| Yes       | 20        | 7.3%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 202       | 73.99%  |
| Yes       | 71        | 26.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 80        | 29.3%   |
| Dell                | 64        | 23.44%  |
| ASUSTek Computer    | 48        | 17.58%  |
| Hewlett-Packard     | 43        | 15.75%  |
| Acer                | 8         | 2.93%   |
| Samsung Electronics | 5         | 1.83%   |
| Toshiba             | 4         | 1.47%   |
| Apple               | 4         | 1.47%   |
| LG Electronics      | 3         | 1.1%    |
| Fujitsu             | 3         | 1.1%    |
| Fujitsu Siemens     | 2         | 0.73%   |
| Timi                | 1         | 0.37%   |
| System76            | 1         | 0.37%   |
| Purism              | 1         | 0.37%   |
| Notebook            | 1         | 0.37%   |
| MSI                 | 1         | 0.37%   |
| IP3 Tech            | 1         | 0.37%   |
| HUAWEI              | 1         | 0.37%   |
| GPD                 | 1         | 0.37%   |
| Unknown             | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 5         | 1.83%   |
| Lenovo IdeaPad 5 14ITL05 82FE                                                            | 3         | 1.1%    |
| HP Pavilion Notebook                                                                     | 3         | 1.1%    |
| HP Compaq Presario CQ61                                                                  | 3         | 1.1%    |
| ASUS UX331UA                                                                             | 3         | 1.1%    |
| Lenovo V14-IIL 82C4                                                                      | 2         | 0.73%   |
| Lenovo IdeaPad Y700-15ISK 80NV                                                           | 2         | 0.73%   |
| Lenovo IdeaPad L340-15IWL 81LG                                                           | 2         | 0.73%   |
| Lenovo G50-80 80L0                                                                       | 2         | 0.73%   |
| HP ZBook 15 G3                                                                           | 2         | 0.73%   |
| HP ProBook 430 G6                                                                        | 2         | 0.73%   |
| HP EliteBook 840 G5                                                                      | 2         | 0.73%   |
| Fujitsu LIFEBOOK AH530                                                                   | 2         | 0.73%   |
| Dell XPS 15 9570                                                                         | 2         | 0.73%   |
| Dell Latitude E6420                                                                      | 2         | 0.73%   |
| Dell Latitude E6330                                                                      | 2         | 0.73%   |
| Dell Latitude E4300                                                                      | 2         | 0.73%   |
| Dell Latitude 7400                                                                       | 2         | 0.73%   |
| Dell Latitude 5410                                                                       | 2         | 0.73%   |
| Dell Inspiron 3593                                                                       | 2         | 0.73%   |
| Dell Inspiron 3542                                                                       | 2         | 0.73%   |
| Dell Inspiron 13-5378                                                                    | 2         | 0.73%   |
| ASUS ZenBook UX425EA_UX425EA                                                             | 2         | 0.73%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                                                     | 2         | 0.73%   |
| ASUS UX430UNR                                                                            | 2         | 0.73%   |
| ASUS N550JV                                                                              | 2         | 0.73%   |
| Toshiba Satellite P50t-B-10T                                                             | 1         | 0.37%   |
| Toshiba Satellite L755                                                                   | 1         | 0.37%   |
| Toshiba Satellite A200                                                                   | 1         | 0.37%   |
| Toshiba PORTEGE R700                                                                     | 1         | 0.37%   |
| Timi TM1701                                                                              | 1         | 0.37%   |
| System76 Gazelle                                                                         | 1         | 0.37%   |
| Samsung N248P                                                                            | 1         | 0.37%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV                                                 | 1         | 0.37%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                                                      | 1         | 0.37%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B                                               | 1         | 0.37%   |
| Purism Librem 14                                                                         | 1         | 0.37%   |
| Notebook N2x0WU                                                                          | 1         | 0.37%   |
| MSI Summit E16FlipEvo A12MT                                                              | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 39        | 14.29%  |
| Dell Latitude     | 25        | 9.16%   |
| Dell Inspiron     | 19        | 6.96%   |
| Lenovo IdeaPad    | 18        | 6.59%   |
| ASUS VivoBook     | 11        | 4.03%   |
| HP Pavilion       | 9         | 3.3%    |
| Dell Vostro       | 9         | 3.3%    |
| Dell XPS          | 8         | 2.93%   |
| ASUS ROG          | 7         | 2.56%   |
| Acer Aspire       | 7         | 2.56%   |
| Lenovo Legion     | 6         | 2.2%    |
| HP ProBook        | 6         | 2.2%    |
| HP EliteBook      | 5         | 1.83%   |
| ASUS ZenBook      | 5         | 1.83%   |
| Unknown           | 5         | 1.83%   |
| HP ZBook          | 4         | 1.47%   |
| Toshiba Satellite | 3         | 1.1%    |
| Lenovo G50-80     | 3         | 1.1%    |
| HP Laptop         | 3         | 1.1%    |
| HP Compaq         | 3         | 1.1%    |
| Fujitsu LIFEBOOK  | 3         | 1.1%    |
| ASUS UX331UA      | 3         | 1.1%    |
| Lenovo Yoga       | 2         | 0.73%   |
| Lenovo V14-IIL    | 2         | 0.73%   |
| HP ENVY           | 2         | 0.73%   |
| ASUS UX430UNR     | 2         | 0.73%   |
| ASUS N550JV       | 2         | 0.73%   |
| ASUS ASUS         | 2         | 0.73%   |
| Toshiba PORTEGE   | 1         | 0.37%   |
| Timi TM1701       | 1         | 0.37%   |
| System76 Gazelle  | 1         | 0.37%   |
| Samsung N248P     | 1         | 0.37%   |
| Samsung 3570R     | 1         | 0.37%   |
| Samsung 355V4C    | 1         | 0.37%   |
| Samsung 350V5C    | 1         | 0.37%   |
| Samsung 300V3A    | 1         | 0.37%   |
| Purism Librem     | 1         | 0.37%   |
| Notebook N2x0WU   | 1         | 0.37%   |
| MSI Summit        | 1         | 0.37%   |
| LG A310           | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 44        | 16.12%  |
| 2020 | 33        | 12.09%  |
| 2018 | 29        | 10.62%  |
| 2017 | 20        | 7.33%   |
| 2016 | 20        | 7.33%   |
| 2015 | 19        | 6.96%   |
| 2021 | 18        | 6.59%   |
| 2012 | 16        | 5.86%   |
| 2011 | 16        | 5.86%   |
| 2010 | 12        | 4.4%    |
| 2008 | 11        | 4.03%   |
| 2014 | 10        | 3.66%   |
| 2013 | 8         | 2.93%   |
| 2009 | 6         | 2.2%    |
| 2007 | 6         | 2.2%    |
| 2022 | 3         | 1.1%    |
| 2006 | 2         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 273       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 241       | 87.64%  |
| Enabled  | 34        | 12.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 272       | 99.63%  |
| Yes  | 1         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 72        | 26.37%  |
| 16.01-24.0  | 66        | 24.18%  |
| 32.01-64.0  | 37        | 13.55%  |
| 3.01-4.0    | 35        | 12.82%  |
| 8.01-16.0   | 35        | 12.82%  |
| 1.01-2.0    | 14        | 5.13%   |
| 64.01-256.0 | 5         | 1.83%   |
| 2.01-3.0    | 4         | 1.47%   |
| 24.01-32.0  | 3         | 1.1%    |
| 0.51-1.0    | 2         | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 27.3%   |
| 2.01-3.0   | 71        | 24.23%  |
| 4.01-8.0   | 49        | 16.72%  |
| 3.01-4.0   | 49        | 16.72%  |
| 8.01-16.0  | 24        | 8.19%   |
| 0.51-1.0   | 13        | 4.44%   |
| 16.01-24.0 | 4         | 1.37%   |
| 0.01-0.5   | 3         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 228       | 83.21%  |
| 2      | 42        | 15.33%  |
| 3      | 2         | 0.73%   |
| 0      | 2         | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 68.13%  |
| Yes       | 87        | 31.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 79.93%  |
| No        | 55        | 20.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 98.17%  |
| No        | 5         | 1.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 80.51%  |
| No        | 54        | 19.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Israel  | 273       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Tel Aviv              | 131       | 44.56%  |
| Ramat Gan             | 28        | 9.52%   |
| Jerusalem             | 12        | 4.08%   |
| Petaẖ Tiqwa         | 11        | 3.74%   |
| Rishon LeZiyyon       | 9         | 3.06%   |
| Herzliya              | 9         | 3.06%   |
| Haifa                 | 8         | 2.72%   |
| Givatayim             | 8         | 2.72%   |
| Netanya               | 7         | 2.38%   |
| Rehovot               | 5         | 1.7%    |
| Ramat HaSharon        | 5         | 1.7%    |
| Nahariya              | 5         | 1.7%    |
| Holon                 | 5         | 1.7%    |
| Kiryat Ono            | 4         | 1.36%   |
| Ashquelon             | 4         | 1.36%   |
| Raanana               | 3         | 1.02%   |
| Givat Shmuel          | 3         | 1.02%   |
| Bet Shemesh           | 3         | 1.02%   |
| Yavne                 | 2         | 0.68%   |
| Rishon LeTsiyyon      | 2         | 0.68%   |
| Kfar Saba             | 2         | 0.68%   |
| Hadera                | 2         | 0.68%   |
| Beersheba             | 2         | 0.68%   |
| Yehud                 | 1         | 0.34%   |
| Tiberias              | 1         | 0.34%   |
| Shelomi               | 1         | 0.34%   |
| Sha`ar Ha`Amaqim      | 1         | 0.34%   |
| Sde Nehemya           | 1         | 0.34%   |
| Ramla                 | 1         | 0.34%   |
| Qiryat Moẕqin       | 1         | 0.34%   |
| Qiryat Bialik         | 1         | 0.34%   |
| Pardes Hanna Karkur   | 1         | 0.34%   |
| Ofakim                | 1         | 0.34%   |
| Ness Ziona            | 1         | 0.34%   |
| Modiin Makkabbim Reut | 1         | 0.34%   |
| Mazkeret Batya        | 1         | 0.34%   |
| Lod                   | 1         | 0.34%   |
| Kinneret              | 1         | 0.34%   |
| Kfar Yona             | 1         | 0.34%   |
| Karmi’el            | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 65     | 16.61%  |
| WDC                 | 36        | 37     | 11.73%  |
| Seagate             | 31        | 38     | 10.1%   |
| SK hynix            | 27        | 38     | 8.79%   |
| SanDisk             | 26        | 31     | 8.47%   |
| Toshiba             | 25        | 27     | 8.14%   |
| Intel               | 18        | 21     | 5.86%   |
| Kingston            | 15        | 16     | 4.89%   |
| Micron Technology   | 14        | 17     | 4.56%   |
| HGST                | 13        | 14     | 4.23%   |
| Hitachi             | 8         | 8      | 2.61%   |
| Unknown             | 7         | 7      | 2.28%   |
| Crucial             | 6         | 14     | 1.95%   |
| KIOXIA              | 5         | 5      | 1.63%   |
| Transcend           | 3         | 4      | 0.98%   |
| StoreJet            | 3         | 3      | 0.98%   |
| Fujitsu             | 3         | 3      | 0.98%   |
| A-DATA Technology   | 3         | 4      | 0.98%   |
| LITEON              | 2         | 2      | 0.65%   |
| JMicron Technology  | 2         | 2      | 0.65%   |
| China               | 2         | 3      | 0.65%   |
| Apple               | 2         | 2      | 0.65%   |
| Apacer              | 2         | 2      | 0.65%   |
| Lexar               | 1         | 1      | 0.33%   |
| faspeed             | 1         | 2      | 0.33%   |
| ADATA Technology    | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                        | 9         | 2.87%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 2.23%   |
| SK hynix NVMe SSD Drive 256GB                       | 5         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.59%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 1.27%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.27%   |
| Intel NVMe SSD Drive 512GB                          | 4         | 1.27%   |
| Toshiba NVMe SSD Drive 512GB                        | 3         | 0.96%   |
| SK hynix PC401 NVMe 512GB                           | 3         | 0.96%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.96%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.96%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.96%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 3         | 0.96%   |
| Intel NVMe SSD Drive 256GB                          | 3         | 0.96%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.96%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.96%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.96%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 2         | 0.64%   |
| WDC WD5000BPKT-75PK4T0 500GB                        | 2         | 0.64%   |
| WDC PC SN730 NVMe 512GB                             | 2         | 0.64%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 2         | 0.64%   |
| WDC PC SN530 NVMe 256GB                             | 2         | 0.64%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.64%   |
| Toshiba KXG6AZNV1T02 1TB                            | 2         | 0.64%   |
| StoreJet Transcend 240GB                            | 2         | 0.64%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.64%   |
| SanDisk SSD PLUS 240GB                              | 2         | 0.64%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 2         | 0.64%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.64%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.64%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.64%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 2         | 0.64%   |
| Micron MTFDHBA256TCK-1AS1AABHA  256GB               | 2         | 0.64%   |
| Micron 1300 SATA 256GB SSD                          | 2         | 0.64%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 2         | 0.64%   |
| LITEON CV1-8B512 512GB SSD                          | 2         | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 38     | 34.44%  |
| WDC                 | 18        | 18     | 20%     |
| Toshiba             | 15        | 15     | 16.67%  |
| HGST                | 13        | 14     | 14.44%  |
| Hitachi             | 8         | 8      | 8.89%   |
| Fujitsu             | 3         | 3      | 3.33%   |
| Unknown             | 1         | 1      | 1.11%   |
| Samsung Electronics | 1         | 1      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 17     | 18.68%  |
| SanDisk             | 15        | 19     | 16.48%  |
| Kingston            | 12        | 13     | 13.19%  |
| SK hynix            | 9         | 19     | 9.89%   |
| Micron Technology   | 7         | 7      | 7.69%   |
| Crucial             | 6         | 14     | 6.59%   |
| WDC                 | 3         | 3      | 3.3%    |
| Transcend           | 3         | 4      | 3.3%    |
| A-DATA Technology   | 3         | 4      | 3.3%    |
| Toshiba             | 2         | 2      | 2.2%    |
| StoreJet            | 2         | 2      | 2.2%    |
| LITEON              | 2         | 2      | 2.2%    |
| JMicron Technology  | 2         | 2      | 2.2%    |
| Intel               | 2         | 2      | 2.2%    |
| China               | 2         | 3      | 2.2%    |
| Apple               | 2         | 2      | 2.2%    |
| Apacer              | 2         | 2      | 2.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 118       | 144    | 39.6%   |
| SSD     | 87        | 117    | 29.19%  |
| HDD     | 86        | 98     | 28.86%  |
| MMC     | 5         | 5      | 1.68%   |
| Unknown | 2         | 3      | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 160       | 207    | 54.42%  |
| NVMe | 118       | 144    | 40.14%  |
| SAS  | 11        | 11     | 3.74%   |
| MMC  | 5         | 5      | 1.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 119       | 148    | 68.79%  |
| 0.51-1.0   | 49        | 62     | 28.32%  |
| 1.01-2.0   | 4         | 4      | 2.31%   |
| 3.01-4.0   | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 32.97%  |
| 251-500        | 80        | 28.67%  |
| 501-1000       | 41        | 14.7%   |
| 51-100         | 19        | 6.81%   |
| 1-20           | 15        | 5.38%   |
| Unknown        | 9         | 3.23%   |
| 21-50          | 8         | 2.87%   |
| 1001-2000      | 8         | 2.87%   |
| 2001-3000      | 5         | 1.79%   |
| More than 3000 | 2         | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 104       | 35.86%  |
| 21-50     | 63        | 21.72%  |
| 101-250   | 46        | 15.86%  |
| 51-100    | 41        | 14.14%  |
| 251-500   | 20        | 6.9%    |
| Unknown   | 9         | 3.1%    |
| 501-1000  | 4         | 1.38%   |
| 1001-2000 | 3         | 1.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB            | 2         | 2      | 8.7%    |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 4.35%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 4.35%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 4.35%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 4.35%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 4.35%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 4.35%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 4.35%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 4.35%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 4.35%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 4.35%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4.35%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 2      | 4.35%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 4.35%   |
| Intel SSDSCKKF256H6 SATA 256GB        | 1         | 1      | 4.35%   |
| Hitachi HTS545025B9A300 250GB         | 1         | 1      | 4.35%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 4.35%   |
| HGST HCC545050A7E380 500GB            | 1         | 1      | 4.35%   |
| Fujitsu MHY2160BH 160GB               | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 5         | 5      | 22.73%  |
| Seagate  | 4         | 6      | 18.18%  |
| WDC      | 3         | 3      | 13.64%  |
| HGST     | 3         | 3      | 13.64%  |
| SK hynix | 2         | 6      | 9.09%   |
| Hitachi  | 2         | 2      | 9.09%   |
| SanDisk  | 1         | 1      | 4.55%   |
| Intel    | 1         | 1      | 4.55%   |
| Fujitsu  | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 27.78%  |
| Seagate | 4         | 6      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| HGST    | 3         | 3      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 20     | 78.95%  |
| SSD  | 4         | 8      | 21.05%  |

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
| Detected | 160       | 206    | 55.75%  |
| Works    | 108       | 133    | 37.63%  |
| Malfunc  | 19        | 28     | 6.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 212       | 64.83%  |
| Samsung Electronics          | 34        | 10.4%   |
| SanDisk                      | 25        | 7.65%   |
| SK hynix                     | 18        | 5.5%    |
| Toshiba America Info Systems | 9         | 2.75%   |
| AMD                          | 9         | 2.75%   |
| Micron Technology            | 7         | 2.14%   |
| KIOXIA                       | 5         | 1.53%   |
| Kingston Technology Company  | 3         | 0.92%   |
| VIA Technologies             | 1         | 0.31%   |
| Union Memory (Shenzhen)      | 1         | 0.31%   |
| Shenzhen Longsys Electronics | 1         | 0.31%   |
| Nvidia                       | 1         | 0.31%   |
| ADATA Technology             | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 40        | 11.46%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 5.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 5.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 4.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 4.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 3.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 2.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.58%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 2.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 2.29%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 8         | 2.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 2.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 2.29%   |
| Micron Non-Volatile memory controller                                          | 7         | 2.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 2.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.72%   |
| Intel SSD 660P Series                                                          | 6         | 1.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.43%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 5         | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.43%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 1.15%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.15%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.15%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.15%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.15%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 0.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.86%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.86%   |
| Intel Non-Volatile memory controller                                           | 3         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 184       | 53.49%  |
| NVMe | 118       | 34.3%   |
| RAID | 29        | 8.43%   |
| IDE  | 13        | 3.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 257       | 94.14%  |
| AMD          | 15        | 5.49%   |
| CentaurHauls | 1         | 0.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 17        | 6.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 9         | 3.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 7         | 2.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 2.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 7         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 2.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 6         | 2.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 2.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 2.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 5         | 1.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 1.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 1.83%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 1.47%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 1.47%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 1.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.47%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 4         | 1.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.1%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 1.1%    |
| Intel Atom CPU N455 @ 1.66GHz               | 3         | 1.1%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 1.1%    |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 0.73%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 2         | 0.73%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 0.73%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.73%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.73%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 2         | 0.73%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.73%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.73%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 0.73%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 2         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 95        | 34.8%   |
| Intel Core i5           | 71        | 26.01%  |
| Other                   | 29        | 10.62%  |
| Intel Core i3           | 23        | 8.42%   |
| Intel Core 2 Duo        | 9         | 3.3%    |
| Intel Celeron           | 6         | 2.2%    |
| Intel Pentium Dual-Core | 5         | 1.83%   |
| Intel Core i9           | 4         | 1.47%   |
| Intel Pentium Dual      | 3         | 1.1%    |
| Intel Pentium           | 3         | 1.1%    |
| Intel Atom              | 3         | 1.1%    |
| AMD Ryzen 9             | 3         | 1.1%    |
| AMD Ryzen 7             | 3         | 1.1%    |
| AMD Ryzen 5             | 3         | 1.1%    |
| Intel Genuine           | 2         | 0.73%   |
| AMD A6                  | 2         | 0.73%   |
| Intel Xeon              | 1         | 0.37%   |
| Intel Core M            | 1         | 0.37%   |
| Intel Core 2            | 1         | 0.37%   |
| Intel Celeron Dual-Core | 1         | 0.37%   |
| CentaurHauls VIA C7     | 1         | 0.37%   |
| AMD Turion 64 X2 Mobile | 1         | 0.37%   |
| AMD Ryzen 7 PRO         | 1         | 0.37%   |
| AMD A8                  | 1         | 0.37%   |
| AMD A10                 | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 115       | 42.12%  |
| 2       | 115       | 42.12%  |
| 6       | 19        | 6.96%   |
| 8       | 14        | 5.13%   |
| 1       | 6         | 2.2%    |
| 14      | 3         | 1.1%    |
| Unknown | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 272       | 99.63%  |
| Unknown | 1         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 235       | 85.77%  |
| 1       | 38        | 13.87%  |
| Unknown | 1         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 266       | 97.44%  |
| Unknown        | 6         | 2.2%    |
| 32-bit         | 1         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 22.89%  |
| 0x806ea    | 22        | 7.75%   |
| 0x806ec    | 17        | 5.99%   |
| 0x806c1    | 17        | 5.99%   |
| 0x406e3    | 14        | 4.93%   |
| 0x206a7    | 13        | 4.58%   |
| 0x306a9    | 11        | 3.87%   |
| 0x706e5    | 10        | 3.52%   |
| 0x306d4    | 10        | 3.52%   |
| 0x806e9    | 9         | 3.17%   |
| 0x20655    | 8         | 2.82%   |
| 0xa0652    | 7         | 2.46%   |
| 0x906ea    | 7         | 2.46%   |
| 0x506e3    | 7         | 2.46%   |
| 0x1067a    | 7         | 2.46%   |
| 0x806eb    | 6         | 2.11%   |
| 0x906ed    | 5         | 1.76%   |
| 0x6fd      | 5         | 1.76%   |
| 0x40651    | 5         | 1.76%   |
| 0x306c3    | 5         | 1.76%   |
| 0x806d1    | 3         | 1.06%   |
| 0x106ca    | 3         | 1.06%   |
| 0x906e9    | 2         | 0.7%    |
| 0x906a3    | 2         | 0.7%    |
| 0x706a1    | 2         | 0.7%    |
| 0x6fa      | 2         | 0.7%    |
| 0x10676    | 2         | 0.7%    |
| 0x0a50000c | 2         | 0.7%    |
| 0x08600104 | 2         | 0.7%    |
| 0x08108109 | 2         | 0.7%    |
| 0x08108102 | 2         | 0.7%    |
| 0xa0660    | 1         | 0.35%   |
| 0x806c2    | 1         | 0.35%   |
| 0x6f6      | 1         | 0.35%   |
| 0x6f4      | 1         | 0.35%   |
| 0x506c9    | 1         | 0.35%   |
| 0x106e5    | 1         | 0.35%   |
| 0x0a404101 | 1         | 0.35%   |
| 0x08600106 | 1         | 0.35%   |
| 0x07030106 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 87        | 31.87%  |
| Skylake          | 24        | 8.79%   |
| TigerLake        | 23        | 8.42%   |
| SandyBridge      | 16        | 5.86%   |
| IvyBridge        | 15        | 5.49%   |
| IceLake          | 14        | 5.13%   |
| Haswell          | 14        | 5.13%   |
| Penryn           | 13        | 4.76%   |
| Broadwell        | 12        | 4.4%    |
| Westmere         | 10        | 3.66%   |
| Core             | 9         | 3.3%    |
| CometLake        | 9         | 3.3%    |
| Zen+             | 4         | 1.47%   |
| Unknown          | 4         | 1.47%   |
| Zen 2            | 3         | 1.1%    |
| Zen 3            | 2         | 0.73%   |
| Puma             | 2         | 0.73%   |
| Piledriver       | 2         | 0.73%   |
| Goldmont plus    | 2         | 0.73%   |
| Bonnell          | 2         | 0.73%   |
| Alderlake Hybrid | 2         | 0.73%   |
| Silvermont       | 1         | 0.37%   |
| Nehalem          | 1         | 0.37%   |
| K8 Hammer        | 1         | 0.37%   |
| Goldmont         | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 248       | 69.66%  |
| Nvidia           | 83        | 23.31%  |
| AMD              | 24        | 6.74%   |
| VIA Technologies | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 29        | 7.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 20        | 5.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 19        | 5.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 14        | 3.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 14        | 3.86%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 14        | 3.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 14        | 3.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 13        | 3.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 11        | 3.03%   |
| Intel HD Graphics 620                                                     | 10        | 2.75%   |
| Intel HD Graphics 5500                                                    | 10        | 2.75%   |
| Intel Core Processor Integrated Graphics Controller                       | 10        | 2.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 8         | 2.2%    |
| Nvidia GP108M [GeForce MX150]                                             | 7         | 1.93%   |
| Intel HD Graphics 530                                                     | 7         | 1.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 1.93%   |
| Intel Iris Plus Graphics G7                                               | 6         | 1.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 6         | 1.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 5         | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 5         | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 4         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 4         | 1.1%    |
| Nvidia GM107M [GeForce GTX 960M]                                          | 4         | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 1.1%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 3         | 0.83%   |
| Nvidia GP108M [GeForce MX230]                                             | 3         | 0.83%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 3         | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 0.83%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 0.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 3         | 0.83%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 0.83%   |
| AMD Renoir                                                                | 3         | 0.83%   |
| Nvidia TU117M [GeForce MX450]                                             | 2         | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX330]                                             | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.55%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 170       | 62.27%  |
| Intel + Nvidia | 69        | 25.27%  |
| 1 x AMD        | 10        | 3.66%   |
| 1 x Nvidia     | 8         | 2.93%   |
| Intel + AMD    | 8         | 2.93%   |
| AMD + Nvidia   | 5         | 1.83%   |
| 2 x Intel      | 1         | 0.37%   |
| 2 x AMD        | 1         | 0.37%   |
| 1 x VIA        | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 230       | 83.33%  |
| Proprietary | 40        | 14.49%  |
| Unknown     | 6         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 200       | 72.2%   |
| 1.01-2.0   | 24        | 8.66%   |
| 3.01-4.0   | 23        | 8.3%    |
| 0.01-0.5   | 13        | 4.69%   |
| 5.01-6.0   | 6         | 2.17%   |
| 0.51-1.0   | 6         | 2.17%   |
| 7.01-8.0   | 4         | 1.44%   |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 67        | 19.94%  |
| Chimei Innolux          | 46        | 13.69%  |
| LG Display              | 45        | 13.39%  |
| BOE                     | 39        | 11.61%  |
| Dell                    | 29        | 8.63%   |
| Samsung Electronics     | 28        | 8.33%   |
| Lenovo                  | 14        | 4.17%   |
| Sharp                   | 10        | 2.98%   |
| Goldstar                | 9         | 2.68%   |
| InfoVision              | 7         | 2.08%   |
| Hewlett-Packard         | 6         | 1.79%   |
| Chi Mei Optoelectronics | 6         | 1.79%   |
| LG Philips              | 5         | 1.49%   |
| Philips                 | 4         | 1.19%   |
| Apple                   | 4         | 1.19%   |
| Toshiba                 | 2         | 0.6%    |
| CSO                     | 2         | 0.6%    |
| VOR                     | 1         | 0.3%    |
| STD                     | 1         | 0.3%    |
| Seiko/Epson             | 1         | 0.3%    |
| RIS                     | 1         | 0.3%    |
| PANDA                   | 1         | 0.3%    |
| Panasonic               | 1         | 0.3%    |
| LGD                     | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| BOE Technology Group    | 1         | 0.3%    |
| ASUSTek Computer        | 1         | 0.3%    |
| AOC                     | 1         | 0.3%    |
| Ancor Communications    | 1         | 0.3%    |
| Acer                    | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 1.75%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 6         | 1.75%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 1.17%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 4         | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.17%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.87%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 3         | 0.87%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch           | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch           | 3         | 0.87%   |
| Toshiba LCD Monitor LCD2207 1280x800 287x180mm 13.3-inch                 | 2         | 0.58%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.58%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch       | 2         | 0.58%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 2         | 0.58%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.58%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.58%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch              | 2         | 0.58%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                     | 2         | 0.58%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                        | 2         | 0.58%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                        | 2         | 0.58%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                        | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.58%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE0846 1920x1080 294x165mm 13.3-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE07BC 1920x1080 309x173mm 13.9-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.58%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 155       | 51.32%  |
| 1366x768 (WXGA)    | 67        | 22.19%  |
| 3840x2160 (4K)     | 22        | 7.28%   |
| 2560x1440 (QHD)    | 12        | 3.97%   |
| 1280x800 (WXGA)    | 12        | 3.97%   |
| 1920x1200 (WUXGA)  | 7         | 2.32%   |
| 1600x900 (HD+)     | 5         | 1.66%   |
| 3440x1440          | 3         | 0.99%   |
| 1440x900 (WXGA+)   | 3         | 0.99%   |
| 3200x1800 (QHD+)   | 2         | 0.66%   |
| 1680x1050 (WSXGA+) | 2         | 0.66%   |
| 1024x768 (XGA)     | 2         | 0.66%   |
| 3840x1080          | 1         | 0.33%   |
| 3456x2160          | 1         | 0.33%   |
| 2880x1800          | 1         | 0.33%   |
| 2560x1600          | 1         | 0.33%   |
| 2560x1080          | 1         | 0.33%   |
| 2160x1440          | 1         | 0.33%   |
| 1280x768           | 1         | 0.33%   |
| 1280x1024 (SXGA)   | 1         | 0.33%   |
| 1024x600           | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 129       | 38.39%  |
| 13      | 65        | 19.35%  |
| 14      | 43        | 12.8%   |
| 24      | 23        | 6.85%   |
| 27      | 19        | 5.65%   |
| 23      | 11        | 3.27%   |
| 17      | 9         | 2.68%   |
| 21      | 8         | 2.38%   |
| 12      | 7         | 2.08%   |
| 34      | 3         | 0.89%   |
| 31      | 3         | 0.89%   |
| 11      | 3         | 0.89%   |
| Unknown | 3         | 0.89%   |
| 22      | 2         | 0.6%    |
| 19      | 2         | 0.6%    |
| 84      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 25      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 10      | 1         | 0.3%    |
| 8       | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 201       | 60.91%  |
| 501-600     | 46        | 13.94%  |
| 201-300     | 46        | 13.94%  |
| 351-400     | 13        | 3.94%   |
| 401-500     | 10        | 3.03%   |
| 601-700     | 5         | 1.52%   |
| 701-800     | 3         | 0.91%   |
| Unknown     | 3         | 0.91%   |
| 801-900     | 1         | 0.3%    |
| 1501-2000   | 1         | 0.3%    |
| 101-200     | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 239       | 85.66%  |
| 16/10   | 28        | 10.04%  |
| 21/9    | 3         | 1.08%   |
| Unknown | 3         | 1.08%   |
| 5/4     | 2         | 0.72%   |
| 4/3     | 2         | 0.72%   |
| 3/2     | 2         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 129       | 38.62%  |
| 81-90          | 76        | 22.75%  |
| 201-250        | 37        | 11.08%  |
| 71-80          | 31        | 9.28%   |
| 301-350        | 19        | 5.69%   |
| 61-70          | 7         | 2.1%    |
| 121-130        | 7         | 2.1%    |
| 351-500        | 6         | 1.8%    |
| 251-300        | 5         | 1.5%    |
| 51-60          | 3         | 0.9%    |
| 151-200        | 3         | 0.9%    |
| Unknown        | 3         | 0.9%    |
| 131-140        | 2         | 0.6%    |
| More than 1000 | 1         | 0.3%    |
| 41-50          | 1         | 0.3%    |
| 1-40           | 1         | 0.3%    |
| 111-120        | 1         | 0.3%    |
| 501-1000       | 1         | 0.3%    |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 41.59%  |
| 101-120       | 84        | 25.69%  |
| 51-100        | 60        | 18.35%  |
| 161-240       | 25        | 7.65%   |
| More than 240 | 19        | 5.81%   |
| Unknown       | 3         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 205       | 74.01%  |
| 2     | 55        | 19.86%  |
| 3     | 11        | 3.97%   |
| 0     | 5         | 1.81%   |
| 4     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 166       | 37.99%  |
| Realtek Semiconductor           | 140       | 32.04%  |
| Qualcomm Atheros                | 54        | 12.36%  |
| Broadcom                        | 20        | 4.58%   |
| Lenovo                          | 10        | 2.29%   |
| Broadcom Limited                | 9         | 2.06%   |
| MediaTek                        | 5         | 1.14%   |
| DisplayLink                     | 4         | 0.92%   |
| Marvell Technology Group        | 3         | 0.69%   |
| Xiaomi                          | 2         | 0.46%   |
| Samsung Electronics             | 2         | 0.46%   |
| Qualcomm Atheros Communications | 2         | 0.46%   |
| Edimax Technology               | 2         | 0.46%   |
| ASIX Electronics                | 2         | 0.46%   |
| U-Blox                          | 1         | 0.23%   |
| Toshiba                         | 1         | 0.23%   |
| Ralink Technology               | 1         | 0.23%   |
| PEAK-System Technik             | 1         | 0.23%   |
| Nvidia                          | 1         | 0.23%   |
| Nokia Mobile Phones             | 1         | 0.23%   |
| Linksys                         | 1         | 0.23%   |
| LG Electronics                  | 1         | 0.23%   |
| Huawei Technologies             | 1         | 0.23%   |
| HMD Global                      | 1         | 0.23%   |
| Hewlett-Packard                 | 1         | 0.23%   |
| Google                          | 1         | 0.23%   |
| Dell                            | 1         | 0.23%   |
| Comneon                         | 1         | 0.23%   |
| Attansic Technology             | 1         | 0.23%   |
| ASUSTek Computer                | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 85        | 16.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 30        | 5.66%   |
| Intel Wireless 8265 / 8275                                              | 20        | 3.77%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.89%   |
| Intel Wireless 8260                                                     | 10        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.7%    |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.51%   |
| Intel Wireless 3165                                                     | 8         | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 1.51%   |
| Intel Wireless 3160                                                     | 7         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.13%   |
| Intel Wireless 7265                                                     | 6         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.94%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 0.94%   |
| Intel Ethernet Connection (13) I219-V                                   | 5         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.75%   |
| Lenovo USB-C Dock Ethernet                                              | 4         | 0.75%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 4         | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                   | 4         | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 56.68%  |
| Qualcomm Atheros                | 50        | 18.05%  |
| Realtek Semiconductor           | 31        | 11.19%  |
| Broadcom                        | 20        | 7.22%   |
| Broadcom Limited                | 7         | 2.53%   |
| MediaTek                        | 5         | 1.81%   |
| Qualcomm Atheros Communications | 2         | 0.72%   |
| Edimax Technology               | 2         | 0.72%   |
| Ralink Technology               | 1         | 0.36%   |
| Dell                            | 1         | 0.36%   |
| ASUSTek Computer                | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 20        | 7.17%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 6.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 3.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 3.94%   |
| Intel Wireless 8260                                                     | 10        | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 2.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.87%   |
| Intel Wireless 3165                                                     | 8         | 2.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 2.87%   |
| Intel Wireless 3160                                                     | 7         | 2.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.15%   |
| Intel Wireless 7265                                                     | 6         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.43%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.72%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.72%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.72%   |
| Intel Wireless 7260                                                     | 2         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 131       | 54.36%  |
| Intel                    | 64        | 26.56%  |
| Qualcomm Atheros         | 10        | 4.15%   |
| Lenovo                   | 10        | 4.15%   |
| Broadcom                 | 5         | 2.07%   |
| DisplayLink              | 4         | 1.66%   |
| Marvell Technology Group | 3         | 1.24%   |
| Broadcom Limited         | 3         | 1.24%   |
| Xiaomi                   | 2         | 0.83%   |
| Samsung Electronics      | 2         | 0.83%   |
| ASIX Electronics         | 2         | 0.83%   |
| Nvidia                   | 1         | 0.41%   |
| Linksys                  | 1         | 0.41%   |
| HMD Global               | 1         | 0.41%   |
| Google                   | 1         | 0.41%   |
| Attansic Technology      | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85        | 34.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 12.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.7%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.06%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 2.06%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 1.65%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 1.65%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.65%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.82%   |
| DisplayLink USB3.0 Dual Video Dock                                | 2         | 0.82%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.41%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 268       | 54.14%  |
| Ethernet | 219       | 44.24%  |
| Modem    | 7         | 1.41%   |
| Unknown  | 1         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 215       | 74.65%  |
| Ethernet | 72        | 25%     |
| Modem    | 1         | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 198       | 72.26%  |
| 1     | 73        | 26.64%  |
| 3     | 3         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 235       | 85.14%  |
| Yes  | 41        | 14.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 136       | 60.44%  |
| Realtek Semiconductor           | 18        | 8%      |
| Qualcomm Atheros Communications | 18        | 8%      |
| IMC Networks                    | 14        | 6.22%   |
| Broadcom                        | 9         | 4%      |
| Foxconn / Hon Hai               | 6         | 2.67%   |
| Lite-On Technology              | 5         | 2.22%   |
| Dell                            | 4         | 1.78%   |
| Apple                           | 4         | 1.78%   |
| Hewlett-Packard                 | 2         | 0.89%   |
| Cambridge Silicon Radio         | 2         | 0.89%   |
| Askey Computer                  | 2         | 0.89%   |
| Toshiba                         | 1         | 0.44%   |
| Realtek                         | 1         | 0.44%   |
| MediaTek                        | 1         | 0.44%   |
| ASUSTek Computer                | 1         | 0.44%   |
| Actions                         | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 56        | 24.89%  |
| Intel AX201 Bluetooth                               | 37        | 16.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 8.44%   |
| Realtek Bluetooth Radio                             | 11        | 4.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 4%      |
| Intel AX200 Bluetooth                               | 8         | 3.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 3.11%   |
| Lite-On Bluetooth Device                            | 4         | 1.78%   |
| Intel AX210 Bluetooth                               | 4         | 1.78%   |
| IMC Networks Bluetooth Device                       | 4         | 1.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.33%   |
| Intel Bluetooth Device                              | 3         | 1.33%   |
| IMC Networks Wireless_Device                        | 3         | 1.33%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.89%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.89%   |
| Foxconn / Hon Hai BT                                | 2         | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.89%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.89%   |
| Askey Bluetooth Device                              | 2         | 0.89%   |
| Apple Bluetooth Host Controller                     | 2         | 0.89%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.44%   |
| Realtek Bluetooth Radio                             | 1         | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.44%   |
| MediaTek BT                                         | 1         | 0.44%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.44%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 257       | 76.72%  |
| Nvidia                     | 34        | 10.15%  |
| AMD                        | 15        | 4.48%   |
| Lenovo                     | 10        | 2.99%   |
| Realtek Semiconductor      | 4         | 1.19%   |
| Microsoft                  | 2         | 0.6%    |
| GN Netcom                  | 2         | 0.6%    |
| XMOS                       | 1         | 0.3%    |
| VIA Technologies           | 1         | 0.3%    |
| Texas Instruments          | 1         | 0.3%    |
| Sennheiser Communications  | 1         | 0.3%    |
| Razer USA                  | 1         | 0.3%    |
| PreSonus Audio Electronics | 1         | 0.3%    |
| Plantronics                | 1         | 0.3%    |
| Logitech                   | 1         | 0.3%    |
| FIFINE Microphones         | 1         | 0.3%    |
| Creative Technology        | 1         | 0.3%    |
| C-Media Electronics        | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 55        | 14.71%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 6.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 5.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 4.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 15        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 3.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 3.21%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 3.21%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 3.21%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.14%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 2.14%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.34%   |
| Realtek Semiconductor USB Audio                                            | 4         | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.07%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 4         | 1.07%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 4         | 1.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.07%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 3         | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.8%    |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.53%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.53%   |
| Microsoft LifeChat LX-3000 Headset                                         | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 28.57%  |
| SK hynix            | 43        | 22.75%  |
| Micron Technology   | 35        | 18.52%  |
| Kingston            | 14        | 7.41%   |
| Unknown             | 11        | 5.82%   |
| Crucial             | 9         | 4.76%   |
| Ramaxel Technology  | 5         | 2.65%   |
| G.Skill             | 4         | 2.12%   |
| Nanya Technology    | 3         | 1.59%   |
| Elpida              | 3         | 1.59%   |
| Transcend           | 2         | 1.06%   |
| V-Color             | 1         | 0.53%   |
| Corsair             | 1         | 0.53%   |
| Avant               | 1         | 0.53%   |
| ASint Technology    | 1         | 0.53%   |
| A-DATA Technology   | 1         | 0.53%   |
| 48spaces            | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 2.06%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 2.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 1.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 1.55%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 3         | 1.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 1.55%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 1.55%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.55%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s           | 3         | 1.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 3         | 1.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 2         | 1.03%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 2         | 1.03%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 2         | 1.03%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s             | 2         | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.03%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.03%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 2         | 1.03%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 1.03%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 1.03%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 1.03%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 1.03%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 1.03%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM DDR3 1067MT/s     | 2         | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 1.03%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 2         | 1.03%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.03%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 2         | 1.03%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s     | 2         | 1.03%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.03%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 1.03%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 2         | 1.03%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s      | 2         | 1.03%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 2         | 1.03%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s  | 2         | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 1.03%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s       | 2         | 1.03%   |
| Kingston RAM 9905711-035.A00G 8GB SODIMM DDR4 3200MT/s       | 2         | 1.03%   |
| Elpida RAM SNY1333D3S9ELC/4G 4GB SODIMM DDR 1333MT/s         | 2         | 1.03%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s      | 2         | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 56.86%  |
| DDR3    | 37        | 24.18%  |
| LPDDR3  | 10        | 6.54%   |
| DDR2    | 9         | 5.88%   |
| DDR5    | 3         | 1.96%   |
| DDR     | 3         | 1.96%   |
| LPDDR4  | 2         | 1.31%   |
| LPDDR5  | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 135       | 88.24%  |
| Row Of Chips | 16        | 10.46%  |
| DIMM         | 1         | 0.65%   |
| Chip         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 58        | 34.73%  |
| 4096  | 38        | 22.75%  |
| 16384 | 37        | 22.16%  |
| 2048  | 19        | 11.38%  |
| 1024  | 8         | 4.79%   |
| 32768 | 7         | 4.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 46        | 27.88%  |
| 3200    | 28        | 16.97%  |
| 1600    | 26        | 15.76%  |
| 2133    | 15        | 9.09%   |
| 2400    | 13        | 7.88%   |
| 667     | 6         | 3.64%   |
| 1334    | 5         | 3.03%   |
| 1067    | 5         | 3.03%   |
| 4800    | 3         | 1.82%   |
| 1333    | 3         | 1.82%   |
| Unknown | 3         | 1.82%   |
| 4267    | 2         | 1.21%   |
| 3266    | 2         | 1.21%   |
| 1867    | 2         | 1.21%   |
| 800     | 2         | 1.21%   |
| 8400    | 1         | 0.61%   |
| 6400    | 1         | 0.61%   |
| 1066    | 1         | 0.61%   |
| 533     | 1         | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 50%     |
| Samsung M288x Series               | 1         | 50%     |

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
| IMC Networks                           | 47        | 18.15%  |
| Chicony Electronics                    | 42        | 16.22%  |
| Realtek Semiconductor                  | 41        | 15.83%  |
| Sunplus Innovation Technology          | 21        | 8.11%   |
| Acer                                   | 21        | 8.11%   |
| Microdia                               | 20        | 7.72%   |
| Lite-On Technology                     | 8         | 3.09%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.7%    |
| Apple                                  | 7         | 2.7%    |
| Suyin                                  | 6         | 2.32%   |
| Quanta                                 | 5         | 1.93%   |
| Logitech                               | 5         | 1.93%   |
| Syntek                                 | 4         | 1.54%   |
| Silicon Motion                         | 4         | 1.54%   |
| Microsoft                              | 4         | 1.54%   |
| Luxvisions Innotech Limited            | 2         | 0.77%   |
| Lenovo                                 | 2         | 0.77%   |
| Cubeternet                             | 2         | 0.77%   |
| ALi                                    | 2         | 0.77%   |
| Alcor Micro                            | 2         | 0.77%   |
| Z-Star Microelectronics                | 1         | 0.39%   |
| Samsung Electronics                    | 1         | 0.39%   |
| Primax Electronics                     | 1         | 0.39%   |
| Jieli Technology                       | 1         | 0.39%   |
| Generalplus Technology                 | 1         | 0.39%   |
| eMPIA Technology                       | 1         | 0.39%   |
| DJJHFA1BIF5595                         | 1         | 0.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 23        | 8.85%   |
| Chicony Integrated Camera                     | 15        | 5.77%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 13        | 5%      |
| IMC Networks USB2.0 HD UVC WebCam             | 12        | 4.62%   |
| IMC Networks Integrated Camera                | 12        | 4.62%   |
| Microdia Integrated_Webcam_HD                 | 10        | 3.85%   |
| Acer Integrated Camera                        | 6         | 2.31%   |
| Sunplus Integrated_Webcam_HD                  | 4         | 1.54%   |
| Lite-On HP HD Camera                          | 4         | 1.54%   |
| Chicony HP HD Camera                          | 4         | 1.54%   |
| Apple iPhone5/5C/5S/6                         | 4         | 1.54%   |
| Acer SunplusIT Integrated Camera              | 4         | 1.54%   |
| Acer Lenovo EasyCamera                        | 4         | 1.54%   |
| Syntek Integrated Camera                      | 3         | 1.15%   |
| Sunplus SPCA2650 AV Camera                    | 3         | 1.15%   |
| Realtek Lenovo EasyCamera                     | 3         | 1.15%   |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 1.15%   |
| Chicony Lenovo EasyCamera                     | 3         | 1.15%   |
| Chicony Integrated Camera (1280x720@30)       | 3         | 1.15%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 2         | 0.77%   |
| Sunplus ASUS Webcam                           | 2         | 0.77%   |
| Realtek USB2.0 HD UVC WebCam                  | 2         | 0.77%   |
| Realtek USB Camera                            | 2         | 0.77%   |
| Realtek HP Wide Vision HD Camera              | 2         | 0.77%   |
| Quanta USB Webcam                             | 2         | 0.77%   |
| Quanta HP TrueVision HD Camera                | 2         | 0.77%   |
| Microsoft LifeCam NX-6000                     | 2         | 0.77%   |
| Microdia Integrated Webcam                    | 2         | 0.77%   |
| Microdia Dell Integrated HD Webcam            | 2         | 0.77%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.77%   |
| Lite-On Integrated Camera                     | 2         | 0.77%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 2         | 0.77%   |
| IMC Networks Lenovo EasyCamera                | 2         | 0.77%   |
| Cubeternet USB2.0 Camera                      | 2         | 0.77%   |
| Chicony HP Webcam                             | 2         | 0.77%   |
| Apple FaceTime HD Camera                      | 2         | 0.77%   |
| ALi Gateway Webcam                            | 2         | 0.77%   |
| Acer BisonCam, NB Pro                         | 2         | 0.77%   |
| Z-Star WebCam SC-03FFL11739P                  | 1         | 0.38%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 23        | 41.07%  |
| Validity Sensors           | 17        | 30.36%  |
| Shenzhen Goodix Technology | 7         | 12.5%   |
| Elan Microelectronics      | 3         | 5.36%   |
| STMicroelectronics         | 2         | 3.57%   |
| AuthenTec                  | 2         | 3.57%   |
| Upek                       | 1         | 1.79%   |
| LighTuning Technology      | 1         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 23.21%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 7.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.36%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.36%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 3.57%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.57%   |
| Unknown                                                                    | 2         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.79%   |
| Validity Sensors VFS491                                                    | 1         | 1.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.79%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.79%   |
| Synaptics  WBDI                                                            | 1         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.79%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 65.71%  |
| Alcor Micro | 12        | 34.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 34.29%  |
| Broadcom 58200                                                               | 8         | 22.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 20%     |
| Broadcom 5880                                                                | 6         | 17.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 5.71%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 160       | 56.74%  |
| 1     | 91        | 32.27%  |
| 2     | 25        | 8.87%   |
| 3     | 4         | 1.42%   |
| 7     | 1         | 0.35%   |
| 4     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 34.81%  |
| Chipcard                 | 32        | 20.25%  |
| Graphics card            | 30        | 18.99%  |
| Net/wireless             | 17        | 10.76%  |
| Camera                   | 6         | 3.8%    |
| Multimedia controller    | 5         | 3.16%   |
| Card reader              | 3         | 1.9%    |
| Storage                  | 2         | 1.27%   |
| Sound                    | 2         | 1.27%   |
| Bluetooth                | 2         | 1.27%   |
| Unassigned class         | 1         | 0.63%   |
| Network                  | 1         | 0.63%   |
| Net/ethernet             | 1         | 0.63%   |
| Communication controller | 1         | 0.63%   |


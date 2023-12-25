Linux in Ireland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 582

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| AVITA         | NS14A6                      | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Toshiba       | Satellite A660              | [d0415e05d3](https://linux-hardware.org/?probe=d0415e05d3) | Dec 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| Dell          | Latitude 5400               | [9ae128faf4](https://linux-hardware.org/?probe=9ae128faf4) | Dec 16, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| Samsung       | 750XED                      | [5263f7ebc0](https://linux-hardware.org/?probe=5263f7ebc0) | Dec 07, 2023 |
| Acer          | Swift SFG14-71              | [a84f25d406](https://linux-hardware.org/?probe=a84f25d406) | Dec 07, 2023 |
| Valve         | Jupiter                     | [6a95e96b1b](https://linux-hardware.org/?probe=6a95e96b1b) | Dec 02, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Valve         | Jupiter                     | [2c7d8106d0](https://linux-hardware.org/?probe=2c7d8106d0) | Nov 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0af175a9d7](https://linux-hardware.org/?probe=0af175a9d7) | Nov 19, 2023 |
| ASUSTek       | X540NA                      | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [a76432f7df](https://linux-hardware.org/?probe=a76432f7df) | Nov 16, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Alienware     | m18 R1                      | [f4c5c9d2ec](https://linux-hardware.org/?probe=f4c5c9d2ec) | Nov 13, 2023 |
| HP            | Pavilion m6                 | [60a4921f94](https://linux-hardware.org/?probe=60a4921f94) | Nov 13, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [5ad5316ab5](https://linux-hardware.org/?probe=5ad5316ab5) | Nov 11, 2023 |
| Acer          | Aspire 5750                 | [94186792b2](https://linux-hardware.org/?probe=94186792b2) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| System76      | Lemur Pro                   | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| System76      | Lemur Pro                   | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| Acer          | Aspire 5750                 | [3ba4126936](https://linux-hardware.org/?probe=3ba4126936) | Nov 04, 2023 |
| Packard Be... | EasyNote TE69KB             | [440d52f445](https://linux-hardware.org/?probe=440d52f445) | Nov 04, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Dell          | Latitude 5421               | [670d635ddc](https://linux-hardware.org/?probe=670d635ddc) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1a7844f56d](https://linux-hardware.org/?probe=1a7844f56d) | Oct 30, 2023 |
| Acer          | Swift SFG14-71              | [1a28398320](https://linux-hardware.org/?probe=1a28398320) | Oct 26, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | EliteBook 830 G6            | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| Dell          | Latitude E6430              | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| Dell          | Latitude 5580               | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | Latitude 5580               | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| Dell          | Latitude 5410               | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [86d39b72d6](https://linux-hardware.org/?probe=86d39b72d6) | Sep 29, 2023 |
| Dell          | Latitude 5410               | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Dell          | Latitude 7320               | [2549020a4e](https://linux-hardware.org/?probe=2549020a4e) | Sep 26, 2023 |
| MSI           | Katana GF76 12UG            | [ee50afcf85](https://linux-hardware.org/?probe=ee50afcf85) | Sep 18, 2023 |
| Dell          | Inspiron 5559               | [8bf4c79f98](https://linux-hardware.org/?probe=8bf4c79f98) | Sep 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| Dell          | Latitude E6400              | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| ASUSTek       | X540NA                      | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| ASUSTek       | K53SV                       | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Apple         | MacBookPro14,2              | [8b0d028b37](https://linux-hardware.org/?probe=8b0d028b37) | Aug 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [179beade50](https://linux-hardware.org/?probe=179beade50) | Aug 08, 2023 |
| Dell          | Precision M2800             | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| Acer          | Predator PH315-53           | [6c13f7a1f0](https://linux-hardware.org/?probe=6c13f7a1f0) | Aug 04, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [928fd8c7cb](https://linux-hardware.org/?probe=928fd8c7cb) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | [8e05eceeef](https://linux-hardware.org/?probe=8e05eceeef) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | [5457b19b2b](https://linux-hardware.org/?probe=5457b19b2b) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| HP            | Pavilion m6                 | [8566e9607f](https://linux-hardware.org/?probe=8566e9607f) | Jul 14, 2023 |
| Dell          | Inspiron 1545               | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [a72d009fab](https://linux-hardware.org/?probe=a72d009fab) | Jul 13, 2023 |
| Acer          | Aspire A515-56              | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Samsung       | 750XED                      | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Dell          | Latitude 3410               | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Apple         | MacBook6,1                  | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Lenovo        | V330-15IKB 81AX             | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | ZBook 15                    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | XPS 13 9380                 | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Dell          | XPS 13 9380                 | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Acer          | Nitro AN515-54              | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | Inspiron 7577               | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Dell          | Latitude 7420               | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Lenovo        | S21e-20 80M4                | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | Latitude 5400               | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| ASUSTek       | G752VM                      | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | Inspiron 13-5378            | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Timi          | A35S                        | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Acer          | Aspire F5-573G              | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Dell          | Latitude 7420               | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| Samsung       | 940XFG                      | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Google        | Reks                        | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Dell          | Latitude 7420               | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Dell          | Latitude 7420               | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude 7420               | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Valve         | Jupiter                     | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Dell          | Latitude E7240              | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Dell          | G15 5520                    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Valve         | Jupiter                     | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Dell          | Latitude 7420               | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Valve         | Jupiter                     | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Dell          | Latitude 7420               | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Samsung       | 940XFG                      | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| Dell          | Latitude 7420               | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Acer          | Aspire A514-55              | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Chuwi         | X312B                       | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | Latitude E6440              | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Dell          | Latitude 7400               | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Toshiba       | PORTEGE R830                | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Timi          | TM1709                      | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | Pavilion m6                 | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Jumper        | EZbook                      | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| HP            | EliteBook 840 G1            | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| Dell          | Latitude E6520              | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| Packard Be... | EasyNote TK85               | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Dell          | Latitude E5440              | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| Dell          | Latitude E6430              | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| PC Special... | NH5xAx                      | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Dell          | Latitude 9420               | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | XPS 13 9310                 | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Toshiba       | PORTEGE R830                | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291W99       | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Acer          | AOD255                      | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Dell          | Inspiron MM061              | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Dell          | XPS 13 9310                 | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Acer          | Nitro AN515-45              | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| Apple         | MacBookPro5,3               | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Sony          | VPCCB35FG                   | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Dell          | Studio XPS 1640             | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| Dell          | Latitude 7370               | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| Entroware     | Apollo                      | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| Dell          | XPS 13 9300                 | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | Inspiron 1764               | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| HP            | Pavilion 15                 | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 15                          | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Entroware     | Proteus                     | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| HP            | HDX 18                      | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| HP            | EliteBook Folio G1          | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| HP            | Pavilion g6                 | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Acer          | Aspire 5920G                | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | X540LA                      | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| HP            | Pavilion m6                 | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| HP            | EliteBook 745 G6            | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| HUAWEI        | BOHL-WXX9                   | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Samsung       | N150/N210/N220              | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| Dell          | System XPS L502X            | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| Acer          | Aspire 5551                 | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| Dell          | Latitude E6420              | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| Notebook      | NL40_50CU                   | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| System76      | Galago Pro                  | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Medion        | E6239 MD99452               | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| HP            | Laptop 14-bs0xx             | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Apple         | MacBook5,1                  | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| Toshiba       | Satellite L50-B             | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| HP            | Laptop 14-bs0xx             | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Acer          | Aspire 5349                 | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| Dell          | Latitude E7450              | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| MSI           | WS65 9TK                    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Dell          | Latitude 5480               | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 255 G2                      | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| Dell          | Inspiron 15-3552            | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| SLIMBOOK      | PROX15                      | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Dell          | Latitude E5420              | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Dell          | Vostro 5490                 | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| HP            | EliteBook 8560w             | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Dell          | Latitude E7240              | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | XPS M1530                   | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| Dell          | Latitude E5450              | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| HP            | Pavilion dv6                | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| Dell          | Inspiron 13-5378            | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | Precision M6300             | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| System76      | Galago Pro                  | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Alienware     | 17 R4                       | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Lenovo        | V145-15AST 81MT             | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Acer          | Aspire ES1-512              | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| Acer          | Aspire E1-572               | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| Advent        | Roma                        | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| System76      | Bonobo Extreme              | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| HP            | Pavilion dv6                | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| ASUSTek       | S550CA                      | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| ASUSTek       | S550CA                      | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| Dell          | Inspiron ME051              | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Toshiba       | Satellite Pro C660          | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| Dell          | Latitude E6230              | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Acer          | Aspire E5-575G              | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| Dell          | Latitude E6230              | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 48        | 11.16%  |
| Ubuntu 22.04       | 30        | 6.98%   |
| Ubuntu 18.04       | 28        | 6.51%   |
| Debian 11          | 14        | 3.26%   |
| Zorin 16           | 11        | 2.56%   |
| Pop!_OS 22.04      | 10        | 2.33%   |
| Linux Mint 21.1    | 8         | 1.86%   |
| Fedora 38          | 8         | 1.86%   |
| Fedora 36          | 7         | 1.63%   |
| Debian 10          | 7         | 1.63%   |
| Ubuntu 23.04       | 6         | 1.4%    |
| OpenMandriva 4.2   | 6         | 1.4%    |
| OpenMandriva 23.01 | 6         | 1.4%    |
| Manjaro            | 6         | 1.4%    |
| Linux Mint 21      | 6         | 1.4%    |
| Ubuntu 22.10       | 5         | 1.16%   |
| Ubuntu 19.10       | 5         | 1.16%   |
| Linux Mint 20.3    | 5         | 1.16%   |
| Linux Mint 20.2    | 5         | 1.16%   |
| Linux Mint 20      | 5         | 1.16%   |
| KDE neon 20.04     | 5         | 1.16%   |
| Fedora 37          | 5         | 1.16%   |
| ArcoLinux Rolling  | 5         | 1.16%   |
| Ubuntu 21.10       | 4         | 0.93%   |
| Ubuntu 19.04       | 4         | 0.93%   |
| Pop!_OS 21.10      | 4         | 0.93%   |
| Pop!_OS 20.04      | 4         | 0.93%   |
| Lubuntu 20.04      | 4         | 0.93%   |
| Linux Mint 21.2    | 4         | 0.93%   |
| Linux Mint 19.3    | 4         | 0.93%   |
| Kubuntu 20.04      | 4         | 0.93%   |
| Fedora 34          | 4         | 0.93%   |
| Debian Unstable    | 4         | 0.93%   |
| Debian 12          | 4         | 0.93%   |
| BlackPanther 18.1  | 4         | 0.93%   |
| Arch Rolling       | 4         | 0.93%   |
| Arch               | 4         | 0.93%   |
| Zorin 15           | 3         | 0.7%    |
| ROSA R10           | 3         | 0.7%    |
| Pop!_OS 20.10      | 3         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 132       | 32.27%  |
| Linux Mint    | 44        | 10.76%  |
| Fedora        | 30        | 7.33%   |
| Debian        | 29        | 7.09%   |
| Pop!_OS       | 23        | 5.62%   |
| OpenMandriva  | 21        | 5.13%   |
| Zorin         | 14        | 3.42%   |
| Manjaro       | 14        | 3.42%   |
| Kubuntu       | 13        | 3.18%   |
| Arch          | 8         | 1.96%   |
| ROSA          | 6         | 1.47%   |
| Lubuntu       | 6         | 1.47%   |
| KDE neon      | 6         | 1.47%   |
| Elementary    | 5         | 1.22%   |
| ArcoLinux     | 5         | 1.22%   |
| Ubuntu MATE   | 4         | 0.98%   |
| SteamOS       | 4         | 0.98%   |
| openSUSE      | 4         | 0.98%   |
| BlackPanther  | 4         | 0.98%   |
| Xubuntu       | 3         | 0.73%   |
| Ubuntu Unity  | 3         | 0.73%   |
| Ubuntu Budgie | 3         | 0.73%   |
| Endless       | 3         | 0.73%   |
| Rocky Linux   | 2         | 0.49%   |
| Parrot        | 2         | 0.49%   |
| LMDE          | 2         | 0.49%   |
| Clear Linux   | 2         | 0.49%   |
| CentOS        | 2         | 0.49%   |
| CachyOS       | 2         | 0.49%   |
| Xero          | 1         | 0.24%   |
| RHEL          | 1         | 0.24%   |
| Redcore       | 1         | 0.24%   |
| Reborn OS     | 1         | 0.24%   |
| Peppermint    | 1         | 0.24%   |
| Nobara        | 1         | 0.24%   |
| MX            | 1         | 0.24%   |
| Linux Lite    | 1         | 0.24%   |
| Kali          | 1         | 0.24%   |
| Gentoo        | 1         | 0.24%   |
| Garuda Linux  | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.3.0-46-generic         | 8         | 1.72%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.29%   |
| 5.4.0-42-generic         | 6         | 1.29%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.29%   |
| 5.4.0-52-generic         | 5         | 1.07%   |
| 5.19.0-35-generic        | 5         | 1.07%   |
| 5.15.0-56-generic        | 5         | 1.07%   |
| 5.15.0-52-generic        | 5         | 1.07%   |
| 5.15.0-46-generic        | 5         | 1.07%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.86%   |
| 6.2.0-36-generic         | 4         | 0.86%   |
| 5.4.0-26-generic         | 4         | 0.86%   |
| 5.15.0-67-generic        | 4         | 0.86%   |
| 5.15.0-48-generic        | 4         | 0.86%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.64%   |
| 6.2.0-26-generic         | 3         | 0.64%   |
| 5.4.0-31-generic         | 3         | 0.64%   |
| 5.4.0-29-generic         | 3         | 0.64%   |
| 5.19.0-32-generic        | 3         | 0.64%   |
| 5.15.0-40-generic        | 3         | 0.64%   |
| 5.11.0-27-generic        | 3         | 0.64%   |
| 5.10.0-8-amd64           | 3         | 0.64%   |
| 5.10.0-23-amd64          | 3         | 0.64%   |
| 5.10.0-14-amd64          | 3         | 0.64%   |
| 4.19.0-9-amd64           | 3         | 0.64%   |
| 4.18.16-desktop-1bP      | 3         | 0.64%   |
| 6.5.5-arch1-1            | 2         | 0.43%   |
| 6.3.8-200.fc38.x86_64    | 2         | 0.43%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.43%   |
| 6.2.0-32-generic         | 2         | 0.43%   |
| 6.2.0-20-generic         | 2         | 0.43%   |
| 6.1.0-1parrot1-amd64     | 2         | 0.43%   |
| 6.1.0-11-amd64           | 2         | 0.43%   |
| 6.0.9-300.fc37.x86_64    | 2         | 0.43%   |
| 6.0.6-76060006-generic   | 2         | 0.43%   |
| 6.0.12-76060006-generic  | 2         | 0.43%   |
| 6.0.10-300.fc37.x86_64   | 2         | 0.43%   |
| 5.8.0-7625-generic       | 2         | 0.43%   |
| 5.8.0-53-generic         | 2         | 0.43%   |
| 5.8.0-43-generic         | 2         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 71        | 16.47%  |
| 5.15.0  | 44        | 10.21%  |
| 5.19.0  | 23        | 5.34%   |
| 4.15.0  | 23        | 5.34%   |
| 5.3.0   | 17        | 3.94%   |
| 5.11.0  | 17        | 3.94%   |
| 6.2.0   | 15        | 3.48%   |
| 5.8.0   | 15        | 3.48%   |
| 5.10.0  | 15        | 3.48%   |
| 5.13.0  | 14        | 3.25%   |
| 5.0.0   | 8         | 1.86%   |
| 4.19.0  | 8         | 1.86%   |
| 6.1.0   | 7         | 1.62%   |
| 6.1.1   | 6         | 1.39%   |
| 5.10.14 | 6         | 1.39%   |
| 4.18.0  | 5         | 1.16%   |
| 6.4.11  | 4         | 0.93%   |
| 6.2.6   | 4         | 0.93%   |
| 6.5.6   | 3         | 0.7%    |
| 6.3.8   | 3         | 0.7%    |
| 5.18.0  | 3         | 0.7%    |
| 5.14.0  | 3         | 0.7%    |
| 4.18.16 | 3         | 0.7%    |
| 6.6.4   | 2         | 0.46%   |
| 6.5.5   | 2         | 0.46%   |
| 6.2.9   | 2         | 0.46%   |
| 6.0.9   | 2         | 0.46%   |
| 6.0.6   | 2         | 0.46%   |
| 6.0.12  | 2         | 0.46%   |
| 6.0.10  | 2         | 0.46%   |
| 6.0.0   | 2         | 0.46%   |
| 5.7.9   | 2         | 0.46%   |
| 5.6.7   | 2         | 0.46%   |
| 5.6.15  | 2         | 0.46%   |
| 5.6.0   | 2         | 0.46%   |
| 5.19.1  | 2         | 0.46%   |
| 5.18.17 | 2         | 0.46%   |
| 5.17.5  | 2         | 0.46%   |
| 5.16.7  | 2         | 0.46%   |
| 5.16.11 | 2         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 17.29%  |
| 5.15    | 51        | 11.92%  |
| 5.19    | 28        | 6.54%   |
| 5.10    | 27        | 6.31%   |
| 4.15    | 23        | 5.37%   |
| 6.2     | 22        | 5.14%   |
| 5.3     | 18        | 4.21%   |
| 5.8     | 17        | 3.97%   |
| 5.11    | 17        | 3.97%   |
| 6.1     | 16        | 3.74%   |
| 5.13    | 16        | 3.74%   |
| 6.0     | 13        | 3.04%   |
| 4.19    | 9         | 2.1%    |
| 6.5     | 8         | 1.87%   |
| 5.14    | 8         | 1.87%   |
| 5.0     | 8         | 1.87%   |
| 4.18    | 8         | 1.87%   |
| 5.6     | 7         | 1.64%   |
| 5.18    | 7         | 1.64%   |
| 6.4     | 6         | 1.4%    |
| 5.17    | 6         | 1.4%    |
| 5.16    | 6         | 1.4%    |
| 6.3     | 5         | 1.17%   |
| 4.9     | 5         | 1.17%   |
| 5.9     | 4         | 0.93%   |
| 5.7     | 4         | 0.93%   |
| 5.12    | 4         | 0.93%   |
| 6.6     | 2         | 0.47%   |
| 4.12    | 2         | 0.47%   |
| 3.10    | 2         | 0.47%   |
| 5.2     | 1         | 0.23%   |
| 4.4     | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |
| 4.13    | 1         | 0.23%   |
| 4.10    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 378       | 96.92%  |
| i686   | 12        | 3.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 198       | 48.18%  |
| KDE5            | 62        | 15.09%  |
| Unknown         | 41        | 9.98%   |
| X-Cinnamon      | 35        | 8.52%   |
| XFCE            | 22        | 5.35%   |
| KDE             | 11        | 2.68%   |
| MATE            | 8         | 1.95%   |
| LXQt            | 6         | 1.46%   |
| Cinnamon        | 6         | 1.46%   |
| Pantheon        | 5         | 1.22%   |
| i3              | 4         | 0.97%   |
| Unity           | 3         | 0.73%   |
| Budgie          | 3         | 0.73%   |
| KDE4            | 2         | 0.49%   |
| GNOME Classic   | 2         | 0.49%   |
| GNOME Flashback | 1         | 0.24%   |
| DWM             | 1         | 0.24%   |
| BunsenLabs      | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 302       | 75.5%   |
| Wayland | 72        | 18%     |
| Unknown | 22        | 5.5%    |
| Tty     | 4         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 202       | 49.88%  |
| GDM     | 52        | 12.84%  |
| SDDM    | 48        | 11.85%  |
| GDM3    | 47        | 11.6%   |
| LightDM | 41        | 10.12%  |
| TDM     | 12        | 2.96%   |
| KDM     | 2         | 0.49%   |
| SLiM    | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 199       | 49.26%  |
| en_US   | 70        | 17.33%  |
| en_GB   | 70        | 17.33%  |
| Unknown | 35        | 8.66%   |
| pl_PL   | 12        | 2.97%   |
| en_CA   | 2         | 0.5%    |
| C       | 2         | 0.5%    |
| bg_BG   | 2         | 0.5%    |
| zh_CN   | 1         | 0.25%   |
| pt_PT   | 1         | 0.25%   |
| lt_LT   | 1         | 0.25%   |
| it_IT   | 1         | 0.25%   |
| ga_IE   | 1         | 0.25%   |
| fr_FR   | 1         | 0.25%   |
| fr_BE   | 1         | 0.25%   |
| es_ES   | 1         | 0.25%   |
| en_ZA   | 1         | 0.25%   |
| en_IN   | 1         | 0.25%   |
| en_DE   | 1         | 0.25%   |
| en_AU   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 215       | 53.88%  |
| BIOS | 184       | 46.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 292       | 72.64%  |
| Btrfs               | 46        | 11.44%  |
| Overlay             | 26        | 6.47%   |
| Unknown             | 14        | 3.48%   |
| Tmpfs               | 10        | 2.49%   |
| Xfs                 | 9         | 2.24%   |
| Zfs                 | 3         | 0.75%   |
| Fuse.fuse-overlayfs | 1         | 0.25%   |
| Ext3                | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 210       | 52.5%   |
| GPT     | 151       | 37.75%  |
| MBR     | 39        | 9.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 346       | 87.59%  |
| Yes       | 49        | 12.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 306       | 77.27%  |
| Yes       | 90        | 22.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 94        | 24.1%   |
| Lenovo              | 90        | 23.08%  |
| Hewlett-Packard     | 51        | 13.08%  |
| ASUSTek Computer    | 31        | 7.95%   |
| Acer                | 29        | 7.44%   |
| Toshiba             | 13        | 3.33%   |
| Apple               | 10        | 2.56%   |
| Samsung Electronics | 8         | 2.05%   |
| MSI                 | 5         | 1.28%   |
| Valve               | 4         | 1.03%   |
| TUXEDO              | 4         | 1.03%   |
| Timi                | 4         | 1.03%   |
| PC Specialist       | 4         | 1.03%   |
| Medion              | 4         | 1.03%   |
| Chuwi               | 4         | 1.03%   |
| System76            | 3         | 0.77%   |
| Notebook            | 3         | 0.77%   |
| HUAWEI              | 3         | 0.77%   |
| Fujitsu             | 3         | 0.77%   |
| Packard Bell        | 2         | 0.51%   |
| Fujitsu Siemens     | 2         | 0.51%   |
| Entroware           | 2         | 0.51%   |
| eMachines           | 2         | 0.51%   |
| AVITA               | 2         | 0.51%   |
| Alienware           | 2         | 0.51%   |
| Star Labs           | 1         | 0.26%   |
| Sony                | 1         | 0.26%   |
| SLIMBOOK            | 1         | 0.26%   |
| Schenker            | 1         | 0.26%   |
| Microtech           | 1         | 0.26%   |
| Jumper              | 1         | 0.26%   |
| Google              | 1         | 0.26%   |
| Gigabyte Technology | 1         | 0.26%   |
| Framework           | 1         | 0.26%   |
| Dynabook            | 1         | 0.26%   |
| Advent              | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Dell Latitude 7420                | 8         | 2.05%   |
| Valve Jupiter                     | 4         | 1.03%   |
| Lenovo V145-15AST 81MT            | 3         | 0.77%   |
| Dell Latitude E7240               | 3         | 0.77%   |
| Dell Inspiron 13-5378             | 3         | 0.77%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.51%   |
| Samsung 750XED                    | 2         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.51%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.51%   |
| HUAWEI NBLK-WAX9X                 | 2         | 0.51%   |
| HP Pavilion Laptop 15-eh0xxx      | 2         | 0.51%   |
| HP Pavilion g6                    | 2         | 0.51%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.51%   |
| HP Notebook                       | 2         | 0.51%   |
| Dell XPS 9320                     | 2         | 0.51%   |
| Dell XPS 13 9310                  | 2         | 0.51%   |
| Dell XPS 13 9300                  | 2         | 0.51%   |
| Dell XPS 13 7390                  | 2         | 0.51%   |
| Dell Precision 5550               | 2         | 0.51%   |
| Dell Latitude E6430               | 2         | 0.51%   |
| Dell Latitude E6400               | 2         | 0.51%   |
| Dell Latitude E6230               | 2         | 0.51%   |
| Dell Inspiron 7577                | 2         | 0.51%   |
| Dell Inspiron 5570                | 2         | 0.51%   |
| Chuwi GemiBook Pro                | 2         | 0.51%   |
| ASUS X501A1                       | 2         | 0.51%   |
| Apple MacBook6,1                  | 2         | 0.51%   |
| Acer Aspire F5-573G               | 2         | 0.51%   |
| Acer Aspire E5-575G               | 2         | 0.51%   |
| TUXEDO InfinityBook Pro 15 v5     | 1         | 0.26%   |
| TUXEDO InfinityBook Pro 14 Gen6   | 1         | 0.26%   |
| Toshiba TECRA R850                | 1         | 0.26%   |
| Toshiba TECRA M4                  | 1         | 0.26%   |
| Toshiba Satellite Pro S500        | 1         | 0.26%   |
| Toshiba Satellite Pro R50-B       | 1         | 0.26%   |
| Toshiba Satellite Pro C660        | 1         | 0.26%   |
| Toshiba Satellite L500            | 1         | 0.26%   |
| Toshiba Satellite L50-C           | 1         | 0.26%   |
| Toshiba Satellite L50-B           | 1         | 0.26%   |
| Toshiba Satellite C50D-A-138      | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 49        | 12.56%  |
| Dell Latitude         | 47        | 12.05%  |
| Lenovo IdeaPad        | 20        | 5.13%   |
| Dell Inspiron         | 20        | 5.13%   |
| Acer Aspire           | 20        | 5.13%   |
| HP EliteBook          | 14        | 3.59%   |
| Dell XPS              | 13        | 3.33%   |
| HP Pavilion           | 12        | 3.08%   |
| Toshiba Satellite     | 10        | 2.56%   |
| Dell Precision        | 7         | 1.79%   |
| Valve Jupiter         | 4         | 1.03%   |
| ASUS ZenBook          | 4         | 1.03%   |
| ASUS ROG              | 4         | 1.03%   |
| Lenovo V145-15AST     | 3         | 0.77%   |
| Lenovo ThinkBook      | 3         | 0.77%   |
| HP ProBook            | 3         | 0.77%   |
| HP Presario           | 3         | 0.77%   |
| HP OMEN               | 3         | 0.77%   |
| HP Laptop             | 3         | 0.77%   |
| HP Compaq             | 3         | 0.77%   |
| Fujitsu LIFEBOOK      | 3         | 0.77%   |
| ASUS VivoBook         | 3         | 0.77%   |
| Apple MacBookPro5     | 3         | 0.77%   |
| Acer Nitro            | 3         | 0.77%   |
| TUXEDO Pulse          | 2         | 0.51%   |
| TUXEDO InfinityBook   | 2         | 0.51%   |
| Toshiba TECRA         | 2         | 0.51%   |
| Samsung 750XED        | 2         | 0.51%   |
| Packard Bell EasyNote | 2         | 0.51%   |
| Lenovo Yoga           | 2         | 0.51%   |
| Lenovo IdeaPadFlex    | 2         | 0.51%   |
| HUAWEI NBLK-WAX9X     | 2         | 0.51%   |
| HP ZBook              | 2         | 0.51%   |
| HP Notebook           | 2         | 0.51%   |
| Fujitsu Siemens AMILO | 2         | 0.51%   |
| Dell Vostro           | 2         | 0.51%   |
| Chuwi GemiBook        | 2         | 0.51%   |
| ASUS X501A1           | 2         | 0.51%   |
| ASUS TUF              | 2         | 0.51%   |
| Apple MacBook6        | 2         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 50        | 12.82%  |
| 2019 | 37        | 9.49%   |
| 2017 | 31        | 7.95%   |
| 2021 | 29        | 7.44%   |
| 2012 | 29        | 7.44%   |
| 2018 | 28        | 7.18%   |
| 2013 | 27        | 6.92%   |
| 2011 | 23        | 5.9%    |
| 2022 | 21        | 5.38%   |
| 2016 | 21        | 5.38%   |
| 2015 | 18        | 4.62%   |
| 2008 | 18        | 4.62%   |
| 2010 | 14        | 3.59%   |
| 2009 | 14        | 3.59%   |
| 2014 | 11        | 2.82%   |
| 2023 | 7         | 1.79%   |
| 2007 | 7         | 1.79%   |
| 2006 | 3         | 0.77%   |
| 2005 | 1         | 0.26%   |
| 2003 | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 390       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 343       | 86.84%  |
| Enabled  | 52        | 13.16%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 387       | 99.23%  |
| Yes  | 3         | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 115       | 28.97%  |
| 16.01-24.0  | 84        | 21.16%  |
| 3.01-4.0    | 69        | 17.38%  |
| 8.01-16.0   | 62        | 15.62%  |
| 32.01-64.0  | 35        | 8.82%   |
| 1.01-2.0    | 14        | 3.53%   |
| 2.01-3.0    | 6         | 1.51%   |
| 24.01-32.0  | 5         | 1.26%   |
| 64.01-256.0 | 4         | 1.01%   |
| 0.51-1.0    | 2         | 0.5%    |
| 0.01-0.5    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 122       | 27.92%  |
| 2.01-3.0   | 121       | 27.69%  |
| 4.01-8.0   | 76        | 17.39%  |
| 3.01-4.0   | 73        | 16.7%   |
| 0.51-1.0   | 23        | 5.26%   |
| 8.01-16.0  | 14        | 3.2%    |
| 16.01-24.0 | 5         | 1.14%   |
| 0.01-0.5   | 3         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 294       | 72.95%  |
| 2      | 93        | 23.08%  |
| 3      | 13        | 3.23%   |
| 0      | 3         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 266       | 67.68%  |
| Yes       | 127       | 32.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 310       | 78.88%  |
| No        | 83        | 21.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 387       | 98.98%  |
| No        | 4         | 1.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 79.19%  |
| No        | 82        | 20.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 390       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 233       | 57.96%  |
| Cork                | 25        | 6.22%   |
| Galway              | 20        | 4.98%   |
| Limerick            | 11        | 2.74%   |
| Naas                | 8         | 1.99%   |
| Drogheda            | 6         | 1.49%   |
| Enniscorthy         | 5         | 1.24%   |
| Ennis               | 5         | 1.24%   |
| Navan               | 4         | 1%      |
| Lucan               | 3         | 0.75%   |
| Dún Laoghaire      | 3         | 0.75%   |
| Wexford             | 2         | 0.5%    |
| Westport            | 2         | 0.5%    |
| Waterford           | 2         | 0.5%    |
| Tullamore           | 2         | 0.5%    |
| Portlaoise          | 2         | 0.5%    |
| Nenagh              | 2         | 0.5%    |
| Maynooth            | 2         | 0.5%    |
| Loughrea            | 2         | 0.5%    |
| Letterkenny         | 2         | 0.5%    |
| Kilkenny            | 2         | 0.5%    |
| Donegal             | 2         | 0.5%    |
| Cobh                | 2         | 0.5%    |
| Clonakilty          | 2         | 0.5%    |
| Clane               | 2         | 0.5%    |
| Ballina             | 2         | 0.5%    |
| Athlone             | 2         | 0.5%    |
| Youghal             | 1         | 0.25%   |
| Wicklow             | 1         | 0.25%   |
| Tullow              | 1         | 0.25%   |
| Tuam                | 1         | 0.25%   |
| Tobercurry          | 1         | 0.25%   |
| Tallaght            | 1         | 0.25%   |
| Sligo               | 1         | 0.25%   |
| Slane               | 1         | 0.25%   |
| Scarriff            | 1         | 0.25%   |
| Santry              | 1         | 0.25%   |
| Rathcool            | 1         | 0.25%   |
| Oughterard          | 1         | 0.25%   |
| Newmarket on Fergus | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 94        | 126    | 19.42%  |
| WDC                         | 55        | 66     | 11.36%  |
| Seagate                     | 42        | 55     | 8.68%   |
| Unknown                     | 35        | 49     | 7.23%   |
| SanDisk                     | 33        | 37     | 6.82%   |
| Toshiba                     | 30        | 38     | 6.2%    |
| Hitachi                     | 22        | 27     | 4.55%   |
| Crucial                     | 18        | 26     | 3.72%   |
| Micron Technology           | 16        | 18     | 3.31%   |
| KIOXIA                      | 15        | 16     | 3.1%    |
| Kingston                    | 15        | 17     | 3.1%    |
| SK hynix                    | 14        | 14     | 2.89%   |
| Intel                       | 14        | 17     | 2.89%   |
| HGST                        | 11        | 14     | 2.27%   |
| Fujitsu                     | 6         | 7      | 1.24%   |
| LITEON                      | 4         | 5      | 0.83%   |
| PNY                         | 3         | 3      | 0.62%   |
| OCZ                         | 3         | 3      | 0.62%   |
| LITEONIT                    | 3         | 3      | 0.62%   |
| KingSpec                    | 3         | 3      | 0.62%   |
| FORESEE                     | 3         | 4      | 0.62%   |
| Apple                       | 3         | 4      | 0.62%   |
| Transcend                   | 2         | 2      | 0.41%   |
| SSSTC                       | 2         | 2      | 0.41%   |
| Silicon Motion              | 2         | 3      | 0.41%   |
| O2 Micro                    | 2         | 4      | 0.41%   |
| Micron/Crucial Technology   | 2         | 2      | 0.41%   |
| Kingston Technology Company | 2         | 2      | 0.41%   |
| China                       | 2         | 8      | 0.41%   |
| A-DATA Technology           | 2         | 2      | 0.41%   |
| Zheino                      | 1         | 1      | 0.21%   |
| Wibtek                      | 1         | 2      | 0.21%   |
| W800S                       | 1         | 2      | 0.21%   |
| Verbatim                    | 1         | 1      | 0.21%   |
| USB                         | 1         | 1      | 0.21%   |
| Union Memory                | 1         | 1      | 0.21%   |
| Star                        | 1         | 1      | 0.21%   |
| SPCC                        | 1         | 1      | 0.21%   |
| ShanDianZhe                 | 1         | 1      | 0.21%   |
| SABRENT                     | 1         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 1.99%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 8         | 1.59%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 1.39%   |
| Unknown MMC Card  64GB                              | 5         | 0.99%   |
| Unknown MMC Card  32GB                              | 5         | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 0.99%   |
| Kingston SA400S37480G 480GB SSD                     | 5         | 0.99%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.8%    |
| Samsung SSD 860 EVO 500GB                           | 4         | 0.8%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 4         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 4         | 0.8%    |
| Hitachi HTS723232A7A364 320GB                       | 4         | 0.8%    |
| HGST HTS721010A9E630 1TB                            | 4         | 0.8%    |
| HGST HTS545050A7E680 500GB                          | 4         | 0.8%    |
| Crucial CT1000MX500SSD1 1TB                         | 4         | 0.8%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 3         | 0.6%    |
| WDC PC SN530 NVMe 512GB                             | 3         | 0.6%    |
| Unknown SL16G  16GB                                 | 3         | 0.6%    |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.6%    |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 3         | 0.6%    |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.6%    |
| Samsung NVMe SSD Drive 512GB                        | 3         | 0.6%    |
| Samsung NVMe SSD Drive 500GB                        | 3         | 0.6%    |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 3         | 0.6%    |
| PNY CS900 120GB SSD                                 | 3         | 0.6%    |
| FORESEE 256GB SSD                                   | 3         | 0.6%    |
| Crucial M4-CT128M4SSD2 128GB                        | 3         | 0.6%    |
| WDC WDS100T1B0A-00H9H0 1TB SSD                      | 2         | 0.4%    |
| WDC WD3200LPVX-75V0TT0 320GB                        | 2         | 0.4%    |
| WDC WD10SPZX-75Z10T2 1TB                            | 2         | 0.4%    |
| WDC WD10JPVX-00JC3T0 1TB                            | 2         | 0.4%    |
| WDC WD10JPCX-24UE4T0 1TB                            | 2         | 0.4%    |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.4%    |
| Unknown MMC Card  512GB                             | 2         | 0.4%    |
| Unknown MMC Card  16GB                              | 2         | 0.4%    |
| Unknown MMC Card  128GB                             | 2         | 0.4%    |
| Unknown HBG4a2  32GB                                | 2         | 0.4%    |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2         | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.4%    |
| Toshiba KBG30ZMS256G NVMe 256GB                     | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 54     | 28.87%  |
| WDC                 | 35        | 38     | 24.65%  |
| Hitachi             | 22        | 27     | 15.49%  |
| Toshiba             | 17        | 19     | 11.97%  |
| HGST                | 11        | 14     | 7.75%   |
| Fujitsu             | 6         | 7      | 4.23%   |
| Samsung Electronics | 3         | 4      | 2.11%   |
| Unknown             | 2         | 2      | 1.41%   |
| USB                 | 1         | 1      | 0.7%    |
| SABRENT             | 1         | 2      | 0.7%    |
| QNAP                | 1         | 1      | 0.7%    |
| LaCie               | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 46     | 26.35%  |
| SanDisk             | 18        | 18     | 12.16%  |
| Crucial             | 17        | 25     | 11.49%  |
| Kingston            | 13        | 15     | 8.78%   |
| WDC                 | 7         | 10     | 4.73%   |
| SK hynix            | 4         | 4      | 2.7%    |
| Micron Technology   | 4         | 4      | 2.7%    |
| Intel               | 4         | 4      | 2.7%    |
| Toshiba             | 3         | 5      | 2.03%   |
| PNY                 | 3         | 3      | 2.03%   |
| OCZ                 | 3         | 3      | 2.03%   |
| LITEONIT            | 3         | 3      | 2.03%   |
| LITEON              | 3         | 4      | 2.03%   |
| KingSpec            | 3         | 3      | 2.03%   |
| FORESEE             | 3         | 4      | 2.03%   |
| China               | 2         | 8      | 1.35%   |
| Zheino              | 1         | 1      | 0.68%   |
| Wibtek              | 1         | 2      | 0.68%   |
| W800S               | 1         | 2      | 0.68%   |
| Verbatim            | 1         | 1      | 0.68%   |
| Union Memory        | 1         | 1      | 0.68%   |
| Transcend           | 1         | 1      | 0.68%   |
| Star                | 1         | 1      | 0.68%   |
| SPCC                | 1         | 1      | 0.68%   |
| Plextor             | 1         | 1      | 0.68%   |
| Patriot             | 1         | 1      | 0.68%   |
| JMicron Technology  | 1         | 1      | 0.68%   |
| Integral            | 1         | 1      | 0.68%   |
| GOODRAM             | 1         | 1      | 0.68%   |
| faspeed             | 1         | 1      | 0.68%   |
| Fanxiang            | 1         | 1      | 0.68%   |
| Emtec               | 1         | 2      | 0.68%   |
| Dogfish             | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |
| A-DATA Technology   | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 154       | 205    | 33.33%  |
| SSD     | 138       | 181    | 29.87%  |
| HDD     | 134       | 171    | 29%     |
| MMC     | 32        | 46     | 6.93%   |
| Unknown | 4         | 4      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 246       | 343    | 55.66%  |
| NVMe | 154       | 205    | 34.84%  |
| MMC  | 32        | 46     | 7.24%   |
| SAS  | 10        | 13     | 2.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 185       | 243    | 69.81%  |
| 0.51-1.0   | 71        | 95     | 26.79%  |
| 1.01-2.0   | 6         | 9      | 2.26%   |
| 4.01-10.0  | 2         | 4      | 0.75%   |
| 3.01-4.0   | 1         | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 123       | 30.15%  |
| 101-250        | 117       | 28.68%  |
| 501-1000       | 46        | 11.27%  |
| 1-20           | 35        | 8.58%   |
| 51-100         | 32        | 7.84%   |
| 1001-2000      | 23        | 5.64%   |
| 21-50          | 13        | 3.19%   |
| Unknown        | 10        | 2.45%   |
| More than 3000 | 6         | 1.47%   |
| 2001-3000      | 3         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 168       | 39.07%  |
| 21-50          | 75        | 17.44%  |
| 101-250        | 67        | 15.58%  |
| 51-100         | 59        | 13.72%  |
| 251-500        | 29        | 6.74%   |
| 501-1000       | 17        | 3.95%   |
| Unknown        | 10        | 2.33%   |
| 1001-2000      | 4         | 0.93%   |
| More than 3000 | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 8.7%    |
| WDC WD5000LPCX-24VHAT0 500GB                   | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 4.35%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 4.35%   |
| Toshiba MK3261GSYN 320GB                       | 1         | 1      | 4.35%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 4.35%   |
| SK hynix SC308 SATA 256GB SSD                  | 1         | 1      | 4.35%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 4.35%   |
| Seagate ST500LM030-2E717D 500GB                | 1         | 1      | 4.35%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 4.35%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 4.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 4.35%   |
| JMicron Technology Generic 250GB               | 1         | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 4.35%   |
| Hitachi HTS545032A7E380 320GB                  | 1         | 1      | 4.35%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 3      | 4.35%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 4.35%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 4.35%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 4.35%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 9      | 30.43%  |
| Toshiba             | 4         | 4      | 17.39%  |
| WDC                 | 2         | 2      | 8.7%    |
| Seagate             | 2         | 2      | 8.7%    |
| Micron Technology   | 2         | 2      | 8.7%    |
| SK hynix            | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 9      | 38.89%  |
| Toshiba             | 4         | 4      | 22.22%  |
| WDC                 | 2         | 2      | 11.11%  |
| Seagate             | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 20     | 75%     |
| SSD  | 5         | 5      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 239       | 373    | 58.15%  |
| Works    | 152       | 208    | 36.98%  |
| Malfunc  | 19        | 25     | 4.62%   |
| Failed   | 1         | 1      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 255       | 55.19%  |
| Samsung Electronics            | 54        | 11.69%  |
| AMD                            | 44        | 9.52%   |
| Sandisk                        | 29        | 6.28%   |
| KIOXIA                         | 14        | 3.03%   |
| Micron Technology              | 12        | 2.6%    |
| Toshiba America Info Systems   | 11        | 2.38%   |
| SK hynix                       | 10        | 2.16%   |
| Nvidia                         | 9         | 1.95%   |
| Kingston Technology Company    | 4         | 0.87%   |
| Micron/Crucial Technology      | 3         | 0.65%   |
| Union Memory (Shenzhen)        | 2         | 0.43%   |
| Solid State Storage Technology | 2         | 0.43%   |
| Silicon Motion                 | 2         | 0.43%   |
| Phison Electronics             | 2         | 0.43%   |
| O2 Micro                       | 2         | 0.43%   |
| Transcend                      | 1         | 0.22%   |
| Silicon Image                  | 1         | 0.22%   |
| Lite-On Technology             | 1         | 0.22%   |
| Lenovo                         | 1         | 0.22%   |
| Apple                          | 1         | 0.22%   |
| ADATA Technology               | 1         | 0.22%   |
| Adaptec                        | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 41        | 8.3%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 8.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 25        | 5.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 4.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 3.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 2.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 2.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 12        | 2.43%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 9         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 1.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.21%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.21%   |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 0.81%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.81%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 4         | 0.81%   |
| Intel SSD 660P Series                                                          | 4         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.81%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 0.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 0.61%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 3         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 252       | 53.16%  |
| NVMe | 155       | 32.7%   |
| RAID | 42        | 8.86%   |
| IDE  | 24        | 5.06%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 316       | 80.82%  |
| AMD    | 75        | 19.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 13        | 3.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.28%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.02%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 1.02%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 1.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.02%   |
| AMD Custom APU 0405                           | 4         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.77%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.77%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.77%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.77%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.77%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.77%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.77%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 0.77%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.77%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 3         | 0.77%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.77%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.77%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.77%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.77%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.77%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 84        | 21.48%  |
| Intel Core i5           | 84        | 21.48%  |
| Other                   | 55        | 14.07%  |
| Intel Core i3           | 23        | 5.88%   |
| Intel Celeron           | 23        | 5.88%   |
| Intel Core 2 Duo        | 22        | 5.63%   |
| AMD Ryzen 7             | 17        | 4.35%   |
| AMD Ryzen 5             | 15        | 3.84%   |
| Intel Pentium           | 8         | 2.05%   |
| Intel Atom              | 6         | 1.53%   |
| AMD E1                  | 4         | 1.02%   |
| AMD A8                  | 4         | 1.02%   |
| Intel Core 2            | 3         | 0.77%   |
| AMD Ryzen 9             | 3         | 0.77%   |
| AMD Ryzen 7 PRO         | 3         | 0.77%   |
| Intel Pentium Silver    | 2         | 0.51%   |
| Intel Pentium Dual-Core | 2         | 0.51%   |
| Intel Core i9           | 2         | 0.51%   |
| Intel Celeron Dual-Core | 2         | 0.51%   |
| AMD Sempron             | 2         | 0.51%   |
| AMD Ryzen 5 PRO         | 2         | 0.51%   |
| AMD Ryzen 3 PRO         | 2         | 0.51%   |
| AMD Ryzen 3             | 2         | 0.51%   |
| AMD E2                  | 2         | 0.51%   |
| AMD A10                 | 2         | 0.51%   |
| Intel Pentium M         | 1         | 0.26%   |
| Intel Pentium III       | 1         | 0.26%   |
| Intel Pentium Dual      | 1         | 0.26%   |
| Intel Genuine           | 1         | 0.26%   |
| Intel Core m7           | 1         | 0.26%   |
| Intel Core m5           | 1         | 0.26%   |
| Intel Core m3           | 1         | 0.26%   |
| Intel Core 2 Extreme    | 1         | 0.26%   |
| Intel Celeron M         | 1         | 0.26%   |
| AMD Turion 64 X2 Mobile | 1         | 0.26%   |
| AMD PRO A10             | 1         | 0.26%   |
| AMD Phenom II           | 1         | 0.26%   |
| AMD FX                  | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD Athlon 64 X2        | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 177       | 45.27%  |
| 4      | 139       | 35.55%  |
| 8      | 24        | 6.14%   |
| 6      | 21        | 5.37%   |
| 1      | 11        | 2.81%   |
| 14     | 7         | 1.79%   |
| 12     | 5         | 1.28%   |
| 10     | 5         | 1.28%   |
| 24     | 1         | 0.26%   |
| 3      | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 390       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 289       | 73.91%  |
| 1      | 102       | 26.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 382       | 97.2%   |
| Unknown        | 8         | 2.04%   |
| 32-bit         | 3         | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 31.2%   |
| 0x806ec    | 21        | 5.16%   |
| 0x306a9    | 20        | 4.91%   |
| 0x806e9    | 15        | 3.69%   |
| 0x806c1    | 14        | 3.44%   |
| 0x206a7    | 14        | 3.44%   |
| 0x1067a    | 13        | 3.19%   |
| 0x806ea    | 12        | 2.95%   |
| 0x406e3    | 11        | 2.7%    |
| 0x40651    | 10        | 2.46%   |
| 0xa0652    | 7         | 1.72%   |
| 0x906ea    | 7         | 1.72%   |
| 0x0a50000c | 7         | 1.72%   |
| 0x906e9    | 6         | 1.47%   |
| 0x306d4    | 6         | 1.47%   |
| 0x306c3    | 6         | 1.47%   |
| 0x30678    | 6         | 1.47%   |
| 0x406c4    | 5         | 1.23%   |
| 0x20655    | 5         | 1.23%   |
| 0x10676    | 5         | 1.23%   |
| 0x08108109 | 5         | 1.23%   |
| 0x06006705 | 5         | 1.23%   |
| 0x906a3    | 4         | 0.98%   |
| 0x6fd      | 4         | 0.98%   |
| 0x08108102 | 4         | 0.98%   |
| 0x806d1    | 3         | 0.74%   |
| 0x706e5    | 3         | 0.74%   |
| 0x706a8    | 3         | 0.74%   |
| 0x506e3    | 3         | 0.74%   |
| 0x106ca    | 3         | 0.74%   |
| 0x08600106 | 3         | 0.74%   |
| 0x906a4    | 2         | 0.49%   |
| 0x706a1    | 2         | 0.49%   |
| 0x6f6      | 2         | 0.49%   |
| 0x6d8      | 2         | 0.49%   |
| 0x20652    | 2         | 0.49%   |
| 0x08608103 | 2         | 0.49%   |
| 0x08600109 | 2         | 0.49%   |
| 0x08600103 | 2         | 0.49%   |
| 0x0810100b | 2         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 79        | 20.2%   |
| IvyBridge        | 27        | 6.91%   |
| TigerLake        | 25        | 6.39%   |
| SandyBridge      | 23        | 5.88%   |
| Skylake          | 22        | 5.63%   |
| Penryn           | 21        | 5.37%   |
| Haswell          | 21        | 5.37%   |
| Unknown          | 17        | 4.35%   |
| Silvermont       | 15        | 3.84%   |
| Zen 2            | 12        | 3.07%   |
| Westmere         | 12        | 3.07%   |
| Zen+             | 11        | 2.81%   |
| Core             | 11        | 2.81%   |
| Alderlake Hybrid | 11        | 2.81%   |
| Zen 3            | 10        | 2.56%   |
| Excavator        | 9         | 2.3%    |
| IceLake          | 8         | 2.05%   |
| Goldmont plus    | 8         | 2.05%   |
| CometLake        | 8         | 2.05%   |
| Broadwell        | 7         | 1.79%   |
| Zen              | 5         | 1.28%   |
| P6               | 4         | 1.02%   |
| Bobcat           | 4         | 1.02%   |
| Puma             | 3         | 0.77%   |
| K8 Hammer        | 3         | 0.77%   |
| Jaguar           | 3         | 0.77%   |
| Goldmont         | 3         | 0.77%   |
| Bonnell          | 3         | 0.77%   |
| Piledriver       | 2         | 0.51%   |
| K10              | 2         | 0.51%   |
| Nehalem          | 1         | 0.26%   |
| K8 & K10 hybrid  | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 282       | 59.37%  |
| Nvidia | 111       | 23.37%  |
| AMD    | 82        | 17.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 5.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 4.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 4.09%   |
| Intel UHD Graphics 620                                                                   | 16        | 3.27%   |
| Intel HD Graphics 620                                                                    | 16        | 3.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 2.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 2.25%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 2.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.64%   |
| Intel HD Graphics 630                                                                    | 7         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.43%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.23%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.02%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.82%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.82%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 0.82%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 0.82%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.82%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 4         | 0.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 205       | 52.43%  |
| Intel + Nvidia | 69        | 17.65%  |
| 1 x AMD        | 59        | 15.09%  |
| 1 x Nvidia     | 32        | 8.18%   |
| AMD + Nvidia   | 9         | 2.3%    |
| 2 x AMD        | 8         | 2.05%   |
| Intel + AMD    | 6         | 1.53%   |
| 2 x Intel      | 2         | 0.51%   |
| 2 x Nvidia     | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 325       | 82.49%  |
| Proprietary | 55        | 13.96%  |
| Unknown     | 14        | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 264       | 65.67%  |
| 0.01-0.5   | 53        | 13.18%  |
| 1.01-2.0   | 28        | 6.97%   |
| 3.01-4.0   | 26        | 6.47%   |
| 0.51-1.0   | 18        | 4.48%   |
| 5.01-6.0   | 6         | 1.49%   |
| 7.01-8.0   | 5         | 1.24%   |
| 2.01-3.0   | 2         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 76        | 16.7%   |
| BOE                     | 73        | 16.04%  |
| LG Display              | 66        | 14.51%  |
| Chimei Innolux          | 48        | 10.55%  |
| Samsung Electronics     | 35        | 7.69%   |
| Dell                    | 28        | 6.15%   |
| Sharp                   | 21        | 4.62%   |
| Lenovo                  | 11        | 2.42%   |
| ViewSonic               | 9         | 1.98%   |
| PANDA                   | 9         | 1.98%   |
| Apple                   | 9         | 1.98%   |
| Chi Mei Optoelectronics | 8         | 1.76%   |
| Hewlett-Packard         | 7         | 1.54%   |
| Goldstar                | 7         | 1.54%   |
| Philips                 | 6         | 1.32%   |
| LG Philips              | 5         | 1.1%    |
| Acer                    | 5         | 1.1%    |
| Valve                   | 3         | 0.66%   |
| InfoVision              | 3         | 0.66%   |
| AOC                     | 3         | 0.66%   |
| MSI                     | 2         | 0.44%   |
| KDB                     | 2         | 0.44%   |
| CSO                     | 2         | 0.44%   |
| CPT                     | 2         | 0.44%   |
| BOE Technology Group    | 2         | 0.44%   |
| BenQ                    | 2         | 0.44%   |
| ___                     | 1         | 0.22%   |
| Vestel Elektronik       | 1         | 0.22%   |
| Unknown                 | 1         | 0.22%   |
| Toshiba                 | 1         | 0.22%   |
| Quanta Display          | 1         | 0.22%   |
| OEM                     | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| Lenovo Group Limited    | 1         | 0.22%   |
| Iiyama                  | 1         | 0.22%   |
| ASUSTek Computer        | 1         | 0.22%   |
| Analogix                | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 9         | 1.93%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 8         | 1.72%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                    | 8         | 1.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 1.07%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 4         | 0.86%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 4         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 4         | 0.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 4         | 0.86%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 3         | 0.64%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 3         | 0.64%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 3         | 0.64%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.64%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.64%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 0.64%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch              | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.64%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.43%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.43%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.43%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch | 2         | 0.43%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2         | 0.43%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.43%   |
| LG Philips LCD Monitor LPLA104 1440x900 367x230mm 17.1-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch          | 2         | 0.43%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 2         | 0.43%   |
| KDB LCD Monitor KDB0526 1920x1080 344x194mm 15.5-inch                | 2         | 0.43%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.43%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 198       | 46.26%  |
| 1366x768 (WXGA)    | 103       | 24.07%  |
| 3840x2160 (4K)     | 17        | 3.97%   |
| 1600x900 (HD+)     | 16        | 3.74%   |
| 2560x1440 (QHD)    | 15        | 3.5%    |
| 1280x800 (WXGA)    | 14        | 3.27%   |
| 1920x1200 (WUXGA)  | 12        | 2.8%    |
| 1440x900 (WXGA+)   | 12        | 2.8%    |
| 2560x1600          | 6         | 1.4%    |
| 800x1280           | 4         | 0.93%   |
| 3440x1440          | 4         | 0.93%   |
| 2880x1800          | 4         | 0.93%   |
| 3840x2400          | 3         | 0.7%    |
| 1280x1024 (SXGA)   | 3         | 0.7%    |
| 1024x600           | 3         | 0.7%    |
| 3456x2160          | 2         | 0.47%   |
| 3200x1800 (QHD+)   | 2         | 0.47%   |
| 2160x1440          | 2         | 0.47%   |
| 1600x1200          | 2         | 0.47%   |
| 1360x768           | 2         | 0.47%   |
| 2560x1080          | 1         | 0.23%   |
| 2256x1504          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1680x1050 (WSXGA+) | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 180       | 38.96%  |
| 14      | 69        | 14.94%  |
| 13      | 57        | 12.34%  |
| 27      | 28        | 6.06%   |
| 17      | 23        | 4.98%   |
| 24      | 17        | 3.68%   |
| 12      | 17        | 3.68%   |
| 21      | 16        | 3.46%   |
| 23      | 9         | 1.95%   |
| Unknown | 8         | 1.73%   |
| 11      | 6         | 1.3%    |
| 34      | 5         | 1.08%   |
| 16      | 5         | 1.08%   |
| 31      | 4         | 0.87%   |
| 10      | 3         | 0.65%   |
| 7       | 3         | 0.65%   |
| 29      | 2         | 0.43%   |
| 18      | 2         | 0.43%   |
| 84      | 1         | 0.22%   |
| 72      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |
| 25      | 1         | 0.22%   |
| 20      | 1         | 0.22%   |
| 19      | 1         | 0.22%   |
| 3       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 267       | 58.68%  |
| 201-300     | 62        | 13.63%  |
| 501-600     | 47        | 10.33%  |
| 351-400     | 30        | 6.59%   |
| 401-500     | 19        | 4.18%   |
| 601-700     | 10        | 2.2%    |
| Unknown     | 8         | 1.76%   |
| 701-800     | 5         | 1.1%    |
| 1-100       | 4         | 0.88%   |
| 1501-2000   | 2         | 0.44%   |
| 801-900     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 319       | 80.76%  |
| 16/10   | 50        | 12.66%  |
| Unknown | 7         | 1.77%   |
| 21/9    | 6         | 1.52%   |
| 3/2     | 4         | 1.01%   |
| 5/4     | 3         | 0.76%   |
| 0.67    | 3         | 0.76%   |
| 4/3     | 2         | 0.51%   |
| 6/5     | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 177       | 38.39%  |
| 81-90          | 98        | 21.26%  |
| 201-250        | 36        | 7.81%   |
| 301-350        | 30        | 6.51%   |
| 71-80          | 29        | 6.29%   |
| 121-130        | 17        | 3.69%   |
| 61-70          | 16        | 3.47%   |
| 351-500        | 10        | 2.17%   |
| Unknown        | 8         | 1.74%   |
| 111-120        | 7         | 1.52%   |
| 51-60          | 6         | 1.3%    |
| 1-40           | 4         | 0.87%   |
| 251-300        | 4         | 0.87%   |
| 151-200        | 4         | 0.87%   |
| 141-150        | 4         | 0.87%   |
| 131-140        | 4         | 0.87%   |
| 41-50          | 3         | 0.65%   |
| More than 1000 | 2         | 0.43%   |
| 501-1000       | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 201       | 45.27%  |
| 101-120       | 116       | 26.13%  |
| 51-100        | 63        | 14.19%  |
| 161-240       | 38        | 8.56%   |
| More than 240 | 16        | 3.6%    |
| Unknown       | 8         | 1.8%    |
| 1-50          | 2         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 309       | 76.87%  |
| 2     | 64        | 15.92%  |
| 3     | 15        | 3.73%   |
| 0     | 13        | 3.23%   |
| 4     | 1         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 229       | 36.58%  |
| Realtek Semiconductor             | 194       | 30.99%  |
| Qualcomm Atheros                  | 70        | 11.18%  |
| Broadcom                          | 43        | 6.87%   |
| MediaTek                          | 12        | 1.92%   |
| Nvidia                            | 9         | 1.44%   |
| Broadcom Limited                  | 9         | 1.44%   |
| Ralink Technology                 | 7         | 1.12%   |
| Marvell Technology Group          | 6         | 0.96%   |
| Lenovo                            | 5         | 0.8%    |
| Ericsson Business Mobile Networks | 5         | 0.8%    |
| ASIX Electronics                  | 5         | 0.8%    |
| Samsung Electronics               | 4         | 0.64%   |
| Xiaomi                            | 3         | 0.48%   |
| Ralink                            | 3         | 0.48%   |
| DisplayLink                       | 3         | 0.48%   |
| Qualcomm                          | 2         | 0.32%   |
| Microsoft                         | 2         | 0.32%   |
| Dell                              | 2         | 0.32%   |
| Xilinx                            | 1         | 0.16%   |
| TP-Link                           | 1         | 0.16%   |
| Toshiba                           | 1         | 0.16%   |
| T & A Mobile Phones               | 1         | 0.16%   |
| Sierra Wireless                   | 1         | 0.16%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.16%   |
| NetGear                           | 1         | 0.16%   |
| LSI                               | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Bose                              | 1         | 0.16%   |
| Apple                             | 1         | 0.16%   |
| 3Com                              | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 105       | 13.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 34        | 4.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 25        | 3.32%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 21        | 2.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 2.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 2.52%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.26%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 2.12%   |
| Intel Wireless 7260                                                     | 15        | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.73%   |
| Intel Wireless 8260                                                     | 12        | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.06%   |
| Intel Ethernet Connection I218-LM                                       | 8         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.93%   |
| Intel Wireless 3165                                                     | 7         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.93%   |
| Nvidia MCP79 Ethernet                                                   | 6         | 0.8%    |
| Intel Wireless 7265                                                     | 6         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.8%    |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.53%   |
| Intel Wireless 3160                                                     | 4         | 0.53%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 4         | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 223       | 54.39%  |
| Qualcomm Atheros                  | 62        | 15.12%  |
| Realtek Semiconductor             | 55        | 13.41%  |
| Broadcom                          | 34        | 8.29%   |
| MediaTek                          | 12        | 2.93%   |
| Ralink Technology                 | 7         | 1.71%   |
| Ralink                            | 3         | 0.73%   |
| Broadcom Limited                  | 3         | 0.73%   |
| Qualcomm                          | 2         | 0.49%   |
| Ericsson Business Mobile Networks | 2         | 0.49%   |
| Dell                              | 2         | 0.49%   |
| TP-Link                           | 1         | 0.24%   |
| Sierra Wireless                   | 1         | 0.24%   |
| NetGear                           | 1         | 0.24%   |
| Microsoft                         | 1         | 0.24%   |
| Apple                             | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 22        | 5.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 4.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 4.61%   |
| Intel Wireless 8265 / 8275                                              | 17        | 4.13%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 3.88%   |
| Intel Wireless 7260                                                     | 15        | 3.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.16%   |
| Intel Wireless 8260                                                     | 12        | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 2.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.7%    |
| Intel Wireless 3165                                                     | 7         | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.7%    |
| Intel Wireless 7265                                                     | 6         | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.46%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.97%   |
| Intel Wireless 3160                                                     | 4         | 0.97%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 4         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.73%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.73%   |
| Intel WiFi Link 5100                                                    | 3         | 0.73%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 169       | 51.68%  |
| Intel                         | 83        | 25.38%  |
| Qualcomm Atheros              | 16        | 4.89%   |
| Broadcom                      | 13        | 3.98%   |
| Nvidia                        | 9         | 2.75%   |
| Broadcom Limited              | 7         | 2.14%   |
| Marvell Technology Group      | 6         | 1.83%   |
| Lenovo                        | 5         | 1.53%   |
| ASIX Electronics              | 5         | 1.53%   |
| Xiaomi                        | 3         | 0.92%   |
| DisplayLink                   | 3         | 0.92%   |
| Samsung Electronics           | 2         | 0.61%   |
| Xilinx                        | 1         | 0.31%   |
| T & A Mobile Phones           | 1         | 0.31%   |
| OnePlus Technology (Shenzhen) | 1         | 0.31%   |
| Microsoft                     | 1         | 0.31%   |
| ICS Advent                    | 1         | 0.31%   |
| 3Com                          | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 105       | 31.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 10.3%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 7.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 6.36%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 2.42%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 1.21%   |
| Intel Ethernet Connection I219-V                                  | 4         | 1.21%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.21%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.91%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.91%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.91%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.61%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.61%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.61%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.61%   |
| Xilinx Ethernet controller                                        | 1         | 0.3%    |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.3%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 387       | 54.74%  |
| Ethernet | 309       | 43.71%  |
| Modem    | 11        | 1.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 316       | 77.64%  |
| Ethernet | 91        | 22.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 273       | 69.82%  |
| 1     | 112       | 28.64%  |
| 3     | 3         | 0.77%   |
| 0     | 3         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 329       | 82.87%  |
| Yes  | 68        | 17.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 172       | 54.6%   |
| Realtek Semiconductor           | 30        | 9.52%   |
| Qualcomm Atheros Communications | 19        | 6.03%   |
| IMC Networks                    | 19        | 6.03%   |
| Lite-On Technology              | 17        | 5.4%    |
| Broadcom                        | 17        | 5.4%    |
| Foxconn / Hon Hai               | 7         | 2.22%   |
| Dell                            | 7         | 2.22%   |
| Apple                           | 7         | 2.22%   |
| Hewlett-Packard                 | 5         | 1.59%   |
| Toshiba                         | 4         | 1.27%   |
| Realtek                         | 4         | 1.27%   |
| Cambridge Silicon Radio         | 3         | 0.95%   |
| Foxconn International           | 2         | 0.63%   |
| Ralink                          | 1         | 0.32%   |
| ASUSTek Computer                | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 64        | 20.32%  |
| Intel AX201 Bluetooth                               | 38        | 12.06%  |
| Realtek Bluetooth Radio                             | 23        | 7.3%    |
| Intel AX200 Bluetooth                               | 21        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 6.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 3.81%   |
| Intel Bluetooth Device                              | 10        | 3.17%   |
| IMC Networks Bluetooth Radio                        | 10        | 3.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 2.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 2.22%   |
| Intel AX210 Bluetooth                               | 6         | 1.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.59%   |
| IMC Networks Wireless_Device                        | 5         | 1.59%   |
| Apple Bluetooth Host Controller                     | 5         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.27%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.95%   |
| Lite-On Wireless_Device                             | 3         | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.95%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.95%   |
| Toshiba Bluetooth Device                            | 2         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.63%   |
| IMC Networks Bluetooth Device                       | 2         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.63%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.63%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.32%   |
| Toshiba BCM43142A0                                  | 1         | 0.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 305       | 61.12%  |
| AMD                    | 77        | 15.43%  |
| Nvidia                 | 73        | 14.63%  |
| Realtek Semiconductor  | 12        | 2.4%    |
| Plantronics            | 7         | 1.4%    |
| GN Netcom              | 5         | 1%      |
| Logitech               | 3         | 0.6%    |
| Lenovo                 | 3         | 0.6%    |
| RODE Microphones       | 2         | 0.4%    |
| C-Media Electronics    | 2         | 0.4%    |
| VIA Technologies       | 1         | 0.2%    |
| Sony                   | 1         | 0.2%    |
| No brand               | 1         | 0.2%    |
| Kingston Technology    | 1         | 0.2%    |
| Huawei Technologies    | 1         | 0.2%    |
| Generalplus Technology | 1         | 0.2%    |
| ESS Technology         | 1         | 0.2%    |
| Creative Technology    | 1         | 0.2%    |
| Conexant Systems       | 1         | 0.2%    |
| AUDIOLAB               | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 8.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 42        | 7.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 5.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 4.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 3.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 2.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 2.21%   |
| Realtek Semiconductor USB Audio                                                                   | 12        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 1.87%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.36%   |
| Plantronics Poly Voyager Focus 2 Series                                                           | 7         | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.19%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 1.19%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.19%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 7         | 1.19%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 70        | 28.69%  |
| SK hynix            | 59        | 24.18%  |
| Micron Technology   | 29        | 11.89%  |
| Kingston            | 20        | 8.2%    |
| Unknown             | 16        | 6.56%   |
| Crucial             | 14        | 5.74%   |
| Ramaxel Technology  | 7         | 2.87%   |
| Corsair             | 7         | 2.87%   |
| Elpida              | 5         | 2.05%   |
| Nanya Technology    | 4         | 1.64%   |
| Unknown (ABCD)      | 3         | 1.23%   |
| Transcend           | 1         | 0.41%   |
| Silicon Power       | 1         | 0.41%   |
| SHARETRONIC         | 1         | 0.41%   |
| Patriot             | 1         | 0.41%   |
| G.Skill             | 1         | 0.41%   |
| CSX                 | 1         | 0.41%   |
| Apacer              | 1         | 0.41%   |
| A Force             | 1         | 0.41%   |
| 4ea5                | 1         | 0.41%   |
| Unknown             | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 3.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 2.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 2.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.18%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.18%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 1.18%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 3         | 1.18%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.78%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.78%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.78%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.78%   |
| Ramaxel RAM RMSA3230KE68H9F2133 4GB SODIMM DDR4 2133MT/s         | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.78%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s              | 2         | 0.78%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.78%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.39%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 108       | 51.67%  |
| DDR3    | 53        | 25.36%  |
| LPDDR4  | 16        | 7.66%   |
| DDR2    | 10        | 4.78%   |
| LPDDR3  | 6         | 2.87%   |
| SDRAM   | 5         | 2.39%   |
| LPDDR5  | 3         | 1.44%   |
| DDR5    | 3         | 1.44%   |
| DRAM    | 2         | 0.96%   |
| DDR     | 2         | 0.96%   |
| Unknown | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 183       | 85.92%  |
| Row Of Chips | 24        | 11.27%  |
| Chip         | 4         | 1.88%   |
| Unknown      | 2         | 0.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 89        | 39.04%  |
| 4096  | 62        | 27.19%  |
| 16384 | 36        | 15.79%  |
| 2048  | 24        | 10.53%  |
| 32768 | 8         | 3.51%   |
| 1024  | 7         | 3.07%   |
| 256   | 1         | 0.44%   |
| 128   | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 42        | 18.58%  |
| 2667    | 39        | 17.26%  |
| 1600    | 37        | 16.37%  |
| 2400    | 18        | 7.96%   |
| 2133    | 16        | 7.08%   |
| 1334    | 10        | 4.42%   |
| 4267    | 8         | 3.54%   |
| 3266    | 8         | 3.54%   |
| 1333    | 6         | 2.65%   |
| 800     | 6         | 2.65%   |
| 667     | 6         | 2.65%   |
| 1067    | 5         | 2.21%   |
| 8400    | 3         | 1.33%   |
| 6400    | 3         | 1.33%   |
| 4800    | 3         | 1.33%   |
| 4266    | 3         | 1.33%   |
| 1867    | 3         | 1.33%   |
| 4199    | 2         | 0.88%   |
| 2048    | 2         | 0.88%   |
| 975     | 2         | 0.88%   |
| Unknown | 2         | 0.88%   |
| 2267    | 1         | 0.44%   |
| 533     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| STMicroelectronics | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 50%     |
| Brother HL-L2340D series                                  | 1         | 50%     |

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
| Chicony Electronics                    | 88        | 24.93%  |
| Realtek Semiconductor                  | 40        | 11.33%  |
| Microdia                               | 38        | 10.76%  |
| IMC Networks                           | 37        | 10.48%  |
| Bison Electronics                      | 24        | 6.8%    |
| Sunplus Innovation Technology          | 23        | 6.52%   |
| Quanta                                 | 19        | 5.38%   |
| Apple                                  | 9         | 2.55%   |
| Logitech                               | 8         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.27%   |
| Suyin                                  | 6         | 1.7%    |
| Samsung Electronics                    | 6         | 1.7%    |
| Acer                                   | 6         | 1.7%    |
| Ricoh                                  | 5         | 1.42%   |
| Lite-On Technology                     | 5         | 1.42%   |
| ALi                                    | 5         | 1.42%   |
| Syntek                                 | 4         | 1.13%   |
| Silicon Motion                         | 4         | 1.13%   |
| SunplusIT                              | 2         | 0.57%   |
| Sonix Technology                       | 2         | 0.57%   |
| Microsoft                              | 2         | 0.57%   |
| Lenovo                                 | 2         | 0.57%   |
| Alcor Micro                            | 2         | 0.57%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| Y Media                                | 1         | 0.28%   |
| Trust                                  | 1         | 0.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.28%   |
| Nokia Mobile Phones                    | 1         | 0.28%   |
| Nikon                                  | 1         | 0.28%   |
| Luxvisions Innotech Limited            | 1         | 0.28%   |
| DigiTech                               | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 18        | 5.07%   |
| Chicony Integrated Camera               | 17        | 4.79%   |
| Realtek Integrated_Webcam_HD            | 15        | 4.23%   |
| IMC Networks Integrated Camera          | 13        | 3.66%   |
| Chicony HD WebCam                       | 9         | 2.54%   |
| Bison Integrated Camera                 | 9         | 2.54%   |
| Sunplus Integrated_Webcam_FHD           | 8         | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam       | 7         | 1.97%   |
| Chicony Chicony USB2.0 Camera           | 7         | 1.97%   |
| Sunplus Integrated_Webcam_HD            | 6         | 1.69%   |
| Samsung Galaxy series, misc. (MTP mode) | 6         | 1.69%   |
| Microdia Integrated Webcam              | 6         | 1.69%   |
| Apple Built-in iSight                   | 6         | 1.69%   |
| Lite-On HP HD Camera                    | 4         | 1.13%   |
| Chicony HP Wide Vision HD Camera        | 4         | 1.13%   |
| Bison EasyCamera                        | 4         | 1.13%   |
| Realtek USB2.0 HD UVC WebCam            | 3         | 0.85%   |
| Realtek USB Camera                      | 3         | 0.85%   |
| Realtek EasyCamera                      | 3         | 0.85%   |
| Quanta HD User Facing                   | 3         | 0.85%   |
| Quanta ACER HD User Facing              | 3         | 0.85%   |
| Microdia Webcam Vitade AF               | 3         | 0.85%   |
| Logitech HD Pro Webcam C920             | 3         | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 3         | 0.85%   |
| Chicony thinkpad t430s camera           | 3         | 0.85%   |
| Chicony Lenovo EasyCamera               | 3         | 0.85%   |
| Chicony Integrated Camera (1280x720@30) | 3         | 0.85%   |
| Chicony HP HD Camera                    | 3         | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 3         | 0.85%   |
| ALi WebCam                              | 3         | 0.85%   |
| Syntek Integrated Camera                | 2         | 0.56%   |
| Syntek EasyCamera                       | 2         | 0.56%   |
| Suyin HP Truevision HD                  | 2         | 0.56%   |
| SunplusIT 720p HD Camera                | 2         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD    | 2         | 0.56%   |
| Sunplus HP HD Webcam [Fixed]            | 2         | 0.56%   |
| Sunplus FHD Camera Microphone           | 2         | 0.56%   |
| Sonix USB2.0 FHD UVC WebCam             | 2         | 0.56%   |
| Ricoh Integrated Webcam                 | 2         | 0.56%   |
| Realtek Laptop_Integrated_Webcam_HD     | 2         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 24        | 32.88%  |
| Validity Sensors           | 21        | 28.77%  |
| Shenzhen Goodix Technology | 13        | 17.81%  |
| Upek                       | 4         | 5.48%   |
| AuthenTec                  | 4         | 5.48%   |
| Elan Microelectronics      | 3         | 4.11%   |
| LighTuning Technology      | 2         | 2.74%   |
| STMicroelectronics         | 1         | 1.37%   |
| Focal-systems.Corp         | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 6         | 8.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 6         | 8.22%   |
| Shenzhen Goodix FingerPrint                              | 6         | 8.22%   |
| Unknown                                                  | 5         | 6.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 4         | 5.48%   |
| Shenzhen Goodix  Fingerprint Device                      | 4         | 5.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 4.11%   |
| Synaptics Fingerprint reader [HP G6]                     | 3         | 4.11%   |
| Shenzhen Goodix Fingerprint Reader                       | 3         | 4.11%   |
| AuthenTec Fingerprint Sensor                             | 3         | 4.11%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 2.74%   |
| Validity Sensors VFS471 Fingerprint Reader               | 2         | 2.74%   |
| Validity Sensors VFS451 Fingerprint Reader               | 2         | 2.74%   |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 2.74%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 2         | 2.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 2.74%   |
| Elan ELAN:ARM-M4                                         | 2         | 2.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 1.37%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 1.37%   |
| Validity Sensors VFS300 Fingerprint Reader               | 1         | 1.37%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 1.37%   |
| Validity Sensors Synaptics WBDI                          | 1         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.37%   |
| Validity Sensors Fingerprint scanner                     | 1         | 1.37%   |
| Synaptics WBDI                                           | 1         | 1.37%   |
| Synaptics UWP WBDI Device                                | 1         | 1.37%   |
| Synaptics  WBDI                                          | 1         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.37%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.37%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 1.37%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 1.37%   |
| Elan ELAN:Fingerprint                                    | 1         | 1.37%   |
| AuthenTec AES2810                                        | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 33        | 62.26%  |
| Alcor Micro | 8         | 15.09%  |
| Upek        | 5         | 9.43%   |
| O2 Micro    | 5         | 9.43%   |
| Lenovo      | 2         | 3.77%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 15        | 28.3%   |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 15.09%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 15.09%  |
| Broadcom 5880                                                                | 6         | 11.32%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 9.43%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.77%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 221       | 54.98%  |
| 1     | 141       | 35.07%  |
| 2     | 34        | 8.46%   |
| 3     | 6         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 72        | 33.33%  |
| Chipcard                 | 47        | 21.76%  |
| Graphics card            | 39        | 18.06%  |
| Net/wireless             | 29        | 13.43%  |
| Camera                   | 8         | 3.7%    |
| Storage                  | 5         | 2.31%   |
| Multimedia controller    | 5         | 2.31%   |
| Communication controller | 4         | 1.85%   |
| Card reader              | 3         | 1.39%   |
| Bluetooth                | 3         | 1.39%   |
| Modem                    | 1         | 0.46%   |


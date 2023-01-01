Linux in Malaysia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Malaysia/Desktop/README.md) and [notebooks](/Location/Malaysia/Notebook/README.md).

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

Total: 507

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | A320M-DVS R4.0              | Desktop     | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Dell          | Latitude 5420               | Notebook    | [06dc453cbc](https://linux-hardware.org/?probe=06dc453cbc) | Dec 27, 2022 |
| HP            | Notebook                    | Notebook    | [8ba42c8ebc](https://linux-hardware.org/?probe=8ba42c8ebc) | Dec 27, 2022 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [44d3b06704](https://linux-hardware.org/?probe=44d3b06704) | Dec 23, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [fd4611b301](https://linux-hardware.org/?probe=fd4611b301) | Dec 21, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4efe19137d](https://linux-hardware.org/?probe=4efe19137d) | Dec 21, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [2b0d31db9d](https://linux-hardware.org/?probe=2b0d31db9d) | Dec 18, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [10a6f30aeb](https://linux-hardware.org/?probe=10a6f30aeb) | Dec 04, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [725404aadb](https://linux-hardware.org/?probe=725404aadb) | Dec 04, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| HP            | 2B2C                        | Desktop     | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [c92cd25690](https://linux-hardware.org/?probe=c92cd25690) | Nov 19, 2022 |
| HP            | 2B2C                        | Desktop     | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| Lenovo        | ThinkPad T450 20BUS1S81K    | Notebook    | [ee3fb9c9d2](https://linux-hardware.org/?probe=ee3fb9c9d2) | Nov 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1fef4a8aa5](https://linux-hardware.org/?probe=1fef4a8aa5) | Nov 13, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b39c12a9a4](https://linux-hardware.org/?probe=b39c12a9a4) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| NEC Comput... | PC-VK27MXZCG                | Notebook    | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [dcf74e5715](https://linux-hardware.org/?probe=dcf74e5715) | Oct 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [f514228295](https://linux-hardware.org/?probe=f514228295) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| ASUSTek       | UN65U                       | Mini pc     | [f0bab8d97c](https://linux-hardware.org/?probe=f0bab8d97c) | Oct 06, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| HP            | 2B2C                        | Desktop     | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | Notebook    | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3e5af3e86c](https://linux-hardware.org/?probe=3e5af3e86c) | Sep 25, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Alienware     | M14xR1                      | Notebook    | [a4064c0342](https://linux-hardware.org/?probe=a4064c0342) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [3162a68bf5](https://linux-hardware.org/?probe=3162a68bf5) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [d764e72d74](https://linux-hardware.org/?probe=d764e72d74) | Sep 12, 2022 |
| Alienware     | M14xR1                      | Notebook    | [ea2adf914b](https://linux-hardware.org/?probe=ea2adf914b) | Sep 10, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [25e7e97937](https://linux-hardware.org/?probe=25e7e97937) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9b0e2c480f](https://linux-hardware.org/?probe=9b0e2c480f) | Aug 28, 2022 |
| Alienware     | M14xR1                      | Notebook    | [498d5f5254](https://linux-hardware.org/?probe=498d5f5254) | Aug 27, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [398f6d4b78](https://linux-hardware.org/?probe=398f6d4b78) | Aug 25, 2022 |
| Dell          | 0PU052                      | Desktop     | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [23316377ee](https://linux-hardware.org/?probe=23316377ee) | Aug 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [9630e2d4f5](https://linux-hardware.org/?probe=9630e2d4f5) | Aug 21, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [ee6cfb6de5](https://linux-hardware.org/?probe=ee6cfb6de5) | Aug 19, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66a759db9c](https://linux-hardware.org/?probe=66a759db9c) | Aug 14, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Lenovo        | ThinkCentre M58 7359DHJ     | Desktop     | [46c2c1db62](https://linux-hardware.org/?probe=46c2c1db62) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [82b077a668](https://linux-hardware.org/?probe=82b077a668) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [616a2b7524](https://linux-hardware.org/?probe=616a2b7524) | Jul 12, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [71758de9e1](https://linux-hardware.org/?probe=71758de9e1) | Jul 06, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [5540b74d09](https://linux-hardware.org/?probe=5540b74d09) | Jul 03, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [c793608515](https://linux-hardware.org/?probe=c793608515) | Jul 03, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASUSTek       | K42Jc                       | Notebook    | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d525e0eb0c](https://linux-hardware.org/?probe=d525e0eb0c) | May 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0a9f8b0a4a](https://linux-hardware.org/?probe=0a9f8b0a4a) | May 09, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS           | Iris8                       | Desktop     | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Lenovo        | 30D9 NOK                    | Desktop     | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| Dell          | Precision 7730              | Notebook    | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar       | G41D3+                      | Desktop     | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle       | FH170                       | Desktop     | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | Notebook    | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP            | 2B44                        | Desktop     | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [eb4fb496ae](https://linux-hardware.org/?probe=eb4fb496ae) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek       | T200TA                      | Notebook    | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Lenovo        | U310                        | Notebook    | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | Notebook    | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Intel         | B75                         | Desktop     | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [ccd587fde5](https://linux-hardware.org/?probe=ccd587fde5) | Oct 21, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | Notebook    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | Notebook    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [17e78af479](https://linux-hardware.org/?probe=17e78af479) | Sep 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | Notebook    | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [acc6c11a97](https://linux-hardware.org/?probe=acc6c11a97) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| HP            | Notebook                    | Notebook    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | Notebook    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | Notebook    | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | Notebook    | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | Notebook    | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | Notebook    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | Notebook    | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| HP            | Notebook                    | Notebook    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| HP            | 0AA8h                       | Desktop     | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [6bb8ea7872](https://linux-hardware.org/?probe=6bb8ea7872) | Apr 23, 2021 |
| System76      | Galago Pro                  | Notebook    | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| HP            | 2B1C MVB,A                  | All in one  | [ea47f5adbe](https://linux-hardware.org/?probe=ea47f5adbe) | Apr 05, 2021 |
| Dell          | XPS L412Z                   | Notebook    | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| Sony          | VPCEA42EG                   | Notebook    | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | Notebook    | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | Notebook    | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | Notebook    | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | Notebook    | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | Notebook    | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| HP            | G42                         | Notebook    | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| HP            | Notebook                    | Notebook    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| HP            | Pavilion g4                 | Notebook    | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | Notebook    | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fa76a31b79](https://linux-hardware.org/?probe=fa76a31b79) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell          | 0PU052                      | Desktop     | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar       | A320MH                      | Desktop     | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [4d1d3b1722](https://linux-hardware.org/?probe=4d1d3b1722) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [400561434f](https://linux-hardware.org/?probe=400561434f) | Nov 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | Notebook    | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Gigabyte      | Z490 VISION D               | Desktop     | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| Acer          | TM4750                      | Notebook    | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | Notebook    | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | Notebook    | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a37736727](https://linux-hardware.org/?probe=1a37736727) | Oct 13, 2020 |
| Dell          | 06D7TR A02                  | Desktop     | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Sony          | VGN-Z27GN_X                 | Notebook    | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | Notebook    | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| Dell          | Inspiron 5482               | Convertible | [4085a729ac](https://linux-hardware.org/?probe=4085a729ac) | Sep 03, 2020 |
| Dell          | 0RW203                      | Desktop     | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | Notebook    | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Unknown       | Unknown                     | Phone       | [38378b572a](https://linux-hardware.org/?probe=38378b572a) | Aug 01, 2020 |
| HP            | Presario CQ43               | Notebook    | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | Notebook    | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7285               | Tablet      | [ed3aa05fd5](https://linux-hardware.org/?probe=ed3aa05fd5) | Jul 25, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [81e5774167](https://linux-hardware.org/?probe=81e5774167) | Jul 24, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [1856c4ccbf](https://linux-hardware.org/?probe=1856c4ccbf) | Jul 23, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Unknown       | Unknown                     | Phone       | [c0d8474803](https://linux-hardware.org/?probe=c0d8474803) | Jul 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [33534eca13](https://linux-hardware.org/?probe=33534eca13) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6ae79e439f](https://linux-hardware.org/?probe=6ae79e439f) | Jun 28, 2020 |
| Acer          | Aspire 4738                 | Notebook    | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | Notebook    | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| Unknown       | Unknown                     | Phone       | [6566b884d6](https://linux-hardware.org/?probe=6566b884d6) | Jun 15, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| HP            | 14                          | Notebook    | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [6c1d889b0d](https://linux-hardware.org/?probe=6c1d889b0d) | Jun 06, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [709dcae624](https://linux-hardware.org/?probe=709dcae624) | Jun 06, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer          | EQ45M                       | Desktop     | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| Dell          | 0PU052                      | Desktop     | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| SNS Networ... | JOI Book 150                | Notebook    | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4893a0cfcd](https://linux-hardware.org/?probe=4893a0cfcd) | May 06, 2020 |
| Dell          | 0RY007                      | Desktop     | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| HP            | 14                          | Notebook    | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| Acer          | EQ45M                       | Desktop     | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| BUSH          | Windows tablet              | Notebook    | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI           | B150M Night Elf             | Desktop     | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| Acer          | TM4750                      | Notebook    | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [46ad418d75](https://linux-hardware.org/?probe=46ad418d75) | Feb 24, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [c1b65d99ff](https://linux-hardware.org/?probe=c1b65d99ff) | Feb 23, 2020 |
| Teclast       | F5                          | Convertible | [23690a5a6e](https://linux-hardware.org/?probe=23690a5a6e) | Feb 16, 2020 |
| Acer          | Aspire 4736Z                | Notebook    | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP            | 3647h                       | Desktop     | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| ASUSTek       | P8Z77-M                     | Desktop     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Chuwi         | LapBook Pro                 | Notebook    | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | Notebook    | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | Notebook    | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | Notebook    | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| Supermicro    | K1SPE-IN001                 | Server      | [5f6d0233a8](https://linux-hardware.org/?probe=5f6d0233a8) | Nov 18, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| Dell          | Vostro V130                 | Notebook    | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | Notebook    | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| Acer          | Swift SF314-55G             | Notebook    | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | Notebook    | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP            | 0AA8h                       | Desktop     | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| HP            | ZBook 15                    | Notebook    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | Notebook    | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| Dell          | 0RY007                      | Desktop     | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| HP            | ProLiant DL60 Gen9          | Server      | [140daf886e](https://linux-hardware.org/?probe=140daf886e) | Jul 24, 2019 |
| ASUSTek       | H81M-C                      | Desktop     | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASUSTek       | X450CP                      | Notebook    | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | Notebook    | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| ASRock        | X79 Extreme9                | Desktop     | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| Dell          | XPS L521X                   | Notebook    | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | Notebook    | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| HP            | 2820h                       | Desktop     | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Malaysia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 60        | 15.96%  |
| Ubuntu 18.04                 | 24        | 6.38%   |
| Ubuntu 22.04                 | 11        | 2.93%   |
| OpenMandriva 4.2             | 11        | 2.93%   |
| Pop!_OS 20.10                | 10        | 2.66%   |
| OpenMandriva 4.3             | 10        | 2.66%   |
| Zorin 16                     | 9         | 2.39%   |
| Pop!_OS 21.04                | 9         | 2.39%   |
| OpenMandriva 4.50            | 9         | 2.39%   |
| KDE neon 20.04               | 9         | 2.39%   |
| Pop!_OS 20.04                | 8         | 2.13%   |
| Fedora 33                    | 8         | 2.13%   |
| Ubuntu 19.04                 | 7         | 1.86%   |
| Debian 11                    | 7         | 1.86%   |
| ArcoLinux Rolling            | 7         | 1.86%   |
| Pop!_OS 22.04                | 6         | 1.6%    |
| Linux Mint 19.3              | 6         | 1.6%    |
| Fedora 34                    | 6         | 1.6%    |
| Arch                         | 5         | 1.33%   |
| Zorin 15                     | 4         | 1.06%   |
| Ubuntu 21.04                 | 4         | 1.06%   |
| Ubuntu 20.10                 | 4         | 1.06%   |
| Ubuntu 19.10                 | 4         | 1.06%   |
| Ubuntu 16.04                 | 4         | 1.06%   |
| Manjaro                      | 4         | 1.06%   |
| Linux Mint 20.2              | 4         | 1.06%   |
| EndeavourOS Rolling          | 4         | 1.06%   |
| Elementary 5.1.7             | 4         | 1.06%   |
| Xubuntu 22.04                | 3         | 0.8%    |
| Xubuntu 18.04                | 3         | 0.8%    |
| Ubuntu 21.10                 | 3         | 0.8%    |
| Linux Mint 20.1              | 3         | 0.8%    |
| Fedora 37                    | 3         | 0.8%    |
| Elementary 6.1               | 3         | 0.8%    |
| Arch Rolling                 | 3         | 0.8%    |
| Android                      | 3         | 0.8%    |
| Ubuntu Unity 16.04           | 2         | 0.53%   |
| Ubuntu MATE 20.04            | 2         | 0.53%   |
| Pop!_OS 21.10                | 2         | 0.53%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 119       | 33.15%  |
| Pop!_OS           | 31        | 8.64%   |
| OpenMandriva      | 29        | 8.08%   |
| Fedora            | 22        | 6.13%   |
| Linux Mint        | 19        | 5.29%   |
| Zorin             | 14        | 3.9%    |
| Manjaro           | 13        | 3.62%   |
| KDE neon          | 12        | 3.34%   |
| Elementary        | 10        | 2.79%   |
| Debian            | 9         | 2.51%   |
| Endless           | 8         | 2.23%   |
| Arch              | 8         | 2.23%   |
| Xubuntu           | 7         | 1.95%   |
| ArcoLinux         | 7         | 1.95%   |
| Lubuntu           | 6         | 1.67%   |
| Kali              | 5         | 1.39%   |
| EndeavourOS       | 5         | 1.39%   |
| Kubuntu           | 4         | 1.11%   |
| CentOS            | 3         | 0.84%   |
| Android           | 3         | 0.84%   |
| Ubuntu Unity      | 2         | 0.56%   |
| Ubuntu MATE       | 2         | 0.56%   |
| Ubuntu Budgie     | 2         | 0.56%   |
| ROSA              | 2         | 0.56%   |
| openSUSE          | 2         | 0.56%   |
| Gentoo            | 2         | 0.56%   |
| Xero              | 1         | 0.28%   |
| Ultramarine Linux | 1         | 0.28%   |
| SteamOS           | 1         | 0.28%   |
| Rocky Linux       | 1         | 0.28%   |
| Reborn OS         | 1         | 0.28%   |
| Raspbian          | 1         | 0.28%   |
| Peppermint        | 1         | 0.28%   |
| MX                | 1         | 0.28%   |
| LMDE              | 1         | 0.28%   |
| Linux Lite        | 1         | 0.28%   |
| BuildRoot         | 1         | 0.28%   |
| Axyl              | 1         | 0.28%   |
| Archcraft         | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 10        | 2.49%   |
| 5.4.0-58-generic         | 8         | 2%      |
| 5.4.0-42-generic         | 8         | 2%      |
| 5.16.7-desktop-1omv4003  | 8         | 2%      |
| 5.15.0-52-generic        | 6         | 1.5%    |
| 5.11.0-7620-generic      | 6         | 1.5%    |
| 5.12.4-desktop-1omv4050  | 5         | 1.25%   |
| 5.11.0-27-generic        | 5         | 1.25%   |
| 5.4.0-7634-generic       | 4         | 1%      |
| 5.4.0-40-generic         | 4         | 1%      |
| 5.15.0-56-generic        | 4         | 1%      |
| 5.0.0-37-generic         | 4         | 1%      |
| 5.8.0-7642-generic       | 3         | 0.75%   |
| 5.8.0-7630-generic       | 3         | 0.75%   |
| 5.4.0-54-generic         | 3         | 0.75%   |
| 5.4.0-52-generic         | 3         | 0.75%   |
| 5.4.0-48-generic         | 3         | 0.75%   |
| 5.4.0-37-generic         | 3         | 0.75%   |
| 5.3.0-53-generic         | 3         | 0.75%   |
| 5.3.0-46-generic         | 3         | 0.75%   |
| 5.16.3-desktop-2omv4050  | 3         | 0.75%   |
| 5.15.0-46-generic        | 3         | 0.75%   |
| 5.15.0-40-generic        | 3         | 0.75%   |
| 5.15.0-39-generic        | 3         | 0.75%   |
| 5.13.0-7614-generic      | 3         | 0.75%   |
| 5.13.0-22-generic        | 3         | 0.75%   |
| 5.11.0-7614-generic      | 3         | 0.75%   |
| 5.11.0-46-generic        | 3         | 0.75%   |
| 5.11.0-43-generic        | 3         | 0.75%   |
| 5.11.0-34-generic        | 3         | 0.75%   |
| 5.0.0-32-generic         | 3         | 0.75%   |
| 5.0.0-25-generic         | 3         | 0.75%   |
| 5.0.0-23-generic         | 3         | 0.75%   |
| 4.15.0-76-generic        | 3         | 0.75%   |
| 4.15.0-45-generic        | 3         | 0.75%   |
| 5.9.0-kali1-amd64        | 2         | 0.5%    |
| 5.8.0-53-generic         | 2         | 0.5%    |
| 5.8.0-45-generic         | 2         | 0.5%    |
| 5.8.0-44-generic         | 2         | 0.5%    |
| 5.8.0-41-generic         | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 17.94%  |
| 5.11.0  | 30        | 7.92%   |
| 5.8.0   | 26        | 6.86%   |
| 5.15.0  | 26        | 6.86%   |
| 4.15.0  | 20        | 5.28%   |
| 5.3.0   | 19        | 5.01%   |
| 5.0.0   | 18        | 4.75%   |
| 5.13.0  | 17        | 4.49%   |
| 5.10.14 | 10        | 2.64%   |
| 5.16.7  | 8         | 2.11%   |
| 5.10.0  | 7         | 1.85%   |
| 4.18.0  | 6         | 1.58%   |
| 5.17.1  | 5         | 1.32%   |
| 5.12.4  | 5         | 1.32%   |
| 5.18.0  | 4         | 1.06%   |
| 5.9.0   | 3         | 0.79%   |
| 5.19.0  | 3         | 0.79%   |
| 5.16.3  | 3         | 0.79%   |
| 5.16.15 | 3         | 0.79%   |
| 6.0.12  | 2         | 0.53%   |
| 5.9.1   | 2         | 0.53%   |
| 5.19.9  | 2         | 0.53%   |
| 5.17.6  | 2         | 0.53%   |
| 5.17.5  | 2         | 0.53%   |
| 5.15.35 | 2         | 0.53%   |
| 5.14.18 | 2         | 0.53%   |
| 5.14.0  | 2         | 0.53%   |
| 5.13.13 | 2         | 0.53%   |
| 5.12.9  | 2         | 0.53%   |
| 5.12.7  | 2         | 0.53%   |
| 5.12.15 | 2         | 0.53%   |
| 5.11.18 | 2         | 0.53%   |
| 5.10.79 | 2         | 0.53%   |
| 5.10.42 | 2         | 0.53%   |
| 5.10.13 | 2         | 0.53%   |
| 4.4.0   | 2         | 0.53%   |
| 6.1.1   | 1         | 0.26%   |
| 6.0.9   | 1         | 0.26%   |
| 6.0.3   | 1         | 0.26%   |
| 6.0.15  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 18.13%  |
| 5.15    | 36        | 9.6%    |
| 5.11    | 35        | 9.33%   |
| 5.8     | 33        | 8.8%    |
| 5.10    | 27        | 7.2%    |
| 5.13    | 20        | 5.33%   |
| 4.15    | 20        | 5.33%   |
| 5.3     | 19        | 5.07%   |
| 5.0     | 18        | 4.8%    |
| 5.16    | 16        | 4.27%   |
| 5.12    | 13        | 3.47%   |
| 5.19    | 9         | 2.4%    |
| 5.18    | 9         | 2.4%    |
| 5.17    | 9         | 2.4%    |
| 5.9     | 8         | 2.13%   |
| 5.14    | 8         | 2.13%   |
| 6.0     | 6         | 1.6%    |
| 4.18    | 6         | 1.6%    |
| 5.7     | 2         | 0.53%   |
| 5.6     | 2         | 0.53%   |
| 4.4     | 2         | 0.53%   |
| 3.18    | 2         | 0.53%   |
| 3.10    | 2         | 0.53%   |
| 6.1     | 1         | 0.27%   |
| 4.9     | 1         | 0.27%   |
| 4.19    | 1         | 0.27%   |
| 4.10    | 1         | 0.27%   |
| 4.1     | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 333       | 97.08%  |
| i686   | 5         | 1.46%   |
| armv8l | 3         | 0.87%   |
| armv7l | 2         | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 165       | 46.22%  |
| KDE5          | 58        | 16.25%  |
| Unknown       | 40        | 11.2%   |
| XFCE          | 25        | 7%      |
| X-Cinnamon    | 16        | 4.48%   |
| KDE           | 12        | 3.36%   |
| Pantheon      | 10        | 2.8%    |
| MATE          | 10        | 2.8%    |
| LXQt          | 5         | 1.4%    |
| openbox       | 4         | 1.12%   |
| Unity         | 2         | 0.56%   |
| LXDE          | 2         | 0.56%   |
| GNOME Classic | 2         | 0.56%   |
| Budgie        | 2         | 0.56%   |
| Peppermint    | 1         | 0.28%   |
| i3            | 1         | 0.28%   |
| Cinnamon      | 1         | 0.28%   |
| bspwm         | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 283       | 80.17%  |
| Wayland | 42        | 11.9%   |
| Unknown | 20        | 5.67%   |
| Tty     | 8         | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 204       | 57.79%  |
| SDDM    | 58        | 16.43%  |
| GDM     | 32        | 9.07%   |
| GDM3    | 29        | 8.22%   |
| LightDM | 23        | 6.52%   |
| TDM     | 5         | 1.42%   |
| LXDM    | 2         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 262       | 75.29%  |
| Unknown | 31        | 8.91%   |
| en_GB   | 25        | 7.18%   |
| en_SG   | 15        | 4.31%   |
| en_AU   | 3         | 0.86%   |
| C       | 3         | 0.86%   |
| zh_CN   | 2         | 0.57%   |
| ms_MY   | 2         | 0.57%   |
| en_MY   | 2         | 0.57%   |
| ja_JP   | 1         | 0.29%   |
| id_ID   | 1         | 0.29%   |
| en_HK   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 191       | 55.04%  |
| EFI  | 156       | 44.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 271       | 77.43%  |
| Overlay | 26        | 7.43%   |
| Btrfs   | 23        | 6.57%   |
| Unknown | 12        | 3.43%   |
| Xfs     | 8         | 2.29%   |
| Zfs     | 7         | 2%      |
| Ext2    | 2         | 0.57%   |
| Ext3    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 213       | 61.21%  |
| GPT     | 87        | 25%     |
| MBR     | 48        | 13.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 287       | 82.23%  |
| Yes       | 62        | 17.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 238       | 68.19%  |
| Yes       | 111       | 31.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 66        | 19.24%  |
| Dell                    | 63        | 18.37%  |
| Hewlett-Packard         | 45        | 13.12%  |
| Lenovo                  | 32        | 9.33%   |
| Gigabyte Technology     | 24        | 7%      |
| Acer                    | 21        | 6.12%   |
| MSI                     | 20        | 5.83%   |
| Intel                   | 15        | 4.37%   |
| Apple                   | 7         | 2.04%   |
| Biostar                 | 5         | 1.46%   |
| ASRock                  | 5         | 1.46%   |
| Unknown                 | 5         | 1.46%   |
| Sony                    | 4         | 1.17%   |
| Fujitsu                 | 3         | 0.87%   |
| Raspberry Pi Foundation | 2         | 0.58%   |
| ILLEGEAR                | 2         | 0.58%   |
| HUAWEI                  | 2         | 0.58%   |
| ECS                     | 2         | 0.58%   |
| Acidanthera             | 2         | 0.58%   |
| Vorke                   | 1         | 0.29%   |
| Toshiba                 | 1         | 0.29%   |
| Timi                    | 1         | 0.29%   |
| Teclast                 | 1         | 0.29%   |
| System76                | 1         | 0.29%   |
| Supermicro              | 1         | 0.29%   |
| SNS Network (M)         | 1         | 0.29%   |
| Shuttle                 | 1         | 0.29%   |
| Seco                    | 1         | 0.29%   |
| ONDA                    | 1         | 0.29%   |
| NEC Computers           | 1         | 0.29%   |
| HONOR                   | 1         | 0.29%   |
| GPD                     | 1         | 0.29%   |
| Chuwi                   | 1         | 0.29%   |
| BUSH                    | 1         | 0.29%   |
| AZW                     | 1         | 0.29%   |
| AMI                     | 1         | 0.29%   |
| Alienware               | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel DH61WW AAG23116-204         | 7         | 2.04%   |
| ASUS All Series                   | 6         | 1.75%   |
| Unknown                           | 5         | 1.46%   |
| HP Notebook                       | 4         | 1.17%   |
| Gigabyte B85M-D3H                 | 4         | 1.17%   |
| MSI MS-7C52                       | 3         | 0.87%   |
| MSI MS-7817                       | 3         | 0.87%   |
| Intel DH61WW AAG23116-300         | 3         | 0.87%   |
| Dell OptiPlex 755                 | 3         | 0.87%   |
| MSI MS-7C81                       | 2         | 0.58%   |
| MSI MS-7B89                       | 2         | 0.58%   |
| MSI Modern 14 B5M                 | 2         | 0.58%   |
| Intel MAHOBAY                     | 2         | 0.58%   |
| HP Pavilion dv6                   | 2         | 0.58%   |
| HP Laptop 15-bs0xx                | 2         | 0.58%   |
| HP EliteBook 8470p                | 2         | 0.58%   |
| HP Compaq Presario CQ40           | 2         | 0.58%   |
| Gigabyte B450M S2H                | 2         | 0.58%   |
| Dell XPS 8940                     | 2         | 0.58%   |
| Dell XPS 15 7590                  | 2         | 0.58%   |
| Dell OptiPlex 990                 | 2         | 0.58%   |
| Dell Latitude E6520               | 2         | 0.58%   |
| Dell Latitude E6440               | 2         | 0.58%   |
| Biostar G41D3C                    | 2         | 0.58%   |
| ASUS P8Z77-V LX                   | 2         | 0.58%   |
| ASUS K45VD                        | 2         | 0.58%   |
| ASUS K43SD                        | 2         | 0.58%   |
| Apple MacBookPro8,1               | 2         | 0.58%   |
| Vorke V1 Plus                     | 1         | 0.29%   |
| Toshiba dynabook Satellite B552/H | 1         | 0.29%   |
| Timi RedmiBook 14 II              | 1         | 0.29%   |
| Teclast F5                        | 1         | 0.29%   |
| System76 Galago Pro               | 1         | 0.29%   |
| Supermicro PIO-5038K-I-IN001      | 1         | 0.29%   |
| Sony VPCSB26FG                    | 1         | 0.29%   |
| Sony VPCEG16EG                    | 1         | 0.29%   |
| Sony VPCEA42EG                    | 1         | 0.29%   |
| Sony VGN-Z27GN_X                  | 1         | 0.29%   |
| SNS Network (M) JOI Book 150      | 1         | 0.29%   |
| Shuttle DH170                     | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 18        | 5.25%   |
| Dell Inspiron       | 17        | 4.96%   |
| Lenovo ThinkPad     | 13        | 3.79%   |
| Acer Aspire         | 13        | 3.79%   |
| Intel DH61WW        | 10        | 2.92%   |
| Dell OptiPlex       | 9         | 2.62%   |
| HP Pavilion         | 8         | 2.33%   |
| HP Compaq           | 8         | 2.33%   |
| Dell XPS            | 8         | 2.33%   |
| Dell Precision      | 7         | 2.04%   |
| HP EliteBook        | 6         | 1.75%   |
| ASUS All            | 6         | 1.75%   |
| HP Laptop           | 5         | 1.46%   |
| Unknown             | 5         | 1.46%   |
| HP Notebook         | 4         | 1.17%   |
| Gigabyte B85M-D3H   | 4         | 1.17%   |
| ASUS VivoBook       | 4         | 1.17%   |
| ASUS TUF            | 4         | 1.17%   |
| ASUS ROG            | 4         | 1.17%   |
| MSI MS-7C52         | 3         | 0.87%   |
| MSI MS-7817         | 3         | 0.87%   |
| Lenovo ThinkStation | 3         | 0.87%   |
| Lenovo ThinkCentre  | 3         | 0.87%   |
| Lenovo IdeaPad      | 3         | 0.87%   |
| Gigabyte X570       | 3         | 0.87%   |
| Gigabyte B450M      | 3         | 0.87%   |
| Fujitsu LIFEBOOK    | 3         | 0.87%   |
| ASUS P8B75-M        | 3         | 0.87%   |
| Apple MacBookPro8   | 3         | 0.87%   |
| RPi Raspberry       | 2         | 0.58%   |
| MSI MS-7C81         | 2         | 0.58%   |
| MSI MS-7B89         | 2         | 0.58%   |
| MSI Modern          | 2         | 0.58%   |
| Lenovo Yoga         | 2         | 0.58%   |
| Intel MAHOBAY       | 2         | 0.58%   |
| HP ProBook          | 2         | 0.58%   |
| Biostar G41D3C      | 2         | 0.58%   |
| ASUS PRIME          | 2         | 0.58%   |
| ASUS P8Z77-V        | 2         | 0.58%   |
| ASUS K45VD          | 2         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 41        | 11.95%  |
| 2013    | 35        | 10.2%   |
| 2019    | 32        | 9.33%   |
| 2018    | 30        | 8.75%   |
| 2020    | 27        | 7.87%   |
| 2012    | 27        | 7.87%   |
| 2021    | 25        | 7.29%   |
| 2015    | 20        | 5.83%   |
| 2017    | 19        | 5.54%   |
| 2010    | 19        | 5.54%   |
| 2014    | 14        | 4.08%   |
| 2008    | 14        | 4.08%   |
| 2009    | 12        | 3.5%    |
| 2016    | 10        | 2.92%   |
| 2007    | 9         | 2.62%   |
| 2022    | 4         | 1.17%   |
| Unknown | 4         | 1.17%   |
| 2006    | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 182       | 53.06%  |
| Desktop        | 132       | 38.48%  |
| Convertible    | 8         | 2.33%   |
| All in one     | 6         | 1.75%   |
| Tablet         | 4         | 1.17%   |
| Phone          | 3         | 0.87%   |
| Mini pc        | 3         | 0.87%   |
| Server         | 3         | 0.87%   |
| System on chip | 2         | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 321       | 93.59%  |
| Enabled  | 22        | 6.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 341       | 99.42%  |
| Yes  | 2         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 77        | 22.25%  |
| 3.01-4.0    | 72        | 20.81%  |
| 8.01-16.0   | 68        | 19.65%  |
| 16.01-24.0  | 62        | 17.92%  |
| 32.01-64.0  | 27        | 7.8%    |
| 1.01-2.0    | 17        | 4.91%   |
| 64.01-256.0 | 9         | 2.6%    |
| 2.01-3.0    | 7         | 2.02%   |
| 24.01-32.0  | 5         | 1.45%   |
| 0.51-1.0    | 2         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 128       | 33.77%  |
| 2.01-3.0   | 110       | 29.02%  |
| 3.01-4.0   | 54        | 14.25%  |
| 4.01-8.0   | 38        | 10.03%  |
| 0.51-1.0   | 29        | 7.65%   |
| 8.01-16.0  | 13        | 3.43%   |
| 0.01-0.5   | 4         | 1.06%   |
| 32.01-64.0 | 1         | 0.26%   |
| 24.01-32.0 | 1         | 0.26%   |
| Unknown    | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 199       | 56.53%  |
| 2      | 101       | 28.69%  |
| 3      | 23        | 6.53%   |
| 4      | 13        | 3.69%   |
| 5      | 8         | 2.27%   |
| 7      | 3         | 0.85%   |
| 6      | 3         | 0.85%   |
| 8      | 2         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 62.5%   |
| Yes       | 129       | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 289       | 84.26%  |
| No        | 54        | 15.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 280       | 81.16%  |
| No        | 65        | 18.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 62.9%   |
| No        | 128       | 37.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Malaysia | 343       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 124       | 33.6%   |
| Petaling Jaya          | 42        | 11.38%  |
| Shah Alam              | 14        | 3.79%   |
| Puchong Batu Dua Belas | 14        | 3.79%   |
| Johor Bahru            | 13        | 3.52%   |
| Sungai Buloh           | 9         | 2.44%   |
| Subang Jaya            | 9         | 2.44%   |
| George Town            | 9         | 2.44%   |
| Seremban               | 8         | 2.17%   |
| Ipoh                   | 8         | 2.17%   |
| Malacca                | 7         | 1.9%    |
| Kota Kinabalu          | 7         | 1.9%    |
| Kota Bharu             | 7         | 1.9%    |
| Kajang                 | 7         | 1.9%    |
| Kulim                  | 5         | 1.36%   |
| Tawau                  | 4         | 1.08%   |
| Skudai                 | 4         | 1.08%   |
| Marabu                 | 4         | 1.08%   |
| Kulai                  | 4         | 1.08%   |
| Kuching                | 4         | 1.08%   |
| Klang                  | 4         | 1.08%   |
| Cyberjaya              | 4         | 1.08%   |
| Butterworth            | 4         | 1.08%   |
| Ampang                 | 4         | 1.08%   |
| Sungai Petani          | 3         | 0.81%   |
| Seri Kembangan         | 3         | 0.81%   |
| Putrajaya              | 3         | 0.81%   |
| Cheras                 | 3         | 0.81%   |
| Bayan Lepas            | 3         | 0.81%   |
| Rawang                 | 2         | 0.54%   |
| Nibong Tebal           | 2         | 0.54%   |
| Long Seridan           | 2         | 0.54%   |
| Bukit Mertajam         | 2         | 0.54%   |
| Ayer Itam              | 2         | 0.54%   |
| Alor Star              | 2         | 0.54%   |
| Taiping                | 1         | 0.27%   |
| Sibu                   | 1         | 0.27%   |
| Sepang                 | 1         | 0.27%   |
| Semenyih               | 1         | 0.27%   |
| Penampang              | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 96        | 128    | 18.01%  |
| WDC                         | 84        | 141    | 15.76%  |
| Kingston                    | 46        | 62     | 8.63%   |
| Samsung Electronics         | 45        | 65     | 8.44%   |
| Toshiba                     | 38        | 46     | 7.13%   |
| Unknown                     | 23        | 31     | 4.32%   |
| SanDisk                     | 20        | 27     | 3.75%   |
| HGST                        | 16        | 19     | 3%      |
| Intel                       | 14        | 18     | 2.63%   |
| A-DATA Technology           | 12        | 15     | 2.25%   |
| Crucial                     | 11        | 18     | 2.06%   |
| Apacer                      | 10        | 14     | 1.88%   |
| SK hynix                    | 8         | 8      | 1.5%    |
| Phison                      | 7         | 10     | 1.31%   |
| Micron Technology           | 7         | 11     | 1.31%   |
| KIOXIA                      | 7         | 8      | 1.31%   |
| Hitachi                     | 6         | 10     | 1.13%   |
| China                       | 6         | 6      | 1.13%   |
| Transcend                   | 5         | 6      | 0.94%   |
| PNY                         | 5         | 5      | 0.94%   |
| TO Exter                    | 4         | 6      | 0.75%   |
| Silicon Motion              | 4         | 5      | 0.75%   |
| Patriot                     | 4         | 5      | 0.75%   |
| Hewlett-Packard             | 4         | 4      | 0.75%   |
| SPCC                        | 3         | 4      | 0.56%   |
| Kingston Technology Company | 3         | 3      | 0.56%   |
| XPG                         | 2         | 3      | 0.38%   |
| Verbatim                    | 2         | 2      | 0.38%   |
| Plextor                     | 2         | 2      | 0.38%   |
| Phison Electronics          | 2         | 2      | 0.38%   |
| KIOXIA-EXCERIA              | 2         | 4      | 0.38%   |
| Kingchuxing                 | 2         | 2      | 0.38%   |
| Gigabyte Technology         | 2         | 2      | 0.38%   |
| Fujitsu                     | 2         | 2      | 0.38%   |
| External                    | 2         | 2      | 0.38%   |
| Colorful                    | 2         | 2      | 0.38%   |
| AGI                         | 2         | 3      | 0.38%   |
| winstar                     | 1         | 1      | 0.19%   |
| USB3.0                      | 1         | 1      | 0.19%   |
| Teclast                     | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 13        | 2.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 6         | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6         | 1.02%   |
| Crucial CT500MX500SSD1 500GB                        | 6         | 1.02%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 5         | 0.85%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 5         | 0.85%   |
| Unknown MMC Card  32GB                              | 5         | 0.85%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 0.85%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 0.85%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.85%   |
| Seagate ST380815AS 80GB                             | 5         | 0.85%   |
| Samsung HD103SJ 1TB                                 | 5         | 0.85%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.85%   |
| Apacer AS340 120GB SSD                              | 5         | 0.85%   |
| TO Exter nal USB 3.0 512GB                          | 4         | 0.68%   |
| Seagate ST500DM002-1BC142 500GB                     | 4         | 0.68%   |
| Seagate ST3160815AS 160GB                           | 4         | 0.68%   |
| SanDisk SSD PLUS 240GB                              | 4         | 0.68%   |
| Samsung SSD 860 EVO 250GB                           | 4         | 0.68%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 3         | 0.51%   |
| WDC WD20EZAZ-00GGJB0 2TB                            | 3         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.51%   |
| Unknown MMC Card  64GB                              | 3         | 0.51%   |
| Unknown MMC Card                                    | 3         | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.51%   |
| Seagate ST9320325AS 320GB                           | 3         | 0.51%   |
| Seagate ST320LT020-9YG142 320GB                     | 3         | 0.51%   |
| Seagate ST2000DM006-2DM164 2TB                      | 3         | 0.51%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB                      | 3         | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                      | 3         | 0.51%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 0.51%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 0.51%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 0.51%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 0.51%   |
| Kingston NVMe SSD Drive 500GB                       | 3         | 0.51%   |
| Intel NVMe SSD Drive 512GB                          | 3         | 0.51%   |
| HGST HTS725050A7E630 500GB                          | 3         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 125    | 39.08%  |
| WDC                 | 72        | 129    | 30.25%  |
| Toshiba             | 33        | 40     | 13.87%  |
| HGST                | 16        | 19     | 6.72%   |
| Samsung Electronics | 10        | 16     | 4.2%    |
| Hitachi             | 6         | 10     | 2.52%   |
| Hewlett-Packard     | 2         | 2      | 0.84%   |
| Fujitsu             | 2         | 2      | 0.84%   |
| USB3.0              | 1         | 1      | 0.42%   |
| Maxtor              | 1         | 2      | 0.42%   |
| JMicron Technology  | 1         | 1      | 0.42%   |
| ASMT                | 1         | 2      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 38        | 48     | 23.03%  |
| Samsung Electronics | 20        | 28     | 12.12%  |
| SanDisk             | 13        | 16     | 7.88%   |
| Crucial             | 11        | 18     | 6.67%   |
| Apacer              | 10        | 14     | 6.06%   |
| A-DATA Technology   | 8         | 8      | 4.85%   |
| China               | 6         | 6      | 3.64%   |
| WDC                 | 5         | 5      | 3.03%   |
| Transcend           | 5         | 5      | 3.03%   |
| Intel               | 5         | 8      | 3.03%   |
| TO Exter            | 4         | 6      | 2.42%   |
| PNY                 | 4         | 4      | 2.42%   |
| Patriot             | 4         | 5      | 2.42%   |
| Micron Technology   | 4         | 8      | 2.42%   |
| SPCC                | 3         | 4      | 1.82%   |
| Verbatim            | 2         | 2      | 1.21%   |
| Toshiba             | 2         | 2      | 1.21%   |
| Seagate             | 2         | 2      | 1.21%   |
| Plextor             | 2         | 2      | 1.21%   |
| KIOXIA-EXCERIA      | 2         | 4      | 1.21%   |
| Colorful            | 2         | 2      | 1.21%   |
| Teclast             | 1         | 1      | 0.61%   |
| SK hynix            | 1         | 1      | 0.61%   |
| SATAFIRM            | 1         | 1      | 0.61%   |
| OCZ                 | 1         | 1      | 0.61%   |
| Netac               | 1         | 1      | 0.61%   |
| LS                  | 1         | 1      | 0.61%   |
| LITEON              | 1         | 1      | 0.61%   |
| Kingmax             | 1         | 1      | 0.61%   |
| Hikvision           | 1         | 2      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |
| FORESEE             | 1         | 1      | 0.61%   |
| Apple               | 1         | 2      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 205       | 349    | 44.37%  |
| SSD     | 142       | 212    | 30.74%  |
| NVMe    | 83        | 127    | 17.97%  |
| MMC     | 20        | 27     | 4.33%   |
| Unknown | 12        | 15     | 2.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 282       | 551    | 69.63%  |
| NVMe | 82        | 124    | 20.25%  |
| SAS  | 21        | 28     | 5.19%   |
| MMC  | 20        | 27     | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 218       | 340    | 61.41%  |
| 0.51-1.0   | 106       | 163    | 29.86%  |
| 1.01-2.0   | 25        | 43     | 7.04%   |
| 3.01-4.0   | 3         | 11     | 0.85%   |
| 4.01-10.0  | 2         | 3      | 0.56%   |
| 2.01-3.0   | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 27.6%   |
| 251-500        | 86        | 23.5%   |
| 501-1000       | 46        | 12.57%  |
| 1-20           | 32        | 8.74%   |
| 51-100         | 27        | 7.38%   |
| 1001-2000      | 25        | 6.83%   |
| 21-50          | 21        | 5.74%   |
| Unknown        | 12        | 3.28%   |
| More than 3000 | 10        | 2.73%   |
| 2001-3000      | 6         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 168       | 44.92%  |
| 21-50          | 56        | 14.97%  |
| 101-250        | 47        | 12.57%  |
| 51-100         | 35        | 9.36%   |
| 251-500        | 27        | 7.22%   |
| Unknown        | 12        | 3.21%   |
| 501-1000       | 11        | 2.94%   |
| 1001-2000      | 9         | 2.41%   |
| More than 3000 | 6         | 1.6%    |
| 2001-3000      | 2         | 0.53%   |
| 0              | 1         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                   | 2         | 2      | 5.88%   |
| Seagate ST3500414CS 500GB                   | 2         | 3      | 5.88%   |
| WDC WDS480G2G0A-00JH30 480GB SSD            | 1         | 1      | 2.94%   |
| WDC WD800AAJS-00PSA0 80GB                   | 1         | 1      | 2.94%   |
| WDC WD5000BPVT-00HXZT1 500GB                | 1         | 1      | 2.94%   |
| WDC WD5000AAKX-753CA1 500GB                 | 1         | 1      | 2.94%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 2.94%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 2.94%   |
| WDC WD10JPVT-75A1YT0 1TB                    | 1         | 1      | 2.94%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 2.94%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.94%   |
| Toshiba MK5065GSX 500GB                     | 1         | 1      | 2.94%   |
| Toshiba MK1059GSMP 1TB                      | 1         | 1      | 2.94%   |
| SPCC Solid State Disk 256GB                 | 1         | 1      | 2.94%   |
| Seagate ST9750420AS 752GB                   | 1         | 1      | 2.94%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 2.94%   |
| Seagate ST380211AS 80GB                     | 1         | 1      | 2.94%   |
| Seagate ST3320620A 320GB                    | 1         | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1      | 2.94%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB | 1         | 1      | 2.94%   |
| Samsung Electronics HM160HI 160GB           | 1         | 1      | 2.94%   |
| Micron Technology 1100 SATA 512GB SSD       | 1         | 1      | 2.94%   |
| Kingston SV300S37A120G 120GB SSD            | 1         | 1      | 2.94%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 2.94%   |
| Hitachi HTS547575A9E384 752GB               | 1         | 3      | 2.94%   |
| Hitachi HDS721050CLA362 500GB               | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.94%   |
| HGST HTS541075A9E680 752GB                  | 1         | 1      | 2.94%   |
| HGST HTS541010A9E680 1TB                    | 1         | 1      | 2.94%   |
| Hewlett-Packard SSD S700 120GB              | 1         | 1      | 2.94%   |
| Unknown                                     | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 27.27%  |
| Seagate             | 8         | 10     | 24.24%  |
| Toshiba             | 3         | 3      | 9.09%   |
| Hitachi             | 3         | 5      | 9.09%   |
| HGST                | 3         | 3      | 9.09%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| SPCC                | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Unknown             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 30.77%  |
| Seagate             | 8         | 10     | 30.77%  |
| Toshiba             | 3         | 3      | 11.54%  |
| Hitachi             | 3         | 5      | 11.54%  |
| HGST                | 3         | 3      | 11.54%  |
| Samsung Electronics | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 30     | 78.13%  |
| SSD  | 7         | 7      | 21.88%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 231       | 518    | 62.43%  |
| Works    | 108       | 175    | 29.19%  |
| Malfunc  | 31        | 37     | 8.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 254       | 61.95%  |
| AMD                          | 47        | 11.46%  |
| Samsung Electronics          | 17        | 4.15%   |
| SanDisk                      | 14        | 3.41%   |
| Phison Electronics           | 13        | 3.17%   |
| Kingston Technology Company  | 11        | 2.68%   |
| SK hynix                     | 7         | 1.71%   |
| Silicon Motion               | 7         | 1.71%   |
| Nvidia                       | 7         | 1.71%   |
| KIOXIA                       | 7         | 1.71%   |
| ASMedia Technology           | 5         | 1.22%   |
| Marvell Technology Group     | 4         | 0.98%   |
| JMicron Technology           | 4         | 0.98%   |
| Toshiba America Info Systems | 3         | 0.73%   |
| Micron Technology            | 3         | 0.73%   |
| ADATA Technology             | 3         | 0.73%   |
| Silicon Image                | 1         | 0.24%   |
| Micron/Crucial Technology    | 1         | 0.24%   |
| Lite-On IT Corp. / Plextor   | 1         | 0.24%   |
| Biwin Storage Technology     | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 41        | 8.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 22        | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 3.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 3.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15        | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 1.85%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.23%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.03%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5         | 1.03%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.03%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 0.82%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 4         | 0.82%   |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 0.82%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 0.82%   |
| Intel SSD 660P Series                                                          | 4         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 4         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 4         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 244       | 59.8%   |
| NVMe | 82        | 20.1%   |
| IDE  | 44        | 10.78%  |
| RAID | 38        | 9.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 273       | 79.59%  |
| AMD    | 65        | 18.95%  |
| ARM    | 5         | 1.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz              | 8         | 2.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1.16%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.16%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 4         | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.16%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.87%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.87%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 3         | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.87%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 3         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 3         | 0.87%   |
| Intel Xeon CPU X5450 @ 3.00GHz                | 2         | 0.58%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.58%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.58%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.58%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.58%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.58%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 92        | 26.74%  |
| Intel Core i7           | 52        | 15.12%  |
| Intel Core i3           | 33        | 9.59%   |
| AMD Ryzen 5             | 24        | 6.98%   |
| Intel Core 2 Duo        | 20        | 5.81%   |
| Other                   | 18        | 5.23%   |
| Intel Pentium           | 17        | 4.94%   |
| Intel Celeron           | 13        | 3.78%   |
| Intel Xeon              | 11        | 3.2%    |
| AMD Ryzen 7             | 11        | 3.2%    |
| Intel Atom              | 6         | 1.74%   |
| Intel Pentium Dual-Core | 5         | 1.45%   |
| Intel Core 2 Quad       | 5         | 1.45%   |
| AMD A6                  | 4         | 1.16%   |
| AMD Ryzen 9             | 3         | 0.87%   |
| AMD Ryzen 3             | 3         | 0.87%   |
| AMD Athlon              | 3         | 0.87%   |
| AMD A10                 | 3         | 0.87%   |
| Intel Core i9           | 2         | 0.58%   |
| ARM BCM                 | 2         | 0.58%   |
| AMD Ryzen 7 PRO         | 2         | 0.58%   |
| AMD Athlon 64 X2        | 2         | 0.58%   |
| AMD A4                  | 2         | 0.58%   |
| AMD A12                 | 2         | 0.58%   |
| Intel Pentium Dual      | 1         | 0.29%   |
| Intel Genuine           | 1         | 0.29%   |
| ARM AArch64             | 1         | 0.29%   |
| AMD Ryzen Threadripper  | 1         | 0.29%   |
| AMD Ryzen Embedded      | 1         | 0.29%   |
| AMD Phenom II X6        | 1         | 0.29%   |
| AMD FX                  | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD Athlon X2           | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 156       | 45.48%  |
| 4      | 117       | 34.11%  |
| 6      | 36        | 10.5%   |
| 8      | 19        | 5.54%   |
| 1      | 5         | 1.46%   |
| 12     | 3         | 0.87%   |
| 16     | 2         | 0.58%   |
| 10     | 2         | 0.58%   |
| 64     | 1         | 0.29%   |
| 14     | 1         | 0.29%   |
| 3      | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 340       | 99.13%  |
| 2      | 3         | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 218       | 63.37%  |
| 1      | 125       | 36.34%  |
| 4      | 1         | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 339       | 98.55%  |
| Unknown        | 5         | 1.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 19.83%  |
| 0x206a7    | 34        | 9.63%   |
| 0x306c3    | 28        | 7.93%   |
| 0x306a9    | 26        | 7.37%   |
| 0x1067a    | 16        | 4.53%   |
| 0x806e9    | 10        | 2.83%   |
| 0x906ea    | 9         | 2.55%   |
| 0x40651    | 8         | 2.27%   |
| 0x08108109 | 7         | 1.98%   |
| 0x406e3    | 6         | 1.7%    |
| 0x306d4    | 6         | 1.7%    |
| 0x20655    | 6         | 1.7%    |
| 0x6fb      | 5         | 1.42%   |
| 0x506e3    | 5         | 1.42%   |
| 0x20652    | 5         | 1.42%   |
| 0x08701021 | 5         | 1.42%   |
| 0x906e9    | 4         | 1.13%   |
| 0x806ea    | 4         | 1.13%   |
| 0x806c1    | 4         | 1.13%   |
| 0x706a1    | 4         | 1.13%   |
| 0x6fd      | 4         | 1.13%   |
| 0x10676    | 4         | 1.13%   |
| 0x08600104 | 4         | 1.13%   |
| 0x06001119 | 4         | 1.13%   |
| 0xa0652    | 3         | 0.85%   |
| 0x90672    | 3         | 0.85%   |
| 0x806ec    | 3         | 0.85%   |
| 0x806eb    | 3         | 0.85%   |
| 0x30678    | 3         | 0.85%   |
| 0xa0671    | 2         | 0.57%   |
| 0xa0655    | 2         | 0.57%   |
| 0xa0653    | 2         | 0.57%   |
| 0x906eb    | 2         | 0.57%   |
| 0x806d1    | 2         | 0.57%   |
| 0x706e5    | 2         | 0.57%   |
| 0x406c4    | 2         | 0.57%   |
| 0x406c3    | 2         | 0.57%   |
| 0x106e5    | 2         | 0.57%   |
| 0x106ca    | 2         | 0.57%   |
| 0x0a50000b | 2         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 44        | 12.83%  |
| KabyLake         | 42        | 12.24%  |
| Haswell          | 40        | 11.66%  |
| IvyBridge        | 33        | 9.62%   |
| Penryn           | 24        | 7%      |
| Zen+             | 14        | 4.08%   |
| Skylake          | 14        | 4.08%   |
| Zen 2            | 13        | 3.79%   |
| Westmere         | 12        | 3.5%    |
| Unknown          | 12        | 3.5%    |
| Zen 3            | 10        | 2.92%   |
| Core             | 10        | 2.92%   |
| CometLake        | 9         | 2.62%   |
| Silvermont       | 8         | 2.33%   |
| Zen              | 7         | 2.04%   |
| Broadwell        | 7         | 2.04%   |
| TigerLake        | 6         | 1.75%   |
| Goldmont plus    | 5         | 1.46%   |
| Alderlake Hybrid | 5         | 1.46%   |
| Piledriver       | 4         | 1.17%   |
| Icelake          | 4         | 1.17%   |
| Nehalem          | 3         | 0.87%   |
| Excavator        | 3         | 0.87%   |
| Steamroller      | 2         | 0.58%   |
| K8 Hammer        | 2         | 0.58%   |
| K10              | 2         | 0.58%   |
| Jaguar           | 2         | 0.58%   |
| Bonnell          | 2         | 0.58%   |
| K8 & K10 hybrid  | 1         | 0.29%   |
| K10 Llano        | 1         | 0.29%   |
| Goldmont         | 1         | 0.29%   |
| Bobcat           | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 206       | 48.7%   |
| Nvidia                     | 120       | 28.37%  |
| AMD                        | 94        | 22.22%  |
| Matrox Electronics Systems | 2         | 0.47%   |
| ASPEED Technology          | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 7.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 2.3%    |
| Intel HD Graphics 620                                                                    | 10        | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 2.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.38%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 6         | 1.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.38%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.38%   |
| AMD Renoir                                                                               | 6         | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.38%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 4         | 0.92%   |
| Intel HD Graphics 630                                                                    | 4         | 0.92%   |
| Intel HD Graphics 530                                                                    | 4         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.69%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 3         | 0.69%   |
| AMD Lucienne                                                                             | 3         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 128       | 37.21%  |
| 1 x AMD              | 62        | 18.02%  |
| 1 x Nvidia           | 61        | 17.73%  |
| Intel + Nvidia       | 52        | 15.12%  |
| Intel + AMD          | 18        | 5.23%   |
| 2 x AMD              | 8         | 2.33%   |
| AMD + Nvidia         | 6         | 1.74%   |
| Other                | 5         | 1.45%   |
| 1 x Matrox           | 2         | 0.58%   |
| 2 x AMD + 3 x Nvidia | 1         | 0.29%   |
| 1 x ASPEED           | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 267       | 76.95%  |
| Proprietary | 67        | 19.31%  |
| Unknown     | 13        | 3.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 50.43%  |
| 1.01-2.0   | 63        | 18.16%  |
| 0.51-1.0   | 32        | 9.22%   |
| 3.01-4.0   | 28        | 8.07%   |
| 0.01-0.5   | 27        | 7.78%   |
| 7.01-8.0   | 14        | 4.03%   |
| 5.01-6.0   | 4         | 1.15%   |
| 2.01-3.0   | 2         | 0.58%   |
| 8.01-16.0  | 2         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 13.19%  |
| Samsung Electronics     | 38        | 10.44%  |
| Dell                    | 37        | 10.16%  |
| Chimei Innolux          | 33        | 9.07%   |
| LG Display              | 31        | 8.52%   |
| BOE                     | 26        | 7.14%   |
| Hewlett-Packard         | 19        | 5.22%   |
| Acer                    | 17        | 4.67%   |
| BenQ                    | 15        | 4.12%   |
| Goldstar                | 13        | 3.57%   |
| AOC                     | 13        | 3.57%   |
| Sharp                   | 11        | 3.02%   |
| Philips                 | 9         | 2.47%   |
| ViewSonic               | 7         | 1.92%   |
| Apple                   | 6         | 1.65%   |
| Lenovo                  | 5         | 1.37%   |
| Chi Mei Optoelectronics | 4         | 1.1%    |
| Toshiba                 | 3         | 0.82%   |
| ASUSTek Computer        | 3         | 0.82%   |
| Unknown                 | 2         | 0.55%   |
| Panasonic               | 2         | 0.55%   |
| LG Electronics          | 2         | 0.55%   |
| InnoLux Display         | 2         | 0.55%   |
| Unknown                 | 2         | 0.55%   |
| Sony                    | 1         | 0.27%   |
| PANDA                   | 1         | 0.27%   |
| MStar                   | 1         | 0.27%   |
| MSI                     | 1         | 0.27%   |
| LTM                     | 1         | 0.27%   |
| LG Philips              | 1         | 0.27%   |
| InfoVision              | 1         | 0.27%   |
| HUYINIUDA               | 1         | 0.27%   |
| EXP                     | 1         | 0.27%   |
| Envision Peripherals    | 1         | 0.27%   |
| Eizo                    | 1         | 0.27%   |
| Dinner                  | 1         | 0.27%   |
| Denver                  | 1         | 0.27%   |
| CVT                     | 1         | 0.27%   |
| Armaggeddon             | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 6         | 1.6%    |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                        | 4         | 1.07%   |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                        | 4         | 1.07%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 3         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 0.8%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 0.8%    |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                         | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 0.8%    |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                         | 3         | 0.8%    |
| Sharp LCD SHP10C9 1920x540                                                | 2         | 0.53%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch         | 2         | 0.53%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch         | 2         | 0.53%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch          | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.53%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                        | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.53%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.53%   |
| Hewlett-Packard LCD Monitor P221                                          | 2         | 0.53%   |
| Hewlett-Packard L1506 HWP265B 1024x768 304x228mm 15.0-inch                | 2         | 0.53%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 2         | 0.53%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 2         | 0.53%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                        | 2         | 0.53%   |
| Dell LCD Monitor E2720HS 1920x1080                                        | 2         | 0.53%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.53%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                        | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 141       | 39.83%  |
| 1366x768 (WXGA)    | 106       | 29.94%  |
| 3840x2160 (4K)     | 18        | 5.08%   |
| 2560x1440 (QHD)    | 15        | 4.24%   |
| 1600x900 (HD+)     | 13        | 3.67%   |
| 1280x800 (WXGA)    | 9         | 2.54%   |
| 1440x900 (WXGA+)   | 6         | 1.69%   |
| 2560x1080          | 5         | 1.41%   |
| Unknown            | 5         | 1.41%   |
| 1920x1200 (WUXGA)  | 4         | 1.13%   |
| 1360x768           | 4         | 1.13%   |
| 1280x1024 (SXGA)   | 3         | 0.85%   |
| 1024x768 (XGA)     | 3         | 0.85%   |
| 5760x1080          | 2         | 0.56%   |
| 2160x1440          | 2         | 0.56%   |
| 1920x540           | 2         | 0.56%   |
| 1680x1050 (WSXGA+) | 2         | 0.56%   |
| 1600x1200          | 2         | 0.56%   |
| 5440x1080          | 1         | 0.28%   |
| 5120x1440          | 1         | 0.28%   |
| 3840x1080          | 1         | 0.28%   |
| 3440x1440          | 1         | 0.28%   |
| 3120x1600          | 1         | 0.28%   |
| 3000x2000          | 1         | 0.28%   |
| 2880x1920          | 1         | 0.28%   |
| 2240x1400          | 1         | 0.28%   |
| 1360x765           | 1         | 0.28%   |
| 1280x960           | 1         | 0.28%   |
| 1280x720 (HD)      | 1         | 0.28%   |
| 1024x600           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 72        | 19.83%  |
| 14      | 45        | 12.4%   |
| 13      | 39        | 10.74%  |
| 23      | 27        | 7.44%   |
| 24      | 25        | 6.89%   |
| 27      | 21        | 5.79%   |
| 21      | 20        | 5.51%   |
| 18      | 18        | 4.96%   |
| Unknown | 18        | 4.96%   |
| 31      | 12        | 3.31%   |
| 19      | 12        | 3.31%   |
| 17      | 10        | 2.75%   |
| 12      | 7         | 1.93%   |
| 32      | 6         | 1.65%   |
| 20      | 6         | 1.65%   |
| 11      | 6         | 1.65%   |
| 34      | 3         | 0.83%   |
| 72      | 2         | 0.55%   |
| 52      | 2         | 0.55%   |
| 28      | 2         | 0.55%   |
| 25      | 2         | 0.55%   |
| 22      | 2         | 0.55%   |
| 84      | 1         | 0.28%   |
| 55      | 1         | 0.28%   |
| 39      | 1         | 0.28%   |
| 16      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |
| 7       | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 145       | 40.17%  |
| 501-600     | 69        | 19.11%  |
| 401-500     | 57        | 15.79%  |
| 201-300     | 27        | 7.48%   |
| Unknown     | 18        | 4.99%   |
| 601-700     | 17        | 4.71%   |
| 351-400     | 11        | 3.05%   |
| 701-800     | 9         | 2.49%   |
| 1501-2000   | 3         | 0.83%   |
| 1001-1500   | 3         | 0.83%   |
| 801-900     | 1         | 0.28%   |
| 101-200     | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 266       | 81.1%   |
| 16/10   | 23        | 7.01%   |
| Unknown | 16        | 4.88%   |
| 3/2     | 6         | 1.83%   |
| 5/4     | 5         | 1.52%   |
| 21/9    | 5         | 1.52%   |
| 4/3     | 4         | 1.22%   |
| 32/9    | 2         | 0.61%   |
| 1.00    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 74        | 20.56%  |
| 101-110        | 73        | 20.28%  |
| 201-250        | 63        | 17.5%   |
| 151-200        | 24        | 6.67%   |
| 351-500        | 21        | 5.83%   |
| 301-350        | 21        | 5.83%   |
| 141-150        | 19        | 5.28%   |
| Unknown        | 18        | 5%      |
| 71-80          | 10        | 2.78%   |
| 251-300        | 8         | 2.22%   |
| 61-70          | 7         | 1.94%   |
| 121-130        | 7         | 1.94%   |
| More than 1000 | 6         | 1.67%   |
| 51-60          | 6         | 1.67%   |
| 41-50          | 1         | 0.28%   |
| 1-40           | 1         | 0.28%   |
| 501-1000       | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 122       | 34.37%  |
| 101-120       | 110       | 30.99%  |
| 121-160       | 83        | 23.38%  |
| Unknown       | 18        | 5.07%   |
| 161-240       | 10        | 2.82%   |
| 1-50          | 9         | 2.54%   |
| More than 240 | 3         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 284       | 82.08%  |
| 2     | 46        | 13.29%  |
| 0     | 14        | 4.05%   |
| 3     | 2         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 176       | 31.43%  |
| Intel                             | 158       | 28.21%  |
| Qualcomm Atheros                  | 79        | 14.11%  |
| Broadcom                          | 34        | 6.07%   |
| TP-Link                           | 20        | 3.57%   |
| Ralink Technology                 | 19        | 3.39%   |
| D-Link                            | 11        | 1.96%   |
| Xiaomi                            | 9         | 1.61%   |
| Qualcomm Atheros Communications   | 7         | 1.25%   |
| MediaTek                          | 6         | 1.07%   |
| Ralink                            | 5         | 0.89%   |
| Nvidia                            | 5         | 0.89%   |
| Broadcom Limited                  | 5         | 0.89%   |
| ASIX Electronics                  | 4         | 0.71%   |
| Huawei Technologies               | 3         | 0.54%   |
| Samsung Electronics               | 2         | 0.36%   |
| OPPO Electronics                  | 2         | 0.36%   |
| InterBiometrics                   | 2         | 0.36%   |
| Aquantia                          | 2         | 0.36%   |
| Tehuti Networks                   | 1         | 0.18%   |
| Sundance Technology Inc / IC Plus | 1         | 0.18%   |
| Marvell Technology Group          | 1         | 0.18%   |
| JMicron Technology                | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| DisplayLink                       | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| Attansic Technology               | 1         | 0.18%   |
| ASUSTek Computer                  | 1         | 0.18%   |
| Apple                             | 1         | 0.18%   |
| AboCom Systems                    | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 117       | 18.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.33%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.56%   |
| TP-Link Archer T4U ver.3                                          | 9         | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.4%    |
| Ralink MT7601U Wireless Adapter                                   | 9         | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 9         | 1.4%    |
| Realtek 802.11ac NIC                                              | 8         | 1.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 8         | 1.24%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.09%   |
| TP-Link 802.11n NIC                                               | 6         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 6         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.93%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 6         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.78%   |
| Intel Wireless 7265                                               | 5         | 0.78%   |
| Intel Wireless 3165                                               | 5         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.62%   |
| Intel Wireless 3160                                               | 4         | 0.62%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 33.98%  |
| Qualcomm Atheros                | 63        | 20.39%  |
| Realtek Semiconductor           | 45        | 14.56%  |
| Broadcom                        | 22        | 7.12%   |
| TP-Link                         | 20        | 6.47%   |
| Ralink Technology               | 19        | 6.15%   |
| D-Link                          | 10        | 3.24%   |
| Qualcomm Atheros Communications | 7         | 2.27%   |
| MediaTek                        | 6         | 1.94%   |
| Ralink                          | 5         | 1.62%   |
| Broadcom Limited                | 4         | 1.29%   |
| D-Link System                   | 1         | 0.32%   |
| ASUSTek Computer                | 1         | 0.32%   |
| AboCom Systems                  | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 13        | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 12        | 3.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 10        | 3.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 10        | 3.19%   |
| TP-Link Archer T4U ver.3                                                             | 9         | 2.88%   |
| Ralink MT7601U Wireless Adapter                                                      | 9         | 2.88%   |
| Realtek 802.11ac NIC                                                                 | 8         | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 8         | 2.56%   |
| Intel Wireless 8265 / 8275                                                           | 8         | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 7         | 2.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 7         | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 7         | 2.24%   |
| TP-Link 802.11n NIC                                                                  | 6         | 1.92%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 6         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 6         | 1.92%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 5         | 1.6%    |
| Intel Wireless 7265                                                                  | 5         | 1.6%    |
| Intel Wireless 3165                                                                  | 5         | 1.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 5         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 4         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 4         | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 4         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 4         | 1.28%   |
| Intel Wireless 3160                                                                  | 4         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                                  | 4         | 1.28%   |
| Intel Centrino Wireless-N 2230                                                       | 4         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                                       | 4         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4         | 1.28%   |
| Ralink RT5572 Wireless Adapter                                                       | 3         | 0.96%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 3         | 0.96%   |
| Intel Wireless-AC 9260                                                               | 3         | 0.96%   |
| Intel Wireless 7260                                                                  | 3         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 3         | 0.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 157       | 49.53%  |
| Intel                             | 88        | 27.76%  |
| Qualcomm Atheros                  | 21        | 6.62%   |
| Broadcom                          | 15        | 4.73%   |
| Xiaomi                            | 9         | 2.84%   |
| Nvidia                            | 5         | 1.58%   |
| ASIX Electronics                  | 4         | 1.26%   |
| Huawei Technologies               | 3         | 0.95%   |
| Samsung Electronics               | 2         | 0.63%   |
| OPPO Electronics                  | 2         | 0.63%   |
| Aquantia                          | 2         | 0.63%   |
| Tehuti Networks                   | 1         | 0.32%   |
| Sundance Technology Inc / IC Plus | 1         | 0.32%   |
| Marvell Technology Group          | 1         | 0.32%   |
| JMicron Technology                | 1         | 0.32%   |
| DisplayLink                       | 1         | 0.32%   |
| D-Link                            | 1         | 0.32%   |
| Broadcom Limited                  | 1         | 0.32%   |
| Attansic Technology               | 1         | 0.32%   |
| Apple                             | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 117       | 35.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 7.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 4.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.75%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 2.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.83%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 1.22%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.22%   |
| Intel Ethernet Connection (11) I219-V                             | 4         | 1.22%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.92%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.92%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.92%   |
| Huawei STK-L21                                                    | 3         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.61%   |
| OPPO RMX3263                                                      | 2         | 0.61%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.61%   |
| Intel I350 Gigabit Fiber Network Connection                       | 2         | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.61%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.61%   |
| Intel 82562V-2 10/100 Network Connection                          | 2         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 288       | 50.44%  |
| WiFi     | 280       | 49.04%  |
| Modem    | 3         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 230       | 66.28%  |
| Ethernet | 117       | 33.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 188       | 54.65%  |
| 1     | 126       | 36.63%  |
| 0     | 21        | 6.1%    |
| 3     | 7         | 2.03%   |
| 9     | 1         | 0.29%   |
| 8     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 261       | 74.15%  |
| Yes  | 91        | 25.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 36.65%  |
| Cambridge Silicon Radio         | 22        | 9.95%   |
| Realtek Semiconductor           | 18        | 8.14%   |
| Qualcomm Atheros Communications | 18        | 8.14%   |
| Broadcom                        | 14        | 6.33%   |
| IMC Networks                    | 13        | 5.88%   |
| Foxconn / Hon Hai               | 12        | 5.43%   |
| Apple                           | 11        | 4.98%   |
| Lite-On Technology              | 10        | 4.52%   |
| Dell                            | 5         | 2.26%   |
| Hewlett-Packard                 | 4         | 1.81%   |
| Realtek                         | 3         | 1.36%   |
| Ralink                          | 2         | 0.9%    |
| MediaTek                        | 2         | 0.9%    |
| TP-Link                         | 1         | 0.45%   |
| Ralink Technology               | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |
| Askey Computer                  | 1         | 0.45%   |
| Alps Electric                   | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 11.31%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 22        | 9.95%   |
| Intel AX201 Bluetooth                                                               | 13        | 5.88%   |
| Intel AX200 Bluetooth                                                               | 13        | 5.88%   |
| Realtek Bluetooth Radio                                                             | 12        | 5.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 4.98%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 2.71%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.71%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.26%   |
| Intel AX210 Bluetooth                                                               | 5         | 2.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.81%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.81%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.81%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.36%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.36%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.36%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.9%    |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.9%    |
| Intel Bluetooth Device                                                              | 2         | 0.9%    |
| IMC Networks Wireless_Device                                                        | 2         | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.9%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.9%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.9%    |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.9%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.9%    |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.9%    |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.9%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.9%    |
| Broadcom BCM20702A0                                                                 | 2         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 258       | 55.36%  |
| AMD                         | 86        | 18.45%  |
| Nvidia                      | 84        | 18.03%  |
| C-Media Electronics         | 8         | 1.72%   |
| Logitech                    | 7         | 1.5%    |
| JMTek                       | 3         | 0.64%   |
| Samsung Electronics         | 2         | 0.43%   |
| RODE Microphones            | 2         | 0.43%   |
| Realtek Semiconductor       | 2         | 0.43%   |
| Generalplus Technology      | 2         | 0.43%   |
| Unknown                     | 1         | 0.21%   |
| Texas Instruments           | 1         | 0.21%   |
| Razer USA                   | 1         | 0.21%   |
| Plantronics                 | 1         | 0.21%   |
| MVSILICON.INC.              | 1         | 0.21%   |
| MosArt Semiconductor        | 1         | 0.21%   |
| GN Netcom                   | 1         | 0.21%   |
| FiiO Electronics Technology | 1         | 0.21%   |
| Creative Labs               | 1         | 0.21%   |
| Cooler Master               | 1         | 0.21%   |
| Cambridge Audio             | 1         | 0.21%   |
| ASUSTek Computer            | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 40        | 7.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 32        | 5.85%   |
| AMD Family 17h/19h HD Audio Controller                                            | 30        | 5.48%   |
| Intel Sunrise Point-LP HD Audio                                                   | 24        | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 23        | 4.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 17        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16        | 2.93%   |
| Nvidia GF108 High Definition Audio Controller                                     | 15        | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 15        | 2.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 13        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 13        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                        | 12        | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                          | 10        | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9         | 1.65%   |
| Intel 8 Series HD Audio Controller                                                | 9         | 1.65%   |
| AMD FCH Azalia Controller                                                         | 9         | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9         | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                             | 8         | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6         | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 6         | 1.1%    |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 5         | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5         | 0.91%   |
| Intel Comet Lake PCH cAVS                                                         | 5         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 5         | 0.91%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5         | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 0.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5         | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 0.73%   |
| Nvidia High Definition Audio Controller                                           | 4         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4         | 0.73%   |
| Logitech H600 [Wireless Headset]                                                  | 4         | 0.73%   |
| Intel Alder Lake-S HD Audio Controller                                            | 4         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 54        | 27.84%  |
| Samsung Electronics | 35        | 18.04%  |
| SK hynix            | 34        | 17.53%  |
| Micron Technology   | 11        | 5.67%   |
| Unknown             | 10        | 5.15%   |
| Corsair             | 8         | 4.12%   |
| Nanya Technology    | 7         | 3.61%   |
| A-DATA Technology   | 7         | 3.61%   |
| Ramaxel Technology  | 4         | 2.06%   |
| Kingmax             | 4         | 2.06%   |
| Crucial             | 3         | 1.55%   |
| Apacer              | 3         | 1.55%   |
| Unknown (ABCD)      | 2         | 1.03%   |
| Team                | 2         | 1.03%   |
| Silicon Power       | 2         | 1.03%   |
| Kimtigo             | 2         | 1.03%   |
| SemsoTai            | 1         | 0.52%   |
| PNY                 | 1         | 0.52%   |
| Kinlstuo            | 1         | 0.52%   |
| Hewlett-Packard     | 1         | 0.52%   |
| G.Skill             | 1         | 0.52%   |
| Elpida              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 5         | 2.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.92%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 3         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 1.44%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s          | 3         | 1.44%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.96%   |
| Kingston RAM 99U5428-082.A00LF 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.96%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                 | 2         | 0.96%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.96%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.96%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s                     | 2         | 0.96%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.48%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.48%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                    | 1         | 0.48%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 1         | 0.48%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 0.48%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.48%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                    | 1         | 0.48%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.48%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s           | 1         | 0.48%   |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.48%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.48%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 74        | 45.96%  |
| DDR4    | 64        | 39.75%  |
| SDRAM   | 7         | 4.35%   |
| DDR2    | 5         | 3.11%   |
| LPDDR4  | 4         | 2.48%   |
| LPDDR3  | 3         | 1.86%   |
| Unknown | 2         | 1.24%   |
| DDR5    | 1         | 0.62%   |
| DDR     | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 58.75%  |
| DIMM         | 59        | 36.88%  |
| Row Of Chips | 6         | 3.75%   |
| FB-DIMM      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 62        | 34.64%  |
| 8192  | 55        | 30.73%  |
| 2048  | 29        | 16.2%   |
| 16384 | 18        | 10.06%  |
| 32768 | 10        | 5.59%   |
| 1024  | 5         | 2.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 24.29%  |
| 2667    | 23        | 12.99%  |
| 3200    | 22        | 12.43%  |
| 1334    | 15        | 8.47%   |
| 1333    | 14        | 7.91%   |
| 2400    | 13        | 7.34%   |
| 2133    | 7         | 3.95%   |
| 800     | 5         | 2.82%   |
| Unknown | 5         | 2.82%   |
| 3600    | 4         | 2.26%   |
| 1067    | 4         | 2.26%   |
| 667     | 4         | 2.26%   |
| 4267    | 2         | 1.13%   |
| 3400    | 2         | 1.13%   |
| 1867    | 2         | 1.13%   |
| 1066    | 2         | 1.13%   |
| 4800    | 1         | 0.56%   |
| 4199    | 1         | 0.56%   |
| 3466    | 1         | 0.56%   |
| 3266    | 1         | 0.56%   |
| 3000    | 1         | 0.56%   |
| 2933    | 1         | 0.56%   |
| 2134    | 1         | 0.56%   |
| 2048    | 1         | 0.56%   |
| 1866    | 1         | 0.56%   |
| 1800    | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 3         | 21.43%  |
| Samsung Electronics | 3         | 21.43%  |
| Canon               | 3         | 21.43%  |
| Brother Industries  | 3         | 21.43%  |
| Prolific Technology | 1         | 7.14%   |
| Hewlett-Packard     | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 3         | 21.43%  |
| Canon E410 series             | 2         | 14.29%  |
| Seiko Epson L3150 Series      | 1         | 7.14%   |
| Seiko Epson L312 Series       | 1         | 7.14%   |
| Seiko Epson L210 Series       | 1         | 7.14%   |
| Prolific PL2305 Parallel Port | 1         | 7.14%   |
| HP Ink Tank 110 series        | 1         | 7.14%   |
| Canon LBP6030w/6018w          | 1         | 7.14%   |
| Brother DCP-J105              | 1         | 7.14%   |
| Brother DCP-1610W             | 1         | 7.14%   |
| Brother DCP-1510              | 1         | 7.14%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 17.71%  |
| Microdia                               | 23        | 11.98%  |
| Realtek Semiconductor                  | 17        | 8.85%   |
| IMC Networks                           | 17        | 8.85%   |
| Sunplus Innovation Technology          | 15        | 7.81%   |
| Suyin                                  | 11        | 5.73%   |
| Acer                                   | 11        | 5.73%   |
| Logitech                               | 9         | 4.69%   |
| Apple                                  | 9         | 4.69%   |
| Generalplus Technology                 | 7         | 3.65%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.13%   |
| Quanta                                 | 5         | 2.6%    |
| Alcor Micro                            | 4         | 2.08%   |
| Syntek                                 | 3         | 1.56%   |
| Luxvisions Innotech Limited            | 3         | 1.56%   |
| Lite-On Technology                     | 3         | 1.56%   |
| YGTek                                  | 2         | 1.04%   |
| Z-Star Microelectronics                | 1         | 0.52%   |
| WCM_USB                                | 1         | 0.52%   |
| USB Camera                             | 1         | 0.52%   |
| Sonix Technology                       | 1         | 0.52%   |
| Samsung Electronics                    | 1         | 0.52%   |
| Ricoh                                  | 1         | 0.52%   |
| Primax Electronics                     | 1         | 0.52%   |
| OmniVision Technologies                | 1         | 0.52%   |
| Lenovo                                 | 1         | 0.52%   |
| Jieli Technology                       | 1         | 0.52%   |
| eMPIA Technology                       | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |
| ARC International                      | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 10        | 5.21%   |
| Chicony USB2.0 VGA UVC WebCam                           | 8         | 4.17%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 2.6%    |
| Chicony HD WebCam                                       | 5         | 2.6%    |
| Realtek Integrated_Webcam_HD                            | 4         | 2.08%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 2.08%   |
| Generalplus GENERAL WEBCAM                              | 4         | 2.08%   |
| Chicony Integrated Camera                               | 4         | 2.08%   |
| Logitech HD Pro Webcam C920                             | 3         | 1.56%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 1.56%   |
| Chicony HP HD Webcam                                    | 3         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.56%   |
| Apple FaceTime HD Camera                                | 3         | 1.56%   |
| Acer Lenovo Integrated Webcam                           | 3         | 1.56%   |
| YGTek Webcam                                            | 2         | 1.04%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 1.04%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 1.04%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.04%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.04%   |
| Realtek USB Camera                                      | 2         | 1.04%   |
| Realtek HD WebCam                                       | 2         | 1.04%   |
| Quanta HP TrueVision HD Camera                          | 2         | 1.04%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.04%   |
| Logitech Webcam C270                                    | 2         | 1.04%   |
| Lite-On Integrated Camera                               | 2         | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 1.04%   |
| IMC Networks Integrated Camera                          | 2         | 1.04%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 2         | 1.04%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.04%   |
| Apple iPhone5/5C/5S/6                                   | 2         | 1.04%   |
| Apple Built-in iSight                                   | 2         | 1.04%   |
| Alcor Micro Asus Integrated Webcam                      | 2         | 1.04%   |
| Acer EasyCamera                                         | 2         | 1.04%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.04%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.52%   |
| WCM_USB WEB CAM                                         | 1         | 0.52%   |
| USB Camera USB Camera                                   | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 26.92%  |
| Shenzhen Goodix Technology | 5         | 19.23%  |
| Synaptics                  | 4         | 15.38%  |
| Elan Microelectronics      | 3         | 11.54%  |
| AuthenTec                  | 3         | 11.54%  |
| Upek                       | 2         | 7.69%   |
| LighTuning Technology      | 1         | 3.85%   |
| Focal-systems.Corp         | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                          | 3         | 11.54%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 7.69%   |
| Elan ELAN:ARM-M4                                            | 2         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 3.85%   |
| Validity Sensors VFS491                                     | 1         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 1         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                        | 1         | 3.85%   |
| Synaptics  WBDI                                             | 1         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 3.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 3.85%   |
| Shenzhen Goodix  Fingerprint Device                         | 1         | 3.85%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 3.85%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 3.85%   |
| Elan ELAN:Fingerprint                                       | 1         | 3.85%   |
| AuthenTec Fingerprint Sensor                                | 1         | 3.85%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 3.85%   |
| AuthenTec AES1660 Fingerprint Sensor                        | 1         | 3.85%   |
| Unknown                                                     | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 80%     |
| O2 Micro    | 1         | 10%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom 58200                                                               | 2         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 261       | 74.79%  |
| 1     | 72        | 20.63%  |
| 2     | 12        | 3.44%   |
| 3     | 2         | 0.57%   |
| 6     | 1         | 0.29%   |
| 4     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 25.24%  |
| Net/wireless             | 21        | 20.39%  |
| Graphics card            | 18        | 17.48%  |
| Multimedia controller    | 8         | 7.77%   |
| Chipcard                 | 8         | 7.77%   |
| Communication controller | 5         | 4.85%   |
| Unassigned class         | 3         | 2.91%   |
| Storage                  | 3         | 2.91%   |
| Bluetooth                | 3         | 2.91%   |
| Storage/ide              | 2         | 1.94%   |
| Sound                    | 2         | 1.94%   |
| Net/ethernet             | 2         | 1.94%   |
| Network                  | 1         | 0.97%   |
| Card reader              | 1         | 0.97%   |


Kubuntu 23.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Notebook                    | [7541fcf0c8](https://linux-hardware.org/?probe=7541fcf0c8) | Dec 22, 2023 |
| Lenovo        | G500 20236                  | [d8f95bfd45](https://linux-hardware.org/?probe=d8f95bfd45) | Dec 18, 2023 |
| Lenovo        | G500 20236                  | [f9a70833ee](https://linux-hardware.org/?probe=f9a70833ee) | Dec 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [65530f33de](https://linux-hardware.org/?probe=65530f33de) | Dec 06, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [997c41ef61](https://linux-hardware.org/?probe=997c41ef61) | Dec 01, 2023 |
| HP            | 355 G2                      | [bb79df3643](https://linux-hardware.org/?probe=bb79df3643) | Nov 28, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [c3fc46a4a5](https://linux-hardware.org/?probe=c3fc46a4a5) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3f1d1d36ef](https://linux-hardware.org/?probe=3f1d1d36ef) | Nov 10, 2023 |
| HP            | Notebook                    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| HUAWEI        | KPL-W0X                     | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| Samsung       | 730QCJ/730QCR               | [67863a015a](https://linux-hardware.org/?probe=67863a015a) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| Timi          | RedmiBook Pro 15            | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| Dell          | Precision M6800             | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| HP            | 14                          | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| HP            | Laptop 15-ef0xxx            | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | [5962f780e9](https://linux-hardware.org/?probe=5962f780e9) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | [9990a91f59](https://linux-hardware.org/?probe=9990a91f59) | Oct 21, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| GPU Compan... | GWTN141-10                  | [413edf8cdb](https://linux-hardware.org/?probe=413edf8cdb) | Oct 18, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [05ee51f822](https://linux-hardware.org/?probe=05ee51f822) | Oct 18, 2023 |
| Avell High... | C62 MOB                     | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| Acer          | Aspire A317-32              | [e4bcb7e688](https://linux-hardware.org/?probe=e4bcb7e688) | Oct 15, 2023 |
| HP            | ProBook 4540s               | [c3be7c74a0](https://linux-hardware.org/?probe=c3be7c74a0) | Oct 11, 2023 |
| Dell          | Inspiron 3520               | [3fe42a607c](https://linux-hardware.org/?probe=3fe42a607c) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| Dell          | Inspiron 7400               | [38b7ffd223](https://linux-hardware.org/?probe=38b7ffd223) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7513e708f6](https://linux-hardware.org/?probe=7513e708f6) | Oct 07, 2023 |
| Google        | Woomax                      | [2163941472](https://linux-hardware.org/?probe=2163941472) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| Apple         | MacBookAir7,2               | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| CHIPHD        | NT125D                      | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Dell          | Latitude E5470              | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [d4060b585a](https://linux-hardware.org/?probe=d4060b585a) | Sep 20, 2023 |
| HP            | ENVY TS 15                  | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| Acer          | Aspire A515-57              | [a73abd96f1](https://linux-hardware.org/?probe=a73abd96f1) | Sep 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [20ad52b9a4](https://linux-hardware.org/?probe=20ad52b9a4) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| Valve         | Jupiter                     | [23da68a72c](https://linux-hardware.org/?probe=23da68a72c) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | [5180b1e51e](https://linux-hardware.org/?probe=5180b1e51e) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | [6f3051262d](https://linux-hardware.org/?probe=6f3051262d) | Sep 09, 2023 |
| Google        | Robo360                     | [86308cca01](https://linux-hardware.org/?probe=86308cca01) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| ASUSTek       | G551JM                      | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| HP            | Notebook                    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| Avell High... | C62 MOB                     | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Dell          | Precision 7780              | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| HP            | Laptop 17-ca1xxx            | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Dell          | XPS 15 9550                 | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Acer          | Nitro AN517-41              | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| Acer          | Aspire A515-51              | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| HP            | EliteBook 840 G6            | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Google        | Dragonair                   | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| TECNO         | MEGABOOK T1                 | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| GPD           | G1621-02                    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Precision 7670              | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Alienware     | 14                          | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| HP            | G62                         | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| HP            | ENVY Notebook               | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| HP            | ZBook 17 G2                 | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| HP            | Pavilion 15                 | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| Dell          | G3 3779                     | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| Unknown       | Unknown                     | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| Acer          | Predator G3-572             | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| Dell          | G3 3779                     | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| HP            | 240 G7 Notebook PC          | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| HP            | ProBook 650 G1              | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Dell          | G3 3779                     | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP            | Laptop 14s-dq2xxx           | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| HP            | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Dell          | Latitude E6420              | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Dell          | G3 3779                     | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| ASUSTek       | K50IJ                       | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte      | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| MSI           | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer          | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Google        | Bluebird                    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Apple         | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME       | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Acer          | Swift SFX14-41G             | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| HP            | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Google        | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| HP            | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Acer          | Aspire A515-45              | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| HUAWEI        | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Dell          | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 55        | 31.07%  |
| 6.2.0-26-generic        | 16        | 9.04%   |
| 6.2.0-32-generic        | 10        | 5.65%   |
| 6.2.0-24-generic        | 9         | 5.08%   |
| 6.2.0-23-generic        | 9         | 5.08%   |
| 6.2.0-34-generic        | 8         | 4.52%   |
| 6.2.0-33-generic        | 8         | 4.52%   |
| 6.2.0-27-generic        | 8         | 4.52%   |
| 6.2.0-35-generic        | 6         | 3.39%   |
| 6.2.0-25-generic        | 4         | 2.26%   |
| 6.2.0-37-generic        | 3         | 1.69%   |
| 6.2.0-36-generic        | 3         | 1.69%   |
| 6.2.0-31-generic        | 3         | 1.69%   |
| 6.2.0-18-generic        | 3         | 1.69%   |
| 6.4.8-060408-generic    | 2         | 1.13%   |
| 6.2.0-1009-lowlatency   | 2         | 1.13%   |
| 6.2.0-1007-lowlatency   | 2         | 1.13%   |
| 6.2.0-1005-lowlatency   | 2         | 1.13%   |
| 6.5.2                   | 1         | 0.56%   |
| 6.4.0-060400-generic    | 1         | 0.56%   |
| 6.3.8-x64v3-xanmod1     | 1         | 0.56%   |
| 6.3.8                   | 1         | 0.56%   |
| 6.3.7-060307-generic    | 1         | 0.56%   |
| 6.3.6-custom            | 1         | 0.56%   |
| 6.3.4-060304-generic    | 1         | 0.56%   |
| 6.3.3-060303-generic    | 1         | 0.56%   |
| 6.3.1-060301-generic    | 1         | 0.56%   |
| 6.2.10-060210-generic   | 1         | 0.56%   |
| 6.2.0-9032-generic      | 1         | 0.56%   |
| 6.2.0-39-generic        | 1         | 0.56%   |
| 6.2.0-21-generic        | 1         | 0.56%   |
| 6.2.0-1015-lowlatency   | 1         | 0.56%   |
| 6.2.0-1014-lowlatency   | 1         | 0.56%   |
| 6.2.0-1011-lowlatency   | 1         | 0.56%   |
| 6.2.0-1008-lowlatency   | 1         | 0.56%   |
| 6.1.12-060112-generic   | 1         | 0.56%   |
| 6.1.0-14-generic        | 1         | 0.56%   |
| 6.1.0-060100rc4-generic | 1         | 0.56%   |
| 5.19.0-42-generic       | 1         | 0.56%   |
| 5.19.0-40-generic       | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 143       | 88.27%  |
| 5.19.0  | 4         | 2.47%   |
| 6.4.8   | 2         | 1.23%   |
| 6.3.8   | 2         | 1.23%   |
| 6.1.0   | 2         | 1.23%   |
| 6.5.2   | 1         | 0.62%   |
| 6.4.0   | 1         | 0.62%   |
| 6.3.7   | 1         | 0.62%   |
| 6.3.6   | 1         | 0.62%   |
| 6.3.4   | 1         | 0.62%   |
| 6.3.3   | 1         | 0.62%   |
| 6.3.1   | 1         | 0.62%   |
| 6.2.10  | 1         | 0.62%   |
| 6.1.12  | 1         | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 144       | 88.89%  |
| 6.3     | 7         | 4.32%   |
| 5.19    | 4         | 2.47%   |
| 6.4     | 3         | 1.85%   |
| 6.1     | 3         | 1.85%   |
| 6.5     | 1         | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 161       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 157       | 97.52%  |
| KDE   | 3         | 1.86%   |
| GNOME | 1         | 0.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 134       | 83.23%  |
| Wayland | 25        | 15.53%  |
| Tty     | 2         | 1.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 97        | 60.25%  |
| Unknown | 56        | 34.78%  |
| GDM3    | 5         | 3.11%   |
| LightDM | 3         | 1.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 78        | 48.45%  |
| de_DE  | 17        | 10.56%  |
| en_GB  | 12        | 7.45%   |
| ru_RU  | 7         | 4.35%   |
| it_IT  | 7         | 4.35%   |
| pl_PL  | 6         | 3.73%   |
| pt_BR  | 4         | 2.48%   |
| fr_FR  | 4         | 2.48%   |
| es_ES  | 2         | 1.24%   |
| en_NZ  | 2         | 1.24%   |
| en_CA  | 2         | 1.24%   |
| en_AU  | 2         | 1.24%   |
| zh_TW  | 1         | 0.62%   |
| zh_HK  | 1         | 0.62%   |
| sk_SK  | 1         | 0.62%   |
| pt_PT  | 1         | 0.62%   |
| nl_NL  | 1         | 0.62%   |
| nb_NO  | 1         | 0.62%   |
| hu_HU  | 1         | 0.62%   |
| fr_BE  | 1         | 0.62%   |
| es_PE  | 1         | 0.62%   |
| es_MX  | 1         | 0.62%   |
| es_CR  | 1         | 0.62%   |
| es_CL  | 1         | 0.62%   |
| es_419 | 1         | 0.62%   |
| en_PH  | 1         | 0.62%   |
| en_IN  | 1         | 0.62%   |
| en_DK  | 1         | 0.62%   |
| cs_CZ  | 1         | 0.62%   |
| C      | 1         | 0.62%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 84        | 51.85%  |
| EFI  | 78        | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 116       | 71.17%  |
| Tmpfs   | 32        | 19.63%  |
| Btrfs   | 7         | 4.29%   |
| Overlay | 5         | 3.07%   |
| Zfs     | 2         | 1.23%   |
| Xfs     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 100       | 62.11%  |
| Unknown | 56        | 34.78%  |
| MBR     | 5         | 3.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 94.41%  |
| Yes       | 9         | 5.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 117       | 72.67%  |
| Yes       | 44        | 27.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 38        | 23.6%   |
| Hewlett-Packard        | 31        | 19.25%  |
| ASUSTek Computer       | 20        | 12.42%  |
| Dell                   | 19        | 11.8%   |
| Acer                   | 13        | 8.07%   |
| Apple                  | 7         | 4.35%   |
| Google                 | 6         | 3.73%   |
| HUAWEI                 | 5         | 3.11%   |
| MSI                    | 4         | 2.48%   |
| Gigabyte Technology    | 3         | 1.86%   |
| Samsung Electronics    | 2         | 1.24%   |
| Valve                  | 1         | 0.62%   |
| Timi                   | 1         | 0.62%   |
| TECNO                  | 1         | 0.62%   |
| Sony                   | 1         | 0.62%   |
| Medion                 | 1         | 0.62%   |
| GPU Company            | 1         | 0.62%   |
| GPD                    | 1         | 0.62%   |
| Framework              | 1         | 0.62%   |
| CHIPHD                 | 1         | 0.62%   |
| BOSGAME                | 1         | 0.62%   |
| Avell High Performance | 1         | 0.62%   |
| Alienware              | 1         | 0.62%   |
| Unknown                | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW | 2         | 1.24%   |
| HP ProBook 650 G1                           | 2         | 1.24%   |
| Dell Latitude E5470                         | 2         | 1.24%   |
| Dell G3 3779                                | 2         | 1.24%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA      | 2         | 1.24%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI    | 2         | 1.24%   |
| Apple MacBookPro8,1                         | 2         | 1.24%   |
| Valve Jupiter                               | 1         | 0.62%   |
| Timi RedmiBook Pro 15                       | 1         | 0.62%   |
| TECNO MEGABOOK T1                           | 1         | 0.62%   |
| Sony VPCSA3J1E                              | 1         | 0.62%   |
| Samsung 950XED                              | 1         | 0.62%   |
| Samsung 730QCJ/730QCR                       | 1         | 0.62%   |
| MSI Titan GT77HX 13VH                       | 1         | 0.62%   |
| MSI Raider GE67HX 12UGS                     | 1         | 0.62%   |
| MSI GE75 Raider 9SE                         | 1         | 0.62%   |
| MSI Bravo 17 A4DDK                          | 1         | 0.62%   |
| Medion E11201                               | 1         | 0.62%   |
| Lenovo Yoga Slim 7 Pro 16ACH6 82QQ          | 1         | 0.62%   |
| Lenovo ThinkPad X270 W10DG 20K5S4K200       | 1         | 0.62%   |
| Lenovo ThinkPad X230 2325FG0                | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB0088RT | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007ART | 1         | 0.62%   |
| Lenovo ThinkPad W510 4391EC4                | 1         | 0.62%   |
| Lenovo ThinkPad P15s Gen 2i 20W7S0SM01      | 1         | 0.62%   |
| Lenovo ThinkPad P14s Gen 1 20S5S01V00       | 1         | 0.62%   |
| Lenovo ThinkPad P1 Gen 2 20QT000LGE         | 1         | 0.62%   |
| Lenovo ThinkPad L15 Gen 2a 20X7S05600       | 1         | 0.62%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100        | 1         | 0.62%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 0.62%   |
| Lenovo ThinkPad E15 Gen 2 20TD00GSPB        | 1         | 0.62%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000        | 1         | 0.62%   |
| Lenovo ThinkPad E14 Gen 3 20YDS02D00        | 1         | 0.62%   |
| Lenovo ThinkBook 14 G4 ABA 21DK             | 1         | 0.62%   |
| Lenovo Slim 7 ProX 14ARH7 82V2              | 1         | 0.62%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 0.62%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 1         | 0.62%   |
| Lenovo Legion 5 15ARH05H 82B1               | 1         | 0.62%   |
| Lenovo IdeaPad Y700-15ISK 80NV              | 1         | 0.62%   |
| Lenovo IdeaPad S340-14IIL 81VV              | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 16        | 9.94%   |
| Lenovo IdeaPad    | 15        | 9.32%   |
| Acer Aspire       | 9         | 5.59%   |
| HP EliteBook      | 7         | 4.35%   |
| Dell Latitude     | 7         | 4.35%   |
| ASUS VivoBook     | 6         | 3.73%   |
| HP Pavilion       | 5         | 3.11%   |
| ASUS ROG          | 5         | 3.11%   |
| HP ProBook        | 4         | 2.48%   |
| HP Laptop         | 4         | 2.48%   |
| Dell Precision    | 4         | 2.48%   |
| Lenovo Legion     | 3         | 1.86%   |
| HP ZBook          | 3         | 1.86%   |
| Dell XPS          | 3         | 1.86%   |
| Dell Inspiron     | 3         | 1.86%   |
| ASUS ASUS         | 3         | 1.86%   |
| HP ENVY           | 2         | 1.24%   |
| Gigabyte G5       | 2         | 1.24%   |
| Dell G3           | 2         | 1.24%   |
| ASUS Zenbook      | 2         | 1.24%   |
| Apple MacBookPro9 | 2         | 1.24%   |
| Apple MacBookPro8 | 2         | 1.24%   |
| Acer Nitro        | 2         | 1.24%   |
| Valve Jupiter     | 1         | 0.62%   |
| Timi RedmiBook    | 1         | 0.62%   |
| TECNO MEGABOOK    | 1         | 0.62%   |
| Sony VPCSA3J1E    | 1         | 0.62%   |
| Samsung 950XED    | 1         | 0.62%   |
| Samsung 730QCJ    | 1         | 0.62%   |
| MSI Titan         | 1         | 0.62%   |
| MSI Raider        | 1         | 0.62%   |
| MSI GE75          | 1         | 0.62%   |
| MSI Bravo         | 1         | 0.62%   |
| Medion E11201     | 1         | 0.62%   |
| Lenovo Yoga       | 1         | 0.62%   |
| Lenovo ThinkBook  | 1         | 0.62%   |
| Lenovo Slim       | 1         | 0.62%   |
| Lenovo G500       | 1         | 0.62%   |
| HUAWEI NBD-WXX9   | 1         | 0.62%   |
| HUAWEI KPL-W0X    | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 32        | 19.88%  |
| 2022 | 25        | 15.53%  |
| 2019 | 16        | 9.94%   |
| 2023 | 13        | 8.07%   |
| 2020 | 12        | 7.45%   |
| 2012 | 9         | 5.59%   |
| 2014 | 8         | 4.97%   |
| 2013 | 8         | 4.97%   |
| 2018 | 7         | 4.35%   |
| 2015 | 7         | 4.35%   |
| 2011 | 7         | 4.35%   |
| 2017 | 6         | 3.73%   |
| 2016 | 5         | 3.11%   |
| 2010 | 3         | 1.86%   |
| 2007 | 2         | 1.24%   |
| 2009 | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 161       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 146       | 90.68%  |
| Enabled  | 15        | 9.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 96.27%  |
| Yes  | 6         | 3.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 24.54%  |
| 8.01-16.0   | 40        | 24.54%  |
| 16.01-24.0  | 36        | 22.09%  |
| 32.01-64.0  | 19        | 11.66%  |
| 3.01-4.0    | 19        | 11.66%  |
| 64.01-256.0 | 5         | 3.07%   |
| 24.01-32.0  | 3         | 1.84%   |
| 2.01-3.0    | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 53        | 30.81%  |
| 2.01-3.0   | 47        | 27.33%  |
| 1.01-2.0   | 30        | 17.44%  |
| 3.01-4.0   | 26        | 15.12%  |
| 8.01-16.0  | 11        | 6.4%    |
| 16.01-24.0 | 2         | 1.16%   |
| 32.01-64.0 | 1         | 0.58%   |
| 24.01-32.0 | 1         | 0.58%   |
| 0.51-1.0   | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 65.85%  |
| 2      | 47        | 28.66%  |
| 3      | 9         | 5.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 81.99%  |
| Yes       | 29        | 18.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 69.33%  |
| No        | 50        | 30.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 98.76%  |
| No        | 2         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 90.06%  |
| No        | 16        | 9.94%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 28        | 17.39%  |
| Germany      | 22        | 13.66%  |
| UK           | 11        | 6.83%   |
| Russia       | 10        | 6.21%   |
| Poland       | 7         | 4.35%   |
| Italy        | 7         | 4.35%   |
| France       | 6         | 3.73%   |
| Brazil       | 5         | 3.11%   |
| Turkey       | 4         | 2.48%   |
| Canada       | 4         | 2.48%   |
| Belgium      | 4         | 2.48%   |
| Netherlands  | 3         | 1.86%   |
| Mexico       | 3         | 1.86%   |
| India        | 3         | 1.86%   |
| Hungary      | 3         | 1.86%   |
| Taiwan       | 2         | 1.24%   |
| Sweden       | 2         | 1.24%   |
| Spain        | 2         | 1.24%   |
| Slovakia     | 2         | 1.24%   |
| Portugal     | 2         | 1.24%   |
| Peru         | 2         | 1.24%   |
| New Zealand  | 2         | 1.24%   |
| Latvia       | 2         | 1.24%   |
| Australia    | 2         | 1.24%   |
| South Africa | 1         | 0.62%   |
| Saudi Arabia | 1         | 0.62%   |
| Philippines  | 1         | 0.62%   |
| Pakistan     | 1         | 0.62%   |
| Norway       | 1         | 0.62%   |
| Luxembourg   | 1         | 0.62%   |
| Lithuania    | 1         | 0.62%   |
| Libya        | 1         | 0.62%   |
| Kazakhstan   | 1         | 0.62%   |
| Ivory Coast  | 1         | 0.62%   |
| Israel       | 1         | 0.62%   |
| Georgia      | 1         | 0.62%   |
| Finland      | 1         | 0.62%   |
| Egypt        | 1         | 0.62%   |
| Czechia      | 1         | 0.62%   |
| Croatia      | 1         | 0.62%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Munich            | 5         | 2.99%   |
| Moscow            | 4         | 2.4%    |
| Istanbul          | 3         | 1.8%    |
| Berlin            | 3         | 1.8%    |
| Vienna            | 2         | 1.2%    |
| Philadelphia      | 2         | 1.2%    |
| Münster          | 2         | 1.2%    |
| Madrid            | 2         | 1.2%    |
| Brussels          | 2         | 1.2%    |
| Birmingham        | 2         | 1.2%    |
| Zhubei            | 1         | 0.6%    |
| Wooster           | 1         | 0.6%    |
| West Des Moines   | 1         | 0.6%    |
| Warsaw            | 1         | 0.6%    |
| Ware              | 1         | 0.6%    |
| Waianae           | 1         | 0.6%    |
| Vsevolozhsk       | 1         | 0.6%    |
| Vol'ginskiy       | 1         | 0.6%    |
| Viña del Mar     | 1         | 0.6%    |
| Vilnius           | 1         | 0.6%    |
| Villa Dominico    | 1         | 0.6%    |
| Venice            | 1         | 0.6%    |
| Valley Center     | 1         | 0.6%    |
| Ulm               | 1         | 0.6%    |
| Trujillo          | 1         | 0.6%    |
| Tripoli           | 1         | 0.6%    |
| Thunder Bay       | 1         | 0.6%    |
| Theydon Bois      | 1         | 0.6%    |
| Tel Aviv          | 1         | 0.6%    |
| Tbilisi           | 1         | 0.6%    |
| Taylorsville      | 1         | 0.6%    |
| Tatabánya        | 1         | 0.6%    |
| Szigetszentmiklos | 1         | 0.6%    |
| Szczecin          | 1         | 0.6%    |
| Sydney            | 1         | 0.6%    |
| Surrey            | 1         | 0.6%    |
| Sumter            | 1         | 0.6%    |
| Stavropol         | 1         | 0.6%    |
| St Petersburg     | 1         | 0.6%    |
| Sisak             | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 36        | 41     | 16.44%  |
| SanDisk                     | 21        | 23     | 9.59%   |
| WDC                         | 15        | 16     | 6.85%   |
| Micron Technology           | 14        | 17     | 6.39%   |
| Toshiba                     | 13        | 20     | 5.94%   |
| SK hynix                    | 12        | 12     | 5.48%   |
| Intel                       | 12        | 13     | 5.48%   |
| Kingston                    | 11        | 12     | 5.02%   |
| Seagate                     | 10        | 12     | 4.57%   |
| Crucial                     | 9         | 12     | 4.11%   |
| Unknown                     | 8         | 9      | 3.65%   |
| Phison Electronics          | 7         | 7      | 3.2%    |
| Silicon Motion              | 5         | 5      | 2.28%   |
| Hitachi                     | 4         | 5      | 1.83%   |
| Patriot                     | 3         | 3      | 1.37%   |
| KIOXIA                      | 3         | 3      | 1.37%   |
| A-DATA Technology           | 3         | 4      | 1.37%   |
| UMIS                        | 2         | 3      | 0.91%   |
| Transcend                   | 2         | 2      | 0.91%   |
| Solid State Storage         | 2         | 2      | 0.91%   |
| HGST                        | 2         | 3      | 0.91%   |
| Wibtek                      | 1         | 2      | 0.46%   |
| WALRAM                      | 1         | 1      | 0.46%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.46%   |
| Union Memory                | 1         | 1      | 0.46%   |
| TXRUI                       | 1         | 1      | 0.46%   |
| Team                        | 1         | 1      | 0.46%   |
| SSSTC                       | 1         | 1      | 0.46%   |
| SSDPR-CX                    | 1         | 1      | 0.46%   |
| SADAYU                      | 1         | 1      | 0.46%   |
| PNY                         | 1         | 1      | 0.46%   |
| Phison                      | 1         | 1      | 0.46%   |
| Netac                       | 1         | 1      | 0.46%   |
| Micron/Crucial Technology   | 1         | 1      | 0.46%   |
| LITEONIT                    | 1         | 1      | 0.46%   |
| Lexar                       | 1         | 1      | 0.46%   |
| Lenovo                      | 1         | 1      | 0.46%   |
| Kingston Technology Company | 1         | 1      | 0.46%   |
| KingFast                    | 1         | 1      | 0.46%   |
| JMicron Technology          | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel SSD 660P Series 512GB                           | 5         | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 4         | 1.78%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 3         | 1.33%   |
| Phison E16 PCIe4 NVMe Controller 500GB                | 3         | 1.33%   |
| Intel SSDPEKNU512GZ 512GB                             | 3         | 1.33%   |
| WDC WD10SPZX-24Z10 1TB                                | 2         | 0.89%   |
| Unknown SD/MMC/MS PRO 128GB                           | 2         | 0.89%   |
| Unknown MMC Card  32GB                                | 2         | 0.89%   |
| UMIS RPJTJ512MGE1QDQ 512GB                            | 2         | 0.89%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.89%   |
| Toshiba MQ01ACF050 500GB                              | 2         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.89%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB     | 2         | 0.89%   |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 0.89%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB          | 2         | 0.89%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 2         | 0.89%   |
| Sandisk WD Black SN850 1024GB                         | 2         | 0.89%   |
| SanDisk NVMe SSD Drive 2TB                            | 2         | 0.89%   |
| SanDisk NVMe SSD Drive 1TB                            | 2         | 0.89%   |
| Samsung SSD 980 500GB                                 | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 2         | 0.89%   |
| Samsung MZVLW256HEHP-000L2 256GB                      | 2         | 0.89%   |
| Samsung MZVLQ256HAJD-000H1 256GB                      | 2         | 0.89%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 2         | 0.89%   |
| Kingston SA400S37240G 240GB SSD                       | 2         | 0.89%   |
| Crucial CT1000MX500SSD1 1TB                           | 2         | 0.89%   |
| Crucial CT1000BX500SSD1 1TB                           | 2         | 0.89%   |
| Wibtek W800S 512GB SSD                                | 1         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 1         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1         | 0.44%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                      | 1         | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 0.44%   |
| WDC WDS100T2B0A 1TB SSD                               | 1         | 0.44%   |
| WDC WDBNCE5000PNC 500GB SSD                           | 1         | 0.44%   |
| WDC WD16 00AVBB-63SYA0 160GB                          | 1         | 0.44%   |
| WDC WD10 JPVX-00JC3T0 1TB                             | 1         | 0.44%   |
| WDC WD Blue SA510 2.5 1000GB                          | 1         | 0.44%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 1         | 0.44%   |
| WDC PC SN530 SDBPTPZ-1T00 1TB                         | 1         | 0.44%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                  | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 32.26%  |
| Toshiba | 9         | 14     | 29.03%  |
| WDC     | 4         | 4      | 12.9%   |
| Hitachi | 4         | 5      | 12.9%   |
| Unknown | 2         | 2      | 6.45%   |
| HGST    | 2         | 3      | 6.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 13.33%  |
| Crucial             | 8         | 10     | 13.33%  |
| SanDisk             | 7         | 8      | 11.67%  |
| WDC                 | 6         | 7      | 10%     |
| Micron Technology   | 5         | 7      | 8.33%   |
| Samsung Electronics | 4         | 4      | 6.67%   |
| Transcend           | 2         | 2      | 3.33%   |
| SK hynix            | 2         | 2      | 3.33%   |
| Patriot             | 2         | 2      | 3.33%   |
| Intel               | 2         | 3      | 3.33%   |
| Wibtek              | 1         | 2      | 1.67%   |
| Team                | 1         | 1      | 1.67%   |
| SADAYU              | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| LITEONIT            | 1         | 1      | 1.67%   |
| Lexar               | 1         | 1      | 1.67%   |
| Lenovo              | 1         | 1      | 1.67%   |
| JMicron Technology  | 1         | 1      | 1.67%   |
| Intenso             | 1         | 1      | 1.67%   |
| FURY                | 1         | 2      | 1.67%   |
| China               | 1         | 1      | 1.67%   |
| BAITITON            | 1         | 4      | 1.67%   |
| Apple               | 1         | 1      | 1.67%   |
| A-DATA Technology   | 1         | 1      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 102       | 130    | 51%     |
| SSD     | 56        | 72     | 28%     |
| HDD     | 30        | 40     | 15%     |
| MMC     | 6         | 7      | 3%      |
| Unknown | 6         | 7      | 3%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 102       | 130    | 52.85%  |
| SATA | 74        | 107    | 38.34%  |
| SAS  | 11        | 12     | 5.7%    |
| MMC  | 6         | 7      | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 66     | 59.04%  |
| 0.51-1.0   | 28        | 39     | 33.73%  |
| 1.01-2.0   | 4         | 5      | 4.82%   |
| 3.01-4.0   | 1         | 1      | 1.2%    |
| 4.01-10.0  | 1         | 1      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 28.48%  |
| 251-500        | 36        | 21.82%  |
| 501-1000       | 33        | 20%     |
| 1001-2000      | 19        | 11.52%  |
| 51-100         | 8         | 4.85%   |
| More than 3000 | 7         | 4.24%   |
| 1-20           | 6         | 3.64%   |
| 21-50          | 5         | 3.03%   |
| 2001-3000      | 4         | 2.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 41        | 24.12%  |
| 21-50          | 39        | 22.94%  |
| 101-250        | 30        | 17.65%  |
| 51-100         | 24        | 14.12%  |
| 251-500        | 12        | 7.06%   |
| 501-1000       | 12        | 7.06%   |
| 1001-2000      | 7         | 4.12%   |
| 2001-3000      | 4         | 2.35%   |
| More than 3000 | 1         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB              | 1         | 2      | 20%     |
| Team L3 EVO SSD 120GB                 | 1         | 1      | 20%     |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1         | 1      | 20%     |
| SanDisk SDSSDXPS480G 480GB            | 1         | 1      | 20%     |
| Intel SSDPEKNU512GZ 512GB             | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 1         | 2      | 20%     |
| Team     | 1         | 1      | 20%     |
| SK hynix | 1         | 1      | 20%     |
| SanDisk  | 1         | 1      | 20%     |
| Intel    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| HDD  | 1         | 2      | 20%     |

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
| Detected | 100       | 165    | 58.82%  |
| Works    | 65        | 85     | 38.24%  |
| Malfunc  | 5         | 6      | 2.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 87        | 40.47%  |
| Samsung Electronics            | 33        | 15.35%  |
| AMD                            | 22        | 10.23%  |
| SanDisk                        | 18        | 8.37%   |
| SK hynix                       | 10        | 4.65%   |
| Micron Technology              | 9         | 4.19%   |
| Phison Electronics             | 8         | 3.72%   |
| Silicon Motion                 | 5         | 2.33%   |
| Union Memory (Shenzhen)        | 4         | 1.86%   |
| Toshiba America Info Systems   | 4         | 1.86%   |
| Kingston Technology Company    | 4         | 1.86%   |
| Solid State Storage Technology | 3         | 1.4%    |
| KIOXIA                         | 3         | 1.4%    |
| Micron/Crucial Technology      | 2         | 0.93%   |
| ADATA Technology               | 2         | 0.93%   |
| Biwin Storage Technology       | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 9.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 5.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 4.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 3.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 3.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 3.11%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 2.67%   |
| Intel SSD 660P Series                                                          | 6         | 2.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.22%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4         | 1.78%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.33%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.33%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1.33%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.33%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.33%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 2         | 0.89%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.89%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.89%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 2         | 0.89%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.89%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.89%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 2         | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.89%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 102       | 48.11%  |
| SATA | 92        | 43.4%   |
| RAID | 17        | 8.02%   |
| IDE  | 1         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 71.43%  |
| AMD    | 46        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 4.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 2.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.86%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 1.86%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 1.86%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 1.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.86%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.86%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.86%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 1.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.24%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.24%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.24%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.24%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.24%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.24%   |
| Intel 12th Gen Core i5-1235U                  | 2         | 1.24%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.24%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.24%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 2         | 1.24%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.62%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.62%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.62%   |
| Intel Pentium CPU 6405U @ 2.40GHz             | 1         | 0.62%   |
| Intel N95                                     | 1         | 0.62%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.62%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.62%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.62%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.62%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.62%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.62%   |
| Intel Core i7-4610M CPU @ 3.00GHz             | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 22.36%  |
| Other                   | 35        | 21.74%  |
| Intel Core i7           | 24        | 14.91%  |
| AMD Ryzen 5             | 18        | 11.18%  |
| AMD Ryzen 7             | 15        | 9.32%   |
| Intel Celeron           | 9         | 5.59%   |
| Intel Core i3           | 7         | 4.35%   |
| AMD Ryzen 9             | 4         | 2.48%   |
| Intel Pentium Dual-Core | 2         | 1.24%   |
| AMD A4                  | 2         | 1.24%   |
| Intel Pentium Silver    | 1         | 0.62%   |
| Intel Pentium           | 1         | 0.62%   |
| Intel Core 2 Duo        | 1         | 0.62%   |
| AMD Ryzen 7 PRO         | 1         | 0.62%   |
| AMD Ryzen 5 PRO         | 1         | 0.62%   |
| AMD Ryzen 3             | 1         | 0.62%   |
| AMD PRO A10             | 1         | 0.62%   |
| AMD A8                  | 1         | 0.62%   |
| AMD A6                  | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 57        | 35.4%   |
| 2      | 45        | 27.95%  |
| 8      | 21        | 13.04%  |
| 6      | 19        | 11.8%   |
| 12     | 6         | 3.73%   |
| 10     | 5         | 3.11%   |
| 14     | 4         | 2.48%   |
| 24     | 2         | 1.24%   |
| 16     | 2         | 1.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 138       | 85.71%  |
| 1      | 23        | 14.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 161       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 83.33%  |
| 0x0a50000c | 9         | 5.56%   |
| 0x0a404102 | 4         | 2.47%   |
| 0x0a404101 | 2         | 1.23%   |
| 0x08608103 | 2         | 1.23%   |
| 0x08108109 | 2         | 1.23%   |
| 0x90672    | 1         | 0.62%   |
| 0x0a601203 | 1         | 0.62%   |
| 0x0a50000d | 1         | 0.62%   |
| 0x08900201 | 1         | 0.62%   |
| 0x08600104 | 1         | 0.62%   |
| 0x08108102 | 1         | 0.62%   |
| 0x08101016 | 1         | 0.62%   |
| 0x03000027 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 28        | 17.39%  |
| KabyLake         | 22        | 13.66%  |
| Zen 3            | 13        | 8.07%   |
| Alderlake Hybrid | 12        | 7.45%   |
| TigerLake        | 11        | 6.83%   |
| Skylake          | 11        | 6.83%   |
| IvyBridge        | 11        | 6.83%   |
| SandyBridge      | 8         | 4.97%   |
| Haswell          | 8         | 4.97%   |
| Zen+             | 7         | 4.35%   |
| Zen 2            | 4         | 2.48%   |
| CometLake        | 4         | 2.48%   |
| Broadwell        | 4         | 2.48%   |
| Goldmont         | 3         | 1.86%   |
| Puma             | 2         | 1.24%   |
| Penryn           | 2         | 1.24%   |
| IceLake          | 2         | 1.24%   |
| Goldmont plus    | 2         | 1.24%   |
| Excavator        | 2         | 1.24%   |
| Zen              | 1         | 0.62%   |
| Westmere         | 1         | 0.62%   |
| Nehalem          | 1         | 0.62%   |
| K10 Llano        | 1         | 0.62%   |
| Core             | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 111       | 51.15%  |
| AMD    | 56        | 25.81%  |
| Nvidia | 50        | 23.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 5.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 9         | 4.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 8         | 3.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 7         | 3.2%    |
| AMD Rembrandt [Radeon 680M]                                                   | 7         | 3.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 7         | 3.2%    |
| AMD Lucienne                                                                  | 7         | 3.2%    |
| Intel HD Graphics 530                                                         | 6         | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 6         | 2.74%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 6         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 2.74%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 2.28%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 5         | 2.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 2.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 1.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.83%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 4         | 1.83%   |
| AMD Barcelo                                                                   | 4         | 1.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 1.37%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 3         | 1.37%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 3         | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 1.37%   |
| Intel HD Graphics 620                                                         | 3         | 1.37%   |
| Intel HD Graphics 500                                                         | 3         | 1.37%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.91%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.91%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 2         | 0.91%   |
| Nvidia GK104GLM [Quadro K3100M]                                               | 2         | 0.91%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 0.91%   |
| Intel Raptor Lake-S UHD Graphics                                              | 2         | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.91%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 0.91%   |
| Intel HD Graphics 630                                                         | 2         | 0.91%   |
| Intel HD Graphics 5500                                                        | 2         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 0.91%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 2         | 0.91%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                    | 2         | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 40.37%  |
| Intel + Nvidia | 37        | 22.98%  |
| 1 x AMD        | 35        | 21.74%  |
| AMD + Nvidia   | 12        | 7.45%   |
| Intel + AMD    | 7         | 4.35%   |
| 2 x AMD        | 2         | 1.24%   |
| Other          | 1         | 0.62%   |
| 2 x Intel      | 1         | 0.62%   |
| 1 x Nvidia     | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 123       | 75.46%  |
| Proprietary | 39        | 23.93%  |
| Unknown     | 1         | 0.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 75.46%  |
| 0.01-0.5   | 13        | 7.98%   |
| 3.01-4.0   | 11        | 6.75%   |
| 0.51-1.0   | 7         | 4.29%   |
| 1.01-2.0   | 6         | 3.68%   |
| 7.01-8.0   | 2         | 1.23%   |
| 5.01-6.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 37        | 19.07%  |
| AU Optronics            | 35        | 18.04%  |
| Chimei Innolux          | 25        | 12.89%  |
| Samsung Electronics     | 24        | 12.37%  |
| LG Display              | 16        | 8.25%   |
| Apple                   | 7         | 3.61%   |
| Goldstar                | 6         | 3.09%   |
| Sharp                   | 5         | 2.58%   |
| PANDA                   | 5         | 2.58%   |
| Dell                    | 5         | 2.58%   |
| Philips                 | 3         | 1.55%   |
| Lenovo                  | 3         | 1.55%   |
| InfoVision              | 3         | 1.55%   |
| SAC                     | 2         | 1.03%   |
| Chi Mei Optoelectronics | 2         | 1.03%   |
| AOC                     | 2         | 1.03%   |
| ViewSonic               | 1         | 0.52%   |
| Valve                   | 1         | 0.52%   |
| UGD                     | 1         | 0.52%   |
| TMX                     | 1         | 0.52%   |
| STA                     | 1         | 0.52%   |
| Panasonic               | 1         | 0.52%   |
| MSI                     | 1         | 0.52%   |
| LOE                     | 1         | 0.52%   |
| KDC                     | 1         | 0.52%   |
| KDB                     | 1         | 0.52%   |
| Denver                  | 1         | 0.52%   |
| CSO                     | 1         | 0.52%   |
| AGO                     | 1         | 0.52%   |
| Acer                    | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 1.55%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 1.03%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                 | 2         | 1.03%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 1.03%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 2         | 1.03%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch             | 1         | 0.52%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.52%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 0.52%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.52%   |
| STA SEMP LEDTV STA0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.52%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.52%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch   | 1         | 0.52%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 1         | 0.52%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch  | 1         | 0.52%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch     | 1         | 0.52%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 84        | 46.15%  |
| 1366x768 (WXGA)   | 34        | 18.68%  |
| 2560x1440 (QHD)   | 11        | 6.04%   |
| 3840x2160 (4K)    | 10        | 5.49%   |
| 2560x1600         | 6         | 3.3%    |
| 1600x900 (HD+)    | 5         | 2.75%   |
| 2880x1800         | 4         | 2.2%    |
| 2560x1080         | 3         | 1.65%   |
| 1280x800 (WXGA)   | 3         | 1.65%   |
| 3840x2400         | 2         | 1.1%    |
| 3440x1440         | 2         | 1.1%    |
| 2240x1400         | 2         | 1.1%    |
| 1920x540          | 2         | 1.1%    |
| 1920x1200 (WUXGA) | 2         | 1.1%    |
| 1440x900 (WXGA+)  | 2         | 1.1%    |
| 800x1280          | 1         | 0.55%   |
| 3840x1100         | 1         | 0.55%   |
| 3456x2160         | 1         | 0.55%   |
| 3200x2000         | 1         | 0.55%   |
| 3072x1920         | 1         | 0.55%   |
| 2256x1504         | 1         | 0.55%   |
| 2160x1440         | 1         | 0.55%   |
| 1920x1280         | 1         | 0.55%   |
| 1280x720 (HD)     | 1         | 0.55%   |
| 1280x1024 (SXGA)  | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 67        | 34.72%  |
| 14      | 28        | 14.51%  |
| 13      | 24        | 12.44%  |
| 17      | 23        | 11.92%  |
| 27      | 6         | 3.11%   |
| 24      | 6         | 3.11%   |
| 16      | 6         | 3.11%   |
| 12      | 5         | 2.59%   |
| 34      | 4         | 2.07%   |
| 31      | 4         | 2.07%   |
| 11      | 4         | 2.07%   |
| 23      | 3         | 1.55%   |
| 21      | 3         | 1.55%   |
| 72      | 1         | 0.52%   |
| 65      | 1         | 0.52%   |
| 54      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 37      | 1         | 0.52%   |
| 28      | 1         | 0.52%   |
| 20      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| 7       | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 113       | 59.16%  |
| 351-400     | 25        | 13.09%  |
| 201-300     | 18        | 9.42%   |
| 501-600     | 15        | 7.85%   |
| 601-700     | 5         | 2.62%   |
| 401-500     | 4         | 2.09%   |
| 801-900     | 3         | 1.57%   |
| 701-800     | 3         | 1.57%   |
| 1001-1500   | 2         | 1.05%   |
| 1501-2000   | 1         | 0.52%   |
| 1-100       | 1         | 0.52%   |
| Unknown     | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 135       | 78.49%  |
| 16/10 | 26        | 15.12%  |
| 21/9  | 4         | 2.33%   |
| 3/2   | 3         | 1.74%   |
| 5/4   | 1         | 0.58%   |
| 4/3   | 1         | 0.58%   |
| 3.40  | 1         | 0.58%   |
| 0.67  | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 34.72%  |
| 81-90          | 44        | 22.8%   |
| 121-130        | 23        | 11.92%  |
| 201-250        | 10        | 5.18%   |
| 351-500        | 8         | 4.15%   |
| 301-350        | 7         | 3.63%   |
| 71-80          | 6         | 3.11%   |
| 111-120        | 6         | 3.11%   |
| 51-60          | 5         | 2.59%   |
| More than 1000 | 3         | 1.55%   |
| 61-70          | 3         | 1.55%   |
| 91-100         | 3         | 1.55%   |
| 251-300        | 2         | 1.04%   |
| 151-200        | 2         | 1.04%   |
| 501-1000       | 2         | 1.04%   |
| 1-40           | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 88        | 46.81%  |
| 101-120       | 38        | 20.21%  |
| 51-100        | 24        | 12.77%  |
| 161-240       | 22        | 11.7%   |
| More than 240 | 12        | 6.38%   |
| 1-50          | 3         | 1.6%    |
| Unknown       | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 124       | 76.54%  |
| 2     | 36        | 22.22%  |
| 3     | 1         | 0.62%   |
| 0     | 1         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 34.57%  |
| Realtek Semiconductor | 83        | 34.16%  |
| Qualcomm Atheros      | 17        | 7%      |
| MediaTek              | 16        | 6.58%   |
| Broadcom              | 13        | 5.35%   |
| Broadcom Limited      | 5         | 2.06%   |
| Ralink                | 4         | 1.65%   |
| Hewlett-Packard       | 4         | 1.65%   |
| ASIX Electronics      | 4         | 1.65%   |
| Samsung Electronics   | 2         | 0.82%   |
| Qualcomm              | 2         | 0.82%   |
| ZyXEL Communications  | 1         | 0.41%   |
| Xiaomi                | 1         | 0.41%   |
| Microsoft             | 1         | 0.41%   |
| Lenovo                | 1         | 0.41%   |
| ICS Advent            | 1         | 0.41%   |
| Huawei Technologies   | 1         | 0.41%   |
| Google                | 1         | 0.41%   |
| DisplayLink           | 1         | 0.41%   |
| Dell                  | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 15.38%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 3.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.45%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.45%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 2.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 6         | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.75%   |
| Intel Wireless 8260                                               | 5         | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 5         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 4         | 1.4%    |
| Intel Wireless 7265                                               | 4         | 1.4%    |
| Intel Wireless 7260                                               | 4         | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.4%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 1.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.7%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.7%    |
| Intel Wireless 3165                                               | 2         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 83        | 50.3%   |
| Realtek Semiconductor | 27        | 16.36%  |
| MediaTek              | 16        | 9.7%    |
| Qualcomm Atheros      | 15        | 9.09%   |
| Broadcom              | 11        | 6.67%   |
| Ralink                | 4         | 2.42%   |
| Broadcom Limited      | 3         | 1.82%   |
| Hewlett-Packard       | 2         | 1.21%   |
| ZyXEL Communications  | 1         | 0.61%   |
| Qualcomm              | 1         | 0.61%   |
| Microsoft             | 1         | 0.61%   |
| Dell                  | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 10        | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 8         | 4.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 4.24%   |
| Intel Wi-Fi 6 AX201                                                  | 7         | 4.24%   |
| Intel Wi-Fi 6 AX200                                                  | 7         | 4.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 7         | 4.24%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 6         | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 3.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 5         | 3.03%   |
| Intel Wireless 8260                                                  | 5         | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 5         | 3.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 5         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 5         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 5         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 3.03%   |
| Intel Wireless 8265 / 8275                                           | 4         | 2.42%   |
| Intel Wireless 7265                                                  | 4         | 2.42%   |
| Intel Wireless 7260                                                  | 4         | 2.42%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 2.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 3         | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 2         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.21%   |
| Intel Wireless 3165                                                  | 2         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.21%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 1.21%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 2         | 1.21%   |
| HP lt4112 Gobi 4G Module Network Device                              | 2         | 1.21%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.21%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 1.21%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                        | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.61%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 69        | 58.47%  |
| Intel                 | 23        | 19.49%  |
| Broadcom              | 6         | 5.08%   |
| Qualcomm Atheros      | 5         | 4.24%   |
| ASIX Electronics      | 4         | 3.39%   |
| Samsung Electronics   | 2         | 1.69%   |
| Broadcom Limited      | 2         | 1.69%   |
| Xiaomi                | 1         | 0.85%   |
| Qualcomm              | 1         | 0.85%   |
| Lenovo                | 1         | 0.85%   |
| ICS Advent            | 1         | 0.85%   |
| Huawei Technologies   | 1         | 0.85%   |
| Google                | 1         | 0.85%   |
| DisplayLink           | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 36.97%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 7.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 3.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 3.36%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.68%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.84%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.84%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.84%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.84%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.84%   |
| Intel Ethernet Controller I219-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.84%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.84%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.84%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.84%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.84%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.84%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.84%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.84%   |
| Huawei MAR-LX1M                                                   | 1         | 0.84%   |
| Google Pixel 7                                                    | 1         | 0.84%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.84%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 58.46%  |
| Ethernet | 111       | 40.81%  |
| Modem    | 2         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 83.54%  |
| Ethernet | 27        | 16.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 97        | 60.25%  |
| 1     | 63        | 39.13%  |
| 0     | 1         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 71.34%  |
| Yes  | 47        | 28.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 51.72%  |
| Realtek Semiconductor           | 19        | 13.1%   |
| IMC Networks                    | 10        | 6.9%    |
| Lite-On Technology              | 7         | 4.83%   |
| Foxconn / Hon Hai               | 7         | 4.83%   |
| Apple                           | 7         | 4.83%   |
| Qualcomm Atheros Communications | 6         | 4.14%   |
| Broadcom                        | 6         | 4.14%   |
| Realtek                         | 2         | 1.38%   |
| Ralink                          | 2         | 1.38%   |
| Toshiba                         | 1         | 0.69%   |
| Foxconn International           | 1         | 0.69%   |
| Dell                            | 1         | 0.69%   |
| Cambridge Silicon Radio         | 1         | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 13.79%  |
| Intel AX201 Bluetooth                               | 16        | 11.03%  |
| Intel Bluetooth Device                              | 15        | 10.34%  |
| Realtek Bluetooth Radio                             | 14        | 9.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 6.9%    |
| Intel AX200 Bluetooth                               | 7         | 4.83%   |
| Intel AX210 Bluetooth                               | 5         | 3.45%   |
| IMC Networks Wireless_Device                        | 5         | 3.45%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.76%   |
| Lite-On Wireless_Device                             | 4         | 2.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.07%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.07%   |
| Apple Bluetooth USB Host Controller                 | 3         | 2.07%   |
| Apple Bluetooth Host Controller                     | 3         | 2.07%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.38%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.38%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.38%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.69%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.69%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.69%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.69%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.69%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.69%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.69%   |
| Broadcom BCM20702A0                                 | 1         | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 114       | 56.16%  |
| AMD                      | 49        | 24.14%  |
| Nvidia                   | 31        | 15.27%  |
| Realtek Semiconductor    | 2         | 0.99%   |
| Hewlett-Packard          | 2         | 0.99%   |
| C-Media Electronics      | 2         | 0.99%   |
| Nordic Semiconductor ASA | 1         | 0.49%   |
| Lenovo                   | 1         | 0.49%   |
| GN Netcom                | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 15.08%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 20        | 7.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 5.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 4.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 3.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 2.78%   |
| Nvidia Audio device                                                        | 6         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.98%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 5         | 1.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.59%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.19%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.19%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.79%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.79%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 30.69%  |
| SK hynix            | 21        | 20.79%  |
| Micron Technology   | 21        | 20.79%  |
| Kingston            | 5         | 4.95%   |
| Ramaxel Technology  | 4         | 3.96%   |
| Crucial             | 4         | 3.96%   |
| Unknown             | 3         | 2.97%   |
| Unknown (ABCD)      | 2         | 1.98%   |
| A-DATA Technology   | 2         | 1.98%   |
| Transcend           | 1         | 0.99%   |
| Timetec             | 1         | 0.99%   |
| GOODRAM             | 1         | 0.99%   |
| G.Skill             | 1         | 0.99%   |
| fef5                | 1         | 0.99%   |
| Corsair             | 1         | 0.99%   |
| 4ea5                | 1         | 0.99%   |
| Unknown             | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 3         | 2.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 3         | 2.83%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.89%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s        | 2         | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.89%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s              | 2         | 1.89%   |
| Micron RAM 4ATF51264HZ_3G2J1 4GB Row Of Chips DDR4 3200MT/s       | 2         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 2         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 2         | 1.89%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 1         | 0.94%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                             | 1         | 0.94%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s               | 1         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 1         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 0.94%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s             | 1         | 0.94%   |
| Timetec RAM S16G-3200 16GB SODIMM DDR4 2133MT/s                   | 1         | 0.94%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.94%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s            | 1         | 0.94%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s             | 1         | 0.94%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s             | 1         | 0.94%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 1         | 0.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB Row Of Chips DDR4 2400MT/s      | 1         | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 1         | 0.94%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.94%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s        | 1         | 0.94%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s  | 1         | 0.94%   |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s      | 1         | 0.94%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                       | 1         | 0.94%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s               | 1         | 0.94%   |
| Samsung RAM Module 16GB SODIMM DDR5 5600MT/s                      | 1         | 0.94%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 0.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 38        | 43.68%  |
| DDR3    | 17        | 19.54%  |
| LPDDR5  | 11        | 12.64%  |
| LPDDR4  | 9         | 10.34%  |
| DDR5    | 8         | 9.2%    |
| LPDDR3  | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 69.32%  |
| Row Of Chips | 23        | 26.14%  |
| Unknown      | 3         | 3.41%   |
| DIMM         | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 40        | 43.01%  |
| 4096  | 31        | 33.33%  |
| 16384 | 12        | 12.9%   |
| 2048  | 5         | 5.38%   |
| 32768 | 3         | 3.23%   |
| 12288 | 1         | 1.08%   |
| 1024  | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 23        | 26.14%  |
| 1600    | 12        | 13.64%  |
| 2667    | 11        | 12.5%   |
| 6400    | 9         | 10.23%  |
| 2400    | 8         | 9.09%   |
| 4800    | 6         | 6.82%   |
| 4267    | 3         | 3.41%   |
| 2133    | 3         | 3.41%   |
| 1333    | 3         | 3.41%   |
| 5600    | 2         | 2.27%   |
| 7467    | 1         | 1.14%   |
| 4266    | 1         | 1.14%   |
| 3733    | 1         | 1.14%   |
| 3266    | 1         | 1.14%   |
| 1867    | 1         | 1.14%   |
| 1334    | 1         | 1.14%   |
| 800     | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P1006        | 1         | 33.33%  |
| Canon PIXMA MX490 Series | 1         | 33.33%  |
| Canon LBP6020            | 1         | 33.33%  |

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
| Chicony Electronics                    | 27        | 19.29%  |
| Quanta                                 | 14        | 10%     |
| IMC Networks                           | 14        | 10%     |
| Realtek Semiconductor                  | 11        | 7.86%   |
| Bison Electronics                      | 11        | 7.86%   |
| Syntek                                 | 9         | 6.43%   |
| Microdia                               | 9         | 6.43%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 6.43%   |
| Sunplus Innovation Technology          | 8         | 5.71%   |
| Apple                                  | 6         | 4.29%   |
| Luxvisions Innotech Limited            | 4         | 2.86%   |
| Lite-On Technology                     | 3         | 2.14%   |
| Acer                                   | 3         | 2.14%   |
| SunplusIT                              | 2         | 1.43%   |
| Suyin                                  | 1         | 0.71%   |
| Sonix Technology                       | 1         | 0.71%   |
| Silicon Motion                         | 1         | 0.71%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.71%   |
| Ricoh                                  | 1         | 0.71%   |
| Primax Electronics                     | 1         | 0.71%   |
| OYT Tech                               | 1         | 0.71%   |
| Logitech                               | 1         | 0.71%   |
| Lenovo                                 | 1         | 0.71%   |
| Alcor Micro                            | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                        | 8         | 5.63%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 8         | 5.63%   |
| Chicony Integrated Camera                                       | 8         | 5.63%   |
| Bison Integrated Camera                                         | 5         | 3.52%   |
| Sunplus Integrated_Webcam_HD                                    | 4         | 2.82%   |
| Realtek HP Truevision HD                                        | 4         | 2.82%   |
| Apple FaceTime HD Camera                                        | 4         | 2.82%   |
| Quanta USB2.0 HD UVC WebCam                                     | 3         | 2.11%   |
| Quanta HD User Facing                                           | 3         | 2.11%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 2.11%   |
| Bison HD Webcam                                                 | 3         | 2.11%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 1.41%   |
| Microdia Integrated_Webcam_FHD                                  | 2         | 1.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 2         | 1.41%   |
| Chicony HP TrueVision HD                                        | 2         | 1.41%   |
| Chicony HD WebCam                                               | 2         | 1.41%   |
| Chicony 720p HD Camera                                          | 2         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 1.41%   |
| Bison Integrated RGB Camera                                     | 2         | 1.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 2         | 1.41%   |
| Syntek Lenovo EasyCamera                                        | 1         | 0.7%    |
| Suyin 1.3M HD WebCam                                            | 1         | 0.7%    |
| SunplusIT USB Camera                                            | 1         | 0.7%    |
| SunplusIT 1080p FHD Camera                                      | 1         | 0.7%    |
| Sunplus XiaoMi USB 2.0 Webcam                                   | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 1         | 0.7%    |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.7%    |
| Sunplus 1.3M HD WebCam                                          | 1         | 0.7%    |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.7%    |
| Silicon Motion HP Webcam-101                                    | 1         | 0.7%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                 | 1         | 0.7%    |
| Ricoh USB2.0 Camera                                             | 1         | 0.7%    |
| Realtek USB Camera                                              | 1         | 0.7%    |
| Realtek Laptop Camera                                           | 1         | 0.7%    |
| Realtek Integrated Webcam                                       | 1         | 0.7%    |
| Realtek HP Truevision HD integrated webcam                      | 1         | 0.7%    |
| Realtek HP "Truevision HD" laptop camera                        | 1         | 0.7%    |
| Quanta ov9734_techfront_camera                                  | 1         | 0.7%    |
| Quanta HP Wide Vision HD Camera                                 | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 9         | 37.5%   |
| Synaptics                          | 6         | 25%     |
| Shenzhen Goodix Technology         | 5         | 20.83%  |
| Samsung Electronics                | 1         | 4.17%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 4.17%   |
| Elan Microelectronics              | 1         | 4.17%   |
| AuthenTec                          | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 20.83%  |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor                       | 3         | 12.5%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 4.17%   |
| Samsung Fingerprint Sensor Device - 730B                        | 1         | 4.17%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                                | 1         | 4.17%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Broadcom     | 6         | 54.55%  |
| Alcor Micro  | 2         | 18.18%  |
| O2 Micro     | 1         | 9.09%   |
| Lenovo       | 1         | 9.09%   |
| Aladdin R.D. | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 9.09%   |
| Aladdin R.D. JaCarta                                                         | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 101       | 62.73%  |
| 1     | 51        | 31.68%  |
| 2     | 9         | 5.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 24        | 35.29%  |
| Chipcard              | 10        | 14.71%  |
| Multimedia controller | 9         | 13.24%  |
| Graphics card         | 7         | 10.29%  |
| Net/wireless          | 6         | 8.82%   |
| Camera                | 6         | 8.82%   |
| Sound                 | 2         | 2.94%   |
| Bluetooth             | 2         | 2.94%   |
| Storage               | 1         | 1.47%   |
| Card reader           | 1         | 1.47%   |


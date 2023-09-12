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

Total: 158

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 6.2.0-20-generic        | 53        | 39.85%  |
| 6.2.0-26-generic        | 16        | 12.03%  |
| 6.2.0-24-generic        | 9         | 6.77%   |
| 6.2.0-23-generic        | 9         | 6.77%   |
| 6.2.0-27-generic        | 8         | 6.02%   |
| 6.2.0-25-generic        | 4         | 3.01%   |
| 6.2.0-18-generic        | 3         | 2.26%   |
| 6.4.8-060408-generic    | 2         | 1.5%    |
| 6.2.0-32-generic        | 2         | 1.5%    |
| 6.2.0-31-generic        | 2         | 1.5%    |
| 6.2.0-1009-lowlatency   | 2         | 1.5%    |
| 6.2.0-1007-lowlatency   | 2         | 1.5%    |
| 6.2.0-1005-lowlatency   | 2         | 1.5%    |
| 6.4.0-060400-generic    | 1         | 0.75%   |
| 6.3.8-x64v3-xanmod1     | 1         | 0.75%   |
| 6.3.8                   | 1         | 0.75%   |
| 6.3.7-060307-generic    | 1         | 0.75%   |
| 6.3.6-custom            | 1         | 0.75%   |
| 6.3.4-060304-generic    | 1         | 0.75%   |
| 6.3.3-060303-generic    | 1         | 0.75%   |
| 6.3.1-060301-generic    | 1         | 0.75%   |
| 6.2.10-060210-generic   | 1         | 0.75%   |
| 6.2.0-21-generic        | 1         | 0.75%   |
| 6.2.0-1011-lowlatency   | 1         | 0.75%   |
| 6.2.0-1008-lowlatency   | 1         | 0.75%   |
| 6.1.12-060112-generic   | 1         | 0.75%   |
| 6.1.0-14-generic        | 1         | 0.75%   |
| 6.1.0-060100rc4-generic | 1         | 0.75%   |
| 5.19.0-42-generic       | 1         | 0.75%   |
| 5.19.0-40-generic       | 1         | 0.75%   |
| 5.19.0-28-generic       | 1         | 0.75%   |
| 5.19.0-21-generic       | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 107       | 85.6%   |
| 5.19.0  | 4         | 3.2%    |
| 6.4.8   | 2         | 1.6%    |
| 6.3.8   | 2         | 1.6%    |
| 6.1.0   | 2         | 1.6%    |
| 6.4.0   | 1         | 0.8%    |
| 6.3.7   | 1         | 0.8%    |
| 6.3.6   | 1         | 0.8%    |
| 6.3.4   | 1         | 0.8%    |
| 6.3.3   | 1         | 0.8%    |
| 6.3.1   | 1         | 0.8%    |
| 6.2.10  | 1         | 0.8%    |
| 6.1.12  | 1         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 108       | 86.4%   |
| 6.3     | 7         | 5.6%    |
| 5.19    | 4         | 3.2%    |
| 6.4     | 3         | 2.4%    |
| 6.1     | 3         | 2.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 124       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 120       | 96.77%  |
| KDE   | 3         | 2.42%   |
| GNOME | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 102       | 82.26%  |
| Wayland | 21        | 16.94%  |
| Tty     | 1         | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 72        | 58.06%  |
| Unknown | 46        | 37.1%   |
| GDM3    | 4         | 3.23%   |
| LightDM | 2         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 63        | 50.81%  |
| de_DE  | 13        | 10.48%  |
| en_GB  | 7         | 5.65%   |
| pl_PL  | 6         | 4.84%   |
| ru_RU  | 5         | 4.03%   |
| pt_BR  | 4         | 3.23%   |
| it_IT  | 4         | 3.23%   |
| fr_FR  | 3         | 2.42%   |
| en_NZ  | 2         | 1.61%   |
| en_AU  | 2         | 1.61%   |
| zh_HK  | 1         | 0.81%   |
| pt_PT  | 1         | 0.81%   |
| nl_NL  | 1         | 0.81%   |
| nb_NO  | 1         | 0.81%   |
| hu_HU  | 1         | 0.81%   |
| fr_BE  | 1         | 0.81%   |
| es_PE  | 1         | 0.81%   |
| es_ES  | 1         | 0.81%   |
| es_CR  | 1         | 0.81%   |
| es_CL  | 1         | 0.81%   |
| es_419 | 1         | 0.81%   |
| en_IN  | 1         | 0.81%   |
| en_DK  | 1         | 0.81%   |
| en_CA  | 1         | 0.81%   |
| C      | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 68        | 54.4%   |
| EFI  | 57        | 45.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 69.05%  |
| Tmpfs   | 25        | 19.84%  |
| Btrfs   | 7         | 5.56%   |
| Overlay | 4         | 3.17%   |
| Zfs     | 2         | 1.59%   |
| Xfs     | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 75        | 60.48%  |
| Unknown | 46        | 37.1%   |
| MBR     | 3         | 2.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 97.58%  |
| Yes       | 3         | 2.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 75.81%  |
| Yes       | 30        | 24.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 30        | 24.19%  |
| Hewlett-Packard        | 24        | 19.35%  |
| ASUSTek Computer       | 17        | 13.71%  |
| Dell                   | 15        | 12.1%   |
| Acer                   | 10        | 8.06%   |
| HUAWEI                 | 4         | 3.23%   |
| Google                 | 4         | 3.23%   |
| Apple                  | 4         | 3.23%   |
| MSI                    | 3         | 2.42%   |
| Gigabyte Technology    | 3         | 2.42%   |
| TECNO                  | 1         | 0.81%   |
| Samsung Electronics    | 1         | 0.81%   |
| Medion                 | 1         | 0.81%   |
| GPU Company            | 1         | 0.81%   |
| GPD                    | 1         | 0.81%   |
| Framework              | 1         | 0.81%   |
| BOSGAME                | 1         | 0.81%   |
| Avell High Performance | 1         | 0.81%   |
| Alienware              | 1         | 0.81%   |
| Unknown                | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP ProBook 650 G1                           | 2         | 1.61%   |
| Dell G3 3779                                | 2         | 1.61%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI    | 2         | 1.61%   |
| TECNO MEGABOOK T1                           | 1         | 0.81%   |
| Samsung 950XED                              | 1         | 0.81%   |
| MSI Titan GT77HX 13VH                       | 1         | 0.81%   |
| MSI Raider GE67HX 12UGS                     | 1         | 0.81%   |
| MSI Bravo 17 A4DDK                          | 1         | 0.81%   |
| Medion E11201                               | 1         | 0.81%   |
| Lenovo Yoga Slim 7 Pro 16ACH6 82QQ          | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB0088RT | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007ART | 1         | 0.81%   |
| Lenovo ThinkPad W510 4391EC4                | 1         | 0.81%   |
| Lenovo ThinkPad P15s Gen 2i 20W7S0SM01      | 1         | 0.81%   |
| Lenovo ThinkPad P14s Gen 1 20S5S01V00       | 1         | 0.81%   |
| Lenovo ThinkPad P1 Gen 2 20QT000LGE         | 1         | 0.81%   |
| Lenovo ThinkPad L15 Gen 2a 20X7S05600       | 1         | 0.81%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100        | 1         | 0.81%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 0.81%   |
| Lenovo ThinkPad E15 Gen 2 20TD00GSPB        | 1         | 0.81%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000        | 1         | 0.81%   |
| Lenovo ThinkPad E14 Gen 3 20YDS02D00        | 1         | 0.81%   |
| Lenovo ThinkBook 14 G4 ABA 21DK             | 1         | 0.81%   |
| Lenovo Slim 7 ProX 14ARH7 82V2              | 1         | 0.81%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 0.81%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 1         | 0.81%   |
| Lenovo Legion 5 15ARH05H 82B1               | 1         | 0.81%   |
| Lenovo IdeaPad Y700-15ISK 80NV              | 1         | 0.81%   |
| Lenovo IdeaPad S340-14IIL 81VV              | 1         | 0.81%   |
| Lenovo IdeaPad S145-15API 81V7              | 1         | 0.81%   |
| Lenovo IdeaPad C340-14API 81N6              | 1         | 0.81%   |
| Lenovo IdeaPad 700-17ISK 80RV               | 1         | 0.81%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN            | 1         | 0.81%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7            | 1         | 0.81%   |
| Lenovo IdeaPad 300-14ISK 80Q6               | 1         | 0.81%   |
| Lenovo IdeaPad 3 15IAU7 82RK                | 1         | 0.81%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 1         | 0.81%   |
| Lenovo IdeaPad 3 14ALC6 82KT                | 1         | 0.81%   |
| HUAWEI NBD-WXX9                             | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 10.48%  |
| Lenovo IdeaPad         | 11        | 8.87%   |
| Dell Latitude          | 6         | 4.84%   |
| Acer Aspire            | 6         | 4.84%   |
| HP Pavilion            | 5         | 4.03%   |
| HP EliteBook           | 5         | 4.03%   |
| ASUS ROG               | 5         | 4.03%   |
| Lenovo Legion          | 3         | 2.42%   |
| HP ProBook             | 3         | 2.42%   |
| HP Laptop              | 3         | 2.42%   |
| Dell XPS               | 3         | 2.42%   |
| Dell Precision         | 3         | 2.42%   |
| ASUS VivoBook          | 3         | 2.42%   |
| ASUS ASUS              | 3         | 2.42%   |
| HP ZBook               | 2         | 1.61%   |
| HP ENVY                | 2         | 1.61%   |
| Gigabyte G5            | 2         | 1.61%   |
| Dell G3                | 2         | 1.61%   |
| ASUS Zenbook           | 2         | 1.61%   |
| Apple MacBookPro9      | 2         | 1.61%   |
| Acer Nitro             | 2         | 1.61%   |
| TECNO MEGABOOK         | 1         | 0.81%   |
| Samsung 950XED         | 1         | 0.81%   |
| MSI Titan              | 1         | 0.81%   |
| MSI Raider             | 1         | 0.81%   |
| MSI Bravo              | 1         | 0.81%   |
| Medion E11201          | 1         | 0.81%   |
| Lenovo Yoga            | 1         | 0.81%   |
| Lenovo ThinkBook       | 1         | 0.81%   |
| Lenovo Slim            | 1         | 0.81%   |
| HUAWEI NBD-WXX9        | 1         | 0.81%   |
| HUAWEI HN-WX9X         | 1         | 0.81%   |
| HUAWEI BOM-WXX9        | 1         | 0.81%   |
| HUAWEI BOHB-WAX9       | 1         | 0.81%   |
| HP Notebook            | 1         | 0.81%   |
| HP G62                 | 1         | 0.81%   |
| HP Compaq              | 1         | 0.81%   |
| HP 240                 | 1         | 0.81%   |
| GPU Company GWTN141-10 | 1         | 0.81%   |
| GPD G1621-02           | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 29        | 23.39%  |
| 2022 | 23        | 18.55%  |
| 2019 | 12        | 9.68%   |
| 2020 | 9         | 7.26%   |
| 2023 | 8         | 6.45%   |
| 2014 | 6         | 4.84%   |
| 2018 | 5         | 4.03%   |
| 2015 | 5         | 4.03%   |
| 2013 | 5         | 4.03%   |
| 2012 | 5         | 4.03%   |
| 2011 | 5         | 4.03%   |
| 2017 | 4         | 3.23%   |
| 2016 | 3         | 2.42%   |
| 2010 | 3         | 2.42%   |
| 2009 | 1         | 0.81%   |
| 2007 | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 124       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 116       | 93.55%  |
| Enabled  | 8         | 6.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 120       | 96.77%  |
| Yes  | 4         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 32        | 25.6%   |
| 4.01-8.0    | 27        | 21.6%   |
| 16.01-24.0  | 27        | 21.6%   |
| 32.01-64.0  | 18        | 14.4%   |
| 3.01-4.0    | 13        | 10.4%   |
| 64.01-256.0 | 5         | 4%      |
| 24.01-32.0  | 2         | 1.6%    |
| 2.01-3.0    | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 43        | 32.82%  |
| 2.01-3.0   | 37        | 28.24%  |
| 1.01-2.0   | 20        | 15.27%  |
| 3.01-4.0   | 17        | 12.98%  |
| 8.01-16.0  | 10        | 7.63%   |
| 16.01-24.0 | 2         | 1.53%   |
| 32.01-64.0 | 1         | 0.76%   |
| 24.01-32.0 | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 65.6%   |
| 2      | 37        | 29.6%   |
| 3      | 6         | 4.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 85.48%  |
| Yes       | 18        | 14.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 70.97%  |
| No        | 36        | 29.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 99.19%  |
| No        | 1         | 0.81%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 88.71%  |
| No        | 14        | 11.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 18        | 14.52%  |
| Germany      | 18        | 14.52%  |
| UK           | 8         | 6.45%   |
| Russia       | 8         | 6.45%   |
| Poland       | 6         | 4.84%   |
| France       | 5         | 4.03%   |
| Brazil       | 5         | 4.03%   |
| Turkey       | 4         | 3.23%   |
| Italy        | 4         | 3.23%   |
| Belgium      | 4         | 3.23%   |
| Netherlands  | 3         | 2.42%   |
| India        | 3         | 2.42%   |
| Hungary      | 3         | 2.42%   |
| Canada       | 3         | 2.42%   |
| Sweden       | 2         | 1.61%   |
| Portugal     | 2         | 1.61%   |
| Peru         | 2         | 1.61%   |
| New Zealand  | 2         | 1.61%   |
| Mexico       | 2         | 1.61%   |
| Australia    | 2         | 1.61%   |
| Taiwan       | 1         | 0.81%   |
| Spain        | 1         | 0.81%   |
| Slovakia     | 1         | 0.81%   |
| Saudi Arabia | 1         | 0.81%   |
| Norway       | 1         | 0.81%   |
| Luxembourg   | 1         | 0.81%   |
| Lithuania    | 1         | 0.81%   |
| Libya        | 1         | 0.81%   |
| Latvia       | 1         | 0.81%   |
| Kazakhstan   | 1         | 0.81%   |
| Ivory Coast  | 1         | 0.81%   |
| Israel       | 1         | 0.81%   |
| Georgia      | 1         | 0.81%   |
| Finland      | 1         | 0.81%   |
| Croatia      | 1         | 0.81%   |
| Costa Rica   | 1         | 0.81%   |
| Colombia     | 1         | 0.81%   |
| Chile        | 1         | 0.81%   |
| Bulgaria     | 1         | 0.81%   |
| Argentina    | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Munich                  | 4         | 3.17%   |
| Moscow                  | 3         | 2.38%   |
| Istanbul                | 3         | 2.38%   |
| Berlin                  | 3         | 2.38%   |
| Münster                | 2         | 1.59%   |
| Brussels                | 2         | 1.59%   |
| West Des Moines         | 1         | 0.79%   |
| Warsaw                  | 1         | 0.79%   |
| Ware                    | 1         | 0.79%   |
| Waianae                 | 1         | 0.79%   |
| Vsevolozhsk             | 1         | 0.79%   |
| Vol'ginskiy             | 1         | 0.79%   |
| Viña del Mar           | 1         | 0.79%   |
| Vilnius                 | 1         | 0.79%   |
| Villa Dominico          | 1         | 0.79%   |
| Vienna                  | 1         | 0.79%   |
| Valley Center           | 1         | 0.79%   |
| Ulm                     | 1         | 0.79%   |
| Trujillo                | 1         | 0.79%   |
| Tripoli                 | 1         | 0.79%   |
| Thunder Bay             | 1         | 0.79%   |
| Theydon Bois            | 1         | 0.79%   |
| Tel Aviv                | 1         | 0.79%   |
| Tbilisi                 | 1         | 0.79%   |
| Tatabánya              | 1         | 0.79%   |
| Szigetszentmiklos       | 1         | 0.79%   |
| Szczecin                | 1         | 0.79%   |
| Sydney                  | 1         | 0.79%   |
| Sumter                  | 1         | 0.79%   |
| Stavropol               | 1         | 0.79%   |
| St Petersburg           | 1         | 0.79%   |
| Sisak                   | 1         | 0.79%   |
| Shumen                  | 1         | 0.79%   |
| Sherbrooke              | 1         | 0.79%   |
| Santa Maria di Sala     | 1         | 0.79%   |
| Salt Lake City          | 1         | 0.79%   |
| Saint-Georges-sur-Meuse | 1         | 0.79%   |
| Roubaix                 | 1         | 0.79%   |
| Riga                    | 1         | 0.79%   |
| Rewal                   | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 30        | 35     | 17.86%  |
| SanDisk                     | 18        | 19     | 10.71%  |
| Micron Technology           | 12        | 13     | 7.14%   |
| Intel                       | 11        | 12     | 6.55%   |
| WDC                         | 10        | 11     | 5.95%   |
| SK hynix                    | 10        | 10     | 5.95%   |
| Kingston                    | 10        | 10     | 5.95%   |
| Toshiba                     | 9         | 13     | 5.36%   |
| Seagate                     | 7         | 8      | 4.17%   |
| Crucial                     | 7         | 9      | 4.17%   |
| Phison Electronics          | 5         | 5      | 2.98%   |
| Unknown                     | 4         | 4      | 2.38%   |
| Silicon Motion              | 3         | 3      | 1.79%   |
| Hitachi                     | 3         | 3      | 1.79%   |
| UMIS                        | 2         | 3      | 1.19%   |
| Solid State Storage         | 2         | 2      | 1.19%   |
| Patriot                     | 2         | 2      | 1.19%   |
| KIOXIA                      | 2         | 2      | 1.19%   |
| A-DATA Technology           | 2         | 2      | 1.19%   |
| Wibtek                      | 1         | 1      | 0.6%    |
| WALRAM                      | 1         | 1      | 0.6%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.6%    |
| Team                        | 1         | 1      | 0.6%    |
| SSSTC                       | 1         | 1      | 0.6%    |
| SSDPR-CX                    | 1         | 1      | 0.6%    |
| Phison                      | 1         | 1      | 0.6%    |
| Netac                       | 1         | 1      | 0.6%    |
| Micron/Crucial Technology   | 1         | 1      | 0.6%    |
| Lexar                       | 1         | 1      | 0.6%    |
| Lenovo                      | 1         | 1      | 0.6%    |
| Kingston Technology Company | 1         | 1      | 0.6%    |
| KingFast                    | 1         | 1      | 0.6%    |
| JMicron Technology          | 1         | 1      | 0.6%    |
| HGST                        | 1         | 2      | 0.6%    |
| FURY                        | 1         | 4      | 0.6%    |
| China                       | 1         | 1      | 0.6%    |
| Biwin Storage Technology    | 1         | 1      | 0.6%    |
| BAITITON                    | 1         | 2      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel SSD 660P Series 512GB                           | 5         | 2.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 4         | 2.33%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 3         | 1.74%   |
| Unknown MMC Card  32GB                                | 2         | 1.16%   |
| UMIS RPJTJ512MGE1QDQ 512GB                            | 2         | 1.16%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 1.16%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 2         | 1.16%   |
| Sandisk WD Black SN850 256GB                          | 2         | 1.16%   |
| SanDisk NVMe SSD Drive 2TB                            | 2         | 1.16%   |
| SanDisk NVMe SSD Drive 1TB                            | 2         | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 2         | 1.16%   |
| Samsung MZVLQ256HAJD-000H1 256GB                      | 2         | 1.16%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 2         | 1.16%   |
| Intel SSDPEKNU512GZ 512GB                             | 2         | 1.16%   |
| Crucial CT1000MX500SSD1 1TB                           | 2         | 1.16%   |
| Wibtek W800S 512GB                                    | 1         | 0.58%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 1         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1         | 0.58%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 0.58%   |
| WDC WDS100T2B0A 1TB SSD                               | 1         | 0.58%   |
| WDC WDBNCE5000PNC 500GB SSD                           | 1         | 0.58%   |
| WDC WD16 00AVBB-63SYA0 160GB                          | 1         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                                | 1         | 0.58%   |
| WDC WD10 JPVX-00JC3T0 1TB                             | 1         | 0.58%   |
| WDC WD Blue SA510 2.5 1000GB                          | 1         | 0.58%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 1         | 0.58%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                  | 1         | 0.58%   |
| WALRAM 240G                                           | 1         | 0.58%   |
| Unknown MMC Card  64GB                                | 1         | 0.58%   |
| Unknown Biwin  64GB                                   | 1         | 0.58%   |
| Union Memory (Shenzhen) RPFTJ256PDD2MWX 256GB         | 1         | 0.58%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 1         | 0.58%   |
| Toshiba MQ02ABF100 1TB                                | 1         | 0.58%   |
| Toshiba MQ01ACF050 500GB                              | 1         | 0.58%   |
| Toshiba MQ01ABD100 1TB                                | 1         | 0.58%   |
| Toshiba MQ01ABD075 752GB                              | 1         | 0.58%   |
| Toshiba KXG60ZNV512G 512GB                            | 1         | 0.58%   |
| Toshiba KBG40ZNT512G MEMORY 512GB                     | 1         | 0.58%   |
| Team L3 EVO SSD 120GB                                 | 1         | 0.58%   |
| SSSTC CL4-4D512-Q79 512GB                             | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 35%     |
| Toshiba | 6         | 9      | 30%     |
| WDC     | 3         | 3      | 15%     |
| Hitachi | 3         | 3      | 15%     |
| HGST    | 1         | 2      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 15.91%  |
| Crucial             | 6         | 7      | 13.64%  |
| WDC                 | 5         | 6      | 11.36%  |
| SanDisk             | 5         | 5      | 11.36%  |
| Samsung Electronics | 4         | 4      | 9.09%   |
| Micron Technology   | 4         | 5      | 9.09%   |
| SK hynix            | 2         | 2      | 4.55%   |
| Patriot             | 2         | 2      | 4.55%   |
| Intel               | 2         | 3      | 4.55%   |
| Team                | 1         | 1      | 2.27%   |
| Lexar               | 1         | 1      | 2.27%   |
| Lenovo              | 1         | 1      | 2.27%   |
| JMicron Technology  | 1         | 1      | 2.27%   |
| FURY                | 1         | 2      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| BAITITON            | 1         | 2      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 83        | 104    | 53.9%   |
| SSD     | 41        | 50     | 26.62%  |
| HDD     | 20        | 25     | 12.99%  |
| Unknown | 6         | 7      | 3.9%    |
| MMC     | 4         | 4      | 2.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 83        | 104    | 55.7%   |
| SATA | 53        | 73     | 35.57%  |
| SAS  | 9         | 9      | 6.04%   |
| MMC  | 4         | 4      | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 40     | 55%     |
| 0.51-1.0   | 23        | 30     | 38.33%  |
| 1.01-2.0   | 3         | 4      | 5%      |
| 4.01-10.0  | 1         | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 26.98%  |
| 251-500        | 27        | 21.43%  |
| 501-1000       | 26        | 20.63%  |
| 1001-2000      | 15        | 11.9%   |
| 51-100         | 7         | 5.56%   |
| More than 3000 | 6         | 4.76%   |
| 1-20           | 5         | 3.97%   |
| 2001-3000      | 4         | 3.17%   |
| 21-50          | 2         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 25%     |
| 21-50          | 31        | 23.48%  |
| 101-250        | 24        | 18.18%  |
| 51-100         | 13        | 9.85%   |
| 251-500        | 10        | 7.58%   |
| 501-1000       | 10        | 7.58%   |
| 1001-2000      | 6         | 4.55%   |
| 2001-3000      | 4         | 3.03%   |
| More than 3000 | 1         | 0.76%   |

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
| Detected | 79        | 125    | 60.77%  |
| Works    | 46        | 59     | 35.38%  |
| Malfunc  | 5         | 6      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 69        | 40.35%  |
| Samsung Electronics            | 26        | 15.2%   |
| AMD                            | 16        | 9.36%   |
| SanDisk                        | 15        | 8.77%   |
| SK hynix                       | 8         | 4.68%   |
| Micron Technology              | 8         | 4.68%   |
| Phison Electronics             | 6         | 3.51%   |
| Kingston Technology Company    | 4         | 2.34%   |
| Union Memory (Shenzhen)        | 3         | 1.75%   |
| Toshiba America Info Systems   | 3         | 1.75%   |
| Solid State Storage Technology | 3         | 1.75%   |
| Silicon Motion                 | 3         | 1.75%   |
| Micron/Crucial Technology      | 2         | 1.17%   |
| KIOXIA                         | 2         | 1.17%   |
| ADATA Technology               | 2         | 1.17%   |
| Biwin Storage Technology       | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 8.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 6.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 4.49%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 3.37%   |
| Intel SSD 660P Series                                                          | 6         | 3.37%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 2.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.69%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1.69%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 1.69%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 1.69%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 2         | 1.12%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.12%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 2         | 1.12%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.12%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 2         | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.12%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 1.12%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.12%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.12%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.12%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.56%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 0.56%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 83        | 50%     |
| SATA | 70        | 42.17%  |
| RAID | 12        | 7.23%   |
| IDE  | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 70.97%  |
| AMD    | 36        | 29.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 4.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.42%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 2.42%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 2.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 2.42%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 2.42%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 2.42%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 2.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.61%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.61%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 2         | 1.61%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.81%   |
| Intel Pentium CPU 6405U @ 2.40GHz             | 1         | 0.81%   |
| Intel N95                                     | 1         | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.81%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.81%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.81%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.81%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.81%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.81%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.81%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.81%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.81%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.81%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 28        | 22.58%  |
| Intel Core i5           | 25        | 20.16%  |
| Intel Core i7           | 21        | 16.94%  |
| AMD Ryzen 7             | 15        | 12.1%   |
| AMD Ryzen 5             | 13        | 10.48%  |
| Intel Celeron           | 5         | 4.03%   |
| Intel Core i3           | 4         | 3.23%   |
| AMD Ryzen 9             | 4         | 3.23%   |
| Intel Pentium Dual-Core | 2         | 1.61%   |
| Intel Pentium Silver    | 1         | 0.81%   |
| Intel Pentium           | 1         | 0.81%   |
| Intel Core 2 Duo        | 1         | 0.81%   |
| AMD Ryzen 7 PRO         | 1         | 0.81%   |
| AMD Ryzen 5 PRO         | 1         | 0.81%   |
| AMD A6                  | 1         | 0.81%   |
| AMD A4                  | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 43        | 34.68%  |
| 2      | 28        | 22.58%  |
| 8      | 21        | 16.94%  |
| 6      | 16        | 12.9%   |
| 12     | 5         | 4.03%   |
| 14     | 4         | 3.23%   |
| 10     | 3         | 2.42%   |
| 24     | 2         | 1.61%   |
| 16     | 2         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 124       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 109       | 87.9%   |
| 1      | 15        | 12.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 124       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 82.4%   |
| 0x0a50000c | 9         | 7.2%    |
| 0x0a404102 | 4         | 3.2%    |
| 0x0a404101 | 2         | 1.6%    |
| 0x90672    | 1         | 0.8%    |
| 0x0a601203 | 1         | 0.8%    |
| 0x08608103 | 1         | 0.8%    |
| 0x08600104 | 1         | 0.8%    |
| 0x08108109 | 1         | 0.8%    |
| 0x08108102 | 1         | 0.8%    |
| 0x03000027 | 1         | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 25        | 20.16%  |
| KabyLake         | 19        | 15.32%  |
| Zen 3            | 12        | 9.68%   |
| Alderlake Hybrid | 10        | 8.06%   |
| TigerLake        | 8         | 6.45%   |
| Skylake          | 8         | 6.45%   |
| IvyBridge        | 7         | 5.65%   |
| Haswell          | 6         | 4.84%   |
| Zen+             | 4         | 3.23%   |
| Zen 2            | 4         | 3.23%   |
| SandyBridge      | 4         | 3.23%   |
| CometLake        | 4         | 3.23%   |
| Penryn           | 2         | 1.61%   |
| IceLake          | 2         | 1.61%   |
| Broadwell        | 2         | 1.61%   |
| Westmere         | 1         | 0.81%   |
| Puma             | 1         | 0.81%   |
| Nehalem          | 1         | 0.81%   |
| K10 Llano        | 1         | 0.81%   |
| Goldmont plus    | 1         | 0.81%   |
| Goldmont         | 1         | 0.81%   |
| Core             | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 49.42%  |
| Nvidia | 45        | 26.16%  |
| AMD    | 42        | 24.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 4.05%   |
| AMD Rembrandt [Radeon 680M]                                                   | 7         | 4.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 3.47%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 6         | 3.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 3.47%   |
| AMD Lucienne                                                                  | 6         | 3.47%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 2.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 2.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 2.31%   |
| Intel HD Graphics 530                                                         | 4         | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 2.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 2.31%   |
| AMD Renoir                                                                    | 4         | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 2.31%   |
| AMD Barcelo                                                                   | 4         | 2.31%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 1.73%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 3         | 1.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.73%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 3         | 1.73%   |
| Intel HD Graphics 620                                                         | 3         | 1.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 1.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 1.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 1.16%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 1.16%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 1.16%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 2         | 1.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.16%   |
| Intel Raptor Lake-S UHD Graphics                                              | 2         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.16%   |
| Intel HD Graphics 630                                                         | 2         | 1.16%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                    | 2         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                          | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 1         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                       | 1         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                        | 1         | 0.58%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 37.9%   |
| Intel + Nvidia | 32        | 25.81%  |
| 1 x AMD        | 25        | 20.16%  |
| AMD + Nvidia   | 12        | 9.68%   |
| Intel + AMD    | 4         | 3.23%   |
| Other          | 1         | 0.81%   |
| 2 x Intel      | 1         | 0.81%   |
| 2 x AMD        | 1         | 0.81%   |
| 1 x Nvidia     | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 71.43%  |
| Proprietary | 35        | 27.78%  |
| Unknown     | 1         | 0.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 74.6%   |
| 3.01-4.0   | 10        | 7.94%   |
| 0.01-0.5   | 10        | 7.94%   |
| 1.01-2.0   | 6         | 4.76%   |
| 0.51-1.0   | 4         | 3.17%   |
| 7.01-8.0   | 2         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 29        | 18.71%  |
| AU Optronics            | 29        | 18.71%  |
| Samsung Electronics     | 22        | 14.19%  |
| Chimei Innolux          | 16        | 10.32%  |
| LG Display              | 12        | 7.74%   |
| Goldstar                | 6         | 3.87%   |
| Sharp                   | 5         | 3.23%   |
| Dell                    | 5         | 3.23%   |
| PANDA                   | 4         | 2.58%   |
| Apple                   | 4         | 2.58%   |
| Philips                 | 3         | 1.94%   |
| SAC                     | 2         | 1.29%   |
| Lenovo                  | 2         | 1.29%   |
| InfoVision              | 2         | 1.29%   |
| Chi Mei Optoelectronics | 2         | 1.29%   |
| AOC                     | 2         | 1.29%   |
| UGD                     | 1         | 0.65%   |
| STA                     | 1         | 0.65%   |
| Panasonic               | 1         | 0.65%   |
| MSI                     | 1         | 0.65%   |
| LOE                     | 1         | 0.65%   |
| KDC                     | 1         | 0.65%   |
| KDB                     | 1         | 0.65%   |
| Denver                  | 1         | 0.65%   |
| CSO                     | 1         | 0.65%   |
| Acer                    | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch         | 3         | 1.94%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 2         | 1.29%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                  | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch          | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 1.29%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                   | 1         | 0.65%   |
| STA SEMP LEDTV STA0030 1920x540                                        | 1         | 0.65%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                | 1         | 0.65%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 0.65%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                | 1         | 0.65%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                       | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch    | 1         | 0.65%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 521x293mm 23.5-inch      | 1         | 0.65%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch   | 1         | 0.65%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch      | 1         | 0.65%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM094D 1920x1080 1210x680mm 54.6-inch | 1         | 0.65%   |
| SAC LED MONITOR SAC952D 1920x1080 480x260mm 21.5-inch                  | 1         | 0.65%   |
| SAC DP1 SAC3236 2560x1440 697x393mm 31.5-inch                          | 1         | 0.65%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.65%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                     | 1         | 0.65%   |
| Philips 272B7QUB PHL0933 2560x1440 597x336mm 27.0-inch                 | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 68        | 47.22%  |
| 1366x768 (WXGA)   | 24        | 16.67%  |
| 2560x1440 (QHD)   | 10        | 6.94%   |
| 3840x2160 (4K)    | 9         | 6.25%   |
| 2880x1800         | 3         | 2.08%   |
| 2560x1600         | 3         | 2.08%   |
| 2560x1080         | 3         | 2.08%   |
| 1600x900 (HD+)    | 3         | 2.08%   |
| 3840x2400         | 2         | 1.39%   |
| 3440x1440         | 2         | 1.39%   |
| 2240x1400         | 2         | 1.39%   |
| 1920x540          | 2         | 1.39%   |
| 1920x1200 (WUXGA) | 2         | 1.39%   |
| 1280x800 (WXGA)   | 2         | 1.39%   |
| 3840x1100         | 1         | 0.69%   |
| 3456x2160         | 1         | 0.69%   |
| 3072x1920         | 1         | 0.69%   |
| 2256x1504         | 1         | 0.69%   |
| 2160x1440         | 1         | 0.69%   |
| 1920x1280         | 1         | 0.69%   |
| 1440x900 (WXGA+)  | 1         | 0.69%   |
| 1280x720 (HD)     | 1         | 0.69%   |
| 1280x1024 (SXGA)  | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 53        | 34.42%  |
| 14      | 24        | 15.58%  |
| 17      | 19        | 12.34%  |
| 13      | 15        | 9.74%   |
| 16      | 6         | 3.9%    |
| 27      | 5         | 3.25%   |
| 24      | 5         | 3.25%   |
| 34      | 4         | 2.6%    |
| 31      | 4         | 2.6%    |
| 23      | 4         | 2.6%    |
| 21      | 3         | 1.95%   |
| 11      | 3         | 1.95%   |
| 72      | 1         | 0.65%   |
| 65      | 1         | 0.65%   |
| 54      | 1         | 0.65%   |
| 40      | 1         | 0.65%   |
| 37      | 1         | 0.65%   |
| 20      | 1         | 0.65%   |
| 19      | 1         | 0.65%   |
| 12      | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 90        | 59.21%  |
| 351-400     | 21        | 13.82%  |
| 501-600     | 14        | 9.21%   |
| 201-300     | 9         | 5.92%   |
| 601-700     | 4         | 2.63%   |
| 401-500     | 4         | 2.63%   |
| 801-900     | 3         | 1.97%   |
| 701-800     | 3         | 1.97%   |
| 1001-1500   | 2         | 1.32%   |
| 1501-2000   | 1         | 0.66%   |
| Unknown     | 1         | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 106       | 79.1%   |
| 16/10 | 19        | 14.18%  |
| 21/9  | 4         | 2.99%   |
| 3/2   | 3         | 2.24%   |
| 5/4   | 1         | 0.75%   |
| 3.40  | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 34.42%  |
| 81-90          | 34        | 22.08%  |
| 121-130        | 19        | 12.34%  |
| 201-250        | 10        | 6.49%   |
| 351-500        | 8         | 5.19%   |
| 111-120        | 6         | 3.9%    |
| 301-350        | 5         | 3.25%   |
| 51-60          | 4         | 2.6%    |
| More than 1000 | 3         | 1.95%   |
| 71-80          | 2         | 1.3%    |
| 251-300        | 2         | 1.3%    |
| 151-200        | 2         | 1.3%    |
| 501-1000       | 2         | 1.3%    |
| 91-100         | 2         | 1.3%    |
| 61-70          | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 70        | 46.98%  |
| 101-120       | 27        | 18.12%  |
| 51-100        | 24        | 16.11%  |
| 161-240       | 14        | 9.4%    |
| More than 240 | 10        | 6.71%   |
| 1-50          | 3         | 2.01%   |
| Unknown       | 1         | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 90        | 72%     |
| 2     | 33        | 26.4%   |
| 3     | 1         | 0.8%    |
| 0     | 1         | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 68        | 36.17%  |
| Intel                 | 64        | 34.04%  |
| MediaTek              | 15        | 7.98%   |
| Qualcomm Atheros      | 11        | 5.85%   |
| Broadcom              | 9         | 4.79%   |
| Ralink                | 3         | 1.6%    |
| Hewlett-Packard       | 3         | 1.6%    |
| Broadcom Limited      | 3         | 1.6%    |
| ASIX Electronics      | 3         | 1.6%    |
| Samsung Electronics   | 2         | 1.06%   |
| ZyXEL Communications  | 1         | 0.53%   |
| Xiaomi                | 1         | 0.53%   |
| Qualcomm              | 1         | 0.53%   |
| Microsoft             | 1         | 0.53%   |
| Lenovo                | 1         | 0.53%   |
| Google                | 1         | 0.53%   |
| Dell                  | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 16.59%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 4.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 5         | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 5         | 2.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 2.24%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.79%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.35%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.35%   |
| Intel Wireless 7260                                               | 3         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 1.35%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 3         | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.9%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.9%    |
| Intel Wireless 8260                                               | 2         | 0.9%    |
| Intel Wireless 7265                                               | 2         | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 0.9%    |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 0.9%    |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                     | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 49.22%  |
| Realtek Semiconductor | 22        | 17.19%  |
| MediaTek              | 15        | 11.72%  |
| Qualcomm Atheros      | 11        | 8.59%   |
| Broadcom              | 8         | 6.25%   |
| Ralink                | 3         | 2.34%   |
| ZyXEL Communications  | 1         | 0.78%   |
| Qualcomm              | 1         | 0.78%   |
| Microsoft             | 1         | 0.78%   |
| Hewlett-Packard       | 1         | 0.78%   |
| Dell                  | 1         | 0.78%   |
| Broadcom Limited      | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 7.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 5.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 4.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 3.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 3.91%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.91%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 3.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 2.34%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.34%   |
| Intel Wireless 7260                                                     | 3         | 2.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 2.34%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 3         | 2.34%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.56%   |
| Intel Wireless 8260                                                     | 2         | 1.56%   |
| Intel Wireless 7265                                                     | 2         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.56%   |
| Intel 700 Series Chipset Family Wi-Fi                                   | 2         | 1.56%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                           | 1         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.78%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.78%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 1         | 0.78%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 58        | 63.04%  |
| Intel                 | 18        | 19.57%  |
| Broadcom              | 4         | 4.35%   |
| ASIX Electronics      | 3         | 3.26%   |
| Samsung Electronics   | 2         | 2.17%   |
| Qualcomm Atheros      | 2         | 2.17%   |
| Broadcom Limited      | 2         | 2.17%   |
| Xiaomi                | 1         | 1.09%   |
| Lenovo                | 1         | 1.09%   |
| Google                | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 39.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 7.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 6.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 3.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.23%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.15%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.15%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 2.15%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.08%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.08%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.08%   |
| Intel Ethernet Controller I219-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.08%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 1.08%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.08%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.08%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.08%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.08%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.08%   |
| Google Pixel 6 Pro                                                | 1         | 1.08%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.08%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 1.08%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 58.29%  |
| Ethernet | 86        | 40.76%  |
| Modem    | 2         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 83.46%  |
| Ethernet | 21        | 16.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 78        | 62.9%   |
| 1     | 46        | 37.1%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 89        | 70.63%  |
| Yes  | 37        | 29.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 51.82%  |
| Realtek Semiconductor           | 17        | 15.45%  |
| IMC Networks                    | 6         | 5.45%   |
| Foxconn / Hon Hai               | 6         | 5.45%   |
| Qualcomm Atheros Communications | 5         | 4.55%   |
| Lite-On Technology              | 5         | 4.55%   |
| Broadcom                        | 4         | 3.64%   |
| Apple                           | 4         | 3.64%   |
| Realtek                         | 2         | 1.82%   |
| Toshiba                         | 1         | 0.91%   |
| Ralink                          | 1         | 0.91%   |
| Dell                            | 1         | 0.91%   |
| Cambridge Silicon Radio         | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 14        | 12.73%  |
| Intel Bluetooth Device                              | 13        | 11.82%  |
| Intel AX201 Bluetooth                               | 13        | 11.82%  |
| Intel Bluetooth wireless interface                  | 12        | 10.91%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 7.27%   |
| Intel AX210 Bluetooth                               | 5         | 4.55%   |
| Intel AX200 Bluetooth                               | 5         | 4.55%   |
| IMC Networks Wireless_Device                        | 5         | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.73%   |
| Lite-On Wireless_Device                             | 3         | 2.73%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.73%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.82%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.82%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.82%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.91%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.91%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.91%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.91%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.91%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.91%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.91%   |
| Broadcom BCM20702A0                                 | 1         | 0.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.91%   |
| Apple Bluetooth Host Controller                     | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 53.37%  |
| AMD                      | 38        | 23.31%  |
| Nvidia                   | 29        | 17.79%  |
| Realtek Semiconductor    | 2         | 1.23%   |
| Hewlett-Packard          | 2         | 1.23%   |
| C-Media Electronics      | 2         | 1.23%   |
| Nordic Semiconductor ASA | 1         | 0.61%   |
| Lenovo                   | 1         | 0.61%   |
| GN Netcom                | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 16.5%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 9%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 4%      |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 4%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4%      |
| Nvidia Audio device                                                        | 6         | 3%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 3%      |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2%      |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2%      |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.5%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 3         | 1.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.5%    |
| Realtek Semiconductor USB Audio                                            | 2         | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1%      |
| Intel CM238 HD Audio Controller                                            | 2         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 2         | 1%      |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1%      |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1%      |
| AMD FCH Azalia Controller                                                  | 2         | 1%      |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 29.73%  |
| Micron Technology   | 16        | 21.62%  |
| SK hynix            | 15        | 20.27%  |
| Kingston            | 4         | 5.41%   |
| Ramaxel Technology  | 3         | 4.05%   |
| Crucial             | 3         | 4.05%   |
| Unknown             | 2         | 2.7%    |
| Unknown (ABCD)      | 1         | 1.35%   |
| Transcend           | 1         | 1.35%   |
| Timetec             | 1         | 1.35%   |
| GOODRAM             | 1         | 1.35%   |
| G.Skill             | 1         | 1.35%   |
| Corsair             | 1         | 1.35%   |
| A-DATA Technology   | 1         | 1.35%   |
| 4ea5                | 1         | 1.35%   |
| Unknown             | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 3.9%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.9%    |
| Unknown RAM Module 4GB SODIMM 800MT/s                            | 1         | 1.3%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.3%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 1.3%    |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 1.3%    |
| Timetec RAM S16G-3200 16GB SODIMM DDR4 2133MT/s                  | 1         | 1.3%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.3%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.3%    |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 1         | 1.3%    |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 1         | 1.3%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.3%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.3%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.3%    |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 1.3%    |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.3%    |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.3%    |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.3%    |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 1.3%    |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.3%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.3%    |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.3%    |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 1         | 1.3%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.3%    |
| Samsung RAM K4F6E3S4HM-MGCJ 2GB LPDDR4 2400MT/s                  | 1         | 1.3%    |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 1.3%    |
| Samsung RAM K4A8G165WC-BCTD 4096MB SODIMM DDR4 2667MT/s          | 1         | 1.3%    |
| Samsung RAM K3LKCKC0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.3%    |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s       | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 44.44%  |
| DDR3    | 10        | 15.87%  |
| LPDDR5  | 9         | 14.29%  |
| DDR5    | 7         | 11.11%  |
| LPDDR4  | 6         | 9.52%   |
| LPDDR3  | 2         | 3.17%   |
| Unknown | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 70.77%  |
| Row Of Chips | 18        | 27.69%  |
| Unknown      | 1         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 46.27%  |
| 4096  | 18        | 26.87%  |
| 16384 | 10        | 14.93%  |
| 2048  | 4         | 5.97%   |
| 32768 | 3         | 4.48%   |
| 12288 | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 18        | 28.13%  |
| 6400  | 9         | 14.06%  |
| 2667  | 7         | 10.94%  |
| 1600  | 7         | 10.94%  |
| 4800  | 6         | 9.38%   |
| 2400  | 4         | 6.25%   |
| 2133  | 3         | 4.69%   |
| 4267  | 2         | 3.13%   |
| 1333  | 2         | 3.13%   |
| 5600  | 1         | 1.56%   |
| 3733  | 1         | 1.56%   |
| 3266  | 1         | 1.56%   |
| 1867  | 1         | 1.56%   |
| 1334  | 1         | 1.56%   |
| 800   | 1         | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon PIXMA MX490 Series | 1         | 50%     |
| Canon LBP6020            | 1         | 50%     |

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
| Chicony Electronics                    | 20        | 18.69%  |
| Quanta                                 | 11        | 10.28%  |
| IMC Networks                           | 11        | 10.28%  |
| Bison Electronics                      | 9         | 8.41%   |
| Realtek Semiconductor                  | 8         | 7.48%   |
| Syntek                                 | 7         | 6.54%   |
| Microdia                               | 7         | 6.54%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 6.54%   |
| Sunplus Innovation Technology          | 6         | 5.61%   |
| Apple                                  | 5         | 4.67%   |
| Luxvisions Innotech Limited            | 4         | 3.74%   |
| SunplusIT                              | 2         | 1.87%   |
| Suyin                                  | 1         | 0.93%   |
| Sonix Technology                       | 1         | 0.93%   |
| Silicon Motion                         | 1         | 0.93%   |
| Primax Electronics                     | 1         | 0.93%   |
| OYT Tech                               | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| Lite-On Technology                     | 1         | 0.93%   |
| Lenovo                                 | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |
| Acer                                   | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 6.42%   |
| Chicony Integrated Camera                                       | 7         | 6.42%   |
| Syntek Integrated Camera                                        | 6         | 5.5%    |
| Realtek HP Truevision HD                                        | 4         | 3.67%   |
| Bison Integrated Camera                                         | 4         | 3.67%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 2.75%   |
| Quanta HD User Facing                                           | 3         | 2.75%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 2.75%   |
| Apple FaceTime HD Camera                                        | 3         | 2.75%   |
| Quanta USB2.0 HD UVC WebCam                                     | 2         | 1.83%   |
| Microdia Integrated_Webcam_FHD                                  | 2         | 1.83%   |
| Chicony HP TrueVision HD                                        | 2         | 1.83%   |
| Chicony HD WebCam                                               | 2         | 1.83%   |
| Chicony 720p HD Camera                                          | 2         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 1.83%   |
| Bison Integrated RGB Camera                                     | 2         | 1.83%   |
| Bison HD Webcam                                                 | 2         | 1.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 2         | 1.83%   |
| Syntek Lenovo EasyCamera                                        | 1         | 0.92%   |
| Suyin 1.3M HD WebCam                                            | 1         | 0.92%   |
| SunplusIT USB Camera                                            | 1         | 0.92%   |
| SunplusIT 1080p FHD Camera                                      | 1         | 0.92%   |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 1         | 0.92%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.92%   |
| Sunplus 1.3M HD WebCam                                          | 1         | 0.92%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.92%   |
| Silicon Motion HP Webcam-101                                    | 1         | 0.92%   |
| Realtek MTD camera                                              | 1         | 0.92%   |
| Realtek Laptop Camera                                           | 1         | 0.92%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 0.92%   |
| Realtek Integrated Webcam                                       | 1         | 0.92%   |
| Quanta ov9734_techfront_camera                                  | 1         | 0.92%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 0.92%   |
| Quanta HP HD Camera                                             | 1         | 0.92%   |
| Quanta HP 5MP Camera                                            | 1         | 0.92%   |
| Quanta HD Webcam                                                | 1         | 0.92%   |
| Quanta HD Camera                                                | 1         | 0.92%   |
| Primax HP HD Webcam [Fixed]                                     | 1         | 0.92%   |
| OYT Tech OYV1RDFF1                                              | 1         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 6         | 33.33%  |
| Synaptics                          | 5         | 27.78%  |
| Shenzhen Goodix Technology         | 5         | 27.78%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 5.56%   |
| Elan Microelectronics              | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 4         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 5.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 5.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                                | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Broadcom     | 4         | 44.44%  |
| Alcor Micro  | 2         | 22.22%  |
| O2 Micro     | 1         | 11.11%  |
| Lenovo       | 1         | 11.11%  |
| Aladdin R.D. | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader            | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 11.11%  |
| Broadcom 5880                                  | 1         | 11.11%  |
| Aladdin R.D. JaCarta                           | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 78        | 62.9%   |
| 1     | 38        | 30.65%  |
| 2     | 8         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 33.96%  |
| Chipcard              | 8         | 15.09%  |
| Graphics card         | 7         | 13.21%  |
| Multimedia controller | 6         | 11.32%  |
| Camera                | 6         | 11.32%  |
| Net/wireless          | 4         | 7.55%   |
| Storage               | 1         | 1.89%   |
| Sound                 | 1         | 1.89%   |
| Card reader           | 1         | 1.89%   |
| Bluetooth             | 1         | 1.89%   |


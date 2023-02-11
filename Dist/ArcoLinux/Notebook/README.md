ArcoLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

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

Total: 1068

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Raider GE76 12UHS           | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| HP            | Folio 13                    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Acer          | Aspire A515-52G             | [a95489f0b7](https://linux-hardware.org/?probe=a95489f0b7) | Jan 24, 2023 |
| Chuwi         | GemiBook Pro                | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [66287c2f72](https://linux-hardware.org/?probe=66287c2f72) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [369b022d8e](https://linux-hardware.org/?probe=369b022d8e) | Jan 22, 2023 |
| Timi          | TM1701                      | [bec2d3a691](https://linux-hardware.org/?probe=bec2d3a691) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| Dell          | Latitude 7480               | [0d4396d043](https://linux-hardware.org/?probe=0d4396d043) | Jan 21, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [ae81429a64](https://linux-hardware.org/?probe=ae81429a64) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| MSI           | GL65 Leopard 10SFK          | [8aa69f1dae](https://linux-hardware.org/?probe=8aa69f1dae) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| MSI           | GL65 Leopard 10SFK          | [0ea710bda6](https://linux-hardware.org/?probe=0ea710bda6) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Acer          | Aspire A715-75G             | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Alienware     | M17xR4                      | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6643ab6cf1](https://linux-hardware.org/?probe=6643ab6cf1) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [91fed2c125](https://linux-hardware.org/?probe=91fed2c125) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [0ece2f508b](https://linux-hardware.org/?probe=0ece2f508b) | Jan 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e275cc7891](https://linux-hardware.org/?probe=e275cc7891) | Jan 13, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a786384700](https://linux-hardware.org/?probe=a786384700) | Jan 10, 2023 |
| HP            | ENVY Notebook               | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| System76      | Oryx Pro                    | [e3f5a24a6e](https://linux-hardware.org/?probe=e3f5a24a6e) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| Dell          | Precision M3800             | [ca9cfa3f5a](https://linux-hardware.org/?probe=ca9cfa3f5a) | Jan 07, 2023 |
| Dell          | Precision M3800             | [454d4b6b55](https://linux-hardware.org/?probe=454d4b6b55) | Jan 07, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| System76      | Pangolin                    | [823d50a20f](https://linux-hardware.org/?probe=823d50a20f) | Jan 06, 2023 |
| HP            | ENVY 15                     | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Dell          | Precision 7740              | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| HP            | Folio 13                    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| HP            | EliteBook 830 G5            | [bdd6f3912d](https://linux-hardware.org/?probe=bdd6f3912d) | Dec 30, 2022 |
| Packard Be... | EasyNote TE69HW             | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| Dell          | Inspiron 7580               | [eb5b708877](https://linux-hardware.org/?probe=eb5b708877) | Dec 22, 2022 |
| Sony          | SVF15N26CXB                 | [ffc2ea8936](https://linux-hardware.org/?probe=ffc2ea8936) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| MSI           | GL75 Leopard 10SDK          | [a269c3ef8a](https://linux-hardware.org/?probe=a269c3ef8a) | Dec 20, 2022 |
| ASUSTek       | X555QA                      | [3a7e8867bd](https://linux-hardware.org/?probe=3a7e8867bd) | Dec 19, 2022 |
| Dell          | Latitude 5580               | [c8b402d4df](https://linux-hardware.org/?probe=c8b402d4df) | Dec 18, 2022 |
| Dell          | Latitude 5580               | [b45e1798cc](https://linux-hardware.org/?probe=b45e1798cc) | Dec 18, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| MSI           | GE72VR 6RF                  | [ce2ebf80a1](https://linux-hardware.org/?probe=ce2ebf80a1) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Apple         | MacBookAir6,2               | [65bc0e828c](https://linux-hardware.org/?probe=65bc0e828c) | Dec 08, 2022 |
| LG Electro... | C500                        | [078e13cadd](https://linux-hardware.org/?probe=078e13cadd) | Dec 08, 2022 |
| MSI           | GE72VR 6RF                  | [23a83a5e8e](https://linux-hardware.org/?probe=23a83a5e8e) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| Dell          | Inspiron 5502               | [311215d00b](https://linux-hardware.org/?probe=311215d00b) | Dec 05, 2022 |
| ASUSTek       | X550MD                      | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| ASUSTek       | X555QA                      | [677ef3b3f2](https://linux-hardware.org/?probe=677ef3b3f2) | Dec 03, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| MSI           | Katana GF76 11UD            | [186950bae6](https://linux-hardware.org/?probe=186950bae6) | Nov 29, 2022 |
| MSI           | Katana GF76 11UD            | [48bb9075a7](https://linux-hardware.org/?probe=48bb9075a7) | Nov 29, 2022 |
| Lenovo        | B51-80 80LM                 | [3c50a742a9](https://linux-hardware.org/?probe=3c50a742a9) | Nov 28, 2022 |
| System76      | Oryx Pro                    | [c7d2918a69](https://linux-hardware.org/?probe=c7d2918a69) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| HP            | EliteBook 840 G1            | [1071e10a2c](https://linux-hardware.org/?probe=1071e10a2c) | Nov 23, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [88bbdb925b](https://linux-hardware.org/?probe=88bbdb925b) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [f7ebd3f633](https://linux-hardware.org/?probe=f7ebd3f633) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK U759               | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| HUAWEI        | HLYL-WXX9                   | [560c24bf74](https://linux-hardware.org/?probe=560c24bf74) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| HP            | 250 G7 Notebook PC          | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| Dell          | Vostro 3550                 | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| Toshiba       | Satellite L775              | [a8c9c0ffda](https://linux-hardware.org/?probe=a8c9c0ffda) | Nov 12, 2022 |
| Dell          | Latitude 3380               | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| HP            | EliteBook 840 G2            | [91bdce735b](https://linux-hardware.org/?probe=91bdce735b) | Nov 12, 2022 |
| Dell          | Precision 3571              | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| CSL-Comput... | R Evolve C14i               | [2a99a4d733](https://linux-hardware.org/?probe=2a99a4d733) | Nov 10, 2022 |
| Dell          | XPS 15 9570                 | [44c3eceeee](https://linux-hardware.org/?probe=44c3eceeee) | Nov 10, 2022 |
| Timi          | RedmiBook Pro 15S           | [02b3508a99](https://linux-hardware.org/?probe=02b3508a99) | Nov 09, 2022 |
| Dell          | Latitude E5470              | [a9c69c7418](https://linux-hardware.org/?probe=a9c69c7418) | Nov 09, 2022 |
| Dell          | Precision 3571              | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| HP            | Pavilion dv6                | [f715c6e15c](https://linux-hardware.org/?probe=f715c6e15c) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [caf9066e2a](https://linux-hardware.org/?probe=caf9066e2a) | Nov 06, 2022 |
| TUXEDO        | Aura 15 Gen2                | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Alienware     | 14                          | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [813cfb5bdf](https://linux-hardware.org/?probe=813cfb5bdf) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f790aefcad](https://linux-hardware.org/?probe=f790aefcad) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | [d81e8b3ea2](https://linux-hardware.org/?probe=d81e8b3ea2) | Nov 01, 2022 |
| ASUSTek       | Zephyrus S GX531GS_GX531... | [4823244248](https://linux-hardware.org/?probe=4823244248) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [69768228d4](https://linux-hardware.org/?probe=69768228d4) | Nov 01, 2022 |
| Dell          | Vostro 3500                 | [a3abf820e1](https://linux-hardware.org/?probe=a3abf820e1) | Oct 31, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | [7b414a3c7c](https://linux-hardware.org/?probe=7b414a3c7c) | Oct 29, 2022 |
| Dell          | Inspiron 5590               | [f1a5637218](https://linux-hardware.org/?probe=f1a5637218) | Oct 27, 2022 |
| Dell          | Precision 7530              | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| Dell          | Inspiron 5590               | [802e0f0c61](https://linux-hardware.org/?probe=802e0f0c61) | Oct 24, 2022 |
| NEC Comput... | PC-VK27MXZCG                | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Latitude E6440              | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Toshiba       | Satellite L775              | [180b9ab9ae](https://linux-hardware.org/?probe=180b9ab9ae) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aca44a3eab](https://linux-hardware.org/?probe=aca44a3eab) | Oct 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWA0DW0... | [117e1e8e03](https://linux-hardware.org/?probe=117e1e8e03) | Oct 20, 2022 |
| Acer          | Aspire 7720Z                | [164c89c324](https://linux-hardware.org/?probe=164c89c324) | Oct 20, 2022 |
| HUAWEI        | HLYL-WXX9                   | [6a7e7ac7ce](https://linux-hardware.org/?probe=6a7e7ac7ce) | Oct 19, 2022 |
| TUXEDO        | Aura 15 Gen2                | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| HP            | Pavilion g7                 | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| Dell          | Latitude 3380               | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| Sony          | SVE14A27CXH                 | [85398590ee](https://linux-hardware.org/?probe=85398590ee) | Oct 18, 2022 |
| Sony          | SVE14A27CXH                 | [76a531edcf](https://linux-hardware.org/?probe=76a531edcf) | Oct 18, 2022 |
| LG Electro... | C500                        | [f688cc0536](https://linux-hardware.org/?probe=f688cc0536) | Oct 18, 2022 |
| Dell          | Latitude 3380               | [76a82ca1e6](https://linux-hardware.org/?probe=76a82ca1e6) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | [57436f7d31](https://linux-hardware.org/?probe=57436f7d31) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| Dell          | Latitude 3350               | [4c634a0308](https://linux-hardware.org/?probe=4c634a0308) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [411a334a74](https://linux-hardware.org/?probe=411a334a74) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| Schenker      | SLIM_13_14_SSL13_14L18      | [b7bd0894f2](https://linux-hardware.org/?probe=b7bd0894f2) | Oct 13, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| System76      | Oryx Pro                    | [5e2fd69a86](https://linux-hardware.org/?probe=5e2fd69a86) | Oct 11, 2022 |
| Acer          | Aspire E5-575G              | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| Dell          | Inspiron 7559               | [c963b4157a](https://linux-hardware.org/?probe=c963b4157a) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| MSI           | CR61 3M                     | [496910c25b](https://linux-hardware.org/?probe=496910c25b) | Oct 04, 2022 |
| Lenovo        | ThinkPad Edge 03193UG       | [49afe38831](https://linux-hardware.org/?probe=49afe38831) | Oct 04, 2022 |
| Sony          | SVE14A27CXH                 | [09cb572f35](https://linux-hardware.org/?probe=09cb572f35) | Oct 03, 2022 |
| MSI           | CR61 3M                     | [818a721825](https://linux-hardware.org/?probe=818a721825) | Oct 02, 2022 |
| HUAWEI        | HLYL-WXX9                   | [318010d949](https://linux-hardware.org/?probe=318010d949) | Oct 01, 2022 |
| ASUSTek       | X580VD                      | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Dell          | Latitude 3410               | [0f7ad40255](https://linux-hardware.org/?probe=0f7ad40255) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| ASUSTek       | E402BA                      | [e672656164](https://linux-hardware.org/?probe=e672656164) | Sep 10, 2022 |
| Gigabyte      | AERO 15-SA                  | [5ec761c633](https://linux-hardware.org/?probe=5ec761c633) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| System76      | Oryx Pro                    | [66f701b53f](https://linux-hardware.org/?probe=66f701b53f) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| System76      | Oryx Pro                    | [78adcc218f](https://linux-hardware.org/?probe=78adcc218f) | Sep 04, 2022 |
| System76      | Oryx Pro                    | [0113a2a928](https://linux-hardware.org/?probe=0113a2a928) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Shuttle       | DS437                       | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| ASUSTek       | N61Jv                       | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| Samsung       | 550XDA                      | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| HP            | ProBook 450 G1              | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| Chuwi         | GemiBook Pro                | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| Unknown       | Unknown                     | [472eb48ecc](https://linux-hardware.org/?probe=472eb48ecc) | Aug 21, 2022 |
| Dell          | Vostro 3400                 | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| Toshiba       | Satellite P55t-C            | [deac60d261](https://linux-hardware.org/?probe=deac60d261) | Aug 18, 2022 |
| Dell          | Inspiron 5570               | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Dell          | G7 7588                     | [246c96a8ae](https://linux-hardware.org/?probe=246c96a8ae) | Aug 16, 2022 |
| HP            | EliteBook 8540p             | [e2799ec7f9](https://linux-hardware.org/?probe=e2799ec7f9) | Aug 15, 2022 |
| Chuwi         | HeroBook Air                | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00BNRT    | [72139648d3](https://linux-hardware.org/?probe=72139648d3) | Aug 10, 2022 |
| Acer          | Aspire E5-575G              | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | [490109686e](https://linux-hardware.org/?probe=490109686e) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [cd51b4a39c](https://linux-hardware.org/?probe=cd51b4a39c) | Aug 06, 2022 |
| Xplore        | iX104C5                     | [6ef6194939](https://linux-hardware.org/?probe=6ef6194939) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Sony          | VPCF120FL                   | [75bd2bb218](https://linux-hardware.org/?probe=75bd2bb218) | Aug 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| System76      | Oryx Pro                    | [b55d1a9fe5](https://linux-hardware.org/?probe=b55d1a9fe5) | Jul 25, 2022 |
| System76      | Oryx Pro                    | [3b91037c6f](https://linux-hardware.org/?probe=3b91037c6f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| Dell          | Inspiron 14 5401            | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| HP            | Unknown                     | [01622a24ef](https://linux-hardware.org/?probe=01622a24ef) | Jul 17, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [3cc4a578df](https://linux-hardware.org/?probe=3cc4a578df) | Jul 17, 2022 |
| HP            | Notebook                    | [e5a1df8ba8](https://linux-hardware.org/?probe=e5a1df8ba8) | Jul 17, 2022 |
| System76      | Oryx Pro                    | [5cac9c78e6](https://linux-hardware.org/?probe=5cac9c78e6) | Jul 16, 2022 |
| System76      | Oryx Pro                    | [7cb7b3fd6a](https://linux-hardware.org/?probe=7cb7b3fd6a) | Jul 14, 2022 |
| Dell          | XPS 17 9710                 | [2438f42e95](https://linux-hardware.org/?probe=2438f42e95) | Jul 13, 2022 |
| Dell          | Vostro 15 3510              | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| Dell          | Inspiron N5050              | [8002a8ec0f](https://linux-hardware.org/?probe=8002a8ec0f) | Jul 10, 2022 |
| HP            | Laptop 15-da1xxx            | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | [019c2b1194](https://linux-hardware.org/?probe=019c2b1194) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | [1f47ada680](https://linux-hardware.org/?probe=1f47ada680) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | [8476e2e1c3](https://linux-hardware.org/?probe=8476e2e1c3) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | [add34d1f6a](https://linux-hardware.org/?probe=add34d1f6a) | Jul 05, 2022 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [1773a0941f](https://linux-hardware.org/?probe=1773a0941f) | Jul 05, 2022 |
| Acer          | Aspire E5-576G              | [74f6e010da](https://linux-hardware.org/?probe=74f6e010da) | Jul 04, 2022 |
| MSI           | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| System76      | Oryx Pro                    | [7fa7a1ca82](https://linux-hardware.org/?probe=7fa7a1ca82) | Jun 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Toshiba       | Satellite Pro S300          | [09f9ef25cd](https://linux-hardware.org/?probe=09f9ef25cd) | Jun 27, 2022 |
| HP            | EliteBook 840 G3            | [0d16a3f2ce](https://linux-hardware.org/?probe=0d16a3f2ce) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| ASUSTek       | All Series                  | [19dde83002](https://linux-hardware.org/?probe=19dde83002) | Jun 26, 2022 |
| Acer          | Aspire E1-572G              | [c2fceb2c81](https://linux-hardware.org/?probe=c2fceb2c81) | Jun 24, 2022 |
| Dell          | Inspiron 5459               | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| Acer          | Aspire ES1-571              | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1D00... | [eacaed715b](https://linux-hardware.org/?probe=eacaed715b) | Jun 21, 2022 |
| System76      | Oryx Pro                    | [c623d50d29](https://linux-hardware.org/?probe=c623d50d29) | Jun 20, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [bf292ae80a](https://linux-hardware.org/?probe=bf292ae80a) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1cf9eae6e5](https://linux-hardware.org/?probe=1cf9eae6e5) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Notebook      | PA70ES                      | [7024a9dc03](https://linux-hardware.org/?probe=7024a9dc03) | Jun 16, 2022 |
| HP            | ZBook Studio G3             | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| System76      | Oryx Pro                    | [8488dcacf9](https://linux-hardware.org/?probe=8488dcacf9) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [5d49ce7763](https://linux-hardware.org/?probe=5d49ce7763) | Jun 10, 2022 |
| Razer         | Blade                       | [2d8524dc81](https://linux-hardware.org/?probe=2d8524dc81) | Jun 10, 2022 |
| HP            | Laptop 14-dk1xxx            | [f895a113f9](https://linux-hardware.org/?probe=f895a113f9) | Jun 09, 2022 |
| HP            | Laptop 14-dk1xxx            | [e29eb57530](https://linux-hardware.org/?probe=e29eb57530) | Jun 09, 2022 |
| Dell          | Latitude 5421               | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| HP            | Laptop 15-da1xxx            | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| ASUSTek       | GL703VD                     | [3a9d836e5e](https://linux-hardware.org/?probe=3a9d836e5e) | Jun 03, 2022 |
| ASUSTek       | GL703VD                     | [531d7297d9](https://linux-hardware.org/?probe=531d7297d9) | Jun 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| System76      | Oryx Pro                    | [5f84134f5d](https://linux-hardware.org/?probe=5f84134f5d) | May 29, 2022 |
| Toshiba       | Satellite C675              | [72daf96a34](https://linux-hardware.org/?probe=72daf96a34) | May 28, 2022 |
| Unknown       | Unknown                     | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| System76      | Oryx Pro                    | [2652ac64a4](https://linux-hardware.org/?probe=2652ac64a4) | May 25, 2022 |
| Lenovo        | ThinkPad L540 20AV0031GE    | [13f326fc7d](https://linux-hardware.org/?probe=13f326fc7d) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| Toshiba       | PORTEGE R30-A               | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| MSI           | GF75 Thin 9SC               | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| LG Electro... | C500                        | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| HP            | Pavilion Notebook           | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Sony          | SVE1712C1EW                 | [9410df7433](https://linux-hardware.org/?probe=9410df7433) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [75ec4a948b](https://linux-hardware.org/?probe=75ec4a948b) | May 18, 2022 |
| Lenovo        | ThinkPad T400 276521G       | [9a2f5118c5](https://linux-hardware.org/?probe=9a2f5118c5) | May 15, 2022 |
| HP            | Folio 13                    | [9c9cd2aa91](https://linux-hardware.org/?probe=9c9cd2aa91) | May 15, 2022 |
| System76      | Oryx Pro                    | [d740686b5e](https://linux-hardware.org/?probe=d740686b5e) | May 14, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [3780dc0fe5](https://linux-hardware.org/?probe=3780dc0fe5) | May 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [09d0c5a57c](https://linux-hardware.org/?probe=09d0c5a57c) | May 10, 2022 |
| Samsung       | 550XDA                      | [d3d7a64817](https://linux-hardware.org/?probe=d3d7a64817) | May 08, 2022 |
| HP            | EliteBook 840 G3            | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| HP            | 250 G5 Notebook PC          | [a21e01fec5](https://linux-hardware.org/?probe=a21e01fec5) | May 07, 2022 |
| HP            | Laptop 17-cn0xxx            | [eab46c9089](https://linux-hardware.org/?probe=eab46c9089) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| ASUSTek       | G752VT                      | [b007cf4ed2](https://linux-hardware.org/?probe=b007cf4ed2) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [744b50ab3b](https://linux-hardware.org/?probe=744b50ab3b) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| HP            | Pavilion g7                 | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| HP            | Pavilion g7                 | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| Dell          | Latitude E7250              | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| HP            | ProBook 4430s               | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| Dell          | Latitude E7250              | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [542c9c6703](https://linux-hardware.org/?probe=542c9c6703) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Dell          | Latitude E6230              | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| Dell          | Latitude E6230              | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| Dell          | Latitude E6430              | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Dell          | Latitude 5421               | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8e7fc0aef9](https://linux-hardware.org/?probe=8e7fc0aef9) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | [9a18c2ac1c](https://linux-hardware.org/?probe=9a18c2ac1c) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ceae86aef1](https://linux-hardware.org/?probe=ceae86aef1) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| HP            | Laptop 15-dw0xxx            | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| System76      | Oryx Pro                    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| ASUSTek       | N550JK                      | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| Acer          | Aspire A515-52G             | [13775d028d](https://linux-hardware.org/?probe=13775d028d) | Mar 15, 2022 |
| Dell          | Precision 7540              | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| System76      | Oryx Pro                    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| Sony          | VPCEH25FM                   | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| Apple         | MacBookPro11,2              | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [270aaf59b6](https://linux-hardware.org/?probe=270aaf59b6) | Feb 25, 2022 |
| Lenovo        | ThinkPad S430 68852BU       | [7d7bb498fe](https://linux-hardware.org/?probe=7d7bb498fe) | Feb 25, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| Dell          | Inspiron 5567               | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| Dell          | Inspiron 15-3567            | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | K54L                        | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [3beffcfd3e](https://linux-hardware.org/?probe=3beffcfd3e) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [35ac77d812](https://linux-hardware.org/?probe=35ac77d812) | Feb 17, 2022 |
| ASUSTek       | K53E                        | [929e5d8462](https://linux-hardware.org/?probe=929e5d8462) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | 255 G7 Notebook PC          | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| Lenovo        | V15-IIL 82C5                | [c50b098929](https://linux-hardware.org/?probe=c50b098929) | Feb 10, 2022 |
| Dell          | XPS 15 9570                 | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| Compal        | PBL21                       | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [e6bc24c5b9](https://linux-hardware.org/?probe=e6bc24c5b9) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| HP            | 255 G7 Notebook PC          | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| HP            | 255 G7 Notebook PC          | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Dell          | Precision 5550              | [2853896d4c](https://linux-hardware.org/?probe=2853896d4c) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Notebook      | PA70ES                      | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| ASUSTek       | X750LN                      | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | [1c3c43b4ce](https://linux-hardware.org/?probe=1c3c43b4ce) | Feb 02, 2022 |
| Acer          | Aspire V3-771               | [f755eb7a78](https://linux-hardware.org/?probe=f755eb7a78) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Casper        | EXCALIBUR G860              | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [d2ebf4698b](https://linux-hardware.org/?probe=d2ebf4698b) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [9a1fb4d53e](https://linux-hardware.org/?probe=9a1fb4d53e) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | XPS 15 9500                 | [1db87d66c6](https://linux-hardware.org/?probe=1db87d66c6) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS0QQ00    | [470cd66ae6](https://linux-hardware.org/?probe=470cd66ae6) | Jan 27, 2022 |
| Dell          | XPS 17 9710                 | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a4172550fa](https://linux-hardware.org/?probe=a4172550fa) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| HP            | ProBook 450 G1              | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| ASUSTek       | X580VD                      | [299f1c8cca](https://linux-hardware.org/?probe=299f1c8cca) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Standard      | MB50II                      | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0287de904c](https://linux-hardware.org/?probe=0287de904c) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| ASUSTek       | 1001PX                      | [5343777492](https://linux-hardware.org/?probe=5343777492) | Jan 16, 2022 |
| HP            | 250 G7 Notebook PC          | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| HP            | ProBook 450 G2              | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Lenovo        | ThinkPad T560 20FH001TUS    | [f8400f7913](https://linux-hardware.org/?probe=f8400f7913) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| Acer          | Extensa 5620                | [a10369e225](https://linux-hardware.org/?probe=a10369e225) | Jan 08, 2022 |
| Sony          | VPCEB2B4E                   | [4d3b6ede0c](https://linux-hardware.org/?probe=4d3b6ede0c) | Jan 08, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| Monster       | ABRA A5 V11.1               | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [14ca887c8f](https://linux-hardware.org/?probe=14ca887c8f) | Jan 02, 2022 |
| Dell          | XPS 17 9710                 | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| Lenovo        | ThinkPad T410 2522AC1       | [0cf80c2ee3](https://linux-hardware.org/?probe=0cf80c2ee3) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Acer          | Nitro AN715-51              | [c3caffed3c](https://linux-hardware.org/?probe=c3caffed3c) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Latitude E4310              | [8b6976bdd2](https://linux-hardware.org/?probe=8b6976bdd2) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Monster       | ABRA A5 V11.1               | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Dell          | Latitude E4310              | [e5b46c1542](https://linux-hardware.org/?probe=e5b46c1542) | Dec 24, 2021 |
| ASUSTek       | X450LD                      | [b5e36a24f9](https://linux-hardware.org/?probe=b5e36a24f9) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Dell          | XPS 15 9510                 | [9bd5592765](https://linux-hardware.org/?probe=9bd5592765) | Dec 23, 2021 |
| Medion        | E4213 MD99329               | [8801cfdb2a](https://linux-hardware.org/?probe=8801cfdb2a) | Dec 23, 2021 |
| Teclast       | F15S                        | [8be33fb7e2](https://linux-hardware.org/?probe=8be33fb7e2) | Dec 23, 2021 |
| MSI           | GE72 6QC                    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Dell          | Latitude 3410               | [a0b79031ae](https://linux-hardware.org/?probe=a0b79031ae) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| Apple         | MacBookPro8,1               | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Acer          | Aspire F5-573G              | [55e4486324](https://linux-hardware.org/?probe=55e4486324) | Dec 18, 2021 |
| Lenovo        | ThinkPad T430 2349DG5       | [9bd0a6e07d](https://linux-hardware.org/?probe=9bd0a6e07d) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| Acer          | Aspire 5741G                | [702be0b615](https://linux-hardware.org/?probe=702be0b615) | Dec 17, 2021 |
| Acer          | Aspire 5741G                | [60d68b4c13](https://linux-hardware.org/?probe=60d68b4c13) | Dec 17, 2021 |
| Dell          | Inspiron 3505               | [14ffa86838](https://linux-hardware.org/?probe=14ffa86838) | Dec 17, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Apple         | MacBookPro11,2              | [9cb226408e](https://linux-hardware.org/?probe=9cb226408e) | Dec 15, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [b7b09dcc5e](https://linux-hardware.org/?probe=b7b09dcc5e) | Dec 15, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Precision M4800             | [90109636fe](https://linux-hardware.org/?probe=90109636fe) | Dec 15, 2021 |
| Dell          | Precision M4800             | [0d1cfc9a0e](https://linux-hardware.org/?probe=0d1cfc9a0e) | Dec 15, 2021 |
| Notebook      | NH5xAx                      | [62f88112f1](https://linux-hardware.org/?probe=62f88112f1) | Dec 14, 2021 |
| Alienware     | 15 R3                       | [6394aa965a](https://linux-hardware.org/?probe=6394aa965a) | Dec 14, 2021 |
| Acer          | Aspire E5-532G              | [8cbbaee4ad](https://linux-hardware.org/?probe=8cbbaee4ad) | Dec 14, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | [5faef7686a](https://linux-hardware.org/?probe=5faef7686a) | Dec 14, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| HP            | Laptop 15-da0xxx            | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| Acer          | Extensa 5635ZG              | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [91eeb42bcb](https://linux-hardware.org/?probe=91eeb42bcb) | Dec 13, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | Precision 5550              | [9e88f6034f](https://linux-hardware.org/?probe=9e88f6034f) | Dec 12, 2021 |
| System76      | Galago Pro                  | [9fe1e9175f](https://linux-hardware.org/?probe=9fe1e9175f) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [6343dc8a43](https://linux-hardware.org/?probe=6343dc8a43) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| Apple         | MacBookPro11,5              | [e59e1a3c29](https://linux-hardware.org/?probe=e59e1a3c29) | Dec 12, 2021 |
| Lenovo        | ThinkPad X201 3680KC5       | [64958365b3](https://linux-hardware.org/?probe=64958365b3) | Dec 12, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [da7c19f0b4](https://linux-hardware.org/?probe=da7c19f0b4) | Dec 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| System76      | Darter Pro                  | [2e84db8ffb](https://linux-hardware.org/?probe=2e84db8ffb) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c5f999eb1e](https://linux-hardware.org/?probe=c5f999eb1e) | Dec 11, 2021 |
| Acer          | Swift SF314-41              | [4e9e6b5c99](https://linux-hardware.org/?probe=4e9e6b5c99) | Dec 11, 2021 |
| Apple         | MacBookPro11,2              | [debd9b86e1](https://linux-hardware.org/?probe=debd9b86e1) | Dec 11, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [8fe2d382de](https://linux-hardware.org/?probe=8fe2d382de) | Dec 08, 2021 |
| Dell          | Inspiron 5468               | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [cf8576527d](https://linux-hardware.org/?probe=cf8576527d) | Dec 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [ee8b533768](https://linux-hardware.org/?probe=ee8b533768) | Dec 07, 2021 |
| HP            | ENVY Notebook               | [179bd0eae8](https://linux-hardware.org/?probe=179bd0eae8) | Dec 05, 2021 |
| HP            | ENVY Notebook               | [58488b0351](https://linux-hardware.org/?probe=58488b0351) | Dec 05, 2021 |
| Razer         | Blade Stealth               | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| ASUSTek       | K501UX                      | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| HP            | Notebook                    | [9f7082bedb](https://linux-hardware.org/?probe=9f7082bedb) | Dec 03, 2021 |
| Lenovo        | V14-ADA 82C6                | [7fd0e9e7cd](https://linux-hardware.org/?probe=7fd0e9e7cd) | Dec 03, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| HP            | Pavilion g7                 | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| Apple         | MacBookPro11,2              | [681845a2e3](https://linux-hardware.org/?probe=681845a2e3) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [b022b376ee](https://linux-hardware.org/?probe=b022b376ee) | Nov 28, 2021 |
| Dell          | Inspiron 3505               | [d3cfe93dc6](https://linux-hardware.org/?probe=d3cfe93dc6) | Nov 28, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | V14-ADA 82C6                | [a0f72af8d9](https://linux-hardware.org/?probe=a0f72af8d9) | Nov 26, 2021 |
| ASUSTek       | X556UQK                     | [38ca30691b](https://linux-hardware.org/?probe=38ca30691b) | Nov 26, 2021 |
| HP            | Laptop 15-bw0xx             | [071447b964](https://linux-hardware.org/?probe=071447b964) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [485f0b0858](https://linux-hardware.org/?probe=485f0b0858) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [e215995139](https://linux-hardware.org/?probe=e215995139) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| HP            | Laptop 14q-cs0xxx           | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| Dell          | Latitude E5450              | [a1c9396c75](https://linux-hardware.org/?probe=a1c9396c75) | Nov 23, 2021 |
| HP            | EliteBook 840 G1            | [8338e70267](https://linux-hardware.org/?probe=8338e70267) | Nov 22, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [dcc60be203](https://linux-hardware.org/?probe=dcc60be203) | Nov 20, 2021 |
| HUAWEI        | WRT-WX9                     | [b94e6da627](https://linux-hardware.org/?probe=b94e6da627) | Nov 18, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Dell          | Inspiron 3558               | [b0f06cc210](https://linux-hardware.org/?probe=b0f06cc210) | Nov 18, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| Dell          | Inspiron 5579               | [0f7bccdef0](https://linux-hardware.org/?probe=0f7bccdef0) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| Apple         | MacBook5,1                  | [6ddb5fdd76](https://linux-hardware.org/?probe=6ddb5fdd76) | Nov 12, 2021 |
| HUAWEI        | KPL-W0X                     | [bffba05735](https://linux-hardware.org/?probe=bffba05735) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HUAWEI        | KPL-W0X                     | [4a189c2903](https://linux-hardware.org/?probe=4a189c2903) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Dell          | Inspiron 5721               | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| Dell          | Latitude E6440              | [38e3c1e18a](https://linux-hardware.org/?probe=38e3c1e18a) | Nov 06, 2021 |
| Dell          | Precision 7510              | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| HP            | 630                         | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [000c804ed5](https://linux-hardware.org/?probe=000c804ed5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T470 20HES01100    | [d3c8a48b29](https://linux-hardware.org/?probe=d3c8a48b29) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | [f581cf8319](https://linux-hardware.org/?probe=f581cf8319) | Nov 01, 2021 |
| Apple         | MacBookPro8,1               | [6e17fb6ea4](https://linux-hardware.org/?probe=6e17fb6ea4) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | XPS 13 9343                 | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Razer         | Blade                       | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| Dell          | Latitude E6540              | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| ASUSTek       | X580VD                      | [aff8edafa4](https://linux-hardware.org/?probe=aff8edafa4) | Oct 20, 2021 |
| ASUSTek       | X555LD                      | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Acer          | Aspire E5-523               | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| Dell          | Latitude E7440              | [98c988645f](https://linux-hardware.org/?probe=98c988645f) | Oct 18, 2021 |
| Acer          | Aspire SW5-173              | [38872d1422](https://linux-hardware.org/?probe=38872d1422) | Oct 17, 2021 |
| HUAWEI        | WRT-WX9                     | [d9cd722532](https://linux-hardware.org/?probe=d9cd722532) | Oct 17, 2021 |
| ASUSTek       | N53Jq                       | [3cd3bb5eae](https://linux-hardware.org/?probe=3cd3bb5eae) | Oct 16, 2021 |
| Dell          | Inspiron 3520               | [56fe4ab8a1](https://linux-hardware.org/?probe=56fe4ab8a1) | Oct 16, 2021 |
| Acer          | Nitro AN515-55              | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| Dell          | Precision M4800             | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8fbafb0d7e](https://linux-hardware.org/?probe=8fbafb0d7e) | Oct 16, 2021 |
| System76      | Pangolin                    | [e4fb2b6b8a](https://linux-hardware.org/?probe=e4fb2b6b8a) | Oct 16, 2021 |
| UNITCOM       | W55xEU                      | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e16a7eaba9](https://linux-hardware.org/?probe=e16a7eaba9) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [eed2a8b965](https://linux-hardware.org/?probe=eed2a8b965) | Oct 15, 2021 |
| Lenovo        | G50-30 80G0                 | [3d5411b3f0](https://linux-hardware.org/?probe=3d5411b3f0) | Oct 13, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Samsung       | 550P5C/550P7C               | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| Razer         | Blade Stealth               | [82e8aefe39](https://linux-hardware.org/?probe=82e8aefe39) | Oct 09, 2021 |
| TUXEDO        | Unknown                     | [59193a23d9](https://linux-hardware.org/?probe=59193a23d9) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| MSI           | GS66 Stealth 10SFS          | [2ff9b97589](https://linux-hardware.org/?probe=2ff9b97589) | Oct 06, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| HP            | Pavilion dv6                | [ee806bc406](https://linux-hardware.org/?probe=ee806bc406) | Sep 30, 2021 |
| HP            | Pavilion dv6                | [252520800c](https://linux-hardware.org/?probe=252520800c) | Sep 30, 2021 |
| Chuwi         | GemiBook Pro                | [4ee2cf61ef](https://linux-hardware.org/?probe=4ee2cf61ef) | Sep 29, 2021 |
| Monster       | ABRA A5 V11.1               | [34b6bc562c](https://linux-hardware.org/?probe=34b6bc562c) | Sep 29, 2021 |
| Apple         | MacBookAir7,1               | [4642e930ca](https://linux-hardware.org/?probe=4642e930ca) | Sep 28, 2021 |
| Monster       | ABRA A5 V11.1               | [b70d12e2f5](https://linux-hardware.org/?probe=b70d12e2f5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [9cd2ba74a0](https://linux-hardware.org/?probe=9cd2ba74a0) | Sep 27, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Lenovo        | ThinkPad T450s 20BWS07N0... | [cb83c57f1c](https://linux-hardware.org/?probe=cb83c57f1c) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [de3b970f84](https://linux-hardware.org/?probe=de3b970f84) | Sep 23, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [7d9277109c](https://linux-hardware.org/?probe=7d9277109c) | Sep 23, 2021 |
| Toshiba       | IS 1442                     | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| Samsung       | QX311/QX411/QX412/QX511     | [9c968d26f7](https://linux-hardware.org/?probe=9c968d26f7) | Sep 21, 2021 |
| ASUSTek       | UX550VE                     | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [2aab2f6ffb](https://linux-hardware.org/?probe=2aab2f6ffb) | Sep 21, 2021 |
| Chuwi         | GemiBook Pro                | [17c3ec978f](https://linux-hardware.org/?probe=17c3ec978f) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | UX303LN                     | [9c8bb62a98](https://linux-hardware.org/?probe=9c8bb62a98) | Sep 17, 2021 |
| MSI           | GP76 Leopard 10UE           | [547ee4e1ea](https://linux-hardware.org/?probe=547ee4e1ea) | Sep 16, 2021 |
| MSI           | GP76 Leopard 10UE           | [90168ebbeb](https://linux-hardware.org/?probe=90168ebbeb) | Sep 16, 2021 |
| Toshiba       | QOSMIO X75-A                | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Fujitsu       | LIFEBOOK A357               | [efc14ead6c](https://linux-hardware.org/?probe=efc14ead6c) | Sep 13, 2021 |
| Toshiba       | QOSMIO X75-A                | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| Lenovo        | ThinkPad T490 20N3S19L00    | [a19eee5494](https://linux-hardware.org/?probe=a19eee5494) | Sep 11, 2021 |
| Fujitsu       | LIFEBOOK A357               | [6a38389900](https://linux-hardware.org/?probe=6a38389900) | Sep 11, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| HP            | ZBook Studio G3             | [d239ae254a](https://linux-hardware.org/?probe=d239ae254a) | Sep 09, 2021 |
| Pegatron      | T14AF                       | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Lenovo        | ThinkPad T450s 20BWS04K0... | [3c7ed2f9b7](https://linux-hardware.org/?probe=3c7ed2f9b7) | Sep 06, 2021 |
| Acer          | Aspire 7750G                | [2b645d2c16](https://linux-hardware.org/?probe=2b645d2c16) | Sep 05, 2021 |
| ASUSTek       | X510UA                      | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| Acer          | Swift SF114-32              | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| Dell          | XPS 15 9560                 | [4b8701a2b3](https://linux-hardware.org/?probe=4b8701a2b3) | Sep 05, 2021 |
| Dell          | Inspiron 5570               | [ffa40a366f](https://linux-hardware.org/?probe=ffa40a366f) | Sep 05, 2021 |
| HP            | Laptop 15q-bu0xx            | [bc433a2411](https://linux-hardware.org/?probe=bc433a2411) | Sep 04, 2021 |
| Lenovo        | ThinkPad W540 20BHS0LA00    | [d5b967eeee](https://linux-hardware.org/?probe=d5b967eeee) | Sep 04, 2021 |
| Dell          | Latitude E6420              | [0d79becf85](https://linux-hardware.org/?probe=0d79becf85) | Sep 03, 2021 |
| Dell          | XPS 13 9300                 | [9b10289848](https://linux-hardware.org/?probe=9b10289848) | Sep 02, 2021 |
| ASUSTek       | X555QG                      | [14d10602c8](https://linux-hardware.org/?probe=14d10602c8) | Sep 02, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | [1fd99ca58d](https://linux-hardware.org/?probe=1fd99ca58d) | Sep 02, 2021 |
| Acer          | Aspire 5750                 | [c3ae9f4793](https://linux-hardware.org/?probe=c3ae9f4793) | Sep 01, 2021 |
| Acer          | Nitro AN517-52              | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Timi          | TM1607                      | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| ASUSTek       | G750JX                      | [53da9f0547](https://linux-hardware.org/?probe=53da9f0547) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | [14f5f8a179](https://linux-hardware.org/?probe=14f5f8a179) | Aug 28, 2021 |
| Dell          | Inspiron 15-5568            | [81b3e142a3](https://linux-hardware.org/?probe=81b3e142a3) | Aug 28, 2021 |
| Dell          | Inspiron 5579               | [11d1c6d073](https://linux-hardware.org/?probe=11d1c6d073) | Aug 28, 2021 |
| Apple         | MacBookPro11,1              | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| Eluktronic... | MAG-15 2070                 | [28b869ed18](https://linux-hardware.org/?probe=28b869ed18) | Aug 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f6fa665265](https://linux-hardware.org/?probe=f6fa665265) | Aug 27, 2021 |
| Dell          | XPS 15 9500                 | [62f508237e](https://linux-hardware.org/?probe=62f508237e) | Aug 25, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6ab2831848](https://linux-hardware.org/?probe=6ab2831848) | Aug 25, 2021 |
| HP            | Laptop 15-bw0xx             | [e6c79ed475](https://linux-hardware.org/?probe=e6c79ed475) | Aug 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0016FR     | [94091b0705](https://linux-hardware.org/?probe=94091b0705) | Aug 24, 2021 |
| System76      | Gazelle                     | [b1f5d2f5db](https://linux-hardware.org/?probe=b1f5d2f5db) | Aug 24, 2021 |
| System76      | Gazelle                     | [be7855ec0c](https://linux-hardware.org/?probe=be7855ec0c) | Aug 24, 2021 |
| Fujitsu       | LIFEBOOK E756               | [ad2bc5b140](https://linux-hardware.org/?probe=ad2bc5b140) | Aug 23, 2021 |
| HP            | Laptop 15-da0xxx            | [2aafbc0a72](https://linux-hardware.org/?probe=2aafbc0a72) | Aug 23, 2021 |
| Dell          | Inspiron 5579               | [4e844d3321](https://linux-hardware.org/?probe=4e844d3321) | Aug 22, 2021 |
| HP            | Laptop 15-db0xxx            | [83c1674e38](https://linux-hardware.org/?probe=83c1674e38) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | [6dbfd72cd8](https://linux-hardware.org/?probe=6dbfd72cd8) | Aug 21, 2021 |
| ASUSTek       | X580VD                      | [5df36dba53](https://linux-hardware.org/?probe=5df36dba53) | Aug 21, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [24bbd4d06f](https://linux-hardware.org/?probe=24bbd4d06f) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e7fd668005](https://linux-hardware.org/?probe=e7fd668005) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e17fcec0b4](https://linux-hardware.org/?probe=e17fcec0b4) | Aug 21, 2021 |
| Dell          | Inspiron 15-5568            | [7fec9a3a5b](https://linux-hardware.org/?probe=7fec9a3a5b) | Aug 21, 2021 |
| Lenovo        | ThinkPad T440 20B70048US    | [14e8d60953](https://linux-hardware.org/?probe=14e8d60953) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 7661ZLF        | [d28b77f82f](https://linux-hardware.org/?probe=d28b77f82f) | Aug 19, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC1K    | [d693db633c](https://linux-hardware.org/?probe=d693db633c) | Aug 18, 2021 |
| Dell          | XPS 15 7590                 | [3d348a9d2a](https://linux-hardware.org/?probe=3d348a9d2a) | Aug 18, 2021 |
| ASUSTek       | X556UA                      | [04710b290b](https://linux-hardware.org/?probe=04710b290b) | Aug 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4cfe1daabe](https://linux-hardware.org/?probe=4cfe1daabe) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ffa5f6a0e](https://linux-hardware.org/?probe=1ffa5f6a0e) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d00e9f1724](https://linux-hardware.org/?probe=d00e9f1724) | Aug 14, 2021 |
| ASUSTek       | X580VD                      | [4a86f48291](https://linux-hardware.org/?probe=4a86f48291) | Aug 14, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| ASUSTek       | X580VD                      | [aeae754f0f](https://linux-hardware.org/?probe=aeae754f0f) | Aug 12, 2021 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e42d32bf2a](https://linux-hardware.org/?probe=e42d32bf2a) | Aug 12, 2021 |
| Acer          | Aspire 7741                 | [9d26562113](https://linux-hardware.org/?probe=9d26562113) | Aug 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| HP            | Laptop 15q-bu1xx            | [5aced87a3f](https://linux-hardware.org/?probe=5aced87a3f) | Aug 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [e9d2ccb049](https://linux-hardware.org/?probe=e9d2ccb049) | Aug 09, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [5f24fa8f98](https://linux-hardware.org/?probe=5f24fa8f98) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [51115b9f9f](https://linux-hardware.org/?probe=51115b9f9f) | Aug 08, 2021 |
| Lenovo        | ThinkPad W541 20EF0000US    | [6150ef8ebc](https://linux-hardware.org/?probe=6150ef8ebc) | Aug 07, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| Acer          | Nitro AN515-53              | [baf0ccecb1](https://linux-hardware.org/?probe=baf0ccecb1) | Aug 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [c434457251](https://linux-hardware.org/?probe=c434457251) | Aug 03, 2021 |
| AZW           | SEi                         | [de596531ae](https://linux-hardware.org/?probe=de596531ae) | Aug 02, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Lenovo        | ThinkPad X201 3626GWG       | [3709f5744a](https://linux-hardware.org/?probe=3709f5744a) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [2b732e43eb](https://linux-hardware.org/?probe=2b732e43eb) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [68b431bc45](https://linux-hardware.org/?probe=68b431bc45) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [a8e52318c8](https://linux-hardware.org/?probe=a8e52318c8) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [949e4af6a7](https://linux-hardware.org/?probe=949e4af6a7) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [65d9b956bc](https://linux-hardware.org/?probe=65d9b956bc) | Jul 30, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e84e4c3d4c](https://linux-hardware.org/?probe=e84e4c3d4c) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Dell          | Precision 7520              | [bb1844c704](https://linux-hardware.org/?probe=bb1844c704) | Jul 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| HP            | Compaq Presario CQ40        | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| HP            | Compaq Presario CQ40        | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| Unknown       | Unknown                     | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| Dell          | Latitude 5410               | [cb463b1fc3](https://linux-hardware.org/?probe=cb463b1fc3) | Jul 22, 2021 |
| HP            | Stream Notebook PC 13       | [6631c46029](https://linux-hardware.org/?probe=6631c46029) | Jul 22, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| HP            | Laptop 15-da0xxx            | [4cb2daf424](https://linux-hardware.org/?probe=4cb2daf424) | Jul 16, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [be2edf1657](https://linux-hardware.org/?probe=be2edf1657) | Jul 14, 2021 |
| Acer          | Aspire E5-575G              | [672a2b3117](https://linux-hardware.org/?probe=672a2b3117) | Jul 14, 2021 |
| HP            | Notebook                    | [021a011da8](https://linux-hardware.org/?probe=021a011da8) | Jul 13, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [9779eaca87](https://linux-hardware.org/?probe=9779eaca87) | Jul 11, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [329bbc8c40](https://linux-hardware.org/?probe=329bbc8c40) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | [2114ad4f9e](https://linux-hardware.org/?probe=2114ad4f9e) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | [a469d525e3](https://linux-hardware.org/?probe=a469d525e3) | Jul 10, 2021 |
| Fujitsu       | LIFEBOOK S751               | [fc7d66f096](https://linux-hardware.org/?probe=fc7d66f096) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | [252e038506](https://linux-hardware.org/?probe=252e038506) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | [bb7d68bae6](https://linux-hardware.org/?probe=bb7d68bae6) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK T902               | [4ed05b4d7b](https://linux-hardware.org/?probe=4ed05b4d7b) | Jul 07, 2021 |
| Acer          | Aspire E5-573G              | [f1f413aced](https://linux-hardware.org/?probe=f1f413aced) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6f489566ae](https://linux-hardware.org/?probe=6f489566ae) | Jul 06, 2021 |
| Fujitsu       | LIFEBOOK T902               | [4fb535811d](https://linux-hardware.org/?probe=4fb535811d) | Jul 05, 2021 |
| ASUSTek       | Q550LF                      | [3aafd6f8a6](https://linux-hardware.org/?probe=3aafd6f8a6) | Jul 05, 2021 |
| Dell          | Latitude 7480               | [827e1b8a21](https://linux-hardware.org/?probe=827e1b8a21) | Jul 04, 2021 |
| Fujitsu       | LIFEBOOK T902               | [7e6ee2f561](https://linux-hardware.org/?probe=7e6ee2f561) | Jul 04, 2021 |
| ASUSTek       | X510UNR                     | [3c8630ec48](https://linux-hardware.org/?probe=3c8630ec48) | Jul 04, 2021 |
| Notebook      | P95_HP                      | [8aa8037e16](https://linux-hardware.org/?probe=8aa8037e16) | Jul 03, 2021 |
| Dell          | Vostro 5568                 | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | [e08d79f016](https://linux-hardware.org/?probe=e08d79f016) | Jul 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | [06e8c86830](https://linux-hardware.org/?probe=06e8c86830) | Jul 02, 2021 |
| HP            | 250 G1                      | [bc56e9fe6f](https://linux-hardware.org/?probe=bc56e9fe6f) | Jul 02, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c0ed3a3c09](https://linux-hardware.org/?probe=c0ed3a3c09) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | [ea85c0f143](https://linux-hardware.org/?probe=ea85c0f143) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Apple         | MacBookPro12,1              | [0a8dac703d](https://linux-hardware.org/?probe=0a8dac703d) | Jun 29, 2021 |
| Apple         | MacBookPro8,1               | [aac1bf4737](https://linux-hardware.org/?probe=aac1bf4737) | Jun 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [127874b25b](https://linux-hardware.org/?probe=127874b25b) | Jun 28, 2021 |
| ASUSTek       | K53E                        | [3ad8363a7d](https://linux-hardware.org/?probe=3ad8363a7d) | Jun 28, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [ceab39c39a](https://linux-hardware.org/?probe=ceab39c39a) | Jun 28, 2021 |
| Acer          | Predator G3-572             | [982137c856](https://linux-hardware.org/?probe=982137c856) | Jun 28, 2021 |
| Lenovo        | ThinkPad X240 20AM001RGE    | [5e80a2492e](https://linux-hardware.org/?probe=5e80a2492e) | Jun 28, 2021 |
| Apple         | MacBookPro11,5              | [29dedcc0c7](https://linux-hardware.org/?probe=29dedcc0c7) | Jun 28, 2021 |
| AZW           | GT-R                        | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | [5fd8e985e9](https://linux-hardware.org/?probe=5fd8e985e9) | Jun 28, 2021 |
| Dell          | XPS 17 9700                 | [cbf1953567](https://linux-hardware.org/?probe=cbf1953567) | Jun 27, 2021 |
| Alienware     | m15 Ryzen Ed. R5            | [d48faf5072](https://linux-hardware.org/?probe=d48faf5072) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Toshiba       | Satellite C600              | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| MSI           | Modern 14 A10M              | [a07552d987](https://linux-hardware.org/?probe=a07552d987) | Jun 24, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| HP            | EliteBook 840 G4            | [1155abf435](https://linux-hardware.org/?probe=1155abf435) | Jun 22, 2021 |
| HUAWEI        | MACH-WX9                    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Dell          | Inspiron 13-5378            | [5246eabc5f](https://linux-hardware.org/?probe=5246eabc5f) | Jun 17, 2021 |
| Dell          | Inspiron 3593               | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [22aabc71ef](https://linux-hardware.org/?probe=22aabc71ef) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [99a0a332ec](https://linux-hardware.org/?probe=99a0a332ec) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | [b81aa5226f](https://linux-hardware.org/?probe=b81aa5226f) | Jun 17, 2021 |
| Alienware     | 17                          | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ac8e80e0cc](https://linux-hardware.org/?probe=ac8e80e0cc) | Jun 15, 2021 |
| Apple         | MacBookAir1,1               | [a6cf581d50](https://linux-hardware.org/?probe=a6cf581d50) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | [48c28ecda7](https://linux-hardware.org/?probe=48c28ecda7) | Jun 14, 2021 |
| Dell          | Inspiron 5485 2n1           | [cda45b1f3c](https://linux-hardware.org/?probe=cda45b1f3c) | Jun 14, 2021 |
| Dell          | Latitude E6440              | [908df2d475](https://linux-hardware.org/?probe=908df2d475) | Jun 13, 2021 |
| Medion        | Erazer X7841 MD99556        | [a15e0c5ae0](https://linux-hardware.org/?probe=a15e0c5ae0) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | [f6b6b11c24](https://linux-hardware.org/?probe=f6b6b11c24) | Jun 12, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Fujitsu       | LIFEBOOK S751               | [20ff390b75](https://linux-hardware.org/?probe=20ff390b75) | Jun 11, 2021 |
| Acer          | Aspire A715-71G             | [64db1224d0](https://linux-hardware.org/?probe=64db1224d0) | Jun 10, 2021 |
| HP            | Laptop 15q-bu0xx            | [758cd92d87](https://linux-hardware.org/?probe=758cd92d87) | Jun 10, 2021 |
| Razer         | Blade                       | [e6ee630e9b](https://linux-hardware.org/?probe=e6ee630e9b) | Jun 06, 2021 |
| Apple         | MacBookPro11,1              | [f6f2cf5f89](https://linux-hardware.org/?probe=f6f2cf5f89) | Jun 05, 2021 |
| Lenovo        | ThinkPad X220 4290LD4       | [22bbadb3dd](https://linux-hardware.org/?probe=22bbadb3dd) | Jun 03, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | [fa237f560a](https://linux-hardware.org/?probe=fa237f560a) | Jun 02, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | [4d799b19db](https://linux-hardware.org/?probe=4d799b19db) | Jun 02, 2021 |
| Toshiba       | Satellite L635              | [c5883a9da8](https://linux-hardware.org/?probe=c5883a9da8) | Jun 01, 2021 |
| Toshiba       | Satellite L635              | [634bc5add8](https://linux-hardware.org/?probe=634bc5add8) | May 30, 2021 |
| System76      | Oryx Pro                    | [e18b16565f](https://linux-hardware.org/?probe=e18b16565f) | May 29, 2021 |
| Toshiba       | Satellite R630              | [0c557895be](https://linux-hardware.org/?probe=0c557895be) | May 29, 2021 |
| Daten Tecn... | ESTELAR                     | [f19e7920ca](https://linux-hardware.org/?probe=f19e7920ca) | May 29, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1daf88898e](https://linux-hardware.org/?probe=1daf88898e) | May 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [302b62a5c7](https://linux-hardware.org/?probe=302b62a5c7) | May 20, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [0d44d30be1](https://linux-hardware.org/?probe=0d44d30be1) | May 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [00aa4c11f4](https://linux-hardware.org/?probe=00aa4c11f4) | May 13, 2021 |
| Sony          | SVE14125CXP                 | [23d5e048cb](https://linux-hardware.org/?probe=23d5e048cb) | May 13, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [28f6f5a90b](https://linux-hardware.org/?probe=28f6f5a90b) | May 12, 2021 |
| Toshiba       | Satellite L50-A-19N         | [988020930b](https://linux-hardware.org/?probe=988020930b) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| HP            | Pavilion Notebook           | [da82b1b43f](https://linux-hardware.org/?probe=da82b1b43f) | May 09, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [ab871dcbe2](https://linux-hardware.org/?probe=ab871dcbe2) | May 01, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [f8bbdfd850](https://linux-hardware.org/?probe=f8bbdfd850) | Apr 30, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [2df93a93d1](https://linux-hardware.org/?probe=2df93a93d1) | Apr 30, 2021 |
| HP            | 250 G1                      | [0810673d99](https://linux-hardware.org/?probe=0810673d99) | Apr 29, 2021 |
| Dell          | Latitude E6440              | [535815022c](https://linux-hardware.org/?probe=535815022c) | Apr 23, 2021 |
| HP            | 255 G2                      | [338785dab3](https://linux-hardware.org/?probe=338785dab3) | Apr 22, 2021 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [f707b24713](https://linux-hardware.org/?probe=f707b24713) | Apr 22, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [16ab380d72](https://linux-hardware.org/?probe=16ab380d72) | Apr 21, 2021 |
| Dell          | Vostro 3550                 | [2b122eb7e6](https://linux-hardware.org/?probe=2b122eb7e6) | Apr 21, 2021 |
| ASUSTek       | UX430UAR                    | [a071188f1c](https://linux-hardware.org/?probe=a071188f1c) | Apr 21, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| HP            | EliteBook 8460p             | [dc1e0bf320](https://linux-hardware.org/?probe=dc1e0bf320) | Apr 19, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [eeee3c8078](https://linux-hardware.org/?probe=eeee3c8078) | Apr 18, 2021 |
| HP            | 255 G7 Notebook PC          | [ba1e3ed32e](https://linux-hardware.org/?probe=ba1e3ed32e) | Apr 15, 2021 |
| Dell          | XPS 15 9570                 | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Lenovo        | G50-45 80E3                 | [7633456df0](https://linux-hardware.org/?probe=7633456df0) | Apr 15, 2021 |
| ASUSTek       | N550JV                      | [61b2baa2d1](https://linux-hardware.org/?probe=61b2baa2d1) | Apr 13, 2021 |
| Chuwi         | GemiBook Pro                | [9909625298](https://linux-hardware.org/?probe=9909625298) | Apr 12, 2021 |
| Acer          | Predator PH315-52           | [97c81f4b56](https://linux-hardware.org/?probe=97c81f4b56) | Apr 11, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [76b41f73e8](https://linux-hardware.org/?probe=76b41f73e8) | Apr 11, 2021 |
| Toshiba       | PORTEGE Z30t-C              | [39dd5ca43b](https://linux-hardware.org/?probe=39dd5ca43b) | Apr 11, 2021 |
| Dell          | XPS 13 9380                 | [8ceda587e7](https://linux-hardware.org/?probe=8ceda587e7) | Apr 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [337a0c3723](https://linux-hardware.org/?probe=337a0c3723) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| HP            | EliteBook 840 G3            | [5a663fff6e](https://linux-hardware.org/?probe=5a663fff6e) | Apr 05, 2021 |
| Lenovo        | ThinkPad X220 4291WF5       | [7cf8cfd8f8](https://linux-hardware.org/?probe=7cf8cfd8f8) | Apr 04, 2021 |
| Lenovo        | ThinkPad T480 20L6S27S0P    | [6fc0f5a4b6](https://linux-hardware.org/?probe=6fc0f5a4b6) | Apr 03, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [53fe8e1c6c](https://linux-hardware.org/?probe=53fe8e1c6c) | Mar 31, 2021 |
| Dell          | Latitude E7440              | [e0c5eda63a](https://linux-hardware.org/?probe=e0c5eda63a) | Mar 31, 2021 |
| Dell          | Inspiron 5520               | [151b34a749](https://linux-hardware.org/?probe=151b34a749) | Mar 29, 2021 |
| Dell          | Latitude E7440              | [1c004faf2a](https://linux-hardware.org/?probe=1c004faf2a) | Mar 28, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [7fe4a33a38](https://linux-hardware.org/?probe=7fe4a33a38) | Mar 27, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| Dell          | Latitude 3580               | [0de8d9cd4c](https://linux-hardware.org/?probe=0de8d9cd4c) | Mar 25, 2021 |
| Dell          | Latitude E6530              | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad 11e 20D90020US     | [e5948a4e4c](https://linux-hardware.org/?probe=e5948a4e4c) | Mar 24, 2021 |
| Dell          | Inspiron 5593               | [0348f8af6b](https://linux-hardware.org/?probe=0348f8af6b) | Mar 23, 2021 |
| Dell          | Latitude E4310              | [16025a8970](https://linux-hardware.org/?probe=16025a8970) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Dell          | Inspiron 5575               | [4b72276133](https://linux-hardware.org/?probe=4b72276133) | Mar 17, 2021 |
| Dell          | Latitude E6440              | [8eb5c8aaa9](https://linux-hardware.org/?probe=8eb5c8aaa9) | Mar 17, 2021 |
| Dell          | Inspiron 5555               | [4b3ec85962](https://linux-hardware.org/?probe=4b3ec85962) | Mar 16, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| HP            | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2347GU8       | [1c74d63cc4](https://linux-hardware.org/?probe=1c74d63cc4) | Mar 10, 2021 |
| Apple         | MacBookPro11,3              | [06f7468dab](https://linux-hardware.org/?probe=06f7468dab) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| Lenovo        | ThinkPad T570 20H90002GE    | [ce32634171](https://linux-hardware.org/?probe=ce32634171) | Mar 09, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| Dell          | Latitude E6530              | [15b1567c06](https://linux-hardware.org/?probe=15b1567c06) | Feb 27, 2021 |
| Dell          | Latitude E6530              | [519e2218aa](https://linux-hardware.org/?probe=519e2218aa) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | [602223a1ab](https://linux-hardware.org/?probe=602223a1ab) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| Toshiba       | Satellite L775              | [670f2c264f](https://linux-hardware.org/?probe=670f2c264f) | Feb 24, 2021 |
| Acer          | Aspire E5-573G              | [55a00ca46d](https://linux-hardware.org/?probe=55a00ca46d) | Feb 24, 2021 |
| Bluechip C... | BUSINESSline                | [740e39daaa](https://linux-hardware.org/?probe=740e39daaa) | Feb 23, 2021 |
| Dell          | XPS 15 9570                 | [084be10f62](https://linux-hardware.org/?probe=084be10f62) | Feb 19, 2021 |
| Dell          | Latitude 5480               | [41472dbe02](https://linux-hardware.org/?probe=41472dbe02) | Feb 18, 2021 |
| Apple         | MacBookPro5,1               | [238564a9fc](https://linux-hardware.org/?probe=238564a9fc) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [b27e52570f](https://linux-hardware.org/?probe=b27e52570f) | Feb 17, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Apple         | MacBookPro11,1              | [e121595694](https://linux-hardware.org/?probe=e121595694) | Feb 16, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| Apple         | MacBookPro5,5               | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| Notebook      | N2x0WU                      | [e660e0f0da](https://linux-hardware.org/?probe=e660e0f0da) | Feb 05, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [874d0c0e0e](https://linux-hardware.org/?probe=874d0c0e0e) | Feb 05, 2021 |
| Sony          | VPCF11J1E                   | [a4c36618e9](https://linux-hardware.org/?probe=a4c36618e9) | Feb 03, 2021 |
| HP            | ENVY 17                     | [7b09b4c5b4](https://linux-hardware.org/?probe=7b09b4c5b4) | Feb 02, 2021 |
| Dell          | XPS 13 9300                 | [ec70bba0fc](https://linux-hardware.org/?probe=ec70bba0fc) | Feb 01, 2021 |
| Google        | Swanky                      | [c4dd59ca8a](https://linux-hardware.org/?probe=c4dd59ca8a) | Jan 29, 2021 |
| Dell          | Latitude D820               | [c4b9edad97](https://linux-hardware.org/?probe=c4b9edad97) | Jan 24, 2021 |
| Lenovo        | ThinkPad T61 64659TU        | [6bb7d90da6](https://linux-hardware.org/?probe=6bb7d90da6) | Jan 23, 2021 |
| Lenovo        | ThinkPad T61 64659TU        | [b302c2489e](https://linux-hardware.org/?probe=b302c2489e) | Jan 23, 2021 |
| ASUSTek       | K56CM                       | [e1da558e84](https://linux-hardware.org/?probe=e1da558e84) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Lenovo        | B50-10 80QR                 | [136f6c27fb](https://linux-hardware.org/?probe=136f6c27fb) | Jan 22, 2021 |
| Medion        | E7222                       | [c5b59cdd1a](https://linux-hardware.org/?probe=c5b59cdd1a) | Jan 21, 2021 |
| HP            | Pavilion Notebook           | [66efbfed55](https://linux-hardware.org/?probe=66efbfed55) | Jan 19, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [fc5afc1dc2](https://linux-hardware.org/?probe=fc5afc1dc2) | Jan 18, 2021 |
| Lenovo        | ThinkPad T440S 20AQ005NU... | [356ab4974a](https://linux-hardware.org/?probe=356ab4974a) | Jan 18, 2021 |
| HP            | ENVY Notebook               | [e75216ca48](https://linux-hardware.org/?probe=e75216ca48) | Jan 17, 2021 |
| Dell          | Latitude E6530              | [da4602f931](https://linux-hardware.org/?probe=da4602f931) | Jan 16, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [325809a72d](https://linux-hardware.org/?probe=325809a72d) | Jan 16, 2021 |
| Dell          | Inspiron 7558               | [272d237def](https://linux-hardware.org/?probe=272d237def) | Jan 15, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80UE         | [7b790852bf](https://linux-hardware.org/?probe=7b790852bf) | Jan 13, 2021 |
| Acer          | Aspire VN7-792G             | [0b1c2de104](https://linux-hardware.org/?probe=0b1c2de104) | Jan 13, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [8956e9185a](https://linux-hardware.org/?probe=8956e9185a) | Jan 13, 2021 |
| Lenovo        | V155-15API 81V5             | [a3143c0638](https://linux-hardware.org/?probe=a3143c0638) | Jan 13, 2021 |
| Acer          | NU-A515-44-R68D             | [f45afd1e14](https://linux-hardware.org/?probe=f45afd1e14) | Jan 12, 2021 |
| Dell          | Latitude E6540              | [c6ab95a062](https://linux-hardware.org/?probe=c6ab95a062) | Jan 11, 2021 |
| Dell          | Latitude E6540              | [565853d023](https://linux-hardware.org/?probe=565853d023) | Jan 10, 2021 |
| HP            | 250 G7 Notebook PC          | [0d0aa5182b](https://linux-hardware.org/?probe=0d0aa5182b) | Jan 10, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| HP            | 15                          | [7559b865f0](https://linux-hardware.org/?probe=7559b865f0) | Jan 06, 2021 |
| Apple         | MacBookPro9,2               | [62f0ab94ac](https://linux-hardware.org/?probe=62f0ab94ac) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| Dell          | XPS L501X                   | [4ced160372](https://linux-hardware.org/?probe=4ced160372) | Dec 31, 2020 |
| SLIMBOOK      | PROX15-AMD                  | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [ca0a06995e](https://linux-hardware.org/?probe=ca0a06995e) | Dec 28, 2020 |
| HP            | ENVY m6                     | [50e8b7f0f6](https://linux-hardware.org/?probe=50e8b7f0f6) | Dec 28, 2020 |
| Dell          | XPS 13 9370                 | [d96119f05d](https://linux-hardware.org/?probe=d96119f05d) | Dec 26, 2020 |
| Dell          | Inspiron 3476               | [c269f527ed](https://linux-hardware.org/?probe=c269f527ed) | Dec 25, 2020 |
| Lenovo        | V155-15API 81V5             | [afd1dcfbae](https://linux-hardware.org/?probe=afd1dcfbae) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| ASUSTek       | X540SAA                     | [fafdaae4cb](https://linux-hardware.org/?probe=fafdaae4cb) | Dec 23, 2020 |
| HP            | EliteBook 6930p             | [ddde2864e6](https://linux-hardware.org/?probe=ddde2864e6) | Dec 22, 2020 |
| Lenovo        | V155-15API 81V5             | [45526695b8](https://linux-hardware.org/?probe=45526695b8) | Dec 21, 2020 |
| Lenovo        | ThinkPad T480s 20L8S8540... | [12fb9652a7](https://linux-hardware.org/?probe=12fb9652a7) | Dec 21, 2020 |
| Dell          | XPS 15 9560                 | [47fb295e32](https://linux-hardware.org/?probe=47fb295e32) | Dec 21, 2020 |
| Samsung       | NC210/NC110                 | [98057a3a7a](https://linux-hardware.org/?probe=98057a3a7a) | Dec 19, 2020 |
| Samsung       | NC210/NC110                 | [4f3402c9dc](https://linux-hardware.org/?probe=4f3402c9dc) | Dec 19, 2020 |
| Timi          | TM1709                      | [089615b43f](https://linux-hardware.org/?probe=089615b43f) | Dec 16, 2020 |
| HP            | EliteBook 8760w             | [5e2ff51ade](https://linux-hardware.org/?probe=5e2ff51ade) | Dec 15, 2020 |
| Lenovo        | Flex 2-14 20404             | [8c7c33ba8b](https://linux-hardware.org/?probe=8c7c33ba8b) | Dec 14, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| HP            | EliteBook Folio 9480m       | [7d51a3bee8](https://linux-hardware.org/?probe=7d51a3bee8) | Dec 14, 2020 |
| HP            | Notebook                    | [a770f1e52d](https://linux-hardware.org/?probe=a770f1e52d) | Dec 13, 2020 |
| TUXEDO        | Polaris 15 AMD Gen1         | [602a601769](https://linux-hardware.org/?probe=602a601769) | Dec 11, 2020 |
| HP            | OMEN by Laptop              | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| Acer          | Swift SF314-41              | [5155111cfa](https://linux-hardware.org/?probe=5155111cfa) | Dec 10, 2020 |
| Acer          | AOD260                      | [635a9139e1](https://linux-hardware.org/?probe=635a9139e1) | Dec 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [baf10417f7](https://linux-hardware.org/?probe=baf10417f7) | Dec 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| Dell          | Latitude 5480               | [02680953ae](https://linux-hardware.org/?probe=02680953ae) | Dec 04, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [e6ee8ad4bb](https://linux-hardware.org/?probe=e6ee8ad4bb) | Dec 03, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [153a43bcc6](https://linux-hardware.org/?probe=153a43bcc6) | Dec 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [52cf6d4786](https://linux-hardware.org/?probe=52cf6d4786) | Dec 02, 2020 |
| Fujitsu       | LIFEBOOK AH562              | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Timi          | TM1709                      | [bcccdee6ec](https://linux-hardware.org/?probe=bcccdee6ec) | Nov 29, 2020 |
| System76      | Galago Pro                  | [00eb3fca1a](https://linux-hardware.org/?probe=00eb3fca1a) | Nov 27, 2020 |
| Dell          | System Inspiron N4110       | [8d8bd09d64](https://linux-hardware.org/?probe=8d8bd09d64) | Nov 27, 2020 |
| Toshiba       | Satellite S70-B             | [d9925a0d93](https://linux-hardware.org/?probe=d9925a0d93) | Nov 26, 2020 |
| Dell          | Latitude 5310               | [b941f2a157](https://linux-hardware.org/?probe=b941f2a157) | Nov 25, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [cd48e9d406](https://linux-hardware.org/?probe=cd48e9d406) | Nov 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ce492b1a92](https://linux-hardware.org/?probe=ce492b1a92) | Nov 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3cfe7597e](https://linux-hardware.org/?probe=e3cfe7597e) | Nov 25, 2020 |
| Dell          | Inspiron 3558               | [2beee5183a](https://linux-hardware.org/?probe=2beee5183a) | Nov 24, 2020 |
| Lenovo        | G580                        | [bbca803600](https://linux-hardware.org/?probe=bbca803600) | Nov 23, 2020 |
| Dell          | Latitude 5480               | [30bffef4fc](https://linux-hardware.org/?probe=30bffef4fc) | Nov 22, 2020 |
| Lenovo        | V130-14IGM 81HM             | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| HP            | EliteBook 8540p             | [d9ca357ad7](https://linux-hardware.org/?probe=d9ca357ad7) | Nov 20, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Lenovo        | ThinkPad T430 2347AQ9       | [6fa209f1de](https://linux-hardware.org/?probe=6fa209f1de) | Nov 19, 2020 |
| Entroware     | Apollo                      | [6d7a020174](https://linux-hardware.org/?probe=6d7a020174) | Nov 19, 2020 |
| Dell          | XPS L421X                   | [4efcda4ace](https://linux-hardware.org/?probe=4efcda4ace) | Nov 18, 2020 |
| Dell          | Inspiron 5770               | [6abb25b1de](https://linux-hardware.org/?probe=6abb25b1de) | Nov 18, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [75d38974bc](https://linux-hardware.org/?probe=75d38974bc) | Nov 15, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [299e10281f](https://linux-hardware.org/?probe=299e10281f) | Nov 15, 2020 |
| Timi          | TM1709                      | [522d6ab484](https://linux-hardware.org/?probe=522d6ab484) | Nov 15, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [eafab55a01](https://linux-hardware.org/?probe=eafab55a01) | Nov 15, 2020 |
| Acer          | Aspire E5-532               | [79948d67b4](https://linux-hardware.org/?probe=79948d67b4) | Nov 15, 2020 |
| ASUSTek       | K52JT                       | [be614c012f](https://linux-hardware.org/?probe=be614c012f) | Nov 15, 2020 |
| Timi          | TM1607                      | [db600ca49e](https://linux-hardware.org/?probe=db600ca49e) | Nov 14, 2020 |
| Acer          | Aspire E5-523               | [316dc021cb](https://linux-hardware.org/?probe=316dc021cb) | Nov 14, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [867148b244](https://linux-hardware.org/?probe=867148b244) | Nov 14, 2020 |
| HP            | EliteBook 8540p             | [1df463aa08](https://linux-hardware.org/?probe=1df463aa08) | Nov 13, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [addf2ac7fa](https://linux-hardware.org/?probe=addf2ac7fa) | Nov 12, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 692       | 87.59%  |
| ArcoLinux             | 77        | 9.75%   |
| ArcoLinux 20.6.5      | 7         | 0.89%   |
| ArcoLinux 20.7.5      | 4         | 0.51%   |
| ArcoLinux 20.3.4      | 2         | 0.25%   |
| ArcoLinux 20.3.3      | 2         | 0.25%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.13%   |
| ArcoLinux 6.9.2       | 1         | 0.13%   |
| ArcoLinux 20.2.12     | 1         | 0.13%   |
| ArcoLinux 20.1.4      | 1         | 0.13%   |
| ArcoLinux 19.07.11    | 1         | 0.13%   |
| ArcoLinux 19.02.4     | 1         | 0.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ArcoLinux | 785       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.15.7-arch1-1  | 20        | 2.27%   |
| 5.15.10-arch1-1 | 19        | 2.15%   |
| 5.13.13-arch1-1 | 18        | 2.04%   |
| 5.14.14-arch1-1 | 14        | 1.59%   |
| 5.13.12-arch1-1 | 13        | 1.47%   |
| 5.14.12-arch1-1 | 12        | 1.36%   |
| 5.17.1-arch1-1  | 11        | 1.25%   |
| 5.12.13-arch1-2 | 10        | 1.13%   |
| 5.15.11-arch2-1 | 9         | 1.02%   |
| 6.0.8-arch1-1   | 8         | 0.91%   |
| 5.9.8-arch1-1   | 8         | 0.91%   |
| 5.9.1-arch1-1   | 8         | 0.91%   |
| 5.16.10-arch1-1 | 8         | 0.91%   |
| 5.15.5-arch1-1  | 8         | 0.91%   |
| 5.12.15-arch1-1 | 8         | 0.91%   |
| 5.12.14-arch1-1 | 8         | 0.91%   |
| 5.17.4-arch1-1  | 7         | 0.79%   |
| 5.16.2-arch1-1  | 7         | 0.79%   |
| 5.16.16-arch1-1 | 7         | 0.79%   |
| 5.15.13-arch1-1 | 7         | 0.79%   |
| 5.12.10-arch1-1 | 7         | 0.79%   |
| 6.1.1-arch1-1   | 6         | 0.68%   |
| 6.0.2-arch1-1   | 6         | 0.68%   |
| 6.0.10-arch2-1  | 6         | 0.68%   |
| 5.9.10-arch1-1  | 6         | 0.68%   |
| 5.19.13-arch1-1 | 6         | 0.68%   |
| 5.18.16-arch1-1 | 6         | 0.68%   |
| 5.17.5-arch1-1  | 6         | 0.68%   |
| 5.16.12-arch1-1 | 6         | 0.68%   |
| 5.14.9-arch2-1  | 6         | 0.68%   |
| 5.13.8-arch1-1  | 6         | 0.68%   |
| 5.12.12-arch1-1 | 6         | 0.68%   |
| 5.10.84-1-lts   | 6         | 0.68%   |
| 6.0.7-arch1-1   | 5         | 0.57%   |
| 5.4.70-1-lts    | 5         | 0.57%   |
| 5.19.11-arch1-1 | 5         | 0.57%   |
| 5.18.3-arch1-1  | 5         | 0.57%   |
| 5.16.11-arch1-1 | 5         | 0.57%   |
| 5.15.4-arch1-1  | 5         | 0.57%   |
| 5.15.12-arch1-1 | 5         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.7  | 24        | 2.72%   |
| 5.15.10 | 19        | 2.15%   |
| 5.13.13 | 18        | 2.04%   |
| 5.17.1  | 14        | 1.59%   |
| 5.14.14 | 14        | 1.59%   |
| 5.14.12 | 13        | 1.47%   |
| 5.13.12 | 13        | 1.47%   |
| 5.9.8   | 12        | 1.36%   |
| 6.0.2   | 11        | 1.25%   |
| 6.0.8   | 10        | 1.13%   |
| 5.9.1   | 10        | 1.13%   |
| 5.12.13 | 10        | 1.13%   |
| 6.1.1   | 9         | 1.02%   |
| 5.16.2  | 9         | 1.02%   |
| 5.16.10 | 9         | 1.02%   |
| 5.15.5  | 9         | 1.02%   |
| 5.15.11 | 9         | 1.02%   |
| 5.12.15 | 9         | 1.02%   |
| 5.9.14  | 8         | 0.91%   |
| 5.14.9  | 8         | 0.91%   |
| 5.12.14 | 8         | 0.91%   |
| 5.10.16 | 8         | 0.91%   |
| 6.1.6   | 7         | 0.79%   |
| 6.0.7   | 7         | 0.79%   |
| 6.0.10  | 7         | 0.79%   |
| 5.9.6   | 7         | 0.79%   |
| 5.9.10  | 7         | 0.79%   |
| 5.17.5  | 7         | 0.79%   |
| 5.17.4  | 7         | 0.79%   |
| 5.16.16 | 7         | 0.79%   |
| 5.15.13 | 7         | 0.79%   |
| 5.12.10 | 7         | 0.79%   |
| 5.19.13 | 6         | 0.68%   |
| 5.19.11 | 6         | 0.68%   |
| 5.18.3  | 6         | 0.68%   |
| 5.18.16 | 6         | 0.68%   |
| 5.16.12 | 6         | 0.68%   |
| 5.16.11 | 6         | 0.68%   |
| 5.15.4  | 6         | 0.68%   |
| 5.13.9  | 6         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 138       | 16.16%  |
| 5.10    | 123       | 14.4%   |
| 5.16    | 64        | 7.49%   |
| 5.14    | 62        | 7.26%   |
| 5.13    | 60        | 7.03%   |
| 5.9     | 57        | 6.67%   |
| 5.12    | 54        | 6.32%   |
| 6.0     | 53        | 6.21%   |
| 5.17    | 47        | 5.5%    |
| 5.18    | 43        | 5.04%   |
| 5.11    | 35        | 4.1%    |
| 6.1     | 33        | 3.86%   |
| 5.4     | 33        | 3.86%   |
| 5.19    | 33        | 3.86%   |
| 5.8     | 6         | 0.7%    |
| 5.7     | 4         | 0.47%   |
| 5.5     | 3         | 0.35%   |
| 5.6     | 2         | 0.23%   |
| 5.2     | 1         | 0.12%   |
| 5.0     | 1         | 0.12%   |
| 4.20    | 1         | 0.12%   |
| 4.18    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 785       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| XFCE           | 253       | 31.16%  |
| KDE5           | 133       | 16.38%  |
| i3             | 67        | 8.25%   |
| GNOME          | 56        | 6.9%    |
| awesome        | 50        | 6.16%   |
| qtile          | 39        | 4.8%    |
| bspwm          | 33        | 4.06%   |
| X-Cinnamon     | 30        | 3.69%   |
| xmonad         | 27        | 3.33%   |
| DWM            | 27        | 3.33%   |
| LeftWM         | 12        | 1.48%   |
| KDE            | 12        | 1.48%   |
| Unknown        | 11        | 1.35%   |
| MATE           | 9         | 1.11%   |
| Deepin         | 8         | 0.99%   |
| Budgie         | 7         | 0.86%   |
| i3-with-shmlog | 6         | 0.74%   |
| herbstluftwm   | 6         | 0.74%   |
| LXQt           | 4         | 0.49%   |
| Cinnamon       | 4         | 0.49%   |
| sway           | 3         | 0.37%   |
| spectrwm       | 3         | 0.37%   |
| Unity          | 2         | 0.25%   |
| cwm            | 2         | 0.25%   |
| openbox        | 1         | 0.12%   |
| jwm            | 1         | 0.12%   |
| ICEWM          | 1         | 0.12%   |
| Hyprland       | 1         | 0.12%   |
| GNOME Classic  | 1         | 0.12%   |
| dwm-sc         | 1         | 0.12%   |
| dusk           | 1         | 0.12%   |
| Cutefish       | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 736       | 93.28%  |
| Tty     | 27        | 3.42%   |
| Wayland | 23        | 2.92%   |
| Unknown | 3         | 0.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 414       | 50.36%  |
| TDM     | 149       | 18.13%  |
| LightDM | 139       | 16.91%  |
| Unknown | 94        | 11.44%  |
| GDM     | 20        | 2.43%   |
| Ly      | 3         | 0.36%   |
| XDM     | 1         | 0.12%   |
| SLiM    | 1         | 0.12%   |
| LXDM    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 459       | 57.81%  |
| en_GB   | 56        | 7.05%   |
| de_DE   | 44        | 5.54%   |
| en_CA   | 27        | 3.4%    |
| en_IN   | 26        | 3.27%   |
| fr_FR   | 18        | 2.27%   |
| en_AU   | 13        | 1.64%   |
| ru_RU   | 11        | 1.39%   |
| pt_BR   | 11        | 1.39%   |
| pl_PL   | 10        | 1.26%   |
| es_ES   | 9         | 1.13%   |
| Unknown | 7         | 0.88%   |
| hu_HU   | 6         | 0.76%   |
| es_AR   | 6         | 0.76%   |
| it_IT   | 5         | 0.63%   |
| en_ZA   | 5         | 0.63%   |
| tr_TR   | 4         | 0.5%    |
| ru_UA   | 4         | 0.5%    |
| es_MX   | 4         | 0.5%    |
| en_IE   | 4         | 0.5%    |
| nl_BE   | 3         | 0.38%   |
| es_CL   | 3         | 0.38%   |
| en_SG   | 3         | 0.38%   |
| en_PH   | 3         | 0.38%   |
| en_IL   | 3         | 0.38%   |
| en_DK   | 3         | 0.38%   |
| el_GR   | 3         | 0.38%   |
| C       | 3         | 0.38%   |
| sv_SE   | 2         | 0.25%   |
| ro_RO   | 2         | 0.25%   |
| nl_NL   | 2         | 0.25%   |
| nb_NO   | 2         | 0.25%   |
| ja_JP   | 2         | 0.25%   |
| fr_CA   | 2         | 0.25%   |
| fr_BE   | 2         | 0.25%   |
| fi_FI   | 2         | 0.25%   |
| es_CO   | 2         | 0.25%   |
| en_NZ   | 2         | 0.25%   |
| de_ch   | 2         | 0.25%   |
| de_AT   | 2         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 552       | 69.87%  |
| BIOS | 238       | 30.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 603       | 76.04%  |
| Btrfs   | 138       | 17.4%   |
| Overlay | 34        | 4.29%   |
| Xfs     | 12        | 1.51%   |
| F2fs    | 3         | 0.38%   |
| Tmpfs   | 1         | 0.13%   |
| Jfs     | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 563       | 71.09%  |
| MBR     | 142       | 17.93%  |
| Unknown | 87        | 10.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 652       | 81.4%   |
| Yes       | 149       | 18.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 523       | 66.29%  |
| Yes       | 266       | 33.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 222       | 28.28%  |
| Dell                  | 124       | 15.8%   |
| Hewlett-Packard       | 105       | 13.38%  |
| ASUSTek Computer      | 94        | 11.97%  |
| Acer                  | 56        | 7.13%   |
| Apple                 | 28        | 3.57%   |
| MSI                   | 18        | 2.29%   |
| Toshiba               | 17        | 2.17%   |
| Sony                  | 10        | 1.27%   |
| Samsung Electronics   | 10        | 1.27%   |
| HUAWEI                | 9         | 1.15%   |
| System76              | 8         | 1.02%   |
| Timi                  | 7         | 0.89%   |
| Razer                 | 7         | 0.89%   |
| Fujitsu               | 7         | 0.89%   |
| Notebook              | 6         | 0.76%   |
| Medion                | 6         | 0.76%   |
| Alienware             | 6         | 0.76%   |
| TUXEDO                | 5         | 0.64%   |
| Chuwi                 | 4         | 0.51%   |
| Schenker              | 3         | 0.38%   |
| Unknown               | 3         | 0.38%   |
| Teclast               | 2         | 0.25%   |
| LG Electronics        | 2         | 0.25%   |
| Gigabyte Technology   | 2         | 0.25%   |
| Casper                | 2         | 0.25%   |
| AZW                   | 2         | 0.25%   |
| Xplore                | 1         | 0.13%   |
| UNITCOM               | 1         | 0.13%   |
| Standard              | 1         | 0.13%   |
| SLIMBOOK              | 1         | 0.13%   |
| Shuttle               | 1         | 0.13%   |
| Semp Toshiba          | 1         | 0.13%   |
| Positivo Bahia - VAIO | 1         | 0.13%   |
| Pegatron              | 1         | 0.13%   |
| Packard Bell          | 1         | 0.13%   |
| NEC Computers         | 1         | 0.13%   |
| Monster               | 1         | 0.13%   |
| Intel Client Systems  | 1         | 0.13%   |
| Google                | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Pavilion Notebook                | 6         | 0.76%   |
| HP Notebook                         | 5         | 0.64%   |
| Unknown                             | 5         | 0.64%   |
| Razer Blade                         | 4         | 0.51%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ    | 4         | 0.51%   |
| HP EliteBook 840 G3                 | 4         | 0.51%   |
| Dell XPS 15 9570                    | 4         | 0.51%   |
| Timi TM1607                         | 3         | 0.38%   |
| Lenovo Legion Y540-15IRH 81SX       | 3         | 0.38%   |
| Lenovo Legion 5 15ARH05 82B5        | 3         | 0.38%   |
| Lenovo IdeaPad 5 14ARE05 81YM       | 3         | 0.38%   |
| Lenovo IdeaPad 320-15ISK 80XH       | 3         | 0.38%   |
| HUAWEI KLVL-WXX9                    | 3         | 0.38%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 3         | 0.38%   |
| HP Laptop 15s-eq2xxx                | 3         | 0.38%   |
| HP Laptop 15-da0xxx                 | 3         | 0.38%   |
| HP ENVY Notebook                    | 3         | 0.38%   |
| HP EliteBook 8460p                  | 3         | 0.38%   |
| HP 255 G7 Notebook PC               | 3         | 0.38%   |
| HP 250 G7 Notebook PC               | 3         | 0.38%   |
| Dell Precision M4800                | 3         | 0.38%   |
| Dell Latitude E6530                 | 3         | 0.38%   |
| Dell Latitude 7480                  | 3         | 0.38%   |
| Dell Inspiron 5570                  | 3         | 0.38%   |
| Dell Inspiron 15 7000 Gaming        | 3         | 0.38%   |
| Chuwi GemiBook Pro                  | 3         | 0.38%   |
| Apple MacBookPro9,2                 | 3         | 0.38%   |
| Apple MacBookPro8,1                 | 3         | 0.38%   |
| Apple MacBookPro11,2                | 3         | 0.38%   |
| Apple MacBookPro11,1                | 3         | 0.38%   |
| Acer Swift SF314-41                 | 3         | 0.38%   |
| Acer Aspire E5-575G                 | 3         | 0.38%   |
| Toshiba Satellite L775              | 2         | 0.25%   |
| Timi TM1701                         | 2         | 0.25%   |
| System76 Pangolin                   | 2         | 0.25%   |
| System76 Oryx Pro                   | 2         | 0.25%   |
| System76 Galago Pro                 | 2         | 0.25%   |
| Samsung 550XDA                      | 2         | 0.25%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 2         | 0.25%   |
| Razer Blade Stealth                 | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 124       | 15.8%   |
| Lenovo IdeaPad     | 50        | 6.37%   |
| Dell Latitude      | 42        | 5.35%   |
| Dell Inspiron      | 39        | 4.97%   |
| Acer Aspire        | 37        | 4.71%   |
| Dell XPS           | 22        | 2.8%    |
| ASUS VivoBook      | 22        | 2.8%    |
| HP Laptop          | 21        | 2.68%   |
| HP EliteBook       | 21        | 2.68%   |
| Lenovo Legion      | 20        | 2.55%   |
| HP Pavilion        | 20        | 2.55%   |
| Toshiba Satellite  | 14        | 1.78%   |
| Dell Precision     | 12        | 1.53%   |
| ASUS ROG           | 9         | 1.15%   |
| HP ENVY            | 8         | 1.02%   |
| Apple MacBookPro11 | 8         | 1.02%   |
| Acer Nitro         | 8         | 1.02%   |
| Razer Blade        | 7         | 0.89%   |
| HP ProBook         | 7         | 0.89%   |
| Fujitsu LIFEBOOK   | 7         | 0.89%   |
| Dell Vostro        | 7         | 0.89%   |
| ASUS TUF           | 7         | 0.89%   |
| HP 250             | 6         | 0.76%   |
| HP Notebook        | 5         | 0.64%   |
| Acer Swift         | 5         | 0.64%   |
| Unknown            | 5         | 0.64%   |
| Lenovo Yoga        | 4         | 0.51%   |
| HP 255             | 4         | 0.51%   |
| ASUS Zephyrus      | 4         | 0.51%   |
| Timi TM1607        | 3         | 0.38%   |
| Lenovo ThinkBook   | 3         | 0.38%   |
| HUAWEI KLVL-WXX9   | 3         | 0.38%   |
| HP ZBook           | 3         | 0.38%   |
| Chuwi GemiBook     | 3         | 0.38%   |
| ASUS ZenBook       | 3         | 0.38%   |
| Apple MacBookPro9  | 3         | 0.38%   |
| Apple MacBookPro8  | 3         | 0.38%   |
| Apple MacBookPro5  | 3         | 0.38%   |
| Acer Predator      | 3         | 0.38%   |
| Toshiba PORTEGE    | 2         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 96        | 12.23%  |
| 2019 | 92        | 11.72%  |
| 2017 | 84        | 10.7%   |
| 2018 | 82        | 10.45%  |
| 2016 | 63        | 8.03%   |
| 2011 | 58        | 7.39%   |
| 2021 | 54        | 6.88%   |
| 2013 | 54        | 6.88%   |
| 2015 | 43        | 5.48%   |
| 2012 | 43        | 5.48%   |
| 2010 | 42        | 5.35%   |
| 2014 | 37        | 4.71%   |
| 2009 | 12        | 1.53%   |
| 2008 | 12        | 1.53%   |
| 2022 | 8         | 1.02%   |
| 2007 | 4         | 0.51%   |
| 2006 | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 785       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 785       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 780       | 99.36%  |
| Yes  | 5         | 0.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 260       | 32.95%  |
| 16.01-24.0  | 186       | 23.57%  |
| 8.01-16.0   | 144       | 18.25%  |
| 3.01-4.0    | 109       | 13.81%  |
| 32.01-64.0  | 53        | 6.72%   |
| 1.01-2.0    | 12        | 1.52%   |
| 24.01-32.0  | 10        | 1.27%   |
| 64.01-256.0 | 10        | 1.27%   |
| 2.01-3.0    | 5         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 276       | 32.62%  |
| 2.01-3.0   | 214       | 25.3%   |
| 3.01-4.0   | 121       | 14.3%   |
| 4.01-8.0   | 110       | 13%     |
| 0.51-1.0   | 81        | 9.57%   |
| 8.01-16.0  | 29        | 3.43%   |
| 0.01-0.5   | 12        | 1.42%   |
| 16.01-24.0 | 2         | 0.24%   |
| 24.01-32.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 525       | 65.87%  |
| 2      | 237       | 29.74%  |
| 3      | 27        | 3.39%   |
| 4      | 4         | 0.5%    |
| 0      | 3         | 0.38%   |
| 6      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 571       | 72.55%  |
| Yes       | 216       | 27.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 647       | 82.11%  |
| No        | 141       | 17.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 778       | 99.11%  |
| No        | 7         | 0.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 674       | 85.21%  |
| No        | 117       | 14.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 139       | 17.62%  |
| Germany      | 64        | 8.11%   |
| India        | 43        | 5.45%   |
| UK           | 37        | 4.69%   |
| Canada       | 34        | 4.31%   |
| France       | 26        | 3.3%    |
| Italy        | 21        | 2.66%   |
| Brazil       | 20        | 2.53%   |
| Belgium      | 20        | 2.53%   |
| Russia       | 19        | 2.41%   |
| Turkey       | 18        | 2.28%   |
| Poland       | 18        | 2.28%   |
| Spain        | 16        | 2.03%   |
| Netherlands  | 15        | 1.9%    |
| Switzerland  | 14        | 1.77%   |
| Australia    | 14        | 1.77%   |
| Hungary      | 13        | 1.65%   |
| Ukraine      | 12        | 1.52%   |
| Sweden       | 12        | 1.52%   |
| Romania      | 10        | 1.27%   |
| Argentina    | 10        | 1.27%   |
| Indonesia    | 9         | 1.14%   |
| Norway       | 8         | 1.01%   |
| Greece       | 8         | 1.01%   |
| Bangladesh   | 8         | 1.01%   |
| Finland      | 7         | 0.89%   |
| Egypt        | 7         | 0.89%   |
| South Africa | 6         | 0.76%   |
| Portugal     | 6         | 0.76%   |
| Mexico       | 6         | 0.76%   |
| Estonia      | 6         | 0.76%   |
| Czechia      | 6         | 0.76%   |
| Colombia     | 6         | 0.76%   |
| China        | 6         | 0.76%   |
| Bulgaria     | 6         | 0.76%   |
| Malaysia     | 5         | 0.63%   |
| Latvia       | 5         | 0.63%   |
| Ireland      | 5         | 0.63%   |
| Chile        | 5         | 0.63%   |
| Slovenia     | 4         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 7         | 0.86%   |
| Berlin            | 7         | 0.86%   |
| Tallinn           | 6         | 0.74%   |
| Pune              | 6         | 0.74%   |
| Paris             | 6         | 0.74%   |
| Milan             | 6         | 0.74%   |
| Ankara            | 6         | 0.74%   |
| Sydney            | 5         | 0.61%   |
| Madrid            | 5         | 0.61%   |
| Frankfurt am Main | 5         | 0.61%   |
| Budapest          | 5         | 0.61%   |
| Bergheim          | 5         | 0.61%   |
| Zurich            | 4         | 0.49%   |
| Warsaw            | 4         | 0.49%   |
| Stockholm         | 4         | 0.49%   |
| Spokane           | 4         | 0.49%   |
| Seville           | 4         | 0.49%   |
| Mumbai            | 4         | 0.49%   |
| Kolkata           | 4         | 0.49%   |
| Houston           | 4         | 0.49%   |
| Helsinki          | 4         | 0.49%   |
| Dhaka             | 4         | 0.49%   |
| Cairo             | 4         | 0.49%   |
| Brooklyn          | 4         | 0.49%   |
| Bogotá           | 4         | 0.49%   |
| Athens            | 4         | 0.49%   |
| Toronto           | 3         | 0.37%   |
| Tehran            | 3         | 0.37%   |
| Sofia             | 3         | 0.37%   |
| Singapore         | 3         | 0.37%   |
| Scottsdale        | 3         | 0.37%   |
| Sao Luís         | 3         | 0.37%   |
| Santiago          | 3         | 0.37%   |
| Rio de Janeiro    | 3         | 0.37%   |
| Ochten            | 3         | 0.37%   |
| London            | 3         | 0.37%   |
| Lisbon            | 3         | 0.37%   |
| Lier              | 3         | 0.37%   |
| Kyiv              | 3         | 0.37%   |
| Izmir             | 3         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 192       | 245    | 18.44%  |
| WDC                         | 141       | 174    | 13.54%  |
| Seagate                     | 117       | 129    | 11.24%  |
| Toshiba                     | 86        | 100    | 8.26%   |
| SanDisk                     | 56        | 65     | 5.38%   |
| SK hynix                    | 52        | 58     | 5%      |
| Kingston                    | 50        | 60     | 4.8%    |
| Crucial                     | 36        | 41     | 3.46%   |
| Intel                       | 35        | 43     | 3.36%   |
| HGST                        | 26        | 30     | 2.5%    |
| Micron Technology           | 25        | 25     | 2.4%    |
| Unknown                     | 24        | 35     | 2.31%   |
| Apple                       | 18        | 22     | 1.73%   |
| A-DATA Technology           | 16        | 17     | 1.54%   |
| Hitachi                     | 15        | 16     | 1.44%   |
| KIOXIA                      | 14        | 17     | 1.34%   |
| PNY                         | 11        | 13     | 1.06%   |
| LITEON                      | 11        | 12     | 1.06%   |
| Phison                      | 7         | 9      | 0.67%   |
| LITEONIT                    | 7         | 7      | 0.67%   |
| JMicron Technology          | 7         | 7      | 0.67%   |
| SPCC                        | 6         | 6      | 0.58%   |
| Kingston Technology Company | 5         | 6      | 0.48%   |
| Mushkin                     | 4         | 4      | 0.38%   |
| Micron/Crucial Technology   | 4         | 5      | 0.38%   |
| Intenso                     | 4         | 4      | 0.38%   |
| Corsair                     | 4         | 4      | 0.38%   |
| China                       | 4         | 4      | 0.38%   |
| Transcend                   | 3         | 3      | 0.29%   |
| Phison Electronics          | 3         | 3      | 0.29%   |
| Lenovo                      | 3         | 4      | 0.29%   |
| KingSpec                    | 3         | 3      | 0.29%   |
| Hewlett-Packard             | 3         | 4      | 0.29%   |
| Team                        | 2         | 2      | 0.19%   |
| SSSTC                       | 2         | 2      | 0.19%   |
| Silicon Motion              | 2         | 3      | 0.19%   |
| Plextor                     | 2         | 2      | 0.19%   |
| Patriot                     | 2         | 5      | 0.19%   |
| Netac                       | 2         | 2      | 0.19%   |
| Lexar                       | 2         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 32        | 2.94%   |
| Toshiba MQ04ABF100 1TB                              | 18        | 1.65%   |
| Samsung SSD 860 EVO 500GB                           | 17        | 1.56%   |
| Toshiba MQ01ABD100 1TB                              | 16        | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 13        | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 11        | 1.01%   |
| Kingston SA400S37240G 240GB SSD                     | 11        | 1.01%   |
| Seagate ST1000LM048-2E7172 1TB                      | 8         | 0.74%   |
| Samsung SSD 970 EVO Plus 1TB                        | 8         | 0.74%   |
| Seagate ST1000LM049-2GH172 1TB                      | 7         | 0.64%   |
| HGST HTS721010A9E630 1TB                            | 7         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                         | 7         | 0.64%   |
| Kingston SA400S37480G 480GB SSD                     | 6         | 0.55%   |
| JMicron Generic 500GB                               | 6         | 0.55%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 5         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 5         | 0.46%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 5         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB                      | 5         | 0.46%   |
| SanDisk SSD PLUS 480GB                              | 5         | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.46%   |
| Samsung SSD 850 EVO 250GB                           | 5         | 0.46%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 5         | 0.46%   |
| Intel SSD 660P Series 512GB                         | 5         | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 5         | 0.46%   |
| Apple SSD SM0256F 256GB                             | 5         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4         | 0.37%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 4         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 4         | 0.37%   |
| WDC WD10SPZX-08Z10 1TB                              | 4         | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 4         | 0.37%   |
| Unknown MMC Card  64GB                              | 4         | 0.37%   |
| SK hynix HFM512GDJTNG-8310A 512GB                   | 4         | 0.37%   |
| Seagate ST9320325AS 320GB                           | 4         | 0.37%   |
| Seagate Expansion 240GB                             | 4         | 0.37%   |
| SanDisk SSD U110 16GB                               | 4         | 0.37%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 0.37%   |
| Samsung SSD 860 EVO 1TB                             | 4         | 0.37%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 113       | 124    | 37.92%  |
| WDC                 | 69        | 87     | 23.15%  |
| Toshiba             | 59        | 68     | 19.8%   |
| HGST                | 26        | 30     | 8.72%   |
| Hitachi             | 15        | 16     | 5.03%   |
| Unknown             | 3         | 3      | 1.01%   |
| Samsung Electronics | 3         | 4      | 1.01%   |
| Apple               | 3         | 3      | 1.01%   |
| USB3.0              | 1         | 2      | 0.34%   |
| SABRENT             | 1         | 1      | 0.34%   |
| LaCie               | 1         | 1      | 0.34%   |
| KESU                | 1         | 1      | 0.34%   |
| Intenso             | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 2      | 0.34%   |
| ASMT                | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 100       | 131    | 25.19%  |
| SanDisk             | 42        | 46     | 10.58%  |
| Kingston            | 37        | 43     | 9.32%   |
| WDC                 | 35        | 43     | 8.82%   |
| Crucial             | 32        | 33     | 8.06%   |
| SK hynix            | 15        | 16     | 3.78%   |
| Apple               | 12        | 14     | 3.02%   |
| PNY                 | 11        | 13     | 2.77%   |
| Micron Technology   | 11        | 11     | 2.77%   |
| Intel               | 10        | 13     | 2.52%   |
| A-DATA Technology   | 10        | 11     | 2.52%   |
| Toshiba             | 9         | 11     | 2.27%   |
| LITEON              | 9         | 10     | 2.27%   |
| LITEONIT            | 7         | 7      | 1.76%   |
| SPCC                | 6         | 6      | 1.51%   |
| JMicron Technology  | 6         | 6      | 1.51%   |
| China               | 4         | 4      | 1.01%   |
| Transcend           | 3         | 3      | 0.76%   |
| KingSpec            | 3         | 3      | 0.76%   |
| Intenso             | 3         | 3      | 0.76%   |
| Team                | 2         | 2      | 0.5%    |
| Seagate             | 2         | 2      | 0.5%    |
| Plextor             | 2         | 2      | 0.5%    |
| Patriot             | 2         | 5      | 0.5%    |
| Mushkin             | 2         | 2      | 0.5%    |
| Lexar               | 2         | 2      | 0.5%    |
| Hewlett-Packard     | 2         | 2      | 0.5%    |
| GOODRAM             | 2         | 4      | 0.5%    |
| XrayDisk            | 1         | 1      | 0.25%   |
| W800S               | 1         | 2      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |
| SSSTC               | 1         | 1      | 0.25%   |
| Pioneer             | 1         | 1      | 0.25%   |
| OCZ                 | 1         | 1      | 0.25%   |
| NGFF                | 1         | 1      | 0.25%   |
| Netac               | 1         | 1      | 0.25%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.25%   |
| Kingmax             | 1         | 2      | 0.25%   |
| KingFast            | 1         | 1      | 0.25%   |
| HS-SSD-C100         | 1         | 2      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 358       | 467    | 36.64%  |
| NVMe    | 300       | 386    | 30.71%  |
| HDD     | 291       | 344    | 29.79%  |
| MMC     | 22        | 33     | 2.25%   |
| Unknown | 6         | 7      | 0.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 555       | 759    | 60%     |
| NVMe | 300       | 385    | 32.43%  |
| SAS  | 48        | 60     | 5.19%   |
| MMC  | 22        | 33     | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 382       | 492    | 58.68%  |
| 0.51-1.0   | 241       | 282    | 37.02%  |
| 1.01-2.0   | 20        | 29     | 3.07%   |
| 4.01-10.0  | 5         | 5      | 0.77%   |
| 3.01-4.0   | 3         | 3      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 222       | 27.34%  |
| 251-500        | 191       | 23.52%  |
| 501-1000       | 124       | 15.27%  |
| 1001-2000      | 83        | 10.22%  |
| Unknown        | 45        | 5.54%   |
| More than 3000 | 44        | 5.42%   |
| 51-100         | 44        | 5.42%   |
| 1-20           | 34        | 4.19%   |
| 21-50          | 14        | 1.72%   |
| 2001-3000      | 11        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 237       | 28.25%  |
| 21-50          | 171       | 20.38%  |
| 101-250        | 138       | 16.45%  |
| 51-100         | 109       | 12.99%  |
| 251-500        | 63        | 7.51%   |
| 501-1000       | 46        | 5.48%   |
| Unknown        | 45        | 5.36%   |
| More than 3000 | 14        | 1.67%   |
| 1001-2000      | 14        | 1.67%   |
| 2001-3000      | 1         | 0.12%   |
| 0              | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 5.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 6         | 6      | 5.22%   |
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 3.48%   |
| Toshiba MQ01ABF050 500GB                 | 3         | 3      | 2.61%   |
| Seagate ST9320325AS 320GB                | 3         | 3      | 2.61%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.74%   |
| Seagate ST9250315AS 250GB                | 2         | 2      | 1.74%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 1.74%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 2      | 1.74%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 1.74%   |
| Seagate ST1000LM014-1EJ164 1TB           | 2         | 2      | 1.74%   |
| SanDisk SSD PLUS 1000GB                  | 2         | 2      | 1.74%   |
| HGST HTS725050A7E630 500GB               | 2         | 3      | 1.74%   |
| HGST HTS545050A7E680 500GB               | 2         | 2      | 1.74%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.74%   |
| HGST HTS541075A9E680 752GB               | 2         | 2      | 1.74%   |
| HGST HTS541010A9E680 1TB                 | 2         | 3      | 1.74%   |
| WDC WD6400BEVT-60A0RT0 640GB             | 1         | 2      | 0.87%   |
| WDC WD5000L 500GB                        | 1         | 1      | 0.87%   |
| WDC WD5000BPVT-22HXZT1 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000BPKX-22HPJT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD3200BPVT-00JJ5T0 320GB             | 1         | 1      | 0.87%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 0.87%   |
| WDC WD3200BEKT-75PVMT0 320GB             | 1         | 1      | 0.87%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.87%   |
| WDC WD2500BEKT-60PVMT0 250GB             | 1         | 1      | 0.87%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10SPZX-08Z10 1TB                   | 1         | 1      | 0.87%   |
| WDC WD10JPVT-75A1YT0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 0.87%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 1         | 1      | 0.87%   |
| USB3.0 Super Speed 128GB                 | 1         | 2      | 0.87%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.87%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.87%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 2      | 0.87%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.87%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.87%   |
| Toshiba MK5065GSX 500GB                  | 1         | 1      | 0.87%   |
| Toshiba MK5061GSYN 500GB                 | 1         | 1      | 0.87%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 0.87%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 33        | 35     | 28.95%  |
| Toshiba                   | 16        | 17     | 14.04%  |
| WDC                       | 14        | 15     | 12.28%  |
| HGST                      | 11        | 14     | 9.65%   |
| SK hynix                  | 5         | 5      | 4.39%   |
| SanDisk                   | 5         | 5      | 4.39%   |
| Intel                     | 4         | 5      | 3.51%   |
| Hitachi                   | 4         | 4      | 3.51%   |
| Samsung Electronics       | 3         | 3      | 2.63%   |
| Micron Technology         | 3         | 3      | 2.63%   |
| LITEONIT                  | 2         | 2      | 1.75%   |
| Kingston                  | 2         | 2      | 1.75%   |
| Crucial                   | 2         | 2      | 1.75%   |
| USB3.0                    | 1         | 2      | 0.88%   |
| SSSTC                     | 1         | 1      | 0.88%   |
| Plextor                   | 1         | 1      | 0.88%   |
| Mushkin                   | 1         | 1      | 0.88%   |
| Micron/Crucial Technology | 1         | 1      | 0.88%   |
| Lenovo                    | 1         | 1      | 0.88%   |
| LaCie                     | 1         | 1      | 0.88%   |
| Corsair                   | 1         | 1      | 0.88%   |
| Apple                     | 1         | 1      | 0.88%   |
| A-DATA Technology         | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 33        | 35     | 42.31%  |
| Toshiba | 14        | 15     | 17.95%  |
| WDC     | 13        | 14     | 16.67%  |
| HGST    | 11        | 14     | 14.1%   |
| Hitachi | 4         | 4      | 5.13%   |
| USB3.0  | 1         | 2      | 1.28%   |
| LaCie   | 1         | 1      | 1.28%   |
| Apple   | 1         | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 78        | 86     | 69.03%  |
| SSD  | 29        | 31     | 25.66%  |
| NVMe | 6         | 6      | 5.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB   | 1         | 1      | 25%     |
| Seagate ST9320325AS 320GB  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB   | 1         | 1      | 25%     |
| HGST HTS545050A7E680 500GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 612       | 905    | 69.86%  |
| Detected | 149       | 205    | 17.01%  |
| Malfunc  | 111       | 123    | 12.67%  |
| Failed   | 4         | 4      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 563       | 57.68%  |
| Samsung Electronics            | 105       | 10.76%  |
| AMD                            | 93        | 9.53%   |
| SanDisk                        | 52        | 5.33%   |
| SK hynix                       | 37        | 3.79%   |
| KIOXIA                         | 19        | 1.95%   |
| Kingston Technology Company    | 18        | 1.84%   |
| Phison Electronics             | 16        | 1.64%   |
| Toshiba America Info Systems   | 15        | 1.54%   |
| Micron Technology              | 14        | 1.43%   |
| Micron/Crucial Technology      | 8         | 0.82%   |
| ADATA Technology               | 7         | 0.72%   |
| Silicon Motion                 | 5         | 0.51%   |
| Nvidia                         | 5         | 0.51%   |
| Union Memory (Shenzhen)        | 3         | 0.31%   |
| Lenovo                         | 3         | 0.31%   |
| Apple                          | 3         | 0.31%   |
| Marvell Technology Group       | 2         | 0.2%    |
| Lite-On Technology             | 2         | 0.2%    |
| Solid State Storage Technology | 1         | 0.1%    |
| Shenzhen Longsys Electronics   | 1         | 0.1%    |
| Realtek Semiconductor          | 1         | 0.1%    |
| Netac Technology               | 1         | 0.1%    |
| INNOGRIT                       | 1         | 0.1%    |
| ASMedia Technology             | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 93        | 9.24%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 92        | 9.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 61        | 6.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 58        | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 50        | 4.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 43        | 4.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 41        | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 31        | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 26        | 2.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 2.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 23        | 2.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 21        | 2.09%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 17        | 1.69%   |
| Samsung NVMe SSD Controller 980                                                  | 17        | 1.69%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 17        | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 1.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 1.39%   |
| Micron Non-Volatile memory controller                                            | 14        | 1.39%   |
| Intel SSD 660P Series                                                            | 14        | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 12        | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                              | 11        | 1.09%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 10        | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 10        | 0.99%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 0.89%   |
| Phison E12 NVMe Controller                                                       | 8         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 0.79%   |
| SanDisk Non-Volatile memory controller                                           | 7         | 0.7%    |
| SK hynix Non-Volatile memory controller                                          | 6         | 0.6%    |
| SK hynix BC511                                                                   | 6         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.6%    |
| Samsung Apple PCIe SSD                                                           | 6         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 5         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 585       | 60.31%  |
| NVMe | 302       | 31.13%  |
| RAID | 67        | 6.91%   |
| IDE  | 16        | 1.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 649       | 82.68%  |
| AMD    | 136       | 17.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 23        | 2.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 21        | 2.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 21        | 2.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 19        | 2.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 19        | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 15        | 1.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 14        | 1.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 13        | 1.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 12        | 1.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 12        | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 10        | 1.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 10        | 1.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 10        | 1.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 10        | 1.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 10        | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 9         | 1.15%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 9         | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 8         | 1.02%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 8         | 1.02%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 8         | 1.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 8         | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 8         | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 7         | 0.89%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 7         | 0.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 6         | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 6         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 6         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 6         | 0.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 6         | 0.76%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 6         | 0.76%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 6         | 0.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 6         | 0.76%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 6         | 0.76%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 6         | 0.76%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 6         | 0.76%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 5         | 0.64%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 5         | 0.64%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 5         | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 0.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 5         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 240       | 30.57%  |
| Intel Core i7           | 239       | 30.45%  |
| Intel Core i3           | 51        | 6.5%    |
| AMD Ryzen 7             | 40        | 5.1%    |
| Other                   | 39        | 4.97%   |
| AMD Ryzen 5             | 38        | 4.84%   |
| Intel Celeron           | 22        | 2.8%    |
| Intel Pentium           | 19        | 2.42%   |
| Intel Core 2 Duo        | 18        | 2.29%   |
| AMD Ryzen 3             | 12        | 1.53%   |
| AMD Ryzen 7 PRO         | 8         | 1.02%   |
| AMD A6                  | 8         | 1.02%   |
| AMD A12                 | 6         | 0.76%   |
| Intel Atom              | 5         | 0.64%   |
| AMD Ryzen 9             | 5         | 0.64%   |
| AMD A10                 | 5         | 0.64%   |
| Intel Pentium Dual-Core | 4         | 0.51%   |
| Intel Xeon              | 3         | 0.38%   |
| Intel Pentium Silver    | 3         | 0.38%   |
| Intel Core m3           | 3         | 0.38%   |
| Intel Core i9           | 3         | 0.38%   |
| AMD A8                  | 3         | 0.38%   |
| AMD A4                  | 3         | 0.38%   |
| Intel Core 2            | 2         | 0.25%   |
| Intel Pentium Dual      | 1         | 0.13%   |
| Intel Core m7           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |
| AMD E2                  | 1         | 0.13%   |
| AMD E1                  | 1         | 0.13%   |
| AMD Athlon II           | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 373       | 47.52%  |
| 4      | 273       | 34.78%  |
| 6      | 73        | 9.3%    |
| 8      | 57        | 7.26%   |
| 14     | 3         | 0.38%   |
| 1      | 3         | 0.38%   |
| 16     | 1         | 0.13%   |
| 12     | 1         | 0.13%   |
| 10     | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 785       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 672       | 85.61%  |
| 1      | 113       | 14.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 784       | 99.87%  |
| Unknown        | 1         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 14.54%  |
| 0x206a7    | 53        | 6.64%   |
| 0x906ea    | 45        | 5.64%   |
| 0x406e3    | 42        | 5.26%   |
| 0x806ea    | 40        | 5.01%   |
| 0x806e9    | 39        | 4.89%   |
| 0x306a9    | 35        | 4.39%   |
| 0x306c3    | 34        | 4.26%   |
| 0x40651    | 28        | 3.51%   |
| 0x306d4    | 24        | 3.01%   |
| 0x906e9    | 23        | 2.88%   |
| 0x806ec    | 23        | 2.88%   |
| 0x20655    | 22        | 2.76%   |
| 0xa0652    | 20        | 2.51%   |
| 0x806c1    | 20        | 2.51%   |
| 0x08600106 | 18        | 2.26%   |
| 0x08108102 | 16        | 2.01%   |
| 0x08108109 | 13        | 1.63%   |
| 0x706e5    | 12        | 1.5%    |
| 0x806eb    | 10        | 1.25%   |
| 0x30678    | 10        | 1.25%   |
| 0x506e3    | 9         | 1.13%   |
| 0x1067a    | 9         | 1.13%   |
| 0x0a50000c | 9         | 1.13%   |
| 0x806d1    | 7         | 0.88%   |
| 0x706a8    | 7         | 0.88%   |
| 0x10676    | 7         | 0.88%   |
| 0x08608103 | 7         | 0.88%   |
| 0x08600104 | 7         | 0.88%   |
| 0x08600103 | 7         | 0.88%   |
| 0x0810100b | 7         | 0.88%   |
| 0x20652    | 6         | 0.75%   |
| 0x106e5    | 6         | 0.75%   |
| 0x06006705 | 6         | 0.75%   |
| 0x0600611a | 5         | 0.63%   |
| 0x406c4    | 4         | 0.5%    |
| 0x40661    | 4         | 0.5%    |
| 0x0a50000b | 4         | 0.5%    |
| 0x06006704 | 4         | 0.5%    |
| 0x906ed    | 3         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 213       | 27.1%   |
| Haswell          | 75        | 9.54%   |
| SandyBridge      | 59        | 7.51%   |
| Skylake          | 58        | 7.38%   |
| IvyBridge        | 47        | 5.98%   |
| Zen 2            | 35        | 4.45%   |
| Westmere         | 34        | 4.33%   |
| Zen+             | 33        | 4.2%    |
| Broadwell        | 28        | 3.56%   |
| Excavator        | 24        | 3.05%   |
| TigerLake        | 22        | 2.8%    |
| CometLake        | 22        | 2.8%    |
| Penryn           | 19        | 2.42%   |
| Silvermont       | 18        | 2.29%   |
| IceLake          | 18        | 2.29%   |
| Zen 3            | 17        | 2.16%   |
| Zen              | 10        | 1.27%   |
| Goldmont plus    | 10        | 1.27%   |
| Unknown          | 10        | 1.27%   |
| Nehalem          | 6         | 0.76%   |
| Core             | 6         | 0.76%   |
| Alderlake Hybrid | 5         | 0.64%   |
| Puma             | 3         | 0.38%   |
| Piledriver       | 3         | 0.38%   |
| Goldmont         | 3         | 0.38%   |
| Bonnell          | 3         | 0.38%   |
| Tremont          | 2         | 0.25%   |
| Jaguar           | 2         | 0.25%   |
| K10              | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 600       | 56.55%  |
| Nvidia | 290       | 27.33%  |
| AMD    | 171       | 16.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 53        | 4.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 51        | 4.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 44        | 4.06%   |
| Intel UHD Graphics 620                                                                   | 43        | 3.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 3.79%   |
| Intel HD Graphics 620                                                                    | 40        | 3.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 33        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 33        | 3.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 2.95%   |
| AMD Renoir                                                                               | 30        | 2.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 2.49%   |
| Intel HD Graphics 630                                                                    | 24        | 2.22%   |
| Intel HD Graphics 5500                                                                   | 24        | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 2.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 1.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 1.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 1.29%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 14        | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.29%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 1.02%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 11        | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.02%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 11        | 1.02%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 9         | 0.83%   |
| Intel HD Graphics 530                                                                    | 9         | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 0.74%   |
| AMD Lucienne                                                                             | 8         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.65%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 7         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 347       | 44.09%  |
| Intel + Nvidia | 216       | 27.45%  |
| 1 x AMD        | 99        | 12.58%  |
| 1 x Nvidia     | 49        | 6.23%   |
| Intel + AMD    | 34        | 4.32%   |
| AMD + Nvidia   | 24        | 3.05%   |
| 2 x AMD        | 14        | 1.78%   |
| 2 x Intel      | 3         | 0.38%   |
| 2 x Nvidia     | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 625       | 79.11%  |
| Proprietary | 156       | 19.75%  |
| Unknown     | 9         | 1.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 547       | 68.63%  |
| 0.01-0.5   | 76        | 9.54%   |
| 1.01-2.0   | 72        | 9.03%   |
| 0.51-1.0   | 43        | 5.4%    |
| 3.01-4.0   | 31        | 3.89%   |
| 5.01-6.0   | 17        | 2.13%   |
| 7.01-8.0   | 6         | 0.75%   |
| 2.01-3.0   | 3         | 0.38%   |
| 8.01-16.0  | 2         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 162       | 17.33%  |
| AU Optronics            | 161       | 17.22%  |
| Chimei Innolux          | 128       | 13.69%  |
| BOE                     | 128       | 13.69%  |
| Samsung Electronics     | 67        | 7.17%   |
| Sharp                   | 32        | 3.42%   |
| Dell                    | 29        | 3.1%    |
| Goldstar                | 26        | 2.78%   |
| Apple                   | 26        | 2.78%   |
| Lenovo                  | 21        | 2.25%   |
| PANDA                   | 16        | 1.71%   |
| Chi Mei Optoelectronics | 13        | 1.39%   |
| Hewlett-Packard         | 12        | 1.28%   |
| BenQ                    | 12        | 1.28%   |
| AOC                     | 9         | 0.96%   |
| Acer                    | 8         | 0.86%   |
| Philips                 | 7         | 0.75%   |
| CSO                     | 7         | 0.75%   |
| Sony                    | 6         | 0.64%   |
| Panasonic               | 6         | 0.64%   |
| InfoVision              | 5         | 0.53%   |
| Ancor Communications    | 4         | 0.43%   |
| ViewSonic               | 3         | 0.32%   |
| Sceptre Tech            | 3         | 0.32%   |
| ASUSTek Computer        | 3         | 0.32%   |
| Medion                  | 2         | 0.21%   |
| LG Philips              | 2         | 0.21%   |
| InnoLux Display         | 2         | 0.21%   |
| Iiyama                  | 2         | 0.21%   |
| HannStar                | 2         | 0.21%   |
| Eizo                    | 2         | 0.21%   |
| CPT                     | 2         | 0.21%   |
| Westinghouse            | 1         | 0.11%   |
| VIE                     | 1         | 0.11%   |
| Toshiba                 | 1         | 0.11%   |
| TMX                     | 1         | 0.11%   |
| SKY                     | 1         | 0.11%   |
| Seiki                   | 1         | 0.11%   |
| RGT                     | 1         | 0.11%   |
| PRO                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 11        | 1.17%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 11        | 1.17%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.85%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 7         | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.64%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.64%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 0.53%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 5         | 0.53%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.53%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.53%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.53%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 5         | 0.53%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 5         | 0.53%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.43%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 4         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.43%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.43%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 4         | 0.43%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch | 3         | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.32%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 3         | 0.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 3         | 0.32%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 3         | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 437       | 50.93%  |
| 1366x768 (WXGA)    | 209       | 24.36%  |
| 1600x900 (HD+)     | 43        | 5.01%   |
| 3840x2160 (4K)     | 31        | 3.61%   |
| 2560x1440 (QHD)    | 23        | 2.68%   |
| 1280x800 (WXGA)    | 22        | 2.56%   |
| 1440x900 (WXGA+)   | 13        | 1.52%   |
| 1920x1200 (WUXGA)  | 11        | 1.28%   |
| 2880x1800          | 10        | 1.17%   |
| 2560x1080          | 8         | 0.93%   |
| 2160x1440          | 8         | 0.93%   |
| 2560x1600          | 7         | 0.82%   |
| 1280x1024 (SXGA)   | 7         | 0.82%   |
| 3200x1800 (QHD+)   | 6         | 0.7%    |
| 3840x2400          | 4         | 0.47%   |
| 1680x1050 (WSXGA+) | 4         | 0.47%   |
| 3440x1440          | 3         | 0.35%   |
| 1360x768           | 3         | 0.35%   |
| 1920x540           | 2         | 0.23%   |
| 1024x600           | 2         | 0.23%   |
| 3840x1600          | 1         | 0.12%   |
| 3200x2000          | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2160x1350          | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 391       | 42%     |
| 14      | 120       | 12.89%  |
| 13      | 116       | 12.46%  |
| 17      | 81        | 8.7%    |
| 24      | 36        | 3.87%   |
| 12      | 32        | 3.44%   |
| 27      | 30        | 3.22%   |
| 23      | 29        | 3.11%   |
| 21      | 22        | 2.36%   |
| 34      | 10        | 1.07%   |
| 11      | 7         | 0.75%   |
| 19      | 6         | 0.64%   |
| 18      | 6         | 0.64%   |
| 16      | 6         | 0.64%   |
| Unknown | 6         | 0.64%   |
| 31      | 4         | 0.43%   |
| 22      | 4         | 0.43%   |
| 84      | 3         | 0.32%   |
| 54      | 3         | 0.32%   |
| 32      | 3         | 0.32%   |
| 10      | 3         | 0.32%   |
| 40      | 2         | 0.21%   |
| 72      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 47      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 35      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 25      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 561       | 60.85%  |
| 201-300     | 105       | 11.39%  |
| 501-600     | 91        | 9.87%   |
| 351-400     | 89        | 9.65%   |
| 401-500     | 36        | 3.9%    |
| 701-800     | 13        | 1.41%   |
| 1001-1500   | 7         | 0.76%   |
| Unknown     | 6         | 0.65%   |
| 801-900     | 5         | 0.54%   |
| 601-700     | 5         | 0.54%   |
| 1501-2000   | 4         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 700       | 86.21%  |
| 16/10   | 74        | 9.11%   |
| 3/2     | 14        | 1.72%   |
| 21/9    | 12        | 1.48%   |
| 5/4     | 4         | 0.49%   |
| 4/3     | 3         | 0.37%   |
| Unknown | 3         | 0.37%   |
| 6/5     | 2         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 387       | 41.61%  |
| 81-90          | 189       | 20.32%  |
| 201-250        | 78        | 8.39%   |
| 121-130        | 75        | 8.06%   |
| 71-80          | 48        | 5.16%   |
| 301-350        | 31        | 3.33%   |
| 61-70          | 28        | 3.01%   |
| 351-500        | 19        | 2.04%   |
| 251-300        | 11        | 1.18%   |
| More than 1000 | 10        | 1.08%   |
| 151-200        | 9         | 0.97%   |
| 141-150        | 9         | 0.97%   |
| 51-60          | 8         | 0.86%   |
| 91-100         | 8         | 0.86%   |
| Unknown        | 6         | 0.65%   |
| 131-140        | 5         | 0.54%   |
| 501-1000       | 4         | 0.43%   |
| 111-120        | 3         | 0.32%   |
| 41-50          | 2         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 437       | 47.6%   |
| 101-120       | 237       | 25.82%  |
| 51-100        | 134       | 14.6%   |
| 161-240       | 68        | 7.41%   |
| More than 240 | 27        | 2.94%   |
| 1-50          | 9         | 0.98%   |
| Unknown       | 6         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 632       | 79%     |
| 2     | 142       | 17.75%  |
| 3     | 15        | 1.88%   |
| 0     | 11        | 1.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 462       | 38.06%  |
| Realtek Semiconductor             | 423       | 34.84%  |
| Qualcomm Atheros                  | 172       | 14.17%  |
| Broadcom                          | 57        | 4.7%    |
| Broadcom Limited                  | 14        | 1.15%   |
| TP-Link                           | 8         | 0.66%   |
| Dell                              | 8         | 0.66%   |
| Sierra Wireless                   | 7         | 0.58%   |
| MediaTek                          | 6         | 0.49%   |
| Marvell Technology Group          | 6         | 0.49%   |
| Ericsson Business Mobile Networks | 5         | 0.41%   |
| ASIX Electronics                  | 5         | 0.41%   |
| Samsung Electronics               | 4         | 0.33%   |
| Ralink                            | 4         | 0.33%   |
| Nvidia                            | 4         | 0.33%   |
| Hewlett-Packard                   | 4         | 0.33%   |
| Ralink Technology                 | 3         | 0.25%   |
| Lenovo                            | 3         | 0.25%   |
| NetGear                           | 2         | 0.16%   |
| JMicron Technology                | 2         | 0.16%   |
| Huawei Technologies               | 2         | 0.16%   |
| Xiaomi                            | 1         | 0.08%   |
| vivo                              | 1         | 0.08%   |
| U-Blox                            | 1         | 0.08%   |
| Qualcomm Atheros Communications   | 1         | 0.08%   |
| Qualcomm                          | 1         | 0.08%   |
| Novatel Wireless                  | 1         | 0.08%   |
| Motorola PCS                      | 1         | 0.08%   |
| Microsoft                         | 1         | 0.08%   |
| Google                            | 1         | 0.08%   |
| Fibocom                           | 1         | 0.08%   |
| DisplayLink                       | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |
| Apple                             | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 303       | 20.24%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 57        | 3.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 3.54%   |
| Intel Wireless 8265 / 8275                                        | 48        | 3.21%   |
| Intel Wi-Fi 6 AX200                                               | 48        | 3.21%   |
| Intel Wireless 7260                                               | 38        | 2.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 36        | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 34        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.87%   |
| Intel Wireless 8260                                               | 27        | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 1.6%    |
| Intel Wireless 7265                                               | 24        | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 22        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 18        | 1.2%    |
| Intel Wireless 3165                                               | 17        | 1.14%   |
| Intel Wi-Fi 6 AX201                                               | 17        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.07%   |
| Intel Centrino Ultimate-N 6300                                    | 15        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 0.8%    |
| Intel Wireless-AC 9260                                            | 12        | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 12        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 0.73%   |
| Intel Centrino Advanced-N 6200                                    | 11        | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 10        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 10        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.67%   |
| Intel Centrino Advanced-N 6235                                    | 10        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 448       | 55.31%  |
| Qualcomm Atheros                  | 147       | 18.15%  |
| Realtek Semiconductor             | 123       | 15.19%  |
| Broadcom                          | 42        | 5.19%   |
| Broadcom Limited                  | 11        | 1.36%   |
| Sierra Wireless                   | 7         | 0.86%   |
| MediaTek                          | 6         | 0.74%   |
| TP-Link                           | 5         | 0.62%   |
| Ralink                            | 4         | 0.49%   |
| Dell                              | 4         | 0.49%   |
| Ralink Technology                 | 3         | 0.37%   |
| NetGear                           | 2         | 0.25%   |
| Hewlett-Packard                   | 2         | 0.25%   |
| Ericsson Business Mobile Networks | 2         | 0.25%   |
| Qualcomm Atheros Communications   | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Fibocom                           | 1         | 0.12%   |
| ASUSTek Computer                  | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 57        | 7.02%   |
| Intel Wireless 8265 / 8275                                     | 48        | 5.91%   |
| Intel Wi-Fi 6 AX200                                            | 48        | 5.91%   |
| Intel Wireless 7260                                            | 38        | 4.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 36        | 4.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 34        | 4.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 3.45%   |
| Intel Wireless 8260                                            | 27        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 2.96%   |
| Intel Wireless 7265                                            | 24        | 2.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 22        | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 2.22%   |
| Intel Wireless 3165                                            | 17        | 2.09%   |
| Intel Wi-Fi 6 AX201                                            | 17        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 1.97%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 1.48%   |
| Intel Wireless-AC 9260                                         | 12        | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.35%   |
| Intel Centrino Advanced-N 6200                                 | 11        | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 10        | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 10        | 1.23%   |
| Intel Centrino Advanced-N 6235                                 | 10        | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 0.99%   |
| Intel Wireless 3160                                            | 7         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 6         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 6         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 387       | 58.55%  |
| Intel                    | 168       | 25.42%  |
| Qualcomm Atheros         | 44        | 6.66%   |
| Broadcom                 | 24        | 3.63%   |
| Marvell Technology Group | 6         | 0.91%   |
| ASIX Electronics         | 5         | 0.76%   |
| Samsung Electronics      | 4         | 0.61%   |
| Nvidia                   | 4         | 0.61%   |
| TP-Link                  | 3         | 0.45%   |
| Lenovo                   | 3         | 0.45%   |
| Broadcom Limited         | 3         | 0.45%   |
| JMicron Technology       | 2         | 0.3%    |
| Xiaomi                   | 1         | 0.15%   |
| Qualcomm                 | 1         | 0.15%   |
| Novatel Wireless         | 1         | 0.15%   |
| Motorola PCS             | 1         | 0.15%   |
| MediaTek                 | 1         | 0.15%   |
| Google                   | 1         | 0.15%   |
| DisplayLink              | 1         | 0.15%   |
| Apple                    | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 303       | 45.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 7.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 2.68%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 2.08%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 1.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 1.04%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 4         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.6%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.45%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 3         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.45%   |
| Intel Ethernet Connection (10) I219-LM                            | 3         | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 779       | 54.25%  |
| Ethernet | 644       | 44.85%  |
| Modem    | 12        | 0.84%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 665       | 80.02%  |
| Ethernet | 166       | 19.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 598       | 76.08%  |
| 1     | 172       | 21.88%  |
| 3     | 11        | 1.4%    |
| 0     | 5         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 625       | 78.42%  |
| Yes  | 172       | 21.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 355       | 52.51%  |
| Realtek Semiconductor           | 77        | 11.39%  |
| Qualcomm Atheros Communications | 64        | 9.47%   |
| IMC Networks                    | 38        | 5.62%   |
| Broadcom                        | 32        | 4.73%   |
| Lite-On Technology              | 31        | 4.59%   |
| Apple                           | 25        | 3.7%    |
| Foxconn / Hon Hai               | 20        | 2.96%   |
| Dell                            | 9         | 1.33%   |
| Cambridge Silicon Radio         | 6         | 0.89%   |
| Toshiba                         | 4         | 0.59%   |
| Realtek                         | 4         | 0.59%   |
| ASUSTek Computer                | 4         | 0.59%   |
| Hewlett-Packard                 | 2         | 0.3%    |
| Ralink Technology               | 1         | 0.15%   |
| Ralink                          | 1         | 0.15%   |
| Opticis                         | 1         | 0.15%   |
| Dynex                           | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 156       | 23.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 58        | 8.58%   |
| Intel Bluetooth Device                                                              | 55        | 8.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 48        | 7.1%    |
| Intel AX200 Bluetooth                                                               | 46        | 6.8%    |
| Realtek Bluetooth Radio                                                             | 39        | 5.77%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 24        | 3.55%   |
| Lite-On Bluetooth Device                                                            | 24        | 3.55%   |
| Apple Bluetooth Host Controller                                                     | 18        | 2.66%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 17        | 2.51%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 2.22%   |
| IMC Networks Bluetooth Device                                                       | 14        | 2.07%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 12        | 1.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.18%   |
| Realtek RTL8821A Bluetooth                                                          | 7         | 1.04%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 6         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.89%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.44%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.44%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 3         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.44%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.44%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.44%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.44%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.44%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.3%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 2         | 0.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.3%    |
| IMC Networks BCM20702A0                                                             | 2         | 0.3%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.3%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.3%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 642       | 63.25%  |
| Nvidia                   | 173       | 17.04%  |
| AMD                      | 146       | 14.38%  |
| Logitech                 | 7         | 0.69%   |
| Realtek Semiconductor    | 5         | 0.49%   |
| C-Media Electronics      | 4         | 0.39%   |
| Lenovo                   | 3         | 0.3%    |
| Kingston Technology      | 3         | 0.3%    |
| GN Netcom                | 3         | 0.3%    |
| BEHRINGER International  | 3         | 0.3%    |
| Samson Technologies      | 2         | 0.2%    |
| Generalplus Technology   | 2         | 0.2%    |
| Focusrite-Novation       | 2         | 0.2%    |
| VIA Technologies         | 1         | 0.1%    |
| Texas Instruments        | 1         | 0.1%    |
| SteelSeries ApS          | 1         | 0.1%    |
| Sony                     | 1         | 0.1%    |
| Samsung Electronics      | 1         | 0.1%    |
| Plantronics              | 1         | 0.1%    |
| Nordic Semiconductor ASA | 1         | 0.1%    |
| No brand                 | 1         | 0.1%    |
| Microchip Technology     | 1         | 0.1%    |
| Mark of the Unicorn      | 1         | 0.1%    |
| LG Electronics           | 1         | 0.1%    |
| JMTek                    | 1         | 0.1%    |
| Jieli Technology         | 1         | 0.1%    |
| GS3                      | 1         | 0.1%    |
| Fujitsu                  | 1         | 0.1%    |
| DSEA A/S                 | 1         | 0.1%    |
| Dell                     | 1         | 0.1%    |
| Corsair                  | 1         | 0.1%    |
| Barco Display Systems    | 1         | 0.1%    |
| Asahi Kasei Microsystems | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 135       | 11.04%  |
| AMD Family 17h/19h HD Audio Controller                                     | 100       | 8.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 4.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 54        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 52        | 4.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 43        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 42        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 40        | 3.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 38        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 32        | 2.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 2.62%   |
| Intel 8 Series HD Audio Controller                                         | 32        | 2.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 28        | 2.29%   |
| Intel Broadwell-U Audio Controller                                         | 28        | 2.29%   |
| Intel CM238 HD Audio Controller                                            | 27        | 2.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 25        | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 24        | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 22        | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 1.8%    |
| Intel Comet Lake PCH cAVS                                                  | 22        | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 1.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 20        | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 16        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 1.14%   |
| AMD High Definition Audio Controller                                       | 13        | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 10        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10        | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 0.82%   |
| AMD FCH Azalia Controller                                                  | 8         | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                         | 6         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 269       | 31.72%  |
| SK hynix            | 204       | 24.06%  |
| Micron Technology   | 106       | 12.5%   |
| Kingston            | 71        | 8.37%   |
| Crucial             | 41        | 4.83%   |
| Unknown             | 37        | 4.36%   |
| Ramaxel Technology  | 16        | 1.89%   |
| Elpida              | 13        | 1.53%   |
| Nanya Technology    | 12        | 1.42%   |
| A-DATA Technology   | 12        | 1.42%   |
| Corsair             | 8         | 0.94%   |
| Unknown (ABCD)      | 5         | 0.59%   |
| Patriot             | 5         | 0.59%   |
| Apacer              | 5         | 0.59%   |
| Team                | 4         | 0.47%   |
| GOODRAM             | 4         | 0.47%   |
| Transcend           | 3         | 0.35%   |
| Goldkey             | 3         | 0.35%   |
| Avant               | 3         | 0.35%   |
| ASint Technology    | 3         | 0.35%   |
| Unknown             | 3         | 0.35%   |
| Silicon Power       | 2         | 0.24%   |
| Neo Forza           | 2         | 0.24%   |
| G.Skill             | 2         | 0.24%   |
| CSX                 | 2         | 0.24%   |
| AMD                 | 2         | 0.24%   |
| Unknown (898F)      | 1         | 0.12%   |
| Unknown (0x8634)    | 1         | 0.12%   |
| Unknown (0x8319)    | 1         | 0.12%   |
| Unknown (09D5)      | 1         | 0.12%   |
| Timetec             | 1         | 0.12%   |
| Sesame              | 1         | 0.12%   |
| Saikano             | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| EUDAR               | 1         | 0.12%   |
| DSL                 | 1         | 0.12%   |
| 48spaces            | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 2.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 18        | 1.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 1.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 1.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 1.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 1.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 1.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1%      |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.89%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 7         | 0.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.78%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.78%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 7         | 0.78%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 6         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.66%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.55%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.55%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.55%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 5         | 0.55%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 4         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 0.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 374       | 53.2%   |
| DDR3    | 253       | 35.99%  |
| LPDDR3  | 29        | 4.13%   |
| LPDDR4  | 22        | 3.13%   |
| SDRAM   | 9         | 1.28%   |
| DDR2    | 9         | 1.28%   |
| DDR5    | 4         | 0.57%   |
| Unknown | 2         | 0.28%   |
| LPDDR5  | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 646       | 91.5%   |
| Row Of Chips | 51        | 7.22%   |
| Chip         | 8         | 1.13%   |
| DIMM         | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 325       | 41.88%  |
| 4096  | 270       | 34.79%  |
| 16384 | 95        | 12.24%  |
| 2048  | 60        | 7.73%   |
| 32768 | 18        | 2.32%   |
| 1024  | 7         | 0.9%    |
| 64    | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 199       | 25.51%  |
| 1600    | 191       | 24.49%  |
| 3200    | 116       | 14.87%  |
| 2400    | 75        | 9.62%   |
| 2133    | 46        | 5.9%    |
| 1334    | 33        | 4.23%   |
| 1333    | 24        | 3.08%   |
| 3266    | 17        | 2.18%   |
| 1067    | 15        | 1.92%   |
| 1867    | 12        | 1.54%   |
| Unknown | 10        | 1.28%   |
| 4267    | 8         | 1.03%   |
| 4199    | 6         | 0.77%   |
| 667     | 5         | 0.64%   |
| 8400    | 4         | 0.51%   |
| 4800    | 4         | 0.51%   |
| 975     | 3         | 0.38%   |
| 800     | 3         | 0.38%   |
| 2048    | 2         | 0.26%   |
| 6400    | 1         | 0.13%   |
| 3733    | 1         | 0.13%   |
| 3000    | 1         | 0.13%   |
| 2933    | 1         | 0.13%   |
| 1776    | 1         | 0.13%   |
| 1639    | 1         | 0.13%   |
| 533     | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| MIIIW              | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| MIIIW MW Keyboard Air Mini  | 1         | 33.33%  |
| Canon G2000 series          | 1         | 33.33%  |
| Brother MFC-L3770CDW series | 1         | 33.33%  |

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
| Chicony Electronics                    | 194       | 27.13%  |
| IMC Networks                           | 95        | 13.29%  |
| Acer                                   | 72        | 10.07%  |
| Realtek Semiconductor                  | 68        | 9.51%   |
| Microdia                               | 58        | 8.11%   |
| Sunplus Innovation Technology          | 40        | 5.59%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.06%   |
| Quanta                                 | 27        | 3.78%   |
| Apple                                  | 20        | 2.8%    |
| Lite-On Technology                     | 19        | 2.66%   |
| Syntek                                 | 18        | 2.52%   |
| Suyin                                  | 15        | 2.1%    |
| Logitech                               | 10        | 1.4%    |
| Lenovo                                 | 9         | 1.26%   |
| Silicon Motion                         | 8         | 1.12%   |
| Primax Electronics                     | 5         | 0.7%    |
| Luxvisions Innotech Limited            | 5         | 0.7%    |
| Samsung Electronics                    | 4         | 0.56%   |
| Ricoh                                  | 3         | 0.42%   |
| Importek                               | 3         | 0.42%   |
| Alcor Micro                            | 3         | 0.42%   |
| Sunplus Technology                     | 2         | 0.28%   |
| Generalplus Technology                 | 2         | 0.28%   |
| WaveRider Communications               | 1         | 0.14%   |
| Sonix Technology                       | 1         | 0.14%   |
| Microsoft                              | 1         | 0.14%   |
| icSpring                               | 1         | 0.14%   |
| Creative Technology                    | 1         | 0.14%   |
| ARC International                      | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 51        | 7.09%   |
| Realtek Integrated_Webcam_HD                                   | 28        | 3.89%   |
| Microdia Integrated_Webcam_HD                                  | 27        | 3.76%   |
| IMC Networks Integrated Camera                                 | 24        | 3.34%   |
| Chicony HD WebCam                                              | 24        | 3.34%   |
| Acer Integrated Camera                                         | 22        | 3.06%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 21        | 2.92%   |
| Lite-On Integrated Camera                                      | 14        | 1.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 14        | 1.95%   |
| Sunplus Integrated_Webcam_HD                                   | 13        | 1.81%   |
| Syntek Integrated Camera                                       | 11        | 1.53%   |
| Chicony USB2.0 Camera                                          | 11        | 1.53%   |
| Acer EasyCamera                                                | 10        | 1.39%   |
| Chicony HP TrueVision HD                                       | 9         | 1.25%   |
| Microdia Integrated Webcam                                     | 8         | 1.11%   |
| Acer BisonCam,NB Pro                                           | 8         | 1.11%   |
| Quanta HD Webcam                                               | 7         | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 7         | 0.97%   |
| Apple Built-in iSight                                          | 7         | 0.97%   |
| Lenovo Integrated Webcam [R5U877]                              | 6         | 0.83%   |
| IMC Networks Lenovo EasyCamera                                 | 6         | 0.83%   |
| Chicony HP TrueVision HD Camera                                | 6         | 0.83%   |
| Chicony HP HD Webcam                                           | 6         | 0.83%   |
| Apple FaceTime HD Camera                                       | 6         | 0.83%   |
| Acer HD Webcam                                                 | 6         | 0.83%   |
| Realtek Integrated Webcam HD                                   | 5         | 0.7%    |
| Quanta HD User Facing                                          | 5         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 5         | 0.7%    |
| IMC Networks VGA UVC WebCam                                    | 5         | 0.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 5         | 0.7%    |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 0.7%    |
| Chicony HP Wide Vision HD Camera                               | 5         | 0.7%    |
| Chicony HP HD Camera                                           | 5         | 0.7%    |
| Chicony FJ Camera                                              | 5         | 0.7%    |
| Chicony EasyCamera                                             | 5         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 5         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 5         | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE                                      | 5         | 0.7%    |
| Acer SunplusIT Integrated Camera                               | 5         | 0.7%    |
| Acer Lenovo EasyCamera                                         | 5         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 62        | 44.6%   |
| Synaptics                  | 24        | 17.27%  |
| Shenzhen Goodix Technology | 20        | 14.39%  |
| Upek                       | 11        | 7.91%   |
| Elan Microelectronics      | 9         | 6.47%   |
| LighTuning Technology      | 6         | 4.32%   |
| AuthenTec                  | 6         | 4.32%   |
| STMicroelectronics         | 1         | 0.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 12.23%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 7.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 7.91%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 7.91%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 7.19%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 5.04%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 5.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 4.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 4.32%   |
| Elan ELAN:Fingerprint                                                      | 6         | 4.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.6%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.16%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.44%   |
| Synaptics WBDI Device                                                      | 2         | 1.44%   |
| Synaptics  WBDI                                                            | 2         | 1.44%   |
| AuthenTec AES1600                                                          | 2         | 1.44%   |
| Unknown                                                                    | 2         | 1.44%   |
| Validity Sensors VFS491                                                    | 1         | 0.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.72%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.72%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.72%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.72%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.72%   |
| AuthenTec AES2810                                                          | 1         | 0.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.72%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 29        | 46.03%  |
| Alcor Micro | 23        | 36.51%  |
| O2 Micro    | 5         | 7.94%   |
| Lenovo      | 4         | 6.35%   |
| Upek        | 2         | 3.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 36.51%  |
| Broadcom 5880                                                                | 8         | 12.7%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 11.11%  |
| Broadcom 58200                                                               | 7         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 9.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 6.35%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.35%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 503       | 62.88%  |
| 1     | 232       | 29%     |
| 2     | 61        | 7.63%   |
| 3     | 3         | 0.38%   |
| 4     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 138       | 38.55%  |
| Graphics card         | 83        | 23.18%  |
| Chipcard              | 63        | 17.6%   |
| Net/wireless          | 26        | 7.26%   |
| Multimedia controller | 18        | 5.03%   |
| Camera                | 18        | 5.03%   |
| Network               | 2         | 0.56%   |
| Net/ethernet          | 2         | 0.56%   |
| Card reader           | 2         | 0.56%   |
| Bluetooth             | 2         | 0.56%   |
| Wireless              | 1         | 0.28%   |
| Storage/nvme          | 1         | 0.28%   |
| Storage               | 1         | 0.28%   |
| Dvb card              | 1         | 0.28%   |


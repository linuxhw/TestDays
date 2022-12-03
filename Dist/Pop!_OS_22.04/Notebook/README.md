Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 1243

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Google        | Cyan                        | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| Dell          | Latitude E7240              | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Alienware     | 17                          | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Precision 7670              | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Dell          | G15 5515                    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Lemur Pro                   | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| MSI           | MS-1688                     | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Dell          | Latitude E7240              | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [0622b6fa8f](https://linux-hardware.org/?probe=0622b6fa8f) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [bec7082d7a](https://linux-hardware.org/?probe=bec7082d7a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [fa19e49b0a](https://linux-hardware.org/?probe=fa19e49b0a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [d63435720c](https://linux-hardware.org/?probe=d63435720c) | Nov 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| Dell          | XPS 13 9310                 | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Apple         | MacBookPro3,1               | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| MSI           | Prestige 15 A12UC           | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| HP            | ZBook 15                    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Dell          | G15 5511                    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Dell          | Latitude E7240              | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Dell          | XPS 15 9570                 | [d76c41ef1b](https://linux-hardware.org/?probe=d76c41ef1b) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| Apple         | MacBookAir6,2               | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| System76      | Gazelle                     | [77686d0854](https://linux-hardware.org/?probe=77686d0854) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [c70d6b90b6](https://linux-hardware.org/?probe=c70d6b90b6) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| System76      | Oryx Pro                    | [7de5d55c99](https://linux-hardware.org/?probe=7de5d55c99) | Oct 22, 2022 |
| Intel         | Montevina CRB               | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [504036a2f6](https://linux-hardware.org/?probe=504036a2f6) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| System76      | Lemur Pro                   | [df61411c9d](https://linux-hardware.org/?probe=df61411c9d) | Oct 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [ed64a103f1](https://linux-hardware.org/?probe=ed64a103f1) | Oct 18, 2022 |
| HP            | Laptop 15-dy0xxx            | [2d1482e433](https://linux-hardware.org/?probe=2d1482e433) | Oct 18, 2022 |
| System76      | Lemur Pro                   | [53226822f5](https://linux-hardware.org/?probe=53226822f5) | Oct 18, 2022 |
| MSI           | GF63 Thin 11UD              | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| Lenovo        | Legion Y740-17IRH 81UG      | [67aec6ad33](https://linux-hardware.org/?probe=67aec6ad33) | Oct 17, 2022 |
| MSI           | GP72VR 7RF                  | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| HP            | G62                         | [839b09744e](https://linux-hardware.org/?probe=839b09744e) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [502f19e8b3](https://linux-hardware.org/?probe=502f19e8b3) | Oct 16, 2022 |
| HP            | Pavilion g6                 | [2729d4b101](https://linux-hardware.org/?probe=2729d4b101) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Google        | Kefka                       | [4775b995dd](https://linux-hardware.org/?probe=4775b995dd) | Oct 13, 2022 |
| System76      | Lemur Pro                   | [ec569ddc8f](https://linux-hardware.org/?probe=ec569ddc8f) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [3c11d61a58](https://linux-hardware.org/?probe=3c11d61a58) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [236e24530f](https://linux-hardware.org/?probe=236e24530f) | Oct 12, 2022 |
| Dell          | Precision M6700             | [4c867e9075](https://linux-hardware.org/?probe=4c867e9075) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| Razer         | Blade                       | [c7386df23f](https://linux-hardware.org/?probe=c7386df23f) | Oct 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| HP            | Pavilion 15                 | [8b93ec27f4](https://linux-hardware.org/?probe=8b93ec27f4) | Oct 12, 2022 |
| GPU Compan... | GWTN141-10                  | [1feb5d7501](https://linux-hardware.org/?probe=1feb5d7501) | Oct 12, 2022 |
| Alienware     | 15 R3                       | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [f4a46537c2](https://linux-hardware.org/?probe=f4a46537c2) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| HP            | Laptop 15-bw0xx             | [7231761ea1](https://linux-hardware.org/?probe=7231761ea1) | Oct 09, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Sony          | VPCEH3LFX                   | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| Alienware     | 17 R4                       | [cac06d6050](https://linux-hardware.org/?probe=cac06d6050) | Oct 07, 2022 |
| Positivo      | Mobile                      | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| MSI           | GP66 Leopard 10UG           | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Acer          | Aspire 5520                 | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Lenovo        | IdeaPad Y560                | [15e2c8994f](https://linux-hardware.org/?probe=15e2c8994f) | Oct 06, 2022 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [fa7e7d106e](https://linux-hardware.org/?probe=fa7e7d106e) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Valve         | Jupiter                     | [2fda8270f0](https://linux-hardware.org/?probe=2fda8270f0) | Oct 05, 2022 |
| Acer          | Aspire A315-21              | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Lenovo        | Z51-70 80K6                 | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| System76      | Lemur Pro                   | [8842585a92](https://linux-hardware.org/?probe=8842585a92) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Dell          | Latitude E6420              | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| Google        | Banon                       | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [2637a452d0](https://linux-hardware.org/?probe=2637a452d0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Dell          | XPS L421X                   | [aedcc42b0a](https://linux-hardware.org/?probe=aedcc42b0a) | Oct 02, 2022 |
| Apple         | MacBookPro5,2               | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| Alienware     | 15 R3                       | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| ASUSTek       | GL502VM                     | [1d1616405d](https://linux-hardware.org/?probe=1d1616405d) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| Apple         | MacBook7,1                  | [49595ef8f4](https://linux-hardware.org/?probe=49595ef8f4) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Micro Elec... | Element                     | [9cee0f76c1](https://linux-hardware.org/?probe=9cee0f76c1) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| System76      | Darter Pro                  | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [bde2b36c88](https://linux-hardware.org/?probe=bde2b36c88) | Oct 01, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Dell          | Latitude 5400               | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [81653ba834](https://linux-hardware.org/?probe=81653ba834) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [d31b97630d](https://linux-hardware.org/?probe=d31b97630d) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | [5ce350f38b](https://linux-hardware.org/?probe=5ce350f38b) | Sep 28, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a3c4032d28](https://linux-hardware.org/?probe=a3c4032d28) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [99b6a53bd2](https://linux-hardware.org/?probe=99b6a53bd2) | Sep 27, 2022 |
| ASUSTek       | GL702VSK                    | [3b69ddb263](https://linux-hardware.org/?probe=3b69ddb263) | Sep 27, 2022 |
| Acer          | Nitro AN515-45              | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| ASUSTek       | GL702VSK                    | [e91056ceab](https://linux-hardware.org/?probe=e91056ceab) | Sep 26, 2022 |
| Dell          | Inspiron N5110              | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| ASUSTek       | K52N                        | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [e9de38d8eb](https://linux-hardware.org/?probe=e9de38d8eb) | Sep 25, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| HP            | Laptop 15s-eq1xxx           | [2bc6e102ef](https://linux-hardware.org/?probe=2bc6e102ef) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| Apple         | MacBookPro9,2               | [86b6d46191](https://linux-hardware.org/?probe=86b6d46191) | Sep 24, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| System76      | Darter Pro                  | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| System76      | Darter Pro                  | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Dell          | Inspiron 5520               | [032bbec1e3](https://linux-hardware.org/?probe=032bbec1e3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Dell          | Latitude 3490               | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Dell          | Latitude 7490               | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Dell          | Vostro 3500                 | [7fa417e9a6](https://linux-hardware.org/?probe=7fa417e9a6) | Sep 21, 2022 |
| Apple         | MacBookAir6,2               | [7fc6799a48](https://linux-hardware.org/?probe=7fc6799a48) | Sep 21, 2022 |
| Dell          | Inspiron 5577               | [c6f4124e49](https://linux-hardware.org/?probe=c6f4124e49) | Sep 21, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| Itronix       | GD8200                      | [d9f515b935](https://linux-hardware.org/?probe=d9f515b935) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| GPU Compan... | GWTN141-10                  | [6d43012457](https://linux-hardware.org/?probe=6d43012457) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [47b0aed151](https://linux-hardware.org/?probe=47b0aed151) | Sep 19, 2022 |
| Framework     | Laptop                      | [8dbbe54af9](https://linux-hardware.org/?probe=8dbbe54af9) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [37b4da9922](https://linux-hardware.org/?probe=37b4da9922) | Sep 18, 2022 |
| Gateway       | NV55C                       | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Latitude E7470              | [ceed7544ab](https://linux-hardware.org/?probe=ceed7544ab) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| MSI           | Sword 15 A11UD              | [e749154c3d](https://linux-hardware.org/?probe=e749154c3d) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [5a1085f939](https://linux-hardware.org/?probe=5a1085f939) | Sep 18, 2022 |
| ASUSTek       | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| MSI           | Prestige 15 A12UC           | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| OriginPC      | NT17-PRO                    | [962138caa9](https://linux-hardware.org/?probe=962138caa9) | Sep 17, 2022 |
| System76      | Darter Pro                  | [5d1e0ddc1a](https://linux-hardware.org/?probe=5d1e0ddc1a) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude 3420               | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| Dell          | XPS 13 9360                 | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| ASUSTek       | X555LN                      | [64b85307ec](https://linux-hardware.org/?probe=64b85307ec) | Sep 14, 2022 |
| ASUSTek       | X405UA                      | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [81b9b18da4](https://linux-hardware.org/?probe=81b9b18da4) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Dell          | Studio 1555                 | [0d0f3de3b4](https://linux-hardware.org/?probe=0d0f3de3b4) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [1889334e1f](https://linux-hardware.org/?probe=1889334e1f) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [f9add8f93d](https://linux-hardware.org/?probe=f9add8f93d) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | Dev One Notebook PC         | [bb72f0c2f4](https://linux-hardware.org/?probe=bb72f0c2f4) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5811e17863](https://linux-hardware.org/?probe=5811e17863) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4d3543d03f](https://linux-hardware.org/?probe=4d3543d03f) | Sep 09, 2022 |
| System76      | Galago Pro                  | [8d52d900f2](https://linux-hardware.org/?probe=8d52d900f2) | Sep 09, 2022 |
| Dell          | Inspiron 5457               | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| AZW           | SEi                         | [d3531738fa](https://linux-hardware.org/?probe=d3531738fa) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [6108c677a2](https://linux-hardware.org/?probe=6108c677a2) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [0f8da1f0c8](https://linux-hardware.org/?probe=0f8da1f0c8) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| HP            | 245 G6                      | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| Acer          | Aspire S3                   | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [cb787086fa](https://linux-hardware.org/?probe=cb787086fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Dell          | XPS 15 9500                 | [ea5f9662d7](https://linux-hardware.org/?probe=ea5f9662d7) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| Apple         | MacBookPro11,3              | [c40b757ca3](https://linux-hardware.org/?probe=c40b757ca3) | Sep 04, 2022 |
| MSI           | GP72 7RDX                   | [5d4efc6589](https://linux-hardware.org/?probe=5d4efc6589) | Sep 04, 2022 |
| Apple         | MacBookPro5,5               | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | [b75636bf8b](https://linux-hardware.org/?probe=b75636bf8b) | Sep 03, 2022 |
| Dell          | Inspiron 13-7378            | [0ab8b4e169](https://linux-hardware.org/?probe=0ab8b4e169) | Sep 03, 2022 |
| Dell          | XPS 15 9520                 | [39e1d43301](https://linux-hardware.org/?probe=39e1d43301) | Sep 03, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | [cfb4e75518](https://linux-hardware.org/?probe=cfb4e75518) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| ASUSTek       | X550CL                      | [6e45ea1408](https://linux-hardware.org/?probe=6e45ea1408) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Dell          | Latitude E5570              | [20350411cf](https://linux-hardware.org/?probe=20350411cf) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | [2e3f16bc80](https://linux-hardware.org/?probe=2e3f16bc80) | Sep 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [9b42566191](https://linux-hardware.org/?probe=9b42566191) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| Dell          | Precision 5530              | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Dell          | G3 3590                     | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| Apple         | MacBookAir9,1               | [51c4002c97](https://linux-hardware.org/?probe=51c4002c97) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d96b24b7f3](https://linux-hardware.org/?probe=d96b24b7f3) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Dell          | Inspiron 13-7378            | [42666a5460](https://linux-hardware.org/?probe=42666a5460) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6d04d534fa](https://linux-hardware.org/?probe=6d04d534fa) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Dell          | Inspiron 3493               | [dc23941a16](https://linux-hardware.org/?probe=dc23941a16) | Aug 31, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| HP            | EliteBook 8570w             | [907d5f36e6](https://linux-hardware.org/?probe=907d5f36e6) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [065da8ca1e](https://linux-hardware.org/?probe=065da8ca1e) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [c4be3fe1b6](https://linux-hardware.org/?probe=c4be3fe1b6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [568802fb43](https://linux-hardware.org/?probe=568802fb43) | Aug 28, 2022 |
| HP            | ENVY dv7                    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2e085a419b](https://linux-hardware.org/?probe=2e085a419b) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c47cd7c7ed](https://linux-hardware.org/?probe=c47cd7c7ed) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| Dell          | XPS 9315                    | [6ab1d7417d](https://linux-hardware.org/?probe=6ab1d7417d) | Aug 27, 2022 |
| Apple         | MacBook4,1                  | [fdb7c715b3](https://linux-hardware.org/?probe=fdb7c715b3) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [a45848f10f](https://linux-hardware.org/?probe=a45848f10f) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | [88467a99ae](https://linux-hardware.org/?probe=88467a99ae) | Aug 26, 2022 |
| Dell          | Precision M4600             | [de9a03d9be](https://linux-hardware.org/?probe=de9a03d9be) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [0ec106ca31](https://linux-hardware.org/?probe=0ec106ca31) | Aug 26, 2022 |
| Dell          | Precision M4600             | [83c727c6db](https://linux-hardware.org/?probe=83c727c6db) | Aug 26, 2022 |
| ASUSTek       | X540LJ                      | [edac754e93](https://linux-hardware.org/?probe=edac754e93) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HONOR         | NBR-WAX9                    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| HUAWEI        | KPL-W0X                     | [b502ab922f](https://linux-hardware.org/?probe=b502ab922f) | Aug 25, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [b008775e13](https://linux-hardware.org/?probe=b008775e13) | Aug 24, 2022 |
| HP            | Dev One Notebook PC         | [4263165650](https://linux-hardware.org/?probe=4263165650) | Aug 24, 2022 |
| MSI           | Prestige 15 A10SC           | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [6cb194ca87](https://linux-hardware.org/?probe=6cb194ca87) | Aug 23, 2022 |
| Acer          | Aspire V3-772G              | [92b070c9be](https://linux-hardware.org/?probe=92b070c9be) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| MSI           | PS63 Modern 8RC             | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Acer          | Swift SFX14-41G             | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| System76      | Oryx Pro                    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [314250b1d7](https://linux-hardware.org/?probe=314250b1d7) | Aug 21, 2022 |
| MSI           | Katana GF76 11UD            | [256a057752](https://linux-hardware.org/?probe=256a057752) | Aug 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Vostro 15 3515              | [3f12b83029](https://linux-hardware.org/?probe=3f12b83029) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | GL703VD                     | [54f9d46a7d](https://linux-hardware.org/?probe=54f9d46a7d) | Aug 19, 2022 |
| Gateway       | NV55C                       | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| System76      | Oryx Pro                    | [1583fbab76](https://linux-hardware.org/?probe=1583fbab76) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| Acer          | Aspire A515-43              | [bec0e1fbd6](https://linux-hardware.org/?probe=bec0e1fbd6) | Aug 16, 2022 |
| Apple         | MacBookPro13,3              | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | UX310UQ                     | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [332459de48](https://linux-hardware.org/?probe=332459de48) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [b2c1b403b8](https://linux-hardware.org/?probe=b2c1b403b8) | Aug 14, 2022 |
| Acer          | Aspire 4752                 | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| MSI           | GF63 Thin 11UD              | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Dell          | Latitude E7470              | [1c49732e63](https://linux-hardware.org/?probe=1c49732e63) | Aug 14, 2022 |
| Apple         | MacBookAir3,2               | [0756ed833b](https://linux-hardware.org/?probe=0756ed833b) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| ASUSTek       | G74Sx                       | [309312e25d](https://linux-hardware.org/?probe=309312e25d) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [da7cc3fcb6](https://linux-hardware.org/?probe=da7cc3fcb6) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| Dell          | Inspiron N5110              | [74624820da](https://linux-hardware.org/?probe=74624820da) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Dell          | Inspiron 13-7378            | [097cd944e0](https://linux-hardware.org/?probe=097cd944e0) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| ASUSTek       | X455LJ                      | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1RT0... | [b2f479d0b0](https://linux-hardware.org/?probe=b2f479d0b0) | Aug 11, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [1f0a966a58](https://linux-hardware.org/?probe=1f0a966a58) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| Dell          | Inspiron 13-7378            | [637b0f0905](https://linux-hardware.org/?probe=637b0f0905) | Aug 11, 2022 |
| System76      | Galago UltraPro             | [8c38c1dac4](https://linux-hardware.org/?probe=8c38c1dac4) | Aug 11, 2022 |
| Dell          | Latitude 3330               | [e1f58ad934](https://linux-hardware.org/?probe=e1f58ad934) | Aug 10, 2022 |
| Dell          | Latitude 3330               | [24c9c3fe68](https://linux-hardware.org/?probe=24c9c3fe68) | Aug 10, 2022 |
| Dell          | Inspiron 13-7378            | [4093a81a8d](https://linux-hardware.org/?probe=4093a81a8d) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| ASUSTek       | K55A                        | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [cbcfa4fc6e](https://linux-hardware.org/?probe=cbcfa4fc6e) | Aug 10, 2022 |
| Apple         | MacBookPro15,4              | [494f3495c8](https://linux-hardware.org/?probe=494f3495c8) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | [c0813b6c4e](https://linux-hardware.org/?probe=c0813b6c4e) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | [d93b98ed98](https://linux-hardware.org/?probe=d93b98ed98) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [fa15ec0e79](https://linux-hardware.org/?probe=fa15ec0e79) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| HUAWEI        | NBD-WXX9                    | [6f0c6f7474](https://linux-hardware.org/?probe=6f0c6f7474) | Aug 09, 2022 |
| System76      | Gazelle                     | [a251ef0ac1](https://linux-hardware.org/?probe=a251ef0ac1) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| HP            | Laptop 14s-dk0xxx           | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Dell          | XPS 13 7390                 | [15c1c667af](https://linux-hardware.org/?probe=15c1c667af) | Aug 08, 2022 |
| HP            | Laptop 15-db1xxx            | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| Avell High... | B.ON                        | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| HP            | Pavilion g7                 | [ecd57742f3](https://linux-hardware.org/?probe=ecd57742f3) | Aug 07, 2022 |
| Apple         | MacBookPro11,5              | [221e16bfb1](https://linux-hardware.org/?probe=221e16bfb1) | Aug 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [80794c55e8](https://linux-hardware.org/?probe=80794c55e8) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Dell          | Inspiron 3480               | [637d2f9f41](https://linux-hardware.org/?probe=637d2f9f41) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [e4d16e5adf](https://linux-hardware.org/?probe=e4d16e5adf) | Aug 05, 2022 |
| Dell          | Inspiron 3583               | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Lenovo        | IdeaPad U410                | [048c78d129](https://linux-hardware.org/?probe=048c78d129) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| Lenovo        | ThinkPad L590 20Q7001HGE    | [3549ef85b6](https://linux-hardware.org/?probe=3549ef85b6) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [85f64b5fa5](https://linux-hardware.org/?probe=85f64b5fa5) | Aug 03, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
| Acer          | Aspire A115-32              | [d7eb24100d](https://linux-hardware.org/?probe=d7eb24100d) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| GPU Compan... | GWTN141-10                  | [d73365fe3e](https://linux-hardware.org/?probe=d73365fe3e) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| HP            | Pavilion 17                 | [b2c0846cf5](https://linux-hardware.org/?probe=b2c0846cf5) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| HP            | Pavilion dv6                | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [04ae47501b](https://linux-hardware.org/?probe=04ae47501b) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| Acer          | Ferrari One 200             | [023ff9a691](https://linux-hardware.org/?probe=023ff9a691) | Jul 25, 2022 |
| Acer          | Ferrari One 200             | [447f8a06ea](https://linux-hardware.org/?probe=447f8a06ea) | Jul 25, 2022 |
| System76      | Lemur Pro                   | [c6269208fe](https://linux-hardware.org/?probe=c6269208fe) | Jul 25, 2022 |
| Acer          | Nitro AN515-42              | [8c5e11fe0e](https://linux-hardware.org/?probe=8c5e11fe0e) | Jul 25, 2022 |
| Dynabook      | Satellite Pro C50D-B        | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| GPU Compan... | GWTC116-2                   | [ac0f2b51c0](https://linux-hardware.org/?probe=ac0f2b51c0) | Jul 25, 2022 |
| Lenovo        | E41-25 81FS                 | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Acer          | Aspire V3-551G              | [970f226406](https://linux-hardware.org/?probe=970f226406) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [147556bf0a](https://linux-hardware.org/?probe=147556bf0a) | Jul 23, 2022 |
| Apple         | MacBookPro12,1              | [752155f862](https://linux-hardware.org/?probe=752155f862) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| ASUSTek       | K93SM                       | [add292129b](https://linux-hardware.org/?probe=add292129b) | Jul 22, 2022 |
| Samsung       | 760XDA                      | [c3e04193b8](https://linux-hardware.org/?probe=c3e04193b8) | Jul 22, 2022 |
| GPU Compan... | GWTC116-2                   | [4763ba77ba](https://linux-hardware.org/?probe=4763ba77ba) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [da25f9d9b4](https://linux-hardware.org/?probe=da25f9d9b4) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [ed3f7b7f50](https://linux-hardware.org/?probe=ed3f7b7f50) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Acer          | Aspire V3-551G              | [f5675c45dc](https://linux-hardware.org/?probe=f5675c45dc) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| Dell          | Latitude D430               | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| HP            | Laptop 14-bw0xx             | [df814add04](https://linux-hardware.org/?probe=df814add04) | Jul 18, 2022 |
| Acer          | Aspire V3-551G              | [2baa51bbc9](https://linux-hardware.org/?probe=2baa51bbc9) | Jul 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b903541b55](https://linux-hardware.org/?probe=b903541b55) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| Acer          | Aspire 5520                 | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| ASUSTek       | K53SJ                       | [515f269efc](https://linux-hardware.org/?probe=515f269efc) | Jul 17, 2022 |
| Gigabyte      | Blade Pro                   | [3c2576e897](https://linux-hardware.org/?probe=3c2576e897) | Jul 16, 2022 |
| MSI           | GS75 Stealth 9SG            | [8707f3e800](https://linux-hardware.org/?probe=8707f3e800) | Jul 16, 2022 |
| Alienware     | 15 R2                       | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| MSI           | Katana GF76 11UD            | [61b03607fa](https://linux-hardware.org/?probe=61b03607fa) | Jul 15, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| HUAWEI        | MACH-WX9                    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| HP            | Laptop 17z-ca200            | [1159e9b888](https://linux-hardware.org/?probe=1159e9b888) | Jul 15, 2022 |
| System76      | Pangolin                    | [690b7b5984](https://linux-hardware.org/?probe=690b7b5984) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| ASUSTek       | X555LAB                     | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Dell          | XPS 15 9520                 | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| Lenovo        | ThinkPad X230 2325YHU       | [4720a42a7f](https://linux-hardware.org/?probe=4720a42a7f) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [285e41f0aa](https://linux-hardware.org/?probe=285e41f0aa) | Jul 14, 2022 |
| Samsung       | 950XED                      | [b7f59889a0](https://linux-hardware.org/?probe=b7f59889a0) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | [b70dfefc75](https://linux-hardware.org/?probe=b70dfefc75) | Jul 13, 2022 |
| Dell          | Latitude 3500               | [f42f32c17f](https://linux-hardware.org/?probe=f42f32c17f) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| GPU Compan... | GWTN141-10                  | [0ce04e7b03](https://linux-hardware.org/?probe=0ce04e7b03) | Jul 12, 2022 |
| Apple         | MacBookPro7,1               | [821459e114](https://linux-hardware.org/?probe=821459e114) | Jul 12, 2022 |
| Dell          | Vostro 5470                 | [aedb7a18da](https://linux-hardware.org/?probe=aedb7a18da) | Jul 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | K53SJ                       | [1a9d6df3b5](https://linux-hardware.org/?probe=1a9d6df3b5) | Jul 11, 2022 |
| Dell          | Latitude E5440              | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| Dell          | Inspiron 1750               | [c39e03e656](https://linux-hardware.org/?probe=c39e03e656) | Jul 10, 2022 |
| MSI           | Katana GF76 11UG            | [8f152d3669](https://linux-hardware.org/?probe=8f152d3669) | Jul 10, 2022 |
| Dell          | Inspiron 1750               | [a885fd8b41](https://linux-hardware.org/?probe=a885fd8b41) | Jul 10, 2022 |
| Medion        | Erazer P6661 MD60303        | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| Apple         | MacBookPro11,3              | [9b65b57a57](https://linux-hardware.org/?probe=9b65b57a57) | Jul 10, 2022 |
| Acer          | Aspire A515-52              | [9dc5c32b9f](https://linux-hardware.org/?probe=9dc5c32b9f) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Dell          | Latitude E7450              | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| MSI           | MS-16G4                     | [53f40f3420](https://linux-hardware.org/?probe=53f40f3420) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [38e90a5b4d](https://linux-hardware.org/?probe=38e90a5b4d) | Jul 08, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | G751JT                      | [92eb60a700](https://linux-hardware.org/?probe=92eb60a700) | Jul 08, 2022 |
| Panasonic     | CF-C2AQAZXLM                | [be9cf3127a](https://linux-hardware.org/?probe=be9cf3127a) | Jul 08, 2022 |
| ASUSTek       | K53SJ                       | [f9d5ea94ec](https://linux-hardware.org/?probe=f9d5ea94ec) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| ASUSTek       | X55CR                       | [9e40e3f8ad](https://linux-hardware.org/?probe=9e40e3f8ad) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Vostro 5625                 | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| System76      | Lemur Pro                   | [bdc2ddb608](https://linux-hardware.org/?probe=bdc2ddb608) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [861d7b3714](https://linux-hardware.org/?probe=861d7b3714) | Jul 07, 2022 |
| Acer          | Nitro AN515-53              | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Pegatron      | H36FF                       | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [a194cebb73](https://linux-hardware.org/?probe=a194cebb73) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [90ccec43bf](https://linux-hardware.org/?probe=90ccec43bf) | Jul 06, 2022 |
| HP            | EliteBook 745 G2            | [21b712ca64](https://linux-hardware.org/?probe=21b712ca64) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [ece534d446](https://linux-hardware.org/?probe=ece534d446) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [1c52419886](https://linux-hardware.org/?probe=1c52419886) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [b7ed5b72a9](https://linux-hardware.org/?probe=b7ed5b72a9) | Jul 05, 2022 |
| HP            | ProBook 640 G1              | [2f88b6162e](https://linux-hardware.org/?probe=2f88b6162e) | Jul 05, 2022 |
| HP            | Pavilion 15                 | [abbd7fd848](https://linux-hardware.org/?probe=abbd7fd848) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| Toshiba       | Satellite C650D             | [23da2ae018](https://linux-hardware.org/?probe=23da2ae018) | Jul 04, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Acer          | Aspire E1-572G              | [6f24a453bf](https://linux-hardware.org/?probe=6f24a453bf) | Jul 04, 2022 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [67d4a66421](https://linux-hardware.org/?probe=67d4a66421) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Notebook      | P65xHP                      | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [80c5bb3483](https://linux-hardware.org/?probe=80c5bb3483) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Acer          | Aspire E5-473G              | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8999ce3eca](https://linux-hardware.org/?probe=8999ce3eca) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6e6839a1d0](https://linux-hardware.org/?probe=6e6839a1d0) | Jul 03, 2022 |
| ASUSTek       | G751JT                      | [f437b1ee99](https://linux-hardware.org/?probe=f437b1ee99) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [a8c5e48dc8](https://linux-hardware.org/?probe=a8c5e48dc8) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [516b60430c](https://linux-hardware.org/?probe=516b60430c) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [c70a95cfc1](https://linux-hardware.org/?probe=c70a95cfc1) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| Dell          | Precision 7510              | [4831b50f9a](https://linux-hardware.org/?probe=4831b50f9a) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Samsung       | 930XED                      | [56a04fa69d](https://linux-hardware.org/?probe=56a04fa69d) | Jul 01, 2022 |
| ASUSTek       | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| Dell          | Precision 5530              | [d6dc0ecd91](https://linux-hardware.org/?probe=d6dc0ecd91) | Jul 01, 2022 |
| Dell          | Precision 5550              | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| Dell          | Precision 7510              | [c82cc3cb0f](https://linux-hardware.org/?probe=c82cc3cb0f) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Apple         | MacBookAir7,2               | [ab31abf1d5](https://linux-hardware.org/?probe=ab31abf1d5) | Jun 30, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| Notebook      | P7xxDM3(-G)                 | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| Dell          | Latitude E5470              | [2440e59a5a](https://linux-hardware.org/?probe=2440e59a5a) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| Eluktronic... | MECH-15 G3                  | [d307b13800](https://linux-hardware.org/?probe=d307b13800) | Jun 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c14a32dd6b](https://linux-hardware.org/?probe=c14a32dd6b) | Jun 28, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [843cbccc63](https://linux-hardware.org/?probe=843cbccc63) | Jun 27, 2022 |
| HP            | Pavilion Notebook           | [8e17cfd388](https://linux-hardware.org/?probe=8e17cfd388) | Jun 26, 2022 |
| HP            | EliteBook 820 G2            | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [490c1074fe](https://linux-hardware.org/?probe=490c1074fe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [51d3a22bf6](https://linux-hardware.org/?probe=51d3a22bf6) | Jun 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| System76      | Darter Pro                  | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| HP            | EliteBook 745 G2            | [fe87d16f84](https://linux-hardware.org/?probe=fe87d16f84) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [c2a22e5a3d](https://linux-hardware.org/?probe=c2a22e5a3d) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [962571591a](https://linux-hardware.org/?probe=962571591a) | Jun 24, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| ASUSTek       | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| Dell          | Precision 5520              | [2216faa750](https://linux-hardware.org/?probe=2216faa750) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| Lenovo        | V14-IIL 82C4                | [c288025720](https://linux-hardware.org/?probe=c288025720) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [3086580cf5](https://linux-hardware.org/?probe=3086580cf5) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [0bc7456f92](https://linux-hardware.org/?probe=0bc7456f92) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Quanta        | TWC                         | [6a466d7eac](https://linux-hardware.org/?probe=6a466d7eac) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [0350f8d8f7](https://linux-hardware.org/?probe=0350f8d8f7) | Jun 21, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | 15 Notebook PC              | [b3efe3d4b5](https://linux-hardware.org/?probe=b3efe3d4b5) | Jun 19, 2022 |
| Apple         | MacBookPro11,5              | [b04866cc36](https://linux-hardware.org/?probe=b04866cc36) | Jun 19, 2022 |
| Apple         | MacBook5,1                  | [e601e834f2](https://linux-hardware.org/?probe=e601e834f2) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [41eb5a7de2](https://linux-hardware.org/?probe=41eb5a7de2) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ed83fdd673](https://linux-hardware.org/?probe=ed83fdd673) | Jun 18, 2022 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [77dd393da8](https://linux-hardware.org/?probe=77dd393da8) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [d542c2f694](https://linux-hardware.org/?probe=d542c2f694) | Jun 18, 2022 |
| Dell          | Latitude E7240              | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| HP            | Unknown                     | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Apple         | MacBookAir7,2               | [13d72fd6f0](https://linux-hardware.org/?probe=13d72fd6f0) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Schenker      | VIA 15 Pro                  | [1d1727713f](https://linux-hardware.org/?probe=1d1727713f) | Jun 17, 2022 |
| HP            | EliteBook 8560p             | [8f60c0fb25](https://linux-hardware.org/?probe=8f60c0fb25) | Jun 17, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | Aspire E5-574G              | [23c2dd37fe](https://linux-hardware.org/?probe=23c2dd37fe) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Acer          | Aspire 4741                 | [9f25816784](https://linux-hardware.org/?probe=9f25816784) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| System76      | Oryx Pro                    | [4daa6c7d77](https://linux-hardware.org/?probe=4daa6c7d77) | Jun 16, 2022 |
| Dell          | Latitude E6540              | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| System76      | Galago Pro                  | [440ba53ef9](https://linux-hardware.org/?probe=440ba53ef9) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Dell          | Inspiron 7520               | [d6e4d7642d](https://linux-hardware.org/?probe=d6e4d7642d) | Jun 16, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| Acer          | Aspire E5-575G              | [aa390f3eaa](https://linux-hardware.org/?probe=aa390f3eaa) | Jun 15, 2022 |
| Sony          | SVF15A1M2ES                 | [bdcd4a90fc](https://linux-hardware.org/?probe=bdcd4a90fc) | Jun 15, 2022 |
| Dell          | Latitude E6540              | [03fb6fa23c](https://linux-hardware.org/?probe=03fb6fa23c) | Jun 15, 2022 |
| Dell          | Precision 5550              | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | Precision 7720              | [8b4da2326e](https://linux-hardware.org/?probe=8b4da2326e) | Jun 14, 2022 |
| Dell          | Precision 7720              | [bf25929cec](https://linux-hardware.org/?probe=bf25929cec) | Jun 14, 2022 |
| Dell          | Latitude E6540              | [44b876534d](https://linux-hardware.org/?probe=44b876534d) | Jun 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f4ef35b902](https://linux-hardware.org/?probe=f4ef35b902) | Jun 14, 2022 |
| Dell          | Inspiron 7737               | [6fa74e19b1](https://linux-hardware.org/?probe=6fa74e19b1) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [2eb24f0195](https://linux-hardware.org/?probe=2eb24f0195) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [110ff08266](https://linux-hardware.org/?probe=110ff08266) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | [7222fb776a](https://linux-hardware.org/?probe=7222fb776a) | Jun 13, 2022 |
| Dell          | Latitude E6540              | [91e07b8f2d](https://linux-hardware.org/?probe=91e07b8f2d) | Jun 12, 2022 |
| ASUSTek       | UX430UQ                     | [9754c7394d](https://linux-hardware.org/?probe=9754c7394d) | Jun 12, 2022 |
| Dell          | System XPS L702X            | [b79115e065](https://linux-hardware.org/?probe=b79115e065) | Jun 12, 2022 |
| MSI           | Alpha 17 A4DEK              | [42171e02bb](https://linux-hardware.org/?probe=42171e02bb) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Acer          | Aspire 4349                 | [7c8c3427a9](https://linux-hardware.org/?probe=7c8c3427a9) | Jun 11, 2022 |
| HP            | ProBook 455 G3              | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| Dell          | Latitude E7270              | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| HP            | Elite x2 1012 G1            | [ad03ec2516](https://linux-hardware.org/?probe=ad03ec2516) | Jun 09, 2022 |
| Dell          | Inspiron 7520               | [ebbea30b2b](https://linux-hardware.org/?probe=ebbea30b2b) | Jun 09, 2022 |
| Dell          | G7 7790                     | [58cfc35862](https://linux-hardware.org/?probe=58cfc35862) | Jun 09, 2022 |
| Dell          | G7 7790                     | [495cfbb6f3](https://linux-hardware.org/?probe=495cfbb6f3) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| System76      | Oryx Pro                    | [2f96b6b08d](https://linux-hardware.org/?probe=2f96b6b08d) | Jun 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5c2fedfca8](https://linux-hardware.org/?probe=5c2fedfca8) | Jun 08, 2022 |
| Dell          | Vostro 5402                 | [ebf8dce138](https://linux-hardware.org/?probe=ebf8dce138) | Jun 07, 2022 |
| Dell          | Precision M4800             | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Framework     | Laptop                      | [ed8e682778](https://linux-hardware.org/?probe=ed8e682778) | Jun 06, 2022 |
| Samsung       | 760XDA                      | [46350b515c](https://linux-hardware.org/?probe=46350b515c) | Jun 06, 2022 |
| MSI           | GS75 Stealth 9SF            | [9d18e7094e](https://linux-hardware.org/?probe=9d18e7094e) | Jun 05, 2022 |
| ASUSTek       | X556URK                     | [d6da70c8bd](https://linux-hardware.org/?probe=d6da70c8bd) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [1485986503](https://linux-hardware.org/?probe=1485986503) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [2f60fd04bf](https://linux-hardware.org/?probe=2f60fd04bf) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Dell          | Inspiron 3502               | [afa1c5cd74](https://linux-hardware.org/?probe=afa1c5cd74) | Jun 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [f729442cad](https://linux-hardware.org/?probe=f729442cad) | Jun 04, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 5.19.0-76051900-generic              | 265       | 27.07%  |
| 5.17.5-76051705-generic              | 225       | 22.98%  |
| 5.18.10-76051810-generic             | 114       | 11.64%  |
| 5.17.15-76051715-generic             | 104       | 10.62%  |
| 6.0.6-76060006-generic               | 76        | 7.76%   |
| 5.16.19-76051619-generic             | 70        | 7.15%   |
| 6.0.2-76060002-generic               | 56        | 5.72%   |
| 6.0.3-76060003-generic               | 23        | 2.35%   |
| 5.19.16-76051916-generic             | 21        | 2.15%   |
| 5.17.5-051705-generic                | 2         | 0.2%    |
| 5.16.15-76051615-generic             | 2         | 0.2%    |
| 6.0.9-x64v1-xanmod1                  | 1         | 0.1%    |
| 6.0.9-060009-generic                 | 1         | 0.1%    |
| 6.0.2-x64v2-xanmod1                  | 1         | 0.1%    |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.1%    |
| 6.0.0-060000-generic                 | 1         | 0.1%    |
| 5.19.3-051903-generic                | 1         | 0.1%    |
| 5.19.14-xanmod1                      | 1         | 0.1%    |
| 5.19.12-xanmod1                      | 1         | 0.1%    |
| 5.19.0-rc1+                          | 1         | 0.1%    |
| 5.19.0-051900-generic                | 1         | 0.1%    |
| 5.18.6-xanmod1                       | 1         | 0.1%    |
| 5.18.4-xanmod1                       | 1         | 0.1%    |
| 5.18.16-xanmod1                      | 1         | 0.1%    |
| 5.18.0-051800rc1-generic             | 1         | 0.1%    |
| 5.17.7-051707-generic                | 1         | 0.1%    |
| 5.17.6-051706-generic                | 1         | 0.1%    |
| 5.17.5-tkg-bmq                       | 1         | 0.1%    |
| 5.17.2-xanmod1                       | 1         | 0.1%    |
| 5.17.0-051700-generic                | 1         | 0.1%    |
| 5.16.11-76051611-generic             | 1         | 0.1%    |
| 5.15.0-46-generic                    | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 267       | 27.27%  |
| 5.17.5  | 228       | 23.29%  |
| 5.18.10 | 114       | 11.64%  |
| 5.17.15 | 104       | 10.62%  |
| 6.0.6   | 76        | 7.76%   |
| 5.16.19 | 70        | 7.15%   |
| 6.0.2   | 57        | 5.82%   |
| 6.0.3   | 23        | 2.35%   |
| 5.19.16 | 21        | 2.15%   |
| 6.0.9   | 2         | 0.2%    |
| 6.0.0   | 2         | 0.2%    |
| 5.16.15 | 2         | 0.2%    |
| 5.19.3  | 1         | 0.1%    |
| 5.19.14 | 1         | 0.1%    |
| 5.19.12 | 1         | 0.1%    |
| 5.18.6  | 1         | 0.1%    |
| 5.18.4  | 1         | 0.1%    |
| 5.18.16 | 1         | 0.1%    |
| 5.18.0  | 1         | 0.1%    |
| 5.17.7  | 1         | 0.1%    |
| 5.17.6  | 1         | 0.1%    |
| 5.17.2  | 1         | 0.1%    |
| 5.17.0  | 1         | 0.1%    |
| 5.16.11 | 1         | 0.1%    |
| 5.15.0  | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 330       | 34.06%  |
| 5.19    | 289       | 29.82%  |
| 6.0     | 158       | 16.31%  |
| 5.18    | 118       | 12.18%  |
| 5.16    | 73        | 7.53%   |
| 5.15    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 922       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 901       | 97.51%  |
| KDE5            | 9         | 0.97%   |
| Unknown         | 7         | 0.76%   |
| X-Cinnamon      | 2         | 0.22%   |
| GNOME Flashback | 2         | 0.22%   |
| XFCE            | 1         | 0.11%   |
| Unity           | 1         | 0.11%   |
| LXQt            | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 877       | 94.61%  |
| Wayland | 43        | 4.64%   |
| Unknown | 5         | 0.54%   |
| Tty     | 2         | 0.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 674       | 72.63%  |
| GDM3    | 251       | 27.05%  |
| GDM     | 3         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 556       | 60.04%  |
| en_GB   | 65        | 7.02%   |
| pt_BR   | 55        | 5.94%   |
| de_DE   | 37        | 4%      |
| it_IT   | 25        | 2.7%    |
| en_AU   | 24        | 2.59%   |
| C       | 18        | 1.94%   |
| fr_FR   | 16        | 1.73%   |
| es_ES   | 14        | 1.51%   |
| en_CA   | 14        | 1.51%   |
| ru_RU   | 9         | 0.97%   |
| pl_PL   | 8         | 0.86%   |
| nb_NO   | 8         | 0.86%   |
| en_IE   | 6         | 0.65%   |
| Unknown | 6         | 0.65%   |
| sv_SE   | 5         | 0.54%   |
| fi_FI   | 5         | 0.54%   |
| pt_PT   | 4         | 0.43%   |
| es_MX   | 4         | 0.43%   |
| es_AR   | 4         | 0.43%   |
| de_CH   | 4         | 0.43%   |
| nl_NL   | 3         | 0.32%   |
| fr_CA   | 3         | 0.32%   |
| es_CO   | 3         | 0.32%   |
| es_CL   | 3         | 0.32%   |
| en_NZ   | 3         | 0.32%   |
| en_IN   | 3         | 0.32%   |
| en_ZA   | 2         | 0.22%   |
| en_SG   | 2         | 0.22%   |
| en_DK   | 2         | 0.22%   |
| da_DK   | 2         | 0.22%   |
| tr_TR   | 1         | 0.11%   |
| sr_RS   | 1         | 0.11%   |
| ro_RO   | 1         | 0.11%   |
| hr_HR   | 1         | 0.11%   |
| fr_CH   | 1         | 0.11%   |
| fr_BE   | 1         | 0.11%   |
| es_UY   | 1         | 0.11%   |
| es_HN   | 1         | 0.11%   |
| es_GT   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 687       | 74.11%  |
| EFI  | 240       | 25.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 876       | 94.7%   |
| Btrfs   | 34        | 3.68%   |
| Overlay | 12        | 1.3%    |
| Xfs     | 3         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 668       | 71.98%  |
| GPT     | 243       | 26.19%  |
| MBR     | 17        | 1.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 895       | 96.76%  |
| Yes       | 30        | 3.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 839       | 90.7%   |
| Yes       | 86        | 9.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 174       | 18.87%  |
| Dell                   | 158       | 17.14%  |
| ASUSTek Computer       | 120       | 13.02%  |
| Hewlett-Packard        | 113       | 12.26%  |
| Acer                   | 70        | 7.59%   |
| Apple                  | 65        | 7.05%   |
| MSI                    | 39        | 4.23%   |
| System76               | 31        | 3.36%   |
| Toshiba                | 21        | 2.28%   |
| Samsung Electronics    | 18        | 1.95%   |
| HUAWEI                 | 15        | 1.63%   |
| Google                 | 8         | 0.87%   |
| Fujitsu                | 7         | 0.76%   |
| GPU Company            | 6         | 0.65%   |
| Alienware              | 6         | 0.65%   |
| Sony                   | 5         | 0.54%   |
| Notebook               | 5         | 0.54%   |
| Gigabyte Technology    | 5         | 0.54%   |
| Razer                  | 4         | 0.43%   |
| Framework              | 4         | 0.43%   |
| Timi                   | 3         | 0.33%   |
| PC Specialist          | 3         | 0.33%   |
| Valve                  | 2         | 0.22%   |
| TUXEDO                 | 2         | 0.22%   |
| Positivo               | 2         | 0.22%   |
| Panasonic              | 2         | 0.22%   |
| Medion                 | 2         | 0.22%   |
| HONOR                  | 2         | 0.22%   |
| Clevo                  | 2         | 0.22%   |
| Avell High Performance | 2         | 0.22%   |
| Unknown                | 2         | 0.22%   |
| Wortmann AG            | 1         | 0.11%   |
| Tactus                 | 1         | 0.11%   |
| Semp Toshiba           | 1         | 0.11%   |
| Schenker               | 1         | 0.11%   |
| Razer x Lambda         | 1         | 0.11%   |
| Quanta                 | 1         | 0.11%   |
| Purism                 | 1         | 0.11%   |
| Pegatron               | 1         | 0.11%   |
| OriginPC               | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| System76 Oryx Pro                     | 12        | 1.3%    |
| System76 Lemur Pro                    | 8         | 0.87%   |
| Apple MacBookAir7,2                   | 7         | 0.76%   |
| Apple MacBookAir6,2                   | 7         | 0.76%   |
| Dell XPS 15 9520                      | 6         | 0.65%   |
| Lenovo IdeaPad S145-15API 81V7        | 5         | 0.54%   |
| Apple MacBookPro9,2                   | 5         | 0.54%   |
| Unknown                               | 5         | 0.54%   |
| Dell XPS 13 9310                      | 4         | 0.43%   |
| Apple MacBookPro7,1                   | 4         | 0.43%   |
| Acer Aspire A515-45                   | 4         | 0.43%   |
| System76 Galago Pro                   | 3         | 0.33%   |
| System76 Darter Pro                   | 3         | 0.33%   |
| MSI Prestige 15 A10SC                 | 3         | 0.33%   |
| Lenovo Legion Y530-15ICH 81FV         | 3         | 0.33%   |
| Lenovo IdeaPad 3 15ALC6 82MF          | 3         | 0.33%   |
| HP Pavilion Notebook                  | 3         | 0.33%   |
| HP Pavilion 15                        | 3         | 0.33%   |
| HP OMEN Laptop 15-en0xxx              | 3         | 0.33%   |
| HP Dev One Notebook PC                | 3         | 0.33%   |
| HP 15 Notebook PC                     | 3         | 0.33%   |
| GPU Company GWTN141-10                | 3         | 0.33%   |
| GPU Company GWTC116-2                 | 3         | 0.33%   |
| Framework Laptop                      | 3         | 0.33%   |
| Dell XPS 15 9570                      | 3         | 0.33%   |
| Dell XPS 13 9360                      | 3         | 0.33%   |
| Dell XPS 13 9305                      | 3         | 0.33%   |
| Dell Latitude E7270                   | 3         | 0.33%   |
| Dell Latitude E7240                   | 3         | 0.33%   |
| Dell Latitude E6540                   | 3         | 0.33%   |
| Dell Inspiron 5547                    | 3         | 0.33%   |
| Dell Inspiron 3442                    | 3         | 0.33%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 0.33%   |
| Apple MacBookPro12,1                  | 3         | 0.33%   |
| Apple MacBookPro11,3                  | 3         | 0.33%   |
| Valve Jupiter                         | 2         | 0.22%   |
| Toshiba Satellite C55t-C              | 2         | 0.22%   |
| System76 Pangolin                     | 2         | 0.22%   |
| System76 Gazelle                      | 2         | 0.22%   |
| Samsung 800G5M/800G5W                 | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 76        | 8.24%   |
| Acer Aspire        | 49        | 5.31%   |
| Dell Inspiron      | 45        | 4.88%   |
| Lenovo IdeaPad     | 44        | 4.77%   |
| Dell Latitude      | 37        | 4.01%   |
| Dell XPS           | 35        | 3.8%    |
| ASUS ROG           | 25        | 2.71%   |
| HP Pavilion        | 24        | 2.6%    |
| Lenovo Legion      | 23        | 2.49%   |
| HP Laptop          | 22        | 2.39%   |
| Toshiba Satellite  | 18        | 1.95%   |
| HP ProBook         | 17        | 1.84%   |
| HP EliteBook       | 17        | 1.84%   |
| Dell Precision     | 17        | 1.84%   |
| ASUS VivoBook      | 17        | 1.84%   |
| Dell Vostro        | 13        | 1.41%   |
| ASUS ASUS          | 13        | 1.41%   |
| System76 Oryx      | 12        | 1.3%    |
| ASUS ZenBook       | 11        | 1.19%   |
| Acer Swift         | 9         | 0.98%   |
| System76 Lemur     | 8         | 0.87%   |
| Lenovo ThinkBook   | 8         | 0.87%   |
| Apple MacBookPro11 | 8         | 0.87%   |
| Acer Nitro         | 8         | 0.87%   |
| HP ZBook           | 7         | 0.76%   |
| HP OMEN            | 7         | 0.76%   |
| Apple MacBookAir7  | 7         | 0.76%   |
| Apple MacBookAir6  | 7         | 0.76%   |
| MSI Prestige       | 6         | 0.65%   |
| Fujitsu LIFEBOOK   | 6         | 0.65%   |
| Apple MacBookPro9  | 6         | 0.65%   |
| Apple MacBookPro5  | 6         | 0.65%   |
| MSI Modern         | 5         | 0.54%   |
| Lenovo Yoga        | 5         | 0.54%   |
| HP ENVY            | 5         | 0.54%   |
| Unknown            | 5         | 0.54%   |
| System76 Galago    | 4         | 0.43%   |
| Razer Blade        | 4         | 0.43%   |
| MSI Katana         | 4         | 0.43%   |
| MSI GF63           | 4         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 158       | 17.14%  |
| 2020 | 118       | 12.8%   |
| 2022 | 87        | 9.44%   |
| 2019 | 83        | 9%      |
| 2018 | 68        | 7.38%   |
| 2016 | 57        | 6.18%   |
| 2013 | 57        | 6.18%   |
| 2015 | 51        | 5.53%   |
| 2012 | 50        | 5.42%   |
| 2017 | 45        | 4.88%   |
| 2014 | 40        | 4.34%   |
| 2011 | 37        | 4.01%   |
| 2010 | 31        | 3.36%   |
| 2009 | 29        | 3.15%   |
| 2008 | 8         | 0.87%   |
| 2007 | 3         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 922       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 922       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 891       | 96.64%  |
| Yes  | 31        | 3.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 270       | 29.19%  |
| 16.01-24.0  | 233       | 25.19%  |
| 8.01-16.0   | 169       | 18.27%  |
| 3.01-4.0    | 114       | 12.32%  |
| 32.01-64.0  | 100       | 10.81%  |
| 64.01-256.0 | 21        | 2.27%   |
| 24.01-32.0  | 13        | 1.41%   |
| 1.01-2.0    | 3         | 0.32%   |
| 2.01-3.0    | 2         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 343       | 35.25%  |
| 3.01-4.0   | 221       | 22.71%  |
| 4.01-8.0   | 218       | 22.4%   |
| 1.01-2.0   | 123       | 12.64%  |
| 8.01-16.0  | 60        | 6.17%   |
| 16.01-24.0 | 8         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 677       | 73.03%  |
| 2      | 220       | 23.73%  |
| 3      | 28        | 3.02%   |
| 7      | 1         | 0.11%   |
| 0      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 713       | 77.25%  |
| Yes       | 210       | 22.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 696       | 75.24%  |
| No        | 229       | 24.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 917       | 99.46%  |
| No        | 5         | 0.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 799       | 86.29%  |
| No        | 127       | 13.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 239       | 25.78%  |
| Brazil      | 87        | 9.39%   |
| Germany     | 59        | 6.36%   |
| Italy       | 46        | 4.96%   |
| UK          | 40        | 4.31%   |
| India       | 39        | 4.21%   |
| Canada      | 34        | 3.67%   |
| France      | 26        | 2.8%    |
| Australia   | 26        | 2.8%    |
| Russia      | 19        | 2.05%   |
| Norway      | 17        | 1.83%   |
| Netherlands | 16        | 1.73%   |
| Spain       | 15        | 1.62%   |
| Sweden      | 13        | 1.4%    |
| Mexico      | 13        | 1.4%    |
| Portugal    | 11        | 1.19%   |
| Poland      | 11        | 1.19%   |
| Switzerland | 10        | 1.08%   |
| Argentina   | 10        | 1.08%   |
| Turkey      | 9         | 0.97%   |
| Finland     | 9         | 0.97%   |
| Romania     | 8         | 0.86%   |
| Greece      | 8         | 0.86%   |
| Philippines | 7         | 0.76%   |
| New Zealand | 7         | 0.76%   |
| Indonesia   | 7         | 0.76%   |
| Chile       | 7         | 0.76%   |
| Egypt       | 6         | 0.65%   |
| Denmark     | 6         | 0.65%   |
| Colombia    | 6         | 0.65%   |
| Belgium     | 6         | 0.65%   |
| Thailand    | 5         | 0.54%   |
| Singapore   | 5         | 0.54%   |
| Serbia      | 5         | 0.54%   |
| Hungary     | 5         | 0.54%   |
| Malaysia    | 4         | 0.43%   |
| Ireland     | 4         | 0.43%   |
| Bulgaria    | 4         | 0.43%   |
| Austria     | 4         | 0.43%   |
| Vietnam     | 3         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brisbane       | 10        | 1.06%   |
| Milan          | 9         | 0.95%   |
| Oslo           | 8         | 0.85%   |
| Berlin         | 8         | 0.85%   |
| Bengaluru      | 8         | 0.85%   |
| Rome           | 7         | 0.74%   |
| Rio de Janeiro | 7         | 0.74%   |
| Melbourne      | 7         | 0.74%   |
| Istanbul       | 7         | 0.74%   |
| Sao Paulo      | 6         | 0.64%   |
| Moscow         | 6         | 0.64%   |
| Helsinki       | 6         | 0.64%   |
| Zurich         | 5         | 0.53%   |
| Singapore      | 5         | 0.53%   |
| Mumbai         | 5         | 0.53%   |
| Warsaw         | 4         | 0.42%   |
| Sydney         | 4         | 0.42%   |
| Stockholm      | 4         | 0.42%   |
| St Petersburg  | 4         | 0.42%   |
| Paris          | 4         | 0.42%   |
| Munich         | 4         | 0.42%   |
| Mannheim       | 4         | 0.42%   |
| Madrid         | 4         | 0.42%   |
| London         | 4         | 0.42%   |
| Lincoln        | 4         | 0.42%   |
| Jakarta        | 4         | 0.42%   |
| Hamburg        | 4         | 0.42%   |
| Edmonton       | 4         | 0.42%   |
| Denver         | 4         | 0.42%   |
| Dallas         | 4         | 0.42%   |
| Bucharest      | 4         | 0.42%   |
| Victoria       | 3         | 0.32%   |
| Tucson         | 3         | 0.32%   |
| Toronto        | 3         | 0.32%   |
| Stuttgart      | 3         | 0.32%   |
| Sofia          | 3         | 0.32%   |
| Sao Luís      | 3         | 0.32%   |
| San Diego      | 3         | 0.32%   |
| Salt Lake City | 3         | 0.32%   |
| Ribeirao Preto | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 219       | 263    | 18.78%  |
| WDC                            | 98        | 106    | 8.4%    |
| SanDisk                        | 97        | 118    | 8.32%   |
| Seagate                        | 80        | 89     | 6.86%   |
| Toshiba                        | 71        | 81     | 6.09%   |
| SK hynix                       | 70        | 77     | 6%      |
| Kingston                       | 65        | 72     | 5.57%   |
| Micron Technology              | 44        | 48     | 3.77%   |
| Unknown                        | 41        | 48     | 3.52%   |
| Crucial                        | 39        | 39     | 3.34%   |
| Intel                          | 37        | 41     | 3.17%   |
| Apple                          | 35        | 38     | 3%      |
| HGST                           | 32        | 33     | 2.74%   |
| Phison                         | 20        | 22     | 1.72%   |
| Hitachi                        | 13        | 15     | 1.11%   |
| A-DATA Technology              | 13        | 14     | 1.11%   |
| PNY                            | 12        | 15     | 1.03%   |
| KIOXIA                         | 12        | 12     | 1.03%   |
| Silicon Motion                 | 10        | 11     | 0.86%   |
| Micron/Crucial Technology      | 9         | 10     | 0.77%   |
| China                          | 9         | 10     | 0.77%   |
| KingSpec                       | 7         | 8      | 0.6%    |
| Union Memory (Shenzhen)        | 6         | 8      | 0.51%   |
| Phison Electronics             | 6         | 7      | 0.51%   |
| LITEON                         | 6         | 7      | 0.51%   |
| Intenso                        | 6         | 6      | 0.51%   |
| Unknown                        | 6         | 7      | 0.51%   |
| LITEONIT                       | 5         | 7      | 0.43%   |
| ADATA Technology               | 5         | 5      | 0.43%   |
| Team                           | 4         | 4      | 0.34%   |
| SPCC                           | 4         | 4      | 0.34%   |
| Solid State Storage Technology | 4         | 4      | 0.34%   |
| Netac                          | 4         | 5      | 0.34%   |
| Kingston Technology Company    | 4         | 4      | 0.34%   |
| W800S                          | 3         | 6      | 0.26%   |
| MyDigitalSSD                   | 3         | 3      | 0.26%   |
| Fujitsu                        | 3         | 3      | 0.26%   |
| UMIS                           | 2         | 2      | 0.17%   |
| SSSTC                          | 2         | 2      | 0.17%   |
| Solid State Storage            | 2         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 19        | 1.56%   |
| Samsung NVMe SSD Drive 512GB                         | 17        | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB                       | 15        | 1.23%   |
| SK hynix NVMe SSD Drive 512GB                        | 14        | 1.15%   |
| HGST HTS721010A9E630 1TB                             | 13        | 1.07%   |
| SanDisk NVMe SSD Drive 1TB                           | 12        | 0.98%   |
| Toshiba MQ01ABD100 1TB                               | 10        | 0.82%   |
| Samsung NVMe SSD Drive 1TB                           | 10        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 10        | 0.82%   |
| SK hynix NVMe SSD Drive 1024GB                       | 9         | 0.74%   |
| SanDisk NVMe SSD Drive 512GB                         | 9         | 0.74%   |
| SanDisk NVMe SSD Drive 256GB                         | 9         | 0.74%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 9         | 0.74%   |
| Samsung NVMe SSD Drive 500GB                         | 9         | 0.74%   |
| Kingston SA400S37480G 480GB SSD                      | 9         | 0.74%   |
| Seagate ST1000LM049-2GH172 1TB                       | 8         | 0.66%   |
| Samsung SSD 850 EVO 500GB                            | 8         | 0.66%   |
| Samsung NVMe SSD Drive 2TB                           | 8         | 0.66%   |
| Samsung NVMe SSD Drive 1024GB                        | 8         | 0.66%   |
| Crucial CT240BX500SSD1 240GB                         | 8         | 0.66%   |
| WDC WD10SPZX-24Z10 1TB                               | 7         | 0.57%   |
| Unknown MMC Card  64GB                               | 7         | 0.57%   |
| Unknown MMC Card  32GB                               | 7         | 0.57%   |
| Toshiba MQ04ABF100 1TB                               | 7         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 7         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB                         | 7         | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 7         | 0.57%   |
| Micron NVMe SSD Drive 512GB                          | 7         | 0.57%   |
| Kingston NVMe SSD Drive 512GB                        | 7         | 0.57%   |
| Unknown MMC Card  128GB                              | 6         | 0.49%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 6         | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB  | 6         | 0.49%   |
| Kingston SA400S37120G 120GB SSD                      | 6         | 0.49%   |
| Apple SSD SM0128G 121GB                              | 6         | 0.49%   |
| Unknown                                              | 6         | 0.49%   |
| SK hynix NVMe SSD Drive 256GB                        | 5         | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB    | 5         | 0.41%   |
| SanDisk NVMe SSD Drive 500GB                         | 5         | 0.41%   |
| SanDisk NVMe SSD Drive 1024GB                        | 5         | 0.41%   |
| Samsung SSD 860 EVO 500GB                            | 5         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 87     | 33.48%  |
| WDC                 | 55        | 61     | 23.61%  |
| Toshiba             | 41        | 46     | 17.6%   |
| HGST                | 32        | 33     | 13.73%  |
| Hitachi             | 13        | 15     | 5.58%   |
| Unknown             | 3         | 3      | 1.29%   |
| Samsung Electronics | 3         | 3      | 1.29%   |
| Fujitsu             | 3         | 3      | 1.29%   |
| Apple               | 2         | 2      | 0.86%   |
| Intenso             | 1         | 1      | 0.43%   |
| HGST HDN            | 1         | 1      | 0.43%   |
| Asm                 | 1         | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 82     | 19.89%  |
| Kingston            | 47        | 48     | 13.17%  |
| SanDisk             | 37        | 42     | 10.36%  |
| Crucial             | 33        | 33     | 9.24%   |
| Apple               | 28        | 30     | 7.84%   |
| WDC                 | 18        | 19     | 5.04%   |
| PNY                 | 11        | 14     | 3.08%   |
| Toshiba             | 9         | 9      | 2.52%   |
| China               | 9         | 10     | 2.52%   |
| SK hynix            | 8         | 9      | 2.24%   |
| Micron Technology   | 7         | 7      | 1.96%   |
| KingSpec            | 7         | 8      | 1.96%   |
| LITEON              | 6         | 7      | 1.68%   |
| Intel               | 6         | 6      | 1.68%   |
| A-DATA Technology   | 6         | 7      | 1.68%   |
| LITEONIT            | 5         | 7      | 1.4%    |
| Intenso             | 4         | 4      | 1.12%   |
| Netac               | 3         | 4      | 0.84%   |
| MyDigitalSSD        | 3         | 3      | 0.84%   |
| SPCC                | 2         | 2      | 0.56%   |
| KingDian            | 2         | 2      | 0.56%   |
| JMicron Technology  | 2         | 2      | 0.56%   |
| Apacer              | 2         | 4      | 0.56%   |
| W800S               | 1         | 1      | 0.28%   |
| USB3.0              | 1         | 1      | 0.28%   |
| TwinMOS             | 1         | 1      | 0.28%   |
| TrekStor            | 1         | 1      | 0.28%   |
| Transcend           | 1         | 1      | 0.28%   |
| Teutons             | 1         | 1      | 0.28%   |
| SATAFIRM            | 1         | 1      | 0.28%   |
| Ramaxel Technology  | 1         | 1      | 0.28%   |
| Radeon              | 1         | 1      | 0.28%   |
| PUSKILL             | 1         | 1      | 0.28%   |
| PNY USB             | 1         | 1      | 0.28%   |
| Phison              | 1         | 1      | 0.28%   |
| Patriot             | 1         | 1      | 0.28%   |
| OWC                 | 1         | 1      | 0.28%   |
| Lexar               | 1         | 1      | 0.28%   |
| Leven               | 1         | 1      | 0.28%   |
| KingFast            | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 475       | 607    | 43.46%  |
| SSD     | 336       | 390    | 30.74%  |
| HDD     | 226       | 256    | 20.68%  |
| MMC     | 39        | 43     | 3.57%   |
| Unknown | 17        | 23     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 499       | 623    | 47.39%  |
| NVMe | 474       | 605    | 45.01%  |
| SAS  | 41        | 48     | 3.89%   |
| MMC  | 39        | 43     | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 355       | 427    | 64.43%  |
| 0.51-1.0   | 177       | 194    | 32.12%  |
| 1.01-2.0   | 14        | 18     | 2.54%   |
| 3.01-4.0   | 2         | 2      | 0.36%   |
| 4.01-10.0  | 2         | 4      | 0.36%   |
| 2.01-3.0   | 1         | 1      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 312       | 33.33%  |
| 251-500        | 275       | 29.38%  |
| 501-1000       | 192       | 20.51%  |
| 1001-2000      | 61        | 6.52%   |
| 51-100         | 28        | 2.99%   |
| 21-50          | 20        | 2.14%   |
| 2001-3000      | 15        | 1.6%    |
| 1-20           | 15        | 1.6%    |
| More than 3000 | 13        | 1.39%   |
| Unknown        | 5         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 319       | 32.99%  |
| 21-50          | 229       | 23.68%  |
| 101-250        | 160       | 16.55%  |
| 51-100         | 126       | 13.03%  |
| 251-500        | 79        | 8.17%   |
| 501-1000       | 38        | 3.93%   |
| 1001-2000      | 8         | 0.83%   |
| Unknown        | 5         | 0.52%   |
| More than 3000 | 3         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 10.53%  |
| HGST HTS725050A7E630 500GB                          | 2         | 3      | 10.53%  |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 5.26%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 5.26%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 5.26%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 5.26%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB               | 1         | 1      | 5.26%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 5.26%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 5.26%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 5.26%   |
| Lexar 1TB SSD                                       | 1         | 1      | 5.26%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 5.26%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 26.32%  |
| HGST                | 3         | 4      | 15.79%  |
| Toshiba             | 2         | 2      | 10.53%  |
| SK hynix            | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| Team                | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Lexar               | 1         | 1      | 5.26%   |
| Leven               | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 3      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 50%     |
| HGST    | 3         | 4      | 30%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 3      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 13     | 52.63%  |
| SSD  | 5         | 5      | 26.32%  |
| NVMe | 4         | 4      | 21.05%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 691       | 966    | 71.02%  |
| Works    | 262       | 330    | 26.93%  |
| Malfunc  | 19        | 22     | 1.95%   |
| Failed   | 1         | 1      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 554       | 45.94%  |
| Samsung Electronics            | 167       | 13.85%  |
| AMD                            | 124       | 10.28%  |
| SanDisk                        | 82        | 6.8%    |
| SK hynix                       | 62        | 5.14%   |
| Micron Technology              | 36        | 2.99%   |
| Phison Electronics             | 28        | 2.32%   |
| Toshiba America Info Systems   | 21        | 1.74%   |
| Kingston Technology Company    | 21        | 1.74%   |
| Nvidia                         | 19        | 1.58%   |
| Micron/Crucial Technology      | 14        | 1.16%   |
| KIOXIA                         | 13        | 1.08%   |
| Silicon Motion                 | 12        | 1%      |
| ADATA Technology               | 11        | 0.91%   |
| Union Memory (Shenzhen)        | 8         | 0.66%   |
| Solid State Storage Technology | 8         | 0.66%   |
| Marvell Technology Group       | 7         | 0.58%   |
| Apple                          | 5         | 0.41%   |
| Shenzhen Longsys Electronics   | 4         | 0.33%   |
| Realtek Semiconductor          | 2         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.17%   |
| INNOGRIT                       | 2         | 0.17%   |
| Yangtze Memory Technologies    | 1         | 0.08%   |
| Seagate Technology             | 1         | 0.08%   |
| O2 Micro                       | 1         | 0.08%   |
| Lite-On Technology             | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 119       | 9.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 65        | 5.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 60        | 4.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 4.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 50        | 3.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 48        | 3.8%    |
| Samsung NVMe SSD Controller 980                                                | 37        | 2.93%   |
| Micron Non-Volatile memory controller                                          | 36        | 2.85%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 35        | 2.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 33        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 33        | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 32        | 2.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 24        | 1.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 1.74%   |
| SanDisk Non-Volatile memory controller                                         | 21        | 1.66%   |
| Intel SSD 660P Series                                                          | 18        | 1.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 18        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 17        | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 16        | 1.27%   |
| SK hynix Non-Volatile memory controller                                        | 15        | 1.19%   |
| Phison E12 NVMe Controller                                                     | 15        | 1.19%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                            | 14        | 1.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 1.11%   |
| Samsung Electronics SATA controller                                            | 13        | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 13        | 1.03%   |
| Kingston Company Company Non-Volatile memory controller                        | 12        | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 11        | 0.87%   |
| Nvidia MCP79 AHCI Controller                                                   | 11        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 11        | 0.87%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 9         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 9         | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 0.63%   |
| Solid State Storage Non-Volatile memory controller                             | 8         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 599       | 49.96%  |
| NVMe | 471       | 39.28%  |
| RAID | 102       | 8.51%   |
| IDE  | 27        | 2.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 710       | 77.01%  |
| AMD    | 212       | 22.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 24        | 2.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 2.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 21        | 2.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 1.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 16        | 1.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 1.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.3%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.3%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 1.3%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 12        | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.19%   |
| Intel 12th Gen Core i7-12700H                 | 11        | 1.19%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 0.98%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.98%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.98%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 0.98%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.87%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.76%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 0.65%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.65%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 0.65%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.65%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 6         | 0.65%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.65%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 6         | 0.65%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 5         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 230       | 24.95%  |
| Intel Core i5           | 207       | 22.45%  |
| Other                   | 141       | 15.29%  |
| AMD Ryzen 5             | 64        | 6.94%   |
| AMD Ryzen 7             | 63        | 6.83%   |
| Intel Core i3           | 46        | 4.99%   |
| Intel Core 2 Duo        | 33        | 3.58%   |
| Intel Celeron           | 30        | 3.25%   |
| AMD Ryzen 9             | 16        | 1.74%   |
| AMD Ryzen 3             | 12        | 1.3%    |
| Intel Pentium           | 11        | 1.19%   |
| AMD A10                 | 9         | 0.98%   |
| AMD Ryzen 7 PRO         | 8         | 0.87%   |
| AMD A8                  | 8         | 0.87%   |
| AMD A6                  | 8         | 0.87%   |
| Intel Pentium Dual-Core | 5         | 0.54%   |
| Intel Core i9           | 5         | 0.54%   |
| AMD Ryzen 5 PRO         | 4         | 0.43%   |
| AMD A4                  | 4         | 0.43%   |
| Intel Xeon              | 2         | 0.22%   |
| AMD Athlon              | 2         | 0.22%   |
| Intel Pentium Gold      | 1         | 0.11%   |
| Intel Genuine           | 1         | 0.11%   |
| Intel Core m3           | 1         | 0.11%   |
| Intel Core 2 Quad       | 1         | 0.11%   |
| Intel Core 2            | 1         | 0.11%   |
| Intel Atom              | 1         | 0.11%   |
| AMD Turion II           | 1         | 0.11%   |
| AMD Turion 64 X2 Mobile | 1         | 0.11%   |
| AMD Ryzen 3 PRO         | 1         | 0.11%   |
| AMD Phenom II           | 1         | 0.11%   |
| AMD E2                  | 1         | 0.11%   |
| AMD E                   | 1         | 0.11%   |
| AMD Athlon X2           | 1         | 0.11%   |
| AMD A12                 | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 341       | 36.98%  |
| 4      | 312       | 33.84%  |
| 8      | 122       | 13.23%  |
| 6      | 103       | 11.17%  |
| 14     | 22        | 2.39%   |
| 12     | 11        | 1.19%   |
| 10     | 7         | 0.76%   |
| 1      | 3         | 0.33%   |
| 16     | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 922       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 792       | 85.9%   |
| 1      | 130       | 14.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 922       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 658       | 70.53%  |
| 0x806c1    | 24        | 2.57%   |
| 0x806d1    | 20        | 2.14%   |
| 0x0a50000c | 19        | 2.04%   |
| 0x906a3    | 15        | 1.61%   |
| 0x806ec    | 15        | 1.61%   |
| 0xa0652    | 13        | 1.39%   |
| 0x306a9    | 13        | 1.39%   |
| 0x806ea    | 11        | 1.18%   |
| 0x906ea    | 10        | 1.07%   |
| 0x406e3    | 9         | 0.96%   |
| 0x40651    | 9         | 0.96%   |
| 0x0a404101 | 8         | 0.86%   |
| 0x08600104 | 8         | 0.86%   |
| 0x906e9    | 7         | 0.75%   |
| 0x08608103 | 7         | 0.75%   |
| 0x806e9    | 6         | 0.64%   |
| 0x706e5    | 6         | 0.64%   |
| 0x506e3    | 6         | 0.64%   |
| 0x306c3    | 6         | 0.64%   |
| 0x08600106 | 6         | 0.64%   |
| 0x08108109 | 6         | 0.64%   |
| 0x906a4    | 5         | 0.54%   |
| 0x306d4    | 5         | 0.54%   |
| 0x806eb    | 4         | 0.43%   |
| 0x206a7    | 4         | 0.43%   |
| 0x1067a    | 4         | 0.43%   |
| 0x806c2    | 3         | 0.32%   |
| 0x706a8    | 3         | 0.32%   |
| 0x08600103 | 3         | 0.32%   |
| 0xa0660    | 2         | 0.21%   |
| 0x08608102 | 2         | 0.21%   |
| 0x08108102 | 2         | 0.21%   |
| 0x0810100b | 2         | 0.21%   |
| 0x906ed    | 1         | 0.11%   |
| 0x906c0    | 1         | 0.11%   |
| 0x706a1    | 1         | 0.11%   |
| 0x30678    | 1         | 0.11%   |
| 0x0a50000d | 1         | 0.11%   |
| 0x0a50000b | 1         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 171       | 18.53%  |
| Unknown          | 84        | 9.1%    |
| Haswell          | 77        | 8.34%   |
| TigerLake        | 63        | 6.83%   |
| IvyBridge        | 54        | 5.85%   |
| Zen 3            | 52        | 5.63%   |
| SandyBridge      | 46        | 4.98%   |
| Skylake          | 44        | 4.77%   |
| CometLake        | 37        | 4.01%   |
| Penryn           | 36        | 3.9%    |
| Zen 2            | 35        | 3.79%   |
| IceLake          | 35        | 3.79%   |
| Broadwell        | 35        | 3.79%   |
| Zen+             | 33        | 3.58%   |
| Westmere         | 23        | 2.49%   |
| Alderlake Hybrid | 18        | 1.95%   |
| Silvermont       | 14        | 1.52%   |
| Goldmont plus    | 12        | 1.3%    |
| Excavator        | 12        | 1.3%    |
| Puma             | 8         | 0.87%   |
| Piledriver       | 8         | 0.87%   |
| Zen              | 7         | 0.76%   |
| K10 Llano        | 5         | 0.54%   |
| Core             | 4         | 0.43%   |
| Steamroller      | 2         | 0.22%   |
| K8 Hammer        | 2         | 0.22%   |
| K10              | 2         | 0.22%   |
| Tremont          | 1         | 0.11%   |
| Nehalem          | 1         | 0.11%   |
| Goldmont         | 1         | 0.11%   |
| Bobcat           | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 646       | 52.61%  |
| Nvidia | 338       | 27.52%  |
| AMD    | 244       | 19.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 58        | 4.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 51        | 4.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 43        | 3.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 42        | 3.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 41        | 3.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 38        | 3.03%   |
| AMD Renoir                                                                            | 35        | 2.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 33        | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 33        | 2.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 30        | 2.39%   |
| Intel UHD Graphics 620                                                                | 29        | 2.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 28        | 2.23%   |
| AMD Lucienne                                                                          | 28        | 2.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 27        | 2.15%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 27        | 2.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 26        | 2.07%   |
| Intel HD Graphics 620                                                                 | 26        | 2.07%   |
| Intel HD Graphics 5500                                                                | 25        | 1.99%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 24        | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 23        | 1.83%   |
| Intel HD Graphics 630                                                                 | 19        | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                   | 18        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 18        | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 1.2%    |
| AMD Rembrandt [Radeon 680M]                                                           | 15        | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 14        | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 14        | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 13        | 1.04%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 13        | 1.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 12        | 0.96%   |
| Intel HD Graphics 530                                                                 | 12        | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 12        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 10        | 0.8%    |
| Nvidia TU117M                                                                         | 10        | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 10        | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 10        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 10        | 0.8%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 9         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 8         | 0.64%   |
| Nvidia C79 [GeForce 9400M]                                                            | 8         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 405       | 43.74%  |
| Intel + Nvidia     | 215       | 23.22%  |
| 1 x AMD            | 140       | 15.12%  |
| AMD + Nvidia       | 60        | 6.48%   |
| 1 x Nvidia         | 58        | 6.26%   |
| Intel + AMD        | 26        | 2.81%   |
| 2 x AMD            | 18        | 1.94%   |
| 2 x Nvidia         | 3         | 0.32%   |
| Intel + 2 x Nvidia | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 643       | 69.36%  |
| Proprietary | 267       | 28.8%   |
| Unknown     | 17        | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 804       | 86.45%  |
| 0.01-0.5   | 32        | 3.44%   |
| 1.01-2.0   | 25        | 2.69%   |
| 3.01-4.0   | 23        | 2.47%   |
| 7.01-8.0   | 18        | 1.94%   |
| 5.01-6.0   | 16        | 1.72%   |
| 0.51-1.0   | 7         | 0.75%   |
| 2.01-3.0   | 3         | 0.32%   |
| 8.01-16.0  | 2         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 217       | 19.85%  |
| BOE                     | 161       | 14.73%  |
| Chimei Innolux          | 149       | 13.63%  |
| LG Display              | 143       | 13.08%  |
| Samsung Electronics     | 90        | 8.23%   |
| Apple                   | 52        | 4.76%   |
| Dell                    | 38        | 3.48%   |
| Sharp                   | 33        | 3.02%   |
| Goldstar                | 31        | 2.84%   |
| PANDA                   | 28        | 2.56%   |
| CSO                     | 12        | 1.1%    |
| Acer                    | 12        | 1.1%    |
| Lenovo                  | 11        | 1.01%   |
| Hewlett-Packard         | 11        | 1.01%   |
| InfoVision              | 10        | 0.91%   |
| ASUSTek Computer        | 9         | 0.82%   |
| Chi Mei Optoelectronics | 8         | 0.73%   |
| Philips                 | 6         | 0.55%   |
| AOC                     | 6         | 0.55%   |
| ViewSonic               | 5         | 0.46%   |
| TMX                     | 4         | 0.37%   |
| MSI                     | 4         | 0.37%   |
| BenQ                    | 4         | 0.37%   |
| Vizio                   | 3         | 0.27%   |
| Panasonic               | 3         | 0.27%   |
| Iiyama                  | 3         | 0.27%   |
| Ancor Communications    | 3         | 0.27%   |
| Vestel Elektronik       | 2         | 0.18%   |
| Unknown                 | 2         | 0.18%   |
| TCL                     | 2         | 0.18%   |
| Sony                    | 2         | 0.18%   |
| JDI                     | 2         | 0.18%   |
| Denver                  | 2         | 0.18%   |
| ___                     | 1         | 0.09%   |
| Valve                   | 1         | 0.09%   |
| Toshiba                 | 1         | 0.09%   |
| STA                     | 1         | 0.09%   |
| SGT                     | 1         | 0.09%   |
| Sceptre Tech            | 1         | 0.09%   |
| SAC                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 12        | 1.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.9%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 9         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.81%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 9         | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.81%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.72%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 8         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 7         | 0.63%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 7         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 6         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 5         | 0.45%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 5         | 0.45%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 5         | 0.45%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 5         | 0.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 4         | 0.36%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 4         | 0.36%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 4         | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.36%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 4         | 0.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 0.36%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.36%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                  | 4         | 0.36%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 3         | 0.27%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 3         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 494       | 48.24%  |
| 1366x768 (WXGA)    | 224       | 21.88%  |
| 3840x2160 (4K)     | 42        | 4.1%    |
| 1600x900 (HD+)     | 41        | 4%      |
| 2560x1440 (QHD)    | 38        | 3.71%   |
| 1920x1200 (WUXGA)  | 36        | 3.52%   |
| 2560x1600          | 25        | 2.44%   |
| 1440x900 (WXGA+)   | 24        | 2.34%   |
| 2880x1800          | 17        | 1.66%   |
| 1280x800 (WXGA)    | 16        | 1.56%   |
| 3440x1440          | 12        | 1.17%   |
| 2560x1080          | 6         | 0.59%   |
| 3840x2400          | 5         | 0.49%   |
| 3456x2160          | 4         | 0.39%   |
| 2256x1504          | 4         | 0.39%   |
| 2160x1440          | 4         | 0.39%   |
| 1360x768           | 4         | 0.39%   |
| 1920x540           | 3         | 0.29%   |
| 1280x1024 (SXGA)   | 3         | 0.29%   |
| 800x1280           | 2         | 0.2%    |
| 3840x1100          | 2         | 0.2%    |
| 3840x1080          | 2         | 0.2%    |
| 3200x2000          | 2         | 0.2%    |
| 3000x2000          | 2         | 0.2%    |
| 1280x720 (HD)      | 2         | 0.2%    |
| 3840x1200          | 1         | 0.1%    |
| 3200x1800 (QHD+)   | 1         | 0.1%    |
| 3120x2080          | 1         | 0.1%    |
| 3072x1920          | 1         | 0.1%    |
| 1920x515           | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1680x1050 (WSXGA+) | 1         | 0.1%    |
| 1400x1050          | 1         | 0.1%    |
| 1280x1080          | 1         | 0.1%    |
| Unknown            | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 440       | 40.26%  |
| 13      | 193       | 17.66%  |
| 14      | 121       | 11.07%  |
| 17      | 72        | 6.59%   |
| 27      | 36        | 3.29%   |
| 24      | 36        | 3.29%   |
| 23      | 31        | 2.84%   |
| 16      | 23        | 2.1%    |
| 12      | 22        | 2.01%   |
| 21      | 18        | 1.65%   |
| 34      | 15        | 1.37%   |
| 31      | 14        | 1.28%   |
| 11      | 12        | 1.1%    |
| Unknown | 10        | 0.91%   |
| 32      | 8         | 0.73%   |
| 18      | 6         | 0.55%   |
| 19      | 5         | 0.46%   |
| 84      | 3         | 0.27%   |
| 48      | 3         | 0.27%   |
| 35      | 3         | 0.27%   |
| 22      | 3         | 0.27%   |
| 20      | 3         | 0.27%   |
| 72      | 2         | 0.18%   |
| 54      | 2         | 0.18%   |
| 49      | 2         | 0.18%   |
| 40      | 2         | 0.18%   |
| 29      | 2         | 0.18%   |
| 28      | 2         | 0.18%   |
| 47      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 7       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 671       | 61.84%  |
| 201-300     | 129       | 11.89%  |
| 501-600     | 90        | 8.29%   |
| 351-400     | 82        | 7.56%   |
| 401-500     | 33        | 3.04%   |
| 601-700     | 26        | 2.4%    |
| 701-800     | 23        | 2.12%   |
| Unknown     | 10        | 0.92%   |
| 1001-1500   | 9         | 0.83%   |
| 801-900     | 6         | 0.55%   |
| 1501-2000   | 5         | 0.46%   |
| 1-100       | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 774       | 81.13%  |
| 16/10   | 132       | 13.84%  |
| 21/9    | 19        | 1.99%   |
| 3/2     | 13        | 1.36%   |
| 5/4     | 3         | 0.31%   |
| 32/9    | 3         | 0.31%   |
| Unknown | 3         | 0.31%   |
| 3.40    | 2         | 0.21%   |
| 4/3     | 1         | 0.1%    |
| 3.73    | 1         | 0.1%    |
| 3.20    | 1         | 0.1%    |
| 0.67    | 1         | 0.1%    |
| 0.62    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 441       | 40.42%  |
| 81-90          | 247       | 22.64%  |
| 201-250        | 69        | 6.32%   |
| 121-130        | 67        | 6.14%   |
| 71-80          | 63        | 5.77%   |
| 351-500        | 42        | 3.85%   |
| 301-350        | 36        | 3.3%    |
| 61-70          | 21        | 1.92%   |
| 111-120        | 20        | 1.83%   |
| 151-200        | 15        | 1.37%   |
| 51-60          | 14        | 1.28%   |
| 251-300        | 13        | 1.19%   |
| More than 1000 | 10        | 0.92%   |
| Unknown        | 10        | 0.92%   |
| 141-150        | 7         | 0.64%   |
| 501-1000       | 7         | 0.64%   |
| 131-140        | 4         | 0.37%   |
| 91-100         | 4         | 0.37%   |
| 1-40           | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 494       | 46.13%  |
| 101-120       | 268       | 25.02%  |
| 51-100        | 139       | 12.98%  |
| 161-240       | 107       | 9.99%   |
| More than 240 | 42        | 3.92%   |
| 1-50          | 11        | 1.03%   |
| Unknown       | 10        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 716       | 76.74%  |
| 2     | 165       | 17.68%  |
| 0     | 26        | 2.79%   |
| 3     | 25        | 2.68%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 510       | 34.58%  |
| Intel                                 | 482       | 32.68%  |
| Qualcomm Atheros                      | 189       | 12.81%  |
| Broadcom                              | 87        | 5.9%    |
| MediaTek                              | 46        | 3.12%   |
| Broadcom Limited                      | 39        | 2.64%   |
| Nvidia                                | 12        | 0.81%   |
| ASIX Electronics                      | 12        | 0.81%   |
| Samsung Electronics                   | 11        | 0.75%   |
| TP-Link                               | 10        | 0.68%   |
| Marvell Technology Group              | 10        | 0.68%   |
| DisplayLink                           | 9         | 0.61%   |
| Ralink                                | 6         | 0.41%   |
| Dell                                  | 6         | 0.41%   |
| Sierra Wireless                       | 4         | 0.27%   |
| NetGear                               | 4         | 0.27%   |
| Ralink Technology                     | 3         | 0.2%    |
| Qualcomm                              | 3         | 0.2%    |
| Lenovo                                | 3         | 0.2%    |
| JMicron Technology                    | 3         | 0.2%    |
| Hewlett-Packard                       | 3         | 0.2%    |
| Xiaomi                                | 2         | 0.14%   |
| OPPO Electronics                      | 2         | 0.14%   |
| OnePlus Technology (Shenzhen)         | 2         | 0.14%   |
| Huawei Technologies                   | 2         | 0.14%   |
| Ericsson Business Mobile Networks     | 2         | 0.14%   |
| ASUSTek Computer                      | 2         | 0.14%   |
| Apple                                 | 2         | 0.14%   |
| U-Blox                                | 1         | 0.07%   |
| Qualcomm Atheros Communications       | 1         | 0.07%   |
| Motorola PCS                          | 1         | 0.07%   |
| Google                                | 1         | 0.07%   |
| Fibocom                               | 1         | 0.07%   |
| D-Link                                | 1         | 0.07%   |
| Arduino SA                            | 1         | 0.07%   |
| Accton Technology                     | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 331       | 19.19%  |
| Intel Wi-Fi 6 AX200                                               | 60        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 58        | 3.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 2.72%   |
| Intel Wi-Fi 6 AX201                                               | 44        | 2.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 36        | 2.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 35        | 2.03%   |
| Intel Wireless 8265 / 8275                                        | 34        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 31        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 31        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 29        | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.62%   |
| Intel Wireless 7265                                               | 28        | 1.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 25        | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 1.45%   |
| Intel Wireless 8260                                               | 24        | 1.39%   |
| Intel Wireless 7260                                               | 24        | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 1.1%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 19        | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 15        | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 15        | 0.87%   |
| Intel Wireless-AC 9260                                            | 13        | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.7%    |
| Intel Centrino Advanced-N 6235                                    | 12        | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.64%   |
| Realtek Realtek Network controller                                | 10        | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 10        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.58%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 10        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 9         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 467       | 48.19%  |
| Qualcomm Atheros                      | 163       | 16.82%  |
| Realtek Semiconductor                 | 142       | 14.65%  |
| Broadcom                              | 74        | 7.64%   |
| MediaTek                              | 45        | 4.64%   |
| Broadcom Limited                      | 34        | 3.51%   |
| TP-Link                               | 9         | 0.93%   |
| Ralink                                | 6         | 0.62%   |
| Dell                                  | 6         | 0.62%   |
| Sierra Wireless                       | 4         | 0.41%   |
| NetGear                               | 4         | 0.41%   |
| Ralink Technology                     | 3         | 0.31%   |
| Qualcomm                              | 3         | 0.31%   |
| Hewlett-Packard                       | 2         | 0.21%   |
| Qualcomm Atheros Communications       | 1         | 0.1%    |
| Fibocom                               | 1         | 0.1%    |
| D-Link                                | 1         | 0.1%    |
| ASUSTek Computer                      | 1         | 0.1%    |
| Arduino SA                            | 1         | 0.1%    |
| Accton Technology                     | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 60        | 6.14%   |
| Intel Wi-Fi 6 AX201                                            | 44        | 4.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 36        | 3.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 35        | 3.58%   |
| Intel Wireless 8265 / 8275                                     | 34        | 3.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 31        | 3.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 31        | 3.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 30        | 3.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 30        | 3.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 29        | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 28        | 2.87%   |
| Intel Wireless 7265                                            | 28        | 2.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 25        | 2.56%   |
| Intel Wireless 8260                                            | 24        | 2.46%   |
| Intel Wireless 7260                                            | 24        | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22        | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 1.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 19        | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 1.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 16        | 1.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 15        | 1.54%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 15        | 1.54%   |
| Intel Wireless-AC 9260                                         | 13        | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 1.33%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.13%   |
| Realtek Realtek Network controller                             | 10        | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 0.82%   |
| MediaTek WLAN controller                                       | 8         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.72%   |
| Intel Wireless 3165                                            | 6         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 446       | 61.35%  |
| Intel                         | 131       | 18.02%  |
| Qualcomm Atheros              | 41        | 5.64%   |
| Broadcom                      | 31        | 4.26%   |
| Nvidia                        | 12        | 1.65%   |
| ASIX Electronics              | 12        | 1.65%   |
| Samsung Electronics           | 11        | 1.51%   |
| Marvell Technology Group      | 10        | 1.38%   |
| DisplayLink                   | 9         | 1.24%   |
| Broadcom Limited              | 5         | 0.69%   |
| Lenovo                        | 3         | 0.41%   |
| JMicron Technology            | 3         | 0.41%   |
| Xiaomi                        | 2         | 0.28%   |
| OPPO Electronics              | 2         | 0.28%   |
| OnePlus Technology (Shenzhen) | 2         | 0.28%   |
| Apple                         | 2         | 0.28%   |
| TP-Link                       | 1         | 0.14%   |
| Motorola PCS                  | 1         | 0.14%   |
| Huawei Technologies           | 1         | 0.14%   |
| Google                        | 1         | 0.14%   |
| ASUSTek Computer              | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 331       | 44.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 58        | 7.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 6.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 3.38%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 1.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 1.49%   |
| Nvidia MCP79 Ethernet                                             | 10        | 1.35%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 1.08%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.81%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.68%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.54%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 4         | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.54%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 3         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 918       | 56.74%  |
| Ethernet | 692       | 42.77%  |
| Modem    | 6         | 0.37%   |
| Unknown  | 2         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 776       | 79.75%  |
| Ethernet | 197       | 20.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 632       | 68.55%  |
| 1     | 280       | 30.37%  |
| 0     | 6         | 0.65%   |
| 3     | 4         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 652       | 70.26%  |
| Yes  | 276       | 29.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 418       | 52.18%  |
| Qualcomm Atheros Communications | 75        | 9.36%   |
| Realtek Semiconductor           | 68        | 8.49%   |
| Apple                           | 59        | 7.37%   |
| IMC Networks                    | 53        | 6.62%   |
| Lite-On Technology              | 36        | 4.49%   |
| Foxconn / Hon Hai               | 24        | 3%      |
| Broadcom                        | 23        | 2.87%   |
| Dell                            | 8         | 1%      |
| Toshiba                         | 6         | 0.75%   |
| Realtek                         | 6         | 0.75%   |
| Cambridge Silicon Radio         | 6         | 0.75%   |
| Hewlett-Packard                 | 5         | 0.62%   |
| Taiyo Yuden                     | 2         | 0.25%   |
| Ralink                          | 2         | 0.25%   |
| Opticis                         | 2         | 0.25%   |
| Foxconn International           | 2         | 0.25%   |
| USI                             | 1         | 0.12%   |
| Ralink Technology               | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| MediaTek                        | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| ASUSTek Computer                | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 118       | 14.71%  |
| Intel AX201 Bluetooth                               | 101       | 12.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 59        | 7.36%   |
| Intel AX200 Bluetooth                               | 59        | 7.36%   |
| Realtek Bluetooth Radio                             | 52        | 6.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 41        | 5.11%   |
| Intel Bluetooth Device                              | 28        | 3.49%   |
| Apple Bluetooth Host Controller                     | 28        | 3.49%   |
| Apple Bluetooth USB Host Controller                 | 26        | 3.24%   |
| IMC Networks Wireless_Device                        | 23        | 2.87%   |
| Intel AX210 Bluetooth                               | 18        | 2.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 14        | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 1.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 1.5%    |
| IMC Networks Bluetooth Device                       | 11        | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 1.37%   |
| IMC Networks Bluetooth Radio                        | 10        | 1.25%   |
| Lite-On Wireless_Device                             | 8         | 1%      |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.87%   |
| Lite-On Bluetooth Device                            | 7         | 0.87%   |
| Realtek Bluetooth Radio                             | 6         | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.37%   |
| Lite-On Bluetooth Radio                             | 3         | 0.37%   |
| IMC Networks Bluetooth USB Host Controller          | 3         | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.37%   |
| Broadcom BCM20702A0                                 | 3         | 0.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.37%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.37%   |
| Apple Bluetooth HCI                                 | 3         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 691       | 56.78%  |
| AMD                                  | 225       | 18.49%  |
| Nvidia                               | 215       | 17.67%  |
| C-Media Electronics                  | 9         | 0.74%   |
| GN Netcom                            | 8         | 0.66%   |
| Logitech                             | 5         | 0.41%   |
| Lenovo                               | 5         | 0.41%   |
| Kingston Technology                  | 5         | 0.41%   |
| Hewlett-Packard                      | 5         | 0.41%   |
| Texas Instruments                    | 4         | 0.33%   |
| Sony                                 | 4         | 0.33%   |
| Realtek Semiconductor                | 4         | 0.33%   |
| JMTek                                | 4         | 0.33%   |
| Apple                                | 4         | 0.33%   |
| SteelSeries ApS                      | 3         | 0.25%   |
| Focusrite-Novation                   | 3         | 0.25%   |
| Sennheiser Communications            | 2         | 0.16%   |
| Razer USA                            | 2         | 0.16%   |
| Plantronics                          | 2         | 0.16%   |
| Generalplus Technology               | 2         | 0.16%   |
| ASUSTek Computer                     | 2         | 0.16%   |
| Turtle Beach                         | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.08%   |
| TerraTec Electronic                  | 1         | 0.08%   |
| Samson Technologies                  | 1         | 0.08%   |
| Reloop                               | 1         | 0.08%   |
| Pioneer DJ                           | 1         | 0.08%   |
| No brand                             | 1         | 0.08%   |
| Midiplus                             | 1         | 0.08%   |
| iConnectivity                        | 1         | 0.08%   |
| Corsair                              | 1         | 0.08%   |
| Audio-Technica                       | 1         | 0.08%   |
| Astro Gaming                         | 1         | 0.08%   |
| Antlion Audio                        | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 164       | 10.95%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 92        | 6.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 86        | 5.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 63        | 4.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 62        | 4.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 43        | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 42        | 2.8%    |
| Intel 8 Series HD Audio Controller                                         | 42        | 2.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 39        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 38        | 2.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 2.34%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 35        | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 34        | 2.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 33        | 2.2%    |
| Intel Comet Lake PCH cAVS                                                  | 33        | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 29        | 1.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 26        | 1.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 26        | 1.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 24        | 1.6%    |
| Intel CM238 HD Audio Controller                                            | 24        | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 24        | 1.6%    |
| AMD FCH Azalia Controller                                                  | 23        | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 22        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 1.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 1.47%   |
| Nvidia Audio device                                                        | 19        | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 1.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 14        | 0.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 13        | 0.87%   |
| Nvidia MCP79 High Definition Audio                                         | 12        | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 0.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 12        | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 10        | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 105       | 31.44%  |
| SK hynix            | 72        | 21.56%  |
| Micron Technology   | 51        | 15.27%  |
| Kingston            | 20        | 5.99%   |
| Crucial             | 19        | 5.69%   |
| Unknown             | 8         | 2.4%    |
| Unknown             | 7         | 2.1%    |
| A-DATA Technology   | 6         | 1.8%    |
| Smart               | 5         | 1.5%    |
| Neo Forza           | 5         | 1.5%    |
| G.Skill             | 4         | 1.2%    |
| Team                | 3         | 0.9%    |
| Ramaxel Technology  | 3         | 0.9%    |
| Goldkey             | 3         | 0.9%    |
| Elpida              | 3         | 0.9%    |
| Corsair             | 3         | 0.9%    |
| PNY                 | 2         | 0.6%    |
| Nanya Technology    | 2         | 0.6%    |
| GSkill              | 2         | 0.6%    |
| Gold Key            | 2         | 0.6%    |
| Avant               | 2         | 0.6%    |
| Unknown (ABCD)      | 1         | 0.3%    |
| Unknown (8A02)      | 1         | 0.3%    |
| Timetec             | 1         | 0.3%    |
| Teikon              | 1         | 0.3%    |
| Smart Brazil        | 1         | 0.3%    |
| ChangXin Memory     | 1         | 0.3%    |
| Apacer              | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 11        | 3.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 2.27%   |
| Unknown                                                             | 8         | 2.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 1.98%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 6         | 1.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 1.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 1.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 1.42%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 5         | 1.42%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 1.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 1.13%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 4         | 1.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 4         | 1.13%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 4         | 1.13%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 1.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 1.13%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                  | 4         | 1.13%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 4         | 1.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 1.13%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 0.85%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 3         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 3         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 3         | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.85%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 3         | 0.85%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s            | 3         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 3         | 0.85%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s              | 3         | 0.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.57%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.57%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.57%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 182       | 64.08%  |
| DDR3    | 43        | 15.14%  |
| LPDDR4  | 20        | 7.04%   |
| LPDDR3  | 11        | 3.87%   |
| DDR5    | 10        | 3.52%   |
| LPDDR5  | 9         | 3.17%   |
| SDRAM   | 3         | 1.06%   |
| DDR2    | 3         | 1.06%   |
| Unknown | 3         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 238       | 81.51%  |
| Row Of Chips | 52        | 17.81%  |
| Chip         | 2         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 141       | 46.23%  |
| 4096  | 68        | 22.3%   |
| 16384 | 57        | 18.69%  |
| 32768 | 19        | 6.23%   |
| 2048  | 19        | 6.23%   |
| 1024  | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 105       | 34.31%  |
| 2667  | 63        | 20.59%  |
| 1600  | 32        | 10.46%  |
| 2400  | 19        | 6.21%   |
| 2133  | 17        | 5.56%   |
| 4800  | 12        | 3.92%   |
| 4267  | 11        | 3.59%   |
| 6400  | 10        | 3.27%   |
| 8400  | 6         | 1.96%   |
| 1333  | 5         | 1.63%   |
| 3266  | 4         | 1.31%   |
| 1334  | 4         | 1.31%   |
| 4266  | 3         | 0.98%   |
| 3733  | 3         | 0.98%   |
| 1867  | 3         | 0.98%   |
| 800   | 3         | 0.98%   |
| 2048  | 2         | 0.65%   |
| 1067  | 2         | 0.65%   |
| 4199  | 1         | 0.33%   |
| 1200  | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 40%     |
| Xerox           | 1         | 20%     |
| ICS Advent      | 1         | 20%     |
| Hewlett-Packard | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox B215                      | 1         | 20%     |
| ICS Advent Parallel Adapter     | 1         | 20%     |
| HP Ink Tank Wireless 410 series | 1         | 20%     |
| Canon PIXMA MX920 Series        | 1         | 20%     |
| Canon E400 series               | 1         | 20%     |

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
| Chicony Electronics                    | 192       | 22.91%  |
| Acer                                   | 102       | 12.17%  |
| Microdia                               | 89        | 10.62%  |
| IMC Networks                           | 89        | 10.62%  |
| Realtek Semiconductor                  | 63        | 7.52%   |
| Quanta                                 | 49        | 5.85%   |
| Sunplus Innovation Technology          | 40        | 4.77%   |
| Apple                                  | 40        | 4.77%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 2.86%   |
| Syntek                                 | 20        | 2.39%   |
| Suyin                                  | 19        | 2.27%   |
| Luxvisions Innotech Limited            | 18        | 2.15%   |
| Lite-On Technology                     | 13        | 1.55%   |
| Silicon Motion                         | 10        | 1.19%   |
| Logitech                               | 10        | 1.19%   |
| Sonix Technology                       | 9         | 1.07%   |
| SunplusIT                              | 8         | 0.95%   |
| Samsung Electronics                    | 6         | 0.72%   |
| Z-Star Microelectronics                | 5         | 0.6%    |
| Microsoft                              | 4         | 0.48%   |
| Razer USA                              | 3         | 0.36%   |
| Generalplus Technology                 | 3         | 0.36%   |
| DJKANA19IDX53W                         | 3         | 0.36%   |
| Alcor Micro                            | 3         | 0.36%   |
| Ricoh                                  | 2         | 0.24%   |
| Primax Electronics                     | 2         | 0.24%   |
| Unknown                                | 1         | 0.12%   |
| Tobii Technology AB                    | 1         | 0.12%   |
| SJ-180517-N                            | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Oculus VR                              | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| KYE Systems (Mouse Systems)            | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| Importek                               | 1         | 0.12%   |
| Goodong Industry                       | 1         | 0.12%   |
| eMPIA Technology                       | 1         | 0.12%   |
| AVerMedia Technologies                 | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 45        | 5.34%   |
| Chicony Integrated Camera                           | 40        | 4.75%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 34        | 4.04%   |
| Realtek Integrated_Webcam_HD                        | 25        | 2.97%   |
| IMC Networks Integrated Camera                      | 22        | 2.61%   |
| Chicony HD WebCam                                   | 20        | 2.38%   |
| Acer Integrated Camera                              | 19        | 2.26%   |
| Acer HD Webcam                                      | 19        | 2.26%   |
| Syntek Integrated Camera                            | 18        | 2.14%   |
| Acer BisonCam,NB Pro                                | 18        | 2.14%   |
| Chicony USB2.0 Camera                               | 15        | 1.78%   |
| Apple Built-in iSight                               | 15        | 1.78%   |
| Quanta HD User Facing                               | 12        | 1.43%   |
| Sunplus Integrated_Webcam_HD                        | 11        | 1.31%   |
| Chicony USB2.0 VGA UVC WebCam                       | 9         | 1.07%   |
| Chicony HD User Facing                              | 9         | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE                           | 9         | 1.07%   |
| Apple FaceTime HD Camera                            | 9         | 1.07%   |
| Quanta HP HD Camera                                 | 8         | 0.95%   |
| Microdia Integrated Webcam                          | 8         | 0.95%   |
| Chicony Integrated Camera (1280x720@30)             | 8         | 0.95%   |
| Realtek USB Camera                                  | 7         | 0.83%   |
| Luxvisions Innotech Limited HP HD Camera            | 7         | 0.83%   |
| Chicony USB 2.0 Camera                              | 7         | 0.83%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 0.83%   |
| Acer SunplusIT Integrated Camera                    | 7         | 0.83%   |
| Sonix USB2.0 HD UVC WebCam                          | 6         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)             | 6         | 0.71%   |
| Microdia Integrated Webcam HD                       | 6         | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 6         | 0.71%   |
| Lite-On Integrated Camera                           | 6         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 0.71%   |
| Chicony HP HD Camera                                | 6         | 0.71%   |
| Acer Lenovo EasyCamera                              | 6         | 0.71%   |
| Acer BisonCam, NB Pro                               | 6         | 0.71%   |
| Suyin 1.3M HD WebCam                                | 5         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.59%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.59%   |
| Microdia Laptop_Integrated_Webcam_HD                | 5         | 0.59%   |
| Chicony VGA WebCam                                  | 5         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 52        | 34.9%   |
| Validity Sensors                   | 37        | 24.83%  |
| Shenzhen Goodix Technology         | 31        | 20.81%  |
| LighTuning Technology              | 9         | 6.04%   |
| Elan Microelectronics              | 7         | 4.7%    |
| AuthenTec                          | 5         | 3.36%   |
| Upek                               | 3         | 2.01%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.01%   |
| HOLTEK                             | 2         | 1.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 18        | 12.08%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 10.74%  |
| Unknown                                                                    | 14        | 9.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 7.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 4.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.7%    |
| Shenzhen Goodix FingerPrint                                                | 7         | 4.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 4.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 4.03%   |
| Elan ELAN:ARM-M4                                                           | 6         | 4.03%   |
| Synaptics WBDI Device                                                      | 5         | 3.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.01%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.01%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.01%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.01%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.01%   |
| Validity Sensors VFS491                                                    | 2         | 1.34%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.34%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.34%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.34%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 1.34%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.67%   |
| Synaptics  WBDI                                                            | 1         | 0.67%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.67%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.67%   |
| AuthenTec AES2810                                                          | 1         | 0.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 31        | 51.67%  |
| Alcor Micro | 19        | 31.67%  |
| O2 Micro    | 4         | 6.67%   |
| Upek        | 2         | 3.33%   |
| Lenovo      | 2         | 3.33%   |
| OmniKey     | 1         | 1.67%   |
| Clay Logic  | 1         | 1.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 31.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 16.67%  |
| Broadcom 5880                                                                | 9         | 15%     |
| Broadcom 58200                                                               | 8         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 5%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.33%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.33%   |
| OmniKey CardMan 4321                                                         | 1         | 1.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.67%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 559       | 60.11%  |
| 1     | 289       | 31.08%  |
| 2     | 66        | 7.1%    |
| 3     | 15        | 1.61%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 142       | 31.14%  |
| Multimedia controller    | 80        | 17.54%  |
| Chipcard                 | 56        | 12.28%  |
| Net/wireless             | 51        | 11.18%  |
| Graphics card            | 50        | 10.96%  |
| Bluetooth                | 28        | 6.14%   |
| Camera                   | 16        | 3.51%   |
| Storage                  | 6         | 1.32%   |
| Sound                    | 6         | 1.32%   |
| Net/ethernet             | 5         | 1.1%    |
| Network                  | 4         | 0.88%   |
| Modem                    | 4         | 0.88%   |
| Communication controller | 4         | 0.88%   |
| Storage/ide              | 2         | 0.44%   |
| Card reader              | 2         | 0.44%   |


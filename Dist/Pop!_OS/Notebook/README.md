Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 6195

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
| Dell          | Inspiron 7720               | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
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
| System76      | Galago Pro                  | [8728b448e9](https://linux-hardware.org/?probe=8728b448e9) | Nov 05, 2022 |
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
| Acer          | Predator PH317-52           | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| HP            | Laptop 15-bw0xx             | [7231761ea1](https://linux-hardware.org/?probe=7231761ea1) | Oct 09, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Dell          | G7 7500                     | [e50429ccfa](https://linux-hardware.org/?probe=e50429ccfa) | Oct 08, 2022 |
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
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
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
| MSI           | GS73 Stealth 8RF            | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
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
| System76      | Oryx Pro                    | [3cf39a6993](https://linux-hardware.org/?probe=3cf39a6993) | Sep 24, 2022 |
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
| ASUSTek       | E402NA                      | [9d97fe89bb](https://linux-hardware.org/?probe=9d97fe89bb) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| HP            | Laptop 15s-fq1xxx           | [dc870b4e8a](https://linux-hardware.org/?probe=dc870b4e8a) | Sep 15, 2022 |
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
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
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
| Dell          | Latitude E6400              | [714643ef93](https://linux-hardware.org/?probe=714643ef93) | Aug 25, 2022 |
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
| Dell          | G7 7500                     | [981382d336](https://linux-hardware.org/?probe=981382d336) | Aug 03, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
| Alienware     | x17 R2                      | [48772fabd8](https://linux-hardware.org/?probe=48772fabd8) | Aug 02, 2022 |
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
| Dell          | Precision M6800             | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [b3d3ab37ef](https://linux-hardware.org/?probe=b3d3ab37ef) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [adb71c8acc](https://linux-hardware.org/?probe=adb71c8acc) | Jul 28, 2022 |
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
| Intel Clie... | LAPKC71F                    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
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
| Acer          | Nitro AN515-57              | [b9429f25d1](https://linux-hardware.org/?probe=b9429f25d1) | Jul 17, 2022 |
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
| HP            | ProBook 440 G2              | [a2a01affe3](https://linux-hardware.org/?probe=a2a01affe3) | Jul 09, 2022 |
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
| HP            | Victus by Laptop 16-e0xx... | [842c5317f7](https://linux-hardware.org/?probe=842c5317f7) | Jul 07, 2022 |
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
| MSI           | GE62 2QF                    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
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
| System76      | Lemur Pro                   | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| HP            | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 1146      | 25.32%  |
| Pop!_OS 21.04 | 956       | 21.12%  |
| Pop!_OS 22.04 | 922       | 20.37%  |
| Pop!_OS 20.10 | 856       | 18.91%  |
| Pop!_OS 21.10 | 599       | 13.23%  |
| Pop!_OS 19.10 | 30        | 0.66%   |
| Pop!_OS 18.04 | 7         | 0.15%   |
| Pop!_OS 19.04 | 6         | 0.13%   |
| Pop!_OS 18.10 | 4         | 0.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 4295      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 441       | 9.2%    |
| 5.8.0-7630-generic       | 381       | 7.95%   |
| 5.4.0-7634-generic       | 346       | 7.22%   |
| 5.19.0-76051900-generic  | 265       | 5.53%   |
| 5.13.0-7614-generic      | 262       | 5.47%   |
| 5.4.0-7642-generic       | 256       | 5.34%   |
| 5.17.5-76051705-generic  | 243       | 5.07%   |
| 5.8.0-7642-generic       | 242       | 5.05%   |
| 5.11.0-7614-generic      | 227       | 4.74%   |
| 5.13.0-7620-generic      | 217       | 4.53%   |
| 5.15.15-76051515-generic | 154       | 3.21%   |
| 5.16.11-76051611-generic | 138       | 2.88%   |
| 5.11.0-7612-generic      | 127       | 2.65%   |
| 5.15.5-76051505-generic  | 123       | 2.57%   |
| 5.18.10-76051810-generic | 116       | 2.42%   |
| 5.8.0-7625-generic       | 105       | 2.19%   |
| 5.17.15-76051715-generic | 105       | 2.19%   |
| 5.11.0-7633-generic      | 99        | 2.07%   |
| 5.15.8-76051508-generic  | 98        | 2.05%   |
| 5.16.19-76051619-generic | 95        | 1.98%   |
| 5.16.15-76051615-generic | 91        | 1.9%    |
| 5.4.0-7626-generic       | 84        | 1.75%   |
| 6.0.6-76060006-generic   | 76        | 1.59%   |
| 5.15.11-76051511-generic | 60        | 1.25%   |
| 6.0.2-76060002-generic   | 56        | 1.17%   |
| 5.15.23-76051523-generic | 56        | 1.17%   |
| 5.4.0-7625-generic       | 44        | 0.92%   |
| 5.4.0-7629-generic       | 35        | 0.73%   |
| 6.0.3-76060003-generic   | 23        | 0.48%   |
| 5.19.16-76051916-generic | 21        | 0.44%   |
| 5.3.0-7625-generic       | 10        | 0.21%   |
| 5.3.0-7648-generic       | 6         | 0.13%   |
| 5.11.0-051100-generic    | 6         | 0.13%   |
| 5.3.0-7642-generic       | 4         | 0.08%   |
| 5.3.0-7629-generic       | 4         | 0.08%   |
| 5.3.0-20-generic         | 4         | 0.08%   |
| 5.7.1-050701-generic     | 3         | 0.06%   |
| 4.18.0-16-generic        | 3         | 0.06%   |
| 5.9.12-xanmod1           | 2         | 0.04%   |
| 5.8.9-050809-generic     | 2         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 872       | 18.6%   |
| 5.4.0   | 744       | 15.87%  |
| 5.8.0   | 698       | 14.89%  |
| 5.13.0  | 466       | 9.94%   |
| 5.19.0  | 267       | 5.69%   |
| 5.17.5  | 246       | 5.25%   |
| 5.15.15 | 154       | 3.28%   |
| 5.16.11 | 138       | 2.94%   |
| 5.15.5  | 123       | 2.62%   |
| 5.18.10 | 116       | 2.47%   |
| 5.17.15 | 105       | 2.24%   |
| 5.15.8  | 98        | 2.09%   |
| 5.16.19 | 95        | 2.03%   |
| 5.16.15 | 91        | 1.94%   |
| 6.0.6   | 76        | 1.62%   |
| 5.15.11 | 60        | 1.28%   |
| 6.0.2   | 57        | 1.22%   |
| 5.15.23 | 56        | 1.19%   |
| 5.3.0   | 32        | 0.68%   |
| 6.0.3   | 23        | 0.49%   |
| 5.19.16 | 21        | 0.45%   |
| 5.0.0   | 6         | 0.13%   |
| 4.18.0  | 6         | 0.13%   |
| 5.7.0   | 4         | 0.09%   |
| 5.8.6   | 3         | 0.06%   |
| 5.8.11  | 3         | 0.06%   |
| 5.7.1   | 3         | 0.06%   |
| 5.15.0  | 3         | 0.06%   |
| 5.14.0  | 3         | 0.06%   |
| 5.12.14 | 3         | 0.06%   |
| 5.10.0  | 3         | 0.06%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |
| 5.9.12  | 2         | 0.04%   |
| 5.8.9   | 2         | 0.04%   |
| 5.8.1   | 2         | 0.04%   |
| 5.7.15  | 2         | 0.04%   |
| 5.6.7   | 2         | 0.04%   |
| 5.6.16  | 2         | 0.04%   |
| 5.15.4  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 878       | 18.85%  |
| 5.4     | 745       | 16%     |
| 5.8     | 712       | 15.29%  |
| 5.15    | 489       | 10.5%   |
| 5.13    | 477       | 10.24%  |
| 5.17    | 350       | 7.52%   |
| 5.16    | 322       | 6.91%   |
| 5.19    | 289       | 6.21%   |
| 6.0     | 158       | 3.39%   |
| 5.18    | 120       | 2.58%   |
| 5.3     | 32        | 0.69%   |
| 5.10    | 18        | 0.39%   |
| 5.12    | 13        | 0.28%   |
| 5.7     | 11        | 0.24%   |
| 5.14    | 11        | 0.24%   |
| 5.9     | 9         | 0.19%   |
| 5.6     | 7         | 0.15%   |
| 4.18    | 7         | 0.15%   |
| 5.0     | 6         | 0.13%   |
| 4.15    | 2         | 0.04%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4295      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4156      | 96.2%   |
| KDE5            | 37        | 0.86%   |
| Unknown         | 36        | 0.83%   |
| KDE             | 25        | 0.58%   |
| X-Cinnamon      | 15        | 0.35%   |
| GNOME Flashback | 10        | 0.23%   |
| XFCE            | 9         | 0.21%   |
| MATE            | 8         | 0.19%   |
| LXQt            | 8         | 0.19%   |
| Cinnamon        | 6         | 0.14%   |
| Unity           | 4         | 0.09%   |
| Budgie          | 4         | 0.09%   |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4160      | 96.39%  |
| Wayland | 135       | 3.13%   |
| Unknown | 14        | 0.32%   |
| Tty     | 7         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3297      | 76%     |
| GDM     | 772       | 17.8%   |
| GDM3    | 257       | 5.92%   |
| SDDM    | 6         | 0.14%   |
| TDM     | 5         | 0.12%   |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2477      | 57.32%  |
| pt_BR   | 327       | 7.57%   |
| en_GB   | 314       | 7.27%   |
| de_DE   | 184       | 4.26%   |
| C       | 104       | 2.41%   |
| en_AU   | 91        | 2.11%   |
| es_ES   | 90        | 2.08%   |
| fr_FR   | 88        | 2.04%   |
| it_IT   | 87        | 2.01%   |
| en_CA   | 82        | 1.9%    |
| ru_RU   | 59        | 1.37%   |
| Unknown | 48        | 1.11%   |
| pt_PT   | 38        | 0.88%   |
| pl_PL   | 38        | 0.88%   |
| sv_SE   | 28        | 0.65%   |
| en_IN   | 25        | 0.58%   |
| nl_NL   | 18        | 0.42%   |
| nb_NO   | 16        | 0.37%   |
| en_ZA   | 16        | 0.37%   |
| fi_FI   | 15        | 0.35%   |
| es_MX   | 15        | 0.35%   |
| tr_TR   | 11        | 0.25%   |
| es_AR   | 10        | 0.23%   |
| fr_CA   | 9         | 0.21%   |
| hr_HR   | 8         | 0.19%   |
| en_NZ   | 8         | 0.19%   |
| en_DK   | 8         | 0.19%   |
| hu_HU   | 7         | 0.16%   |
| en_IE   | 7         | 0.16%   |
| da_DK   | 7         | 0.16%   |
| ro_RO   | 6         | 0.14%   |
| es_CL   | 6         | 0.14%   |
| cs_CZ   | 6         | 0.14%   |
| sk_SK   | 5         | 0.12%   |
| de_CH   | 5         | 0.12%   |
| zh_CN   | 4         | 0.09%   |
| nl_BE   | 4         | 0.09%   |
| es_CO   | 4         | 0.09%   |
| zh_TW   | 3         | 0.07%   |
| es_PE   | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3025      | 69.33%  |
| EFI  | 1338      | 30.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4123      | 95.71%  |
| Btrfs   | 100       | 2.32%   |
| Overlay | 61        | 1.42%   |
| Xfs     | 17        | 0.39%   |
| Unknown | 7         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3269      | 75.44%  |
| GPT     | 965       | 22.27%  |
| MBR     | 99        | 2.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4199      | 97.49%  |
| Yes       | 108       | 2.51%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3921      | 90.89%  |
| Yes       | 393       | 9.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 818       | 19.05%  |
| Dell                   | 768       | 17.88%  |
| Hewlett-Packard        | 579       | 13.48%  |
| ASUSTek Computer       | 496       | 11.55%  |
| Acer                   | 347       | 8.08%   |
| Apple                  | 241       | 5.61%   |
| System76               | 161       | 3.75%   |
| MSI                    | 147       | 3.42%   |
| Toshiba                | 89        | 2.07%   |
| Samsung Electronics    | 80        | 1.86%   |
| HUAWEI                 | 52        | 1.21%   |
| Sony                   | 45        | 1.05%   |
| Notebook               | 41        | 0.95%   |
| Google                 | 33        | 0.77%   |
| Alienware              | 33        | 0.77%   |
| Fujitsu                | 26        | 0.61%   |
| Positivo               | 24        | 0.56%   |
| Razer                  | 20        | 0.47%   |
| PC Specialist          | 16        | 0.37%   |
| Gigabyte Technology    | 15        | 0.35%   |
| Timi                   | 14        | 0.33%   |
| TUXEDO                 | 11        | 0.26%   |
| Medion                 | 11        | 0.26%   |
| LG Electronics         | 11        | 0.26%   |
| Framework              | 10        | 0.23%   |
| Unknown                | 10        | 0.23%   |
| Packard Bell           | 9         | 0.21%   |
| GPU Company            | 9         | 0.21%   |
| Eluktronics            | 7         | 0.16%   |
| Avell High Performance | 7         | 0.16%   |
| Teclast                | 6         | 0.14%   |
| Panasonic              | 6         | 0.14%   |
| Intel                  | 6         | 0.14%   |
| Gateway                | 6         | 0.14%   |
| Clevo                  | 5         | 0.12%   |
| Chuwi                  | 5         | 0.12%   |
| SLIMBOOK               | 4         | 0.09%   |
| Schenker               | 4         | 0.09%   |
| Quanta                 | 4         | 0.09%   |
| MOTILE                 | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 41        | 0.95%   |
| System76 Lemur Pro                        | 34        | 0.79%   |
| Dell XPS 15 7590                          | 29        | 0.68%   |
| Apple MacBookPro9,2                       | 22        | 0.51%   |
| Unknown                                   | 21        | 0.49%   |
| System76 Galago Pro                       | 20        | 0.47%   |
| HP Pavilion Notebook                      | 19        | 0.44%   |
| Dell XPS 15 9500                          | 19        | 0.44%   |
| System76 Gazelle                          | 18        | 0.42%   |
| System76 Darter Pro                       | 16        | 0.37%   |
| Apple MacBookPro8,1                       | 16        | 0.37%   |
| HP Pavilion 15                            | 15        | 0.35%   |
| HP Notebook                               | 14        | 0.33%   |
| Dell XPS 15 9560                          | 14        | 0.33%   |
| Apple MacBookPro12,1                      | 14        | 0.33%   |
| Apple MacBookAir7,2                       | 14        | 0.33%   |
| Apple MacBookAir6,2                       | 14        | 0.33%   |
| HP Pavilion dv6                           | 13        | 0.3%    |
| Dell Latitude E6420                       | 13        | 0.3%    |
| Lenovo IdeaPad S145-15API 81V7            | 12        | 0.28%   |
| Dell XPS 15 9570                          | 12        | 0.28%   |
| Apple MacBookPro7,1                       | 12        | 0.28%   |
| Dell XPS 17 9700                          | 11        | 0.26%   |
| Dell XPS 13 9380                          | 11        | 0.26%   |
| Apple MacBookPro5,5                       | 11        | 0.26%   |
| Acer Aspire E5-575G                       | 11        | 0.26%   |
| HP Pavilion g6                            | 10        | 0.23%   |
| Dell Inspiron N5110                       | 10        | 0.23%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 10        | 0.23%   |
| Samsung 340XAA/350XAA/550XAA              | 9         | 0.21%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 9         | 0.21%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY      | 9         | 0.21%   |
| HP Pavilion Laptop 15-cw1xxx              | 9         | 0.21%   |
| Framework Laptop                          | 9         | 0.21%   |
| Dell XPS 13 9310                          | 9         | 0.21%   |
| Dell Latitude E7470                       | 9         | 0.21%   |
| Dell Latitude E7240                       | 9         | 0.21%   |
| Dell Inspiron 3542                        | 9         | 0.21%   |
| Dell Inspiron 3521                        | 9         | 0.21%   |
| Acer Aspire A315-42                       | 9         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 406       | 9.45%   |
| Dell Inspiron      | 256       | 5.96%   |
| Acer Aspire        | 243       | 5.66%   |
| Lenovo IdeaPad     | 225       | 5.24%   |
| Dell Latitude      | 182       | 4.24%   |
| Dell XPS           | 167       | 3.89%   |
| HP Pavilion        | 146       | 3.4%    |
| HP EliteBook       | 88        | 2.05%   |
| HP Laptop          | 85        | 1.98%   |
| Toshiba Satellite  | 77        | 1.79%   |
| ASUS ROG           | 72        | 1.68%   |
| ASUS VivoBook      | 71        | 1.65%   |
| HP ProBook         | 69        | 1.61%   |
| Lenovo Legion      | 59        | 1.37%   |
| Dell Precision     | 52        | 1.21%   |
| Dell Vostro        | 45        | 1.05%   |
| Acer Nitro         | 42        | 0.98%   |
| System76 Oryx      | 41        | 0.95%   |
| System76 Lemur     | 37        | 0.86%   |
| ASUS ASUS          | 37        | 0.86%   |
| ASUS TUF           | 30        | 0.7%    |
| Apple MacBookPro9  | 29        | 0.68%   |
| HP ENVY            | 28        | 0.65%   |
| Apple MacBookPro11 | 28        | 0.65%   |
| Acer Swift         | 28        | 0.65%   |
| ASUS ZenBook       | 27        | 0.63%   |
| HP OMEN            | 25        | 0.58%   |
| System76 Galago    | 23        | 0.54%   |
| Apple MacBookPro8  | 23        | 0.54%   |
| Apple MacBookPro5  | 23        | 0.54%   |
| Lenovo ThinkBook   | 21        | 0.49%   |
| Unknown            | 21        | 0.49%   |
| System76 Gazelle   | 20        | 0.47%   |
| Razer Blade        | 20        | 0.47%   |
| Fujitsu LIFEBOOK   | 20        | 0.47%   |
| Lenovo Yoga        | 17        | 0.4%    |
| HP ZBook           | 17        | 0.4%    |
| System76 Darter    | 16        | 0.37%   |
| Apple MacBookAir6  | 16        | 0.37%   |
| HP Compaq          | 15        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 570       | 13.27%  |
| 2020    | 530       | 12.34%  |
| 2018    | 413       | 9.62%   |
| 2021    | 399       | 9.29%   |
| 2012    | 319       | 7.43%   |
| 2013    | 278       | 6.47%   |
| 2017    | 276       | 6.43%   |
| 2015    | 264       | 6.15%   |
| 2011    | 263       | 6.12%   |
| 2016    | 237       | 5.52%   |
| 2014    | 214       | 4.98%   |
| 2010    | 179       | 4.17%   |
| 2009    | 112       | 2.61%   |
| 2008    | 102       | 2.37%   |
| 2022    | 92        | 2.14%   |
| 2007    | 34        | 0.79%   |
| 2006    | 9         | 0.21%   |
| Unknown | 2         | 0.05%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4295      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4292      | 99.93%  |
| Enabled  | 3         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4164      | 96.95%  |
| Yes  | 131       | 3.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1281      | 29.6%   |
| 16.01-24.0  | 970       | 22.41%  |
| 8.01-16.0   | 788       | 18.21%  |
| 3.01-4.0    | 669       | 15.46%  |
| 32.01-64.0  | 388       | 8.96%   |
| 64.01-256.0 | 84        | 1.94%   |
| 1.01-2.0    | 66        | 1.52%   |
| 24.01-32.0  | 50        | 1.16%   |
| 2.01-3.0    | 32        | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1527      | 32.76%  |
| 1.01-2.0   | 1269      | 27.23%  |
| 3.01-4.0   | 847       | 18.17%  |
| 4.01-8.0   | 794       | 17.03%  |
| 8.01-16.0  | 187       | 4.01%   |
| 16.01-24.0 | 21        | 0.45%   |
| 0.51-1.0   | 10        | 0.21%   |
| 24.01-32.0 | 5         | 0.11%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3030      | 69.37%  |
| 2      | 1149      | 26.3%   |
| 3      | 143       | 3.27%   |
| 0      | 20        | 0.46%   |
| 4      | 18        | 0.41%   |
| 5      | 6         | 0.14%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3050      | 70.8%   |
| Yes       | 1258      | 29.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3452      | 79.98%  |
| No        | 864       | 20.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4247      | 98.81%  |
| No        | 51        | 1.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3631      | 83.78%  |
| No        | 703       | 16.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1140      | 26.43%  |
| Brazil       | 458       | 10.62%  |
| Germany      | 263       | 6.1%    |
| UK           | 193       | 4.47%   |
| India        | 186       | 4.31%   |
| Canada       | 153       | 3.55%   |
| Italy        | 138       | 3.2%    |
| France       | 129       | 2.99%   |
| Australia    | 98        | 2.27%   |
| Netherlands  | 89        | 2.06%   |
| Russia       | 77        | 1.78%   |
| Sweden       | 73        | 1.69%   |
| Spain        | 69        | 1.6%    |
| Poland       | 63        | 1.46%   |
| Mexico       | 63        | 1.46%   |
| Portugal     | 62        | 1.44%   |
| Romania      | 51        | 1.18%   |
| Switzerland  | 44        | 1.02%   |
| Norway       | 44        | 1.02%   |
| South Africa | 42        | 0.97%   |
| Turkey       | 37        | 0.86%   |
| Finland      | 35        | 0.81%   |
| Greece       | 34        | 0.79%   |
| Indonesia    | 33        | 0.76%   |
| Argentina    | 33        | 0.76%   |
| Philippines  | 32        | 0.74%   |
| Belgium      | 32        | 0.74%   |
| Denmark      | 30        | 0.7%    |
| Austria      | 28        | 0.65%   |
| New Zealand  | 25        | 0.58%   |
| Chile        | 23        | 0.53%   |
| Croatia      | 22        | 0.51%   |
| Malaysia     | 19        | 0.44%   |
| Hungary      | 19        | 0.44%   |
| Colombia     | 19        | 0.44%   |
| Czechia      | 18        | 0.42%   |
| Vietnam      | 17        | 0.39%   |
| Ireland      | 17        | 0.39%   |
| Ukraine      | 16        | 0.37%   |
| Japan        | 16        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 50        | 1.11%   |
| Bengaluru      | 29        | 0.65%   |
| Milan          | 27        | 0.6%    |
| Brisbane       | 26        | 0.58%   |
| Sydney         | 24        | 0.53%   |
| Rio de Janeiro | 24        | 0.53%   |
| Dallas         | 23        | 0.51%   |
| Paris          | 22        | 0.49%   |
| Moscow         | 20        | 0.45%   |
| London         | 20        | 0.45%   |
| Bucharest      | 20        | 0.45%   |
| Vienna         | 19        | 0.42%   |
| Melbourne      | 19        | 0.42%   |
| Berlin         | 19        | 0.42%   |
| Athens         | 19        | 0.42%   |
| Rome           | 18        | 0.4%    |
| New York       | 18        | 0.4%    |
| Zagreb         | 17        | 0.38%   |
| Madrid         | 17        | 0.38%   |
| Helsinki       | 17        | 0.38%   |
| Amsterdam      | 17        | 0.38%   |
| Warsaw         | 16        | 0.36%   |
| Istanbul       | 16        | 0.36%   |
| Los Angeles    | 15        | 0.33%   |
| Johannesburg   | 15        | 0.33%   |
| Zurich         | 14        | 0.31%   |
| Toronto        | 14        | 0.31%   |
| Stockholm      | 14        | 0.31%   |
| Mexico City    | 14        | 0.31%   |
| Singapore      | 13        | 0.29%   |
| Oslo           | 13        | 0.29%   |
| Fortaleza      | 13        | 0.29%   |
| Brooklyn       | 13        | 0.29%   |
| Auckland       | 13        | 0.29%   |
| St Petersburg  | 12        | 0.27%   |
| Sofia          | 12        | 0.27%   |
| Jakarta        | 12        | 0.27%   |
| Hyderabad      | 12        | 0.27%   |
| Edmonton       | 12        | 0.27%   |
| Chicago        | 12        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 995       | 1325   | 17.98%  |
| WDC                            | 593       | 674    | 10.72%  |
| Seagate                        | 555       | 652    | 10.03%  |
| SanDisk                        | 394       | 511    | 7.12%   |
| Toshiba                        | 370       | 434    | 6.69%   |
| Kingston                       | 304       | 357    | 5.49%   |
| Unknown                        | 264       | 321    | 4.77%   |
| SK hynix                       | 260       | 334    | 4.7%    |
| Crucial                        | 194       | 225    | 3.51%   |
| Intel                          | 176       | 218    | 3.18%   |
| HGST                           | 169       | 194    | 3.05%   |
| Micron Technology              | 140       | 154    | 2.53%   |
| Apple                          | 115       | 122    | 2.08%   |
| Hitachi                        | 90        | 98     | 1.63%   |
| A-DATA Technology              | 83        | 99     | 1.5%    |
| Phison                         | 72        | 89     | 1.3%    |
| PNY                            | 42        | 48     | 0.76%   |
| China                          | 42        | 47     | 0.76%   |
| LITEON                         | 39        | 45     | 0.7%    |
| Silicon Motion                 | 37        | 45     | 0.67%   |
| KIOXIA                         | 32        | 38     | 0.58%   |
| Transcend                      | 30        | 34     | 0.54%   |
| Micron/Crucial Technology      | 30        | 40     | 0.54%   |
| LITEONIT                       | 26        | 34     | 0.47%   |
| ADATA Technology               | 21        | 30     | 0.38%   |
| Fujitsu                        | 18        | 19     | 0.33%   |
| Team                           | 17        | 21     | 0.31%   |
| SPCC                           | 17        | 18     | 0.31%   |
| JMicron Technology             | 16        | 22     | 0.29%   |
| KingSpec                       | 14        | 16     | 0.25%   |
| Union Memory (Shenzhen)        | 13        | 16     | 0.23%   |
| Solid State Storage Technology | 12        | 15     | 0.22%   |
| Patriot                        | 12        | 12     | 0.22%   |
| OCZ                            | 12        | 12     | 0.22%   |
| Corsair                        | 12        | 14     | 0.22%   |
| Hewlett-Packard                | 11        | 13     | 0.2%    |
| Unknown                        | 10        | 11     | 0.18%   |
| UMIS                           | 9         | 9      | 0.16%   |
| Netac                          | 9         | 10     | 0.16%   |
| Lexar                          | 9         | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 95        | 1.64%   |
| Samsung NVMe SSD Drive 512GB           | 80        | 1.38%   |
| Kingston SA400S37240G 240GB SSD        | 80        | 1.38%   |
| HGST HTS721010A9E630 1TB               | 73        | 1.26%   |
| Unknown MMC Card  64GB                 | 65        | 1.12%   |
| Samsung NVMe SSD Drive 1TB             | 64        | 1.1%    |
| SK hynix NVMe SSD Drive 512GB          | 59        | 1.02%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 57        | 0.98%   |
| Toshiba MQ01ABD100 1TB                 | 56        | 0.97%   |
| SanDisk NVMe SSD Drive 512GB           | 52        | 0.9%    |
| Samsung NVMe SSD Drive 500GB           | 52        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 51        | 0.88%   |
| Unknown MMC Card  32GB                 | 47        | 0.81%   |
| Intel NVMe SSD Drive 512GB             | 47        | 0.81%   |
| Toshiba MQ04ABF100 1TB                 | 42        | 0.73%   |
| Samsung NVMe SSD Drive 1024GB          | 40        | 0.69%   |
| WDC WD10SPZX-24Z10 1TB                 | 37        | 0.64%   |
| SanDisk NVMe SSD Drive 1TB             | 36        | 0.62%   |
| SanDisk NVMe SSD Drive 256GB           | 35        | 0.6%    |
| Seagate ST9500325AS 500GB              | 34        | 0.59%   |
| Samsung SSD 860 EVO 500GB              | 33        | 0.57%   |
| Seagate ST1000LM049-2GH172 1TB         | 32        | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB               | 31        | 0.54%   |
| SK hynix NVMe SSD Drive 1024GB         | 31        | 0.54%   |
| Kingston SA400S37480G 480GB SSD        | 30        | 0.52%   |
| SK hynix NVMe SSD Drive 256GB          | 29        | 0.5%    |
| Toshiba NVMe SSD Drive 512GB           | 28        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB        | 28        | 0.48%   |
| SanDisk NVMe SSD Drive 500GB           | 28        | 0.48%   |
| Samsung SSD 850 EVO 250GB              | 28        | 0.48%   |
| Unknown MMC Card  128GB                | 27        | 0.47%   |
| Crucial CT500MX500SSD1 500GB           | 27        | 0.47%   |
| Samsung NVMe SSD Drive 2TB             | 26        | 0.45%   |
| Micron NVMe SSD Drive 512GB            | 26        | 0.45%   |
| Kingston SA400S37120G 120GB SSD        | 26        | 0.45%   |
| HGST HTS541010A9E680 1TB               | 26        | 0.45%   |
| Samsung SSD 860 EVO 1TB                | 25        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB           | 24        | 0.41%   |
| Samsung SSD 850 EVO 500GB              | 24        | 0.41%   |
| Crucial CT240BX500SSD1 240GB           | 24        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 531       | 612    | 35.78%  |
| WDC                 | 367       | 401    | 24.73%  |
| Toshiba             | 228       | 256    | 15.36%  |
| HGST                | 169       | 194    | 11.39%  |
| Hitachi             | 90        | 98     | 6.06%   |
| Samsung Electronics | 28        | 29     | 1.89%   |
| Unknown             | 22        | 24     | 1.48%   |
| Fujitsu             | 18        | 19     | 1.21%   |
| Apple               | 15        | 15     | 1.01%   |
| ASMT                | 5         | 6      | 0.34%   |
| JMicron Technology  | 2         | 5      | 0.13%   |
| Intenso             | 2         | 2      | 0.13%   |
| SABRENT             | 1         | 2      | 0.07%   |
| RSH-339             | 1         | 1      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| HGST HDN            | 1         | 1      | 0.07%   |
| DAS                 | 1         | 4      | 0.07%   |
| Asm                 | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 417       | 536    | 21.76%  |
| Kingston            | 234       | 260    | 12.21%  |
| SanDisk             | 196       | 237    | 10.23%  |
| Crucial             | 179       | 210    | 9.34%   |
| WDC                 | 123       | 148    | 6.42%   |
| Apple               | 85        | 89     | 4.44%   |
| A-DATA Technology   | 58        | 68     | 3.03%   |
| SK hynix            | 49        | 57     | 2.56%   |
| Micron Technology   | 49        | 52     | 2.56%   |
| Toshiba             | 47        | 57     | 2.45%   |
| PNY                 | 41        | 47     | 2.14%   |
| China               | 41        | 46     | 2.14%   |
| Intel               | 39        | 42     | 2.04%   |
| LITEON              | 37        | 43     | 1.93%   |
| Transcend           | 29        | 33     | 1.51%   |
| LITEONIT            | 26        | 34     | 1.36%   |
| SPCC                | 15        | 16     | 0.78%   |
| Seagate             | 14        | 15     | 0.73%   |
| KingSpec            | 13        | 15     | 0.68%   |
| Patriot             | 12        | 12     | 0.63%   |
| OCZ                 | 12        | 12     | 0.63%   |
| Team                | 11        | 15     | 0.57%   |
| JMicron Technology  | 9         | 10     | 0.47%   |
| Corsair             | 9         | 10     | 0.47%   |
| Netac               | 8         | 9      | 0.42%   |
| Lexar               | 8         | 8      | 0.42%   |
| Hewlett-Packard     | 8         | 10     | 0.42%   |
| KingDian            | 7         | 8      | 0.37%   |
| Dogfish             | 6         | 8      | 0.31%   |
| BHT                 | 6         | 6      | 0.31%   |
| Apacer              | 6         | 8      | 0.31%   |
| TO Exter            | 5         | 5      | 0.26%   |
| Plextor             | 5         | 7      | 0.26%   |
| Intenso             | 5         | 5      | 0.26%   |
| GOODRAM             | 5         | 6      | 0.26%   |
| Mushkin             | 4         | 4      | 0.21%   |
| Maxtor              | 4         | 4      | 0.21%   |
| Gigabyte Technology | 4         | 6      | 0.21%   |
| FORESEE             | 4         | 5      | 0.21%   |
| Unknown             | 3         | 3      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1781      | 2252   | 33.98%  |
| NVMe    | 1735      | 2414   | 33.1%   |
| HDD     | 1439      | 1672   | 27.45%  |
| MMC     | 216       | 261    | 4.12%   |
| Unknown | 71        | 92     | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2815      | 3783   | 56.85%  |
| NVMe | 1731      | 2404   | 34.96%  |
| MMC  | 216       | 261    | 4.36%   |
| SAS  | 190       | 243    | 3.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2037      | 2574   | 64.18%  |
| 0.51-1.0   | 1030      | 1213   | 32.45%  |
| 1.01-2.0   | 91        | 116    | 2.87%   |
| 4.01-10.0  | 7         | 10     | 0.22%   |
| 3.01-4.0   | 3         | 4      | 0.09%   |
| 2.01-3.0   | 3         | 3      | 0.09%   |
| 10.01-20.0 | 3         | 4      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1514      | 34.21%  |
| 251-500        | 1245      | 28.14%  |
| 501-1000       | 793       | 17.92%  |
| 1001-2000      | 297       | 6.71%   |
| 51-100         | 226       | 5.11%   |
| 21-50          | 115       | 2.6%    |
| 1-20           | 99        | 2.24%   |
| 2001-3000      | 61        | 1.38%   |
| More than 3000 | 47        | 1.06%   |
| Unknown        | 28        | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1877      | 40.45%  |
| 21-50          | 1002      | 21.59%  |
| 101-250        | 605       | 13.04%  |
| 51-100         | 586       | 12.63%  |
| 251-500        | 297       | 6.4%    |
| 501-1000       | 163       | 3.51%   |
| 1001-2000      | 58        | 1.25%   |
| Unknown        | 28        | 0.6%    |
| More than 3000 | 14        | 0.3%    |
| 2001-3000      | 10        | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 5         | 8      | 4.9%    |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 3.92%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.92%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.94%   |
| Seagate ST1000LX015-1U7172 1TB           | 3         | 3      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.94%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.94%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.94%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.96%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.96%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.96%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.96%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.96%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.98%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.98%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.98%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.98%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.98%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.98%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.98%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.98%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.98%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.98%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.98%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.98%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 0.98%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.98%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.98%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 0.98%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.98%   |
| Toshiba MK5059GSXP 500GB                 | 1         | 1      | 0.98%   |
| Toshiba MK2035GSS 200GB                  | 1         | 1      | 0.98%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 0.98%   |
| Team TM8FP4004T 4TB                      | 1         | 1      | 0.98%   |
| SK hynix SC210 mSATA 256GB SSD           | 1         | 2      | 0.98%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 1         | 1      | 0.98%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 0.98%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 1         | 1      | 0.98%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 26     | 24.51%  |
| WDC                 | 13        | 13     | 12.75%  |
| HGST                | 12        | 15     | 11.76%  |
| Toshiba             | 9         | 10     | 8.82%   |
| SK hynix            | 6         | 7      | 5.88%   |
| Hitachi             | 6         | 8      | 5.88%   |
| Samsung Electronics | 5         | 5      | 4.9%    |
| Crucial             | 5         | 5      | 4.9%    |
| Micron Technology   | 4         | 4      | 3.92%   |
| Kingston            | 4         | 4      | 3.92%   |
| A-DATA Technology   | 4         | 4      | 3.92%   |
| Intel               | 3         | 3      | 2.94%   |
| SanDisk             | 2         | 2      | 1.96%   |
| Team                | 1         | 1      | 0.98%   |
| Lexar               | 1         | 1      | 0.98%   |
| Leven               | 1         | 1      | 0.98%   |
| China               | 1         | 1      | 0.98%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 26     | 40.32%  |
| WDC     | 12        | 12     | 19.35%  |
| HGST    | 12        | 15     | 19.35%  |
| Toshiba | 7         | 7      | 11.29%  |
| Hitachi | 6         | 8      | 9.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 68     | 60.78%  |
| SSD  | 27        | 29     | 26.47%  |
| NVMe | 13        | 13     | 12.75%  |

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
| Detected | 3332      | 5165   | 74.21%  |
| Works    | 1055      | 1415   | 23.5%   |
| Malfunc  | 102       | 110    | 2.27%   |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2929      | 54.58%  |
| Samsung Electronics              | 637       | 11.87%  |
| AMD                              | 544       | 10.14%  |
| SanDisk                          | 295       | 5.5%    |
| SK hynix                         | 210       | 3.91%   |
| Toshiba America Info Systems     | 103       | 1.92%   |
| Micron Technology                | 91        | 1.7%    |
| Phison Electronics               | 82        | 1.53%   |
| Kingston Technology Company      | 73        | 1.36%   |
| Nvidia                           | 71        | 1.32%   |
| ADATA Technology                 | 47        | 0.88%   |
| Silicon Motion                   | 44        | 0.82%   |
| Micron/Crucial Technology        | 41        | 0.76%   |
| KIOXIA                           | 36        | 0.67%   |
| Solid State Storage Technology   | 29        | 0.54%   |
| Union Memory (Shenzhen)          | 28        | 0.52%   |
| Marvell Technology Group         | 17        | 0.32%   |
| Realtek Semiconductor            | 16        | 0.3%    |
| Apple                            | 15        | 0.28%   |
| Seagate Technology               | 11        | 0.2%    |
| Silicon Integrated Systems [SiS] | 8         | 0.15%   |
| Shenzhen Longsys Electronics     | 7         | 0.13%   |
| Lite-On Technology               | 7         | 0.13%   |
| Lenovo                           | 6         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| JMicron Technology               | 4         | 0.07%   |
| ASMedia Technology               | 3         | 0.06%   |
| INNOGRIT                         | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 515       | 9.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 359       | 6.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 348       | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 312       | 5.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 282       | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 239       | 4.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 225       | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 182       | 3.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 145       | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 123       | 2.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 109       | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 106       | 1.89%   |
| Samsung NVMe SSD Controller 980                                                | 98        | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 94        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 92        | 1.64%   |
| Micron Non-Volatile memory controller                                          | 91        | 1.62%   |
| Intel SSD 660P Series                                                          | 82        | 1.46%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 81        | 1.44%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 77        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 77        | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 76        | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 74        | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 63        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 59        | 1.05%   |
| SanDisk Non-Volatile memory controller                                         | 53        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 48        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 46        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 46        | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 46        | 0.82%   |
| SK hynix Non-Volatile memory controller                                        | 44        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 43        | 0.77%   |
| Nvidia MCP79 AHCI Controller                                                   | 41        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 41        | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 39        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 38        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 37        | 0.66%   |
| Samsung Electronics SATA controller                                            | 36        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 34        | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 33        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3092      | 57.39%  |
| NVMe | 1729      | 32.09%  |
| RAID | 416       | 7.72%   |
| IDE  | 151       | 2.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3513      | 81.79%  |
| AMD    | 782       | 18.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 111       | 2.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 90        | 2.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 87        | 2.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 76        | 1.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 73        | 1.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 64        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 63        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 62        | 1.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 62        | 1.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 61        | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 60        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 59        | 1.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 51        | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 49        | 1.14%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 47        | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 45        | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 44        | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 39        | 0.91%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 38        | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 36        | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 36        | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 35        | 0.81%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 32        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 32        | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 32        | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 32        | 0.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 29        | 0.67%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 28        | 0.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 28        | 0.65%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 27        | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 26        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 26        | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.61%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 26        | 0.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 26        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1298      | 30.22%  |
| Intel Core i5           | 1112      | 25.89%  |
| Other                   | 309       | 7.19%   |
| Intel Core i3           | 273       | 6.36%   |
| AMD Ryzen 5             | 222       | 5.17%   |
| AMD Ryzen 7             | 204       | 4.75%   |
| Intel Core 2 Duo        | 161       | 3.75%   |
| Intel Celeron           | 143       | 3.33%   |
| Intel Pentium           | 54        | 1.26%   |
| AMD Ryzen 3             | 54        | 1.26%   |
| AMD Ryzen 9             | 49        | 1.14%   |
| Intel Core i9           | 48        | 1.12%   |
| AMD A6                  | 47        | 1.09%   |
| Intel Pentium Dual-Core | 31        | 0.72%   |
| AMD A8                  | 31        | 0.72%   |
| AMD A10                 | 27        | 0.63%   |
| AMD A4                  | 24        | 0.56%   |
| AMD Ryzen 7 PRO         | 22        | 0.51%   |
| Intel Atom              | 19        | 0.44%   |
| Intel Core 2            | 16        | 0.37%   |
| Intel Pentium Dual      | 13        | 0.3%    |
| Intel Genuine           | 12        | 0.28%   |
| Intel Core m3           | 12        | 0.28%   |
| Intel Xeon              | 11        | 0.26%   |
| AMD Athlon              | 10        | 0.23%   |
| AMD E1                  | 9         | 0.21%   |
| AMD E                   | 8         | 0.19%   |
| AMD Ryzen 5 PRO         | 7         | 0.16%   |
| AMD E2                  | 7         | 0.16%   |
| AMD Turion 64 X2 Mobile | 6         | 0.14%   |
| AMD FX                  | 6         | 0.14%   |
| AMD A12                 | 6         | 0.14%   |
| Intel Core M            | 4         | 0.09%   |
| Intel Celeron Dual-Core | 4         | 0.09%   |
| AMD C-60                | 4         | 0.09%   |
| Intel Pentium Silver    | 3         | 0.07%   |
| Intel Core m5           | 3         | 0.07%   |
| AMD Athlon X2           | 3         | 0.07%   |
| AMD V120                | 2         | 0.05%   |
| AMD PRO A10             | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1902      | 44.28%  |
| 4      | 1509      | 35.13%  |
| 6      | 439       | 10.22%  |
| 8      | 368       | 8.57%   |
| 14     | 25        | 0.58%   |
| 1      | 22        | 0.51%   |
| 12     | 15        | 0.35%   |
| 10     | 11        | 0.26%   |
| 16     | 2         | 0.05%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4295      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3574      | 83.17%  |
| 1      | 723       | 16.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4288      | 99.84%  |
| Unknown        | 7         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2727      | 61.94%  |
| 0x906ea    | 145       | 3.29%   |
| 0x806ea    | 99        | 2.25%   |
| 0x306a9    | 98        | 2.23%   |
| 0x806ec    | 94        | 2.13%   |
| 0x206a7    | 88        | 2%      |
| 0x406e3    | 82        | 1.86%   |
| 0x806c1    | 81        | 1.84%   |
| 0x40651    | 78        | 1.77%   |
| 0xa0652    | 68        | 1.54%   |
| 0x806e9    | 57        | 1.29%   |
| 0x306c3    | 55        | 1.25%   |
| 0x906e9    | 53        | 1.2%    |
| 0x08108102 | 43        | 0.98%   |
| 0x306d4    | 37        | 0.84%   |
| 0x0a50000c | 37        | 0.84%   |
| 0x806d1    | 34        | 0.77%   |
| 0x806eb    | 33        | 0.75%   |
| 0x506e3    | 33        | 0.75%   |
| 0x1067a    | 31        | 0.7%    |
| 0x906ed    | 27        | 0.61%   |
| 0x08600106 | 27        | 0.61%   |
| 0x08108109 | 26        | 0.59%   |
| 0x08600104 | 23        | 0.52%   |
| 0x20655    | 21        | 0.48%   |
| 0x706e5    | 19        | 0.43%   |
| 0x906a3    | 17        | 0.39%   |
| 0x08600103 | 17        | 0.39%   |
| 0x06006705 | 17        | 0.39%   |
| 0x08608103 | 15        | 0.34%   |
| 0x0810100b | 15        | 0.34%   |
| 0x706a1    | 13        | 0.3%    |
| 0x40661    | 11        | 0.25%   |
| 0x10676    | 11        | 0.25%   |
| 0xa0660    | 9         | 0.2%    |
| 0x07030105 | 9         | 0.2%    |
| 0x0a404101 | 8         | 0.18%   |
| 0x08600102 | 8         | 0.18%   |
| 0x06001119 | 8         | 0.18%   |
| 0x406c4    | 7         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1039      | 24.18%  |
| Haswell          | 386       | 8.98%   |
| IvyBridge        | 314       | 7.31%   |
| SandyBridge      | 312       | 7.26%   |
| Skylake          | 251       | 5.84%   |
| TigerLake        | 185       | 4.31%   |
| Zen+             | 175       | 4.07%   |
| Penryn           | 174       | 4.05%   |
| CometLake        | 172       | 4%      |
| Zen 2            | 164       | 3.82%   |
| Broadwell        | 150       | 3.49%   |
| Westmere         | 134       | 3.12%   |
| Unknown          | 134       | 3.12%   |
| Zen 3            | 115       | 2.68%   |
| Icelake          | 83        | 1.93%   |
| Silvermont       | 74        | 1.72%   |
| Core             | 70        | 1.63%   |
| Excavator        | 62        | 1.44%   |
| Goldmont plus    | 46        | 1.07%   |
| Zen              | 45        | 1.05%   |
| Puma             | 36        | 0.84%   |
| Piledriver       | 33        | 0.77%   |
| Bobcat           | 21        | 0.49%   |
| Goldmont         | 20        | 0.47%   |
| Alderlake Hybrid | 20        | 0.47%   |
| Nehalem          | 15        | 0.35%   |
| Steamroller      | 12        | 0.28%   |
| K10 Llano        | 12        | 0.28%   |
| Jaguar           | 12        | 0.28%   |
| K8 Hammer        | 11        | 0.26%   |
| K10              | 8         | 0.19%   |
| K8 & K10 hybrid  | 7         | 0.16%   |
| Bonnell          | 4         | 0.09%   |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3179      | 55.39%  |
| Nvidia                           | 1560      | 27.18%  |
| AMD                              | 993       | 17.3%   |
| Silicon Integrated Systems [SiS] | 6         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 302       | 5.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 288       | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 284       | 4.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 218       | 3.71%   |
| Intel UHD Graphics 620                                                                   | 176       | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 176       | 3%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 173       | 2.94%   |
| AMD Renoir                                                                               | 155       | 2.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 152       | 2.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 143       | 2.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 137       | 2.33%   |
| Intel HD Graphics 620                                                                    | 129       | 2.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 123       | 2.09%   |
| Intel HD Graphics 630                                                                    | 111       | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 111       | 1.89%   |
| Intel HD Graphics 5500                                                                   | 108       | 1.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 107       | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 102       | 1.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 79        | 1.34%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 76        | 1.29%   |
| Intel HD Graphics 530                                                                    | 65        | 1.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 64        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 61        | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 59        | 1%      |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 53        | 0.9%    |
| AMD Lucienne                                                                             | 52        | 0.89%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 51        | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 50        | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 48        | 0.82%   |
| Nvidia TU117M                                                                            | 45        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 45        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 45        | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 43        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 41        | 0.7%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 36        | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 35        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 35        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1946      | 45.02%  |
| Intel + Nvidia     | 1074      | 24.84%  |
| 1 x AMD            | 570       | 13.19%  |
| 1 x Nvidia         | 292       | 6.75%   |
| AMD + Nvidia       | 173       | 4%      |
| Intel + AMD        | 166       | 3.84%   |
| 2 x AMD            | 85        | 1.97%   |
| 2 x Nvidia         | 9         | 0.21%   |
| 1 x SiS            | 6         | 0.14%   |
| 1 x S3 Graphics    | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2962      | 68.36%  |
| Proprietary | 1246      | 28.76%  |
| Unknown     | 125       | 2.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3189      | 72.99%  |
| 1.01-2.0   | 320       | 7.32%   |
| 3.01-4.0   | 302       | 6.91%   |
| 5.01-6.0   | 175       | 4.01%   |
| 0.01-0.5   | 160       | 3.66%   |
| 7.01-8.0   | 98        | 2.24%   |
| 0.51-1.0   | 86        | 1.97%   |
| 2.01-3.0   | 29        | 0.66%   |
| 8.01-16.0  | 10        | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 909       | 18.18%  |
| Chimei Innolux          | 720       | 14.4%   |
| LG Display              | 715       | 14.3%   |
| BOE                     | 626       | 12.52%  |
| Samsung Electronics     | 470       | 9.4%    |
| Apple                   | 201       | 4.02%   |
| Sharp                   | 185       | 3.7%    |
| Goldstar                | 152       | 3.04%   |
| Dell                    | 145       | 2.9%    |
| PANDA                   | 123       | 2.46%   |
| Chi Mei Optoelectronics | 79        | 1.58%   |
| Lenovo                  | 61        | 1.22%   |
| Hewlett-Packard         | 51        | 1.02%   |
| AOC                     | 51        | 1.02%   |
| Acer                    | 51        | 1.02%   |
| BenQ                    | 41        | 0.82%   |
| Philips                 | 39        | 0.78%   |
| InfoVision              | 35        | 0.7%    |
| Ancor Communications    | 30        | 0.6%    |
| ASUSTek Computer        | 26        | 0.52%   |
| CSO                     | 24        | 0.48%   |
| ViewSonic               | 19        | 0.38%   |
| LG Philips              | 14        | 0.28%   |
| Sony                    | 13        | 0.26%   |
| Vizio                   | 11        | 0.22%   |
| TMX                     | 11        | 0.22%   |
| Panasonic               | 11        | 0.22%   |
| InnoLux Display         | 10        | 0.2%    |
| Sceptre Tech            | 8         | 0.16%   |
| Iiyama                  | 8         | 0.16%   |
| Toshiba                 | 7         | 0.14%   |
| JDI                     | 7         | 0.14%   |
| MSI                     | 6         | 0.12%   |
| Vestel Elektronik       | 5         | 0.1%    |
| LGD                     | 5         | 0.1%    |
| Insignia                | 4         | 0.08%   |
| HannStar                | 4         | 0.08%   |
| Eizo                    | 4         | 0.08%   |
| CPT                     | 4         | 0.08%   |
| Viotek                  | 3         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 55        | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 48        | 0.95%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 41        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 40        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 39        | 0.77%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 34        | 0.67%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 33        | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 33        | 0.65%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 25        | 0.49%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 24        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 24        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 24        | 0.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 24        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 23        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 22        | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 22        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 21        | 0.42%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 19        | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 18        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 18        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 17        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 17        | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 16        | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 15        | 0.3%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 15        | 0.3%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch        | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 14        | 0.28%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 14        | 0.28%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 14        | 0.28%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 14        | 0.28%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 14        | 0.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 13        | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 13        | 0.26%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 13        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2201      | 47.08%  |
| 1366x768 (WXGA)    | 1218      | 26.05%  |
| 3840x2160 (4K)     | 236       | 5.05%   |
| 1600x900 (HD+)     | 203       | 4.34%   |
| 2560x1440 (QHD)    | 142       | 3.04%   |
| 1280x800 (WXGA)    | 114       | 2.44%   |
| 1920x1200 (WUXGA)  | 90        | 1.93%   |
| 1440x900 (WXGA+)   | 88        | 1.88%   |
| 2560x1600          | 58        | 1.24%   |
| 2880x1800          | 47        | 1.01%   |
| 2560x1080          | 41        | 0.88%   |
| 3440x1440          | 29        | 0.62%   |
| 3840x2400          | 27        | 0.58%   |
| 1680x1050 (WSXGA+) | 26        | 0.56%   |
| 2160x1440          | 17        | 0.36%   |
| 1360x768           | 17        | 0.36%   |
| 3200x1800 (QHD+)   | 15        | 0.32%   |
| 1920x540           | 13        | 0.28%   |
| 2256x1504          | 12        | 0.26%   |
| 3000x2000          | 10        | 0.21%   |
| 1280x1024 (SXGA)   | 10        | 0.21%   |
| 3840x1080          | 9         | 0.19%   |
| 3456x2160          | 6         | 0.13%   |
| Unknown            | 6         | 0.13%   |
| 3200x2000          | 4         | 0.09%   |
| 3840x1100          | 3         | 0.06%   |
| 3072x1920          | 3         | 0.06%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 2560x1700          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x768 (XGA)     | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |
| 7680x2160          | 1         | 0.02%   |
| 5120x1080          | 1         | 0.02%   |
| 3280x1080          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2126      | 42.55%  |
| 13      | 769       | 15.39%  |
| 14      | 551       | 11.03%  |
| 17      | 371       | 7.43%   |
| 27      | 167       | 3.34%   |
| 24      | 146       | 2.92%   |
| 23      | 130       | 2.6%    |
| 12      | 106       | 2.12%   |
| 21      | 93        | 1.86%   |
| 31      | 74        | 1.48%   |
| 11      | 62        | 1.24%   |
| 34      | 60        | 1.2%    |
| 16      | 55        | 1.1%    |
| 18      | 46        | 0.92%   |
| Unknown | 42        | 0.84%   |
| 19      | 24        | 0.48%   |
| 32      | 19        | 0.38%   |
| 20      | 17        | 0.34%   |
| 84      | 15        | 0.3%    |
| 72      | 12        | 0.24%   |
| 22      | 12        | 0.24%   |
| 40      | 11        | 0.22%   |
| 48      | 10        | 0.2%    |
| 54      | 9         | 0.18%   |
| 25      | 7         | 0.14%   |
| 52      | 5         | 0.1%    |
| 28      | 5         | 0.1%    |
| 26      | 5         | 0.1%    |
| 10      | 5         | 0.1%    |
| 65      | 4         | 0.08%   |
| 49      | 4         | 0.08%   |
| 46      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 35      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 29      | 4         | 0.08%   |
| 47      | 3         | 0.06%   |
| 37      | 3         | 0.06%   |
| 99      | 1         | 0.02%   |
| 69      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3054      | 61.56%  |
| 201-300        | 541       | 10.91%  |
| 351-400        | 449       | 9.05%   |
| 501-600        | 403       | 8.12%   |
| 401-500        | 187       | 3.77%   |
| 601-700        | 107       | 2.16%   |
| 701-800        | 82        | 1.65%   |
| 1001-1500      | 42        | 0.85%   |
| Unknown        | 42        | 0.85%   |
| 1501-2000      | 28        | 0.56%   |
| 801-900        | 20        | 0.4%    |
| 901-1000       | 3         | 0.06%   |
| More than 2000 | 1         | 0.02%   |
| 101-200        | 1         | 0.02%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3688      | 85.15%  |
| 16/10   | 461       | 10.64%  |
| 21/9    | 71        | 1.64%   |
| 3/2     | 49        | 1.13%   |
| Unknown | 23        | 0.53%   |
| 5/4     | 12        | 0.28%   |
| 32/9    | 10        | 0.23%   |
| 4/3     | 7         | 0.16%   |
| 3.40    | 3         | 0.07%   |
| 3.73    | 2         | 0.05%   |
| 0.62    | 2         | 0.05%   |
| 6/5     | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2138      | 42.88%  |
| 81-90          | 1068      | 21.42%  |
| 121-130        | 347       | 6.96%   |
| 201-250        | 317       | 6.36%   |
| 71-80          | 250       | 5.01%   |
| 301-350        | 171       | 3.43%   |
| 351-500        | 160       | 3.21%   |
| 61-70          | 100       | 2.01%   |
| 51-60          | 65        | 1.3%    |
| 151-200        | 64        | 1.28%   |
| More than 1000 | 55        | 1.1%    |
| 251-300        | 51        | 1.02%   |
| 141-150        | 48        | 0.96%   |
| Unknown        | 42        | 0.84%   |
| 111-120        | 38        | 0.76%   |
| 501-1000       | 37        | 0.74%   |
| 131-140        | 21        | 0.42%   |
| 91-100         | 7         | 0.14%   |
| 41-50          | 5         | 0.1%    |
| 1-40           | 2         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2148      | 44%     |
| 101-120       | 1386      | 28.39%  |
| 51-100        | 682       | 13.97%  |
| 161-240       | 353       | 7.23%   |
| More than 240 | 208       | 4.26%   |
| 1-50          | 63        | 1.29%   |
| Unknown       | 42        | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3394      | 77.26%  |
| 2     | 755       | 17.19%  |
| 0     | 154       | 3.51%   |
| 3     | 84        | 1.91%   |
| 4     | 6         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2354      | 33.69%  |
| Intel                             | 2305      | 32.99%  |
| Qualcomm Atheros                  | 996       | 14.26%  |
| Broadcom                          | 480       | 6.87%   |
| Broadcom Limited                  | 136       | 1.95%   |
| MediaTek                          | 94        | 1.35%   |
| Marvell Technology Group          | 61        | 0.87%   |
| Nvidia                            | 51        | 0.73%   |
| Ralink                            | 49        | 0.7%    |
| TP-Link                           | 45        | 0.64%   |
| ASIX Electronics                  | 42        | 0.6%    |
| Ralink Technology                 | 36        | 0.52%   |
| Samsung Electronics               | 34        | 0.49%   |
| DisplayLink                       | 27        | 0.39%   |
| Dell                              | 22        | 0.31%   |
| Lenovo                            | 20        | 0.29%   |
| Ericsson Business Mobile Networks | 20        | 0.29%   |
| Sierra Wireless                   | 19        | 0.27%   |
| Qualcomm                          | 15        | 0.21%   |
| JMicron Technology                | 15        | 0.21%   |
| Xiaomi                            | 14        | 0.2%    |
| Google                            | 13        | 0.19%   |
| Hewlett-Packard                   | 12        | 0.17%   |
| NetGear                           | 11        | 0.16%   |
| ASUSTek Computer                  | 11        | 0.16%   |
| Huawei Technologies               | 10        | 0.14%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.11%   |
| D-Link                            | 8         | 0.11%   |
| Motorola PCS                      | 7         | 0.1%    |
| Apple                             | 6         | 0.09%   |
| OPPO Electronics                  | 5         | 0.07%   |
| Microsoft                         | 4         | 0.06%   |
| Linksys                           | 4         | 0.06%   |
| Qualcomm Atheros Communications   | 3         | 0.04%   |
| Fibocom                           | 3         | 0.04%   |
| Edimax Technology                 | 3         | 0.04%   |
| U-Blox                            | 2         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| LSI                               | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1529      | 18.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 390       | 4.75%   |
| Intel Wi-Fi 6 AX200                                               | 294       | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 220       | 2.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 177       | 2.16%   |
| Intel Wireless 8265 / 8275                                        | 165       | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 164       | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 157       | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 148       | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 147       | 1.79%   |
| Intel Wireless 7260                                               | 146       | 1.78%   |
| Intel Wi-Fi 6 AX201                                               | 137       | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 135       | 1.65%   |
| Intel Wireless 7265                                               | 134       | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 130       | 1.58%   |
| Intel Wireless 8260                                               | 109       | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 103       | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 102       | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 101       | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 97        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 96        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 81        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 73        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 69        | 0.84%   |
| Intel Wireless 3165                                               | 69        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 56        | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 55        | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 52        | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 52        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 51        | 0.62%   |
| Intel Wireless 3160                                               | 50        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 49        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 49        | 0.6%    |
| Intel Wireless-AC 9260                                            | 47        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 47        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 45        | 0.55%   |
| Intel Centrino Ultimate-N 6300                                    | 43        | 0.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 43        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2221      | 49.65%  |
| Qualcomm Atheros                      | 830       | 18.56%  |
| Realtek Semiconductor                 | 584       | 13.06%  |
| Broadcom                              | 407       | 9.1%    |
| Broadcom Limited                      | 107       | 2.39%   |
| MediaTek                              | 90        | 2.01%   |
| Ralink                                | 49        | 1.1%    |
| TP-Link                               | 40        | 0.89%   |
| Ralink Technology                     | 36        | 0.8%    |
| Sierra Wireless                       | 19        | 0.42%   |
| Dell                                  | 19        | 0.42%   |
| Qualcomm                              | 12        | 0.27%   |
| NetGear                               | 10        | 0.22%   |
| ASUSTek Computer                      | 9         | 0.2%    |
| D-Link                                | 8         | 0.18%   |
| Hewlett-Packard                       | 6         | 0.13%   |
| Qualcomm Atheros Communications       | 3         | 0.07%   |
| Microsoft                             | 3         | 0.07%   |
| Fibocom                               | 3         | 0.07%   |
| Edimax Technology                     | 3         | 0.07%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 294       | 6.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 220       | 4.88%   |
| Intel Wireless 8265 / 8275                                     | 165       | 3.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 157       | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 148       | 3.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 147       | 3.26%   |
| Intel Wireless 7260                                            | 146       | 3.24%   |
| Intel Wi-Fi 6 AX201                                            | 137       | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 135       | 3%      |
| Intel Wireless 7265                                            | 134       | 2.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 130       | 2.89%   |
| Intel Wireless 8260                                            | 109       | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 103       | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 102       | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 101       | 2.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 97        | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 81        | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                  | 73        | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 69        | 1.53%   |
| Intel Wireless 3165                                            | 69        | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 56        | 1.24%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 55        | 1.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 52        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 51        | 1.13%   |
| Intel Wireless 3160                                            | 50        | 1.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 49        | 1.09%   |
| Intel Wireless-AC 9260                                         | 47        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 45        | 1%      |
| Intel Centrino Ultimate-N 6300                                 | 43        | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 43        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 40        | 0.89%   |
| Intel Centrino Advanced-N 6235                                 | 39        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 38        | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 37        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 37        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 33        | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 32        | 0.71%   |
| Intel Centrino Wireless-N 2230                                 | 29        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2141      | 59.37%  |
| Intel                            | 660       | 18.3%   |
| Qualcomm Atheros                 | 262       | 7.27%   |
| Broadcom                         | 163       | 4.52%   |
| Marvell Technology Group         | 61        | 1.69%   |
| Nvidia                           | 51        | 1.41%   |
| ASIX Electronics                 | 42        | 1.16%   |
| Samsung Electronics              | 33        | 0.92%   |
| Broadcom Limited                 | 33        | 0.92%   |
| DisplayLink                      | 27        | 0.75%   |
| Lenovo                           | 20        | 0.55%   |
| JMicron Technology               | 15        | 0.42%   |
| Xiaomi                           | 14        | 0.39%   |
| Google                           | 13        | 0.36%   |
| Silicon Integrated Systems [SiS] | 8         | 0.22%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.22%   |
| Huawei Technologies              | 7         | 0.19%   |
| TP-Link                          | 5         | 0.14%   |
| OPPO Electronics                 | 5         | 0.14%   |
| Motorola PCS                     | 5         | 0.14%   |
| Apple                            | 5         | 0.14%   |
| Qualcomm                         | 3         | 0.08%   |
| MediaTek                         | 3         | 0.08%   |
| Linksys                          | 3         | 0.08%   |
| T & A Mobile Phones              | 2         | 0.06%   |
| LSI                              | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| ICS Advent                       | 2         | 0.06%   |
| ASUSTek Computer                 | 2         | 0.06%   |
| Aquantia                         | 2         | 0.06%   |
| Research In Motion               | 1         | 0.03%   |
| NTmore                           | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Cypress Semiconductor            | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1529      | 41.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 390       | 10.68%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 177       | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 164       | 4.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 52        | 1.42%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 49        | 1.34%   |
| Intel Ethernet Connection I219-LM                                 | 47        | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 38        | 1.04%   |
| Nvidia MCP79 Ethernet                                             | 37        | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 34        | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 33        | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 29        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19        | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 18        | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 18        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 17        | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 17        | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 17        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 15        | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.41%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 14        | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4251      | 54.89%  |
| Ethernet | 3443      | 44.46%  |
| Modem    | 38        | 0.49%   |
| Unknown  | 12        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3612      | 78.8%   |
| Ethernet | 972       | 21.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3154      | 73.38%  |
| 1     | 1089      | 25.34%  |
| 0     | 28        | 0.65%   |
| 3     | 27        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3480      | 80.07%  |
| Yes  | 866       | 19.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1862      | 50.93%  |
| Qualcomm Atheros Communications | 365       | 9.98%   |
| Realtek Semiconductor           | 294       | 8.04%   |
| Apple                           | 222       | 6.07%   |
| IMC Networks                    | 194       | 5.31%   |
| Lite-On Technology              | 181       | 4.95%   |
| Broadcom                        | 179       | 4.9%    |
| Foxconn / Hon Hai               | 96        | 2.63%   |
| Dell                            | 60        | 1.64%   |
| Cambridge Silicon Radio         | 37        | 1.01%   |
| Ralink                          | 27        | 0.74%   |
| Toshiba                         | 26        | 0.71%   |
| Realtek                         | 26        | 0.71%   |
| Hewlett-Packard                 | 26        | 0.71%   |
| ASUSTek Computer                | 14        | 0.38%   |
| Foxconn International           | 10        | 0.27%   |
| Ralink Technology               | 7         | 0.19%   |
| Alps Electric                   | 7         | 0.19%   |
| Askey Computer                  | 4         | 0.11%   |
| USI                             | 3         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Qcom                            | 3         | 0.08%   |
| Unknown                         | 2         | 0.05%   |
| Opticis                         | 2         | 0.05%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| MediaTek                        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 660       | 18.04%  |
| Intel AX201 Bluetooth                               | 355       | 9.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 317       | 8.67%   |
| Intel AX200 Bluetooth                               | 290       | 7.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 201       | 5.49%   |
| Realtek Bluetooth Radio                             | 184       | 5.03%   |
| Apple Bluetooth Host Controller                     | 122       | 3.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 87        | 2.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 71        | 1.94%   |
| Apple Bluetooth USB Host Controller                 | 71        | 1.94%   |
| IMC Networks Bluetooth Radio                        | 63        | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.64%   |
| IMC Networks Wireless_Device                        | 49        | 1.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 46        | 1.26%   |
| Intel AX210 Bluetooth                               | 45        | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 42        | 1.15%   |
| Lite-On Bluetooth Device                            | 41        | 1.12%   |
| IMC Networks Bluetooth Device                       | 41        | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 38        | 1.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 37        | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 36        | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 0.87%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 32        | 0.87%   |
| Intel Bluetooth Device                              | 30        | 0.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.77%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.74%   |
| Realtek Bluetooth Radio                             | 26        | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.66%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.52%   |
| Apple Bluetooth HCI                                 | 18        | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.44%   |
| Lite-On Wireless_Device                             | 15        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.38%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 14        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3426      | 61.08%  |
| Nvidia                               | 976       | 17.4%   |
| AMD                                  | 853       | 15.21%  |
| C-Media Electronics                  | 45        | 0.8%    |
| Realtek Semiconductor                | 35        | 0.62%   |
| Logitech                             | 33        | 0.59%   |
| Lenovo                               | 19        | 0.34%   |
| JMTek                                | 19        | 0.34%   |
| GN Netcom                            | 18        | 0.32%   |
| Texas Instruments                    | 13        | 0.23%   |
| Kingston Technology                  | 13        | 0.23%   |
| Apple                                | 12        | 0.21%   |
| Razer USA                            | 9         | 0.16%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.14%   |
| Hewlett-Packard                      | 8         | 0.14%   |
| Corsair                              | 8         | 0.14%   |
| SteelSeries ApS                      | 7         | 0.12%   |
| Sony                                 | 7         | 0.12%   |
| Plantronics                          | 7         | 0.12%   |
| Generalplus Technology               | 6         | 0.11%   |
| Focusrite-Novation                   | 5         | 0.09%   |
| Sennheiser Communications            | 4         | 0.07%   |
| Creative Technology                  | 4         | 0.07%   |
| Tenx Technology                      | 3         | 0.05%   |
| Samson Technologies                  | 3         | 0.05%   |
| No brand                             | 3         | 0.05%   |
| ASUSTek Computer                     | 3         | 0.05%   |
| Yamaha                               | 2         | 0.04%   |
| XMOS                                 | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |
| TerraTec Electronic                  | 2         | 0.04%   |
| Pioneer DJ                           | 2         | 0.04%   |
| GYROCOM C&C                          | 2         | 0.04%   |
| FiiO Electronics Technology          | 2         | 0.04%   |
| DSEA A/S                             | 2         | 0.04%   |
| Blue Microphones                     | 2         | 0.04%   |
| AudioQuest                           | 2         | 0.04%   |
| Astro Gaming                         | 2         | 0.04%   |
| Vestax                               | 1         | 0.02%   |
| Vault                                | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 549       | 8.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 491       | 7.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 357       | 5.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 325       | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 267       | 3.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 245       | 3.62%   |
| Intel 8 Series HD Audio Controller                                         | 219       | 3.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 217       | 3.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 194       | 2.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 185       | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 170       | 2.51%   |
| Intel Comet Lake PCH cAVS                                                  | 158       | 2.33%   |
| Intel Broadwell-U Audio Controller                                         | 150       | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 149       | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 144       | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 143       | 2.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 140       | 2.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 126       | 1.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 123       | 1.82%   |
| Intel CM238 HD Audio Controller                                            | 123       | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 117       | 1.73%   |
| AMD FCH Azalia Controller                                                  | 115       | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 108       | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 88        | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 82        | 1.21%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 67        | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                   | 66        | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                              | 64        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 63        | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 62        | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 59        | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 52        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 50        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 48        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 46        | 0.68%   |
| AMD High Definition Audio Controller                                       | 44        | 0.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 42        | 0.62%   |
| Nvidia MCP79 High Definition Audio                                         | 41        | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 40        | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 37        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 401       | 29.12%  |
| SK hynix            | 305       | 22.15%  |
| Micron Technology   | 183       | 13.29%  |
| Kingston            | 117       | 8.5%    |
| Crucial             | 78        | 5.66%   |
| Unknown             | 47        | 3.41%   |
| A-DATA Technology   | 32        | 2.32%   |
| Smart               | 26        | 1.89%   |
| Ramaxel Technology  | 23        | 1.67%   |
| Corsair             | 21        | 1.53%   |
| Elpida              | 18        | 1.31%   |
| Goldkey             | 17        | 1.23%   |
| Neo Forza           | 16        | 1.16%   |
| G.Skill             | 13        | 0.94%   |
| Unknown (ABCD)      | 9         | 0.65%   |
| Smart Brazil        | 9         | 0.65%   |
| Unknown             | 9         | 0.65%   |
| Teikon              | 6         | 0.44%   |
| Team                | 5         | 0.36%   |
| Nanya Technology    | 5         | 0.36%   |
| Apacer              | 5         | 0.36%   |
| Patriot             | 3         | 0.22%   |
| High Bridge         | 3         | 0.22%   |
| Avant               | 3         | 0.22%   |
| Timetec             | 2         | 0.15%   |
| PNY                 | 2         | 0.15%   |
| GSkill              | 2         | 0.15%   |
| GOODRAM             | 2         | 0.15%   |
| Gold Key            | 2         | 0.15%   |
| ChangXin Memory     | 2         | 0.15%   |
| Unknown (8A02)      | 1         | 0.07%   |
| Unknown (898F)      | 1         | 0.07%   |
| Silicon Power       | 1         | 0.07%   |
| RZX                 | 1         | 0.07%   |
| PUSKILL             | 1         | 0.07%   |
| Multilaser          | 1         | 0.07%   |
| Magnum Tech         | 1         | 0.07%   |
| Lenovo              | 1         | 0.07%   |
| Hewlett-Packard     | 1         | 0.07%   |
| CSX                 | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 34        | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 23        | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 1.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 1.18%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 1.18%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 1.11%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 1.04%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.97%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.69%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 0.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.62%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.62%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.62%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.62%   |
| Unknown                                                          | 9         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.55%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.55%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.55%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 7         | 0.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.48%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.48%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 7         | 0.48%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 764       | 66.61%  |
| DDR3    | 227       | 19.79%  |
| LPDDR4  | 59        | 5.14%   |
| LPDDR3  | 55        | 4.8%    |
| DDR5    | 12        | 1.05%   |
| DDR2    | 10        | 0.87%   |
| LPDDR5  | 9         | 0.78%   |
| Unknown | 7         | 0.61%   |
| SDRAM   | 4         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1005      | 86.04%  |
| Row Of Chips | 148       | 12.67%  |
| Chip         | 11        | 0.94%   |
| DIMM         | 3         | 0.26%   |
| Unknown      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 564       | 44.9%   |
| 4096  | 313       | 24.92%  |
| 16384 | 246       | 19.59%  |
| 2048  | 66        | 5.25%   |
| 32768 | 60        | 4.78%   |
| 1024  | 7         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 379       | 30.25%  |
| 3200    | 277       | 22.11%  |
| 1600    | 186       | 14.84%  |
| 2400    | 123       | 9.82%   |
| 2133    | 79        | 6.3%    |
| 4267    | 27        | 2.15%   |
| 1334    | 26        | 2.08%   |
| 3266    | 23        | 1.84%   |
| 1333    | 20        | 1.6%    |
| 8400    | 17        | 1.36%   |
| 1867    | 15        | 1.2%    |
| 4800    | 14        | 1.12%   |
| 6400    | 10        | 0.8%    |
| 4266    | 10        | 0.8%    |
| 800     | 9         | 0.72%   |
| 3733    | 7         | 0.56%   |
| 1067    | 7         | 0.56%   |
| 1866    | 5         | 0.4%    |
| 667     | 4         | 0.32%   |
| Unknown | 3         | 0.24%   |
| 4199    | 2         | 0.16%   |
| 2933    | 2         | 0.16%   |
| 2048    | 2         | 0.16%   |
| 3466    | 1         | 0.08%   |
| 3400    | 1         | 0.08%   |
| 3333    | 1         | 0.08%   |
| 3000    | 1         | 0.08%   |
| 1200    | 1         | 0.08%   |
| 1066    | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 27.27%  |
| Seiko Epson         | 5         | 22.73%  |
| Canon               | 4         | 18.18%  |
| Brother Industries  | 3         | 13.64%  |
| Xerox               | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |
| MIIIW               | 1         | 4.55%   |
| ICS Advent          | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox B215                      | 1         | 4.55%   |
| Seiko Epson WF-3520 Series      | 1         | 4.55%   |
| Seiko Epson L4150 Series        | 1         | 4.55%   |
| Seiko Epson L3110 Series        | 1         | 4.55%   |
| Seiko Epson L132 Series         | 1         | 4.55%   |
| Seiko Epson ET-3750 Series      | 1         | 4.55%   |
| Samsung M2020 Series            | 1         | 4.55%   |
| MIIIW MW Keyboard Air Mini      | 1         | 4.55%   |
| ICS Advent Parallel Adapter     | 1         | 4.55%   |
| HP Ink Tank Wireless 410 series | 1         | 4.55%   |
| HP ENVY Photo 7800 series       | 1         | 4.55%   |
| HP ENVY 4520 series             | 1         | 4.55%   |
| HP Deskjet 3050 J610 series     | 1         | 4.55%   |
| HP Deskjet 2540 series          | 1         | 4.55%   |
| HP Deskjet 2050 J510            | 1         | 4.55%   |
| Canon PIXMA MX920 Series        | 1         | 4.55%   |
| Canon GX7000 series             | 1         | 4.55%   |
| Canon G4010 series              | 1         | 4.55%   |
| Canon E400 series               | 1         | 4.55%   |
| Brother HL-L2320D series        | 1         | 4.55%   |
| Brother HL-3170CDW series       | 1         | 4.55%   |
| Brother HL-2270DW Laser Printer | 1         | 4.55%   |

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
| Chicony Electronics                    | 930       | 24.32%  |
| IMC Networks                           | 417       | 10.9%   |
| Microdia                               | 391       | 10.22%  |
| Acer                                   | 387       | 10.12%  |
| Realtek Semiconductor                  | 315       | 8.24%   |
| Sunplus Innovation Technology          | 214       | 5.6%    |
| Quanta                                 | 186       | 4.86%   |
| Apple                                  | 168       | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 137       | 3.58%   |
| Suyin                                  | 118       | 3.09%   |
| Syntek                                 | 94        | 2.46%   |
| Lite-On Technology                     | 73        | 1.91%   |
| Silicon Motion                         | 57        | 1.49%   |
| Logitech                               | 49        | 1.28%   |
| Luxvisions Innotech Limited            | 40        | 1.05%   |
| Ricoh                                  | 36        | 0.94%   |
| Alcor Micro                            | 27        | 0.71%   |
| Samsung Electronics                    | 21        | 0.55%   |
| Sonix Technology                       | 13        | 0.34%   |
| DJKANA19IDX53W                         | 11        | 0.29%   |
| ALi                                    | 11        | 0.29%   |
| SunplusIT                              | 10        | 0.26%   |
| DigiTech                               | 10        | 0.26%   |
| Primax Electronics                     | 9         | 0.24%   |
| Microsoft                              | 9         | 0.24%   |
| Importek                               | 9         | 0.24%   |
| Z-Star Microelectronics                | 8         | 0.21%   |
| Lenovo                                 | 7         | 0.18%   |
| Intel                                  | 6         | 0.16%   |
| Unknown                                | 5         | 0.13%   |
| OmniVision Technologies                | 5         | 0.13%   |
| Generalplus Technology                 | 5         | 0.13%   |
| Foxconn / Hon Hai                      | 4         | 0.1%    |
| Razer USA                              | 3         | 0.08%   |
| MacroSilicon                           | 3         | 0.08%   |
| AVerMedia Technologies                 | 3         | 0.08%   |
| USB Camera                             | 2         | 0.05%   |
| Tobii Technology AB                    | 2         | 0.05%   |
| Sunplus Technology                     | 2         | 0.05%   |
| Mustek Systems                         | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 206       | 5.36%   |
| Chicony Integrated Camera                           | 169       | 4.4%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 135       | 3.51%   |
| Chicony HD WebCam                                   | 128       | 3.33%   |
| Realtek Integrated_Webcam_HD                        | 122       | 3.17%   |
| IMC Networks Integrated Camera                      | 117       | 3.04%   |
| Chicony USB2.0 Camera                               | 90        | 2.34%   |
| Acer BisonCam,NB Pro                                | 86        | 2.24%   |
| Acer Integrated Camera                              | 71        | 1.85%   |
| Sunplus Integrated_Webcam_HD                        | 62        | 1.61%   |
| Syntek Integrated Camera                            | 58        | 1.51%   |
| Apple Built-in iSight                               | 58        | 1.51%   |
| Apple FaceTime HD Camera                            | 53        | 1.38%   |
| Acer HD Webcam                                      | 50        | 1.3%    |
| Quanta HD User Facing                               | 46        | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 44        | 1.14%   |
| Acer BisonCam, NB Pro                               | 39        | 1.01%   |
| Chicony USB 2.0 Camera                              | 37        | 0.96%   |
| Apple iPhone 5/5C/5S/6/SE                           | 35        | 0.91%   |
| Microdia Laptop_Integrated_Webcam_HD                | 32        | 0.83%   |
| Quanta HD Webcam                                    | 31        | 0.81%   |
| Chicony TOSHIBA Web Camera - HD                     | 31        | 0.81%   |
| Sunplus HD WebCam                                   | 30        | 0.78%   |
| Realtek USB Camera                                  | 30        | 0.78%   |
| Chicony Integrated Camera (1280x720@30)             | 30        | 0.78%   |
| Microdia Integrated Webcam                          | 29        | 0.75%   |
| Lite-On Integrated Camera                           | 29        | 0.75%   |
| Sunplus ASUS Webcam                                 | 27        | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                        | 27        | 0.7%    |
| Chicony HD User Facing                              | 27        | 0.7%    |
| Acer SunplusIT Integrated Camera                    | 25        | 0.65%   |
| Chicony USB2.0 VGA UVC WebCam                       | 24        | 0.62%   |
| Chicony HP HD Camera                                | 23        | 0.6%    |
| Quanta VGA WebCam                                   | 21        | 0.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.55%   |
| Chicony HP Wide Vision HD Camera                    | 21        | 0.55%   |
| Acer Lenovo EasyCamera                              | 21        | 0.55%   |
| Realtek Integrated Webcam HD                        | 20        | 0.52%   |
| Realtek Integrated Webcam                           | 20        | 0.52%   |
| Quanta HP TrueVision HD Camera                      | 20        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 222       | 30.25%  |
| Synaptics                          | 221       | 30.11%  |
| Shenzhen Goodix Technology         | 135       | 18.39%  |
| Upek                               | 41        | 5.59%   |
| Elan Microelectronics              | 40        | 5.45%   |
| LighTuning Technology              | 35        | 4.77%   |
| AuthenTec                          | 26        | 3.54%   |
| STMicroelectronics                 | 7         | 0.95%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.41%   |
| HOLTEK                             | 2         | 0.27%   |
| Samsung Electronics                | 1         | 0.14%   |
| DigitalPersona                     | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 68        | 9.26%   |
| Shenzhen Goodix  Fingerprint Device                                        | 64        | 8.72%   |
| Unknown                                                                    | 64        | 8.72%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 53        | 7.22%   |
| Shenzhen Goodix FingerPrint                                                | 43        | 5.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 41        | 5.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 5.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 4.09%   |
| Elan ELAN:Fingerprint                                                      | 30        | 4.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 28        | 3.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 2.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.45%   |
| Validity Sensors VFS491                                                    | 18        | 2.45%   |
| Synaptics WBDI Device                                                      | 18        | 2.45%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.32%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 2.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.36%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.36%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.23%   |
| Synaptics  WBDI                                                            | 8         | 1.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.09%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 0.95%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.95%   |
| AuthenTec AES2810                                                          | 7         | 0.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 0.68%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.41%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.41%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.41%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.41%   |
| AuthenTec AES1600                                                          | 3         | 0.41%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 134       | 46.85%  |
| Alcor Micro               | 78        | 27.27%  |
| Upek                      | 28        | 9.79%   |
| O2 Micro                  | 22        | 7.69%   |
| Lenovo                    | 16        | 5.59%   |
| Aladdin Knowledge Systems | 2         | 0.7%    |
| SCM Microsystems          | 1         | 0.35%   |
| OmniKey                   | 1         | 0.35%   |
| Giesecke & Devrient       | 1         | 0.35%   |
| Gemalto (was Gemplus)     | 1         | 0.35%   |
| Clay Logic                | 1         | 0.35%   |
| Advanced Card Systems     | 1         | 0.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 78        | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 15.38%  |
| Broadcom 5880                                                                | 36        | 12.59%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 12.24%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 9.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.29%   |
| Broadcom 58200                                                               | 17        | 5.94%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.59%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.4%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.7%    |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.7%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.35%   |
| OmniKey CardMan 4321                                                         | 1         | 0.35%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.35%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.35%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.35%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2746      | 62.92%  |
| 1     | 1269      | 29.08%  |
| 2     | 299       | 6.85%   |
| 3     | 44        | 1.01%   |
| 4     | 5         | 0.11%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 716       | 36.61%  |
| Chipcard                 | 278       | 14.21%  |
| Multimedia controller    | 267       | 13.65%  |
| Net/wireless             | 239       | 12.22%  |
| Graphics card            | 214       | 10.94%  |
| Bluetooth                | 63        | 3.22%   |
| Storage                  | 37        | 1.89%   |
| Camera                   | 37        | 1.89%   |
| Net/ethernet             | 26        | 1.33%   |
| Sound                    | 21        | 1.07%   |
| Communication controller | 14        | 0.72%   |
| Card reader              | 14        | 0.72%   |
| Modem                    | 9         | 0.46%   |
| Network                  | 8         | 0.41%   |
| Storage/ide              | 5         | 0.26%   |
| Storage/nvme             | 2         | 0.1%    |
| Flash memory             | 2         | 0.1%    |
| Firewire controller      | 2         | 0.1%    |
| Unclassified device      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

